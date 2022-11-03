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

Total: 48

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | CROSSHAIR VI HERO           | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Gigabyte  | B550 GAMING X V2            | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| ASRock    | X570 Phantom Gaming-ITX/... | [59904b8a87](https://linux-hardware.org/?probe=59904b8a87) | Oct 19, 2022 |
| HP        | 8433 11                     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| ASRock    | X570 Phantom Gaming-ITX/... | [9873ba1845](https://linux-hardware.org/?probe=9873ba1845) | Oct 09, 2022 |
| Gigabyte  | B450M DS3H-CF               | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| ASRock    | X570 Phantom Gaming-ITX/... | [2e6852099a](https://linux-hardware.org/?probe=2e6852099a) | Oct 06, 2022 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Apple     | Mac-27AD2F918AE68F61 Mac... | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| ASRock    | X570 Phantom Gaming-ITX/... | [5746aa7609](https://linux-hardware.org/?probe=5746aa7609) | Sep 29, 2022 |
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
| SteamOS 3.3                  | 25       | 62.5%   |
| SteamOS 3.2 (steamdeck-main) | 7        | 17.5%   |
| SteamOS Snapshot             | 3        | 7.5%    |
| SteamOS                      | 2        | 5%      |
| SteamOS Rolling              | 1        | 2.5%    |
| SteamOS 3.4                  | 1        | 2.5%    |
| SteamOS 3.2                  | 1        | 2.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 37       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 11       | 28.95%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 28.95%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 18.42%  |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 3        | 7.89%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 5.26%   |
| 5.15.60-1-lts                                      | 1        | 2.63%   |
| 5.13.0-valve24-1-neptune                           | 1        | 2.63%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 2.63%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 34       | 89.47%  |
| 5.18.1  | 3        | 7.89%   |
| 5.15.60 | 1        | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 34       | 89.47%  |
| 5.18    | 3        | 7.89%   |
| 5.15    | 1        | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 37       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 37       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 31       | 83.78%  |
| fr_FR | 2        | 5.41%   |
| pt_PT | 1        | 2.7%    |
| en_IE | 1        | 2.7%    |
| en_GB | 1        | 2.7%    |
| C     | 1        | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 37       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 37       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 97.37%  |
| GPT     | 1        | 2.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 29.73%  |
| Gigabyte Technology | 10       | 27.03%  |
| MSI                 | 6        | 16.22%  |
| ASRock              | 5        | 13.51%  |
| Dell                | 2        | 5.41%   |
| Hewlett-Packard     | 1        | 2.7%    |
| Apple               | 1        | 2.7%    |
| Alienware           | 1        | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 8.11%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 5.41%   |
| MSI MS-7C02                         | 1        | 2.7%    |
| MSI MS-7B79                         | 1        | 2.7%    |
| MSI MS-7B09                         | 1        | 2.7%    |
| MSI MS-7693                         | 1        | 2.7%    |
| MSI MPG H510 Trident 3 (MS-B935)    | 1        | 2.7%    |
| MSI H310 Gaming Trident3 (MS-B920)  | 1        | 2.7%    |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 2.7%    |
| Gigabyte X570 I AORUS PRO WIFI      | 1        | 2.7%    |
| Gigabyte X570 GAMING X              | 1        | 2.7%    |
| Gigabyte MBB-670016                 | 1        | 2.7%    |
| Gigabyte H310M S2V 2.0              | 1        | 2.7%    |
| Gigabyte H170N-WIFI                 | 1        | 2.7%    |
| Gigabyte B560M AORUS PRO            | 1        | 2.7%    |
| Gigabyte B550 GAMING X V2           | 1        | 2.7%    |
| Gigabyte B450M DS3H                 | 1        | 2.7%    |
| Gigabyte B450 AORUS M               | 1        | 2.7%    |
| Gigabyte AB350-Gaming 3             | 1        | 2.7%    |
| Dell Precision Tower 5810           | 1        | 2.7%    |
| Dell OptiPlex 9010                  | 1        | 2.7%    |
| ASUS TUF Gaming X570-PLUS           | 1        | 2.7%    |
| ASUS PRIME B550-PLUS                | 1        | 2.7%    |
| ASUS PRIME A320M-K                  | 1        | 2.7%    |
| ASUS H61M-K                         | 1        | 2.7%    |
| ASUS EX-A320M-GAMING                | 1        | 2.7%    |
| ASUS CROSSHAIR VI HERO              | 1        | 2.7%    |
| ASRock X570 Phantom Gaming-ITX/TB3  | 1        | 2.7%    |
| ASRock B550 PG Velocita             | 1        | 2.7%    |
| ASRock B450M-HDV R4.0               | 1        | 2.7%    |
| ASRock B365M Pro4-F                 | 1        | 2.7%    |
| ASRock A520M-ITX/ac                 | 1        | 2.7%    |
| Apple MacPro7,1                     | 1        | 2.7%    |
| Alienware Aurora R8                 | 1        | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS All              | 3        | 8.11%   |
| Gigabyte X570         | 2        | 5.41%   |
| ASUS ROG              | 2        | 5.41%   |
| ASUS PRIME            | 2        | 5.41%   |
| MSI MS-7C02           | 1        | 2.7%    |
| MSI MS-7B79           | 1        | 2.7%    |
| MSI MS-7B09           | 1        | 2.7%    |
| MSI MS-7693           | 1        | 2.7%    |
| MSI MPG               | 1        | 2.7%    |
| MSI H310              | 1        | 2.7%    |
| HP Pavilion           | 1        | 2.7%    |
| Gigabyte MBB-670016   | 1        | 2.7%    |
| Gigabyte H310M        | 1        | 2.7%    |
| Gigabyte H170N-WIFI   | 1        | 2.7%    |
| Gigabyte B560M        | 1        | 2.7%    |
| Gigabyte B550         | 1        | 2.7%    |
| Gigabyte B450M        | 1        | 2.7%    |
| Gigabyte B450         | 1        | 2.7%    |
| Gigabyte AB350-Gaming | 1        | 2.7%    |
| Dell Precision        | 1        | 2.7%    |
| Dell OptiPlex         | 1        | 2.7%    |
| ASUS TUF              | 1        | 2.7%    |
| ASUS H61M-K           | 1        | 2.7%    |
| ASUS EX-A320M-GAMING  | 1        | 2.7%    |
| ASUS CROSSHAIR        | 1        | 2.7%    |
| ASRock X570           | 1        | 2.7%    |
| ASRock B550           | 1        | 2.7%    |
| ASRock B450M-HDV      | 1        | 2.7%    |
| ASRock B365M          | 1        | 2.7%    |
| ASRock A520M-ITX      | 1        | 2.7%    |
| Apple MacPro7         | 1        | 2.7%    |
| Alienware Aurora      | 1        | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 21.62%  |
| 2018 | 7        | 18.92%  |
| 2019 | 5        | 13.51%  |
| 2021 | 4        | 10.81%  |
| 2017 | 3        | 8.11%   |
| 2016 | 3        | 8.11%   |
| 2013 | 3        | 8.11%   |
| 2022 | 2        | 5.41%   |
| 2014 | 1        | 2.7%    |
| 2012 | 1        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 37       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 37       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 21       | 56.76%  |
| 32.01-64.0  | 9        | 24.32%  |
| 24.01-32.0  | 2        | 5.41%   |
| 64.01-256.0 | 2        | 5.41%   |
| 8.01-16.0   | 2        | 5.41%   |
| 4.01-8.0    | 1        | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 19       | 51.35%  |
| 3.01-4.0 | 8        | 21.62%  |
| 4.01-8.0 | 7        | 18.92%  |
| 1.01-2.0 | 3        | 8.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 26.32%  |
| 3      | 9        | 23.68%  |
| 2      | 9        | 23.68%  |
| 4      | 4        | 10.53%  |
| 5      | 3        | 7.89%   |
| 11     | 1        | 2.63%   |
| 7      | 1        | 2.63%   |
| 6      | 1        | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 86.49%  |
| Yes       | 5        | 13.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 59.46%  |
| No        | 15       | 40.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 55.26%  |
| Yes       | 17       | 44.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 14       | 37.84%  |
| UK        | 5        | 13.51%  |
| France    | 4        | 10.81%  |
| Australia | 3        | 8.11%   |
| Turkey    | 1        | 2.7%    |
| Spain     | 1        | 2.7%    |
| Romania   | 1        | 2.7%    |
| Portugal  | 1        | 2.7%    |
| Poland    | 1        | 2.7%    |
| Oman      | 1        | 2.7%    |
| Latvia    | 1        | 2.7%    |
| Ireland   | 1        | 2.7%    |
| Hong Kong | 1        | 2.7%    |
| Canada    | 1        | 2.7%    |
| Cambodia  | 1        | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Walsall                 | 1        | 2.7%    |
| Vilas                   | 1        | 2.7%    |
| Tuam                    | 1        | 2.7%    |
| Targoviste              | 1        | 2.7%    |
| Sterling Heights        | 1        | 2.7%    |
| South Holland           | 1        | 2.7%    |
| Skarzysko-Kamienna      | 1        | 2.7%    |
| Riga                    | 1        | 2.7%    |
| Phnom Penh              | 1        | 2.7%    |
| Perth                   | 1        | 2.7%    |
| Peoria                  | 1        | 2.7%    |
| Paris                   | 1        | 2.7%    |
| Norwich                 | 1        | 2.7%    |
| Noble Park              | 1        | 2.7%    |
| Newcastle-under-Lyme    | 1        | 2.7%    |
| Muscat                  | 1        | 2.7%    |
| Moyeuvre-Grande         | 1        | 2.7%    |
| Milford                 | 1        | 2.7%    |
| Memphis                 | 1        | 2.7%    |
| Mascot                  | 1        | 2.7%    |
| Loveland                | 1        | 2.7%    |
| Lisbon                  | 1        | 2.7%    |
| Langley                 | 1        | 2.7%    |
| Ivry-sur-Seine          | 1        | 2.7%    |
| Istanbul                | 1        | 2.7%    |
| Hornsea                 | 1        | 2.7%    |
| Henderson               | 1        | 2.7%    |
| Elk Grove               | 1        | 2.7%    |
| Detroit                 | 1        | 2.7%    |
| Dallas                  | 1        | 2.7%    |
| Corning                 | 1        | 2.7%    |
| Chiclana de la Frontera | 1        | 2.7%    |
| Central                 | 1        | 2.7%    |
| Buffalo                 | 1        | 2.7%    |
| Bexleyheath             | 1        | 2.7%    |
| Aubervilliers           | 1        | 2.7%    |
| Albuquerque             | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 14       | 18     | 16.47%  |
| Samsung Electronics       | 12       | 24     | 14.12%  |
| WDC                       | 7        | 10     | 8.24%   |
| SanDisk                   | 6        | 8      | 7.06%   |
| Toshiba                   | 5        | 7      | 5.88%   |
| Kingston                  | 5        | 5      | 5.88%   |
| A-DATA Technology         | 5        | 5      | 5.88%   |
| PNY                       | 4        | 5      | 4.71%   |
| Phison                    | 4        | 4      | 4.71%   |
| Crucial                   | 4        | 4      | 4.71%   |
| Realtek Semiconductor     | 2        | 2      | 2.35%   |
| Phison Electronics        | 2        | 4      | 2.35%   |
| Micron/Crucial Technology | 2        | 2      | 2.35%   |
| China                     | 2        | 3      | 2.35%   |
| Apple                     | 2        | 3      | 2.35%   |
| Unknown                   | 2        | 3      | 2.35%   |
| Unknown                   | 1        | 1      | 1.18%   |
| Union Memory (Shenzhen)   | 1        | 1      | 1.18%   |
| SPCC                      | 1        | 2      | 1.18%   |
| SK hynix                  | 1        | 1      | 1.18%   |
| Mushkin                   | 1        | 1      | 1.18%   |
| HS-SSD-C100               | 1        | 1      | 1.18%   |
| GALAX                     | 1        | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                   | 3        | 3%      |
| Seagate ST1000LM014-1EJ164 1TB               | 2        | 2%      |
| SanDisk NVMe SSD Drive 500GB                 | 2        | 2%      |
| Realtek NVMe SSD Drive 256GB                 | 2        | 2%      |
| PNY CS900 120GB SSD                          | 2        | 2%      |
| A-DATA SU650 240GB SSD                       | 2        | 2%      |
| A-DATA SU630 240GB SSD                       | 2        | 2%      |
| Unknown                                      | 2        | 2%      |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1        | 1%      |
| WDC WDBNCE5000PNC 500GB SSD                  | 1        | 1%      |
| WDC WDBNCE2500PNC 250GB SSD                  | 1        | 1%      |
| WDC WDBNCE0010PNC 1TB SSD                    | 1        | 1%      |
| WDC WD7500BPVT-80HXZT3 752GB                 | 1        | 1%      |
| WDC WD5000BPKT-60PK4T0 500GB                 | 1        | 1%      |
| WDC WD10EZEX-00BN5A0 1TB                     | 1        | 1%      |
| WDC WD10EURX-83UY4Y0 1TB                     | 1        | 1%      |
| WDC WD10EURX-63FH1Y0 1TB                     | 1        | 1%      |
| WDC WD10EADS-00M2B0 1TB                      | 1        | 1%      |
| Unknown NVMe SSD Drive 512GB                 | 1        | 1%      |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1        | 1%      |
| Toshiba MQ01ABD100 1TB                       | 1        | 1%      |
| Toshiba MK3275GSX 320GB                      | 1        | 1%      |
| Toshiba MK1059GSM 1TB                        | 1        | 1%      |
| Toshiba HDWD130 3TB                          | 1        | 1%      |
| Toshiba DT01ACA200 2TB                       | 1        | 1%      |
| Toshiba DT01ACA100 1TB                       | 1        | 1%      |
| SPCC Solid State Disk 1024GB                 | 1        | 1%      |
| SK hynix NVMe SSD Drive 256GB                | 1        | 1%      |
| Seagate ST9320325AS 320GB                    | 1        | 1%      |
| Seagate ST6000DM003-2CY186 6TB               | 1        | 1%      |
| Seagate ST4000DX001-1CE168 4TB               | 1        | 1%      |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1%      |
| Seagate ST3750640NS 752GB                    | 1        | 1%      |
| Seagate ST3500413AS 500GB                    | 1        | 1%      |
| Seagate ST3500312CS 500GB                    | 1        | 1%      |
| Seagate ST3160318AS 160GB                    | 1        | 1%      |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1%      |
| Seagate ST1000LM049-2GH172 1TB               | 1        | 1%      |
| Seagate ST1000LM035-1RK172 1TB               | 1        | 1%      |
| Seagate ST1000DX001-1CM162 1TB               | 1        | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 13       | 17     | 56.52%  |
| Toshiba | 5        | 7      | 21.74%  |
| WDC     | 4        | 6      | 17.39%  |
| Apple   | 1        | 2      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 16     | 25.64%  |
| A-DATA Technology   | 5        | 5      | 12.82%  |
| WDC                 | 4        | 4      | 10.26%  |
| SanDisk             | 4        | 5      | 10.26%  |
| PNY                 | 4        | 5      | 10.26%  |
| Kingston            | 4        | 4      | 10.26%  |
| Crucial             | 4        | 4      | 10.26%  |
| China               | 2        | 3      | 5.13%   |
| SPCC                | 1        | 2      | 2.56%   |
| Mushkin             | 1        | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 26       | 49     | 36.11%  |
| NVMe    | 23       | 29     | 31.94%  |
| HDD     | 19       | 32     | 26.39%  |
| Unknown | 4        | 5      | 5.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 78     | 55.17%  |
| NVMe | 23       | 29     | 39.66%  |
| SAS  | 3        | 8      | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 40     | 46%     |
| 0.51-1.0   | 17       | 25     | 34%     |
| 1.01-2.0   | 4        | 8      | 8%      |
| 3.01-4.0   | 3        | 4      | 6%      |
| 4.01-10.0  | 2        | 2      | 4%      |
| 2.01-3.0   | 1        | 2      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 34.21%  |
| 251-500        | 7        | 18.42%  |
| 501-1000       | 7        | 18.42%  |
| 1001-2000      | 6        | 15.79%  |
| More than 3000 | 3        | 7.89%   |
| 2001-3000      | 2        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 18       | 46.15%  |
| 51-100         | 10       | 25.64%  |
| 101-250        | 4        | 10.26%  |
| 21-50          | 3        | 7.69%   |
| More than 3000 | 1        | 2.56%   |
| 2001-3000      | 1        | 2.56%   |
| 1001-2000      | 1        | 2.56%   |
| 501-1000       | 1        | 2.56%   |

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
| Detected | 37       | 115    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 22       | 36.67%  |
| Intel                       | 14       | 23.33%  |
| Phison Electronics          | 6        | 10%     |
| Samsung Electronics         | 5        | 8.33%   |
| SanDisk                     | 3        | 5%      |
| Realtek Semiconductor       | 2        | 3.33%   |
| Micron/Crucial Technology   | 2        | 3.33%   |
| Unknown                     | 1        | 1.67%   |
| Union Memory (Shenzhen)     | 1        | 1.67%   |
| SK hynix                    | 1        | 1.67%   |
| Seagate Technology          | 1        | 1.67%   |
| Kingston Technology Company | 1        | 1.67%   |
| Apple                       | 1        | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15       | 20.55%  |
| AMD 500 Series Chipset SATA Controller                                         | 6        | 8.22%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 6.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 4.11%   |
| Phison E12 NVMe Controller                                                     | 3        | 4.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 4.11%   |
| Phison Electronics Non-Volatile memory controller                              | 2        | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.74%   |
| AMD FCH SATA Controller D                                                      | 2        | 2.74%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 2.74%   |
| Unknown Non-Volatile memory controller                                         | 1        | 1.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 1.37%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 1.37%   |
| Seagate FireCuda 510 SSD                                                       | 1        | 1.37%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.37%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.37%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 1.37%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 1.37%   |
| Phison NVMe Storage Controller                                                 | 1        | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.37%   |
| Micron/Crucial Non-Volatile memory controller                                  | 1        | 1.37%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 1.37%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.37%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 1.37%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 1.37%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.37%   |
| Apple ANS2 NVMe Controller                                                     | 1        | 1.37%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 1.37%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 59.32%  |
| NVMe | 23       | 38.98%  |
| RAID | 1        | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 22       | 59.46%  |
| Intel  | 15       | 40.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 8.11%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 2        | 5.41%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 5.41%   |
| Intel Xeon W-3223 CPU @ 3.50GHz                | 1        | 2.7%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 2.7%    |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 2.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 2.7%    |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 2.7%    |
| Intel Core i5-8500T CPU @ 2.10GHz              | 1        | 2.7%    |
| Intel Core i5-6600 CPU @ 3.30GHz               | 1        | 2.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 2.7%    |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 2.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 2.7%    |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 2.7%    |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 2.7%    |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 2.7%    |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2.7%    |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2.7%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.7%    |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 2.7%    |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 2.7%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.7%    |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 2.7%    |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 2.7%    |
| AMD FX-8370 Eight-Core Processor               | 1        | 2.7%    |
| AMD Athlon 3000G with Radeon Vega Graphics     | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 9        | 24.32%  |
| Intel Core i5          | 7        | 18.92%  |
| AMD Ryzen 7            | 6        | 16.22%  |
| AMD Ryzen 9            | 4        | 10.81%  |
| Intel Xeon             | 3        | 8.11%   |
| Other                  | 2        | 5.41%   |
| Intel Core i7          | 2        | 5.41%   |
| Intel Core i3          | 1        | 2.7%    |
| AMD Ryzen Threadripper | 1        | 2.7%    |
| AMD FX                 | 1        | 2.7%    |
| AMD Athlon             | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 13       | 35.14%  |
| 8      | 10       | 27.03%  |
| 4      | 9        | 24.32%  |
| 12     | 4        | 10.81%  |
| 2      | 1        | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 78.38%  |
| 1      | 8        | 21.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 37       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 7        | 18.92%  |
| Zen 3       | 6        | 16.22%  |
| Zen+        | 5        | 13.51%  |
| KabyLake    | 4        | 10.81%  |
| Haswell     | 4        | 10.81%  |
| Zen         | 3        | 8.11%   |
| Skylake     | 3        | 8.11%   |
| Unknown     | 2        | 5.41%   |
| SandyBridge | 1        | 2.7%    |
| Piledriver  | 1        | 2.7%    |
| IvyBridge   | 1        | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 26       | 61.9%   |
| Nvidia | 11       | 26.19%  |
| Intel  | 5        | 11.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 16.67%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 7.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 7.14%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 3        | 7.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 7.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 4.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 4.76%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 4.76%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 4.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 4.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 2.38%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.38%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 2.38%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.38%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.38%   |
| Intel HD Graphics 530                                                       | 1        | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.38%   |
| AMD Navi 21 Pro-XTA [Radeon Pro W6900X]                                     | 1        | 2.38%   |
| AMD Cezanne                                                                 | 1        | 2.38%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 25       | 67.57%  |
| 1 x Nvidia   | 10       | 27.03%  |
| 1 x Intel    | 1        | 2.7%    |
| AMD + Nvidia | 1        | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 70.27%  |
| Proprietary | 11       | 29.73%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 70.27%  |
| 3.01-4.0   | 5        | 13.51%  |
| 7.01-8.0   | 2        | 5.41%   |
| 5.01-6.0   | 2        | 5.41%   |
| 16.01-24.0 | 1        | 2.7%    |
| 8.01-16.0  | 1        | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 15.79%  |
| Goldstar             | 4        | 10.53%  |
| Philips              | 3        | 7.89%   |
| Dell                 | 3        | 7.89%   |
| Ancor Communications | 3        | 7.89%   |
| Acer                 | 3        | 7.89%   |
| Sony                 | 2        | 5.26%   |
| ASUSTek Computer     | 2        | 5.26%   |
| ___                  | 1        | 2.63%   |
| Wacom                | 1        | 2.63%   |
| ViewSonic            | 1        | 2.63%   |
| Unknown              | 1        | 2.63%   |
| Toshiba              | 1        | 2.63%   |
| Sun                  | 1        | 2.63%   |
| Sceptre Tech         | 1        | 2.63%   |
| Pixio                | 1        | 2.63%   |
| MSI                  | 1        | 2.63%   |
| HannStar             | 1        | 2.63%   |
| DZX                  | 1        | 2.63%   |
| BenQ                 | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ___ LCD TV ___9000 1360x768                                            | 1        | 2.56%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch               | 1        | 2.56%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 700x390mm 31.5-inch             | 1        | 2.56%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 2.56%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                      | 1        | 2.56%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1        | 2.56%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 2.56%   |
| Sony TV *00 SNY8204 3840x2160 1218x685mm 55.0-inch                     | 1        | 2.56%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                 | 1        | 2.56%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch      | 1        | 2.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch  | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1        | 2.56%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 1        | 2.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1        | 2.56%   |
| Pixio PX275h WAM2700 2560x1440 600x330mm 27.0-inch                     | 1        | 2.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1        | 2.56%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 2.56%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                     | 1        | 2.56%   |
| MSI MAG272C MSI3CA5 1920x1080 598x336mm 27.0-inch                      | 1        | 2.56%   |
| HannStar HF289H HSD190B 1920x1200 610x350mm 27.7-inch                  | 1        | 2.56%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch               | 1        | 2.56%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 1        | 2.56%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 1        | 2.56%   |
| Goldstar 27MP35 GSM5A5B 1920x1080 598x337mm 27.0-inch                  | 1        | 2.56%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 600x303mm 26.5-inch                   | 1        | 2.56%   |
| DZX K3-1 DZX1581 1920x1080 350x190mm 15.7-inch                         | 1        | 2.56%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                      | 1        | 2.56%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                      | 1        | 2.56%   |
| Dell E2420H DELF11B 1920x1080 527x296mm 23.8-inch                      | 1        | 2.56%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                    | 1        | 2.56%   |
| ASUSTek Computer VP248 AUS24CB 1920x1080 531x299mm 24.0-inch           | 1        | 2.56%   |
| ASUSTek Computer VG32VQ1B AUS32E0 2560x1440 697x392mm 31.5-inch        | 1        | 2.56%   |
| Ancor Communications VE249 ACI2495 1920x1080 531x299mm 24.0-inch       | 1        | 2.56%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 1        | 2.56%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 1        | 2.56%   |
| Acer VG270U ACR06C9 2560x1440 600x340mm 27.2-inch                      | 1        | 2.56%   |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch                    | 1        | 2.56%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                      | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 22       | 59.46%  |
| 3840x2160 (4K)    | 5        | 13.51%  |
| 2560x1440 (QHD)   | 4        | 10.81%  |
| 3840x1080         | 1        | 2.7%    |
| 2560x1080         | 1        | 2.7%    |
| 1920x1200 (WUXGA) | 1        | 2.7%    |
| 1440x900 (WXGA+)  | 1        | 2.7%    |
| 1366x768 (WXGA)   | 1        | 2.7%    |
| 1360x768          | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 24.32%  |
| 23      | 7        | 18.92%  |
| 24      | 4        | 10.81%  |
| 72      | 3        | 8.11%   |
| 48      | 2        | 5.41%   |
| 31      | 2        | 5.41%   |
| 21      | 2        | 5.41%   |
| 84      | 1        | 2.7%    |
| 65      | 1        | 2.7%    |
| 57      | 1        | 2.7%    |
| 46      | 1        | 2.7%    |
| 34      | 1        | 2.7%    |
| 18      | 1        | 2.7%    |
| 15      | 1        | 2.7%    |
| Unknown | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 47.22%  |
| 1001-1500   | 5        | 13.89%  |
| 601-700     | 4        | 11.11%  |
| 1501-2000   | 4        | 11.11%  |
| 401-500     | 3        | 8.33%   |
| 701-800     | 1        | 2.78%   |
| 301-350     | 1        | 2.78%   |
| Unknown     | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 32       | 94.12%  |
| 32/9  | 1        | 2.94%   |
| 21/9  | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 35.14%  |
| 301-350        | 9        | 24.32%  |
| More than 1000 | 7        | 18.92%  |
| 351-500        | 3        | 8.11%   |
| 501-1000       | 2        | 5.41%   |
| 141-150        | 1        | 2.7%    |
| 101-110        | 1        | 2.7%    |
| Unknown        | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 63.89%  |
| 1-50    | 5        | 13.89%  |
| 101-120 | 5        | 13.89%  |
| 161-240 | 1        | 2.78%   |
| 121-160 | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 84.21%  |
| 2     | 6        | 15.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 39.29%  |
| Intel                 | 18       | 32.14%  |
| Microsoft             | 4        | 7.14%   |
| Broadcom              | 4        | 7.14%   |
| TP-Link               | 1        | 1.79%   |
| Samsung Electronics   | 1        | 1.79%   |
| Qualcomm Atheros      | 1        | 1.79%   |
| OnePlus               | 1        | 1.79%   |
| Huawei Technologies   | 1        | 1.79%   |
| Google                | 1        | 1.79%   |
| Aquantia              | 1        | 1.79%   |
| Apple                 | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 26.09%  |
| Intel Wi-Fi 6 AX200                                               | 6        | 8.7%    |
| Intel I211 Gigabit Network Connection                             | 5        | 7.25%   |
| Intel Ethernet Controller I225-V                                  | 4        | 5.8%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 5.8%    |
| Microsoft XBOX ACC                                                | 3        | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 2.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.45%   |
| Realtek 802.11ac NIC                                              | 1        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.45%   |
| OnePlus OnePlus                                                   | 1        | 1.45%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.45%   |
| Intel Wireless 8260                                               | 1        | 1.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.45%   |
| Huawei LYA-L09                                                    | 1        | 1.45%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.45%   |
| Broadcom Network controller                                       | 1        | 1.45%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 1        | 1.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.45%   |
| Apple USB-Serial (0001)                                           | 1        | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 43.48%  |
| Microsoft             | 4        | 17.39%  |
| Broadcom              | 4        | 17.39%  |
| Realtek Semiconductor | 3        | 13.04%  |
| TP-Link               | 1        | 4.35%   |
| Qualcomm Atheros      | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 6        | 26.09%  |
| Microsoft XBOX ACC                                         | 3        | 13.04%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 2        | 8.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.35%   |
| Realtek 802.11ac NIC                                       | 1        | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 4.35%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1        | 4.35%   |
| Intel Wireless 8260                                        | 1        | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 4.35%   |
| Broadcom Network controller                                | 1        | 4.35%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter         | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 50%     |
| Intel                 | 16       | 36.36%  |
| Samsung Electronics   | 1        | 2.27%   |
| Qualcomm Atheros      | 1        | 2.27%   |
| OnePlus               | 1        | 2.27%   |
| Huawei Technologies   | 1        | 2.27%   |
| Google                | 1        | 2.27%   |
| Aquantia              | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 40%     |
| Intel I211 Gigabit Network Connection                             | 5        | 11.11%  |
| Intel Ethernet Controller I225-V                                  | 4        | 8.89%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 8.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.44%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 2.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.22%   |
| OnePlus OnePlus                                                   | 1        | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.22%   |
| Huawei LYA-L09                                                    | 1        | 2.22%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 2.22%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 61.67%  |
| WiFi     | 22       | 36.67%  |
| Modem    | 1        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 79.49%  |
| WiFi     | 8        | 20.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 54.05%  |
| 2     | 15       | 40.54%  |
| 3     | 2        | 5.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 70.27%  |
| Yes  | 11       | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 52.94%  |
| Broadcom                        | 2        | 11.76%  |
| TP-Link                         | 1        | 5.88%   |
| Realtek Semiconductor           | 1        | 5.88%   |
| Qualcomm Atheros Communications | 1        | 5.88%   |
| Integrated System Solution      | 1        | 5.88%   |
| Cambridge Silicon Radio         | 1        | 5.88%   |
| ASUSTek Computer                | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 5        | 29.41%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 11.76%  |
| TP-Link TPuLink UB500 Adapter                         | 1        | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 5.88%   |
| Intel Bluetooth wireless interface                    | 1        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 5.88%   |
| Intel AX210 Bluetooth                                 | 1        | 5.88%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1        | 5.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 32       | 43.84%  |
| Intel                       | 14       | 19.18%  |
| Nvidia                      | 11       | 15.07%  |
| Logitech                    | 4        | 5.48%   |
| Apple                       | 2        | 2.74%   |
| Tenx Technology             | 1        | 1.37%   |
| SteelSeries ApS             | 1        | 1.37%   |
| Sony                        | 1        | 1.37%   |
| Realtek Semiconductor       | 1        | 1.37%   |
| Quanta                      | 1        | 1.37%   |
| Kingston Technology         | 1        | 1.37%   |
| FiiO Electronics Technology | 1        | 1.37%   |
| Creative Labs               | 1        | 1.37%   |
| Corsair                     | 1        | 1.37%   |
| C-Media Electronics         | 1        | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 10.87%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9        | 9.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 7.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 7.61%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 4.35%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 3.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.17%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 2.17%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.17%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.09%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 1.09%   |
| Sony DualSense wireless controller (PS5)                                   | 1        | 1.09%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.09%   |
| Quanta USB Audio                                                           | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.09%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1        | 1.09%   |
| Logitech G733 Gaming Headset                                               | 1        | 1.09%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 1.09%   |
| Logitech Blue Microphones                                                  | 1        | 1.09%   |
| Kingston Technology HyperX Cloud Alpha S                                   | 1        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 1.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.09%   |
| FiiO Electronics Technology Q3                                             | 1        | 1.09%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.09%   |
| Corsair VOID ELITE Wireless Gaming Dongle                                  | 1        | 1.09%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.09%   |

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
| Logitech                      | 2        | 33.33%  |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Quanta                        | 1        | 16.67%  |
| Magic Control Technology      | 1        | 16.67%  |
| Apple                         | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus USB 2.0 Camera          | 1        | 16.67%  |
| Quanta HD Camera                | 1        | 16.67%  |
| Magic Control j5 WebCam JVCU100 | 1        | 16.67%  |
| Logitech Webcam C930e           | 1        | 16.67%  |
| Logitech HD Webcam C525         | 1        | 16.67%  |
| Apple iPhone 5/5C/5S/6/SE       | 1        | 16.67%  |

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
| 0     | 29       | 78.38%  |
| 1     | 7        | 18.92%  |
| 4     | 1        | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Net/wireless       | 5        | 45.45%  |
| Unassigned class   | 3        | 27.27%  |
| Sound              | 1        | 9.09%   |
| Net/ethernet       | 1        | 9.09%   |
| Fingerprint reader | 1        | 9.09%   |

