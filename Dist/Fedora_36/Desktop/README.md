Fedora 36 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 530

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0MWYPT A02                  | [e2f98387b0](https://linux-hardware.org/?probe=e2f98387b0) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [e5c7462ead](https://linux-hardware.org/?probe=e5c7462ead) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| Dell          | 0KV3RP A00                  | [731a14ee10](https://linux-hardware.org/?probe=731a14ee10) | Aug 31, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [2c72dfccbb](https://linux-hardware.org/?probe=2c72dfccbb) | Aug 30, 2022 |
| HP            | 8464                        | [16bb2588e0](https://linux-hardware.org/?probe=16bb2588e0) | Aug 30, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9fbdc83458](https://linux-hardware.org/?probe=9fbdc83458) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7b0113a203](https://linux-hardware.org/?probe=7b0113a203) | Aug 29, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [cf0cdab1da](https://linux-hardware.org/?probe=cf0cdab1da) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [60bc287a81](https://linux-hardware.org/?probe=60bc287a81) | Aug 29, 2022 |
| HP            | 8751                        | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [7d1dae1de6](https://linux-hardware.org/?probe=7d1dae1de6) | Aug 29, 2022 |
| MSI           | Z77A-G43                    | [1d1864dabc](https://linux-hardware.org/?probe=1d1864dabc) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3de4d575a9](https://linux-hardware.org/?probe=3de4d575a9) | Aug 27, 2022 |
| HP            | 805D                        | [419598ebba](https://linux-hardware.org/?probe=419598ebba) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Dell          | 0KV3RP A00                  | [f73bf383ce](https://linux-hardware.org/?probe=f73bf383ce) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | [f1c16cf6e7](https://linux-hardware.org/?probe=f1c16cf6e7) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dd68273352](https://linux-hardware.org/?probe=dd68273352) | Aug 26, 2022 |
| ASUSTek       | P5QL-E                      | [e69218ea58](https://linux-hardware.org/?probe=e69218ea58) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | UN62                        | [49fcd1324f](https://linux-hardware.org/?probe=49fcd1324f) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [69fd53a234](https://linux-hardware.org/?probe=69fd53a234) | Aug 25, 2022 |
| ASRock        | B450M Pro4                  | [47dc749c6c](https://linux-hardware.org/?probe=47dc749c6c) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Dell          | 0PU052                      | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | Z97-AR                      | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ae4a81a473](https://linux-hardware.org/?probe=ae4a81a473) | Aug 24, 2022 |
| ASRock        | X570M Pro4                  | [f2bc1e0fae](https://linux-hardware.org/?probe=f2bc1e0fae) | Aug 23, 2022 |
| Gigabyte      | H81M-S                      | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b0af95356c](https://linux-hardware.org/?probe=b0af95356c) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bc32a93168](https://linux-hardware.org/?probe=bc32a93168) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [eb81df27ce](https://linux-hardware.org/?probe=eb81df27ce) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| ASRock        | X370 Taichi                 | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [b2ac87cffc](https://linux-hardware.org/?probe=b2ac87cffc) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [fd0604d0fb](https://linux-hardware.org/?probe=fd0604d0fb) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| ASUSTek       | P8H67-M LE                  | [ce8c93b28f](https://linux-hardware.org/?probe=ce8c93b28f) | Aug 19, 2022 |
| ASRock        | B450 Pro4                   | [ed013e82aa](https://linux-hardware.org/?probe=ed013e82aa) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8fc237babf](https://linux-hardware.org/?probe=8fc237babf) | Aug 17, 2022 |
| Lenovo        | SHARKBAY NOK                | [e73d7ae317](https://linux-hardware.org/?probe=e73d7ae317) | Aug 17, 2022 |
| Dell          | 09M8Y8 A01                  | [9defe532c0](https://linux-hardware.org/?probe=9defe532c0) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [8b591b08b0](https://linux-hardware.org/?probe=8b591b08b0) | Aug 16, 2022 |
| ASUSTek       | Z97-C                       | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [97ff4c0078](https://linux-hardware.org/?probe=97ff4c0078) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [bbbda98d21](https://linux-hardware.org/?probe=bbbda98d21) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| ASUSTek       | P8H77-V                     | [83abda5bc9](https://linux-hardware.org/?probe=83abda5bc9) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [4983efddbb](https://linux-hardware.org/?probe=4983efddbb) | Aug 13, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [e1f4ef0670](https://linux-hardware.org/?probe=e1f4ef0670) | Aug 12, 2022 |
| MSI           | Z97 GAMING 5                | [e7c81a6ce7](https://linux-hardware.org/?probe=e7c81a6ce7) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6a8f06be23](https://linux-hardware.org/?probe=6a8f06be23) | Aug 12, 2022 |
| HP            | 8183                        | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| Gigabyte      | H370 HD3-CF                 | [3d93d807ca](https://linux-hardware.org/?probe=3d93d807ca) | Aug 12, 2022 |
| MSI           | X370 SLI PLUS               | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [5f25d77994](https://linux-hardware.org/?probe=5f25d77994) | Aug 11, 2022 |
| HP            | 8183                        | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [0790b09ae3](https://linux-hardware.org/?probe=0790b09ae3) | Aug 11, 2022 |
| Gigabyte      | B150M-D3H-CF                | [43b4579869](https://linux-hardware.org/?probe=43b4579869) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [c788f4d7a8](https://linux-hardware.org/?probe=c788f4d7a8) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [d586bdd82d](https://linux-hardware.org/?probe=d586bdd82d) | Aug 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8558001fa2](https://linux-hardware.org/?probe=8558001fa2) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| ECS           | H61H2-MV                    | [21fadb20ca](https://linux-hardware.org/?probe=21fadb20ca) | Aug 09, 2022 |
| MSI           | Z87-G45 GAMING              | [093a936372](https://linux-hardware.org/?probe=093a936372) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b421a8c6c4](https://linux-hardware.org/?probe=b421a8c6c4) | Aug 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [07c89bcbc6](https://linux-hardware.org/?probe=07c89bcbc6) | Aug 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | [f08a60d37c](https://linux-hardware.org/?probe=f08a60d37c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| MSI           | MAG B460M MORTAR            | [a823925843](https://linux-hardware.org/?probe=a823925843) | Aug 07, 2022 |
| HP            | 1587h                       | [d9d1b6832f](https://linux-hardware.org/?probe=d9d1b6832f) | Aug 07, 2022 |
| HP            | 1587h                       | [737b509512](https://linux-hardware.org/?probe=737b509512) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [31c87abaf3](https://linux-hardware.org/?probe=31c87abaf3) | Aug 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | SABERTOOTH X79              | [4f10e80880](https://linux-hardware.org/?probe=4f10e80880) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [36e148426c](https://linux-hardware.org/?probe=36e148426c) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [28ec23aa22](https://linux-hardware.org/?probe=28ec23aa22) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| ASRock        | B460M Pro4S/ac              | [79f01ebf66](https://linux-hardware.org/?probe=79f01ebf66) | Aug 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c6e5356615](https://linux-hardware.org/?probe=c6e5356615) | Aug 04, 2022 |
| Gigabyte      | M68MT-S2P                   | [7c41cd3006](https://linux-hardware.org/?probe=7c41cd3006) | Aug 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [df01e617f2](https://linux-hardware.org/?probe=df01e617f2) | Aug 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6e77095fb6](https://linux-hardware.org/?probe=6e77095fb6) | Aug 03, 2022 |
| Dell          | 05GD68 A00                  | [32bda73b5e](https://linux-hardware.org/?probe=32bda73b5e) | Aug 03, 2022 |
| ASRock        | AB350M-HDV                  | [4678a0f755](https://linux-hardware.org/?probe=4678a0f755) | Aug 03, 2022 |
| HP            | 8767 A                      | [3679ccede7](https://linux-hardware.org/?probe=3679ccede7) | Aug 02, 2022 |
| MSI           | H510M-A PRO                 | [b570321ffa](https://linux-hardware.org/?probe=b570321ffa) | Aug 02, 2022 |
| Dell          | 0Y56T3 A00                  | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [37b8171416](https://linux-hardware.org/?probe=37b8171416) | Aug 01, 2022 |
| MSI           | H81M-E34                    | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| ASUSTek       | M4A77TD                     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ebe9fe3b1a](https://linux-hardware.org/?probe=ebe9fe3b1a) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| ASRock        | B450M Pro4-F                | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| HP            | 1494                        | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Dell          | 0DF42J A00                  | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41dbccf7d9](https://linux-hardware.org/?probe=41dbccf7d9) | Jul 21, 2022 |
| Dell          | 0WMJ54 A01                  | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c763e49e7e](https://linux-hardware.org/?probe=c763e49e7e) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| NCR           | Pocono BIOS.6.0             | [3026f24fe3](https://linux-hardware.org/?probe=3026f24fe3) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [190936df71](https://linux-hardware.org/?probe=190936df71) | Jul 19, 2022 |
| ASUSTek       | M11BB                       | [582292657c](https://linux-hardware.org/?probe=582292657c) | Jul 18, 2022 |
| MSI           | MEG B550 UNIFY              | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| ASRock        | AD2700-ITX                  | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [aae1bec902](https://linux-hardware.org/?probe=aae1bec902) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Huanan        | B75                         | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [326c97ba50](https://linux-hardware.org/?probe=326c97ba50) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d60e6afc41](https://linux-hardware.org/?probe=d60e6afc41) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41517adf39](https://linux-hardware.org/?probe=41517adf39) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fc316a6331](https://linux-hardware.org/?probe=fc316a6331) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| HP            | 88BF                        | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1338941bd0](https://linux-hardware.org/?probe=1338941bd0) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| ASUSTek       | M5A97 PRO                   | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [165cdc7df2](https://linux-hardware.org/?probe=165cdc7df2) | Jul 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea3f033d93](https://linux-hardware.org/?probe=ea3f033d93) | Jul 14, 2022 |
| ASUSTek       | PRIME Z390-A                | [7486493ea1](https://linux-hardware.org/?probe=7486493ea1) | Jul 14, 2022 |
| Dell          | 0J3C2F A00                  | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| ASRock        | X570 Taichi                 | [98ffa2e8b0](https://linux-hardware.org/?probe=98ffa2e8b0) | Jul 13, 2022 |
| HP            | 1632                        | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| HP            | 8768 A                      | [f4afb80e18](https://linux-hardware.org/?probe=f4afb80e18) | Jul 12, 2022 |
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c69dd8da85](https://linux-hardware.org/?probe=c69dd8da85) | Jul 12, 2022 |
| MSI           | H97M-G43                    | [c8b2844540](https://linux-hardware.org/?probe=c8b2844540) | Jul 11, 2022 |
| HP            | 3646h                       | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Dell          | 0XCR8D A03                  | [b6771bbe08](https://linux-hardware.org/?probe=b6771bbe08) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [314c3aaf0e](https://linux-hardware.org/?probe=314c3aaf0e) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | [d6f1e47bf5](https://linux-hardware.org/?probe=d6f1e47bf5) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [45e46ac933](https://linux-hardware.org/?probe=45e46ac933) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6513be6d44](https://linux-hardware.org/?probe=6513be6d44) | Jul 09, 2022 |
| HP            | 8455                        | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [546a26c882](https://linux-hardware.org/?probe=546a26c882) | Jul 07, 2022 |
| HP            | 8455                        | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [234b2b0ee8](https://linux-hardware.org/?probe=234b2b0ee8) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [8c15268c47](https://linux-hardware.org/?probe=8c15268c47) | Jul 06, 2022 |
| Unknown       | Unknown                     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [a0a2cd9568](https://linux-hardware.org/?probe=a0a2cd9568) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [699e033557](https://linux-hardware.org/?probe=699e033557) | Jul 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [54f8e71da0](https://linux-hardware.org/?probe=54f8e71da0) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [0954f0b44c](https://linux-hardware.org/?probe=0954f0b44c) | Jul 06, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| MSI           | MEG X570 UNIFY              | [f1de99a0da](https://linux-hardware.org/?probe=f1de99a0da) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [58b8e08cf9](https://linux-hardware.org/?probe=58b8e08cf9) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [963029db26](https://linux-hardware.org/?probe=963029db26) | Jul 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d22d14874](https://linux-hardware.org/?probe=2d22d14874) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [519e378380](https://linux-hardware.org/?probe=519e378380) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| BESSTAR Te... | HM90                        | [e8a4e37cc6](https://linux-hardware.org/?probe=e8a4e37cc6) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3c48bb18e](https://linux-hardware.org/?probe=c3c48bb18e) | Jun 25, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| HP            | 89D8 SMVB                   | [f92ff0c37f](https://linux-hardware.org/?probe=f92ff0c37f) | Jun 24, 2022 |
| MSI           | IONA                        | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASRock        | H77 Pro4/MVP                | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5129e4893a](https://linux-hardware.org/?probe=5129e4893a) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [dbfad9b8fe](https://linux-hardware.org/?probe=dbfad9b8fe) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [6f13e0f8a0](https://linux-hardware.org/?probe=6f13e0f8a0) | Jun 23, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Unknown       | HX90                        | [837e70229a](https://linux-hardware.org/?probe=837e70229a) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 2B05                        | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASRock        | B550M Pro4                  | [45871f6d61](https://linux-hardware.org/?probe=45871f6d61) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| System76      | Thelio Mira thelio-mira-... | [58c9da7f20](https://linux-hardware.org/?probe=58c9da7f20) | Jun 22, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [04927da7b6](https://linux-hardware.org/?probe=04927da7b6) | Jun 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| MSI           | H510I PRO WIFI              | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| Dell          | 0XC7MM A01                  | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| HP            | 18E5                        | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| MSI           | B450M MORTAR                | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c446ea33eb](https://linux-hardware.org/?probe=c446ea33eb) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9fe17edc24](https://linux-hardware.org/?probe=9fe17edc24) | Jun 06, 2022 |
| ASUSTek       | P8H67-M LE                  | [d1409ca910](https://linux-hardware.org/?probe=d1409ca910) | Jun 06, 2022 |
| Dell          | 0XC7MM A01                  | [ed376c819b](https://linux-hardware.org/?probe=ed376c819b) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Dell          | 08K0X7 A00                  | [28a29e32c6](https://linux-hardware.org/?probe=28a29e32c6) | Jun 06, 2022 |
| Dell          | 06JWJY A00                  | [577bbe62e1](https://linux-hardware.org/?probe=577bbe62e1) | Jun 06, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [8b87017c24](https://linux-hardware.org/?probe=8b87017c24) | Jun 05, 2022 |
| Gigabyte      | B460M DS3H V2               | [afb7427d61](https://linux-hardware.org/?probe=afb7427d61) | Jun 05, 2022 |
| Foxconn       | H81MXV FAB A                | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Gigabyte      | B75M-HD3                    | [63a565a5e1](https://linux-hardware.org/?probe=63a565a5e1) | Jun 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [feec15b490](https://linux-hardware.org/?probe=feec15b490) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [1813b3a9a5](https://linux-hardware.org/?probe=1813b3a9a5) | Jun 04, 2022 |
| ASUSTek       | CROSSHAIR                   | [11834759e2](https://linux-hardware.org/?probe=11834759e2) | Jun 04, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2e9cc784ac](https://linux-hardware.org/?probe=2e9cc784ac) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| MSI           | B560M PRO-VDH               | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [b68bcf6b84](https://linux-hardware.org/?probe=b68bcf6b84) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [53dbc2fe14](https://linux-hardware.org/?probe=53dbc2fe14) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [07a1bcfa9e](https://linux-hardware.org/?probe=07a1bcfa9e) | May 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b27373492](https://linux-hardware.org/?probe=7b27373492) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | [23c83c37e6](https://linux-hardware.org/?probe=23c83c37e6) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| ASUSTek       | H81M-A                      | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| BESSTAR Te... | UM700                       | [f754f78f66](https://linux-hardware.org/?probe=f754f78f66) | May 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [06e3526c59](https://linux-hardware.org/?probe=06e3526c59) | May 25, 2022 |
| ASRock        | X99 Taichi                  | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | KCMA-D8                     | [2d8bea4f55](https://linux-hardware.org/?probe=2d8bea4f55) | May 24, 2022 |
| Dell          | 0PU052                      | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [282c849b82](https://linux-hardware.org/?probe=282c849b82) | May 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | Z77A-G43                    | [7d35f08c28](https://linux-hardware.org/?probe=7d35f08c28) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| ASRock        | AB350 Pro4                  | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | [1984313b19](https://linux-hardware.org/?probe=1984313b19) | May 20, 2022 |
| ASRock        | Z390 Taichi Ultimate        | [68d0cdd597](https://linux-hardware.org/?probe=68d0cdd597) | May 19, 2022 |
| HP            | 82A2                        | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| HP            | 8767 A                      | [0f564fe004](https://linux-hardware.org/?probe=0f564fe004) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| Dell          | 0DF42J A00                  | [ac9f539524](https://linux-hardware.org/?probe=ac9f539524) | May 18, 2022 |
| HP            | 8767 A                      | [caad4001f1](https://linux-hardware.org/?probe=caad4001f1) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Dell          | 0NKW6Y A02                  | [ffee0745b6](https://linux-hardware.org/?probe=ffee0745b6) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [fa17134027](https://linux-hardware.org/?probe=fa17134027) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [16bd9d3c6d](https://linux-hardware.org/?probe=16bd9d3c6d) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [12d277d32c](https://linux-hardware.org/?probe=12d277d32c) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [6fc56522d6](https://linux-hardware.org/?probe=6fc56522d6) | May 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1bde2ca3e7](https://linux-hardware.org/?probe=1bde2ca3e7) | May 14, 2022 |
| ASUSTek       | P8Z77-V LK                  | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| ASRock        | B560M-C                     | [b4946d836b](https://linux-hardware.org/?probe=b4946d836b) | May 13, 2022 |
| ASRock        | B560M-C                     | [16360de6cd](https://linux-hardware.org/?probe=16360de6cd) | May 13, 2022 |
| Gigabyte      | GA-K8NF-9                   | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| ASRock        | X570M Pro4                  | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Acer          | Aspire M3985                | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASRock        | X470 Taichi                 | [9ead3d53b0](https://linux-hardware.org/?probe=9ead3d53b0) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| ASRock        | 880GMH/U3S3                 | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| ASRock        | X470 Taichi                 | [fb1d5703eb](https://linux-hardware.org/?probe=fb1d5703eb) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d7e92b0ac7](https://linux-hardware.org/?probe=d7e92b0ac7) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d24bbea844](https://linux-hardware.org/?probe=d24bbea844) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| ASUSTek       | PRIME X470-PRO              | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Gigabyte      | H410M H V3                  | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| ASUSTek       | P8H67-M LE                  | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| HP            | 1589                        | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| ASRock        | B450 Steel Legend           | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS PRO              | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| Gigabyte      | H81M-S2H                    | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Gigabyte      | H110M-H-CF                  | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Dell          | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Gigabyte      | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Biostar       | H55 HD                      | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| HP            | 304Ah                       | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.18.13-200.fc36.x86_64                                       | 42       | 9.57%   |
| 5.18.16-200.fc36.x86_64                                       | 31       | 7.06%   |
| 5.18.5-200.fc36.x86_64                                        | 30       | 6.83%   |
| 5.18.11-200.fc36.x86_64                                       | 30       | 6.83%   |
| 5.17.5-300.fc36.x86_64                                        | 30       | 6.83%   |
| 5.17.6-300.fc36.x86_64                                        | 23       | 5.24%   |
| 5.17.11-300.fc36.x86_64                                       | 20       | 4.56%   |
| 5.18.18-200.fc36.x86_64                                       | 19       | 4.33%   |
| 5.18.10-200.fc36.x86_64                                       | 18       | 4.1%    |
| 5.17.12-300.fc36.x86_64                                       | 16       | 3.64%   |
| 5.18.9-200.fc36.x86_64                                        | 15       | 3.42%   |
| 5.17.13-300.fc36.x86_64                                       | 15       | 3.42%   |
| 5.17.8-300.fc36.x86_64                                        | 13       | 2.96%   |
| 5.18.7-200.fc36.x86_64                                        | 12       | 2.73%   |
| 5.18.6-200.fc36.x86_64                                        | 11       | 2.51%   |
| 5.17.2-300.fc36.x86_64                                        | 11       | 2.51%   |
| 5.17.1-300.fc36.x86_64                                        | 10       | 2.28%   |
| 5.17.7-300.fc36.x86_64                                        | 9        | 2.05%   |
| 5.18.19-200.fc36.x86_64                                       | 8        | 1.82%   |
| 5.18.17-200.fc36.x86_64                                       | 8        | 1.82%   |
| 5.18.15-200.fc36.x86_64                                       | 8        | 1.82%   |
| 5.17.3-302.fc36.x86_64                                        | 6        | 1.37%   |
| 5.19.4-200.fc36.x86_64                                        | 5        | 1.14%   |
| 5.17.9-300.fc36.x86_64                                        | 5        | 1.14%   |
| 5.17.14-300.fc36.x86_64                                       | 3        | 0.68%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 3        | 0.68%   |
| 5.18.1-602.inttf.fc36.x86_64                                  | 2        | 0.46%   |
| 5.18.1-200.fc36.x86_64                                        | 2        | 0.46%   |
| 5.17.4-300.fc36.x86_64                                        | 2        | 0.46%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2        | 0.46%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 2        | 0.46%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2        | 0.46%   |
| 5.19.6-200.fc36.x86_64                                        | 1        | 0.23%   |
| 5.19.3-603.inttf.fc36.x86_64                                  | 1        | 0.23%   |
| 5.19.2-300.fc36.x86_64                                        | 1        | 0.23%   |
| 5.19.0-0.rc5.39.fc37.x86_64                                   | 1        | 0.23%   |
| 5.18.9-gnu                                                    | 1        | 0.23%   |
| 5.18.9-201.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.18.9-100.fc35.x86_64                                        | 1        | 0.23%   |
| 5.18.8-xm1.0.fc36.x86_64                                      | 1        | 0.23%   |
| 5.18.6-201.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.18.5-gnu                                                    | 1        | 0.23%   |
| 5.18.5-201.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.18.2-rc1_MY                                                 | 1        | 0.23%   |
| 5.18.10-201.fsync.fc36.x86_64                                 | 1        | 0.23%   |
| 5.18.0-0.rc4.20220428git8f4dd16603ce834.36.fc37.x86_64        | 1        | 0.23%   |
| 5.17.9-602.inttf.fc36.x86_64                                  | 1        | 0.23%   |
| 5.17.9-301.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.17.7-301.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.17.6-602.inttf.fc36.x86_64                                  | 1        | 0.23%   |
| 5.17.5-301.fsync.fc36.x86_64                                  | 1        | 0.23%   |
| 5.17.12-301.fsync.fc36.x86_64                                 | 1        | 0.23%   |
| 5.17.11-602.inttf.fc36.x86_64                                 | 1        | 0.23%   |
| 5.17.11-301.fsync.fc36.x86_64                                 | 1        | 0.23%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1        | 0.23%   |
| 5.16.17-200.fc35.x86_64                                       | 1        | 0.23%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1        | 0.23%   |
| 5.11.12-300.fc34.x86_64                                       | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.18.13 | 42       | 9.57%   |
| 5.18.5  | 32       | 7.29%   |
| 5.18.16 | 31       | 7.06%   |
| 5.17.5  | 31       | 7.06%   |
| 5.18.11 | 30       | 6.83%   |
| 5.17.6  | 24       | 5.47%   |
| 5.17.11 | 22       | 5.01%   |
| 5.18.18 | 19       | 4.33%   |
| 5.18.10 | 19       | 4.33%   |
| 5.18.9  | 18       | 4.1%    |
| 5.17.12 | 17       | 3.87%   |
| 5.17.13 | 15       | 3.42%   |
| 5.17.8  | 13       | 2.96%   |
| 5.18.7  | 12       | 2.73%   |
| 5.18.6  | 12       | 2.73%   |
| 5.17.2  | 11       | 2.51%   |
| 5.17.7  | 10       | 2.28%   |
| 5.17.1  | 10       | 2.28%   |
| 5.18.19 | 8        | 1.82%   |
| 5.18.17 | 8        | 1.82%   |
| 5.18.15 | 8        | 1.82%   |
| 5.17.9  | 7        | 1.59%   |
| 5.17.3  | 6        | 1.37%   |
| 5.17.0  | 6        | 1.37%   |
| 5.19.4  | 5        | 1.14%   |
| 5.18.1  | 4        | 0.91%   |
| 5.17.14 | 3        | 0.68%   |
| 5.15.0  | 3        | 0.68%   |
| 5.17.4  | 2        | 0.46%   |
| 5.14.0  | 2        | 0.46%   |
| 5.19.6  | 1        | 0.23%   |
| 5.19.3  | 1        | 0.23%   |
| 5.19.2  | 1        | 0.23%   |
| 5.19.0  | 1        | 0.23%   |
| 5.18.8  | 1        | 0.23%   |
| 5.18.2  | 1        | 0.23%   |
| 5.18.0  | 1        | 0.23%   |
| 5.16.17 | 1        | 0.23%   |
| 5.11.12 | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.18    | 233      | 55.74%  |
| 5.17    | 169      | 40.43%  |
| 5.19    | 9        | 2.15%   |
| 5.15    | 3        | 0.72%   |
| 5.14    | 2        | 0.48%   |
| 5.16    | 1        | 0.24%   |
| 5.11    | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 398      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 273      | 68.59%  |
| KDE5          | 78       | 19.6%   |
| Cinnamon      | 11       | 2.76%   |
| XFCE          | 10       | 2.51%   |
| X-Cinnamon    | 10       | 2.51%   |
| Unknown       | 7        | 1.76%   |
| MATE          | 4        | 1.01%   |
| GNOME Classic | 2        | 0.5%    |
| LXQt          | 1        | 0.25%   |
| i3            | 1        | 0.25%   |
| awesome       | 1        | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 245      | 60.95%  |
| X11     | 133      | 33.08%  |
| Tty     | 21       | 5.22%   |
| Web     | 2        | 0.5%    |
| Unknown | 1        | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 242      | 60.65%  |
| GDM     | 91       | 22.81%  |
| SDDM    | 36       | 9.02%   |
| LightDM | 30       | 7.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 193      | 48.49%  |
| ru_RU   | 33       | 8.29%   |
| en_GB   | 28       | 7.04%   |
| pt_BR   | 23       | 5.78%   |
| en_AU   | 20       | 5.03%   |
| de_DE   | 13       | 3.27%   |
| fr_FR   | 11       | 2.76%   |
| pl_PL   | 8        | 2.01%   |
| es_ES   | 8        | 2.01%   |
| en_CA   | 6        | 1.51%   |
| en_NZ   | 5        | 1.26%   |
| cs_CZ   | 5        | 1.26%   |
| zh_CN   | 4        | 1.01%   |
| es_AR   | 4        | 1.01%   |
| en_IN   | 4        | 1.01%   |
| nl_NL   | 3        | 0.75%   |
| nl_BE   | 3        | 0.75%   |
| ja_JP   | 2        | 0.5%    |
| it_IT   | 2        | 0.5%    |
| fi_FI   | 2        | 0.5%    |
| es_MX   | 2        | 0.5%    |
| en_SG   | 2        | 0.5%    |
| C       | 2        | 0.5%    |
| tr_TR   | 1        | 0.25%   |
| sv_SE   | 1        | 0.25%   |
| sr_RS   | 1        | 0.25%   |
| sk_SK   | 1        | 0.25%   |
| pt_PT   | 1        | 0.25%   |
| fr_BE   | 1        | 0.25%   |
| es_EC   | 1        | 0.25%   |
| es_CR   | 1        | 0.25%   |
| en_ZA   | 1        | 0.25%   |
| en_IE   | 1        | 0.25%   |
| en_DK   | 1        | 0.25%   |
| de_AT   | 1        | 0.25%   |
| Default | 1        | 0.25%   |
| da_DK   | 1        | 0.25%   |
| ar_SA   | 1        | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 285      | 71.43%  |
| BIOS | 114      | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 327      | 81.95%  |
| Ext4  | 55       | 13.78%  |
| Xfs   | 17       | 4.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 238      | 59.65%  |
| GPT     | 130      | 32.58%  |
| MBR     | 31       | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 87.25%  |
| Yes       | 51       | 12.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 312      | 78.2%   |
| Yes       | 87       | 21.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 126      | 31.66%  |
| Gigabyte Technology | 82       | 20.6%   |
| MSI                 | 69       | 17.34%  |
| ASRock              | 37       | 9.3%    |
| Dell                | 26       | 6.53%   |
| Hewlett-Packard     | 21       | 5.28%   |
| Lenovo              | 10       | 2.51%   |
| Intel               | 4        | 1.01%   |
| Huanan              | 3        | 0.75%   |
| BESSTAR Tech        | 3        | 0.75%   |
| Foxconn             | 2        | 0.5%    |
| ECS                 | 2        | 0.5%    |
| Biostar             | 2        | 0.5%    |
| Acer                | 2        | 0.5%    |
| Unknown             | 2        | 0.5%    |
| ZOTAC               | 1        | 0.25%   |
| System76            | 1        | 0.25%   |
| Positivo            | 1        | 0.25%   |
| Pegatron            | 1        | 0.25%   |
| NCR                 | 1        | 0.25%   |
| MACHINIST           | 1        | 0.25%   |
| Fujitsu             | 1        | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 10       | 2.51%   |
| ASUS ROG STRIX B550-F GAMING         | 7        | 1.76%   |
| MSI MS-7A38                          | 6        | 1.51%   |
| MSI MS-7C37                          | 5        | 1.26%   |
| ASUS TUF Gaming B550M-PLUS           | 4        | 1.01%   |
| MSI MS-7C95                          | 3        | 0.75%   |
| MSI MS-7C91                          | 3        | 0.75%   |
| Dell OptiPlex 9020                   | 3        | 0.75%   |
| ASUS TUF Gaming X570-PLUS            | 3        | 0.75%   |
| ASUS ROG STRIX B550-I GAMING         | 3        | 0.75%   |
| ASUS PRIME X470-PRO                  | 3        | 0.75%   |
| ASUS CROSSHAIR V FORMULA-Z           | 3        | 0.75%   |
| Unknown                              | 3        | 0.75%   |
| MSI MS-7D54                          | 2        | 0.5%    |
| MSI MS-7D43                          | 2        | 0.5%    |
| MSI MS-7C92                          | 2        | 0.5%    |
| MSI MS-7C56                          | 2        | 0.5%    |
| MSI MS-7B86                          | 2        | 0.5%    |
| MSI MS-7B79                          | 2        | 0.5%    |
| MSI MS-7A33                          | 2        | 0.5%    |
| MSI MS-7996                          | 2        | 0.5%    |
| MSI MS-7817                          | 2        | 0.5%    |
| MSI MS-7758                          | 2        | 0.5%    |
| Intel DH77EB AAG39073-304            | 2        | 0.5%    |
| HP Z2 Tower G4 Workstation           | 2        | 0.5%    |
| Gigabyte Z87-HD3                     | 2        | 0.5%    |
| Gigabyte X570 AORUS PRO              | 2        | 0.5%    |
| Gigabyte GA-78LMT-USB3 6.0           | 2        | 0.5%    |
| Gigabyte B550M DS3H                  | 2        | 0.5%    |
| Gigabyte B550I AORUS PRO AX          | 2        | 0.5%    |
| Gigabyte B550 GAMING X V2            | 2        | 0.5%    |
| Gigabyte B450 AORUS M                | 2        | 0.5%    |
| Gigabyte 970A-DS3P                   | 2        | 0.5%    |
| ECS H61H2-MV                         | 2        | 0.5%    |
| Dell XPS 8940                        | 2        | 0.5%    |
| Dell Precision Tower 3620            | 2        | 0.5%    |
| Dell OptiPlex 790                    | 2        | 0.5%    |
| Dell OptiPlex 755                    | 2        | 0.5%    |
| Dell OptiPlex 7020                   | 2        | 0.5%    |
| BESSTAR Tech HM90                    | 2        | 0.5%    |
| ASUS TUF Gaming B550-PLUS            | 2        | 0.5%    |
| ASUS ROG STRIX X570-F GAMING         | 2        | 0.5%    |
| ASUS ROG STRIX X570-E GAMING WIFI II | 2        | 0.5%    |
| ASUS ROG STRIX X570-E GAMING         | 2        | 0.5%    |
| ASUS ROG STRIX B550-E GAMING         | 2        | 0.5%    |
| ASUS ROG STRIX B450-F GAMING II      | 2        | 0.5%    |
| ASUS ROG CROSSHAIR VIII IMPACT       | 2        | 0.5%    |
| ASUS ProArt Z690-CREATOR WIFI        | 2        | 0.5%    |
| ASUS PRIME Z390-A                    | 2        | 0.5%    |
| ASUS PRIME Z370-A                    | 2        | 0.5%    |
| ASUS PRIME B550M-A                   | 2        | 0.5%    |
| ASRock X570M Pro4                    | 2        | 0.5%    |
| ASRock X470 Taichi                   | 2        | 0.5%    |
| ASRock B450M Steel Legend            | 2        | 0.5%    |
| ASRock B450M Pro4                    | 2        | 0.5%    |
| System76 Thelio Mira                 | 1        | 0.25%   |
| Positivo POS-PIH55BO                 | 1        | 0.25%   |
| Pegatron IPM41-D3                    | 1        | 0.25%   |
| NCR 7606-1007-8801                   | 1        | 0.25%   |
| MSI WC698AA-UUG p6320be              | 1        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 37       | 9.3%    |
| ASUS PRIME             | 25       | 6.28%   |
| ASUS TUF               | 17       | 4.27%   |
| Dell OptiPlex          | 12       | 3.02%   |
| ASUS All               | 10       | 2.51%   |
| Dell Precision         | 8        | 2.01%   |
| MSI MS-7A38            | 6        | 1.51%   |
| Lenovo ThinkCentre     | 6        | 1.51%   |
| MSI MS-7C37            | 5        | 1.26%   |
| Gigabyte B550          | 5        | 1.26%   |
| ASRock B450M           | 5        | 1.26%   |
| HP Z2                  | 4        | 1.01%   |
| HP Compaq              | 4        | 1.01%   |
| Gigabyte X570          | 4        | 1.01%   |
| Dell XPS               | 4        | 1.01%   |
| ASUS CROSSHAIR         | 4        | 1.01%   |
| MSI MS-7C95            | 3        | 0.75%   |
| MSI MS-7C91            | 3        | 0.75%   |
| Gigabyte B550M         | 3        | 0.75%   |
| Gigabyte B450          | 3        | 0.75%   |
| ASUS ProArt            | 3        | 0.75%   |
| ASRock B450            | 3        | 0.75%   |
| Unknown                | 3        | 0.75%   |
| MSI MS-7D54            | 2        | 0.5%    |
| MSI MS-7D43            | 2        | 0.5%    |
| MSI MS-7C92            | 2        | 0.5%    |
| MSI MS-7C56            | 2        | 0.5%    |
| MSI MS-7B86            | 2        | 0.5%    |
| MSI MS-7B79            | 2        | 0.5%    |
| MSI MS-7A33            | 2        | 0.5%    |
| MSI MS-7996            | 2        | 0.5%    |
| MSI MS-7817            | 2        | 0.5%    |
| MSI MS-7758            | 2        | 0.5%    |
| Intel DH77EB           | 2        | 0.5%    |
| Huanan X99-BD4         | 2        | 0.5%    |
| HP ProDesk             | 2        | 0.5%    |
| HP Pavilion            | 2        | 0.5%    |
| HP EliteDesk           | 2        | 0.5%    |
| Gigabyte Z87-HD3       | 2        | 0.5%    |
| Gigabyte Z690I         | 2        | 0.5%    |
| Gigabyte Z390          | 2        | 0.5%    |
| Gigabyte X470          | 2        | 0.5%    |
| Gigabyte H410M         | 2        | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 2        | 0.5%    |
| Gigabyte B550I         | 2        | 0.5%    |
| Gigabyte 970A-DS3P     | 2        | 0.5%    |
| ECS H61H2-MV           | 2        | 0.5%    |
| Dell Inspiron          | 2        | 0.5%    |
| BESSTAR Tech HM90      | 2        | 0.5%    |
| ASUS STRIX             | 2        | 0.5%    |
| ASUS M5A97             | 2        | 0.5%    |
| ASRock Z390            | 2        | 0.5%    |
| ASRock X570M           | 2        | 0.5%    |
| ASRock X570            | 2        | 0.5%    |
| ASRock X470            | 2        | 0.5%    |
| ASRock X370            | 2        | 0.5%    |
| ASRock AB350           | 2        | 0.5%    |
| Acer Aspire            | 2        | 0.5%    |
| System76 Thelio        | 1        | 0.25%   |
| Positivo POS-PIH55BO   | 1        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 70       | 17.59%  |
| 2019 | 50       | 12.56%  |
| 2021 | 42       | 10.55%  |
| 2018 | 42       | 10.55%  |
| 2012 | 30       | 7.54%   |
| 2017 | 25       | 6.28%   |
| 2014 | 24       | 6.03%   |
| 2013 | 20       | 5.03%   |
| 2022 | 16       | 4.02%   |
| 2015 | 16       | 4.02%   |
| 2016 | 15       | 3.77%   |
| 2011 | 13       | 3.27%   |
| 2010 | 12       | 3.02%   |
| 2009 | 7        | 1.76%   |
| 2008 | 7        | 1.76%   |
| 2007 | 6        | 1.51%   |
| 2006 | 2        | 0.5%    |
| 2005 | 1        | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 398      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 366      | 91.5%   |
| Enabled  | 34       | 8.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 398      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 129      | 32.33%  |
| 32.01-64.0  | 115      | 28.82%  |
| 8.01-16.0   | 48       | 12.03%  |
| 4.01-8.0    | 44       | 11.03%  |
| 64.01-256.0 | 32       | 8.02%   |
| 3.01-4.0    | 17       | 4.26%   |
| 24.01-32.0  | 8        | 2.01%   |
| 1.01-2.0    | 4        | 1%      |
| 2.01-3.0    | 2        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 130      | 31.18%  |
| 2.01-3.0   | 106      | 25.42%  |
| 3.01-4.0   | 84       | 20.14%  |
| 1.01-2.0   | 43       | 10.31%  |
| 8.01-16.0  | 37       | 8.87%   |
| 0.51-1.0   | 8        | 1.92%   |
| 16.01-24.0 | 7        | 1.68%   |
| 0.01-0.5   | 2        | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 133      | 33.25%  |
| 1      | 102      | 25.5%   |
| 3      | 80       | 20%     |
| 4      | 52       | 13%     |
| 6      | 13       | 3.25%   |
| 5      | 12       | 3%      |
| 7      | 5        | 1.25%   |
| 10     | 2        | 0.5%    |
| 9      | 1        | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 286      | 71.86%  |
| Yes       | 112      | 28.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 394      | 98.99%  |
| No        | 4        | 1.01%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 225      | 56.39%  |
| No        | 174      | 43.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 208      | 52.13%  |
| Yes       | 191      | 47.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 93       | 23.31%  |
| Russia          | 33       | 8.27%   |
| Brazil          | 31       | 7.77%   |
| Germany         | 24       | 6.02%   |
| Australia       | 20       | 5.01%   |
| UK              | 17       | 4.26%   |
| France          | 15       | 3.76%   |
| Poland          | 14       | 3.51%   |
| Spain           | 10       | 2.51%   |
| Netherlands     | 10       | 2.51%   |
| Canada          | 9        | 2.26%   |
| Sweden          | 8        | 2.01%   |
| India           | 8        | 2.01%   |
| Belgium         | 8        | 2.01%   |
| Italy           | 6        | 1.5%    |
| Finland         | 6        | 1.5%    |
| Argentina       | 6        | 1.5%    |
| Czechia         | 5        | 1.25%   |
| Switzerland     | 4        | 1%      |
| New Zealand     | 4        | 1%      |
| Mexico          | 4        | 1%      |
| Israel          | 4        | 1%      |
| China           | 4        | 1%      |
| Belarus         | 4        | 1%      |
| Turkey          | 3        | 0.75%   |
| Norway          | 3        | 0.75%   |
| Indonesia       | 3        | 0.75%   |
| Greece          | 3        | 0.75%   |
| Thailand        | 2        | 0.5%    |
| Slovakia        | 2        | 0.5%    |
| Romania         | 2        | 0.5%    |
| Japan           | 2        | 0.5%    |
| Ireland         | 2        | 0.5%    |
| Hungary         | 2        | 0.5%    |
| Estonia         | 2        | 0.5%    |
| Ecuador         | 2        | 0.5%    |
| Colombia        | 2        | 0.5%    |
| Bulgaria        | 2        | 0.5%    |
| Vietnam         | 1        | 0.25%   |
| Uruguay         | 1        | 0.25%   |
| Ukraine         | 1        | 0.25%   |
| South Korea     | 1        | 0.25%   |
| South Africa    | 1        | 0.25%   |
| Singapore       | 1        | 0.25%   |
| Serbia          | 1        | 0.25%   |
| Saudi Arabia    | 1        | 0.25%   |
| Puerto Rico     | 1        | 0.25%   |
| Portugal        | 1        | 0.25%   |
| Philippines     | 1        | 0.25%   |
| Pakistan        | 1        | 0.25%   |
| North Macedonia | 1        | 0.25%   |
| Malaysia        | 1        | 0.25%   |
| Denmark         | 1        | 0.25%   |
| Costa Rica      | 1        | 0.25%   |
| Bangladesh      | 1        | 0.25%   |
| Austria         | 1        | 0.25%   |
| Andorra         | 1        | 0.25%   |
| Albania         | 1        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Launceston     | 8        | 1.98%   |
| Moscow         | 7        | 1.73%   |
| Brisbane       | 6        | 1.48%   |
| Warsaw         | 5        | 1.23%   |
| Novosibirsk    | 5        | 1.23%   |
| Vitória       | 4        | 0.99%   |
| Berlin         | 4        | 0.99%   |
| Sydney         | 3        | 0.74%   |
| Porto Alegre   | 3        | 0.74%   |
| Portland       | 3        | 0.74%   |
| Pasco          | 3        | 0.74%   |
| Oulu           | 3        | 0.74%   |
| New York       | 3        | 0.74%   |
| Minsk          | 3        | 0.74%   |
| Mexico City    | 3        | 0.74%   |
| Melbourne      | 3        | 0.74%   |
| Marietta       | 3        | 0.74%   |
| Los Angeles    | 3        | 0.74%   |
| Lane Cove      | 3        | 0.74%   |
| Chicago        | 3        | 0.74%   |
| Brussels       | 3        | 0.74%   |
| Belo Horizonte | 3        | 0.74%   |
| Auckland       | 3        | 0.74%   |
| Yekaterinburg  | 2        | 0.49%   |
| Wroclaw        | 2        | 0.49%   |
| Tel Aviv       | 2        | 0.49%   |
| Tallinn        | 2        | 0.49%   |
| Stuttgart      | 2        | 0.49%   |
| St Petersburg  | 2        | 0.49%   |
| Sollentuna     | 2        | 0.49%   |
| Sao Paulo      | 2        | 0.49%   |
| San Jose       | 2        | 0.49%   |
| Rio de Janeiro | 2        | 0.49%   |
| Paris          | 2        | 0.49%   |
| Las Vegas      | 2        | 0.49%   |
| Kansas City    | 2        | 0.49%   |
| Jakarta        | 2        | 0.49%   |
| Houston        | 2        | 0.49%   |
| Goiânia       | 2        | 0.49%   |
| Fayetteville   | 2        | 0.49%   |
| Burgas         | 2        | 0.49%   |
| Bucharest      | 2        | 0.49%   |
| Bonn           | 2        | 0.49%   |
| Beijing        | 2        | 0.49%   |
| Athens         | 2        | 0.49%   |
| Assen          | 2        | 0.49%   |
| Antwerp        | 2        | 0.49%   |
| Amsterdam      | 2        | 0.49%   |
| Allen          | 2        | 0.49%   |
| Zurich         | 1        | 0.25%   |
| Zaporizhzhya   | 1        | 0.25%   |
| Yakutsk        | 1        | 0.25%   |
| Woodstock      | 1        | 0.25%   |
| Woodbine       | 1        | 0.25%   |
| Winnipeg       | 1        | 0.25%   |
| Wetzikon       | 1        | 0.25%   |
| Westlake       | 1        | 0.25%   |
| Westerhoven    | 1        | 0.25%   |
| West Bromwich  | 1        | 0.25%   |
| Vladivostok    | 1        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 147      | 232    | 18.04%  |
| WDC                         | 141      | 215    | 17.3%   |
| Seagate                     | 137      | 203    | 16.81%  |
| Kingston                    | 61       | 71     | 7.48%   |
| SanDisk                     | 49       | 57     | 6.01%   |
| Crucial                     | 42       | 55     | 5.15%   |
| Toshiba                     | 40       | 45     | 4.91%   |
| Phison                      | 19       | 22     | 2.33%   |
| Hitachi                     | 15       | 19     | 1.84%   |
| Intel                       | 13       | 15     | 1.6%    |
| Micron/Crucial Technology   | 12       | 13     | 1.47%   |
| A-DATA Technology           | 11       | 12     | 1.35%   |
| China                       | 9        | 9      | 1.1%    |
| XPG                         | 7        | 8      | 0.86%   |
| PNY                         | 6        | 8      | 0.74%   |
| Corsair                     | 6        | 7      | 0.74%   |
| SPCC                        | 5        | 8      | 0.61%   |
| SK hynix                    | 5        | 5      | 0.61%   |
| Patriot                     | 5        | 6      | 0.61%   |
| Micron Technology           | 5        | 6      | 0.61%   |
| Unknown                     | 4        | 5      | 0.49%   |
| Silicon Motion              | 4        | 4      | 0.49%   |
| HGST                        | 4        | 7      | 0.49%   |
| Gigabyte Technology         | 4        | 7      | 0.49%   |
| SABRENT                     | 3        | 5      | 0.37%   |
| OCZ                         | 3        | 4      | 0.37%   |
| Intenso                     | 3        | 5      | 0.37%   |
| Hewlett-Packard             | 3        | 3      | 0.37%   |
| GOODRAM                     | 3        | 4      | 0.37%   |
| Team                        | 2        | 2      | 0.25%   |
| Realtek Semiconductor       | 2        | 2      | 0.25%   |
| Plextor                     | 2        | 3      | 0.25%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.25%   |
| KIOXIA-EXCERIA              | 2        | 2      | 0.25%   |
| KIOXIA                      | 2        | 3      | 0.25%   |
| KingDian                    | 2        | 2      | 0.25%   |
| ASMT                        | 2        | 2      | 0.25%   |
| Unknown                     | 2        | 2      | 0.25%   |
| XSTAR                       | 1        | 1      | 0.12%   |
| WXC-M3                      | 1        | 1      | 0.12%   |
| Verbatim                    | 1        | 1      | 0.12%   |
| USB                         | 1        | 1      | 0.12%   |
| Transcend                   | 1        | 1      | 0.12%   |
| Timetec                     | 1        | 1      | 0.12%   |
| T-FORCE                     | 1        | 1      | 0.12%   |
| SSK                         | 1        | 2      | 0.12%   |
| RSH-339                     | 1        | 1      | 0.12%   |
| Realtek                     | 1        | 1      | 0.12%   |
| Phison Electronics          | 1        | 2      | 0.12%   |
| Netac                       | 1        | 1      | 0.12%   |
| N300                        | 1        | 1      | 0.12%   |
| MyDigitalSSD                | 1        | 1      | 0.12%   |
| Maxtor                      | 1        | 3      | 0.12%   |
| LITEONIT                    | 1        | 1      | 0.12%   |
| LITEON                      | 1        | 1      | 0.12%   |
| Lite-On                     | 1        | 1      | 0.12%   |
| Leven                       | 1        | 1      | 0.12%   |
| KUIJIA                      | 1        | 1      | 0.12%   |
| KingSpec                    | 1        | 1      | 0.12%   |
| HP SSD S                    | 1        | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB          | 17       | 1.78%   |
| Seagate ST1000DM010-2EP102 1TB      | 15       | 1.57%   |
| Samsung SSD 850 EVO 250GB           | 14       | 1.47%   |
| Samsung NVMe SSD Drive 500GB        | 13       | 1.36%   |
| Kingston SA400S37240G 240GB SSD     | 13       | 1.36%   |
| Seagate ST500DM002-1BD142 500GB     | 12       | 1.26%   |
| SanDisk NVMe SSD Drive 1TB          | 12       | 1.26%   |
| Samsung NVMe SSD Drive 2TB          | 11       | 1.15%   |
| SanDisk NVMe SSD Drive 500GB        | 10       | 1.05%   |
| Samsung SSD 850 EVO 500GB           | 10       | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB      | 9        | 0.94%   |
| Kingston SA400S37120G 120GB SSD     | 8        | 0.84%   |
| Crucial CT240BX500SSD1 240GB        | 8        | 0.84%   |
| Crucial CT1000MX500SSD1 1TB         | 8        | 0.84%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7        | 0.73%   |
| Samsung SSD 870 QVO 2TB             | 7        | 0.73%   |
| Samsung SSD 860 EVO 500GB           | 7        | 0.73%   |
| Samsung NVMe SSD Drive 250GB        | 7        | 0.73%   |
| WDC WD40EFRX-68N32N0 4TB            | 6        | 0.63%   |
| WDC WD10EZEX-00WN4A0 1TB            | 6        | 0.63%   |
| Samsung SSD 850 EVO 1TB             | 6        | 0.63%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 6        | 0.63%   |
| Crucial CT500MX500SSD1 500GB        | 6        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB      | 5        | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB      | 5        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB      | 5        | 0.52%   |
| Samsung SSD 870 QVO 1TB             | 5        | 0.52%   |
| Samsung SSD 840 EVO 250GB           | 5        | 0.52%   |
| Phison NVMe SSD Drive 1024GB        | 5        | 0.52%   |
| Kingston SA400S37480G 480GB SSD     | 5        | 0.52%   |
| Crucial CT480BX500SSD1 480GB        | 5        | 0.52%   |
| Crucial CT2000MX500SSD1 2TB         | 5        | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4        | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 4        | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 0.42%   |
| WDC WD10EZEX-60M2NA0 1TB            | 4        | 0.42%   |
| WDC WD10EZEX-08M2NA0 1TB            | 4        | 0.42%   |
| Toshiba HDWD110 1TB                 | 4        | 0.42%   |
| Seagate ST3500418AS 500GB           | 4        | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB      | 4        | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 0.42%   |
| Seagate Expansion 500GB             | 4        | 0.42%   |
| Seagate Backup+ Hub BK 8TB          | 4        | 0.42%   |
| Samsung SSD 980 PRO 1TB             | 4        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB        | 4        | 0.42%   |
| Samsung SSD 970 EVO 250GB           | 4        | 0.42%   |
| Samsung SSD 870 EVO 500GB           | 4        | 0.42%   |
| Samsung SSD 870 EVO 1TB             | 4        | 0.42%   |
| Samsung NVMe SSD Drive 512GB        | 4        | 0.42%   |
| Micron/Crucial NVMe SSD Drive 500GB | 4        | 0.42%   |
| Kingston NVMe SSD Drive 500GB       | 4        | 0.42%   |
| Crucial CT250MX500SSD1 250GB        | 4        | 0.42%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 3        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.31%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 3        | 0.31%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 3        | 0.31%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 3        | 0.31%   |
| WDC WD10EZEX-60WN4A0 1TB            | 3        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 132      | 193    | 41.12%  |
| WDC                 | 118      | 178    | 36.76%  |
| Toshiba             | 31       | 33     | 9.66%   |
| Hitachi             | 15       | 19     | 4.67%   |
| Samsung Electronics | 8        | 11     | 2.49%   |
| HGST                | 4        | 7      | 1.25%   |
| SABRENT             | 3        | 5      | 0.93%   |
| ASMT                | 2        | 2      | 0.62%   |
| USB                 | 1        | 1      | 0.31%   |
| Unknown             | 1        | 1      | 0.31%   |
| RSH-339             | 1        | 1      | 0.31%   |
| Maxtor              | 1        | 3      | 0.31%   |
| Intenso             | 1        | 1      | 0.31%   |
| Hewlett-Packard     | 1        | 1      | 0.31%   |
| Fujitsu             | 1        | 1      | 0.31%   |
| ASMT106x            | 1        | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 81       | 112    | 27.74%  |
| Kingston            | 43       | 50     | 14.73%  |
| Crucial             | 39       | 52     | 13.36%  |
| WDC                 | 22       | 28     | 7.53%   |
| SanDisk             | 21       | 21     | 7.19%   |
| China               | 9        | 9      | 3.08%   |
| A-DATA Technology   | 7        | 7      | 2.4%    |
| PNY                 | 6        | 8      | 2.05%   |
| Intel               | 6        | 7      | 2.05%   |
| SPCC                | 5        | 8      | 1.71%   |
| Patriot             | 5        | 6      | 1.71%   |
| Toshiba             | 4        | 4      | 1.37%   |
| Seagate             | 4        | 4      | 1.37%   |
| Gigabyte Technology | 4        | 7      | 1.37%   |
| Corsair             | 4        | 4      | 1.37%   |
| OCZ                 | 3        | 4      | 1.03%   |
| Micron Technology   | 3        | 3      | 1.03%   |
| GOODRAM             | 3        | 4      | 1.03%   |
| Team                | 2        | 2      | 0.68%   |
| Plextor             | 2        | 3      | 0.68%   |
| KingDian            | 2        | 2      | 0.68%   |
| Intenso             | 2        | 4      | 0.68%   |
| XSTAR               | 1        | 1      | 0.34%   |
| Verbatim            | 1        | 1      | 0.34%   |
| Transcend           | 1        | 1      | 0.34%   |
| Timetec             | 1        | 1      | 0.34%   |
| SK hynix            | 1        | 1      | 0.34%   |
| Netac               | 1        | 1      | 0.34%   |
| MyDigitalSSD        | 1        | 1      | 0.34%   |
| LITEONIT            | 1        | 1      | 0.34%   |
| LITEON              | 1        | 1      | 0.34%   |
| Leven               | 1        | 1      | 0.34%   |
| KUIJIA              | 1        | 1      | 0.34%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.34%   |
| KingSpec            | 1        | 1      | 0.34%   |
| Drevo               | 1        | 1      | 0.34%   |
| Apacer              | 1        | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 253      | 458    | 36.35%  |
| SSD     | 234      | 364    | 33.62%  |
| NVMe    | 195      | 277    | 28.02%  |
| Unknown | 14       | 18     | 2.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 345      | 794    | 60.21%  |
| NVMe | 195      | 276    | 34.03%  |
| SAS  | 33       | 47     | 5.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 236      | 390    | 43.54%  |
| 0.51-1.0   | 162      | 229    | 29.89%  |
| 1.01-2.0   | 68       | 99     | 12.55%  |
| 3.01-4.0   | 37       | 51     | 6.83%   |
| 4.01-10.0  | 19       | 29     | 3.51%   |
| 2.01-3.0   | 18       | 20     | 3.32%   |
| 10.01-20.0 | 2        | 4      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 76       | 18.72%  |
| 501-1000       | 75       | 18.47%  |
| 1001-2000      | 74       | 18.23%  |
| 251-500        | 57       | 14.04%  |
| 2001-3000      | 39       | 9.61%   |
| 101-250        | 37       | 9.11%   |
| 1-20           | 17       | 4.19%   |
| Unknown        | 16       | 3.94%   |
| 51-100         | 10       | 2.46%   |
| 21-50          | 5        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 77       | 18.55%  |
| 21-50          | 57       | 13.73%  |
| 101-250        | 48       | 11.57%  |
| 51-100         | 47       | 11.33%  |
| 251-500        | 46       | 11.08%  |
| 1001-2000      | 44       | 10.6%   |
| 501-1000       | 43       | 10.36%  |
| More than 3000 | 24       | 5.78%   |
| Unknown        | 16       | 3.86%   |
| 2001-3000      | 13       | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 4        | 6      | 9.09%   |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 3      | 6.82%   |
| Seagate ST3500418AS 500GB           | 2        | 2      | 4.55%   |
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 4.55%   |
| Intel SSDSC2CT120A3 120GB           | 2        | 3      | 4.55%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 1      | 2.27%   |
| WDC WD3200AAKS-75B3A0 320GB         | 1        | 1      | 2.27%   |
| WDC WD30EZRX-00SPEB0 3TB            | 1        | 1      | 2.27%   |
| WDC WD2500AAKX-753CA1 250GB         | 1        | 1      | 2.27%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 2.27%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 2.27%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 2.27%   |
| WDC WD10EARS-22Y5B1 1TB             | 1        | 1      | 2.27%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 2.27%   |
| WDC WD10EADS-65M2B1 1TB             | 1        | 1      | 2.27%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1        | 2      | 2.27%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1      | 2.27%   |
| Toshiba MQ01ABD050 500GB            | 1        | 2      | 2.27%   |
| Toshiba MK3275GSX 320GB             | 1        | 1      | 2.27%   |
| Toshiba DT01ACA100 1TB              | 1        | 1      | 2.27%   |
| SPCC Solid State Disk 1TB           | 1        | 2      | 2.27%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 2.27%   |
| Seagate ST500LM030-2E717D 500GB     | 1        | 1      | 2.27%   |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1      | 2.27%   |
| Seagate ST32000542AS 2TB            | 1        | 2      | 2.27%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 2.27%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1      | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 870 EVO 2TB | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 850 EVO 1TB | 1        | 1      | 2.27%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 2.27%   |
| Samsung Electronics HD501LJ 500GB   | 1        | 4      | 2.27%   |
| Kingston SUV400S37480G 480GB SSD    | 1        | 1      | 2.27%   |
| Hitachi HTS725032A9A364 320GB       | 1        | 1      | 2.27%   |
| Hitachi HDS721010CLA332 1TB         | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 28.57%  |
| WDC                 | 11       | 13     | 26.19%  |
| Samsung Electronics | 9        | 12     | 21.43%  |
| Toshiba             | 4        | 5      | 9.52%   |
| Intel               | 2        | 3      | 4.76%   |
| Hitachi             | 2        | 2      | 4.76%   |
| SPCC                | 1        | 2      | 2.38%   |
| Kingston            | 1        | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 36.36%  |
| WDC                 | 11       | 13     | 33.33%  |
| Toshiba             | 4        | 5      | 12.12%  |
| Samsung Electronics | 4        | 7      | 12.12%  |
| Hitachi             | 2        | 2      | 6.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 43     | 78.05%  |
| SSD  | 9        | 11     | 21.95%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 252      | 696    | 56.25%  |
| Works    | 154      | 365    | 34.38%  |
| Malfunc  | 41       | 54     | 9.15%   |
| Failed   | 1        | 2      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 216      | 32.58%  |
| AMD                           | 178      | 26.85%  |
| Samsung Electronics           | 83       | 12.52%  |
| SanDisk                       | 34       | 5.13%   |
| ASMedia Technology            | 28       | 4.22%   |
| Phison Electronics            | 23       | 3.47%   |
| Kingston Technology Company   | 19       | 2.87%   |
| Micron/Crucial Technology     | 15       | 2.26%   |
| ADATA Technology              | 10       | 1.51%   |
| JMicron Technology            | 9        | 1.36%   |
| Marvell Technology Group      | 7        | 1.06%   |
| Toshiba America Info Systems  | 6        | 0.9%    |
| Silicon Motion                | 6        | 0.9%    |
| Nvidia                        | 5        | 0.75%   |
| SK hynix                      | 4        | 0.6%    |
| Realtek Semiconductor         | 3        | 0.45%   |
| Silicon Image                 | 2        | 0.3%    |
| Seagate Technology            | 2        | 0.3%    |
| Micron Technology             | 2        | 0.3%    |
| MAXIO Technology (Hangzhou)   | 2        | 0.3%    |
| KIOXIA                        | 2        | 0.3%    |
| VIA Technologies              | 1        | 0.15%   |
| Unknown                       | 1        | 0.15%   |
| ULi Electronics               | 1        | 0.15%   |
| Netac Technology              | 1        | 0.15%   |
| Lite-On Technology            | 1        | 0.15%   |
| Integrated Technology Express | 1        | 0.15%   |
| Broadcom / LSI                | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 98       | 12.48%  |
| AMD 500 Series Chipset SATA Controller                                                  | 47       | 5.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 45       | 5.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 5.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 4.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 27       | 3.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 22       | 2.8%    |
| Intel SATA Controller [RAID mode]                                                       | 18       | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.29%   |
| Phison E12 NVMe Controller                                                              | 17       | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 2.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16       | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 2.04%   |
| Samsung NVMe SSD Controller 980                                                         | 14       | 1.78%   |
| SanDisk Non-Volatile memory controller                                                  | 13       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 10       | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 9        | 1.15%   |
| Kingston Company Company Non-Volatile memory controller                                 | 8        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 0.89%   |
| Intel SSD 660P Series                                                                   | 6        | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.76%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.64%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 0.51%   |
| Micron/Crucial NVMe Controller                                                          | 4        | 0.51%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.51%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3        | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.38%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 3        | 0.38%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3        | 0.38%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 3        | 0.38%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.38%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.38%   |
| Intel Comet Lake PCH-H RAID                                                             | 3        | 0.38%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.38%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2        | 0.25%   |
| SK hynix Gold P31 SSD                                                                   | 2        | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 351      | 55.1%   |
| NVMe | 195      | 30.61%  |
| IDE  | 54       | 8.48%   |
| RAID | 35       | 5.49%   |
| SAS  | 2        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 213      | 53.52%  |
| AMD    | 185      | 46.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 19       | 4.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 15       | 3.75%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 12       | 3%      |
| AMD Ryzen 7 5800X 8-Core Processor          | 12       | 3%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 12       | 3%      |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 2%      |
| Intel Core i5-10400F CPU @ 2.90GHz          | 7        | 1.75%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 7        | 1.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 1.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 1.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 6        | 1.5%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 1.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.25%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 1.25%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.25%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1%      |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 1%      |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1%      |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 1%      |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1%      |
| AMD FX-6300 Six-Core Processor              | 4        | 1%      |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.75%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.75%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 0.75%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.75%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.75%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.75%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.75%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.75%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 0.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.75%   |
| Intel 12th Gen Core i9-12900K               | 3        | 0.75%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.75%   |
| Intel 12th Gen Core i7-12700                | 3        | 0.75%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.75%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3        | 0.75%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.75%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz         | 2        | 0.5%    |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 0.5%    |
| Intel Core i9-10900K CPU @ 3.70GHz          | 2        | 0.5%    |
| Intel Core i7-8086K CPU @ 4.00GHz           | 2        | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.5%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.5%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 0.5%    |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 0.5%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.5%    |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.5%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.5%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.5%    |
| Intel 12th Gen Core i5-12600K               | 2        | 0.5%    |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.5%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.5%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 70       | 17.54%  |
| Intel Core i5           | 66       | 16.54%  |
| Intel Core i7           | 55       | 13.78%  |
| AMD Ryzen 7             | 41       | 10.28%  |
| AMD Ryzen 9             | 33       | 8.27%   |
| Other                   | 24       | 6.02%   |
| Intel Core i3           | 19       | 4.76%   |
| Intel Xeon              | 16       | 4.01%   |
| AMD FX                  | 12       | 3.01%   |
| Intel Core i9           | 9        | 2.26%   |
| Intel Core 2 Duo        | 9        | 2.26%   |
| Intel Core 2 Quad       | 4        | 1%      |
| AMD Phenom II X4        | 4        | 1%      |
| Intel Pentium           | 3        | 0.75%   |
| Intel Atom              | 3        | 0.75%   |
| AMD Ryzen 3             | 3        | 0.75%   |
| AMD Phenom II X2        | 3        | 0.75%   |
| AMD A8                  | 3        | 0.75%   |
| Intel Celeron           | 2        | 0.5%    |
| AMD Athlon Dual Core    | 2        | 0.5%    |
| AMD Athlon 64 X2        | 2        | 0.5%    |
| AMD A6                  | 2        | 0.5%    |
| AMD A10                 | 2        | 0.5%    |
| Intel Pentium Silver    | 1        | 0.25%   |
| Intel Pentium Gold      | 1        | 0.25%   |
| Intel Pentium Dual-Core | 1        | 0.25%   |
| Intel Genuine           | 1        | 0.25%   |
| AMD Ryzen 7 PRO         | 1        | 0.25%   |
| AMD PRO A10             | 1        | 0.25%   |
| AMD Phenom II X6        | 1        | 0.25%   |
| AMD Opteron             | 1        | 0.25%   |
| AMD Athlon X4           | 1        | 0.25%   |
| AMD Athlon II X2        | 1        | 0.25%   |
| AMD Athlon 64           | 1        | 0.25%   |
| AMD Athlon              | 1        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 121      | 30.33%  |
| 6      | 107      | 26.82%  |
| 8      | 59       | 14.79%  |
| 2      | 52       | 13.03%  |
| 12     | 32       | 8.02%   |
| 16     | 11       | 2.76%   |
| 10     | 10       | 2.51%   |
| 3      | 5        | 1.25%   |
| 18     | 1        | 0.25%   |
| 1      | 1        | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 395      | 99.25%  |
| 2      | 3        | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 297      | 74.62%  |
| 1      | 101      | 25.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 398      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 39       | 9.77%   |
| 0x08701021 | 30       | 7.52%   |
| 0x0a201016 | 27       | 6.77%   |
| 0x906ea    | 19       | 4.76%   |
| 0x506e3    | 18       | 4.51%   |
| 0x0800820d | 18       | 4.51%   |
| Unknown    | 18       | 4.51%   |
| 0x306a9    | 17       | 4.26%   |
| 0x0a50000c | 16       | 4.01%   |
| 0x206a7    | 13       | 3.26%   |
| 0x90672    | 12       | 3.01%   |
| 0xa0655    | 10       | 2.51%   |
| 0xa0653    | 10       | 2.51%   |
| 0xa0671    | 8        | 2.01%   |
| 0x906e9    | 8        | 2.01%   |
| 0x1067a    | 8        | 2.01%   |
| 0x0a201009 | 8        | 2.01%   |
| 0x06000822 | 7        | 1.75%   |
| 0x906ed    | 6        | 1.5%    |
| 0x08101016 | 6        | 1.5%    |
| 0x306f2    | 5        | 1.25%   |
| 0x0a20120a | 5        | 1.25%   |
| 0x0a201205 | 5        | 1.25%   |
| 0x08701013 | 5        | 1.25%   |
| 0x6fb      | 4        | 1%      |
| 0x206d7    | 4        | 1%      |
| 0x0a50000d | 4        | 1%      |
| 0x08001138 | 4        | 1%      |
| 0x906ec    | 3        | 0.75%   |
| 0x906eb    | 3        | 0.75%   |
| 0x106e5    | 3        | 0.75%   |
| 0x10676    | 3        | 0.75%   |
| 0x0a201204 | 3        | 0.75%   |
| 0x08001137 | 3        | 0.75%   |
| 0x010000b6 | 3        | 0.75%   |
| 0x90675    | 2        | 0.5%    |
| 0x30661    | 2        | 0.5%    |
| 0x20655    | 2        | 0.5%    |
| 0x20652    | 2        | 0.5%    |
| 0x0a50000b | 2        | 0.5%    |
| 0x08600106 | 2        | 0.5%    |
| 0x08008204 | 2        | 0.5%    |
| 0x06001119 | 2        | 0.5%    |
| 0x06000817 | 2        | 0.5%    |
| 0x010000c8 | 2        | 0.5%    |
| 0x010000c6 | 2        | 0.5%    |
| 0x906c0    | 1        | 0.25%   |
| 0x6fd      | 1        | 0.25%   |
| 0x50657    | 1        | 0.25%   |
| 0x40661    | 1        | 0.25%   |
| 0x40651    | 1        | 0.25%   |
| 0x306e4    | 1        | 0.25%   |
| 0x106ca    | 1        | 0.25%   |
| 0x0a201006 | 1        | 0.25%   |
| 0x08108109 | 1        | 0.25%   |
| 0x08008206 | 1        | 0.25%   |
| 0x08001126 | 1        | 0.25%   |
| 0x0800111c | 1        | 0.25%   |
| 0x0700010b | 1        | 0.25%   |
| 0x06006705 | 1        | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 76       | 19.05%  |
| Haswell          | 48       | 12.03%  |
| KabyLake         | 39       | 9.77%   |
| Zen 2            | 37       | 9.27%   |
| Zen+             | 22       | 5.51%   |
| CometLake        | 21       | 5.26%   |
| Skylake          | 19       | 4.76%   |
| IvyBridge        | 18       | 4.51%   |
| SandyBridge      | 17       | 4.26%   |
| Zen              | 15       | 3.76%   |
| Alderlake Hybrid | 14       | 3.51%   |
| Piledriver       | 12       | 3.01%   |
| Penryn           | 11       | 2.76%   |
| K10              | 10       | 2.51%   |
| Icelake          | 8        | 2.01%   |
| K8 Hammer        | 5        | 1.25%   |
| Core             | 5        | 1.25%   |
| Westmere         | 4        | 1%      |
| Nehalem          | 3        | 0.75%   |
| Bulldozer        | 3        | 0.75%   |
| Bonnell          | 3        | 0.75%   |
| Steamroller      | 2        | 0.5%    |
| Excavator        | 2        | 0.5%    |
| Unknown          | 2        | 0.5%    |
| Tremont          | 1        | 0.25%   |
| K10 Llano        | 1        | 0.25%   |
| Jaguar           | 1        | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 168      | 38.98%  |
| Nvidia            | 167      | 38.75%  |
| Intel             | 95       | 22.04%  |
| ASPEED Technology | 1        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 28       | 6.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 4.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 18       | 4.04%   |
| AMD Cezanne                                                                 | 18       | 4.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 15       | 3.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 2.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 2.47%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 2.47%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 2.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 1.8%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 1.8%    |
| Intel HD Graphics 530                                                       | 7        | 1.57%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.57%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 7        | 1.57%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 1.57%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.12%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 1.12%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.9%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 0.67%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.67%   |
| Intel HD Graphics 630                                                       | 3        | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 0.67%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 0.67%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 3        | 0.67%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 2        | 0.45%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.45%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.45%   |
| Nvidia GK107 [GeForce GT 740]                                               | 2        | 0.45%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.45%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.45%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 0.45%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 151      | 37.94%  |
| 1 x Nvidia      | 148      | 37.19%  |
| 1 x Intel       | 68       | 17.09%  |
| Intel + Nvidia  | 11       | 2.76%   |
| 2 x AMD         | 8        | 2.01%   |
| AMD + Nvidia    | 5        | 1.26%   |
| Intel + AMD     | 3        | 0.75%   |
| 2 x Nvidia      | 2        | 0.5%    |
| Intel + 2 x AMD | 1        | 0.25%   |
| 1 x ASPEED      | 1        | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 287      | 71.39%  |
| Proprietary | 98       | 24.38%  |
| Unknown     | 17       | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 138      | 34.16%  |
| 7.01-8.0   | 65       | 16.09%  |
| 3.01-4.0   | 53       | 13.12%  |
| 1.01-2.0   | 43       | 10.64%  |
| 8.01-16.0  | 30       | 7.43%   |
| 0.51-1.0   | 30       | 7.43%   |
| 0.01-0.5   | 23       | 5.69%   |
| 5.01-6.0   | 19       | 4.7%    |
| 2.01-3.0   | 3        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 66       | 15.07%  |
| Goldstar             | 61       | 13.93%  |
| Dell                 | 50       | 11.42%  |
| AOC                  | 26       | 5.94%   |
| Acer                 | 26       | 5.94%   |
| BenQ                 | 24       | 5.48%   |
| Philips              | 23       | 5.25%   |
| Hewlett-Packard      | 23       | 5.25%   |
| Ancor Communications | 18       | 4.11%   |
| ViewSonic            | 14       | 3.2%    |
| Lenovo               | 10       | 2.28%   |
| Iiyama               | 10       | 2.28%   |
| ASUSTek Computer     | 9        | 2.05%   |
| Gigabyte Technology  | 8        | 1.83%   |
| Sceptre Tech         | 6        | 1.37%   |
| MSI                  | 6        | 1.37%   |
| Sony                 | 3        | 0.68%   |
| NEC Computers        | 3        | 0.68%   |
| Mi                   | 3        | 0.68%   |
| HannStar             | 3        | 0.68%   |
| Eizo                 | 3        | 0.68%   |
| Vizio                | 2        | 0.46%   |
| Unknown              | 2        | 0.46%   |
| SGT                  | 2        | 0.46%   |
| RTK                  | 2        | 0.46%   |
| Mitsubishi           | 2        | 0.46%   |
| Marantz              | 2        | 0.46%   |
| HUAWEI               | 2        | 0.46%   |
| Westinghouse         | 1        | 0.23%   |
| SKK                  | 1        | 0.23%   |
| Planar               | 1        | 0.23%   |
| Pixio                | 1        | 0.23%   |
| Panasonic            | 1        | 0.23%   |
| Packard Bell         | 1        | 0.23%   |
| ONN                  | 1        | 0.23%   |
| Onkyo                | 1        | 0.23%   |
| NEX                  | 1        | 0.23%   |
| MIT                  | 1        | 0.23%   |
| Medion               | 1        | 0.23%   |
| LDLC                 | 1        | 0.23%   |
| Insignia             | 1        | 0.23%   |
| INS                  | 1        | 0.23%   |
| HVR                  | 1        | 0.23%   |
| Hitachi              | 1        | 0.23%   |
| Gateway              | 1        | 0.23%   |
| Fujitsu Siemens      | 1        | 0.23%   |
| FOX                  | 1        | 0.23%   |
| Element              | 1        | 0.23%   |
| DSC                  | 1        | 0.23%   |
| DMG                  | 1        | 0.23%   |
| Denver               | 1        | 0.23%   |
| CLB                  | 1        | 0.23%   |
| CHD                  | 1        | 0.23%   |
| Belinea              | 1        | 0.23%   |
| BDS                  | 1        | 0.23%   |
| AU Optronics         | 1        | 0.23%   |
| AGO                  | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 6        | 1.28%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                 | 4        | 0.85%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch  | 3        | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch  | 3        | 0.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch  | 3        | 0.64%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                   | 3        | 0.64%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                | 3        | 0.64%   |
| Goldstar LG ULTRAGEAR GSM774B 3440x1440 800x330mm 34.1-inch        | 3        | 0.64%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch         | 3        | 0.64%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch    | 3        | 0.64%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch   | 3        | 0.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch          | 2        | 0.43%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 560x300mm 25.0-inch     | 2        | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch  | 2        | 0.43%   |
| Samsung Electronics S34J55x SAM0F72 1720x1440                      | 2        | 0.43%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch | 2        | 0.43%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch            | 2        | 0.43%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch            | 2        | 0.43%   |
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch               | 2        | 0.43%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch           | 2        | 0.43%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch         | 2        | 0.43%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch               | 2        | 0.43%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch            | 2        | 0.43%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 2        | 0.43%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch              | 2        | 0.43%   |
| Dell U2414H DELA0A2 1920x1080 527x296mm 23.8-inch                  | 2        | 0.43%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                 | 2        | 0.43%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                  | 2        | 0.43%   |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                    | 2        | 0.43%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                   | 2        | 0.43%   |
| Acer XG270HU ACR0414 2560x1440 598x336mm 27.0-inch                 | 2        | 0.43%   |
| Westinghouse EW32S5KW WDT1B8B 1366x768 1150x650mm 52.0-inch        | 1        | 0.21%   |
| Vizio M55Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch               | 1        | 0.21%   |
| Vizio E321VL VIZ0067 1920x1080 698x393mm 31.5-inch                 | 1        | 0.21%   |
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch            | 1        | 0.21%   |
| ViewSonic XG2705-2K VSCD73A 2560x1440 597x336mm 27.0-inch          | 1        | 0.21%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch      | 1        | 0.21%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch         | 1        | 0.21%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch      | 1        | 0.21%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch         | 1        | 0.21%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch      | 1        | 0.21%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch             | 1        | 0.21%   |
| ViewSonic VX2245wm VSCBB1E 1680x1050 474x296mm 22.0-inch           | 1        | 0.21%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch      | 1        | 0.21%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch      | 1        | 0.21%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch       | 1        | 0.21%   |
| ViewSonic LCD Monitor VSC692F 1920x1080 480x270mm 21.7-inch        | 1        | 0.21%   |
| ViewSonic LCD Monitor VA2226w-3 1680x1050                          | 1        | 0.21%   |
| Sony TV SNY9402 1920x1080                                          | 1        | 0.21%   |
| Sony TV SNY6F02 1360x768                                           | 1        | 0.21%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                 | 1        | 0.21%   |
| SKK SKK SKK0001 1920x1080 708x398mm 32.0-inch                      | 1        | 0.21%   |
| SGT Monitor SGT2700 2560x1440 601x329mm 27.0-inch                  | 1        | 0.21%   |
| SGT LM156LCFL_03 SGT1560 1920x1080 345x194mm 15.6-inch             | 1        | 0.21%   |
| Sceptre Tech Sceptre J20 SPT080D 1600x900 435x237mm 19.5-inch      | 1        | 0.21%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch     | 1        | 0.21%   |
| Sceptre Tech E225W-19206C SPT2261 1920x1080 521x293mm 23.5-inch    | 1        | 0.21%   |
| Sceptre Tech C32 SPT0CB3 1920x1080 544x303mm 24.5-inch             | 1        | 0.21%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch  | 1        | 0.21%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch  | 1        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 203      | 47.32%  |
| 2560x1440 (QHD)    | 58       | 13.52%  |
| 3840x2160 (4K)     | 52       | 12.12%  |
| 3440x1440          | 25       | 5.83%   |
| 1366x768 (WXGA)    | 18       | 4.2%    |
| 1280x1024 (SXGA)   | 14       | 3.26%   |
| 1680x1050 (WSXGA+) | 12       | 2.8%    |
| 1600x900 (HD+)     | 8        | 1.86%   |
| 2560x1080          | 7        | 1.63%   |
| 1920x1200 (WUXGA)  | 6        | 1.4%    |
| 1440x900 (WXGA+)   | 5        | 1.17%   |
| 1360x768           | 4        | 0.93%   |
| 3840x1080          | 3        | 0.7%    |
| 1920x540           | 3        | 0.7%    |
| 1600x1200          | 3        | 0.7%    |
| 2288x1287          | 2        | 0.47%   |
| 3840x1600          | 1        | 0.23%   |
| 2560x1600          | 1        | 0.23%   |
| 2200x1650          | 1        | 0.23%   |
| 2160x1200          | 1        | 0.23%   |
| 1640x2048          | 1        | 0.23%   |
| 1024x768 (XGA)     | 1        | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 90       | 20.13%  |
| 24      | 68       | 15.21%  |
| 23      | 57       | 12.75%  |
| 21      | 50       | 11.19%  |
| 31      | 37       | 8.28%   |
| 34      | 26       | 5.82%   |
| 18      | 18       | 4.03%   |
| 22      | 12       | 2.68%   |
| 20      | 11       | 2.46%   |
| 32      | 9        | 2.01%   |
| 19      | 9        | 2.01%   |
| Unknown | 8        | 1.79%   |
| 72      | 6        | 1.34%   |
| 17      | 5        | 1.12%   |
| 48      | 4        | 0.89%   |
| 54      | 3        | 0.67%   |
| 40      | 3        | 0.67%   |
| 25      | 3        | 0.67%   |
| 142     | 2        | 0.45%   |
| 100     | 2        | 0.45%   |
| 84      | 2        | 0.45%   |
| 42      | 2        | 0.45%   |
| 29      | 2        | 0.45%   |
| 26      | 2        | 0.45%   |
| 15      | 2        | 0.45%   |
| 75      | 1        | 0.22%   |
| 69      | 1        | 0.22%   |
| 52      | 1        | 0.22%   |
| 49      | 1        | 0.22%   |
| 46      | 1        | 0.22%   |
| 43      | 1        | 0.22%   |
| 39      | 1        | 0.22%   |
| 38      | 1        | 0.22%   |
| 37      | 1        | 0.22%   |
| 36      | 1        | 0.22%   |
| 35      | 1        | 0.22%   |
| 28      | 1        | 0.22%   |
| 13      | 1        | 0.22%   |
| 12      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 195      | 45.35%  |
| 401-500        | 88       | 20.47%  |
| 601-700        | 51       | 11.86%  |
| 701-800        | 36       | 8.37%   |
| 1501-2000      | 10       | 2.33%   |
| 351-400        | 9        | 2.09%   |
| 301-350        | 9        | 2.09%   |
| 1001-1500      | 9        | 2.09%   |
| Unknown        | 8        | 1.86%   |
| 801-900        | 6        | 1.4%    |
| More than 2000 | 4        | 0.93%   |
| 901-1000       | 4        | 0.93%   |
| 201-300        | 1        | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 312      | 78%     |
| 21/9    | 30       | 7.5%    |
| 16/10   | 29       | 7.25%   |
| 5/4     | 12       | 3%      |
| 4/3     | 5        | 1.25%   |
| 32/9    | 3        | 0.75%   |
| 6/5     | 2        | 0.5%    |
| 1.00    | 2        | 0.5%    |
| Unknown | 2        | 0.5%    |
| 3/2     | 1        | 0.25%   |
| 1.96    | 1        | 0.25%   |
| 0.80    | 1        | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 144      | 33.18%  |
| 301-350        | 92       | 21.2%   |
| 351-500        | 74       | 17.05%  |
| 151-200        | 40       | 9.22%   |
| 251-300        | 20       | 4.61%   |
| More than 1000 | 19       | 4.38%   |
| 141-150        | 19       | 4.38%   |
| 501-1000       | 14       | 3.23%   |
| Unknown        | 8        | 1.84%   |
| 101-110        | 2        | 0.46%   |
| 81-90          | 1        | 0.23%   |
| 71-80          | 1        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 246      | 58.57%  |
| 101-120 | 111      | 26.43%  |
| 121-160 | 26       | 6.19%   |
| 1-50    | 17       | 4.05%   |
| 161-240 | 12       | 2.86%   |
| Unknown | 8        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 291      | 72.75%  |
| 2     | 79       | 19.75%  |
| 0     | 16       | 4%      |
| 3     | 12       | 3%      |
| 4     | 2        | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 241      | 40.5%   |
| Intel                             | 229      | 38.49%  |
| Qualcomm Atheros                  | 22       | 3.7%    |
| TP-Link                           | 10       | 1.68%   |
| Broadcom                          | 10       | 1.68%   |
| Qualcomm Atheros Communications   | 9        | 1.51%   |
| MediaTek                          | 9        | 1.51%   |
| Ralink Technology                 | 7        | 1.18%   |
| Microsoft                         | 7        | 1.18%   |
| Realtek                           | 5        | 0.84%   |
| Nvidia                            | 5        | 0.84%   |
| Xiaomi                            | 4        | 0.67%   |
| Ralink                            | 4        | 0.67%   |
| Aquantia                          | 4        | 0.67%   |
| ASUSTek Computer                  | 3        | 0.5%    |
| Mellanox Technologies             | 2        | 0.34%   |
| Marvell Technology Group          | 2        | 0.34%   |
| ASIX Electronics                  | 2        | 0.34%   |
| Apple                             | 2        | 0.34%   |
| Sundance Technology Inc / IC Plus | 1        | 0.17%   |
| Sierra Wireless                   | 1        | 0.17%   |
| Samsung Electronics               | 1        | 0.17%   |
| QNAP System                       | 1        | 0.17%   |
| PLANEX                            | 1        | 0.17%   |
| NetGear                           | 1        | 0.17%   |
| Motorola PCS                      | 1        | 0.17%   |
| MicroPython                       | 1        | 0.17%   |
| LSI                               | 1        | 0.17%   |
| Lenovo                            | 1        | 0.17%   |
| InterBiometrics                   | 1        | 0.17%   |
| HMD Global                        | 1        | 0.17%   |
| Google                            | 1        | 0.17%   |
| Edimax Technology                 | 1        | 0.17%   |
| Davicom Semiconductor             | 1        | 0.17%   |
| Conexant Systems                  | 1        | 0.17%   |
| Broadcom Limited                  | 1        | 0.17%   |
| Belkin Components                 | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 163      | 23.45%  |
| Intel Wi-Fi 6 AX200                                                 | 55       | 7.91%   |
| Realtek RTL8125 2.5GbE Controller                                   | 43       | 6.19%   |
| Intel I211 Gigabit Network Connection                               | 41       | 5.9%    |
| Intel Ethernet Controller I225-V                                    | 34       | 4.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 16       | 2.3%    |
| Intel Ethernet Connection (2) I219-V                                | 16       | 2.3%    |
| Intel Ethernet Connection (7) I219-V                                | 13       | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 1.58%   |
| Intel Ethernet Connection I217-LM                                   | 10       | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 10       | 1.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 8        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                                | 8        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 7        | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                     | 7        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                               | 7        | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 7        | 1.01%   |
| Intel Wireless-AC 9260                                              | 6        | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 6        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 5        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 5        | 0.72%   |
| Realtek 802.11ac NIC                                                | 5        | 0.72%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 0.72%   |
| Intel 82579V Gigabit Network Connection                             | 5        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 4        | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 4        | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4        | 0.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 4        | 0.58%   |
| Realtek 802.11ac NIC                                                | 4        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 4        | 0.58%   |
| Intel Wireless 8265 / 8275                                          | 4        | 0.58%   |
| Intel Ethernet Connection I217-V                                    | 4        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.58%   |
| Intel 82574L Gigabit Network Connection                             | 4        | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 3        | 0.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3        | 0.43%   |
| Nvidia MCP61 Ethernet                                               | 3        | 0.43%   |
| Microsoft XBOX ACC                                                  | 3        | 0.43%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 3        | 0.43%   |
| Intel Wireless 7265                                                 | 3        | 0.43%   |
| Intel Wireless 7260                                                 | 3        | 0.43%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 0.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 0.43%   |
| Intel 82583V Gigabit Network Connection                             | 3        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 3        | 0.43%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 2        | 0.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2        | 0.29%   |
| TP-Link TL-WN722N v2                                                | 2        | 0.29%   |
| TP-Link Archer T4U ver.3                                            | 2        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.29%   |
| Realtek Killer E3000 2.5GbE Controller                              | 2        | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 2        | 0.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 119      | 50.21%  |
| Realtek Semiconductor           | 42       | 17.72%  |
| TP-Link                         | 10       | 4.22%   |
| Qualcomm Atheros Communications | 9        | 3.8%    |
| Qualcomm Atheros                | 9        | 3.8%    |
| MediaTek                        | 9        | 3.8%    |
| Broadcom                        | 8        | 3.38%   |
| Ralink Technology               | 7        | 2.95%   |
| Microsoft                       | 7        | 2.95%   |
| Realtek                         | 5        | 2.11%   |
| Ralink                          | 4        | 1.69%   |
| ASUSTek Computer                | 2        | 0.84%   |
| Sierra Wireless                 | 1        | 0.42%   |
| PLANEX                          | 1        | 0.42%   |
| NetGear                         | 1        | 0.42%   |
| Edimax Technology               | 1        | 0.42%   |
| Broadcom Limited                | 1        | 0.42%   |
| Belkin Components               | 1        | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 55       | 23.21%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 16       | 6.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 10       | 4.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 8        | 3.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 7        | 2.95%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 7        | 2.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 7        | 2.95%   |
| Intel Wireless-AC 9260                                                               | 6        | 2.53%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 6        | 2.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 5        | 2.11%   |
| Realtek 802.11ac NIC                                                                 | 5        | 2.11%   |
| Ralink MT7601U Wireless Adapter                                                      | 5        | 2.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 4        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 4        | 1.69%   |
| Realtek 802.11ac NIC                                                                 | 4        | 1.69%   |
| Intel Wireless 8265 / 8275                                                           | 4        | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 3        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 1.27%   |
| Microsoft XBOX ACC                                                                   | 3        | 1.27%   |
| Microsoft Xbox 360 Wireless Adapter                                                  | 3        | 1.27%   |
| Intel Wireless 7265                                                                  | 3        | 1.27%   |
| Intel Wireless 7260                                                                  | 3        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 3        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 3        | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 2        | 0.84%   |
| TP-Link TL-WN722N v2                                                                 | 2        | 0.84%   |
| TP-Link Archer T4U ver.3                                                             | 2        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 2        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2        | 0.84%   |
| Intel Wireless 3165                                                                  | 2        | 0.84%   |
| Intel Wireless 3160                                                                  | 2        | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 2        | 0.84%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.42%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                  | 1        | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 0.42%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1        | 0.42%   |
| Sierra Wireless MC7700                                                               | 1        | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                             | 1        | 0.42%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1        | 0.42%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1        | 0.42%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.42%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 1        | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 0.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1        | 0.42%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 0.42%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                            | 1        | 0.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 1        | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 1        | 0.42%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1        | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 1        | 0.42%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1        | 0.42%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.42%   |
| Ralink RT5362 PCI 802.11n Wireless Network Adapter                                   | 1        | 0.42%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                            | 1        | 0.42%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1        | 0.42%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.42%   |
| Qualcomm Atheros AR5523                                                              | 1        | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1        | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 223      | 50.34%  |
| Intel                             | 174      | 39.28%  |
| Qualcomm Atheros                  | 15       | 3.39%   |
| Nvidia                            | 5        | 1.13%   |
| Xiaomi                            | 4        | 0.9%    |
| Aquantia                          | 4        | 0.9%    |
| Marvell Technology Group          | 2        | 0.45%   |
| Broadcom                          | 2        | 0.45%   |
| ASIX Electronics                  | 2        | 0.45%   |
| Apple                             | 2        | 0.45%   |
| Sundance Technology Inc / IC Plus | 1        | 0.23%   |
| Samsung Electronics               | 1        | 0.23%   |
| QNAP System                       | 1        | 0.23%   |
| Motorola PCS                      | 1        | 0.23%   |
| Mellanox Technologies             | 1        | 0.23%   |
| Lenovo                            | 1        | 0.23%   |
| HMD Global                        | 1        | 0.23%   |
| Google                            | 1        | 0.23%   |
| Davicom Semiconductor             | 1        | 0.23%   |
| ASUSTek Computer                  | 1        | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 163      | 35.98%  |
| Realtek RTL8125 2.5GbE Controller                                          | 43       | 9.49%   |
| Intel I211 Gigabit Network Connection                                      | 41       | 9.05%   |
| Intel Ethernet Controller I225-V                                           | 34       | 7.51%   |
| Intel Ethernet Connection (2) I219-V                                       | 16       | 3.53%   |
| Intel Ethernet Connection (7) I219-V                                       | 13       | 2.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 11       | 2.43%   |
| Intel Ethernet Connection I217-LM                                          | 10       | 2.21%   |
| Intel Ethernet Connection (2) I218-V                                       | 8        | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                                      | 7        | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 5        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                    | 5        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 4        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 4        | 0.88%   |
| Intel Ethernet Connection I217-V                                           | 4        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                      | 4        | 0.88%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.66%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 0.66%   |
| Intel 82583V Gigabit Network Connection                                    | 3        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 3        | 0.66%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]        | 3        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 2        | 0.44%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                                      | 2        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 2        | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2        | 0.44%   |
| Apple iPad 4/Mini1                                                         | 2        | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 0.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.22%   |
| QNAP System Pacific                                                        | 1        | 0.22%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.22%   |
| Nvidia CK804 Ethernet Controller                                           | 1        | 0.22%   |
| Motorola PCS Moto E (4) Plus                                               | 1        | 0.22%   |
| Mellanox MT27500 Family [ConnectX-3]                                       | 1        | 0.22%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                    | 1        | 0.22%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 1        | 0.22%   |
| Lenovo ThinkPad TBT 3 Dock                                                 | 1        | 0.22%   |
| Intel Ethernet Connection (5) I219-LM                                      | 1        | 0.22%   |
| Intel Ethernet Connection (14) I219-V                                      | 1        | 0.22%   |
| Intel Ethernet Connection (14) I219-LM                                     | 1        | 0.22%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.22%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1        | 0.22%   |
| Intel Ethernet Connection (10) I219-V                                      | 1        | 0.22%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.22%   |
| Intel 82578DC Gigabit Network Connection                                   | 1        | 0.22%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 393      | 62.98%  |
| WiFi     | 226      | 36.22%  |
| Modem    | 4        | 0.64%   |
| Unknown  | 1        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 300      | 71.09%  |
| WiFi     | 122      | 28.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 211      | 52.88%  |
| 2     | 161      | 40.35%  |
| 3     | 24       | 6.02%   |
| 0     | 2        | 0.5%    |
| 4     | 1        | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 287      | 71.57%  |
| Yes  | 114      | 28.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 111      | 56.63%  |
| Cambridge Silicon Radio         | 30       | 15.31%  |
| Realtek Semiconductor           | 17       | 8.67%   |
| ASUSTek Computer                | 16       | 8.16%   |
| MediaTek                        | 8        | 4.08%   |
| TP-Link                         | 4        | 2.04%   |
| Qualcomm Atheros Communications | 3        | 1.53%   |
| Apple                           | 3        | 1.53%   |
| Broadcom                        | 2        | 1.02%   |
| IMC Networks                    | 1        | 0.51%   |
| HTC (High Tech Computer)        | 1        | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 51       | 26.02%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 30       | 15.31%  |
| Realtek Bluetooth Radio                                              | 14       | 7.14%   |
| Intel AX210 Bluetooth                                                | 14       | 7.14%   |
| Intel Bluetooth wireless interface                                   | 13       | 6.63%   |
| Intel AX201 Bluetooth                                                | 12       | 6.12%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 10       | 5.1%    |
| MediaTek Wireless_Device                                             | 8        | 4.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 6        | 3.06%   |
| ASUS Bluetooth Radio                                                 | 5        | 2.55%   |
| TP-Link UB500 Adapter                                                | 4        | 2.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 2.04%   |
| ASUS ASUS USB-BT500                                                  | 4        | 2.04%   |
| Apple Bluetooth USB Host Controller                                  | 3        | 1.53%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2        | 1.02%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.51%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.51%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.51%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.51%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.51%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 1        | 0.51%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.51%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.51%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.51%   |
| ASUS BCM20702A0                                                      | 1        | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 224      | 28.87%  |
| Intel                       | 210      | 27.06%  |
| Nvidia                      | 164      | 21.13%  |
| C-Media Electronics         | 27       | 3.48%   |
| Logitech                    | 12       | 1.55%   |
| Texas Instruments           | 8        | 1.03%   |
| Creative Labs               | 8        | 1.03%   |
| JMTek                       | 7        | 0.9%    |
| Corsair                     | 7        | 0.9%    |
| XMOS                        | 6        | 0.77%   |
| Kingston Technology         | 6        | 0.77%   |
| Creative Technology         | 6        | 0.77%   |
| SteelSeries ApS             | 5        | 0.64%   |
| Plantronics                 | 5        | 0.64%   |
| Razer USA                   | 4        | 0.52%   |
| Focusrite-Novation          | 4        | 0.52%   |
| Blue Microphones            | 4        | 0.52%   |
| Samson Technologies         | 3        | 0.39%   |
| Realtek Semiconductor       | 3        | 0.39%   |
| Micro Star International    | 3        | 0.39%   |
| GN Netcom                   | 3        | 0.39%   |
| Generalplus Technology      | 3        | 0.39%   |
| Tenx Technology             | 2        | 0.26%   |
| Sony                        | 2        | 0.26%   |
| Schiit Audio                | 2        | 0.26%   |
| Native Instruments          | 2        | 0.26%   |
| Lenovo                      | 2        | 0.26%   |
| GYROCOM C&C                 | 2        | 0.26%   |
| Giga-Byte Technology        | 2        | 0.26%   |
| FiiO Electronics Technology | 2        | 0.26%   |
| ASUSTek Computer            | 2        | 0.26%   |
| Astro Gaming                | 2        | 0.26%   |
| Yamaha                      | 1        | 0.13%   |
| VIA Technologies            | 1        | 0.13%   |
| USB PnP Sound Device        | 1        | 0.13%   |
| USB MICROPHONE              | 1        | 0.13%   |
| Turtle Beach                | 1        | 0.13%   |
| Trust                       | 1        | 0.13%   |
| TerraTec Electronic         | 1        | 0.13%   |
| Sennheiser Communications   | 1        | 0.13%   |
| Samsung Electronics         | 1        | 0.13%   |
| RODE Microphones            | 1        | 0.13%   |
| ROCCAT                      | 1        | 0.13%   |
| Pro-Ject                    | 1        | 0.13%   |
| ONN                         | 1        | 0.13%   |
| Microdia                    | 1        | 0.13%   |
| Meridian                    | 1        | 0.13%   |
| M-Audio                     | 1        | 0.13%   |
| KORG                        | 1        | 0.13%   |
| iRiver                      | 1        | 0.13%   |
| Hangzhou Worlde             | 1        | 0.13%   |
| Goldvish                    | 1        | 0.13%   |
| FIFINE Microphones          | 1        | 0.13%   |
| FIFINE 683 Microphone       | 1        | 0.13%   |
| Elgato Systems              | 1        | 0.13%   |
| DSEA A/S                    | 1        | 0.13%   |
| Dell                        | 1        | 0.13%   |
| DCMT Technology             | 1        | 0.13%   |
| Cooler Master               | 1        | 0.13%   |
| Cisco Systems               | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 83       | 8.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 44       | 4.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35       | 3.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 30       | 3.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 29       | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28       | 3.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 26       | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20       | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 19       | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 1.94%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 1.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16       | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 1.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 1.51%   |
| AMD Navi 10 HDMI Audio                                                     | 13       | 1.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 1.4%    |
| Nvidia GP106 High Definition Audio Controller                              | 11       | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                              | 10       | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 10       | 1.08%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 10       | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 8        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.76%   |
| Nvidia GA102 High Definition Audio Controller                              | 7        | 0.76%   |
| Intel Comet Lake PCH-V cAVS                                                | 7        | 0.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 0.76%   |
| C-Media Electronics USB Audio Device                                       | 7        | 0.76%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 7        | 0.76%   |
| AMD FCH Azalia Controller                                                  | 7        | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.65%   |
| JMTek USB PnP Audio Device                                                 | 6        | 0.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 5        | 0.54%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 0.54%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5        | 0.54%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.54%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.43%   |
| Nvidia GF116 High Definition Audio Controller                              | 4        | 0.43%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 0.43%   |
| Intel Audio device                                                         | 4        | 0.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 0.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 0.43%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 0.43%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 4        | 0.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 0.43%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 3        | 0.32%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.32%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 38       | 20.11%  |
| G.Skill             | 29       | 15.34%  |
| Corsair             | 25       | 13.23%  |
| Crucial             | 19       | 10.05%  |
| Unknown             | 18       | 9.52%   |
| SK hynix            | 14       | 7.41%   |
| Samsung Electronics | 11       | 5.82%   |
| Micron Technology   | 10       | 5.29%   |
| A-DATA Technology   | 4        | 2.12%   |
| Team                | 3        | 1.59%   |
| Unknown             | 3        | 1.59%   |
| Patriot             | 2        | 1.06%   |
| AMD                 | 2        | 1.06%   |
| V-GeN               | 1        | 0.53%   |
| Smart               | 1        | 0.53%   |
| Silicon Power       | 1        | 0.53%   |
| Samsung 1           | 1        | 0.53%   |
| Ramaxel Technology  | 1        | 0.53%   |
| PUSKILL             | 1        | 0.53%   |
| PNY                 | 1        | 0.53%   |
| Nanya Technology    | 1        | 0.53%   |
| Mushkin             | 1        | 0.53%   |
| Goodram             | 1        | 0.53%   |
| A-TECH              | 1        | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 5        | 2.51%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3             | 3        | 1.51%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 3        | 1.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 3        | 1.51%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s     | 3        | 1.51%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s   | 3        | 1.51%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.51%   |
| Unknown                                                 | 3        | 1.51%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 1.01%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 2        | 1.01%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 2        | 1.01%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 2        | 1.01%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2        | 1.01%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s     | 2        | 1.01%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 2        | 1.01%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s       | 2        | 1.01%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 2        | 1.01%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 1.01%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 1.01%   |
| G.Skill RAM F4-3200C14-8GTZR 8192MB DIMM DDR4 3200MT/s  | 2        | 1.01%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1867MT/s | 2        | 1.01%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 2        | 1.01%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s           | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 800MT/s                     | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM                             | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s               | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2                        | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM                             | 1        | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                 | 1        | 0.5%    |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.5%    |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s            | 1        | 0.5%    |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s      | 1        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s     | 1        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s     | 1        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s      | 1        | 0.5%    |
| Smart RAM SH5641G8FH8N6TNSQG 8GB DIMM DDR3 1600MT/s     | 1        | 0.5%    |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.5%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.5%    |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.5%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s | 1        | 0.5%    |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 0.5%    |
| SK hynix RAM HMA82GR7AFR4N-UH 16GB RIMM DDR4 2133MT/s   | 1        | 0.5%    |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 0.5%    |
| SK hynix RAM HMA81GR7CJR8N-WM 8GB DIMM DDR4 2933MT/s    | 1        | 0.5%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s         | 1        | 0.5%    |
| Silicon Power RAM Module 8GB DIMM DDR4 3200MT/s         | 1        | 0.5%    |
| Samsung RAM Module 32GB DIMM DDR4 3200MT/s              | 1        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1        | 0.5%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.5%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 1        | 0.5%    |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 1        | 0.5%    |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s    | 1        | 0.5%    |
| Samsung RAM M378A1K43BB1-CPB 8192MB DIMM DDR4 2733MT/s  | 1        | 0.5%    |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s     | 1        | 0.5%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s    | 1        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 104      | 61.9%   |
| DDR3    | 43       | 25.6%   |
| Unknown | 14       | 8.33%   |
| DDR2    | 4        | 2.38%   |
| SDRAM   | 2        | 1.19%   |
| DDR     | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 156      | 94.55%  |
| SODIMM | 7        | 4.24%   |
| RIMM   | 2        | 1.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 70       | 39.77%  |
| 16384 | 46       | 26.14%  |
| 4096  | 30       | 17.05%  |
| 2048  | 16       | 9.09%   |
| 32768 | 9        | 5.11%   |
| 1024  | 5        | 2.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 33       | 18.44%  |
| 1600    | 33       | 18.44%  |
| 3600    | 20       | 11.17%  |
| 2133    | 15       | 8.38%   |
| 2667    | 7        | 3.91%   |
| 1333    | 7        | 3.91%   |
| 3000    | 5        | 2.79%   |
| 2933    | 5        | 2.79%   |
| 2400    | 5        | 2.79%   |
| 667     | 5        | 2.79%   |
| 3466    | 4        | 2.23%   |
| 1867    | 4        | 2.23%   |
| 3733    | 3        | 1.68%   |
| 3400    | 3        | 1.68%   |
| 2666    | 3        | 1.68%   |
| 800     | 3        | 1.68%   |
| 400     | 3        | 1.68%   |
| 3866    | 2        | 1.12%   |
| 2800    | 2        | 1.12%   |
| Unknown | 2        | 1.12%   |
| 5200    | 1        | 0.56%   |
| 4800    | 1        | 0.56%   |
| 3800    | 1        | 0.56%   |
| 3467    | 1        | 0.56%   |
| 3333    | 1        | 0.56%   |
| 3100    | 1        | 0.56%   |
| 3067    | 1        | 0.56%   |
| 2733    | 1        | 0.56%   |
| 2600    | 1        | 0.56%   |
| 2048    | 1        | 0.56%   |
| 1639    | 1        | 0.56%   |
| 1067    | 1        | 0.56%   |
| 1066    | 1        | 0.56%   |
| 333     | 1        | 0.56%   |
| 200     | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 37.5%   |
| Hewlett-Packard     | 4        | 25%     |
| Seiko Epson         | 1        | 6.25%   |
| Samsung Electronics | 1        | 6.25%   |
| Prolific Technology | 1        | 6.25%   |
| Kyocera             | 1        | 6.25%   |
| Graphtec America    | 1        | 6.25%   |
| Canon               | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson L300 Series           | 1        | 6.25%   |
| Samsung M2070 Series              | 1        | 6.25%   |
| Prolific PL2305 Parallel Port     | 1        | 6.25%   |
| Kyocera ECOSYS M5521cdw           | 1        | 6.25%   |
| HP Neverstop Laser 100x           | 1        | 6.25%   |
| HP Ink Tank 310 series            | 1        | 6.25%   |
| HP DeskJet 3700 series            | 1        | 6.25%   |
| HP DeskJet 3630 series            | 1        | 6.25%   |
| Graphtec America Graphtec Printer | 1        | 6.25%   |
| Canon CanoScan LiDE 300           | 1        | 6.25%   |
| Brother Printer                   | 1        | 6.25%   |
| Brother MFC-9330CDW               | 1        | 6.25%   |
| Brother HL-1110 series            | 1        | 6.25%   |
| Brother DCP-T510W                 | 1        | 6.25%   |
| Brother DCP-L2530DW series        | 1        | 6.25%   |
| Brother DCP-7055W                 | 1        | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 66.67%  |
| Seiko Epson | 2        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                                 | 2        | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 16.67%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 16.67%  |
| Canon CanoScan LiDE 220                                 | 1        | 16.67%  |
| Canon CanoScan LiDE 200                                 | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 42       | 43.3%   |
| Sunplus Innovation Technology | 10       | 10.31%  |
| Microsoft                     | 8        | 8.25%   |
| Lenovo                        | 4        | 4.12%   |
| KYE Systems (Mouse Systems)   | 4        | 4.12%   |
| Apple                         | 4        | 4.12%   |
| Realtek Semiconductor         | 3        | 3.09%   |
| Microdia                      | 3        | 3.09%   |
| Hewlett-Packard               | 2        | 2.06%   |
| Generalplus Technology        | 2        | 2.06%   |
| Creative Technology           | 2        | 2.06%   |
| Asuscom Network               | 2        | 2.06%   |
| webcam                        | 1        | 1.03%   |
| Samsung Electronics           | 1        | 1.03%   |
| Razer USA                     | 1        | 1.03%   |
| Polycom                       | 1        | 1.03%   |
| Jieli Technology              | 1        | 1.03%   |
| Intel                         | 1        | 1.03%   |
| Huawei Technologies           | 1        | 1.03%   |
| FPL-2053-191010               | 1        | 1.03%   |
| Cubeternet                    | 1        | 1.03%   |
| Chicony Electronics           | 1        | 1.03%   |
| Aveo Technology               | 1        | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 15       | 15.31%  |
| Sunplus HD 720P webcam                     | 4        | 4.08%   |
| Logitech Webcam C310                       | 3        | 3.06%   |
| Logitech Webcam C270                       | 3        | 3.06%   |
| Logitech HD Webcam C615                    | 3        | 3.06%   |
| Logitech C922 Pro Stream Webcam            | 3        | 3.06%   |
| Logitech C920 PRO HD Webcam                | 3        | 3.06%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 3.06%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 3        | 3.06%   |
| Apple iPhone 5/5C/5S/6/SE                  | 3        | 3.06%   |
| Sunplus Depstech webcam MIC                | 2        | 2.04%   |
| Realtek NexiGo N660P FHD Webcam            | 2        | 2.04%   |
| Microsoft LifeCam HD-3000                  | 2        | 2.04%   |
| Microsoft LifeCam Cinema                   | 2        | 2.04%   |
| Microdia USB 2.0 Camera                    | 2        | 2.04%   |
| Logitech HD Webcam C525                    | 2        | 2.04%   |
| Lenovo FHD Webcam Audio                    | 2        | 2.04%   |
| Generalplus GENERAL WEBCAM                 | 2        | 2.04%   |
| Asuscom Network HD 1080P PC-Camera         | 2        | 2.04%   |
| webcam webcam                              | 1        | 1.02%   |
| Sunplus Lihappe8 Webcam L0485A2SP          | 1        | 1.02%   |
| Sunplus ezcap U3 capture-04                | 1        | 1.02%   |
| Sunplus Canyon CNS-CWC5 Webcam             | 1        | 1.02%   |
| Sunplus 5Mega Webcam                       | 1        | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)    | 1        | 1.02%   |
| Realtek USB Camera                         | 1        | 1.02%   |
| Realtek Thronmax StreamGo Webcam           | 1        | 1.02%   |
| Razer USA Razer Kiyo Pro                   | 1        | 1.02%   |
| Polycom Poly Studio P5 webcam              | 1        | 1.02%   |
| Microsoft Xbox NUI Camera                  | 1        | 1.02%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 1        | 1.02%   |
| Microsoft LifeCam VX-5000                  | 1        | 1.02%   |
| Microsoft LifeCam VX-500 [1357]            | 1        | 1.02%   |
| Microdia Webcam Vitade AF                  | 1        | 1.02%   |
| Logitech Webcam C925e                      | 1        | 1.02%   |
| Logitech Webcam C200                       | 1        | 1.02%   |
| Logitech Webcam C110                       | 1        | 1.02%   |
| Logitech Webcam B500                       | 1        | 1.02%   |
| Logitech QuickCam Pro 9000                 | 1        | 1.02%   |
| Logitech QuickCam Communicate Deluxe       | 1        | 1.02%   |
| Logitech B525 HD Webcam                    | 1        | 1.02%   |
| Lenovo FULL HD 1080P Webcam                | 1        | 1.02%   |
| Lenovo 500 RGB Camera                      | 1        | 1.02%   |
| KYE Systems (Mouse Systems) FaceCam 1000X  | 1        | 1.02%   |
| Jieli USB PHY 2.0                          | 1        | 1.02%   |
| Intel RealSense 3D Camera (Front F200)     | 1        | 1.02%   |
| Huawei UVC Camera                          | 1        | 1.02%   |
| HP Webcam HD 2300                          | 1        | 1.02%   |
| HP HD-4110 Webcam                          | 1        | 1.02%   |
| FPL-2053-191010 T2 Webcam                  | 1        | 1.02%   |
| Cubeternet Live Streaming USB Device       | 1        | 1.02%   |
| Creative Live! Cam Sync 1080p V2           | 1        | 1.02%   |
| Creative Live! Cam Sync 1080p              | 1        | 1.02%   |
| Chicony FHD User Facing                    | 1        | 1.02%   |
| Aveo USB2.0 UVC PC Camera                  | 1        | 1.02%   |
| Apple iPod Touch 5.Gen [A1421]             | 1        | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 2        | 33.33%  |
| Yubico.com            | 1        | 16.67%  |
| Realtek Semiconductor | 1        | 16.67%  |
| OmniKey               | 1        | 16.67%  |
| Aktiv                 | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 33.33%  |
| Yubico.com Yubikey 4/5 CCID                            | 1        | 16.67%  |
| Realtek Semiconductor Smart Card Reader Interface      | 1        | 16.67%  |
| OmniKey CardMan 1021                                   | 1        | 16.67%  |
| Aktiv Rutoken lite                                     | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 334      | 83.29%  |
| 1     | 56       | 13.97%  |
| 2     | 8        | 2%      |
| 3     | 2        | 0.5%    |
| 4     | 1        | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 29       | 39.73%  |
| Graphics card            | 21       | 28.77%  |
| Multimedia controller    | 6        | 8.22%   |
| Unassigned class         | 4        | 5.48%   |
| Sound                    | 4        | 5.48%   |
| Modem                    | 2        | 2.74%   |
| Fingerprint reader       | 2        | 2.74%   |
| Wireless                 | 1        | 1.37%   |
| Firewire controller      | 1        | 1.37%   |
| Communication controller | 1        | 1.37%   |
| Camera                   | 1        | 1.37%   |
| Bluetooth                | 1        | 1.37%   |

