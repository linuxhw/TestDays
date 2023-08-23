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

Total: 117

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| SteamOS 3.4                  | 51       | 52.58%  |
| SteamOS 3.3                  | 24       | 24.74%  |
| SteamOS 3.2 (steamdeck-main) | 7        | 7.22%   |
| SteamOS                      | 6        | 6.19%   |
| SteamOS 4                    | 5        | 5.15%   |
| SteamOS Snapshot             | 3        | 3.09%   |
| SteamOS 3.2                  | 1        | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 94       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 40       | 42.11%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 11.58%  |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 10.53%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 7.37%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 6        | 6.32%   |
| 6.1.21-valve1-1-neptune-61                         | 3        | 3.16%   |
| 5.13.0-valve36-1-neptune                           | 3        | 3.16%   |
| 6.1.21-valve1-3-neptune-61                         | 2        | 2.11%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 2.11%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 2        | 2.11%   |
| 6.3.9-arch1-1                                      | 1        | 1.05%   |
| 6.1.29-valve4-1-neptune-61                         | 1        | 1.05%   |
| 6.1.12-valve2-1-neptune-61                         | 1        | 1.05%   |
| 5.15.93-1-lts                                      | 1        | 1.05%   |
| 5.15.79-1-lts                                      | 1        | 1.05%   |
| 5.15.60-1-lts                                      | 1        | 1.05%   |
| 5.13.0-valve24-1-neptune                           | 1        | 1.05%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 1.05%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 78       | 82.11%  |
| 5.18.1  | 6        | 6.32%   |
| 6.1.21  | 5        | 5.26%   |
| 6.3.9   | 1        | 1.05%   |
| 6.1.29  | 1        | 1.05%   |
| 6.1.12  | 1        | 1.05%   |
| 5.15.93 | 1        | 1.05%   |
| 5.15.79 | 1        | 1.05%   |
| 5.15.60 | 1        | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 78       | 82.11%  |
| 6.1     | 7        | 7.37%   |
| 5.18    | 6        | 6.32%   |
| 5.15    | 3        | 3.16%   |
| 6.3     | 1        | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 94       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 94       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 94       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 82       | 86.32%  |
| fr_FR | 3        | 3.16%   |
| ru_RU | 1        | 1.05%   |
| pt_PT | 1        | 1.05%   |
| pt_BR | 1        | 1.05%   |
| n_US  | 1        | 1.05%   |
| en_IE | 1        | 1.05%   |
| en_GB | 1        | 1.05%   |
| en_DE | 1        | 1.05%   |
| de_DE | 1        | 1.05%   |
| de_AT | 1        | 1.05%   |
| C     | 1        | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 94       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 89       | 94.68%  |
| Tmpfs | 5        | 5.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 29       | 30.85%  |
| Gigabyte Technology                  | 25       | 26.6%   |
| MSI                                  | 12       | 12.77%  |
| ASRock                               | 9        | 9.57%   |
| Hewlett-Packard                      | 7        | 7.45%   |
| Dell                                 | 6        | 6.38%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.06%   |
| MAXSUN                               | 1        | 1.06%   |
| Biostar                              | 1        | 1.06%   |
| Apple                                | 1        | 1.06%   |
| Alienware                            | 1        | 1.06%   |
| Acer                                 | 1        | 1.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 6        | 6.38%   |
| Gigabyte B450 AORUS M                      | 4        | 4.26%   |
| ASUS ROG STRIX B550-F GAMING               | 3        | 3.19%   |
| Gigabyte B550 GAMING X V2                  | 2        | 2.13%   |
| Dell OptiPlex 9010                         | 2        | 2.13%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.06%   |
| MSI MS-7D73                                | 1        | 1.06%   |
| MSI MS-7C89                                | 1        | 1.06%   |
| MSI MS-7C37                                | 1        | 1.06%   |
| MSI MS-7C02                                | 1        | 1.06%   |
| MSI MS-7B89                                | 1        | 1.06%   |
| MSI MS-7B79                                | 1        | 1.06%   |
| MSI MS-7B09                                | 1        | 1.06%   |
| MSI MS-7A33                                | 1        | 1.06%   |
| MSI MS-7817                                | 1        | 1.06%   |
| MSI MS-7693                                | 1        | 1.06%   |
| MSI MPG H510 Trident 3 (MS-B935)           | 1        | 1.06%   |
| MSI H310 Gaming Trident3 (MS-B920)         | 1        | 1.06%   |
| MAXSUN MS-H81IL TR M.2                     | 1        | 1.06%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx  | 1        | 1.06%   |
| HP ProDesk 600 G4 MT                       | 1        | 1.06%   |
| HP ProDesk 405 G4 Desktop Mini             | 1        | 1.06%   |
| HP Pavilion Gaming Desktop TG01-2xxx       | 1        | 1.06%   |
| HP Pavilion Gaming Desktop 690-00xx        | 1        | 1.06%   |
| HP EliteDesk 705 G5 SFF                    | 1        | 1.06%   |
| HP EliteDesk 705 G4 DM 65W (TAA)           | 1        | 1.06%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.06%   |
| Gigabyte Z170X-Gaming 6                    | 1        | 1.06%   |
| Gigabyte X570 UD                           | 1        | 1.06%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.06%   |
| Gigabyte X570 GAMING X                     | 1        | 1.06%   |
| Gigabyte MBB-670016                        | 1        | 1.06%   |
| Gigabyte H77N-WIFI                         | 1        | 1.06%   |
| Gigabyte H310M S2V 2.0                     | 1        | 1.06%   |
| Gigabyte H170N-WIFI                        | 1        | 1.06%   |
| Gigabyte F2A68HM-H                         | 1        | 1.06%   |
| Gigabyte B85M-D3H                          | 1        | 1.06%   |
| Gigabyte B560M DS3H V2                     | 1        | 1.06%   |
| Gigabyte B560M AORUS PRO                   | 1        | 1.06%   |
| Gigabyte B550M DS3H                        | 1        | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 8        | 8.51%   |
| ASUS All                                   | 6        | 6.38%   |
| Dell OptiPlex                              | 5        | 5.32%   |
| ASUS ROG                                   | 5        | 5.32%   |
| Gigabyte B450                              | 4        | 4.26%   |
| Gigabyte X570                              | 3        | 3.19%   |
| ASUS TUF                                   | 3        | 3.19%   |
| HP ProDesk                                 | 2        | 2.13%   |
| HP Pavilion                                | 2        | 2.13%   |
| HP EliteDesk                               | 2        | 2.13%   |
| Gigabyte B560M                             | 2        | 2.13%   |
| Gigabyte B550                              | 2        | 2.13%   |
| Gigabyte B450M                             | 2        | 2.13%   |
| ASRock B550                                | 2        | 2.13%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.06%   |
| MSI MS-7D73                                | 1        | 1.06%   |
| MSI MS-7C89                                | 1        | 1.06%   |
| MSI MS-7C37                                | 1        | 1.06%   |
| MSI MS-7C02                                | 1        | 1.06%   |
| MSI MS-7B89                                | 1        | 1.06%   |
| MSI MS-7B79                                | 1        | 1.06%   |
| MSI MS-7B09                                | 1        | 1.06%   |
| MSI MS-7A33                                | 1        | 1.06%   |
| MSI MS-7817                                | 1        | 1.06%   |
| MSI MS-7693                                | 1        | 1.06%   |
| MSI MPG                                    | 1        | 1.06%   |
| MSI H310                                   | 1        | 1.06%   |
| MAXSUN MS-H81IL                            | 1        | 1.06%   |
| HP Victus                                  | 1        | 1.06%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.06%   |
| Gigabyte Z170X-Gaming                      | 1        | 1.06%   |
| Gigabyte MBB-670016                        | 1        | 1.06%   |
| Gigabyte H77N-WIFI                         | 1        | 1.06%   |
| Gigabyte H310M                             | 1        | 1.06%   |
| Gigabyte H170N-WIFI                        | 1        | 1.06%   |
| Gigabyte F2A68HM-H                         | 1        | 1.06%   |
| Gigabyte B85M-D3H                          | 1        | 1.06%   |
| Gigabyte B550M                             | 1        | 1.06%   |
| Gigabyte AX370-Gaming                      | 1        | 1.06%   |
| Gigabyte AB350-Gaming                      | 1        | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 20       | 21.28%  |
| 2018 | 14       | 14.89%  |
| 2019 | 13       | 13.83%  |
| 2021 | 9        | 9.57%   |
| 2017 | 8        | 8.51%   |
| 2014 | 7        | 7.45%   |
| 2022 | 6        | 6.38%   |
| 2013 | 6        | 6.38%   |
| 2016 | 4        | 4.26%   |
| 2012 | 3        | 3.19%   |
| 2015 | 2        | 2.13%   |
| 2011 | 2        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 94       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 94       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 94       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 41       | 43.16%  |
| 32.01-64.0  | 25       | 26.32%  |
| 8.01-16.0   | 14       | 14.74%  |
| 4.01-8.0    | 7        | 7.37%   |
| 24.01-32.0  | 5        | 5.26%   |
| 64.01-256.0 | 3        | 3.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 42       | 44.21%  |
| 3.01-4.0  | 27       | 28.42%  |
| 4.01-8.0  | 16       | 16.84%  |
| 1.01-2.0  | 7        | 7.37%   |
| 8.01-16.0 | 3        | 3.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 32.29%  |
| 2      | 26       | 27.08%  |
| 3      | 20       | 20.83%  |
| 4      | 12       | 12.5%   |
| 5      | 4        | 4.17%   |
| 11     | 1        | 1.04%   |
| 7      | 1        | 1.04%   |
| 6      | 1        | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 87.23%  |
| Yes       | 12       | 12.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 64.89%  |
| No        | 33       | 35.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 52.63%  |
| No        | 45       | 47.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 40       | 42.11%  |
| UK           | 8        | 8.42%   |
| France       | 6        | 6.32%   |
| Australia    | 5        | 5.26%   |
| Brazil       | 4        | 4.21%   |
| Ireland      | 3        | 3.16%   |
| Germany      | 3        | 3.16%   |
| Poland       | 2        | 2.11%   |
| Philippines  | 2        | 2.11%   |
| Canada       | 2        | 2.11%   |
| Uzbekistan   | 1        | 1.05%   |
| Turkey       | 1        | 1.05%   |
| Thailand     | 1        | 1.05%   |
| Spain        | 1        | 1.05%   |
| South Africa | 1        | 1.05%   |
| Romania      | 1        | 1.05%   |
| Portugal     | 1        | 1.05%   |
| Peru         | 1        | 1.05%   |
| Oman         | 1        | 1.05%   |
| Malaysia     | 1        | 1.05%   |
| Latvia       | 1        | 1.05%   |
| Italy        | 1        | 1.05%   |
| Israel       | 1        | 1.05%   |
| Iceland      | 1        | 1.05%   |
| Hong Kong    | 1        | 1.05%   |
| El Salvador  | 1        | 1.05%   |
| Denmark      | 1        | 1.05%   |
| Cambodia     | 1        | 1.05%   |
| Austria      | 1        | 1.05%   |
| Argentina    | 1        | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 2.11%   |
| Sao Paulo              | 2        | 2.11%   |
| San Jose               | 2        | 2.11%   |
| Gujan-Mestras          | 2        | 2.11%   |
| Zevio                  | 1        | 1.05%   |
| West Bloomfield        | 1        | 1.05%   |
| Walsall                | 1        | 1.05%   |
| Ville Platte           | 1        | 1.05%   |
| Vilas                  | 1        | 1.05%   |
| Tuam                   | 1        | 1.05%   |
| Toronto                | 1        | 1.05%   |
| Tashkent               | 1        | 1.05%   |
| Targoviste             | 1        | 1.05%   |
| Sterling Heights       | 1        | 1.05%   |
| Skarzysko-Kamienna     | 1        | 1.05%   |
| Siloam Springs         | 1        | 1.05%   |
| Sassenberg             | 1        | 1.05%   |
| San Salvador           | 1        | 1.05%   |
| Salford                | 1        | 1.05%   |
| Salem                  | 1        | 1.05%   |
| Riga                   | 1        | 1.05%   |
| Reykjavik              | 1        | 1.05%   |
| Quezon City            | 1        | 1.05%   |
| Puchberg am Schneeberg | 1        | 1.05%   |
| Portland               | 1        | 1.05%   |
| Phnom Penh             | 1        | 1.05%   |
| Petah Tikva            | 1        | 1.05%   |
| Perth                  | 1        | 1.05%   |
| Peoria                 | 1        | 1.05%   |
| Paris                  | 1        | 1.05%   |
| Ostrów Wielkopolski   | 1        | 1.05%   |
| Oklahoma City          | 1        | 1.05%   |
| Ocean Springs          | 1        | 1.05%   |
| Norwich                | 1        | 1.05%   |
| Noble Park             | 1        | 1.05%   |
| Newport                | 1        | 1.05%   |
| Newcastle-under-Lyme   | 1        | 1.05%   |
| Muscat                 | 1        | 1.05%   |
| Moyeuvre-Grande        | 1        | 1.05%   |
| Moscow                 | 1        | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 31       | 38     | 15.98%  |
| Samsung Electronics         | 25       | 46     | 12.89%  |
| WDC                         | 22       | 28     | 11.34%  |
| Kingston                    | 15       | 18     | 7.73%   |
| Crucial                     | 15       | 19     | 7.73%   |
| Toshiba                     | 14       | 16     | 7.22%   |
| SanDisk                     | 14       | 16     | 7.22%   |
| Micron/Crucial Technology   | 6        | 6      | 3.09%   |
| A-DATA Technology           | 5        | 5      | 2.58%   |
| PNY                         | 4        | 5      | 2.06%   |
| Phison Electronics          | 4        | 6      | 2.06%   |
| Phison                      | 4        | 5      | 2.06%   |
| Unknown                     | 4        | 5      | 2.06%   |
| Realtek Semiconductor       | 3        | 3      | 1.55%   |
| SK hynix                    | 2        | 2      | 1.03%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 1.03%   |
| Kingston Technology Company | 2        | 2      | 1.03%   |
| Intel                       | 2        | 3      | 1.03%   |
| Hitachi                     | 2        | 2      | 1.03%   |
| China                       | 2        | 5      | 1.03%   |
| Unknown                     | 1        | 1      | 0.52%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.52%   |
| T-FORCE                     | 1        | 1      | 0.52%   |
| SPCC                        | 1        | 3      | 0.52%   |
| Silicon Motion              | 1        | 1      | 0.52%   |
| Realtek                     | 1        | 1      | 0.52%   |
| Ramsta                      | 1        | 1      | 0.52%   |
| Mushkin                     | 1        | 1      | 0.52%   |
| KIOXIA                      | 1        | 1      | 0.52%   |
| KingFast                    | 1        | 1      | 0.52%   |
| Intenso                     | 1        | 1      | 0.52%   |
| HS-SSD-C100                 | 1        | 1      | 0.52%   |
| GALAX                       | 1        | 1      | 0.52%   |
| Apple                       | 1        | 1      | 0.52%   |
| ADATA Technology            | 1        | 2      | 0.52%   |
| 2.5                         | 1        | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5        | 2.28%   |
| Toshiba DT01ACA100 1TB                              | 4        | 1.83%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.83%   |
| Unknown                                             | 4        | 1.83%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 1.37%   |
| Samsung NVMe SSD Drive 1TB                          | 3        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3        | 1.37%   |
| Crucial CT1000BX500SSD1 1TB                         | 3        | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 0.91%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2        | 0.91%   |
| Toshiba MQ01ABD100 1TB                              | 2        | 0.91%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 0.91%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2        | 0.91%   |
| SanDisk NVMe SSD Drive 500GB                        | 2        | 0.91%   |
| Samsung SSD 980 1TB                                 | 2        | 0.91%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 0.91%   |
| Samsung SSD 850 EVO 500GB                           | 2        | 0.91%   |
| Samsung SSD 840 EVO 250GB                           | 2        | 0.91%   |
| Realtek NVMe SSD Drive 256GB                        | 2        | 0.91%   |
| PNY CS900 120GB SSD                                 | 2        | 0.91%   |
| Phison E12 NVMe Controller 2TB                      | 2        | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2        | 0.91%   |
| Micron/Crucial CT1000P1SSD8 1TB                     | 2        | 0.91%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 2        | 0.91%   |
| Kingston SV300S37A120G 120GB SSD                    | 2        | 0.91%   |
| Kingston SH103S3120G 120GB SSD                      | 2        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                     | 2        | 0.91%   |
| Crucial CT500MX500SSD1 500GB                        | 2        | 0.91%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 0.91%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 0.91%   |
| A-DATA SU650 240GB SSD                              | 2        | 0.91%   |
| A-DATA SU630 240GB SSD                              | 2        | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.46%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                      | 1        | 0.46%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1        | 0.46%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.46%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.46%   |
| WDC WDBNCE2500PNC 250GB SSD                         | 1        | 0.46%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.46%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 37     | 51.72%  |
| WDC                 | 13       | 17     | 22.41%  |
| Toshiba             | 12       | 14     | 20.69%  |
| Hitachi             | 2        | 2      | 3.45%   |
| Samsung Electronics | 1        | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 26     | 21.79%  |
| Crucial             | 15       | 19     | 19.23%  |
| Kingston            | 11       | 13     | 14.1%   |
| WDC                 | 10       | 11     | 12.82%  |
| SanDisk             | 8        | 9      | 10.26%  |
| A-DATA Technology   | 5        | 5      | 6.41%   |
| PNY                 | 4        | 5      | 5.13%   |
| China               | 2        | 5      | 2.56%   |
| SPCC                | 1        | 3      | 1.28%   |
| Ramsta              | 1        | 1      | 1.28%   |
| Mushkin             | 1        | 1      | 1.28%   |
| Intenso             | 1        | 1      | 1.28%   |
| Intel               | 1        | 1      | 1.28%   |
| 2.5                 | 1        | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 58       | 101    | 34.94%  |
| NVMe    | 54       | 70     | 32.53%  |
| HDD     | 47       | 71     | 28.31%  |
| Unknown | 7        | 9      | 4.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 79       | 174    | 57.66%  |
| NVMe | 54       | 69     | 39.42%  |
| SAS  | 4        | 8      | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 88     | 47.01%  |
| 0.51-1.0   | 39       | 50     | 33.33%  |
| 1.01-2.0   | 10       | 18     | 8.55%   |
| 3.01-4.0   | 5        | 6      | 4.27%   |
| 2.01-3.0   | 4        | 6      | 3.42%   |
| 4.01-10.0  | 4        | 4      | 3.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 27       | 28.72%  |
| 501-1000       | 22       | 23.4%   |
| 251-500        | 18       | 19.15%  |
| 1001-2000      | 14       | 14.89%  |
| More than 3000 | 8        | 8.51%   |
| 2001-3000      | 2        | 2.13%   |
| Unknown        | 2        | 2.13%   |
| 51-100         | 1        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 33.33%  |
| 51-100         | 20       | 20.83%  |
| 101-250        | 14       | 14.58%  |
| 21-50          | 10       | 10.42%  |
| 501-1000       | 8        | 8.33%   |
| 251-500        | 5        | 5.21%   |
| More than 3000 | 2        | 2.08%   |
| 2001-3000      | 2        | 2.08%   |
| Unknown        | 2        | 2.08%   |
| 1001-2000      | 1        | 1.04%   |

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
| Detected | 95       | 251    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 49       | 32.24%  |
| Intel                        | 43       | 28.29%  |
| Samsung Electronics          | 14       | 9.21%   |
| Phison Electronics           | 8        | 5.26%   |
| SanDisk                      | 7        | 4.61%   |
| Micron/Crucial Technology    | 6        | 3.95%   |
| Kingston Technology Company  | 6        | 3.95%   |
| Realtek Semiconductor        | 3        | 1.97%   |
| Toshiba America Info Systems | 2        | 1.32%   |
| SK hynix                     | 2        | 1.32%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.32%   |
| ASMedia Technology           | 2        | 1.32%   |
| Union Memory (Shenzhen)      | 1        | 0.66%   |
| Silicon Motion               | 1        | 0.66%   |
| Seagate Technology           | 1        | 0.66%   |
| Marvell Technology Group     | 1        | 0.66%   |
| KIOXIA                       | 1        | 0.66%   |
| INNOGRIT                     | 1        | 0.66%   |
| Apple                        | 1        | 0.66%   |
| ADATA Technology             | 1        | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31       | 17.03%  |
| AMD 400 Series Chipset SATA Controller                                         | 14       | 7.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 12       | 6.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 4.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 2.75%   |
| Phison E12 NVMe Controller                                                     | 4        | 2.2%    |
| Intel SATA Controller [RAID mode]                                              | 4        | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 2.2%    |
| AMD FCH SATA Controller D                                                      | 4        | 2.2%    |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 1.65%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2        | 1.1%    |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.1%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2        | 1.1%    |
| Phison Electronics Non-Volatile memory controller                              | 2        | 1.1%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 2        | 1.1%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 1.1%    |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 1.1%    |
| Kingston Company NV1 NVMe SSD                                                  | 2        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.1%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                          | 1        | 0.55%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.55%   |
| SK hynix BC511 NVMe SSD                                                        | 1        | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.55%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1        | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.55%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1        | 0.55%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.55%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.55%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 86       | 58.11%  |
| NVMe | 54       | 36.49%  |
| RAID | 6        | 4.05%   |
| IDE  | 2        | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 51       | 54.26%  |
| Intel  | 43       | 45.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics | 6        | 6.38%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 4.26%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4        | 4.26%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 3        | 3.19%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 3        | 3.19%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 3.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 2.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 2.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 2.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 2.13%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 2        | 2.13%   |
| Intel Core i3-9100F CPU @ 3.60GHz      | 2        | 2.13%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 2        | 2.13%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 2.13%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 2        | 2.13%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 2.13%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 2.13%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 2.13%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 2.13%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 2        | 2.13%   |
| Intel Xeon W-3223 CPU @ 3.50GHz        | 1        | 1.06%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 1        | 1.06%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz    | 1        | 1.06%   |
| Intel Xeon CPU E31220 @ 3.10GHz        | 1        | 1.06%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 1        | 1.06%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.06%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 1.06%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.06%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.06%   |
| Intel Core i5-8500T CPU @ 2.10GHz      | 1        | 1.06%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 1        | 1.06%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1        | 1.06%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 1        | 1.06%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 1.06%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.06%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 1.06%   |
| Intel Core i5-10600KF CPU @ 4.10GHz    | 1        | 1.06%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1        | 1.06%   |
| Intel Celeron CPU G1620 @ 2.70GHz      | 1        | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 22       | 23.4%   |
| Intel Core i5          | 16       | 17.02%  |
| Intel Core i7          | 14       | 14.89%  |
| AMD Ryzen 9            | 10       | 10.64%  |
| AMD Ryzen 7            | 10       | 10.64%  |
| Other                  | 5        | 5.32%   |
| Intel Xeon             | 4        | 4.26%   |
| Intel Core i3          | 3        | 3.19%   |
| AMD Ryzen 5 PRO        | 3        | 3.19%   |
| AMD FX                 | 2        | 2.13%   |
| Intel Celeron          | 1        | 1.06%   |
| AMD Ryzen Threadripper | 1        | 1.06%   |
| AMD Ryzen 7 PRO        | 1        | 1.06%   |
| AMD Athlon X4          | 1        | 1.06%   |
| AMD Athlon             | 1        | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 34.04%  |
| 6      | 31       | 32.98%  |
| 8      | 16       | 17.02%  |
| 12     | 10       | 10.64%  |
| 2      | 4        | 4.26%   |
| 3      | 1        | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 76       | 80.85%  |
| 1      | 18       | 19.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 94       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 16       | 17.02%  |
| Zen+        | 12       | 12.77%  |
| Haswell     | 12       | 12.77%  |
| Zen 2       | 11       | 11.7%   |
| KabyLake    | 11       | 11.7%   |
| Zen         | 7        | 7.45%   |
| Unknown     | 7        | 7.45%   |
| Skylake     | 5        | 5.32%   |
| IvyBridge   | 4        | 4.26%   |
| SandyBridge | 3        | 3.19%   |
| CometLake   | 3        | 3.19%   |
| Piledriver  | 2        | 2.13%   |
| Steamroller | 1        | 1.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 67       | 63.21%  |
| Nvidia | 25       | 23.58%  |
| Intel  | 14       | 13.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 15.32%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 7.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.5%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 4.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 4.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.6%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 4        | 3.6%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 3.6%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 3.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 3.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 2.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.8%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 1.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.8%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.8%    |
| Intel HD Graphics 530                                                       | 2        | 1.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.9%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.9%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.9%    |
| Intel HD Graphics 630                                                       | 1        | 0.9%    |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 0.9%    |
| AMD Raphael                                                                 | 1        | 0.9%    |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 0.9%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 59       | 61.46%  |
| 1 x Nvidia     | 22       | 22.92%  |
| 2 x AMD        | 5        | 5.21%   |
| 1 x Intel      | 4        | 4.17%   |
| Intel + Nvidia | 2        | 2.08%   |
| Intel + AMD    | 2        | 2.08%   |
| AMD + Nvidia   | 2        | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 77.66%  |
| Proprietary | 21       | 22.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 77.89%  |
| 3.01-4.0   | 7        | 7.37%   |
| 7.01-8.0   | 6        | 6.32%   |
| 5.01-6.0   | 3        | 3.16%   |
| 8.01-16.0  | 2        | 2.11%   |
| 2.01-3.0   | 1        | 1.05%   |
| 16.01-24.0 | 1        | 1.05%   |
| 1.01-2.0   | 1        | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 13       | 13.83%  |
| Samsung Electronics  | 12       | 12.77%  |
| Acer                 | 9        | 9.57%   |
| AOC                  | 6        | 6.38%   |
| Hewlett-Packard      | 5        | 5.32%   |
| Dell                 | 4        | 4.26%   |
| ASUSTek Computer     | 4        | 4.26%   |
| Ancor Communications | 4        | 4.26%   |
| ViewSonic            | 3        | 3.19%   |
| Sony                 | 3        | 3.19%   |
| Pixio                | 3        | 3.19%   |
| Philips              | 3        | 3.19%   |
| Toshiba              | 2        | 2.13%   |
| Sceptre Tech         | 2        | 2.13%   |
| ONN                  | 2        | 2.13%   |
| MSI                  | 2        | 2.13%   |
| Hitachi              | 2        | 2.13%   |
| ___                  | 1        | 1.06%   |
| WIT                  | 1        | 1.06%   |
| Wacom                | 1        | 1.06%   |
| Valve                | 1        | 1.06%   |
| Unknown              | 1        | 1.06%   |
| Sun                  | 1        | 1.06%   |
| Roku                 | 1        | 1.06%   |
| Insignia             | 1        | 1.06%   |
| Huion                | 1        | 1.06%   |
| HJW                  | 1        | 1.06%   |
| HannStar             | 1        | 1.06%   |
| Gigabyte Technology  | 1        | 1.06%   |
| DZX                  | 1        | 1.06%   |
| BenQ                 | 1        | 1.06%   |
| AOpen                | 1        | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Pixio DP WAM2700 1920x1080 598x336mm 27.0-inch                          | 2        | 2.08%   |
| Hitachi HISENSE HEC0030 3840x2160 1095x616mm 49.5-inch                  | 2        | 2.08%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch              | 2        | 2.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 2.08%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 2        | 2.08%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 1.04%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 1.04%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 1.04%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 1.04%   |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1        | 1.04%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 1.04%   |
| Valve Index HMD VLV91A8                                                 | 1        | 1.04%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.04%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                      | 1        | 1.04%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 1.04%   |
| Sun 48FHD_LCD_TV SCE0301 1920x1080 1280x720mm 57.8-inch                 | 1        | 1.04%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1.04%   |
| Sony TV *00 SNY3F05 3840x2160 1439x809mm 65.0-inch                      | 1        | 1.04%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 1.04%   |
| Sceptre Tech H50 SPT13C0 1920x1080 575x323mm 26.0-inch                  | 1        | 1.04%   |
| Sceptre Tech E225W-1920 SPT08D5 1920x1080 443x249mm 20.0-inch           | 1        | 1.04%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 1.04%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.04%   |
| Samsung Electronics LS27AG30x SAM717B 1920x1080 597x336mm 27.0-inch     | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM7269 3840x2160 700x390mm 31.5-inch   | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1420x800mm 64.2-inch  | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 1.04%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 1.04%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 1.04%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1        | 1.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.04%   |
| Roku 100068372 RKU0B01 1920x1080 698x392mm 31.5-inch                    | 1        | 1.04%   |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 1.04%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.04%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 1.04%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 1.04%   |
| ONN onn. TV ONN0C94 1920x1080 698x392mm 31.5-inch                       | 1        | 1.04%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                     | 1        | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 48.89%  |
| 3840x2160 (4K)     | 23       | 25.56%  |
| 2560x1440 (QHD)    | 10       | 11.11%  |
| 2560x1080          | 3        | 3.33%   |
| 1920x1200 (WUXGA)  | 2        | 2.22%   |
| 3840x1080          | 1        | 1.11%   |
| 1680x1050 (WSXGA+) | 1        | 1.11%   |
| 1600x900 (HD+)     | 1        | 1.11%   |
| 1440x900 (WXGA+)   | 1        | 1.11%   |
| 1400x1050          | 1        | 1.11%   |
| 1366x768 (WXGA)    | 1        | 1.11%   |
| 1360x768           | 1        | 1.11%   |
| Unknown            | 1        | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 20.43%  |
| 31      | 14       | 15.05%  |
| 24      | 14       | 15.05%  |
| 23      | 14       | 15.05%  |
| 84      | 5        | 5.38%   |
| 21      | 5        | 5.38%   |
| 72      | 4        | 4.3%    |
| 48      | 2        | 2.15%   |
| 34      | 2        | 2.15%   |
| 15      | 2        | 2.15%   |
| Unknown | 2        | 2.15%   |
| 75      | 1        | 1.08%   |
| 74      | 1        | 1.08%   |
| 65      | 1        | 1.08%   |
| 57      | 1        | 1.08%   |
| 47      | 1        | 1.08%   |
| 46      | 1        | 1.08%   |
| 32      | 1        | 1.08%   |
| 26      | 1        | 1.08%   |
| 20      | 1        | 1.08%   |
| 18      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 42       | 47.19%  |
| 601-700     | 16       | 17.98%  |
| 1501-2000   | 11       | 12.36%  |
| 401-500     | 7        | 7.87%   |
| 1001-1500   | 6        | 6.74%   |
| 701-800     | 3        | 3.37%   |
| 301-350     | 2        | 2.25%   |
| Unknown     | 2        | 2.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 77       | 89.53%  |
| 16/10   | 5        | 5.81%   |
| 21/9    | 2        | 2.33%   |
| 32/9    | 1        | 1.16%   |
| Unknown | 1        | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 29.03%  |
| 301-350        | 19       | 20.43%  |
| 351-500        | 17       | 18.28%  |
| More than 1000 | 14       | 15.05%  |
| 251-300        | 7        | 7.53%   |
| 501-1000       | 3        | 3.23%   |
| Unknown        | 2        | 2.15%   |
| 151-200        | 1        | 1.08%   |
| 141-150        | 1        | 1.08%   |
| 101-110        | 1        | 1.08%   |
| 91-100         | 1        | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 58       | 65.17%  |
| 101-120 | 14       | 15.73%  |
| 1-50    | 7        | 7.87%   |
| 121-160 | 6        | 6.74%   |
| 161-240 | 2        | 2.25%   |
| Unknown | 2        | 2.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 85.26%  |
| 2     | 14       | 14.74%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 61       | 40.13%  |
| Intel                         | 51       | 33.55%  |
| Broadcom                      | 8        | 5.26%   |
| TP-Link                       | 6        | 3.95%   |
| Microsoft                     | 6        | 3.95%   |
| Qualcomm Atheros              | 4        | 2.63%   |
| Samsung Electronics           | 2        | 1.32%   |
| Ralink Technology             | 2        | 1.32%   |
| OPPO Electronics              | 2        | 1.32%   |
| MediaTek                      | 2        | 1.32%   |
| ASUSTek Computer              | 2        | 1.32%   |
| OnePlus Technology (Shenzhen) | 1        | 0.66%   |
| Huawei Technologies           | 1        | 0.66%   |
| Google                        | 1        | 0.66%   |
| D-Link                        | 1        | 0.66%   |
| Aquantia                      | 1        | 0.66%   |
| Apple                         | 1        | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 51       | 28.65%  |
| Intel Wi-Fi 6 AX200                                                                           | 11       | 6.18%   |
| Intel Ethernet Connection (2) I219-V                                                          | 9        | 5.06%   |
| Intel Ethernet Controller I225-V                                                              | 8        | 4.49%   |
| Intel I211 Gigabit Network Connection                                                         | 7        | 3.93%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 2.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 2.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 2.81%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 4        | 2.25%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 2.25%   |
| Intel Wireless 8260                                                                           | 3        | 1.69%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2        | 1.12%   |
| Realtek 802.11ac NIC                                                                          | 2        | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.12%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 1.12%   |
| Intel Wireless 7265                                                                           | 2        | 1.12%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.12%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.56%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.56%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 26       | 38.81%  |
| Realtek Semiconductor | 12       | 17.91%  |
| Broadcom              | 8        | 11.94%  |
| TP-Link               | 6        | 8.96%   |
| Microsoft             | 6        | 8.96%   |
| Ralink Technology     | 2        | 2.99%   |
| Qualcomm Atheros      | 2        | 2.99%   |
| MediaTek              | 2        | 2.99%   |
| ASUSTek Computer      | 2        | 2.99%   |
| D-Link                | 1        | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 11       | 16.42%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 7.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 7.46%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 4        | 5.97%   |
| Intel Wireless 8260                                                                           | 3        | 4.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.99%   |
| Realtek 802.11ac NIC                                                                          | 2        | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.99%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 2.99%   |
| Intel Wireless 7265                                                                           | 2        | 2.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.49%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.49%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.49%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 1.49%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.49%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.49%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.49%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.49%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 1        | 1.49%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.49%   |
| Broadcom Network controller                                                                   | 1        | 1.49%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 1.49%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.49%   |
| ASUS 802.11ac WLAN Adapter                                                                    | 1        | 1.49%   |
| ASUS 802.11ac NIC                                                                             | 1        | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 60       | 55.56%  |
| Intel                         | 37       | 34.26%  |
| Qualcomm Atheros              | 3        | 2.78%   |
| Samsung Electronics           | 2        | 1.85%   |
| OPPO Electronics              | 2        | 1.85%   |
| OnePlus Technology (Shenzhen) | 1        | 0.93%   |
| Huawei Technologies           | 1        | 0.93%   |
| Google                        | 1        | 0.93%   |
| Aquantia                      | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51       | 46.36%  |
| Intel Ethernet Connection (2) I219-V                              | 9        | 8.18%   |
| Intel Ethernet Controller I225-V                                  | 8        | 7.27%   |
| Intel I211 Gigabit Network Connection                             | 7        | 6.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.82%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.91%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1        | 0.91%   |
| OPPO SM6375-QRD _SN:0AF7C3B5                                      | 1        | 0.91%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.91%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.91%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.91%   |
| Huawei WLZ-AN00                                                   | 1        | 0.91%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.91%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 60.26%  |
| WiFi     | 61       | 39.1%   |
| Modem    | 1        | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 78.35%  |
| WiFi     | 21       | 21.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 53.19%  |
| 2     | 37       | 39.36%  |
| 3     | 7        | 7.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 67.02%  |
| Yes  | 31       | 32.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 45.28%  |
| Cambridge Silicon Radio         | 9        | 16.98%  |
| ASUSTek Computer                | 5        | 9.43%   |
| Realtek Semiconductor           | 4        | 7.55%   |
| MediaTek                        | 2        | 3.77%   |
| Broadcom                        | 2        | 3.77%   |
| Apple                           | 2        | 3.77%   |
| TP-Link                         | 1        | 1.89%   |
| Realtek                         | 1        | 1.89%   |
| Qualcomm Atheros Communications | 1        | 1.89%   |
| Integrated System Solution      | 1        | 1.89%   |
| IMC Networks                    | 1        | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 10       | 18.87%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 9        | 16.98%  |
| Intel Bluetooth wireless interface                    | 5        | 9.43%   |
| Intel AX210 Bluetooth                                 | 4        | 7.55%   |
| Realtek Bluetooth Radio                               | 3        | 5.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 5.66%   |
| MediaTek Wireless_Device                              | 2        | 3.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 3.77%   |
| Apple Bluetooth USB Host Controller                   | 2        | 3.77%   |
| TP-Link UB500 Adapter                                 | 1        | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.89%   |
| Realtek Bluetooth Radio                               | 1        | 1.89%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.89%   |
| Intel Bluetooth Device                                | 1        | 1.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.89%   |
| Intel AX201 Bluetooth                                 | 1        | 1.89%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.89%   |
| IMC Networks Bluetooth Device                         | 1        | 1.89%   |
| ASUS BCM20702A0                                       | 1        | 1.89%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 77       | 43.5%   |
| Intel                    | 43       | 24.29%  |
| Nvidia                   | 25       | 14.12%  |
| Logitech                 | 7        | 3.95%   |
| C-Media Electronics      | 4        | 2.26%   |
| SteelSeries ApS          | 3        | 1.69%   |
| Valve Software           | 2        | 1.13%   |
| Medeli Electronics       | 2        | 1.13%   |
| Kingston Technology      | 2        | 1.13%   |
| JMTek                    | 2        | 1.13%   |
| Corsair                  | 2        | 1.13%   |
| Apple                    | 2        | 1.13%   |
| Tenx Technology          | 1        | 0.56%   |
| Realtek Semiconductor    | 1        | 0.56%   |
| Quanta                   | 1        | 0.56%   |
| Micro Star International | 1        | 0.56%   |
| Focusrite-Novation       | 1        | 0.56%   |
| Creative Labs            | 1        | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 21       | 9.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 8.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 7.83%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 6.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 6.09%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 3.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 3.48%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 1.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.3%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.3%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.3%    |
| Valve Software Valve VR Radio & HMD Mic                                    | 2        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.87%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 0.87%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 0.87%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 0.87%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.43%   |
| SteelSeries ApS SteelSeries SC2 USB Headset                                | 1        | 0.43%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 0.43%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.43%   |

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


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Valve Software 3D Camera        | 2        | 14.29%  |
| Tobii AB EyeChip                | 1        | 7.14%   |
| Sunplus USB 2.0 Camera          | 1        | 7.14%   |
| Quanta HD Camera                | 1        | 7.14%   |
| Microdia Webcam Vitade AF       | 1        | 7.14%   |
| Magic Control j5 WebCam JVCU100 | 1        | 7.14%   |
| Logitech HD Webcam C615         | 1        | 7.14%   |
| Logitech HD Webcam C525         | 1        | 7.14%   |
| Logitech HD Pro Webcam C920     | 1        | 7.14%   |
| Logitech B525 HD Webcam         | 1        | 7.14%   |
| IPEVO V4K                       | 1        | 7.14%   |
| Generalplus GENERAL WEBCAM      | 1        | 7.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 7.14%   |

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
| 0     | 70       | 73.68%  |
| 1     | 18       | 18.95%  |
| 2     | 6        | 6.32%   |
| 4     | 1        | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 19       | 57.58%  |
| Unassigned class         | 4        | 12.12%  |
| Graphics card            | 3        | 9.09%   |
| Net/ethernet             | 2        | 6.06%   |
| Multimedia controller    | 2        | 6.06%   |
| Sound                    | 1        | 3.03%   |
| Fingerprint reader       | 1        | 3.03%   |
| Communication controller | 1        | 3.03%   |

