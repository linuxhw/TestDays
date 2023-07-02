Q4OS - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Q4OS/Desktop/README.md) and [notebooks](/Dist/Q4OS/Notebook/README.md).

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

Total: 77

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | D845GRG AAA84341-206        | Desktop     | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | Notebook    | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | Notebook    | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| ASUSTek       | ET1602                      | Desktop     | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [43fc15779a](https://linux-hardware.org/?probe=43fc15779a) | Apr 19, 2023 |
| HP            | 1850                        | Desktop     | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| Acer          | One S1003                   | Tablet      | [89fa2c4ac3](https://linux-hardware.org/?probe=89fa2c4ac3) | Mar 28, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | Notebook    | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6a033988f5](https://linux-hardware.org/?probe=6a033988f5) | Feb 07, 2023 |
| HP            | 1850                        | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| VXL           | M6V90AI-VL                  | Desktop     | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| MSI           | G41M4                       | Desktop     | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | Notebook    | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Unknown       | V00                         | Mini pc     | [15a2312211](https://linux-hardware.org/?probe=15a2312211) | Nov 26, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| Google        | Cave                        | Notebook    | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | Notebook    | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Medion        | P6620                       | Notebook    | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | Notebook    | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | Notebook    | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | Notebook    | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Compaq        | 07E4h                       | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| MSI           | U210                        | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | XP-M5S661GX                 | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| Phoenix/Si... | M720SR                      | Notebook    | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| TECO Elect... | TR53A0                      | Desktop     | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | Notebook    | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2               | Desktop     | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| HP            | ProBook 6550b               | Notebook    | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASUSTek       | A6JC                        | Notebook    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | Notebook    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | Notebook    | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | Notebook    | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | Notebook    | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | Notebook    | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                         | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Q4OS 4    | 40        | 64.52%  |
| Q4OS 3    | 16        | 25.81%  |
| Q4OS 2    | 5         | 8.06%   |
| Q4OS 4.11 | 1         | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 62        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-21-amd64      | 6         | 9.52%   |
| 5.10.0-19-amd64      | 4         | 6.35%   |
| 4.19.0-17-amd64      | 4         | 6.35%   |
| 5.10.0-23-amd64      | 3         | 4.76%   |
| 5.10.0-21-686-pae    | 3         | 4.76%   |
| 5.10.0-12-amd64      | 3         | 4.76%   |
| 5.10.0-8-amd64       | 2         | 3.17%   |
| 5.10.0-14-686-pae    | 2         | 3.17%   |
| 5.10.0-10-686-pae    | 2         | 3.17%   |
| 6.0.0-1-amd64        | 1         | 1.59%   |
| 5.9.0-5-amd64        | 1         | 1.59%   |
| 5.6.0-1-amd64        | 1         | 1.59%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.59%   |
| 5.10.0-9-amd64       | 1         | 1.59%   |
| 5.10.0-9-686-pae     | 1         | 1.59%   |
| 5.10.0-8-686-pae     | 1         | 1.59%   |
| 5.10.0-23-686-pae    | 1         | 1.59%   |
| 5.10.0-20-amd64      | 1         | 1.59%   |
| 5.10.0-20-686-pae    | 1         | 1.59%   |
| 5.10.0-20-686        | 1         | 1.59%   |
| 5.10.0-17-amd64      | 1         | 1.59%   |
| 5.10.0-15-686-pae    | 1         | 1.59%   |
| 5.10.0-14-amd64      | 1         | 1.59%   |
| 5.10.0-13-amd64      | 1         | 1.59%   |
| 5.10.0-12-686-pae    | 1         | 1.59%   |
| 5.10.0-11-686-pae    | 1         | 1.59%   |
| 4.9.0-9-686-pae      | 1         | 1.59%   |
| 4.9.0-8-amd64        | 1         | 1.59%   |
| 4.9.0-14-686-pae     | 1         | 1.59%   |
| 4.9.0-12-686-pae     | 1         | 1.59%   |
| 4.19.0-6-amd64       | 1         | 1.59%   |
| 4.19.0-22-amd64      | 1         | 1.59%   |
| 4.19.0-21-amd64      | 1         | 1.59%   |
| 4.19.0-20-amd64      | 1         | 1.59%   |
| 4.19.0-17-686-pae    | 1         | 1.59%   |
| 4.19.0-17-686        | 1         | 1.59%   |
| 4.19.0-16-amd64      | 1         | 1.59%   |
| 4.19.0-16-686        | 1         | 1.59%   |
| 4.19.0-14-amd64      | 1         | 1.59%   |
| 4.19.0-13-amd64      | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 37        | 59.68%  |
| 4.19.0  | 17        | 27.42%  |
| 4.9.0   | 4         | 6.45%   |
| 6.0.0   | 1         | 1.61%   |
| 5.9.0   | 1         | 1.61%   |
| 5.6.0   | 1         | 1.61%   |
| 5.18.0  | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 37        | 59.68%  |
| 4.19    | 17        | 27.42%  |
| 4.9     | 4         | 6.45%   |
| 6.0     | 1         | 1.61%   |
| 5.9     | 1         | 1.61%   |
| 5.6     | 1         | 1.61%   |
| 5.18    | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 64.52%  |
| i686   | 22        | 35.48%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| trinity  | 33        | 52.38%  |
| KDE5     | 25        | 39.68%  |
| KDE      | 2         | 3.17%   |
| LXDE     | 1         | 1.59%   |
| Cinnamon | 1         | 1.59%   |
| Budgie   | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 61        | 98.39%  |
| Tty  | 1         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 33        | 53.23%  |
| SDDM    | 28        | 45.16%  |
| LightDM | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 20        | 32.26%  |
| it_IT   | 7         | 11.29%  |
| en_GB   | 5         | 8.06%   |
| es_ES   | 4         | 6.45%   |
| de_DE   | 4         | 6.45%   |
| hu_HU   | 3         | 4.84%   |
| Unknown | 3         | 4.84%   |
| fr_FR   | 2         | 3.23%   |
| sv_SE   | 1         | 1.61%   |
| sl_SI   | 1         | 1.61%   |
| sk_SK   | 1         | 1.61%   |
| ru_RU   | 1         | 1.61%   |
| pt_BR   | 1         | 1.61%   |
| pl_PL   | 1         | 1.61%   |
| es_VE   | 1         | 1.61%   |
| es_PE   | 1         | 1.61%   |
| es_AR   | 1         | 1.61%   |
| en_ZA   | 1         | 1.61%   |
| en_SG   | 1         | 1.61%   |
| en_IE   | 1         | 1.61%   |
| C       | 1         | 1.61%   |
| bg_BG   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 39        | 62.9%   |
| EFI  | 23        | 37.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 59        | 95.16%  |
| Overlay | 3         | 4.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 33        | 53.23%  |
| GPT     | 28        | 45.16%  |
| Unknown | 1         | 1.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 87.1%   |
| Yes       | 8         | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 66.13%  |
| Yes       | 21        | 33.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 10        | 16.13%  |
| ASUSTek Computer            | 6         | 9.68%   |
| Toshiba                     | 4         | 6.45%   |
| MSI                         | 4         | 6.45%   |
| Lenovo                      | 4         | 6.45%   |
| ASRock                      | 4         | 6.45%   |
| TrekStor                    | 2         | 3.23%   |
| Sony                        | 2         | 3.23%   |
| Medion                      | 2         | 3.23%   |
| Intel                       | 2         | 3.23%   |
| Google                      | 2         | 3.23%   |
| Gigabyte Technology         | 2         | 3.23%   |
| Acer                        | 2         | 3.23%   |
| VXL                         | 1         | 1.61%   |
| Visual Land                 | 1         | 1.61%   |
| TECO Electric and Machinery | 1         | 1.61%   |
| Qilive                      | 1         | 1.61%   |
| Phoenix/SiS                 | 1         | 1.61%   |
| Philco                      | 1         | 1.61%   |
| Packard Bell                | 1         | 1.61%   |
| JVC                         | 1         | 1.61%   |
| IBM                         | 1         | 1.61%   |
| Fujitsu Siemens             | 1         | 1.61%   |
| Foxconn                     | 1         | 1.61%   |
| Dell                        | 1         | 1.61%   |
| Compaq                      | 1         | 1.61%   |
| Chuwi                       | 1         | 1.61%   |
| BESSTAR Tech                | 1         | 1.61%   |
| AMI                         | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 3.23%   |
| Toshiba Satellite C660                 | 2         | 3.23%   |
| VXL TC7500D Series                     | 1         | 1.61%   |
| Visual Land Premier 10                 | 1         | 1.61%   |
| Toshiba Satellite Pro L500             | 1         | 1.61%   |
| Toshiba Satellite M70                  | 1         | 1.61%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 1.61%   |
| Sony VGN-P11Z_Q                        | 1         | 1.61%   |
| Sony VGN-FW21Z                         | 1         | 1.61%   |
| Qilive QW19141AMSP                     | 1         | 1.61%   |
| Phoenix/SiS M720SR                     | 1         | 1.61%   |
| Philco 14I                             | 1         | 1.61%   |
| Packard Bell EasyNote LM81             | 1         | 1.61%   |
| MSI U210                               | 1         | 1.61%   |
| MSI MS-7C56                            | 1         | 1.61%   |
| MSI MS-7597                            | 1         | 1.61%   |
| MSI MS-7592                            | 1         | 1.61%   |
| Medion P6620                           | 1         | 1.61%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 1.61%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 1.61%   |
| Lenovo IdeaPad 5 14IAL7 82SD           | 1         | 1.61%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 1.61%   |
| JVC J3N                                | 1         | 1.61%   |
| Intel NUC5CPYB H61145-407              | 1         | 1.61%   |
| Intel D845GRG AAA84341-206             | 1         | 1.61%   |
| IBM ThinkPad T42 2378FVU               | 1         | 1.61%   |
| HP ProBook 6550b                       | 1         | 1.61%   |
| HP ProBook 650 G1                      | 1         | 1.61%   |
| HP ProBook 450 G2                      | 1         | 1.61%   |
| HP Presario CQ56                       | 1         | 1.61%   |
| HP Pavilion x360 Convertible 11m-ad1xx | 1         | 1.61%   |
| HP OmniBook PC                         | 1         | 1.61%   |
| HP Laptop 15s-fq2xxx                   | 1         | 1.61%   |
| HP Compaq Pro 6305 SFF                 | 1         | 1.61%   |
| HP 250 G5 Notebook PC                  | 1         | 1.61%   |
| HP 2000                                | 1         | 1.61%   |
| Google Reks                            | 1         | 1.61%   |
| Google Cave                            | 1         | 1.61%   |
| Gigabyte XP-M5S661GX                   | 1         | 1.61%   |
| Gigabyte AB350-Gaming                  | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 6.45%   |
| HP ProBook                        | 3         | 4.84%   |
| TrekStor SurfTab                  | 2         | 3.23%   |
| Lenovo ThinkPad                   | 2         | 3.23%   |
| Lenovo IdeaPad                    | 2         | 3.23%   |
| VXL TC7500D                       | 1         | 1.61%   |
| Visual Land Premier               | 1         | 1.61%   |
| TECO Electric and Machinery FUTRO | 1         | 1.61%   |
| Sony VGN-P11Z                     | 1         | 1.61%   |
| Sony VGN-FW21Z                    | 1         | 1.61%   |
| Qilive QW19141AMSP                | 1         | 1.61%   |
| Phoenix/SiS M720SR                | 1         | 1.61%   |
| Philco 14I                        | 1         | 1.61%   |
| Packard Bell EasyNote             | 1         | 1.61%   |
| MSI U210                          | 1         | 1.61%   |
| MSI MS-7C56                       | 1         | 1.61%   |
| MSI MS-7597                       | 1         | 1.61%   |
| MSI MS-7592                       | 1         | 1.61%   |
| Medion P6620                      | 1         | 1.61%   |
| JVC J3N                           | 1         | 1.61%   |
| Intel NUC5CPYB                    | 1         | 1.61%   |
| Intel D845GRG                     | 1         | 1.61%   |
| IBM ThinkPad                      | 1         | 1.61%   |
| HP Presario                       | 1         | 1.61%   |
| HP Pavilion                       | 1         | 1.61%   |
| HP OmniBook                       | 1         | 1.61%   |
| HP Laptop                         | 1         | 1.61%   |
| HP Compaq                         | 1         | 1.61%   |
| HP 250                            | 1         | 1.61%   |
| HP 2000                           | 1         | 1.61%   |
| Google Reks                       | 1         | 1.61%   |
| Google Cave                       | 1         | 1.61%   |
| Gigabyte XP-M5S661GX              | 1         | 1.61%   |
| Gigabyte AB350-Gaming             | 1         | 1.61%   |
| Fujitsu Siemens AMILO             | 1         | 1.61%   |
| Foxconn Pro                       | 1         | 1.61%   |
| Dell Latitude                     | 1         | 1.61%   |
| Compaq Evo                        | 1         | 1.61%   |
| Chuwi GemiBook                    | 1         | 1.61%   |
| BESSTAR Tech UM250                | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 9.68%   |
| 2009    | 6         | 9.68%   |
| 2016    | 5         | 8.06%   |
| 2011    | 5         | 8.06%   |
| 2020    | 4         | 6.45%   |
| 2018    | 3         | 4.84%   |
| 2015    | 3         | 4.84%   |
| 2008    | 3         | 4.84%   |
| 2005    | 3         | 4.84%   |
| 2022    | 2         | 3.23%   |
| 2019    | 2         | 3.23%   |
| 2017    | 2         | 3.23%   |
| 2014    | 2         | 3.23%   |
| 2013    | 2         | 3.23%   |
| 2012    | 2         | 3.23%   |
| 2007    | 2         | 3.23%   |
| 2006    | 2         | 3.23%   |
| 2004    | 2         | 3.23%   |
| 2002    | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| 2023    | 1         | 1.61%   |
| 2021    | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 40        | 64.52%  |
| Desktop     | 17        | 27.42%  |
| Tablet      | 3         | 4.84%   |
| Convertible | 1         | 1.61%   |
| Mini pc     | 1         | 1.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59        | 95.16%  |
| Enabled  | 3         | 4.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 96.77%  |
| Yes  | 2         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 19        | 30.65%  |
| 2.01-3.0    | 11        | 17.74%  |
| 4.01-8.0    | 8         | 12.9%   |
| 1.01-2.0    | 7         | 11.29%  |
| 0.51-1.0    | 6         | 9.68%   |
| 16.01-24.0  | 3         | 4.84%   |
| 8.01-16.0   | 3         | 4.84%   |
| 0.01-0.5    | 2         | 3.23%   |
| 32.01-64.0  | 1         | 1.61%   |
| 24.01-32.0  | 1         | 1.61%   |
| 64.01-256.0 | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 23        | 35.94%  |
| 0.51-1.0  | 15        | 23.44%  |
| 2.01-3.0  | 13        | 20.31%  |
| 0.01-0.5  | 7         | 10.94%  |
| 3.01-4.0  | 3         | 4.69%   |
| 4.01-8.0  | 2         | 3.13%   |
| 8.01-16.0 | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 74.6%   |
| 2      | 12        | 19.05%  |
| 3      | 4         | 6.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 52.38%  |
| Yes       | 30        | 47.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 83.87%  |
| No        | 10        | 16.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 72.58%  |
| No        | 17        | 27.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 62.9%   |
| Yes       | 23        | 37.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 14.52%  |
| Italy        | 8         | 12.9%   |
| UK           | 5         | 8.06%   |
| Spain        | 3         | 4.84%   |
| Kenya        | 3         | 4.84%   |
| Hungary      | 3         | 4.84%   |
| Germany      | 3         | 4.84%   |
| Venezuela    | 2         | 3.23%   |
| Switzerland  | 2         | 3.23%   |
| Romania      | 2         | 3.23%   |
| Poland       | 2         | 3.23%   |
| France       | 2         | 3.23%   |
| Brazil       | 2         | 3.23%   |
| Turkey       | 1         | 1.61%   |
| Sweden       | 1         | 1.61%   |
| South Africa | 1         | 1.61%   |
| Slovenia     | 1         | 1.61%   |
| Slovakia     | 1         | 1.61%   |
| Singapore    | 1         | 1.61%   |
| Saudi Arabia | 1         | 1.61%   |
| Russia       | 1         | 1.61%   |
| Qatar        | 1         | 1.61%   |
| Peru         | 1         | 1.61%   |
| Netherlands  | 1         | 1.61%   |
| Croatia      | 1         | 1.61%   |
| Bulgaria     | 1         | 1.61%   |
| Belgium      | 1         | 1.61%   |
| Belarus      | 1         | 1.61%   |
| Argentina    | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 4.84%   |
| Zurich                | 2         | 3.23%   |
| Swindon               | 2         | 3.23%   |
| Rostock               | 2         | 3.23%   |
| Mesa                  | 2         | 3.23%   |
| Drobeta-Turnu Severin | 2         | 3.23%   |
| Budapest              | 2         | 3.23%   |
| Bologna               | 2         | 3.23%   |
| West Corinth          | 1         | 1.61%   |
| Toalmas               | 1         | 1.61%   |
| The Hague             | 1         | 1.61%   |
| Tenbury Wells         | 1         | 1.61%   |
| Tellico Plains        | 1         | 1.61%   |
| Sosnowiec             | 1         | 1.61%   |
| Sofia                 | 1         | 1.61%   |
| Singapore             | 1         | 1.61%   |
| Schermbeck            | 1         | 1.61%   |
| Savona                | 1         | 1.61%   |
| San Carlos del Zulia  | 1         | 1.61%   |
| Salsomaggiore Terme   | 1         | 1.61%   |
| Rome                  | 1         | 1.61%   |
| Rijeka                | 1         | 1.61%   |
| Puerto Cumarebo       | 1         | 1.61%   |
| Posadas               | 1         | 1.61%   |
| Moscow                | 1         | 1.61%   |
| Mooresville           | 1         | 1.61%   |
| Moirans               | 1         | 1.61%   |
| Mogilev               | 1         | 1.61%   |
| Milano                | 1         | 1.61%   |
| Londrina              | 1         | 1.61%   |
| Ljubljana             | 1         | 1.61%   |
| Lima                  | 1         | 1.61%   |
| Las Vegas             | 1         | 1.61%   |
| Klaudyn               | 1         | 1.61%   |
| Jönköping           | 1         | 1.61%   |
| Johannesburg          | 1         | 1.61%   |
| Indianapolis          | 1         | 1.61%   |
| Guarulhos             | 1         | 1.61%   |
| Grand Junction        | 1         | 1.61%   |
| Gijón                | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 14.86%  |
| Seagate             | 11        | 13     | 14.86%  |
| Unknown             | 8         | 8      | 10.81%  |
| Samsung Electronics | 7         | 7      | 9.46%   |
| Kingston            | 6         | 6      | 8.11%   |
| SanDisk             | 5         | 5      | 6.76%   |
| Hitachi             | 3         | 3      | 4.05%   |
| China               | 3         | 4      | 4.05%   |
| Toshiba             | 2         | 2      | 2.7%    |
| KESU                | 2         | 2      | 2.7%    |
| HGST                | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| Unknown             | 2         | 2      | 2.7%    |
| Unknown (CF)        | 1         | 1      | 1.35%   |
| Transcend           | 1         | 1      | 1.35%   |
| SPCC                | 1         | 1      | 1.35%   |
| Silicon Motion      | 1         | 1      | 1.35%   |
| Phison              | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| KingSpec            | 1         | 1      | 1.35%   |
| IBM/Hitachi         | 1         | 2      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| Crucial             | 1         | 2      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 2.6%    |
| SanDisk SDSSDA120G 120GB             | 2         | 2.6%    |
| Samsung SSD 850 EVO 250GB            | 2         | 2.6%    |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.6%    |
| KESU USB 3.1 256GB                   | 2         | 2.6%    |
| Unknown                              | 2         | 2.6%    |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.3%    |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.3%    |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.3%    |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.3%    |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.3%    |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.3%    |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1.3%    |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.3%    |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.3%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.3%    |
| Unknown USDU1  32GB                  | 1         | 1.3%    |
| Unknown SLD64G  64GB                 | 1         | 1.3%    |
| Unknown SD/MMC/MS PRO 250GB          | 1         | 1.3%    |
| Unknown MMC Card  64GB               | 1         | 1.3%    |
| Unknown HAG2e  16GB                  | 1         | 1.3%    |
| Unknown 064G38  64GB                 | 1         | 1.3%    |
| Unknown (CF) Card 16GB SSD           | 1         | 1.3%    |
| Transcend TS32GHSD370 32GB SSD       | 1         | 1.3%    |
| Toshiba MK8025GAS 80GB               | 1         | 1.3%    |
| Toshiba MK6028GAL 64GB               | 1         | 1.3%    |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.3%    |
| Silicon Motion NVME SSD 512GB        | 1         | 1.3%    |
| Seagate ST96812AS 64GB               | 1         | 1.3%    |
| Seagate ST9500325AS 500GB            | 1         | 1.3%    |
| Seagate ST9120822AS 120GB            | 1         | 1.3%    |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.3%    |
| Seagate ST3500413AS 500GB            | 1         | 1.3%    |
| Seagate ST3320820SCE 320GB           | 1         | 1.3%    |
| Seagate ST3160815AS 160GB            | 1         | 1.3%    |
| Seagate ST3160812AS 160GB            | 1         | 1.3%    |
| Seagate ST310211A 10GB               | 1         | 1.3%    |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.3%    |
| Seagate Backup+ SL 1TB               | 1         | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 31.03%  |
| WDC                 | 8         | 8      | 27.59%  |
| Hitachi             | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Unknown             | 1         | 1      | 3.45%   |
| Samsung Electronics | 1         | 1      | 3.45%   |
| Maxtor              | 1         | 1      | 3.45%   |
| IBM/Hitachi         | 1         | 2      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 24%     |
| SanDisk             | 4         | 4      | 16%     |
| Samsung Electronics | 4         | 4      | 16%     |
| China               | 3         | 4      | 12%     |
| WDC                 | 2         | 2      | 8%      |
| Unknown (CF)        | 1         | 1      | 4%      |
| Transcend           | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |
| Unknown             | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 32     | 36.23%  |
| SSD     | 24        | 26     | 34.78%  |
| MMC     | 10        | 10     | 14.49%  |
| NVMe    | 6         | 7      | 8.7%    |
| Unknown | 4         | 4      | 5.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 57     | 69.12%  |
| MMC  | 10        | 10     | 14.71%  |
| NVMe | 6         | 7      | 8.82%   |
| SAS  | 5         | 5      | 7.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 52     | 87.76%  |
| 0.51-1.0   | 5         | 5      | 10.2%   |
| 4.01-10.0  | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 22.22%  |
| 1-20           | 11        | 17.46%  |
| 51-100         | 11        | 17.46%  |
| 251-500        | 10        | 15.87%  |
| 21-50          | 7         | 11.11%  |
| 1001-2000      | 4         | 6.35%   |
| 501-1000       | 3         | 4.76%   |
| More than 3000 | 2         | 3.17%   |
| Unknown        | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 66.67%  |
| 21-50          | 10        | 15.87%  |
| 101-250        | 3         | 4.76%   |
| 251-500        | 2         | 3.17%   |
| 501-1000       | 2         | 3.17%   |
| 51-100         | 2         | 3.17%   |
| More than 3000 | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1         | 1      | 6.67%   |
| WDC WD400BD-23JMC0 40GB           | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-60A23T0 250GB      | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.67%   |
| Seagate ST9120822AS 120GB         | 1         | 1      | 6.67%   |
| Seagate ST3320820SCE 320GB        | 1         | 2      | 6.67%   |
| Maxtor 6Y080L0 82GB               | 1         | 1      | 6.67%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1         | 2      | 6.67%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 6.67%   |
| Hitachi HTS543225L9SA00 250GB     | 1         | 1      | 6.67%   |
| Hitachi DK23CA-20 20GB            | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.67%   |
| HGST HTS541075A9E680 752GB        | 1         | 1      | 6.67%   |
| Fujitsu MHY2080BH 80GB            | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 4         | 4      | 26.67%  |
| Seagate     | 3         | 4      | 20%     |
| Hitachi     | 3         | 3      | 20%     |
| HGST        | 2         | 2      | 13.33%  |
| Maxtor      | 1         | 1      | 6.67%   |
| IBM/Hitachi | 1         | 2      | 6.67%   |
| Fujitsu     | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 3         | 3      | 21.43%  |
| Seagate     | 3         | 4      | 21.43%  |
| Hitachi     | 3         | 3      | 21.43%  |
| HGST        | 2         | 2      | 14.29%  |
| Maxtor      | 1         | 1      | 7.14%   |
| IBM/Hitachi | 1         | 2      | 7.14%   |
| Fujitsu     | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 38        | 46     | 56.72%  |
| Detected | 15        | 16     | 22.39%  |
| Malfunc  | 14        | 17     | 20.9%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 60%     |
| AMD                              | 11        | 18.33%  |
| Silicon Integrated Systems [SiS] | 4         | 6.67%   |
| VIA Technologies                 | 1         | 1.67%   |
| Silicon Motion                   | 1         | 1.67%   |
| SanDisk                          | 1         | 1.67%   |
| Samsung Electronics              | 1         | 1.67%   |
| Phison Electronics               | 1         | 1.67%   |
| Nvidia                           | 1         | 1.67%   |
| Micron/Crucial Technology        | 1         | 1.67%   |
| ASMedia Technology               | 1         | 1.67%   |
| ADATA Technology                 | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 10.96%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 5.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 5.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 5.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 4.11%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.74%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.74%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.74%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.37%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 1.37%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.37%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.37%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.37%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.37%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 53.97%  |
| IDE  | 22        | 34.92%  |
| NVMe | 5         | 7.94%   |
| RAID | 2         | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 46        | 74.19%  |
| AMD          | 15        | 24.19%  |
| CentaurHauls | 1         | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz             | 3         | 4.84%   |
| Intel Pentium M processor 1.70GHz           | 2         | 3.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 3.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 3.23%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 3.23%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.23%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.61%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.61%   |
| Intel Pentium III (Coppermine)              | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.61%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.61%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.61%   |
| Intel Pentium 4 CPU 1.80GHz                 | 1         | 1.61%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.61%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.61%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.61%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.61%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.61%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.61%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.61%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1         | 1.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.61%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.61%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1         | 1.61%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 1.61%   |
| Intel 12th Gen Core i5-1240P                | 1         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.61%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz   | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 8         | 12.9%   |
| Intel Atom              | 8         | 12.9%   |
| Intel Core 2 Duo        | 6         | 9.68%   |
| Intel Core i5           | 4         | 6.45%   |
| Intel Pentium M         | 3         | 4.84%   |
| Intel Pentium Dual-Core | 3         | 4.84%   |
| Intel Pentium 4         | 3         | 4.84%   |
| Intel Core i3           | 3         | 4.84%   |
| Other                   | 2         | 3.23%   |
| AMD Ryzen 7             | 2         | 3.23%   |
| AMD Athlon              | 2         | 3.23%   |
| AMD A4                  | 2         | 3.23%   |
| Intel Pentium Silver    | 1         | 1.61%   |
| Intel Pentium III       | 1         | 1.61%   |
| Intel Genuine           | 1         | 1.61%   |
| Intel Core m3           | 1         | 1.61%   |
| Intel Core i7           | 1         | 1.61%   |
| Intel Core 2            | 1         | 1.61%   |
| CentaurHauls VIA Eden   | 1         | 1.61%   |
| AMD V120                | 1         | 1.61%   |
| AMD Ryzen 7 PRO         | 1         | 1.61%   |
| AMD Ryzen 5 PRO         | 1         | 1.61%   |
| AMD Mobile Sempron      | 1         | 1.61%   |
| AMD E                   | 1         | 1.61%   |
| AMD C-70                | 1         | 1.61%   |
| AMD Athlon Neo          | 1         | 1.61%   |
| AMD Athlon II X2        | 1         | 1.61%   |
| AMD A8                  | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 45.16%  |
| 4      | 16        | 25.81%  |
| 1      | 15        | 24.19%  |
| 8      | 2         | 3.23%   |
| 12     | 1         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 69.35%  |
| 2      | 19        | 30.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 80.65%  |
| 32-bit         | 12        | 19.35%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 11.29%  |
| 0x206a7    | 5         | 8.06%   |
| 0x1067a    | 5         | 8.06%   |
| 0x30678    | 4         | 6.45%   |
| 0x706a1    | 3         | 4.84%   |
| 0x6fd      | 2         | 3.23%   |
| 0x406c4    | 2         | 3.23%   |
| 0x406c3    | 2         | 3.23%   |
| 0x106c2    | 2         | 3.23%   |
| 0x0810100b | 2         | 3.23%   |
| 0x010000c8 | 2         | 3.23%   |
| 0xf49      | 1         | 1.61%   |
| 0xf27      | 1         | 1.61%   |
| 0xf12      | 1         | 1.61%   |
| 0x906a3    | 1         | 1.61%   |
| 0x806c1    | 1         | 1.61%   |
| 0x706a8    | 1         | 1.61%   |
| 0x6fb      | 1         | 1.61%   |
| 0x6f6      | 1         | 1.61%   |
| 0x6e8      | 1         | 1.61%   |
| 0x6d8      | 1         | 1.61%   |
| 0x6d6      | 1         | 1.61%   |
| 0x695      | 1         | 1.61%   |
| 0x68a      | 1         | 1.61%   |
| 0x406e3    | 1         | 1.61%   |
| 0x40651    | 1         | 1.61%   |
| 0x306c3    | 1         | 1.61%   |
| 0x20655    | 1         | 1.61%   |
| 0x10676    | 1         | 1.61%   |
| 0x08701013 | 1         | 1.61%   |
| 0x08108102 | 1         | 1.61%   |
| 0x0800820d | 1         | 1.61%   |
| 0x07030106 | 1         | 1.61%   |
| 0x06006705 | 1         | 1.61%   |
| 0x0600111f | 1         | 1.61%   |
| 0x05000119 | 1         | 1.61%   |
| 0x0500010d | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 9         | 14.52%  |
| Penryn        | 6         | 9.68%   |
| SandyBridge   | 5         | 8.06%   |
| P6            | 5         | 8.06%   |
| Goldmont plus | 4         | 6.45%   |
| Core          | 4         | 6.45%   |
| NetBurst      | 3         | 4.84%   |
| Bonnell       | 3         | 4.84%   |
| Zen+          | 2         | 3.23%   |
| Zen           | 2         | 3.23%   |
| K8 Hammer     | 2         | 3.23%   |
| K10           | 2         | 3.23%   |
| Haswell       | 2         | 3.23%   |
| Bobcat        | 2         | 3.23%   |
| Unknown       | 2         | 3.23%   |
| Zen 2         | 1         | 1.61%   |
| Westmere      | 1         | 1.61%   |
| TigerLake     | 1         | 1.61%   |
| Skylake       | 1         | 1.61%   |
| Puma          | 1         | 1.61%   |
| Piledriver    | 1         | 1.61%   |
| K6            | 1         | 1.61%   |
| Goldmont      | 1         | 1.61%   |
| Excavator     | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 56.25%  |
| AMD                              | 15        | 23.44%  |
| Nvidia                           | 7         | 10.94%  |
| Silicon Integrated Systems [SiS] | 4         | 6.25%   |
| VIA Technologies                 | 1         | 1.56%   |
| S3 Graphics                      | 1         | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 7.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 4         | 5.88%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 4.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 4.41%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 2         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 2         | 2.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 2         | 2.94%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2         | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 2.94%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 1.47%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.47%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 1.47%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 1.47%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.47%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.47%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.47%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.47%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1         | 1.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.47%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.47%   |
| Intel HD Graphics 515                                                                      | 1         | 1.47%   |
| Intel HD Graphics 500                                                                      | 1         | 1.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.47%   |
| Intel GeminiLake [UHD Graphics 605]                                                        | 1         | 1.47%   |
| Intel Alder Lake-P Integrated Graphics Controller                                          | 1         | 1.47%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.47%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1         | 1.47%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 1.47%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 33        | 53.23%  |
| 1 x AMD         | 14        | 22.58%  |
| 1 x Nvidia      | 6         | 9.68%   |
| 1 x SiS         | 4         | 6.45%   |
| Other           | 1         | 1.61%   |
| 1 x VIA         | 1         | 1.61%   |
| 1 x S3 Graphics | 1         | 1.61%   |
| Intel + Nvidia  | 1         | 1.61%   |
| Intel + AMD     | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 82.26%  |
| Unknown     | 7         | 11.29%  |
| Proprietary | 4         | 6.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 64.52%  |
| 0.01-0.5   | 14        | 22.58%  |
| 1.01-2.0   | 5         | 8.06%   |
| 0.51-1.0   | 2         | 3.23%   |
| 3.01-4.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 18.37%  |
| AU Optronics        | 8         | 16.33%  |
| Chimei Innolux      | 7         | 14.29%  |
| Philips             | 4         | 8.16%   |
| LG Display          | 4         | 8.16%   |
| Hewlett-Packard     | 2         | 4.08%   |
| Dell                | 2         | 4.08%   |
| CPT                 | 2         | 4.08%   |
| BOE                 | 2         | 4.08%   |
| ViewSonic           | 1         | 2.04%   |
| VIE                 | 1         | 2.04%   |
| Orion               | 1         | 2.04%   |
| LG Philips          | 1         | 2.04%   |
| Iiyama              | 1         | 2.04%   |
| HannStar            | 1         | 2.04%   |
| Goldstar            | 1         | 2.04%   |
| AOC                 | 1         | 2.04%   |
| Acer                | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 6.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 4.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 4.08%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.04%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.04%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.04%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.04%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.04%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                     | 1         | 2.04%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.04%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch             | 1         | 2.04%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch             | 1         | 2.04%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.04%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1         | 2.04%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.04%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch               | 1         | 2.04%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.04%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.04%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.04%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1         | 2.04%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.04%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                    | 1         | 2.04%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.04%   |
| BOE LCD Monitor BOE069F 1366x768 256x144mm 11.6-inch                    | 1         | 2.04%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 16        | 32.65%  |
| 1920x1080 (FHD)    | 15        | 30.61%  |
| 1600x900 (HD+)     | 5         | 10.2%   |
| 1280x800 (WXGA)    | 5         | 10.2%   |
| 1920x1200 (WUXGA)  | 2         | 4.08%   |
| 1280x1024 (SXGA)   | 2         | 4.08%   |
| 3840x2160 (4K)     | 1         | 2.04%   |
| 2160x1440          | 1         | 2.04%   |
| 1920x540           | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 36.73%  |
| 24      | 6         | 12.24%  |
| 11      | 4         | 8.16%   |
| 17      | 3         | 6.12%   |
| 13      | 3         | 6.12%   |
| 23      | 2         | 4.08%   |
| 14      | 2         | 4.08%   |
| 12      | 2         | 4.08%   |
| 46      | 1         | 2.04%   |
| 40      | 1         | 2.04%   |
| 31      | 1         | 2.04%   |
| 22      | 1         | 2.04%   |
| 21      | 1         | 2.04%   |
| 20      | 1         | 2.04%   |
| 19      | 1         | 2.04%   |
| 18      | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 46.94%  |
| 501-600     | 8         | 16.33%  |
| 201-300     | 7         | 14.29%  |
| 401-500     | 4         | 8.16%   |
| 351-400     | 3         | 6.12%   |
| 801-900     | 1         | 2.04%   |
| 601-700     | 1         | 2.04%   |
| 1001-1500   | 1         | 2.04%   |
| Unknown     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 71.74%  |
| 16/10 | 9         | 19.57%  |
| 5/4   | 2         | 4.35%   |
| 32/9  | 1         | 2.17%   |
| 3/2   | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 36.73%  |
| 201-250        | 7         | 14.29%  |
| 81-90          | 5         | 10.2%   |
| 51-60          | 4         | 8.16%   |
| 251-300        | 3         | 6.12%   |
| 141-150        | 3         | 6.12%   |
| 61-70          | 2         | 4.08%   |
| 151-200        | 2         | 4.08%   |
| 501-1000       | 2         | 4.08%   |
| 351-500        | 1         | 2.04%   |
| 121-130        | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 19        | 38.78%  |
| 101-120 | 17        | 34.69%  |
| 121-160 | 8         | 16.33%  |
| 161-240 | 3         | 6.12%   |
| 1-50    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 88.71%  |
| 0     | 4         | 6.45%   |
| 2     | 2         | 3.23%   |
| 3     | 1         | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 41        | 41.41%  |
| Intel                            | 20        | 20.2%   |
| Qualcomm Atheros                 | 14        | 14.14%  |
| Broadcom                         | 4         | 4.04%   |
| Silicon Integrated Systems [SiS] | 3         | 3.03%   |
| Marvell Technology Group         | 3         | 3.03%   |
| Samsung Electronics              | 2         | 2.02%   |
| Ralink Technology                | 2         | 2.02%   |
| Broadcom Limited                 | 2         | 2.02%   |
| Xiaomi                           | 1         | 1.01%   |
| Ralink                           | 1         | 1.01%   |
| Motorola PCS                     | 1         | 1.01%   |
| LG Electronics                   | 1         | 1.01%   |
| JMicron Technology               | 1         | 1.01%   |
| IBM                              | 1         | 1.01%   |
| Guillemot                        | 1         | 1.01%   |
| Accton Technology                | 1         | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 18        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 9.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.78%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 2.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.85%   |
| Intel Wireless 7265                                                     | 2         | 1.85%   |
| Intel Wireless 3165                                                     | 2         | 1.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.93%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.93%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.93%   |
| Motorola PCS moto g(30)                                                 | 1         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.93%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 34.04%  |
| Qualcomm Atheros      | 14        | 29.79%  |
| Realtek Semiconductor | 10        | 21.28%  |
| Ralink Technology     | 2         | 4.26%   |
| Broadcom              | 2         | 4.26%   |
| Ralink                | 1         | 2.13%   |
| Guillemot             | 1         | 2.13%   |
| Broadcom Limited      | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 8.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 8.51%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 6.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 6.38%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 6.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 4.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 4.26%   |
| Intel Wireless 7265                                                         | 2         | 4.26%   |
| Intel Wireless 3165                                                         | 2         | 4.26%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 2.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 2.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.13%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 2.13%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.13%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 2.13%   |
| Intel WiFi Link 5100                                                        | 1         | 2.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.13%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 2.13%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 35        | 64.81%  |
| Intel                            | 5         | 9.26%   |
| Marvell Technology Group         | 3         | 5.56%   |
| Silicon Integrated Systems [SiS] | 2         | 3.7%    |
| Broadcom                         | 2         | 3.7%    |
| Xiaomi                           | 1         | 1.85%   |
| Qualcomm Atheros                 | 1         | 1.85%   |
| Motorola PCS                     | 1         | 1.85%   |
| LG Electronics                   | 1         | 1.85%   |
| JMicron Technology               | 1         | 1.85%   |
| Broadcom Limited                 | 1         | 1.85%   |
| Accton Technology                | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 18.52%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 5.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.85%   |
| Motorola PCS moto g(30)                                           | 1         | 1.85%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.85%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.85%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.85%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 1.85%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.85%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.85%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.85%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.85%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.85%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 50%     |
| WiFi     | 45        | 43.27%  |
| Modem    | 6         | 5.77%   |
| Unknown  | 1         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 52.54%  |
| Ethernet | 28        | 47.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 51.61%  |
| 1     | 23        | 37.1%   |
| 0     | 5         | 8.06%   |
| 3     | 2         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 88.71%  |
| Yes  | 7         | 11.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 34.78%  |
| Qualcomm Atheros Communications | 5         | 21.74%  |
| Realtek Semiconductor           | 4         | 17.39%  |
| Alps Electric                   | 2         | 8.7%    |
| Toshiba                         | 1         | 4.35%   |
| Hewlett-Packard                 | 1         | 4.35%   |
| Cambridge Silicon Radio         | 1         | 4.35%   |
| ASUSTek Computer                | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 17.39%  |
| Intel Bluetooth wireless interface                  | 4         | 17.39%  |
| Realtek Bluetooth Radio                             | 3         | 13.04%  |
| Intel AX200 Bluetooth                               | 3         | 13.04%  |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 8.7%    |
| Toshiba Askey for                                   | 1         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 37        | 60.66%  |
| AMD                              | 15        | 24.59%  |
| Nvidia                           | 4         | 6.56%   |
| Silicon Integrated Systems [SiS] | 3         | 4.92%   |
| VIA Technologies                 | 1         | 1.64%   |
| ESS Technology                   | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 6.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 5.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 4.05%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 4.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 4.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.05%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.05%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 2.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.7%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.7%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.35%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.35%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.35%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.35%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.35%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 35.82%  |
| Samsung Electronics | 12        | 17.91%  |
| SK hynix            | 8         | 11.94%  |
| Kingston            | 6         | 8.96%   |
| Unknown (ABCD)      | 2         | 2.99%   |
| Team                | 2         | 2.99%   |
| Elpida              | 2         | 2.99%   |
| A-DATA Technology   | 2         | 2.99%   |
| Unknown             | 2         | 2.99%   |
| Transcend           | 1         | 1.49%   |
| Toshiba             | 1         | 1.49%   |
| Teikon              | 1         | 1.49%   |
| S                   | 1         | 1.49%   |
| Micron Technology   | 1         | 1.49%   |
| M                   | 1         | 1.49%   |
| Crucial             | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 8.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 4.23%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 2.82%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 2.82%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 2.82%   |
| Unknown                                                          | 2         | 2.82%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.41%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.41%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.41%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.41%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.41%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.41%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.41%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.41%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.41%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.41%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.41%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1.41%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.41%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.41%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.41%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 1.41%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.41%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.41%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.41%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.41%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.41%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s                  | 1         | 1.41%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM 1334MT/s             | 1         | 1.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.41%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 33.87%  |
| DDR4    | 11        | 17.74%  |
| DDR2    | 10        | 16.13%  |
| SDRAM   | 8         | 12.9%   |
| DDR     | 5         | 8.06%   |
| LPDDR4  | 2         | 3.23%   |
| LPDDR3  | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| DRAM    | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 67.21%  |
| DIMM         | 17        | 27.87%  |
| Unknown      | 2         | 3.28%   |
| Row Of Chips | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 21        | 32.31%  |
| 4096  | 17        | 26.15%  |
| 1024  | 11        | 16.92%  |
| 8192  | 8         | 12.31%  |
| 512   | 4         | 6.15%   |
| 16384 | 2         | 3.08%   |
| 32768 | 1         | 1.54%   |
| 256   | 1         | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 13        | 20.63%  |
| 1600    | 9         | 14.29%  |
| 1333    | 6         | 9.52%   |
| 2667    | 5         | 7.94%   |
| 1334    | 5         | 7.94%   |
| 2400    | 4         | 6.35%   |
| 266     | 3         | 4.76%   |
| 3200    | 2         | 3.17%   |
| 1867    | 2         | 3.17%   |
| 1067    | 2         | 3.17%   |
| 1066    | 2         | 3.17%   |
| 800     | 2         | 3.17%   |
| 4199    | 1         | 1.59%   |
| 3600    | 1         | 1.59%   |
| 3266    | 1         | 1.59%   |
| 2666    | 1         | 1.59%   |
| 2048    | 1         | 1.59%   |
| 667     | 1         | 1.59%   |
| 533     | 1         | 1.59%   |
| 400     | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Brother HL-1110 series | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 4         | 15.38%  |
| Chicony Electronics                    | 4         | 15.38%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 11.54%  |
| Ricoh                                  | 2         | 7.69%   |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| Acer                                   | 2         | 7.69%   |
| Suyin                                  | 1         | 3.85%   |
| Silicon Motion                         | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Luxvisions Innotech Limited            | 1         | 3.85%   |
| KYE Systems (Mouse Systems)            | 1         | 3.85%   |
| ALi                                    | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.85%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.85%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.85%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.85%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.85%   |
| Realtek HP Wide Vision HD Camera                            | 1         | 3.85%   |
| Quanta Chromebook HD Camera                                 | 1         | 3.85%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.85%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 3.85%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.85%   |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.85%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.85%   |
| IMC Networks Integrated Camera                              | 1         | 3.85%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.85%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.85%   |
| Chicony Integrated Camera                                   | 1         | 3.85%   |
| Chicony HP Webcam                                           | 1         | 3.85%   |
| Chicony HP HD Webcam                                        | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 3.85%   |
| ALi M5603 Video Camera Controller                           | 1         | 3.85%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 3.85%   |
| Acer HP Webcam-101                                          | 1         | 3.85%   |
| Acer EasyCamera                                             | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 48        | 77.42%  |
| 1     | 8         | 12.9%   |
| 2     | 5         | 8.06%   |
| 4     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 40.91%  |
| Fingerprint reader       | 4         | 18.18%  |
| Flash memory             | 2         | 9.09%   |
| Communication controller | 2         | 9.09%   |
| Chipcard                 | 2         | 9.09%   |
| Network                  | 1         | 4.55%   |
| Net/wireless             | 1         | 4.55%   |
| Camera                   | 1         | 4.55%   |

