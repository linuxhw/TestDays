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

Total: 85

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | Notebook    | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [9ebfdab7fa](https://linux-hardware.org/?probe=9ebfdab7fa) | Aug 31, 2023 |
| Acer          | Aspire 1700                 | Notebook    | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | Notebook    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [5a968533da](https://linux-hardware.org/?probe=5a968533da) | Jul 28, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
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
| Q4OS 4    | 42        | 60%     |
| Q4OS 3    | 16        | 22.86%  |
| Q4OS 5    | 6         | 8.57%   |
| Q4OS 2    | 5         | 7.14%   |
| Q4OS 4.11 | 1         | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 70        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-21-amd64      | 6         | 8.45%   |
| 5.10.0-23-amd64      | 4         | 5.63%   |
| 5.10.0-19-amd64      | 4         | 5.63%   |
| 4.19.0-17-amd64      | 4         | 5.63%   |
| 5.10.0-21-686-pae    | 3         | 4.23%   |
| 5.10.0-12-amd64      | 3         | 4.23%   |
| 5.10.0-8-amd64       | 2         | 2.82%   |
| 5.10.0-14-686-pae    | 2         | 2.82%   |
| 5.10.0-10-686-pae    | 2         | 2.82%   |
| 6.5.1-060501-generic | 1         | 1.41%   |
| 6.1.0-12-amd64       | 1         | 1.41%   |
| 6.1.0-12-686-pae     | 1         | 1.41%   |
| 6.1.0-11-686-pae     | 1         | 1.41%   |
| 6.1.0-10-amd64       | 1         | 1.41%   |
| 6.1.0-10-686-pae     | 1         | 1.41%   |
| 6.0.0-1-amd64        | 1         | 1.41%   |
| 5.9.0-5-amd64        | 1         | 1.41%   |
| 5.6.0-1-amd64        | 1         | 1.41%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.41%   |
| 5.10.0-9-amd64       | 1         | 1.41%   |
| 5.10.0-9-686-pae     | 1         | 1.41%   |
| 5.10.0-8-686-pae     | 1         | 1.41%   |
| 5.10.0-25-amd64      | 1         | 1.41%   |
| 5.10.0-23-686-pae    | 1         | 1.41%   |
| 5.10.0-20-amd64      | 1         | 1.41%   |
| 5.10.0-20-686-pae    | 1         | 1.41%   |
| 5.10.0-20-686        | 1         | 1.41%   |
| 5.10.0-17-amd64      | 1         | 1.41%   |
| 5.10.0-15-686-pae    | 1         | 1.41%   |
| 5.10.0-14-amd64      | 1         | 1.41%   |
| 5.10.0-13-amd64      | 1         | 1.41%   |
| 5.10.0-12-686-pae    | 1         | 1.41%   |
| 5.10.0-11-686-pae    | 1         | 1.41%   |
| 4.9.0-9-686-pae      | 1         | 1.41%   |
| 4.9.0-8-amd64        | 1         | 1.41%   |
| 4.9.0-14-686-pae     | 1         | 1.41%   |
| 4.9.0-12-686-pae     | 1         | 1.41%   |
| 4.19.0-6-amd64       | 1         | 1.41%   |
| 4.19.0-22-amd64      | 1         | 1.41%   |
| 4.19.0-21-amd64      | 1         | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 39        | 55.71%  |
| 4.19.0  | 17        | 24.29%  |
| 6.1.0   | 5         | 7.14%   |
| 4.9.0   | 4         | 5.71%   |
| 6.5.1   | 1         | 1.43%   |
| 6.0.0   | 1         | 1.43%   |
| 5.9.0   | 1         | 1.43%   |
| 5.6.0   | 1         | 1.43%   |
| 5.18.0  | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 39        | 55.71%  |
| 4.19    | 17        | 24.29%  |
| 6.1     | 5         | 7.14%   |
| 4.9     | 4         | 5.71%   |
| 6.5     | 1         | 1.43%   |
| 6.0     | 1         | 1.43%   |
| 5.9     | 1         | 1.43%   |
| 5.6     | 1         | 1.43%   |
| 5.18    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 45        | 64.29%  |
| i686   | 25        | 35.71%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 36        | 50.7%   |
| KDE5     | 30        | 42.25%  |
| KDE      | 2         | 2.82%   |
| LXDE     | 1         | 1.41%   |
| Cinnamon | 1         | 1.41%   |
| Budgie   | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 69        | 98.57%  |
| Tty  | 1         | 1.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 36        | 51.43%  |
| SDDM    | 33        | 47.14%  |
| LightDM | 1         | 1.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 34.29%  |
| it_IT   | 8         | 11.43%  |
| de_DE   | 7         | 10%     |
| en_GB   | 5         | 7.14%   |
| es_ES   | 4         | 5.71%   |
| hu_HU   | 3         | 4.29%   |
| Unknown | 3         | 4.29%   |
| fr_FR   | 2         | 2.86%   |
| sv_SE   | 1         | 1.43%   |
| sl_SI   | 1         | 1.43%   |
| sk_SK   | 1         | 1.43%   |
| ru_RU   | 1         | 1.43%   |
| pt_BR   | 1         | 1.43%   |
| pl_PL   | 1         | 1.43%   |
| es_VE   | 1         | 1.43%   |
| es_PE   | 1         | 1.43%   |
| es_AR   | 1         | 1.43%   |
| en_ZA   | 1         | 1.43%   |
| en_SG   | 1         | 1.43%   |
| en_IE   | 1         | 1.43%   |
| C       | 1         | 1.43%   |
| bg_BG   | 1         | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 62.86%  |
| EFI  | 26        | 37.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 95.71%  |
| Overlay | 3         | 4.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 38        | 54.29%  |
| GPT     | 31        | 44.29%  |
| Unknown | 1         | 1.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 87.14%  |
| Yes       | 9         | 12.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 64.29%  |
| Yes       | 25        | 35.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 10        | 14.29%  |
| ASUSTek Computer            | 6         | 8.57%   |
| MSI                         | 5         | 7.14%   |
| Lenovo                      | 5         | 7.14%   |
| Toshiba                     | 4         | 5.71%   |
| Gigabyte Technology         | 4         | 5.71%   |
| ASRock                      | 4         | 5.71%   |
| Acer                        | 4         | 5.71%   |
| TrekStor                    | 2         | 2.86%   |
| Sony                        | 2         | 2.86%   |
| Medion                      | 2         | 2.86%   |
| Intel                       | 2         | 2.86%   |
| Google                      | 2         | 2.86%   |
| Apple                       | 2         | 2.86%   |
| VXL                         | 1         | 1.43%   |
| Visual Land                 | 1         | 1.43%   |
| TECO Electric and Machinery | 1         | 1.43%   |
| Qilive                      | 1         | 1.43%   |
| Phoenix/SiS                 | 1         | 1.43%   |
| Philco                      | 1         | 1.43%   |
| Packard Bell                | 1         | 1.43%   |
| JVC                         | 1         | 1.43%   |
| IBM                         | 1         | 1.43%   |
| Fujitsu Siemens             | 1         | 1.43%   |
| Foxconn                     | 1         | 1.43%   |
| Dell                        | 1         | 1.43%   |
| Compaq                      | 1         | 1.43%   |
| Chuwi                       | 1         | 1.43%   |
| BESSTAR Tech                | 1         | 1.43%   |
| AMI                         | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 2.86%   |
| Toshiba Satellite C660                 | 2         | 2.86%   |
| VXL TC7500D Series                     | 1         | 1.43%   |
| Visual Land Premier 10                 | 1         | 1.43%   |
| Toshiba Satellite Pro L500             | 1         | 1.43%   |
| Toshiba Satellite M70                  | 1         | 1.43%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 1.43%   |
| Sony VGN-P11Z_Q                        | 1         | 1.43%   |
| Sony VGN-FW21Z                         | 1         | 1.43%   |
| Qilive QW19141AMSP                     | 1         | 1.43%   |
| Phoenix/SiS M720SR                     | 1         | 1.43%   |
| Philco 14I                             | 1         | 1.43%   |
| Packard Bell EasyNote LM81             | 1         | 1.43%   |
| MSI U90/U100                           | 1         | 1.43%   |
| MSI U210                               | 1         | 1.43%   |
| MSI MS-7C56                            | 1         | 1.43%   |
| MSI MS-7597                            | 1         | 1.43%   |
| MSI MS-7592                            | 1         | 1.43%   |
| Medion P6620                           | 1         | 1.43%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 1.43%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 1.43%   |
| Lenovo IdeaPad 5 14IAL7 82SD           | 1         | 1.43%   |
| Lenovo IdeaPad 330S-14IKB 81F4         | 1         | 1.43%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 1.43%   |
| JVC J3N                                | 1         | 1.43%   |
| Intel NUC5CPYB H61145-407              | 1         | 1.43%   |
| Intel D845GRG AAA84341-206             | 1         | 1.43%   |
| IBM ThinkPad T42 2378FVU               | 1         | 1.43%   |
| HP ProBook 6550b                       | 1         | 1.43%   |
| HP ProBook 650 G1                      | 1         | 1.43%   |
| HP ProBook 450 G2                      | 1         | 1.43%   |
| HP Presario CQ56                       | 1         | 1.43%   |
| HP Pavilion x360 Convertible 11m-ad1xx | 1         | 1.43%   |
| HP OmniBook PC                         | 1         | 1.43%   |
| HP Laptop 15s-fq2xxx                   | 1         | 1.43%   |
| HP Compaq Pro 6305 SFF                 | 1         | 1.43%   |
| HP 250 G5 Notebook PC                  | 1         | 1.43%   |
| HP 2000                                | 1         | 1.43%   |
| Google Reks                            | 1         | 1.43%   |
| Google Cave                            | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 5.71%   |
| Lenovo IdeaPad                    | 3         | 4.29%   |
| HP ProBook                        | 3         | 4.29%   |
| TrekStor SurfTab                  | 2         | 2.86%   |
| Lenovo ThinkPad                   | 2         | 2.86%   |
| Acer Aspire                       | 2         | 2.86%   |
| VXL TC7500D                       | 1         | 1.43%   |
| Visual Land Premier               | 1         | 1.43%   |
| TECO Electric and Machinery FUTRO | 1         | 1.43%   |
| Sony VGN-P11Z                     | 1         | 1.43%   |
| Sony VGN-FW21Z                    | 1         | 1.43%   |
| Qilive QW19141AMSP                | 1         | 1.43%   |
| Phoenix/SiS M720SR                | 1         | 1.43%   |
| Philco 14I                        | 1         | 1.43%   |
| Packard Bell EasyNote             | 1         | 1.43%   |
| MSI U90                           | 1         | 1.43%   |
| MSI U210                          | 1         | 1.43%   |
| MSI MS-7C56                       | 1         | 1.43%   |
| MSI MS-7597                       | 1         | 1.43%   |
| MSI MS-7592                       | 1         | 1.43%   |
| Medion P6620                      | 1         | 1.43%   |
| JVC J3N                           | 1         | 1.43%   |
| Intel NUC5CPYB                    | 1         | 1.43%   |
| Intel D845GRG                     | 1         | 1.43%   |
| IBM ThinkPad                      | 1         | 1.43%   |
| HP Presario                       | 1         | 1.43%   |
| HP Pavilion                       | 1         | 1.43%   |
| HP OmniBook                       | 1         | 1.43%   |
| HP Laptop                         | 1         | 1.43%   |
| HP Compaq                         | 1         | 1.43%   |
| HP 250                            | 1         | 1.43%   |
| HP 2000                           | 1         | 1.43%   |
| Google Reks                       | 1         | 1.43%   |
| Google Cave                       | 1         | 1.43%   |
| Gigabyte Z690                     | 1         | 1.43%   |
| Gigabyte XP-M5S661GX              | 1         | 1.43%   |
| Gigabyte H55M-USB3                | 1         | 1.43%   |
| Gigabyte AB350-Gaming             | 1         | 1.43%   |
| Fujitsu Siemens AMILO             | 1         | 1.43%   |
| Foxconn Pro                       | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 8         | 11.43%  |
| 2010    | 7         | 10%     |
| 2011    | 6         | 8.57%   |
| 2016    | 5         | 7.14%   |
| 2020    | 4         | 5.71%   |
| 2018    | 4         | 5.71%   |
| 2008    | 4         | 5.71%   |
| 2015    | 3         | 4.29%   |
| 2012    | 3         | 4.29%   |
| 2005    | 3         | 4.29%   |
| 2022    | 2         | 2.86%   |
| 2019    | 2         | 2.86%   |
| 2017    | 2         | 2.86%   |
| 2014    | 2         | 2.86%   |
| 2013    | 2         | 2.86%   |
| 2007    | 2         | 2.86%   |
| 2006    | 2         | 2.86%   |
| 2004    | 2         | 2.86%   |
| 2002    | 2         | 2.86%   |
| Unknown | 2         | 2.86%   |
| 2023    | 1         | 1.43%   |
| 2021    | 1         | 1.43%   |
| 2003    | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 45        | 64.29%  |
| Desktop     | 19        | 27.14%  |
| Tablet      | 3         | 4.29%   |
| Convertible | 1         | 1.43%   |
| Mini pc     | 1         | 1.43%   |
| All in one  | 1         | 1.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 67        | 95.71%  |
| Enabled  | 3         | 4.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 97.14%  |
| Yes  | 2         | 2.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 20        | 28.57%  |
| 2.01-3.0    | 12        | 17.14%  |
| 4.01-8.0    | 9         | 12.86%  |
| 1.01-2.0    | 8         | 11.43%  |
| 0.51-1.0    | 6         | 8.57%   |
| 16.01-24.0  | 4         | 5.71%   |
| 8.01-16.0   | 4         | 5.71%   |
| 0.01-0.5    | 3         | 4.29%   |
| 64.01-256.0 | 2         | 2.86%   |
| 32.01-64.0  | 1         | 1.43%   |
| 24.01-32.0  | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 34.72%  |
| 0.51-1.0  | 17        | 23.61%  |
| 2.01-3.0  | 14        | 19.44%  |
| 0.01-0.5  | 8         | 11.11%  |
| 4.01-8.0  | 4         | 5.56%   |
| 3.01-4.0  | 3         | 4.17%   |
| 8.01-16.0 | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 70.42%  |
| 2      | 15        | 21.13%  |
| 3      | 6         | 8.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 50.7%   |
| Yes       | 35        | 49.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 87.14%  |
| No        | 9         | 12.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 74.29%  |
| No        | 18        | 25.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 62.86%  |
| Yes       | 26        | 37.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 14.29%  |
| Italy        | 9         | 12.86%  |
| Germany      | 6         | 8.57%   |
| UK           | 5         | 7.14%   |
| Spain        | 3         | 4.29%   |
| Kenya        | 3         | 4.29%   |
| Hungary      | 3         | 4.29%   |
| Venezuela    | 2         | 2.86%   |
| Turkey       | 2         | 2.86%   |
| Switzerland  | 2         | 2.86%   |
| Romania      | 2         | 2.86%   |
| Poland       | 2         | 2.86%   |
| Mexico       | 2         | 2.86%   |
| France       | 2         | 2.86%   |
| Brazil       | 2         | 2.86%   |
| Sweden       | 1         | 1.43%   |
| South Africa | 1         | 1.43%   |
| Slovenia     | 1         | 1.43%   |
| Slovakia     | 1         | 1.43%   |
| Singapore    | 1         | 1.43%   |
| Saudi Arabia | 1         | 1.43%   |
| Russia       | 1         | 1.43%   |
| Qatar        | 1         | 1.43%   |
| Peru         | 1         | 1.43%   |
| Netherlands  | 1         | 1.43%   |
| Croatia      | 1         | 1.43%   |
| Bulgaria     | 1         | 1.43%   |
| Belgium      | 1         | 1.43%   |
| Belarus      | 1         | 1.43%   |
| Argentina    | 1         | 1.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 4.29%   |
| Zurich                | 2         | 2.86%   |
| Swindon               | 2         | 2.86%   |
| Rostock               | 2         | 2.86%   |
| Morelia               | 2         | 2.86%   |
| Mesa                  | 2         | 2.86%   |
| Drobeta-Turnu Severin | 2         | 2.86%   |
| Budapest              | 2         | 2.86%   |
| Bologna               | 2         | 2.86%   |
| West Corinth          | 1         | 1.43%   |
| Toalmas               | 1         | 1.43%   |
| The Hague             | 1         | 1.43%   |
| Tenbury Wells         | 1         | 1.43%   |
| Tellico Plains        | 1         | 1.43%   |
| Sosnowiec             | 1         | 1.43%   |
| Solingen              | 1         | 1.43%   |
| Sofia                 | 1         | 1.43%   |
| Singapore             | 1         | 1.43%   |
| Schermbeck            | 1         | 1.43%   |
| Savona                | 1         | 1.43%   |
| San Carlos del Zulia  | 1         | 1.43%   |
| Salsomaggiore Terme   | 1         | 1.43%   |
| Rome                  | 1         | 1.43%   |
| Rijeka                | 1         | 1.43%   |
| Puerto Cumarebo       | 1         | 1.43%   |
| Posadas               | 1         | 1.43%   |
| Osnabrück            | 1         | 1.43%   |
| Moscow                | 1         | 1.43%   |
| Mooresville           | 1         | 1.43%   |
| Moirans               | 1         | 1.43%   |
| Mogilev               | 1         | 1.43%   |
| Milano                | 1         | 1.43%   |
| Mannheim              | 1         | 1.43%   |
| Londrina              | 1         | 1.43%   |
| Ljubljana             | 1         | 1.43%   |
| Lima                  | 1         | 1.43%   |
| Las Vegas             | 1         | 1.43%   |
| Klaudyn               | 1         | 1.43%   |
| Jönköping           | 1         | 1.43%   |
| Johannesburg          | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 14.12%  |
| Seagate             | 12        | 14     | 14.12%  |
| Samsung Electronics | 9         | 10     | 10.59%  |
| Unknown             | 8         | 8      | 9.41%   |
| SanDisk             | 7         | 9      | 8.24%   |
| Kingston            | 7         | 7      | 8.24%   |
| Toshiba             | 3         | 3      | 3.53%   |
| Hitachi             | 3         | 3      | 3.53%   |
| China               | 3         | 4      | 3.53%   |
| KESU                | 2         | 2      | 2.35%   |
| HGST                | 2         | 2      | 2.35%   |
| Fujitsu             | 2         | 2      | 2.35%   |
| A-DATA Technology   | 2         | 2      | 2.35%   |
| Unknown             | 2         | 2      | 2.35%   |
| USB3.0              | 1         | 1      | 1.18%   |
| Unknown (CF)        | 1         | 1      | 1.18%   |
| Transcend           | 1         | 1      | 1.18%   |
| SPCC                | 1         | 1      | 1.18%   |
| Silicon Motion      | 1         | 1      | 1.18%   |
| Phison              | 1         | 1      | 1.18%   |
| Maxtor              | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| KBG40ZNV            | 1         | 1      | 1.18%   |
| IBM/Hitachi         | 1         | 2      | 1.18%   |
| Crucial             | 1         | 2      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 2.22%   |
| SanDisk SDSSDA120G 120GB             | 2         | 2.22%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.22%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.22%   |
| KESU USB 3.1 256GB                   | 2         | 2.22%   |
| Unknown                              | 2         | 2.22%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.11%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.11%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.11%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.11%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.11%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.11%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.11%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1.11%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.11%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.11%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.11%   |
| USB3.0 Super Speed 2TB               | 1         | 1.11%   |
| Unknown USDU1  32GB                  | 1         | 1.11%   |
| Unknown SLD64G  64GB                 | 1         | 1.11%   |
| Unknown SD/MMC/MS PRO 16GB           | 1         | 1.11%   |
| Unknown MMC Card  64GB               | 1         | 1.11%   |
| Unknown HAG2e  16GB                  | 1         | 1.11%   |
| Unknown 064G38  64GB                 | 1         | 1.11%   |
| Unknown (CF) Card 32GB               | 1         | 1.11%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 1.11%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.11%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.11%   |
| Toshiba MK3252GSX 320GB              | 1         | 1.11%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.11%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.11%   |
| Seagate ST96812AS 64GB               | 1         | 1.11%   |
| Seagate ST9500325AS 500GB            | 1         | 1.11%   |
| Seagate ST9120822AS 120GB            | 1         | 1.11%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.11%   |
| Seagate ST380012A 80GB               | 1         | 1.11%   |
| Seagate ST3500413AS 500GB            | 1         | 1.11%   |
| Seagate ST3320820SCE 320GB           | 1         | 1.11%   |
| Seagate ST3160815AS 160GB            | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 29.41%  |
| WDC                 | 9         | 9      | 26.47%  |
| Toshiba             | 3         | 3      | 8.82%   |
| Hitachi             | 3         | 3      | 8.82%   |
| HGST                | 2         | 2      | 5.88%   |
| Fujitsu             | 2         | 2      | 5.88%   |
| USB3.0              | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Maxtor              | 1         | 1      | 2.94%   |
| IBM/Hitachi         | 1         | 2      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 25%     |
| SanDisk             | 5         | 7      | 17.86%  |
| Samsung Electronics | 5         | 5      | 17.86%  |
| China               | 3         | 4      | 10.71%  |
| WDC                 | 2         | 2      | 7.14%   |
| Unknown (CF)        | 1         | 1      | 3.57%   |
| Transcend           | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |
| Unknown             | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 37     | 37.97%  |
| SSD     | 27        | 31     | 34.18%  |
| MMC     | 10        | 10     | 12.66%  |
| NVMe    | 8         | 11     | 10.13%  |
| Unknown | 4         | 4      | 5.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 66     | 68.35%  |
| MMC  | 10        | 10     | 12.66%  |
| NVMe | 8         | 10     | 10.13%  |
| SAS  | 7         | 7      | 8.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 60     | 85.96%  |
| 0.51-1.0   | 5         | 5      | 8.77%   |
| 1.01-2.0   | 2         | 2      | 3.51%   |
| 4.01-10.0  | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 22.54%  |
| 51-100         | 13        | 18.31%  |
| 251-500        | 11        | 15.49%  |
| 1-20           | 11        | 15.49%  |
| 21-50          | 8         | 11.27%  |
| 501-1000       | 5         | 7.04%   |
| 1001-2000      | 4         | 5.63%   |
| More than 3000 | 2         | 2.82%   |
| Unknown        | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 64.79%  |
| 21-50          | 11        | 15.49%  |
| 51-100         | 4         | 5.63%   |
| 251-500        | 3         | 4.23%   |
| 101-250        | 3         | 4.23%   |
| 501-1000       | 2         | 2.82%   |
| More than 3000 | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1         | 1      | 5.88%   |
| WDC WD400BD-23JMC0 40GB           | 1         | 1      | 5.88%   |
| WDC WD2500BEVT-60A23T0 250GB      | 1         | 1      | 5.88%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 5.88%   |
| Toshiba MK3252GSX 320GB           | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 5.88%   |
| Seagate ST9120822AS 120GB         | 1         | 1      | 5.88%   |
| Seagate ST3320820SCE 320GB        | 1         | 2      | 5.88%   |
| Maxtor 6Y080L0 82GB               | 1         | 1      | 5.88%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1         | 2      | 5.88%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9SA00 250GB     | 1         | 1      | 5.88%   |
| Hitachi DK23CA-20 20GB            | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 5.88%   |
| HGST HTS541075A9E680 752GB        | 1         | 1      | 5.88%   |
| Fujitsu MHZ2160BH G2 160GB        | 1         | 1      | 5.88%   |
| Fujitsu MHY2080BH 80GB            | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 4         | 4      | 23.53%  |
| Seagate     | 3         | 4      | 17.65%  |
| Hitachi     | 3         | 3      | 17.65%  |
| HGST        | 2         | 2      | 11.76%  |
| Fujitsu     | 2         | 2      | 11.76%  |
| Toshiba     | 1         | 1      | 5.88%   |
| Maxtor      | 1         | 1      | 5.88%   |
| IBM/Hitachi | 1         | 2      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 3         | 3      | 18.75%  |
| Seagate     | 3         | 4      | 18.75%  |
| Hitachi     | 3         | 3      | 18.75%  |
| HGST        | 2         | 2      | 12.5%   |
| Fujitsu     | 2         | 2      | 12.5%   |
| Toshiba     | 1         | 1      | 6.25%   |
| Maxtor      | 1         | 1      | 6.25%   |
| IBM/Hitachi | 1         | 2      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 93.75%  |
| SSD  | 1         | 1      | 6.25%   |

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
| Works    | 44        | 57     | 57.89%  |
| Detected | 16        | 17     | 21.05%  |
| Malfunc  | 16        | 19     | 21.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 59.72%  |
| AMD                              | 11        | 15.28%  |
| Silicon Integrated Systems [SiS] | 5         | 6.94%   |
| Samsung Electronics              | 3         | 4.17%   |
| SanDisk                          | 2         | 2.78%   |
| VIA Technologies                 | 1         | 1.39%   |
| Silicon Motion                   | 1         | 1.39%   |
| Phison Electronics               | 1         | 1.39%   |
| Nvidia                           | 1         | 1.39%   |
| Micron/Crucial Technology        | 1         | 1.39%   |
| JMicron Technology               | 1         | 1.39%   |
| ASMedia Technology               | 1         | 1.39%   |
| ADATA Technology                 | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.2%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 5         | 5.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 5.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 4.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 4.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 3.45%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.3%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.3%    |
| Intel 82801DB (ICH4) IDE Controller                                              | 2         | 2.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.3%    |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.15%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.15%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 1.15%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.15%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.15%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.15%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.15%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.15%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.15%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.15%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 41        | 53.95%  |
| IDE  | 26        | 34.21%  |
| NVMe | 7         | 9.21%   |
| RAID | 2         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 54        | 77.14%  |
| AMD          | 15        | 21.43%  |
| CentaurHauls | 1         | 1.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz             | 3         | 4.29%   |
| Intel Atom CPU N270 @ 1.60GHz               | 3         | 4.29%   |
| Intel Pentium M processor 1.70GHz           | 2         | 2.86%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 2.86%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 2.86%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.86%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.43%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.43%   |
| Intel Pentium III (Coppermine)              | 1         | 1.43%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.43%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 1.43%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.43%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.43%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.43%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.43%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.43%   |
| Intel Pentium 4 CPU 1.80GHz                 | 1         | 1.43%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.43%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.43%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.43%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.43%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.43%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.43%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.43%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.43%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.43%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.43%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.43%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.43%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1         | 1.43%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 10        | 14.29%  |
| Intel Celeron           | 8         | 11.43%  |
| Intel Core 2 Duo        | 7         | 10%     |
| Intel Pentium 4         | 4         | 5.71%   |
| Intel Core i5           | 4         | 5.71%   |
| Intel Core i3           | 4         | 5.71%   |
| Other                   | 3         | 4.29%   |
| Intel Pentium M         | 3         | 4.29%   |
| Intel Pentium Dual-Core | 3         | 4.29%   |
| Intel Core i7           | 2         | 2.86%   |
| AMD Ryzen 7             | 2         | 2.86%   |
| AMD Athlon              | 2         | 2.86%   |
| AMD A4                  | 2         | 2.86%   |
| Intel Pentium Silver    | 1         | 1.43%   |
| Intel Pentium III       | 1         | 1.43%   |
| Intel Pentium           | 1         | 1.43%   |
| Intel Genuine           | 1         | 1.43%   |
| Intel Core m3           | 1         | 1.43%   |
| Intel Core 2            | 1         | 1.43%   |
| CentaurHauls VIA Eden   | 1         | 1.43%   |
| AMD V120                | 1         | 1.43%   |
| AMD Ryzen 7 PRO         | 1         | 1.43%   |
| AMD Ryzen 5 PRO         | 1         | 1.43%   |
| AMD Mobile Sempron      | 1         | 1.43%   |
| AMD E                   | 1         | 1.43%   |
| AMD C-70                | 1         | 1.43%   |
| AMD Athlon Neo          | 1         | 1.43%   |
| AMD Athlon II X2        | 1         | 1.43%   |
| AMD A8                  | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 44.29%  |
| 1      | 18        | 25.71%  |
| 4      | 17        | 24.29%  |
| 8      | 2         | 2.86%   |
| 16     | 1         | 1.43%   |
| 12     | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 64.29%  |
| 2      | 25        | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 78.57%  |
| 32-bit         | 15        | 21.43%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 12.86%  |
| 0x206a7    | 5         | 7.14%   |
| 0x1067a    | 5         | 7.14%   |
| 0x30678    | 4         | 5.71%   |
| 0x106c2    | 4         | 5.71%   |
| 0x706a1    | 3         | 4.29%   |
| 0xf27      | 2         | 2.86%   |
| 0x6fd      | 2         | 2.86%   |
| 0x406c4    | 2         | 2.86%   |
| 0x406c3    | 2         | 2.86%   |
| 0x10676    | 2         | 2.86%   |
| 0x0810100b | 2         | 2.86%   |
| 0x010000c8 | 2         | 2.86%   |
| 0xf49      | 1         | 1.43%   |
| 0xf12      | 1         | 1.43%   |
| 0xb0671    | 1         | 1.43%   |
| 0x906a3    | 1         | 1.43%   |
| 0x806e9    | 1         | 1.43%   |
| 0x806c1    | 1         | 1.43%   |
| 0x706a8    | 1         | 1.43%   |
| 0x6fb      | 1         | 1.43%   |
| 0x6f6      | 1         | 1.43%   |
| 0x6e8      | 1         | 1.43%   |
| 0x6d8      | 1         | 1.43%   |
| 0x6d6      | 1         | 1.43%   |
| 0x695      | 1         | 1.43%   |
| 0x68a      | 1         | 1.43%   |
| 0x406e3    | 1         | 1.43%   |
| 0x40651    | 1         | 1.43%   |
| 0x306c3    | 1         | 1.43%   |
| 0x20655    | 1         | 1.43%   |
| 0x08701013 | 1         | 1.43%   |
| 0x08108102 | 1         | 1.43%   |
| 0x0800820d | 1         | 1.43%   |
| 0x07030106 | 1         | 1.43%   |
| 0x06006705 | 1         | 1.43%   |
| 0x0600111f | 1         | 1.43%   |
| 0x05000119 | 1         | 1.43%   |
| 0x0500010d | 1         | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 9         | 12.86%  |
| Penryn           | 7         | 10%     |
| SandyBridge      | 6         | 8.57%   |
| P6               | 5         | 7.14%   |
| Bonnell          | 5         | 7.14%   |
| NetBurst         | 4         | 5.71%   |
| Goldmont plus    | 4         | 5.71%   |
| Core             | 4         | 5.71%   |
| Zen+             | 2         | 2.86%   |
| Zen              | 2         | 2.86%   |
| K8 Hammer        | 2         | 2.86%   |
| K10              | 2         | 2.86%   |
| Haswell          | 2         | 2.86%   |
| Bobcat           | 2         | 2.86%   |
| Unknown          | 2         | 2.86%   |
| Zen 2            | 1         | 1.43%   |
| Westmere         | 1         | 1.43%   |
| TigerLake        | 1         | 1.43%   |
| Skylake          | 1         | 1.43%   |
| Puma             | 1         | 1.43%   |
| Piledriver       | 1         | 1.43%   |
| Nehalem          | 1         | 1.43%   |
| KabyLake         | 1         | 1.43%   |
| K6               | 1         | 1.43%   |
| Goldmont         | 1         | 1.43%   |
| Excavator        | 1         | 1.43%   |
| Alderlake Hybrid | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 42        | 56.76%  |
| AMD                              | 16        | 21.62%  |
| Nvidia                           | 9         | 12.16%  |
| Silicon Integrated Systems [SiS] | 5         | 6.76%   |
| VIA Technologies                 | 1         | 1.35%   |
| S3 Graphics                      | 1         | 1.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 6.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 5         | 6.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 4         | 4.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 4.94%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 3         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 3         | 3.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 3         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 3.7%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 2.47%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2         | 2.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 2.47%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 2.47%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.23%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 1.23%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 1.23%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1         | 1.23%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.23%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.23%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.23%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 1.23%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.23%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.23%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.23%   |
| Intel HD Graphics 610                                                                      | 1         | 1.23%   |
| Intel HD Graphics 515                                                                      | 1         | 1.23%   |
| Intel HD Graphics 500                                                                      | 1         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.23%   |
| Intel GeminiLake [UHD Graphics 605]                                                        | 1         | 1.23%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 1         | 1.23%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.23%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 34        | 48.57%  |
| 1 x AMD         | 14        | 20%     |
| 1 x Nvidia      | 7         | 10%     |
| 1 x SiS         | 5         | 7.14%   |
| 2 x Intel       | 3         | 4.29%   |
| Intel + Nvidia  | 2         | 2.86%   |
| Intel + AMD     | 2         | 2.86%   |
| Other           | 1         | 1.43%   |
| 1 x VIA         | 1         | 1.43%   |
| 1 x S3 Graphics | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 80%     |
| Unknown     | 8         | 11.43%  |
| Proprietary | 6         | 8.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 67.14%  |
| 0.01-0.5   | 14        | 20%     |
| 1.01-2.0   | 5         | 7.14%   |
| 0.51-1.0   | 3         | 4.29%   |
| 3.01-4.0   | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 10        | 17.54%  |
| AU Optronics            | 8         | 14.04%  |
| Chimei Innolux          | 7         | 12.28%  |
| LG Display              | 5         | 8.77%   |
| Philips                 | 4         | 7.02%   |
| Dell                    | 3         | 5.26%   |
| Hewlett-Packard         | 2         | 3.51%   |
| HannStar                | 2         | 3.51%   |
| CPT                     | 2         | 3.51%   |
| BOE                     | 2         | 3.51%   |
| Apple                   | 2         | 3.51%   |
| ViewSonic               | 1         | 1.75%   |
| VIE                     | 1         | 1.75%   |
| Orion                   | 1         | 1.75%   |
| MQP                     | 1         | 1.75%   |
| LG Philips              | 1         | 1.75%   |
| Iiyama                  | 1         | 1.75%   |
| Goldstar                | 1         | 1.75%   |
| Chi Mei Optoelectronics | 1         | 1.75%   |
| AOC                     | 1         | 1.75%   |
| Acer                    | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 3         | 5.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 3.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 3.51%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                | 1         | 1.75%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                            | 1         | 1.75%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch        | 1         | 1.75%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch        | 1         | 1.75%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch  | 1         | 1.75%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 1.75%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                      | 1         | 1.75%   |
| Orion ORION ORN120A 1920x540                                             | 1         | 1.75%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 1.75%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 1.75%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                   | 1         | 1.75%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 1.75%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch                | 1         | 1.75%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.75%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 1.75%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                     | 1         | 1.75%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 1.75%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                 | 1         | 1.75%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                       | 1         | 1.75%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 1.75%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 1.75%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 1.75%   |
| BOE LCD Monitor BOE069F 1366x768 256x144mm 11.6-inch                     | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 29.82%  |
| 1366x768 (WXGA)    | 16        | 28.07%  |
| 1280x800 (WXGA)    | 6         | 10.53%  |
| 1600x900 (HD+)     | 5         | 8.77%   |
| 1920x1200 (WUXGA)  | 3         | 5.26%   |
| 3840x2160 (4K)     | 2         | 3.51%   |
| 1280x1024 (SXGA)   | 2         | 3.51%   |
| 1024x600           | 2         | 3.51%   |
| 800x600            | 1         | 1.75%   |
| 2160x1440          | 1         | 1.75%   |
| 1920x540           | 1         | 1.75%   |
| 1680x1050 (WSXGA+) | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 31.58%  |
| 24      | 7         | 12.28%  |
| 13      | 4         | 7.02%   |
| 11      | 4         | 7.02%   |
| 17      | 3         | 5.26%   |
| 14      | 3         | 5.26%   |
| 12      | 3         | 5.26%   |
| 23      | 2         | 3.51%   |
| 21      | 2         | 3.51%   |
| 10      | 2         | 3.51%   |
| 46      | 1         | 1.75%   |
| 40      | 1         | 1.75%   |
| 31      | 1         | 1.75%   |
| 27      | 1         | 1.75%   |
| 22      | 1         | 1.75%   |
| 20      | 1         | 1.75%   |
| 19      | 1         | 1.75%   |
| 18      | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 42.86%  |
| 201-300     | 10        | 17.86%  |
| 501-600     | 9         | 16.07%  |
| 401-500     | 5         | 8.93%   |
| 351-400     | 3         | 5.36%   |
| 601-700     | 2         | 3.57%   |
| 801-900     | 1         | 1.79%   |
| 1001-1500   | 1         | 1.79%   |
| Unknown     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 70.37%  |
| 16/10 | 11        | 20.37%  |
| 5/4   | 2         | 3.7%    |
| 4/3   | 1         | 1.85%   |
| 32/9  | 1         | 1.85%   |
| 3/2   | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 31.58%  |
| 201-250        | 8         | 14.04%  |
| 81-90          | 7         | 12.28%  |
| 51-60          | 4         | 7.02%   |
| 251-300        | 4         | 7.02%   |
| 141-150        | 3         | 5.26%   |
| 61-70          | 2         | 3.51%   |
| 41-50          | 2         | 3.51%   |
| 151-200        | 2         | 3.51%   |
| 501-1000       | 2         | 3.51%   |
| 71-80          | 1         | 1.75%   |
| 351-500        | 1         | 1.75%   |
| 301-350        | 1         | 1.75%   |
| 121-130        | 1         | 1.75%   |
| Unknown        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 21        | 36.84%  |
| 51-100  | 21        | 36.84%  |
| 121-160 | 10        | 17.54%  |
| 161-240 | 3         | 5.26%   |
| 1-50    | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 87.14%  |
| 0     | 5         | 7.14%   |
| 2     | 3         | 4.29%   |
| 3     | 1         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 44        | 39.29%  |
| Intel                            | 21        | 18.75%  |
| Qualcomm Atheros                 | 17        | 15.18%  |
| Broadcom                         | 6         | 5.36%   |
| Silicon Integrated Systems [SiS] | 4         | 3.57%   |
| Marvell Technology Group         | 4         | 3.57%   |
| Broadcom Limited                 | 3         | 2.68%   |
| Samsung Electronics              | 2         | 1.79%   |
| Ralink Technology                | 2         | 1.79%   |
| Xiaomi                           | 1         | 0.89%   |
| Ralink                           | 1         | 0.89%   |
| Motorola PCS                     | 1         | 0.89%   |
| LG Electronics                   | 1         | 0.89%   |
| JMicron Technology               | 1         | 0.89%   |
| IBM                              | 1         | 0.89%   |
| Guillemot                        | 1         | 0.89%   |
| D-Link System                    | 1         | 0.89%   |
| Accton Technology                | 1         | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 19        | 15.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 8.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.44%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 2.44%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 1.63%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.63%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.63%   |
| Intel Wireless 7265                                                     | 2         | 1.63%   |
| Intel Wireless 3165                                                     | 2         | 1.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.81%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.81%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.81%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 31.48%  |
| Qualcomm Atheros      | 16        | 29.63%  |
| Realtek Semiconductor | 11        | 20.37%  |
| Broadcom              | 3         | 5.56%   |
| Ralink Technology     | 2         | 3.7%    |
| Broadcom Limited      | 2         | 3.7%    |
| Ralink                | 1         | 1.85%   |
| Guillemot             | 1         | 1.85%   |
| D-Link System         | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 7.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 7.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 3         | 5.56%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 5.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 5.56%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 3.7%    |
| Intel Wireless 7265                                                         | 2         | 3.7%    |
| Intel Wireless 3165                                                         | 2         | 3.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 1.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.85%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 1.85%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.85%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 1.85%   |
| Intel WiFi Link 5100                                                        | 1         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.85%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 1.85%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 1.85%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 1.85%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 60.32%  |
| Intel                            | 5         | 7.94%   |
| Marvell Technology Group         | 4         | 6.35%   |
| Silicon Integrated Systems [SiS] | 3         | 4.76%   |
| Broadcom                         | 3         | 4.76%   |
| Samsung Electronics              | 2         | 3.17%   |
| Qualcomm Atheros                 | 2         | 3.17%   |
| Xiaomi                           | 1         | 1.59%   |
| Motorola PCS                     | 1         | 1.59%   |
| LG Electronics                   | 1         | 1.59%   |
| JMicron Technology               | 1         | 1.59%   |
| Broadcom Limited                 | 1         | 1.59%   |
| Accton Technology                | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 30.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 17.46%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 4.76%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2         | 3.17%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 3.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.17%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.59%   |
| Motorola PCS motorola one macro                                   | 1         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 1.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.59%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.59%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 1.59%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.59%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.59%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.59%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.59%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 51.26%  |
| WiFi     | 52        | 43.7%   |
| Modem    | 5         | 4.2%    |
| Unknown  | 1         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 53.73%  |
| Ethernet | 31        | 46.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 52.86%  |
| 1     | 26        | 37.14%  |
| 0     | 5         | 7.14%   |
| 3     | 2         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 84.29%  |
| Yes  | 11        | 15.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 34.62%  |
| Qualcomm Atheros Communications | 6         | 23.08%  |
| Realtek Semiconductor           | 4         | 15.38%  |
| Alps Electric                   | 2         | 7.69%   |
| Toshiba                         | 1         | 3.85%   |
| Hewlett-Packard                 | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |
| Apple                           | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 15.38%  |
| Intel Bluetooth wireless interface                  | 4         | 15.38%  |
| Realtek Bluetooth Radio                             | 3         | 11.54%  |
| Intel AX200 Bluetooth                               | 3         | 11.54%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 7.69%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 7.69%   |
| Toshiba Askey for                                   | 1         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.85%   |
| Intel AX210 Bluetooth                               | 1         | 3.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 3.85%   |
| Apple Bluetooth HCI                                 | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 59.46%  |
| AMD                              | 16        | 21.62%  |
| Nvidia                           | 6         | 8.11%   |
| Silicon Integrated Systems [SiS] | 4         | 5.41%   |
| VIA Technologies                 | 1         | 1.35%   |
| Shenzhen Rapoo Technology        | 1         | 1.35%   |
| Logitech                         | 1         | 1.35%   |
| ESS Technology                   | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 8.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 6.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 4.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.6%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.45%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 3.45%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.3%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.15%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.15%   |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.15%   |
| Nvidia Audio device                                                                               | 1         | 1.15%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.15%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.15%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 27        | 35.06%  |
| Samsung Electronics | 13        | 16.88%  |
| SK hynix            | 8         | 10.39%  |
| Kingston            | 7         | 9.09%   |
| Elpida              | 3         | 3.9%    |
| Unknown (ABCD)      | 2         | 2.6%    |
| Team                | 2         | 2.6%    |
| Micron Technology   | 2         | 2.6%    |
| Crucial             | 2         | 2.6%    |
| A-DATA Technology   | 2         | 2.6%    |
| Unknown             | 2         | 2.6%    |
| Transcend           | 1         | 1.3%    |
| Toshiba             | 1         | 1.3%    |
| Teikon              | 1         | 1.3%    |
| S                   | 1         | 1.3%    |
| Ramaxel Technology  | 1         | 1.3%    |
| M                   | 1         | 1.3%    |
| G.Skill             | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 7.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.7%    |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 2.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.47%   |
| Unknown                                                          | 2         | 2.47%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.23%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.23%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.23%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.23%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.23%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.23%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.23%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.23%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.23%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.23%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.23%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.23%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1.23%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.23%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.23%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.23%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s           | 1         | 1.23%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.23%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.23%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.23%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.23%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.23%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1         | 1.23%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 31.43%  |
| DDR4    | 13        | 18.57%  |
| DDR2    | 13        | 18.57%  |
| SDRAM   | 8         | 11.43%  |
| DDR     | 5         | 7.14%   |
| Unknown | 3         | 4.29%   |
| LPDDR4  | 2         | 2.86%   |
| LPDDR3  | 2         | 2.86%   |
| DRAM    | 2         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 68.12%  |
| DIMM         | 19        | 27.54%  |
| Unknown      | 2         | 2.9%    |
| Row Of Chips | 1         | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 24        | 32%     |
| 4096  | 17        | 22.67%  |
| 1024  | 12        | 16%     |
| 8192  | 11        | 14.67%  |
| 512   | 5         | 6.67%   |
| 16384 | 3         | 4%      |
| 32768 | 2         | 2.67%   |
| 256   | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 15        | 20.83%  |
| 1600    | 9         | 12.5%   |
| 1333    | 7         | 9.72%   |
| 2667    | 6         | 8.33%   |
| 1334    | 5         | 6.94%   |
| 2400    | 4         | 5.56%   |
| 3200    | 3         | 4.17%   |
| 1067    | 3         | 4.17%   |
| 266     | 3         | 4.17%   |
| 3600    | 2         | 2.78%   |
| 1867    | 2         | 2.78%   |
| 1066    | 2         | 2.78%   |
| 800     | 2         | 2.78%   |
| 667     | 2         | 2.78%   |
| 533     | 2         | 2.78%   |
| 4199    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 2666    | 1         | 1.39%   |
| 2048    | 1         | 1.39%   |
| 400     | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon MF4100 series    | 1         | 50%     |
| Brother HL-1110 series | 1         | 50%     |

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
| IMC Networks                           | 4         | 13.33%  |
| Chicony Electronics                    | 4         | 13.33%  |
| Microdia                               | 3         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10%     |
| Ricoh                                  | 2         | 6.67%   |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Acer                                   | 2         | 6.67%   |
| Suyin                                  | 1         | 3.33%   |
| Silicon Motion                         | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Luxvisions Innotech Limited            | 1         | 3.33%   |
| Logitech                               | 1         | 3.33%   |
| KYE Systems (Mouse Systems)            | 1         | 3.33%   |
| Bison Electronics                      | 1         | 3.33%   |
| Apple                                  | 1         | 3.33%   |
| ALi                                    | 1         | 3.33%   |
| Alcor Micro                            | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 6.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.33%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.33%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.33%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.33%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.33%   |
| Realtek HP Wide Vision HD Camera                            | 1         | 3.33%   |
| Quanta Chromebook HD Camera                                 | 1         | 3.33%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.33%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.33%   |
| Logitech HD Webcam C525                                     | 1         | 3.33%   |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.33%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.33%   |
| IMC Networks Integrated Camera                              | 1         | 3.33%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.33%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.33%   |
| Chicony Integrated Camera                                   | 1         | 3.33%   |
| Chicony HP Webcam                                           | 1         | 3.33%   |
| Chicony HP HD Webcam                                        | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 3.33%   |
| Bison EasyCamera                                            | 1         | 3.33%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 3.33%   |
| ALi M5603 Video Camera Controller                           | 1         | 3.33%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 3.33%   |
| Acer Integrated Camera                                      | 1         | 3.33%   |
| Acer HP Webcam-101                                          | 1         | 3.33%   |

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
| 0     | 54        | 77.14%  |
| 1     | 9         | 12.86%  |
| 2     | 6         | 8.57%   |
| 4     | 1         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 48%     |
| Fingerprint reader       | 4         | 16%     |
| Flash memory             | 2         | 8%      |
| Communication controller | 2         | 8%      |
| Chipcard                 | 2         | 8%      |
| Network                  | 1         | 4%      |
| Net/wireless             | 1         | 4%      |
| Camera                   | 1         | 4%      |

