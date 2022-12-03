Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 4502

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
| MSI           | 2AE0                        | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
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
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
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
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
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
| Gigabyte      | TRX40 DESIGNARE             | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
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
| System76      | Thelio thelio-r2            | [6eb968883d](https://linux-hardware.org/?probe=6eb968883d) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
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
| MSI           | B360-A PRO                  | [a5505919b5](https://linux-hardware.org/?probe=a5505919b5) | Aug 14, 2022 |
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
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3dc0a4c49](https://linux-hardware.org/?probe=e3dc0a4c49) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [36e0686495](https://linux-hardware.org/?probe=36e0686495) | Jul 28, 2022 |
| MSI           | X370 GAMING PLUS            | [a39ccd24ff](https://linux-hardware.org/?probe=a39ccd24ff) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [71f25aa9f5](https://linux-hardware.org/?probe=71f25aa9f5) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| MSI           | Z490-A PRO                  | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| HP            | 8433 11                     | [a66fb85e77](https://linux-hardware.org/?probe=a66fb85e77) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| Positivo      | POS-PIQ77CL                 | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
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
| Gigabyte      | A320M-S2H V2-CF             | [618141855c](https://linux-hardware.org/?probe=618141855c) | Jul 11, 2022 |
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
| Positivo      | POS-PIQ77CL                 | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| MSI           | B360-A PRO                  | [4534101418](https://linux-hardware.org/?probe=4534101418) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [82fe9f31c7](https://linux-hardware.org/?probe=82fe9f31c7) | Jul 04, 2022 |
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
| ASUSTek       | B85M-E/BR                   | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| ASRock        | N68-S                       | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
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
| ASUSTek       | TUF Gaming X570-PRO         | [c5a5527f1d](https://linux-hardware.org/?probe=c5a5527f1d) | Jun 23, 2022 |
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
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
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
| ASUSTek       | M5A97 R2.0                  | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| PCWare        | IPX4105G Pro                | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASRock        | B365M Pro4                  | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
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
| Dell          | 0R790T A00                  | [f9388b2163](https://linux-hardware.org/?probe=f9388b2163) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [57a20bde9f](https://linux-hardware.org/?probe=57a20bde9f) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [084dab5bd4](https://linux-hardware.org/?probe=084dab5bd4) | May 26, 2022 |
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
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [5ebbcedcc1](https://linux-hardware.org/?probe=5ebbcedcc1) | May 22, 2022 |
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
| ASUSTek       | H110M-A/DP                  | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3f9a21ddc1](https://linux-hardware.org/?probe=3f9a21ddc1) | May 19, 2022 |
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
| ASUSTek       | H170M-PLUS                  | [c1f5cb662f](https://linux-hardware.org/?probe=c1f5cb662f) | May 15, 2022 |
| ASUSTek       | Z87-K                       | [bb296e5f39](https://linux-hardware.org/?probe=bb296e5f39) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| MSI           | CSM-B85M-E45                | [85abf64cf5](https://linux-hardware.org/?probe=85abf64cf5) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Gigabyte      | B75M-D3H                    | [cfae917826](https://linux-hardware.org/?probe=cfae917826) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| Acer          | RS780HVF                    | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| HP            | 0AE8h C                     | [bc0fa7f9b8](https://linux-hardware.org/?probe=bc0fa7f9b8) | May 08, 2022 |
| HP            | 0AE8h C                     | [fdf9e3acd8](https://linux-hardware.org/?probe=fdf9e3acd8) | May 08, 2022 |
| Acer          | RS780HVF                    | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
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
| Gigabyte      | H110M-S2V-CF                | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [0e40616573](https://linux-hardware.org/?probe=0e40616573) | May 02, 2022 |
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
| MSI           | B450 TOMAHAWK MAX II        | [6db8017245](https://linux-hardware.org/?probe=6db8017245) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| MSI           | H110M PRO-VH PLUS           | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| HP            | 8704                        | [41d896b51d](https://linux-hardware.org/?probe=41d896b51d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| Gigabyte      | X570 AORUS PRO              | [44e25caaa1](https://linux-hardware.org/?probe=44e25caaa1) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| ASUSTek       | P9X79 LE                    | [ad35094812](https://linux-hardware.org/?probe=ad35094812) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 S           | [21663dc8b3](https://linux-hardware.org/?probe=21663dc8b3) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [31b5451ae1](https://linux-hardware.org/?probe=31b5451ae1) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [486215d495](https://linux-hardware.org/?probe=486215d495) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASRock        | A320M-HD                    | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| ASUSTek       | G20AJ                       | [ed023008e4](https://linux-hardware.org/?probe=ed023008e4) | Apr 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9236e9bc93](https://linux-hardware.org/?probe=9236e9bc93) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [d1d705c163](https://linux-hardware.org/?probe=d1d705c163) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [97ff7b7591](https://linux-hardware.org/?probe=97ff7b7591) | Apr 25, 2022 |
| MSI           | G31TM-P35                   | [711f26a820](https://linux-hardware.org/?probe=711f26a820) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | [2c1b91769f](https://linux-hardware.org/?probe=2c1b91769f) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [0534d32a13](https://linux-hardware.org/?probe=0534d32a13) | Apr 23, 2022 |
| ASRock        | B450 Pro4                   | [61ab02b4e8](https://linux-hardware.org/?probe=61ab02b4e8) | Apr 23, 2022 |
| ECS           | Iris8                       | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [8ae54427ca](https://linux-hardware.org/?probe=8ae54427ca) | Apr 23, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3cb8eac116](https://linux-hardware.org/?probe=3cb8eac116) | Apr 23, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | [017717599c](https://linux-hardware.org/?probe=017717599c) | Apr 22, 2022 |
| Lenovo        | 31900058 STD                | [0e3c909996](https://linux-hardware.org/?probe=0e3c909996) | Apr 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| Gigabyte      | Z270XP-SLI-CF               | [f1a2e57e22](https://linux-hardware.org/?probe=f1a2e57e22) | Apr 21, 2022 |
| Gigabyte      | AB350M-HD3-CF               | [dd16ab4768](https://linux-hardware.org/?probe=dd16ab4768) | Apr 21, 2022 |
| ASUSTek       | Z87-K                       | [480a64a95a](https://linux-hardware.org/?probe=480a64a95a) | Apr 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| ASUSTek       | P8H67-M LE                  | [0d5a9fcacc](https://linux-hardware.org/?probe=0d5a9fcacc) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-P                | [c9ef889715](https://linux-hardware.org/?probe=c9ef889715) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [61ca629904](https://linux-hardware.org/?probe=61ca629904) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [c722e417a1](https://linux-hardware.org/?probe=c722e417a1) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| ASUSTek       | Q87M-E                      | [e409d7a8df](https://linux-hardware.org/?probe=e409d7a8df) | Apr 20, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fd661468b9](https://linux-hardware.org/?probe=fd661468b9) | Apr 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dc42beaa8d](https://linux-hardware.org/?probe=dc42beaa8d) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [49d51ee541](https://linux-hardware.org/?probe=49d51ee541) | Apr 18, 2022 |
| MSI           | Z370-A PRO                  | [9f5287d8cb](https://linux-hardware.org/?probe=9f5287d8cb) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| MSI           | Z590-A PRO                  | [ebe60e3c9e](https://linux-hardware.org/?probe=ebe60e3c9e) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7b61fb0ba4](https://linux-hardware.org/?probe=7b61fb0ba4) | Apr 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f7008a1e16](https://linux-hardware.org/?probe=f7008a1e16) | Apr 17, 2022 |
| Unknown       | Unknown                     | [f5deab7689](https://linux-hardware.org/?probe=f5deab7689) | Apr 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [49c981ee41](https://linux-hardware.org/?probe=49c981ee41) | Apr 17, 2022 |
| MSI           | Z590-A PRO                  | [52a97f186f](https://linux-hardware.org/?probe=52a97f186f) | Apr 17, 2022 |
| Gigabyte      | GA-990FX-GAMING             | [dc1e145cf3](https://linux-hardware.org/?probe=dc1e145cf3) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [9a5d59c375](https://linux-hardware.org/?probe=9a5d59c375) | Apr 16, 2022 |
| ASUSTek       | Maximus VI HERO             | [923a82e975](https://linux-hardware.org/?probe=923a82e975) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [f83ee2cc17](https://linux-hardware.org/?probe=f83ee2cc17) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [eef3c69fcd](https://linux-hardware.org/?probe=eef3c69fcd) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [b0a5b307c9](https://linux-hardware.org/?probe=b0a5b307c9) | Apr 16, 2022 |
| ASUSTek       | M5A78L/USB3                 | [48deb234f0](https://linux-hardware.org/?probe=48deb234f0) | Apr 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [37e172faec](https://linux-hardware.org/?probe=37e172faec) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [0bd7facf9b](https://linux-hardware.org/?probe=0bd7facf9b) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | [17622a538e](https://linux-hardware.org/?probe=17622a538e) | Apr 14, 2022 |
| NZXT          | N7 B550                     | [71e92a4807](https://linux-hardware.org/?probe=71e92a4807) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [843c3d4758](https://linux-hardware.org/?probe=843c3d4758) | Apr 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [c372810f3f](https://linux-hardware.org/?probe=c372810f3f) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| MSI           | B550-A PRO                  | [d0933b6a76](https://linux-hardware.org/?probe=d0933b6a76) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [392f621ca6](https://linux-hardware.org/?probe=392f621ca6) | Apr 13, 2022 |
| Gigabyte      | X570 GAMING X               | [b089bb9293](https://linux-hardware.org/?probe=b089bb9293) | Apr 13, 2022 |
| System76      | Thelio Major thelio-majo... | [5924b8c844](https://linux-hardware.org/?probe=5924b8c844) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e05e4dc47b](https://linux-hardware.org/?probe=e05e4dc47b) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Dell          | 0JP3NX A00                  | [c76114b4b3](https://linux-hardware.org/?probe=c76114b4b3) | Apr 13, 2022 |
| MSI           | B250M PRO-VD                | [e5744a1f58](https://linux-hardware.org/?probe=e5744a1f58) | Apr 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [47404cf177](https://linux-hardware.org/?probe=47404cf177) | Apr 12, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [921b858e18](https://linux-hardware.org/?probe=921b858e18) | Apr 11, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [8c6cc15607](https://linux-hardware.org/?probe=8c6cc15607) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| MSI           | B360-A PRO                  | [cb8b648eac](https://linux-hardware.org/?probe=cb8b648eac) | Apr 10, 2022 |
| eMachines     | EL1850G                     | [cfa8d1c8d5](https://linux-hardware.org/?probe=cfa8d1c8d5) | Apr 10, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [28114b7924](https://linux-hardware.org/?probe=28114b7924) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [117eded7f8](https://linux-hardware.org/?probe=117eded7f8) | Apr 10, 2022 |
| Gigabyte      | Z77-DS3H                    | [88fba1bae6](https://linux-hardware.org/?probe=88fba1bae6) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1c57ef464e](https://linux-hardware.org/?probe=1c57ef464e) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [e641889a70](https://linux-hardware.org/?probe=e641889a70) | Apr 09, 2022 |
| NZXT          | N7 B550                     | [e3f895a70b](https://linux-hardware.org/?probe=e3f895a70b) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| ASUSTek       | P5QPL-AM                    | [1d0d38c7c8](https://linux-hardware.org/?probe=1d0d38c7c8) | Apr 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ed6ff884fc](https://linux-hardware.org/?probe=ed6ff884fc) | Apr 08, 2022 |
| MSI           | B450M MORTAR MAX            | [bde8b0ab3c](https://linux-hardware.org/?probe=bde8b0ab3c) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [d1f213c4f0](https://linux-hardware.org/?probe=d1f213c4f0) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS M                | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f5106f79ee](https://linux-hardware.org/?probe=f5106f79ee) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| Gigabyte      | H87M-HD3                    | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c95df20756](https://linux-hardware.org/?probe=c95df20756) | Apr 05, 2022 |
| MSI           | B360-A PRO                  | [aa22c203eb](https://linux-hardware.org/?probe=aa22c203eb) | Apr 05, 2022 |
| ASUSTek       | Z87-K                       | [8d1d44d764](https://linux-hardware.org/?probe=8d1d44d764) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7a354d771f](https://linux-hardware.org/?probe=7a354d771f) | Apr 04, 2022 |
| Pegatron      | 2AC2                        | [f6d4a4c17e](https://linux-hardware.org/?probe=f6d4a4c17e) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| Dell          | 0K240Y A03                  | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| Gigabyte      | H410M H V3                  | [48f0951752](https://linux-hardware.org/?probe=48f0951752) | Apr 02, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [62bdba9365](https://linux-hardware.org/?probe=62bdba9365) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4e2f534de0](https://linux-hardware.org/?probe=4e2f534de0) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [625d6cc105](https://linux-hardware.org/?probe=625d6cc105) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| ASUSTek       | Z87-K                       | [616258c6a5](https://linux-hardware.org/?probe=616258c6a5) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | [254b38e98f](https://linux-hardware.org/?probe=254b38e98f) | Apr 01, 2022 |
| Medion        | H81H3-EM2                   | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | [069ce7ef8f](https://linux-hardware.org/?probe=069ce7ef8f) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| MSI           | H410M PRO-VH                | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| ECS           | A55F-M4                     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | [92eae45686](https://linux-hardware.org/?probe=92eae45686) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| ASUSTek       | P8H67-M LX                  | [a30f5893f6](https://linux-hardware.org/?probe=a30f5893f6) | Mar 30, 2022 |
| ASUSTek       | PRIME X570-P                | [eeef359646](https://linux-hardware.org/?probe=eeef359646) | Mar 30, 2022 |
| System76      | Thelio thelio-r2            | [426cd0671d](https://linux-hardware.org/?probe=426cd0671d) | Mar 29, 2022 |
| Gigabyte      | EX58-UD4P                   | [b3a7b518b6](https://linux-hardware.org/?probe=b3a7b518b6) | Mar 29, 2022 |
| Intel         | DQ77MK AAG39642-400         | [29e7a23412](https://linux-hardware.org/?probe=29e7a23412) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [fb5d1f7bc1](https://linux-hardware.org/?probe=fb5d1f7bc1) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [acb42fe25a](https://linux-hardware.org/?probe=acb42fe25a) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [d39c4f7d2b](https://linux-hardware.org/?probe=d39c4f7d2b) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [dac91a1c12](https://linux-hardware.org/?probe=dac91a1c12) | Mar 28, 2022 |
| Dell          | 0D6H9T A00                  | [48ab5aae1e](https://linux-hardware.org/?probe=48ab5aae1e) | Mar 27, 2022 |
| MSI           | Z170A PC MATE               | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| Gigabyte      | B450M S2H                   | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | [986e01838e](https://linux-hardware.org/?probe=986e01838e) | Mar 27, 2022 |
| HP            | 1495                        | [19569ad62b](https://linux-hardware.org/?probe=19569ad62b) | Mar 27, 2022 |
| ASUSTek       | Z87-K                       | [d0d493d449](https://linux-hardware.org/?probe=d0d493d449) | Mar 27, 2022 |
| MSI           | B360-A PRO                  | [f3eb3387fb](https://linux-hardware.org/?probe=f3eb3387fb) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| MSI           | B450M PRO-M2 V2             | [f7daea6e27](https://linux-hardware.org/?probe=f7daea6e27) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS            | [31106ba339](https://linux-hardware.org/?probe=31106ba339) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [296d97246f](https://linux-hardware.org/?probe=296d97246f) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1272ec27ff](https://linux-hardware.org/?probe=1272ec27ff) | Mar 26, 2022 |
| ASUSTek       | B85M-G                      | [1d78876e0c](https://linux-hardware.org/?probe=1d78876e0c) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [3825c4904e](https://linux-hardware.org/?probe=3825c4904e) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [27f565aeca](https://linux-hardware.org/?probe=27f565aeca) | Mar 26, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [aae529497f](https://linux-hardware.org/?probe=aae529497f) | Mar 25, 2022 |
| MSI           | IONA                        | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| ASRock        | A75M-HVS                    | [5340d6cada](https://linux-hardware.org/?probe=5340d6cada) | Mar 25, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [0579061135](https://linux-hardware.org/?probe=0579061135) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH X58              | [bce45f36b9](https://linux-hardware.org/?probe=bce45f36b9) | Mar 25, 2022 |
| Gigabyte      | B450 AORUS M                | [81a6571a8b](https://linux-hardware.org/?probe=81a6571a8b) | Mar 25, 2022 |
| Dell          | 08WKV3 A00                  | [04bca4a56e](https://linux-hardware.org/?probe=04bca4a56e) | Mar 25, 2022 |
| MSI           | Z97 GAMING 5                | [0bb5a2b0d1](https://linux-hardware.org/?probe=0bb5a2b0d1) | Mar 24, 2022 |
| ASRock        | 4X4-V1000                   | [f02931fb21](https://linux-hardware.org/?probe=f02931fb21) | Mar 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Pegatron      | 2ACE                        | [3f091e30fe](https://linux-hardware.org/?probe=3f091e30fe) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [f7248b112d](https://linux-hardware.org/?probe=f7248b112d) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0e85a5ee68](https://linux-hardware.org/?probe=0e85a5ee68) | Mar 24, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [87989ace9b](https://linux-hardware.org/?probe=87989ace9b) | Mar 24, 2022 |
| ASUSTek       | PRIME Z390-P                | [53a7830bc0](https://linux-hardware.org/?probe=53a7830bc0) | Mar 23, 2022 |
| ASRock        | B560M-HDV                   | [f54eafc909](https://linux-hardware.org/?probe=f54eafc909) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | [e7181d25ff](https://linux-hardware.org/?probe=e7181d25ff) | Mar 23, 2022 |
| Alienware     | 0FPV4P A00                  | [b1d20542b8](https://linux-hardware.org/?probe=b1d20542b8) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [66f133fcf0](https://linux-hardware.org/?probe=66f133fcf0) | Mar 22, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [35f8ba571f](https://linux-hardware.org/?probe=35f8ba571f) | Mar 22, 2022 |
| ASUSTek       | P5KC                        | [b4511f91a2](https://linux-hardware.org/?probe=b4511f91a2) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [b789768b64](https://linux-hardware.org/?probe=b789768b64) | Mar 21, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| ASUSTek       | P5KC                        | [b2fd45aebb](https://linux-hardware.org/?probe=b2fd45aebb) | Mar 21, 2022 |
| MSI           | B250M PRO-VH                | [d3885311bc](https://linux-hardware.org/?probe=d3885311bc) | Mar 20, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [db394898e7](https://linux-hardware.org/?probe=db394898e7) | Mar 20, 2022 |
| Dell          | 0NV0M7 A02                  | [978401b13f](https://linux-hardware.org/?probe=978401b13f) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | [861e43b0c6](https://linux-hardware.org/?probe=861e43b0c6) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8328ee30d7](https://linux-hardware.org/?probe=8328ee30d7) | Mar 19, 2022 |
| ASUSTek       | PRIME B450M-A               | [893f0d0600](https://linux-hardware.org/?probe=893f0d0600) | Mar 19, 2022 |
| HP            | 2B4B                        | [def1b2ee5b](https://linux-hardware.org/?probe=def1b2ee5b) | Mar 19, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [6c60e6d6af](https://linux-hardware.org/?probe=6c60e6d6af) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d64fc66c4](https://linux-hardware.org/?probe=9d64fc66c4) | Mar 19, 2022 |
| MSI           | Z97 GUARD-PRO               | [a412a37e5f](https://linux-hardware.org/?probe=a412a37e5f) | Mar 18, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0c7c91a687](https://linux-hardware.org/?probe=0c7c91a687) | Mar 18, 2022 |
| ASRock        | H370M-ITX/ac                | [e425e911e9](https://linux-hardware.org/?probe=e425e911e9) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | P7H55-M LE                  | [a3c7a555df](https://linux-hardware.org/?probe=a3c7a555df) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a3b5b7c37e](https://linux-hardware.org/?probe=a3b5b7c37e) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5d2c6c0279](https://linux-hardware.org/?probe=5d2c6c0279) | Mar 18, 2022 |
| ASRock        | Z97 Extreme6                | [bf2f07e405](https://linux-hardware.org/?probe=bf2f07e405) | Mar 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f43e92acdd](https://linux-hardware.org/?probe=f43e92acdd) | Mar 18, 2022 |
| ASUSTek       | Z87-K                       | [984debdd3a](https://linux-hardware.org/?probe=984debdd3a) | Mar 17, 2022 |
| MSI           | H61I-E35 V2/W8              | [172c4ac7f6](https://linux-hardware.org/?probe=172c4ac7f6) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Minix         | NEO Z83-4 V1.1              | [c630bfd983](https://linux-hardware.org/?probe=c630bfd983) | Mar 15, 2022 |
| HP            | 8056                        | [4e8b5eb8bd](https://linux-hardware.org/?probe=4e8b5eb8bd) | Mar 14, 2022 |
| MSI           | G31TM-P35                   | [47bfa2ee49](https://linux-hardware.org/?probe=47bfa2ee49) | Mar 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [96846ed571](https://linux-hardware.org/?probe=96846ed571) | Mar 14, 2022 |
| ASUSTek       | H170M-PLUS                  | [ed2262d433](https://linux-hardware.org/?probe=ed2262d433) | Mar 13, 2022 |
| Biostar       | TZ590-BTC DUO               | [fa2f8683b7](https://linux-hardware.org/?probe=fa2f8683b7) | Mar 13, 2022 |
| ASUSTek       | Z97M-PLUS                   | [ed5eba97e9](https://linux-hardware.org/?probe=ed5eba97e9) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9ca31007a9](https://linux-hardware.org/?probe=9ca31007a9) | Mar 13, 2022 |
| ASUSTek       | H110T                       | [5ef8fe35e7](https://linux-hardware.org/?probe=5ef8fe35e7) | Mar 13, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [f8ef0e1c18](https://linux-hardware.org/?probe=f8ef0e1c18) | Mar 12, 2022 |
| ASUSTek       | PRIME B460M-K               | [a93650d1a2](https://linux-hardware.org/?probe=a93650d1a2) | Mar 12, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.304     | [e2e15f011b](https://linux-hardware.org/?probe=e2e15f011b) | Mar 12, 2022 |
| ASRock        | B560M-HDV                   | [45e9c424b0](https://linux-hardware.org/?probe=45e9c424b0) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6e87cdd1f8](https://linux-hardware.org/?probe=6e87cdd1f8) | Mar 12, 2022 |
| ECS           | Nettle3                     | [7a96fa9c3f](https://linux-hardware.org/?probe=7a96fa9c3f) | Mar 12, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [508f6f6c0c](https://linux-hardware.org/?probe=508f6f6c0c) | Mar 11, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [034b528c9b](https://linux-hardware.org/?probe=034b528c9b) | Mar 11, 2022 |
| ASUSTek       | H61M-A/BR                   | [f3a97cad04](https://linux-hardware.org/?probe=f3a97cad04) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [9de4c6210f](https://linux-hardware.org/?probe=9de4c6210f) | Mar 11, 2022 |
| ASUSTek       | H110T                       | [2e32ea8d20](https://linux-hardware.org/?probe=2e32ea8d20) | Mar 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Intel         | H61                         | [8ce8958b88](https://linux-hardware.org/?probe=8ce8958b88) | Mar 10, 2022 |
| ASUSTek       | H110T                       | [1a3a353683](https://linux-hardware.org/?probe=1a3a353683) | Mar 10, 2022 |
| Intel         | H61                         | [cb91470ea7](https://linux-hardware.org/?probe=cb91470ea7) | Mar 10, 2022 |
| Unknown       | Unknown                     | [b60fd7636c](https://linux-hardware.org/?probe=b60fd7636c) | Mar 10, 2022 |
| Gigabyte      | Z77P-D3                     | [55cb8434d9](https://linux-hardware.org/?probe=55cb8434d9) | Mar 09, 2022 |
| ASRock        | Z68 Pro3                    | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| ASRock        | B550M Steel Legend          | [2eeb109321](https://linux-hardware.org/?probe=2eeb109321) | Mar 09, 2022 |
| Dell          | 042P49 A02                  | [fe8ce505f4](https://linux-hardware.org/?probe=fe8ce505f4) | Mar 09, 2022 |
| MSI           | Z590 PRO WIFI [CEC]         | [e543f0217a](https://linux-hardware.org/?probe=e543f0217a) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| ASUSTek       | Z97-DELUXE                  | [a1a19b3342](https://linux-hardware.org/?probe=a1a19b3342) | Mar 08, 2022 |
| HP            | 8266                        | [3f34cb2ada](https://linux-hardware.org/?probe=3f34cb2ada) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [d5c1e965d0](https://linux-hardware.org/?probe=d5c1e965d0) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [d00f0e5d1f](https://linux-hardware.org/?probe=d00f0e5d1f) | Mar 07, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [8d0b8e2e12](https://linux-hardware.org/?probe=8d0b8e2e12) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [ea3781cdac](https://linux-hardware.org/?probe=ea3781cdac) | Mar 07, 2022 |
| ASRock        | H310M-HDV                   | [5be286e220](https://linux-hardware.org/?probe=5be286e220) | Mar 07, 2022 |
| Intel         | H61                         | [5198074ef6](https://linux-hardware.org/?probe=5198074ef6) | Mar 07, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [422afde3de](https://linux-hardware.org/?probe=422afde3de) | Mar 07, 2022 |
| HP            | 802F                        | [af498c9331](https://linux-hardware.org/?probe=af498c9331) | Mar 07, 2022 |
| ASRock        | X570 Pro4                   | [2ee17064c4](https://linux-hardware.org/?probe=2ee17064c4) | Mar 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4d84ed2405](https://linux-hardware.org/?probe=4d84ed2405) | Mar 06, 2022 |
| ASRock        | X570 Pro4                   | [e893774a5b](https://linux-hardware.org/?probe=e893774a5b) | Mar 06, 2022 |
| HP            | 8054                        | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Foxconn       | H61MXE/-S/-V/-K             | [8aa740825f](https://linux-hardware.org/?probe=8aa740825f) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [308df080e6](https://linux-hardware.org/?probe=308df080e6) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [71714718d9](https://linux-hardware.org/?probe=71714718d9) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [ccd6a19ec5](https://linux-hardware.org/?probe=ccd6a19ec5) | Mar 06, 2022 |
| Gigabyte      | H61M-S1                     | [50f8055f7f](https://linux-hardware.org/?probe=50f8055f7f) | Mar 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 20.04 | 856      | 26.63%  |
| Pop!_OS 21.04 | 718      | 22.33%  |
| Pop!_OS 20.10 | 670      | 20.84%  |
| Pop!_OS 22.04 | 526      | 16.36%  |
| Pop!_OS 21.10 | 419      | 13.03%  |
| Pop!_OS 19.10 | 15       | 0.47%   |
| Pop!_OS 19.04 | 6        | 0.19%   |
| Pop!_OS 18.04 | 4        | 0.12%   |
| Pop!_OS 18.10 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3022     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 340      | 9.82%   |
| 5.8.0-7630-generic       | 315      | 9.1%    |
| 5.4.0-7634-generic       | 281      | 8.12%   |
| 5.13.0-7614-generic      | 203      | 5.87%   |
| 5.8.0-7642-generic       | 202      | 5.84%   |
| 5.4.0-7642-generic       | 187      | 5.4%    |
| 5.11.0-7614-generic      | 180      | 5.2%    |
| 5.17.5-76051705-generic  | 174      | 5.03%   |
| 5.13.0-7620-generic      | 171      | 4.94%   |
| 5.19.0-76051900-generic  | 140      | 4.05%   |
| 5.16.11-76051611-generic | 111      | 3.21%   |
| 5.15.15-76051515-generic | 109      | 3.15%   |
| 5.15.5-76051505-generic  | 92       | 2.66%   |
| 5.11.0-7612-generic      | 87       | 2.51%   |
| 5.8.0-7625-generic       | 77       | 2.22%   |
| 5.18.10-76051810-generic | 72       | 2.08%   |
| 5.11.0-7633-generic      | 71       | 2.05%   |
| 5.17.15-76051715-generic | 68       | 1.96%   |
| 5.16.19-76051619-generic | 64       | 1.85%   |
| 5.15.8-76051508-generic  | 63       | 1.82%   |
| 5.16.15-76051615-generic | 56       | 1.62%   |
| 5.15.11-76051511-generic | 47       | 1.36%   |
| 5.4.0-7626-generic       | 43       | 1.24%   |
| 6.0.6-76060006-generic   | 38       | 1.1%    |
| 5.15.23-76051523-generic | 29       | 0.84%   |
| 5.4.0-7625-generic       | 24       | 0.69%   |
| 6.0.2-76060002-generic   | 23       | 0.66%   |
| 5.4.0-7629-generic       | 21       | 0.61%   |
| 5.19.16-76051916-generic | 17       | 0.49%   |
| 6.0.3-76060003-generic   | 13       | 0.38%   |
| 5.3.0-7629-generic       | 5        | 0.14%   |
| 5.3.0-7625-generic       | 5        | 0.14%   |
| 5.8.5-xanmod1            | 4        | 0.12%   |
| 5.8.5-050805-generic     | 4        | 0.12%   |
| 5.8.12-xanmod1           | 4        | 0.12%   |
| 5.7.8-050708-generic     | 3        | 0.09%   |
| 5.4.0-7624-generic       | 3        | 0.09%   |
| 5.3.0-7648-generic       | 3        | 0.09%   |
| 5.3.0-22-generic         | 3        | 0.09%   |
| 5.15.0-76051500-generic  | 3        | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 650      | 19.28%  |
| 5.8.0   | 566      | 16.79%  |
| 5.4.0   | 537      | 15.93%  |
| 5.13.0  | 371      | 11.01%  |
| 5.17.5  | 174      | 5.16%   |
| 5.19.0  | 140      | 4.15%   |
| 5.16.11 | 111      | 3.29%   |
| 5.15.15 | 110      | 3.26%   |
| 5.15.5  | 92       | 2.73%   |
| 5.18.10 | 72       | 2.14%   |
| 5.17.15 | 68       | 2.02%   |
| 5.16.19 | 64       | 1.9%    |
| 5.15.8  | 63       | 1.87%   |
| 5.16.15 | 56       | 1.66%   |
| 5.15.11 | 47       | 1.39%   |
| 6.0.6   | 39       | 1.16%   |
| 5.15.23 | 29       | 0.86%   |
| 6.0.2   | 24       | 0.71%   |
| 5.3.0   | 17       | 0.5%    |
| 5.19.16 | 17       | 0.5%    |
| 6.0.3   | 13       | 0.39%   |
| 5.8.5   | 8        | 0.24%   |
| 5.0.0   | 6        | 0.18%   |
| 5.8.12  | 5        | 0.15%   |
| 5.7.8   | 3        | 0.09%   |
| 5.7.0   | 3        | 0.09%   |
| 5.6.16  | 3        | 0.09%   |
| 5.15.0  | 3        | 0.09%   |
| 5.9.1   | 2        | 0.06%   |
| 5.8.6   | 2        | 0.06%   |
| 5.8.18  | 2        | 0.06%   |
| 5.7.16  | 2        | 0.06%   |
| 5.7.12  | 2        | 0.06%   |
| 5.16.0  | 2        | 0.06%   |
| 5.15.7  | 2        | 0.06%   |
| 5.15.22 | 2        | 0.06%   |
| 5.13.12 | 2        | 0.06%   |
| 5.10.23 | 2        | 0.06%   |
| 5.10.0  | 2        | 0.06%   |
| 6.0.9   | 1        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 652      | 19.54%  |
| 5.8     | 588      | 17.63%  |
| 5.4     | 539      | 16.16%  |
| 5.13    | 376      | 11.27%  |
| 5.15    | 343      | 10.28%  |
| 5.17    | 240      | 7.19%   |
| 5.16    | 222      | 6.65%   |
| 5.19    | 157      | 4.71%   |
| 6.0     | 76       | 2.28%   |
| 5.18    | 74       | 2.22%   |
| 5.3     | 17       | 0.51%   |
| 5.7     | 14       | 0.42%   |
| 5.6     | 8        | 0.24%   |
| 5.10    | 8        | 0.24%   |
| 5.0     | 6        | 0.18%   |
| 5.9     | 5        | 0.15%   |
| 5.14    | 5        | 0.15%   |
| 5.12    | 4        | 0.12%   |
| 4.18    | 1        | 0.03%   |
| 4.15    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3022     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 2918     | 95.99%  |
| KDE             | 33       | 1.09%   |
| KDE5            | 26       | 0.86%   |
| X-Cinnamon      | 16       | 0.53%   |
| Unknown         | 14       | 0.46%   |
| MATE            | 9        | 0.3%    |
| XFCE            | 7        | 0.23%   |
| Cinnamon        | 5        | 0.16%   |
| GNOME Flashback | 4        | 0.13%   |
| LXQt            | 2        | 0.07%   |
| i3              | 2        | 0.07%   |
| Budgie          | 2        | 0.07%   |
| Unity           | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2977     | 98.22%  |
| Wayland | 43       | 1.42%   |
| Tty     | 6        | 0.2%    |
| Unknown | 5        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2607     | 85.73%  |
| GDM     | 342      | 11.25%  |
| GDM3    | 80       | 2.63%   |
| SDDM    | 7        | 0.23%   |
| TDM     | 3        | 0.1%    |
| LightDM | 2        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1697     | 55.8%   |
| en_GB   | 236      | 7.76%   |
| pt_BR   | 229      | 7.53%   |
| de_DE   | 156      | 5.13%   |
| C       | 103      | 3.39%   |
| en_AU   | 97       | 3.19%   |
| en_CA   | 88       | 2.89%   |
| fr_FR   | 62       | 2.04%   |
| it_IT   | 40       | 1.32%   |
| ru_RU   | 38       | 1.25%   |
| es_ES   | 37       | 1.22%   |
| pl_PL   | 29       | 0.95%   |
| nl_NL   | 26       | 0.85%   |
| sv_SE   | 21       | 0.69%   |
| Unknown | 18       | 0.59%   |
| fi_FI   | 13       | 0.43%   |
| pt_PT   | 12       | 0.39%   |
| fr_CA   | 8        | 0.26%   |
| zh_TW   | 7        | 0.23%   |
| es_CL   | 7        | 0.23%   |
| es_AR   | 7        | 0.23%   |
| en_DK   | 7        | 0.23%   |
| nl_BE   | 6        | 0.2%    |
| en_NZ   | 6        | 0.2%    |
| en_IN   | 6        | 0.2%    |
| sk_SK   | 5        | 0.16%   |
| ja_JP   | 5        | 0.16%   |
| es_MX   | 5        | 0.16%   |
| en_ZA   | 5        | 0.16%   |
| da_DK   | 5        | 0.16%   |
| cs_CZ   | 5        | 0.16%   |
| tr_TR   | 4        | 0.13%   |
| hr_HR   | 4        | 0.13%   |
| fr_CH   | 4        | 0.13%   |
| zh_CN   | 3        | 0.1%    |
| uk_UA   | 3        | 0.1%    |
| nb_NO   | 3        | 0.1%    |
| hu_HU   | 3        | 0.1%    |
| en_IL   | 3        | 0.1%    |
| ro_RO   | 2        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2461     | 80.53%  |
| EFI  | 595      | 19.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2912     | 96.07%  |
| Overlay | 53       | 1.75%   |
| Btrfs   | 51       | 1.68%   |
| Xfs     | 6        | 0.2%    |
| Unknown | 5        | 0.16%   |
| Zfs     | 4        | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2598     | 85.46%  |
| GPT     | 378      | 12.43%  |
| MBR     | 64       | 2.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2937     | 96.8%   |
| Yes       | 97       | 3.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2774     | 91.31%  |
| Yes       | 264      | 8.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 851      | 28.16%  |
| Gigabyte Technology | 599      | 19.82%  |
| MSI                 | 450      | 14.89%  |
| ASRock              | 310      | 10.26%  |
| Dell                | 233      | 7.71%   |
| Hewlett-Packard     | 153      | 5.06%   |
| Lenovo              | 75       | 2.48%   |
| Intel               | 55       | 1.82%   |
| System76            | 29       | 0.96%   |
| Pegatron            | 24       | 0.79%   |
| Acer                | 23       | 0.76%   |
| Unknown             | 19       | 0.63%   |
| Foxconn             | 16       | 0.53%   |
| Biostar             | 16       | 0.53%   |
| Alienware           | 16       | 0.53%   |
| ECS                 | 15       | 0.5%    |
| Fujitsu             | 12       | 0.4%    |
| Medion              | 10       | 0.33%   |
| Apple               | 10       | 0.33%   |
| Positivo            | 9        | 0.3%    |
| Huanan              | 9        | 0.3%    |
| PCWare              | 8        | 0.26%   |
| Supermicro          | 7        | 0.23%   |
| Gateway             | 6        | 0.2%    |
| Minix               | 5        | 0.17%   |
| EVGA                | 5        | 0.17%   |
| BESSTAR Tech        | 4        | 0.13%   |
| OEM                 | 3        | 0.1%    |
| MACHINIST           | 3        | 0.1%    |
| TYAN Computer       | 2        | 0.07%   |
| T-bao               | 2        | 0.07%   |
| Shuttle             | 2        | 0.07%   |
| NZXT                | 2        | 0.07%   |
| Megaware            | 2        | 0.07%   |
| MAXSUN              | 2        | 0.07%   |
| Login Informatica   | 2        | 0.07%   |
| Google              | 2        | 0.07%   |
| Fujitsu Siemens     | 2        | 0.07%   |
| eMachines           | 2        | 0.07%   |
| Colorful Technology | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 79       | 2.61%   |
| ASUS TUF Gaming X570-PLUS      | 35       | 1.16%   |
| Gigabyte B450M DS3H            | 33       | 1.09%   |
| MSI MS-7C02                    | 29       | 0.96%   |
| MSI MS-7C37                    | 26       | 0.86%   |
| MSI MS-7B86                    | 25       | 0.83%   |
| ASUS ROG STRIX B450-F GAMING   | 25       | 0.83%   |
| ASUS PRIME B450M-A             | 21       | 0.69%   |
| Dell OptiPlex 9020             | 20       | 0.66%   |
| ASUS ROG STRIX B550-F GAMING   | 20       | 0.66%   |
| Unknown                        | 20       | 0.66%   |
| System76 Thelio                | 19       | 0.63%   |
| Gigabyte X570 AORUS ELITE      | 18       | 0.6%    |
| ASRock B450M Pro4              | 16       | 0.53%   |
| Dell OptiPlex 7010             | 15       | 0.5%    |
| ASRock B450M Steel Legend      | 15       | 0.5%    |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.43%   |
| MSI MS-7C91                    | 12       | 0.4%    |
| Gigabyte X570 AORUS MASTER     | 12       | 0.4%    |
| Gigabyte B450 AORUS M          | 12       | 0.4%    |
| Gigabyte A320M-S2H             | 12       | 0.4%    |
| ASUS PRIME B450M-GAMING/BR     | 12       | 0.4%    |
| MSI MS-7B89                    | 11       | 0.36%   |
| MSI MS-7B79                    | 11       | 0.36%   |
| Gigabyte B75M-D3H              | 11       | 0.36%   |
| Dell OptiPlex 3010             | 11       | 0.36%   |
| ASUS TUF Gaming X570-PRO       | 11       | 0.36%   |
| Gigabyte B450 AORUS PRO WIFI   | 10       | 0.33%   |
| ASUS TUF Gaming B550-PLUS      | 10       | 0.33%   |
| ASUS ROG STRIX B350-F GAMING   | 10       | 0.33%   |
| System76 Thelio Major          | 9        | 0.3%    |
| MSI MS-7C84                    | 9        | 0.3%    |
| MSI MS-7B85                    | 9        | 0.3%    |
| MSI MS-7693                    | 9        | 0.3%    |
| HP Compaq 8200 Elite SFF PC    | 9        | 0.3%    |
| Dell OptiPlex 790              | 9        | 0.3%    |
| Dell OptiPlex 3020             | 9        | 0.3%    |
| ASUS TUF Gaming B550M-PLUS     | 9        | 0.3%    |
| ASUS ROG STRIX X570-E GAMING   | 9        | 0.3%    |
| ASUS ROG STRIX B550-I GAMING   | 9        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 184      | 6.09%   |
| ASUS PRIME             | 159      | 5.26%   |
| Dell OptiPlex          | 130      | 4.3%    |
| ASUS TUF               | 106      | 3.51%   |
| ASUS All               | 79       | 2.61%   |
| Gigabyte X570          | 66       | 2.18%   |
| HP Compaq              | 51       | 1.69%   |
| Gigabyte B450          | 46       | 1.52%   |
| Gigabyte B450M         | 45       | 1.49%   |
| Lenovo ThinkCentre     | 44       | 1.46%   |
| Dell Precision         | 40       | 1.32%   |
| ASRock B450M           | 37       | 1.22%   |
| ASRock X570            | 31       | 1.03%   |
| System76 Thelio        | 29       | 0.96%   |
| MSI MS-7C02            | 29       | 0.96%   |
| MSI MS-7C37            | 26       | 0.86%   |
| Gigabyte B550          | 26       | 0.86%   |
| MSI MS-7B86            | 25       | 0.83%   |
| Dell Inspiron          | 25       | 0.83%   |
| ASRock B450            | 21       | 0.69%   |
| Unknown                | 20       | 0.66%   |
| ASUS SABERTOOTH        | 19       | 0.63%   |
| HP EliteDesk           | 17       | 0.56%   |
| Dell XPS               | 17       | 0.56%   |
| Gigabyte Z390          | 16       | 0.53%   |
| Gigabyte GA-78LMT-USB3 | 16       | 0.53%   |
| Gigabyte A320M-S2H     | 15       | 0.5%    |
| ASUS P8Z77-V           | 15       | 0.5%    |
| ASUS M5A97             | 14       | 0.46%   |
| ASUS M5A78L-M          | 14       | 0.46%   |
| Acer Aspire            | 14       | 0.46%   |
| MSI MS-7C91            | 12       | 0.4%    |
| ASUS Maximus           | 12       | 0.4%    |
| ASUS CROSSHAIR         | 12       | 0.4%    |
| MSI MS-7B89            | 11       | 0.36%   |
| MSI MS-7B79            | 11       | 0.36%   |
| Lenovo IdeaCentre      | 11       | 0.36%   |
| HP ProDesk             | 11       | 0.36%   |
| Gigabyte X470          | 11       | 0.36%   |
| Gigabyte B75M-D3H      | 11       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 499      | 16.51%  |
| 2019 | 375      | 12.41%  |
| 2020 | 332      | 10.99%  |
| 2012 | 255      | 8.44%   |
| 2017 | 229      | 7.58%   |
| 2013 | 207      | 6.85%   |
| 2011 | 187      | 6.19%   |
| 2014 | 181      | 5.99%   |
| 2021 | 133      | 4.4%    |
| 2015 | 127      | 4.2%    |
| 2016 | 125      | 4.14%   |
| 2010 | 119      | 3.94%   |
| 2009 | 104      | 3.44%   |
| 2008 | 62       | 2.05%   |
| 2007 | 51       | 1.69%   |
| 2022 | 24       | 0.79%   |
| 2006 | 12       | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3022     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3020     | 99.93%  |
| Enabled  | 2        | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3020     | 99.93%  |
| Yes  | 2        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1010     | 32.76%  |
| 32.01-64.0      | 629      | 20.4%   |
| 8.01-16.0       | 578      | 18.75%  |
| 4.01-8.0        | 300      | 9.73%   |
| 3.01-4.0        | 245      | 7.95%   |
| 64.01-256.0     | 180      | 5.84%   |
| 24.01-32.0      | 92       | 2.98%   |
| 1.01-2.0        | 29       | 0.94%   |
| 2.01-3.0        | 11       | 0.36%   |
| More than 256.0 | 8        | 0.26%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 945      | 28.45%  |
| 1.01-2.0    | 899      | 27.06%  |
| 4.01-8.0    | 672      | 20.23%  |
| 3.01-4.0    | 593      | 17.85%  |
| 8.01-16.0   | 151      | 4.55%   |
| 16.01-24.0  | 29       | 0.87%   |
| 32.01-64.0  | 12       | 0.36%   |
| 24.01-32.0  | 11       | 0.33%   |
| 0.51-1.0    | 7        | 0.21%   |
| 64.01-256.0 | 3        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1018     | 32.62%  |
| 2      | 931      | 29.83%  |
| 3      | 570      | 18.26%  |
| 4      | 332      | 10.64%  |
| 5      | 139      | 4.45%   |
| 6      | 61       | 1.95%   |
| 7      | 23       | 0.74%   |
| 0      | 16       | 0.51%   |
| 8      | 8        | 0.26%   |
| 11     | 7        | 0.22%   |
| 9      | 7        | 0.22%   |
| 10     | 3        | 0.1%    |
| 23     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 19     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2022     | 66.32%  |
| Yes       | 1027     | 33.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2983     | 98.68%  |
| No        | 40       | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1600     | 52.36%  |
| No        | 1456     | 47.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1871     | 61.18%  |
| Yes       | 1187     | 38.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1041     | 34.27%  |
| Brazil       | 285      | 9.38%   |
| Germany      | 207      | 6.81%   |
| UK           | 168      | 5.53%   |
| Canada       | 160      | 5.27%   |
| Australia    | 113      | 3.72%   |
| Netherlands  | 75       | 2.47%   |
| Italy        | 68       | 2.24%   |
| France       | 65       | 2.14%   |
| Sweden       | 58       | 1.91%   |
| Poland       | 51       | 1.68%   |
| Russia       | 44       | 1.45%   |
| South Africa | 36       | 1.18%   |
| Spain        | 35       | 1.15%   |
| India        | 34       | 1.12%   |
| Finland      | 32       | 1.05%   |
| Switzerland  | 28       | 0.92%   |
| Romania      | 26       | 0.86%   |
| Norway       | 24       | 0.79%   |
| New Zealand  | 24       | 0.79%   |
| Mexico       | 23       | 0.76%   |
| Austria      | 23       | 0.76%   |
| Portugal     | 21       | 0.69%   |
| Philippines  | 20       | 0.66%   |
| Greece       | 20       | 0.66%   |
| Denmark      | 20       | 0.66%   |
| Belgium      | 20       | 0.66%   |
| Argentina    | 20       | 0.66%   |
| Czechia      | 16       | 0.53%   |
| Chile        | 14       | 0.46%   |
| Bulgaria     | 14       | 0.46%   |
| Ireland      | 13       | 0.43%   |
| Japan        | 12       | 0.39%   |
| Ukraine      | 11       | 0.36%   |
| Slovakia     | 10       | 0.33%   |
| Serbia       | 10       | 0.33%   |
| Lithuania    | 10       | 0.33%   |
| Israel       | 10       | 0.33%   |
| Hungary      | 10       | 0.33%   |
| Turkey       | 9        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 37       | 1.18%   |
| Sydney         | 32       | 1.02%   |
| Berlin         | 24       | 0.76%   |
| Melbourne      | 22       | 0.7%    |
| Miami          | 19       | 0.61%   |
| Brisbane       | 18       | 0.57%   |
| Rio de Janeiro | 17       | 0.54%   |
| Helsinki       | 15       | 0.48%   |
| Browning       | 15       | 0.48%   |
| Warsaw         | 14       | 0.45%   |
| Vienna         | 14       | 0.45%   |
| Milan          | 13       | 0.41%   |
| Denver         | 13       | 0.41%   |
| Chicago        | 13       | 0.41%   |
| Seattle        | 12       | 0.38%   |
| Phoenix        | 12       | 0.38%   |
| Perth          | 12       | 0.38%   |
| London         | 12       | 0.38%   |
| Auckland       | 12       | 0.38%   |
| Moscow         | 11       | 0.35%   |
| Dallas         | 11       | 0.35%   |
| Athens         | 11       | 0.35%   |
| Amsterdam      | 11       | 0.35%   |
| Adelaide       | 11       | 0.35%   |
| Toronto        | 10       | 0.32%   |
| Montreal       | 10       | 0.32%   |
| Edmonton       | 10       | 0.32%   |
| Cape Town      | 10       | 0.32%   |
| Calgary        | 10       | 0.32%   |
| Washington     | 9        | 0.29%   |
| St Louis       | 9        | 0.29%   |
| Sofia          | 9        | 0.29%   |
| Paris          | 9        | 0.29%   |
| Atlanta        | 9        | 0.29%   |
| Rome           | 8        | 0.25%   |
| New York       | 8        | 0.25%   |
| Madrid         | 8        | 0.25%   |
| Las Vegas      | 8        | 0.25%   |
| Johannesburg   | 8        | 0.25%   |
| Budapest       | 8        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 1064     | 1660   | 17.96%  |
| WDC                       | 1025     | 1556   | 17.3%   |
| Samsung Electronics       | 1018     | 1723   | 17.18%  |
| Kingston                  | 366      | 484    | 6.18%   |
| SanDisk                   | 357      | 476    | 6.03%   |
| Crucial                   | 269      | 379    | 4.54%   |
| Toshiba                   | 259      | 329    | 4.37%   |
| Hitachi                   | 150      | 195    | 2.53%   |
| Phison                    | 146      | 219    | 2.46%   |
| Intel                     | 128      | 176    | 2.16%   |
| A-DATA Technology         | 92       | 119    | 1.55%   |
| PNY                       | 70       | 93     | 1.18%   |
| Silicon Motion            | 67       | 95     | 1.13%   |
| Micron/Crucial Technology | 65       | 84     | 1.1%    |
| China                     | 64       | 94     | 1.08%   |
| Unknown                   | 51       | 79     | 0.86%   |
| HGST                      | 42       | 57     | 0.71%   |
| OCZ                       | 41       | 56     | 0.69%   |
| SK hynix                  | 38       | 51     | 0.64%   |
| XPG                       | 35       | 47     | 0.59%   |
| Micron Technology         | 31       | 46     | 0.52%   |
| SPCC                      | 30       | 39     | 0.51%   |
| Maxtor                    | 30       | 31     | 0.51%   |
| Corsair                   | 30       | 39     | 0.51%   |
| Patriot                   | 28       | 40     | 0.47%   |
| Realtek Semiconductor     | 26       | 30     | 0.44%   |
| Team                      | 22       | 26     | 0.37%   |
| Phison Electronics        | 18       | 26     | 0.3%    |
| Intenso                   | 16       | 18     | 0.27%   |
| Lexar                     | 14       | 15     | 0.24%   |
| Hewlett-Packard           | 14       | 19     | 0.24%   |
| JMicron Technology        | 12       | 22     | 0.2%    |
| GOODRAM                   | 11       | 11     | 0.19%   |
| Gigabyte Technology       | 11       | 11     | 0.19%   |
| Transcend                 | 10       | 12     | 0.17%   |
| KingSpec                  | 10       | 13     | 0.17%   |
| T-FORCE                   | 9        | 11     | 0.15%   |
| SABRENT                   | 9        | 9      | 0.15%   |
| Apacer                    | 9        | 12     | 0.15%   |
| Mushkin                   | 8        | 10     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB        | 131      | 1.9%    |
| Samsung NVMe SSD Drive 500GB      | 117      | 1.7%    |
| Kingston SA400S37240G 240GB SSD   | 97       | 1.41%   |
| Seagate ST2000DM008-2FR102 2TB    | 90       | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB    | 87       | 1.26%   |
| Samsung SSD 850 EVO 250GB         | 79       | 1.15%   |
| Seagate ST500DM002-1BD142 500GB   | 73       | 1.06%   |
| Samsung SSD 850 EVO 500GB         | 71       | 1.03%   |
| Samsung SSD 860 EVO 500GB         | 66       | 0.96%   |
| SanDisk NVMe SSD Drive 500GB      | 65       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB          | 64       | 0.93%   |
| SanDisk NVMe SSD Drive 1TB        | 63       | 0.91%   |
| Samsung SSD 860 EVO 1TB           | 62       | 0.9%    |
| Kingston SA400S37120G 120GB SSD   | 57       | 0.83%   |
| Samsung NVMe SSD Drive 250GB      | 47       | 0.68%   |
| Crucial CT1000MX500SSD1 1TB       | 46       | 0.67%   |
| Seagate ST1000DM003-1CH162 1TB    | 44       | 0.64%   |
| Phison NVMe SSD Drive 1TB         | 43       | 0.62%   |
| Kingston SA400S37480G 480GB SSD   | 42       | 0.61%   |
| Toshiba DT01ACA100 1TB            | 40       | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB    | 38       | 0.55%   |
| Kingston SV300S37A120G 120GB SSD  | 38       | 0.55%   |
| Micron/Crucial NVMe SSD Drive 1TB | 37       | 0.54%   |
| Crucial CT500MX500SSD1 500GB      | 36       | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB    | 33       | 0.48%   |
| Samsung SSD 860 EVO 250GB         | 33       | 0.48%   |
| Samsung NVMe SSD Drive 2TB        | 29       | 0.42%   |
| Crucial CT240BX500SSD1 240GB      | 29       | 0.42%   |
| Seagate ST2000DM006-2DM164 2TB    | 28       | 0.41%   |
| Samsung SSD 840 EVO 250GB         | 28       | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB          | 27       | 0.39%   |
| Toshiba HDWD110 1TB               | 27       | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB    | 27       | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB      | 27       | 0.39%   |
| Samsung SSD 860 QVO 1TB           | 27       | 0.39%   |
| Phison NVMe SSD Drive 2TB         | 27       | 0.39%   |
| Seagate ST3500418AS 500GB         | 26       | 0.38%   |
| Intel NVMe SSD Drive 1024GB       | 25       | 0.36%   |
| Toshiba DT01ACA200 2TB            | 24       | 0.35%   |
| Seagate ST31000524AS 1TB          | 24       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1034     | 1579   | 40.84%  |
| WDC                 | 891      | 1318   | 35.19%  |
| Toshiba             | 231      | 292    | 9.12%   |
| Hitachi             | 150      | 195    | 5.92%   |
| Samsung Electronics | 102      | 123    | 4.03%   |
| HGST                | 42       | 57     | 1.66%   |
| Maxtor              | 26       | 27     | 1.03%   |
| Unknown             | 17       | 25     | 0.67%   |
| ASMT                | 7        | 8      | 0.28%   |
| Apple               | 6        | 8      | 0.24%   |
| Fujitsu             | 4        | 5      | 0.16%   |
| USB                 | 3        | 4      | 0.12%   |
| JMicron Technology  | 3        | 8      | 0.12%   |
| Hewlett-Packard     | 3        | 5      | 0.12%   |
| ExcelStor           | 3        | 3      | 0.12%   |
| Magnetic Data       | 2        | 2      | 0.08%   |
| SABRENT             | 1        | 1      | 0.04%   |
| Quantum             | 1        | 1      | 0.04%   |
| OEM                 | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| Glyph               | 1        | 2      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 578      | 898    | 26.5%   |
| Kingston            | 313      | 410    | 14.35%  |
| Crucial             | 253      | 354    | 11.6%   |
| SanDisk             | 192      | 252    | 8.8%    |
| WDC                 | 159      | 205    | 7.29%   |
| A-DATA Technology   | 81       | 106    | 3.71%   |
| PNY                 | 69       | 92     | 3.16%   |
| China               | 63       | 93     | 2.89%   |
| Intel               | 56       | 71     | 2.57%   |
| OCZ                 | 40       | 52     | 1.83%   |
| Patriot             | 28       | 40     | 1.28%   |
| SPCC                | 27       | 32     | 1.24%   |
| Corsair             | 23       | 29     | 1.05%   |
| SK hynix            | 22       | 32     | 1.01%   |
| Team                | 21       | 25     | 0.96%   |
| Micron Technology   | 19       | 23     | 0.87%   |
| Toshiba             | 17       | 18     | 0.78%   |
| Seagate             | 16       | 29     | 0.73%   |
| Lexar               | 13       | 14     | 0.6%    |
| Transcend           | 10       | 12     | 0.46%   |
| KingSpec            | 10       | 13     | 0.46%   |
| Intenso             | 10       | 12     | 0.46%   |
| Hewlett-Packard     | 10       | 13     | 0.46%   |
| GOODRAM             | 9        | 9      | 0.41%   |
| Apacer              | 9        | 12     | 0.41%   |
| Gigabyte Technology | 8        | 8      | 0.37%   |
| Plextor             | 7        | 9      | 0.32%   |
| LITEONIT            | 7        | 7      | 0.32%   |
| Netac               | 6        | 6      | 0.28%   |
| Mushkin             | 6        | 8      | 0.28%   |
| TO Exter            | 5        | 8      | 0.23%   |
| LITEON              | 5        | 9      | 0.23%   |
| KingDian            | 5        | 6      | 0.23%   |
| Maxtor              | 4        | 4      | 0.18%   |
| JMicron Technology  | 4        | 4      | 0.18%   |
| PNY USB             | 3        | 10     | 0.14%   |
| OWC                 | 3        | 12     | 0.14%   |
| Dogfish             | 3        | 3      | 0.14%   |
| XPG                 | 2        | 3      | 0.09%   |
| Verbatim            | 2        | 3      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1979     | 3669   | 39.68%  |
| SSD     | 1767     | 3025   | 35.43%  |
| NVMe    | 1113     | 1836   | 22.31%  |
| Unknown | 114      | 169    | 2.29%   |
| MMC     | 15       | 19     | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2687     | 6509   | 66.54%  |
| NVMe | 1109     | 1819   | 27.46%  |
| SAS  | 227      | 371    | 5.62%   |
| MMC  | 15       | 19     | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1991     | 3425   | 48.56%  |
| 0.51-1.0   | 1187     | 1841   | 28.95%  |
| 1.01-2.0   | 500      | 721    | 12.2%   |
| 3.01-4.0   | 166      | 273    | 4.05%   |
| 2.01-3.0   | 126      | 179    | 3.07%   |
| 4.01-10.0  | 113      | 211    | 2.76%   |
| 10.01-20.0 | 17       | 44     | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 743      | 23.42%  |
| 251-500        | 640      | 20.18%  |
| 501-1000       | 614      | 19.36%  |
| 1001-2000      | 432      | 13.62%  |
| More than 3000 | 313      | 9.87%   |
| 2001-3000      | 177      | 5.58%   |
| 51-100         | 107      | 3.37%   |
| 1-20           | 71       | 2.24%   |
| 21-50          | 54       | 1.7%    |
| Unknown        | 21       | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1086     | 32.97%  |
| 21-50          | 550      | 16.7%   |
| 101-250        | 392      | 11.9%   |
| 51-100         | 343      | 10.41%  |
| 251-500        | 304      | 9.23%   |
| 501-1000       | 235      | 7.13%   |
| 1001-2000      | 184      | 5.59%   |
| More than 3000 | 115      | 3.49%   |
| 2001-3000      | 64       | 1.94%   |
| Unknown        | 21       | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 4      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 2.27%   |
| Seagate ST1500DL003-9VT16L 1TB     | 3        | 3      | 2.27%   |
| Seagate ST1000DM003-9YN162 1TB     | 3        | 3      | 2.27%   |
| Samsung Electronics HD502HI 500GB  | 3        | 3      | 2.27%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 5      | 2.27%   |
| WDC WD3200AAKS-75B3A0 320GB        | 2        | 2      | 1.52%   |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 2      | 1.52%   |
| Toshiba HDWD110 1TB                | 2        | 2      | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2      | 1.52%   |
| Samsung Electronics HD103SJ 1TB    | 2        | 2      | 1.52%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 3      | 1.52%   |
| Hitachi HDP725050GLA360 500GB      | 2        | 2      | 1.52%   |
| Crucial CT525MX300SSD1 528GB       | 2        | 2      | 1.52%   |
| WDC WD7500BPVT-60HXZT1 752GB       | 1        | 1      | 0.76%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1        | 1      | 0.76%   |
| WDC WD6400AAKS-22A7B2 640GB        | 1        | 1      | 0.76%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 1      | 0.76%   |
| WDC WD5001AALS-00J7B1 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1        | 2      | 0.76%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1        | 2      | 0.76%   |
| WDC WD5000AVVS-63H0B1 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000AAKS-41YGA1 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 0.76%   |
| WDC WD5000AADS-00M2B0 500GB        | 1        | 1      | 0.76%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 0.76%   |
| WDC WD30EZRX-00SPEB0 3TB           | 1        | 1      | 0.76%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 0.76%   |
| WDC WD20EFRX-68AX9N0 2TB           | 1        | 4      | 0.76%   |
| WDC WD2003FYYS-05T9B0 2TB          | 1        | 1      | 0.76%   |
| WDC WD15EVDS-73V9B0 1TB            | 1        | 1      | 0.76%   |
| WDC WD15EADS-11P8B1 1TB            | 1        | 1      | 0.76%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 2      | 0.76%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 1      | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 2      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 43     | 28.91%  |
| WDC                 | 34       | 41     | 26.56%  |
| Samsung Electronics | 18       | 22     | 14.06%  |
| Kingston            | 7        | 10     | 5.47%   |
| Toshiba             | 6        | 6      | 4.69%   |
| HGST                | 5        | 5      | 3.91%   |
| Hitachi             | 4        | 5      | 3.13%   |
| Crucial             | 3        | 3      | 2.34%   |
| Intel               | 2        | 2      | 1.56%   |
| SPCC                | 1        | 1      | 0.78%   |
| SanDisk             | 1        | 1      | 0.78%   |
| SABRENT             | 1        | 1      | 0.78%   |
| S3+                 | 1        | 1      | 0.78%   |
| Plextor             | 1        | 1      | 0.78%   |
| Micron Technology   | 1        | 1      | 0.78%   |
| Maxtor              | 1        | 1      | 0.78%   |
| Intenso             | 1        | 1      | 0.78%   |
| China               | 1        | 1      | 0.78%   |
| BAITITON            | 1        | 1      | 0.78%   |
| ASMT                | 1        | 1      | 0.78%   |
| A-DATA Technology   | 1        | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 43     | 37.76%  |
| WDC                 | 34       | 41     | 34.69%  |
| Samsung Electronics | 10       | 10     | 10.2%   |
| Toshiba             | 6        | 6      | 6.12%   |
| HGST                | 5        | 5      | 5.1%    |
| Hitachi             | 4        | 5      | 4.08%   |
| Maxtor              | 1        | 1      | 1.02%   |
| ASMT                | 1        | 1      | 1.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 87       | 112    | 74.36%  |
| SSD  | 27       | 34     | 23.08%  |
| NVMe | 3        | 3      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Patriot Pyro SSD 120GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Patriot | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2619     | 7461   | 82.18%  |
| Works    | 457      | 1105   | 14.34%  |
| Malfunc  | 109      | 149    | 3.42%   |
| Failed   | 1        | 2      | 0.03%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1654     | 35.36%  |
| AMD                              | 1340     | 28.65%  |
| Samsung Electronics              | 499      | 10.67%  |
| SanDisk                          | 189      | 4.04%   |
| ASMedia Technology               | 180      | 3.85%   |
| Phison Electronics               | 173      | 3.7%    |
| Micron/Crucial Technology        | 81       | 1.73%   |
| Marvell Technology Group         | 79       | 1.69%   |
| JMicron Technology               | 75       | 1.6%    |
| Silicon Motion                   | 73       | 1.56%   |
| Nvidia                           | 59       | 1.26%   |
| Kingston Technology Company      | 59       | 1.26%   |
| ADATA Technology                 | 45       | 0.96%   |
| Realtek Semiconductor            | 31       | 0.66%   |
| Broadcom / LSI                   | 19       | 0.41%   |
| SK hynix                         | 16       | 0.34%   |
| Toshiba America Info Systems     | 14       | 0.3%    |
| Micron Technology                | 14       | 0.3%    |
| LSI Logic / Symbios Logic        | 14       | 0.3%    |
| Seagate Technology               | 13       | 0.28%   |
| VIA Technologies                 | 10       | 0.21%   |
| Lite-On Technology               | 8        | 0.17%   |
| Silicon Image                    | 6        | 0.13%   |
| Shenzhen Longsys Electronics     | 4        | 0.09%   |
| INNOGRIT                         | 4        | 0.09%   |
| Adaptec                          | 4        | 0.09%   |
| HighPoint Technologies           | 3        | 0.06%   |
| Silicon Integrated Systems [SiS] | 2        | 0.04%   |
| Hewlett-Packard                  | 2        | 0.04%   |
| Union Memory (Shenzhen)          | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| KIOXIA                           | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 901      | 15.59%  |
| AMD 400 Series Chipset SATA Controller                                                  | 411      | 7.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 323      | 5.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 181      | 3.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 173      | 2.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 171      | 2.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 148      | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 146      | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 134      | 2.32%   |
| Intel SATA Controller [RAID mode]                                                       | 133      | 2.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 117      | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 97       | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 96       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 95       | 1.64%   |
| Phison E12 NVMe Controller                                                              | 88       | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 72       | 1.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 71       | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 71       | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 70       | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 68       | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 64       | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 64       | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 64       | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 61       | 1.06%   |
| AMD FCH SATA Controller D                                                               | 61       | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 60       | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 53       | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 49       | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 44       | 0.76%   |
| Intel SSD 660P Series                                                                   | 44       | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 44       | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 41       | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 41       | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 40       | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 39       | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 37       | 0.64%   |
| Samsung NVMe SSD Controller 980                                                         | 36       | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.62%   |
| Nvidia MCP61 IDE                                                                        | 33       | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 32       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2562     | 57.73%  |
| NVMe | 1112     | 25.06%  |
| IDE  | 512      | 11.54%  |
| RAID | 212      | 4.78%   |
| SAS  | 29       | 0.65%   |
| SCSI | 11       | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1628     | 53.87%  |
| AMD    | 1394     | 46.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 137      | 4.51%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 108      | 3.55%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 63       | 2.07%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 56       | 1.84%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 50       | 1.64%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 50       | 1.64%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 48       | 1.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 45       | 1.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 40       | 1.32%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 40       | 1.32%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 40       | 1.32%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 39       | 1.28%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 36       | 1.18%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 35       | 1.15%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 34       | 1.12%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 34       | 1.12%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 31       | 1.02%   |
| AMD FX-8350 Eight-Core Processor            | 31       | 1.02%   |
| AMD FX-6300 Six-Core Processor              | 31       | 1.02%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 29       | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 28       | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 28       | 0.92%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 28       | 0.92%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 27       | 0.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 26       | 0.86%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 23       | 0.76%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 23       | 0.76%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.76%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 23       | 0.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 21       | 0.69%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 20       | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 20       | 0.66%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 20       | 0.66%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 19       | 0.63%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 18       | 0.59%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 18       | 0.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 18       | 0.59%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 18       | 0.59%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 18       | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 514      | 16.94%  |
| AMD Ryzen 5             | 481      | 15.85%  |
| Intel Core i7           | 474      | 15.62%  |
| AMD Ryzen 7             | 312      | 10.28%  |
| AMD Ryzen 9             | 155      | 5.11%   |
| Intel Core i3           | 153      | 5.04%   |
| Intel Xeon              | 138      | 4.55%   |
| AMD FX                  | 109      | 3.59%   |
| AMD Ryzen 3             | 59       | 1.94%   |
| Intel Core i9           | 53       | 1.75%   |
| Other                   | 52       | 1.71%   |
| Intel Core 2 Duo        | 49       | 1.61%   |
| Intel Core 2 Quad       | 46       | 1.52%   |
| AMD Ryzen Threadripper  | 45       | 1.48%   |
| Intel Pentium           | 43       | 1.42%   |
| Intel Celeron           | 37       | 1.22%   |
| AMD Phenom II X4        | 31       | 1.02%   |
| Intel Pentium Dual-Core | 29       | 0.96%   |
| AMD A8                  | 25       | 0.82%   |
| AMD A10                 | 25       | 0.82%   |
| AMD Athlon II X2        | 19       | 0.63%   |
| Intel Core 2            | 16       | 0.53%   |
| AMD Athlon              | 16       | 0.53%   |
| AMD A6                  | 14       | 0.46%   |
| AMD Phenom II X6        | 12       | 0.4%    |
| AMD Athlon II X4        | 12       | 0.4%    |
| AMD A4                  | 11       | 0.36%   |
| AMD Athlon 64 X2        | 10       | 0.33%   |
| Intel Atom              | 9        | 0.3%    |
| AMD Phenom              | 9        | 0.3%    |
| Intel Pentium Dual      | 8        | 0.26%   |
| AMD Ryzen 5 PRO         | 8        | 0.26%   |
| Intel Pentium Gold      | 6        | 0.2%    |
| AMD Athlon X4           | 6        | 0.2%    |
| Intel Pentium D         | 5        | 0.16%   |
| AMD Sempron             | 5        | 0.16%   |
| AMD Ryzen 7 PRO         | 4        | 0.13%   |
| AMD Ryzen 3 PRO         | 4        | 0.13%   |
| AMD Athlon 64           | 4        | 0.13%   |
| AMD PRO A10             | 3        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1173     | 38.66%  |
| 6      | 634      | 20.9%   |
| 2      | 446      | 14.7%   |
| 8      | 434      | 14.3%   |
| 12     | 137      | 4.52%   |
| 16     | 63       | 2.08%   |
| 3      | 47       | 1.55%   |
| 10     | 30       | 0.99%   |
| 1      | 29       | 0.96%   |
| 32     | 16       | 0.53%   |
| 24     | 16       | 0.53%   |
| 64     | 4        | 0.13%   |
| 14     | 3        | 0.1%    |
| 28     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2992     | 99.01%  |
| 2      | 30       | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2037     | 67.27%  |
| 1      | 991      | 32.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3018     | 99.87%  |
| Unknown        | 4        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2156     | 69.66%  |
| 0x08701021 | 97       | 3.13%   |
| 0x306c3    | 73       | 2.36%   |
| 0x08701013 | 72       | 2.33%   |
| 0x0800820d | 70       | 2.26%   |
| 0x306a9    | 61       | 1.97%   |
| 0x206a7    | 50       | 1.62%   |
| 0x506e3    | 39       | 1.26%   |
| 0x906ea    | 38       | 1.23%   |
| 0x906e9    | 29       | 0.94%   |
| 0x1067a    | 27       | 0.87%   |
| 0x08001138 | 27       | 0.87%   |
| 0x08108109 | 23       | 0.74%   |
| 0x06000852 | 23       | 0.74%   |
| 0x0a201016 | 19       | 0.61%   |
| 0x906ec    | 15       | 0.48%   |
| 0x906ed    | 14       | 0.45%   |
| 0x0a201009 | 13       | 0.42%   |
| 0x08301039 | 13       | 0.42%   |
| 0x06001119 | 11       | 0.36%   |
| 0x08001137 | 10       | 0.32%   |
| 0x010000c8 | 10       | 0.32%   |
| 0xa0655    | 9        | 0.29%   |
| 0x306f2    | 9        | 0.29%   |
| 0x106a5    | 9        | 0.29%   |
| 0x06003106 | 9        | 0.29%   |
| 0xa0653    | 8        | 0.26%   |
| 0x206c2    | 8        | 0.26%   |
| 0xa0671    | 7        | 0.23%   |
| 0x906eb    | 7        | 0.23%   |
| 0x6fd      | 6        | 0.19%   |
| 0x206d7    | 6        | 0.19%   |
| 0x20655    | 6        | 0.19%   |
| 0x0a50000c | 6        | 0.19%   |
| 0x90672    | 5        | 0.16%   |
| 0x6fb      | 5        | 0.16%   |
| 0x08101016 | 5        | 0.16%   |
| 0x010000dc | 5        | 0.16%   |
| 0x50654    | 4        | 0.13%   |
| 0x106e5    | 4        | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 465      | 15.34%  |
| Haswell          | 316      | 10.42%  |
| KabyLake         | 277      | 9.14%   |
| Zen+             | 249      | 8.21%   |
| IvyBridge        | 224      | 7.39%   |
| Zen 3            | 206      | 6.79%   |
| SandyBridge      | 203      | 6.7%    |
| Zen              | 157      | 5.18%   |
| Skylake          | 156      | 5.15%   |
| Piledriver       | 132      | 4.35%   |
| Penryn           | 105      | 3.46%   |
| K10              | 96       | 3.17%   |
| CometLake        | 78       | 2.57%   |
| Nehalem          | 66       | 2.18%   |
| Core             | 54       | 1.78%   |
| Westmere         | 53       | 1.75%   |
| Unknown          | 48       | 1.58%   |
| Steamroller      | 22       | 0.73%   |
| Silvermont       | 20       | 0.66%   |
| K8 Hammer        | 18       | 0.59%   |
| Excavator        | 15       | 0.49%   |
| K10 Llano        | 13       | 0.43%   |
| Bulldozer        | 11       | 0.36%   |
| NetBurst         | 8        | 0.26%   |
| Goldmont plus    | 7        | 0.23%   |
| Jaguar           | 6        | 0.2%    |
| Icelake          | 6        | 0.2%    |
| Broadwell        | 6        | 0.2%    |
| Alderlake Hybrid | 5        | 0.16%   |
| Bobcat           | 4        | 0.13%   |
| Goldmont         | 3        | 0.1%    |
| Bonnell          | 2        | 0.07%   |
| Puma             | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1582     | 48.74%  |
| AMD                              | 1087     | 33.49%  |
| Intel                            | 570      | 17.56%  |
| Matrox Electronics Systems       | 5        | 0.15%   |
| Silicon Integrated Systems [SiS] | 2        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 225      | 6.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 108      | 3.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 106      | 3.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 99       | 2.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 73       | 2.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 71       | 2.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 70       | 2.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 62       | 1.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 61       | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 61       | 1.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 59       | 1.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 50       | 1.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 48       | 1.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 45       | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 44       | 1.31%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 44       | 1.31%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 44       | 1.31%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 40       | 1.19%   |
| Intel HD Graphics 530                                                       | 40       | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 38       | 1.13%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 38       | 1.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 36       | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 33       | 0.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 30       | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30       | 0.89%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 30       | 0.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 29       | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 28       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 27       | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                  | 27       | 0.81%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 27       | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 27       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 26       | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 24       | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 24       | 0.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 24       | 0.72%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 24       | 0.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 23       | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 22       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1469     | 47.87%  |
| 1 x AMD              | 995      | 32.42%  |
| 1 x Intel            | 420      | 13.69%  |
| Intel + Nvidia       | 44       | 1.43%   |
| 2 x AMD              | 41       | 1.34%   |
| 2 x Nvidia           | 32       | 1.04%   |
| AMD + Nvidia         | 32       | 1.04%   |
| Intel + AMD          | 22       | 0.72%   |
| 1 x Matrox           | 4        | 0.13%   |
| 1 x SiS              | 2        | 0.07%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| Intel + 2 x Nvidia   | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1595     | 52.01%  |
| Proprietary | 1283     | 41.83%  |
| Unknown     | 189      | 6.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1568     | 50.68%  |
| 7.01-8.0   | 430      | 13.9%   |
| 1.01-2.0   | 280      | 9.05%   |
| 3.01-4.0   | 267      | 8.63%   |
| 5.01-6.0   | 230      | 7.43%   |
| 8.01-16.0  | 124      | 4.01%   |
| 0.51-1.0   | 83       | 2.68%   |
| 2.01-3.0   | 48       | 1.55%   |
| 0.01-0.5   | 42       | 1.36%   |
| 16.01-24.0 | 17       | 0.55%   |
| 4.01-5.0   | 3        | 0.1%    |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 560      | 16.64%  |
| Goldstar             | 399      | 11.86%  |
| Dell                 | 369      | 10.97%  |
| Acer                 | 296      | 8.8%    |
| Hewlett-Packard      | 209      | 6.21%   |
| AOC                  | 193      | 5.74%   |
| Ancor Communications | 173      | 5.14%   |
| BenQ                 | 156      | 4.64%   |
| ASUSTek Computer     | 108      | 3.21%   |
| Philips              | 98       | 2.91%   |
| ViewSonic            | 59       | 1.75%   |
| Lenovo               | 54       | 1.6%    |
| Iiyama               | 51       | 1.52%   |
| Sony                 | 46       | 1.37%   |
| MSI                  | 41       | 1.22%   |
| Sceptre Tech         | 35       | 1.04%   |
| Vizio                | 26       | 0.77%   |
| Toshiba              | 22       | 0.65%   |
| Gigabyte Technology  | 21       | 0.62%   |
| Unknown              | 20       | 0.59%   |
| Panasonic            | 16       | 0.48%   |
| Eizo                 | 14       | 0.42%   |
| NEC Computers        | 13       | 0.39%   |
| LG Electronics       | 13       | 0.39%   |
| Insignia             | 13       | 0.39%   |
| Fujitsu Siemens      | 13       | 0.39%   |
| MStar                | 12       | 0.36%   |
| Hitachi              | 11       | 0.33%   |
| Vestel Elektronik    | 10       | 0.3%    |
| HannStar             | 9        | 0.27%   |
| Videoseven           | 8        | 0.24%   |
| Pixio                | 8        | 0.24%   |
| ONN                  | 8        | 0.24%   |
| Mi                   | 8        | 0.24%   |
| Viotek               | 7        | 0.21%   |
| CVT                  | 7        | 0.21%   |
| ___                  | 6        | 0.18%   |
| Valve                | 6        | 0.18%   |
| Sharp                | 6        | 0.18%   |
| Seiki                | 6        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 41       | 1.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 27       | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 22       | 0.62%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 22       | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 16       | 0.45%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 15       | 0.42%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                  | 14       | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 13       | 0.36%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 13       | 0.36%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 12       | 0.34%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 12       | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 11       | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 11       | 0.31%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 11       | 0.31%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                        | 11       | 0.31%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 10       | 0.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 10       | 0.28%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 10       | 0.28%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch       | 10       | 0.28%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 10       | 0.28%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                     | 10       | 0.28%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                      | 9        | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 9        | 0.25%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch       | 9        | 0.25%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 9        | 0.25%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                | 8        | 0.22%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 8        | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 8        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 8        | 0.22%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 8        | 0.22%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                     | 8        | 0.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 8        | 0.22%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                       | 8        | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 8        | 0.22%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 8        | 0.22%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                    | 7        | 0.2%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 7        | 0.2%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch           | 7        | 0.2%    |
| AOC 2770G4 AOC2770 1920x1080 598x336mm 27.0-inch                       | 7        | 0.2%    |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                       | 7        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1482     | 46.4%   |
| 3840x2160 (4K)     | 393      | 12.3%   |
| 2560x1440 (QHD)    | 318      | 9.96%   |
| 1680x1050 (WSXGA+) | 134      | 4.2%    |
| 1280x1024 (SXGA)   | 124      | 3.88%   |
| 3440x1440          | 114      | 3.57%   |
| 1366x768 (WXGA)    | 109      | 3.41%   |
| 2560x1080          | 103      | 3.22%   |
| 1440x900 (WXGA+)   | 76       | 2.38%   |
| 1920x1200 (WUXGA)  | 72       | 2.25%   |
| 1600x900 (HD+)     | 69       | 2.16%   |
| 1360x768           | 40       | 1.25%   |
| 3840x1080          | 28       | 0.88%   |
| 1920x540           | 28       | 0.88%   |
| Unknown            | 24       | 0.75%   |
| 3840x1600          | 11       | 0.34%   |
| 1280x720 (HD)      | 10       | 0.31%   |
| 1024x768 (XGA)     | 10       | 0.31%   |
| 1600x1200          | 9        | 0.28%   |
| 2560x1600          | 6        | 0.19%   |
| 2048x1152          | 4        | 0.13%   |
| 5120x1440          | 2        | 0.06%   |
| 4480x1440          | 2        | 0.06%   |
| 3840x1200          | 2        | 0.06%   |
| 9840x3840          | 1        | 0.03%   |
| 8320x2160          | 1        | 0.03%   |
| 8160x4627          | 1        | 0.03%   |
| 7680x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |
| 5280x1080          | 1        | 0.03%   |
| 5200x2160          | 1        | 0.03%   |
| 4096x2160          | 1        | 0.03%   |
| 4080x2030          | 1        | 0.03%   |
| 4080x2026          | 1        | 0.03%   |
| 3360x1080          | 1        | 0.03%   |
| 3280x2048          | 1        | 0.03%   |
| 3280x1080          | 1        | 0.03%   |
| 3040x900           | 1        | 0.03%   |
| 2960x1050          | 1        | 0.03%   |
| 2880x1600          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 593      | 17.75%  |
| 24      | 512      | 15.33%  |
| 23      | 403      | 12.07%  |
| 21      | 328      | 9.82%   |
| 31      | 197      | 5.9%    |
| 34      | 180      | 5.39%   |
| 19      | 136      | 4.07%   |
| Unknown | 112      | 3.35%   |
| 18      | 100      | 2.99%   |
| 22      | 98       | 2.93%   |
| 20      | 78       | 2.34%   |
| 84      | 65       | 1.95%   |
| 17      | 64       | 1.92%   |
| 72      | 53       | 1.59%   |
| 32      | 53       | 1.59%   |
| 15      | 45       | 1.35%   |
| 54      | 30       | 0.9%    |
| 26      | 27       | 0.81%   |
| 25      | 25       | 0.75%   |
| 48      | 21       | 0.63%   |
| 35      | 19       | 0.57%   |
| 49      | 18       | 0.54%   |
| 65      | 16       | 0.48%   |
| 28      | 16       | 0.48%   |
| 52      | 15       | 0.45%   |
| 40      | 14       | 0.42%   |
| 37      | 12       | 0.36%   |
| 46      | 11       | 0.33%   |
| 29      | 11       | 0.33%   |
| 33      | 8        | 0.24%   |
| 47      | 7        | 0.21%   |
| 42      | 7        | 0.21%   |
| 43      | 6        | 0.18%   |
| 74      | 5        | 0.15%   |
| 55      | 5        | 0.15%   |
| 36      | 5        | 0.15%   |
| 41      | 4        | 0.12%   |
| 38      | 4        | 0.12%   |
| 11      | 4        | 0.12%   |
| 64      | 3        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1347     | 42.13%  |
| 401-500        | 654      | 20.46%  |
| 601-700        | 308      | 9.63%   |
| 701-800        | 241      | 7.54%   |
| 1001-1500      | 138      | 4.32%   |
| 1501-2000      | 126      | 3.94%   |
| Unknown        | 112      | 3.5%    |
| 301-350        | 99       | 3.1%    |
| 351-400        | 87       | 2.72%   |
| 801-900        | 56       | 1.75%   |
| 901-1000       | 18       | 0.56%   |
| 201-300        | 10       | 0.31%   |
| More than 2000 | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2140     | 72.2%   |
| 16/10   | 331      | 11.17%  |
| 21/9    | 221      | 7.46%   |
| 5/4     | 120      | 4.05%   |
| Unknown | 67       | 2.26%   |
| 32/9    | 31       | 1.05%   |
| 4/3     | 29       | 0.98%   |
| 3/2     | 10       | 0.34%   |
| 6/5     | 7        | 0.24%   |
| 1.96    | 5        | 0.17%   |
| 3.20    | 2        | 0.07%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1050     | 32.27%  |
| 301-350        | 607      | 18.65%  |
| 351-500        | 461      | 14.17%  |
| 151-200        | 318      | 9.77%   |
| More than 1000 | 214      | 6.58%   |
| 251-300        | 191      | 5.87%   |
| 141-150        | 132      | 4.06%   |
| Unknown        | 112      | 3.44%   |
| 501-1000       | 106      | 3.26%   |
| 101-110        | 35       | 1.08%   |
| 131-140        | 7        | 0.22%   |
| 91-100         | 6        | 0.18%   |
| 71-80          | 4        | 0.12%   |
| 51-60          | 4        | 0.12%   |
| 111-120        | 4        | 0.12%   |
| 121-130        | 3        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1864     | 61.24%  |
| 101-120       | 669      | 21.98%  |
| 1-50          | 170      | 5.58%   |
| 121-160       | 161      | 5.29%   |
| Unknown       | 112      | 3.68%   |
| 161-240       | 67       | 2.2%    |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2146     | 69.32%  |
| 2     | 641      | 20.7%   |
| 0     | 218      | 7.04%   |
| 3     | 80       | 2.58%   |
| 4     | 9        | 0.29%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1791     | 40.15%  |
| Intel                           | 1458     | 32.68%  |
| Qualcomm Atheros                | 265      | 5.94%   |
| Broadcom                        | 159      | 3.56%   |
| Ralink Technology               | 92       | 2.06%   |
| TP-Link                         | 86       | 1.93%   |
| Microsoft                       | 62       | 1.39%   |
| Nvidia                          | 48       | 1.08%   |
| Ralink                          | 42       | 0.94%   |
| Samsung Electronics             | 39       | 0.87%   |
| Qualcomm Atheros Communications | 33       | 0.74%   |
| NetGear                         | 32       | 0.72%   |
| InterBiometrics                 | 31       | 0.69%   |
| Aquantia                        | 28       | 0.63%   |
| Xiaomi                          | 20       | 0.45%   |
| MediaTek                        | 20       | 0.45%   |
| Marvell Technology Group        | 20       | 0.45%   |
| D-Link                          | 17       | 0.38%   |
| Huawei Technologies             | 16       | 0.36%   |
| Google                          | 16       | 0.36%   |
| Linksys                         | 14       | 0.31%   |
| Broadcom Limited                | 13       | 0.29%   |
| ASUSTek Computer                | 13       | 0.29%   |
| ASIX Electronics                | 10       | 0.22%   |
| Edimax Technology               | 8        | 0.18%   |
| Belkin Components               | 8        | 0.18%   |
| OnePlus Technology (Shenzhen)   | 7        | 0.16%   |
| Motorola PCS                    | 7        | 0.16%   |
| D-Link System                   | 7        | 0.16%   |
| OPPO Electronics                | 6        | 0.13%   |
| DisplayLink                     | 6        | 0.13%   |
| AVM                             | 6        | 0.13%   |
| Sitecom Europe                  | 5        | 0.11%   |
| Gemtek                          | 5        | 0.11%   |
| VIA Technologies                | 4        | 0.09%   |
| Mercucys                        | 4        | 0.09%   |
| Mellanox Technologies           | 4        | 0.09%   |
| Qualcomm                        | 3        | 0.07%   |
| Microchip Technology            | 3        | 0.07%   |
| IMC Networks                    | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1407     | 27.18%  |
| Intel I211 Gigabit Network Connection                             | 363      | 7.01%   |
| Intel Wi-Fi 6 AX200                                               | 301      | 5.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 180      | 3.48%   |
| Intel Ethernet Connection (2) I219-V                              | 138      | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 117      | 2.26%   |
| Intel Ethernet Controller I225-V                                  | 95       | 1.84%   |
| Intel Wireless-AC 9260                                            | 94       | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 86       | 1.66%   |
| Intel Ethernet Connection (7) I219-V                              | 83       | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 67       | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 55       | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 0.95%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 49       | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 47       | 0.91%   |
| Realtek 802.11ac NIC                                              | 44       | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 39       | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 38       | 0.73%   |
| Nvidia MCP61 Ethernet                                             | 35       | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 34       | 0.66%   |
| InterBiometrics Io                                                | 30       | 0.58%   |
| Microsoft XBOX ACC                                                | 29       | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28       | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 27       | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27       | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 26       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.48%   |
| Intel Wireless 7265                                               | 25       | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24       | 0.46%   |
| Microsoft Xbox 360 Wireless Adapter                               | 24       | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.44%   |
| Intel Wireless 8265 / 8275                                        | 23       | 0.44%   |
| Intel Wireless 8260                                               | 22       | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 22       | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 21       | 0.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 20       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 697      | 40.29%  |
| Realtek Semiconductor                 | 350      | 20.23%  |
| Qualcomm Atheros                      | 133      | 7.69%   |
| Ralink Technology                     | 92       | 5.32%   |
| Broadcom                              | 92       | 5.32%   |
| TP-Link                               | 82       | 4.74%   |
| Microsoft                             | 62       | 3.58%   |
| Ralink                                | 42       | 2.43%   |
| Qualcomm Atheros Communications       | 33       | 1.91%   |
| NetGear                               | 32       | 1.85%   |
| MediaTek                              | 16       | 0.92%   |
| D-Link                                | 16       | 0.92%   |
| Linksys                               | 13       | 0.75%   |
| ASUSTek Computer                      | 13       | 0.75%   |
| Edimax Technology                     | 8        | 0.46%   |
| Belkin Components                     | 8        | 0.46%   |
| AVM                                   | 6        | 0.35%   |
| Sitecom Europe                        | 5        | 0.29%   |
| Gemtek                                | 5        | 0.29%   |
| Mercucys                              | 4        | 0.23%   |
| Broadcom Limited                      | 4        | 0.23%   |
| IMC Networks                          | 3        | 0.17%   |
| D-Link System                         | 3        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.12%   |
| ZyDAS                                 | 1        | 0.06%   |
| Wilocity                              | 1        | 0.06%   |
| TRENDnet                              | 1        | 0.06%   |
| Texas Instruments                     | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| Ovislink                              | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| BUFFALO                               | 1        | 0.06%   |
| Accton Technology                     | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 301      | 17.22%  |
| Intel Wireless-AC 9260                                         | 94       | 5.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 86       | 4.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 55       | 3.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 49       | 2.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 47       | 2.69%   |
| Realtek 802.11ac NIC                                           | 44       | 2.52%   |
| Ralink MT7601U Wireless Adapter                                | 39       | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 38       | 2.17%   |
| Microsoft XBOX ACC                                             | 29       | 1.66%   |
| Qualcomm Atheros AR9271 802.11n                                | 27       | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 27       | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 26       | 1.49%   |
| Intel Wireless 7265                                            | 25       | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24       | 1.37%   |
| Microsoft Xbox 360 Wireless Adapter                            | 24       | 1.37%   |
| Intel Wireless 8265 / 8275                                     | 23       | 1.32%   |
| Intel Wireless 8260                                            | 22       | 1.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 20       | 1.14%   |
| Intel Wireless 7260                                            | 20       | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19       | 1.09%   |
| TP-Link 802.11ac WLAN Adapter                                  | 18       | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 18       | 1.03%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 15       | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15       | 0.86%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15       | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 15       | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 14       | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 13       | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 13       | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13       | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 13       | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 12       | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12       | 0.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 11       | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11       | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1648     | 50.15%  |
| Intel                            | 1155     | 35.15%  |
| Qualcomm Atheros                 | 141      | 4.29%   |
| Broadcom                         | 72       | 2.19%   |
| Nvidia                           | 48       | 1.46%   |
| Samsung Electronics              | 38       | 1.16%   |
| Aquantia                         | 28       | 0.85%   |
| Xiaomi                           | 20       | 0.61%   |
| Marvell Technology Group         | 20       | 0.61%   |
| Huawei Technologies              | 16       | 0.49%   |
| Google                           | 16       | 0.49%   |
| ASIX Electronics                 | 10       | 0.3%    |
| Broadcom Limited                 | 9        | 0.27%   |
| OPPO Electronics                 | 6        | 0.18%   |
| DisplayLink                      | 6        | 0.18%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.15%   |
| Motorola PCS                     | 5        | 0.15%   |
| VIA Technologies                 | 4        | 0.12%   |
| TP-Link                          | 4        | 0.12%   |
| MediaTek                         | 4        | 0.12%   |
| D-Link System                    | 4        | 0.12%   |
| Qualcomm                         | 3        | 0.09%   |
| Mellanox Technologies            | 3        | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| ICS Advent                       | 2        | 0.06%   |
| 3Com                             | 2        | 0.06%   |
| Tehuti Networks                  | 1        | 0.03%   |
| Solarflare Communications        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| QLogic                           | 1        | 0.03%   |
| Netchip Technology               | 1        | 0.03%   |
| Linksys                          | 1        | 0.03%   |
| LG Electronics                   | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| JMicron Technology               | 1        | 0.03%   |
| HMD Global                       | 1        | 0.03%   |
| Hangzhou Silan Microelectronics  | 1        | 0.03%   |
| Emulex                           | 1        | 0.03%   |
| D-Link                           | 1        | 0.03%   |
| Corega K.K.                      | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1407     | 41.78%  |
| Intel I211 Gigabit Network Connection                             | 363      | 10.78%  |
| Realtek RTL8125 2.5GbE Controller                                 | 180      | 5.34%   |
| Intel Ethernet Connection (2) I219-V                              | 138      | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 117      | 3.47%   |
| Intel Ethernet Controller I225-V                                  | 95       | 2.82%   |
| Intel Ethernet Connection (7) I219-V                              | 83       | 2.46%   |
| Intel Ethernet Connection I217-LM                                 | 67       | 1.99%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 1.45%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 1.19%   |
| Nvidia MCP61 Ethernet                                             | 35       | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 34       | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28       | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 22       | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 21       | 0.62%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 20       | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19       | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 18       | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17       | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16       | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 15       | 0.45%   |
| Huawei SNE-LX1                                                    | 14       | 0.42%   |
| Google Nexus/Pixel Device (tether)                                | 14       | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13       | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 13       | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.39%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11       | 0.33%   |
| Intel 82583V Gigabit Network Connection                           | 9        | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 8        | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 8        | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8        | 0.24%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2984     | 64.21%  |
| WiFi     | 1603     | 34.5%   |
| Modem    | 49       | 1.05%   |
| Unknown  | 11       | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2278     | 71.46%  |
| WiFi     | 908      | 28.48%  |
| Unknown  | 2        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1803     | 59.25%  |
| 2     | 1032     | 33.91%  |
| 3     | 148      | 4.86%   |
| 0     | 31       | 1.02%   |
| 4     | 21       | 0.69%   |
| 5     | 4        | 0.13%   |
| 10    | 2        | 0.07%   |
| 6     | 2        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2447     | 79.65%  |
| Yes  | 625      | 20.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 646      | 53.39%  |
| Cambridge Silicon Radio         | 260      | 21.49%  |
| ASUSTek Computer                | 75       | 6.2%    |
| Broadcom                        | 59       | 4.88%   |
| Realtek Semiconductor           | 55       | 4.55%   |
| Qualcomm Atheros Communications | 37       | 3.06%   |
| Apple                           | 20       | 1.65%   |
| IMC Networks                    | 8        | 0.66%   |
| Foxconn / Hon Hai               | 8        | 0.66%   |
| TP-Link                         | 6        | 0.5%    |
| MediaTek                        | 6        | 0.5%    |
| HTC (High Tech Computer)        | 4        | 0.33%   |
| Dynex                           | 3        | 0.25%   |
| Realtek                         | 2        | 0.17%   |
| Ralink                          | 2        | 0.17%   |
| Lite-On Technology              | 2        | 0.17%   |
| Integrated System Solution      | 2        | 0.17%   |
| Hewlett-Packard                 | 2        | 0.17%   |
| Dell                            | 2        | 0.17%   |
| Creative Technology             | 2        | 0.17%   |
| Conwise Technology              | 2        | 0.17%   |
| Belkin Components               | 2        | 0.17%   |
| SINO WEALTH                     | 1        | 0.08%   |
| Primax Electronics              | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| Logitech                        | 1        | 0.08%   |
| Edimax Technology               | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 280      | 23.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 260      | 21.43%  |
| Intel Bluetooth wireless interface                                   | 90       | 7.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 88       | 7.25%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 85       | 7.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 44       | 3.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 40       | 3.3%    |
| Realtek Bluetooth Radio                                              | 37       | 3.05%   |
| Intel AX201 Bluetooth                                                | 34       | 2.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 24       | 1.98%   |
| Intel AX210 Bluetooth                                                | 23       | 1.9%    |
| ASUS Bluetooth Radio                                                 | 20       | 1.65%   |
| Qualcomm Atheros  Bluetooth Device                                   | 18       | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 13       | 1.07%   |
| Apple Bluetooth USB Host Controller                                  | 11       | 0.91%   |
| ASUS ASUS USB-BT500                                                  | 8        | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.58%   |
| TP-Link UB500 Adapter                                                | 6        | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.49%   |
| MediaTek Wireless_Device                                             | 6        | 0.49%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.49%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.49%   |
| ASUS BCM20702A0                                                      | 6        | 0.49%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 5        | 0.41%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.41%   |
| Realtek RTL8821A Bluetooth                                           | 4        | 0.33%   |
| Intel Bluetooth Device                                               | 4        | 0.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 4        | 0.33%   |
| Apple Bluetooth HCI                                                  | 4        | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 3        | 0.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.25%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 3        | 0.25%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.25%   |
| ASUS Bluetooth Device                                                | 3        | 0.25%   |
| ASUS Bluetooth Adapter                                               | 3        | 0.25%   |
| Realtek Bluetooth Radio                                              | 2        | 0.16%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 0.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                     | 2        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1663     | 28.82%  |
| Intel                                           | 1544     | 26.76%  |
| Nvidia                                          | 1526     | 26.45%  |
| C-Media Electronics                             | 161      | 2.79%   |
| Logitech                                        | 82       | 1.42%   |
| Creative Labs                                   | 60       | 1.04%   |
| Razer USA                                       | 45       | 0.78%   |
| Kingston Technology                             | 44       | 0.76%   |
| JMTek                                           | 44       | 0.76%   |
| Corsair                                         | 43       | 0.75%   |
| Texas Instruments                               | 36       | 0.62%   |
| SteelSeries ApS                                 | 33       | 0.57%   |
| Focusrite-Novation                              | 32       | 0.55%   |
| ASUSTek Computer                                | 27       | 0.47%   |
| Blue Microphones                                | 26       | 0.45%   |
| Creative Technology                             | 25       | 0.43%   |
| Generalplus Technology                          | 20       | 0.35%   |
| Giga-Byte Technology                            | 14       | 0.24%   |
| Astro Gaming                                    | 14       | 0.24%   |
| Sony                                            | 13       | 0.23%   |
| GN Netcom                                       | 13       | 0.23%   |
| Turtle Beach                                    | 11       | 0.19%   |
| Samson Technologies                             | 11       | 0.19%   |
| Plantronics                                     | 11       | 0.19%   |
| SAVITECH                                        | 10       | 0.17%   |
| M-Audio                                         | 10       | 0.17%   |
| Yamaha                                          | 9        | 0.16%   |
| Valve Software                                  | 9        | 0.16%   |
| Tenx Technology                                 | 9        | 0.16%   |
| Sennheiser Communications                       | 9        | 0.16%   |
| Realtek Semiconductor                           | 9        | 0.16%   |
| Thesycon Systemsoftware & Consulting            | 8        | 0.14%   |
| Micro Star International                        | 8        | 0.14%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.14%   |
| FiiO Electronics Technology                     | 7        | 0.12%   |
| Audio-Technica                                  | 7        | 0.12%   |
| Unknown                                         | 6        | 0.1%    |
| BEHRINGER International                         | 6        | 0.1%    |
| VIA Technologies                                | 5        | 0.09%   |
| Trust                                           | 4        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 604      | 8.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 274      | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 225      | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 212      | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 199      | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 171      | 2.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 167      | 2.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 161      | 2.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 156      | 2.32%   |
| Intel 200 Series PCH HD Audio                                              | 149      | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 148      | 2.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 130      | 1.93%   |
| AMD Navi 10 HDMI Audio                                                     | 129      | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 119      | 1.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 118      | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 114      | 1.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 110      | 1.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 108      | 1.61%   |
| Nvidia TU104 HD Audio Controller                                           | 100      | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 94       | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 90       | 1.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 87       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 79       | 1.18%   |
| AMD FCH Azalia Controller                                                  | 79       | 1.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 77       | 1.15%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 73       | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 73       | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 64       | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 61       | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 59       | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 54       | 0.8%    |
| Nvidia GA102 High Definition Audio Controller                              | 53       | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 51       | 0.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 51       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 47       | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 46       | 0.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 46       | 0.68%   |
| Nvidia MCP61 High Definition Audio                                         | 41       | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 38       | 0.57%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 38       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 126      | 22.34%  |
| Kingston                     | 100      | 17.73%  |
| G.Skill                      | 83       | 14.72%  |
| Crucial                      | 57       | 10.11%  |
| Unknown                      | 51       | 9.04%   |
| Samsung Electronics          | 32       | 5.67%   |
| SK hynix                     | 26       | 4.61%   |
| Team                         | 20       | 3.55%   |
| Micron Technology            | 17       | 3.01%   |
| A-DATA Technology            | 14       | 2.48%   |
| Patriot                      | 8        | 1.42%   |
| Ramaxel Technology           | 3        | 0.53%   |
| Patriot Memory               | 2        | 0.35%   |
| OLOY                         | 2        | 0.35%   |
| Avant                        | 2        | 0.35%   |
| Unknown                      | 2        | 0.35%   |
| Unifosa                      | 1        | 0.18%   |
| Transcend                    | 1        | 0.18%   |
| Toshiba                      | 1        | 0.18%   |
| Teikon                       | 1        | 0.18%   |
| Smart                        | 1        | 0.18%   |
| Silicon Power                | 1        | 0.18%   |
| Patriot Memory (PDP Systems) | 1        | 0.18%   |
| Neo Forza                    | 1        | 0.18%   |
| Nanya Technology             | 1        | 0.18%   |
| HMD                          | 1        | 0.18%   |
| Goodram                      | 1        | 0.18%   |
| Goldkey                      | 1        | 0.18%   |
| GLOWAY                       | 1        | 0.18%   |
| EVGA                         | 1        | 0.18%   |
| Elpida                       | 1        | 0.18%   |
| CSX                          | 1        | 0.18%   |
| ASint Technology             | 1        | 0.18%   |
| Apacer                       | 1        | 0.18%   |
| AMD                          | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 19       | 3.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 11       | 1.84%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 9        | 1.5%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 8        | 1.34%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s   | 8        | 1.34%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 6        | 1%      |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 6        | 1%      |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 5        | 0.83%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 5        | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 5        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 32GB DIMM DDR4 3000MT/s      | 4        | 0.67%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 4        | 0.67%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 4        | 0.67%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8192MB DIMM DDR4 3733MT/s | 4        | 0.67%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 4        | 0.67%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 4        | 0.67%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s   | 4        | 0.67%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 4        | 0.67%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s    | 4        | 0.67%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s              | 4        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 3        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s       | 3        | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 3        | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 0.5%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 0.5%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 3        | 0.5%    |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s  | 3        | 0.5%    |
| G.Skill RAM F4-3600C18-8GVK 8192MB DIMM DDR4 3600MT/s    | 3        | 0.5%    |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s     | 3        | 0.5%    |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s     | 3        | 0.5%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 3        | 0.5%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 3        | 0.5%    |
| Crucial RAM BLS8G4D26BFSEK.8FD 8GB DIMM DDR4 3000MT/s    | 3        | 0.5%    |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 3        | 0.5%    |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s              | 3        | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 2        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 2        | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 370      | 71.57%  |
| DDR3    | 111      | 21.47%  |
| Unknown | 15       | 2.9%    |
| DDR2    | 10       | 1.93%   |
| SDRAM   | 7        | 1.35%   |
| DDR     | 2        | 0.39%   |
| LPDDR4  | 1        | 0.19%   |
| DDR5    | 1        | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 496      | 96.69%  |
| SODIMM       | 15       | 2.92%   |
| Row Of Chips | 1        | 0.19%   |
| RIMM         | 1        | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 262      | 47.64%  |
| 16384 | 121      | 22%     |
| 4096  | 95       | 17.27%  |
| 32768 | 36       | 6.55%   |
| 2048  | 25       | 4.55%   |
| 1024  | 9        | 1.64%   |
| 512   | 2        | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 101      | 18.1%   |
| 3200    | 76       | 13.62%  |
| 1600    | 58       | 10.39%  |
| 1333    | 44       | 7.89%   |
| 2400    | 41       | 7.35%   |
| 3000    | 25       | 4.48%   |
| 2133    | 22       | 3.94%   |
| 2667    | 20       | 3.58%   |
| 3400    | 17       | 3.05%   |
| 3866    | 14       | 2.51%   |
| 3466    | 13       | 2.33%   |
| 1867    | 13       | 2.33%   |
| 3800    | 11       | 1.97%   |
| 2933    | 9        | 1.61%   |
| 2666    | 9        | 1.61%   |
| 3733    | 8        | 1.43%   |
| 2800    | 8        | 1.43%   |
| 800     | 8        | 1.43%   |
| 1866    | 6        | 1.08%   |
| 667     | 6        | 1.08%   |
| Unknown | 5        | 0.9%    |
| 1800    | 4        | 0.72%   |
| 4400    | 3        | 0.54%   |
| 4000    | 3        | 0.54%   |
| 3666    | 3        | 0.54%   |
| 3333    | 3        | 0.54%   |
| 3533    | 2        | 0.36%   |
| 3334    | 2        | 0.36%   |
| 3151    | 2        | 0.36%   |
| 3100    | 2        | 0.36%   |
| 2733    | 2        | 0.36%   |
| 2472    | 2        | 0.36%   |
| 2134    | 2        | 0.36%   |
| 1066    | 2        | 0.36%   |
| 49926   | 1        | 0.18%   |
| 8400    | 1        | 0.18%   |
| 4800    | 1        | 0.18%   |
| 4266    | 1        | 0.18%   |
| 4133    | 1        | 0.18%   |
| 3066    | 1        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 39       | 29.32%  |
| Brother Industries    | 28       | 21.05%  |
| Canon                 | 21       | 15.79%  |
| Samsung Electronics   | 16       | 12.03%  |
| Seiko Epson           | 13       | 9.77%   |
| Dymo-CoStar           | 4        | 3.01%   |
| Fuji Xerox            | 3        | 2.26%   |
| QinHeng Electronics   | 2        | 1.5%    |
| Xerox                 | 1        | 0.75%   |
| STMicroelectronics    | 1        | 0.75%   |
| Prolific Technology   | 1        | 0.75%   |
| Oki Data              | 1        | 0.75%   |
| Lexmark International | 1        | 0.75%   |
| Kyocera               | 1        | 0.75%   |
| Apple                 | 1        | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.99%   |
| Samsung SCX-3400 Series                                    | 3        | 2.24%   |
| Brother Printer                                            | 3        | 2.24%   |
| Brother HL-2130 series                                     | 3        | 2.24%   |
| Seiko Epson L4150 Series                                   | 2        | 1.49%   |
| Seiko Epson L355 Series                                    | 2        | 1.49%   |
| Seiko Epson ET-2600 Series                                 | 2        | 1.49%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.49%   |
| Samsung M2070 Series                                       | 2        | 1.49%   |
| Samsung M2020 Series                                       | 2        | 1.49%   |
| QinHeng CH340S                                             | 2        | 1.49%   |
| HP LaserJet Professional P 1102w                           | 2        | 1.49%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.49%   |
| HP ENVY 4500 series                                        | 2        | 1.49%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.49%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.49%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.49%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.49%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.49%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.49%   |
| Brother HL-L3230CDW series                                 | 2        | 1.49%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.49%   |
| Brother HL-1110 series                                     | 2        | 1.49%   |
| Xerox Phaser 6000B                                         | 1        | 0.75%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.75%   |
| Seiko Epson WF-4830 Series                                 | 1        | 0.75%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.75%   |
| Seiko Epson L365 Series                                    | 1        | 0.75%   |
| Seiko Epson L3110 Series                                   | 1        | 0.75%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.75%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.75%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.75%   |
| Samsung SCX-4200 series                                    | 1        | 0.75%   |
| Samsung ML-2540 Series Laser Printer                       | 1        | 0.75%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1        | 0.75%   |
| Samsung ML-1670 Series                                     | 1        | 0.75%   |
| Samsung ML-1660 Series                                     | 1        | 0.75%   |
| Samsung Composite Device                                   | 1        | 0.75%   |
| Samsung C43x Series                                        | 1        | 0.75%   |
| Prolific PL2305 Parallel Port                              | 1        | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 66.67%  |
| Seiko Epson     | 2        | 13.33%  |
| Hewlett-Packard | 2        | 13.33%  |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30          | 2        | 13.33%  |
| Canon CanoScan LiDE 210                | 2        | 13.33%  |
| Seiko Epson Scanner                    | 1        | 6.67%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1        | 6.67%   |
| Mustek Systems ScanExpress 1200 UB     | 1        | 6.67%   |
| HP Scanjet 300                         | 1        | 6.67%   |
| HP ScanJet 2400c                       | 1        | 6.67%   |
| Canon CanoScan N650U/N656U             | 1        | 6.67%   |
| Canon CanoScan LiDE 60                 | 1        | 6.67%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 6.67%   |
| Canon CanoScan LiDE 220                | 1        | 6.67%   |
| Canon CanoScan LiDE 200                | 1        | 6.67%   |
| Canon CanoScan LiDE 110                | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 257      | 45.41%  |
| Microdia                      | 42       | 7.42%   |
| Microsoft                     | 30       | 5.3%    |
| Sunplus Innovation Technology | 17       | 3%      |
| Generalplus Technology        | 17       | 3%      |
| Apple                         | 14       | 2.47%   |
| ARC International             | 13       | 2.3%    |
| Samsung Electronics           | 12       | 2.12%   |
| Z-Star Microelectronics       | 10       | 1.77%   |
| Realtek Semiconductor         | 10       | 1.77%   |
| Razer USA                     | 10       | 1.77%   |
| MacroSilicon                  | 10       | 1.77%   |
| Chicony Electronics           | 10       | 1.77%   |
| Valve Software                | 9        | 1.59%   |
| KYE Systems (Mouse Systems)   | 8        | 1.41%   |
| Jieli Technology              | 8        | 1.41%   |
| Cubeternet                    | 6        | 1.06%   |
| Creative Technology           | 6        | 1.06%   |
| AVerMedia Technologies        | 5        | 0.88%   |
| LG Electronics                | 4        | 0.71%   |
| Huawei Technologies           | 4        | 0.71%   |
| Hewlett-Packard               | 4        | 0.71%   |
| Aveo Technology               | 4        | 0.71%   |
| A4Tech                        | 3        | 0.53%   |
| 2M UVC CAMERA                 | 3        | 0.53%   |
| WCM_USB                       | 2        | 0.35%   |
| Unknown                       | 2        | 0.35%   |
| Trust                         | 2        | 0.35%   |
| Sunplus IT                    | 2        | 0.35%   |
| Novatek Microelectronics      | 2        | 0.35%   |
| Intel                         | 2        | 0.35%   |
| HTC (High Tech Computer)      | 2        | 0.35%   |
| GenesysLogic Technology       | 2        | 0.35%   |
| Genesys Logic                 | 2        | 0.35%   |
| GEMBIRD                       | 2        | 0.35%   |
| Alcor Micro                   | 2        | 0.35%   |
| Acer                          | 2        | 0.35%   |
| YSD-2053--200409              | 1        | 0.18%   |
| YGTek                         | 1        | 0.18%   |
| Yealink Network Technology    | 1        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 60       | 10.58%  |
| Logitech Webcam C270                    | 51       | 8.99%   |
| Logitech C922 Pro Stream Webcam         | 21       | 3.7%    |
| Microdia Webcam Vitade AF               | 16       | 2.82%   |
| Logitech BRIO                           | 14       | 2.47%   |
| Generalplus GENERAL WEBCAM              | 13       | 2.29%   |
| ARC International Camera                | 13       | 2.29%   |
| Apple iPhone 5/5C/5S/6/SE               | 13       | 2.29%   |
| Samsung Galaxy series, misc. (MTP mode) | 12       | 2.12%   |
| Microsoft LifeCam HD-3000               | 12       | 2.12%   |
| Logitech HD Webcam C525                 | 12       | 2.12%   |
| Logitech HD Webcam C615                 | 11       | 1.94%   |
| Valve Software 3D Camera                | 9        | 1.59%   |
| Razer USA Gaming Webcam [Kiyo]          | 9        | 1.59%   |
| MacroSilicon USB Video                  | 8        | 1.41%   |
| Logitech Webcam Pro 9000                | 8        | 1.41%   |
| Logitech Webcam C310                    | 8        | 1.41%   |
| Jieli USB PHY 2.0                       | 8        | 1.41%   |
| Logitech Webcam C930e                   | 7        | 1.23%   |
| Logitech Webcam C925e                   | 7        | 1.23%   |
| Logitech Webcam C170                    | 7        | 1.23%   |
| Microsoft LifeCam Cinema                | 6        | 1.06%   |
| Microdia USB 2.0 Camera                 | 6        | 1.06%   |
| Microdia Integrated Camera              | 6        | 1.06%   |
| Logitech StreamCam                      | 6        | 1.06%   |
| Microdia Hy-HD-Camera                   | 5        | 0.88%   |
| Logitech C920 PRO HD Webcam             | 5        | 0.88%   |
| Chicony HP High Definition 1MP Webcam   | 5        | 0.88%   |
| AVerMedia Live Streamer CAM 313         | 5        | 0.88%   |
| Sunplus USB 2.0 Camera                  | 4        | 0.71%   |
| Realtek HD webcam                       | 4        | 0.71%   |
| Microdia Sonix USB 2.0 Camera           | 4        | 0.71%   |
| Logitech HD Webcam C910                 | 4        | 0.71%   |
| Logitech HD Webcam C510                 | 4        | 0.71%   |
| Huawei HiCamera                         | 4        | 0.71%   |
| Z-Star Venus USB2.0 Camera              | 3        | 0.53%   |
| Sunplus SPCA2281 Web Camera             | 3        | 0.53%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 3        | 0.53%   |
| Microsoft LifeCam VX-2000               | 3        | 0.53%   |
| Logitech QuickCam Pro 9000              | 3        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 33.33%  |
| Validity Sensors      | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |
| AuthenTec             | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 33.33%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader                           | 1        | 16.67%  |
| AuthenTec Fingerprint Sensor                                | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 40%     |
| OmniKey               | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Alcor Micro           | 2        | 13.33%  |
| Chicony Electronics   | 1        | 6.67%   |
| Advanced Card Systems | 1        | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 26.67%  |
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 13.33%  |
| OmniKey CardMan 3021 / 3121                            | 2        | 13.33%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 6.67%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 6.67%   |
| OmniKey CardMan 1021                                   | 1        | 6.67%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 6.67%   |
| Alcor Micro Watchdata W 1981                           | 1        | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 6.67%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2480     | 80.28%  |
| 1     | 544      | 17.61%  |
| 2     | 55       | 1.78%   |
| 3     | 7        | 0.23%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 246      | 37.05%  |
| Graphics card            | 233      | 35.09%  |
| Unassigned class         | 40       | 6.02%   |
| Sound                    | 22       | 3.31%   |
| Multimedia controller    | 18       | 2.71%   |
| Communication controller | 18       | 2.71%   |
| Bluetooth                | 17       | 2.56%   |
| Net/ethernet             | 13       | 1.96%   |
| Chipcard                 | 12       | 1.81%   |
| Storage/raid             | 11       | 1.66%   |
| Network                  | 11       | 1.66%   |
| Fingerprint reader       | 6        | 0.9%    |
| Camera                   | 5        | 0.75%   |
| Storage/ide              | 4        | 0.6%    |
| Card reader              | 4        | 0.6%    |
| Firewire controller      | 2        | 0.3%    |
| Storage/nvme             | 1        | 0.15%   |
| Dvb card                 | 1        | 0.15%   |

