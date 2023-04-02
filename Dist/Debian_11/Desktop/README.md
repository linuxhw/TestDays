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

Total: 3002

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| AZW           | MINI S                      | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| HP            | 8433 11                     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| Medion        | TJ4125                      | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| HP            | 3397                        | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| ASRock        | 970M Pro3                   | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| Medion        | TJ4125                      | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| Intel         | JSL MRD                     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| Unknown       | Unknown                     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Gigabyte      | H81M-S2V                    | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| HP            | 3397                        | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| AZW           | U59                         | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Unknown       | Unknown                     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| HP            | 1589                        | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| AZW           | MINI S                      | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Intel         | SKYBAY                      | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Medion        | TJ4125                      | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| ASRock        | A300M-STX                   | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | JSL MRD                     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| MSI           | MS-B1711                    | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Medion        | TJ4125                      | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| HP            | 21EF                        | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Dell          | 01XK1W A00                  | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| MSI           | MS-7519                     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| Pegatron      | Maureen                     | [071cde04e9](https://linux-hardware.org/?probe=071cde04e9) | Jan 03, 2023 |
| ASUSTek       | Z170-DELUXE                 | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Lenovo        | SHARKBAY NOK                | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Google        | Teemo                       | [6f6671a40e](https://linux-hardware.org/?probe=6f6671a40e) | Dec 31, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Google        | Teemo                       | [e3c39f29da](https://linux-hardware.org/?probe=e3c39f29da) | Dec 31, 2022 |
| ASRock        | J3455-ITX                   | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| HP            | 339A                        | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| HP            | ProLiant ML30 Gen9          | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| HP            | 158A                        | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| ASRock        | Brazos                      | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Dell          | 02YRK5 A02                  | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| HP            | 876C SMVB                   | [988b03aae5](https://linux-hardware.org/?probe=988b03aae5) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Intel         | DQ77CP AAG67261-300         | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| MSI           | MS-7318                     | [4622016059](https://linux-hardware.org/?probe=4622016059) | Dec 21, 2022 |
| Intel         | DG35EC AAE29266-205         | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| MSI           | A320M-A PRO MAX             | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | [493ddb6998](https://linux-hardware.org/?probe=493ddb6998) | Dec 19, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | [647bf0e2a7](https://linux-hardware.org/?probe=647bf0e2a7) | Dec 19, 2022 |
| Dell          | 0UY894 A02                  | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Dell          | 06JWJY A00                  | [89ac693c2c](https://linux-hardware.org/?probe=89ac693c2c) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Gigabyte      | X570S AERO G                | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| Dell          | 0V8F20 A01                  | [d9e3649f12](https://linux-hardware.org/?probe=d9e3649f12) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| HP            | 876C SMVB                   | [e214378eea](https://linux-hardware.org/?probe=e214378eea) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [138cbfa0ba](https://linux-hardware.org/?probe=138cbfa0ba) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| HP            | 876C SMVB                   | [c704265799](https://linux-hardware.org/?probe=c704265799) | Dec 15, 2022 |
| HP            | 876C SMVB                   | [3a6fdcc184](https://linux-hardware.org/?probe=3a6fdcc184) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [4651fa0db3](https://linux-hardware.org/?probe=4651fa0db3) | Dec 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | [47c18717db](https://linux-hardware.org/?probe=47c18717db) | Dec 14, 2022 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [32d47ba775](https://linux-hardware.org/?probe=32d47ba775) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [ee28e5efa8](https://linux-hardware.org/?probe=ee28e5efa8) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Dell          | 0H8367                      | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| MSI           | MS-7318                     | [420ae8857b](https://linux-hardware.org/?probe=420ae8857b) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| MSI           | MS-B1591                    | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| NetGear       | ReadyDATA 5200              | [2db45cfb13](https://linux-hardware.org/?probe=2db45cfb13) | Dec 13, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| HP            | 1850                        | [af4f26481a](https://linux-hardware.org/?probe=af4f26481a) | Dec 11, 2022 |
| HP            | 1850                        | [28b194e897](https://linux-hardware.org/?probe=28b194e897) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [822e79aa3e](https://linux-hardware.org/?probe=822e79aa3e) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [e3cecbe4be](https://linux-hardware.org/?probe=e3cecbe4be) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| ASRock        | X370 Killer SLI/ac          | [83fc85f9e5](https://linux-hardware.org/?probe=83fc85f9e5) | Dec 10, 2022 |
| Dell          | 0VHWTR A02                  | [b489057ccc](https://linux-hardware.org/?probe=b489057ccc) | Dec 10, 2022 |
| HP            | 876C SMVB                   | [d6211ccceb](https://linux-hardware.org/?probe=d6211ccceb) | Dec 10, 2022 |
| HP            | 339A                        | [ca1d494630](https://linux-hardware.org/?probe=ca1d494630) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0VHWTR A02                  | [5b85a90055](https://linux-hardware.org/?probe=5b85a90055) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| Unknown       | Unknown                     | [3a5aa82738](https://linux-hardware.org/?probe=3a5aa82738) | Dec 07, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Unknown       | Unknown                     | [4d8d2c3a47](https://linux-hardware.org/?probe=4d8d2c3a47) | Dec 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [7766e8d043](https://linux-hardware.org/?probe=7766e8d043) | Dec 07, 2022 |
| MSI           | B550-A PRO                  | [eb1b8bc98a](https://linux-hardware.org/?probe=eb1b8bc98a) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| MSI           | H110M PRO-VD                | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| Gigabyte      | Z97-HD3                     | [9b7999b50d](https://linux-hardware.org/?probe=9b7999b50d) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4d38cbb41a](https://linux-hardware.org/?probe=4d38cbb41a) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7428311d73](https://linux-hardware.org/?probe=7428311d73) | Dec 04, 2022 |
| Dell          | 0K3CM7 A00                  | [9ee4df50e7](https://linux-hardware.org/?probe=9ee4df50e7) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-A               | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [61e955b5a6](https://linux-hardware.org/?probe=61e955b5a6) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [dc9c0686e7](https://linux-hardware.org/?probe=dc9c0686e7) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| Intel         | DP45SG AAE27733-401         | [bc19b3f6a3](https://linux-hardware.org/?probe=bc19b3f6a3) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
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
| 5.10.0-7-amd64         | 513      | 22.01%  |
| 5.10.0-8-amd64         | 231      | 9.91%   |
| 5.10.0-9-amd64         | 120      | 5.15%   |
| 5.10.0-2-amd64         | 116      | 4.98%   |
| 5.10.0-21-amd64        | 115      | 4.93%   |
| 5.10.0-19-amd64        | 100      | 4.29%   |
| 5.10.0-13-amd64        | 86       | 3.69%   |
| 5.10.0-20-amd64        | 83       | 3.56%   |
| 5.10.0-18-amd64        | 80       | 3.43%   |
| 5.10.0-11-amd64        | 72       | 3.09%   |
| 5.10.0-10-amd64        | 72       | 3.09%   |
| 5.10.0-16-amd64        | 68       | 2.92%   |
| 5.10.0-14-amd64        | 50       | 2.15%   |
| 5.10.0-17-amd64        | 43       | 1.84%   |
| 5.10.0-15-amd64        | 41       | 1.76%   |
| 5.10.0-12-amd64        | 29       | 1.24%   |
| 5.15.0-2-amd64         | 22       | 0.94%   |
| 6.0.0-0.deb11.6-amd64  | 19       | 0.82%   |
| 5.16.0-0.bpo.4-amd64   | 18       | 0.77%   |
| 5.13.19-6-pve          | 18       | 0.77%   |
| 5.18.0-0.bpo.1-amd64   | 16       | 0.69%   |
| 5.13.19-2-pve          | 14       | 0.6%    |
| 5.18.0-0.deb11.4-amd64 | 13       | 0.56%   |
| 5.15.83-1-pve          | 13       | 0.56%   |
| 5.10.0-6-amd64         | 13       | 0.56%   |
| 5.15.74-1-pve          | 12       | 0.51%   |
| 5.15.85-1-pve          | 11       | 0.47%   |
| 5.15.30-2-pve          | 11       | 0.47%   |
| 5.15.53-1-pve          | 10       | 0.43%   |
| 5.15.35-1-pve          | 9        | 0.39%   |
| 6.0.0-0.deb11.2-amd64  | 8        | 0.34%   |
| 5.19.0-2-amd64         | 7        | 0.3%    |
| 5.19.0-0.deb11.2-amd64 | 7        | 0.3%    |
| 5.14.0-0.bpo.2-amd64   | 7        | 0.3%    |
| 5.11.22-4-pve          | 7        | 0.3%    |
| 5.15.39-4-pve          | 6        | 0.26%   |
| 5.13.19-1-pve          | 6        | 0.26%   |
| 5.15.39-1-pve          | 5        | 0.21%   |
| 5.10.0-9-686           | 5        | 0.21%   |
| 5.18.0-2-amd64         | 4        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 1781     | 80.55%  |
| 5.13.19  | 44       | 1.99%   |
| 5.18.0   | 42       | 1.9%    |
| 6.0.0    | 35       | 1.58%   |
| 5.15.0   | 35       | 1.58%   |
| 5.16.0   | 29       | 1.31%   |
| 5.19.0   | 19       | 0.86%   |
| 5.11.22  | 17       | 0.77%   |
| 5.14.0   | 16       | 0.72%   |
| 5.15.83  | 13       | 0.59%   |
| 5.15.39  | 13       | 0.59%   |
| 5.15.35  | 13       | 0.59%   |
| 5.15.74  | 12       | 0.54%   |
| 5.15.85  | 11       | 0.5%    |
| 5.15.30  | 11       | 0.5%    |
| 5.15.53  | 10       | 0.45%   |
| 5.17.0   | 9        | 0.41%   |
| 6.1.0    | 7        | 0.32%   |
| 6.0.8    | 4        | 0.18%   |
| 5.15.60  | 4        | 0.18%   |
| 5.15.102 | 4        | 0.18%   |
| 5.13.0   | 4        | 0.18%   |
| 5.19.17  | 3        | 0.14%   |
| 5.16.5   | 3        | 0.14%   |
| 4.19.0   | 3        | 0.14%   |
| 6.1.12   | 2        | 0.09%   |
| 5.4.0    | 2        | 0.09%   |
| 5.15.79  | 2        | 0.09%   |
| 5.15.64  | 2        | 0.09%   |
| 5.15.19  | 2        | 0.09%   |
| 5.15.12  | 2        | 0.09%   |
| 5.13.13  | 2        | 0.09%   |
| 5.11.0   | 2        | 0.09%   |
| 5.10.81  | 2        | 0.09%   |
| 5.10.57  | 2        | 0.09%   |
| 5.10.46  | 2        | 0.09%   |
| 5.10.109 | 2        | 0.09%   |
| 6.3.0    | 1        | 0.05%   |
| 6.2.7    | 1        | 0.05%   |
| 6.2.6    | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 1799     | 81.74%  |
| 5.15    | 128      | 5.82%   |
| 5.13    | 54       | 2.45%   |
| 5.18    | 46       | 2.09%   |
| 6.0     | 40       | 1.82%   |
| 5.16    | 34       | 1.54%   |
| 5.19    | 26       | 1.18%   |
| 5.11    | 20       | 0.91%   |
| 5.14    | 17       | 0.77%   |
| 6.1     | 12       | 0.55%   |
| 5.17    | 11       | 0.5%    |
| 6.2     | 3        | 0.14%   |
| 5.4     | 3        | 0.14%   |
| 4.19    | 3        | 0.14%   |
| 6.3     | 1        | 0.05%   |
| 5.8     | 1        | 0.05%   |
| 5.5     | 1        | 0.05%   |
| 5.12    | 1        | 0.05%   |
| 5.1     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2099     | 97.49%  |
| i686    | 50       | 2.32%   |
| riscv64 | 2        | 0.09%   |
| i586    | 1        | 0.05%   |
| armv7l  | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 941      | 43.09%  |
| GNOME             | 396      | 18.13%  |
| KDE5              | 230      | 10.53%  |
| XFCE              | 224      | 10.26%  |
| MATE              | 88       | 4.03%   |
| X-Cinnamon        | 70       | 3.21%   |
| LXDE              | 54       | 2.47%   |
| Cinnamon          | 50       | 2.29%   |
| LXQt              | 27       | 1.24%   |
| i3                | 22       | 1.01%   |
| Openbox           | 16       | 0.73%   |
| Trinity           | 12       | 0.55%   |
| KDE               | 12       | 0.55%   |
| lightdm-xsession  | 11       | 0.5%    |
| GNOME Flashback   | 9        | 0.41%   |
| Budgie            | 7        | 0.32%   |
| sway              | 3        | 0.14%   |
| awesome           | 3        | 0.14%   |
| GNOME Classic     | 2        | 0.09%   |
| UKUI              | 1        | 0.05%   |
| GNUstep           | 1        | 0.05%   |
| gnome-xorg        | 1        | 0.05%   |
| Enlightenment     | 1        | 0.05%   |
| e16-session       | 1        | 0.05%   |
| DWM               | 1        | 0.05%   |
| /etc/X11/Xsession | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 951      | 43.66%  |
| Unknown | 661      | 30.35%  |
| Tty     | 353      | 16.21%  |
| Wayland | 212      | 9.73%   |
| Web     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1193     | 54.98%  |
| LightDM | 366      | 16.87%  |
| GDM     | 289      | 13.32%  |
| SDDM    | 191      | 8.8%    |
| TDM     | 73       | 3.36%   |
| GDM3    | 39       | 1.8%    |
| SLiM    | 8        | 0.37%   |
| XDM     | 5        | 0.23%   |
| NODM    | 4        | 0.18%   |
| LXDM    | 2        | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 718      | 33.21%  |
| ru_RU   | 658      | 30.43%  |
| de_DE   | 107      | 4.95%   |
| fr_FR   | 99       | 4.58%   |
| en_GB   | 87       | 4.02%   |
| es_ES   | 59       | 2.73%   |
| pt_BR   | 47       | 2.17%   |
| it_IT   | 44       | 2.04%   |
| Unknown | 41       | 1.9%    |
| en_CA   | 29       | 1.34%   |
| C       | 28       | 1.3%    |
| en_AU   | 26       | 1.2%    |
| pl_PL   | 21       | 0.97%   |
| ja_JP   | 12       | 0.56%   |
| en_IE   | 12       | 0.56%   |
| hu_HU   | 11       | 0.51%   |
| es_VE   | 10       | 0.46%   |
| es_MX   | 10       | 0.46%   |
| es_AR   | 10       | 0.46%   |
| de_AT   | 9        | 0.42%   |
| zh_CN   | 8        | 0.37%   |
| nl_BE   | 7        | 0.32%   |
| pt_PT   | 6        | 0.28%   |
| en_NZ   | 6        | 0.28%   |
| en_IN   | 5        | 0.23%   |
| ca_ES   | 5        | 0.23%   |
| uk_UA   | 4        | 0.19%   |
| nl_NL   | 4        | 0.19%   |
| fr_BE   | 4        | 0.19%   |
| de_CH   | 4        | 0.19%   |
| cs_CZ   | 4        | 0.19%   |
| sv_SE   | 3        | 0.14%   |
| ru_UA   | 3        | 0.14%   |
| hr_HR   | 3        | 0.14%   |
| es_PE   | 3        | 0.14%   |
| es_CO   | 3        | 0.14%   |
| en_ZA   | 3        | 0.14%   |
| en_HK   | 3        | 0.14%   |
| bg_BG   | 3        | 0.14%   |
| tr_TR   | 2        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1392     | 63.68%  |
| EFI  | 794      | 36.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1336     | 61.79%  |
| Overlay | 654      | 30.25%  |
| Btrfs   | 72       | 3.33%   |
| Zfs     | 52       | 2.41%   |
| Xfs     | 28       | 1.3%    |
| Ext3    | 12       | 0.56%   |
| Unknown | 3        | 0.14%   |
| Tmpfs   | 2        | 0.09%   |
| Ext2    | 2        | 0.09%   |
| Rootfs  | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 970      | 44.43%  |
| MBR     | 918      | 42.05%  |
| Unknown | 295      | 13.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1790     | 82.49%  |
| Yes       | 380      | 17.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1195     | 55.04%  |
| Yes       | 976      | 44.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 584      | 27.14%  |
| Gigabyte Technology | 371      | 17.24%  |
| MSI                 | 226      | 10.5%   |
| ASRock              | 208      | 9.67%   |
| Dell                | 146      | 6.78%   |
| Hewlett-Packard     | 129      | 5.99%   |
| Intel               | 71       | 3.3%    |
| Lenovo              | 69       | 3.21%   |
| ECS                 | 48       | 2.23%   |
| Unknown             | 30       | 1.39%   |
| Foxconn             | 27       | 1.25%   |
| ASRockRack          | 24       | 1.12%   |
| Fujitsu             | 22       | 1.02%   |
| AZW                 | 19       | 0.88%   |
| Supermicro          | 16       | 0.74%   |
| Acer                | 14       | 0.65%   |
| Pegatron            | 13       | 0.6%    |
| Biostar             | 11       | 0.51%   |
| Inventec            | 6        | 0.28%   |
| Huanan              | 6        | 0.28%   |
| Medion              | 5        | 0.23%   |
| Google              | 5        | 0.23%   |
| BESSTAR Tech        | 5        | 0.23%   |
| Apple               | 5        | 0.23%   |
| Positivo            | 4        | 0.19%   |
| Fujitsu Siemens     | 4        | 0.19%   |
| Techvision          | 3        | 0.14%   |
| Shuttle             | 3        | 0.14%   |
| Packard Bell        | 3        | 0.14%   |
| IceWhale Technology | 3        | 0.14%   |
| HPE                 | 3        | 0.14%   |
| Aquarius            | 3        | 0.14%   |
| Thecus              | 2        | 0.09%   |
| Semp Toshiba        | 2        | 0.09%   |
| Seeed Studio        | 2        | 0.09%   |
| PC Engines          | 2        | 0.09%   |
| Maxtang             | 2        | 0.09%   |
| Hardkernel          | 2        | 0.09%   |
| Gateway             | 2        | 0.09%   |
| AAEON               | 2        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 73       | 3.39%   |
| ASUS S20 K29                      | 55       | 2.56%   |
| MSI MS-7996                       | 38       | 1.77%   |
| Unknown                           | 31       | 1.44%   |
| ECS G31T-M9                       | 22       | 1.02%   |
| MSI MS-7817                       | 20       | 0.93%   |
| ASRock H470M-HVS                  | 20       | 0.93%   |
| Gigabyte H81M-S2V                 | 18       | 0.84%   |
| ASUS PRIME H510M-A                | 17       | 0.79%   |
| Gigabyte H410M S2H                | 16       | 0.74%   |
| ECS H61H2-M13                     | 16       | 0.74%   |
| ASUS P8H61-M LX3 R2.0             | 15       | 0.7%    |
| Dell OptiPlex 7010                | 13       | 0.6%    |
| Gigabyte B450M DS3H               | 10       | 0.46%   |
| ASUS PRIME B450M-A                | 10       | 0.46%   |
| ASUS H110M-R                      | 10       | 0.46%   |
| ASUS P8H67-M                      | 9        | 0.42%   |
| Gigabyte B360M H                  | 8        | 0.37%   |
| ASUS TUF Gaming X570-PLUS         | 8        | 0.37%   |
| ASUS PRIME A320M-K                | 8        | 0.37%   |
| ASRock G31M-VS2                   | 8        | 0.37%   |
| ASRock B450M Pro4                 | 8        | 0.37%   |
| MSI MS-7C56                       | 7        | 0.33%   |
| MSI MS-7C02                       | 7        | 0.33%   |
| HP ProLiant MicroServer Gen8      | 7        | 0.33%   |
| Gigabyte A320M-S2H                | 7        | 0.33%   |
| Fujitsu ESPRIMO P720              | 7        | 0.33%   |
| Dell OptiPlex 790                 | 7        | 0.33%   |
| AZW U59                           | 7        | 0.33%   |
| AZW MINI S                        | 7        | 0.33%   |
| ASUS P8H61-M LX3 PLUS R2.0        | 7        | 0.33%   |
| ASUS P5G41T-M LE                  | 7        | 0.33%   |
| ASRock H61M-VG4                   | 7        | 0.33%   |
| Intel Pro, Std, Elt Series        | 6        | 0.28%   |
| Intel Jasper Lake Client Platform | 6        | 0.28%   |
| HP Z620 Workstation               | 6        | 0.28%   |
| HP Z420 Workstation               | 6        | 0.28%   |
| Gigabyte P85-D3                   | 6        | 0.28%   |
| Gigabyte GA-78LMT-USB3            | 6        | 0.28%   |
| Gigabyte B85M-D3H                 | 6        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 112      | 5.2%    |
| Dell OptiPlex          | 79       | 3.67%   |
| ASUS All               | 73       | 3.39%   |
| ASUS S20               | 55       | 2.56%   |
| Lenovo ThinkCentre     | 40       | 1.86%   |
| MSI MS-7996            | 38       | 1.77%   |
| ASUS ROG               | 37       | 1.72%   |
| ASUS TUF               | 36       | 1.67%   |
| HP Compaq              | 35       | 1.63%   |
| Dell Precision         | 31       | 1.44%   |
| ASUS P8H61-M           | 31       | 1.44%   |
| Unknown                | 31       | 1.44%   |
| Gigabyte B450M         | 24       | 1.12%   |
| ECS G31T-M9            | 22       | 1.02%   |
| ASUS Pro               | 21       | 0.98%   |
| MSI MS-7817            | 20       | 0.93%   |
| ASRock H470M-HVS       | 20       | 0.93%   |
| HP ProLiant            | 18       | 0.84%   |
| Gigabyte H81M-S2V      | 18       | 0.84%   |
| Gigabyte H410M         | 18       | 0.84%   |
| HP EliteDesk           | 17       | 0.79%   |
| ECS H61H2-M13          | 16       | 0.74%   |
| Fujitsu ESPRIMO        | 14       | 0.65%   |
| ASRock B450M           | 13       | 0.6%    |
| Gigabyte X570          | 12       | 0.56%   |
| ASUS P5G41T-M          | 12       | 0.56%   |
| Lenovo ThinkStation    | 11       | 0.51%   |
| ASUS P8H67-M           | 11       | 0.51%   |
| ASUS H110M-R           | 10       | 0.46%   |
| ASRock B450            | 10       | 0.46%   |
| HP ProDesk             | 9        | 0.42%   |
| Gigabyte H61M-DS2      | 9        | 0.42%   |
| Gigabyte B550          | 9        | 0.42%   |
| Gigabyte B360M         | 9        | 0.42%   |
| Gigabyte A320M-S2H     | 9        | 0.42%   |
| Dell XPS               | 9        | 0.42%   |
| Dell Vostro            | 9        | 0.42%   |
| ASUS M5A97             | 9        | 0.42%   |
| Gigabyte GA-78LMT-USB3 | 8        | 0.37%   |
| Gigabyte B450          | 8        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 242      | 11.25%  |
| 2012    | 214      | 9.94%   |
| 2018    | 190      | 8.83%   |
| 2021    | 184      | 8.55%   |
| 2013    | 182      | 8.46%   |
| 2011    | 135      | 6.27%   |
| 2019    | 125      | 5.81%   |
| 2014    | 115      | 5.34%   |
| 2009    | 114      | 5.3%    |
| 2015    | 109      | 5.07%   |
| 2017    | 98       | 4.55%   |
| 2010    | 95       | 4.41%   |
| 2016    | 87       | 4.04%   |
| 2008    | 80       | 3.72%   |
| 2022    | 73       | 3.39%   |
| 2007    | 52       | 2.42%   |
| 2006    | 22       | 1.02%   |
| 2005    | 16       | 0.74%   |
| 2023    | 5        | 0.23%   |
| 2003    | 5        | 0.23%   |
| 2001    | 3        | 0.14%   |
| Unknown | 3        | 0.14%   |
| 2004    | 2        | 0.09%   |
| 2000    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2152     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2124     | 98.47%  |
| Enabled  | 33       | 1.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2140     | 99.44%  |
| Yes  | 12       | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 421      | 19.35%  |
| 16.01-24.0      | 412      | 18.93%  |
| 3.01-4.0        | 367      | 16.87%  |
| 8.01-16.0       | 303      | 13.92%  |
| 32.01-64.0      | 264      | 12.13%  |
| 64.01-256.0     | 184      | 8.46%   |
| 1.01-2.0        | 110      | 5.06%   |
| 24.01-32.0      | 46       | 2.11%   |
| 2.01-3.0        | 39       | 1.79%   |
| 0.51-1.0        | 12       | 0.55%   |
| More than 256.0 | 10       | 0.46%   |
| 0.01-0.5        | 8        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 722      | 31.74%  |
| 1.01-2.0        | 431      | 18.95%  |
| 2.01-3.0        | 324      | 14.24%  |
| 4.01-8.0        | 284      | 12.48%  |
| 3.01-4.0        | 194      | 8.53%   |
| 8.01-16.0       | 110      | 4.84%   |
| 0.01-0.5        | 92       | 4.04%   |
| 16.01-24.0      | 53       | 2.33%   |
| 32.01-64.0      | 35       | 1.54%   |
| 24.01-32.0      | 19       | 0.84%   |
| 64.01-256.0     | 10       | 0.44%   |
| More than 256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1128     | 51.23%  |
| 2      | 435      | 19.75%  |
| 3      | 249      | 11.31%  |
| 4      | 173      | 7.86%   |
| 5      | 79       | 3.59%   |
| 6      | 45       | 2.04%   |
| 7      | 27       | 1.23%   |
| 8      | 22       | 1%      |
| 0      | 11       | 0.5%    |
| 10     | 7        | 0.32%   |
| 9      | 7        | 0.32%   |
| 13     | 5        | 0.23%   |
| 12     | 4        | 0.18%   |
| 11     | 3        | 0.14%   |
| 29     | 1        | 0.05%   |
| 28     | 1        | 0.05%   |
| 27     | 1        | 0.05%   |
| 22     | 1        | 0.05%   |
| 21     | 1        | 0.05%   |
| 18     | 1        | 0.05%   |
| 14     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1450     | 67.01%  |
| Yes       | 714      | 32.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2141     | 99.49%  |
| No        | 11       | 0.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1557     | 71.98%  |
| Yes       | 606      | 28.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1684     | 77.85%  |
| Yes       | 479      | 22.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 679      | 31.52%  |
| USA         | 314      | 14.58%  |
| Germany     | 188      | 8.73%   |
| France      | 123      | 5.71%   |
| Spain       | 80       | 3.71%   |
| UK          | 64       | 2.97%   |
| Brazil      | 63       | 2.92%   |
| Italy       | 60       | 2.79%   |
| Canada      | 52       | 2.41%   |
| Australia   | 38       | 1.76%   |
| Poland      | 37       | 1.72%   |
| Netherlands | 28       | 1.3%    |
| Austria     | 22       | 1.02%   |
| Belgium     | 21       | 0.97%   |
| Ukraine     | 20       | 0.93%   |
| Mexico      | 19       | 0.88%   |
| Hungary     | 18       | 0.84%   |
| Argentina   | 18       | 0.84%   |
| Switzerland | 17       | 0.79%   |
| Japan       | 14       | 0.65%   |
| Bulgaria    | 14       | 0.65%   |
| Portugal    | 13       | 0.6%    |
| Venezuela   | 12       | 0.56%   |
| Romania     | 12       | 0.56%   |
| Czechia     | 12       | 0.56%   |
| China       | 12       | 0.56%   |
| Sweden      | 11       | 0.51%   |
| Finland     | 11       | 0.51%   |
| Norway      | 10       | 0.46%   |
| Malaysia    | 10       | 0.46%   |
| India       | 8        | 0.37%   |
| Turkey      | 7        | 0.32%   |
| Taiwan      | 7        | 0.32%   |
| Denmark     | 7        | 0.32%   |
| Croatia     | 7        | 0.32%   |
| Belarus     | 7        | 0.32%   |
| Pakistan    | 6        | 0.28%   |
| New Zealand | 6        | 0.28%   |
| Ireland     | 6        | 0.28%   |
| Hong Kong   | 6        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Voronezh       | 571      | 25.99%  |
| Moscow         | 29       | 1.32%   |
| Vienna         | 18       | 0.82%   |
| St Petersburg  | 15       | 0.68%   |
| Seville        | 15       | 0.68%   |
| Falkenstein    | 15       | 0.68%   |
| Paris          | 13       | 0.59%   |
| Barcelona      | 12       | 0.55%   |
| Bangor         | 12       | 0.55%   |
| Sao Paulo      | 11       | 0.5%    |
| Berlin         | 11       | 0.5%    |
| Dover-Foxcroft | 10       | 0.46%   |
| Kuala Lumpur   | 9        | 0.41%   |
| Toronto        | 8        | 0.36%   |
| Munich         | 8        | 0.36%   |
| Madrid         | 8        | 0.36%   |
| London         | 8        | 0.36%   |
| Chicago        | 8        | 0.36%   |
| Warsaw         | 7        | 0.32%   |
| Sydney         | 7        | 0.32%   |
| Milan          | 7        | 0.32%   |
| Melbourne      | 7        | 0.32%   |
| Brisbane       | 7        | 0.32%   |
| Zurich         | 6        | 0.27%   |
| Stockholm      | 6        | 0.27%   |
| Sofia          | 6        | 0.27%   |
| Ocala          | 6        | 0.27%   |
| New York       | 6        | 0.27%   |
| Leipzig        | 6        | 0.27%   |
| Cologne        | 6        | 0.27%   |
| Buenos Aires   | 6        | 0.27%   |
| Amsterdam      | 6        | 0.27%   |
| Yekaterinburg  | 5        | 0.23%   |
| Windsor        | 5        | 0.23%   |
| Stuttgart      | 5        | 0.23%   |
| San José      | 5        | 0.23%   |
| Rio de Janeiro | 5        | 0.23%   |
| Orlando        | 5        | 0.23%   |
| Nuremberg      | 5        | 0.23%   |
| Lyon           | 5        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 658      | 1150   | 18.22%  |
| WDC                 | 628      | 1074   | 17.39%  |
| Samsung Electronics | 512      | 793    | 14.18%  |
| Kingston            | 278      | 353    | 7.7%    |
| Toshiba             | 265      | 485    | 7.34%   |
| Crucial             | 221      | 273    | 6.12%   |
| Hitachi             | 132      | 182    | 3.66%   |
| SanDisk             | 120      | 157    | 3.32%   |
| Intel               | 74       | 98     | 2.05%   |
| China               | 57       | 70     | 1.58%   |
| HGST                | 50       | 80     | 1.38%   |
| A-DATA Technology   | 48       | 61     | 1.33%   |
| SPCC                | 35       | 40     | 0.97%   |
| PNY                 | 30       | 55     | 0.83%   |
| Unknown             | 28       | 44     | 0.78%   |
| Netac               | 24       | 83     | 0.66%   |
| Phison              | 22       | 29     | 0.61%   |
| Corsair             | 22       | 41     | 0.61%   |
| Micron Technology   | 20       | 23     | 0.55%   |
| Maxtor              | 20       | 22     | 0.55%   |
| Transcend           | 19       | 20     | 0.53%   |
| Intenso             | 17       | 22     | 0.47%   |
| Hewlett-Packard     | 17       | 31     | 0.47%   |
| Patriot             | 16       | 19     | 0.44%   |
| OCZ                 | 16       | 20     | 0.44%   |
| SK hynix            | 15       | 27     | 0.42%   |
| Gigabyte Technology | 15       | 17     | 0.42%   |
| GOODRAM             | 13       | 28     | 0.36%   |
| Unknown             | 13       | 14     | 0.36%   |
| Apacer              | 9        | 9      | 0.25%   |
| XPG                 | 8        | 10     | 0.22%   |
| JMicron Technology  | 8        | 8      | 0.22%   |
| LITEON              | 7        | 8      | 0.19%   |
| Hajaan              | 7        | 9      | 0.19%   |
| Team                | 6        | 8      | 0.17%   |
| Silicon Motion      | 6        | 9      | 0.17%   |
| KIOXIA              | 6        | 8      | 0.17%   |
| Xinhaike            | 5        | 8      | 0.14%   |
| T-FORCE             | 5        | 7      | 0.14%   |
| Plextor             | 5        | 8      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 81       | 1.92%   |
| Kingston SA400S37240G 240GB SSD  | 67       | 1.59%   |
| Crucial CT480BX500SSD1 480GB     | 66       | 1.56%   |
| Toshiba DT01ACA050 500GB         | 58       | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB   | 46       | 1.09%   |
| Kingston SV300S37A120G 120GB SSD | 41       | 0.97%   |
| Kingston SA400S37480G 480GB SSD  | 40       | 0.95%   |
| Samsung SSD 860 EVO 250GB        | 37       | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 35       | 0.83%   |
| Toshiba DT01ACA100 1TB           | 35       | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB         | 31       | 0.73%   |
| Samsung SSD 860 EVO 1TB          | 31       | 0.73%   |
| Hitachi HDS721050CLA362 500GB    | 31       | 0.73%   |
| Toshiba HDWD110 1TB              | 30       | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB   | 28       | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 28       | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB   | 27       | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB   | 26       | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB     | 25       | 0.59%   |
| Crucial CT500MX500SSD1 500GB     | 24       | 0.57%   |
| Crucial CT240BX500SSD1 240GB     | 24       | 0.57%   |
| Crucial CT1000MX500SSD1 1TB      | 24       | 0.57%   |
| Samsung SSD 850 EVO 250GB        | 23       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB   | 22       | 0.52%   |
| Kingston SA400S37120G 120GB SSD  | 22       | 0.52%   |
| Netac SSD 240GB                  | 20       | 0.47%   |
| Seagate ST3250318AS 250GB        | 19       | 0.45%   |
| Samsung SSD 850 EVO 500GB        | 19       | 0.45%   |
| Toshiba DT01ACA200 2TB           | 18       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB   | 18       | 0.43%   |
| Samsung SSD 980 PRO 1TB          | 17       | 0.4%    |
| Samsung SSD 870 EVO 500GB        | 17       | 0.4%    |
| Seagate ST3500418AS 500GB        | 16       | 0.38%   |
| Seagate ST250DM000-1BD141 250GB  | 16       | 0.38%   |
| SanDisk NVMe SSD Drive 1TB       | 16       | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 14       | 0.33%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 14       | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB   | 14       | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB   | 14       | 0.33%   |
| Seagate ST3500413AS 500GB        | 13       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 645      | 1114   | 36.88%  |
| WDC                 | 549      | 944    | 31.39%  |
| Toshiba             | 246      | 452    | 14.07%  |
| Hitachi             | 132      | 182    | 7.55%   |
| Samsung Electronics | 61       | 78     | 3.49%   |
| HGST                | 50       | 80     | 2.86%   |
| Maxtor              | 19       | 21     | 1.09%   |
| Unknown             | 8        | 13     | 0.46%   |
| Hewlett-Packard     | 5        | 14     | 0.29%   |
| SABRENT             | 4        | 4      | 0.23%   |
| Intenso             | 3        | 3      | 0.17%   |
| Fujitsu             | 3        | 4      | 0.17%   |
| QNAP                | 2        | 3      | 0.11%   |
| HPE                 | 2        | 6      | 0.11%   |
| Apple               | 2        | 2      | 0.11%   |
| Synology            | 1        | 1      | 0.06%   |
| StoreJet            | 1        | 1      | 0.06%   |
| SD                  | 1        | 1      | 0.06%   |
| RSH-319             | 1        | 1      | 0.06%   |
| pqi                 | 1        | 1      | 0.06%   |
| NAS                 | 1        | 5      | 0.06%   |
| MaxDigital          | 1        | 4      | 0.06%   |
| MARSHAL             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| Hajaan              | 1        | 1      | 0.06%   |
| H/W                 | 1        | 3      | 0.06%   |
| China               | 1        | 1      | 0.06%   |
| ASMT                | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |
| AMP                 | 1        | 1      | 0.06%   |
| Advantech           | 1        | 1      | 0.06%   |
| 3ware               | 1        | 4      | 0.06%   |
| 128MB               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 289      | 420    | 21.23%  |
| Kingston            | 249      | 314    | 18.3%   |
| Crucial             | 203      | 247    | 14.92%  |
| SanDisk             | 81       | 102    | 5.95%   |
| WDC                 | 68       | 74     | 5%      |
| China               | 55       | 68     | 4.04%   |
| Intel               | 39       | 50     | 2.87%   |
| A-DATA Technology   | 38       | 46     | 2.79%   |
| SPCC                | 31       | 34     | 2.28%   |
| Netac               | 24       | 83     | 1.76%   |
| PNY                 | 20       | 42     | 1.47%   |
| Transcend           | 17       | 18     | 1.25%   |
| Toshiba             | 17       | 20     | 1.25%   |
| OCZ                 | 16       | 20     | 1.18%   |
| Patriot             | 13       | 14     | 0.96%   |
| Micron Technology   | 13       | 14     | 0.96%   |
| Intenso             | 12       | 15     | 0.88%   |
| GOODRAM             | 11       | 17     | 0.81%   |
| Gigabyte Technology | 9        | 9      | 0.66%   |
| Hewlett-Packard     | 8        | 11     | 0.59%   |
| Apacer              | 8        | 8      | 0.59%   |
| Hajaan              | 7        | 8      | 0.51%   |
| Corsair             | 7        | 11     | 0.51%   |
| Unknown             | 7        | 8      | 0.51%   |
| Seagate             | 6        | 7      | 0.44%   |
| LITEON              | 6        | 7      | 0.44%   |
| Xinhaike            | 5        | 8      | 0.37%   |
| Team                | 5        | 6      | 0.37%   |
| Mushkin             | 5        | 6      | 0.37%   |
| LITEONIT            | 5        | 7      | 0.37%   |
| Unknown             | 4        | 7      | 0.29%   |
| Plextor             | 4        | 7      | 0.29%   |
| NGFF                | 4        | 4      | 0.29%   |
| JMicron Technology  | 4        | 4      | 0.29%   |
| Foxline             | 4        | 4      | 0.29%   |
| T-FORCE             | 3        | 4      | 0.22%   |
| Supermicro          | 3        | 4      | 0.22%   |
| SK hynix            | 3        | 3      | 0.22%   |
| KingDian            | 3        | 3      | 0.22%   |
| TEXTORM             | 2        | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1378     | 2950   | 44.81%  |
| SSD     | 1147     | 1798   | 37.3%   |
| NVMe    | 495      | 762    | 16.1%   |
| Unknown | 39       | 74     | 1.27%   |
| MMC     | 16       | 17     | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1951     | 4542   | 75.44%  |
| NVMe | 493      | 755    | 19.06%  |
| SAS  | 126      | 287    | 4.87%   |
| MMC  | 16       | 17     | 0.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1543     | 2435   | 55.23%  |
| 0.51-1.0   | 629      | 1019   | 22.51%  |
| 1.01-2.0   | 269      | 455    | 9.63%   |
| 3.01-4.0   | 131      | 266    | 4.69%   |
| 4.01-10.0  | 119      | 298    | 4.26%   |
| 2.01-3.0   | 70       | 129    | 2.51%   |
| 10.01-20.0 | 32       | 145    | 1.15%   |
| 20.01-50.0 | 1        | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 666      | 30.29%  |
| 101-250        | 318      | 14.46%  |
| 251-500        | 266      | 12.1%   |
| 501-1000       | 252      | 11.46%  |
| More than 3000 | 215      | 9.78%   |
| 1001-2000      | 150      | 6.82%   |
| 51-100         | 102      | 4.64%   |
| 1-20           | 81       | 3.68%   |
| 2001-3000      | 78       | 3.55%   |
| 21-50          | 71       | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 666      | 29.83%  |
| 1-20           | 569      | 25.48%  |
| 101-250        | 190      | 8.51%   |
| 21-50          | 159      | 7.12%   |
| 51-100         | 155      | 6.94%   |
| 251-500        | 134      | 6%      |
| 501-1000       | 119      | 5.33%   |
| More than 3000 | 98       | 4.39%   |
| 1001-2000      | 86       | 3.85%   |
| 2001-3000      | 49       | 2.19%   |
| 0              | 8        | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 24     | 4.02%   |
| Seagate ST500DM002-1BD142 500GB  | 20       | 28     | 4.02%   |
| Kingston SV300S37A120G 120GB SSD | 16       | 16     | 3.21%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 8        | 8      | 1.61%   |
| Hitachi HDS721050CLA362 500GB    | 8        | 8      | 1.61%   |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 1.41%   |
| Toshiba DT01ACA050 500GB         | 6        | 7      | 1.2%    |
| Seagate ST3250318AS 250GB        | 6        | 6      | 1.2%    |
| Seagate ST1000DM003-9YN162 1TB   | 6        | 7      | 1.2%    |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 1%      |
| Seagate ST3500418AS 500GB        | 5        | 6      | 1%      |
| Seagate ST31500341AS 1TB         | 5        | 7      | 1%      |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.8%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 5      | 0.8%    |
| WDC WD20EARX-00PASB0 2TB         | 4        | 4      | 0.8%    |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 4      | 0.8%    |
| Seagate ST3500413AS 500GB        | 4        | 5      | 0.8%    |
| Seagate ST3320613AS 320GB        | 4        | 4      | 0.8%    |
| Seagate ST31000528AS 1TB         | 4        | 4      | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 4      | 0.8%    |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB         | 3        | 5      | 0.6%    |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 3      | 0.6%    |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 3      | 0.6%    |
| WDC WD2500AAJS-00YZCA0 250GB     | 3        | 3      | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 3      | 0.6%    |
| Toshiba MK2555GSXF 250GB         | 3        | 3      | 0.6%    |
| Toshiba DT01ACA100 1TB           | 3        | 4      | 0.6%    |
| Seagate ST3320620AS 320GB        | 3        | 5      | 0.6%    |
| Seagate ST3120827AS 120GB        | 3        | 4      | 0.6%    |
| Seagate ST3120811AS 120GB        | 3        | 3      | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 4      | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 3      | 0.6%    |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 4      | 0.6%    |
| SanDisk SSD PLUS 120 GB          | 3        | 3      | 0.6%    |
| Samsung Electronics HD103SJ 1TB  | 3        | 3      | 0.6%    |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 2      | 0.4%    |
| WDC WD3200AAKX-753CA1 320GB      | 2        | 2      | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 150      | 203    | 31.38%  |
| WDC                 | 148      | 181    | 30.96%  |
| Hitachi             | 35       | 48     | 7.32%   |
| Samsung Electronics | 31       | 33     | 6.49%   |
| Kingston            | 25       | 30     | 5.23%   |
| Toshiba             | 24       | 26     | 5.02%   |
| Intel               | 16       | 19     | 3.35%   |
| A-DATA Technology   | 8        | 11     | 1.67%   |
| Maxtor              | 7        | 7      | 1.46%   |
| Crucial             | 6        | 10     | 1.26%   |
| SanDisk             | 5        | 5      | 1.05%   |
| HGST                | 4        | 4      | 0.84%   |
| China               | 3        | 3      | 0.63%   |
| SK hynix            | 2        | 5      | 0.42%   |
| OCZ                 | 2        | 2      | 0.42%   |
| Micron Technology   | 2        | 2      | 0.42%   |
| Hewlett-Packard     | 2        | 3      | 0.42%   |
| Apacer              | 2        | 2      | 0.42%   |
| Transcend           | 1        | 1      | 0.21%   |
| SPCC                | 1        | 1      | 0.21%   |
| PNY                 | 1        | 1      | 0.21%   |
| LITEONIT            | 1        | 1      | 0.21%   |
| KingDian            | 1        | 1      | 0.21%   |
| Fujitsu             | 1        | 2      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 150      | 203    | 39.27%  |
| WDC                 | 143      | 175    | 37.43%  |
| Hitachi             | 35       | 48     | 9.16%   |
| Toshiba             | 23       | 25     | 6.02%   |
| Samsung Electronics | 17       | 17     | 4.45%   |
| Maxtor              | 7        | 7      | 1.83%   |
| HGST                | 4        | 4      | 1.05%   |
| Hewlett-Packard     | 2        | 3      | 0.52%   |
| Fujitsu             | 1        | 2      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 355      | 484    | 78.71%  |
| SSD  | 84       | 100    | 18.63%  |
| NVMe | 12       | 17     | 2.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB        | 1        | 1      | 9.09%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 2      | 9.09%   |
| Seagate ST3500830AS 500GB         | 1        | 1      | 9.09%   |
| Seagate ST3500630A 500GB          | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 9.09%   |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 9.09%   |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 9.09%   |
| HGST HUH728080ALN600 8TB          | 1        | 1      | 9.09%   |
| HGST HDN724040ALE640 4TB          | 1        | 1      | 9.09%   |
| Hewlett-Packard SSD S700 500GB    | 1        | 2      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 36.36%  |
| Samsung Electronics | 3        | 3      | 27.27%  |
| HGST                | 2        | 2      | 18.18%  |
| WDC                 | 1        | 1      | 9.09%   |
| Hewlett-Packard     | 1        | 2      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1629     | 3754   | 65.5%   |
| Malfunc  | 433      | 601    | 17.41%  |
| Detected | 413      | 1232   | 16.61%  |
| Failed   | 11       | 13     | 0.44%   |
| Limited  | 1        | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1524     | 51.52%  |
| AMD                              | 557      | 18.83%  |
| Samsung Electronics              | 211      | 7.13%   |
| ASMedia Technology               | 99       | 3.35%   |
| SanDisk                          | 79       | 2.67%   |
| Phison Electronics               | 65       | 2.2%    |
| Marvell Technology Group         | 64       | 2.16%   |
| JMicron Technology               | 60       | 2.03%   |
| Nvidia                           | 49       | 1.66%   |
| Kingston Technology Company      | 34       | 1.15%   |
| VIA Technologies                 | 27       | 0.91%   |
| LSI Logic / Symbios Logic        | 27       | 0.91%   |
| Micron/Crucial Technology        | 26       | 0.88%   |
| Broadcom / LSI                   | 21       | 0.71%   |
| Silicon Motion                   | 15       | 0.51%   |
| ADATA Technology                 | 15       | 0.51%   |
| SK hynix                         | 11       | 0.37%   |
| Toshiba America Info Systems     | 10       | 0.34%   |
| Adaptec                          | 10       | 0.34%   |
| Micron Technology                | 8        | 0.27%   |
| Silicon Image                    | 7        | 0.24%   |
| KIOXIA                           | 7        | 0.24%   |
| Seagate Technology               | 5        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.17%   |
| Realtek Semiconductor            | 4        | 0.14%   |
| INNOGRIT                         | 3        | 0.1%    |
| Hewlett-Packard                  | 3        | 0.1%    |
| Silicon Integrated Systems [SiS] | 2        | 0.07%   |
| Lite-On Technology               | 2        | 0.07%   |
| Integrated Technology Express    | 2        | 0.07%   |
| 3ware                            | 2        | 0.07%   |
| Jiangsu Huacun Elec.             | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Broadcom                         | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 321      | 8.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 187      | 5.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 134      | 3.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 133      | 3.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 125      | 3.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 124      | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 122      | 3.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 114      | 3.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 94       | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 84       | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 79       | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 74       | 2%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 71       | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 70       | 1.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 63       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 61       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 61       | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 50       | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 49       | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 48       | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 47       | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 38       | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 37       | 1%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.97%   |
| AMD FCH SATA Controller D                                                               | 35       | 0.94%   |
| Phison E12 NVMe Controller                                                              | 32       | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 31       | 0.84%   |
| Nvidia MCP61 SATA Controller                                                            | 29       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 27       | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 27       | 0.73%   |
| Samsung NVMe SSD Controller 980                                                         | 26       | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 26       | 0.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 26       | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 24       | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 24       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 22       | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20       | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 20       | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 20       | 0.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 19       | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1727     | 58.4%   |
| IDE  | 547      | 18.5%   |
| NVMe | 492      | 16.64%  |
| RAID | 124      | 4.19%   |
| SAS  | 53       | 1.79%   |
| SCSI | 14       | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1537     | 71.42%  |
| AMD                   | 608      | 28.25%  |
| CentaurHauls          | 4        | 0.19%   |
| sifive,u74-mc         | 1        | 0.05%   |
| Marvell Semiconductor | 1        | 0.05%   |
| Unknown               | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 61       | 2.83%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.62%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 30       | 1.39%   |
| AMD Ryzen 5 3600 6-Core Processor           | 30       | 1.39%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.3%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 27       | 1.25%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 1.25%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 27       | 1.25%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 24       | 1.11%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 23       | 1.07%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 22       | 1.02%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 21       | 0.97%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 0.93%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 20       | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 20       | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 20       | 0.93%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 19       | 0.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 19       | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 19       | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 18       | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 16       | 0.74%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 0.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 15       | 0.7%    |
| Intel Celeron N5105 @ 2.00GHz               | 15       | 0.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 15       | 0.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 15       | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 14       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 14       | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 13       | 0.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 13       | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 13       | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 13       | 0.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 13       | 0.6%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 13       | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 0.6%    |
| AMD FX-8350 Eight-Core Processor            | 13       | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 12       | 0.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 12       | 0.56%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 12       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 353      | 16.39%  |
| Intel Core i3           | 218      | 10.12%  |
| Intel Core i7           | 187      | 8.68%   |
| Intel Pentium           | 161      | 7.47%   |
| AMD Ryzen 5             | 136      | 6.31%   |
| Intel Xeon              | 134      | 6.22%   |
| Intel Celeron           | 118      | 5.48%   |
| AMD Ryzen 7             | 101      | 4.69%   |
| Intel Core 2 Duo        | 94       | 4.36%   |
| Other                   | 80       | 3.71%   |
| AMD Ryzen 9             | 64       | 2.97%   |
| AMD FX                  | 58       | 2.69%   |
| Intel Pentium Dual-Core | 52       | 2.41%   |
| AMD Ryzen 3             | 34       | 1.58%   |
| Intel Core 2 Quad       | 33       | 1.53%   |
| AMD Ryzen Threadripper  | 25       | 1.16%   |
| Intel Atom              | 22       | 1.02%   |
| Intel Core i9           | 21       | 0.97%   |
| AMD Athlon              | 19       | 0.88%   |
| Intel Pentium Gold      | 17       | 0.79%   |
| AMD Athlon II X2        | 17       | 0.79%   |
| AMD A10                 | 17       | 0.79%   |
| AMD Phenom II X4        | 16       | 0.74%   |
| AMD Athlon 64 X2        | 16       | 0.74%   |
| Intel Pentium 4         | 14       | 0.65%   |
| Intel Core 2            | 12       | 0.56%   |
| AMD Phenom II X6        | 10       | 0.46%   |
| AMD GX                  | 9        | 0.42%   |
| Intel Pentium Dual      | 8        | 0.37%   |
| AMD Ryzen 5 PRO         | 8        | 0.37%   |
| Intel Pentium Silver    | 7        | 0.32%   |
| Intel Pentium D         | 7        | 0.32%   |
| AMD A8                  | 7        | 0.32%   |
| AMD Sempron             | 6        | 0.28%   |
| AMD E                   | 5        | 0.23%   |
| AMD Athlon II X4        | 5        | 0.23%   |
| AMD A4                  | 5        | 0.23%   |
| Intel Genuine           | 4        | 0.19%   |
| AMD Turion II Neo       | 4        | 0.19%   |
| AMD Opteron             | 4        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 705      | 32.73%  |
| 4       | 696      | 32.31%  |
| 6       | 308      | 14.3%   |
| 8       | 198      | 9.19%   |
| 16      | 65       | 3.02%   |
| 1       | 61       | 2.83%   |
| 12      | 52       | 2.41%   |
| 3       | 24       | 1.11%   |
| 10      | 16       | 0.74%   |
| 32      | 10       | 0.46%   |
| 24      | 6        | 0.28%   |
| 18      | 3        | 0.14%   |
| 44      | 2        | 0.09%   |
| 20      | 2        | 0.09%   |
| 14      | 2        | 0.09%   |
| Unknown | 2        | 0.09%   |
| 64      | 1        | 0.05%   |
| 28      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2115     | 98.24%  |
| 2       | 36       | 1.67%   |
| Unknown | 2        | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1116     | 51.81%  |
| 1       | 1036     | 48.1%   |
| Unknown | 2        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2125     | 98.7%   |
| 32-bit         | 24       | 1.11%   |
| Unknown        | 4        | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 347      | 15.84%  |
| 0x306c3    | 198      | 9.04%   |
| 0x206a7    | 130      | 5.93%   |
| 0x1067a    | 127      | 5.8%    |
| 0x306a9    | 118      | 5.39%   |
| 0x506e3    | 98       | 4.47%   |
| 0x906ea    | 97       | 4.43%   |
| 0xa0653    | 66       | 3.01%   |
| 0x08701021 | 62       | 2.83%   |
| 0x906e9    | 46       | 2.1%    |
| 0xa0655    | 38       | 1.73%   |
| 0x0a201016 | 37       | 1.69%   |
| 0x08108109 | 35       | 1.6%    |
| 0x0800820d | 33       | 1.51%   |
| 0xa0671    | 31       | 1.41%   |
| 0x906c0    | 27       | 1.23%   |
| 0x010000c8 | 24       | 1.1%    |
| 0x6fd      | 21       | 0.96%   |
| 0x90672    | 20       | 0.91%   |
| 0x08101016 | 17       | 0.78%   |
| 0x906ed    | 16       | 0.73%   |
| 0x906eb    | 16       | 0.73%   |
| 0x6fb      | 16       | 0.73%   |
| 0x0a50000c | 16       | 0.73%   |
| 0x06003106 | 16       | 0.73%   |
| 0x206d7    | 15       | 0.68%   |
| 0x306f2    | 14       | 0.64%   |
| 0x306e4    | 14       | 0.64%   |
| 0x20655    | 14       | 0.64%   |
| 0x0a201009 | 14       | 0.64%   |
| 0x06000852 | 14       | 0.64%   |
| 0x010000b6 | 14       | 0.64%   |
| 0x10676    | 13       | 0.59%   |
| 0x06000822 | 13       | 0.59%   |
| 0x206c2    | 12       | 0.55%   |
| 0x08600106 | 12       | 0.55%   |
| 0x08001137 | 11       | 0.5%    |
| 0x90675    | 10       | 0.46%   |
| 0x706a8    | 10       | 0.46%   |
| 0x30678    | 10       | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 259      | 12.02%  |
| KabyLake         | 214      | 9.94%   |
| SandyBridge      | 164      | 7.61%   |
| Penryn           | 159      | 7.38%   |
| IvyBridge        | 149      | 6.92%   |
| Skylake          | 121      | 5.62%   |
| Zen 2            | 119      | 5.52%   |
| CometLake        | 119      | 5.52%   |
| Zen 3            | 117      | 5.43%   |
| Zen+             | 93       | 4.32%   |
| Unknown          | 68       | 3.16%   |
| K10              | 66       | 3.06%   |
| Core             | 64       | 2.97%   |
| Zen              | 55       | 2.55%   |
| Piledriver       | 53       | 2.46%   |
| Westmere         | 36       | 1.67%   |
| Silvermont       | 32       | 1.49%   |
| Tremont          | 30       | 1.39%   |
| NetBurst         | 26       | 1.21%   |
| K8 Hammer        | 25       | 1.16%   |
| Nehalem          | 24       | 1.11%   |
| Goldmont plus    | 20       | 0.93%   |
| Steamroller      | 19       | 0.88%   |
| Bulldozer        | 16       | 0.74%   |
| Bonnell          | 16       | 0.74%   |
| Alderlake Hybrid | 16       | 0.74%   |
| Goldmont         | 12       | 0.56%   |
| Broadwell        | 12       | 0.56%   |
| Jaguar           | 9        | 0.42%   |
| Excavator        | 9        | 0.42%   |
| Icelake          | 8        | 0.37%   |
| Bobcat           | 7        | 0.32%   |
| Puma             | 5        | 0.23%   |
| P6               | 4        | 0.19%   |
| K6               | 3        | 0.14%   |
| TigerLake        | 2        | 0.09%   |
| K10 Llano        | 2        | 0.09%   |
| Geode            | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 982      | 43.05%  |
| Nvidia                           | 719      | 31.52%  |
| AMD                              | 501      | 21.96%  |
| ASPEED Technology                | 50       | 2.19%   |
| Matrox Electronics Systems       | 21       | 0.92%   |
| VIA Technologies                 | 5        | 0.22%   |
| Silicon Integrated Systems [SiS] | 2        | 0.09%   |
| ATI Technologies                 | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 143      | 6.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 101      | 4.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 88       | 3.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 73       | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 68       | 2.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 61       | 2.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 57       | 2.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 54       | 2.32%   |
| ASPEED Technology ASPEED Graphics Family                                    | 50       | 2.15%   |
| Nvidia GK208B [GeForce GT 710]                                              | 44       | 1.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 43       | 1.85%   |
| Intel HD Graphics 530                                                       | 43       | 1.85%   |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 1.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 37       | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 37       | 1.59%   |
| Intel HD Graphics 630                                                       | 30       | 1.29%   |
| Intel HD Graphics 510                                                       | 30       | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 28       | 1.2%    |
| Intel JasperLake [UHD Graphics]                                             | 28       | 1.2%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 27       | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 27       | 1.16%   |
| Nvidia GF108 [GeForce GT 630]                                               | 24       | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 24       | 1.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 22       | 0.95%   |
| Nvidia GT218 [GeForce 210]                                                  | 21       | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 19       | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 18       | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 17       | 0.73%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 16       | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 16       | 0.69%   |
| AMD Renoir                                                                  | 15       | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 14       | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 13       | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13       | 0.56%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 13       | 0.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 13       | 0.56%   |
| Nvidia GF108 [GeForce GT 430]                                               | 13       | 0.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 13       | 0.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 13       | 0.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 12       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 891      | 41.06%  |
| 1 x Nvidia                        | 649      | 29.91%  |
| 1 x AMD                           | 448      | 20.65%  |
| 1 x ASPEED                        | 36       | 1.66%   |
| Intel + Nvidia                    | 33       | 1.52%   |
| 2 x AMD                           | 21       | 0.97%   |
| 1 x Matrox                        | 20       | 0.92%   |
| AMD + Nvidia                      | 16       | 0.74%   |
| Other                             | 15       | 0.69%   |
| Intel + AMD                       | 9        | 0.41%   |
| Nvidia + ASPEED                   | 7        | 0.32%   |
| 2 x Nvidia                        | 6        | 0.28%   |
| 1 x VIA                           | 5        | 0.23%   |
| AMD + ASPEED                      | 5        | 0.23%   |
| Intel + 2 x Nvidia                | 3        | 0.14%   |
| 1 x SiS                           | 2        | 0.09%   |
| 3 x AMD                           | 1        | 0.05%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.05%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.05%   |
| AMD + Matrox                      | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1093     | 50.37%  |
| Unknown     | 785      | 36.18%  |
| Proprietary | 292      | 13.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1462     | 66.94%  |
| 1.01-2.0   | 170      | 7.78%   |
| 0.01-0.5   | 128      | 5.86%   |
| 0.51-1.0   | 114      | 5.22%   |
| 3.01-4.0   | 109      | 4.99%   |
| 7.01-8.0   | 102      | 4.67%   |
| 5.01-6.0   | 47       | 2.15%   |
| 8.01-16.0  | 26       | 1.19%   |
| 2.01-3.0   | 17       | 0.78%   |
| 16.01-24.0 | 6        | 0.27%   |
| 4.01-5.0   | 2        | 0.09%   |
| 24.01-32.0 | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 220      | 15.09%  |
| Dell                    | 168      | 11.52%  |
| Goldstar                | 146      | 10.01%  |
| Acer                    | 98       | 6.72%   |
| Hewlett-Packard         | 88       | 6.04%   |
| BenQ                    | 83       | 5.69%   |
| AOC                     | 71       | 4.87%   |
| Ancor Communications    | 64       | 4.39%   |
| Philips                 | 63       | 4.32%   |
| Iiyama                  | 35       | 2.4%    |
| Unknown                 | 34       | 2.33%   |
| ASUSTek Computer        | 32       | 2.19%   |
| ViewSonic               | 29       | 1.99%   |
| Eizo                    | 24       | 1.65%   |
| Lenovo                  | 22       | 1.51%   |
| LG Electronics          | 19       | 1.3%    |
| Sony                    | 15       | 1.03%   |
| NEC Computers           | 11       | 0.75%   |
| Unknown                 | 11       | 0.75%   |
| Vestel Elektronik       | 10       | 0.69%   |
| MSI                     | 8        | 0.55%   |
| Vizio                   | 7        | 0.48%   |
| Medion                  | 7        | 0.48%   |
| Fujitsu Siemens         | 6        | 0.41%   |
| Belinea                 | 6        | 0.41%   |
| Toshiba                 | 5        | 0.34%   |
| Panasonic               | 5        | 0.34%   |
| Idek Iiyama             | 5        | 0.34%   |
| Microstep               | 4        | 0.27%   |
| Hitachi                 | 4        | 0.27%   |
| Chi Mei Optoelectronics | 4        | 0.27%   |
| Sceptre Tech            | 3        | 0.21%   |
| ONN                     | 3        | 0.21%   |
| Mi                      | 3        | 0.21%   |
| Lenovo Group Limited    | 3        | 0.21%   |
| HPN                     | 3        | 0.21%   |
| HKC                     | 3        | 0.21%   |
| Grundig                 | 3        | 0.21%   |
| Gigabyte Technology     | 3        | 0.21%   |
| DENON                   | 3        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 25       | 1.62%   |
| Unknown                                                                | 11       | 0.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 10       | 0.65%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 9        | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 8        | 0.52%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 7        | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 7        | 0.45%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 6        | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 5        | 0.32%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                      | 5        | 0.32%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 5        | 0.32%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 5        | 0.32%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 5        | 0.32%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 4        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 4        | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 4        | 0.26%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 4        | 0.26%   |
| Hewlett-Packard E201 HWP305F 1600x900 443x249mm 20.0-inch              | 4        | 0.26%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 4        | 0.26%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 4        | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 4        | 0.26%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                       | 4        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4        | 0.26%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                      | 4        | 0.26%   |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                      | 4        | 0.26%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch       | 4        | 0.26%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 4        | 0.26%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 4        | 0.26%   |
| Samsung Electronics S24F350 SAM0D22 1920x1080 521x293mm 23.5-inch      | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 3        | 0.19%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 3        | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3        | 0.19%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 3        | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 3        | 0.19%   |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                    | 3        | 0.19%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                  | 3        | 0.19%   |
| Iiyama PL2390 IVM562E 1920x1080 509x286mm 23.0-inch                    | 3        | 0.19%   |
| Grundig WUXGA GRU4448 1920x1080                                        | 3        | 0.19%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 3        | 0.19%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                 | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 605      | 42.07%  |
| 3840x2160 (4K)     | 140      | 9.74%   |
| 1280x1024 (SXGA)   | 128      | 8.9%    |
| 2560x1440 (QHD)    | 110      | 7.65%   |
| 1680x1050 (WSXGA+) | 68       | 4.73%   |
| Unknown            | 50       | 3.48%   |
| 1366x768 (WXGA)    | 42       | 2.92%   |
| 1920x1200 (WUXGA)  | 37       | 2.57%   |
| 1600x900 (HD+)     | 34       | 2.36%   |
| 1440x900 (WXGA+)   | 33       | 2.29%   |
| 2288x1287          | 27       | 1.88%   |
| 3440x1440          | 21       | 1.46%   |
| 2560x1080          | 20       | 1.39%   |
| 3840x1080          | 17       | 1.18%   |
| 1360x768           | 17       | 1.18%   |
| 1600x1200          | 16       | 1.11%   |
| 1024x768 (XGA)     | 16       | 1.11%   |
| 4480x1440          | 6        | 0.42%   |
| 1920x540           | 6        | 0.42%   |
| 5760x1080          | 4        | 0.28%   |
| 3200x1080          | 3        | 0.21%   |
| 2560x1600          | 3        | 0.21%   |
| 1400x1050          | 3        | 0.21%   |
| 5760x2160          | 2        | 0.14%   |
| 5360x1440          | 2        | 0.14%   |
| 3360x1050          | 2        | 0.14%   |
| 2048x1152          | 2        | 0.14%   |
| 1280x800 (WXGA)    | 2        | 0.14%   |
| 1280x720 (HD)      | 2        | 0.14%   |
| 7680x4320          | 1        | 0.07%   |
| 6400x2160          | 1        | 0.07%   |
| 6160x1440          | 1        | 0.07%   |
| 5120x2160          | 1        | 0.07%   |
| 5120x1440          | 1        | 0.07%   |
| 5120x1080          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 3840x2560          | 1        | 0.07%   |
| 3840x1600          | 1        | 0.07%   |
| 3840x1200          | 1        | 0.07%   |
| 3360x1080          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 205      | 14.47%  |
| 27      | 182      | 12.84%  |
| 23      | 175      | 12.35%  |
| Unknown | 132      | 9.32%   |
| 21      | 131      | 9.24%   |
| 19      | 92       | 6.49%   |
| 17      | 65       | 4.59%   |
| 31      | 59       | 4.16%   |
| 18      | 56       | 3.95%   |
| 22      | 49       | 3.46%   |
| 20      | 42       | 2.96%   |
| 15      | 33       | 2.33%   |
| 34      | 30       | 2.12%   |
| 142     | 25       | 1.76%   |
| 84      | 22       | 1.55%   |
| 32      | 13       | 0.92%   |
| 72      | 12       | 0.85%   |
| 25      | 10       | 0.71%   |
| 54      | 9        | 0.64%   |
| 28      | 8        | 0.56%   |
| 26      | 8        | 0.56%   |
| 52      | 5        | 0.35%   |
| 48      | 5        | 0.35%   |
| 40      | 5        | 0.35%   |
| 42      | 4        | 0.28%   |
| 13      | 4        | 0.28%   |
| 65      | 3        | 0.21%   |
| 43      | 3        | 0.21%   |
| 39      | 3        | 0.21%   |
| 35      | 3        | 0.21%   |
| 33      | 3        | 0.21%   |
| 29      | 3        | 0.21%   |
| 75      | 2        | 0.14%   |
| 36      | 2        | 0.14%   |
| 99      | 1        | 0.07%   |
| 74      | 1        | 0.07%   |
| 64      | 1        | 0.07%   |
| 61      | 1        | 0.07%   |
| 50      | 1        | 0.07%   |
| 49      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 515      | 37.48%  |
| 401-500        | 305      | 22.2%   |
| Unknown        | 132      | 9.61%   |
| 601-700        | 96       | 6.99%   |
| 301-350        | 94       | 6.84%   |
| 351-400        | 68       | 4.95%   |
| 701-800        | 46       | 3.35%   |
| 1501-2000      | 37       | 2.69%   |
| 1001-1500      | 27       | 1.97%   |
| More than 2000 | 26       | 1.89%   |
| 801-900        | 13       | 0.95%   |
| 901-1000       | 7        | 0.51%   |
| 201-300        | 6        | 0.44%   |
| 101-200        | 2        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 816      | 61.26%  |
| 16/10   | 149      | 11.19%  |
| 5/4     | 119      | 8.93%   |
| Unknown | 118      | 8.86%   |
| 4/3     | 41       | 3.08%   |
| 21/9    | 38       | 2.85%   |
| 1.00    | 27       | 2.03%   |
| 3/2     | 9        | 0.68%   |
| 6/5     | 7        | 0.53%   |
| 32/9    | 3        | 0.23%   |
| 2.65    | 1        | 0.08%   |
| 2.00    | 1        | 0.08%   |
| 11/10   | 1        | 0.08%   |
| 1.96    | 1        | 0.08%   |
| 0.56    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 451      | 32.63%  |
| 301-350        | 187      | 13.53%  |
| 151-200        | 175      | 12.66%  |
| Unknown        | 132      | 9.55%   |
| 351-500        | 115      | 8.32%   |
| 141-150        | 101      | 7.31%   |
| More than 1000 | 85       | 6.15%   |
| 251-300        | 69       | 4.99%   |
| 101-110        | 26       | 1.88%   |
| 501-1000       | 22       | 1.59%   |
| 111-120        | 5        | 0.36%   |
| 131-140        | 4        | 0.29%   |
| 71-80          | 3        | 0.22%   |
| 1-40           | 2        | 0.14%   |
| 121-130        | 2        | 0.14%   |
| 81-90          | 1        | 0.07%   |
| 41-50          | 1        | 0.07%   |
| 91-100         | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 812      | 61.14%  |
| 101-120       | 225      | 16.94%  |
| Unknown       | 132      | 9.94%   |
| 121-160       | 65       | 4.89%   |
| 1-50          | 63       | 4.74%   |
| 161-240       | 29       | 2.18%   |
| More than 240 | 2        | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1018     | 46.63%  |
| 0     | 893      | 40.91%  |
| 2     | 245      | 11.22%  |
| 3     | 25       | 1.15%   |
| 4     | 2        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1345     | 47.76%  |
| Intel                            | 838      | 29.76%  |
| Qualcomm Atheros                 | 157      | 5.58%   |
| Broadcom                         | 73       | 2.59%   |
| Ralink Technology                | 48       | 1.7%    |
| Nvidia                           | 43       | 1.53%   |
| Broadcom Limited                 | 25       | 0.89%   |
| TP-Link                          | 24       | 0.85%   |
| Ralink                           | 17       | 0.6%    |
| Marvell Technology Group         | 17       | 0.6%    |
| MediaTek                         | 16       | 0.57%   |
| Aquantia                         | 16       | 0.57%   |
| Mellanox Technologies            | 14       | 0.5%    |
| Samsung Electronics              | 13       | 0.46%   |
| D-Link System                    | 12       | 0.43%   |
| Qualcomm Atheros Communications  | 11       | 0.39%   |
| ASIX Electronics                 | 10       | 0.36%   |
| D-Link                           | 9        | 0.32%   |
| NetGear                          | 8        | 0.28%   |
| Microsoft                        | 8        | 0.28%   |
| American Megatrends              | 8        | 0.28%   |
| VIA Technologies                 | 7        | 0.25%   |
| Huawei Technologies              | 7        | 0.25%   |
| ASUSTek Computer                 | 7        | 0.25%   |
| Edimax Technology                | 5        | 0.18%   |
| Gemtek                           | 4        | 0.14%   |
| Dresden Elektronik               | 4        | 0.14%   |
| Belkin Components                | 4        | 0.14%   |
| 3Com                             | 4        | 0.14%   |
| ZTE WCDMA Technologies MSM       | 3        | 0.11%   |
| Xiaomi                           | 3        | 0.11%   |
| Texas Instruments                | 3        | 0.11%   |
| Sigma Designs                    | 3        | 0.11%   |
| QLogic                           | 3        | 0.11%   |
| IMC Networks                     | 3        | 0.11%   |
| DisplayLink                      | 3        | 0.11%   |
| Silicon Integrated Systems [SiS] | 2        | 0.07%   |
| Seeed Technology                 | 2        | 0.07%   |
| Qualcomm                         | 2        | 0.07%   |
| OPPO Electronics                 | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1093     | 34.94%  |
| Realtek RTL8125 2.5GbE Controller                                 | 87       | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 83       | 2.65%   |
| Intel I211 Gigabit Network Connection                             | 78       | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 75       | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73       | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 54       | 1.73%   |
| Intel Ethernet Connection (2) I219-V                              | 52       | 1.66%   |
| Intel I210 Gigabit Network Connection                             | 51       | 1.63%   |
| Intel Ethernet Connection I217-LM                                 | 38       | 1.21%   |
| Intel Ethernet Connection (14) I219-V                             | 34       | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 33       | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 30       | 0.96%   |
| Nvidia MCP61 Ethernet                                             | 28       | 0.9%    |
| Intel Wireless 3165                                               | 28       | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 26       | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 25       | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24       | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 22       | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 20       | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20       | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 20       | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 20       | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17       | 0.54%   |
| Intel Wireless-AC 9260                                            | 17       | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.51%   |
| Ralink MT7601U Wireless Adapter                                   | 16       | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16       | 0.51%   |
| Intel Ethernet Controller X550                                    | 16       | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.45%   |
| Realtek 802.11ac NIC                                              | 14       | 0.45%   |
| Intel I350 Gigabit Network Connection                             | 14       | 0.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 14       | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 13       | 0.42%   |
| Ralink RT5370 Wireless Adapter                                    | 13       | 0.42%   |
| Intel Wireless 7260                                               | 13       | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 250      | 38.64%  |
| Realtek Semiconductor           | 129      | 19.94%  |
| Qualcomm Atheros                | 68       | 10.51%  |
| Ralink Technology               | 48       | 7.42%   |
| TP-Link                         | 22       | 3.4%    |
| Broadcom                        | 19       | 2.94%   |
| Ralink                          | 17       | 2.63%   |
| MediaTek                        | 15       | 2.32%   |
| Qualcomm Atheros Communications | 11       | 1.7%    |
| D-Link                          | 9        | 1.39%   |
| NetGear                         | 8        | 1.24%   |
| Microsoft                       | 7        | 1.08%   |
| D-Link System                   | 7        | 1.08%   |
| ASUSTek Computer                | 7        | 1.08%   |
| Edimax Technology               | 5        | 0.77%   |
| Broadcom Limited                | 4        | 0.62%   |
| Belkin Components               | 4        | 0.62%   |
| IMC Networks                    | 3        | 0.46%   |
| Gemtek                          | 3        | 0.46%   |
| Linksys                         | 2        | 0.31%   |
| AVM                             | 2        | 0.31%   |
| Wilocity                        | 1        | 0.15%   |
| Tenda                           | 1        | 0.15%   |
| Sitecom Europe                  | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| Marvell Technology Group        | 1        | 0.15%   |
| CyberTAN Technology             | 1        | 0.15%   |
| BUFFALO                         | 1        | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 75       | 11.54%  |
| Intel Wireless 3165                                            | 28       | 4.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24       | 3.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 20       | 3.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 20       | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17       | 2.62%   |
| Intel Wireless-AC 9260                                         | 17       | 2.62%   |
| Ralink MT7601U Wireless Adapter                                | 16       | 2.46%   |
| Realtek 802.11ac NIC                                           | 14       | 2.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13       | 2%      |
| Ralink RT5370 Wireless Adapter                                 | 13       | 2%      |
| Intel Wireless 7260                                            | 13       | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12       | 1.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.69%   |
| Intel Wireless 7265                                            | 11       | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                | 10       | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 10       | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 10       | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8        | 1.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7        | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.92%   |
| Ralink RT5372 Wireless Adapter                                 | 6        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6        | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6        | 0.92%   |
| Intel Wireless 8260                                            | 6        | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 0.77%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 5        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5        | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 4        | 0.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 4        | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4        | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4        | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1295     | 55.46%  |
| Intel                             | 697      | 29.85%  |
| Qualcomm Atheros                  | 96       | 4.11%   |
| Broadcom                          | 57       | 2.44%   |
| Nvidia                            | 43       | 1.84%   |
| Broadcom Limited                  | 21       | 0.9%    |
| Marvell Technology Group          | 17       | 0.73%   |
| Aquantia                          | 16       | 0.69%   |
| Samsung Electronics               | 13       | 0.56%   |
| Mellanox Technologies             | 12       | 0.51%   |
| ASIX Electronics                  | 10       | 0.43%   |
| American Megatrends               | 8        | 0.34%   |
| VIA Technologies                  | 7        | 0.3%    |
| D-Link System                     | 5        | 0.21%   |
| Huawei Technologies               | 4        | 0.17%   |
| 3Com                              | 4        | 0.17%   |
| Xiaomi                            | 3        | 0.13%   |
| QLogic                            | 3        | 0.13%   |
| DisplayLink                       | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.09%   |
| TP-Link                           | 2        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 2        | 0.09%   |
| Qualcomm                          | 2        | 0.09%   |
| OPPO Electronics                  | 2        | 0.09%   |
| ICS Advent                        | 2        | 0.09%   |
| Tehuti Networks                   | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Motorola PCS                      | 1        | 0.04%   |
| Microsoft                         | 1        | 0.04%   |
| Google                            | 1        | 0.04%   |
| Gemtek                            | 1        | 0.04%   |
| ATEN International                | 1        | 0.04%   |
| ADMtek                            | 1        | 0.04%   |
| Accton Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1093     | 44.74%  |
| Realtek RTL8125 2.5GbE Controller                                 | 87       | 3.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 83       | 3.4%    |
| Intel I211 Gigabit Network Connection                             | 78       | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73       | 2.99%   |
| Intel Ethernet Controller I225-V                                  | 54       | 2.21%   |
| Intel Ethernet Connection (2) I219-V                              | 52       | 2.13%   |
| Intel I210 Gigabit Network Connection                             | 51       | 2.09%   |
| Intel Ethernet Connection I217-LM                                 | 38       | 1.56%   |
| Intel Ethernet Connection (14) I219-V                             | 34       | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 33       | 1.35%   |
| Intel 82574L Gigabit Network Connection                           | 30       | 1.23%   |
| Nvidia MCP61 Ethernet                                             | 28       | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 26       | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 25       | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 22       | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20       | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 20       | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16       | 0.65%   |
| Intel Ethernet Controller X550                                    | 16       | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.57%   |
| Intel I350 Gigabit Network Connection                             | 14       | 0.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 14       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 11       | 0.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 10       | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.37%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 9        | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 9        | 0.37%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 8        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 8        | 0.33%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2141     | 76.99%  |
| WiFi     | 606      | 21.79%  |
| Modem    | 30       | 1.08%   |
| Unknown  | 4        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1904     | 88.6%   |
| WiFi     | 245      | 11.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1459     | 67.58%  |
| 2     | 512      | 23.71%  |
| 3     | 116      | 5.37%   |
| 4     | 27       | 1.25%   |
| 5     | 17       | 0.79%   |
| 6     | 10       | 0.46%   |
| 0     | 9        | 0.42%   |
| 8     | 4        | 0.19%   |
| 7     | 2        | 0.09%   |
| 13    | 1        | 0.05%   |
| 12    | 1        | 0.05%   |
| 9     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1788     | 82.51%  |
| Yes  | 379      | 17.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 232      | 46.77%  |
| Cambridge Silicon Radio         | 114      | 22.98%  |
| Realtek Semiconductor           | 36       | 7.26%   |
| ASUSTek Computer                | 26       | 5.24%   |
| Broadcom                        | 25       | 5.04%   |
| Qualcomm Atheros Communications | 16       | 3.23%   |
| IMC Networks                    | 13       | 2.62%   |
| MediaTek                        | 10       | 2.02%   |
| Apple                           | 4        | 0.81%   |
| TP-Link                         | 3        | 0.6%    |
| Lite-On Technology              | 2        | 0.4%    |
| Foxconn / Hon Hai               | 2        | 0.4%    |
| Belkin Components               | 2        | 0.4%    |
| Toshiba                         | 1        | 0.2%    |
| Sitecom Europe                  | 1        | 0.2%    |
| SINO WEALTH                     | 1        | 0.2%    |
| Realtek                         | 1        | 0.2%    |
| Microsoft                       | 1        | 0.2%    |
| Micro Star International        | 1        | 0.2%    |
| Integrated System Solution      | 1        | 0.2%    |
| Hewlett-Packard                 | 1        | 0.2%    |
| Edimax Technology               | 1        | 0.2%    |
| Dynex                           | 1        | 0.2%    |
| Unknown                         | 1        | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 114      | 22.94%  |
| Intel AX200 Bluetooth                                     | 71       | 14.29%  |
| Intel Bluetooth wireless interface                        | 62       | 12.47%  |
| Realtek Bluetooth Radio                                   | 28       | 5.63%   |
| Intel Wireless-AC 3168 Bluetooth                          | 24       | 4.83%   |
| Intel AX201 Bluetooth                                     | 21       | 4.23%   |
| Intel AX210 Bluetooth                                     | 18       | 3.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 16       | 3.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 15       | 3.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 15       | 3.02%   |
| MediaTek Wireless_Device                                  | 10       | 2.01%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 9        | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                            | 6        | 1.21%   |
| Qualcomm Atheros  Bluetooth Device                        | 5        | 1.01%   |
| IMC Networks Bluetooth Radio                              | 5        | 1.01%   |
| ASUS ASUS USB-BT500                                       | 5        | 1.01%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 4        | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 0.8%    |
| IMC Networks Bluetooth Device                             | 4        | 0.8%    |
| ASUS Bluetooth Radio                                      | 4        | 0.8%    |
| TP-Link UB500 Adapter                                     | 3        | 0.6%    |
| Qualcomm Atheros Bluetooth USB Host Controller            | 3        | 0.6%    |
| Intel Bluetooth Device                                    | 3        | 0.6%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.4%    |
| IMC Networks Wireless_Device                              | 2        | 0.4%    |
| ASUS Bluetooth Adapter                                    | 2        | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.4%    |
| Apple Bluetooth Host Controller                           | 2        | 0.4%    |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.2%    |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.2%    |
| SINO WEALTH RK Bluetooth Keyboard                         | 1        | 0.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                   | 1        | 0.2%    |
| Realtek Bluetooth 5.1 Radio                               | 1        | 0.2%    |
| Realtek Bluetooth Radio                                   | 1        | 0.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.2%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)           | 1        | 0.2%    |
| Microsoft Wireless Transceiver for Bluetooth              | 1        | 0.2%    |
| Micro Star International Bluetooth EDR Device             | 1        | 0.2%    |
| Lite-On Bluetooth Device                                  | 1        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1411     | 45.09%  |
| AMD                                          | 680      | 21.73%  |
| Nvidia                                       | 670      | 21.41%  |
| C-Media Electronics                          | 61       | 1.95%   |
| Logitech                                     | 27       | 0.86%   |
| Creative Labs                                | 27       | 0.86%   |
| ASUSTek Computer                             | 21       | 0.67%   |
| Texas Instruments                            | 14       | 0.45%   |
| KTMicro                                      | 13       | 0.42%   |
| Generalplus Technology                       | 12       | 0.38%   |
| Focusrite-Novation                           | 12       | 0.38%   |
| VIA Technologies                             | 11       | 0.35%   |
| Micro Star International                     | 9        | 0.29%   |
| Kingston Technology                          | 9        | 0.29%   |
| Creative Technology                          | 9        | 0.29%   |
| JMTek                                        | 7        | 0.22%   |
| GN Netcom                                    | 7        | 0.22%   |
| SteelSeries ApS                              | 6        | 0.19%   |
| RODE Microphones                             | 6        | 0.19%   |
| Plantronics                                  | 6        | 0.19%   |
| GYROCOM C&C                                  | 6        | 0.19%   |
| Yamaha                                       | 5        | 0.16%   |
| Razer USA                                    | 5        | 0.16%   |
| Dell                                         | 5        | 0.16%   |
| Cambridge Silicon Radio                      | 5        | 0.16%   |
| Blue Microphones                             | 4        | 0.13%   |
| BEHRINGER International                      | 4        | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.1%    |
| TerraTec Electronic                          | 3        | 0.1%    |
| Tenx Technology                              | 3        | 0.1%    |
| Samson Technologies                          | 3        | 0.1%    |
| Giga-Byte Technology                         | 3        | 0.1%    |
| Corsair                                      | 3        | 0.1%    |
| XMOS                                         | 2        | 0.06%   |
| Unknown                                      | 2        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 2        | 0.06%   |
| Sennheiser Communications                    | 2        | 0.06%   |
| ROCCAT                                       | 2        | 0.06%   |
| Musical Fidelity                             | 2        | 0.06%   |
| Microsoft                                    | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 202      | 5.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 173      | 4.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 170      | 4.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 160      | 4.41%   |
| Intel 200 Series PCH HD Audio                                              | 135      | 3.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 125      | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 119      | 3.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 118      | 3.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 111      | 3.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 85       | 2.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 78       | 2.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 75       | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 67       | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 63       | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 61       | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60       | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 51       | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 49       | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 48       | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 46       | 1.27%   |
| AMD FCH Azalia Controller                                                  | 45       | 1.24%   |
| Nvidia High Definition Audio Controller                                    | 37       | 1.02%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 37       | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 37       | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 34       | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 33       | 0.91%   |
| Intel Alder Lake-S HD Audio Controller                                     | 33       | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                              | 32       | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 31       | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                | 30       | 0.83%   |
| AMD Navi 10 HDMI Audio                                                     | 30       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 29       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                              | 28       | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 28       | 0.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 28       | 0.77%   |
| Nvidia MCP61 High Definition Audio                                         | 27       | 0.74%   |
| Intel Jasper Lake HD Audio                                                 | 27       | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27       | 0.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 26       | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 359      | 16.91%  |
| Unknown                      | 327      | 15.4%   |
| Crucial                      | 280      | 13.19%  |
| Samsung Electronics          | 222      | 10.46%  |
| SK hynix                     | 188      | 8.86%   |
| Corsair                      | 166      | 7.82%   |
| G.Skill                      | 118      | 5.56%   |
| Micron Technology            | 92       | 4.33%   |
| Patriot                      | 61       | 2.87%   |
| A-DATA Technology            | 32       | 1.51%   |
| Unknown                      | 27       | 1.27%   |
| Hikvision                    | 21       | 0.99%   |
| Team                         | 20       | 0.94%   |
| Ramaxel Technology           | 19       | 0.89%   |
| AMD                          | 18       | 0.85%   |
| Unknown (ABCD)               | 14       | 0.66%   |
| Nanya Technology             | 14       | 0.66%   |
| Elpida                       | 13       | 0.61%   |
| Smart                        | 7        | 0.33%   |
| GOODRAM                      | 7        | 0.33%   |
| Transcend                    | 6        | 0.28%   |
| Hewlett-Packard              | 6        | 0.28%   |
| GeIL                         | 6        | 0.28%   |
| Apacer                       | 6        | 0.28%   |
| Timetec                      | 5        | 0.24%   |
| Qimonda                      | 5        | 0.24%   |
| Unknown (0x5846)             | 3        | 0.14%   |
| Toshiba                      | 3        | 0.14%   |
| Kingmax                      | 3        | 0.14%   |
| Goldkey                      | 3        | 0.14%   |
| Wilk                         | 2        | 0.09%   |
| V-Color                      | 2        | 0.09%   |
| Unknown (0x0DD5)             | 2        | 0.09%   |
| Unknown (0x0B45)             | 2        | 0.09%   |
| Unifosa                      | 2        | 0.09%   |
| Silicon Power                | 2        | 0.09%   |
| PNY                          | 2        | 0.09%   |
| Patriot Memory (PDP Systems) | 2        | 0.09%   |
| Kllisre                      | 2        | 0.09%   |
| KLEVV                        | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                            | 43       | 1.84%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 35       | 1.5%    |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s        | 31       | 1.33%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s       | 29       | 1.24%   |
| Unknown                                                      | 27       | 1.16%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 24       | 1.03%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s         | 24       | 1.03%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s      | 20       | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 20       | 0.86%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 19       | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 18       | 0.77%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s        | 18       | 0.77%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 16       | 0.68%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 16       | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 15       | 0.64%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 15       | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 14       | 0.6%    |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s               | 14       | 0.6%    |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s         | 12       | 0.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 11       | 0.47%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                         | 10       | 0.43%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 10       | 0.43%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s      | 10       | 0.43%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 9        | 0.39%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s        | 9        | 0.39%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 9        | 0.39%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 9        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 8        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 8        | 0.34%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 8        | 0.34%   |
| Patriot RAM PSD32G133381 2GB DIMM DDR3 1333MT/s              | 8        | 0.34%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 8        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 8        | 0.34%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s       | 8        | 0.34%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                  | 8        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 7        | 0.3%    |
| Unknown RAM Module 2GB DIMM                                  | 7        | 0.3%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 7        | 0.3%    |
| Unknown RAM Module 1GB DIMM                                  | 7        | 0.3%    |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s         | 7        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 847      | 44.79%  |
| DDR3         | 642      | 33.95%  |
| Unknown      | 136      | 7.19%   |
| SDRAM        | 118      | 6.24%   |
| DDR2         | 89       | 4.71%   |
| DDR          | 22       | 1.16%   |
| LPDDR4       | 21       | 1.11%   |
| DDR5         | 12       | 0.63%   |
| DRAM         | 3        | 0.16%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1711     | 91.74%  |
| SODIMM       | 137      | 7.35%   |
| Row Of Chips | 7        | 0.38%   |
| FB-DIMM      | 4        | 0.21%   |
| RIMM         | 3        | 0.16%   |
| Unknown      | 2        | 0.11%   |
| Chip         | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 642      | 31.29%  |
| 4096    | 479      | 23.34%  |
| 2048    | 347      | 16.91%  |
| 16384   | 293      | 14.28%  |
| 32768   | 137      | 6.68%   |
| 1024    | 115      | 5.6%    |
| 512     | 26       | 1.27%   |
| 256     | 6        | 0.29%   |
| 65536   | 4        | 0.19%   |
| 1536    | 1        | 0.05%   |
| 128     | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 367      | 17.9%   |
| 1333    | 242      | 11.8%   |
| 2667    | 166      | 8.1%    |
| 3200    | 165      | 8.05%   |
| 2400    | 124      | 6.05%   |
| 2133    | 101      | 4.93%   |
| 800     | 99       | 4.83%   |
| 3600    | 88       | 4.29%   |
| Unknown | 85       | 4.15%   |
| 2666    | 63       | 3.07%   |
| 1866    | 62       | 3.02%   |
| 667     | 50       | 2.44%   |
| 3400    | 36       | 1.76%   |
| 3000    | 28       | 1.37%   |
| 1066    | 27       | 1.32%   |
| 2933    | 26       | 1.27%   |
| 2866    | 26       | 1.27%   |
| 1867    | 24       | 1.17%   |
| 3466    | 23       | 1.12%   |
| 1067    | 22       | 1.07%   |
| 3733    | 20       | 0.98%   |
| 1800    | 17       | 0.83%   |
| 3266    | 15       | 0.73%   |
| 3800    | 12       | 0.59%   |
| 400     | 11       | 0.54%   |
| 4800    | 10       | 0.49%   |
| 3866    | 10       | 0.49%   |
| 3534    | 9        | 0.44%   |
| 1334    | 9        | 0.44%   |
| 533     | 9        | 0.44%   |
| 2048    | 8        | 0.39%   |
| 4333    | 7        | 0.34%   |
| 1648    | 7        | 0.34%   |
| 3100    | 6        | 0.29%   |
| 3066    | 6        | 0.29%   |
| 2800    | 6        | 0.29%   |
| 3666    | 5        | 0.24%   |
| 3500    | 5        | 0.24%   |
| 333     | 4        | 0.2%    |
| 266     | 4        | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 31       | 35.23%  |
| Brother Industries    | 18       | 20.45%  |
| Canon                 | 9        | 10.23%  |
| Samsung Electronics   | 7        | 7.95%   |
| Xerox                 | 3        | 3.41%   |
| Seiko Epson           | 3        | 3.41%   |
| Dymo-CoStar           | 3        | 3.41%   |
| Zebra                 | 2        | 2.27%   |
| Prolific Technology   | 2        | 2.27%   |
| Pantum                | 2        | 2.27%   |
| STMicroelectronics    | 1        | 1.14%   |
| QinHeng Electronics   | 1        | 1.14%   |
| Printer               | 1        | 1.14%   |
| Lexmark International | 1        | 1.14%   |
| Kyocera               | 1        | 1.14%   |
| Konica Minolta        | 1        | 1.14%   |
| GODEX INTERNATIONAL   | 1        | 1.14%   |
| Apple                 | 1        | 1.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Xerox B205                                                | 3        | 3.41%   |
| Samsung ML-1660 Series                                    | 3        | 3.41%   |
| HP LaserJet M101-M106                                     | 3        | 3.41%   |
| HP LaserJet 1200                                          | 3        | 3.41%   |
| HP LaserJet 1020                                          | 3        | 3.41%   |
| Prolific PL2305 Parallel Port                             | 2        | 2.27%   |
| HP LaserJet P1005                                         | 2        | 2.27%   |
| HP ENVY 4520 series                                       | 2        | 2.27%   |
| Canon MF4410                                              | 2        | 2.27%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 1.14%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 1.14%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.14%   |
| Seiko Epson XP-200 Series                                 | 1        | 1.14%   |
| Seiko Epson ET-2710 Series                                | 1        | 1.14%   |
| Seiko Epson ET-2700 Series                                | 1        | 1.14%   |
| Samsung SCX-4x26 Series                                   | 1        | 1.14%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 1.14%   |
| Samsung SCX-3200 Series                                   | 1        | 1.14%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 1.14%   |
| QinHeng CH340S                                            | 1        | 1.14%   |
| Printer Printer                                           | 1        | 1.14%   |
| Pantum P2500W series                                      | 1        | 1.14%   |
| Pantum M6500-series                                       | 1        | 1.14%   |
| Lexmark International MS710                               | 1        | 1.14%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 1.14%   |
| Konica Minolta bizhub 4402P                               | 1        | 1.14%   |
| HP Officejet J4500 series                                 | 1        | 1.14%   |
| HP Officejet 7110 series                                  | 1        | 1.14%   |
| HP LaserJet Pro M404-M405                                 | 1        | 1.14%   |
| HP LaserJet Pro M148-M149                                 | 1        | 1.14%   |
| HP LaserJet P2055 series                                  | 1        | 1.14%   |
| HP Laserjet P1505                                         | 1        | 1.14%   |
| HP LaserJet P1006                                         | 1        | 1.14%   |
| HP LaserJet M14-M17                                       | 1        | 1.14%   |
| HP LaserJet 400 M401a                                     | 1        | 1.14%   |
| HP LaserJet 1320                                          | 1        | 1.14%   |
| HP LaserJet 1300                                          | 1        | 1.14%   |
| HP LaserJet 1150                                          | 1        | 1.14%   |
| HP LaserJet 1015                                          | 1        | 1.14%   |
| HP ENVY Photo 6200 series                                 | 1        | 1.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 52.63%  |
| Seiko Epson     | 4        | 21.05%  |
| Hewlett-Packard | 3        | 15.79%  |
| AGFA-Gevaert NV | 2        | 10.53%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                                       | 3        | 15.79%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2        | 10.53%  |
| Canon CanoScan LiDE 110                                       | 2        | 10.53%  |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 10.53%  |
| Seiko Epson GT-X770 [Perfection V500]                         | 1        | 5.26%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 5.26%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 5.26%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 5.26%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 5.26%   |
| HP ScanJet 3970c                                              | 1        | 5.26%   |
| HP Scanjet 300                                                | 1        | 5.26%   |
| Canon CanoScan LiDE 210                                       | 1        | 5.26%   |
| Canon CanoScan 8800F                                          | 1        | 5.26%   |
| Canon CanoScan 5600F                                          | 1        | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 122      | 42.81%  |
| Microdia                      | 21       | 7.37%   |
| Generalplus Technology        | 14       | 4.91%   |
| Sunplus Innovation Technology | 12       | 4.21%   |
| Microsoft                     | 10       | 3.51%   |
| Creative Technology           | 9        | 3.16%   |
| Samsung Electronics           | 8        | 2.81%   |
| Apple                         | 8        | 2.81%   |
| KYE Systems (Mouse Systems)   | 6        | 2.11%   |
| Jieli Technology              | 6        | 2.11%   |
| ARC International             | 5        | 1.75%   |
| Z-Star Microelectronics       | 4        | 1.4%    |
| Chicony Electronics           | 4        | 1.4%    |
| Novatek Microelectronics      | 3        | 1.05%   |
| Genesys Logic                 | 3        | 1.05%   |
| GEMBIRD                       | 3        | 1.05%   |
| Xiongmai                      | 2        | 0.7%    |
| webcam                        | 2        | 0.7%    |
| Realtek Semiconductor         | 2        | 0.7%    |
| Razer USA                     | 2        | 0.7%    |
| Nintendo                      | 2        | 0.7%    |
| MacroSilicon                  | 2        | 0.7%    |
| Google                        | 2        | 0.7%    |
| Cubeternet                    | 2        | 0.7%    |
| AVerMedia Technologies        | 2        | 0.7%    |
| Arkmicro Technologies         | 2        | 0.7%    |
| Xiaomi                        | 1        | 0.35%   |
| WaveRider Communications      | 1        | 0.35%   |
| Valve Software                | 1        | 0.35%   |
| ValueHD                       | 1        | 0.35%   |
| Unknown                       | 1        | 0.35%   |
| Trust                         | 1        | 0.35%   |
| Syntek                        | 1        | 0.35%   |
| SunplusIT                     | 1        | 0.35%   |
| Sunplus IT                    | 1        | 0.35%   |
| Silicon Motion                | 1        | 0.35%   |
| SiGma Micro                   | 1        | 0.35%   |
| Ruision                       | 1        | 0.35%   |
| Mimaki Engineering            | 1        | 0.35%   |
| Lite-On Technology            | 1        | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 41       | 14.29%  |
| Logitech HD Pro Webcam C920                       | 12       | 4.18%   |
| Logitech C922 Pro Stream Webcam                   | 12       | 4.18%   |
| Generalplus GENERAL WEBCAM                        | 11       | 3.83%   |
| Microdia USB 2.0 Camera                           | 9        | 3.14%   |
| Samsung Galaxy A5 (MTP)                           | 8        | 2.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 8        | 2.79%   |
| Microdia Webcam Vitade AF                         | 7        | 2.44%   |
| Microsoft LifeCam HD-3000                         | 6        | 2.09%   |
| Logitech Webcam C170                              | 6        | 2.09%   |
| Logitech HD Webcam C615                           | 6        | 2.09%   |
| Jieli USB PHY 2.0                                 | 6        | 2.09%   |
| Logitech Webcam C310                              | 5        | 1.74%   |
| Logitech HD Webcam C525                           | 5        | 1.74%   |
| Logitech C920 PRO HD Webcam                       | 5        | 1.74%   |
| Creative Live! Cam Chat HD [VF0700]               | 4        | 1.39%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 1.05%   |
| Novatek HP High Definition 2MP Webcam             | 3        | 1.05%   |
| Logitech Webcam C925e                             | 3        | 1.05%   |
| Logitech Logi Webcam C920e                        | 3        | 1.05%   |
| Logitech HD Webcam C910                           | 3        | 1.05%   |
| Logitech BRIO Ultra HD Webcam                     | 3        | 1.05%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam   | 3        | 1.05%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 3        | 1.05%   |
| ARC International Camera                          | 3        | 1.05%   |
| Xiongmai web camera                               | 2        | 0.7%    |
| webcam webcam                                     | 2        | 0.7%    |
| Sunplus WEMISS CM-A1                              | 2        | 0.7%    |
| Sunplus HD 720P webcam                            | 2        | 0.7%    |
| Sunplus Full HD webcam                            | 2        | 0.7%    |
| Razer USA Gaming Webcam [Kiyo]                    | 2        | 0.7%    |
| Nintendo USB Camera                               | 2        | 0.7%    |
| Microdia Sonix USB 2.0 Camera                     | 2        | 0.7%    |
| Logitech StreamCam                                | 2        | 0.7%    |
| Logitech QuickCam Pro 9000                        | 2        | 0.7%    |
| Logitech QuickCam Pro 4000                        | 2        | 0.7%    |
| Logitech QuickCam Communicate MP/S5500            | 2        | 0.7%    |
| KYE Systems (Mouse Systems) PC-W3 Camera          | 2        | 0.7%    |
| Genesys Logic USB2.0 Digital Camera               | 2        | 0.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 0.7%    |

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
| SCM Microsystems      | 3        | 21.43%  |
| Gemalto (was Gemplus) | 2        | 14.29%  |
| Alcor Micro           | 2        | 14.29%  |
| Yubico.com            | 1        | 7.14%   |
| Lenovo                | 1        | 7.14%   |
| Feitian Technologies  | 1        | 7.14%   |
| Clay Logic            | 1        | 7.14%   |
| Chicony Electronics   | 1        | 7.14%   |
| Cherry                | 1        | 7.14%   |
| Advanced Card Systems | 1        | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 14.29%  |
| Yubico.com Yubikey 4/5 CCID                            | 1        | 7.14%   |
| SCM Microsystems uTrust 3512 SAM slot Token            | 1        | 7.14%   |
| Lenovo Smartcard Keyboard                              | 1        | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 7.14%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader       | 1        | 7.14%   |
| Feitian Technologies SCR301                            | 1        | 7.14%   |
| Clay Logic Nitrokey Pro                                | 1        | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 7.14%   |
| Cherry SmartTerminal XX1X                              | 1        | 7.14%   |
| Alcor Micro Watchdata W 1981                           | 1        | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 7.14%   |
| Advanced Card Systems ACR39U                           | 1        | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1217     | 55.98%  |
| 1     | 841      | 38.68%  |
| 2     | 103      | 4.74%   |
| 3     | 9        | 0.41%   |
| 4     | 2        | 0.09%   |
| 7     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 815      | 80.22%  |
| Net/wireless             | 60       | 5.91%   |
| Communication controller | 34       | 3.35%   |
| Unassigned class         | 29       | 2.85%   |
| Sound                    | 16       | 1.57%   |
| Multimedia controller    | 13       | 1.28%   |
| Bluetooth                | 11       | 1.08%   |
| Camera                   | 8        | 0.79%   |
| Chipcard                 | 6        | 0.59%   |
| Net/ethernet             | 5        | 0.49%   |
| Card reader              | 5        | 0.49%   |
| Storage/raid             | 4        | 0.39%   |
| Tv card                  | 3        | 0.3%    |
| Modem                    | 3        | 0.3%    |
| Storage                  | 1        | 0.1%    |
| Network                  | 1        | 0.1%    |
| Fingerprint reader       | 1        | 0.1%    |
| Dvb card                 | 1        | 0.1%    |

