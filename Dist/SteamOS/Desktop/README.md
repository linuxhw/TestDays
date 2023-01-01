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

Total: 60

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | PRIME B450M-A II            | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek   | PRIME B450M-A II            | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Dell      | 0KC9NP A01                  | [0e70489d5c](https://linux-hardware.org/?probe=0e70489d5c) | Dec 16, 2022 |
| ASUSTek   | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [65ccd1da0e](https://linux-hardware.org/?probe=65ccd1da0e) | Dec 05, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS       | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| ASUSTek   | Z170 PRO GAMING             | [3f642a7844](https://linux-hardware.org/?probe=3f642a7844) | Dec 02, 2022 |
| Gigabyte  | B450M DS3H V2               | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| MSI       | 970A-G46                    | [3cd88e88d3](https://linux-hardware.org/?probe=3cd88e88d3) | Nov 28, 2022 |
| Gigabyte  | B450 AORUS M                | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| ASUSTek   | Z170 PRO GAMING             | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| ASUSTek   | PRIME X570-PRO              | [c278b19567](https://linux-hardware.org/?probe=c278b19567) | Nov 20, 2022 |
| HP        | 8626                        | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP        | 8626                        | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| Gigabyte  | 970A-DS3P FX                | [85ef5eaf43](https://linux-hardware.org/?probe=85ef5eaf43) | Nov 12, 2022 |
| MSI       | X370 GAMING PLUS            | [a0b134897f](https://linux-hardware.org/?probe=a0b134897f) | Nov 05, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Gigabyte  | B550 GAMING X V2            | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| HP        | 8433 11                     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| Gigabyte  | B450M DS3H-CF               | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Apple     | Mac-27AD2F918AE68F61 Mac... | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| ASUSTek   | CROSSHAIR VI HERO           | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| MSI       | X399 SLI PLUS               | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| MSI       | X470 GAMING PLUS            | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| MSI       | 970A-G46                    | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| ASUSTek   | H81M-PLUS                   | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Gigabyte  | B450 AORUS M                | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Dell      | 0HHV7N A00                  | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| ASUSTek   | PRIME A320M-K               | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| MSI       | MS-B9201                    | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Gigabyte  | B550 AORUS ELITE AX V2      | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| ASUSTek   | PRIME B550-PLUS             | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| ASUSTek   | H97-PRO GAMER               | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| ASUSTek   | H97-PRO GAMER               | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Gigabyte  | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS        | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| MSI       | MS-B9351                    | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI       | MS-B9351                    | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| MSI       | B450 TOMAHAWK MAX II        | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| ASUSTek   | SABERTOOTH X99              | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| Dell      | 00F82W A00                  | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Gigabyte  | H310M S2V                   | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| ASRock    | A520M-ITX/ac                | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock    | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ASUSTek   | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Gigabyte  | H170N-WIFI-CF               | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Gigabyte  | B550 GAMING X V2            | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte  | B550 GAMING X V2            | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Alienware | 02XRCM A01                  | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| ASUSTek   | H61M-K                      | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock    | B550 PG Velocita            | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock    | B365M Pro4-F                | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte  | B560M AORUS PRO             | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte  | B560M AORUS PRO             | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Gigabyte  | Z170XP-SLI-CF               | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| SteamOS 3.3                  | 24       | 47.06%  |
| SteamOS 3.4                  | 13       | 25.49%  |
| SteamOS 3.2 (steamdeck-main) | 7        | 13.73%  |
| SteamOS Snapshot             | 3        | 5.88%   |
| SteamOS                      | 3        | 5.88%   |
| SteamOS 3.2                  | 1        | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 48       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 22.45%  |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 10       | 20.41%  |
| 5.13.0-valve21.3-1-neptune                         | 10       | 20.41%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 14.29%  |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 4        | 8.16%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 4.08%   |
| 5.15.79-1-lts                                      | 1        | 2.04%   |
| 5.15.60-1-lts                                      | 1        | 2.04%   |
| 5.13.0-valve24-1-neptune                           | 1        | 2.04%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 2.04%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 43       | 87.76%  |
| 5.18.1  | 4        | 8.16%   |
| 5.15.79 | 1        | 2.04%   |
| 5.15.60 | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 43       | 87.76%  |
| 5.18    | 4        | 8.16%   |
| 5.15    | 2        | 4.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 48       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 48       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 40       | 81.63%  |
| fr_FR | 3        | 6.12%   |
| pt_PT | 1        | 2.04%   |
| en_IE | 1        | 2.04%   |
| en_GB | 1        | 2.04%   |
| de_DE | 1        | 2.04%   |
| de_AT | 1        | 2.04%   |
| C     | 1        | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 48       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 48       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 35.42%  |
| Gigabyte Technology | 13       | 27.08%  |
| MSI                 | 7        | 14.58%  |
| ASRock              | 4        | 8.33%   |
| Dell                | 3        | 6.25%   |
| Hewlett-Packard     | 2        | 4.17%   |
| Apple               | 1        | 2.08%   |
| Alienware           | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 6.25%   |
| Gigabyte B450 AORUS M               | 2        | 4.17%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 4.17%   |
| MSI MS-7C02                         | 1        | 2.08%   |
| MSI MS-7B79                         | 1        | 2.08%   |
| MSI MS-7B09                         | 1        | 2.08%   |
| MSI MS-7A33                         | 1        | 2.08%   |
| MSI MS-7693                         | 1        | 2.08%   |
| MSI MPG H510 Trident 3 (MS-B935)    | 1        | 2.08%   |
| MSI H310 Gaming Trident3 (MS-B920)  | 1        | 2.08%   |
| HP ProDesk 405 G4 Desktop Mini      | 1        | 2.08%   |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 2.08%   |
| Gigabyte X570 I AORUS PRO WIFI      | 1        | 2.08%   |
| Gigabyte X570 GAMING X              | 1        | 2.08%   |
| Gigabyte MBB-670016                 | 1        | 2.08%   |
| Gigabyte H310M S2V 2.0              | 1        | 2.08%   |
| Gigabyte H170N-WIFI                 | 1        | 2.08%   |
| Gigabyte B560M AORUS PRO            | 1        | 2.08%   |
| Gigabyte B550 GAMING X V2           | 1        | 2.08%   |
| Gigabyte B450M DS3H V2              | 1        | 2.08%   |
| Gigabyte B450M DS3H                 | 1        | 2.08%   |
| Gigabyte AB350-Gaming 3             | 1        | 2.08%   |
| Gigabyte 970A-DS3P FX               | 1        | 2.08%   |
| Dell Precision Tower 5810           | 1        | 2.08%   |
| Dell OptiPlex 9020                  | 1        | 2.08%   |
| Dell OptiPlex 9010                  | 1        | 2.08%   |
| ASUS Z170 PRO GAMING                | 1        | 2.08%   |
| ASUS TUF Gaming X570-PLUS           | 1        | 2.08%   |
| ASUS TUF Gaming B550M-PLUS          | 1        | 2.08%   |
| ASUS ROG CROSSHAIR VIII HERO        | 1        | 2.08%   |
| ASUS PRIME X570-PRO                 | 1        | 2.08%   |
| ASUS PRIME B550-PLUS                | 1        | 2.08%   |
| ASUS PRIME B450M-A II               | 1        | 2.08%   |
| ASUS PRIME A320M-K                  | 1        | 2.08%   |
| ASUS M80CJ-O                        | 1        | 2.08%   |
| ASUS H61M-K                         | 1        | 2.08%   |
| ASUS EX-A320M-GAMING                | 1        | 2.08%   |
| ASUS CROSSHAIR VI HERO              | 1        | 2.08%   |
| ASRock B550 PG Velocita             | 1        | 2.08%   |
| ASRock B450M-HDV R4.0               | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 4        | 8.33%   |
| ASUS ROG              | 3        | 6.25%   |
| ASUS All              | 3        | 6.25%   |
| Gigabyte X570         | 2        | 4.17%   |
| Gigabyte B450M        | 2        | 4.17%   |
| Gigabyte B450         | 2        | 4.17%   |
| Dell OptiPlex         | 2        | 4.17%   |
| ASUS TUF              | 2        | 4.17%   |
| MSI MS-7C02           | 1        | 2.08%   |
| MSI MS-7B79           | 1        | 2.08%   |
| MSI MS-7B09           | 1        | 2.08%   |
| MSI MS-7A33           | 1        | 2.08%   |
| MSI MS-7693           | 1        | 2.08%   |
| MSI MPG               | 1        | 2.08%   |
| MSI H310              | 1        | 2.08%   |
| HP ProDesk            | 1        | 2.08%   |
| HP Pavilion           | 1        | 2.08%   |
| Gigabyte MBB-670016   | 1        | 2.08%   |
| Gigabyte H310M        | 1        | 2.08%   |
| Gigabyte H170N-WIFI   | 1        | 2.08%   |
| Gigabyte B560M        | 1        | 2.08%   |
| Gigabyte B550         | 1        | 2.08%   |
| Gigabyte AB350-Gaming | 1        | 2.08%   |
| Gigabyte 970A-DS3P    | 1        | 2.08%   |
| Dell Precision        | 1        | 2.08%   |
| ASUS Z170             | 1        | 2.08%   |
| ASUS M80CJ-O          | 1        | 2.08%   |
| ASUS H61M-K           | 1        | 2.08%   |
| ASUS EX-A320M-GAMING  | 1        | 2.08%   |
| ASUS CROSSHAIR        | 1        | 2.08%   |
| ASRock B550           | 1        | 2.08%   |
| ASRock B450M-HDV      | 1        | 2.08%   |
| ASRock B365M          | 1        | 2.08%   |
| ASRock A520M-ITX      | 1        | 2.08%   |
| Apple MacPro7         | 1        | 2.08%   |
| Alienware Aurora      | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 11       | 22.92%  |
| 2018 | 9        | 18.75%  |
| 2019 | 7        | 14.58%  |
| 2017 | 5        | 10.42%  |
| 2021 | 4        | 8.33%   |
| 2016 | 3        | 6.25%   |
| 2013 | 3        | 6.25%   |
| 2022 | 2        | 4.17%   |
| 2015 | 2        | 4.17%   |
| 2014 | 1        | 2.08%   |
| 2012 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 48       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 25       | 52.08%  |
| 32.01-64.0  | 11       | 22.92%  |
| 8.01-16.0   | 4        | 8.33%   |
| 24.01-32.0  | 3        | 6.25%   |
| 64.01-256.0 | 3        | 6.25%   |
| 4.01-8.0    | 2        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 23       | 47.92%  |
| 3.01-4.0 | 12       | 25%     |
| 4.01-8.0 | 8        | 16.67%  |
| 1.01-2.0 | 5        | 10.42%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 28.57%  |
| 2      | 13       | 26.53%  |
| 3      | 11       | 22.45%  |
| 4      | 5        | 10.2%   |
| 5      | 3        | 6.12%   |
| 11     | 1        | 2.04%   |
| 7      | 1        | 2.04%   |
| 6      | 1        | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 85.42%  |
| Yes       | 7        | 14.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 60.42%  |
| No        | 19       | 39.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 53.06%  |
| Yes       | 23       | 46.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 18       | 36.73%  |
| UK        | 7        | 14.29%  |
| France    | 5        | 10.2%   |
| Australia | 3        | 6.12%   |
| Brazil    | 2        | 4.08%   |
| Turkey    | 1        | 2.04%   |
| Spain     | 1        | 2.04%   |
| Romania   | 1        | 2.04%   |
| Portugal  | 1        | 2.04%   |
| Poland    | 1        | 2.04%   |
| Oman      | 1        | 2.04%   |
| Latvia    | 1        | 2.04%   |
| Ireland   | 1        | 2.04%   |
| Hong Kong | 1        | 2.04%   |
| Germany   | 1        | 2.04%   |
| Denmark   | 1        | 2.04%   |
| Canada    | 1        | 2.04%   |
| Cambodia  | 1        | 2.04%   |
| Austria   | 1        | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Walsall                | 1        | 2.04%   |
| Vilas                  | 1        | 2.04%   |
| Tuam                   | 1        | 2.04%   |
| Targoviste             | 1        | 2.04%   |
| Sterling Heights       | 1        | 2.04%   |
| Skarzysko-Kamienna     | 1        | 2.04%   |
| Sao Paulo              | 1        | 2.04%   |
| Salford                | 1        | 2.04%   |
| Salem                  | 1        | 2.04%   |
| Riga                   | 1        | 2.04%   |
| Puchberg am Schneeberg | 1        | 2.04%   |
| Phnom Penh             | 1        | 2.04%   |
| Perth                  | 1        | 2.04%   |
| Peoria                 | 1        | 2.04%   |
| Paris                  | 1        | 2.04%   |
| Oklahoma City          | 1        | 2.04%   |
| Norwich                | 1        | 2.04%   |
| Noble Park             | 1        | 2.04%   |
| Newcastle-under-Lyme   | 1        | 2.04%   |
| Muscat                 | 1        | 2.04%   |
| Moyeuvre-Grande        | 1        | 2.04%   |
| Milford                | 1        | 2.04%   |
| Memphis                | 1        | 2.04%   |
| Mascot                 | 1        | 2.04%   |
| Loveland               | 1        | 2.04%   |
| Lisbon                 | 1        | 2.04%   |
| Langley                | 1        | 2.04%   |
| Kaukauna               | 1        | 2.04%   |
| Johnstone              | 1        | 2.04%   |
| Ivry-sur-Seine         | 1        | 2.04%   |
| Istanbul               | 1        | 2.04%   |
| Hornsea                | 1        | 2.04%   |
| Henderson              | 1        | 2.04%   |
| Gujan-Mestras          | 1        | 2.04%   |
| Glostrup Municipality  | 1        | 2.04%   |
| Frankfurt am Main      | 1        | 2.04%   |
| Elk Grove              | 1        | 2.04%   |
| Detroit                | 1        | 2.04%   |
| Davison                | 1        | 2.04%   |
| Dallas                 | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 17       | 22     | 16.35%  |
| Samsung Electronics         | 13       | 25     | 12.5%   |
| SanDisk                     | 9        | 11     | 8.65%   |
| WDC                         | 8        | 11     | 7.69%   |
| Crucial                     | 8        | 10     | 7.69%   |
| Kingston                    | 7        | 8      | 6.73%   |
| Toshiba                     | 6        | 8      | 5.77%   |
| A-DATA Technology           | 5        | 5      | 4.81%   |
| PNY                         | 4        | 5      | 3.85%   |
| Phison                      | 4        | 5      | 3.85%   |
| SK hynix                    | 2        | 2      | 1.92%   |
| Realtek Semiconductor       | 2        | 2      | 1.92%   |
| Micron/Crucial Technology   | 2        | 2      | 1.92%   |
| China                       | 2        | 5      | 1.92%   |
| Unknown                     | 2        | 3      | 1.92%   |
| Unknown                     | 1        | 1      | 0.96%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.96%   |
| SPCC                        | 1        | 2      | 0.96%   |
| Phison Electronics          | 1        | 2      | 0.96%   |
| Mushkin                     | 1        | 1      | 0.96%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.96%   |
| Kingston Technology Company | 1        | 1      | 0.96%   |
| Intenso                     | 1        | 1      | 0.96%   |
| Intel                       | 1        | 1      | 0.96%   |
| HS-SSD-C100                 | 1        | 1      | 0.96%   |
| GALAX                       | 1        | 1      | 0.96%   |
| Apple                       | 1        | 1      | 0.96%   |
| ADATA Technology            | 1        | 2      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                   | 3        | 2.5%    |
| Crucial CT1000BX500SSD1 1TB                  | 3        | 2.5%    |
| Toshiba MQ01ABD100 1TB                       | 2        | 1.67%   |
| Seagate ST1000LM014-1EJ164 1TB               | 2        | 1.67%   |
| SanDisk NVMe SSD Drive 500GB                 | 2        | 1.67%   |
| Realtek NVMe SSD Drive 256GB                 | 2        | 1.67%   |
| PNY CS900 120GB SSD                          | 2        | 1.67%   |
| A-DATA SU650 240GB SSD                       | 2        | 1.67%   |
| A-DATA SU630 240GB SSD                       | 2        | 1.67%   |
| Unknown                                      | 2        | 1.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1        | 0.83%   |
| WDC WDBNCE5000PNC 500GB SSD                  | 1        | 0.83%   |
| WDC WDBNCE2500PNC 250GB SSD                  | 1        | 0.83%   |
| WDC WDBNCE0010PNC 1TB SSD                    | 1        | 0.83%   |
| WDC WD7500BPVT-80HXZT3 752GB                 | 1        | 0.83%   |
| WDC WD5000BPKT-60PK4T0 500GB                 | 1        | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1        | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1        | 0.83%   |
| WDC WD10EURX-83UY4Y0 1TB                     | 1        | 0.83%   |
| WDC WD10EURX-63FH1Y0 1TB                     | 1        | 0.83%   |
| WDC WD10EADS-00M2B0 1TB                      | 1        | 0.83%   |
| Unknown NVMe SSD Drive 512GB                 | 1        | 0.83%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1        | 0.83%   |
| Toshiba MK3275GSX 320GB                      | 1        | 0.83%   |
| Toshiba MK1059GSM 1TB                        | 1        | 0.83%   |
| Toshiba HDWD130 3TB                          | 1        | 0.83%   |
| Toshiba DT01ACA200 2TB                       | 1        | 0.83%   |
| Toshiba DT01ACA100 1TB                       | 1        | 0.83%   |
| SPCC Solid State Disk 1024GB                 | 1        | 0.83%   |
| SK hynix NVMe SSD Drive 256GB                | 1        | 0.83%   |
| SK hynix BC511 256GB                         | 1        | 0.83%   |
| Seagate ST9320325AS 320GB                    | 1        | 0.83%   |
| Seagate ST6000DM003-2CY186 6TB               | 1        | 0.83%   |
| Seagate ST500LM021-1KJ152 500GB              | 1        | 0.83%   |
| Seagate ST4000DX001-1CE168 4TB               | 1        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 0.83%   |
| Seagate ST3750640NS 752GB                    | 1        | 0.83%   |
| Seagate ST3500413AS 500GB                    | 1        | 0.83%   |
| Seagate ST3500312CS 500GB                    | 1        | 0.83%   |
| Seagate ST3160318AS 160GB                    | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 16       | 21     | 59.26%  |
| Toshiba | 6        | 8      | 22.22%  |
| WDC     | 5        | 7      | 18.52%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 16     | 21.74%  |
| Crucial             | 8        | 10     | 17.39%  |
| SanDisk             | 5        | 6      | 10.87%  |
| A-DATA Technology   | 5        | 5      | 10.87%  |
| WDC                 | 4        | 4      | 8.7%    |
| PNY                 | 4        | 5      | 8.7%    |
| Kingston            | 4        | 5      | 8.7%    |
| China               | 2        | 5      | 4.35%   |
| SPCC                | 1        | 2      | 2.17%   |
| Mushkin             | 1        | 1      | 2.17%   |
| Intenso             | 1        | 1      | 2.17%   |
| Intel               | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 32       | 61     | 36.36%  |
| NVMe    | 29       | 38     | 32.95%  |
| HDD     | 23       | 36     | 26.14%  |
| Unknown | 4        | 5      | 4.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 41       | 95     | 56.16%  |
| NVMe | 29       | 38     | 39.73%  |
| SAS  | 3        | 7      | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 51     | 46.67%  |
| 0.51-1.0   | 23       | 30     | 38.33%  |
| 1.01-2.0   | 4        | 8      | 6.67%   |
| 3.01-4.0   | 3        | 5      | 5%      |
| 2.01-3.0   | 1        | 2      | 1.67%   |
| 4.01-10.0  | 1        | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 37.5%   |
| 501-1000       | 10       | 20.83%  |
| 251-500        | 9        | 18.75%  |
| 1001-2000      | 7        | 14.58%  |
| More than 3000 | 3        | 6.25%   |
| 2001-3000      | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 23       | 46%     |
| 51-100    | 13       | 26%     |
| 21-50     | 6        | 12%     |
| 101-250   | 5        | 10%     |
| 2001-3000 | 1        | 2%      |
| 1001-2000 | 1        | 2%      |
| 501-1000  | 1        | 2%      |

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
| Detected | 48       | 140    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 30       | 37.97%  |
| Intel                       | 17       | 21.52%  |
| Samsung Electronics         | 6        | 7.59%   |
| SanDisk                     | 5        | 6.33%   |
| Phison Electronics          | 5        | 6.33%   |
| Kingston Technology Company | 4        | 5.06%   |
| SK hynix                    | 2        | 2.53%   |
| Realtek Semiconductor       | 2        | 2.53%   |
| Micron/Crucial Technology   | 2        | 2.53%   |
| Union Memory (Shenzhen)     | 1        | 1.27%   |
| Seagate Technology          | 1        | 1.27%   |
| MAXIO Technology (Hangzhou) | 1        | 1.27%   |
| INNOGRIT                    | 1        | 1.27%   |
| Apple                       | 1        | 1.27%   |
| ADATA Technology            | 1        | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18       | 18.95%  |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 8.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 7.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 4.21%   |
| Phison E12 NVMe Controller                                                     | 3        | 3.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 3.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.16%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 3.16%   |
| SanDisk Non-Volatile memory controller                                         | 2        | 2.11%   |
| Phison Electronics Non-Volatile memory controller                              | 2        | 2.11%   |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 2.11%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 2        | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.11%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 2.11%   |
| AMD FCH SATA Controller D                                                      | 2        | 2.11%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 1.05%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 1.05%   |
| SK hynix BC511                                                                 | 1        | 1.05%   |
| Seagate FireCuda 510 SSD                                                       | 1        | 1.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.05%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.05%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.05%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 1.05%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.05%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 1.05%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.05%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 1.05%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 1.05%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 45       | 59.21%  |
| NVMe | 29       | 38.16%  |
| RAID | 2        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 30       | 62.5%   |
| Intel  | 18       | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 6.25%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 6.25%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 4.17%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 4.17%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 4.17%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 4.17%   |
| Intel Xeon W-3223 CPU @ 3.50GHz                | 1        | 2.08%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 2.08%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.08%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 2.08%   |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1        | 2.08%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 1        | 2.08%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i5-4590S CPU @ 3.00GHz              | 1        | 2.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 2.08%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 2.08%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 2.08%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 2.08%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2.08%   |
| AMD Ryzen 9 3900XT 12-Core Processor           | 1        | 2.08%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 2.08%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 2.08%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 2.08%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 5 PRO 2400GE w/ Radeon Vega Graphics | 1        | 2.08%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 2.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 1        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.08%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 2.08%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 2.08%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 2.08%   |
| AMD FX-8370 Eight-Core Processor               | 1        | 2.08%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 2.08%   |
| AMD Athlon 3000G with Radeon Vega Graphics     | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 10       | 20.83%  |
| Intel Core i5          | 9        | 18.75%  |
| AMD Ryzen 9            | 7        | 14.58%  |
| AMD Ryzen 7            | 7        | 14.58%  |
| Intel Xeon             | 3        | 6.25%   |
| Intel Core i7          | 3        | 6.25%   |
| Other                  | 2        | 4.17%   |
| AMD FX                 | 2        | 4.17%   |
| Intel Core i3          | 1        | 2.08%   |
| AMD Ryzen Threadripper | 1        | 2.08%   |
| AMD Ryzen 7 PRO        | 1        | 2.08%   |
| AMD Ryzen 5 PRO        | 1        | 2.08%   |
| AMD Athlon             | 1        | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 14       | 29.17%  |
| 6      | 13       | 27.08%  |
| 8      | 12       | 25%     |
| 12     | 7        | 14.58%  |
| 3      | 1        | 2.08%   |
| 2      | 1        | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 37       | 77.08%  |
| 1      | 11       | 22.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 9        | 18.75%  |
| Zen 3       | 8        | 16.67%  |
| Zen+        | 7        | 14.58%  |
| KabyLake    | 5        | 10.42%  |
| Haswell     | 5        | 10.42%  |
| Zen         | 4        | 8.33%   |
| Skylake     | 4        | 8.33%   |
| Piledriver  | 2        | 4.17%   |
| Unknown     | 2        | 4.17%   |
| SandyBridge | 1        | 2.08%   |
| IvyBridge   | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 30       | 54.55%  |
| Nvidia | 18       | 32.73%  |
| Intel  | 7        | 12.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 12.73%  |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 7.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 5.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 5.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 3.64%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.64%   |
| Intel HD Graphics 530                                                       | 2        | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 3.64%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 2        | 3.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.64%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 3.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 3.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.82%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.82%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.82%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 1.82%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.82%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.82%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.82%   |
| AMD Navi 21 Pro-XTA [Radeon Pro W6900X]                                     | 1        | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 1.82%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.82%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 28       | 57.14%  |
| 1 x Nvidia     | 16       | 32.65%  |
| 1 x Intel      | 2        | 4.08%   |
| AMD + Nvidia   | 2        | 4.08%   |
| Intel + Nvidia | 1        | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 66.67%  |
| Proprietary | 16       | 33.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 67.35%  |
| 7.01-8.0   | 5        | 10.2%   |
| 3.01-4.0   | 5        | 10.2%   |
| 5.01-6.0   | 2        | 4.08%   |
| 8.01-16.0  | 2        | 4.08%   |
| 2.01-3.0   | 1        | 2.04%   |
| 16.01-24.0 | 1        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 14.58%  |
| AOC                  | 4        | 8.33%   |
| ViewSonic            | 3        | 6.25%   |
| Philips              | 3        | 6.25%   |
| Goldstar             | 3        | 6.25%   |
| Dell                 | 3        | 6.25%   |
| Ancor Communications | 3        | 6.25%   |
| Acer                 | 3        | 6.25%   |
| Sony                 | 2        | 4.17%   |
| Pixio                | 2        | 4.17%   |
| ASUSTek Computer     | 2        | 4.17%   |
| ___                  | 1        | 2.08%   |
| Wacom                | 1        | 2.08%   |
| Unknown              | 1        | 2.08%   |
| Toshiba              | 1        | 2.08%   |
| Sun                  | 1        | 2.08%   |
| Sceptre Tech         | 1        | 2.08%   |
| MSI                  | 1        | 2.08%   |
| HJW                  | 1        | 2.08%   |
| Hitachi              | 1        | 2.08%   |
| Hewlett-Packard      | 1        | 2.08%   |
| HannStar             | 1        | 2.08%   |
| DZX                  | 1        | 2.08%   |
| BenQ                 | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 2.04%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 2.04%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 2.04%   |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1        | 2.04%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1        | 2.04%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 2.04%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1        | 2.04%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 2.04%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 2.04%   |
| Sony TV *00 SNY8204 3840x2160 1085x610mm 49.0-inch                      | 1        | 2.04%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 2.04%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch       | 1        | 2.04%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 2.04%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 2.04%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 2.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 2.04%   |
| Pixio UG30 WAM3000 2560x1080 597x336mm 27.0-inch                        | 1        | 2.04%   |
| Pixio UG27Q WAM2700 2560x1440 597x336mm 27.0-inch                       | 1        | 2.04%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 2.04%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 2.04%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1        | 2.04%   |
| MSI MAG272C MSI3CA5 1920x1080 598x336mm 27.0-inch                       | 1        | 2.04%   |
| HJW MACROSILICON HJW1836 1680x1050 530x290mm 23.8-inch                  | 1        | 2.04%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                   | 1        | 2.04%   |
| Hewlett-Packard 24o HPN337C 1920x1080 531x299mm 24.0-inch               | 1        | 2.04%   |
| HannStar HF289H HSD190B 1920x1200 610x350mm 27.7-inch                   | 1        | 2.04%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 1        | 2.04%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 1        | 2.04%   |
| Goldstar 27MP35 GSM5A5B 1920x1080 598x337mm 27.0-inch                   | 1        | 2.04%   |
| DZX K3-1 DZX1581 1920x1080 350x190mm 15.7-inch                          | 1        | 2.04%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                       | 1        | 2.04%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                       | 1        | 2.04%   |
| Dell E2420H DELF11B 1920x1080 527x296mm 23.8-inch                       | 1        | 2.04%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                     | 1        | 2.04%   |
| ASUSTek Computer VP248 AUS24CB 1920x1080 531x299mm 24.0-inch            | 1        | 2.04%   |
| ASUSTek Computer VG32VQ1B AUS32E0 2560x1440 697x392mm 31.5-inch         | 1        | 2.04%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                      | 1        | 2.04%   |
| AOC 931Wx AOC1931 1680x1050 440x325mm 21.5-inch                         | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 52.17%  |
| 3840x2160 (4K)     | 8        | 17.39%  |
| 2560x1440 (QHD)    | 6        | 13.04%  |
| 3840x1080          | 1        | 2.17%   |
| 2560x1080          | 1        | 2.17%   |
| 1920x1200 (WUXGA)  | 1        | 2.17%   |
| 1680x1050 (WSXGA+) | 1        | 2.17%   |
| 1440x900 (WXGA+)   | 1        | 2.17%   |
| 1400x1050          | 1        | 2.17%   |
| 1366x768 (WXGA)    | 1        | 2.17%   |
| 1360x768           | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 12       | 26.09%  |
| 23      | 8        | 17.39%  |
| 24      | 7        | 15.22%  |
| 72      | 3        | 6.52%   |
| 31      | 3        | 6.52%   |
| 84      | 2        | 4.35%   |
| 48      | 2        | 4.35%   |
| 21      | 2        | 4.35%   |
| 65      | 1        | 2.17%   |
| 57      | 1        | 2.17%   |
| 46      | 1        | 2.17%   |
| 32      | 1        | 2.17%   |
| 18      | 1        | 2.17%   |
| 15      | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 54.55%  |
| 1501-2000   | 5        | 11.36%  |
| 1001-1500   | 5        | 11.36%  |
| 601-700     | 4        | 9.09%   |
| 401-500     | 3        | 6.82%   |
| 701-800     | 1        | 2.27%   |
| 301-350     | 1        | 2.27%   |
| Unknown     | 1        | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 40       | 93.02%  |
| 16/10 | 2        | 4.65%   |
| 32/9  | 1        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 31.91%  |
| 301-350        | 12       | 25.53%  |
| More than 1000 | 8        | 17.02%  |
| 351-500        | 4        | 8.51%   |
| 251-300        | 3        | 6.38%   |
| 501-1000       | 2        | 4.26%   |
| 141-150        | 1        | 2.13%   |
| 101-110        | 1        | 2.13%   |
| Unknown        | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 66.67%  |
| 101-120 | 7        | 15.56%  |
| 1-50    | 5        | 11.11%  |
| 161-240 | 1        | 2.22%   |
| 121-160 | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 85.71%  |
| 2     | 7        | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 31       | 41.33%  |
| Intel                         | 22       | 29.33%  |
| Microsoft                     | 4        | 5.33%   |
| Broadcom                      | 4        | 5.33%   |
| TP-Link                       | 3        | 4%      |
| Qualcomm Atheros              | 2        | 2.67%   |
| Samsung Electronics           | 1        | 1.33%   |
| Ralink Technology             | 1        | 1.33%   |
| OPPO Electronics              | 1        | 1.33%   |
| OnePlus Technology (Shenzhen) | 1        | 1.33%   |
| Huawei Technologies           | 1        | 1.33%   |
| Google                        | 1        | 1.33%   |
| D-Link                        | 1        | 1.33%   |
| Aquantia                      | 1        | 1.33%   |
| Apple                         | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 25       | 27.78%  |
| Intel Wi-Fi 6 AX200                                                                           | 6        | 6.67%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 6.67%   |
| Intel Ethernet Connection (2) I219-V                                                          | 5        | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 4        | 4.44%   |
| Intel Ethernet Controller I225-V                                                              | 4        | 4.44%   |
| Microsoft XBOX ACC                                                                            | 3        | 3.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2        | 2.22%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                                                          | 2        | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 2        | 2.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.11%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 1.11%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 1.11%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.11%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.11%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 1.11%   |
| OPPO RMX3263                                                                                  | 1        | 1.11%   |
| OnePlus (Shenzhen) OnePlus                                                                    | 1        | 1.11%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.11%   |
| Intel Wireless 8260                                                                           | 1        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1        | 1.11%   |
| Huawei STK-L21                                                                                | 1        | 1.11%   |
| Google Nexus/Pixel Device (tether)                                                            | 1        | 1.11%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.11%   |
| Broadcom Network controller                                                                   | 1        | 1.11%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 1.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                             | 1        | 1.11%   |
| Apple USB-Serial (0001)                                                                       | 1        | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 35.48%  |
| Realtek Semiconductor | 5        | 16.13%  |
| Microsoft             | 4        | 12.9%   |
| Broadcom              | 4        | 12.9%   |
| TP-Link               | 3        | 9.68%   |
| Qualcomm Atheros      | 2        | 6.45%   |
| Ralink Technology     | 1        | 3.23%   |
| D-Link                | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 6        | 19.35%  |
| Microsoft XBOX ACC                                                                            | 3        | 9.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 6.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 6.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2        | 6.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 2        | 6.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 3.23%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 3.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 3.23%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 3.23%   |
| Realtek 802.11ac NIC                                                                          | 1        | 3.23%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 3.23%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 3.23%   |
| Intel Wireless 8260                                                                           | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 3.23%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 3.23%   |
| Broadcom Network controller                                                                   | 1        | 3.23%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                            | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 31       | 54.39%  |
| Intel                         | 19       | 33.33%  |
| Samsung Electronics           | 1        | 1.75%   |
| Qualcomm Atheros              | 1        | 1.75%   |
| OPPO Electronics              | 1        | 1.75%   |
| OnePlus Technology (Shenzhen) | 1        | 1.75%   |
| Huawei Technologies           | 1        | 1.75%   |
| Google                        | 1        | 1.75%   |
| Aquantia                      | 1        | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 43.1%   |
| Intel I211 Gigabit Network Connection                             | 6        | 10.34%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 8.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 6.9%    |
| Intel Ethernet Controller I225-V                                  | 4        | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.45%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.72%   |
| OPPO RMX3263                                                      | 1        | 1.72%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.72%   |
| Huawei STK-L21                                                    | 1        | 1.72%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 61.54%  |
| WiFi     | 29       | 37.18%  |
| Modem    | 1        | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 80.77%  |
| WiFi     | 10       | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 60.42%  |
| 2     | 16       | 33.33%  |
| 3     | 3        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 66.67%  |
| Yes  | 16       | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 41.67%  |
| Cambridge Silicon Radio         | 3        | 12.5%   |
| ASUSTek Computer                | 3        | 12.5%   |
| Realtek Semiconductor           | 2        | 8.33%   |
| Broadcom                        | 2        | 8.33%   |
| TP-Link                         | 1        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| Integrated System Solution      | 1        | 4.17%   |
| IMC Networks                    | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 5        | 20.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 12.5%   |
| Intel AX210 Bluetooth                                 | 2        | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 8.33%   |
| TP-Link UB500 Adapter                                 | 1        | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 4.17%   |
| Realtek Bluetooth Radio                               | 1        | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.17%   |
| Intel Bluetooth wireless interface                    | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 4.17%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.17%   |
| IMC Networks Bluetooth Device                         | 1        | 4.17%   |
| ASUS Bluetooth Device                                 | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 40       | 43.01%  |
| Nvidia                | 18       | 19.35%  |
| Intel                 | 17       | 18.28%  |
| Logitech              | 5        | 5.38%   |
| Corsair               | 2        | 2.15%   |
| Apple                 | 2        | 2.15%   |
| Valve Software        | 1        | 1.08%   |
| Tenx Technology       | 1        | 1.08%   |
| SteelSeries ApS       | 1        | 1.08%   |
| Realtek Semiconductor | 1        | 1.08%   |
| Quanta                | 1        | 1.08%   |
| Kingston Technology   | 1        | 1.08%   |
| JMTek                 | 1        | 1.08%   |
| Creative Labs         | 1        | 1.08%   |
| C-Media Electronics   | 1        | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 14       | 11.97%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 9        | 7.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 8        | 6.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 7        | 5.98%   |
| AMD Family 17h/19h HD Audio Controller                              | 6        | 5.13%   |
| AMD Navi 10 HDMI Audio                                              | 5        | 4.27%   |
| Nvidia GA104 High Definition Audio Controller                       | 3        | 2.56%   |
| Intel 200 Series PCH HD Audio                                       | 3        | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3        | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3        | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3        | 2.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 3        | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                       | 2        | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2        | 1.71%   |
| Nvidia GM204 High Definition Audio Controller                       | 2        | 1.71%   |
| Nvidia GA106 High Definition Audio Controller                       | 2        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2        | 1.71%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2        | 1.71%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 1.71%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 2        | 1.71%   |
| Valve Software Valve VR Radio & HMD Mic                             | 1        | 0.85%   |
| Tenx Technology USB AUDIO                                           | 1        | 0.85%   |
| SteelSeries ApS SteelSeries Arctis Pro                              | 1        | 0.85%   |
| Realtek Semiconductor USB Audio                                     | 1        | 0.85%   |
| Quanta USB Audio                                                    | 1        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                       | 1        | 0.85%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                       | 1        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                       | 1        | 0.85%   |
| Nvidia GA102 High Definition Audio Controller                       | 1        | 0.85%   |
| Logitech PRO X Wireless Gaming Headset                              | 1        | 0.85%   |
| Logitech PRO X                                                      | 1        | 0.85%   |
| Logitech G733 Gaming Headset                                        | 1        | 0.85%   |
| Logitech G430 Surround Sound Gaming Headset                         | 1        | 0.85%   |
| Logitech Blue Microphones                                           | 1        | 0.85%   |
| Kingston Technology HyperX Cloud Alpha S                            | 1        | 0.85%   |
| JMTek USB PnP Audio Device                                          | 1        | 0.85%   |

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
| Valve Software                | 1        | 11.11%  |
| Tobii Technology AB           | 1        | 11.11%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Quanta                        | 1        | 11.11%  |
| Microdia                      | 1        | 11.11%  |
| Magic Control Technology      | 1        | 11.11%  |
| Logitech                      | 1        | 11.11%  |
| Generalplus Technology        | 1        | 11.11%  |
| Apple                         | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Valve Software 3D Camera        | 1        | 11.11%  |
| Tobii AB EyeChip                | 1        | 11.11%  |
| Sunplus USB 2.0 Camera          | 1        | 11.11%  |
| Quanta HD Camera                | 1        | 11.11%  |
| Microdia Webcam Vitade AF       | 1        | 11.11%  |
| Magic Control j5 WebCam JVCU100 | 1        | 11.11%  |
| Logitech HD Webcam C525         | 1        | 11.11%  |
| Generalplus GENERAL WEBCAM      | 1        | 11.11%  |
| Apple iPhone5/5C/5S/6           | 1        | 11.11%  |

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
| 0     | 36       | 75%     |
| 1     | 9        | 18.75%  |
| 2     | 2        | 4.17%   |
| 4     | 1        | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 8        | 50%     |
| Unassigned class      | 3        | 18.75%  |
| Sound                 | 1        | 6.25%   |
| Net/ethernet          | 1        | 6.25%   |
| Multimedia controller | 1        | 6.25%   |
| Graphics card         | 1        | 6.25%   |
| Fingerprint reader    | 1        | 6.25%   |

