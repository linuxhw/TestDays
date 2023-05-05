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

Total: 105

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| SteamOS 3.4                  | 42       | 49.41%  |
| SteamOS 3.3                  | 24       | 28.24%  |
| SteamOS 3.2 (steamdeck-main) | 7        | 8.24%   |
| SteamOS                      | 5        | 5.88%   |
| SteamOS Snapshot             | 3        | 3.53%   |
| SteamOS 4                    | 3        | 3.53%   |
| SteamOS 3.2                  | 1        | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 82       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 34       | 40.96%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 13.25%  |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 12.05%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 8.43%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 6        | 7.23%   |
| 5.13.0-valve36-1-neptune                           | 3        | 3.61%   |
| 6.1.21-valve1-1-neptune-61                         | 2        | 2.41%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 2.41%   |
| 6.1.12-valve2-1-neptune-61                         | 1        | 1.2%    |
| 5.15.93-1-lts                                      | 1        | 1.2%    |
| 5.15.79-1-lts                                      | 1        | 1.2%    |
| 5.15.60-1-lts                                      | 1        | 1.2%    |
| 5.13.0-valve24-1-neptune                           | 1        | 1.2%    |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 1.2%    |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 1        | 1.2%    |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 71       | 85.54%  |
| 5.18.1  | 6        | 7.23%   |
| 6.1.21  | 2        | 2.41%   |
| 6.1.12  | 1        | 1.2%    |
| 5.15.93 | 1        | 1.2%    |
| 5.15.79 | 1        | 1.2%    |
| 5.15.60 | 1        | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 71       | 85.54%  |
| 5.18    | 6        | 7.23%   |
| 6.1     | 3        | 3.61%   |
| 5.15    | 3        | 3.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 82       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 82       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 82       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 72       | 86.75%  |
| fr_FR | 3        | 3.61%   |
| ru_RU | 1        | 1.2%    |
| pt_PT | 1        | 1.2%    |
| pt_BR | 1        | 1.2%    |
| en_IE | 1        | 1.2%    |
| en_GB | 1        | 1.2%    |
| de_DE | 1        | 1.2%    |
| de_AT | 1        | 1.2%    |
| C     | 1        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 82       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 78       | 95.12%  |
| Tmpfs | 4        | 4.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 25       | 30.49%  |
| Gigabyte Technology                  | 22       | 26.83%  |
| MSI                                  | 11       | 13.41%  |
| ASRock                               | 8        | 9.76%   |
| Hewlett-Packard                      | 6        | 7.32%   |
| Dell                                 | 5        | 6.1%    |
| Shenzhen Meigao Electronic Equipment | 1        | 1.22%   |
| Biostar                              | 1        | 1.22%   |
| Apple                                | 1        | 1.22%   |
| Alienware                            | 1        | 1.22%   |
| Acer                                 | 1        | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 5        | 6.1%    |
| Gigabyte B450 AORUS M                      | 4        | 4.88%   |
| Gigabyte B550 GAMING X V2                  | 2        | 2.44%   |
| Dell OptiPlex 9010                         | 2        | 2.44%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 2.44%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.22%   |
| MSI MS-7D73                                | 1        | 1.22%   |
| MSI MS-7C37                                | 1        | 1.22%   |
| MSI MS-7C02                                | 1        | 1.22%   |
| MSI MS-7B89                                | 1        | 1.22%   |
| MSI MS-7B79                                | 1        | 1.22%   |
| MSI MS-7B09                                | 1        | 1.22%   |
| MSI MS-7A33                                | 1        | 1.22%   |
| MSI MS-7817                                | 1        | 1.22%   |
| MSI MS-7693                                | 1        | 1.22%   |
| MSI MPG H510 Trident 3 (MS-B935)           | 1        | 1.22%   |
| MSI H310 Gaming Trident3 (MS-B920)         | 1        | 1.22%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx  | 1        | 1.22%   |
| HP ProDesk 600 G4 MT                       | 1        | 1.22%   |
| HP ProDesk 405 G4 Desktop Mini             | 1        | 1.22%   |
| HP Pavilion Gaming Desktop TG01-2xxx       | 1        | 1.22%   |
| HP Pavilion Gaming Desktop 690-00xx        | 1        | 1.22%   |
| HP EliteDesk 705 G4 DM 65W (TAA)           | 1        | 1.22%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.22%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.22%   |
| Gigabyte X570 GAMING X                     | 1        | 1.22%   |
| Gigabyte MBB-670016                        | 1        | 1.22%   |
| Gigabyte H77N-WIFI                         | 1        | 1.22%   |
| Gigabyte H310M S2V 2.0                     | 1        | 1.22%   |
| Gigabyte H170N-WIFI                        | 1        | 1.22%   |
| Gigabyte F2A68HM-H                         | 1        | 1.22%   |
| Gigabyte B85M-D3H                          | 1        | 1.22%   |
| Gigabyte B560M AORUS PRO                   | 1        | 1.22%   |
| Gigabyte B550M DS3H                        | 1        | 1.22%   |
| Gigabyte B450M DS3H V2                     | 1        | 1.22%   |
| Gigabyte B450M DS3H                        | 1        | 1.22%   |
| Gigabyte AX370-Gaming                      | 1        | 1.22%   |
| Gigabyte AB350-Gaming 3                    | 1        | 1.22%   |
| Gigabyte 970A-DS3P FX                      | 1        | 1.22%   |
| Dell Precision Tower 5810                  | 1        | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 8        | 9.76%   |
| ASUS All                                   | 5        | 6.1%    |
| Gigabyte B450                              | 4        | 4.88%   |
| Dell OptiPlex                              | 4        | 4.88%   |
| ASUS TUF                                   | 3        | 3.66%   |
| ASUS ROG                                   | 3        | 3.66%   |
| HP ProDesk                                 | 2        | 2.44%   |
| HP Pavilion                                | 2        | 2.44%   |
| Gigabyte X570                              | 2        | 2.44%   |
| Gigabyte B550                              | 2        | 2.44%   |
| Gigabyte B450M                             | 2        | 2.44%   |
| ASRock B550                                | 2        | 2.44%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.22%   |
| MSI MS-7D73                                | 1        | 1.22%   |
| MSI MS-7C37                                | 1        | 1.22%   |
| MSI MS-7C02                                | 1        | 1.22%   |
| MSI MS-7B89                                | 1        | 1.22%   |
| MSI MS-7B79                                | 1        | 1.22%   |
| MSI MS-7B09                                | 1        | 1.22%   |
| MSI MS-7A33                                | 1        | 1.22%   |
| MSI MS-7817                                | 1        | 1.22%   |
| MSI MS-7693                                | 1        | 1.22%   |
| MSI MPG                                    | 1        | 1.22%   |
| MSI H310                                   | 1        | 1.22%   |
| HP Victus                                  | 1        | 1.22%   |
| HP EliteDesk                               | 1        | 1.22%   |
| Gigabyte Z97X-UD5H                         | 1        | 1.22%   |
| Gigabyte MBB-670016                        | 1        | 1.22%   |
| Gigabyte H77N-WIFI                         | 1        | 1.22%   |
| Gigabyte H310M                             | 1        | 1.22%   |
| Gigabyte H170N-WIFI                        | 1        | 1.22%   |
| Gigabyte F2A68HM-H                         | 1        | 1.22%   |
| Gigabyte B85M-D3H                          | 1        | 1.22%   |
| Gigabyte B560M                             | 1        | 1.22%   |
| Gigabyte B550M                             | 1        | 1.22%   |
| Gigabyte AX370-Gaming                      | 1        | 1.22%   |
| Gigabyte AB350-Gaming                      | 1        | 1.22%   |
| Gigabyte 970A-DS3P                         | 1        | 1.22%   |
| Dell Precision                             | 1        | 1.22%   |
| Biostar A320MH                             | 1        | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 16       | 19.51%  |
| 2019 | 12       | 14.63%  |
| 2018 | 12       | 14.63%  |
| 2021 | 8        | 9.76%   |
| 2017 | 7        | 8.54%   |
| 2022 | 6        | 7.32%   |
| 2013 | 6        | 7.32%   |
| 2016 | 4        | 4.88%   |
| 2014 | 4        | 4.88%   |
| 2015 | 3        | 3.66%   |
| 2012 | 3        | 3.66%   |
| 2011 | 1        | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 82       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 82       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 39       | 46.99%  |
| 32.01-64.0  | 20       | 24.1%   |
| 8.01-16.0   | 11       | 13.25%  |
| 4.01-8.0    | 6        | 7.23%   |
| 24.01-32.0  | 4        | 4.82%   |
| 64.01-256.0 | 3        | 3.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 39       | 46.99%  |
| 3.01-4.0  | 22       | 26.51%  |
| 4.01-8.0  | 12       | 14.46%  |
| 1.01-2.0  | 7        | 8.43%   |
| 8.01-16.0 | 3        | 3.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 36.9%   |
| 2      | 20       | 23.81%  |
| 3      | 18       | 21.43%  |
| 4      | 9        | 10.71%  |
| 5      | 3        | 3.57%   |
| 11     | 1        | 1.19%   |
| 7      | 1        | 1.19%   |
| 6      | 1        | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 85.37%  |
| Yes       | 12       | 14.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 64.63%  |
| No        | 29       | 35.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 53.01%  |
| No        | 39       | 46.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 32       | 38.55%  |
| UK           | 8        | 9.64%   |
| France       | 5        | 6.02%   |
| Australia    | 5        | 6.02%   |
| Brazil       | 4        | 4.82%   |
| Ireland      | 3        | 3.61%   |
| Poland       | 2        | 2.41%   |
| Germany      | 2        | 2.41%   |
| Canada       | 2        | 2.41%   |
| Uzbekistan   | 1        | 1.2%    |
| Turkey       | 1        | 1.2%    |
| Thailand     | 1        | 1.2%    |
| Spain        | 1        | 1.2%    |
| South Africa | 1        | 1.2%    |
| Romania      | 1        | 1.2%    |
| Portugal     | 1        | 1.2%    |
| Philippines  | 1        | 1.2%    |
| Peru         | 1        | 1.2%    |
| Oman         | 1        | 1.2%    |
| Malaysia     | 1        | 1.2%    |
| Latvia       | 1        | 1.2%    |
| Italy        | 1        | 1.2%    |
| Israel       | 1        | 1.2%    |
| Iceland      | 1        | 1.2%    |
| Hong Kong    | 1        | 1.2%    |
| Denmark      | 1        | 1.2%    |
| Cambodia     | 1        | 1.2%    |
| Austria      | 1        | 1.2%    |
| Argentina    | 1        | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 2.41%   |
| West Bloomfield        | 1        | 1.2%    |
| Walsall                | 1        | 1.2%    |
| Vilas                  | 1        | 1.2%    |
| Verona                 | 1        | 1.2%    |
| Tuam                   | 1        | 1.2%    |
| Tashkent               | 1        | 1.2%    |
| Targoviste             | 1        | 1.2%    |
| Sterling Heights       | 1        | 1.2%    |
| Skarzysko-Kamienna     | 1        | 1.2%    |
| Siloam Springs         | 1        | 1.2%    |
| Scotts Valley          | 1        | 1.2%    |
| Sao Paulo              | 1        | 1.2%    |
| Salford                | 1        | 1.2%    |
| Salem                  | 1        | 1.2%    |
| Riga                   | 1        | 1.2%    |
| Reykjavik              | 1        | 1.2%    |
| Raszkow                | 1        | 1.2%    |
| Puchberg am Schneeberg | 1        | 1.2%    |
| Portland               | 1        | 1.2%    |
| Phnom Penh             | 1        | 1.2%    |
| Petah Tikva            | 1        | 1.2%    |
| Perth                  | 1        | 1.2%    |
| Peoria                 | 1        | 1.2%    |
| Paris                  | 1        | 1.2%    |
| Osasco                 | 1        | 1.2%    |
| Oklahoma City          | 1        | 1.2%    |
| Ocean Springs          | 1        | 1.2%    |
| Norwich                | 1        | 1.2%    |
| North York             | 1        | 1.2%    |
| Noble Park             | 1        | 1.2%    |
| Newport                | 1        | 1.2%    |
| Newcastle-under-Lyme   | 1        | 1.2%    |
| Muscat                 | 1        | 1.2%    |
| Moyeuvre-Grande        | 1        | 1.2%    |
| Moscow                 | 1        | 1.2%    |
| Milford                | 1        | 1.2%    |
| Mercedes               | 1        | 1.2%    |
| Memphis                | 1        | 1.2%    |
| Mascot                 | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 28       | 35     | 16.77%  |
| Samsung Electronics         | 19       | 36     | 11.38%  |
| WDC                         | 16       | 20     | 9.58%   |
| Kingston                    | 14       | 16     | 8.38%   |
| SanDisk                     | 13       | 15     | 7.78%   |
| Crucial                     | 13       | 16     | 7.78%   |
| Toshiba                     | 11       | 13     | 6.59%   |
| A-DATA Technology           | 5        | 5      | 2.99%   |
| PNY                         | 4        | 5      | 2.4%    |
| Phison                      | 4        | 5      | 2.4%    |
| Micron/Crucial Technology   | 4        | 4      | 2.4%    |
| Unknown                     | 4        | 5      | 2.4%    |
| Realtek Semiconductor       | 3        | 3      | 1.8%    |
| Phison Electronics          | 3        | 5      | 1.8%    |
| SK hynix                    | 2        | 2      | 1.2%    |
| MAXIO Technology (Hangzhou) | 2        | 2      | 1.2%    |
| Kingston Technology Company | 2        | 2      | 1.2%    |
| Intel                       | 2        | 3      | 1.2%    |
| Hitachi                     | 2        | 2      | 1.2%    |
| China                       | 2        | 5      | 1.2%    |
| Unknown                     | 1        | 1      | 0.6%    |
| Union Memory (Shenzhen)     | 1        | 1      | 0.6%    |
| T-FORCE                     | 1        | 1      | 0.6%    |
| SPCC                        | 1        | 3      | 0.6%    |
| Silicon Motion              | 1        | 1      | 0.6%    |
| Realtek                     | 1        | 1      | 0.6%    |
| Ramsta                      | 1        | 1      | 0.6%    |
| Mushkin                     | 1        | 1      | 0.6%    |
| KingFast                    | 1        | 1      | 0.6%    |
| Intenso                     | 1        | 1      | 0.6%    |
| HS-SSD-C100                 | 1        | 1      | 0.6%    |
| GALAX                       | 1        | 1      | 0.6%    |
| Apple                       | 1        | 1      | 0.6%    |
| ADATA Technology            | 1        | 2      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 4        | 2.14%   |
| Toshiba DT01ACA100 1TB                            | 3        | 1.6%    |
| Samsung NVMe SSD Drive 1TB                        | 3        | 1.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 1.6%    |
| Kingston SA400S37120G 120GB SSD                   | 3        | 1.6%    |
| Crucial CT1000BX500SSD1 1TB                       | 3        | 1.6%    |
| Toshiba MQ01ABD100 1TB                            | 2        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 1.07%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 2        | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2        | 1.07%   |
| SanDisk NVMe SSD Drive 500GB                      | 2        | 1.07%   |
| Samsung SSD 980 1TB                               | 2        | 1.07%   |
| Samsung SSD 840 EVO 250GB                         | 2        | 1.07%   |
| Realtek NVMe SSD Drive 256GB                      | 2        | 1.07%   |
| PNY CS900 120GB SSD                               | 2        | 1.07%   |
| Phison E12 NVMe Controller 512GB                  | 2        | 1.07%   |
| Micron/Crucial CT1000P1SSD8 1TB                   | 2        | 1.07%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1TB  | 2        | 1.07%   |
| Kingston SV300S37A120G 120GB SSD                  | 2        | 1.07%   |
| Kingston SH103S3120G 120GB SSD                    | 2        | 1.07%   |
| Crucial CT500MX500SSD1 500GB                      | 2        | 1.07%   |
| Crucial CT250MX500SSD1 250GB                      | 2        | 1.07%   |
| A-DATA SU650 240GB SSD                            | 2        | 1.07%   |
| A-DATA SU630 240GB SSD                            | 2        | 1.07%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.53%   |
| WDC WDBNCE5000PNC 500GB SSD                       | 1        | 0.53%   |
| WDC WDBNCE2500PNC 250GB SSD                       | 1        | 0.53%   |
| WDC WDBNCE0010PNC 1TB SSD                         | 1        | 0.53%   |
| WDC WD7500BPVT-80HXZT3 752GB                      | 1        | 0.53%   |
| WDC WD5000BPKT-60PK4T0 500GB                      | 1        | 0.53%   |
| WDC WD4005FZBX-00K5WB0 4TB                        | 1        | 0.53%   |
| WDC WD30EZRX-00DC0B0 3TB                          | 1        | 0.53%   |
| WDC WD2500AAKX-753CA1 250GB                       | 1        | 0.53%   |
| WDC WD15EARS-00MVWB0 1TB                          | 1        | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 1        | 0.53%   |
| WDC WD10EZEX-00WN4A0 1TB                          | 1        | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 1        | 0.53%   |
| WDC WD10EURX-83UY4Y0 1TB                          | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 34     | 52.94%  |
| WDC                 | 11       | 14     | 21.57%  |
| Toshiba             | 10       | 12     | 19.61%  |
| Hitachi             | 2        | 2      | 3.92%   |
| Samsung Electronics | 1        | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 13       | 16     | 20.31%  |
| Samsung Electronics | 12       | 21     | 18.75%  |
| Kingston            | 10       | 11     | 15.63%  |
| SanDisk             | 7        | 8      | 10.94%  |
| WDC                 | 6        | 6      | 9.38%   |
| A-DATA Technology   | 5        | 5      | 7.81%   |
| PNY                 | 4        | 5      | 6.25%   |
| China               | 2        | 5      | 3.13%   |
| SPCC                | 1        | 3      | 1.56%   |
| Ramsta              | 1        | 1      | 1.56%   |
| Mushkin             | 1        | 1      | 1.56%   |
| Intenso             | 1        | 1      | 1.56%   |
| Intel               | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 48       | 84     | 33.8%   |
| NVMe    | 46       | 60     | 32.39%  |
| HDD     | 41       | 63     | 28.87%  |
| Unknown | 7        | 9      | 4.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 68       | 149    | 57.63%  |
| NVMe | 46       | 59     | 38.98%  |
| SAS  | 4        | 8      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 76     | 47.47%  |
| 0.51-1.0   | 32       | 41     | 32.32%  |
| 1.01-2.0   | 7        | 14     | 7.07%   |
| 3.01-4.0   | 5        | 6      | 5.05%   |
| 2.01-3.0   | 4        | 6      | 4.04%   |
| 4.01-10.0  | 4        | 4      | 4.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 31.71%  |
| 501-1000       | 19       | 23.17%  |
| 251-500        | 18       | 21.95%  |
| 1001-2000      | 10       | 12.2%   |
| More than 3000 | 6        | 7.32%   |
| 2001-3000      | 1        | 1.22%   |
| 51-100         | 1        | 1.22%   |
| Unknown        | 1        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 38.1%   |
| 51-100         | 19       | 22.62%  |
| 101-250        | 12       | 14.29%  |
| 21-50          | 10       | 11.9%   |
| 251-500        | 3        | 3.57%   |
| 501-1000       | 3        | 3.57%   |
| More than 3000 | 2        | 2.38%   |
| 2001-3000      | 1        | 1.19%   |
| 1001-2000      | 1        | 1.19%   |
| Unknown        | 1        | 1.19%   |

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
| Detected | 83       | 216    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 45       | 34.62%  |
| Intel                        | 35       | 26.92%  |
| Samsung Electronics          | 10       | 7.69%   |
| SanDisk                      | 7        | 5.38%   |
| Phison Electronics           | 7        | 5.38%   |
| Kingston Technology Company  | 6        | 4.62%   |
| Micron/Crucial Technology    | 4        | 3.08%   |
| Realtek Semiconductor        | 3        | 2.31%   |
| SK hynix                     | 2        | 1.54%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.54%   |
| Union Memory (Shenzhen)      | 1        | 0.77%   |
| Toshiba America Info Systems | 1        | 0.77%   |
| Silicon Motion               | 1        | 0.77%   |
| Seagate Technology           | 1        | 0.77%   |
| Marvell Technology Group     | 1        | 0.77%   |
| INNOGRIT                     | 1        | 0.77%   |
| ASMedia Technology           | 1        | 0.77%   |
| Apple                        | 1        | 0.77%   |
| ADATA Technology             | 1        | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30       | 18.75%  |
| AMD 400 Series Chipset SATA Controller                                         | 13       | 8.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 10       | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 3.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 3.13%   |
| Phison E12 NVMe Controller                                                     | 4        | 2.5%    |
| AMD FCH SATA Controller D                                                      | 4        | 2.5%    |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 2.5%    |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.88%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 1.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.88%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.88%   |
| SanDisk Non-Volatile memory controller                                         | 2        | 1.25%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.25%   |
| Realtek NVMe Controller                                                        | 2        | 1.25%   |
| Phison Electronics Non-Volatile memory controller                              | 2        | 1.25%   |
| Micron/Crucial NVMe Storage Controller                                         | 2        | 1.25%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 1.25%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 2        | 1.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 1.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.25%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.63%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.63%   |
| SK hynix BC511                                                                 | 1        | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.63%   |
| Seagate FireCuda 510 SSD                                                       | 1        | 0.63%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.63%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.63%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1        | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.63%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 74       | 58.27%  |
| NVMe | 46       | 36.22%  |
| RAID | 5        | 3.94%   |
| IDE  | 2        | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 47       | 57.32%  |
| Intel  | 35       | 42.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics  | 5        | 6.1%    |
| AMD Ryzen 9 5900X 12-Core Processor     | 4        | 4.88%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3        | 3.66%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3        | 3.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 2        | 2.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2        | 2.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 2.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2        | 2.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 2.44%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 2        | 2.44%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 2        | 2.44%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 2        | 2.44%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2        | 2.44%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 2        | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 2.44%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 2        | 2.44%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2        | 2.44%   |
| Intel Xeon W-3223 CPU @ 3.50GHz         | 1        | 1.22%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 1        | 1.22%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 1.22%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 1.22%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 1        | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.22%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1        | 1.22%   |
| Intel Core i5-8500T CPU @ 2.10GHz       | 1        | 1.22%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1        | 1.22%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 1        | 1.22%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1        | 1.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1        | 1.22%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1        | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1        | 1.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1        | 1.22%   |
| Intel Core i3-7100 CPU @ 3.90GHz        | 1        | 1.22%   |
| Intel Celeron CPU G1620 @ 2.70GHz       | 1        | 1.22%   |
| Intel 12th Gen Core i7-12700F           | 1        | 1.22%   |
| Intel 12th Gen Core i3-12100F           | 1        | 1.22%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz | 1        | 1.22%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz | 1        | 1.22%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 21       | 25.61%  |
| Intel Core i5          | 13       | 15.85%  |
| Intel Core i7          | 10       | 12.2%   |
| AMD Ryzen 9            | 9        | 10.98%  |
| AMD Ryzen 7            | 9        | 10.98%  |
| Other                  | 5        | 6.1%    |
| Intel Xeon             | 3        | 3.66%   |
| Intel Core i3          | 3        | 3.66%   |
| AMD Ryzen 5 PRO        | 2        | 2.44%   |
| AMD FX                 | 2        | 2.44%   |
| Intel Celeron          | 1        | 1.22%   |
| AMD Ryzen Threadripper | 1        | 1.22%   |
| AMD Ryzen 7 PRO        | 1        | 1.22%   |
| AMD Athlon X4          | 1        | 1.22%   |
| AMD Athlon             | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 27       | 32.93%  |
| 4      | 26       | 31.71%  |
| 8      | 15       | 18.29%  |
| 12     | 9        | 10.98%  |
| 2      | 4        | 4.88%   |
| 3      | 1        | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 66       | 80.49%  |
| 1      | 16       | 19.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 82       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 14       | 17.07%  |
| Zen+        | 11       | 13.41%  |
| Zen 2       | 10       | 12.2%   |
| Haswell     | 10       | 12.2%   |
| KabyLake    | 9        | 10.98%  |
| Zen         | 7        | 8.54%   |
| Unknown     | 7        | 8.54%   |
| Skylake     | 4        | 4.88%   |
| IvyBridge   | 4        | 4.88%   |
| SandyBridge | 2        | 2.44%   |
| Piledriver  | 2        | 2.44%   |
| Steamroller | 1        | 1.22%   |
| CometLake   | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 57       | 61.29%  |
| Nvidia | 23       | 24.73%  |
| Intel  | 13       | 13.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 16.67%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.17%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 4.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 4.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 4.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 4.17%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 3.13%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.08%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.08%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.08%   |
| Intel HD Graphics 530                                                       | 2        | 2.08%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.08%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 2.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.04%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.04%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.04%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.04%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1        | 1.04%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 1.04%   |
| AMD Raphael                                                                 | 1        | 1.04%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 1.04%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.04%   |
| AMD Navi 21 Pro-XTA [Radeon Pro W6900X]                                     | 1        | 1.04%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 51       | 60.71%  |
| 1 x Nvidia     | 20       | 23.81%  |
| 1 x Intel      | 4        | 4.76%   |
| 2 x AMD        | 3        | 3.57%   |
| Intel + Nvidia | 2        | 2.38%   |
| Intel + AMD    | 2        | 2.38%   |
| AMD + Nvidia   | 2        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 63       | 76.83%  |
| Proprietary | 19       | 23.17%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 77.11%  |
| 3.01-4.0   | 7        | 8.43%   |
| 7.01-8.0   | 6        | 7.23%   |
| 5.01-6.0   | 2        | 2.41%   |
| 8.01-16.0  | 2        | 2.41%   |
| 2.01-3.0   | 1        | 1.2%    |
| 16.01-24.0 | 1        | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 12.82%  |
| Goldstar             | 10       | 12.82%  |
| AOC                  | 6        | 7.69%   |
| Acer                 | 6        | 7.69%   |
| Hewlett-Packard      | 4        | 5.13%   |
| ViewSonic            | 3        | 3.85%   |
| Sony                 | 3        | 3.85%   |
| Pixio                | 3        | 3.85%   |
| Philips              | 3        | 3.85%   |
| Dell                 | 3        | 3.85%   |
| ASUSTek Computer     | 3        | 3.85%   |
| Ancor Communications | 3        | 3.85%   |
| Toshiba              | 2        | 2.56%   |
| MSI                  | 2        | 2.56%   |
| ___                  | 1        | 1.28%   |
| WIT                  | 1        | 1.28%   |
| Wacom                | 1        | 1.28%   |
| Valve                | 1        | 1.28%   |
| Unknown              | 1        | 1.28%   |
| Sun                  | 1        | 1.28%   |
| Sceptre Tech         | 1        | 1.28%   |
| Roku                 | 1        | 1.28%   |
| ONN                  | 1        | 1.28%   |
| Insignia             | 1        | 1.28%   |
| Huion                | 1        | 1.28%   |
| HJW                  | 1        | 1.28%   |
| Hitachi              | 1        | 1.28%   |
| HannStar             | 1        | 1.28%   |
| DZX                  | 1        | 1.28%   |
| BenQ                 | 1        | 1.28%   |
| AOpen                | 1        | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Pixio PX275h WAM2700 2560x1440 600x330mm 27.0-inch                      | 2        | 2.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 2.5%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 2        | 2.5%    |
| ___ LCD TV ___9000 1360x768                                             | 1        | 1.25%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 1.25%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 1.25%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 1.25%   |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1        | 1.25%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 1.25%   |
| Valve LCD Monitor VLV91A8                                               | 1        | 1.25%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.25%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 1.25%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 1.25%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 1.25%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1.25%   |
| Sony TV *00 SNY3F05 3840x2160 1085x610mm 49.0-inch                      | 1        | 1.25%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 1.25%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 1.25%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 1.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM7269 3840x2160 700x390mm 31.5-inch   | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch   | 1        | 1.25%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 1.25%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 1.25%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 1.25%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1        | 1.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.25%   |
| Roku 100012590 RKU0B01 1920x1080 698x392mm 31.5-inch                    | 1        | 1.25%   |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 1.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.25%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 1.25%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 1.25%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                    | 1        | 1.25%   |
| MSI MAG272C MSI3CA5 1920x1080 598x336mm 27.0-inch                       | 1        | 1.25%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                         | 1        | 1.25%   |
| Insignia 48DR420NA16 BBY3253 1920x1080 1054x591mm 47.6-inch             | 1        | 1.25%   |
| Huion GT-133 HAT1330 1920x1080 294x165mm 13.3-inch                      | 1        | 1.25%   |
| HJW MACROSILICON HJW1836 1400x1050 530x290mm 23.8-inch                  | 1        | 1.25%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 1        | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 51.32%  |
| 3840x2160 (4K)     | 18       | 23.68%  |
| 2560x1440 (QHD)    | 8        | 10.53%  |
| 2560x1080          | 2        | 2.63%   |
| 1920x1200 (WUXGA)  | 2        | 2.63%   |
| 3840x1080          | 1        | 1.32%   |
| 1680x1050 (WSXGA+) | 1        | 1.32%   |
| 1440x900 (WXGA+)   | 1        | 1.32%   |
| 1400x1050          | 1        | 1.32%   |
| 1366x768 (WXGA)    | 1        | 1.32%   |
| 1360x768           | 1        | 1.32%   |
| Unknown            | 1        | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 17       | 22.08%  |
| 31      | 11       | 14.29%  |
| 24      | 11       | 14.29%  |
| 23      | 11       | 14.29%  |
| 21      | 5        | 6.49%   |
| 72      | 4        | 5.19%   |
| 84      | 3        | 3.9%    |
| 48      | 2        | 2.6%    |
| 15      | 2        | 2.6%    |
| Unknown | 2        | 2.6%    |
| 75      | 1        | 1.3%    |
| 74      | 1        | 1.3%    |
| 65      | 1        | 1.3%    |
| 57      | 1        | 1.3%    |
| 47      | 1        | 1.3%    |
| 46      | 1        | 1.3%    |
| 34      | 1        | 1.3%    |
| 32      | 1        | 1.3%    |
| 18      | 1        | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 35       | 46.67%  |
| 601-700     | 13       | 17.33%  |
| 1501-2000   | 9        | 12%     |
| 401-500     | 6        | 8%      |
| 1001-1500   | 6        | 8%      |
| 701-800     | 2        | 2.67%   |
| 301-350     | 2        | 2.67%   |
| Unknown     | 2        | 2.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 65       | 89.04%  |
| 16/10   | 5        | 6.85%   |
| 32/9    | 1        | 1.37%   |
| 21/9    | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 28.21%  |
| 301-350        | 17       | 21.79%  |
| 351-500        | 13       | 16.67%  |
| More than 1000 | 12       | 15.38%  |
| 251-300        | 5        | 6.41%   |
| 501-1000       | 3        | 3.85%   |
| Unknown        | 2        | 2.56%   |
| 151-200        | 1        | 1.28%   |
| 141-150        | 1        | 1.28%   |
| 101-110        | 1        | 1.28%   |
| 91-100         | 1        | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 48       | 64%     |
| 101-120 | 12       | 16%     |
| 1-50    | 7        | 9.33%   |
| 121-160 | 5        | 6.67%   |
| Unknown | 2        | 2.67%   |
| 161-240 | 1        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 73       | 87.95%  |
| 2     | 10       | 12.05%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 54       | 40.91%  |
| Intel                         | 43       | 32.58%  |
| Broadcom                      | 7        | 5.3%    |
| TP-Link                       | 6        | 4.55%   |
| Microsoft                     | 5        | 3.79%   |
| Qualcomm Atheros              | 3        | 2.27%   |
| Samsung Electronics           | 2        | 1.52%   |
| Ralink Technology             | 2        | 1.52%   |
| MediaTek                      | 2        | 1.52%   |
| OPPO Electronics              | 1        | 0.76%   |
| OnePlus Technology (Shenzhen) | 1        | 0.76%   |
| Huawei Technologies           | 1        | 0.76%   |
| Google                        | 1        | 0.76%   |
| D-Link                        | 1        | 0.76%   |
| ASUSTek Computer              | 1        | 0.76%   |
| Aquantia                      | 1        | 0.76%   |
| Apple                         | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 46       | 30.26%  |
| Intel Wi-Fi 6 AX200                                                                           | 8        | 5.26%   |
| Intel Ethernet Connection (2) I219-V                                                          | 8        | 5.26%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 3.95%   |
| Intel Ethernet Controller I225-V                                                              | 6        | 3.95%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 3.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4        | 2.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 4        | 2.63%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 3        | 1.97%   |
| Intel Wireless 8260                                                                           | 3        | 1.97%   |
| Intel Ethernet Connection (2) I218-V                                                          | 3        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3        | 1.97%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.32%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.32%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.66%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.66%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.66%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.66%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.66%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.66%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.66%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.66%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.66%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 0.66%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                                          | 1        | 0.66%   |
| OnePlus (Shenzhen) OnePlus                                                                    | 1        | 0.66%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 0.66%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1        | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 36.84%  |
| Realtek Semiconductor | 10       | 17.54%  |
| Broadcom              | 7        | 12.28%  |
| TP-Link               | 6        | 10.53%  |
| Microsoft             | 5        | 8.77%   |
| Ralink Technology     | 2        | 3.51%   |
| Qualcomm Atheros      | 2        | 3.51%   |
| MediaTek              | 2        | 3.51%   |
| D-Link                | 1        | 1.75%   |
| ASUSTek Computer      | 1        | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 8        | 14.04%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4        | 7.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 4        | 7.02%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 3        | 5.26%   |
| Intel Wireless 8260                                                                           | 3        | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 3.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.75%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.75%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.75%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.75%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.75%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.75%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.75%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1        | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.75%   |
| Intel Wireless 7265                                                                           | 1        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.75%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.75%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 1        | 1.75%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.75%   |
| Broadcom Network controller                                                                   | 1        | 1.75%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 1.75%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.75%   |
| ASUS 802.11ac NIC                                                                             | 1        | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 53       | 56.99%  |
| Intel                         | 31       | 33.33%  |
| Samsung Electronics           | 2        | 2.15%   |
| Qualcomm Atheros              | 2        | 2.15%   |
| OPPO Electronics              | 1        | 1.08%   |
| OnePlus Technology (Shenzhen) | 1        | 1.08%   |
| Huawei Technologies           | 1        | 1.08%   |
| Google                        | 1        | 1.08%   |
| Aquantia                      | 1        | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46       | 48.94%  |
| Intel Ethernet Connection (2) I219-V                              | 8        | 8.51%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.38%   |
| Intel Ethernet Controller I225-V                                  | 6        | 6.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 5.32%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.19%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.13%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.06%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1        | 1.06%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.06%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.06%   |
| Huawei ATU-L21                                                    | 1        | 1.06%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.06%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 60.29%  |
| WiFi     | 53       | 38.97%  |
| Modem    | 1        | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 77.65%  |
| WiFi     | 19       | 22.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 56.1%   |
| 2     | 30       | 36.59%  |
| 3     | 6        | 7.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 67.07%  |
| Yes  | 27       | 32.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 40.43%  |
| Cambridge Silicon Radio         | 9        | 19.15%  |
| ASUSTek Computer                | 5        | 10.64%  |
| Realtek Semiconductor           | 4        | 8.51%   |
| MediaTek                        | 2        | 4.26%   |
| Broadcom                        | 2        | 4.26%   |
| TP-Link                         | 1        | 2.13%   |
| Realtek                         | 1        | 2.13%   |
| Qualcomm Atheros Communications | 1        | 2.13%   |
| Integrated System Solution      | 1        | 2.13%   |
| IMC Networks                    | 1        | 2.13%   |
| Apple                           | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 9        | 19.15%  |
| Intel AX200 Bluetooth                                 | 7        | 14.89%  |
| Intel Bluetooth wireless interface                    | 4        | 8.51%   |
| Realtek Bluetooth Radio                               | 3        | 6.38%   |
| Intel AX210 Bluetooth                                 | 3        | 6.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 6.38%   |
| MediaTek Wireless_Device                              | 2        | 4.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 4.26%   |
| TP-Link UB500 Adapter                                 | 1        | 2.13%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.13%   |
| Realtek Bluetooth Radio                               | 1        | 2.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.13%   |
| Intel Bluetooth Device                                | 1        | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.13%   |
| Intel AX201 Bluetooth                                 | 1        | 2.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.13%   |
| IMC Networks Bluetooth Device                         | 1        | 2.13%   |
| ASUS BCM20702A0                                       | 1        | 2.13%   |
| ASUS ASUS USB-BT500                                   | 1        | 2.13%   |
| Apple Bluetooth Host Controller                       | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 67       | 44.37%  |
| Intel                    | 35       | 23.18%  |
| Nvidia                   | 23       | 15.23%  |
| Logitech                 | 6        | 3.97%   |
| Valve Software           | 2        | 1.32%   |
| SteelSeries ApS          | 2        | 1.32%   |
| Medeli Electronics       | 2        | 1.32%   |
| Corsair                  | 2        | 1.32%   |
| C-Media Electronics      | 2        | 1.32%   |
| Apple                    | 2        | 1.32%   |
| Tenx Technology          | 1        | 0.66%   |
| Realtek Semiconductor    | 1        | 0.66%   |
| Quanta                   | 1        | 0.66%   |
| Micro Star International | 1        | 0.66%   |
| Kingston Technology      | 1        | 0.66%   |
| JMTek                    | 1        | 0.66%   |
| Focusrite-Novation       | 1        | 0.66%   |
| Creative Labs            | 1        | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 8.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17       | 8.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16       | 8.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 7.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 6.57%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 4.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 3.54%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 2.53%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.02%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.52%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.52%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.52%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 2        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.01%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.01%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.01%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.51%   |
| SteelSeries ApS SteelSeries SC2 USB Headset                                | 1        | 0.51%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 0.51%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.51%   |
| Quanta USB Audio                                                           | 1        | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.51%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.51%   |

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
| Valve Software                | 2        | 20%     |
| Tobii Technology AB           | 1        | 10%     |
| Sunplus Innovation Technology | 1        | 10%     |
| Quanta                        | 1        | 10%     |
| Microdia                      | 1        | 10%     |
| Magic Control Technology      | 1        | 10%     |
| Logitech                      | 1        | 10%     |
| Generalplus Technology        | 1        | 10%     |
| Apple                         | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Valve Software 3D Camera        | 2        | 20%     |
| Tobii AB EyeChip                | 1        | 10%     |
| Sunplus USB 2.0 Camera          | 1        | 10%     |
| Quanta HD Camera                | 1        | 10%     |
| Microdia Webcam Vitade AF       | 1        | 10%     |
| Magic Control j5 WebCam JVCU100 | 1        | 10%     |
| Logitech HD Webcam C525         | 1        | 10%     |
| Generalplus GENERAL WEBCAM      | 1        | 10%     |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 10%     |

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
| 0     | 61       | 73.49%  |
| 1     | 16       | 19.28%  |
| 2     | 5        | 6.02%   |
| 4     | 1        | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 16       | 53.33%  |
| Unassigned class         | 4        | 13.33%  |
| Graphics card            | 3        | 10%     |
| Net/ethernet             | 2        | 6.67%   |
| Multimedia controller    | 2        | 6.67%   |
| Sound                    | 1        | 3.33%   |
| Fingerprint reader       | 1        | 3.33%   |
| Communication controller | 1        | 3.33%   |

