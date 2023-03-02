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

Total: 82

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| SteamOS 3.4                  | 28       | 41.79%  |
| SteamOS 3.3                  | 24       | 35.82%  |
| SteamOS 3.2 (steamdeck-main) | 7        | 10.45%  |
| SteamOS                      | 4        | 5.97%   |
| SteamOS Snapshot             | 3        | 4.48%   |
| SteamOS 3.2                  | 1        | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 64       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 22       | 33.85%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 16.92%  |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 15.38%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 10.77%  |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 5        | 7.69%   |
| 5.13.0-valve36-1-neptune                           | 2        | 3.08%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 3.08%   |
| 5.15.79-1-lts                                      | 1        | 1.54%   |
| 5.15.60-1-lts                                      | 1        | 1.54%   |
| 5.13.0-valve24-1-neptune                           | 1        | 1.54%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 1.54%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 1        | 1.54%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 58       | 89.23%  |
| 5.18.1  | 5        | 7.69%   |
| 5.15.79 | 1        | 1.54%   |
| 5.15.60 | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 58       | 89.23%  |
| 5.18    | 5        | 7.69%   |
| 5.15    | 2        | 3.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 64       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 64       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 56       | 86.15%  |
| fr_FR | 3        | 4.62%   |
| pt_PT | 1        | 1.54%   |
| en_IE | 1        | 1.54%   |
| en_GB | 1        | 1.54%   |
| de_DE | 1        | 1.54%   |
| de_AT | 1        | 1.54%   |
| C     | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 64       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 62       | 96.88%  |
| Tmpfs | 2        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 18       | 28.13%  |
| Gigabyte Technology                  | 16       | 25%     |
| MSI                                  | 10       | 15.63%  |
| ASRock                               | 7        | 10.94%  |
| Dell                                 | 5        | 7.81%   |
| Hewlett-Packard                      | 4        | 6.25%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.56%   |
| Biostar                              | 1        | 1.56%   |
| Apple                                | 1        | 1.56%   |
| Alienware                            | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Gigabyte B450 AORUS M                      | 3        | 4.69%   |
| ASUS All Series                            | 3        | 4.69%   |
| Dell OptiPlex 9010                         | 2        | 3.13%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 3.13%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.56%   |
| MSI MS-7C37                                | 1        | 1.56%   |
| MSI MS-7C02                                | 1        | 1.56%   |
| MSI MS-7B89                                | 1        | 1.56%   |
| MSI MS-7B79                                | 1        | 1.56%   |
| MSI MS-7B09                                | 1        | 1.56%   |
| MSI MS-7A33                                | 1        | 1.56%   |
| MSI MS-7817                                | 1        | 1.56%   |
| MSI MS-7693                                | 1        | 1.56%   |
| MSI MPG H510 Trident 3 (MS-B935)           | 1        | 1.56%   |
| MSI H310 Gaming Trident3 (MS-B920)         | 1        | 1.56%   |
| HP ProDesk 600 G4 MT                       | 1        | 1.56%   |
| HP ProDesk 405 G4 Desktop Mini             | 1        | 1.56%   |
| HP Pavilion Gaming Desktop TG01-2xxx       | 1        | 1.56%   |
| HP Pavilion Gaming Desktop 690-00xx        | 1        | 1.56%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.56%   |
| Gigabyte X570 GAMING X                     | 1        | 1.56%   |
| Gigabyte MBB-670016                        | 1        | 1.56%   |
| Gigabyte H310M S2V 2.0                     | 1        | 1.56%   |
| Gigabyte H170N-WIFI                        | 1        | 1.56%   |
| Gigabyte B85M-D3H                          | 1        | 1.56%   |
| Gigabyte B560M AORUS PRO                   | 1        | 1.56%   |
| Gigabyte B550M DS3H                        | 1        | 1.56%   |
| Gigabyte B550 GAMING X V2                  | 1        | 1.56%   |
| Gigabyte B450M DS3H V2                     | 1        | 1.56%   |
| Gigabyte B450M DS3H                        | 1        | 1.56%   |
| Gigabyte AB350-Gaming 3                    | 1        | 1.56%   |
| Gigabyte 970A-DS3P FX                      | 1        | 1.56%   |
| Dell Precision Tower 5810                  | 1        | 1.56%   |
| Dell OptiPlex 990                          | 1        | 1.56%   |
| Dell OptiPlex 9020                         | 1        | 1.56%   |
| Biostar A320MH                             | 1        | 1.56%   |
| ASUS Z170 PRO GAMING                       | 1        | 1.56%   |
| ASUS TUF Gaming X570-PLUS                  | 1        | 1.56%   |
| ASUS TUF Gaming B550M-PLUS                 | 1        | 1.56%   |
| ASUS ROG CROSSHAIR VIII HERO               | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 5        | 7.81%   |
| Dell OptiPlex                              | 4        | 6.25%   |
| Gigabyte B450                              | 3        | 4.69%   |
| ASUS ROG                                   | 3        | 4.69%   |
| ASUS All                                   | 3        | 4.69%   |
| HP ProDesk                                 | 2        | 3.13%   |
| HP Pavilion                                | 2        | 3.13%   |
| Gigabyte X570                              | 2        | 3.13%   |
| Gigabyte B450M                             | 2        | 3.13%   |
| ASUS TUF                                   | 2        | 3.13%   |
| ASRock B550                                | 2        | 3.13%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.56%   |
| MSI MS-7C37                                | 1        | 1.56%   |
| MSI MS-7C02                                | 1        | 1.56%   |
| MSI MS-7B89                                | 1        | 1.56%   |
| MSI MS-7B79                                | 1        | 1.56%   |
| MSI MS-7B09                                | 1        | 1.56%   |
| MSI MS-7A33                                | 1        | 1.56%   |
| MSI MS-7817                                | 1        | 1.56%   |
| MSI MS-7693                                | 1        | 1.56%   |
| MSI MPG                                    | 1        | 1.56%   |
| MSI H310                                   | 1        | 1.56%   |
| Gigabyte MBB-670016                        | 1        | 1.56%   |
| Gigabyte H310M                             | 1        | 1.56%   |
| Gigabyte H170N-WIFI                        | 1        | 1.56%   |
| Gigabyte B85M-D3H                          | 1        | 1.56%   |
| Gigabyte B560M                             | 1        | 1.56%   |
| Gigabyte B550M                             | 1        | 1.56%   |
| Gigabyte B550                              | 1        | 1.56%   |
| Gigabyte AB350-Gaming                      | 1        | 1.56%   |
| Gigabyte 970A-DS3P                         | 1        | 1.56%   |
| Dell Precision                             | 1        | 1.56%   |
| Biostar A320MH                             | 1        | 1.56%   |
| ASUS Z170                                  | 1        | 1.56%   |
| ASUS M80CJ-O                               | 1        | 1.56%   |
| ASUS H61M-K                                | 1        | 1.56%   |
| ASUS EX-A320M-GAMING                       | 1        | 1.56%   |
| ASUS CROSSHAIR                             | 1        | 1.56%   |
| ASRock B760M-ITX                           | 1        | 1.56%   |
| ASRock B560                                | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 13       | 20.31%  |
| 2018 | 11       | 17.19%  |
| 2019 | 9        | 14.06%  |
| 2021 | 7        | 10.94%  |
| 2017 | 6        | 9.38%   |
| 2013 | 6        | 9.38%   |
| 2022 | 4        | 6.25%   |
| 2016 | 3        | 4.69%   |
| 2015 | 2        | 3.13%   |
| 2014 | 1        | 1.56%   |
| 2012 | 1        | 1.56%   |
| 2011 | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 46.88%  |
| 32.01-64.0  | 15       | 23.44%  |
| 8.01-16.0   | 9        | 14.06%  |
| 4.01-8.0    | 4        | 6.25%   |
| 24.01-32.0  | 3        | 4.69%   |
| 64.01-256.0 | 3        | 4.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 29       | 45.31%  |
| 3.01-4.0  | 15       | 23.44%  |
| 4.01-8.0  | 11       | 17.19%  |
| 1.01-2.0  | 7        | 10.94%  |
| 8.01-16.0 | 2        | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 35.38%  |
| 2      | 16       | 24.62%  |
| 3      | 13       | 20%     |
| 4      | 7        | 10.77%  |
| 5      | 3        | 4.62%   |
| 11     | 1        | 1.54%   |
| 7      | 1        | 1.54%   |
| 6      | 1        | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 84.38%  |
| Yes       | 10       | 15.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 65.63%  |
| No        | 22       | 34.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 52.31%  |
| Yes       | 31       | 47.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 25       | 38.46%  |
| UK           | 7        | 10.77%  |
| France       | 5        | 7.69%   |
| Australia    | 5        | 7.69%   |
| Brazil       | 3        | 4.62%   |
| Ireland      | 2        | 3.08%   |
| Canada       | 2        | 3.08%   |
| Turkey       | 1        | 1.54%   |
| Spain        | 1        | 1.54%   |
| South Africa | 1        | 1.54%   |
| Romania      | 1        | 1.54%   |
| Portugal     | 1        | 1.54%   |
| Poland       | 1        | 1.54%   |
| Philippines  | 1        | 1.54%   |
| Oman         | 1        | 1.54%   |
| Malaysia     | 1        | 1.54%   |
| Latvia       | 1        | 1.54%   |
| Hong Kong    | 1        | 1.54%   |
| Germany      | 1        | 1.54%   |
| Denmark      | 1        | 1.54%   |
| Cambodia     | 1        | 1.54%   |
| Austria      | 1        | 1.54%   |
| Argentina    | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 3.08%   |
| Walsall                | 1        | 1.54%   |
| Vilas                  | 1        | 1.54%   |
| Tuam                   | 1        | 1.54%   |
| Targoviste             | 1        | 1.54%   |
| Sterling Heights       | 1        | 1.54%   |
| Skarzysko-Kamienna     | 1        | 1.54%   |
| Siloam Springs         | 1        | 1.54%   |
| Scotts Valley          | 1        | 1.54%   |
| Sao Paulo              | 1        | 1.54%   |
| Salford                | 1        | 1.54%   |
| Salem                  | 1        | 1.54%   |
| Riga                   | 1        | 1.54%   |
| Puchberg am Schneeberg | 1        | 1.54%   |
| Portland               | 1        | 1.54%   |
| Phnom Penh             | 1        | 1.54%   |
| Perth                  | 1        | 1.54%   |
| Peoria                 | 1        | 1.54%   |
| Paris                  | 1        | 1.54%   |
| Oklahoma City          | 1        | 1.54%   |
| Norwich                | 1        | 1.54%   |
| North York             | 1        | 1.54%   |
| Noble Park             | 1        | 1.54%   |
| Newcastle-under-Lyme   | 1        | 1.54%   |
| Muscat                 | 1        | 1.54%   |
| Moyeuvre-Grande        | 1        | 1.54%   |
| Milford                | 1        | 1.54%   |
| Mercedes               | 1        | 1.54%   |
| Memphis                | 1        | 1.54%   |
| Mascot                 | 1        | 1.54%   |
| Loveland               | 1        | 1.54%   |
| Lisbon                 | 1        | 1.54%   |
| Limerick               | 1        | 1.54%   |
| Langley                | 1        | 1.54%   |
| Kuala Lumpur           | 1        | 1.54%   |
| Kraaifontein           | 1        | 1.54%   |
| Kaukauna               | 1        | 1.54%   |
| Johnstone              | 1        | 1.54%   |
| Ivry-sur-Seine         | 1        | 1.54%   |
| Istanbul               | 1        | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 24       | 31     | 18.46%  |
| Samsung Electronics         | 15       | 31     | 11.54%  |
| SanDisk                     | 11       | 13     | 8.46%   |
| Kingston                    | 11       | 13     | 8.46%   |
| WDC                         | 9        | 12     | 6.92%   |
| Toshiba                     | 8        | 10     | 6.15%   |
| Crucial                     | 8        | 11     | 6.15%   |
| A-DATA Technology           | 5        | 5      | 3.85%   |
| PNY                         | 4        | 5      | 3.08%   |
| Phison                      | 4        | 5      | 3.08%   |
| Micron/Crucial Technology   | 4        | 4      | 3.08%   |
| Realtek Semiconductor       | 3        | 3      | 2.31%   |
| Phison Electronics          | 3        | 5      | 2.31%   |
| SK hynix                    | 2        | 2      | 1.54%   |
| Kingston Technology Company | 2        | 2      | 1.54%   |
| China                       | 2        | 5      | 1.54%   |
| Unknown                     | 2        | 3      | 1.54%   |
| Unknown                     | 1        | 1      | 0.77%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.77%   |
| SPCC                        | 1        | 3      | 0.77%   |
| Ramsta                      | 1        | 1      | 0.77%   |
| Mushkin                     | 1        | 1      | 0.77%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.77%   |
| KingFast                    | 1        | 1      | 0.77%   |
| Intenso                     | 1        | 1      | 0.77%   |
| Intel                       | 1        | 1      | 0.77%   |
| HS-SSD-C100                 | 1        | 1      | 0.77%   |
| GALAX                       | 1        | 1      | 0.77%   |
| Apple                       | 1        | 1      | 0.77%   |
| ADATA Technology            | 1        | 2      | 0.77%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 3        | 2.01%   |
| Crucial CT1000BX500SSD1 1TB                         | 3        | 2.01%   |
| Toshiba MQ01ABD100 1TB                              | 2        | 1.34%   |
| Toshiba DT01ACA100 1TB                              | 2        | 1.34%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2        | 1.34%   |
| SanDisk NVMe SSD Drive 500GB                        | 2        | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 1.34%   |
| Realtek NVMe SSD Drive 256GB                        | 2        | 1.34%   |
| PNY CS900 120GB SSD                                 | 2        | 1.34%   |
| Phison E12 NVMe Controller 1024GB                   | 2        | 1.34%   |
| Micron/Crucial CT1000P1SSD8 1TB                     | 2        | 1.34%   |
| Kingston SH103S3120G 120GB SSD                      | 2        | 1.34%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.34%   |
| A-DATA SU650 240GB SSD                              | 2        | 1.34%   |
| A-DATA SU630 240GB SSD                              | 2        | 1.34%   |
| Unknown                                             | 2        | 1.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.67%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.67%   |
| WDC WDBNCE2500PNC 250GB SSD                         | 1        | 0.67%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.67%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1        | 0.67%   |
| WDC WD5000BPKT-60PK4T0 500GB                        | 1        | 0.67%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 0.67%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 0.67%   |
| WDC WD10EURX-83UY4Y0 1TB                            | 1        | 0.67%   |
| WDC WD10EURX-63FH1Y0 1TB                            | 1        | 0.67%   |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.67%   |
| Unknown NVMe SSD Drive 512GB                        | 1        | 0.67%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1        | 0.67%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 0.67%   |
| Toshiba MK3275GSX 320GB                             | 1        | 0.67%   |
| Toshiba MK1059GSM 1TB                               | 1        | 0.67%   |
| Toshiba HDWD130 3TB                                 | 1        | 0.67%   |
| Toshiba DT01ACA200 2TB                              | 1        | 0.67%   |
| SPCC Solid State Disk 1024GB                        | 1        | 0.67%   |
| SK hynix NVMe SSD Drive 256GB                       | 1        | 0.67%   |
| SK hynix BC511 512GB                                | 1        | 0.67%   |
| Seagate ST9320325AS 320GB                           | 1        | 0.67%   |
| Seagate ST8000DM004-2CX188 8TB                      | 1        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 60.53%  |
| Toshiba             | 8        | 10     | 21.05%  |
| WDC                 | 6        | 8      | 15.79%  |
| Samsung Electronics | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 19     | 19.23%  |
| Kingston            | 8        | 9      | 15.38%  |
| Crucial             | 8        | 11     | 15.38%  |
| SanDisk             | 6        | 7      | 11.54%  |
| A-DATA Technology   | 5        | 5      | 9.62%   |
| WDC                 | 4        | 4      | 7.69%   |
| PNY                 | 4        | 5      | 7.69%   |
| China               | 2        | 5      | 3.85%   |
| SPCC                | 1        | 3      | 1.92%   |
| Ramsta              | 1        | 1      | 1.92%   |
| Mushkin             | 1        | 1      | 1.92%   |
| Intenso             | 1        | 1      | 1.92%   |
| Intel               | 1        | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 38       | 72     | 33.93%  |
| NVMe    | 37       | 49     | 33.04%  |
| HDD     | 32       | 49     | 28.57%  |
| Unknown | 5        | 6      | 4.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 52       | 120    | 56.52%  |
| NVMe | 37       | 49     | 40.22%  |
| SAS  | 3        | 7      | 3.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 62     | 46.15%  |
| 0.51-1.0   | 26       | 34     | 33.33%  |
| 1.01-2.0   | 5        | 12     | 6.41%   |
| 3.01-4.0   | 4        | 5      | 5.13%   |
| 4.01-10.0  | 4        | 4      | 5.13%   |
| 2.01-3.0   | 3        | 4      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 35.94%  |
| 501-1000       | 14       | 21.88%  |
| 251-500        | 11       | 17.19%  |
| 1001-2000      | 9        | 14.06%  |
| More than 3000 | 5        | 7.81%   |
| 2001-3000      | 1        | 1.56%   |
| Unknown        | 1        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26       | 39.39%  |
| 51-100         | 16       | 24.24%  |
| 21-50          | 8        | 12.12%  |
| 101-250        | 8        | 12.12%  |
| 251-500        | 2        | 3.03%   |
| 501-1000       | 2        | 3.03%   |
| More than 3000 | 1        | 1.52%   |
| 2001-3000      | 1        | 1.52%   |
| 1001-2000      | 1        | 1.52%   |
| Unknown        | 1        | 1.52%   |

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
| Detected | 64       | 176    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 37       | 35.92%  |
| Intel                       | 25       | 24.27%  |
| Samsung Electronics         | 7        | 6.8%    |
| Phison Electronics          | 7        | 6.8%    |
| SanDisk                     | 6        | 5.83%   |
| Kingston Technology Company | 5        | 4.85%   |
| Micron/Crucial Technology   | 4        | 3.88%   |
| Realtek Semiconductor       | 3        | 2.91%   |
| SK hynix                    | 2        | 1.94%   |
| Union Memory (Shenzhen)     | 1        | 0.97%   |
| Seagate Technology          | 1        | 0.97%   |
| MAXIO Technology (Hangzhou) | 1        | 0.97%   |
| INNOGRIT                    | 1        | 0.97%   |
| ASMedia Technology          | 1        | 0.97%   |
| Apple                       | 1        | 0.97%   |
| ADATA Technology            | 1        | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 19.2%   |
| AMD 400 Series Chipset SATA Controller                                         | 11       | 8.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 9        | 7.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 4%      |
| Phison E12 NVMe Controller                                                     | 4        | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.2%    |
| SanDisk Non-Volatile memory controller                                         | 3        | 2.4%    |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 2.4%    |
| Intel SATA Controller [RAID mode]                                              | 3        | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 2.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 2.4%    |
| AMD FCH SATA Controller D                                                      | 3        | 2.4%    |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 2.4%    |
| Realtek Realtek Non-Volatile memory controller                                 | 2        | 1.6%    |
| Phison Electronics Non-Volatile memory controller                              | 2        | 1.6%    |
| Micron/Crucial NVMe Controller                                                 | 2        | 1.6%    |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 2        | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.6%    |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.6%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 0.8%    |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.8%    |
| SK hynix BC511                                                                 | 1        | 0.8%    |
| Seagate FireCuda 510 SSD                                                       | 1        | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.8%    |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.8%    |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.8%    |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.8%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.8%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.8%    |
| Intel SATA controller                                                          | 1        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1        | 0.8%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 58       | 58.59%  |
| NVMe | 37       | 37.37%  |
| RAID | 4        | 4.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 38       | 59.38%  |
| Intel  | 26       | 40.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 6.25%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 4.69%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 4.69%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 4.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 3.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 3.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 3.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 3.13%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 3.13%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 3.13%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 3.13%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.13%   |
| Intel Xeon W-3223 CPU @ 3.50GHz                | 1        | 1.56%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 1.56%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.56%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 1.56%   |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1        | 1.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 1        | 1.56%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 1        | 1.56%   |
| Intel Core i5-4590S CPU @ 3.00GHz              | 1        | 1.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.56%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.56%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 1.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz               | 1        | 1.56%   |
| Intel 12th Gen Core i7-12700F                  | 1        | 1.56%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 1.56%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz        | 1        | 1.56%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 1.56%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.56%   |
| AMD Ryzen 9 6900HX with Radeon Graphics        | 1        | 1.56%   |
| AMD Ryzen 9 3900XT 12-Core Processor           | 1        | 1.56%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 1.56%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.56%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 1.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 1.56%   |
| AMD Ryzen 5 PRO 2400GE w/ Radeon Vega Graphics | 1        | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 16       | 25%     |
| Intel Core i5          | 12       | 18.75%  |
| AMD Ryzen 9            | 9        | 14.06%  |
| AMD Ryzen 7            | 7        | 10.94%  |
| Intel Core i7          | 5        | 7.81%   |
| Other                  | 4        | 6.25%   |
| Intel Xeon             | 3        | 4.69%   |
| Intel Core i3          | 2        | 3.13%   |
| AMD FX                 | 2        | 3.13%   |
| AMD Ryzen Threadripper | 1        | 1.56%   |
| AMD Ryzen 7 PRO        | 1        | 1.56%   |
| AMD Ryzen 5 PRO        | 1        | 1.56%   |
| AMD Athlon             | 1        | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 20       | 31.25%  |
| 4      | 19       | 29.69%  |
| 8      | 13       | 20.31%  |
| 12     | 9        | 14.06%  |
| 2      | 2        | 3.13%   |
| 3      | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 50       | 78.13%  |
| 1      | 14       | 21.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 64       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 12       | 18.75%  |
| Zen+        | 9        | 14.06%  |
| Zen 2       | 9        | 14.06%  |
| KabyLake    | 7        | 10.94%  |
| Haswell     | 7        | 10.94%  |
| Zen         | 5        | 7.81%   |
| Unknown     | 5        | 7.81%   |
| Skylake     | 4        | 6.25%   |
| SandyBridge | 2        | 3.13%   |
| Piledriver  | 2        | 3.13%   |
| IvyBridge   | 2        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 44       | 59.46%  |
| Nvidia | 19       | 25.68%  |
| Intel  | 11       | 14.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 14.67%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 5.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 5.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4        | 5.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 5.33%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 4%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 4%      |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.67%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.67%   |
| Intel HD Graphics 530                                                       | 2        | 2.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.33%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.33%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.33%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.33%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.33%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.33%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 1.33%   |
| AMD Navi 21 Pro-XTA [Radeon Pro W6900X]                                     | 1        | 1.33%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 41       | 62.12%  |
| 1 x Nvidia     | 16       | 24.24%  |
| 1 x Intel      | 3        | 4.55%   |
| Intel + Nvidia | 2        | 3.03%   |
| AMD + Nvidia   | 2        | 3.03%   |
| 2 x AMD        | 1        | 1.52%   |
| Intel + AMD    | 1        | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 73.44%  |
| Proprietary | 17       | 26.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 73.85%  |
| 3.01-4.0   | 6        | 9.23%   |
| 7.01-8.0   | 5        | 7.69%   |
| 5.01-6.0   | 2        | 3.08%   |
| 8.01-16.0  | 2        | 3.08%   |
| 2.01-3.0   | 1        | 1.54%   |
| 16.01-24.0 | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 12.5%   |
| Goldstar             | 8        | 12.5%   |
| AOC                  | 6        | 9.38%   |
| Acer                 | 6        | 9.38%   |
| ViewSonic            | 3        | 4.69%   |
| Pixio                | 3        | 4.69%   |
| Philips              | 3        | 4.69%   |
| Dell                 | 3        | 4.69%   |
| Ancor Communications | 3        | 4.69%   |
| Toshiba              | 2        | 3.13%   |
| Sony                 | 2        | 3.13%   |
| ASUSTek Computer     | 2        | 3.13%   |
| ___                  | 1        | 1.56%   |
| WIT                  | 1        | 1.56%   |
| Wacom                | 1        | 1.56%   |
| Valve                | 1        | 1.56%   |
| Unknown              | 1        | 1.56%   |
| Sun                  | 1        | 1.56%   |
| Sceptre Tech         | 1        | 1.56%   |
| Roku                 | 1        | 1.56%   |
| MSI                  | 1        | 1.56%   |
| HJW                  | 1        | 1.56%   |
| Hitachi              | 1        | 1.56%   |
| Hewlett-Packard      | 1        | 1.56%   |
| HannStar             | 1        | 1.56%   |
| DZX                  | 1        | 1.56%   |
| BenQ                 | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Pixio OZDSP27IPS WAM2700 2560x1440 597x336mm 27.0-inch                  | 2        | 3.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 3.03%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                       | 2        | 3.03%   |
| ___ LCD TV ___9000 1360x768                                             | 1        | 1.52%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 1.52%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 1.52%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 1.52%   |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1        | 1.52%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 1.52%   |
| Valve LCD Monitor VLV91A8                                               | 1        | 1.52%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.52%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 1.52%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 1.52%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 1.52%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1.52%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                     | 1        | 1.52%   |
| Sceptre Tech E22 SPT08D5 1920x1080 470x300mm 22.0-inch                  | 1        | 1.52%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 1.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 1.52%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch     | 1        | 1.52%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 1.52%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1        | 1.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.52%   |
| Roku 100012590 RKU0B01 1920x1080 698x392mm 31.5-inch                    | 1        | 1.52%   |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 1.52%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.52%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 1.52%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 1.52%   |
| MSI MAG272C MSI3CA5 1920x1080 598x336mm 27.0-inch                       | 1        | 1.52%   |
| HJW MACROSILICON HJW1836 1400x1050 530x290mm 23.8-inch                  | 1        | 1.52%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                   | 1        | 1.52%   |
| Hewlett-Packard 24o HPN337C 1920x1080 530x300mm 24.0-inch               | 1        | 1.52%   |
| HannStar HF289H HSD190B 1920x1200 610x350mm 27.7-inch                   | 1        | 1.52%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch                | 1        | 1.52%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 1        | 1.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1        | 1.52%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 1        | 1.52%   |
| Goldstar 27MP35 GSM5A5B 1920x1080 598x337mm 27.0-inch                   | 1        | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 52.38%  |
| 3840x2160 (4K)     | 13       | 20.63%  |
| 2560x1440 (QHD)    | 7        | 11.11%  |
| 2560x1080          | 2        | 3.17%   |
| 3840x1080          | 1        | 1.59%   |
| 1920x1200 (WUXGA)  | 1        | 1.59%   |
| 1680x1050 (WSXGA+) | 1        | 1.59%   |
| 1440x900 (WXGA+)   | 1        | 1.59%   |
| 1400x1050          | 1        | 1.59%   |
| 1366x768 (WXGA)    | 1        | 1.59%   |
| 1360x768           | 1        | 1.59%   |
| Unknown            | 1        | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 14       | 22.22%  |
| 23      | 11       | 17.46%  |
| 24      | 9        | 14.29%  |
| 31      | 8        | 12.7%   |
| 21      | 4        | 6.35%   |
| 72      | 3        | 4.76%   |
| 84      | 2        | 3.17%   |
| 48      | 2        | 3.17%   |
| Unknown | 2        | 3.17%   |
| 74      | 1        | 1.59%   |
| 65      | 1        | 1.59%   |
| 57      | 1        | 1.59%   |
| 46      | 1        | 1.59%   |
| 34      | 1        | 1.59%   |
| 32      | 1        | 1.59%   |
| 18      | 1        | 1.59%   |
| 15      | 1        | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 31       | 50.82%  |
| 601-700     | 9        | 14.75%  |
| 1501-2000   | 6        | 9.84%   |
| 401-500     | 5        | 8.2%    |
| 1001-1500   | 5        | 8.2%    |
| 701-800     | 2        | 3.28%   |
| Unknown     | 2        | 3.28%   |
| 301-350     | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 53       | 88.33%  |
| 16/10   | 4        | 6.67%   |
| 32/9    | 1        | 1.67%   |
| 21/9    | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 32.81%  |
| 301-350        | 14       | 21.88%  |
| 351-500        | 10       | 15.63%  |
| More than 1000 | 9        | 14.06%  |
| 251-300        | 4        | 6.25%   |
| 501-1000       | 2        | 3.13%   |
| Unknown        | 2        | 3.13%   |
| 141-150        | 1        | 1.56%   |
| 101-110        | 1        | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 65.57%  |
| 101-120 | 10       | 16.39%  |
| 1-50    | 6        | 9.84%   |
| 121-160 | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |
| 161-240 | 1        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 86.15%  |
| 2     | 9        | 13.85%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 41       | 40.2%   |
| Intel                         | 33       | 32.35%  |
| TP-Link                       | 5        | 4.9%    |
| Microsoft                     | 5        | 4.9%    |
| Broadcom                      | 5        | 4.9%    |
| Ralink Technology             | 2        | 1.96%   |
| Qualcomm Atheros              | 2        | 1.96%   |
| Samsung Electronics           | 1        | 0.98%   |
| OPPO                          | 1        | 0.98%   |
| OnePlus Technology (Shenzhen) | 1        | 0.98%   |
| MediaTek                      | 1        | 0.98%   |
| Huawei Technologies           | 1        | 0.98%   |
| Google                        | 1        | 0.98%   |
| D-Link                        | 1        | 0.98%   |
| Aquantia                      | 1        | 0.98%   |
| Apple                         | 1        | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 34       | 28.33%  |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 5.83%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 5%      |
| Intel Ethernet Controller I225-V                                                              | 6        | 5%      |
| Intel Ethernet Connection (2) I219-V                                                          | 6        | 5%      |
| Realtek RTL8125 2.5GbE Controller                                                             | 4        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4        | 3.33%   |
| Microsoft XBOX ACC                                                                            | 3        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3        | 2.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.67%   |
| Intel Wireless 8260                                                                           | 2        | 1.67%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.67%   |
| Intel Ethernet Connection (2) I218-V                                                          | 2        | 1.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.83%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.83%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.83%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.83%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.83%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.83%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.83%   |
| OPPO CPH1923                                                                                  | 1        | 0.83%   |
| OnePlus (Shenzhen) Android                                                                    | 1        | 0.83%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 0.83%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1        | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 0.83%   |
| Intel WLAN controller                                                                         | 1        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1        | 0.83%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 35.56%  |
| Realtek Semiconductor | 8        | 17.78%  |
| TP-Link               | 5        | 11.11%  |
| Microsoft             | 5        | 11.11%  |
| Broadcom              | 5        | 11.11%  |
| Ralink Technology     | 2        | 4.44%   |
| Qualcomm Atheros      | 2        | 4.44%   |
| MediaTek              | 1        | 2.22%   |
| D-Link                | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 7        | 15.56%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4        | 8.89%   |
| Microsoft XBOX ACC                                                                            | 3        | 6.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 4.44%   |
| Intel Wireless 8260                                                                           | 2        | 4.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 2.22%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 2.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 2.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 2.22%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 2.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 2.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.22%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.22%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.22%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 2.22%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1        | 2.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 2.22%   |
| Intel WLAN controller                                                                         | 1        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.22%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 2.22%   |
| Broadcom Network controller                                                                   | 1        | 2.22%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 40       | 54.79%  |
| Intel                         | 26       | 35.62%  |
| Samsung Electronics           | 1        | 1.37%   |
| Qualcomm Atheros              | 1        | 1.37%   |
| OPPO                          | 1        | 1.37%   |
| OnePlus Technology (Shenzhen) | 1        | 1.37%   |
| Huawei Technologies           | 1        | 1.37%   |
| Google                        | 1        | 1.37%   |
| Aquantia                      | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34       | 45.95%  |
| Intel I211 Gigabit Network Connection                             | 6        | 8.11%   |
| Intel Ethernet Controller I225-V                                  | 6        | 8.11%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 8.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.05%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.7%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.35%   |
| OPPO CPH1923                                                      | 1        | 1.35%   |
| OnePlus (Shenzhen) Android                                        | 1        | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.35%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.35%   |
| Huawei MLA-L11                                                    | 1        | 1.35%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 59.81%  |
| WiFi     | 42       | 39.25%  |
| Modem    | 1        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 77.61%  |
| WiFi     | 15       | 22.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 57.81%  |
| 2     | 24       | 37.5%   |
| 3     | 3        | 4.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 68.75%  |
| Yes  | 20       | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 43.75%  |
| Cambridge Silicon Radio         | 5        | 15.63%  |
| Realtek Semiconductor           | 3        | 9.38%   |
| ASUSTek Computer                | 3        | 9.38%   |
| Broadcom                        | 2        | 6.25%   |
| TP-Link                         | 1        | 3.13%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| MediaTek                        | 1        | 3.13%   |
| Integrated System Solution      | 1        | 3.13%   |
| IMC Networks                    | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 6        | 18.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 15.63%  |
| Intel AX210 Bluetooth                                 | 3        | 9.38%   |
| Realtek Bluetooth Radio                               | 2        | 6.25%   |
| Intel Bluetooth wireless interface                    | 2        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 6.25%   |
| TP-Link TPuLink UB500 Adapter                         | 1        | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 3.13%   |
| MediaTek Wireless_Device                              | 1        | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 3.13%   |
| Intel Bluetooth Device                                | 1        | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 3.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.13%   |
| IMC Networks Bluetooth Device                         | 1        | 3.13%   |
| ASUS ASUS USB-BT500                                   | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 54       | 45%     |
| Intel                 | 25       | 20.83%  |
| Nvidia                | 19       | 15.83%  |
| Logitech              | 6        | 5%      |
| Valve Software        | 2        | 1.67%   |
| Corsair               | 2        | 1.67%   |
| C-Media Electronics   | 2        | 1.67%   |
| Apple                 | 2        | 1.67%   |
| Tenx Technology       | 1        | 0.83%   |
| SteelSeries ApS       | 1        | 0.83%   |
| Realtek Semiconductor | 1        | 0.83%   |
| Quanta                | 1        | 0.83%   |
| Medeli Electronics    | 1        | 0.83%   |
| Kingston Technology   | 1        | 0.83%   |
| JMTek                 | 1        | 0.83%   |
| Creative Labs         | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 10.32%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13       | 8.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11       | 7.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 7.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 5.81%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 4.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.58%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.94%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 2        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.29%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.29%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.29%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.65%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 0.65%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.65%   |
| Quanta USB Audio                                                           | 1        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.65%   |
| Medeli Electronics AudioPro X5 Microphone                                  | 1        | 0.65%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1        | 0.65%   |

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
| Apple iPhone 5/5C/5S/6/SE       | 1        | 10%     |

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
| 0     | 47       | 72.31%  |
| 1     | 13       | 20%     |
| 2     | 4        | 6.15%   |
| 4     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 54.17%  |
| Unassigned class         | 3        | 12.5%   |
| Net/ethernet             | 2        | 8.33%   |
| Multimedia controller    | 2        | 8.33%   |
| Sound                    | 1        | 4.17%   |
| Graphics card            | 1        | 4.17%   |
| Fingerprint reader       | 1        | 4.17%   |
| Communication controller | 1        | 4.17%   |

