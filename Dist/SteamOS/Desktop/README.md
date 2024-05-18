SteamOS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 176

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450M GAMING                | [dc7364667b](https://linux-hardware.org/?probe=dc7364667b) | May 05, 2024 |
| ASRock        | B760M PG Lightning/D4       | [50c91b7d78](https://linux-hardware.org/?probe=50c91b7d78) | May 03, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [4ffacbaeac](https://linux-hardware.org/?probe=4ffacbaeac) | Apr 25, 2024 |
| ASUSTek       | PRIME A320M-K               | [97e9e0c7a1](https://linux-hardware.org/?probe=97e9e0c7a1) | Apr 13, 2024 |
| Gigabyte      | B450M GAMING                | [d0241d517a](https://linux-hardware.org/?probe=d0241d517a) | Apr 08, 2024 |
| ASRock        | B450M Pro4-F                | [c70e4f20eb](https://linux-hardware.org/?probe=c70e4f20eb) | Apr 05, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3fe2ef5687](https://linux-hardware.org/?probe=3fe2ef5687) | Apr 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [24108983ab](https://linux-hardware.org/?probe=24108983ab) | Apr 01, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [1cda914d9f](https://linux-hardware.org/?probe=1cda914d9f) | Mar 27, 2024 |
| Gigabyte      | A620M GAMING X AX           | [95dabe0b93](https://linux-hardware.org/?probe=95dabe0b93) | Mar 17, 2024 |
| Gigabyte      | A620M GAMING X AX           | [ac8a1cf30d](https://linux-hardware.org/?probe=ac8a1cf30d) | Mar 16, 2024 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [853a2babec](https://linux-hardware.org/?probe=853a2babec) | Mar 16, 2024 |
| QIYIDA        | ED4 V1.1                    | [cbfcb37d83](https://linux-hardware.org/?probe=cbfcb37d83) | Mar 06, 2024 |
| ASRock        | B550M Steel Legend          | [ff01bc4e69](https://linux-hardware.org/?probe=ff01bc4e69) | Mar 03, 2024 |
| ASUSTek       | Z170-A                      | [5c7cfb2969](https://linux-hardware.org/?probe=5c7cfb2969) | Mar 02, 2024 |
| Dell          | 042P49 A02                  | [721c874400](https://linux-hardware.org/?probe=721c874400) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | [e9d405fea6](https://linux-hardware.org/?probe=e9d405fea6) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | [c95130db9f](https://linux-hardware.org/?probe=c95130db9f) | Mar 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [b8d705b208](https://linux-hardware.org/?probe=b8d705b208) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [04b45ee685](https://linux-hardware.org/?probe=04b45ee685) | Feb 21, 2024 |
| Gigabyte      | A520I AC                    | [e0d169ccee](https://linux-hardware.org/?probe=e0d169ccee) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2c5e1e36f8](https://linux-hardware.org/?probe=2c5e1e36f8) | Feb 12, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [63ed84550f](https://linux-hardware.org/?probe=63ed84550f) | Feb 08, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [1e4f204b76](https://linux-hardware.org/?probe=1e4f204b76) | Feb 08, 2024 |
| QIYIDA        | ED4 V1.1                    | [3583de3c82](https://linux-hardware.org/?probe=3583de3c82) | Jan 30, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [b4510875e8](https://linux-hardware.org/?probe=b4510875e8) | Jan 28, 2024 |
| ASUSTek       | SABERTOOTH Z170 S           | [953ea23870](https://linux-hardware.org/?probe=953ea23870) | Jan 19, 2024 |
| MSI           | H310M PRO-VD                | [3cdbce90e0](https://linux-hardware.org/?probe=3cdbce90e0) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [ffe6ae701f](https://linux-hardware.org/?probe=ffe6ae701f) | Jan 15, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [79504ec34b](https://linux-hardware.org/?probe=79504ec34b) | Jan 09, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [9c61eb5bab](https://linux-hardware.org/?probe=9c61eb5bab) | Jan 07, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [c6cd1c43ba](https://linux-hardware.org/?probe=c6cd1c43ba) | Dec 29, 2023 |
| ASRock        | AB350M-HDV                  | [2860ba102d](https://linux-hardware.org/?probe=2860ba102d) | Dec 18, 2023 |
| ASRock        | AB350M-HDV                  | [8d45a13b61](https://linux-hardware.org/?probe=8d45a13b61) | Dec 17, 2023 |
| Gigabyte      | B560M DS3H V2               | [2fa2dbdf4a](https://linux-hardware.org/?probe=2fa2dbdf4a) | Dec 06, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [a0e082b7d2](https://linux-hardware.org/?probe=a0e082b7d2) | Dec 01, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [532f8ccb97](https://linux-hardware.org/?probe=532f8ccb97) | Nov 27, 2023 |
| HP            | 89D8 SMVB                   | [e5bd9d36f3](https://linux-hardware.org/?probe=e5bd9d36f3) | Nov 25, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [829e6fdd78](https://linux-hardware.org/?probe=829e6fdd78) | Nov 23, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [887bb8aabe](https://linux-hardware.org/?probe=887bb8aabe) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [32e985afeb](https://linux-hardware.org/?probe=32e985afeb) | Nov 21, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [e723e12a01](https://linux-hardware.org/?probe=e723e12a01) | Nov 19, 2023 |
| Gigabyte      | B450M GAMING                | [33064ccfdf](https://linux-hardware.org/?probe=33064ccfdf) | Nov 14, 2023 |
| MSI           | Z270 PC MATE                | [e53ba2625b](https://linux-hardware.org/?probe=e53ba2625b) | Nov 09, 2023 |
| Gigabyte      | B450M GAMING                | [d788a3221f](https://linux-hardware.org/?probe=d788a3221f) | Nov 08, 2023 |
| ASRock        | B550M Pro4                  | [665120f441](https://linux-hardware.org/?probe=665120f441) | Nov 07, 2023 |
| ASRock        | B450 Gaming K4              | [166a9aee87](https://linux-hardware.org/?probe=166a9aee87) | Nov 06, 2023 |
| HP            | 89D8 SMVB                   | [3672a7681b](https://linux-hardware.org/?probe=3672a7681b) | Oct 24, 2023 |
| Shenzhen M... | F7BRC                       | [f61616bfcb](https://linux-hardware.org/?probe=f61616bfcb) | Oct 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ac47775d14](https://linux-hardware.org/?probe=ac47775d14) | Oct 17, 2023 |
| Gigabyte      | B550M S2H                   | [92cf4d1df2](https://linux-hardware.org/?probe=92cf4d1df2) | Oct 03, 2023 |
| Gigabyte      | B550M S2H                   | [d7efd8ecaa](https://linux-hardware.org/?probe=d7efd8ecaa) | Oct 03, 2023 |
| Dell          | 0Y56T3 A01                  | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [3e29eb1d63](https://linux-hardware.org/?probe=3e29eb1d63) | Sep 26, 2023 |
| Dell          | 0KRC95 A01                  | [bfed5cdd27](https://linux-hardware.org/?probe=bfed5cdd27) | Sep 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [6f73b0398c](https://linux-hardware.org/?probe=6f73b0398c) | Sep 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [7b10a3651b](https://linux-hardware.org/?probe=7b10a3651b) | Sep 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ac041357b0](https://linux-hardware.org/?probe=ac041357b0) | Aug 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [131535162e](https://linux-hardware.org/?probe=131535162e) | Aug 14, 2023 |
| Gigabyte      | X570 UD                     | [c693096b39](https://linux-hardware.org/?probe=c693096b39) | Jul 26, 2023 |
| MSI           | H410M PRO                   | [881d77ac47](https://linux-hardware.org/?probe=881d77ac47) | Jul 04, 2023 |
| ASRock        | H310CM-DVS                  | [46429ac6ae](https://linux-hardware.org/?probe=46429ac6ae) | Jun 29, 2023 |
| ASUSTek       | H110M-D                     | [f95d5e83f5](https://linux-hardware.org/?probe=f95d5e83f5) | Jun 25, 2023 |
| MAXSUN        | MS-H81IL TR M.2             | [72c79949e0](https://linux-hardware.org/?probe=72c79949e0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [9493891426](https://linux-hardware.org/?probe=9493891426) | Jun 18, 2023 |
| Gigabyte      | Z170X-Gaming 6              | [21eaab076a](https://linux-hardware.org/?probe=21eaab076a) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc54139aa6](https://linux-hardware.org/?probe=cc54139aa6) | Jun 08, 2023 |
| HP            | 8617                        | [7f5df3475c](https://linux-hardware.org/?probe=7f5df3475c) | Jun 06, 2023 |
| Dell          | 0J3C2F A00                  | [b7d801d9e5](https://linux-hardware.org/?probe=b7d801d9e5) | May 24, 2023 |
| Gigabyte      | B560M DS3H V2               | [47f3dabdb0](https://linux-hardware.org/?probe=47f3dabdb0) | May 14, 2023 |
| ASUSTek       | Z97-DELUXE                  | [c47205c3cb](https://linux-hardware.org/?probe=c47205c3cb) | May 06, 2023 |
| ASUSTek       | X99-A                       | [1adc932507](https://linux-hardware.org/?probe=1adc932507) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD5H                   | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| Gigabyte      | H77N-WIFI                   | [10e158aabd](https://linux-hardware.org/?probe=10e158aabd) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [2391458529](https://linux-hardware.org/?probe=2391458529) | Apr 15, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1146ed168f](https://linux-hardware.org/?probe=1146ed168f) | Apr 14, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [7c32eb6bf9](https://linux-hardware.org/?probe=7c32eb6bf9) | Apr 11, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [cabf7adac2](https://linux-hardware.org/?probe=cabf7adac2) | Apr 11, 2023 |
| HP            | 89D8 SMVB                   | [a9980f1194](https://linux-hardware.org/?probe=a9980f1194) | Apr 04, 2023 |
| Acer          | Nitro N50-610               | [937d1bc73a](https://linux-hardware.org/?probe=937d1bc73a) | Mar 29, 2023 |
| ASRock        | X300M-STX                   | [0393d25a9d](https://linux-hardware.org/?probe=0393d25a9d) | Mar 23, 2023 |
| ASRock        | X300M-STX                   | [296411b749](https://linux-hardware.org/?probe=296411b749) | Mar 23, 2023 |
| HP            | 83E9                        | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [a77d320c80](https://linux-hardware.org/?probe=a77d320c80) | Mar 18, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | [5cb3c60db6](https://linux-hardware.org/?probe=5cb3c60db6) | Mar 14, 2023 |
| HP            | 89D8 SMVB                   | [6b3f831210](https://linux-hardware.org/?probe=6b3f831210) | Mar 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [e2d3c4e17e](https://linux-hardware.org/?probe=e2d3c4e17e) | Mar 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | [79f1c1822c](https://linux-hardware.org/?probe=79f1c1822c) | Mar 09, 2023 |
| Gigabyte      | B450 AORUS M                | [e67eb9d235](https://linux-hardware.org/?probe=e67eb9d235) | Mar 06, 2023 |
| ASUSTek       | PRIME A320I-K               | [88e6308c0a](https://linux-hardware.org/?probe=88e6308c0a) | Mar 05, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [53d547f79c](https://linux-hardware.org/?probe=53d547f79c) | Mar 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [0195132360](https://linux-hardware.org/?probe=0195132360) | Feb 28, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8cd8d4b833](https://linux-hardware.org/?probe=8cd8d4b833) | Feb 28, 2023 |
| Biostar       | A320MH                      | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| ASRock        | B760M-ITX/D4 WiFi           | [8a29735d16](https://linux-hardware.org/?probe=8a29735d16) | Feb 16, 2023 |
| HP            | 83EC                        | [4757525f5d](https://linux-hardware.org/?probe=4757525f5d) | Feb 15, 2023 |
| Shenzhen M... | F7BFC                       | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| ASRock        | B560 Pro4                   | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| MSI           | B450M MORTAR MAX            | [2f0810d441](https://linux-hardware.org/?probe=2f0810d441) | Feb 05, 2023 |
| Gigabyte      | B450 AORUS M                | [c35fa9b7f5](https://linux-hardware.org/?probe=c35fa9b7f5) | Feb 05, 2023 |
| Gigabyte      | B85M-D3H                    | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte      | B85M-D3H                    | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Dell          | 0F3KHR A00                  | [a088ccf72c](https://linux-hardware.org/?probe=a088ccf72c) | Feb 02, 2023 |
| Dell          | 0F3KHR A00                  | [6c793de699](https://linux-hardware.org/?probe=6c793de699) | Feb 01, 2023 |
| Dell          | 0D6H9T A00                  | [2c34aba28a](https://linux-hardware.org/?probe=2c34aba28a) | Jan 30, 2023 |
| HP            | 8906 SMVB                   | [625d54930d](https://linux-hardware.org/?probe=625d54930d) | Jan 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3b92dd60cf](https://linux-hardware.org/?probe=3b92dd60cf) | Jan 11, 2023 |
| Gigabyte      | B450 AORUS M                | [0851440887](https://linux-hardware.org/?probe=0851440887) | Jan 11, 2023 |
| Gigabyte      | B550M DS3H                  | [3d656e7bfd](https://linux-hardware.org/?probe=3d656e7bfd) | Jan 05, 2023 |
| MSI           | H81M-P33                    | [041ee2fde1](https://linux-hardware.org/?probe=041ee2fde1) | Jan 03, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Dell          | 0KC9NP A01                  | [0e70489d5c](https://linux-hardware.org/?probe=0e70489d5c) | Dec 16, 2022 |
| ASUSTek       | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [65ccd1da0e](https://linux-hardware.org/?probe=65ccd1da0e) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [3f642a7844](https://linux-hardware.org/?probe=3f642a7844) | Dec 02, 2022 |
| Gigabyte      | B450M DS3H V2               | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| MSI           | 970A-G46                    | [3cd88e88d3](https://linux-hardware.org/?probe=3cd88e88d3) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c278b19567](https://linux-hardware.org/?probe=c278b19567) | Nov 20, 2022 |
| HP            | 8626                        | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP            | 8626                        | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| Gigabyte      | 970A-DS3P FX                | [85ef5eaf43](https://linux-hardware.org/?probe=85ef5eaf43) | Nov 12, 2022 |
| MSI           | X370 GAMING PLUS            | [a0b134897f](https://linux-hardware.org/?probe=a0b134897f) | Nov 05, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Gigabyte      | B550 GAMING X V2            | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| HP            | 8433 11                     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| MSI           | X399 SLI PLUS               | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| MSI           | X470 GAMING PLUS            | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| MSI           | 970A-G46                    | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| ASUSTek       | H81M-PLUS                   | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS M                | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Dell          | 0HHV7N A00                  | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Gigabyte      | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| MSI           | MS-B9351                    | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| Dell          | 00F82W A00                  | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Gigabyte      | H310M S2V                   | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| ASRock        | A520M-ITX/ac                | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock        | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Gigabyte      | H170N-WIFI-CF               | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Alienware     | 02XRCM A01                  | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| ASUSTek       | H61M-K                      | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock        | B550 PG Velocita            | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock        | B365M Pro4-F                | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | B560M AORUS PRO             | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| SteamOS 3.4                   | 54       | 38.3%   |
| SteamOS 3.3                   | 24       | 17.02%  |
| SteamOS 4                     | 23       | 16.31%  |
| SteamOS 3.2 (steamdeck-main)  | 7        | 4.96%   |
| SteamOS 3.5.7                 | 6        | 4.26%   |
| SteamOS                       | 6        | 4.26%   |
| SteamOS 1.1.2                 | 4        | 2.84%   |
| SteamOS Snapshot              | 3        | 2.13%   |
| SteamOS 3.5.17                | 2        | 1.42%   |
| SteamOS 1.1.6-prefinal_fixups | 2        | 1.42%   |
| SteamOS 1.1.4                 | 2        | 1.42%   |
| SteamOS 1.1.3                 | 2        | 1.42%   |
| SteamOS 1.01-dev_nv           | 2        | 1.42%   |
| SteamOS Rolling               | 1        | 0.71%   |
| SteamOS 3.2                   | 1        | 0.71%   |
| SteamOS 1.1.7_prerc-hotfix    | 1        | 0.71%   |
| SteamOS 1.03_3.5.13-dev_nv    | 1        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 137      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 43       | 30.94%  |
| 6.3.7-zen1-1-zen                                   | 21       | 15.11%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 7.91%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 7.19%   |
| 6.4.12-zen1-1-zen                                  | 8        | 5.76%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 5.04%   |
| 6.1.52-valve9-1-neptune-61                         | 6        | 4.32%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 6        | 4.32%   |
| 6.7.4-holoiso-beta_lljy-kernel-lljy-g76a2d2abfbba  | 3        | 2.16%   |
| 6.1.21-valve1-1-neptune-61                         | 3        | 2.16%   |
| 5.13.0-valve36-1-neptune                           | 3        | 2.16%   |
| 6.1.52-valve16-1-neptune-61                        | 2        | 1.44%   |
| 6.1.21-valve1-3-neptune-61                         | 2        | 1.44%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 1.44%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 2        | 1.44%   |
| 6.8.8-zen1-1-zen                                   | 1        | 0.72%   |
| 6.3.9-arch1-1                                      | 1        | 0.72%   |
| 6.1.29-valve4-1-neptune-61                         | 1        | 0.72%   |
| 6.1.12-valve2-1-neptune-61                         | 1        | 0.72%   |
| 5.15.93-1-lts                                      | 1        | 0.72%   |
| 5.15.79-1-lts                                      | 1        | 0.72%   |
| 5.15.60-1-lts                                      | 1        | 0.72%   |
| 5.13.0-valve24-1-neptune                           | 1        | 0.72%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 0.72%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 81       | 58.27%  |
| 6.3.7   | 21       | 15.11%  |
| 6.4.12  | 8        | 5.76%   |
| 6.1.52  | 8        | 5.76%   |
| 5.18.1  | 6        | 4.32%   |
| 6.1.21  | 5        | 3.6%    |
| 6.7.4   | 3        | 2.16%   |
| 6.8.8   | 1        | 0.72%   |
| 6.3.9   | 1        | 0.72%   |
| 6.1.29  | 1        | 0.72%   |
| 6.1.12  | 1        | 0.72%   |
| 5.15.93 | 1        | 0.72%   |
| 5.15.79 | 1        | 0.72%   |
| 5.15.60 | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 81       | 58.27%  |
| 6.3     | 22       | 15.83%  |
| 6.1     | 15       | 10.79%  |
| 6.4     | 8        | 5.76%   |
| 5.18    | 6        | 4.32%   |
| 6.7     | 3        | 2.16%   |
| 5.15    | 3        | 2.16%   |
| 6.8     | 1        | 0.72%   |

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


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 137      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 137      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 136      | 99.27%  |
| SDDM    | 1        | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 105      | 76.09%  |
| C     | 10       | 7.25%   |
| pt_BR | 5        | 3.62%   |
| fr_FR | 5        | 3.62%   |
| ru_RU | 2        | 1.45%   |
| es_ES | 2        | 1.45%   |
| de_DE | 2        | 1.45%   |
| pt_PT | 1        | 0.72%   |
| pl_PL | 1        | 0.72%   |
| n_US  | 1        | 0.72%   |
| en_IE | 1        | 0.72%   |
| en_GB | 1        | 0.72%   |
| en_DE | 1        | 0.72%   |
| de_AT | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 136      | 99.27%  |
| EFI  | 1        | 0.73%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 131      | 95.62%  |
| Tmpfs | 6        | 4.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 136      | 99.27%  |
| GPT     | 1        | 0.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 41       | 29.93%  |
| Gigabyte Technology                  | 35       | 25.55%  |
| ASRock                               | 18       | 13.14%  |
| MSI                                  | 17       | 12.41%  |
| Hewlett-Packard                      | 8        | 5.84%   |
| Dell                                 | 8        | 5.84%   |
| Shenzhen Meigao Electronic Equipment | 2        | 1.46%   |
| Apple                                | 2        | 1.46%   |
| QIYIDA                               | 1        | 0.73%   |
| MAXSUN                               | 1        | 0.73%   |
| MACHINIST                            | 1        | 0.73%   |
| Biostar                              | 1        | 0.73%   |
| Alienware                            | 1        | 0.73%   |
| Acer                                 | 1        | 0.73%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| ASUS All Series                                     | 6        | 4.38%   |
| Gigabyte B450 AORUS M                               | 4        | 2.92%   |
| Gigabyte B450M GAMING                               | 3        | 2.19%   |
| ASUS ROG STRIX B550-F GAMING                        | 3        | 2.19%   |
| ASUS PRIME A320M-K                                  | 3        | 2.19%   |
| MSI MS-7C02                                         | 2        | 1.46%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx           | 2        | 1.46%   |
| Gigabyte B550 GAMING X V2                           | 2        | 1.46%   |
| Dell OptiPlex 9010                                  | 2        | 1.46%   |
| ASRock B450 Gaming-ITX/ac                           | 2        | 1.46%   |
| Shenzhen Meigao Electronic Equipment UM690          | 1        | 0.73%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 1        | 0.73%   |
| QIYIDA ED4 V1.1                                     | 1        | 0.73%   |
| MSI MS-7D73                                         | 1        | 0.73%   |
| MSI MS-7C95                                         | 1        | 0.73%   |
| MSI MS-7C91                                         | 1        | 0.73%   |
| MSI MS-7C89                                         | 1        | 0.73%   |
| MSI MS-7C37                                         | 1        | 0.73%   |
| MSI MS-7B89                                         | 1        | 0.73%   |
| MSI MS-7B79                                         | 1        | 0.73%   |
| MSI MS-7B33                                         | 1        | 0.73%   |
| MSI MS-7B09                                         | 1        | 0.73%   |
| MSI MS-7A72                                         | 1        | 0.73%   |
| MSI MS-7A33                                         | 1        | 0.73%   |
| MSI MS-7817                                         | 1        | 0.73%   |
| MSI MS-7693                                         | 1        | 0.73%   |
| MSI MPG H510 Trident 3 (MS-B935)                    | 1        | 0.73%   |
| MSI H310 Gaming Trident3 (MS-B920)                  | 1        | 0.73%   |
| MAXSUN MS-H81IL TR M.2                              | 1        | 0.73%   |
| MACHINIST E5 MR9A PRO MAX V1.1                      | 1        | 0.73%   |
| HP ProDesk 600 G4 MT                                | 1        | 0.73%   |
| HP ProDesk 405 G4 Desktop Mini                      | 1        | 0.73%   |
| HP Pavilion Gaming Desktop TG01-2xxx                | 1        | 0.73%   |
| HP Pavilion Gaming Desktop 690-00xx                 | 1        | 0.73%   |
| HP EliteDesk 705 G5 SFF                             | 1        | 0.73%   |
| HP EliteDesk 705 G4 DM 65W (TAA)                    | 1        | 0.73%   |
| Gigabyte Z97X-UD5H                                  | 1        | 0.73%   |
| Gigabyte Z690M AORUS ELITE AX DDR4                  | 1        | 0.73%   |
| Gigabyte Z170X-Gaming 6                             | 1        | 0.73%   |
| Gigabyte X570 UD                                    | 1        | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| ASUS PRIME                                   | 11       | 8.03%   |
| ASUS ROG                                     | 9        | 6.57%   |
| Dell OptiPlex                                | 6        | 4.38%   |
| ASUS All                                     | 6        | 4.38%   |
| Gigabyte B450M                               | 5        | 3.65%   |
| Gigabyte B450                                | 5        | 3.65%   |
| ASUS TUF                                     | 5        | 3.65%   |
| Gigabyte X570                                | 3        | 2.19%   |
| ASRock B450                                  | 3        | 2.19%   |
| MSI MS-7C02                                  | 2        | 1.46%   |
| HP Victus                                    | 2        | 1.46%   |
| HP ProDesk                                   | 2        | 1.46%   |
| HP Pavilion                                  | 2        | 1.46%   |
| HP EliteDesk                                 | 2        | 1.46%   |
| Gigabyte B560M                               | 2        | 1.46%   |
| Gigabyte B550M                               | 2        | 1.46%   |
| Gigabyte B550                                | 2        | 1.46%   |
| Dell Precision                               | 2        | 1.46%   |
| ASRock B550M                                 | 2        | 1.46%   |
| ASRock B550                                  | 2        | 1.46%   |
| Shenzhen Meigao Electronic Equipment UM690   | 1        | 0.73%   |
| Shenzhen Meigao Electronic Equipment Mercury | 1        | 0.73%   |
| QIYIDA ED4                                   | 1        | 0.73%   |
| MSI MS-7D73                                  | 1        | 0.73%   |
| MSI MS-7C95                                  | 1        | 0.73%   |
| MSI MS-7C91                                  | 1        | 0.73%   |
| MSI MS-7C89                                  | 1        | 0.73%   |
| MSI MS-7C37                                  | 1        | 0.73%   |
| MSI MS-7B89                                  | 1        | 0.73%   |
| MSI MS-7B79                                  | 1        | 0.73%   |
| MSI MS-7B33                                  | 1        | 0.73%   |
| MSI MS-7B09                                  | 1        | 0.73%   |
| MSI MS-7A72                                  | 1        | 0.73%   |
| MSI MS-7A33                                  | 1        | 0.73%   |
| MSI MS-7817                                  | 1        | 0.73%   |
| MSI MS-7693                                  | 1        | 0.73%   |
| MSI MPG                                      | 1        | 0.73%   |
| MSI H310                                     | 1        | 0.73%   |
| MAXSUN MS-H81IL                              | 1        | 0.73%   |
| MACHINIST E5                                 | 1        | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 27       | 19.71%  |
| 2018 | 25       | 18.25%  |
| 2019 | 14       | 10.22%  |
| 2017 | 13       | 9.49%   |
| 2021 | 12       | 8.76%   |
| 2022 | 11       | 8.03%   |
| 2014 | 8        | 5.84%   |
| 2016 | 6        | 4.38%   |
| 2012 | 6        | 4.38%   |
| 2013 | 5        | 3.65%   |
| 2023 | 4        | 2.92%   |
| 2015 | 3        | 2.19%   |
| 2011 | 2        | 1.46%   |
| 2024 | 1        | 0.73%   |

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
| 16.01-24.0  | 62       | 44.93%  |
| 32.01-64.0  | 36       | 26.09%  |
| 8.01-16.0   | 19       | 13.77%  |
| 24.01-32.0  | 8        | 5.8%    |
| 4.01-8.0    | 7        | 5.07%   |
| 64.01-256.0 | 6        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 45       | 32.37%  |
| 2.01-3.0  | 45       | 32.37%  |
| 4.01-8.0  | 35       | 25.18%  |
| 1.01-2.0  | 8        | 5.76%   |
| 8.01-16.0 | 6        | 4.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 30.94%  |
| 2      | 37       | 26.62%  |
| 3      | 32       | 23.02%  |
| 4      | 15       | 10.79%  |
| 5      | 8        | 5.76%   |
| 11     | 1        | 0.72%   |
| 8      | 1        | 0.72%   |
| 7      | 1        | 0.72%   |
| 6      | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 88.32%  |
| Yes       | 16       | 11.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 135      | 98.54%  |
| No        | 2        | 1.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 63.5%   |
| No        | 50       | 36.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 55.07%  |
| No        | 62       | 44.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 52       | 37.68%  |
| Brazil       | 10       | 7.25%   |
| UK           | 8        | 5.8%    |
| France       | 8        | 5.8%    |
| Germany      | 6        | 4.35%   |
| Australia    | 5        | 3.62%   |
| Poland       | 4        | 2.9%    |
| Spain        | 3        | 2.17%   |
| South Africa | 3        | 2.17%   |
| Italy        | 3        | 2.17%   |
| Ireland      | 3        | 2.17%   |
| Canada       | 3        | 2.17%   |
| Russia       | 2        | 1.45%   |
| Philippines  | 2        | 1.45%   |
| Austria      | 2        | 1.45%   |
| Vietnam      | 1        | 0.72%   |
| Uzbekistan   | 1        | 0.72%   |
| Turkey       | 1        | 0.72%   |
| Thailand     | 1        | 0.72%   |
| Romania      | 1        | 0.72%   |
| Portugal     | 1        | 0.72%   |
| Peru         | 1        | 0.72%   |
| Paraguay     | 1        | 0.72%   |
| Oman         | 1        | 0.72%   |
| Malaysia     | 1        | 0.72%   |
| Latvia       | 1        | 0.72%   |
| Kazakhstan   | 1        | 0.72%   |
| Japan        | 1        | 0.72%   |
| Israel       | 1        | 0.72%   |
| Indonesia    | 1        | 0.72%   |
| Iceland      | 1        | 0.72%   |
| Hungary      | 1        | 0.72%   |
| Hong Kong    | 1        | 0.72%   |
| El Salvador  | 1        | 0.72%   |
| Denmark      | 1        | 0.72%   |
| Czechia      | 1        | 0.72%   |
| Chile        | 1        | 0.72%   |
| Cambodia     | 1        | 0.72%   |
| Argentina    | 1        | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 1.44%   |
| Sao Paulo              | 2        | 1.44%   |
| San Jose               | 2        | 1.44%   |
| Oklahoma City          | 2        | 1.44%   |
| Moscow                 | 2        | 1.44%   |
| Gujan-Mestras          | 2        | 1.44%   |
| Dallas                 | 2        | 1.44%   |
| Brasília              | 2        | 1.44%   |
| Zevio                  | 1        | 0.72%   |
| Woodway                | 1        | 0.72%   |
| West Bloomfield        | 1        | 0.72%   |
| Walsall                | 1        | 0.72%   |
| Ville Platte           | 1        | 0.72%   |
| Vilas                  | 1        | 0.72%   |
| Tyumen                 | 1        | 0.72%   |
| Tuam                   | 1        | 0.72%   |
| Toronto                | 1        | 0.72%   |
| Tashkent               | 1        | 0.72%   |
| Targoviste             | 1        | 0.72%   |
| Sundern                | 1        | 0.72%   |
| Sterling Heights       | 1        | 0.72%   |
| St Louis               | 1        | 0.72%   |
| Spartanburg            | 1        | 0.72%   |
| Sparta                 | 1        | 0.72%   |
| Skarzysko-Kamienna     | 1        | 0.72%   |
| Siloam Springs         | 1        | 0.72%   |
| Seattle                | 1        | 0.72%   |
| Sassenberg             | 1        | 0.72%   |
| Santiago               | 1        | 0.72%   |
| Santa Rosa             | 1        | 0.72%   |
| Santa Barbara d'Oeste  | 1        | 0.72%   |
| Sant Quirze del Valles | 1        | 0.72%   |
| Sankt Pölten          | 1        | 0.72%   |
| San Salvador           | 1        | 0.72%   |
| Salford                | 1        | 0.72%   |
| Salem                  | 1        | 0.72%   |
| Riga                   | 1        | 0.72%   |
| Reykjavik              | 1        | 0.72%   |
| Quezon City            | 1        | 0.72%   |
| Puchberg am Schneeberg | 1        | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 46       | 58     | 15.86%  |
| WDC                         | 36       | 45     | 12.41%  |
| Samsung Electronics         | 36       | 63     | 12.41%  |
| Kingston                    | 24       | 27     | 8.28%   |
| Sandisk                     | 22       | 26     | 7.59%   |
| Toshiba                     | 19       | 21     | 6.55%   |
| Crucial                     | 18       | 22     | 6.21%   |
| Phison Electronics          | 7        | 9      | 2.41%   |
| Micron/Crucial Technology   | 7        | 7      | 2.41%   |
| Silicon Motion              | 6        | 7      | 2.07%   |
| PNY                         | 6        | 7      | 2.07%   |
| MAXIO Technology (Hangzhou) | 6        | 7      | 2.07%   |
| A-DATA Technology           | 6        | 6      | 2.07%   |
| Realtek Semiconductor       | 4        | 4      | 1.38%   |
| Phison                      | 4        | 5      | 1.38%   |
| Intel                       | 4        | 6      | 1.38%   |
| Unknown                     | 4        | 5      | 1.38%   |
| Hitachi                     | 3        | 3      | 1.03%   |
| China                       | 3        | 6      | 1.03%   |
| SPCC                        | 2        | 4      | 0.69%   |
| SK hynix                    | 2        | 2      | 0.69%   |
| Realtek                     | 2        | 2      | 0.69%   |
| Patriot                     | 2        | 2      | 0.69%   |
| Mushkin                     | 2        | 2      | 0.69%   |
| Kingston Technology Company | 2        | 2      | 0.69%   |
| Unknown                     | 1        | 1      | 0.34%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.34%   |
| T-FORCE                     | 1        | 1      | 0.34%   |
| Ramsta                      | 1        | 1      | 0.34%   |
| Micron Technology           | 1        | 1      | 0.34%   |
| KIOXIA                      | 1        | 1      | 0.34%   |
| KingFast                    | 1        | 1      | 0.34%   |
| Intenso                     | 1        | 1      | 0.34%   |
| HUSKY                       | 1        | 1      | 0.34%   |
| HS-SSD-C100                 | 1        | 1      | 0.34%   |
| Gigastone                   | 1        | 1      | 0.34%   |
| General                     | 1        | 1      | 0.34%   |
| GALAX                       | 1        | 1      | 0.34%   |
| Apple                       | 1        | 1      | 0.34%   |
| Apacer                      | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6        | 1.85%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB    | 6        | 1.85%   |
| Toshiba DT01ACA100 1TB                                | 5        | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 5        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 5        | 1.54%   |
| Kingston SA400S37240G 240GB SSD                       | 5        | 1.54%   |
| Crucial CT1000BX500SSD1 1TB                           | 5        | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 1.23%   |
| Kingston SA400S37120G 120GB SSD                       | 4        | 1.23%   |
| Unknown                                               | 4        | 1.23%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                       | 3        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3        | 0.92%   |
| Samsung SSD 980 1TB                                   | 3        | 0.92%   |
| Samsung SSD 850 EVO 250GB                             | 3        | 0.92%   |
| Samsung NVMe SSD Drive 1TB                            | 3        | 0.92%   |
| Phison E12 NVMe Controller 2TB                        | 3        | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 3        | 0.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 2        | 0.62%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2        | 0.62%   |
| WDC WD10EZEX-00WN4A0 1TB                              | 2        | 0.62%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 2        | 0.62%   |
| Toshiba MQ01ABD100 1TB                                | 2        | 0.62%   |
| Seagate ST4000DX001-1CE168 4TB                        | 2        | 0.62%   |
| Seagate ST3500414CS 500GB                             | 2        | 0.62%   |
| Seagate ST3500413AS 500GB                             | 2        | 0.62%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                        | 2        | 0.62%   |
| Seagate ST1000LM014-1EJ164 1TB                        | 2        | 0.62%   |
| Sandisk WD Blue SN570 1TB                             | 2        | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 2        | 0.62%   |
| SanDisk SSD PLUS 480GB                                | 2        | 0.62%   |
| SanDisk NVMe SSD Drive 500GB                          | 2        | 0.62%   |
| Samsung SSD 860 EVO 250GB                             | 2        | 0.62%   |
| Samsung SSD 850 EVO 500GB                             | 2        | 0.62%   |
| Samsung SSD 840 EVO 250GB                             | 2        | 0.62%   |
| Realtek NVMe SSD Drive 256GB                          | 2        | 0.62%   |
| PNY CS900 120GB SSD                                   | 2        | 0.62%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 2        | 0.62%   |
| Micron/Crucial CT1000P1SSD8 1TB                       | 2        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 57     | 48.39%  |
| WDC                 | 25       | 31     | 26.88%  |
| Toshiba             | 17       | 19     | 18.28%  |
| Samsung Electronics | 3        | 3      | 3.23%   |
| Hitachi             | 3        | 3      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 33     | 20.18%  |
| Crucial             | 18       | 22     | 16.51%  |
| Kingston            | 17       | 19     | 15.6%   |
| WDC                 | 13       | 14     | 11.93%  |
| SanDisk             | 10       | 11     | 9.17%   |
| PNY                 | 6        | 7      | 5.5%    |
| A-DATA Technology   | 6        | 6      | 5.5%    |
| China               | 3        | 6      | 2.75%   |
| SPCC                | 2        | 4      | 1.83%   |
| Patriot             | 2        | 2      | 1.83%   |
| Mushkin             | 2        | 2      | 1.83%   |
| Ramsta              | 1        | 1      | 0.92%   |
| Micron Technology   | 1        | 1      | 0.92%   |
| Intenso             | 1        | 1      | 0.92%   |
| Intel               | 1        | 1      | 0.92%   |
| HUSKY               | 1        | 1      | 0.92%   |
| Gigastone           | 1        | 1      | 0.92%   |
| Apacer              | 1        | 1      | 0.92%   |
| 2.5                 | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 83       | 134    | 34.16%  |
| NVMe    | 82       | 109    | 33.74%  |
| HDD     | 70       | 113    | 28.81%  |
| Unknown | 8        | 10     | 3.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 114      | 246    | 55.34%  |
| NVMe | 82       | 106    | 39.81%  |
| SAS  | 10       | 14     | 4.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 76       | 120    | 44.19%  |
| 0.51-1.0   | 59       | 78     | 34.3%   |
| 1.01-2.0   | 17       | 25     | 9.88%   |
| 3.01-4.0   | 11       | 12     | 6.4%    |
| 2.01-3.0   | 4        | 6      | 2.33%   |
| 4.01-10.0  | 4        | 4      | 2.33%   |
| 10.01-20.0 | 1        | 2      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 37       | 26.81%  |
| 501-1000       | 35       | 25.36%  |
| 251-500        | 24       | 17.39%  |
| 1001-2000      | 22       | 15.94%  |
| More than 3000 | 12       | 8.7%    |
| 2001-3000      | 3        | 2.17%   |
| Unknown        | 3        | 2.17%   |
| 1-20           | 1        | 0.72%   |
| 51-100         | 1        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 27.86%  |
| 101-250        | 25       | 17.86%  |
| 21-50          | 23       | 16.43%  |
| 51-100         | 22       | 15.71%  |
| 501-1000       | 13       | 9.29%   |
| 251-500        | 6        | 4.29%   |
| 1001-2000      | 5        | 3.57%   |
| Unknown        | 3        | 2.14%   |
| More than 3000 | 2        | 1.43%   |
| 2001-3000      | 2        | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 137      | 365    | 99.28%  |
| Works    | 1        | 1      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 76       | 33.48%  |
| Intel                        | 58       | 25.55%  |
| Samsung Electronics          | 20       | 8.81%   |
| SanDisk                      | 13       | 5.73%   |
| Phison Electronics           | 11       | 4.85%   |
| Kingston Technology Company  | 9        | 3.96%   |
| Micron/Crucial Technology    | 7        | 3.08%   |
| Silicon Motion               | 6        | 2.64%   |
| MAXIO Technology (Hangzhou)  | 6        | 2.64%   |
| Realtek Semiconductor        | 4        | 1.76%   |
| ASMedia Technology           | 4        | 1.76%   |
| Marvell Technology Group     | 3        | 1.32%   |
| Toshiba America Info Systems | 2        | 0.88%   |
| SK hynix                     | 2        | 0.88%   |
| Union Memory (Shenzhen)      | 1        | 0.44%   |
| Seagate Technology           | 1        | 0.44%   |
| KIOXIA                       | 1        | 0.44%   |
| INNOGRIT                     | 1        | 0.44%   |
| Apple                        | 1        | 0.44%   |
| ADATA Technology             | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 45       | 16.42%  |
| AMD 400 Series Chipset SATA Controller                                         | 25       | 9.12%   |
| AMD 500 Series Chipset SATA Controller                                         | 19       | 6.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8        | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 2.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.55%   |
| AMD FCH SATA Controller D                                                      | 7        | 2.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6        | 2.19%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 6        | 2.19%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 2.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5        | 1.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5        | 1.82%   |
| Phison E12 NVMe Controller                                                     | 5        | 1.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 5        | 1.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4        | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.46%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4        | 1.46%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3        | 1.09%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 3        | 1.09%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.09%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.09%   |
| AMD 600 Series Chipset SATA Controller                                         | 3        | 1.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2        | 0.73%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2        | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 0.73%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2        | 0.73%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 2        | 0.73%   |
| Phison PS5015-E15 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 2        | 0.73%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                 | 2        | 0.73%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 2        | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.73%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 0.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 125      | 57.08%  |
| NVMe | 82       | 37.44%  |
| RAID | 9        | 4.11%   |
| IDE  | 2        | 0.91%   |
| SAS  | 1        | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 80       | 58.39%  |
| Intel  | 57       | 41.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics | 10       | 7.3%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 5        | 3.65%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 5        | 3.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 4        | 2.92%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 2.92%   |
| AMD Ryzen 5 3600 6-Core Processor      | 4        | 2.92%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 4        | 2.92%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 4        | 2.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 2.19%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 3        | 2.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 3        | 2.19%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 3        | 2.19%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 2.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.46%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 1.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1.46%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 2        | 1.46%   |
| Intel Core i3-9100F CPU @ 3.60GHz      | 2        | 1.46%   |
| Intel 12th Gen Core i3-12100F          | 2        | 1.46%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 2        | 1.46%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 1.46%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 2        | 1.46%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 2        | 1.46%   |
| AMD Ryzen 5 4500 6-Core Processor      | 2        | 1.46%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 1.46%   |
| AMD FX-6300 Six-Core Processor         | 2        | 1.46%   |
| Intel Xeon W-3223 CPU @ 3.50GHz        | 1        | 0.73%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.73%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1        | 0.73%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz    | 1        | 0.73%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz    | 1        | 0.73%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 1        | 0.73%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz    | 1        | 0.73%   |
| Intel Xeon CPU E31220 @ 3.10GHz        | 1        | 0.73%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 1        | 0.73%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 0.73%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 0.73%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 0.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.73%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 39       | 28.47%  |
| Intel Core i5          | 19       | 13.87%  |
| Intel Core i7          | 18       | 13.14%  |
| AMD Ryzen 7            | 16       | 11.68%  |
| AMD Ryzen 9            | 12       | 8.76%   |
| Other                  | 8        | 5.84%   |
| Intel Xeon             | 8        | 5.84%   |
| AMD Ryzen 5 PRO        | 4        | 2.92%   |
| Intel Core i3          | 3        | 2.19%   |
| AMD FX                 | 3        | 2.19%   |
| AMD Ryzen 3            | 2        | 1.46%   |
| Intel Celeron          | 1        | 0.73%   |
| AMD Ryzen Threadripper | 1        | 0.73%   |
| AMD Ryzen 7 PRO        | 1        | 0.73%   |
| AMD Athlon X4          | 1        | 0.73%   |
| AMD Athlon             | 1        | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 52       | 37.96%  |
| 4      | 40       | 29.2%   |
| 8      | 23       | 16.79%  |
| 12     | 13       | 9.49%   |
| 2      | 4        | 2.92%   |
| 16     | 3        | 2.19%   |
| 3      | 2        | 1.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 98.54%  |
| 2      | 2        | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 114      | 83.21%  |
| 1      | 23       | 16.79%  |

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
| Unknown    | 136      | 99.27%  |
| 0x08701021 | 1        | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 25       | 18.25%  |
| Zen+        | 19       | 13.87%  |
| Zen 2       | 19       | 13.87%  |
| KabyLake    | 15       | 10.95%  |
| Haswell     | 13       | 9.49%   |
| Unknown     | 13       | 9.49%   |
| Zen         | 8        | 5.84%   |
| Skylake     | 7        | 5.11%   |
| IvyBridge   | 5        | 3.65%   |
| SandyBridge | 4        | 2.92%   |
| Piledriver  | 3        | 2.19%   |
| CometLake   | 3        | 2.19%   |
| Westmere    | 1        | 0.73%   |
| Steamroller | 1        | 0.73%   |
| Broadwell   | 1        | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 100      | 65.79%  |
| Nvidia | 35       | 23.03%  |
| Intel  | 17       | 11.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23       | 14.29%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 11       | 6.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 5.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 4.97%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 4.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 3.73%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 6        | 3.73%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.11%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 3.11%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4        | 2.48%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.86%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.24%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 1.24%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.24%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.24%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.24%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.24%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.24%   |
| Intel HD Graphics 530                                                       | 2        | 1.24%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2        | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.24%   |
| AMD Raphael                                                                 | 2        | 1.24%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 1.24%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 2        | 1.24%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.62%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 85       | 61.15%  |
| 1 x Nvidia     | 31       | 22.3%   |
| 2 x AMD        | 9        | 6.47%   |
| 1 x Intel      | 5        | 3.6%    |
| Intel + AMD    | 4        | 2.88%   |
| AMD + Nvidia   | 3        | 2.16%   |
| Intel + Nvidia | 2        | 1.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 113      | 82.48%  |
| Proprietary | 24       | 17.52%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 113      | 81.88%  |
| 3.01-4.0   | 9        | 6.52%   |
| 7.01-8.0   | 8        | 5.8%    |
| 5.01-6.0   | 3        | 2.17%   |
| 8.01-16.0  | 2        | 1.45%   |
| 2.01-3.0   | 1        | 0.72%   |
| 16.01-24.0 | 1        | 0.72%   |
| 1.01-2.0   | 1        | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 17       | 12.32%  |
| Goldstar             | 17       | 12.32%  |
| Acer                 | 12       | 8.7%    |
| AOC                  | 9        | 6.52%   |
| Ancor Communications | 8        | 5.8%    |
| Hewlett-Packard      | 6        | 4.35%   |
| Dell                 | 6        | 4.35%   |
| ASUSTek Computer     | 6        | 4.35%   |
| Sony                 | 5        | 3.62%   |
| Philips              | 5        | 3.62%   |
| ViewSonic            | 4        | 2.9%    |
| Toshiba              | 3        | 2.17%   |
| Sceptre Tech         | 3        | 2.17%   |
| Pixio                | 3        | 2.17%   |
| MSI                  | 3        | 2.17%   |
| Hitachi              | 3        | 2.17%   |
| Valve                | 2        | 1.45%   |
| Unknown (XXX)        | 2        | 1.45%   |
| RTK                  | 2        | 1.45%   |
| ONN                  | 2        | 1.45%   |
| ___                  | 1        | 0.72%   |
| WIT                  | 1        | 0.72%   |
| Wacom                | 1        | 0.72%   |
| VIE                  | 1        | 0.72%   |
| Unknown              | 1        | 0.72%   |
| Sun                  | 1        | 0.72%   |
| SKG                  | 1        | 0.72%   |
| SANYO                | 1        | 0.72%   |
| Roku                 | 1        | 0.72%   |
| Panasonic            | 1        | 0.72%   |
| MStar                | 1        | 0.72%   |
| Insignia             | 1        | 0.72%   |
| Huion                | 1        | 0.72%   |
| HJW                  | 1        | 0.72%   |
| HannStar             | 1        | 0.72%   |
| Gigabyte Technology  | 1        | 0.72%   |
| Fujitsu Siemens      | 1        | 0.72%   |
| DZX                  | 1        | 0.72%   |
| BenQ                 | 1        | 0.72%   |
| AOpen                | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 2.13%   |
| Valve Index HMD VLV91A8 2880x1600                                       | 2        | 1.42%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 2        | 1.42%   |
| Toshiba TV TSB0206 1920x1080                                            | 2        | 1.42%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2        | 1.42%   |
| Pixio OZDSP27IPS WAM2700 2560x1440 597x336mm 27.0-inch                  | 2        | 1.42%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 2        | 1.42%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 1.42%   |
| AOC Q32G2WG3 AOC3202 2560x1440 697x392mm 31.5-inch                      | 2        | 1.42%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2        | 1.42%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 0.71%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 0.71%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.71%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 0.71%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch              | 1        | 0.71%   |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch             | 1        | 0.71%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 0.71%   |
| VIE R270Q144 VIE2700 2560x1440 598x336mm 27.0-inch                      | 1        | 0.71%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.71%   |
| Toshiba TV TSB010E 1920x1080 882x498mm 39.9-inch                        | 1        | 0.71%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 0.71%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 0.71%   |
| Sony TV SNY5803 1360x768                                                | 1        | 0.71%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                           | 1        | 0.71%   |
| Sony TV *00 SNY3F05 3840x2160 1218x685mm 55.0-inch                      | 1        | 0.71%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 0.71%   |
| SKG AQ27H1 SKG2722 2560x1440 620x370mm 28.4-inch                        | 1        | 0.71%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch          | 1        | 0.71%   |
| Sceptre Tech E50 SPT13C0 1920x1080 575x323mm 26.0-inch                  | 1        | 0.71%   |
| Sceptre Tech E22 SPT08D5 1920x1080 470x300mm 22.0-inch                  | 1        | 0.71%   |
| SANYO LCD SAN0B60 1440x900 400x225mm 18.1-inch                          | 1        | 0.71%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch       | 1        | 0.71%   |
| Samsung Electronics SMT24A350 SAM07AD 1920x1080 531x299mm 24.0-inch     | 1        | 0.71%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 0.71%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.71%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 630x360mm 28.6-inch       | 1        | 0.71%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.71%   |
| Samsung Electronics LS27AG30x SAM717B 1920x1080 597x336mm 27.0-inch     | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7269 3840x2160 700x390mm 31.5-inch   | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 64       | 48.85%  |
| 3840x2160 (4K)     | 33       | 25.19%  |
| 2560x1440 (QHD)    | 14       | 10.69%  |
| 2560x1080          | 3        | 2.29%   |
| 3840x1080          | 2        | 1.53%   |
| 1920x1200 (WUXGA)  | 2        | 1.53%   |
| 1440x900 (WXGA+)   | 2        | 1.53%   |
| 1360x768           | 2        | 1.53%   |
| Unknown            | 2        | 1.53%   |
| 3440x1440          | 1        | 0.76%   |
| 1680x1050 (WSXGA+) | 1        | 0.76%   |
| 1600x900 (HD+)     | 1        | 0.76%   |
| 1400x1050          | 1        | 0.76%   |
| 1366x768 (WXGA)    | 1        | 0.76%   |
| 1280x1024 (SXGA)   | 1        | 0.76%   |
| 1024x768 (XGA)     | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 23       | 16.79%  |
| 24      | 21       | 15.33%  |
| 31      | 19       | 13.87%  |
| 23      | 19       | 13.87%  |
| 84      | 7        | 5.11%   |
| 21      | 7        | 5.11%   |
| 72      | 5        | 3.65%   |
| 48      | 3        | 2.19%   |
| 15      | 3        | 2.19%   |
| Unknown | 3        | 2.19%   |
| 74      | 2        | 1.46%   |
| 65      | 2        | 1.46%   |
| 54      | 2        | 1.46%   |
| 52      | 2        | 1.46%   |
| 46      | 2        | 1.46%   |
| 34      | 2        | 1.46%   |
| 28      | 2        | 1.46%   |
| 19      | 2        | 1.46%   |
| 18      | 2        | 1.46%   |
| 85      | 1        | 0.73%   |
| 57      | 1        | 0.73%   |
| 47      | 1        | 0.73%   |
| 40      | 1        | 0.73%   |
| 35      | 1        | 0.73%   |
| 32      | 1        | 0.73%   |
| 26      | 1        | 0.73%   |
| 25      | 1        | 0.73%   |
| 20      | 1        | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 57       | 43.18%  |
| 601-700     | 24       | 18.18%  |
| 1501-2000   | 15       | 11.36%  |
| 1001-1500   | 13       | 9.85%   |
| 401-500     | 9        | 6.82%   |
| 701-800     | 3        | 2.27%   |
| 351-400     | 3        | 2.27%   |
| 301-350     | 3        | 2.27%   |
| Unknown     | 3        | 2.27%   |
| 801-900     | 2        | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 111      | 86.72%  |
| 16/10   | 7        | 5.47%   |
| 21/9    | 3        | 2.34%   |
| 5/4     | 2        | 1.56%   |
| 32/9    | 2        | 1.56%   |
| Unknown | 2        | 1.56%   |
| 4/3     | 1        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 27.21%  |
| 351-500        | 25       | 18.38%  |
| More than 1000 | 23       | 16.91%  |
| 301-350        | 23       | 16.91%  |
| 251-300        | 10       | 7.35%   |
| 501-1000       | 6        | 4.41%   |
| 151-200        | 4        | 2.94%   |
| Unknown        | 3        | 2.21%   |
| 101-110        | 2        | 1.47%   |
| 141-150        | 1        | 0.74%   |
| 131-140        | 1        | 0.74%   |
| 91-100         | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 63.57%  |
| 101-120 | 20       | 15.5%   |
| 1-50    | 13       | 10.08%  |
| 121-160 | 9        | 6.98%   |
| Unknown | 3        | 2.33%   |
| 161-240 | 2        | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 117      | 84.78%  |
| 2     | 21       | 15.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 89       | 42.18%  |
| Intel                                 | 69       | 32.7%   |
| Broadcom                              | 10       | 4.74%   |
| TP-Link                               | 8        | 3.79%   |
| Microsoft                             | 6        | 2.84%   |
| Qualcomm Atheros                      | 5        | 2.37%   |
| MediaTek                              | 5        | 2.37%   |
| Samsung Electronics                   | 2        | 0.95%   |
| Ralink Technology                     | 2        | 0.95%   |
| OPPO Electronics                      | 2        | 0.95%   |
| D-Link                                | 2        | 0.95%   |
| ASUSTek Computer                      | 2        | 0.95%   |
| Xiaomi                                | 1        | 0.47%   |
| OnePlus Technology (Shenzhen)         | 1        | 0.47%   |
| Linksys                               | 1        | 0.47%   |
| Huawei Technologies                   | 1        | 0.47%   |
| Google                                | 1        | 0.47%   |
| Broadcom Limited                      | 1        | 0.47%   |
| Aquantia                              | 1        | 0.47%   |
| Apple                                 | 1        | 0.47%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 73       | 28.85%  |
| Intel Wi-Fi 6 AX200                                                                           | 13       | 5.14%   |
| Intel I211 Gigabit Network Connection                                                         | 13       | 5.14%   |
| Intel Ethernet Connection (2) I219-V                                                          | 12       | 4.74%   |
| Intel Ethernet Controller I225-V                                                              | 10       | 3.95%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 9        | 3.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 7        | 2.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 6        | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6        | 2.37%   |
| Realtek 802.11ac NIC                                                                          | 5        | 1.98%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 1.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 3        | 1.19%   |
| Microsoft XBOX ACC                                                                            | 3        | 1.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 1.19%   |
| Intel Wireless 8260                                                                           | 3        | 1.19%   |
| Intel Wireless 7265                                                                           | 3        | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.79%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 0.79%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 0.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 0.79%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 0.79%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1        | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.4%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.4%    |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.4%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.4%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 35       | 36.08%  |
| Realtek Semiconductor                 | 21       | 21.65%  |
| Broadcom                              | 10       | 10.31%  |
| TP-Link                               | 8        | 8.25%   |
| Microsoft                             | 6        | 6.19%   |
| MediaTek                              | 5        | 5.15%   |
| Qualcomm Atheros                      | 3        | 3.09%   |
| Ralink Technology                     | 2        | 2.06%   |
| D-Link                                | 2        | 2.06%   |
| ASUSTek Computer                      | 2        | 2.06%   |
| Linksys                               | 1        | 1.03%   |
| Broadcom Limited                      | 1        | 1.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 13       | 13.27%  |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 7        | 7.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 6        | 6.12%   |
| Realtek 802.11ac NIC                                                                          | 5        | 5.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 3.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 3.06%   |
| Microsoft XBOX ACC                                                                            | 3        | 3.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 3.06%   |
| Intel Wireless 8260                                                                           | 3        | 3.06%   |
| Intel Wireless 7265                                                                           | 3        | 3.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.04%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.04%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 2.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 2.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.02%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.02%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.02%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.02%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                                   | 1        | 1.02%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.02%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.02%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.02%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 1.02%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 1        | 1.02%   |
| Linksys WUSB300N 802.11bgn Wireless Adapter [Marvell 88W8362+88W8060]                         | 1        | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 1        | 1.02%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 1        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.02%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.02%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 86       | 56.95%  |
| Intel                         | 53       | 35.1%   |
| Qualcomm Atheros              | 3        | 1.99%   |
| Samsung Electronics           | 2        | 1.32%   |
| OPPO Electronics              | 2        | 1.32%   |
| Xiaomi                        | 1        | 0.66%   |
| OnePlus Technology (Shenzhen) | 1        | 0.66%   |
| Huawei Technologies           | 1        | 0.66%   |
| Google                        | 1        | 0.66%   |
| Aquantia                      | 1        | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 73       | 47.4%   |
| Intel I211 Gigabit Network Connection                                          | 13       | 8.44%   |
| Intel Ethernet Connection (2) I219-V                                           | 12       | 7.79%   |
| Intel Ethernet Controller I225-V                                               | 10       | 6.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 9        | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6        | 3.9%    |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.95%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 1.3%    |
| Intel Ethernet Connection I217-V                                               | 2        | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 2        | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1        | 0.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.65%   |
| OPPO SM8350-MTP _SN:9338D66C                                                   | 1        | 0.65%   |
| OPPO CPH2591                                                                   | 1        | 0.65%   |
| OnePlus (Shenzhen) OnePlus                                                     | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.65%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.65%   |
| Intel Ethernet Connection (12) I219-V                                          | 1        | 0.65%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 0.65%   |
| Huawei VTR-L09                                                                 | 1        | 0.65%   |
| Google Nexus/Pixel Device (tether)                                             | 1        | 0.65%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 135      | 60.54%  |
| WiFi     | 87       | 39.01%  |
| Modem    | 1        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 76.26%  |
| WiFi     | 33       | 23.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 54.74%  |
| 2     | 53       | 38.69%  |
| 3     | 9        | 6.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 65.69%  |
| Yes  | 47       | 34.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 41.25%  |
| Cambridge Silicon Radio         | 16       | 20%     |
| Realtek Semiconductor           | 6        | 7.5%    |
| ASUSTek Computer                | 5        | 6.25%   |
| TP-Link                         | 4        | 5%      |
| MediaTek                        | 4        | 5%      |
| Apple                           | 3        | 3.75%   |
| IMC Networks                    | 2        | 2.5%    |
| Foxconn / Hon Hai               | 2        | 2.5%    |
| Broadcom                        | 2        | 2.5%    |
| Realtek                         | 1        | 1.25%   |
| Qualcomm Atheros Communications | 1        | 1.25%   |
| Integrated System Solution      | 1        | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 16       | 20%     |
| Intel AX200 Bluetooth                                 | 12       | 15%     |
| Intel AX210 Bluetooth                                 | 5        | 6.25%   |
| TP-Link UB500 Adapter                                 | 4        | 5%      |
| MediaTek Wireless_Device                              | 4        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                      | 4        | 5%      |
| Realtek Bluetooth Radio                               | 3        | 3.75%   |
| Intel Bluetooth wireless interface                    | 3        | 3.75%   |
| Intel Bluetooth Device                                | 3        | 3.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 3.75%   |
| Realtek 802.11ac WLAN Adapter                         | 2        | 2.5%    |
| Intel AX201 Bluetooth                                 | 2        | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 2.5%    |
| Apple Bluetooth Host Controller                       | 2        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.25%   |
| Realtek Bluetooth Radio                               | 1        | 1.25%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.25%   |
| Intel AX211 Bluetooth                                 | 1        | 1.25%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.25%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.25%   |
| IMC Networks Bluetooth Device                         | 1        | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.25%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth       | 1        | 1.25%   |
| ASUS BCM20702A0                                       | 1        | 1.25%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 114      | 44.53%  |
| Intel                    | 57       | 22.27%  |
| Nvidia                   | 35       | 13.67%  |
| Logitech                 | 9        | 3.52%   |
| C-Media Electronics      | 5        | 1.95%   |
| SteelSeries ApS          | 4        | 1.56%   |
| Valve Software           | 3        | 1.17%   |
| Razer USA                | 3        | 1.17%   |
| Medeli Electronics       | 3        | 1.17%   |
| Kingston Technology      | 3        | 1.17%   |
| JMTek                    | 3        | 1.17%   |
| Corsair                  | 3        | 1.17%   |
| Realtek Semiconductor    | 2        | 0.78%   |
| Hewlett-Packard          | 2        | 0.78%   |
| Focusrite-Novation       | 2        | 0.78%   |
| Apple                    | 2        | 0.78%   |
| Tenx Technology          | 1        | 0.39%   |
| Sony                     | 1        | 0.39%   |
| Quanta                   | 1        | 0.39%   |
| Micro Star International | 1        | 0.39%   |
| Creative Labs            | 1        | 0.39%   |
| ASUSTek Computer         | 1        | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 30       | 8.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 28       | 8.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 27       | 7.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 25       | 7.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 5.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 16       | 4.72%   |
| AMD Navi 10 HDMI Audio                                                     | 14       | 4.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 2.36%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 2.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 1.18%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4        | 1.18%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4        | 1.18%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 3        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.88%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 3        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.59%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.59%   |
| Medeli Electronics JOUNIVO JV906                                           | 2        | 0.59%   |
| Logitech G733 Gaming Headset                                               | 2        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| G.Skill | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 1        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 4        | 23.53%  |
| Valve Software                | 3        | 17.65%  |
| Tobii Technology AB           | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Realtek Semiconductor         | 1        | 5.88%   |
| Razer USA                     | 1        | 5.88%   |
| Quanta                        | 1        | 5.88%   |
| Microdia                      | 1        | 5.88%   |
| Magic Control Technology      | 1        | 5.88%   |
| IPEVO                         | 1        | 5.88%   |
| Generalplus Technology        | 1        | 5.88%   |
| Apple                         | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Valve Software 3D Camera        | 3        | 17.65%  |
| Tobii AB EyeChip                | 1        | 5.88%   |
| Sunplus USB 2.0 Camera          | 1        | 5.88%   |
| Realtek USB Camera              | 1        | 5.88%   |
| Razer USA Razer Kiyo Pro        | 1        | 5.88%   |
| Quanta HD Camera                | 1        | 5.88%   |
| Microdia Webcam Vitade AF       | 1        | 5.88%   |
| Magic Control j5 WebCam JVCU100 | 1        | 5.88%   |
| Logitech HD Webcam C615         | 1        | 5.88%   |
| Logitech HD Webcam C525         | 1        | 5.88%   |
| Logitech HD Pro Webcam C920     | 1        | 5.88%   |
| Logitech B525 HD Webcam         | 1        | 5.88%   |
| IPEVO V4K                       | 1        | 5.88%   |
| Generalplus CAMERA - UVC        | 1        | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 107      | 76.98%  |
| 1     | 25       | 17.99%  |
| 2     | 6        | 4.32%   |
| 4     | 1        | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 23       | 57.5%   |
| Graphics card            | 5        | 12.5%   |
| Unassigned class         | 4        | 10%     |
| Net/ethernet             | 2        | 5%      |
| Multimedia controller    | 2        | 5%      |
| Sound                    | 1        | 2.5%    |
| Fingerprint reader       | 1        | 2.5%    |
| Communication controller | 1        | 2.5%    |
| Bluetooth                | 1        | 2.5%    |

