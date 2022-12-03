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

Total: 697

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Maximus VIII RANGER         | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Unknown       | 1.0                         | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| ASRock        | H77M                        | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Acer          | Nitro N50-610               | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| ASRock        | B550M-ITX/ac                | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| Gigabyte      | B550M DS3H                  | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Gigabyte      | 990FXA-UD3                  | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | X399 Taichi                 | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| MSI           | B85-G43                     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | 970A-G46                    | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Pegatron      | 2AD5                        | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| ASUSTek       | PRIME X570-PRO              | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Intel         | DQ35JO AAD82085-801         | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| ASUSTek       | GRYPHON Z87                 | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| HP            | 83E9                        | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| System76      | Thelio Mira                 | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| HP            | 1589                        | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| Minix         | NEO Z83-4 V1.1              | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| NZXT          | N7 B550                     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| ECS           | Nettle3                     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| System76      | Thelio thelio-r2            | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| ASUSTek       | M4N72-E                     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASRock        | B450M/ac                    | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Acer          | 1.0                         | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| Dell          | 088DT1 A01                  | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| HP            | 1497                        | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | 1497                        | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| ASRock        | B560 Steel Legend           | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASRock        | X570 Creator                | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| Dell          | 0KWVT8 A03                  | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| MSI           | FM2-A55M-E33                | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | Z170A PC MATE               | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| MSI           | Z87-G45 GAMING              | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASRock        | A320M                       | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | Z87-K                       | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| MSI           | 970A-G43                    | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.5-76051705-generic   | 155      | 27.1%   |
| 5.19.0-76051900-generic   | 140      | 24.48%  |
| 5.18.10-76051810-generic  | 70       | 12.24%  |
| 5.17.15-76051715-generic  | 65       | 11.36%  |
| 5.16.19-76051619-generic  | 40       | 6.99%   |
| 6.0.6-76060006-generic    | 38       | 6.64%   |
| 6.0.2-76060002-generic    | 23       | 4.02%   |
| 5.19.16-76051916-generic  | 17       | 2.97%   |
| 6.0.3-76060003-generic    | 13       | 2.27%   |
| 6.0.9-060009-generic      | 1        | 0.17%   |
| 6.0.8-x64v1-xanmod1       | 1        | 0.17%   |
| 6.0.6-060006-generic      | 1        | 0.17%   |
| 6.0.2-x64v1-xanmod1       | 1        | 0.17%   |
| 5.4.210-whitehax0r        | 1        | 0.17%   |
| 5.19.6-xanmod1-x64v2      | 1        | 0.17%   |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.17%   |
| 5.17.4-051704-generic     | 1        | 0.17%   |
| 5.17.14-xanmod1           | 1        | 0.17%   |
| 5.16.15-76051615-generic  | 1        | 0.17%   |
| 5.15.15-76051515-generic  | 1        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 155      | 27.1%   |
| 5.19.0  | 140      | 24.48%  |
| 5.18.10 | 70       | 12.24%  |
| 5.17.15 | 65       | 11.36%  |
| 5.16.19 | 40       | 6.99%   |
| 6.0.6   | 39       | 6.82%   |
| 6.0.2   | 24       | 4.2%    |
| 5.19.16 | 17       | 2.97%   |
| 6.0.3   | 13       | 2.27%   |
| 6.0.9   | 1        | 0.17%   |
| 6.0.8   | 1        | 0.17%   |
| 5.4.210 | 1        | 0.17%   |
| 5.19.6  | 1        | 0.17%   |
| 5.18.0  | 1        | 0.17%   |
| 5.17.4  | 1        | 0.17%   |
| 5.17.14 | 1        | 0.17%   |
| 5.16.15 | 1        | 0.17%   |
| 5.15.15 | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 215      | 38.26%  |
| 5.19    | 157      | 27.94%  |
| 6.0     | 76       | 13.52%  |
| 5.18    | 71       | 12.63%  |
| 5.16    | 41       | 7.3%    |
| 5.4     | 1        | 0.18%   |
| 5.15    | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 526      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 505      | 95.64%  |
| KDE5            | 13       | 2.46%   |
| X-Cinnamon      | 5        | 0.95%   |
| Unknown         | 2        | 0.38%   |
| LXQt            | 1        | 0.19%   |
| GNOME Flashback | 1        | 0.19%   |
| Cinnamon        | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 515      | 97.91%  |
| Wayland | 9        | 1.71%   |
| Tty     | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 442      | 84.03%  |
| GDM3    | 77       | 14.64%  |
| SDDM    | 4        | 0.76%   |
| GDM     | 2        | 0.38%   |
| LightDM | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 311      | 58.79%  |
| en_GB   | 34       | 6.43%   |
| pt_BR   | 30       | 5.67%   |
| de_DE   | 23       | 4.35%   |
| C       | 19       | 3.59%   |
| en_CA   | 15       | 2.84%   |
| fr_FR   | 13       | 2.46%   |
| en_AU   | 13       | 2.46%   |
| it_IT   | 10       | 1.89%   |
| pl_PL   | 8        | 1.51%   |
| es_ES   | 6        | 1.13%   |
| fi_FI   | 5        | 0.95%   |
| sv_SE   | 4        | 0.76%   |
| es_CL   | 4        | 0.76%   |
| nl_NL   | 3        | 0.57%   |
| en_IN   | 3        | 0.57%   |
| Unknown | 3        | 0.57%   |
| zh_TW   | 2        | 0.38%   |
| ru_RU   | 2        | 0.38%   |
| pt_PT   | 2        | 0.38%   |
| ja_JP   | 2        | 0.38%   |
| en_DK   | 2        | 0.38%   |
| de_AT   | 2        | 0.38%   |
| cs_CZ   | 2        | 0.38%   |
| ro_RO   | 1        | 0.19%   |
| nl_BE   | 1        | 0.19%   |
| nb_NO   | 1        | 0.19%   |
| fr_CH   | 1        | 0.19%   |
| fr_BE   | 1        | 0.19%   |
| es_UY   | 1        | 0.19%   |
| es_DO   | 1        | 0.19%   |
| en_IL   | 1        | 0.19%   |
| en_IE   | 1        | 0.19%   |
| en_FI   | 1        | 0.19%   |
| da_DK   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 452      | 85.93%  |
| EFI  | 74       | 14.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 500      | 95.06%  |
| Btrfs   | 13       | 2.47%   |
| Overlay | 12       | 2.28%   |
| Xfs     | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 440      | 83.65%  |
| GPT     | 81       | 15.4%   |
| MBR     | 5        | 0.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 507      | 96.39%  |
| Yes       | 19       | 3.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 470      | 89.35%  |
| Yes       | 56       | 10.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 159      | 30.23%  |
| Gigabyte Technology | 97       | 18.44%  |
| MSI                 | 80       | 15.21%  |
| ASRock              | 49       | 9.32%   |
| Dell                | 34       | 6.46%   |
| Hewlett-Packard     | 27       | 5.13%   |
| Lenovo              | 20       | 3.8%    |
| Intel               | 9        | 1.71%   |
| System76            | 6        | 1.14%   |
| Alienware           | 5        | 0.95%   |
| Unknown             | 5        | 0.95%   |
| Acer                | 4        | 0.76%   |
| Pegatron            | 3        | 0.57%   |
| MACHINIST           | 3        | 0.57%   |
| Foxconn             | 3        | 0.57%   |
| BESSTAR Tech        | 3        | 0.57%   |
| NZXT                | 2        | 0.38%   |
| Fujitsu             | 2        | 0.38%   |
| EVGA                | 2        | 0.38%   |
| ECS                 | 2        | 0.38%   |
| Supermicro          | 1        | 0.19%   |
| Soyo                | 1        | 0.19%   |
| SIEMENS             | 1        | 0.19%   |
| Positivo            | 1        | 0.19%   |
| Minix               | 1        | 0.19%   |
| Medion              | 1        | 0.19%   |
| LattePanda          | 1        | 0.19%   |
| Biostar             | 1        | 0.19%   |
| AZW                 | 1        | 0.19%   |
| Apple               | 1        | 0.19%   |
| Acidanthera         | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 11       | 2.09%   |
| ASUS TUF Gaming B550-PLUS         | 7        | 1.33%   |
| Gigabyte B450 AORUS M             | 6        | 1.14%   |
| ASUS ROG STRIX B550-F GAMING      | 6        | 1.14%   |
| Gigabyte X570 AORUS ELITE         | 5        | 0.95%   |
| ASUS ROG STRIX B550-I GAMING      | 5        | 0.95%   |
| ASUS ROG STRIX B450-F GAMING      | 5        | 0.95%   |
| Unknown                           | 5        | 0.95%   |
| System76 Thelio                   | 4        | 0.76%   |
| MSI MS-7B86                       | 4        | 0.76%   |
| Gigabyte B450M DS3H               | 4        | 0.76%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 4        | 0.76%   |
| ASUS PRIME B450M-A                | 4        | 0.76%   |
| MSI MS-7D54                       | 3        | 0.57%   |
| MSI MS-7D25                       | 3        | 0.57%   |
| MSI MS-7C56                       | 3        | 0.57%   |
| MSI MS-7C37                       | 3        | 0.57%   |
| MSI MS-7C35                       | 3        | 0.57%   |
| MSI MS-7C02                       | 3        | 0.57%   |
| MSI MS-7693                       | 3        | 0.57%   |
| HP Compaq Elite 8300 USDT         | 3        | 0.57%   |
| Gigabyte X570 AORUS MASTER        | 3        | 0.57%   |
| Gigabyte B550M DS3H               | 3        | 0.57%   |
| Gigabyte B550 AORUS ELITE V2      | 3        | 0.57%   |
| Dell OptiPlex 3020                | 3        | 0.57%   |
| ASUS TUF Gaming B550M-PLUS        | 3        | 0.57%   |
| ASUS ROG Maximus XI HERO          | 3        | 0.57%   |
| ASUS ROG CROSSHAIR VIII HERO      | 3        | 0.57%   |
| ASUS PRIME A320M-K                | 3        | 0.57%   |
| ASUS P6X58D PREMIUM               | 3        | 0.57%   |
| ASRock B450 Gaming K4             | 3        | 0.57%   |
| NZXT N7 B550                      | 2        | 0.38%   |
| MSI MS-7D32                       | 2        | 0.38%   |
| MSI MS-7D09                       | 2        | 0.38%   |
| MSI MS-7C91                       | 2        | 0.38%   |
| MSI MS-7C52                       | 2        | 0.38%   |
| MSI MS-7B89                       | 2        | 0.38%   |
| MSI MS-7B17                       | 2        | 0.38%   |
| MSI MS-7B12                       | 2        | 0.38%   |
| MSI MS-7A38                       | 2        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 52       | 9.89%   |
| ASUS PRIME             | 26       | 4.94%   |
| ASUS TUF               | 25       | 4.75%   |
| Lenovo ThinkCentre     | 14       | 2.66%   |
| Dell OptiPlex          | 14       | 2.66%   |
| Gigabyte X570          | 12       | 2.28%   |
| ASUS All               | 11       | 2.09%   |
| HP Compaq              | 10       | 1.9%    |
| Dell Precision         | 10       | 1.9%    |
| Gigabyte B450          | 9        | 1.71%   |
| HP EliteDesk           | 7        | 1.33%   |
| System76 Thelio        | 6        | 1.14%   |
| Gigabyte B550          | 6        | 1.14%   |
| Gigabyte B450M         | 6        | 1.14%   |
| Dell Inspiron          | 5        | 0.95%   |
| ASRock X570            | 5        | 0.95%   |
| ASRock B450            | 5        | 0.95%   |
| Alienware Aurora       | 5        | 0.95%   |
| Unknown                | 5        | 0.95%   |
| MSI MS-7B86            | 4        | 0.76%   |
| Gigabyte B550M         | 4        | 0.76%   |
| Dell XPS               | 4        | 0.76%   |
| ASRock B450M           | 4        | 0.76%   |
| MSI MS-7D54            | 3        | 0.57%   |
| MSI MS-7D25            | 3        | 0.57%   |
| MSI MS-7C56            | 3        | 0.57%   |
| MSI MS-7C37            | 3        | 0.57%   |
| MSI MS-7C35            | 3        | 0.57%   |
| MSI MS-7C02            | 3        | 0.57%   |
| MSI MS-7693            | 3        | 0.57%   |
| Lenovo IdeaCentre      | 3        | 0.57%   |
| HP ProDesk             | 3        | 0.57%   |
| Gigabyte H310M         | 3        | 0.57%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.57%   |
| Gigabyte AB350-Gaming  | 3        | 0.57%   |
| ASUS P6X58D            | 3        | 0.57%   |
| ASUS Maximus           | 3        | 0.57%   |
| NZXT N7                | 2        | 0.38%   |
| MSI MS-7D32            | 2        | 0.38%   |
| MSI MS-7D09            | 2        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 83       | 15.78%  |
| 2018 | 76       | 14.45%  |
| 2019 | 59       | 11.22%  |
| 2021 | 52       | 9.89%   |
| 2012 | 35       | 6.65%   |
| 2014 | 31       | 5.89%   |
| 2017 | 29       | 5.51%   |
| 2013 | 29       | 5.51%   |
| 2016 | 25       | 4.75%   |
| 2011 | 25       | 4.75%   |
| 2022 | 22       | 4.18%   |
| 2010 | 19       | 3.61%   |
| 2015 | 16       | 3.04%   |
| 2009 | 13       | 2.47%   |
| 2008 | 6        | 1.14%   |
| 2007 | 5        | 0.95%   |
| 2006 | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 526      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 525      | 99.81%  |
| Enabled  | 1        | 0.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 526      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 178      | 33.4%   |
| 32.01-64.0      | 144      | 27.02%  |
| 8.01-16.0       | 79       | 14.82%  |
| 4.01-8.0        | 46       | 8.63%   |
| 64.01-256.0     | 46       | 8.63%   |
| 3.01-4.0        | 25       | 4.69%   |
| 24.01-32.0      | 10       | 1.88%   |
| More than 256.0 | 3        | 0.56%   |
| 2.01-3.0        | 1        | 0.19%   |
| 1.01-2.0        | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 158      | 27.72%  |
| 4.01-8.0    | 155      | 27.19%  |
| 3.01-4.0    | 144      | 25.26%  |
| 1.01-2.0    | 64       | 11.23%  |
| 8.01-16.0   | 33       | 5.79%   |
| 16.01-24.0  | 10       | 1.75%   |
| 32.01-64.0  | 4        | 0.7%    |
| 24.01-32.0  | 1        | 0.18%   |
| 64.01-256.0 | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 171      | 32.26%  |
| 1      | 146      | 27.55%  |
| 3      | 110      | 20.75%  |
| 4      | 48       | 9.06%   |
| 5      | 25       | 4.72%   |
| 6      | 15       | 2.83%   |
| 7      | 6        | 1.13%   |
| 9      | 3        | 0.57%   |
| 10     | 2        | 0.38%   |
| 0      | 2        | 0.38%   |
| 19     | 1        | 0.19%   |
| 11     | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 379      | 71.92%  |
| Yes       | 148      | 28.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 519      | 98.67%  |
| No        | 7        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 295      | 55.77%  |
| No        | 234      | 44.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 293      | 55.49%  |
| Yes       | 235      | 44.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 200      | 37.81%  |
| Brazil       | 33       | 6.24%   |
| Germany      | 30       | 5.67%   |
| Canada       | 27       | 5.1%    |
| UK           | 24       | 4.54%   |
| Italy        | 21       | 3.97%   |
| Australia    | 18       | 3.4%    |
| France       | 17       | 3.21%   |
| Netherlands  | 12       | 2.27%   |
| Poland       | 11       | 2.08%   |
| Finland      | 10       | 1.89%   |
| Norway       | 9        | 1.7%    |
| Sweden       | 8        | 1.51%   |
| Spain        | 7        | 1.32%   |
| Greece       | 7        | 1.32%   |
| Austria      | 6        | 1.13%   |
| Switzerland  | 5        | 0.95%   |
| Portugal     | 5        | 0.95%   |
| Ireland      | 5        | 0.95%   |
| India        | 5        | 0.95%   |
| South Africa | 4        | 0.76%   |
| Russia       | 4        | 0.76%   |
| Romania      | 4        | 0.76%   |
| Mexico       | 4        | 0.76%   |
| Japan        | 4        | 0.76%   |
| Hong Kong    | 4        | 0.76%   |
| Chile        | 4        | 0.76%   |
| Belgium      | 4        | 0.76%   |
| Thailand     | 3        | 0.57%   |
| Philippines  | 3        | 0.57%   |
| Denmark      | 3        | 0.57%   |
| Czechia      | 3        | 0.57%   |
| Slovakia     | 2        | 0.38%   |
| Lithuania    | 2        | 0.38%   |
| Indonesia    | 2        | 0.38%   |
| Uruguay      | 1        | 0.19%   |
| Turkey       | 1        | 0.19%   |
| Tunisia      | 1        | 0.19%   |
| South Korea  | 1        | 0.19%   |
| Slovenia     | 1        | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 6        | 1.12%   |
| Seattle           | 5        | 0.93%   |
| San Francisco     | 5        | 0.93%   |
| Milan             | 5        | 0.93%   |
| Vienna            | 4        | 0.74%   |
| Sao Paulo         | 4        | 0.74%   |
| Rio de Janeiro    | 4        | 0.74%   |
| Helsinki          | 4        | 0.74%   |
| Sydney            | 3        | 0.56%   |
| Paris             | 3        | 0.56%   |
| Miami             | 3        | 0.56%   |
| Melbourne         | 3        | 0.56%   |
| Madrid            | 3        | 0.56%   |
| Dublin            | 3        | 0.56%   |
| Cleveland         | 3        | 0.56%   |
| Central           | 3        | 0.56%   |
| Brisbane          | 3        | 0.56%   |
| Bedford           | 3        | 0.56%   |
| Bargo             | 3        | 0.56%   |
| Athens            | 3        | 0.56%   |
| Adelaide          | 3        | 0.56%   |
| Zurich            | 2        | 0.37%   |
| Weston-super-Mare | 2        | 0.37%   |
| Weimar            | 2        | 0.37%   |
| Virginia Beach    | 2        | 0.37%   |
| Valparaíso       | 2        | 0.37%   |
| Turku             | 2        | 0.37%   |
| Trondheim         | 2        | 0.37%   |
| Toronto           | 2        | 0.37%   |
| Springfield       | 2        | 0.37%   |
| Sapporo           | 2        | 0.37%   |
| Rome              | 2        | 0.37%   |
| Richmond          | 2        | 0.37%   |
| Regina            | 2        | 0.37%   |
| Recife            | 2        | 0.37%   |
| Orange            | 2        | 0.37%   |
| Ogden             | 2        | 0.37%   |
| Nuremberg         | 2        | 0.37%   |
| Montreal          | 2        | 0.37%   |
| Merced            | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 195      | 297    | 18.01%  |
| Seagate                   | 175      | 256    | 16.16%  |
| WDC                       | 172      | 252    | 15.88%  |
| SanDisk                   | 71       | 84     | 6.56%   |
| Crucial                   | 65       | 100    | 6%      |
| Kingston                  | 54       | 68     | 4.99%   |
| Toshiba                   | 49       | 55     | 4.52%   |
| Hitachi                   | 22       | 30     | 2.03%   |
| Phison                    | 21       | 30     | 1.94%   |
| Intel                     | 19       | 21     | 1.75%   |
| A-DATA Technology         | 19       | 20     | 1.75%   |
| Micron/Crucial Technology | 16       | 19     | 1.48%   |
| Phison Electronics        | 14       | 22     | 1.29%   |
| Silicon Motion            | 13       | 18     | 1.2%    |
| PNY                       | 12       | 17     | 1.11%   |
| SPCC                      | 11       | 15     | 1.02%   |
| China                     | 11       | 14     | 1.02%   |
| Unknown                   | 10       | 21     | 0.92%   |
| SK hynix                  | 8        | 10     | 0.74%   |
| Micron Technology         | 8        | 10     | 0.74%   |
| Patriot                   | 7        | 8      | 0.65%   |
| OCZ                       | 7        | 9      | 0.65%   |
| HGST                      | 6        | 8      | 0.55%   |
| XPG                       | 5        | 6      | 0.46%   |
| Netac                     | 5        | 5      | 0.46%   |
| Team                      | 4        | 6      | 0.37%   |
| Realtek Semiconductor     | 4        | 4      | 0.37%   |
| Lexar                     | 4        | 4      | 0.37%   |
| JMicron Technology        | 4        | 13     | 0.37%   |
| Intenso                   | 4        | 4      | 0.37%   |
| Hewlett-Packard           | 4        | 4      | 0.37%   |
| Corsair                   | 4        | 6      | 0.37%   |
| Maxtor                    | 3        | 3      | 0.28%   |
| Apple                     | 3        | 3      | 0.28%   |
| WALRAM                    | 2        | 2      | 0.18%   |
| T-FORCE                   | 2        | 3      | 0.18%   |
| Mushkin                   | 2        | 3      | 0.18%   |
| MaxDigital                | 2        | 2      | 0.18%   |
| LITEON                    | 2        | 3      | 0.18%   |
| GOODRAM                   | 2        | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                           | 25       | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB                       | 21       | 1.64%   |
| Samsung NVMe SSD Drive 500GB                         | 18       | 1.41%   |
| Samsung SSD 860 EVO 1TB                              | 16       | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB                       | 14       | 1.1%    |
| SanDisk NVMe SSD Drive 1TB                           | 14       | 1.1%    |
| Samsung SSD 850 EVO 500GB                            | 14       | 1.1%    |
| Samsung SSD 850 EVO 250GB                            | 13       | 1.02%   |
| Kingston SA400S37240G 240GB SSD                      | 13       | 1.02%   |
| Crucial CT1000MX500SSD1 1TB                          | 13       | 1.02%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 10       | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB                       | 10       | 0.78%   |
| Samsung NVMe SSD Drive 2TB                           | 10       | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 10       | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                      | 9        | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB                       | 9        | 0.7%    |
| Samsung SSD 860 EVO 500GB                            | 9        | 0.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 8        | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                       | 8        | 0.63%   |
| SanDisk NVMe SSD Drive 500GB                         | 8        | 0.63%   |
| Phison E12 NVMe Controller 2TB                       | 8        | 0.63%   |
| Kingston SV300S37A120G 120GB SSD                     | 8        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                      | 8        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                         | 8        | 0.63%   |
| Crucial CT1000BX500SSD1 1TB                          | 8        | 0.63%   |
| Toshiba DT01ACA100 1TB                               | 7        | 0.55%   |
| Phison NVMe SSD Drive 1TB                            | 7        | 0.55%   |
| Micron/Crucial NVMe SSD Drive 1TB                    | 7        | 0.55%   |
| Crucial CT2000MX500SSD1 2TB                          | 7        | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 6        | 0.47%   |
| Seagate ST8000DM004-2CX188 8TB                       | 6        | 0.47%   |
| Seagate Expansion 1TB                                | 6        | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB                         | 6        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 6        | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 5        | 0.39%   |
| Toshiba HDWD120 2TB                                  | 5        | 0.39%   |
| Toshiba DT01ACA200 2TB                               | 5        | 0.39%   |
| Seagate ST31000528AS 1TB                             | 5        | 0.39%   |
| Seagate ST31000524AS 1TB                             | 5        | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 167      | 241    | 40.93%  |
| WDC                 | 141      | 201    | 34.56%  |
| Toshiba             | 44       | 50     | 10.78%  |
| Hitachi             | 22       | 30     | 5.39%   |
| Samsung Electronics | 16       | 21     | 3.92%   |
| HGST                | 6        | 8      | 1.47%   |
| Unknown             | 3        | 7      | 0.74%   |
| Apple               | 3        | 3      | 0.74%   |
| Maxtor              | 2        | 2      | 0.49%   |
| JMicron Technology  | 2        | 7      | 0.49%   |
| Fujitsu             | 1        | 2      | 0.25%   |
| ASMT                | 1        | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 94       | 135    | 24.48%  |
| Crucial             | 61       | 91     | 15.89%  |
| Kingston            | 46       | 56     | 11.98%  |
| WDC                 | 32       | 40     | 8.33%   |
| SanDisk             | 24       | 27     | 6.25%   |
| A-DATA Technology   | 16       | 17     | 4.17%   |
| PNY                 | 12       | 17     | 3.13%   |
| China               | 10       | 13     | 2.6%    |
| SPCC                | 9        | 10     | 2.34%   |
| Intel               | 8        | 8      | 2.08%   |
| Patriot             | 7        | 8      | 1.82%   |
| OCZ                 | 7        | 9      | 1.82%   |
| Netac               | 5        | 5      | 1.3%    |
| Team                | 4        | 6      | 1.04%   |
| SK hynix            | 4        | 5      | 1.04%   |
| Toshiba             | 3        | 3      | 0.78%   |
| Micron Technology   | 3        | 3      | 0.78%   |
| Lexar               | 3        | 3      | 0.78%   |
| Hewlett-Packard     | 3        | 3      | 0.78%   |
| Seagate             | 2        | 2      | 0.52%   |
| Mushkin             | 2        | 3      | 0.52%   |
| Intenso             | 2        | 2      | 0.52%   |
| GOODRAM             | 2        | 2      | 0.52%   |
| Corsair             | 2        | 3      | 0.52%   |
| Yeyian              | 1        | 1      | 0.26%   |
| Verbatim            | 1        | 2      | 0.26%   |
| Transcend           | 1        | 2      | 0.26%   |
| TO Exter            | 1        | 1      | 0.26%   |
| TCSUNBOW            | 1        | 1      | 0.26%   |
| PNY USB             | 1        | 1      | 0.26%   |
| Plextor             | 1        | 1      | 0.26%   |
| Maxtor              | 1        | 1      | 0.26%   |
| LITEON              | 1        | 2      | 0.26%   |
| KingDian            | 1        | 2      | 0.26%   |
| JMicron Technology  | 1        | 1      | 0.26%   |
| HS-SSD-E100N        | 1        | 1      | 0.26%   |
| Gigabyte Technology | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| FORESEE             | 1        | 2      | 0.26%   |
| Fanxiang            | 1        | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 316      | 573    | 34.84%  |
| SSD     | 312      | 500    | 34.4%   |
| NVMe    | 245      | 385    | 27.01%  |
| Unknown | 30       | 47     | 3.31%   |
| MMC     | 4        | 5      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 453      | 1047   | 60.72%  |
| NVMe | 245      | 384    | 32.84%  |
| SAS  | 44       | 74     | 5.9%    |
| MMC  | 4        | 5      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 296      | 473    | 41.75%  |
| 0.51-1.0   | 228      | 337    | 32.16%  |
| 1.01-2.0   | 105      | 135    | 14.81%  |
| 3.01-4.0   | 31       | 46     | 4.37%   |
| 4.01-10.0  | 27       | 46     | 3.81%   |
| 2.01-3.0   | 19       | 25     | 2.68%   |
| 10.01-20.0 | 3        | 11     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 125      | 23.15%  |
| 101-250        | 98       | 18.15%  |
| 251-500        | 94       | 17.41%  |
| 1001-2000      | 88       | 16.3%   |
| More than 3000 | 61       | 11.3%   |
| 2001-3000      | 37       | 6.85%   |
| 1-20           | 14       | 2.59%   |
| 51-100         | 11       | 2.04%   |
| 21-50          | 8        | 1.48%   |
| Unknown        | 4        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 133      | 23.88%  |
| 21-50          | 95       | 17.06%  |
| 101-250        | 77       | 13.82%  |
| 51-100         | 65       | 11.67%  |
| 251-500        | 64       | 11.49%  |
| 501-1000       | 43       | 7.72%   |
| 1001-2000      | 39       | 7%      |
| More than 3000 | 25       | 4.49%   |
| 2001-3000      | 12       | 2.15%   |
| Unknown        | 4        | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 1      | 4.17%   |
| WDC WD5001AALS-00J7B1 500GB                  | 1        | 1      | 4.17%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 4.17%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 3      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 4.17%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 4.17%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1        | 1      | 4.17%   |
| Seagate ST5000LM000-2AN170 5TB               | 1        | 1      | 4.17%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1        | 1      | 4.17%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1      | 4.17%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 4.17%   |
| Seagate Expansion Desk 8TB                   | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 4.17%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 4.17%   |
| SABRENT Disk 500GB                           | 1        | 1      | 4.17%   |
| Plextor PX-128M6M 128GB SSD                  | 1        | 1      | 4.17%   |
| Kingston SV300S37A240G 240GB SSD             | 1        | 1      | 4.17%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB                   | 1        | 1      | 4.17%   |
| Crucial CT525MX300SSD1 528GB                 | 1        | 1      | 4.17%   |
| BAITITON BT58SSD08M 128GB                    | 1        | 1      | 4.17%   |
| A-DATA Technology SU800 512GB SSD            | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 30.43%  |
| Seagate             | 4        | 5      | 17.39%  |
| Samsung Electronics | 4        | 4      | 17.39%  |
| SABRENT             | 1        | 1      | 4.35%   |
| Plextor             | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |
| BAITITON            | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 50%     |
| Seagate             | 4        | 5      | 28.57%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 17     | 60.87%  |
| SSD  | 8        | 8      | 34.78%  |
| NVMe | 1        | 1      | 4.35%   |

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
| Detected | 448      | 1258   | 79.57%  |
| Works    | 95       | 226    | 16.87%  |
| Malfunc  | 20       | 26     | 3.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 267      | 30.41%  |
| AMD                            | 255      | 29.04%  |
| Samsung Electronics            | 115      | 13.1%   |
| SanDisk                        | 55       | 6.26%   |
| Phison Electronics             | 38       | 4.33%   |
| ASMedia Technology             | 31       | 3.53%   |
| Micron/Crucial Technology      | 21       | 2.39%   |
| Silicon Motion                 | 15       | 1.71%   |
| Marvell Technology Group       | 13       | 1.48%   |
| Kingston Technology Company    | 10       | 1.14%   |
| Nvidia                         | 7        | 0.8%    |
| ADATA Technology               | 7        | 0.8%    |
| Seagate Technology             | 6        | 0.68%   |
| Realtek Semiconductor          | 6        | 0.68%   |
| JMicron Technology             | 6        | 0.68%   |
| Micron Technology              | 5        | 0.57%   |
| SK hynix                       | 4        | 0.46%   |
| Toshiba America Info Systems   | 3        | 0.34%   |
| Broadcom / LSI                 | 3        | 0.34%   |
| Silicon Image                  | 2        | 0.23%   |
| LSI Logic / Symbios Logic      | 2        | 0.23%   |
| Lite-On Technology             | 2        | 0.23%   |
| INNOGRIT                       | 2        | 0.23%   |
| VIA Technologies               | 1        | 0.11%   |
| Solid State Storage Technology | 1        | 0.11%   |
| KIOXIA                         | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 159      | 15.22%  |
| AMD 400 Series Chipset SATA Controller                                                  | 68       | 6.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 61       | 5.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 56       | 5.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30       | 2.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 29       | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 2.11%   |
| Phison E12 NVMe Controller                                                              | 20       | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18       | 1.72%   |
| Samsung NVMe SSD Controller 980                                                         | 17       | 1.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 1.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 15       | 1.44%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 15       | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 1.44%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.24%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 12       | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 11       | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 10       | 0.96%   |
| SanDisk Non-Volatile memory controller                                                  | 9        | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 7        | 0.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7        | 0.67%   |
| Intel SSD 660P Series                                                                   | 7        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 7        | 0.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 465      | 57.13%  |
| NVMe | 246      | 30.22%  |
| IDE  | 69       | 8.48%   |
| RAID | 28       | 3.44%   |
| SAS  | 6        | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 264      | 50.19%  |
| Intel  | 262      | 49.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 23       | 4.36%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 20       | 3.8%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 17       | 3.23%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 15       | 2.85%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 12       | 2.28%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 12       | 2.28%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 2.09%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 1.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 9        | 1.71%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 1.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 7        | 1.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 1.14%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6        | 1.14%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 6        | 1.14%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.95%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 5        | 0.95%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 5        | 0.95%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 0.95%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 0.95%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 5        | 0.95%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 4        | 0.76%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.76%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.76%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.76%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 0.76%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 4        | 0.76%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 4        | 0.76%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.76%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.76%   |
| AMD FX-8320 Eight-Core Processor            | 4        | 0.76%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 93       | 17.65%  |
| Intel Core i7           | 83       | 15.75%  |
| Intel Core i5           | 76       | 14.42%  |
| AMD Ryzen 7             | 71       | 13.47%  |
| AMD Ryzen 9             | 40       | 7.59%   |
| Other                   | 24       | 4.55%   |
| Intel Xeon              | 21       | 3.98%   |
| Intel Core i3           | 18       | 3.42%   |
| AMD FX                  | 17       | 3.23%   |
| Intel Core i9           | 10       | 1.9%    |
| AMD Ryzen Threadripper  | 7        | 1.33%   |
| AMD Ryzen 3             | 7        | 1.33%   |
| Intel Core 2 Quad       | 6        | 1.14%   |
| Intel Celeron           | 6        | 1.14%   |
| Intel Pentium Gold      | 4        | 0.76%   |
| Intel Pentium           | 4        | 0.76%   |
| AMD A8                  | 4        | 0.76%   |
| Intel Core 2 Duo        | 3        | 0.57%   |
| AMD Phenom              | 3        | 0.57%   |
| Intel Pentium Dual      | 2        | 0.38%   |
| Intel Pentium D         | 2        | 0.38%   |
| Intel Core 2            | 2        | 0.38%   |
| AMD Phenom II X6        | 2        | 0.38%   |
| AMD Phenom II X4        | 2        | 0.38%   |
| AMD Athlon II X4        | 2        | 0.38%   |
| AMD Athlon II X2        | 2        | 0.38%   |
| AMD Athlon              | 2        | 0.38%   |
| AMD A4                  | 2        | 0.38%   |
| Intel Pentium Dual-Core | 1        | 0.19%   |
| Intel Atom              | 1        | 0.19%   |
| AMD Sempron             | 1        | 0.19%   |
| AMD Ryzen Embedded      | 1        | 0.19%   |
| AMD Ryzen 5 PRO         | 1        | 0.19%   |
| AMD Ryzen 3 PRO         | 1        | 0.19%   |
| AMD PRO A10             | 1        | 0.19%   |
| AMD Phenom II X3        | 1        | 0.19%   |
| AMD Athlon X4           | 1        | 0.19%   |
| AMD Athlon 64           | 1        | 0.19%   |
| AMD A6                  | 1        | 0.19%   |
| AMD A10                 | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 179      | 33.97%  |
| 6      | 120      | 22.77%  |
| 8      | 94       | 17.84%  |
| 2      | 53       | 10.06%  |
| 12     | 30       | 5.69%   |
| 16     | 24       | 4.55%   |
| 10     | 8        | 1.52%   |
| 3      | 8        | 1.52%   |
| 24     | 3        | 0.57%   |
| 1      | 3        | 0.57%   |
| 32     | 2        | 0.38%   |
| 64     | 1        | 0.19%   |
| 18     | 1        | 0.19%   |
| 14     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 523      | 99.43%  |
| 2      | 3        | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 393      | 74.71%  |
| 1      | 133      | 25.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 526      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 434      | 82.04%  |
| 0x08701021 | 13       | 2.46%   |
| 0x0a201016 | 7        | 1.32%   |
| 0x0800820d | 7        | 1.32%   |
| 0x906ec    | 5        | 0.95%   |
| 0x306a9    | 5        | 0.95%   |
| 0x206a7    | 5        | 0.95%   |
| 0x90672    | 4        | 0.76%   |
| 0x506e3    | 4        | 0.76%   |
| 0x08701013 | 4        | 0.76%   |
| 0x906ea    | 3        | 0.57%   |
| 0x906e9    | 3        | 0.57%   |
| 0x08108109 | 3        | 0.57%   |
| 0x08001138 | 3        | 0.57%   |
| 0x06003106 | 3        | 0.57%   |
| 0xa0671    | 2        | 0.38%   |
| 0xa0653    | 2        | 0.38%   |
| 0x50657    | 2        | 0.38%   |
| 0x306c3    | 2        | 0.38%   |
| 0x0a50000c | 2        | 0.38%   |
| 0x0a201205 | 2        | 0.38%   |
| 0x08001137 | 2        | 0.38%   |
| 0xa0655    | 1        | 0.19%   |
| 0x906ed    | 1        | 0.19%   |
| 0x906c0    | 1        | 0.19%   |
| 0x0a601201 | 1        | 0.19%   |
| 0x0a20120a | 1        | 0.19%   |
| 0x0a201006 | 1        | 0.19%   |
| 0x08301039 | 1        | 0.19%   |
| 0x08101016 | 1        | 0.19%   |
| 0x08001129 | 1        | 0.19%   |
| 0x07013005 | 1        | 0.19%   |
| 0x0600611a | 1        | 0.19%   |
| 0x06000852 | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 89       | 16.89%  |
| Zen 2            | 72       | 13.66%  |
| Haswell          | 49       | 9.3%    |
| KabyLake         | 41       | 7.78%   |
| Zen+             | 35       | 6.64%   |
| IvyBridge        | 33       | 6.26%   |
| Skylake          | 30       | 5.69%   |
| Unknown          | 27       | 5.12%   |
| SandyBridge      | 26       | 4.93%   |
| Zen              | 22       | 4.17%   |
| Piledriver       | 19       | 3.61%   |
| Nehalem          | 13       | 2.47%   |
| CometLake        | 13       | 2.47%   |
| K10              | 12       | 2.28%   |
| Penryn           | 10       | 1.9%    |
| Westmere         | 6        | 1.14%   |
| Steamroller      | 5        | 0.95%   |
| Core             | 5        | 0.95%   |
| Broadwell        | 4        | 0.76%   |
| Alderlake Hybrid | 4        | 0.76%   |
| Silvermont       | 2        | 0.38%   |
| NetBurst         | 2        | 0.38%   |
| Goldmont         | 2        | 0.38%   |
| Excavator        | 2        | 0.38%   |
| K8 Hammer        | 1        | 0.19%   |
| K10 Llano        | 1        | 0.19%   |
| Jaguar           | 1        | 0.19%   |
| Icelake          | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 275      | 48.93%  |
| AMD                        | 200      | 35.59%  |
| Intel                      | 86       | 15.3%   |
| Matrox Electronics Systems | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 3.81%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 18       | 3.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17       | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17       | 2.95%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 17       | 2.95%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14       | 2.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14       | 2.43%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 12       | 2.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.91%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 10       | 1.73%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 9        | 1.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 9        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 1.39%   |
| Intel HD Graphics 530                                                       | 8        | 1.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 7        | 1.21%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 7        | 1.21%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 1.21%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.21%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 1.21%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 7        | 1.21%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.21%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 1.04%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 6        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.04%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 1.04%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 5        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 5        | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 0.87%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 5        | 0.87%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 0.87%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 257      | 48.22%  |
| 1 x AMD              | 185      | 34.71%  |
| 1 x Intel            | 59       | 11.07%  |
| 2 x AMD              | 8        | 1.5%    |
| Intel + Nvidia       | 8        | 1.5%    |
| 2 x Nvidia           | 5        | 0.94%   |
| AMD + Nvidia         | 4        | 0.75%   |
| Intel + AMD          | 3        | 0.56%   |
| Other                | 1        | 0.19%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.19%   |
| 1 x Matrox           | 1        | 0.19%   |
| AMD + 2 x Nvidia     | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 275      | 51.59%  |
| Proprietary | 235      | 44.09%  |
| Unknown     | 23       | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 339      | 63.25%  |
| 7.01-8.0   | 52       | 9.7%    |
| 1.01-2.0   | 34       | 6.34%   |
| 8.01-16.0  | 33       | 6.16%   |
| 5.01-6.0   | 31       | 5.78%   |
| 3.01-4.0   | 29       | 5.41%   |
| 2.01-3.0   | 7        | 1.31%   |
| 0.51-1.0   | 5        | 0.93%   |
| 0.01-0.5   | 3        | 0.56%   |
| 16.01-24.0 | 2        | 0.37%   |
| 32.01-64.0 | 1        | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 106      | 18.03%  |
| Goldstar             | 75       | 12.76%  |
| Dell                 | 63       | 10.71%  |
| Hewlett-Packard      | 42       | 7.14%   |
| AOC                  | 35       | 5.95%   |
| Ancor Communications | 33       | 5.61%   |
| Acer                 | 33       | 5.61%   |
| ASUSTek Computer     | 29       | 4.93%   |
| BenQ                 | 28       | 4.76%   |
| Philips              | 12       | 2.04%   |
| Lenovo               | 11       | 1.87%   |
| MSI                  | 10       | 1.7%    |
| Iiyama               | 9        | 1.53%   |
| Sceptre Tech         | 7        | 1.19%   |
| NEC Computers        | 6        | 1.02%   |
| Gigabyte Technology  | 6        | 1.02%   |
| ViewSonic            | 4        | 0.68%   |
| Unknown              | 4        | 0.68%   |
| Sony                 | 4        | 0.68%   |
| Vizio                | 3        | 0.51%   |
| Viotek               | 3        | 0.51%   |
| Sharp                | 3        | 0.51%   |
| Pioneer              | 3        | 0.51%   |
| Vestel Elektronik    | 2        | 0.34%   |
| Valve                | 2        | 0.34%   |
| Toshiba              | 2        | 0.34%   |
| Pixio                | 2        | 0.34%   |
| Mi                   | 2        | 0.34%   |
| LLL                  | 2        | 0.34%   |
| LG Electronics       | 2        | 0.34%   |
| ITE                  | 2        | 0.34%   |
| HUAWEI               | 2        | 0.34%   |
| GDH                  | 2        | 0.34%   |
| Fujitsu Siemens      | 2        | 0.34%   |
| Eizo                 | 2        | 0.34%   |
| Arnos Instruments    | 2        | 0.34%   |
| ___                  | 1        | 0.17%   |
| VOXICON              | 1        | 0.17%   |
| Unknown (XXX)        | 1        | 0.17%   |
| TXD                  | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch             | 6        | 0.97%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5        | 0.81%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch        | 5        | 0.81%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 4        | 0.65%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 4        | 0.65%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                       | 4        | 0.65%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                        | 4        | 0.65%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 4        | 0.65%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch      | 3        | 0.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 3        | 0.49%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 3        | 0.49%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch             | 3        | 0.49%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 3        | 0.49%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                     | 3        | 0.49%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 3        | 0.49%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                      | 3        | 0.49%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 530x300mm 24.0-inch            | 3        | 0.49%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch        | 3        | 0.49%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 2        | 0.32%   |
| Valve Index HMD VLV91A8                                                 | 2        | 0.32%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 2        | 0.32%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch       | 2        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 2        | 0.32%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch     | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 2        | 0.32%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch      | 2        | 0.32%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 2        | 0.32%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 700x390mm 31.5-inch       | 2        | 0.32%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 2        | 0.32%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 2        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 0.32%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 2        | 0.32%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 2        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2        | 0.32%   |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                          | 2        | 0.32%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                        | 2        | 0.32%   |
| LLL LRK32G30RQ LLL4200 1920x1080 983x576mm 44.9-inch                    | 2        | 0.32%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 2        | 0.32%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                     | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 263      | 47.13%  |
| 3840x2160 (4K)     | 83       | 14.87%  |
| 2560x1440 (QHD)    | 58       | 10.39%  |
| 3440x1440          | 24       | 4.3%    |
| 2560x1080          | 20       | 3.58%   |
| 1680x1050 (WSXGA+) | 19       | 3.41%   |
| 1366x768 (WXGA)    | 17       | 3.05%   |
| 1280x1024 (SXGA)   | 14       | 2.51%   |
| 1920x1200 (WUXGA)  | 11       | 1.97%   |
| 1600x900 (HD+)     | 11       | 1.97%   |
| 3840x1080          | 7        | 1.25%   |
| 1920x540           | 5        | 0.9%    |
| 1360x768           | 5        | 0.9%    |
| 3840x1600          | 4        | 0.72%   |
| 1440x900 (WXGA+)   | 4        | 0.72%   |
| 1024x768 (XGA)     | 3        | 0.54%   |
| Unknown            | 3        | 0.54%   |
| 3280x1080          | 1        | 0.18%   |
| 3040x900           | 1        | 0.18%   |
| 2880x1600          | 1        | 0.18%   |
| 2560x1600          | 1        | 0.18%   |
| 1600x1200          | 1        | 0.18%   |
| 1280x800 (WXGA)    | 1        | 0.18%   |
| 1280x720 (HD)      | 1        | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 105      | 18.13%  |
| 24      | 95       | 16.41%  |
| 23      | 70       | 12.09%  |
| 21      | 48       | 8.29%   |
| 31      | 47       | 8.12%   |
| 34      | 40       | 6.91%   |
| Unknown | 21       | 3.63%   |
| 18      | 15       | 2.59%   |
| 22      | 14       | 2.42%   |
| 19      | 14       | 2.42%   |
| 32      | 12       | 2.07%   |
| 72      | 10       | 1.73%   |
| 84      | 9        | 1.55%   |
| 20      | 9        | 1.55%   |
| 17      | 9        | 1.55%   |
| 48      | 7        | 1.21%   |
| 25      | 6        | 1.04%   |
| 15      | 6        | 1.04%   |
| 37      | 5        | 0.86%   |
| 28      | 5        | 0.86%   |
| 54      | 4        | 0.69%   |
| 26      | 4        | 0.69%   |
| 46      | 3        | 0.52%   |
| 65      | 2        | 0.35%   |
| 52      | 2        | 0.35%   |
| 47      | 2        | 0.35%   |
| 44      | 2        | 0.35%   |
| 42      | 2        | 0.35%   |
| 35      | 2        | 0.35%   |
| 33      | 2        | 0.35%   |
| 75      | 1        | 0.17%   |
| 69      | 1        | 0.17%   |
| 61      | 1        | 0.17%   |
| 49      | 1        | 0.17%   |
| 36      | 1        | 0.17%   |
| 30      | 1        | 0.17%   |
| 29      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 244      | 43.88%  |
| 401-500     | 91       | 16.37%  |
| 601-700     | 69       | 12.41%  |
| 701-800     | 54       | 9.71%   |
| 1001-1500   | 22       | 3.96%   |
| 1501-2000   | 21       | 3.78%   |
| Unknown     | 21       | 3.78%   |
| 301-350     | 15       | 2.7%    |
| 801-900     | 8        | 1.44%   |
| 351-400     | 7        | 1.26%   |
| 901-1000    | 4        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 397      | 75.19%  |
| 21/9    | 49       | 9.28%   |
| 16/10   | 43       | 8.14%   |
| 5/4     | 15       | 2.84%   |
| Unknown | 10       | 1.89%   |
| 32/9    | 9        | 1.7%    |
| 4/3     | 5        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 176      | 31.43%  |
| 301-350        | 109      | 19.46%  |
| 351-500        | 104      | 18.57%  |
| 151-200        | 37       | 6.61%   |
| 251-300        | 32       | 5.71%   |
| More than 1000 | 30       | 5.36%   |
| 141-150        | 23       | 4.11%   |
| 501-1000       | 22       | 3.93%   |
| Unknown        | 21       | 3.75%   |
| 101-110        | 6        | 1.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 322      | 61.45%  |
| 101-120       | 112      | 21.37%  |
| 121-160       | 32       | 6.11%   |
| 1-50          | 24       | 4.58%   |
| Unknown       | 21       | 4.01%   |
| 161-240       | 12       | 2.29%   |
| More than 240 | 1        | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 383      | 72.26%  |
| 2     | 102      | 19.25%  |
| 0     | 25       | 4.72%   |
| 3     | 16       | 3.02%   |
| 4     | 3        | 0.57%   |
| 6     | 1        | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 301      | 38.94%  |
| Intel                           | 281      | 36.35%  |
| Qualcomm Atheros                | 45       | 5.82%   |
| Broadcom                        | 26       | 3.36%   |
| TP-Link                         | 14       | 1.81%   |
| Ralink Technology               | 11       | 1.42%   |
| MediaTek                        | 11       | 1.42%   |
| NetGear                         | 9        | 1.16%   |
| Microsoft                       | 7        | 0.91%   |
| Aquantia                        | 7        | 0.91%   |
| Nvidia                          | 6        | 0.78%   |
| InterBiometrics                 | 6        | 0.78%   |
| Ralink                          | 5        | 0.65%   |
| D-Link                          | 5        | 0.65%   |
| Xiaomi                          | 4        | 0.52%   |
| Samsung Electronics             | 4        | 0.52%   |
| Qualcomm Atheros Communications | 3        | 0.39%   |
| ASUSTek Computer                | 3        | 0.39%   |
| Mellanox Technologies           | 2        | 0.26%   |
| Huawei Technologies             | 2        | 0.26%   |
| Google                          | 2        | 0.26%   |
| Broadcom Limited                | 2        | 0.26%   |
| STMicroelectronics              | 1        | 0.13%   |
| Sitecom Europe                  | 1        | 0.13%   |
| SIEMENS                         | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| OPPO Electronics                | 1        | 0.13%   |
| Micro Star International        | 1        | 0.13%   |
| Marvell Technology Group        | 1        | 0.13%   |
| Manta                           | 1        | 0.13%   |
| IMC Networks                    | 1        | 0.13%   |
| Hyperkin                        | 1        | 0.13%   |
| Gemtek                          | 1        | 0.13%   |
| DisplayLink                     | 1        | 0.13%   |
| D-Link System                   | 1        | 0.13%   |
| Belkin Components               | 1        | 0.13%   |
| AVM                             | 1        | 0.13%   |
| ASIX Electronics                | 1        | 0.13%   |
| Unknown                         | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208      | 22.76%  |
| Intel Wi-Fi 6 AX200                                               | 72       | 7.88%   |
| Intel I211 Gigabit Network Connection                             | 72       | 7.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 61       | 6.67%   |
| Intel Ethernet Controller I225-V                                  | 37       | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 21       | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18       | 1.97%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 1.53%   |
| Realtek 802.11ac NIC                                              | 13       | 1.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13       | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 1.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 12       | 1.31%   |
| Intel Wireless-AC 9260                                            | 10       | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9        | 0.98%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9        | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 8        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 0.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 0.66%   |
| InterBiometrics Io                                                | 6        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6        | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5        | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 5        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.55%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 5        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.44%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4        | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.44%   |
| NetGear A6210                                                     | 4        | 0.44%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4        | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 151      | 48.24%  |
| Realtek Semiconductor           | 53       | 16.93%  |
| Qualcomm Atheros                | 19       | 6.07%   |
| Broadcom                        | 18       | 5.75%   |
| TP-Link                         | 12       | 3.83%   |
| Ralink Technology               | 11       | 3.51%   |
| MediaTek                        | 11       | 3.51%   |
| NetGear                         | 9        | 2.88%   |
| Microsoft                       | 7        | 2.24%   |
| Ralink                          | 5        | 1.6%    |
| D-Link                          | 4        | 1.28%   |
| Qualcomm Atheros Communications | 3        | 0.96%   |
| ASUSTek Computer                | 3        | 0.96%   |
| Sitecom Europe                  | 1        | 0.32%   |
| Micro Star International        | 1        | 0.32%   |
| IMC Networks                    | 1        | 0.32%   |
| Gemtek                          | 1        | 0.32%   |
| D-Link System                   | 1        | 0.32%   |
| Belkin Components               | 1        | 0.32%   |
| AVM                             | 1        | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 72       | 22.71%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 18       | 5.68%   |
| Realtek 802.11ac NIC                                                                          | 13       | 4.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 13       | 4.1%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 12       | 3.79%   |
| Intel Wireless-AC 9260                                                                        | 10       | 3.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 9        | 2.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 9        | 2.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 8        | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 6        | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 5        | 1.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 5        | 1.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 1.58%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 5        | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 4        | 1.26%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4        | 1.26%   |
| NetGear A6210                                                                                 | 4        | 1.26%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 4        | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 4        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.95%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 0.95%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 3        | 0.95%   |
| Microsoft XBOX ACC                                                                            | 3        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3        | 0.95%   |
| Intel Wireless Gigabit 17265                                                                  | 3        | 0.95%   |
| Intel Wireless 7265                                                                           | 3        | 0.95%   |
| Intel Wireless 7260                                                                           | 3        | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 0.63%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 2        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 0.63%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                            | 2        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 276      | 48.08%  |
| Intel                    | 225      | 39.2%   |
| Qualcomm Atheros         | 27       | 4.7%    |
| Broadcom                 | 9        | 1.57%   |
| Aquantia                 | 7        | 1.22%   |
| Nvidia                   | 6        | 1.05%   |
| Xiaomi                   | 4        | 0.7%    |
| Samsung Electronics      | 4        | 0.7%    |
| TP-Link                  | 2        | 0.35%   |
| Mellanox Technologies    | 2        | 0.35%   |
| Huawei Technologies      | 2        | 0.35%   |
| Google                   | 2        | 0.35%   |
| Broadcom Limited         | 2        | 0.35%   |
| Qualcomm                 | 1        | 0.17%   |
| OPPO Electronics         | 1        | 0.17%   |
| Marvell Technology Group | 1        | 0.17%   |
| DisplayLink              | 1        | 0.17%   |
| D-Link                   | 1        | 0.17%   |
| ASIX Electronics         | 1        | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208      | 35.49%  |
| Intel I211 Gigabit Network Connection                             | 72       | 12.29%  |
| Realtek RTL8125 2.5GbE Controller                                 | 61       | 10.41%  |
| Intel Ethernet Controller I225-V                                  | 37       | 6.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 3.75%   |
| Intel Ethernet Connection (2) I219-V                              | 21       | 3.58%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 2.39%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 2.05%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.51%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2        | 0.34%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.34%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.34%   |
| Intel Ethernet Controller X550                                    | 2        | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.34%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.34%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.34%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.34%   |
| Huawei SNE-LX1                                                    | 2        | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 520      | 62.88%  |
| WiFi     | 296      | 35.79%  |
| Modem    | 8        | 0.97%   |
| Unknown  | 3        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 395      | 71.95%  |
| WiFi     | 154      | 28.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 285      | 53.98%  |
| 2     | 195      | 36.93%  |
| 3     | 39       | 7.39%   |
| 0     | 7        | 1.33%   |
| 4     | 2        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 367      | 69.25%  |
| Yes  | 163      | 30.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 137      | 56.85%  |
| Cambridge Silicon Radio         | 46       | 19.09%  |
| ASUSTek Computer                | 13       | 5.39%   |
| Realtek Semiconductor           | 9        | 3.73%   |
| Qualcomm Atheros Communications | 7        | 2.9%    |
| Broadcom                        | 7        | 2.9%    |
| MediaTek                        | 5        | 2.07%   |
| Foxconn / Hon Hai               | 4        | 1.66%   |
| Apple                           | 4        | 1.66%   |
| TP-Link                         | 3        | 1.24%   |
| Micro Star International        | 1        | 0.41%   |
| IMC Networks                    | 1        | 0.41%   |
| HTC (High Tech Computer)        | 1        | 0.41%   |
| Edimax Technology               | 1        | 0.41%   |
| Dynex                           | 1        | 0.41%   |
| Belkin Components               | 1        | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 65       | 26.97%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 46       | 19.09%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 17       | 7.05%   |
| Intel AX201 Bluetooth                                                | 16       | 6.64%   |
| Intel AX210 Bluetooth                                                | 10       | 4.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9        | 3.73%   |
| Intel Bluetooth wireless interface                                   | 9        | 3.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9        | 3.73%   |
| Realtek Bluetooth Radio                                              | 5        | 2.07%   |
| MediaTek Wireless_Device                                             | 5        | 2.07%   |
| ASUS ASUS USB-BT500                                                  | 5        | 2.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 1.66%   |
| ASUS Bluetooth Radio                                                 | 4        | 1.66%   |
| TP-Link UB500 Adapter                                                | 3        | 1.24%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 1.24%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2        | 0.83%   |
| Intel Bluetooth Device                                               | 2        | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 2        | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 2        | 0.83%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 0.83%   |
| Apple Bluetooth USB Host Controller                                  | 2        | 0.83%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.41%   |
| Realtek Bluetooth 5.1 Radio                                          | 1        | 0.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.41%   |
| Qualcomm Atheros Bluetooth                                           | 1        | 0.41%   |
| Micro Star International Bluetooth Device                            | 1        | 0.41%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.41%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.41%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.41%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.41%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.41%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.41%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.41%   |
| Apple Bluetooth HCI                                                  | 1        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 311      | 29.56%  |
| Nvidia                               | 271      | 25.76%  |
| Intel                                | 250      | 23.76%  |
| C-Media Electronics                  | 25       | 2.38%   |
| Logitech                             | 19       | 1.81%   |
| Razer USA                            | 13       | 1.24%   |
| Kingston Technology                  | 13       | 1.24%   |
| Creative Labs                        | 11       | 1.05%   |
| JMTek                                | 10       | 0.95%   |
| Focusrite-Novation                   | 10       | 0.95%   |
| ASUSTek Computer                     | 9        | 0.86%   |
| Blue Microphones                     | 7        | 0.67%   |
| Micro Star International             | 6        | 0.57%   |
| Generalplus Technology               | 6        | 0.57%   |
| Texas Instruments                    | 5        | 0.48%   |
| Creative Technology                  | 5        | 0.48%   |
| Corsair                              | 5        | 0.48%   |
| SteelSeries ApS                      | 4        | 0.38%   |
| GN Netcom                            | 3        | 0.29%   |
| Valve Software                       | 2        | 0.19%   |
| Trust                                | 2        | 0.19%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.19%   |
| Tenx Technology                      | 2        | 0.19%   |
| SAVITECH                             | 2        | 0.19%   |
| Plantronics                          | 2        | 0.19%   |
| Nordic Semiconductor ASA             | 2        | 0.19%   |
| Mackie Designs                       | 2        | 0.19%   |
| M-Audio                              | 2        | 0.19%   |
| DSEA A/S                             | 2        | 0.19%   |
| BEHRINGER International              | 2        | 0.19%   |
| Astro Gaming                         | 2        | 0.19%   |
| Antlion Audio                        | 2        | 0.19%   |
| Yamaha                               | 1        | 0.1%    |
| WL80                                 | 1        | 0.1%    |
| USB MIDI                             | 1        | 0.1%    |
| Unknown                              | 1        | 0.1%    |
| Turtle Beach                         | 1        | 0.1%    |
| Sony                                 | 1        | 0.1%    |
| Solid State System                   | 1        | 0.1%    |
| Shure                                | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 134      | 10.88%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 58       | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 44       | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 39       | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29       | 2.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 27       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26       | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25       | 2.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25       | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25       | 2.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 24       | 1.95%   |
| Intel 200 Series PCH HD Audio                                              | 24       | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24       | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 21       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 1.7%    |
| Nvidia TU104 HD Audio Controller                                           | 20       | 1.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 20       | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 20       | 1.62%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 1.62%   |
| Nvidia GA104 High Definition Audio Controller                              | 18       | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16       | 1.3%    |
| Nvidia GA106 High Definition Audio Controller                              | 15       | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.22%   |
| AMD Navi 10 HDMI Audio                                                     | 15       | 1.22%   |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 14       | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 13       | 1.06%   |
| Kingston Technology HyperX 7.1 Audio                                       | 10       | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 0.81%   |
| AMD FCH Azalia Controller                                                  | 10       | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9        | 0.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7        | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 32       | 30.77%  |
| G.Skill                      | 16       | 15.38%  |
| Kingston                     | 14       | 13.46%  |
| Team                         | 8        | 7.69%   |
| Samsung Electronics          | 8        | 7.69%   |
| Unknown                      | 6        | 5.77%   |
| Crucial                      | 6        | 5.77%   |
| Micron Technology            | 4        | 3.85%   |
| SK hynix                     | 3        | 2.88%   |
| Unknown                      | 2        | 1.92%   |
| Teikon                       | 1        | 0.96%   |
| Patriot Memory (PDP Systems) | 1        | 0.96%   |
| Patriot Memory               | 1        | 0.96%   |
| Patriot                      | 1        | 0.96%   |
| Avant                        | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                   | 7        | 6.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                     | 4        | 3.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s                   | 4        | 3.67%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                      | 2        | 1.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                     | 2        | 1.83%   |
| Kingston RAM KF3600C16D4/16GX 16384MB DIMM DDR4 3600MT/s                | 2        | 1.83%   |
| G.Skill RAM F4-3600C18-8GVK 8192MB DIMM DDR4 3600MT/s                   | 2        | 1.83%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s                    | 2        | 1.83%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s                | 2        | 1.83%   |
| Unknown                                                                 | 2        | 1.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 0.92%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                              | 1        | 0.92%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s                     | 1        | 0.92%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                      | 1        | 0.92%   |
| Teikon RAM TMT451U6BFR8C-PBHJ 4GB DIMM DDR3 1600MT/s                    | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                      | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s                      | 1        | 0.92%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s                   | 1        | 0.92%   |
| SK hynix RAM HMA82GU6DJR8N-WM 16GB DIMM DDR4 2933MT/s                   | 1        | 0.92%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                    | 1        | 0.92%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s                     | 1        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 1        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                | 1        | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s                | 1        | 0.92%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s                  | 1        | 0.92%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 0.92%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s                     | 1        | 0.92%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                         | 1        | 0.92%   |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s               | 1        | 0.92%   |
| Patriot Memory (PDP Systems) RAM 3200 C18 Series 8GB DIMM DDR4 3333MT/s | 1        | 0.92%   |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s                    | 1        | 0.92%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 1        | 0.92%   |
| Micron RAM 8ATF2G64AZ-3G2B1 16GB DIMM DDR4 3200MT/s                     | 1        | 0.92%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s                    | 1        | 0.92%   |
| Kingston RAM Module 16GB DIMM DDR4 2666MT/s                             | 1        | 0.92%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s                          | 1        | 0.92%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s                  | 1        | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 77       | 80.21%  |
| DDR3    | 15       | 15.63%  |
| Unknown | 2        | 2.08%   |
| LPDDR4  | 1        | 1.04%   |
| DDR5    | 1        | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 91       | 94.79%  |
| SODIMM       | 4        | 4.17%   |
| Row Of Chips | 1        | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 48       | 47.06%  |
| 16384 | 27       | 26.47%  |
| 4096  | 17       | 16.67%  |
| 32768 | 9        | 8.82%   |
| 2048  | 1        | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 25       | 24.51%  |
| 3200  | 18       | 17.65%  |
| 1600  | 12       | 11.76%  |
| 3800  | 5        | 4.9%    |
| 2400  | 5        | 4.9%    |
| 1333  | 5        | 4.9%    |
| 3466  | 4        | 3.92%   |
| 3000  | 4        | 3.92%   |
| 2933  | 3        | 2.94%   |
| 2667  | 3        | 2.94%   |
| 2133  | 3        | 2.94%   |
| 3733  | 2        | 1.96%   |
| 2800  | 2        | 1.96%   |
| 2666  | 2        | 1.96%   |
| 4800  | 1        | 0.98%   |
| 4000  | 1        | 0.98%   |
| 3866  | 1        | 0.98%   |
| 3666  | 1        | 0.98%   |
| 3400  | 1        | 0.98%   |
| 3333  | 1        | 0.98%   |
| 3100  | 1        | 0.98%   |
| 2733  | 1        | 0.98%   |
| 1866  | 1        | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 7        | 31.82%  |
| Canon               | 4        | 18.18%  |
| Samsung Electronics | 3        | 13.64%  |
| Hewlett-Packard     | 3        | 13.64%  |
| Seiko Epson         | 2        | 9.09%   |
| QinHeng Electronics | 1        | 4.55%   |
| Prolific Technology | 1        | 4.55%   |
| Dymo-CoStar         | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Brother HL-2130 series                 | 3        | 13.04%  |
| Seiko Epson WF-4830 Series             | 1        | 4.35%   |
| Seiko Epson ET-2800 Series             | 1        | 4.35%   |
| Samsung SCX-3400 Series                | 1        | 4.35%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 4.35%   |
| Samsung M2070 Series                   | 1        | 4.35%   |
| QinHeng CH340S                         | 1        | 4.35%   |
| Prolific PL2305 Parallel Port          | 1        | 4.35%   |
| HP PSC-1315/PSC-1317                   | 1        | 4.35%   |
| HP LaserJet P2035                      | 1        | 4.35%   |
| HP ENVY Pro 6400 series                | 1        | 4.35%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 4.35%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.35%   |
| Canon TR8500 series                    | 1        | 4.35%   |
| Canon Pro9000II series                 | 1        | 4.35%   |
| Canon PIXMA MP240                      | 1        | 4.35%   |
| Canon PIXMA MG2500 Series              | 1        | 4.35%   |
| Brother MFC-L2700DW                    | 1        | 4.35%   |
| Brother MFC-5440CN                     | 1        | 4.35%   |
| Brother HL-3140CW series               | 1        | 4.35%   |
| Brother HL-2270DW Laser Printer        | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 3        | 75%     |
| Mustek Systems | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 25%     |
| Canon CanoScan N650U/N656U         | 1        | 25%     |
| Canon CanoScan LiDE 60             | 1        | 25%     |
| Canon CanoScan LiDE 200            | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 54       | 39.13%  |
| Microdia                      | 9        | 6.52%   |
| Sunplus Innovation Technology | 7        | 5.07%   |
| Microsoft                     | 6        | 4.35%   |
| Samsung Electronics           | 5        | 3.62%   |
| Razer USA                     | 4        | 2.9%    |
| MacroSilicon                  | 4        | 2.9%    |
| Jieli Technology              | 4        | 2.9%    |
| Apple                         | 4        | 2.9%    |
| Realtek Semiconductor         | 3        | 2.17%   |
| Cubeternet                    | 3        | 2.17%   |
| ARC International             | 3        | 2.17%   |
| Valve Software                | 2        | 1.45%   |
| Sunplus IT                    | 2        | 1.45%   |
| LG Electronics                | 2        | 1.45%   |
| Generalplus Technology        | 2        | 1.45%   |
| Creative Technology           | 2        | 1.45%   |
| AVerMedia Technologies        | 2        | 1.45%   |
| Z-Star Microelectronics       | 1        | 0.72%   |
| YGTek                         | 1        | 0.72%   |
| XHT-210518                    | 1        | 0.72%   |
| WaveRider Communications      | 1        | 0.72%   |
| USB Camera                    | 1        | 0.72%   |
| Trust                         | 1        | 0.72%   |
| SN0002                        | 1        | 0.72%   |
| Owon                          | 1        | 0.72%   |
| Novatek Microelectronics      | 1        | 0.72%   |
| Lenovo                        | 1        | 0.72%   |
| KYE Systems (Mouse Systems)   | 1        | 0.72%   |
| HTC (High Tech Computer)      | 1        | 0.72%   |
| Hewlett-Packard               | 1        | 0.72%   |
| GenesysLogic Technology       | 1        | 0.72%   |
| Genesys Logic                 | 1        | 0.72%   |
| eMeet                         | 1        | 0.72%   |
| Elgato Systems                | 1        | 0.72%   |
| Chicony Electronics           | 1        | 0.72%   |
| Celestron                     | 1        | 0.72%   |
| 2M UVC CAMERA                 | 1        | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 14       | 10.14%  |
| Logitech HD Pro Webcam C920                           | 11       | 7.97%   |
| Samsung Galaxy series, misc. (MTP mode)               | 5        | 3.62%   |
| Logitech C922 Pro Stream Webcam                       | 5        | 3.62%   |
| Razer USA Gaming Webcam [Kiyo]                        | 4        | 2.9%    |
| MacroSilicon USB Video                                | 4        | 2.9%    |
| Logitech Webcam C925e                                 | 4        | 2.9%    |
| Jieli USB PHY 2.0                                     | 4        | 2.9%    |
| Apple iPhone 5/5C/5S/6/SE                             | 4        | 2.9%    |
| Microdia USB 2.0 Camera                               | 3        | 2.17%   |
| Logitech HD Webcam C525                               | 3        | 2.17%   |
| Logitech BRIO                                         | 3        | 2.17%   |
| ARC International Camera                              | 3        | 2.17%   |
| Valve Software 3D Camera                              | 2        | 1.45%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 2        | 1.45%   |
| Sunplus SPCA2281 Web Camera                           | 2        | 1.45%   |
| Microsoft LifeCam HD-3000                             | 2        | 1.45%   |
| Microsoft LifeCam Cinema                              | 2        | 1.45%   |
| Microdia Webcam Vitade AF                             | 2        | 1.45%   |
| Microdia Hy-HD-Camera                                 | 2        | 1.45%   |
| Logitech Webcam C930e                                 | 2        | 1.45%   |
| Logitech StreamCam                                    | 2        | 1.45%   |
| Logitech HD Webcam C615                               | 2        | 1.45%   |
| Logitech C920 PRO HD Webcam                           | 2        | 1.45%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.45%   |
| AVerMedia Live Streamer CAM 313                       | 2        | 1.45%   |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 0.72%   |
| YGTek Webcam                                          | 1        | 0.72%   |
| XHT-210518 EC500X                                     | 1        | 0.72%   |
| WaveRider USB 2.0 Camera                              | 1        | 0.72%   |
| USB Camera USB Camera                                 | 1        | 0.72%   |
| Trust USB Camera                                      | 1        | 0.72%   |
| Sunplus USB 2.0 Camera                                | 1        | 0.72%   |
| Sunplus MYPIN HD Capture                              | 1        | 0.72%   |
| Sunplus HD 720P webcam                                | 1        | 0.72%   |
| Sunplus Full HD webcam                                | 1        | 0.72%   |
| Sunplus Canyon CNS-CWC5 Webcam                        | 1        | 0.72%   |
| SN0002 HIK 1080P USB CAMERA                           | 1        | 0.72%   |
| Realtek Webcam                                        | 1        | 0.72%   |
| Realtek USB Camera                                    | 1        | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 33.33%  |
| Alcor Micro           | 1        | 33.33%  |
| Advanced Card Systems | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 33.33%  |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 432      | 81.2%   |
| 1     | 88       | 16.54%  |
| 2     | 11       | 2.07%   |
| 3     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 37       | 34.58%  |
| Graphics card            | 27       | 25.23%  |
| Bluetooth                | 10       | 9.35%   |
| Unassigned class         | 7        | 6.54%   |
| Sound                    | 7        | 6.54%   |
| Net/ethernet             | 6        | 5.61%   |
| Multimedia controller    | 3        | 2.8%    |
| Chipcard                 | 3        | 2.8%    |
| Network                  | 2        | 1.87%   |
| Communication controller | 2        | 1.87%   |
| Storage/ide              | 1        | 0.93%   |
| Fingerprint reader       | 1        | 0.93%   |
| Camera                   | 1        | 0.93%   |

