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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| SteamOS 3.4                  | 40       | 50%     |
| SteamOS 3.3                  | 24       | 30%     |
| SteamOS 3.2 (steamdeck-main) | 7        | 8.75%   |
| SteamOS                      | 4        | 5%      |
| SteamOS Snapshot             | 3        | 3.75%   |
| SteamOS 4                    | 1        | 1.25%   |
| SteamOS 3.2                  | 1        | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 32       | 41.03%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 14.1%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 12.82%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 8.97%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 6        | 7.69%   |
| 5.13.0-valve36-1-neptune                           | 3        | 3.85%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 2.56%   |
| 6.1.12-valve2-1-neptune-61                         | 1        | 1.28%   |
| 5.15.79-1-lts                                      | 1        | 1.28%   |
| 5.15.60-1-lts                                      | 1        | 1.28%   |
| 5.13.0-valve24-1-neptune                           | 1        | 1.28%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 1.28%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 1        | 1.28%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 1.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 69       | 88.46%  |
| 5.18.1  | 6        | 7.69%   |
| 6.1.12  | 1        | 1.28%   |
| 5.15.79 | 1        | 1.28%   |
| 5.15.60 | 1        | 1.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 69       | 88.46%  |
| 5.18    | 6        | 7.69%   |
| 5.15    | 2        | 2.56%   |
| 6.1     | 1        | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 77       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 77       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 77       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 68       | 87.18%  |
| fr_FR | 3        | 3.85%   |
| pt_PT | 1        | 1.28%   |
| pt_BR | 1        | 1.28%   |
| en_IE | 1        | 1.28%   |
| en_GB | 1        | 1.28%   |
| de_DE | 1        | 1.28%   |
| de_AT | 1        | 1.28%   |
| C     | 1        | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 77       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 74       | 96.1%   |
| Tmpfs | 3        | 3.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 22       | 28.57%  |
| Gigabyte Technology                  | 20       | 25.97%  |
| MSI                                  | 11       | 14.29%  |
| ASRock                               | 8        | 10.39%  |
| Hewlett-Packard                      | 6        | 7.79%   |
| Dell                                 | 5        | 6.49%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.3%    |
| Biostar                              | 1        | 1.3%    |
| Apple                                | 1        | 1.3%    |
| Alienware                            | 1        | 1.3%    |
| Acer                                 | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Gigabyte B450 AORUS M                      | 4        | 5.19%   |
| ASUS All Series                            | 4        | 5.19%   |
| Gigabyte B550 GAMING X V2                  | 2        | 2.6%    |
| Dell OptiPlex 9010                         | 2        | 2.6%    |
| ASUS ROG STRIX B550-F GAMING               | 2        | 2.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.3%    |
| MSI MS-7D73                                | 1        | 1.3%    |
| MSI MS-7C37                                | 1        | 1.3%    |
| MSI MS-7C02                                | 1        | 1.3%    |
| MSI MS-7B89                                | 1        | 1.3%    |
| MSI MS-7B79                                | 1        | 1.3%    |
| MSI MS-7B09                                | 1        | 1.3%    |
| MSI MS-7A33                                | 1        | 1.3%    |
| MSI MS-7817                                | 1        | 1.3%    |
| MSI MS-7693                                | 1        | 1.3%    |
| MSI MPG H510 Trident 3 (MS-B935)           | 1        | 1.3%    |
| MSI H310 Gaming Trident3 (MS-B920)         | 1        | 1.3%    |
| HP Victus by 15L Gaming Desktop TG02-0xxx  | 1        | 1.3%    |
| HP ProDesk 600 G4 MT                       | 1        | 1.3%    |
| HP ProDesk 405 G4 Desktop Mini             | 1        | 1.3%    |
| HP Pavilion Gaming Desktop TG01-2xxx       | 1        | 1.3%    |
| HP Pavilion Gaming Desktop 690-00xx        | 1        | 1.3%    |
| HP EliteDesk 705 G4 DM 65W (TAA)           | 1        | 1.3%    |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.3%    |
| Gigabyte X570 GAMING X                     | 1        | 1.3%    |
| Gigabyte MBB-670016                        | 1        | 1.3%    |
| Gigabyte H310M S2V 2.0                     | 1        | 1.3%    |
| Gigabyte H170N-WIFI                        | 1        | 1.3%    |
| Gigabyte F2A68HM-H                         | 1        | 1.3%    |
| Gigabyte B85M-D3H                          | 1        | 1.3%    |
| Gigabyte B560M AORUS PRO                   | 1        | 1.3%    |
| Gigabyte B550M DS3H                        | 1        | 1.3%    |
| Gigabyte B450M DS3H V2                     | 1        | 1.3%    |
| Gigabyte B450M DS3H                        | 1        | 1.3%    |
| Gigabyte AX370-Gaming                      | 1        | 1.3%    |
| Gigabyte AB350-Gaming 3                    | 1        | 1.3%    |
| Gigabyte 970A-DS3P FX                      | 1        | 1.3%    |
| Dell Precision Tower 5810                  | 1        | 1.3%    |
| Dell OptiPlex 990                          | 1        | 1.3%    |
| Dell OptiPlex 9020                         | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 8        | 10.39%  |
| Gigabyte B450                              | 4        | 5.19%   |
| Dell OptiPlex                              | 4        | 5.19%   |
| ASUS All                                   | 4        | 5.19%   |
| ASUS ROG                                   | 3        | 3.9%    |
| HP ProDesk                                 | 2        | 2.6%    |
| HP Pavilion                                | 2        | 2.6%    |
| Gigabyte X570                              | 2        | 2.6%    |
| Gigabyte B550                              | 2        | 2.6%    |
| Gigabyte B450M                             | 2        | 2.6%    |
| ASUS TUF                                   | 2        | 2.6%    |
| ASRock B550                                | 2        | 2.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.3%    |
| MSI MS-7D73                                | 1        | 1.3%    |
| MSI MS-7C37                                | 1        | 1.3%    |
| MSI MS-7C02                                | 1        | 1.3%    |
| MSI MS-7B89                                | 1        | 1.3%    |
| MSI MS-7B79                                | 1        | 1.3%    |
| MSI MS-7B09                                | 1        | 1.3%    |
| MSI MS-7A33                                | 1        | 1.3%    |
| MSI MS-7817                                | 1        | 1.3%    |
| MSI MS-7693                                | 1        | 1.3%    |
| MSI MPG                                    | 1        | 1.3%    |
| MSI H310                                   | 1        | 1.3%    |
| HP Victus                                  | 1        | 1.3%    |
| HP EliteDesk                               | 1        | 1.3%    |
| Gigabyte MBB-670016                        | 1        | 1.3%    |
| Gigabyte H310M                             | 1        | 1.3%    |
| Gigabyte H170N-WIFI                        | 1        | 1.3%    |
| Gigabyte F2A68HM-H                         | 1        | 1.3%    |
| Gigabyte B85M-D3H                          | 1        | 1.3%    |
| Gigabyte B560M                             | 1        | 1.3%    |
| Gigabyte B550M                             | 1        | 1.3%    |
| Gigabyte AX370-Gaming                      | 1        | 1.3%    |
| Gigabyte AB350-Gaming                      | 1        | 1.3%    |
| Gigabyte 970A-DS3P                         | 1        | 1.3%    |
| Dell Precision                             | 1        | 1.3%    |
| Biostar A320MH                             | 1        | 1.3%    |
| ASUS Z170                                  | 1        | 1.3%    |
| ASUS M80CJ-O                               | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 16       | 20.78%  |
| 2018 | 12       | 15.58%  |
| 2019 | 11       | 14.29%  |
| 2021 | 8        | 10.39%  |
| 2017 | 7        | 9.09%   |
| 2022 | 6        | 7.79%   |
| 2013 | 6        | 7.79%   |
| 2016 | 4        | 5.19%   |
| 2015 | 3        | 3.9%    |
| 2014 | 2        | 2.6%    |
| 2012 | 1        | 1.3%    |
| 2011 | 1        | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 77       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 46.75%  |
| 32.01-64.0  | 18       | 23.38%  |
| 8.01-16.0   | 11       | 14.29%  |
| 4.01-8.0    | 5        | 6.49%   |
| 24.01-32.0  | 4        | 5.19%   |
| 64.01-256.0 | 3        | 3.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 37       | 48.05%  |
| 3.01-4.0  | 19       | 24.68%  |
| 4.01-8.0  | 12       | 15.58%  |
| 1.01-2.0  | 7        | 9.09%   |
| 8.01-16.0 | 2        | 2.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 34.62%  |
| 2      | 19       | 24.36%  |
| 3      | 17       | 21.79%  |
| 4      | 9        | 11.54%  |
| 5      | 3        | 3.85%   |
| 11     | 1        | 1.28%   |
| 7      | 1        | 1.28%   |
| 6      | 1        | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 87.01%  |
| Yes       | 10       | 12.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 51       | 66.23%  |
| No        | 26       | 33.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 52.56%  |
| No        | 37       | 47.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 31       | 39.74%  |
| UK           | 8        | 10.26%  |
| France       | 5        | 6.41%   |
| Australia    | 5        | 6.41%   |
| Brazil       | 4        | 5.13%   |
| Ireland      | 3        | 3.85%   |
| Poland       | 2        | 2.56%   |
| Canada       | 2        | 2.56%   |
| Turkey       | 1        | 1.28%   |
| Thailand     | 1        | 1.28%   |
| Spain        | 1        | 1.28%   |
| South Africa | 1        | 1.28%   |
| Romania      | 1        | 1.28%   |
| Portugal     | 1        | 1.28%   |
| Philippines  | 1        | 1.28%   |
| Oman         | 1        | 1.28%   |
| Malaysia     | 1        | 1.28%   |
| Latvia       | 1        | 1.28%   |
| Italy        | 1        | 1.28%   |
| Iceland      | 1        | 1.28%   |
| Hong Kong    | 1        | 1.28%   |
| Germany      | 1        | 1.28%   |
| Denmark      | 1        | 1.28%   |
| Cambodia     | 1        | 1.28%   |
| Austria      | 1        | 1.28%   |
| Argentina    | 1        | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 2.56%   |
| West Bloomfield        | 1        | 1.28%   |
| Walsall                | 1        | 1.28%   |
| Vilas                  | 1        | 1.28%   |
| Verona                 | 1        | 1.28%   |
| Tuam                   | 1        | 1.28%   |
| Targoviste             | 1        | 1.28%   |
| Sterling Heights       | 1        | 1.28%   |
| Skarzysko-Kamienna     | 1        | 1.28%   |
| Siloam Springs         | 1        | 1.28%   |
| Scotts Valley          | 1        | 1.28%   |
| Sao Paulo              | 1        | 1.28%   |
| Salford                | 1        | 1.28%   |
| Salem                  | 1        | 1.28%   |
| Riga                   | 1        | 1.28%   |
| Reykjavik              | 1        | 1.28%   |
| Raszkow                | 1        | 1.28%   |
| Puchberg am Schneeberg | 1        | 1.28%   |
| Portland               | 1        | 1.28%   |
| Phnom Penh             | 1        | 1.28%   |
| Perth                  | 1        | 1.28%   |
| Peoria                 | 1        | 1.28%   |
| Paris                  | 1        | 1.28%   |
| Osasco                 | 1        | 1.28%   |
| Oklahoma City          | 1        | 1.28%   |
| Norwich                | 1        | 1.28%   |
| North York             | 1        | 1.28%   |
| Noble Park             | 1        | 1.28%   |
| Newport                | 1        | 1.28%   |
| Newcastle-under-Lyme   | 1        | 1.28%   |
| Muscat                 | 1        | 1.28%   |
| Moyeuvre-Grande        | 1        | 1.28%   |
| Moscow                 | 1        | 1.28%   |
| Milford                | 1        | 1.28%   |
| Mercedes               | 1        | 1.28%   |
| Memphis                | 1        | 1.28%   |
| Mascot                 | 1        | 1.28%   |
| Loveland               | 1        | 1.28%   |
| Lisbon                 | 1        | 1.28%   |
| Limerick               | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 27       | 34     | 17.09%  |
| Samsung Electronics         | 17       | 34     | 10.76%  |
| Kingston                    | 14       | 16     | 8.86%   |
| WDC                         | 13       | 17     | 8.23%   |
| SanDisk                     | 13       | 15     | 8.23%   |
| Crucial                     | 12       | 15     | 7.59%   |
| Toshiba                     | 10       | 12     | 6.33%   |
| A-DATA Technology           | 5        | 5      | 3.16%   |
| PNY                         | 4        | 5      | 2.53%   |
| Phison                      | 4        | 5      | 2.53%   |
| Micron/Crucial Technology   | 4        | 4      | 2.53%   |
| Unknown                     | 4        | 5      | 2.53%   |
| Realtek Semiconductor       | 3        | 3      | 1.9%    |
| Phison Electronics          | 3        | 5      | 1.9%    |
| SK hynix                    | 2        | 2      | 1.27%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 1.27%   |
| Kingston Technology Company | 2        | 2      | 1.27%   |
| Intel                       | 2        | 2      | 1.27%   |
| China                       | 2        | 5      | 1.27%   |
| Unknown                     | 1        | 1      | 0.63%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.63%   |
| T-FORCE                     | 1        | 1      | 0.63%   |
| SPCC                        | 1        | 3      | 0.63%   |
| Silicon Motion              | 1        | 1      | 0.63%   |
| Realtek                     | 1        | 1      | 0.63%   |
| Ramsta                      | 1        | 1      | 0.63%   |
| Mushkin                     | 1        | 1      | 0.63%   |
| KingFast                    | 1        | 1      | 0.63%   |
| Intenso                     | 1        | 1      | 0.63%   |
| HS-SSD-C100                 | 1        | 1      | 0.63%   |
| Hitachi                     | 1        | 1      | 0.63%   |
| GALAX                       | 1        | 1      | 0.63%   |
| Apple                       | 1        | 1      | 0.63%   |
| ADATA Technology            | 1        | 2      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Unknown                                             | 4        | 2.25%   |
| Samsung NVMe SSD Drive 1TB                          | 3        | 1.69%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 1.69%   |
| Crucial CT1000BX500SSD1 1TB                         | 3        | 1.69%   |
| Toshiba MQ01ABD100 1TB                              | 2        | 1.12%   |
| Toshiba DT01ACA100 1TB                              | 2        | 1.12%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.12%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2        | 1.12%   |
| SanDisk NVMe SSD Drive 500GB                        | 2        | 1.12%   |
| Samsung SSD 980 1TB                                 | 2        | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 1.12%   |
| Realtek NVMe SSD Drive 256GB                        | 2        | 1.12%   |
| PNY CS900 120GB SSD                                 | 2        | 1.12%   |
| Phison E12 NVMe Controller 256GB                    | 2        | 1.12%   |
| Micron/Crucial CT1000P1SSD8 1TB                     | 2        | 1.12%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 2        | 1.12%   |
| Kingston SV300S37A120G 120GB SSD                    | 2        | 1.12%   |
| Kingston SH103S3120G 120GB SSD                      | 2        | 1.12%   |
| Crucial CT500MX500SSD1 500GB                        | 2        | 1.12%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 1.12%   |
| A-DATA SU650 240GB SSD                              | 2        | 1.12%   |
| A-DATA SU630 240GB SSD                              | 2        | 1.12%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.56%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.56%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.56%   |
| WDC WDBNCE2500PNC 250GB SSD                         | 1        | 0.56%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.56%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1        | 0.56%   |
| WDC WD5000BPKT-60PK4T0 500GB                        | 1        | 0.56%   |
| WDC WD30EZRX-00DC0B0 3TB                            | 1        | 0.56%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 0.56%   |
| WDC WD15EARS-00MVWB0 1TB                            | 1        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 0.56%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 1        | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 0.56%   |
| WDC WD10EURX-83UY4Y0 1TB                            | 1        | 0.56%   |
| WDC WD10EURX-63FH1Y0 1TB                            | 1        | 0.56%   |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.56%   |
| Unknown NVMe SSD Drive 512GB                        | 1        | 0.56%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 33     | 56.52%  |
| WDC                 | 9        | 12     | 19.57%  |
| Toshiba             | 9        | 11     | 19.57%  |
| Samsung Electronics | 1        | 1      | 2.17%   |
| Hitachi             | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 12       | 15     | 19.67%  |
| Samsung Electronics | 11       | 20     | 18.03%  |
| Kingston            | 10       | 11     | 16.39%  |
| SanDisk             | 7        | 8      | 11.48%  |
| WDC                 | 5        | 5      | 8.2%    |
| A-DATA Technology   | 5        | 5      | 8.2%    |
| PNY                 | 4        | 5      | 6.56%   |
| China               | 2        | 5      | 3.28%   |
| SPCC                | 1        | 3      | 1.64%   |
| Ramsta              | 1        | 1      | 1.64%   |
| Mushkin             | 1        | 1      | 1.64%   |
| Intenso             | 1        | 1      | 1.64%   |
| Intel               | 1        | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 45       | 58     | 33.58%  |
| SSD     | 45       | 81     | 33.58%  |
| HDD     | 37       | 58     | 27.61%  |
| Unknown | 7        | 9      | 5.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 62       | 141    | 55.86%  |
| NVMe | 45       | 57     | 40.54%  |
| SAS  | 4        | 8      | 3.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 72     | 46.74%  |
| 0.51-1.0   | 30       | 38     | 32.61%  |
| 1.01-2.0   | 7        | 14     | 7.61%   |
| 3.01-4.0   | 4        | 5      | 4.35%   |
| 2.01-3.0   | 4        | 6      | 4.35%   |
| 4.01-10.0  | 4        | 4      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 24       | 31.17%  |
| 501-1000       | 18       | 23.38%  |
| 251-500        | 17       | 22.08%  |
| 1001-2000      | 9        | 11.69%  |
| More than 3000 | 6        | 7.79%   |
| 2001-3000      | 1        | 1.3%    |
| 51-100         | 1        | 1.3%    |
| Unknown        | 1        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 30       | 37.97%  |
| 51-100         | 17       | 21.52%  |
| 101-250        | 11       | 13.92%  |
| 21-50          | 10       | 12.66%  |
| 251-500        | 3        | 3.8%    |
| 501-1000       | 3        | 3.8%    |
| More than 3000 | 2        | 2.53%   |
| 2001-3000      | 1        | 1.27%   |
| 1001-2000      | 1        | 1.27%   |
| Unknown        | 1        | 1.27%   |

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
| Detected | 77       | 206    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 45       | 36.59%  |
| Intel                        | 30       | 24.39%  |
| Samsung Electronics          | 9        | 7.32%   |
| SanDisk                      | 7        | 5.69%   |
| Phison Electronics           | 7        | 5.69%   |
| Kingston Technology Company  | 6        | 4.88%   |
| Micron/Crucial Technology    | 4        | 3.25%   |
| Realtek Semiconductor        | 3        | 2.44%   |
| SK hynix                     | 2        | 1.63%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.63%   |
| Union Memory (Shenzhen)      | 1        | 0.81%   |
| Toshiba America Info Systems | 1        | 0.81%   |
| Silicon Motion               | 1        | 0.81%   |
| Seagate Technology           | 1        | 0.81%   |
| INNOGRIT                     | 1        | 0.81%   |
| ASMedia Technology           | 1        | 0.81%   |
| Apple                        | 1        | 0.81%   |
| ADATA Technology             | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30       | 19.74%  |
| AMD 400 Series Chipset SATA Controller                                         | 13       | 8.55%   |
| AMD 500 Series Chipset SATA Controller                                         | 10       | 6.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 3.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 3.29%   |
| Phison E12 NVMe Controller                                                     | 4        | 2.63%   |
| AMD FCH SATA Controller D                                                      | 4        | 2.63%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 2.63%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.97%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 1.97%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.97%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.97%   |
| SanDisk Non-Volatile memory controller                                         | 2        | 1.32%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.32%   |
| Realtek NVMe Controller                                                        | 2        | 1.32%   |
| Phison Electronics Non-Volatile memory controller                              | 2        | 1.32%   |
| Micron/Crucial NVMe Storage Controller                                         | 2        | 1.32%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 1.32%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 2        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.32%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.66%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.66%   |
| SK hynix BC511                                                                 | 1        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.66%   |
| Seagate FireCuda 510 SSD                                                       | 1        | 0.66%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.66%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.66%   |
| SanDisk NVMe Controller                                                        | 1        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.66%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.66%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 70       | 57.85%  |
| NVMe | 45       | 37.19%  |
| RAID | 5        | 4.13%   |
| IDE  | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 47       | 61.04%  |
| Intel  | 30       | 38.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics         | 5        | 6.49%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 5.19%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 3.9%    |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 3.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 2.6%    |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 2.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 2.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 2.6%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 7 1700 Eight-Core Processor          | 2        | 2.6%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 2.6%    |
| AMD Ryzen 5 2600X Six-Core Processor           | 2        | 2.6%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 2.6%    |
| Intel Xeon W-3223 CPU @ 3.50GHz                | 1        | 1.3%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 1.3%    |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 1.3%    |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.3%    |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.3%    |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 1.3%    |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1        | 1.3%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 1        | 1.3%    |
| Intel Core i5-6600 CPU @ 3.30GHz               | 1        | 1.3%    |
| Intel Core i5-4590S CPU @ 3.00GHz              | 1        | 1.3%    |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.3%    |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.3%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.3%    |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.3%    |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 1.3%    |
| Intel Core i3-7100 CPU @ 3.90GHz               | 1        | 1.3%    |
| Intel 12th Gen Core i7-12700F                  | 1        | 1.3%    |
| Intel 12th Gen Core i3-12100F                  | 1        | 1.3%    |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 1.3%    |
| Intel 11th Gen Core i5-11600K @ 3.90GHz        | 1        | 1.3%    |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 1.3%    |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.3%    |
| AMD Ryzen 9 6900HX with Radeon Graphics        | 1        | 1.3%    |
| AMD Ryzen 9 3900XT 12-Core Processor           | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 21       | 27.27%  |
| Intel Core i5          | 13       | 16.88%  |
| AMD Ryzen 9            | 9        | 11.69%  |
| AMD Ryzen 7            | 9        | 11.69%  |
| Intel Core i7          | 7        | 9.09%   |
| Other                  | 5        | 6.49%   |
| Intel Xeon             | 3        | 3.9%    |
| Intel Core i3          | 2        | 2.6%    |
| AMD Ryzen 5 PRO        | 2        | 2.6%    |
| AMD FX                 | 2        | 2.6%    |
| AMD Ryzen Threadripper | 1        | 1.3%    |
| AMD Ryzen 7 PRO        | 1        | 1.3%    |
| AMD Athlon X4          | 1        | 1.3%    |
| AMD Athlon             | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 26       | 33.77%  |
| 4      | 23       | 29.87%  |
| 8      | 15       | 19.48%  |
| 12     | 9        | 11.69%  |
| 2      | 3        | 3.9%    |
| 3      | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 77       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 63       | 81.82%  |
| 1      | 14       | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 14       | 18.18%  |
| Zen+        | 11       | 14.29%  |
| Zen 2       | 10       | 12.99%  |
| KabyLake    | 8        | 10.39%  |
| Haswell     | 8        | 10.39%  |
| Zen         | 7        | 9.09%   |
| Unknown     | 7        | 9.09%   |
| Skylake     | 4        | 5.19%   |
| SandyBridge | 2        | 2.6%    |
| Piledriver  | 2        | 2.6%    |
| IvyBridge   | 2        | 2.6%    |
| Steamroller | 1        | 1.3%    |
| CometLake   | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 54       | 62.07%  |
| Nvidia | 22       | 25.29%  |
| Intel  | 11       | 12.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 15.56%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.44%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 4.44%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 4.44%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 4.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 4.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 3.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.22%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.22%   |
| Intel HD Graphics 530                                                       | 2        | 2.22%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.22%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 2.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.11%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.11%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.11%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 1.11%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.11%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.11%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.11%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 1.11%   |
| AMD Raphael                                                                 | 1        | 1.11%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 1.11%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.11%   |
| AMD Navi 21 Pro-XTA [Radeon Pro W6900X]                                     | 1        | 1.11%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.11%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 49       | 62.03%  |
| 1 x Nvidia     | 19       | 24.05%  |
| 2 x AMD        | 3        | 3.8%    |
| 1 x Intel      | 3        | 3.8%    |
| Intel + Nvidia | 2        | 2.53%   |
| AMD + Nvidia   | 2        | 2.53%   |
| Intel + AMD    | 1        | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 58       | 75.32%  |
| Proprietary | 19       | 24.68%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 75.64%  |
| 3.01-4.0   | 7        | 8.97%   |
| 7.01-8.0   | 6        | 7.69%   |
| 5.01-6.0   | 2        | 2.56%   |
| 8.01-16.0  | 2        | 2.56%   |
| 2.01-3.0   | 1        | 1.28%   |
| 16.01-24.0 | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 10       | 13.33%  |
| Samsung Electronics  | 9        | 12%     |
| AOC                  | 6        | 8%      |
| Acer                 | 6        | 8%      |
| Hewlett-Packard      | 4        | 5.33%   |
| ViewSonic            | 3        | 4%      |
| Sony                 | 3        | 4%      |
| Pixio                | 3        | 4%      |
| Philips              | 3        | 4%      |
| Dell                 | 3        | 4%      |
| Ancor Communications | 3        | 4%      |
| Toshiba              | 2        | 2.67%   |
| MSI                  | 2        | 2.67%   |
| ASUSTek Computer     | 2        | 2.67%   |
| ___                  | 1        | 1.33%   |
| WIT                  | 1        | 1.33%   |
| Wacom                | 1        | 1.33%   |
| Valve                | 1        | 1.33%   |
| Unknown              | 1        | 1.33%   |
| Sun                  | 1        | 1.33%   |
| Sceptre Tech         | 1        | 1.33%   |
| Roku                 | 1        | 1.33%   |
| Insignia             | 1        | 1.33%   |
| Huion                | 1        | 1.33%   |
| HJW                  | 1        | 1.33%   |
| Hitachi              | 1        | 1.33%   |
| HannStar             | 1        | 1.33%   |
| DZX                  | 1        | 1.33%   |
| BenQ                 | 1        | 1.33%   |
| AOpen                | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Pixio PX275h WAM2700 2560x1440 600x330mm 27.0-inch                      | 2        | 2.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 2.6%    |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                         | 2        | 2.6%    |
| ___ LCD TV ___9000 1360x768                                             | 1        | 1.3%    |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 1.3%    |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 1.3%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 1.3%    |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1        | 1.3%    |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 1.3%    |
| Valve LCD Monitor VLV91A8                                               | 1        | 1.3%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.3%    |
| Toshiba TV TSB0206 1920x1080                                            | 1        | 1.3%    |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 1.3%    |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 1.3%    |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1.3%    |
| Sony TV *00 SNY3F05 3840x2160 1085x610mm 49.0-inch                      | 1        | 1.3%    |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 1.3%    |
| Sceptre Tech E225W-1920 SPT08D5 1920x1080 443x249mm 20.0-inch           | 1        | 1.3%    |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 1.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM7218 3840x2160 1872x1053mm 84.6-inch | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch   | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 1.3%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 1.3%    |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 1.3%    |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1        | 1.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.3%    |
| Roku 100012590 RKU0B01 1920x1080 698x392mm 31.5-inch                    | 1        | 1.3%    |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 1.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 1.3%    |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 1.3%    |
| MSI MAG272C MSI3CA5 1920x1080 598x336mm 27.0-inch                       | 1        | 1.3%    |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                         | 1        | 1.3%    |
| Insignia 48DR420NA16 BBY3253 1920x1080 1054x591mm 47.6-inch             | 1        | 1.3%    |
| Huion GT-133 HAT1330 1920x1080 294x165mm 13.3-inch                      | 1        | 1.3%    |
| HJW MACROSILICON HJW1836 1400x1050 530x290mm 23.8-inch                  | 1        | 1.3%    |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 1        | 1.3%    |
| Hewlett-Packard Z27n HWP3219 2560x1440 597x336mm 27.0-inch              | 1        | 1.3%    |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch           | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 52.05%  |
| 3840x2160 (4K)     | 16       | 21.92%  |
| 2560x1440 (QHD)    | 8        | 10.96%  |
| 2560x1080          | 2        | 2.74%   |
| 1920x1200 (WUXGA)  | 2        | 2.74%   |
| 3840x1080          | 1        | 1.37%   |
| 1680x1050 (WSXGA+) | 1        | 1.37%   |
| 1440x900 (WXGA+)   | 1        | 1.37%   |
| 1400x1050          | 1        | 1.37%   |
| 1366x768 (WXGA)    | 1        | 1.37%   |
| 1360x768           | 1        | 1.37%   |
| Unknown            | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 16       | 21.62%  |
| 24      | 11       | 14.86%  |
| 23      | 11       | 14.86%  |
| 31      | 9        | 12.16%  |
| 21      | 5        | 6.76%   |
| 72      | 4        | 5.41%   |
| 84      | 3        | 4.05%   |
| 48      | 2        | 2.7%    |
| 15      | 2        | 2.7%    |
| Unknown | 2        | 2.7%    |
| 75      | 1        | 1.35%   |
| 74      | 1        | 1.35%   |
| 65      | 1        | 1.35%   |
| 57      | 1        | 1.35%   |
| 47      | 1        | 1.35%   |
| 46      | 1        | 1.35%   |
| 34      | 1        | 1.35%   |
| 32      | 1        | 1.35%   |
| 18      | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 35       | 48.61%  |
| 601-700     | 10       | 13.89%  |
| 1501-2000   | 9        | 12.5%   |
| 401-500     | 6        | 8.33%   |
| 1001-1500   | 6        | 8.33%   |
| 701-800     | 2        | 2.78%   |
| 301-350     | 2        | 2.78%   |
| Unknown     | 2        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 62       | 88.57%  |
| 16/10   | 5        | 7.14%   |
| 32/9    | 1        | 1.43%   |
| 21/9    | 1        | 1.43%   |
| Unknown | 1        | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 29.33%  |
| 301-350        | 16       | 21.33%  |
| More than 1000 | 12       | 16%     |
| 351-500        | 11       | 14.67%  |
| 251-300        | 5        | 6.67%   |
| 501-1000       | 3        | 4%      |
| Unknown        | 2        | 2.67%   |
| 151-200        | 1        | 1.33%   |
| 141-150        | 1        | 1.33%   |
| 101-110        | 1        | 1.33%   |
| 91-100         | 1        | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 47       | 65.28%  |
| 101-120 | 12       | 16.67%  |
| 1-50    | 7        | 9.72%   |
| 121-160 | 3        | 4.17%   |
| Unknown | 2        | 2.78%   |
| 161-240 | 1        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 87.18%  |
| 2     | 10       | 12.82%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 52       | 41.94%  |
| Intel                         | 39       | 31.45%  |
| TP-Link                       | 6        | 4.84%   |
| Broadcom                      | 6        | 4.84%   |
| Microsoft                     | 5        | 4.03%   |
| Samsung Electronics           | 2        | 1.61%   |
| Ralink Technology             | 2        | 1.61%   |
| Qualcomm Atheros              | 2        | 1.61%   |
| MediaTek                      | 2        | 1.61%   |
| OPPO Electronics              | 1        | 0.81%   |
| OnePlus Technology (Shenzhen) | 1        | 0.81%   |
| Huawei Technologies           | 1        | 0.81%   |
| Google                        | 1        | 0.81%   |
| D-Link                        | 1        | 0.81%   |
| ASUSTek Computer              | 1        | 0.81%   |
| Aquantia                      | 1        | 0.81%   |
| Apple                         | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44       | 30.56%  |
| Intel Wi-Fi 6 AX200                                               | 8        | 5.56%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 4.86%   |
| Intel I211 Gigabit Network Connection                             | 6        | 4.17%   |
| Intel Ethernet Controller I225-V                                  | 6        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 2.78%   |
| Microsoft XBOX ACC                                                | 3        | 2.08%   |
| Intel Wireless 8260                                               | 3        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 2.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.69%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.69%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.69%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.69%   |
| Realtek 802.11ac NIC                                              | 1        | 0.69%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.69%   |
| OPPO RMX3263                                                      | 1        | 0.69%   |
| OnePlus (Shenzhen) Android                                        | 1        | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.69%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 36.36%  |
| Realtek Semiconductor | 10       | 18.18%  |
| TP-Link               | 6        | 10.91%  |
| Broadcom              | 6        | 10.91%  |
| Microsoft             | 5        | 9.09%   |
| Ralink Technology     | 2        | 3.64%   |
| Qualcomm Atheros      | 2        | 3.64%   |
| MediaTek              | 2        | 3.64%   |
| D-Link                | 1        | 1.82%   |
| ASUSTek Computer      | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 8        | 14.55%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4        | 7.27%   |
| Microsoft XBOX ACC                                            | 3        | 5.45%   |
| Intel Wireless 8260                                           | 3        | 5.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 3        | 5.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2        | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2        | 3.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 1.82%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                    | 1        | 1.82%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1        | 1.82%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 1        | 1.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1        | 1.82%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1        | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1        | 1.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 1.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1        | 1.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 1        | 1.82%   |
| Realtek 802.11ac WLAN Adapter                                 | 1        | 1.82%   |
| Realtek 802.11ac NIC                                          | 1        | 1.82%   |
| Ralink RT5372 Wireless Adapter                                | 1        | 1.82%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 1.82%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1        | 1.82%   |
| Microsoft Wireless XBox Controller Dongle                     | 1        | 1.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 1.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 1.82%   |
| Intel Wireless 7265                                           | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1        | 1.82%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 1        | 1.82%   |
| D-Link 802.11 n WLAN                                          | 1        | 1.82%   |
| Broadcom Network controller                                   | 1        | 1.82%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 1        | 1.82%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter            | 1        | 1.82%   |
| ASUS 802.11ac NIC                                             | 1        | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 51       | 58.62%  |
| Intel                         | 28       | 32.18%  |
| Samsung Electronics           | 2        | 2.3%    |
| Qualcomm Atheros              | 1        | 1.15%   |
| OPPO Electronics              | 1        | 1.15%   |
| OnePlus Technology (Shenzhen) | 1        | 1.15%   |
| Huawei Technologies           | 1        | 1.15%   |
| Google                        | 1        | 1.15%   |
| Aquantia                      | 1        | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44       | 50%     |
| Intel Ethernet Connection (2) I219-V                              | 7        | 7.95%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.82%   |
| Intel Ethernet Controller I225-V                                  | 6        | 6.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.27%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.14%   |
| OPPO RMX3263                                                      | 1        | 1.14%   |
| OnePlus (Shenzhen) Android                                        | 1        | 1.14%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.14%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.14%   |
| Huawei ANA-NX9                                                    | 1        | 1.14%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.14%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 59.69%  |
| WiFi     | 51       | 39.53%  |
| Modem    | 1        | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 76.54%  |
| WiFi     | 19       | 23.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 55.84%  |
| 2     | 30       | 38.96%  |
| 3     | 4        | 5.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 67.53%  |
| Yes  | 25       | 32.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 40.91%  |
| Cambridge Silicon Radio         | 8        | 18.18%  |
| ASUSTek Computer                | 5        | 11.36%  |
| Realtek Semiconductor           | 4        | 9.09%   |
| MediaTek                        | 2        | 4.55%   |
| Broadcom                        | 2        | 4.55%   |
| TP-Link                         | 1        | 2.27%   |
| Realtek                         | 1        | 2.27%   |
| Qualcomm Atheros Communications | 1        | 2.27%   |
| Integrated System Solution      | 1        | 2.27%   |
| IMC Networks                    | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 18.18%  |
| Intel AX200 Bluetooth                                 | 7        | 15.91%  |
| Intel Bluetooth wireless interface                    | 4        | 9.09%   |
| Realtek Bluetooth Radio                               | 3        | 6.82%   |
| Intel AX210 Bluetooth                                 | 3        | 6.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 6.82%   |
| MediaTek Wireless_Device                              | 2        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 4.55%   |
| TP-Link UB500 Adapter                                 | 1        | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.27%   |
| Realtek Bluetooth Radio                               | 1        | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.27%   |
| Intel Bluetooth Device                                | 1        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.27%   |
| Intel AX201 Bluetooth                                 | 1        | 2.27%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.27%   |
| IMC Networks Bluetooth Device                         | 1        | 2.27%   |
| ASUS BCM20702A0                                       | 1        | 2.27%   |
| ASUS ASUS USB-BT500                                   | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 64       | 45.39%  |
| Intel                    | 30       | 21.28%  |
| Nvidia                   | 22       | 15.6%   |
| Logitech                 | 6        | 4.26%   |
| Valve Software           | 2        | 1.42%   |
| SteelSeries ApS          | 2        | 1.42%   |
| Medeli Electronics       | 2        | 1.42%   |
| Corsair                  | 2        | 1.42%   |
| C-Media Electronics      | 2        | 1.42%   |
| Apple                    | 2        | 1.42%   |
| Tenx Technology          | 1        | 0.71%   |
| Realtek Semiconductor    | 1        | 0.71%   |
| Quanta                   | 1        | 0.71%   |
| Micro Star International | 1        | 0.71%   |
| Kingston Technology      | 1        | 0.71%   |
| JMTek                    | 1        | 0.71%   |
| Creative Labs            | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 9.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16       | 8.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15       | 8.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 7.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 6.95%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 4.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 2.67%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.14%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.6%    |
| Valve Software Valve VR Radio & HMD Mic                                    | 2        | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.07%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.07%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.07%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.53%   |
| SteelSeries ApS SteelSeries SC2 USB Headset                                | 1        | 0.53%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 0.53%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.53%   |
| Quanta USB Audio                                                           | 1        | 0.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.53%   |

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
| 0     | 57       | 73.08%  |
| 1     | 15       | 19.23%  |
| 2     | 5        | 6.41%   |
| 4     | 1        | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 16       | 57.14%  |
| Unassigned class         | 3        | 10.71%  |
| Net/ethernet             | 2        | 7.14%   |
| Multimedia controller    | 2        | 7.14%   |
| Graphics card            | 2        | 7.14%   |
| Sound                    | 1        | 3.57%   |
| Fingerprint reader       | 1        | 3.57%   |
| Communication controller | 1        | 3.57%   |

