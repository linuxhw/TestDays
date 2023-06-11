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

Total: 74

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Q4OS 4    | 38        | 63.33%  |
| Q4OS 3    | 16        | 26.67%  |
| Q4OS 2    | 5         | 8.33%   |
| Q4OS 4.11 | 1         | 1.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 60        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-21-amd64      | 6         | 9.84%   |
| 5.10.0-19-amd64      | 4         | 6.56%   |
| 4.19.0-17-amd64      | 4         | 6.56%   |
| 5.10.0-21-686-pae    | 3         | 4.92%   |
| 5.10.0-12-amd64      | 3         | 4.92%   |
| 5.10.0-8-amd64       | 2         | 3.28%   |
| 5.10.0-23-amd64      | 2         | 3.28%   |
| 5.10.0-14-686-pae    | 2         | 3.28%   |
| 5.10.0-10-686-pae    | 2         | 3.28%   |
| 6.0.0-1-amd64        | 1         | 1.64%   |
| 5.9.0-5-amd64        | 1         | 1.64%   |
| 5.6.0-1-amd64        | 1         | 1.64%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.64%   |
| 5.10.0-9-amd64       | 1         | 1.64%   |
| 5.10.0-9-686-pae     | 1         | 1.64%   |
| 5.10.0-8-686-pae     | 1         | 1.64%   |
| 5.10.0-20-amd64      | 1         | 1.64%   |
| 5.10.0-20-686-pae    | 1         | 1.64%   |
| 5.10.0-20-686        | 1         | 1.64%   |
| 5.10.0-17-amd64      | 1         | 1.64%   |
| 5.10.0-15-686-pae    | 1         | 1.64%   |
| 5.10.0-14-amd64      | 1         | 1.64%   |
| 5.10.0-13-amd64      | 1         | 1.64%   |
| 5.10.0-12-686-pae    | 1         | 1.64%   |
| 5.10.0-11-686-pae    | 1         | 1.64%   |
| 4.9.0-9-686-pae      | 1         | 1.64%   |
| 4.9.0-8-amd64        | 1         | 1.64%   |
| 4.9.0-14-686-pae     | 1         | 1.64%   |
| 4.9.0-12-686-pae     | 1         | 1.64%   |
| 4.19.0-6-amd64       | 1         | 1.64%   |
| 4.19.0-22-amd64      | 1         | 1.64%   |
| 4.19.0-21-amd64      | 1         | 1.64%   |
| 4.19.0-20-amd64      | 1         | 1.64%   |
| 4.19.0-17-686-pae    | 1         | 1.64%   |
| 4.19.0-17-686        | 1         | 1.64%   |
| 4.19.0-16-amd64      | 1         | 1.64%   |
| 4.19.0-16-686        | 1         | 1.64%   |
| 4.19.0-14-amd64      | 1         | 1.64%   |
| 4.19.0-13-amd64      | 1         | 1.64%   |
| 4.19.0-12-amd64      | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 35        | 58.33%  |
| 4.19.0  | 17        | 28.33%  |
| 4.9.0   | 4         | 6.67%   |
| 6.0.0   | 1         | 1.67%   |
| 5.9.0   | 1         | 1.67%   |
| 5.6.0   | 1         | 1.67%   |
| 5.18.0  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 35        | 58.33%  |
| 4.19    | 17        | 28.33%  |
| 4.9     | 4         | 6.67%   |
| 6.0     | 1         | 1.67%   |
| 5.9     | 1         | 1.67%   |
| 5.6     | 1         | 1.67%   |
| 5.18    | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 65%     |
| i686   | 21        | 35%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 32        | 52.46%  |
| KDE5     | 24        | 39.34%  |
| KDE      | 2         | 3.28%   |
| LXDE     | 1         | 1.64%   |
| Cinnamon | 1         | 1.64%   |
| Budgie   | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 59        | 98.33%  |
| Tty  | 1         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 32        | 53.33%  |
| SDDM    | 27        | 45%     |
| LightDM | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 20        | 33.33%  |
| it_IT   | 7         | 11.67%  |
| en_GB   | 5         | 8.33%   |
| de_DE   | 4         | 6.67%   |
| es_ES   | 3         | 5%      |
| Unknown | 3         | 5%      |
| hu_HU   | 2         | 3.33%   |
| fr_FR   | 2         | 3.33%   |
| sv_SE   | 1         | 1.67%   |
| sl_SI   | 1         | 1.67%   |
| sk_SK   | 1         | 1.67%   |
| ru_RU   | 1         | 1.67%   |
| pt_BR   | 1         | 1.67%   |
| pl_PL   | 1         | 1.67%   |
| es_VE   | 1         | 1.67%   |
| es_PE   | 1         | 1.67%   |
| es_AR   | 1         | 1.67%   |
| en_ZA   | 1         | 1.67%   |
| en_SG   | 1         | 1.67%   |
| en_IE   | 1         | 1.67%   |
| C       | 1         | 1.67%   |
| bg_BG   | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 61.67%  |
| EFI  | 23        | 38.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 57        | 95%     |
| Overlay | 3         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 31        | 51.67%  |
| GPT     | 28        | 46.67%  |
| Unknown | 1         | 1.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 86.67%  |
| Yes       | 8         | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 65%     |
| Yes       | 21        | 35%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 10        | 16.67%  |
| ASUSTek Computer            | 5         | 8.33%   |
| Toshiba                     | 4         | 6.67%   |
| MSI                         | 4         | 6.67%   |
| Lenovo                      | 4         | 6.67%   |
| ASRock                      | 4         | 6.67%   |
| TrekStor                    | 2         | 3.33%   |
| Sony                        | 2         | 3.33%   |
| Medion                      | 2         | 3.33%   |
| Google                      | 2         | 3.33%   |
| Gigabyte Technology         | 2         | 3.33%   |
| Acer                        | 2         | 3.33%   |
| VXL                         | 1         | 1.67%   |
| Visual Land                 | 1         | 1.67%   |
| TECO Electric and Machinery | 1         | 1.67%   |
| Qilive                      | 1         | 1.67%   |
| Phoenix/SiS                 | 1         | 1.67%   |
| Philco                      | 1         | 1.67%   |
| Packard Bell                | 1         | 1.67%   |
| JVC                         | 1         | 1.67%   |
| Intel                       | 1         | 1.67%   |
| IBM                         | 1         | 1.67%   |
| Fujitsu Siemens             | 1         | 1.67%   |
| Foxconn                     | 1         | 1.67%   |
| Dell                        | 1         | 1.67%   |
| Compaq                      | 1         | 1.67%   |
| Chuwi                       | 1         | 1.67%   |
| BESSTAR Tech                | 1         | 1.67%   |
| AMI                         | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0            | 2         | 3.33%   |
| Toshiba Satellite C660                  | 2         | 3.33%   |
| VXL TC7500D Series                      | 1         | 1.67%   |
| Visual Land Premier 10                  | 1         | 1.67%   |
| Toshiba Satellite Pro L500              | 1         | 1.67%   |
| Toshiba Satellite M70                   | 1         | 1.67%   |
| TECO Electric and Machinery FUTRO S400  | 1         | 1.67%   |
| Sony VGN-P11Z_Q                         | 1         | 1.67%   |
| Sony VGN-FW21Z                          | 1         | 1.67%   |
| Qilive QW19141AMSP                      | 1         | 1.67%   |
| Phoenix/SiS M720SR                      | 1         | 1.67%   |
| Philco 14I                              | 1         | 1.67%   |
| Packard Bell EasyNote LM81              | 1         | 1.67%   |
| MSI U210                                | 1         | 1.67%   |
| MSI MS-7C56                             | 1         | 1.67%   |
| MSI MS-7597                             | 1         | 1.67%   |
| MSI MS-7592                             | 1         | 1.67%   |
| Medion P6620                            | 1         | 1.67%   |
| Lenovo ThinkPad T495 20NKS0PG00         | 1         | 1.67%   |
| Lenovo ThinkPad 11e 20DAS0PS00          | 1         | 1.67%   |
| Lenovo IdeaPad 5 14IAL7 82SD            | 1         | 1.67%   |
| Lenovo IdeaPad 330-15IGM 81D1           | 1         | 1.67%   |
| JVC J3N                                 | 1         | 1.67%   |
| Intel NUC5CPYB H61145-407               | 1         | 1.67%   |
| IBM ThinkPad T42 2378FVU                | 1         | 1.67%   |
| HP ProBook 6550b                        | 1         | 1.67%   |
| HP ProBook 650 G1                       | 1         | 1.67%   |
| HP ProBook 450 G2                       | 1         | 1.67%   |
| HP Presario CQ56                        | 1         | 1.67%   |
| HP Pavilion x360 Convertible 11m-ad1xx  | 1         | 1.67%   |
| HP OmniBook PC                          | 1         | 1.67%   |
| HP Laptop 15s-fq2xxx                    | 1         | 1.67%   |
| HP Compaq Pro 6305 SFF                  | 1         | 1.67%   |
| HP 250 G5 Notebook PC                   | 1         | 1.67%   |
| HP 2000                                 | 1         | 1.67%   |
| Google Reks                             | 1         | 1.67%   |
| Google Cave                             | 1         | 1.67%   |
| Gigabyte XP-M5S661GX                    | 1         | 1.67%   |
| Gigabyte AB350-Gaming                   | 1         | 1.67%   |
| Fujitsu Siemens AMILO Pro Edition V3505 | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 6.67%   |
| HP ProBook                        | 3         | 5%      |
| TrekStor SurfTab                  | 2         | 3.33%   |
| Lenovo ThinkPad                   | 2         | 3.33%   |
| Lenovo IdeaPad                    | 2         | 3.33%   |
| VXL TC7500D                       | 1         | 1.67%   |
| Visual Land Premier               | 1         | 1.67%   |
| TECO Electric and Machinery FUTRO | 1         | 1.67%   |
| Sony VGN-P11Z                     | 1         | 1.67%   |
| Sony VGN-FW21Z                    | 1         | 1.67%   |
| Qilive QW19141AMSP                | 1         | 1.67%   |
| Phoenix/SiS M720SR                | 1         | 1.67%   |
| Philco 14I                        | 1         | 1.67%   |
| Packard Bell EasyNote             | 1         | 1.67%   |
| MSI U210                          | 1         | 1.67%   |
| MSI MS-7C56                       | 1         | 1.67%   |
| MSI MS-7597                       | 1         | 1.67%   |
| MSI MS-7592                       | 1         | 1.67%   |
| Medion P6620                      | 1         | 1.67%   |
| JVC J3N                           | 1         | 1.67%   |
| Intel NUC5CPYB                    | 1         | 1.67%   |
| IBM ThinkPad                      | 1         | 1.67%   |
| HP Presario                       | 1         | 1.67%   |
| HP Pavilion                       | 1         | 1.67%   |
| HP OmniBook                       | 1         | 1.67%   |
| HP Laptop                         | 1         | 1.67%   |
| HP Compaq                         | 1         | 1.67%   |
| HP 250                            | 1         | 1.67%   |
| HP 2000                           | 1         | 1.67%   |
| Google Reks                       | 1         | 1.67%   |
| Google Cave                       | 1         | 1.67%   |
| Gigabyte XP-M5S661GX              | 1         | 1.67%   |
| Gigabyte AB350-Gaming             | 1         | 1.67%   |
| Fujitsu Siemens AMILO             | 1         | 1.67%   |
| Foxconn Pro                       | 1         | 1.67%   |
| Dell Latitude                     | 1         | 1.67%   |
| Compaq Evo                        | 1         | 1.67%   |
| Chuwi GemiBook                    | 1         | 1.67%   |
| BESSTAR Tech UM250                | 1         | 1.67%   |
| ASUS X540YA                       | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 10%     |
| 2009    | 6         | 10%     |
| 2016    | 5         | 8.33%   |
| 2020    | 4         | 6.67%   |
| 2011    | 4         | 6.67%   |
| 2018    | 3         | 5%      |
| 2015    | 3         | 5%      |
| 2008    | 3         | 5%      |
| 2005    | 3         | 5%      |
| 2022    | 2         | 3.33%   |
| 2019    | 2         | 3.33%   |
| 2017    | 2         | 3.33%   |
| 2014    | 2         | 3.33%   |
| 2013    | 2         | 3.33%   |
| 2012    | 2         | 3.33%   |
| 2007    | 2         | 3.33%   |
| 2006    | 2         | 3.33%   |
| 2004    | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 2023    | 1         | 1.67%   |
| 2021    | 1         | 1.67%   |
| 2002    | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 39        | 65%     |
| Desktop     | 16        | 26.67%  |
| Tablet      | 3         | 5%      |
| Convertible | 1         | 1.67%   |
| Mini pc     | 1         | 1.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 95%     |
| Enabled  | 3         | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 96.67%  |
| Yes  | 2         | 3.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 19        | 31.67%  |
| 2.01-3.0    | 10        | 16.67%  |
| 4.01-8.0    | 7         | 11.67%  |
| 1.01-2.0    | 7         | 11.67%  |
| 0.51-1.0    | 6         | 10%     |
| 16.01-24.0  | 3         | 5%      |
| 8.01-16.0   | 3         | 5%      |
| 0.01-0.5    | 2         | 3.33%   |
| 32.01-64.0  | 1         | 1.67%   |
| 24.01-32.0  | 1         | 1.67%   |
| 64.01-256.0 | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 22        | 36.07%  |
| 0.51-1.0  | 14        | 22.95%  |
| 2.01-3.0  | 12        | 19.67%  |
| 0.01-0.5  | 7         | 11.48%  |
| 3.01-4.0  | 3         | 4.92%   |
| 4.01-8.0  | 2         | 3.28%   |
| 8.01-16.0 | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 73.77%  |
| 2      | 12        | 19.67%  |
| 3      | 4         | 6.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 52.46%  |
| Yes       | 29        | 47.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 83.33%  |
| No        | 10        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 73.33%  |
| No        | 16        | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 63.33%  |
| Yes       | 22        | 36.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 15%     |
| Italy        | 8         | 13.33%  |
| UK           | 5         | 8.33%   |
| Spain        | 3         | 5%      |
| Kenya        | 3         | 5%      |
| Germany      | 3         | 5%      |
| Switzerland  | 2         | 3.33%   |
| Romania      | 2         | 3.33%   |
| Poland       | 2         | 3.33%   |
| Hungary      | 2         | 3.33%   |
| France       | 2         | 3.33%   |
| Brazil       | 2         | 3.33%   |
| Venezuela    | 1         | 1.67%   |
| Turkey       | 1         | 1.67%   |
| Sweden       | 1         | 1.67%   |
| South Africa | 1         | 1.67%   |
| Slovenia     | 1         | 1.67%   |
| Slovakia     | 1         | 1.67%   |
| Singapore    | 1         | 1.67%   |
| Saudi Arabia | 1         | 1.67%   |
| Russia       | 1         | 1.67%   |
| Qatar        | 1         | 1.67%   |
| Peru         | 1         | 1.67%   |
| Netherlands  | 1         | 1.67%   |
| Croatia      | 1         | 1.67%   |
| Bulgaria     | 1         | 1.67%   |
| Belgium      | 1         | 1.67%   |
| Belarus      | 1         | 1.67%   |
| Argentina    | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 5%      |
| Zurich                | 2         | 3.33%   |
| Swindon               | 2         | 3.33%   |
| Rostock               | 2         | 3.33%   |
| Mesa                  | 2         | 3.33%   |
| Drobeta-Turnu Severin | 2         | 3.33%   |
| Bologna               | 2         | 3.33%   |
| West Corinth          | 1         | 1.67%   |
| Toalmas               | 1         | 1.67%   |
| The Hague             | 1         | 1.67%   |
| Tenbury Wells         | 1         | 1.67%   |
| Tellico Plains        | 1         | 1.67%   |
| Sosnowiec             | 1         | 1.67%   |
| Sofia                 | 1         | 1.67%   |
| Singapore             | 1         | 1.67%   |
| Schermbeck            | 1         | 1.67%   |
| Savona                | 1         | 1.67%   |
| Salsomaggiore Terme   | 1         | 1.67%   |
| Rome                  | 1         | 1.67%   |
| Rijeka                | 1         | 1.67%   |
| Puerto Cumarebo       | 1         | 1.67%   |
| Posadas               | 1         | 1.67%   |
| Moscow                | 1         | 1.67%   |
| Mooresville           | 1         | 1.67%   |
| Moirans               | 1         | 1.67%   |
| Mogilev               | 1         | 1.67%   |
| Milano                | 1         | 1.67%   |
| Londrina              | 1         | 1.67%   |
| Ljubljana             | 1         | 1.67%   |
| Lima                  | 1         | 1.67%   |
| Las Vegas             | 1         | 1.67%   |
| Klaudyn               | 1         | 1.67%   |
| Jönköping           | 1         | 1.67%   |
| Johannesburg          | 1         | 1.67%   |
| Indianapolis          | 1         | 1.67%   |
| Guarulhos             | 1         | 1.67%   |
| Grand Junction        | 1         | 1.67%   |
| Gijón                | 1         | 1.67%   |
| Germantown            | 1         | 1.67%   |
| Fulham                | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 15.28%  |
| Seagate             | 10        | 12     | 13.89%  |
| Unknown             | 8         | 8      | 11.11%  |
| Samsung Electronics | 7         | 7      | 9.72%   |
| Kingston            | 6         | 6      | 8.33%   |
| SanDisk             | 5         | 5      | 6.94%   |
| Hitachi             | 3         | 3      | 4.17%   |
| China               | 3         | 4      | 4.17%   |
| Toshiba             | 2         | 2      | 2.78%   |
| KESU                | 2         | 2      | 2.78%   |
| HGST                | 2         | 2      | 2.78%   |
| A-DATA Technology   | 2         | 2      | 2.78%   |
| Unknown             | 2         | 2      | 2.78%   |
| Unknown (CF)        | 1         | 1      | 1.39%   |
| Transcend           | 1         | 1      | 1.39%   |
| SPCC                | 1         | 1      | 1.39%   |
| Silicon Motion      | 1         | 1      | 1.39%   |
| Phison              | 1         | 1      | 1.39%   |
| Maxtor              | 1         | 1      | 1.39%   |
| KingSpec            | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| Crucial             | 1         | 2      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 2.67%   |
| SanDisk SDSSDA120G 120GB             | 2         | 2.67%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.67%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.67%   |
| KESU USB 3.1 256GB                   | 2         | 2.67%   |
| Unknown                              | 2         | 2.67%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.33%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.33%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.33%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.33%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.33%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.33%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1.33%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.33%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.33%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.33%   |
| Unknown USDU1  32GB                  | 1         | 1.33%   |
| Unknown SLD64G  64GB                 | 1         | 1.33%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 1.33%   |
| Unknown MMC Card  64GB               | 1         | 1.33%   |
| Unknown HAG2e  16GB                  | 1         | 1.33%   |
| Unknown 064G38  64GB                 | 1         | 1.33%   |
| Unknown (CF) Card 16GB SSD           | 1         | 1.33%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 1.33%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.33%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.33%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.33%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.33%   |
| Seagate ST96812AS 64GB               | 1         | 1.33%   |
| Seagate ST9120822AS 120GB            | 1         | 1.33%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.33%   |
| Seagate ST3500413AS 500GB            | 1         | 1.33%   |
| Seagate ST3320820SCE 320GB           | 1         | 1.33%   |
| Seagate ST3160815AS 160GB            | 1         | 1.33%   |
| Seagate ST3160812AS 160GB            | 1         | 1.33%   |
| Seagate ST310211A 10GB               | 1         | 1.33%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.33%   |
| Seagate Backup+ SL 1TB               | 1         | 1.33%   |
| Seagate Backup+ Desk 8TB             | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 29.63%  |
| Seagate             | 8         | 10     | 29.63%  |
| Hitachi             | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 2      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |
| Unknown             | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Maxtor              | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |

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
| SSD     | 24        | 26     | 35.82%  |
| HDD     | 23        | 29     | 34.33%  |
| MMC     | 10        | 10     | 14.93%  |
| NVMe    | 6         | 7      | 8.96%   |
| Unknown | 4         | 4      | 5.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 54     | 68.18%  |
| MMC  | 10        | 10     | 15.15%  |
| NVMe | 6         | 7      | 9.09%   |
| SAS  | 5         | 5      | 7.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 49     | 87.23%  |
| 0.51-1.0   | 5         | 5      | 10.64%  |
| 4.01-10.0  | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 22.95%  |
| 1-20           | 11        | 18.03%  |
| 51-100         | 10        | 16.39%  |
| 251-500        | 9         | 14.75%  |
| 21-50          | 7         | 11.48%  |
| 1001-2000      | 4         | 6.56%   |
| 501-1000       | 3         | 4.92%   |
| More than 3000 | 2         | 3.28%   |
| Unknown        | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 40        | 65.57%  |
| 21-50          | 10        | 16.39%  |
| 101-250        | 3         | 4.92%   |
| 251-500        | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |
| 51-100         | 2         | 3.28%   |
| More than 3000 | 1         | 1.64%   |
| Unknown        | 1         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 7.69%   |
| WDC WD400BD-23JMC0 40GB          | 1         | 1      | 7.69%   |
| WDC WD2500BEVT-60A23T0 250GB     | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB      | 1         | 1      | 7.69%   |
| Seagate ST9120822AS 120GB        | 1         | 1      | 7.69%   |
| Seagate ST3320820SCE 320GB       | 1         | 2      | 7.69%   |
| Maxtor 6Y080L0 82GB              | 1         | 1      | 7.69%   |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 7.69%   |
| Hitachi HTS543225L9SA00 250GB    | 1         | 1      | 7.69%   |
| Hitachi DK23CA-20 20GB           | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB       | 1         | 1      | 7.69%   |
| HGST HTS541075A9E680 752GB       | 1         | 1      | 7.69%   |
| Fujitsu MHY2080BH 80GB           | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 30.77%  |
| Hitachi | 3         | 3      | 23.08%  |
| Seagate | 2         | 3      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Maxtor  | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 25%     |
| Hitachi | 3         | 3      | 25%     |
| Seagate | 2         | 3      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| Maxtor  | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Works    | 38        | 46     | 58.46%  |
| Detected | 15        | 16     | 23.08%  |
| Malfunc  | 12        | 14     | 18.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 34        | 58.62%  |
| AMD                              | 11        | 18.97%  |
| Silicon Integrated Systems [SiS] | 4         | 6.9%    |
| VIA Technologies                 | 1         | 1.72%   |
| Silicon Motion                   | 1         | 1.72%   |
| SanDisk                          | 1         | 1.72%   |
| Samsung Electronics              | 1         | 1.72%   |
| Phison Electronics               | 1         | 1.72%   |
| Nvidia                           | 1         | 1.72%   |
| Micron/Crucial Technology        | 1         | 1.72%   |
| ASMedia Technology               | 1         | 1.72%   |
| ADATA Technology                 | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 11.27%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 5.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 5.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 5.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 5.63%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 2.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.82%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.82%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.41%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 1.41%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.41%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.41%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.41%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.41%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.41%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 54.1%   |
| IDE  | 21        | 34.43%  |
| NVMe | 5         | 8.2%    |
| RAID | 2         | 3.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 44        | 73.33%  |
| AMD          | 15        | 25%     |
| CentaurHauls | 1         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 5%      |
| Intel Pentium M processor 1.70GHz               | 2         | 3.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 3.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 3.33%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 2         | 3.33%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 3.33%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 1.67%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.67%   |
| Intel Pentium III (Coppermine)                  | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 1.67%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 1.67%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 1.67%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 1.67%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 1.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 1.67%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1         | 1.67%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 1.67%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 1.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 1.67%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 1.67%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 1.67%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 1.67%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 1.67%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 1.67%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 1.67%   |
| Intel 12th Gen Core i5-1240P                    | 1         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 1.67%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1         | 1.67%   |
| AMD V120 Processor                              | 1         | 1.67%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 8         | 13.33%  |
| Intel Atom              | 8         | 13.33%  |
| Intel Core 2 Duo        | 6         | 10%     |
| Intel Core i5           | 4         | 6.67%   |
| Intel Pentium M         | 3         | 5%      |
| Intel Pentium Dual-Core | 3         | 5%      |
| Other                   | 2         | 3.33%   |
| Intel Pentium 4         | 2         | 3.33%   |
| Intel Core i3           | 2         | 3.33%   |
| AMD Ryzen 7             | 2         | 3.33%   |
| AMD Athlon              | 2         | 3.33%   |
| AMD A4                  | 2         | 3.33%   |
| Intel Pentium Silver    | 1         | 1.67%   |
| Intel Pentium III       | 1         | 1.67%   |
| Intel Genuine           | 1         | 1.67%   |
| Intel Core m3           | 1         | 1.67%   |
| Intel Core i7           | 1         | 1.67%   |
| Intel Core 2            | 1         | 1.67%   |
| CentaurHauls VIA Eden   | 1         | 1.67%   |
| AMD V120                | 1         | 1.67%   |
| AMD Ryzen 7 PRO         | 1         | 1.67%   |
| AMD Ryzen 5 PRO         | 1         | 1.67%   |
| AMD Mobile Sempron      | 1         | 1.67%   |
| AMD E                   | 1         | 1.67%   |
| AMD C-70                | 1         | 1.67%   |
| AMD Athlon Neo          | 1         | 1.67%   |
| AMD Athlon II X2        | 1         | 1.67%   |
| AMD A8                  | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 45%     |
| 4      | 16        | 26.67%  |
| 1      | 14        | 23.33%  |
| 8      | 2         | 3.33%   |
| 12     | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 70%     |
| 2      | 18        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 81.67%  |
| 32-bit         | 11        | 18.33%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 11.67%  |
| 0x1067a    | 5         | 8.33%   |
| 0x30678    | 4         | 6.67%   |
| 0x206a7    | 4         | 6.67%   |
| 0x706a1    | 3         | 5%      |
| 0x6fd      | 2         | 3.33%   |
| 0x406c4    | 2         | 3.33%   |
| 0x406c3    | 2         | 3.33%   |
| 0x106c2    | 2         | 3.33%   |
| 0x0810100b | 2         | 3.33%   |
| 0x010000c8 | 2         | 3.33%   |
| 0xf49      | 1         | 1.67%   |
| 0xf27      | 1         | 1.67%   |
| 0x906a3    | 1         | 1.67%   |
| 0x806c1    | 1         | 1.67%   |
| 0x706a8    | 1         | 1.67%   |
| 0x6fb      | 1         | 1.67%   |
| 0x6f6      | 1         | 1.67%   |
| 0x6e8      | 1         | 1.67%   |
| 0x6d8      | 1         | 1.67%   |
| 0x6d6      | 1         | 1.67%   |
| 0x695      | 1         | 1.67%   |
| 0x68a      | 1         | 1.67%   |
| 0x406e3    | 1         | 1.67%   |
| 0x40651    | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x20655    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x08701013 | 1         | 1.67%   |
| 0x08108102 | 1         | 1.67%   |
| 0x0800820d | 1         | 1.67%   |
| 0x07030106 | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |
| 0x0600111f | 1         | 1.67%   |
| 0x05000119 | 1         | 1.67%   |
| 0x0500010d | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 9         | 15%     |
| Penryn        | 6         | 10%     |
| P6            | 5         | 8.33%   |
| SandyBridge   | 4         | 6.67%   |
| Goldmont plus | 4         | 6.67%   |
| Core          | 4         | 6.67%   |
| Bonnell       | 3         | 5%      |
| Zen+          | 2         | 3.33%   |
| Zen           | 2         | 3.33%   |
| NetBurst      | 2         | 3.33%   |
| K8 Hammer     | 2         | 3.33%   |
| K10           | 2         | 3.33%   |
| Haswell       | 2         | 3.33%   |
| Bobcat        | 2         | 3.33%   |
| Unknown       | 2         | 3.33%   |
| Zen 2         | 1         | 1.67%   |
| Westmere      | 1         | 1.67%   |
| TigerLake     | 1         | 1.67%   |
| Skylake       | 1         | 1.67%   |
| Puma          | 1         | 1.67%   |
| Piledriver    | 1         | 1.67%   |
| K6            | 1         | 1.67%   |
| Goldmont      | 1         | 1.67%   |
| Excavator     | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 34        | 55.74%  |
| AMD                              | 15        | 24.59%  |
| Nvidia                           | 6         | 9.84%   |
| Silicon Integrated Systems [SiS] | 4         | 6.56%   |
| VIA Technologies                 | 1         | 1.64%   |
| S3 Graphics                      | 1         | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 7.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 6.15%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 4.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 4.62%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 3.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 2         | 3.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 2         | 3.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 2         | 3.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 3.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 3.08%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 1.54%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.54%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 1.54%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 1.54%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.54%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.54%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1         | 1.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.54%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.54%   |
| Intel HD Graphics 515                                                                      | 1         | 1.54%   |
| Intel HD Graphics 500                                                                      | 1         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                        | 1         | 1.54%   |
| Intel Alder Lake-P Integrated Graphics Controller                                          | 1         | 1.54%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.54%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.54%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1         | 1.54%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 1.54%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.54%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 32        | 53.33%  |
| 1 x AMD         | 14        | 23.33%  |
| 1 x Nvidia      | 6         | 10%     |
| 1 x SiS         | 4         | 6.67%   |
| Other           | 1         | 1.67%   |
| 1 x VIA         | 1         | 1.67%   |
| 1 x S3 Graphics | 1         | 1.67%   |
| Intel + AMD     | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 50        | 83.33%  |
| Unknown     | 7         | 11.67%  |
| Proprietary | 3         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 63.33%  |
| 0.01-0.5   | 14        | 23.33%  |
| 1.01-2.0   | 5         | 8.33%   |
| 0.51-1.0   | 2         | 3.33%   |
| 3.01-4.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 18.75%  |
| Chimei Innolux      | 7         | 14.58%  |
| AU Optronics        | 7         | 14.58%  |
| Philips             | 4         | 8.33%   |
| LG Display          | 4         | 8.33%   |
| Hewlett-Packard     | 2         | 4.17%   |
| Dell                | 2         | 4.17%   |
| CPT                 | 2         | 4.17%   |
| BOE                 | 2         | 4.17%   |
| ViewSonic           | 1         | 2.08%   |
| VIE                 | 1         | 2.08%   |
| Orion               | 1         | 2.08%   |
| LG Philips          | 1         | 2.08%   |
| Iiyama              | 1         | 2.08%   |
| HannStar            | 1         | 2.08%   |
| Goldstar            | 1         | 2.08%   |
| AOC                 | 1         | 2.08%   |
| Acer                | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 6.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 4.17%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.08%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.08%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.08%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.08%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch    | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch    | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.08%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                     | 1         | 2.08%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.08%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.08%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1         | 2.08%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.08%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 2.08%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.08%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.08%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.08%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1         | 2.08%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.08%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                    | 1         | 2.08%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| BOE LCD Monitor BOE069F 1366x768 256x144mm 11.6-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 31.25%  |
| 1366x768 (WXGA)    | 15        | 31.25%  |
| 1600x900 (HD+)     | 5         | 10.42%  |
| 1280x800 (WXGA)    | 5         | 10.42%  |
| 1920x1200 (WUXGA)  | 2         | 4.17%   |
| 1280x1024 (SXGA)   | 2         | 4.17%   |
| 3840x2160 (4K)     | 1         | 2.08%   |
| 2160x1440          | 1         | 2.08%   |
| 1920x540           | 1         | 2.08%   |
| 1680x1050 (WSXGA+) | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 35.42%  |
| 24      | 6         | 12.5%   |
| 11      | 4         | 8.33%   |
| 17      | 3         | 6.25%   |
| 13      | 3         | 6.25%   |
| 23      | 2         | 4.17%   |
| 14      | 2         | 4.17%   |
| 12      | 2         | 4.17%   |
| 46      | 1         | 2.08%   |
| 40      | 1         | 2.08%   |
| 31      | 1         | 2.08%   |
| 22      | 1         | 2.08%   |
| 21      | 1         | 2.08%   |
| 20      | 1         | 2.08%   |
| 19      | 1         | 2.08%   |
| 18      | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 45.83%  |
| 501-600     | 8         | 16.67%  |
| 201-300     | 7         | 14.58%  |
| 401-500     | 4         | 8.33%   |
| 351-400     | 3         | 6.25%   |
| 801-900     | 1         | 2.08%   |
| 601-700     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |
| Unknown     | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 71.11%  |
| 16/10 | 9         | 20%     |
| 5/4   | 2         | 4.44%   |
| 32/9  | 1         | 2.22%   |
| 3/2   | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 35.42%  |
| 201-250        | 7         | 14.58%  |
| 81-90          | 5         | 10.42%  |
| 51-60          | 4         | 8.33%   |
| 251-300        | 3         | 6.25%   |
| 141-150        | 3         | 6.25%   |
| 61-70          | 2         | 4.17%   |
| 151-200        | 2         | 4.17%   |
| 501-1000       | 2         | 4.17%   |
| 351-500        | 1         | 2.08%   |
| 121-130        | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 19        | 39.58%  |
| 101-120 | 16        | 33.33%  |
| 121-160 | 8         | 16.67%  |
| 161-240 | 3         | 6.25%   |
| 1-50    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 88.33%  |
| 0     | 4         | 6.67%   |
| 2     | 2         | 3.33%   |
| 3     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 40        | 41.67%  |
| Intel                            | 19        | 19.79%  |
| Qualcomm Atheros                 | 13        | 13.54%  |
| Broadcom                         | 4         | 4.17%   |
| Silicon Integrated Systems [SiS] | 3         | 3.13%   |
| Marvell Technology Group         | 3         | 3.13%   |
| Samsung Electronics              | 2         | 2.08%   |
| Ralink Technology                | 2         | 2.08%   |
| Broadcom Limited                 | 2         | 2.08%   |
| Xiaomi                           | 1         | 1.04%   |
| Ralink                           | 1         | 1.04%   |
| Motorola PCS                     | 1         | 1.04%   |
| LG Electronics                   | 1         | 1.04%   |
| JMicron Technology               | 1         | 1.04%   |
| IBM                              | 1         | 1.04%   |
| Guillemot                        | 1         | 1.04%   |
| Accton Technology                | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 17        | 16.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 9.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.86%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 2.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.9%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.9%    |
| Intel Wireless 7265                                                     | 2         | 1.9%    |
| Intel Wireless 3165                                                     | 2         | 1.9%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.95%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.95%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.95%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.95%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.95%   |
| Motorola PCS moto g(40) fusion                                          | 1         | 0.95%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.95%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 34.78%  |
| Qualcomm Atheros      | 13        | 28.26%  |
| Realtek Semiconductor | 10        | 21.74%  |
| Ralink Technology     | 2         | 4.35%   |
| Broadcom              | 2         | 4.35%   |
| Ralink                | 1         | 2.17%   |
| Guillemot             | 1         | 2.17%   |
| Broadcom Limited      | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 8.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 6.52%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 6.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 6.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 6.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 4.35%   |
| Intel Wireless 7265                                                         | 2         | 4.35%   |
| Intel Wireless 3165                                                         | 2         | 4.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 2.17%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.17%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 2.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.17%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 2.17%   |
| Intel WiFi Link 5100                                                        | 1         | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.17%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 2.17%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 34        | 65.38%  |
| Intel                            | 4         | 7.69%   |
| Marvell Technology Group         | 3         | 5.77%   |
| Silicon Integrated Systems [SiS] | 2         | 3.85%   |
| Broadcom                         | 2         | 3.85%   |
| Xiaomi                           | 1         | 1.92%   |
| Qualcomm Atheros                 | 1         | 1.92%   |
| Motorola PCS                     | 1         | 1.92%   |
| LG Electronics                   | 1         | 1.92%   |
| JMicron Technology               | 1         | 1.92%   |
| Broadcom Limited                 | 1         | 1.92%   |
| Accton Technology                | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 32.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 19.23%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 5.77%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 3.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.92%   |
| Motorola PCS moto g(40) fusion                                    | 1         | 1.92%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.92%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 1.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.92%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.92%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 1.92%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.92%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.92%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.92%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.92%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 49.5%   |
| WiFi     | 44        | 43.56%  |
| Modem    | 6         | 5.94%   |
| Unknown  | 1         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 52.63%  |
| Ethernet | 27        | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 51.67%  |
| 1     | 22        | 36.67%  |
| 0     | 5         | 8.33%   |
| 3     | 2         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 88.33%  |
| Yes  | 7         | 11.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 36.36%  |
| Realtek Semiconductor           | 4         | 18.18%  |
| Qualcomm Atheros Communications | 4         | 18.18%  |
| Alps Electric                   | 2         | 9.09%   |
| Toshiba                         | 1         | 4.55%   |
| Hewlett-Packard                 | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |
| ASUSTek Computer                | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 18.18%  |
| Realtek Bluetooth Radio                             | 3         | 13.64%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 13.64%  |
| Intel AX200 Bluetooth                               | 3         | 13.64%  |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 9.09%   |
| Toshiba Askey for                                   | 1         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 59.32%  |
| AMD                              | 15        | 25.42%  |
| Nvidia                           | 4         | 6.78%   |
| Silicon Integrated Systems [SiS] | 3         | 5.08%   |
| VIA Technologies                 | 1         | 1.69%   |
| ESS Technology                   | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 6.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.17%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.17%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.78%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.78%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.39%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 1.39%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.39%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.39%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.39%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.39%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.39%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.39%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.39%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.39%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 37.5%   |
| Samsung Electronics | 11        | 17.19%  |
| SK hynix            | 8         | 12.5%   |
| Kingston            | 6         | 9.38%   |
| Unknown (ABCD)      | 2         | 3.13%   |
| Team                | 2         | 3.13%   |
| A-DATA Technology   | 2         | 3.13%   |
| Transcend           | 1         | 1.56%   |
| Toshiba             | 1         | 1.56%   |
| Teikon              | 1         | 1.56%   |
| S                   | 1         | 1.56%   |
| Micron Technology   | 1         | 1.56%   |
| M                   | 1         | 1.56%   |
| Elpida              | 1         | 1.56%   |
| Crucial             | 1         | 1.56%   |
| Unknown             | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 8.82%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 2.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.94%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.47%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.47%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.47%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.47%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.47%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1.47%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.47%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.47%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.47%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.47%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.47%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.47%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.47%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.47%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s                  | 1         | 1.47%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM 1334MT/s             | 1         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 33.33%  |
| DDR4    | 11        | 18.33%  |
| DDR2    | 10        | 16.67%  |
| SDRAM   | 8         | 13.33%  |
| DDR     | 4         | 6.67%   |
| LPDDR4  | 2         | 3.33%   |
| LPDDR3  | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| DRAM    | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 67.8%   |
| DIMM         | 16        | 27.12%  |
| Unknown      | 2         | 3.39%   |
| Row Of Chips | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 21        | 33.33%  |
| 4096  | 16        | 25.4%   |
| 1024  | 10        | 15.87%  |
| 8192  | 8         | 12.7%   |
| 512   | 4         | 6.35%   |
| 16384 | 2         | 3.17%   |
| 32768 | 1         | 1.59%   |
| 256   | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 13        | 21.31%  |
| 1600    | 9         | 14.75%  |
| 1333    | 6         | 9.84%   |
| 2667    | 5         | 8.2%    |
| 2400    | 4         | 6.56%   |
| 1334    | 4         | 6.56%   |
| 3200    | 2         | 3.28%   |
| 1867    | 2         | 3.28%   |
| 1067    | 2         | 3.28%   |
| 1066    | 2         | 3.28%   |
| 800     | 2         | 3.28%   |
| 266     | 2         | 3.28%   |
| 4199    | 1         | 1.64%   |
| 3600    | 1         | 1.64%   |
| 3266    | 1         | 1.64%   |
| 2666    | 1         | 1.64%   |
| 2048    | 1         | 1.64%   |
| 667     | 1         | 1.64%   |
| 533     | 1         | 1.64%   |
| 400     | 1         | 1.64%   |

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
| Chicony Electronics                    | 4         | 16%     |
| IMC Networks                           | 3         | 12%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 12%     |
| Ricoh                                  | 2         | 8%      |
| Realtek Semiconductor                  | 2         | 8%      |
| Microdia                               | 2         | 8%      |
| Suyin                                  | 1         | 4%      |
| Silicon Motion                         | 1         | 4%      |
| Quanta                                 | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| KYE Systems (Mouse Systems)            | 1         | 4%      |
| Bison Electronics                      | 1         | 4%      |
| ALi                                    | 1         | 4%      |
| Alcor Micro                            | 1         | 4%      |
| Acer                                   | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4%      |
| Silicon Motion 300k Pixel Camera                            | 1         | 4%      |
| Ricoh Sony Visual Communication Camera                      | 1         | 4%      |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 4%      |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 4%      |
| Realtek HP Wide Vision HD Camera                            | 1         | 4%      |
| Quanta Chromebook HD Camera                                 | 1         | 4%      |
| Microdia Webcam Vitade AF                                   | 1         | 4%      |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4%      |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 4%      |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 4%      |
| IMC Networks Integrated Camera                              | 1         | 4%      |
| IMC Networks HP TrueVision HD Camera                        | 1         | 4%      |
| Chicony USB2.0 UVC WebCam                                   | 1         | 4%      |
| Chicony Integrated Camera                                   | 1         | 4%      |
| Chicony HP Webcam                                           | 1         | 4%      |
| Chicony HP HD Webcam                                        | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 4%      |
| Bison EasyCamera                                            | 1         | 4%      |
| ALi M5603 Video Camera Controller                           | 1         | 4%      |
| Alcor Micro USB 2.0 Camera                                  | 1         | 4%      |
| Acer HP Webcam-101                                          | 1         | 4%      |

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
| 0     | 47        | 78.33%  |
| 1     | 7         | 11.67%  |
| 2     | 5         | 8.33%   |
| 4     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 8         | 38.1%   |
| Fingerprint reader       | 4         | 19.05%  |
| Flash memory             | 2         | 9.52%   |
| Communication controller | 2         | 9.52%   |
| Chipcard                 | 2         | 9.52%   |
| Network                  | 1         | 4.76%   |
| Net/wireless             | 1         | 4.76%   |
| Camera                   | 1         | 4.76%   |

