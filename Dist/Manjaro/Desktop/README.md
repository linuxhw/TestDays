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

Total: 4349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B650E-I GAMING... | [769bd9153a](https://linux-hardware.org/?probe=769bd9153a) | Jan 01, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [9c99c1bf71](https://linux-hardware.org/?probe=9c99c1bf71) | Dec 31, 2023 |
| ASRock        | B75M-DGS                    | [3a2df88d60](https://linux-hardware.org/?probe=3a2df88d60) | Dec 31, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| HP            | 8949 11                     | [1add0bc0e2](https://linux-hardware.org/?probe=1add0bc0e2) | Dec 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | [2f24e45b02](https://linux-hardware.org/?probe=2f24e45b02) | Dec 29, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [3bf93539f3](https://linux-hardware.org/?probe=3bf93539f3) | Dec 28, 2023 |
| ASUSTek       | H170-PRO                    | [969aa3e243](https://linux-hardware.org/?probe=969aa3e243) | Dec 26, 2023 |
| MSI           | H510M-A PRO                 | [0260c1a342](https://linux-hardware.org/?probe=0260c1a342) | Dec 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [25e443386a](https://linux-hardware.org/?probe=25e443386a) | Dec 26, 2023 |
| ASUSTek       | PRIME Z370-A II             | [2013c4457a](https://linux-hardware.org/?probe=2013c4457a) | Dec 26, 2023 |
| ASRock        | X670E Taichi                | [281602cb0e](https://linux-hardware.org/?probe=281602cb0e) | Dec 26, 2023 |
| MSI           | GF615M-P33                  | [9e99d63708](https://linux-hardware.org/?probe=9e99d63708) | Dec 25, 2023 |
| MSI           | H510M-A PRO                 | [9f369b34fa](https://linux-hardware.org/?probe=9f369b34fa) | Dec 24, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [cccb18ead9](https://linux-hardware.org/?probe=cccb18ead9) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | [d845a3492b](https://linux-hardware.org/?probe=d845a3492b) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | [a6e1fc3b29](https://linux-hardware.org/?probe=a6e1fc3b29) | Dec 24, 2023 |
| MSI           | PRO B650-S WIFI             | [c084478d6e](https://linux-hardware.org/?probe=c084478d6e) | Dec 24, 2023 |
| MSI           | H510M-A PRO                 | [fe19f4de86](https://linux-hardware.org/?probe=fe19f4de86) | Dec 23, 2023 |
| MSI           | B560M PRO                   | [3885df62ab](https://linux-hardware.org/?probe=3885df62ab) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| ASUSTek       | Maximus VI GENE             | [178aab1062](https://linux-hardware.org/?probe=178aab1062) | Dec 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [98298e164f](https://linux-hardware.org/?probe=98298e164f) | Dec 20, 2023 |
| HP            | 83E0                        | [8f41483d26](https://linux-hardware.org/?probe=8f41483d26) | Dec 19, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [df369cf5be](https://linux-hardware.org/?probe=df369cf5be) | Dec 19, 2023 |
| Lenovo        | 3704 SDK0K17763 WIN 1801... | [9a2472e628](https://linux-hardware.org/?probe=9a2472e628) | Dec 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [448a2dec7d](https://linux-hardware.org/?probe=448a2dec7d) | Dec 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ebfec06632](https://linux-hardware.org/?probe=ebfec06632) | Dec 17, 2023 |
| ASRock        | H310CM-HG4                  | [4e47d91bc7](https://linux-hardware.org/?probe=4e47d91bc7) | Dec 17, 2023 |
| Dell          | 0VHWTR A01                  | [78ef6792a1](https://linux-hardware.org/?probe=78ef6792a1) | Dec 16, 2023 |
| ASRock        | 760GM-HDV                   | [c1403f5d52](https://linux-hardware.org/?probe=c1403f5d52) | Dec 15, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [25b995fdda](https://linux-hardware.org/?probe=25b995fdda) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52ffec69ce](https://linux-hardware.org/?probe=52ffec69ce) | Dec 12, 2023 |
| Gigabyte      | Z97N-WIFI                   | [514227865f](https://linux-hardware.org/?probe=514227865f) | Dec 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2cfceea8dc](https://linux-hardware.org/?probe=2cfceea8dc) | Dec 12, 2023 |
| Gigabyte      | Z270-Gaming K3 2017-06-1... | [5292573e8d](https://linux-hardware.org/?probe=5292573e8d) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [098d790720](https://linux-hardware.org/?probe=098d790720) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [090ebbd9dd](https://linux-hardware.org/?probe=090ebbd9dd) | Dec 10, 2023 |
| ASRock        | B450 Gaming K4              | [581807905e](https://linux-hardware.org/?probe=581807905e) | Dec 10, 2023 |
| Dell          | 0NDYHG A01                  | [f7f70db230](https://linux-hardware.org/?probe=f7f70db230) | Dec 08, 2023 |
| ASRock        | B550M Steel Legend          | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| Unknown       | Unknown                     | [c652e80145](https://linux-hardware.org/?probe=c652e80145) | Dec 08, 2023 |
| Gigabyte      | B550M DS3H                  | [650771c55d](https://linux-hardware.org/?probe=650771c55d) | Dec 07, 2023 |
| Unknown       | Unknown                     | [1dd3b89bd1](https://linux-hardware.org/?probe=1dd3b89bd1) | Dec 07, 2023 |
| HP            | 83E0                        | [a4266f2a5e](https://linux-hardware.org/?probe=a4266f2a5e) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7d7cf8fd3d](https://linux-hardware.org/?probe=7d7cf8fd3d) | Dec 06, 2023 |
| ASRock        | B450 Pro4                   | [1d99a563c9](https://linux-hardware.org/?probe=1d99a563c9) | Dec 05, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [3a8de1659a](https://linux-hardware.org/?probe=3a8de1659a) | Dec 05, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [362161fd73](https://linux-hardware.org/?probe=362161fd73) | Dec 04, 2023 |
| Gigabyte      | Z97N-WIFI                   | [aeae361474](https://linux-hardware.org/?probe=aeae361474) | Dec 04, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [8b11ad9f77](https://linux-hardware.org/?probe=8b11ad9f77) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ae8ecce4bd](https://linux-hardware.org/?probe=ae8ecce4bd) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [0b017377f1](https://linux-hardware.org/?probe=0b017377f1) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [0338afa4db](https://linux-hardware.org/?probe=0338afa4db) | Dec 01, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| Unknown       | Unknown                     | [cd167c532c](https://linux-hardware.org/?probe=cd167c532c) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [bb6640572b](https://linux-hardware.org/?probe=bb6640572b) | Nov 30, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [a139e1830c](https://linux-hardware.org/?probe=a139e1830c) | Nov 29, 2023 |
| ASRock        | H310CM-HG4                  | [bd3a1b9c9a](https://linux-hardware.org/?probe=bd3a1b9c9a) | Nov 28, 2023 |
| Gigabyte      | A55M-DS2                    | [bb5c7bef3f](https://linux-hardware.org/?probe=bb5c7bef3f) | Nov 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [77e8b3479a](https://linux-hardware.org/?probe=77e8b3479a) | Nov 27, 2023 |
| HP            | 2820h                       | [e9bdfab0be](https://linux-hardware.org/?probe=e9bdfab0be) | Nov 27, 2023 |
| HP            | 2B36                        | [3e8b681ec7](https://linux-hardware.org/?probe=3e8b681ec7) | Nov 27, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [bb98eb3ce9](https://linux-hardware.org/?probe=bb98eb3ce9) | Nov 26, 2023 |
| ASRock        | N68C-S UCC                  | [a5b04f6fdb](https://linux-hardware.org/?probe=a5b04f6fdb) | Nov 24, 2023 |
| Apple         | Mac-F221BEC8                | [b11d29c96b](https://linux-hardware.org/?probe=b11d29c96b) | Nov 24, 2023 |
| MSI           | B550M PRO                   | [e834bc66b9](https://linux-hardware.org/?probe=e834bc66b9) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [2a14b62cf5](https://linux-hardware.org/?probe=2a14b62cf5) | Nov 24, 2023 |
| ASRock        | B450 Gaming K4              | [ee82d7417c](https://linux-hardware.org/?probe=ee82d7417c) | Nov 23, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [bc11e1264c](https://linux-hardware.org/?probe=bc11e1264c) | Nov 22, 2023 |
| Dell          | 0WPMFG A00                  | [9cf9520fc3](https://linux-hardware.org/?probe=9cf9520fc3) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [7a4e5e7709](https://linux-hardware.org/?probe=7a4e5e7709) | Nov 19, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [5368b237d8](https://linux-hardware.org/?probe=5368b237d8) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | [ece45e3b1c](https://linux-hardware.org/?probe=ece45e3b1c) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | [1f7e5feb84](https://linux-hardware.org/?probe=1f7e5feb84) | Nov 17, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [7af93dbd28](https://linux-hardware.org/?probe=7af93dbd28) | Nov 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [e57d2d64f5](https://linux-hardware.org/?probe=e57d2d64f5) | Nov 17, 2023 |
| Unknown       | Unknown                     | [90f5f3a274](https://linux-hardware.org/?probe=90f5f3a274) | Nov 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [a09eca53d5](https://linux-hardware.org/?probe=a09eca53d5) | Nov 14, 2023 |
| Gigabyte      | P35-DS3                     | [fac1d1b119](https://linux-hardware.org/?probe=fac1d1b119) | Nov 14, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [f29ef35eec](https://linux-hardware.org/?probe=f29ef35eec) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | [8599ff1b2c](https://linux-hardware.org/?probe=8599ff1b2c) | Nov 13, 2023 |
| ASUSTek       | Z87-A                       | [08f1651d1f](https://linux-hardware.org/?probe=08f1651d1f) | Nov 12, 2023 |
| Gigabyte      | H510M S2H V2                | [238ea043b4](https://linux-hardware.org/?probe=238ea043b4) | Nov 10, 2023 |
| Dell          | 04YP6J A02                  | [b7f860630b](https://linux-hardware.org/?probe=b7f860630b) | Nov 10, 2023 |
| ASRock        | B760M PG Riptide            | [6c0d3672d5](https://linux-hardware.org/?probe=6c0d3672d5) | Nov 10, 2023 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [10234424e1](https://linux-hardware.org/?probe=10234424e1) | Nov 09, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [14438106c9](https://linux-hardware.org/?probe=14438106c9) | Nov 09, 2023 |
| ASRock        | A320M-HDV R4.0              | [8ba89e650a](https://linux-hardware.org/?probe=8ba89e650a) | Nov 08, 2023 |
| HP            | 158B                        | [b8bd2429fa](https://linux-hardware.org/?probe=b8bd2429fa) | Nov 07, 2023 |
| MSI           | MAG B550 TORPEDO            | [fc34295ec7](https://linux-hardware.org/?probe=fc34295ec7) | Nov 07, 2023 |
| HP            | 8053                        | [c46468ecb6](https://linux-hardware.org/?probe=c46468ecb6) | Nov 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7152c7ed2c](https://linux-hardware.org/?probe=7152c7ed2c) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | [034b113ac8](https://linux-hardware.org/?probe=034b113ac8) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| HP            | 1998                        | [d454314b77](https://linux-hardware.org/?probe=d454314b77) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| MSI           | H110I PRO                   | [c335c71c4b](https://linux-hardware.org/?probe=c335c71c4b) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [8841ab599e](https://linux-hardware.org/?probe=8841ab599e) | Nov 04, 2023 |
| MSI           | B560M PRO                   | [903907b7c0](https://linux-hardware.org/?probe=903907b7c0) | Nov 04, 2023 |
| Lenovo        | 317E NOK                    | [1d038af880](https://linux-hardware.org/?probe=1d038af880) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [798cba826c](https://linux-hardware.org/?probe=798cba826c) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2c601304f7](https://linux-hardware.org/?probe=2c601304f7) | Nov 04, 2023 |
| HP            | 0B54h D                     | [574e5fd946](https://linux-hardware.org/?probe=574e5fd946) | Nov 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [44890192a1](https://linux-hardware.org/?probe=44890192a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | 0200DY A02                  | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| MSI           | B560M PRO                   | [adf6c161fa](https://linux-hardware.org/?probe=adf6c161fa) | Nov 02, 2023 |
| Unknown       | 1.0                         | [6265787d93](https://linux-hardware.org/?probe=6265787d93) | Nov 01, 2023 |
| ASUSTek       | PRIME B450M-A II            | [08ee10dc83](https://linux-hardware.org/?probe=08ee10dc83) | Nov 01, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [e03b553957](https://linux-hardware.org/?probe=e03b553957) | Nov 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [7b71031ba1](https://linux-hardware.org/?probe=7b71031ba1) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [3ab77e3324](https://linux-hardware.org/?probe=3ab77e3324) | Oct 31, 2023 |
| ASRock        | A320M-HDV R4.0              | [7941dfd8cf](https://linux-hardware.org/?probe=7941dfd8cf) | Oct 31, 2023 |
| ASRock        | B550M Steel Legend          | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | [6cafea6b4c](https://linux-hardware.org/?probe=6cafea6b4c) | Oct 30, 2023 |
| GEEKOM        | Mini IT12                   | [b9509f49f1](https://linux-hardware.org/?probe=b9509f49f1) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | [10af2377c2](https://linux-hardware.org/?probe=10af2377c2) | Oct 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | [80b9cb5e56](https://linux-hardware.org/?probe=80b9cb5e56) | Oct 28, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [52e07e7ffe](https://linux-hardware.org/?probe=52e07e7ffe) | Oct 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | [7610254116](https://linux-hardware.org/?probe=7610254116) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | [484d866dc6](https://linux-hardware.org/?probe=484d866dc6) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | [a619c8a955](https://linux-hardware.org/?probe=a619c8a955) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| MSI           | B450-A PRO                  | [e71634ac32](https://linux-hardware.org/?probe=e71634ac32) | Oct 26, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3a1039b4b6](https://linux-hardware.org/?probe=3a1039b4b6) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9cb0b1ec27](https://linux-hardware.org/?probe=9cb0b1ec27) | Oct 26, 2023 |
| ASUSTek       | Z170-P                      | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| HP            | 212B                        | [714373878e](https://linux-hardware.org/?probe=714373878e) | Oct 24, 2023 |
| HP            | 83EF                        | [9953e14c0a](https://linux-hardware.org/?probe=9953e14c0a) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| MSI           | Z390-A PRO                  | [48233204f6](https://linux-hardware.org/?probe=48233204f6) | Oct 23, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [07e8b4df09](https://linux-hardware.org/?probe=07e8b4df09) | Oct 23, 2023 |
| ASRock        | B760M PG Riptide            | [d1f12415b9](https://linux-hardware.org/?probe=d1f12415b9) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cb6130951a](https://linux-hardware.org/?probe=cb6130951a) | Oct 23, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [ce9770538c](https://linux-hardware.org/?probe=ce9770538c) | Oct 22, 2023 |
| Dell          | 09WH54 A01                  | [4211349cc4](https://linux-hardware.org/?probe=4211349cc4) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [67c6d6e482](https://linux-hardware.org/?probe=67c6d6e482) | Oct 21, 2023 |
| ASRock        | H97M Pro4                   | [04f6bc7f0c](https://linux-hardware.org/?probe=04f6bc7f0c) | Oct 21, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1ae8f16052](https://linux-hardware.org/?probe=1ae8f16052) | Oct 21, 2023 |
| ASUSTek       | PRIME B450M-K               | [a0b48d8a7e](https://linux-hardware.org/?probe=a0b48d8a7e) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [17f5bf3cef](https://linux-hardware.org/?probe=17f5bf3cef) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| MSI           | Z390-A PRO                  | [7fd0eeaeec](https://linux-hardware.org/?probe=7fd0eeaeec) | Oct 19, 2023 |
| Biostar       | A320MH                      | [e2c20a6c0c](https://linux-hardware.org/?probe=e2c20a6c0c) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-PRO              | [84517c1f4c](https://linux-hardware.org/?probe=84517c1f4c) | Oct 19, 2023 |
| Biostar       | A320MH                      | [62a3d049b2](https://linux-hardware.org/?probe=62a3d049b2) | Oct 18, 2023 |
| ASRock        | AB350 Pro4                  | [71eba7e232](https://linux-hardware.org/?probe=71eba7e232) | Oct 18, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5f780203e2](https://linux-hardware.org/?probe=5f780203e2) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [9b7bc3fc9d](https://linux-hardware.org/?probe=9b7bc3fc9d) | Oct 16, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [c976b314a2](https://linux-hardware.org/?probe=c976b314a2) | Oct 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [f71ad29f6a](https://linux-hardware.org/?probe=f71ad29f6a) | Oct 15, 2023 |
| Gigabyte      | A520M DS3H                  | [e79f4b834d](https://linux-hardware.org/?probe=e79f4b834d) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [ac840f060f](https://linux-hardware.org/?probe=ac840f060f) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | [d1386e080d](https://linux-hardware.org/?probe=d1386e080d) | Oct 12, 2023 |
| MSI           | B560M PRO                   | [3ad673132a](https://linux-hardware.org/?probe=3ad673132a) | Oct 12, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [17b8025f8d](https://linux-hardware.org/?probe=17b8025f8d) | Oct 11, 2023 |
| Lenovo        | 317E NOK                    | [618b7ebe59](https://linux-hardware.org/?probe=618b7ebe59) | Oct 11, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [e185192929](https://linux-hardware.org/?probe=e185192929) | Oct 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [a5c5f58ddb](https://linux-hardware.org/?probe=a5c5f58ddb) | Oct 11, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [2c7e31eb6f](https://linux-hardware.org/?probe=2c7e31eb6f) | Oct 09, 2023 |
| ASRock        | B760M PG Riptide            | [9b5474fee0](https://linux-hardware.org/?probe=9b5474fee0) | Oct 09, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [90041fa012](https://linux-hardware.org/?probe=90041fa012) | Oct 09, 2023 |
| ASUSTek       | P8H67-M EVO                 | [146bc4cb2c](https://linux-hardware.org/?probe=146bc4cb2c) | Oct 08, 2023 |
| MSI           | B450M MORTAR MAX            | [b03eea6d75](https://linux-hardware.org/?probe=b03eea6d75) | Oct 08, 2023 |
| HP            | 212B                        | [faa56daf1d](https://linux-hardware.org/?probe=faa56daf1d) | Oct 07, 2023 |
| HP            | 83E8                        | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e401b0c370](https://linux-hardware.org/?probe=e401b0c370) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ad60cd6e18](https://linux-hardware.org/?probe=ad60cd6e18) | Oct 06, 2023 |
| ASUSTek       | B85-PRO GAMER               | [10baa7a046](https://linux-hardware.org/?probe=10baa7a046) | Oct 06, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cbf93da8d0](https://linux-hardware.org/?probe=cbf93da8d0) | Oct 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | [573f1da6a9](https://linux-hardware.org/?probe=573f1da6a9) | Oct 03, 2023 |
| Gigabyte      | X570S UD                    | [5d8ef7c003](https://linux-hardware.org/?probe=5d8ef7c003) | Oct 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2e1316fb48](https://linux-hardware.org/?probe=2e1316fb48) | Oct 03, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [6a2fa93249](https://linux-hardware.org/?probe=6a2fa93249) | Oct 03, 2023 |
| Gigabyte      | B365M DS3H                  | [c9a7b94ace](https://linux-hardware.org/?probe=c9a7b94ace) | Oct 03, 2023 |
| MSI           | B560M PRO                   | [1312550a66](https://linux-hardware.org/?probe=1312550a66) | Oct 02, 2023 |
| ASRock        | B450 Gaming K4              | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| MSI           | B560M PRO                   | [1dc06a927c](https://linux-hardware.org/?probe=1dc06a927c) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| MSI           | B560M PRO                   | [ce2f5b7349](https://linux-hardware.org/?probe=ce2f5b7349) | Sep 29, 2023 |
| Gigabyte      | H610M S2H DDR4              | [9d767beb12](https://linux-hardware.org/?probe=9d767beb12) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [7ed50e5e43](https://linux-hardware.org/?probe=7ed50e5e43) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7cfa1007ee](https://linux-hardware.org/?probe=7cfa1007ee) | Sep 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [a9c8158139](https://linux-hardware.org/?probe=a9c8158139) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [65369ae480](https://linux-hardware.org/?probe=65369ae480) | Sep 25, 2023 |
| HP            | 8949 11                     | [acb62cff2b](https://linux-hardware.org/?probe=acb62cff2b) | Sep 25, 2023 |
| ASUSTek       | P5G41T-M LX3                | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| HP            | 8055                        | [d8ea4bc33a](https://linux-hardware.org/?probe=d8ea4bc33a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [537e551c45](https://linux-hardware.org/?probe=537e551c45) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a9f9ccb4f9](https://linux-hardware.org/?probe=a9f9ccb4f9) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| ASRock        | A320M-HD                    | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| HP            | 212B                        | [1d71ef5e64](https://linux-hardware.org/?probe=1d71ef5e64) | Sep 19, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| HP            | 3047h                       | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| Gigabyte      | B450M S2H                   | [75f2d2b31d](https://linux-hardware.org/?probe=75f2d2b31d) | Sep 18, 2023 |
| ASRock        | B450M-HDV R4.0              | [e517de2d8f](https://linux-hardware.org/?probe=e517de2d8f) | Sep 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [78535377d6](https://linux-hardware.org/?probe=78535377d6) | Sep 18, 2023 |
| HP            | 212B                        | [a041c8b5a9](https://linux-hardware.org/?probe=a041c8b5a9) | Sep 17, 2023 |
| ASRock        | B450 Gaming K4              | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| HP            | 3647h                       | [89c406366a](https://linux-hardware.org/?probe=89c406366a) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [b7ff5a9cf2](https://linux-hardware.org/?probe=b7ff5a9cf2) | Sep 16, 2023 |
| Shenzhen M... | F7BSC                       | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [c40357b67a](https://linux-hardware.org/?probe=c40357b67a) | Sep 16, 2023 |
| Biostar       | X370GTN                     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| MSI           | PRO B660M-B DDR4            | [9463a6f106](https://linux-hardware.org/?probe=9463a6f106) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | [ba15fb6ed7](https://linux-hardware.org/?probe=ba15fb6ed7) | Sep 14, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| HP            | 0A60h                       | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-P                | [c6f2b822c7](https://linux-hardware.org/?probe=c6f2b822c7) | Sep 12, 2023 |
| HP            | 870C                        | [3de222afdb](https://linux-hardware.org/?probe=3de222afdb) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [6e5224fa1d](https://linux-hardware.org/?probe=6e5224fa1d) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f937bad2e](https://linux-hardware.org/?probe=3f937bad2e) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| HP            | 2B36                        | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 339A                        | [4ba272aaf9](https://linux-hardware.org/?probe=4ba272aaf9) | Sep 08, 2023 |
| HP            | 2B36                        | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b5ea617856](https://linux-hardware.org/?probe=b5ea617856) | Sep 08, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| MSI           | B360M GAMING PLUS           | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [9e7c97275d](https://linux-hardware.org/?probe=9e7c97275d) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| MSI           | 2A9Ch                       | [68fe74d684](https://linux-hardware.org/?probe=68fe74d684) | Sep 06, 2023 |
| HP            | 1905                        | [e0da3a1a45](https://linux-hardware.org/?probe=e0da3a1a45) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| MSI           | MS-B0A81                    | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| MSI           | B350M PRO-VDH               | [4ee783a52f](https://linux-hardware.org/?probe=4ee783a52f) | Sep 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| Biostar       | A320MH                      | [8791e4dd20](https://linux-hardware.org/?probe=8791e4dd20) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [a19ece12f0](https://linux-hardware.org/?probe=a19ece12f0) | Sep 01, 2023 |
| HP            | 82F1                        | [6fca2da71a](https://linux-hardware.org/?probe=6fca2da71a) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [88b6c0365c](https://linux-hardware.org/?probe=88b6c0365c) | Aug 31, 2023 |
| ASUSTek       | PRIME B450M-A II            | [bec8171350](https://linux-hardware.org/?probe=bec8171350) | Aug 30, 2023 |
| Dell          | 07KY25 A00                  | [9346896df5](https://linux-hardware.org/?probe=9346896df5) | Aug 30, 2023 |
| Gigabyte      | P55-UD4                     | [071fa35482](https://linux-hardware.org/?probe=071fa35482) | Aug 29, 2023 |
| Intel         | DH61CR AAG14064-204         | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| MSI           | 970A-G46                    | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| Gigabyte      | P55-UD4                     | [db36b0429d](https://linux-hardware.org/?probe=db36b0429d) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [28b621194b](https://linux-hardware.org/?probe=28b621194b) | Aug 18, 2023 |
| ASRock        | H61M-HG4                    | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [b63e7d3466](https://linux-hardware.org/?probe=b63e7d3466) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f4bcea527c](https://linux-hardware.org/?probe=f4bcea527c) | Aug 14, 2023 |
| ASUSTek       | G15CE                       | [a9ac3a3ce4](https://linux-hardware.org/?probe=a9ac3a3ce4) | Aug 13, 2023 |
| Dell          | 0TTDMJ A00                  | [e0c6e5b185](https://linux-hardware.org/?probe=e0c6e5b185) | Aug 13, 2023 |
| ASRock        | B550M Pro4                  | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| Dell          | 0NC2VH A01                  | [e39fddb92c](https://linux-hardware.org/?probe=e39fddb92c) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Gigabyte      | M720-US3                    | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| HP            | 83E8                        | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Gigabyte      | X570S AERO G                | [22916d4c12](https://linux-hardware.org/?probe=22916d4c12) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [00bb870b78](https://linux-hardware.org/?probe=00bb870b78) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [121b892fa8](https://linux-hardware.org/?probe=121b892fa8) | Aug 08, 2023 |
| MSI           | B550-A PRO                  | [61c59e48d2](https://linux-hardware.org/?probe=61c59e48d2) | Aug 08, 2023 |
| AZW           | U59                         | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [230032816b](https://linux-hardware.org/?probe=230032816b) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| HP            | 8055                        | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | [2e309e76d7](https://linux-hardware.org/?probe=2e309e76d7) | Aug 03, 2023 |
| HP            | 2215                        | [f0589325fc](https://linux-hardware.org/?probe=f0589325fc) | Aug 03, 2023 |
| Unknown       | Unknown                     | [92f3b39535](https://linux-hardware.org/?probe=92f3b39535) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| ASUSTek       | P8Z77-V                     | [65dcccd422](https://linux-hardware.org/?probe=65dcccd422) | Jul 30, 2023 |
| MSI           | PRO X670-P WIFI             | [19b97459c1](https://linux-hardware.org/?probe=19b97459c1) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [c8116c748a](https://linux-hardware.org/?probe=c8116c748a) | Jul 29, 2023 |
| Dell          | 0PU052                      | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [06731541dd](https://linux-hardware.org/?probe=06731541dd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | P8Z77-V                     | [e550626a11](https://linux-hardware.org/?probe=e550626a11) | Jul 27, 2023 |
| Gigabyte      | B360M HD3                   | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| ASRock        | X570 Pro4                   | [96dcaad094](https://linux-hardware.org/?probe=96dcaad094) | Jul 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| MSI           | PRO Z690-A WIFI             | [8f3dc1cb65](https://linux-hardware.org/?probe=8f3dc1cb65) | Jul 24, 2023 |
| ASUSTek       | P8Z77-V                     | [a8f7397fcf](https://linux-hardware.org/?probe=a8f7397fcf) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6094ce5501](https://linux-hardware.org/?probe=6094ce5501) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| AMI           | Intel                       | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [42fc5ff144](https://linux-hardware.org/?probe=42fc5ff144) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [65972dbe80](https://linux-hardware.org/?probe=65972dbe80) | Jul 21, 2023 |
| ASRock        | B450 Pro4                   | [6df8743ac8](https://linux-hardware.org/?probe=6df8743ac8) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2dbb6f2466](https://linux-hardware.org/?probe=2dbb6f2466) | Jul 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | [3014bea7d8](https://linux-hardware.org/?probe=3014bea7d8) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [765ac65603](https://linux-hardware.org/?probe=765ac65603) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| ASRock        | B450 Gaming K4              | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| HP            | 83E0                        | [35abf30fff](https://linux-hardware.org/?probe=35abf30fff) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| HP            | 3397                        | [d20efc761c](https://linux-hardware.org/?probe=d20efc761c) | Jul 13, 2023 |
| ASRock        | B450 Gaming K4              | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| Dell          | 0T10XW A01                  | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| MSI           | X370 GAMING M7 ACK          | [e62935623d](https://linux-hardware.org/?probe=e62935623d) | Jul 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [611ea83c30](https://linux-hardware.org/?probe=611ea83c30) | Jul 11, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [8aadac9d4b](https://linux-hardware.org/?probe=8aadac9d4b) | Jul 11, 2023 |
| ASUSTek       | SABERTOOTH X99              | [1473d3cd3b](https://linux-hardware.org/?probe=1473d3cd3b) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V                     | [1e5cf5e071](https://linux-hardware.org/?probe=1e5cf5e071) | Jul 10, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | [9120c3aa90](https://linux-hardware.org/?probe=9120c3aa90) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | [b48f49fab3](https://linux-hardware.org/?probe=b48f49fab3) | Jul 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [290c9aca96](https://linux-hardware.org/?probe=290c9aca96) | Jul 09, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [2378ebea87](https://linux-hardware.org/?probe=2378ebea87) | Jul 07, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [b67973ece1](https://linux-hardware.org/?probe=b67973ece1) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| ASUSTek       | PRIME A320M-K               | [b66a2be1fe](https://linux-hardware.org/?probe=b66a2be1fe) | Jul 03, 2023 |
| HP            | 8918                        | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| MSI           | H61MA-E35                   | [a5b11bc53c](https://linux-hardware.org/?probe=a5b11bc53c) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | 89B5 A                      | [f0330163de](https://linux-hardware.org/?probe=f0330163de) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b94582735c](https://linux-hardware.org/?probe=b94582735c) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6f96789257](https://linux-hardware.org/?probe=6f96789257) | Jun 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [f46408c9b6](https://linux-hardware.org/?probe=f46408c9b6) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| ASRock        | H370M-ITX/ac                | [5e1d8d04f2](https://linux-hardware.org/?probe=5e1d8d04f2) | Jun 26, 2023 |
| HP            | 1493                        | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [14bd8b577f](https://linux-hardware.org/?probe=14bd8b577f) | Jun 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bd418c39bf](https://linux-hardware.org/?probe=bd418c39bf) | Jun 25, 2023 |
| HP            | 8437                        | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | [85221c654f](https://linux-hardware.org/?probe=85221c654f) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| MSI           | Z170A GAMING M3             | [96c2d6503c](https://linux-hardware.org/?probe=96c2d6503c) | Jun 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0e23ab4ba9](https://linux-hardware.org/?probe=0e23ab4ba9) | Jun 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [bfe09e12f0](https://linux-hardware.org/?probe=bfe09e12f0) | Jun 18, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| ASRock        | 970M Pro3                   | [777a9e4f49](https://linux-hardware.org/?probe=777a9e4f49) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c5491fb02f](https://linux-hardware.org/?probe=c5491fb02f) | Jun 16, 2023 |
| MSI           | X299 GAMING PRO CARBON A... | [6385c09651](https://linux-hardware.org/?probe=6385c09651) | Jun 15, 2023 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [31d4ce59c3](https://linux-hardware.org/?probe=31d4ce59c3) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [f6175fd764](https://linux-hardware.org/?probe=f6175fd764) | Jun 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | [4402afe7ad](https://linux-hardware.org/?probe=4402afe7ad) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | [78c4871863](https://linux-hardware.org/?probe=78c4871863) | Jun 14, 2023 |
| ASRock        | B450 Gaming K4              | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| ASUSTek       | PRIME B560M-K               | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [5275807836](https://linux-hardware.org/?probe=5275807836) | Jun 11, 2023 |
| Gigabyte      | A520M H                     | [af18d05812](https://linux-hardware.org/?probe=af18d05812) | Jun 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Unknown       | Unknown                     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 3397                        | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| HP            | 3397                        | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Dell          | 055H3G A01                  | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| MSI           | GF615M-P33                  | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | P55-GD55                    | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| MSI           | PRO Z790-A WIFI             | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| HP            | 2B36                        | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| ASUSTek       | PRIME H510M-A               | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Intel         | DN2820FYK H24582-204        | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Unknown       | Unknown                     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| HP            | 8876 11                     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| AMI           | Intel                       | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| Unknown       | HX90                        | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Lenovo        | 3714 NOK                    | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Gigabyte      | A520M H                     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| MSI           | 760GM-P23                   | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| HP            | 3047h                       | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Gigabyte      | 970A-DS3P                   | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Gateway       | RS780                       | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| Intel         | H61                         | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Pegatron      | Benicia                     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| HP            | 802E                        | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| ASUSTek       | GR6                         | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| Huanan        | X99-F8                      | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| ASUSTek       | Z170M-PLUS                  | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| MSI           | H81M-E34                    | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| MSI           | GF615M-P33                  | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| HP            | 1495                        | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| MSI           | X570-A PRO                  | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| HP            | 212B                        | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| MSI           | B75MA-P45                   | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| HP            | 8597                        | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H                  | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
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
| Manjaro           | 1290     | 42.43%  |
| Manjaro 20.1      | 135      | 4.44%   |
| Manjaro 20.2.1    | 108      | 3.55%   |
| Manjaro 22.0.0    | 102      | 3.36%   |
| Manjaro 20.2      | 89       | 2.93%   |
| Manjaro 20.0.3    | 81       | 2.66%   |
| Manjaro 23.0.0    | 62       | 2.04%   |
| Manjaro 18.1.5    | 56       | 1.84%   |
| Manjaro 21.2.6    | 53       | 1.74%   |
| Manjaro 21.2.5    | 53       | 1.74%   |
| Manjaro 21.1.0    | 53       | 1.74%   |
| Manjaro 18.0.4    | 46       | 1.51%   |
| Manjaro 21.2.0    | 45       | 1.48%   |
| Manjaro 20.0      | 45       | 1.48%   |
| Manjaro 21.1.6    | 38       | 1.25%   |
| Manjaro 21.0.7    | 36       | 1.18%   |
| Manjaro 21.0.5    | 35       | 1.15%   |
| Manjaro 21.0      | 35       | 1.15%   |
| Manjaro 23.1.0    | 32       | 1.05%   |
| Manjaro 19.0.2    | 31       | 1.02%   |
| Manjaro 20.1.2    | 29       | 0.95%   |
| Manjaro 20.0.1    | 29       | 0.95%   |
| Manjaro 21.2.3    | 27       | 0.89%   |
| Manjaro 22.1.0    | 25       | 0.82%   |
| Manjaro 20.1.1    | 24       | 0.79%   |
| Manjaro 21.2.1    | 23       | 0.76%   |
| Manjaro 21.3.7    | 20       | 0.66%   |
| Manjaro 21.3.6    | 18       | 0.59%   |
| Manjaro 23.0.4    | 17       | 0.56%   |
| Manjaro 22.0.4    | 16       | 0.53%   |
| Manjaro 21.0.4    | 16       | 0.53%   |
| Manjaro 21.0.1    | 14       | 0.46%   |
| Manjaro 21.0.2    | 13       | 0.43%   |
| Manjaro 22.1.1    | 12       | 0.39%   |
| Manjaro 21.2rc    | 12       | 0.39%   |
| Manjaro 21.2.4    | 12       | 0.39%   |
| Manjaro 21.1.2    | 12       | 0.39%   |
| Manjaro 21.0.3    | 12       | 0.39%   |
| Manjaro 18.0.0-rc | 12       | 0.39%   |
| Manjaro 22.0      | 11       | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2786     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 3.37%   |
| 5.8.6-1-MANJARO   | 68       | 1.99%   |
| 5.13.19-2-MANJARO | 67       | 1.96%   |
| 5.15.28-1-MANJARO | 49       | 1.44%   |
| 5.9.11-3-MANJARO  | 48       | 1.41%   |
| 5.8.11-1-MANJARO  | 46       | 1.35%   |
| 5.10.42-1-MANJARO | 40       | 1.17%   |
| 6.1.1-1-MANJARO   | 38       | 1.11%   |
| 5.8.18-1-MANJARO  | 38       | 1.11%   |
| 6.5.5-1-MANJARO   | 34       | 1%      |
| 6.1.31-2-MANJARO  | 32       | 0.94%   |
| 6.1.12-1-MANJARO  | 32       | 0.94%   |
| 5.15.32-1-MANJARO | 32       | 0.94%   |
| 5.6.16-1-MANJARO  | 31       | 0.91%   |
| 5.15.60-1-MANJARO | 30       | 0.88%   |
| 5.10.36-2-MANJARO | 30       | 0.88%   |
| 5.7.9-1-MANJARO   | 29       | 0.85%   |
| 5.15.12-1-MANJARO | 29       | 0.85%   |
| 5.8.3-2-MANJARO   | 25       | 0.73%   |
| 5.8.16-2-MANJARO  | 25       | 0.73%   |
| 5.6.19-2-MANJARO  | 24       | 0.7%    |
| 5.6.15-1-MANJARO  | 24       | 0.7%    |
| 5.17.1-3-MANJARO  | 24       | 0.7%    |
| 5.7.0-3-MANJARO   | 23       | 0.67%   |
| 5.10.2-2-MANJARO  | 23       | 0.67%   |
| 5.6.7-1-MANJARO   | 22       | 0.64%   |
| 5.6.12-1-MANJARO  | 22       | 0.64%   |
| 5.16.14-1-MANJARO | 22       | 0.64%   |
| 5.15.2-2-MANJARO  | 22       | 0.64%   |
| 5.10.23-1-MANJARO | 22       | 0.64%   |
| 5.9.1-1-MANJARO   | 21       | 0.62%   |
| 5.11.6-1-MANJARO  | 21       | 0.62%   |
| 5.4.15-2-MANJARO  | 20       | 0.59%   |
| 5.7.17-2-MANJARO  | 19       | 0.56%   |
| 5.4.6-2-MANJARO   | 19       | 0.56%   |
| 5.10.7-3-MANJARO  | 19       | 0.56%   |
| 5.10.15-1-MANJARO | 19       | 0.56%   |
| 5.14.10-1-MANJARO | 17       | 0.5%    |
| 5.11.2-1-MANJARO  | 17       | 0.5%    |
| 5.10.53-1-MANJARO | 17       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 3.37%   |
| 5.8.6   | 68       | 1.99%   |
| 5.13.19 | 67       | 1.96%   |
| 5.9.11  | 51       | 1.5%    |
| 5.15.28 | 49       | 1.44%   |
| 5.8.11  | 47       | 1.38%   |
| 5.10.42 | 40       | 1.17%   |
| 6.1.1   | 38       | 1.11%   |
| 5.8.18  | 38       | 1.11%   |
| 6.5.5   | 35       | 1.03%   |
| 6.1.31  | 33       | 0.97%   |
| 6.1.12  | 32       | 0.94%   |
| 5.15.32 | 32       | 0.94%   |
| 5.6.16  | 31       | 0.91%   |
| 5.15.60 | 30       | 0.88%   |
| 5.10.36 | 30       | 0.88%   |
| 5.7.9   | 29       | 0.85%   |
| 5.7.0   | 29       | 0.85%   |
| 5.17.1  | 29       | 0.85%   |
| 5.15.12 | 29       | 0.85%   |
| 5.9.1   | 28       | 0.82%   |
| 5.6.19  | 27       | 0.79%   |
| 5.8.3   | 26       | 0.76%   |
| 5.8.16  | 25       | 0.73%   |
| 5.6.15  | 24       | 0.7%    |
| 5.6.12  | 23       | 0.67%   |
| 5.15.2  | 23       | 0.67%   |
| 5.10.2  | 23       | 0.67%   |
| 5.6.7   | 22       | 0.65%   |
| 5.16.14 | 22       | 0.65%   |
| 5.10.23 | 22       | 0.65%   |
| 5.11.6  | 21       | 0.62%   |
| 5.7.17  | 20       | 0.59%   |
| 5.4.15  | 20       | 0.59%   |
| 5.10.7  | 20       | 0.59%   |
| 5.4.6   | 19       | 0.56%   |
| 5.10.15 | 19       | 0.56%   |
| 5.15.7  | 17       | 0.5%    |
| 5.14.10 | 17       | 0.5%    |
| 5.14.0  | 17       | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 460      | 14.49%  |
| 5.10    | 363      | 11.43%  |
| 6.1     | 273      | 8.6%    |
| 5.4     | 253      | 7.97%   |
| 5.9     | 230      | 7.24%   |
| 5.8     | 228      | 7.18%   |
| 5.6     | 172      | 5.42%   |
| 5.13    | 127      | 4%      |
| 5.7     | 109      | 3.43%   |
| 6.5     | 91       | 2.87%   |
| 5.11    | 91       | 2.87%   |
| 4.19    | 68       | 2.14%   |
| 5.17    | 64       | 2.02%   |
| 5.16    | 64       | 2.02%   |
| 6.0     | 61       | 1.92%   |
| 5.14    | 61       | 1.92%   |
| 5.18    | 55       | 1.73%   |
| 5.19    | 54       | 1.7%    |
| 5.12    | 49       | 1.54%   |
| 6.6     | 40       | 1.26%   |
| 6.3     | 39       | 1.23%   |
| 5.5     | 39       | 1.23%   |
| 6.2     | 37       | 1.17%   |
| 4.14    | 33       | 1.04%   |
| 6.4     | 27       | 0.85%   |
| 5.3     | 23       | 0.72%   |
| 5.2     | 17       | 0.54%   |
| 5.1     | 13       | 0.41%   |
| 5.0     | 11       | 0.35%   |
| 4.20    | 5        | 0.16%   |
| 4.18    | 5        | 0.16%   |
| 4.17    | 3        | 0.09%   |
| 4.16    | 3        | 0.09%   |
| 4.9     | 2        | 0.06%   |
| 4.7     | 2        | 0.06%   |
| 4.4     | 2        | 0.06%   |
| 6.7     | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2786     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 1157     | 39.8%   |
| XFCE                     | 607      | 20.88%  |
| GNOME                    | 540      | 18.58%  |
| KDE                      | 250      | 8.6%    |
| Unknown                  | 109      | 3.75%   |
| X-Cinnamon               | 84       | 2.89%   |
| i3                       | 47       | 1.62%   |
| MATE                     | 24       | 0.83%   |
| Cinnamon                 | 22       | 0.76%   |
| Deepin                   | 21       | 0.72%   |
| Budgie                   | 14       | 0.48%   |
| LXQt                     | 8        | 0.28%   |
| sway                     | 5        | 0.17%   |
| Awesome                  | 5        | 0.17%   |
| bspwm                    | 3        | 0.1%    |
| ICEWM                    | 2        | 0.07%   |
| GNOME Classic            | 2        | 0.07%   |
| Yaru:ubuntu:GNOME        | 1        | 0.03%   |
| qtile                    | 1        | 0.03%   |
| openbox                  | 1        | 0.03%   |
| LXDE                     | 1        | 0.03%   |
| Enlightenment            | 1        | 0.03%   |
| DWM                      | 1        | 0.03%   |
| /usr/bin/openbox-session | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2530     | 88.93%  |
| Wayland | 241      | 8.47%   |
| Unknown | 44       | 1.55%   |
| Tty     | 30       | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1285     | 44.71%  |
| SDDM    | 720      | 25.05%  |
| LightDM | 466      | 16.21%  |
| GDM     | 302      | 10.51%  |
| TDM     | 89       | 3.1%    |
| LXDM    | 5        | 0.17%   |
| GREETD  | 3        | 0.1%    |
| SLiM    | 2        | 0.07%   |
| XDM     | 1        | 0.03%   |
| LYNDE   | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1115     | 39.39%  |
| de_DE   | 251      | 8.87%   |
| ru_RU   | 211      | 7.45%   |
| en_GB   | 185      | 6.53%   |
| Unknown | 158      | 5.58%   |
| pt_BR   | 125      | 4.42%   |
| fr_FR   | 84       | 2.97%   |
| en_CA   | 73       | 2.58%   |
| it_IT   | 68       | 2.4%    |
| es_ES   | 68       | 2.4%    |
| pl_PL   | 51       | 1.8%    |
| en_AU   | 42       | 1.48%   |
| nl_NL   | 21       | 0.74%   |
| en_IN   | 21       | 0.74%   |
| de_AT   | 21       | 0.74%   |
| es_AR   | 20       | 0.71%   |
| ru_UA   | 18       | 0.64%   |
| zh_CN   | 16       | 0.57%   |
| sv_SE   | 15       | 0.53%   |
| fi_FI   | 15       | 0.53%   |
| es_MX   | 15       | 0.53%   |
| fr_CA   | 12       | 0.42%   |
| en_PH   | 12       | 0.42%   |
| hu_HU   | 11       | 0.39%   |
| en_IE   | 11       | 0.39%   |
| cs_CZ   | 10       | 0.35%   |
| en_ZA   | 9        | 0.32%   |
| da_DK   | 9        | 0.32%   |
| es_CL   | 8        | 0.28%   |
| en_NZ   | 8        | 0.28%   |
| de_CH   | 8        | 0.28%   |
| pt_PT   | 7        | 0.25%   |
| es_UY   | 7        | 0.25%   |
| en_DK   | 7        | 0.25%   |
| uk_UA   | 6        | 0.21%   |
| ja_JP   | 6        | 0.21%   |
| en_IL   | 6        | 0.21%   |
| tr_TR   | 5        | 0.18%   |
| sk_SK   | 5        | 0.18%   |
| fr_BE   | 5        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1792     | 62.88%  |
| EFI  | 1058     | 37.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2333     | 82.06%  |
| Btrfs   | 316      | 11.12%  |
| Xfs     | 47       | 1.65%   |
| Tmpfs   | 46       | 1.62%   |
| Unknown | 40       | 1.41%   |
| Overlay | 38       | 1.34%   |
| F2fs    | 12       | 0.42%   |
| Zfs     | 4        | 0.14%   |
| Ext2    | 3        | 0.11%   |
| Ext3    | 2        | 0.07%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1379     | 48.2%   |
| GPT     | 1201     | 41.98%  |
| MBR     | 281      | 9.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2358     | 82.85%  |
| Yes       | 488      | 17.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1816     | 63.85%  |
| Yes       | 1028     | 36.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 818      | 29.36%  |
| Gigabyte Technology                  | 567      | 20.35%  |
| MSI                                  | 453      | 16.26%  |
| ASRock                               | 308      | 11.06%  |
| Dell                                 | 144      | 5.17%   |
| Hewlett-Packard                      | 143      | 5.13%   |
| Intel                                | 63       | 2.26%   |
| Lenovo                               | 62       | 2.23%   |
| Acer                                 | 27       | 0.97%   |
| Unknown                              | 25       | 0.9%    |
| Biostar                              | 23       | 0.83%   |
| Pegatron                             | 16       | 0.57%   |
| Huanan                               | 13       | 0.47%   |
| Foxconn                              | 12       | 0.43%   |
| Apple                                | 10       | 0.36%   |
| Medion                               | 8        | 0.29%   |
| Fujitsu                              | 8        | 0.29%   |
| ECS                                  | 7        | 0.25%   |
| Shuttle                              | 5        | 0.18%   |
| Positivo                             | 5        | 0.18%   |
| BESSTAR Tech                         | 5        | 0.18%   |
| AZW                                  | 5        | 0.18%   |
| Alienware                            | 4        | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.11%   |
| PCWare                               | 3        | 0.11%   |
| ZOTAC                                | 2        | 0.07%   |
| OEM                                  | 2        | 0.07%   |
| Minix                                | 2        | 0.07%   |
| MACHINIST                            | 2        | 0.07%   |
| Inventec                             | 2        | 0.07%   |
| Google                               | 2        | 0.07%   |
| Gateway                              | 2        | 0.07%   |
| Fujitsu Siemens                      | 2        | 0.07%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 77       | 2.76%   |
| MSI MS-7C37                      | 32       | 1.15%   |
| MSI MS-7C02                      | 30       | 1.08%   |
| Gigabyte B450M DS3H              | 29       | 1.04%   |
| Unknown                          | 27       | 0.97%   |
| ASUS TUF Gaming X570-PLUS        | 25       | 0.9%    |
| MSI MS-7C91                      | 21       | 0.75%   |
| ASUS PRIME A320M-K               | 20       | 0.72%   |
| MSI MS-7B86                      | 17       | 0.61%   |
| Gigabyte X570 AORUS ELITE        | 16       | 0.57%   |
| ASRock B450M Pro4                | 16       | 0.57%   |
| MSI MS-7B79                      | 15       | 0.54%   |
| MSI MS-7A38                      | 15       | 0.54%   |
| ASUS ROG STRIX B450-F GAMING     | 15       | 0.54%   |
| ASUS ROG STRIX B550-F GAMING     | 14       | 0.5%    |
| Dell OptiPlex 9020               | 13       | 0.47%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.43%   |
| ASUS PRIME B450M-A               | 12       | 0.43%   |
| ASUS PRIME B350-PLUS             | 12       | 0.43%   |
| MSI MS-7B89                      | 11       | 0.39%   |
| Gigabyte B450 AORUS M            | 11       | 0.39%   |
| Gigabyte B450 AORUS ELITE        | 11       | 0.39%   |
| Gigabyte 970A-DS3P               | 11       | 0.39%   |
| Dell OptiPlex 7010               | 11       | 0.39%   |
| MSI MS-7693                      | 10       | 0.36%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.36%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.36%   |
| ASUS ROG STRIX X570-E GAMING     | 10       | 0.36%   |
| ASUS ROG CROSSHAIR VIII HERO     | 10       | 0.36%   |
| ASUS PRIME X370-PRO              | 10       | 0.36%   |
| ASUS PRIME B450-PLUS             | 10       | 0.36%   |
| MSI MS-7817                      | 9        | 0.32%   |
| ASUS PRIME X470-PRO              | 9        | 0.32%   |
| ASUS M5A97 R2.0                  | 9        | 0.32%   |
| ASRock B450 Pro4                 | 9        | 0.32%   |
| MSI MS-7C94                      | 8        | 0.29%   |
| MSI MS-7C84                      | 8        | 0.29%   |
| MSI MS-7A34                      | 8        | 0.29%   |
| ASUS PRIME X570-P                | 8        | 0.29%   |
| ASUS PRIME B350M-A               | 8        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 181      | 6.5%    |
| ASUS ROG            | 161      | 5.78%   |
| ASUS TUF            | 90       | 3.23%   |
| Dell OptiPlex       | 89       | 3.19%   |
| ASUS All            | 77       | 2.76%   |
| Gigabyte X570       | 53       | 1.9%    |
| Gigabyte B450M      | 46       | 1.65%   |
| HP Compaq           | 41       | 1.47%   |
| Gigabyte B450       | 37       | 1.33%   |
| MSI MS-7C37         | 32       | 1.15%   |
| MSI MS-7C02         | 30       | 1.08%   |
| Lenovo ThinkCentre  | 28       | 1.01%   |
| Unknown             | 27       | 0.97%   |
| ASRock B450M        | 26       | 0.93%   |
| Gigabyte B550       | 25       | 0.9%    |
| HP EliteDesk        | 24       | 0.86%   |
| Dell Precision      | 24       | 0.86%   |
| MSI MS-7C91         | 21       | 0.75%   |
| ASRock X570         | 20       | 0.72%   |
| ASRock B450         | 20       | 0.72%   |
| ASUS M5A97          | 19       | 0.68%   |
| MSI MS-7B86         | 17       | 0.61%   |
| ASUS M5A78L-M       | 17       | 0.61%   |
| Acer Aspire         | 17       | 0.61%   |
| ASUS P8Z77-V        | 16       | 0.57%   |
| MSI MS-7B79         | 15       | 0.54%   |
| MSI MS-7A38         | 15       | 0.54%   |
| Gigabyte Z390       | 15       | 0.54%   |
| Gigabyte X470       | 12       | 0.43%   |
| Gigabyte B550M      | 12       | 0.43%   |
| Gigabyte 970A-DS3P  | 12       | 0.43%   |
| ASUS Maximus        | 12       | 0.43%   |
| MSI MS-7B89         | 11       | 0.39%   |
| ASUS P8H61-M        | 11       | 0.39%   |
| ASRock B550M        | 11       | 0.39%   |
| MSI MS-7693         | 10       | 0.36%   |
| Lenovo ThinkStation | 10       | 0.36%   |
| HP Pavilion         | 10       | 0.36%   |
| ASRock AB350        | 10       | 0.36%   |
| ASRock A320M-HDV    | 10       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 447      | 16.04%  |
| 2019    | 339      | 12.17%  |
| 2020    | 307      | 11.02%  |
| 2017    | 226      | 8.11%   |
| 2012    | 220      | 7.9%    |
| 2013    | 188      | 6.75%   |
| 2014    | 167      | 5.99%   |
| 2011    | 149      | 5.35%   |
| 2021    | 122      | 4.38%   |
| 2015    | 122      | 4.38%   |
| 2016    | 115      | 4.13%   |
| 2010    | 96       | 3.45%   |
| 2009    | 83       | 2.98%   |
| 2022    | 76       | 2.73%   |
| 2008    | 48       | 1.72%   |
| 2007    | 47       | 1.69%   |
| 2023    | 16       | 0.57%   |
| 2006    | 13       | 0.47%   |
| 2005    | 4        | 0.14%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2786     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2784     | 99.89%  |
| Enabled  | 3        | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2784     | 99.93%  |
| Yes  | 2        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 1012     | 35.61%  |
| 32.01-64.0  | 608      | 21.39%  |
| 8.01-16.0   | 490      | 17.24%  |
| 4.01-8.0    | 261      | 9.18%   |
| 3.01-4.0    | 180      | 6.33%   |
| 64.01-256.0 | 154      | 5.42%   |
| 24.01-32.0  | 100      | 3.52%   |
| 1.01-2.0    | 30       | 1.06%   |
| 2.01-3.0    | 7        | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 839      | 26.46%  |
| 2.01-3.0    | 690      | 21.76%  |
| 1.01-2.0    | 672      | 21.19%  |
| 3.01-4.0    | 526      | 16.59%  |
| 8.01-16.0   | 277      | 8.74%   |
| 0.51-1.0    | 76       | 2.4%    |
| 16.01-24.0  | 52       | 1.64%   |
| 24.01-32.0  | 15       | 0.47%   |
| 32.01-64.0  | 12       | 0.38%   |
| 0.01-0.5    | 11       | 0.35%   |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 881      | 30.03%  |
| 1      | 689      | 23.48%  |
| 3      | 595      | 20.28%  |
| 4      | 385      | 13.12%  |
| 5      | 215      | 7.33%   |
| 6      | 82       | 2.79%   |
| 7      | 37       | 1.26%   |
| 8      | 17       | 0.58%   |
| 9      | 11       | 0.37%   |
| 0      | 11       | 0.37%   |
| 11     | 5        | 0.17%   |
| 10     | 3        | 0.1%    |
| 12     | 2        | 0.07%   |
| 20     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1889     | 66.77%  |
| Yes       | 940      | 33.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2753     | 98.82%  |
| No        | 33       | 1.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1487     | 52.54%  |
| Yes       | 1343     | 47.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1639     | 57.83%  |
| Yes       | 1195     | 42.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 539      | 19.2%   |
| Germany      | 344      | 12.26%  |
| Russia       | 251      | 8.94%   |
| Brazil       | 169      | 6.02%   |
| Canada       | 111      | 3.95%   |
| France       | 110      | 3.92%   |
| UK           | 91       | 3.24%   |
| Italy        | 90       | 3.21%   |
| Spain        | 89       | 3.17%   |
| Poland       | 81       | 2.89%   |
| Netherlands  | 55       | 1.96%   |
| Ukraine      | 54       | 1.92%   |
| Sweden       | 49       | 1.75%   |
| Australia    | 44       | 1.57%   |
| Austria      | 38       | 1.35%   |
| Finland      | 33       | 1.18%   |
| Argentina    | 29       | 1.03%   |
| Belgium      | 26       | 0.93%   |
| Romania      | 25       | 0.89%   |
| Mexico       | 25       | 0.89%   |
| India        | 25       | 0.89%   |
| Switzerland  | 23       | 0.82%   |
| Hungary      | 23       | 0.82%   |
| Greece       | 23       | 0.82%   |
| Norway       | 21       | 0.75%   |
| Bulgaria     | 21       | 0.75%   |
| Denmark      | 20       | 0.71%   |
| Portugal     | 18       | 0.64%   |
| South Africa | 16       | 0.57%   |
| Czechia      | 16       | 0.57%   |
| China        | 14       | 0.5%    |
| Belarus      | 14       | 0.5%    |
| Turkey       | 13       | 0.46%   |
| Israel       | 13       | 0.46%   |
| Philippines  | 12       | 0.43%   |
| Lithuania    | 11       | 0.39%   |
| Saudi Arabia | 10       | 0.36%   |
| New Zealand  | 10       | 0.36%   |
| Ireland      | 10       | 0.36%   |
| Chile        | 10       | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 58       | 1.95%   |
| St Petersburg     | 25       | 0.84%   |
| Warsaw            | 20       | 0.67%   |
| Berlin            | 20       | 0.67%   |
| Vienna            | 18       | 0.61%   |
| Sao Paulo         | 17       | 0.57%   |
| Kyiv              | 17       | 0.57%   |
| Toronto           | 16       | 0.54%   |
| Madrid            | 15       | 0.51%   |
| Athens            | 15       | 0.51%   |
| Sydney            | 14       | 0.47%   |
| Rome              | 14       | 0.47%   |
| Paris             | 14       | 0.47%   |
| Amsterdam         | 14       | 0.47%   |
| Stockholm         | 13       | 0.44%   |
| Hamburg           | 13       | 0.44%   |
| Rio de Janeiro    | 12       | 0.4%    |
| Frankfurt am Main | 12       | 0.4%    |
| Portland          | 11       | 0.37%   |
| Helsinki          | 11       | 0.37%   |
| Stuttgart         | 10       | 0.34%   |
| Sofia             | 10       | 0.34%   |
| Milan             | 10       | 0.34%   |
| Melbourne         | 10       | 0.34%   |
| Krakow            | 10       | 0.34%   |
| Copenhagen        | 10       | 0.34%   |
| Bucharest         | 10       | 0.34%   |
| Barcelona         | 10       | 0.34%   |
| Yekaterinburg     | 9        | 0.3%    |
| Montreal          | 9        | 0.3%    |
| Minsk             | 9        | 0.3%    |
| Miami             | 9        | 0.3%    |
| Dallas            | 9        | 0.3%    |
| Seattle           | 8        | 0.27%   |
| New York          | 8        | 0.27%   |
| Montevideo        | 8        | 0.27%   |
| London            | 8        | 0.27%   |
| Indianapolis      | 8        | 0.27%   |
| Austin            | 8        | 0.27%   |
| Vilnius           | 7        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1061     | 1803   | 17.33%  |
| Seagate                     | 1043     | 1719   | 17.04%  |
| Samsung Electronics         | 1027     | 1838   | 16.78%  |
| Kingston                    | 388      | 551    | 6.34%   |
| Toshiba                     | 334      | 454    | 5.46%   |
| SanDisk                     | 320      | 448    | 5.23%   |
| Crucial                     | 317      | 477    | 5.18%   |
| Hitachi                     | 145      | 207    | 2.37%   |
| Intel                       | 122      | 164    | 1.99%   |
| A-DATA Technology           | 93       | 137    | 1.52%   |
| Phison                      | 85       | 113    | 1.39%   |
| HGST                        | 68       | 105    | 1.11%   |
| China                       | 64       | 92     | 1.05%   |
| Silicon Motion              | 54       | 74     | 0.88%   |
| Phison Electronics          | 52       | 60     | 0.85%   |
| Micron/Crucial Technology   | 51       | 64     | 0.83%   |
| PNY                         | 46       | 71     | 0.75%   |
| Unknown                     | 41       | 74     | 0.67%   |
| OCZ                         | 40       | 56     | 0.65%   |
| SPCC                        | 39       | 47     | 0.64%   |
| SK hynix                    | 37       | 41     | 0.6%    |
| Patriot                     | 37       | 52     | 0.6%    |
| Intenso                     | 36       | 54     | 0.59%   |
| XPG                         | 32       | 36     | 0.52%   |
| Micron Technology           | 29       | 36     | 0.47%   |
| Corsair                     | 28       | 39     | 0.46%   |
| Transcend                   | 25       | 25     | 0.41%   |
| Realtek Semiconductor       | 25       | 31     | 0.41%   |
| Kingston Technology Company | 23       | 26     | 0.38%   |
| JMicron Technology          | 23       | 29     | 0.38%   |
| Team                        | 22       | 28     | 0.36%   |
| Plextor                     | 21       | 25     | 0.34%   |
| Lexar                       | 21       | 26     | 0.34%   |
| GOODRAM                     | 21       | 32     | 0.34%   |
| Apacer                      | 16       | 18     | 0.26%   |
| ADATA Technology            | 16       | 23     | 0.26%   |
| Maxtor                      | 15       | 17     | 0.25%   |
| Gigabyte Technology         | 14       | 24     | 0.23%   |
| Hewlett-Packard             | 11       | 15     | 0.18%   |
| ASMT                        | 11       | 18     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                           | 97       | 1.33%   |
| Kingston SA400S37240G 240GB SSD                     | 96       | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB                      | 85       | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB                      | 84       | 1.15%   |
| Samsung SSD 850 EVO 500GB                           | 69       | 0.94%   |
| Samsung SSD 850 EVO 250GB                           | 66       | 0.9%    |
| Samsung NVMe SSD Drive 500GB                        | 63       | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 62       | 0.85%   |
| Toshiba DT01ACA100 1TB                              | 62       | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 59       | 0.81%   |
| Kingston SA400S37120G 120GB SSD                     | 58       | 0.79%   |
| Crucial CT500MX500SSD1 500GB                        | 56       | 0.77%   |
| Samsung SSD 860 EVO 1TB                             | 53       | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 52       | 0.71%   |
| Samsung NVMe SSD Drive 1TB                          | 49       | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                         | 48       | 0.66%   |
| Kingston SA400S37480G 480GB SSD                     | 46       | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 45       | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB                      | 45       | 0.62%   |
| Toshiba HDWD110 1TB                                 | 43       | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB                      | 42       | 0.58%   |
| Samsung SSD 860 EVO 250GB                           | 42       | 0.58%   |
| Crucial CT240BX500SSD1 240GB                        | 41       | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 39       | 0.53%   |
| Seagate ST1000DM003-1CH162 1TB                      | 37       | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB                      | 34       | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                      | 34       | 0.47%   |
| Samsung SSD 980 1TB                                 | 33       | 0.45%   |
| Seagate ST3500418AS 500GB                           | 32       | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 32       | 0.44%   |
| Toshiba DT01ACA200 2TB                              | 31       | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                        | 31       | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 29       | 0.4%    |
| Seagate Expansion 2TB                               | 29       | 0.4%    |
| Toshiba DT01ACA050 500GB                            | 27       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB                      | 27       | 0.37%   |
| Seagate ST31000524AS 1TB                            | 26       | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 26       | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 25       | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 25       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1019     | 1667   | 37.46%  |
| WDC                 | 945      | 1554   | 34.74%  |
| Toshiba             | 301      | 402    | 11.07%  |
| Samsung Electronics | 146      | 226    | 5.37%   |
| Hitachi             | 145      | 207    | 5.33%   |
| HGST                | 66       | 103    | 2.43%   |
| Unknown             | 18       | 27     | 0.66%   |
| Maxtor              | 15       | 17     | 0.55%   |
| Fujitsu             | 10       | 19     | 0.37%   |
| SABRENT             | 8        | 8      | 0.29%   |
| Intenso             | 6        | 11     | 0.22%   |
| USB3.0              | 5        | 5      | 0.18%   |
| Apple               | 5        | 8      | 0.18%   |
| External            | 4        | 5      | 0.15%   |
| TO Exter            | 3        | 4      | 0.11%   |
| MaxDigital          | 3        | 3      | 0.11%   |
| HGST HTS            | 3        | 3      | 0.11%   |
| Hewlett-Packard     | 3        | 3      | 0.11%   |
| ASMT                | 3        | 6      | 0.11%   |
| USB                 | 2        | 2      | 0.07%   |
| Maxone              | 2        | 3      | 0.07%   |
| JMicron Technology  | 2        | 5      | 0.07%   |
| StoreJet            | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| Initio              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |
| IB-377U3            | 1        | 1      | 0.04%   |
| HPE                 | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 609      | 943    | 26.42%  |
| Kingston            | 331      | 457    | 14.36%  |
| Crucial             | 290      | 441    | 12.58%  |
| SanDisk             | 187      | 246    | 8.11%   |
| WDC                 | 145      | 203    | 6.29%   |
| A-DATA Technology   | 79       | 118    | 3.43%   |
| China               | 64       | 92     | 2.78%   |
| Intel               | 58       | 77     | 2.52%   |
| PNY                 | 41       | 66     | 1.78%   |
| OCZ                 | 40       | 56     | 1.74%   |
| Patriot             | 35       | 50     | 1.52%   |
| SPCC                | 33       | 41     | 1.43%   |
| Toshiba             | 23       | 34     | 1%      |
| Lexar               | 21       | 26     | 0.91%   |
| Intenso             | 21       | 32     | 0.91%   |
| Transcend           | 20       | 20     | 0.87%   |
| GOODRAM             | 20       | 31     | 0.87%   |
| Corsair             | 20       | 29     | 0.87%   |
| Plextor             | 19       | 23     | 0.82%   |
| Team                | 18       | 24     | 0.78%   |
| Micron Technology   | 18       | 21     | 0.78%   |
| Apacer              | 16       | 18     | 0.69%   |
| SK hynix            | 14       | 15     | 0.61%   |
| Gigabyte Technology | 12       | 17     | 0.52%   |
| Seagate             | 11       | 14     | 0.48%   |
| JMicron Technology  | 11       | 12     | 0.48%   |
| Leven               | 10       | 10     | 0.43%   |
| KingDian            | 10       | 10     | 0.43%   |
| KingSpec            | 8        | 10     | 0.35%   |
| ASMT                | 8        | 12     | 0.35%   |
| LITEON              | 6        | 10     | 0.26%   |
| LITEONIT            | 5        | 8      | 0.22%   |
| Apple               | 5        | 5      | 0.22%   |
| Verbatim            | 4        | 5      | 0.17%   |
| NGFF                | 4        | 4      | 0.17%   |
| Mushkin             | 4        | 4      | 0.17%   |
| Hoodisk             | 4        | 5      | 0.17%   |
| Netac               | 3        | 4      | 0.13%   |
| Kingmax             | 3        | 4      | 0.13%   |
| Hewlett-Packard     | 3        | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1982     | 4294   | 40.08%  |
| SSD     | 1784     | 3298   | 36.08%  |
| NVMe    | 1080     | 1753   | 21.84%  |
| Unknown | 93       | 140    | 1.88%   |
| MMC     | 6        | 6      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2547     | 7324   | 65.63%  |
| NVMe | 1079     | 1751   | 27.8%   |
| SAS  | 249      | 410    | 6.42%   |
| MMC  | 6        | 6      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1854     | 3636   | 43.2%   |
| 0.51-1.0   | 1327     | 2199   | 30.92%  |
| 1.01-2.0   | 615      | 926    | 14.33%  |
| 3.01-4.0   | 199      | 317    | 4.64%   |
| 2.01-3.0   | 139      | 219    | 3.24%   |
| 4.01-10.0  | 134      | 253    | 3.12%   |
| 10.01-20.0 | 24       | 42     | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 509      | 17.12%  |
| 501-1000       | 505      | 16.99%  |
| 101-250        | 493      | 16.58%  |
| 1001-2000      | 491      | 16.52%  |
| More than 3000 | 433      | 14.56%  |
| 2001-3000      | 259      | 8.71%   |
| Unknown        | 104      | 3.5%    |
| 51-100         | 102      | 3.43%   |
| 1-20           | 44       | 1.48%   |
| 21-50          | 33       | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 485      | 15.64%  |
| 1-20           | 434      | 14%     |
| 501-1000       | 400      | 12.9%   |
| 251-500        | 381      | 12.29%  |
| 21-50          | 366      | 11.8%   |
| 51-100         | 335      | 10.8%   |
| 1001-2000      | 305      | 9.84%   |
| More than 3000 | 173      | 5.58%   |
| 2001-3000      | 117      | 3.77%   |
| Unknown        | 104      | 3.35%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8        | 11     | 2.22%   |
| WDC WD5000AAKX-001CA0 500GB           | 6        | 8      | 1.67%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.39%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.39%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.39%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 1.11%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB        | 4        | 4      | 1.11%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.11%   |
| Seagate ST1000DM003-9YN162 1TB        | 4        | 6      | 1.11%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.11%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.11%   |
| Kingston SV300S37A120G 120GB SSD      | 4        | 4      | 1.11%   |
| WDC WD20EARS-00MVWB0 2TB              | 3        | 3      | 0.83%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.83%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.83%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.83%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.83%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 13     | 0.83%   |
| Seagate ST3250318AS 250GB             | 3        | 3      | 0.83%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.83%   |
| Seagate ST2000DX001-1CM164 2TB        | 3        | 3      | 0.83%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.83%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.83%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.83%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.56%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.56%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.56%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.56%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.56%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.56%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2        | 2      | 0.56%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.56%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.56%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.56%   |
| Seagate ST31000528AS 1TB              | 2        | 4      | 0.56%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 108      | 126    | 31.21%  |
| Seagate               | 100      | 146    | 28.9%   |
| Samsung Electronics   | 30       | 36     | 8.67%   |
| Hitachi               | 19       | 21     | 5.49%   |
| Toshiba               | 13       | 16     | 3.76%   |
| Kingston              | 13       | 13     | 3.76%   |
| Intel                 | 10       | 11     | 2.89%   |
| SanDisk               | 9        | 12     | 2.6%    |
| HGST                  | 7        | 7      | 2.02%   |
| Crucial               | 7        | 7      | 2.02%   |
| A-DATA Technology     | 5        | 5      | 1.45%   |
| SK hynix              | 2        | 3      | 0.58%   |
| OCZ                   | 2        | 2      | 0.58%   |
| Micron Technology     | 2        | 2      | 0.58%   |
| Apacer                | 2        | 2      | 0.58%   |
| Transcend             | 1        | 1      | 0.29%   |
| SPCC                  | 1        | 1      | 0.29%   |
| Realtek Semiconductor | 1        | 1      | 0.29%   |
| Phison                | 1        | 2      | 0.29%   |
| Patriot               | 1        | 1      | 0.29%   |
| Maxtor                | 1        | 1      | 0.29%   |
| MaxDigital            | 1        | 1      | 0.29%   |
| KingSpec              | 1        | 2      | 0.29%   |
| JMicron Technology    | 1        | 1      | 0.29%   |
| Intenso               | 1        | 4      | 0.29%   |
| Hewlett-Packard       | 1        | 1      | 0.29%   |
| Fujitsu               | 1        | 1      | 0.29%   |
| Drevo                 | 1        | 1      | 0.29%   |
| Corsair               | 1        | 5      | 0.29%   |
| China                 | 1        | 1      | 0.29%   |
| ASMT                  | 1        | 5      | 0.29%   |
| Unknown               | 1        | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 107      | 125    | 40.07%  |
| Seagate             | 99       | 143    | 37.08%  |
| Samsung Electronics | 19       | 24     | 7.12%   |
| Hitachi             | 19       | 21     | 7.12%   |
| Toshiba             | 13       | 16     | 4.87%   |
| HGST                | 7        | 7      | 2.62%   |
| Maxtor              | 1        | 1      | 0.37%   |
| MaxDigital          | 1        | 1      | 0.37%   |
| Fujitsu             | 1        | 1      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 246      | 339    | 76.16%  |
| SSD  | 64       | 85     | 19.81%  |
| NVMe | 13       | 15     | 4.02%   |

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
| Detected | 1854     | 6005   | 57.4%   |
| Works    | 1057     | 3034   | 32.72%  |
| Malfunc  | 307      | 439    | 9.5%    |
| Failed   | 12       | 13     | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1458     | 33.36%  |
| AMD                              | 1316     | 30.11%  |
| Samsung Electronics              | 449      | 10.27%  |
| ASMedia Technology               | 182      | 4.16%   |
| SanDisk                          | 171      | 3.91%   |
| Phison Electronics               | 146      | 3.34%   |
| Kingston Technology Company      | 89       | 2.04%   |
| Micron/Crucial Technology        | 80       | 1.83%   |
| Marvell Technology Group         | 76       | 1.74%   |
| Silicon Motion                   | 70       | 1.6%    |
| JMicron Technology               | 66       | 1.51%   |
| ADATA Technology                 | 49       | 1.12%   |
| Nvidia                           | 39       | 0.89%   |
| Realtek Semiconductor            | 36       | 0.82%   |
| SK hynix                         | 23       | 0.53%   |
| Toshiba America Info Systems     | 12       | 0.27%   |
| Seagate Technology               | 11       | 0.25%   |
| Micron Technology                | 11       | 0.25%   |
| LSI Logic / Symbios Logic        | 10       | 0.23%   |
| KIOXIA                           | 9        | 0.21%   |
| VIA Technologies                 | 8        | 0.18%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.18%   |
| Lite-On Technology               | 7        | 0.16%   |
| Broadcom / LSI                   | 7        | 0.16%   |
| Silicon Image                    | 5        | 0.11%   |
| Shenzhen Longsys Electronics     | 5        | 0.11%   |
| Adaptec                          | 4        | 0.09%   |
| Integrated Technology Express    | 3        | 0.07%   |
| INNOGRIT                         | 3        | 0.07%   |
| Union Memory (Shenzhen)          | 2        | 0.05%   |
| Lenovo                           | 2        | 0.05%   |
| HighPoint Technologies           | 2        | 0.05%   |
| Yangtze Memory Technologies      | 1        | 0.02%   |
| Transcend                        | 1        | 0.02%   |
| Solidigm                         | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| PMC-Sierra                       | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| HGST                             | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 874      | 16.12%  |
| AMD 400 Series Chipset SATA Controller                                                  | 363      | 6.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 255      | 4.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 179      | 3.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 178      | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 169      | 3.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 139      | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 120      | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 117      | 2.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 116      | 2.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 109      | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 107      | 1.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 92       | 1.7%    |
| AMD 300 Series Chipset SATA Controller                                                  | 92       | 1.7%    |
| Intel SATA Controller [RAID mode]                                                       | 91       | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 83       | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 74       | 1.37%   |
| Phison E12 NVMe Controller                                                              | 70       | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 69       | 1.27%   |
| AMD FCH SATA Controller D                                                               | 62       | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 59       | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 57       | 1.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 53       | 0.98%   |
| AMD X370 Series Chipset SATA Controller                                                 | 47       | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 46       | 0.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 44       | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 44       | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 43       | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42       | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42       | 0.77%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 40       | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 39       | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 38       | 0.7%    |
| Intel SSD 660P Series                                                                   | 38       | 0.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 37       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 37       | 0.68%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 36       | 0.66%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 35       | 0.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 34       | 0.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 34       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2477     | 59.61%  |
| NVMe | 1085     | 26.11%  |
| IDE  | 407      | 9.8%    |
| RAID | 161      | 3.87%   |
| SAS  | 22       | 0.53%   |
| SCSI | 3        | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1429     | 51.27%  |
| AMD    | 1358     | 48.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 141      | 5.03%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 84       | 3%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 66       | 2.36%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 65       | 2.32%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 47       | 1.68%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 47       | 1.68%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 37       | 1.32%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 33       | 1.18%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 30       | 1.07%   |
| AMD FX-8350 Eight-Core Processor            | 30       | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 29       | 1.03%   |
| AMD FX-6300 Six-Core Processor              | 29       | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 27       | 0.96%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 0.96%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 26       | 0.93%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 25       | 0.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 24       | 0.86%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 24       | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 24       | 0.86%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 24       | 0.86%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 24       | 0.86%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 24       | 0.86%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 24       | 0.86%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 23       | 0.82%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 22       | 0.79%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 22       | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 21       | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 21       | 0.75%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 21       | 0.75%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 21       | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 20       | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 20       | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 19       | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.64%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.64%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 17       | 0.61%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 16       | 0.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 472      | 16.88%  |
| Intel Core i5           | 453      | 16.2%   |
| Intel Core i7           | 379      | 13.55%  |
| AMD Ryzen 7             | 328      | 11.73%  |
| AMD Ryzen 9             | 143      | 5.11%   |
| Intel Core i3           | 141      | 5.04%   |
| Intel Xeon              | 132      | 4.72%   |
| AMD FX                  | 122      | 4.36%   |
| Other                   | 88       | 3.15%   |
| AMD Ryzen 3             | 52       | 1.86%   |
| Intel Core 2 Duo        | 46       | 1.64%   |
| Intel Celeron           | 38       | 1.36%   |
| Intel Pentium           | 34       | 1.22%   |
| Intel Core 2 Quad       | 30       | 1.07%   |
| AMD Ryzen Threadripper  | 30       | 1.07%   |
| AMD Phenom II X4        | 29       | 1.04%   |
| Intel Core i9           | 25       | 0.89%   |
| Intel Pentium Dual-Core | 24       | 0.86%   |
| AMD Athlon II X2        | 21       | 0.75%   |
| AMD A8                  | 19       | 0.68%   |
| AMD A10                 | 19       | 0.68%   |
| AMD A4                  | 17       | 0.61%   |
| AMD Athlon              | 15       | 0.54%   |
| AMD Phenom II X6        | 14       | 0.5%    |
| AMD Athlon 64 X2        | 12       | 0.43%   |
| Intel Core 2            | 11       | 0.39%   |
| AMD Ryzen 5 PRO         | 9        | 0.32%   |
| AMD Athlon X4           | 9        | 0.32%   |
| AMD Athlon II X4        | 9        | 0.32%   |
| Intel Atom              | 8        | 0.29%   |
| Intel Pentium Dual      | 7        | 0.25%   |
| AMD Phenom              | 7        | 0.25%   |
| Intel Pentium Gold      | 6        | 0.21%   |
| AMD Ryzen 7 PRO         | 6        | 0.21%   |
| Intel Genuine           | 5        | 0.18%   |
| AMD Athlon II X3        | 5        | 0.18%   |
| Intel Pentium D         | 4        | 0.14%   |
| AMD Sempron             | 4        | 0.14%   |
| AMD Phenom II X2        | 3        | 0.11%   |
| AMD E1                  | 3        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 949      | 33.93%  |
| 6       | 666      | 23.81%  |
| 8       | 433      | 15.48%  |
| 2       | 411      | 14.69%  |
| 12      | 129      | 4.61%   |
| 16      | 87       | 3.11%   |
| 3       | 50       | 1.79%   |
| 1       | 28       | 1%      |
| 10      | 22       | 0.79%   |
| 24      | 9        | 0.32%   |
| 14      | 6        | 0.21%   |
| 32      | 3        | 0.11%   |
| 20      | 2        | 0.07%   |
| Unknown | 2        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2762     | 99.14%  |
| 2      | 24       | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1917     | 68.61%  |
| 1       | 875      | 31.32%  |
| Unknown | 2        | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2758     | 98.82%  |
| Unknown        | 33       | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1496     | 51.71%  |
| 0x08701021 | 145      | 5.01%   |
| 0x0800820d | 107      | 3.7%    |
| 0x306c3    | 106      | 3.66%   |
| 0x08701013 | 76       | 2.63%   |
| 0x306a9    | 69       | 2.39%   |
| 0x206a7    | 64       | 2.21%   |
| 0x906ea    | 59       | 2.04%   |
| 0x06000852 | 52       | 1.8%    |
| 0x506e3    | 51       | 1.76%   |
| 0x1067a    | 35       | 1.21%   |
| 0x08001138 | 33       | 1.14%   |
| 0x906e9    | 28       | 0.97%   |
| 0x0a201016 | 26       | 0.9%    |
| 0x010000c8 | 24       | 0.83%   |
| 0x306f2    | 23       | 0.8%    |
| 0x0a201009 | 22       | 0.76%   |
| 0x0a601203 | 21       | 0.73%   |
| 0x08108109 | 21       | 0.73%   |
| 0x206d7    | 20       | 0.69%   |
| 0x08001137 | 20       | 0.69%   |
| 0x08101016 | 19       | 0.66%   |
| 0x0a20120a | 17       | 0.59%   |
| 0x90672    | 15       | 0.52%   |
| 0x0a50000d | 15       | 0.52%   |
| 0x06003106 | 15       | 0.52%   |
| 0xa0655    | 14       | 0.48%   |
| 0x906ed    | 13       | 0.45%   |
| 0x106e5    | 13       | 0.45%   |
| 0x0a50000c | 13       | 0.45%   |
| 0x06001119 | 13       | 0.45%   |
| 0x08600106 | 11       | 0.38%   |
| 0xa0671    | 9        | 0.31%   |
| 0x206c2    | 9        | 0.31%   |
| 0x08001129 | 9        | 0.31%   |
| 0xa0653    | 8        | 0.28%   |
| 0x906ec    | 8        | 0.28%   |
| 0x906eb    | 8        | 0.28%   |
| 0x6fd      | 8        | 0.28%   |
| 0x010000dc | 8        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 382      | 13.65%  |
| Haswell          | 285      | 10.18%  |
| KabyLake         | 274      | 9.79%   |
| Zen+             | 252      | 9%      |
| Zen 3            | 200      | 7.15%   |
| Zen              | 179      | 6.4%    |
| SandyBridge      | 168      | 6%      |
| IvyBridge        | 166      | 5.93%   |
| Piledriver       | 133      | 4.75%   |
| Skylake          | 122      | 4.36%   |
| Unknown          | 99       | 3.54%   |
| Penryn           | 97       | 3.47%   |
| K10              | 89       | 3.18%   |
| CometLake        | 61       | 2.18%   |
| Core             | 42       | 1.5%    |
| Westmere         | 35       | 1.25%   |
| Nehalem          | 35       | 1.25%   |
| Steamroller      | 27       | 0.96%   |
| Alderlake Hybrid | 27       | 0.96%   |
| Broadwell        | 20       | 0.71%   |
| Bulldozer        | 19       | 0.68%   |
| K8 Hammer        | 15       | 0.54%   |
| Icelake          | 10       | 0.36%   |
| Excavator        | 9        | 0.32%   |
| Silvermont       | 7        | 0.25%   |
| Goldmont plus    | 7        | 0.25%   |
| Bonnell          | 7        | 0.25%   |
| NetBurst         | 6        | 0.21%   |
| K10 Llano        | 6        | 0.21%   |
| Goldmont         | 6        | 0.21%   |
| Jaguar           | 4        | 0.14%   |
| Bobcat           | 4        | 0.14%   |
| TigerLake        | 2        | 0.07%   |
| Puma             | 2        | 0.07%   |
| Tremont          | 1        | 0.04%   |
| Gracemont        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1404     | 46.61%  |
| AMD                        | 1080     | 35.86%  |
| Intel                      | 526      | 17.46%  |
| Matrox Electronics Systems | 1        | 0.03%   |
| ATI Technologies           | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 252      | 8.09%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 100      | 3.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 97       | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 94       | 3.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 89       | 2.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 66       | 2.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 60       | 1.93%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 55       | 1.77%   |
| Nvidia GK208B [GeForce GT 710]                                              | 55       | 1.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 51       | 1.64%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 48       | 1.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 44       | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 43       | 1.38%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 43       | 1.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 41       | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 38       | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 1.19%   |
| Intel HD Graphics 530                                                       | 36       | 1.16%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 35       | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 35       | 1.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 34       | 1.09%   |
| AMD Raphael                                                                 | 33       | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 32       | 1.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 32       | 1.03%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 31       | 1%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 29       | 0.93%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 28       | 0.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 28       | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 27       | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 25       | 0.8%    |
| Intel HD Graphics 630                                                       | 25       | 0.8%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 25       | 0.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 24       | 0.77%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 23       | 0.74%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 23       | 0.74%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 22       | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 22       | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 21       | 0.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 21       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1273     | 44.97%  |
| 1 x AMD            | 964      | 34.05%  |
| 1 x Intel          | 391      | 13.81%  |
| AMD + Nvidia       | 55       | 1.94%   |
| 2 x AMD            | 50       | 1.77%   |
| Intel + Nvidia     | 50       | 1.77%   |
| 2 x Nvidia         | 27       | 0.95%   |
| Intel + AMD        | 17       | 0.6%    |
| 2 x Intel          | 1        | 0.04%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1660     | 58.8%   |
| Proprietary | 1149     | 40.7%   |
| Unknown     | 14       | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1163     | 40.41%  |
| 7.01-8.0   | 434      | 15.08%  |
| 1.01-2.0   | 334      | 11.61%  |
| 3.01-4.0   | 295      | 10.25%  |
| 5.01-6.0   | 189      | 6.57%   |
| 0.51-1.0   | 161      | 5.59%   |
| 8.01-16.0  | 140      | 4.86%   |
| 0.01-0.5   | 87       | 3.02%   |
| 2.01-3.0   | 49       | 1.7%    |
| 16.01-24.0 | 24       | 0.83%   |
| 4.01-5.0   | 2        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 532      | 15.89%  |
| Goldstar             | 360      | 10.75%  |
| Dell                 | 309      | 9.23%   |
| Acer                 | 265      | 7.91%   |
| AOC                  | 206      | 6.15%   |
| BenQ                 | 193      | 5.76%   |
| Ancor Communications | 186      | 5.55%   |
| Hewlett-Packard      | 162      | 4.84%   |
| Philips              | 135      | 4.03%   |
| LG Electronics       | 114      | 3.4%    |
| ViewSonic            | 77       | 2.3%    |
| ASUSTek Computer     | 75       | 2.24%   |
| Lenovo               | 51       | 1.52%   |
| Iiyama               | 51       | 1.52%   |
| Unknown              | 49       | 1.46%   |
| Unknown              | 42       | 1.25%   |
| Sony                 | 29       | 0.87%   |
| MSI                  | 22       | 0.66%   |
| Vizio                | 21       | 0.63%   |
| Gigabyte Technology  | 21       | 0.63%   |
| Eizo                 | 19       | 0.57%   |
| Fujitsu Siemens      | 18       | 0.54%   |
| AUS                  | 17       | 0.51%   |
| Sceptre Tech         | 16       | 0.48%   |
| NEC Computers        | 15       | 0.45%   |
| Idek Iiyama          | 15       | 0.45%   |
| Medion               | 13       | 0.39%   |
| Vestel Elektronik    | 10       | 0.3%    |
| Sharp                | 10       | 0.3%    |
| Panasonic            | 9        | 0.27%   |
| Microstep            | 9        | 0.27%   |
| Lenovo Group Limited | 8        | 0.24%   |
| HannStar             | 8        | 0.24%   |
| Toshiba              | 7        | 0.21%   |
| Pixio                | 7        | 0.21%   |
| Mi                   | 6        | 0.18%   |
| KTC                  | 6        | 0.18%   |
| HPN                  | 6        | 0.18%   |
| Apple                | 6        | 0.18%   |
| VIZ                  | 5        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 42       | 1.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 22       | 0.6%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 21       | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 20       | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 17       | 0.47%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 15       | 0.41%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 13       | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 11       | 0.3%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 10       | 0.27%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 10       | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 9        | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 9        | 0.25%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 9        | 0.25%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                | 8        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 8        | 0.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 8        | 0.22%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                       | 8        | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 8        | 0.22%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 7        | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 7        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 7        | 0.19%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 7        | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 7        | 0.19%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 7        | 0.19%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 7        | 0.19%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 6        | 0.16%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 6        | 0.16%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                   | 6        | 0.16%   |
| Goldstar FHD GSM5B54 1920x1080 480x270mm 21.7-inch                     | 6        | 0.16%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                   | 6        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 6        | 0.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 6        | 0.16%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 0.16%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                         | 6        | 0.16%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 6        | 0.16%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6        | 0.16%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch  | 6        | 0.16%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 6        | 0.16%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                 | 5        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1406     | 43.06%  |
| 2560x1440 (QHD)    | 331      | 10.14%  |
| 3840x2160 (4K)     | 313      | 9.59%   |
| Unknown            | 186      | 5.7%    |
| 1280x1024 (SXGA)   | 132      | 4.04%   |
| 1680x1050 (WSXGA+) | 123      | 3.77%   |
| 3440x1440          | 90       | 2.76%   |
| 1366x768 (WXGA)    | 85       | 2.6%    |
| 1920x1200 (WUXGA)  | 84       | 2.57%   |
| 1440x900 (WXGA+)   | 80       | 2.45%   |
| 3840x1080          | 71       | 2.17%   |
| 2560x1080          | 71       | 2.17%   |
| 1600x900 (HD+)     | 65       | 1.99%   |
| 1360x768           | 29       | 0.89%   |
| 5120x1440          | 15       | 0.46%   |
| 4480x1440          | 14       | 0.43%   |
| 1920x540           | 11       | 0.34%   |
| 1280x720 (HD)      | 11       | 0.34%   |
| 5760x1080          | 10       | 0.31%   |
| 1024x768 (XGA)     | 10       | 0.31%   |
| 5760x2160          | 7        | 0.21%   |
| 3600x1080          | 7        | 0.21%   |
| 2560x1600          | 7        | 0.21%   |
| 3840x1600          | 6        | 0.18%   |
| 3360x1080          | 5        | 0.15%   |
| 3200x1080          | 5        | 0.15%   |
| 1600x1200          | 5        | 0.15%   |
| 7680x2160          | 4        | 0.12%   |
| 7680x1080          | 4        | 0.12%   |
| 6400x2160          | 4        | 0.12%   |
| 3840x1200          | 4        | 0.12%   |
| 3520x1080          | 4        | 0.12%   |
| 3360x1050          | 3        | 0.09%   |
| 3286x1080          | 3        | 0.09%   |
| 2288x1287          | 3        | 0.09%   |
| 6000x1440          | 2        | 0.06%   |
| 5504x1440          | 2        | 0.06%   |
| 5120x1080          | 2        | 0.06%   |
| 4480x1080          | 2        | 0.06%   |
| 4240x1440          | 2        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 578      | 17.94%  |
| 27      | 459      | 14.25%  |
| 24      | 451      | 14%     |
| 23      | 352      | 10.93%  |
| 21      | 322      | 10%     |
| 31      | 140      | 4.35%   |
| 19      | 137      | 4.25%   |
| 34      | 124      | 3.85%   |
| 22      | 86       | 2.67%   |
| 18      | 79       | 2.45%   |
| 20      | 71       | 2.2%    |
| 17      | 59       | 1.83%   |
| 84      | 38       | 1.18%   |
| 40      | 31       | 0.96%   |
| 54      | 25       | 0.78%   |
| 72      | 24       | 0.75%   |
| 32      | 23       | 0.71%   |
| 25      | 21       | 0.65%   |
| 15      | 17       | 0.53%   |
| 28      | 16       | 0.5%    |
| 65      | 13       | 0.4%    |
| 48      | 13       | 0.4%    |
| 42      | 10       | 0.31%   |
| 33      | 10       | 0.31%   |
| 26      | 9        | 0.28%   |
| 49      | 8        | 0.25%   |
| 43      | 8        | 0.25%   |
| 37      | 8        | 0.25%   |
| 46      | 7        | 0.22%   |
| 35      | 7        | 0.22%   |
| 29      | 7        | 0.22%   |
| 14      | 7        | 0.22%   |
| 12      | 7        | 0.22%   |
| 39      | 6        | 0.19%   |
| 36      | 5        | 0.16%   |
| 60      | 4        | 0.12%   |
| 52      | 4        | 0.12%   |
| 16      | 4        | 0.12%   |
| 142     | 3        | 0.09%   |
| 74      | 3        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1129     | 36.57%  |
| 401-500        | 602      | 19.5%   |
| Unknown        | 578      | 18.72%  |
| 601-700        | 208      | 6.74%   |
| 701-800        | 162      | 5.25%   |
| 351-400        | 89       | 2.88%   |
| 1001-1500      | 82       | 2.66%   |
| 301-350        | 72       | 2.33%   |
| 1501-2000      | 69       | 2.24%   |
| 801-900        | 57       | 1.85%   |
| 901-1000       | 19       | 0.62%   |
| 201-300        | 17       | 0.55%   |
| More than 2000 | 3        | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1753     | 60.14%  |
| Unknown | 543      | 18.63%  |
| 16/10   | 281      | 9.64%   |
| 21/9    | 137      | 4.7%    |
| 5/4     | 123      | 4.22%   |
| 4/3     | 31       | 1.06%   |
| 3/2     | 19       | 0.65%   |
| 32/9    | 13       | 0.45%   |
| 6/5     | 5        | 0.17%   |
| 1.00    | 4        | 0.14%   |
| 1.96    | 2        | 0.07%   |
| 3.20    | 1        | 0.03%   |
| 1.03    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |
| 0.56    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 971      | 30.84%  |
| Unknown        | 578      | 18.36%  |
| 301-350        | 463      | 14.7%   |
| 351-500        | 320      | 10.16%  |
| 151-200        | 274      | 8.7%    |
| 251-300        | 158      | 5.02%   |
| More than 1000 | 132      | 4.19%   |
| 141-150        | 111      | 3.52%   |
| 501-1000       | 95       | 3.02%   |
| 101-110        | 21       | 0.67%   |
| 131-140        | 9        | 0.29%   |
| 71-80          | 7        | 0.22%   |
| 81-90          | 3        | 0.1%    |
| 51-60          | 2        | 0.06%   |
| 111-120        | 2        | 0.06%   |
| 91-100         | 2        | 0.06%   |
| 121-130        | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1573     | 52.63%  |
| Unknown | 578      | 19.34%  |
| 101-120 | 566      | 18.94%  |
| 121-160 | 113      | 3.78%   |
| 1-50    | 104      | 3.48%   |
| 161-240 | 55       | 1.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2051     | 71.86%  |
| 2     | 659      | 23.09%  |
| 3     | 97       | 3.4%    |
| 0     | 37       | 1.3%    |
| 4     | 10       | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1721     | 42.93%  |
| Intel                                  | 1257     | 31.35%  |
| Qualcomm Atheros                       | 201      | 5.01%   |
| Broadcom                               | 110      | 2.74%   |
| TP-Link                                | 101      | 2.52%   |
| Ralink Technology                      | 99       | 2.47%   |
| MediaTek                               | 64       | 1.6%    |
| Microsoft                              | 46       | 1.15%   |
| Aquantia                               | 33       | 0.82%   |
| Nvidia                                 | 32       | 0.8%    |
| Ralink                                 | 29       | 0.72%   |
| Qualcomm Atheros Communications        | 26       | 0.65%   |
| Samsung Electronics                    | 25       | 0.62%   |
| Xiaomi                                 | 21       | 0.52%   |
| D-Link                                 | 17       | 0.42%   |
| ASUSTek Computer                       | 17       | 0.42%   |
| NetGear                                | 16       | 0.4%    |
| Marvell Technology Group               | 16       | 0.4%    |
| Huawei Technologies                    | 13       | 0.32%   |
| Broadcom Limited                       | 13       | 0.32%   |
| Linksys                                | 11       | 0.27%   |
| D-Link System                          | 9        | 0.22%   |
| Microchip Technology                   | 8        | 0.2%    |
| Mellanox Technologies                  | 8        | 0.2%    |
| Edimax Technology                      | 7        | 0.17%   |
| Motorola PCS                           | 6        | 0.15%   |
| ZyXEL Communications                   | 5        | 0.12%   |
| ASIX Electronics                       | 5        | 0.12%   |
| Qualcomm                               | 4        | 0.1%    |
| OPPO Electronics                       | 4        | 0.1%    |
| InterBiometrics                        | 4        | 0.1%    |
| Google                                 | 4        | 0.1%    |
| T & A Mobile Phones                    | 3        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.07%   |
| SEGGER                                 | 3        | 0.07%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.07%   |
| JMicron Technology                     | 3        | 0.07%   |
| IMC Networks                           | 3        | 0.07%   |
| HMD Global                             | 3        | 0.07%   |
| Belkin Components                      | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1385     | 30.01%  |
| Intel I211 Gigabit Network Connection                             | 301      | 6.52%   |
| Intel Wi-Fi 6 AX200                                               | 204      | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 190      | 4.12%   |
| Intel Ethernet Connection (2) I219-V                              | 127      | 2.75%   |
| Intel Ethernet Controller I225-V                                  | 102      | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 84       | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 69       | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 61       | 1.32%   |
| Intel Wireless-AC 9260                                            | 53       | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 52       | 1.13%   |
| Intel Ethernet Connection (2) I218-V                              | 46       | 1%      |
| Intel Ethernet Connection I217-LM                                 | 44       | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 41       | 0.89%   |
| Ralink MT7601U Wireless Adapter                                   | 34       | 0.74%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 34       | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 33       | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33       | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31       | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 30       | 0.65%   |
| Realtek 802.11ac NIC                                              | 29       | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28       | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 26       | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                               | 26       | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 26       | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 26       | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25       | 0.54%   |
| Intel Wireless 7265                                               | 24       | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 23       | 0.5%    |
| Intel Wireless 8265 / 8275                                        | 23       | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 21       | 0.46%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 20       | 0.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 20       | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19       | 0.41%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter      | 19       | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 18       | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18       | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 527      | 36.29%  |
| Realtek Semiconductor                 | 284      | 19.56%  |
| Qualcomm Atheros                      | 101      | 6.96%   |
| TP-Link                               | 100      | 6.89%   |
| Ralink Technology                     | 99       | 6.82%   |
| Broadcom                              | 72       | 4.96%   |
| MediaTek                              | 58       | 3.99%   |
| Microsoft                             | 46       | 3.17%   |
| Ralink                                | 29       | 2%      |
| Qualcomm Atheros Communications       | 26       | 1.79%   |
| D-Link                                | 17       | 1.17%   |
| ASUSTek Computer                      | 17       | 1.17%   |
| NetGear                               | 16       | 1.1%    |
| Linksys                               | 11       | 0.76%   |
| Edimax Technology                     | 6        | 0.41%   |
| D-Link System                         | 6        | 0.41%   |
| ZyXEL Communications                  | 5        | 0.34%   |
| Broadcom Limited                      | 5        | 0.34%   |
| IMC Networks                          | 3        | 0.21%   |
| Belkin Components                     | 3        | 0.21%   |
| AVM                                   | 3        | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.21%   |
| ZyDAS                                 | 2        | 0.14%   |
| Xiaomi                                | 2        | 0.14%   |
| Tenda                                 | 2        | 0.14%   |
| Mercucys                              | 2        | 0.14%   |
| Wacom                                 | 1        | 0.07%   |
| Senao                                 | 1        | 0.07%   |
| Samsung Electronics                   | 1        | 0.07%   |
| Philips (or NXP)                      | 1        | 0.07%   |
| Marvell Technology Group              | 1        | 0.07%   |
| Fujitsu Siemens Computers             | 1        | 0.07%   |
| Encore Electronics                    | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 204      | 13.92%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 69       | 4.71%   |
| Intel Wireless-AC 9260                                         | 53       | 3.62%   |
| Ralink MT7601U Wireless Adapter                                | 34       | 2.32%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 34       | 2.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 33       | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33       | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 31       | 2.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 30       | 2.05%   |
| Realtek 802.11ac NIC                                           | 29       | 1.98%   |
| Qualcomm Atheros AR9271 802.11n                                | 26       | 1.77%   |
| Microsoft Xbox 360 Wireless Adapter                            | 26       | 1.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 26       | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25       | 1.71%   |
| Intel Wireless 7265                                            | 24       | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 23       | 1.57%   |
| Intel Wireless 8265 / 8275                                     | 23       | 1.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 20       | 1.36%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 19       | 1.3%    |
| Ralink RT5370 Wireless Adapter                                 | 18       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18       | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 17       | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16       | 1.09%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 1.09%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 15       | 1.02%   |
| Intel Wireless 3165                                            | 14       | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 0.89%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 13       | 0.89%   |
| Intel Wireless 7260                                            | 13       | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 11       | 0.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.75%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 11       | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 10       | 0.68%   |
| TP-Link 802.11ac NIC                                           | 10       | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.68%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 9        | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 9        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1625     | 54.38%  |
| Intel                                  | 1010     | 33.8%   |
| Qualcomm Atheros                       | 115      | 3.85%   |
| Broadcom                               | 41       | 1.37%   |
| Aquantia                               | 33       | 1.1%    |
| Nvidia                                 | 32       | 1.07%   |
| Xiaomi                                 | 19       | 0.64%   |
| Marvell Technology Group               | 15       | 0.5%    |
| Samsung Electronics                    | 14       | 0.47%   |
| Huawei Technologies                    | 11       | 0.37%   |
| Mellanox Technologies                  | 8        | 0.27%   |
| Broadcom Limited                       | 8        | 0.27%   |
| ASIX Electronics                       | 5        | 0.17%   |
| OPPO Electronics                       | 4        | 0.13%   |
| MediaTek                               | 4        | 0.13%   |
| Google                                 | 4        | 0.13%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.1%    |
| Qualcomm                               | 3        | 0.1%    |
| Motorola PCS                           | 3        | 0.1%    |
| JMicron Technology                     | 3        | 0.1%    |
| HMD Global                             | 3        | 0.1%    |
| D-Link System                          | 3        | 0.1%    |
| T & A Mobile Phones                    | 2        | 0.07%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.07%   |
| National Semiconductor                 | 2        | 0.07%   |
| DisplayLink                            | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| VIA Technologies                       | 1        | 0.03%   |
| TP-Link                                | 1        | 0.03%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |
| LG Electronics                         | 1        | 0.03%   |
| ICS Advent                             | 1        | 0.03%   |
| Foxconn / Hon Hai                      | 1        | 0.03%   |
| Edimax Technology                      | 1        | 0.03%   |
| Apple                                  | 1        | 0.03%   |
| Accton Technology                      | 1        | 0.03%   |
| 3Com                                   | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1385     | 44.79%  |
| Intel I211 Gigabit Network Connection                             | 301      | 9.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 190      | 6.14%   |
| Intel Ethernet Connection (2) I219-V                              | 127      | 4.11%   |
| Intel Ethernet Controller I225-V                                  | 102      | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 84       | 2.72%   |
| Intel Ethernet Connection (7) I219-V                              | 61       | 1.97%   |
| Intel 82579V Gigabit Network Connection                           | 52       | 1.68%   |
| Intel Ethernet Connection (2) I218-V                              | 46       | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 44       | 1.42%   |
| Intel Ethernet Connection I217-V                                  | 41       | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 1.07%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28       | 0.91%   |
| Intel 82574L Gigabit Network Connection                           | 26       | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 21       | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 20       | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19       | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 17       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 16       | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14       | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 14       | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 13       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 13       | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.36%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10       | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 9        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.26%   |
| Realtek Killer E3000 2.5GbE Controller                            | 8        | 0.26%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.23%   |
| Huawei MAR-LX1M                                                   | 7        | 0.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7        | 0.23%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2754     | 66.36%  |
| WiFi     | 1342     | 32.34%  |
| Modem    | 45       | 1.08%   |
| Unknown  | 9        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2214     | 75.98%  |
| WiFi     | 699      | 23.99%  |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1744     | 61.98%  |
| 2     | 905      | 32.16%  |
| 3     | 125      | 4.44%   |
| 0     | 22       | 0.78%   |
| 5     | 8        | 0.28%   |
| 4     | 8        | 0.28%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2293     | 80.77%  |
| Yes  | 546      | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 498      | 40.06%  |
| Cambridge Silicon Radio         | 337      | 27.11%  |
| ASUSTek Computer                | 101      | 8.13%   |
| Realtek Semiconductor           | 85       | 6.84%   |
| Broadcom                        | 62       | 4.99%   |
| MediaTek                        | 25       | 2.01%   |
| TP-Link                         | 20       | 1.61%   |
| Qualcomm Atheros Communications | 17       | 1.37%   |
| IMC Networks                    | 17       | 1.37%   |
| Foxconn / Hon Hai               | 15       | 1.21%   |
| Apple                           | 15       | 1.21%   |
| Edimax Technology               | 11       | 0.88%   |
| Realtek                         | 6        | 0.48%   |
| Dynex                           | 6        | 0.48%   |
| HTC (High Tech Computer)        | 5        | 0.4%    |
| Lite-On Technology              | 4        | 0.32%   |
| Integrated System Solution      | 4        | 0.32%   |
| Conwise Technology              | 4        | 0.32%   |
| SINO WEALTH                     | 3        | 0.24%   |
| Belkin Components               | 3        | 0.24%   |
| Ralink                          | 2        | 0.16%   |
| Sitecom Europe                  | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| D-Link                          | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 337      | 27%     |
| Intel AX200 Bluetooth                                                | 189      | 15.14%  |
| Intel Bluetooth wireless interface                                   | 81       | 6.49%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 68       | 5.45%   |
| Realtek Bluetooth Radio                                              | 66       | 5.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 53       | 4.25%   |
| Intel Bluetooth Device                                               | 44       | 3.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 40       | 3.21%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 36       | 2.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 35       | 2.8%    |
| Intel AX210 Bluetooth                                                | 28       | 2.24%   |
| MediaTek Wireless_Device                                             | 25       | 2%      |
| TP-Link UB500 Adapter                                                | 20       | 1.6%    |
| ASUS Bluetooth Device                                                | 19       | 1.52%   |
| ASUS Bluetooth Radio                                                 | 17       | 1.36%   |
| ASUS Bluetooth Adapter                                               | 14       | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 11       | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                                    | 11       | 0.88%   |
| IMC Networks Bluetooth Radio                                         | 10       | 0.8%    |
| Edimax Edimax Bluetooth Adapter                                      | 9        | 0.72%   |
| Qualcomm Atheros  Bluetooth Device                                   | 8        | 0.64%   |
| Broadcom BCM20702A0                                                  | 7        | 0.56%   |
| Apple Bluetooth USB Host Controller                                  | 7        | 0.56%   |
| Realtek Bluetooth Radio                                              | 6        | 0.48%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.48%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.48%   |
| Realtek Bluetooth 5.1 Radio                                          | 5        | 0.4%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.32%   |
| Conwise CW6622                                                       | 4        | 0.32%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.32%   |
| ASUS BCM20702A0                                                      | 4        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 4        | 0.32%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.24%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.24%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.24%   |
| IMC Networks Wireless_Device                                         | 3        | 0.24%   |
| IMC Networks BCM20702A0                                              | 3        | 0.24%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 3        | 0.24%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 1605     | 29.4%   |
| Intel                    | 1385     | 25.37%  |
| Nvidia                   | 1348     | 24.69%  |
| C-Media Electronics      | 193      | 3.54%   |
| Logitech                 | 79       | 1.45%   |
| Creative Labs            | 71       | 1.3%    |
| Kingston Technology      | 53       | 0.97%   |
| JMTek                    | 44       | 0.81%   |
| Texas Instruments        | 41       | 0.75%   |
| ASUSTek Computer         | 38       | 0.7%    |
| Corsair                  | 36       | 0.66%   |
| Focusrite-Novation       | 34       | 0.62%   |
| SteelSeries ApS          | 32       | 0.59%   |
| Creative Technology      | 32       | 0.59%   |
| Razer USA                | 29       | 0.53%   |
| Blue Microphones         | 27       | 0.49%   |
| Generalplus Technology   | 24       | 0.44%   |
| BEHRINGER International  | 22       | 0.4%    |
| Sony                     | 15       | 0.27%   |
| Plantronics              | 15       | 0.27%   |
| Realtek Semiconductor    | 12       | 0.22%   |
| GYROCOM C&C              | 12       | 0.22%   |
| Micro Star International | 11       | 0.2%    |
| GN Netcom                | 11       | 0.2%    |
| VIA Technologies         | 9        | 0.16%   |
| Samson Technologies      | 9        | 0.16%   |
| M-Audio                  | 9        | 0.16%   |
| Turtle Beach             | 8        | 0.15%   |
| RODE Microphones         | 8        | 0.15%   |
| Giga-Byte Technology     | 8        | 0.15%   |
| DSEA A/S                 | 8        | 0.15%   |
| Dell                     | 8        | 0.15%   |
| Audio-Technica           | 8        | 0.15%   |
| XMOS                     | 7        | 0.13%   |
| SAVITECH                 | 7        | 0.13%   |
| Microsoft                | 7        | 0.13%   |
| Elgato Systems           | 7        | 0.13%   |
| Yamaha                   | 6        | 0.11%   |
| DCMT Technology          | 6        | 0.11%   |
| Astro Gaming             | 6        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 487      | 7.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 321      | 5.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 256      | 3.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 199      | 3.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 182      | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 178      | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 163      | 2.54%   |
| Intel 200 Series PCH HD Audio                                              | 146      | 2.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 136      | 2.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 129      | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 122      | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 121      | 1.89%   |
| AMD Navi 10 HDMI Audio                                                     | 121      | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 119      | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 110      | 1.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 104      | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 103      | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 82       | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                              | 79       | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 76       | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 74       | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71       | 1.11%   |
| AMD FCH Azalia Controller                                                  | 71       | 1.11%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 67       | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 64       | 1%      |
| Nvidia GM204 High Definition Audio Controller                              | 64       | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 64       | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 64       | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 62       | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 59       | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 56       | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 48       | 0.75%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 48       | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 47       | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 44       | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 44       | 0.69%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 44       | 0.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 38       | 0.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 37       | 0.58%   |
| Nvidia GA102 High Definition Audio Controller                              | 37       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 324      | 18.54%  |
| Kingston                     | 323      | 18.48%  |
| G.Skill                      | 246      | 14.07%  |
| Unknown                      | 200      | 11.44%  |
| Crucial                      | 155      | 8.87%   |
| Samsung Electronics          | 99       | 5.66%   |
| SK hynix                     | 66       | 3.78%   |
| Micron Technology            | 57       | 3.26%   |
| Team                         | 46       | 2.63%   |
| A-DATA Technology            | 44       | 2.52%   |
| Patriot                      | 32       | 1.83%   |
| Nanya Technology             | 12       | 0.69%   |
| GOODRAM                      | 12       | 0.69%   |
| Elpida                       | 11       | 0.63%   |
| Unknown                      | 11       | 0.63%   |
| Ramaxel Technology           | 8        | 0.46%   |
| Unknown (ABCD)               | 7        | 0.4%    |
| Patriot Memory (PDP Systems) | 5        | 0.29%   |
| Kllisre                      | 5        | 0.29%   |
| GeIL                         | 5        | 0.29%   |
| Transcend                    | 4        | 0.23%   |
| Smart                        | 4        | 0.23%   |
| Silicon Power                | 4        | 0.23%   |
| PNY                          | 4        | 0.23%   |
| Neo Forza                    | 4        | 0.23%   |
| AMD                          | 4        | 0.23%   |
| Kingmax                      | 3        | 0.17%   |
| CSX                          | 3        | 0.17%   |
| Apacer                       | 3        | 0.17%   |
| Unknown (08C8)               | 2        | 0.11%   |
| SemsoTai                     | 2        | 0.11%   |
| Qumo                         | 2        | 0.11%   |
| Patriot Memory               | 2        | 0.11%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x7FFF)             | 1        | 0.06%   |
| Unknown (0x0E9D)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 46       | 2.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 34       | 1.76%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 22       | 1.14%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 21       | 1.09%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 18       | 0.93%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 17       | 0.88%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 17       | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 16       | 0.83%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 15       | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 14       | 0.73%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.73%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s            | 13       | 0.67%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s             | 11       | 0.57%   |
| Unknown                                                        | 11       | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 10       | 0.52%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 10       | 0.52%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 1600MT/s         | 10       | 0.52%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 10       | 0.52%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 10       | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 9        | 0.47%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 9        | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 9        | 0.47%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s            | 9        | 0.47%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.47%   |
| Team RAM TEAMGROUP-UD4-3000 8192MB DIMM DDR4 3200MT/s          | 8        | 0.41%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 8        | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 7        | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.36%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s            | 7        | 0.36%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 7        | 0.36%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s            | 7        | 0.36%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 7        | 0.36%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 7        | 0.36%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 7        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 6        | 0.31%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 6        | 0.31%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.31%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 6        | 0.31%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 6        | 0.31%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 6        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 918      | 58.32%  |
| DDR3    | 431      | 27.38%  |
| Unknown | 82       | 5.21%   |
| DDR2    | 43       | 2.73%   |
| SDRAM   | 41       | 2.6%    |
| DDR5    | 36       | 2.29%   |
| DDR     | 11       | 0.7%    |
| LPDDR4  | 7        | 0.44%   |
| DRAM    | 3        | 0.19%   |
| LPDDR5  | 1        | 0.06%   |
| LPDDR3  | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1505     | 96.72%  |
| SODIMM       | 44       | 2.83%   |
| RIMM         | 3        | 0.19%   |
| FB-DIMM      | 3        | 0.19%   |
| Row Of Chips | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 752      | 44.21%  |
| 4096  | 334      | 19.64%  |
| 16384 | 330      | 19.4%   |
| 2048  | 148      | 8.7%    |
| 32768 | 93       | 5.47%   |
| 1024  | 39       | 2.29%   |
| 512   | 4        | 0.24%   |
| 3072  | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 236      | 13.45%  |
| 3200    | 212      | 12.09%  |
| 3600    | 187      | 10.66%  |
| 1333    | 148      | 8.44%   |
| 2400    | 92       | 5.25%   |
| 2667    | 76       | 4.33%   |
| 2133    | 74       | 4.22%   |
| 3400    | 61       | 3.48%   |
| 1867    | 55       | 3.14%   |
| 3000    | 51       | 2.91%   |
| 3733    | 47       | 2.68%   |
| 800     | 47       | 2.68%   |
| 3800    | 37       | 2.11%   |
| 3533    | 35       | 2%      |
| 1866    | 33       | 1.88%   |
| 3866    | 29       | 1.65%   |
| 667     | 29       | 1.65%   |
| 3466    | 27       | 1.54%   |
| 1800    | 27       | 1.54%   |
| 2933    | 22       | 1.25%   |
| 2666    | 22       | 1.25%   |
| Unknown | 17       | 0.97%   |
| 2800    | 14       | 0.8%    |
| 1066    | 14       | 0.8%    |
| 3666    | 12       | 0.68%   |
| 6000    | 10       | 0.57%   |
| 4800    | 8        | 0.46%   |
| 3534    | 8        | 0.46%   |
| 5200    | 7        | 0.4%    |
| 3334    | 7        | 0.4%    |
| 1334    | 7        | 0.4%    |
| 3266    | 6        | 0.34%   |
| 3100    | 6        | 0.34%   |
| 2448    | 6        | 0.34%   |
| 6400    | 5        | 0.29%   |
| 1067    | 5        | 0.29%   |
| 333     | 5        | 0.29%   |
| 3500    | 4        | 0.23%   |
| 2048    | 4        | 0.23%   |
| 1648    | 4        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 48       | 38.71%  |
| Brother Industries    | 23       | 18.55%  |
| Canon                 | 18       | 14.52%  |
| Seiko Epson           | 9        | 7.26%   |
| Samsung Electronics   | 7        | 5.65%   |
| Pantum                | 3        | 2.42%   |
| Apple                 | 3        | 2.42%   |
| Xerox                 | 2        | 1.61%   |
| Ricoh                 | 2        | 1.61%   |
| Prolific Technology   | 2        | 1.61%   |
| Zebra                 | 1        | 0.81%   |
| STMicroelectronics    | 1        | 0.81%   |
| QinHeng Electronics   | 1        | 0.81%   |
| Oki Data              | 1        | 0.81%   |
| Lexmark International | 1        | 0.81%   |
| Graphtec America      | 1        | 0.81%   |
| Dymo-CoStar           | 1        | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 3.2%    |
| HP LaserJet 1300                                          | 3        | 2.4%    |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.4%    |
| Xerox Phaser 3020                                         | 2        | 1.6%    |
| Seiko Epson L120 Series                                   | 2        | 1.6%    |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.6%    |
| Samsung M2020 Series                                      | 2        | 1.6%    |
| Prolific PL2305 Parallel Port                             | 2        | 1.6%    |
| HP Officejet 2620 series                                  | 2        | 1.6%    |
| HP LaserJet 3020                                          | 2        | 1.6%    |
| HP DeskJet 4530 series                                    | 2        | 1.6%    |
| HP DeskJet 3630 series                                    | 2        | 1.6%    |
| HP DeskJet 2600 series                                    | 2        | 1.6%    |
| HP DeskJet 2130 series                                    | 2        | 1.6%    |
| HP Color LaserJet Pro M453-4                              | 2        | 1.6%    |
| Canon PIXMA MX340                                         | 2        | 1.6%    |
| Canon PIXMA MP250                                         | 2        | 1.6%    |
| Canon PIXMA MG2500 Series                                 | 2        | 1.6%    |
| Canon MG5700 series                                       | 2        | 1.6%    |
| Canon LiDE 400                                            | 2        | 1.6%    |
| Canon G3010 series                                        | 2        | 1.6%    |
| Brother HL-5370DW series                                  | 2        | 1.6%    |
| Brother DCP-7040                                          | 2        | 1.6%    |
| Zebra ZTC ZC100                                           | 1        | 0.8%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.8%    |
| Seiko Epson XP-4100 Series                                | 1        | 0.8%    |
| Seiko Epson XP-3100 Series                                | 1        | 0.8%    |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.8%    |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.8%    |
| Seiko Epson L805 Series                                   | 1        | 0.8%    |
| Seiko Epson L6270 Series                                  | 1        | 0.8%    |
| Seiko Epson L3150 Series                                  | 1        | 0.8%    |
| Seiko Epson ET-4760 Series                                | 1        | 0.8%    |
| Samsung ML-1660 Series                                    | 1        | 0.8%    |
| Samsung CLX-3300 Series                                   | 1        | 0.8%    |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.8%    |
| Ricoh SP 112SU                                            | 1        | 0.8%    |
| Ricoh Printing Support                                    | 1        | 0.8%    |
| QinHeng CH340S                                            | 1        | 0.8%    |
| Pantum P2500W series                                      | 1        | 0.8%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 14       | 53.85%  |
| Seiko Epson        | 6        | 23.08%  |
| Hewlett-Packard    | 2        | 7.69%   |
| Visioneer          | 1        | 3.85%   |
| Ultima Electronics | 1        | 3.85%   |
| Mustek Systems     | 1        | 3.85%   |
| AGFA-Gevaert NV    | 1        | 3.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 15.38%  |
| Canon CanoScan LiDE 220                                                               | 3        | 11.54%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 7.69%   |
| Canon CanoScan LIDE 25                                                                | 2        | 7.69%   |
| Canon CanoScan LiDE 210                                                               | 2        | 7.69%   |
| Visioneer OneTouch 5300 USB                                                           | 1        | 3.85%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 3.85%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 3.85%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 3.85%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 3.85%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 3.85%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 3.85%   |
| HP ScanJet 3500c                                                                      | 1        | 3.85%   |
| HP ScanJet 3400cse                                                                    | 1        | 3.85%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 3.85%   |
| Canon CanoScan LiDE 90                                                                | 1        | 3.85%   |
| Canon CanoScan LiDE 120                                                               | 1        | 3.85%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 3.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 275      | 40.92%  |
| Microdia                      | 57       | 8.48%   |
| Microsoft                     | 50       | 7.44%   |
| Samsung Electronics           | 27       | 4.02%   |
| Z-Star Microelectronics       | 20       | 2.98%   |
| Sunplus Innovation Technology | 19       | 2.83%   |
| Creative Technology           | 12       | 1.79%   |
| Apple                         | 11       | 1.64%   |
| MacroSilicon                  | 10       | 1.49%   |
| GEMBIRD                       | 10       | 1.49%   |
| Cubeternet                    | 10       | 1.49%   |
| Generalplus Technology        | 8        | 1.19%   |
| Chicony Electronics           | 8        | 1.19%   |
| Realtek Semiconductor         | 7        | 1.04%   |
| ARC International             | 7        | 1.04%   |
| LG Electronics                | 6        | 0.89%   |
| KYE Systems (Mouse Systems)   | 6        | 0.89%   |
| Google                        | 6        | 0.89%   |
| Genesys Logic                 | 6        | 0.89%   |
| Aveo Technology               | 6        | 0.89%   |
| Valve Software                | 5        | 0.74%   |
| Pixart Imaging                | 5        | 0.74%   |
| Huawei Technologies           | 5        | 0.74%   |
| Creality 3D Technology        | 5        | 0.74%   |
| Sonix Technology              | 4        | 0.6%    |
| Razer USA                     | 4        | 0.6%    |
| Linux Foundation              | 4        | 0.6%    |
| Jieli Technology              | 4        | 0.6%    |
| Alcor Micro                   | 4        | 0.6%    |
| Xiongmai                      | 3        | 0.45%   |
| WCM_USB                       | 3        | 0.45%   |
| SunplusIT                     | 3        | 0.45%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.45%   |
| Philips (or NXP)              | 3        | 0.45%   |
| Elgato Systems                | 3        | 0.45%   |
| AVerMedia Technologies        | 3        | 0.45%   |
| Arkmicro Technologies         | 3        | 0.45%   |
| A4Tech                        | 3        | 0.45%   |
| Xiaomi                        | 2        | 0.3%    |
| WaveRider Communications      | 2        | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 62       | 9.17%   |
| Logitech HD Pro Webcam C920                           | 51       | 7.54%   |
| Samsung Galaxy series, misc. (MTP mode)               | 27       | 3.99%   |
| Logitech C922 Pro Stream Webcam                       | 24       | 3.55%   |
| Microsoft LifeCam HD-3000                             | 22       | 3.25%   |
| Microdia Webcam Vitade AF                             | 20       | 2.96%   |
| Logitech HD Webcam C615                               | 13       | 1.92%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.63%   |
| Microdia USB Camera                                   | 11       | 1.63%   |
| Logitech Webcam C310                                  | 11       | 1.63%   |
| Logitech Webcam C170                                  | 11       | 1.63%   |
| MacroSilicon USB3. 0 capture                          | 10       | 1.48%   |
| Logitech C920 PRO HD Webcam                           | 10       | 1.48%   |
| Logitech BRIO Ultra HD Webcam                         | 10       | 1.48%   |
| Microdia USB 2.0 Camera                               | 9        | 1.33%   |
| Apple iPhone 5/5C/5S/6/SE                             | 9        | 1.33%   |
| Logitech Webcam C930e                                 | 8        | 1.18%   |
| Logitech HD Webcam C525                               | 8        | 1.18%   |
| Sunplus Integrated_Webcam_HD                          | 7        | 1.04%   |
| Microsoft LifeCam VX-2000                             | 6        | 0.89%   |
| Logitech StreamCam                                    | 6        | 0.89%   |
| Logitech HD Webcam C510                               | 6        | 0.89%   |
| Logitech B525 HD Webcam                               | 6        | 0.89%   |
| GEMBIRD USB2.0 PC CAMERA                              | 6        | 0.89%   |
| ARC International Camera                              | 6        | 0.89%   |
| Valve Software 3D Camera                              | 5        | 0.74%   |
| Sunplus WEBCAM ESSENTIELB W1                          | 5        | 0.74%   |
| Microsoft LifeCam Cinema                              | 5        | 0.74%   |
| Logitech Webcam Pro 9000                              | 5        | 0.74%   |
| Logitech HD Webcam C910                               | 5        | 0.74%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.74%   |
| Huawei HiCamera                                       | 5        | 0.74%   |
| Creality 3D CREALITY CAM                              | 5        | 0.74%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.59%   |
| Microdia Camera                                       | 4        | 0.59%   |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.59%   |
| Linux Foundation EEM Gadget                           | 4        | 0.59%   |
| Jieli USB PHY 2.0                                     | 4        | 0.59%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.59%   |
| Genesys Logic Digital Microscope                      | 4        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 37.5%   |
| STMicroelectronics    | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| Futronic Technology   | 1        | 12.5%   |
| Dell                  | 1        | 12.5%   |
| AuthenTec             | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 37.5%   |
| STMicroelectronics Fingerprint Reader          | 1        | 12.5%   |
| LighTuning Fingerprint Sensor                  | 1        | 12.5%   |
| Futronic FS81 Fingerprint Scanner Module       | 1        | 12.5%   |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 12.5%   |
| AuthenTec AES1600                              | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 6        | 24%     |
| Alcor Micro                       | 5        | 20%     |
| VASCO Data Security International | 4        | 16%     |
| Realtek Semiconductor             | 4        | 16%     |
| OmniKey                           | 2        | 8%      |
| Yubico.com                        | 1        | 4%      |
| SCM Microsystems                  | 1        | 4%      |
| Cherry                            | 1        | 4%      |
| Bit4id                            | 1        | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 20%     |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 16%     |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 16%     |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8%      |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 1        | 4%      |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4%      |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4%      |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4%      |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 4%      |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4%      |
| Bit4id miniLector EVO                                           | 1        | 4%      |
| Alcor Micro Watchdata W 1981                                    | 1        | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2444     | 85.97%  |
| 1     | 358      | 12.59%  |
| 2     | 37       | 1.3%    |
| 3     | 4        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 164      | 38.5%   |
| Graphics card            | 67       | 15.73%  |
| Unassigned class         | 56       | 13.15%  |
| Camera                   | 22       | 5.16%   |
| Chipcard                 | 16       | 3.76%   |
| Multimedia controller    | 15       | 3.52%   |
| Net/ethernet             | 14       | 3.29%   |
| Sound                    | 13       | 3.05%   |
| Communication controller | 13       | 3.05%   |
| Bluetooth                | 11       | 2.58%   |
| Dvb card                 | 9        | 2.11%   |
| Storage/raid             | 7        | 1.64%   |
| Network                  | 6        | 1.41%   |
| Fingerprint reader       | 6        | 1.41%   |
| Storage/ide              | 2        | 0.47%   |
| Video                    | 1        | 0.23%   |
| Tv card                  | 1        | 0.23%   |
| Storage/ata              | 1        | 0.23%   |
| Storage                  | 1        | 0.23%   |
| Modem                    | 1        | 0.23%   |

