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

Total: 124

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| SteamOS 3.4                  | 53       | 51.96%  |
| SteamOS 3.3                  | 24       | 23.53%  |
| SteamOS 4                    | 8        | 7.84%   |
| SteamOS 3.2 (steamdeck-main) | 7        | 6.86%   |
| SteamOS                      | 6        | 5.88%   |
| SteamOS Snapshot             | 3        | 2.94%   |
| SteamOS 3.2                  | 1        | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 99       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 42       | 42%     |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 11%     |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 10%     |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 7%      |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 6        | 6%      |
| 6.1.21-valve1-1-neptune-61                         | 3        | 3%      |
| 5.13.0-valve36-1-neptune                           | 3        | 3%      |
| 6.3.7-zen1-1-zen                                   | 2        | 2%      |
| 6.1.21-valve1-3-neptune-61                         | 2        | 2%      |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 2%      |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 2        | 2%      |
| 6.4.12-zen1-1-zen                                  | 1        | 1%      |
| 6.3.9-arch1-1                                      | 1        | 1%      |
| 6.1.29-valve4-1-neptune-61                         | 1        | 1%      |
| 6.1.12-valve2-1-neptune-61                         | 1        | 1%      |
| 5.15.93-1-lts                                      | 1        | 1%      |
| 5.15.79-1-lts                                      | 1        | 1%      |
| 5.15.60-1-lts                                      | 1        | 1%      |
| 5.13.0-valve24-1-neptune                           | 1        | 1%      |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 1%      |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 1%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 80       | 80%     |
| 5.18.1  | 6        | 6%      |
| 6.1.21  | 5        | 5%      |
| 6.3.7   | 2        | 2%      |
| 6.4.12  | 1        | 1%      |
| 6.3.9   | 1        | 1%      |
| 6.1.29  | 1        | 1%      |
| 6.1.12  | 1        | 1%      |
| 5.15.93 | 1        | 1%      |
| 5.15.79 | 1        | 1%      |
| 5.15.60 | 1        | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 80       | 80%     |
| 6.1     | 7        | 7%      |
| 5.18    | 6        | 6%      |
| 6.3     | 3        | 3%      |
| 5.15    | 3        | 3%      |
| 6.4     | 1        | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 99       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 99       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 99       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 99       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 87       | 87%     |
| fr_FR | 3        | 3%      |
| ru_RU | 1        | 1%      |
| pt_PT | 1        | 1%      |
| pt_BR | 1        | 1%      |
| n_US  | 1        | 1%      |
| en_IE | 1        | 1%      |
| en_GB | 1        | 1%      |
| en_DE | 1        | 1%      |
| de_DE | 1        | 1%      |
| de_AT | 1        | 1%      |
| C     | 1        | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 99       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 93       | 93.94%  |
| Tmpfs | 6        | 6.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 99       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 31       | 31.31%  |
| Gigabyte Technology                  | 26       | 26.26%  |
| MSI                                  | 12       | 12.12%  |
| ASRock                               | 9        | 9.09%   |
| Dell                                 | 8        | 8.08%   |
| Hewlett-Packard                      | 7        | 7.07%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.01%   |
| MAXSUN                               | 1        | 1.01%   |
| Biostar                              | 1        | 1.01%   |
| Apple                                | 1        | 1.01%   |
| Alienware                            | 1        | 1.01%   |
| Acer                                 | 1        | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 6        | 6.06%   |
| Gigabyte B450 AORUS M                      | 4        | 4.04%   |
| ASUS ROG STRIX B550-F GAMING               | 3        | 3.03%   |
| Gigabyte B550 GAMING X V2                  | 2        | 2.02%   |
| Dell OptiPlex 9010                         | 2        | 2.02%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.01%   |
| MSI MS-7D73                                | 1        | 1.01%   |
| MSI MS-7C89                                | 1        | 1.01%   |
| MSI MS-7C37                                | 1        | 1.01%   |
| MSI MS-7C02                                | 1        | 1.01%   |
| MSI MS-7B89                                | 1        | 1.01%   |
| MSI MS-7B79                                | 1        | 1.01%   |
| MSI MS-7B09                                | 1        | 1.01%   |
| MSI MS-7A33                                | 1        | 1.01%   |
| MSI MS-7817                                | 1        | 1.01%   |
| MSI MS-7693                                | 1        | 1.01%   |
| MSI MPG H510 Trident 3 (MS-B935)           | 1        | 1.01%   |
| MSI H310 Gaming Trident3 (MS-B920)         | 1        | 1.01%   |
| MAXSUN MS-H81IL TR M.2                     | 1        | 1.01%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx  | 1        | 1.01%   |
| HP ProDesk 600 G4 MT                       | 1        | 1.01%   |
| HP ProDesk 405 G4 Desktop Mini             | 1        | 1.01%   |
| HP Pavilion Gaming Desktop TG01-2xxx       | 1        | 1.01%   |
| HP Pavilion Gaming Desktop 690-00xx        | 1        | 1.01%   |
| HP EliteDesk 705 G5 SFF                    | 1        | 1.01%   |
| HP EliteDesk 705 G4 DM 65W (TAA)           | 1        | 1.01%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.01%   |
| Gigabyte Z170X-Gaming 6                    | 1        | 1.01%   |
| Gigabyte X570 UD                           | 1        | 1.01%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.01%   |
| Gigabyte X570 GAMING X                     | 1        | 1.01%   |
| Gigabyte MBB-670016                        | 1        | 1.01%   |
| Gigabyte H77N-WIFI                         | 1        | 1.01%   |
| Gigabyte H310M S2V 2.0                     | 1        | 1.01%   |
| Gigabyte H170N-WIFI                        | 1        | 1.01%   |
| Gigabyte F2A68HM-H                         | 1        | 1.01%   |
| Gigabyte B85M-D3H                          | 1        | 1.01%   |
| Gigabyte B560M DS3H V2                     | 1        | 1.01%   |
| Gigabyte B560M AORUS PRO                   | 1        | 1.01%   |
| Gigabyte B550M DS3H                        | 1        | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 9        | 9.09%   |
| Dell OptiPlex                              | 6        | 6.06%   |
| ASUS ROG                                   | 6        | 6.06%   |
| ASUS All                                   | 6        | 6.06%   |
| Gigabyte B450                              | 4        | 4.04%   |
| Gigabyte X570                              | 3        | 3.03%   |
| ASUS TUF                                   | 3        | 3.03%   |
| HP ProDesk                                 | 2        | 2.02%   |
| HP Pavilion                                | 2        | 2.02%   |
| HP EliteDesk                               | 2        | 2.02%   |
| Gigabyte B560M                             | 2        | 2.02%   |
| Gigabyte B550                              | 2        | 2.02%   |
| Gigabyte B450M                             | 2        | 2.02%   |
| Dell Precision                             | 2        | 2.02%   |
| ASRock B550                                | 2        | 2.02%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.01%   |
| MSI MS-7D73                                | 1        | 1.01%   |
| MSI MS-7C89                                | 1        | 1.01%   |
| MSI MS-7C37                                | 1        | 1.01%   |
| MSI MS-7C02                                | 1        | 1.01%   |
| MSI MS-7B89                                | 1        | 1.01%   |
| MSI MS-7B79                                | 1        | 1.01%   |
| MSI MS-7B09                                | 1        | 1.01%   |
| MSI MS-7A33                                | 1        | 1.01%   |
| MSI MS-7817                                | 1        | 1.01%   |
| MSI MS-7693                                | 1        | 1.01%   |
| MSI MPG                                    | 1        | 1.01%   |
| MSI H310                                   | 1        | 1.01%   |
| MAXSUN MS-H81IL                            | 1        | 1.01%   |
| HP Victus                                  | 1        | 1.01%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.01%   |
| Gigabyte Z170X-Gaming                      | 1        | 1.01%   |
| Gigabyte MBB-670016                        | 1        | 1.01%   |
| Gigabyte H77N-WIFI                         | 1        | 1.01%   |
| Gigabyte H310M                             | 1        | 1.01%   |
| Gigabyte H170N-WIFI                        | 1        | 1.01%   |
| Gigabyte F2A68HM-H                         | 1        | 1.01%   |
| Gigabyte B85M-D3H                          | 1        | 1.01%   |
| Gigabyte B550M                             | 1        | 1.01%   |
| Gigabyte AX370-Gaming                      | 1        | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 20       | 20.2%   |
| 2018 | 16       | 16.16%  |
| 2019 | 12       | 12.12%  |
| 2021 | 10       | 10.1%   |
| 2017 | 9        | 9.09%   |
| 2014 | 8        | 8.08%   |
| 2022 | 6        | 6.06%   |
| 2013 | 6        | 6.06%   |
| 2016 | 4        | 4.04%   |
| 2012 | 4        | 4.04%   |
| 2015 | 2        | 2.02%   |
| 2011 | 2        | 2.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 99       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 99       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 99       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 45%     |
| 32.01-64.0  | 25       | 25%     |
| 8.01-16.0   | 14       | 14%     |
| 4.01-8.0    | 7        | 7%      |
| 24.01-32.0  | 5        | 5%      |
| 64.01-256.0 | 4        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 42       | 42%     |
| 3.01-4.0  | 28       | 28%     |
| 4.01-8.0  | 18       | 18%     |
| 1.01-2.0  | 8        | 8%      |
| 8.01-16.0 | 4        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 32.67%  |
| 2      | 27       | 26.73%  |
| 3      | 22       | 21.78%  |
| 4      | 12       | 11.88%  |
| 5      | 4        | 3.96%   |
| 11     | 1        | 0.99%   |
| 7      | 1        | 0.99%   |
| 6      | 1        | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 87.88%  |
| Yes       | 12       | 12.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 99       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 64.65%  |
| No        | 35       | 35.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 52%     |
| No        | 48       | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 42       | 42%     |
| UK           | 8        | 8%      |
| France       | 6        | 6%      |
| Brazil       | 5        | 5%      |
| Australia    | 5        | 5%      |
| Ireland      | 3        | 3%      |
| Germany      | 3        | 3%      |
| Spain        | 2        | 2%      |
| Poland       | 2        | 2%      |
| Philippines  | 2        | 2%      |
| Canada       | 2        | 2%      |
| Vietnam      | 1        | 1%      |
| Uzbekistan   | 1        | 1%      |
| Turkey       | 1        | 1%      |
| Thailand     | 1        | 1%      |
| South Africa | 1        | 1%      |
| Romania      | 1        | 1%      |
| Portugal     | 1        | 1%      |
| Peru         | 1        | 1%      |
| Oman         | 1        | 1%      |
| Malaysia     | 1        | 1%      |
| Latvia       | 1        | 1%      |
| Italy        | 1        | 1%      |
| Israel       | 1        | 1%      |
| Iceland      | 1        | 1%      |
| Hong Kong    | 1        | 1%      |
| El Salvador  | 1        | 1%      |
| Denmark      | 1        | 1%      |
| Cambodia     | 1        | 1%      |
| Austria      | 1        | 1%      |
| Argentina    | 1        | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 2%      |
| Sao Paulo              | 2        | 2%      |
| San Jose               | 2        | 2%      |
| Gujan-Mestras          | 2        | 2%      |
| Zevio                  | 1        | 1%      |
| West Bloomfield        | 1        | 1%      |
| Walsall                | 1        | 1%      |
| Ville Platte           | 1        | 1%      |
| Vilas                  | 1        | 1%      |
| Tuam                   | 1        | 1%      |
| Toronto                | 1        | 1%      |
| Tashkent               | 1        | 1%      |
| Targoviste             | 1        | 1%      |
| Sterling Heights       | 1        | 1%      |
| Sparta                 | 1        | 1%      |
| Skarzysko-Kamienna     | 1        | 1%      |
| Siloam Springs         | 1        | 1%      |
| Sassenberg             | 1        | 1%      |
| Sant Quirze del Valles | 1        | 1%      |
| San Salvador           | 1        | 1%      |
| Salford                | 1        | 1%      |
| Salem                  | 1        | 1%      |
| Riga                   | 1        | 1%      |
| Reykjavik              | 1        | 1%      |
| Quezon City            | 1        | 1%      |
| Puchberg am Schneeberg | 1        | 1%      |
| Porto Alegre           | 1        | 1%      |
| Portland               | 1        | 1%      |
| Phnom Penh             | 1        | 1%      |
| Petah Tikva            | 1        | 1%      |
| Perth                  | 1        | 1%      |
| Peoria                 | 1        | 1%      |
| Paris                  | 1        | 1%      |
| Ostrów Wielkopolski   | 1        | 1%      |
| Oklahoma City          | 1        | 1%      |
| Ocean Springs          | 1        | 1%      |
| Norwich                | 1        | 1%      |
| Noble Park             | 1        | 1%      |
| Newport                | 1        | 1%      |
| Newcastle-under-Lyme   | 1        | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 31       | 38     | 15.35%  |
| Samsung Electronics         | 27       | 52     | 13.37%  |
| WDC                         | 23       | 29     | 11.39%  |
| Toshiba                     | 15       | 17     | 7.43%   |
| Sandisk                     | 15       | 17     | 7.43%   |
| Kingston                    | 15       | 18     | 7.43%   |
| Crucial                     | 15       | 19     | 7.43%   |
| Micron/Crucial Technology   | 6        | 6      | 2.97%   |
| A-DATA Technology           | 5        | 5      | 2.48%   |
| PNY                         | 4        | 5      | 1.98%   |
| Phison Electronics          | 4        | 6      | 1.98%   |
| Phison                      | 4        | 5      | 1.98%   |
| Unknown                     | 4        | 5      | 1.98%   |
| Realtek Semiconductor       | 3        | 3      | 1.49%   |
| China                       | 3        | 6      | 1.49%   |
| SK hynix                    | 2        | 2      | 0.99%   |
| Realtek                     | 2        | 2      | 0.99%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.99%   |
| Kingston Technology Company | 2        | 2      | 0.99%   |
| Intel                       | 2        | 3      | 0.99%   |
| Hitachi                     | 2        | 2      | 0.99%   |
| Unknown                     | 1        | 1      | 0.5%    |
| Union Memory (Shenzhen)     | 1        | 1      | 0.5%    |
| T-FORCE                     | 1        | 1      | 0.5%    |
| SPCC                        | 1        | 3      | 0.5%    |
| Silicon Motion              | 1        | 1      | 0.5%    |
| Ramsta                      | 1        | 1      | 0.5%    |
| Mushkin                     | 1        | 1      | 0.5%    |
| KIOXIA                      | 1        | 1      | 0.5%    |
| KingFast                    | 1        | 1      | 0.5%    |
| Intenso                     | 1        | 1      | 0.5%    |
| HS-SSD-C100                 | 1        | 1      | 0.5%    |
| Gigastone                   | 1        | 1      | 0.5%    |
| GALAX                       | 1        | 1      | 0.5%    |
| Apple                       | 1        | 1      | 0.5%    |
| ADATA Technology            | 1        | 2      | 0.5%    |
| 2.5                         | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 5        | 2.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 5        | 2.18%   |
| Toshiba DT01ACA100 1TB                              | 4        | 1.75%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.75%   |
| Unknown                                             | 4        | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 1.31%   |
| Samsung NVMe SSD Drive 1TB                          | 3        | 1.31%   |
| Crucial CT1000BX500SSD1 1TB                         | 3        | 1.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 0.87%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2        | 0.87%   |
| Toshiba MQ01ABD100 1TB                              | 2        | 0.87%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 0.87%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2        | 0.87%   |
| SanDisk NVMe SSD Drive 500GB                        | 2        | 0.87%   |
| Samsung SSD 980 1TB                                 | 2        | 0.87%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 2        | 0.87%   |
| Samsung SSD 840 EVO 250GB                           | 2        | 0.87%   |
| Realtek NVMe SSD Drive 256GB                        | 2        | 0.87%   |
| PNY CS900 120GB SSD                                 | 2        | 0.87%   |
| Phison E12 NVMe Controller 2TB                      | 2        | 0.87%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2        | 0.87%   |
| Micron/Crucial CT1000P1SSD8 1TB                     | 2        | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB  | 2        | 0.87%   |
| Kingston SV300S37A120G 120GB SSD                    | 2        | 0.87%   |
| Kingston SH103S3120G 120GB SSD                      | 2        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                     | 2        | 0.87%   |
| Crucial CT500MX500SSD1 500GB                        | 2        | 0.87%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 0.87%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 0.87%   |
| A-DATA SU650 240GB SSD                              | 2        | 0.87%   |
| A-DATA SU630 240GB SSD                              | 2        | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.44%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                      | 1        | 0.44%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1        | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.44%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.44%   |
| WDC WDBNCE2500PNC 250GB SSD                         | 1        | 0.44%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.44%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 37     | 50%     |
| WDC                 | 14       | 18     | 23.33%  |
| Toshiba             | 13       | 15     | 21.67%  |
| Hitachi             | 2        | 2      | 3.33%   |
| Samsung Electronics | 1        | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 29     | 22.89%  |
| Crucial             | 15       | 19     | 18.07%  |
| Kingston            | 11       | 13     | 13.25%  |
| WDC                 | 10       | 11     | 12.05%  |
| SanDisk             | 9        | 10     | 10.84%  |
| A-DATA Technology   | 5        | 5      | 6.02%   |
| PNY                 | 4        | 5      | 4.82%   |
| China               | 3        | 6      | 3.61%   |
| SPCC                | 1        | 3      | 1.2%    |
| Ramsta              | 1        | 1      | 1.2%    |
| Mushkin             | 1        | 1      | 1.2%    |
| Intenso             | 1        | 1      | 1.2%    |
| Intel               | 1        | 1      | 1.2%    |
| Gigastone           | 1        | 1      | 1.2%    |
| 2.5                 | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 62       | 107    | 35.63%  |
| NVMe    | 56       | 74     | 32.18%  |
| HDD     | 49       | 73     | 28.16%  |
| Unknown | 7        | 9      | 4.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 84       | 181    | 57.53%  |
| NVMe | 56       | 72     | 38.36%  |
| SAS  | 6        | 10     | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 56       | 89     | 45.53%  |
| 0.51-1.0   | 41       | 54     | 33.33%  |
| 1.01-2.0   | 11       | 19     | 8.94%   |
| 3.01-4.0   | 6        | 7      | 4.88%   |
| 4.01-10.0  | 5        | 5      | 4.07%   |
| 2.01-3.0   | 4        | 6      | 3.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 28       | 28.28%  |
| 501-1000       | 24       | 24.24%  |
| 251-500        | 18       | 18.18%  |
| 1001-2000      | 14       | 14.14%  |
| More than 3000 | 9        | 9.09%   |
| Unknown        | 3        | 3.03%   |
| 2001-3000      | 2        | 2.02%   |
| 51-100         | 1        | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 34       | 33.66%  |
| 51-100         | 20       | 19.8%   |
| 101-250        | 14       | 13.86%  |
| 21-50          | 10       | 9.9%    |
| 501-1000       | 9        | 8.91%   |
| 251-500        | 5        | 4.95%   |
| Unknown        | 3        | 2.97%   |
| More than 3000 | 2        | 1.98%   |
| 2001-3000      | 2        | 1.98%   |
| 1001-2000      | 2        | 1.98%   |

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
| Detected | 100      | 263    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 50       | 31.45%  |
| Intel                        | 47       | 29.56%  |
| Samsung Electronics          | 16       | 10.06%  |
| Phison Electronics           | 8        | 5.03%   |
| SanDisk                      | 7        | 4.4%    |
| Micron/Crucial Technology    | 6        | 3.77%   |
| Kingston Technology Company  | 6        | 3.77%   |
| Realtek Semiconductor        | 3        | 1.89%   |
| Toshiba America Info Systems | 2        | 1.26%   |
| SK hynix                     | 2        | 1.26%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.26%   |
| ASMedia Technology           | 2        | 1.26%   |
| Union Memory (Shenzhen)      | 1        | 0.63%   |
| Silicon Motion               | 1        | 0.63%   |
| Seagate Technology           | 1        | 0.63%   |
| Marvell Technology Group     | 1        | 0.63%   |
| KIOXIA                       | 1        | 0.63%   |
| INNOGRIT                     | 1        | 0.63%   |
| Apple                        | 1        | 0.63%   |
| ADATA Technology             | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32       | 16.67%  |
| AMD 400 Series Chipset SATA Controller                                         | 14       | 7.29%   |
| AMD 500 Series Chipset SATA Controller                                         | 12       | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 4.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5        | 2.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 2.6%    |
| AMD FCH SATA Controller D                                                      | 5        | 2.6%    |
| Phison E12 NVMe Controller                                                     | 4        | 2.08%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 2.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 2.08%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 2.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.56%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2        | 1.04%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.04%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2        | 1.04%   |
| Phison Electronics Non-Volatile memory controller                              | 2        | 1.04%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 2        | 1.04%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 1.04%   |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 1.04%   |
| Kingston Company NV1 NVMe SSD                                                  | 2        | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 1.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.04%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                          | 1        | 0.52%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.52%   |
| SK hynix BC511 NVMe SSD                                                        | 1        | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.52%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1        | 0.52%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.52%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1        | 0.52%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 91       | 57.96%  |
| NVMe | 56       | 35.67%  |
| RAID | 7        | 4.46%   |
| IDE  | 2        | 1.27%   |
| SAS  | 1        | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 52       | 52.53%  |
| Intel  | 47       | 47.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics | 6        | 6.06%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 4.04%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4        | 4.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 3        | 3.03%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 3        | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 3        | 3.03%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 3.03%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 2.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 2.02%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 2.02%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 2        | 2.02%   |
| Intel Core i3-9100F CPU @ 3.60GHz      | 2        | 2.02%   |
| Intel 12th Gen Core i3-12100F          | 2        | 2.02%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 2        | 2.02%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 2.02%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 2        | 2.02%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 2.02%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 2.02%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 2.02%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 2.02%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 2        | 2.02%   |
| Intel Xeon W-3223 CPU @ 3.50GHz        | 1        | 1.01%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1        | 1.01%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 1        | 1.01%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz    | 1        | 1.01%   |
| Intel Xeon CPU E31220 @ 3.10GHz        | 1        | 1.01%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 1        | 1.01%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.01%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 1.01%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.01%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 1.01%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.01%   |
| Intel Core i5-8500T CPU @ 2.10GHz      | 1        | 1.01%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 1        | 1.01%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1        | 1.01%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 1        | 1.01%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 1.01%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.01%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 22       | 22.22%  |
| Intel Core i5          | 17       | 17.17%  |
| Intel Core i7          | 15       | 15.15%  |
| AMD Ryzen 9            | 10       | 10.1%   |
| AMD Ryzen 7            | 10       | 10.1%   |
| Other                  | 6        | 6.06%   |
| Intel Xeon             | 5        | 5.05%   |
| Intel Core i3          | 3        | 3.03%   |
| AMD Ryzen 5 PRO        | 3        | 3.03%   |
| AMD FX                 | 2        | 2.02%   |
| Intel Celeron          | 1        | 1.01%   |
| AMD Ryzen Threadripper | 1        | 1.01%   |
| AMD Ryzen 7 PRO        | 1        | 1.01%   |
| AMD Ryzen 3            | 1        | 1.01%   |
| AMD Athlon X4          | 1        | 1.01%   |
| AMD Athlon             | 1        | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 35       | 35.35%  |
| 6      | 32       | 32.32%  |
| 8      | 16       | 16.16%  |
| 12     | 10       | 10.1%   |
| 2      | 4        | 4.04%   |
| 16     | 1        | 1.01%   |
| 3      | 1        | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 98.99%  |
| 2      | 1        | 1.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 79.8%   |
| 1      | 20       | 20.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 99       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 99       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 16       | 16.16%  |
| Zen+        | 13       | 13.13%  |
| KabyLake    | 12       | 12.12%  |
| Haswell     | 12       | 12.12%  |
| Zen 2       | 11       | 11.11%  |
| Unknown     | 8        | 8.08%   |
| Zen         | 7        | 7.07%   |
| Skylake     | 5        | 5.05%   |
| IvyBridge   | 5        | 5.05%   |
| SandyBridge | 4        | 4.04%   |
| CometLake   | 3        | 3.03%   |
| Piledriver  | 2        | 2.02%   |
| Steamroller | 1        | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 70       | 62.5%   |
| Nvidia | 26       | 23.21%  |
| Intel  | 16       | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 14.53%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 6.84%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 6        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 4.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 4.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 4.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 4.27%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 4        | 3.42%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 3.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.56%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 2.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.71%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 1.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.71%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.71%   |
| Intel HD Graphics 530                                                       | 2        | 1.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.71%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.85%   |
| Intel HD Graphics 630                                                       | 1        | 0.85%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 0.85%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 0.85%   |
| AMD Raphael                                                                 | 1        | 0.85%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 0.85%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 61       | 60.4%   |
| 1 x Nvidia     | 23       | 22.77%  |
| 2 x AMD        | 5        | 4.95%   |
| 1 x Intel      | 5        | 4.95%   |
| Intel + AMD    | 3        | 2.97%   |
| Intel + Nvidia | 2        | 1.98%   |
| AMD + Nvidia   | 2        | 1.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 78.79%  |
| Proprietary | 21       | 21.21%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 79%     |
| 3.01-4.0   | 7        | 7%      |
| 7.01-8.0   | 6        | 6%      |
| 5.01-6.0   | 3        | 3%      |
| 8.01-16.0  | 2        | 2%      |
| 2.01-3.0   | 1        | 1%      |
| 16.01-24.0 | 1        | 1%      |
| 1.01-2.0   | 1        | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 14       | 14.29%  |
| Samsung Electronics  | 13       | 13.27%  |
| Acer                 | 9        | 9.18%   |
| AOC                  | 6        | 6.12%   |
| Hewlett-Packard      | 5        | 5.1%    |
| Dell                 | 5        | 5.1%    |
| ASUSTek Computer     | 4        | 4.08%   |
| Ancor Communications | 4        | 4.08%   |
| ViewSonic            | 3        | 3.06%   |
| Sony                 | 3        | 3.06%   |
| Pixio                | 3        | 3.06%   |
| Philips              | 3        | 3.06%   |
| Toshiba              | 2        | 2.04%   |
| Sceptre Tech         | 2        | 2.04%   |
| ONN                  | 2        | 2.04%   |
| MSI                  | 2        | 2.04%   |
| Hitachi              | 2        | 2.04%   |
| ___                  | 1        | 1.02%   |
| WIT                  | 1        | 1.02%   |
| Wacom                | 1        | 1.02%   |
| Valve                | 1        | 1.02%   |
| Unknown (XXX)        | 1        | 1.02%   |
| Unknown              | 1        | 1.02%   |
| Sun                  | 1        | 1.02%   |
| Roku                 | 1        | 1.02%   |
| Insignia             | 1        | 1.02%   |
| Huion                | 1        | 1.02%   |
| HJW                  | 1        | 1.02%   |
| HannStar             | 1        | 1.02%   |
| Gigabyte Technology  | 1        | 1.02%   |
| DZX                  | 1        | 1.02%   |
| BenQ                 | 1        | 1.02%   |
| AOpen                | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 3%      |
| Pixio U27I4K WAM2700 3840x2160 600x330mm 27.0-inch                      | 2        | 2%      |
| Hitachi Hisense HEC0030 1920x1080 580x330mm 26.3-inch                   | 2        | 2%      |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 2%      |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                         | 2        | 2%      |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 1%      |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 1%      |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 1%      |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 1%      |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch             | 1        | 1%      |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 1%      |
| Valve Index HMD VLV91A8 2880x1600                                       | 1        | 1%      |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1%      |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 1%      |
| Toshiba TV TSB0206 1920x1080                                            | 1        | 1%      |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 1%      |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 1%      |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1%      |
| Sony TV *00 SNY3F05 3840x2160 1439x809mm 65.0-inch                      | 1        | 1%      |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 1%      |
| Sceptre Tech H50 SPT13C0 1920x1080 575x323mm 26.0-inch                  | 1        | 1%      |
| Sceptre Tech E22 SPT08D5 1920x1080 470x300mm 22.0-inch                  | 1        | 1%      |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 1%      |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 1%      |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1%      |
| Samsung Electronics LS27AG30x SAM717B 1920x1080 597x336mm 27.0-inch     | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM7269 3840x2160 700x390mm 31.5-inch   | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1420x800mm 64.2-inch  | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 1%      |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1190x340mm 48.7-inch     | 1        | 1%      |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 1%      |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1        | 1%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1%      |
| Roku WR32FE2009 RKU0B01 1920x1080 698x392mm 31.5-inch                   | 1        | 1%      |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 1%      |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1%      |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 1%      |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 46.81%  |
| 3840x2160 (4K)     | 26       | 27.66%  |
| 2560x1440 (QHD)    | 10       | 10.64%  |
| 2560x1080          | 3        | 3.19%   |
| 1920x1200 (WUXGA)  | 2        | 2.13%   |
| 3840x1080          | 1        | 1.06%   |
| 1680x1050 (WSXGA+) | 1        | 1.06%   |
| 1600x900 (HD+)     | 1        | 1.06%   |
| 1440x900 (WXGA+)   | 1        | 1.06%   |
| 1400x1050          | 1        | 1.06%   |
| 1366x768 (WXGA)    | 1        | 1.06%   |
| 1360x768           | 1        | 1.06%   |
| 1024x768 (XGA)     | 1        | 1.06%   |
| Unknown            | 1        | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 19.59%  |
| 31      | 15       | 15.46%  |
| 24      | 14       | 14.43%  |
| 23      | 14       | 14.43%  |
| 21      | 6        | 6.19%   |
| 84      | 5        | 5.15%   |
| 72      | 4        | 4.12%   |
| 15      | 3        | 3.09%   |
| 48      | 2        | 2.06%   |
| 34      | 2        | 2.06%   |
| Unknown | 2        | 2.06%   |
| 75      | 1        | 1.03%   |
| 74      | 1        | 1.03%   |
| 65      | 1        | 1.03%   |
| 57      | 1        | 1.03%   |
| 54      | 1        | 1.03%   |
| 47      | 1        | 1.03%   |
| 46      | 1        | 1.03%   |
| 32      | 1        | 1.03%   |
| 26      | 1        | 1.03%   |
| 20      | 1        | 1.03%   |
| 18      | 1        | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 42       | 45.16%  |
| 601-700     | 17       | 18.28%  |
| 1501-2000   | 11       | 11.83%  |
| 401-500     | 8        | 8.6%    |
| 1001-1500   | 7        | 7.53%   |
| 701-800     | 3        | 3.23%   |
| 301-350     | 3        | 3.23%   |
| Unknown     | 2        | 2.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 88.89%  |
| 16/10   | 5        | 5.56%   |
| 21/9    | 2        | 2.22%   |
| 4/3     | 1        | 1.11%   |
| 32/9    | 1        | 1.11%   |
| Unknown | 1        | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 28.87%  |
| 301-350        | 19       | 19.59%  |
| 351-500        | 18       | 18.56%  |
| More than 1000 | 15       | 15.46%  |
| 251-300        | 7        | 7.22%   |
| 501-1000       | 3        | 3.09%   |
| 101-110        | 2        | 2.06%   |
| Unknown        | 2        | 2.06%   |
| 151-200        | 1        | 1.03%   |
| 141-150        | 1        | 1.03%   |
| 91-100         | 1        | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 60       | 64.52%  |
| 101-120 | 15       | 16.13%  |
| 1-50    | 7        | 7.53%   |
| 121-160 | 7        | 7.53%   |
| 161-240 | 2        | 2.15%   |
| Unknown | 2        | 2.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 86%     |
| 2     | 14       | 14%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 62       | 38.75%  |
| Intel                         | 55       | 34.38%  |
| Broadcom                      | 8        | 5%      |
| TP-Link                       | 6        | 3.75%   |
| Microsoft                     | 6        | 3.75%   |
| Qualcomm Atheros              | 4        | 2.5%    |
| Samsung Electronics           | 2        | 1.25%   |
| Ralink Technology             | 2        | 1.25%   |
| OPPO Electronics              | 2        | 1.25%   |
| MediaTek                      | 2        | 1.25%   |
| D-Link                        | 2        | 1.25%   |
| ASUSTek Computer              | 2        | 1.25%   |
| OnePlus Technology (Shenzhen) | 1        | 0.63%   |
| Linksys                       | 1        | 0.63%   |
| Huawei Technologies           | 1        | 0.63%   |
| Google                        | 1        | 0.63%   |
| Broadcom Limited              | 1        | 0.63%   |
| Aquantia                      | 1        | 0.63%   |
| Apple                         | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 52       | 27.81%  |
| Intel Wi-Fi 6 AX200                                                                           | 11       | 5.88%   |
| Intel Ethernet Connection (2) I219-V                                                          | 9        | 4.81%   |
| Intel Ethernet Controller I225-V                                                              | 8        | 4.28%   |
| Intel I211 Gigabit Network Connection                                                         | 7        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 2.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 2.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 2.67%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 2.14%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 3        | 1.6%    |
| Intel Wireless 8260                                                                           | 3        | 1.6%    |
| Intel Wireless 7265                                                                           | 3        | 1.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.07%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2        | 1.07%   |
| Realtek 802.11ac NIC                                                                          | 2        | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.07%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 1.07%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.07%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.07%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.53%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.53%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.53%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.53%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.53%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.53%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 27       | 38.03%  |
| Realtek Semiconductor | 12       | 16.9%   |
| Broadcom              | 8        | 11.27%  |
| TP-Link               | 6        | 8.45%   |
| Microsoft             | 6        | 8.45%   |
| Ralink Technology     | 2        | 2.82%   |
| Qualcomm Atheros      | 2        | 2.82%   |
| MediaTek              | 2        | 2.82%   |
| D-Link                | 2        | 2.82%   |
| ASUSTek Computer      | 2        | 2.82%   |
| Linksys               | 1        | 1.41%   |
| Broadcom Limited      | 1        | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 11       | 15.49%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 7.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 7.04%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 3        | 4.23%   |
| Intel Wireless 8260                                                                           | 3        | 4.23%   |
| Intel Wireless 7265                                                                           | 3        | 4.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.82%   |
| Realtek 802.11ac NIC                                                                          | 2        | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.82%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 2.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.41%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 1.41%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.41%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.41%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.41%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1        | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.41%   |
| Linksys WUSB300N 802.11bgn Wireless Adapter [Marvell 88W8362+88W8060]                         | 1        | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.41%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.41%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 1        | 1.41%   |
| D-Link AirPlus G DWL-G122 Wireless Adapter(rev.B1) [Ralink RT2571]                            | 1        | 1.41%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.41%   |
| Broadcom Network controller                                                                   | 1        | 1.41%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                    | 1        | 1.41%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 1.41%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 61       | 53.98%  |
| Intel                         | 41       | 36.28%  |
| Qualcomm Atheros              | 3        | 2.65%   |
| Samsung Electronics           | 2        | 1.77%   |
| OPPO Electronics              | 2        | 1.77%   |
| OnePlus Technology (Shenzhen) | 1        | 0.88%   |
| Huawei Technologies           | 1        | 0.88%   |
| Google                        | 1        | 0.88%   |
| Aquantia                      | 1        | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 45.22%  |
| Intel Ethernet Connection (2) I219-V                              | 9        | 7.83%   |
| Intel Ethernet Controller I225-V                                  | 8        | 6.96%   |
| Intel I211 Gigabit Network Connection                             | 7        | 6.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 3.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.74%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.87%   |
| OPPO KALAMA-MTP_CID:0437_SN:7EF55BBA                              | 1        | 0.87%   |
| OPPO 8                                                            | 1        | 0.87%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.87%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.87%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.87%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.87%   |
| Huawei JKM-LX1                                                    | 1        | 0.87%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.87%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 60.37%  |
| WiFi     | 64       | 39.02%  |
| Modem    | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 80       | 78.43%  |
| WiFi     | 22       | 21.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 53.54%  |
| 2     | 39       | 39.39%  |
| 3     | 7        | 7.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 65.66%  |
| Yes  | 34       | 34.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 45.45%  |
| Cambridge Silicon Radio         | 9        | 16.36%  |
| ASUSTek Computer                | 5        | 9.09%   |
| Realtek Semiconductor           | 4        | 7.27%   |
| MediaTek                        | 2        | 3.64%   |
| Broadcom                        | 2        | 3.64%   |
| Apple                           | 2        | 3.64%   |
| TP-Link                         | 1        | 1.82%   |
| Realtek                         | 1        | 1.82%   |
| Qualcomm Atheros Communications | 1        | 1.82%   |
| Integrated System Solution      | 1        | 1.82%   |
| IMC Networks                    | 1        | 1.82%   |
| Foxconn / Hon Hai               | 1        | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 10       | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 9        | 16.36%  |
| Intel Bluetooth wireless interface                    | 6        | 10.91%  |
| Intel AX210 Bluetooth                                 | 4        | 7.27%   |
| Realtek Bluetooth Radio                               | 3        | 5.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 5.45%   |
| MediaTek Wireless_Device                              | 2        | 3.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 3.64%   |
| Apple Bluetooth Host Controller                       | 2        | 3.64%   |
| TP-Link UB5A Adapter                                  | 1        | 1.82%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.82%   |
| Realtek Bluetooth Radio                               | 1        | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.82%   |
| Intel Bluetooth Device                                | 1        | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.82%   |
| Intel AX201 Bluetooth                                 | 1        | 1.82%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.82%   |
| IMC Networks Bluetooth Device                         | 1        | 1.82%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth       | 1        | 1.82%   |
| ASUS BCM20702A0                                       | 1        | 1.82%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 80       | 42.78%  |
| Intel                    | 47       | 25.13%  |
| Nvidia                   | 26       | 13.9%   |
| Logitech                 | 7        | 3.74%   |
| SteelSeries ApS          | 4        | 2.14%   |
| C-Media Electronics      | 4        | 2.14%   |
| Valve Software           | 2        | 1.07%   |
| Medeli Electronics       | 2        | 1.07%   |
| Kingston Technology      | 2        | 1.07%   |
| JMTek                    | 2        | 1.07%   |
| Corsair                  | 2        | 1.07%   |
| Apple                    | 2        | 1.07%   |
| Tenx Technology          | 1        | 0.53%   |
| Realtek Semiconductor    | 1        | 0.53%   |
| Razer USA                | 1        | 0.53%   |
| Quanta                   | 1        | 0.53%   |
| Micro Star International | 1        | 0.53%   |
| Focusrite-Novation       | 1        | 0.53%   |
| Creative Labs            | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22       | 9.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 7.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 7.47%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16       | 6.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 5.81%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 4.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 3.32%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 1.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.24%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.24%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.24%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.24%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.24%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 2        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.83%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.83%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.83%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.83%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 0.83%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.41%   |
| SteelSeries ApS SteelSeries SC2 USB Headset                                | 1        | 0.41%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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
| Logitech                      | 4        | 28.57%  |
| Valve Software                | 2        | 14.29%  |
| Tobii Technology AB           | 1        | 7.14%   |
| Sunplus Innovation Technology | 1        | 7.14%   |
| Quanta                        | 1        | 7.14%   |
| Microdia                      | 1        | 7.14%   |
| Magic Control Technology      | 1        | 7.14%   |
| IPEVO                         | 1        | 7.14%   |
| Generalplus Technology        | 1        | 7.14%   |
| Apple                         | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Valve Software 3D Camera           | 2        | 14.29%  |
| Tobii AB EyeChip                   | 1        | 7.14%   |
| Sunplus USB 2.0 Camera             | 1        | 7.14%   |
| Quanta HD Camera                   | 1        | 7.14%   |
| Microdia Webcam Vitade AF          | 1        | 7.14%   |
| Magic Control j5 WebCam JVCU100    | 1        | 7.14%   |
| Logitech HD Webcam C615            | 1        | 7.14%   |
| Logitech HD Webcam C525            | 1        | 7.14%   |
| Logitech HD Pro Webcam C920        | 1        | 7.14%   |
| Logitech B525 HD Webcam            | 1        | 7.14%   |
| IPEVO V4K                          | 1        | 7.14%   |
| Generalplus CAMERA - UVC           | 1        | 7.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR | 1        | 7.14%   |

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
| 0     | 75       | 74.26%  |
| 1     | 19       | 18.81%  |
| 2     | 6        | 5.94%   |
| 4     | 1        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 20       | 58.82%  |
| Unassigned class         | 4        | 11.76%  |
| Graphics card            | 3        | 8.82%   |
| Net/ethernet             | 2        | 5.88%   |
| Multimedia controller    | 2        | 5.88%   |
| Sound                    | 1        | 2.94%   |
| Fingerprint reader       | 1        | 2.94%   |
| Communication controller | 1        | 2.94%   |

