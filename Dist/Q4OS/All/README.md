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

Total: 90

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [db6f924b29](https://linux-hardware.org/?probe=db6f924b29) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6df3bded78](https://linux-hardware.org/?probe=6df3bded78) | Nov 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Q4OS 4    | 42        | 56.76%  |
| Q4OS 3    | 16        | 21.62%  |
| Q4OS 5    | 10        | 13.51%  |
| Q4OS 2    | 5         | 6.76%   |
| Q4OS 4.11 | 1         | 1.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 74        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-21-amd64      | 6         | 8%      |
| 5.10.0-23-amd64      | 4         | 5.33%   |
| 5.10.0-19-amd64      | 4         | 5.33%   |
| 4.19.0-17-amd64      | 4         | 5.33%   |
| 6.1.0-13-amd64       | 3         | 4%      |
| 5.10.0-21-686-pae    | 3         | 4%      |
| 5.10.0-12-amd64      | 3         | 4%      |
| 5.10.0-8-amd64       | 2         | 2.67%   |
| 5.10.0-14-686-pae    | 2         | 2.67%   |
| 5.10.0-10-686-pae    | 2         | 2.67%   |
| 6.5.1-060501-generic | 1         | 1.33%   |
| 6.5.0-4-amd64        | 1         | 1.33%   |
| 6.1.0-12-amd64       | 1         | 1.33%   |
| 6.1.0-12-686-pae     | 1         | 1.33%   |
| 6.1.0-11-686-pae     | 1         | 1.33%   |
| 6.1.0-10-amd64       | 1         | 1.33%   |
| 6.1.0-10-686-pae     | 1         | 1.33%   |
| 6.0.0-1-amd64        | 1         | 1.33%   |
| 5.9.0-5-amd64        | 1         | 1.33%   |
| 5.6.0-1-amd64        | 1         | 1.33%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.33%   |
| 5.10.0-9-amd64       | 1         | 1.33%   |
| 5.10.0-9-686-pae     | 1         | 1.33%   |
| 5.10.0-8-686-pae     | 1         | 1.33%   |
| 5.10.0-25-amd64      | 1         | 1.33%   |
| 5.10.0-23-686-pae    | 1         | 1.33%   |
| 5.10.0-20-amd64      | 1         | 1.33%   |
| 5.10.0-20-686-pae    | 1         | 1.33%   |
| 5.10.0-20-686        | 1         | 1.33%   |
| 5.10.0-17-amd64      | 1         | 1.33%   |
| 5.10.0-15-686-pae    | 1         | 1.33%   |
| 5.10.0-14-amd64      | 1         | 1.33%   |
| 5.10.0-13-amd64      | 1         | 1.33%   |
| 5.10.0-12-686-pae    | 1         | 1.33%   |
| 5.10.0-11-686-pae    | 1         | 1.33%   |
| 4.9.0-9-686-pae      | 1         | 1.33%   |
| 4.9.0-8-amd64        | 1         | 1.33%   |
| 4.9.0-14-686-pae     | 1         | 1.33%   |
| 4.9.0-12-686-pae     | 1         | 1.33%   |
| 4.19.0-6-amd64       | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 39        | 52.7%   |
| 4.19.0  | 17        | 22.97%  |
| 6.1.0   | 8         | 10.81%  |
| 4.9.0   | 4         | 5.41%   |
| 6.5.1   | 1         | 1.35%   |
| 6.5.0   | 1         | 1.35%   |
| 6.0.0   | 1         | 1.35%   |
| 5.9.0   | 1         | 1.35%   |
| 5.6.0   | 1         | 1.35%   |
| 5.18.0  | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 39        | 52.7%   |
| 4.19    | 17        | 22.97%  |
| 6.1     | 8         | 10.81%  |
| 4.9     | 4         | 5.41%   |
| 6.5     | 2         | 2.7%    |
| 6.0     | 1         | 1.35%   |
| 5.9     | 1         | 1.35%   |
| 5.6     | 1         | 1.35%   |
| 5.18    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 66.22%  |
| i686   | 25        | 33.78%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 37        | 49.33%  |
| KDE5     | 33        | 44%     |
| KDE      | 2         | 2.67%   |
| LXDE     | 1         | 1.33%   |
| Cinnamon | 1         | 1.33%   |
| Budgie   | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 73        | 98.65%  |
| Tty  | 1         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 37        | 50%     |
| SDDM    | 36        | 48.65%  |
| LightDM | 1         | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 26        | 35.14%  |
| de_DE   | 9         | 12.16%  |
| it_IT   | 8         | 10.81%  |
| en_GB   | 5         | 6.76%   |
| es_ES   | 4         | 5.41%   |
| hu_HU   | 3         | 4.05%   |
| Unknown | 3         | 4.05%   |
| fr_FR   | 2         | 2.7%    |
| sv_SE   | 1         | 1.35%   |
| sl_SI   | 1         | 1.35%   |
| sk_SK   | 1         | 1.35%   |
| ru_RU   | 1         | 1.35%   |
| pt_BR   | 1         | 1.35%   |
| pl_PL   | 1         | 1.35%   |
| es_VE   | 1         | 1.35%   |
| es_PE   | 1         | 1.35%   |
| es_AR   | 1         | 1.35%   |
| en_ZA   | 1         | 1.35%   |
| en_SG   | 1         | 1.35%   |
| en_IE   | 1         | 1.35%   |
| C       | 1         | 1.35%   |
| bg_BG   | 1         | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 45        | 60.81%  |
| EFI  | 29        | 39.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 71        | 95.95%  |
| Overlay | 3         | 4.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 40        | 54.05%  |
| GPT     | 33        | 44.59%  |
| Unknown | 1         | 1.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 87.84%  |
| Yes       | 9         | 12.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 66.22%  |
| Yes       | 25        | 33.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 11        | 14.86%  |
| ASUSTek Computer            | 6         | 8.11%   |
| MSI                         | 5         | 6.76%   |
| Lenovo                      | 5         | 6.76%   |
| Toshiba                     | 4         | 5.41%   |
| Gigabyte Technology         | 4         | 5.41%   |
| ASRock                      | 4         | 5.41%   |
| Acer                        | 4         | 5.41%   |
| Apple                       | 3         | 4.05%   |
| TrekStor                    | 2         | 2.7%    |
| Sony                        | 2         | 2.7%    |
| Medion                      | 2         | 2.7%    |
| Intel                       | 2         | 2.7%    |
| Google                      | 2         | 2.7%    |
| Dell                        | 2         | 2.7%    |
| VXL                         | 1         | 1.35%   |
| Visual Land                 | 1         | 1.35%   |
| TECO Electric and Machinery | 1         | 1.35%   |
| Qilive                      | 1         | 1.35%   |
| Phoenix/SiS                 | 1         | 1.35%   |
| Philco                      | 1         | 1.35%   |
| Packard Bell                | 1         | 1.35%   |
| JVC                         | 1         | 1.35%   |
| IBM                         | 1         | 1.35%   |
| Fujitsu Siemens             | 1         | 1.35%   |
| Framework                   | 1         | 1.35%   |
| Foxconn                     | 1         | 1.35%   |
| Compaq                      | 1         | 1.35%   |
| Chuwi                       | 1         | 1.35%   |
| BESSTAR Tech                | 1         | 1.35%   |
| AMI                         | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 2.7%    |
| Toshiba Satellite C660                 | 2         | 2.7%    |
| VXL TC7500D Series                     | 1         | 1.35%   |
| Visual Land Premier 10                 | 1         | 1.35%   |
| Toshiba Satellite Pro L500             | 1         | 1.35%   |
| Toshiba Satellite M70                  | 1         | 1.35%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 1.35%   |
| Sony VGN-P11Z_Q                        | 1         | 1.35%   |
| Sony VGN-FW21Z                         | 1         | 1.35%   |
| Qilive QW19141AMSP                     | 1         | 1.35%   |
| Phoenix/SiS M720SR                     | 1         | 1.35%   |
| Philco 14I                             | 1         | 1.35%   |
| Packard Bell EasyNote LM81             | 1         | 1.35%   |
| MSI U90/U100                           | 1         | 1.35%   |
| MSI U210                               | 1         | 1.35%   |
| MSI MS-7C56                            | 1         | 1.35%   |
| MSI MS-7597                            | 1         | 1.35%   |
| MSI MS-7592                            | 1         | 1.35%   |
| Medion P6620                           | 1         | 1.35%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 1.35%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 1.35%   |
| Lenovo IdeaPad 5 14IAL7 82SD           | 1         | 1.35%   |
| Lenovo IdeaPad 330S-14IKB 81F4         | 1         | 1.35%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 1.35%   |
| JVC J3N                                | 1         | 1.35%   |
| Intel NUC5CPYB H61145-407              | 1         | 1.35%   |
| Intel D845GRG AAA84341-206             | 1         | 1.35%   |
| IBM ThinkPad T42 2378FVU               | 1         | 1.35%   |
| HP ProBook 6550b                       | 1         | 1.35%   |
| HP ProBook 650 G1                      | 1         | 1.35%   |
| HP ProBook 450 G2                      | 1         | 1.35%   |
| HP Presario CQ56                       | 1         | 1.35%   |
| HP Pavilion x360 Convertible 11m-ad1xx | 1         | 1.35%   |
| HP OmniBook PC                         | 1         | 1.35%   |
| HP Laptop 15s-fq2xxx                   | 1         | 1.35%   |
| HP ENVY x360 Convertible 13-ay0xxx     | 1         | 1.35%   |
| HP Compaq Pro 6305 SFF                 | 1         | 1.35%   |
| HP 250 G5 Notebook PC                  | 1         | 1.35%   |
| HP 2000                                | 1         | 1.35%   |
| Google Reks                            | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 5.41%   |
| Lenovo IdeaPad                    | 3         | 4.05%   |
| HP ProBook                        | 3         | 4.05%   |
| TrekStor SurfTab                  | 2         | 2.7%    |
| Lenovo ThinkPad                   | 2         | 2.7%    |
| Dell Latitude                     | 2         | 2.7%    |
| Acer Aspire                       | 2         | 2.7%    |
| VXL TC7500D                       | 1         | 1.35%   |
| Visual Land Premier               | 1         | 1.35%   |
| TECO Electric and Machinery FUTRO | 1         | 1.35%   |
| Sony VGN-P11Z                     | 1         | 1.35%   |
| Sony VGN-FW21Z                    | 1         | 1.35%   |
| Qilive QW19141AMSP                | 1         | 1.35%   |
| Phoenix/SiS M720SR                | 1         | 1.35%   |
| Philco 14I                        | 1         | 1.35%   |
| Packard Bell EasyNote             | 1         | 1.35%   |
| MSI U90                           | 1         | 1.35%   |
| MSI U210                          | 1         | 1.35%   |
| MSI MS-7C56                       | 1         | 1.35%   |
| MSI MS-7597                       | 1         | 1.35%   |
| MSI MS-7592                       | 1         | 1.35%   |
| Medion P6620                      | 1         | 1.35%   |
| JVC J3N                           | 1         | 1.35%   |
| Intel NUC5CPYB                    | 1         | 1.35%   |
| Intel D845GRG                     | 1         | 1.35%   |
| IBM ThinkPad                      | 1         | 1.35%   |
| HP Presario                       | 1         | 1.35%   |
| HP Pavilion                       | 1         | 1.35%   |
| HP OmniBook                       | 1         | 1.35%   |
| HP Laptop                         | 1         | 1.35%   |
| HP ENVY                           | 1         | 1.35%   |
| HP Compaq                         | 1         | 1.35%   |
| HP 250                            | 1         | 1.35%   |
| HP 2000                           | 1         | 1.35%   |
| Google Reks                       | 1         | 1.35%   |
| Google Cave                       | 1         | 1.35%   |
| Gigabyte Z690                     | 1         | 1.35%   |
| Gigabyte XP-M5S661GX              | 1         | 1.35%   |
| Gigabyte H55M-USB3                | 1         | 1.35%   |
| Gigabyte AB350-Gaming             | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 8         | 10.81%  |
| 2010    | 7         | 9.46%   |
| 2011    | 6         | 8.11%   |
| 2020    | 5         | 6.76%   |
| 2016    | 5         | 6.76%   |
| 2018    | 4         | 5.41%   |
| 2015    | 4         | 5.41%   |
| 2012    | 4         | 5.41%   |
| 2008    | 4         | 5.41%   |
| 2005    | 3         | 4.05%   |
| 2023    | 2         | 2.7%    |
| 2022    | 2         | 2.7%    |
| 2019    | 2         | 2.7%    |
| 2017    | 2         | 2.7%    |
| 2014    | 2         | 2.7%    |
| 2013    | 2         | 2.7%    |
| 2007    | 2         | 2.7%    |
| 2006    | 2         | 2.7%    |
| 2004    | 2         | 2.7%    |
| 2002    | 2         | 2.7%    |
| Unknown | 2         | 2.7%    |
| 2021    | 1         | 1.35%   |
| 2003    | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 47        | 63.51%  |
| Desktop     | 19        | 25.68%  |
| Tablet      | 3         | 4.05%   |
| Convertible | 2         | 2.7%    |
| Mini pc     | 2         | 2.7%    |
| All in one  | 1         | 1.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 71        | 95.95%  |
| Enabled  | 3         | 4.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 97.3%   |
| Yes  | 2         | 2.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 21        | 28.38%  |
| 2.01-3.0    | 12        | 16.22%  |
| 4.01-8.0    | 11        | 14.86%  |
| 1.01-2.0    | 8         | 10.81%  |
| 0.51-1.0    | 6         | 8.11%   |
| 8.01-16.0   | 5         | 6.76%   |
| 16.01-24.0  | 4         | 5.41%   |
| 0.01-0.5    | 3         | 4.05%   |
| 64.01-256.0 | 2         | 2.7%    |
| 32.01-64.0  | 1         | 1.35%   |
| 24.01-32.0  | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 26        | 34.21%  |
| 0.51-1.0  | 18        | 23.68%  |
| 2.01-3.0  | 14        | 18.42%  |
| 0.01-0.5  | 8         | 10.53%  |
| 4.01-8.0  | 5         | 6.58%   |
| 3.01-4.0  | 4         | 5.26%   |
| 8.01-16.0 | 1         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 72%     |
| 2      | 15        | 20%     |
| 3      | 6         | 8%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 52%     |
| Yes       | 36        | 48%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 82.43%  |
| No        | 13        | 17.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 75.68%  |
| No        | 18        | 24.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 60.81%  |
| Yes       | 29        | 39.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 13.51%  |
| Italy        | 9         | 12.16%  |
| Germany      | 8         | 10.81%  |
| UK           | 5         | 6.76%   |
| Spain        | 3         | 4.05%   |
| Kenya        | 3         | 4.05%   |
| Hungary      | 3         | 4.05%   |
| Venezuela    | 2         | 2.7%    |
| Turkey       | 2         | 2.7%    |
| Switzerland  | 2         | 2.7%    |
| Romania      | 2         | 2.7%    |
| Poland       | 2         | 2.7%    |
| Netherlands  | 2         | 2.7%    |
| Mexico       | 2         | 2.7%    |
| France       | 2         | 2.7%    |
| Brazil       | 2         | 2.7%    |
| Sweden       | 1         | 1.35%   |
| South Africa | 1         | 1.35%   |
| Slovenia     | 1         | 1.35%   |
| Slovakia     | 1         | 1.35%   |
| Singapore    | 1         | 1.35%   |
| Saudi Arabia | 1         | 1.35%   |
| Russia       | 1         | 1.35%   |
| Qatar        | 1         | 1.35%   |
| Peru         | 1         | 1.35%   |
| Croatia      | 1         | 1.35%   |
| Canada       | 1         | 1.35%   |
| Bulgaria     | 1         | 1.35%   |
| Belgium      | 1         | 1.35%   |
| Belarus      | 1         | 1.35%   |
| Argentina    | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 4.05%   |
| Zurich                | 2         | 2.7%    |
| Swindon               | 2         | 2.7%    |
| Rostock               | 2         | 2.7%    |
| Morelia               | 2         | 2.7%    |
| Mesa                  | 2         | 2.7%    |
| Drobeta-Turnu Severin | 2         | 2.7%    |
| Budapest              | 2         | 2.7%    |
| Bologna               | 2         | 2.7%    |
| West Corinth          | 1         | 1.35%   |
| Toalmas               | 1         | 1.35%   |
| The Hague             | 1         | 1.35%   |
| Tenbury Wells         | 1         | 1.35%   |
| Tellico Plains        | 1         | 1.35%   |
| Sosnowiec             | 1         | 1.35%   |
| Solingen              | 1         | 1.35%   |
| Sofia                 | 1         | 1.35%   |
| Singapore             | 1         | 1.35%   |
| Schermbeck            | 1         | 1.35%   |
| Savona                | 1         | 1.35%   |
| San Carlos del Zulia  | 1         | 1.35%   |
| Salsomaggiore Terme   | 1         | 1.35%   |
| Rome                  | 1         | 1.35%   |
| Rijeka                | 1         | 1.35%   |
| Puerto Cumarebo       | 1         | 1.35%   |
| Posadas               | 1         | 1.35%   |
| Osnabrück            | 1         | 1.35%   |
| Moscow                | 1         | 1.35%   |
| Mooresville           | 1         | 1.35%   |
| Moirans               | 1         | 1.35%   |
| Mogilev               | 1         | 1.35%   |
| Milano                | 1         | 1.35%   |
| Mannheim              | 1         | 1.35%   |
| Londrina              | 1         | 1.35%   |
| Ljubljana             | 1         | 1.35%   |
| Little Current        | 1         | 1.35%   |
| Lima                  | 1         | 1.35%   |
| Leipzig               | 1         | 1.35%   |
| Las Vegas             | 1         | 1.35%   |
| Klaudyn               | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 14.61%  |
| Seagate             | 12        | 14     | 13.48%  |
| Samsung Electronics | 9         | 10     | 10.11%  |
| Unknown             | 8         | 8      | 8.99%   |
| SanDisk             | 8         | 10     | 8.99%   |
| Kingston            | 7         | 7      | 7.87%   |
| Toshiba             | 3         | 3      | 3.37%   |
| Hitachi             | 3         | 3      | 3.37%   |
| China               | 3         | 4      | 3.37%   |
| KESU                | 2         | 2      | 2.25%   |
| HGST                | 2         | 2      | 2.25%   |
| Fujitsu             | 2         | 2      | 2.25%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| Unknown             | 2         | 2      | 2.25%   |
| USB3.0              | 1         | 1      | 1.12%   |
| Unknown (CF)        | 1         | 1      | 1.12%   |
| Transcend           | 1         | 1      | 1.12%   |
| SPCC                | 1         | 1      | 1.12%   |
| Silicon Motion      | 1         | 1      | 1.12%   |
| Phison              | 1         | 1      | 1.12%   |
| Maxtor              | 1         | 1      | 1.12%   |
| KIOXIA              | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| KBG40ZNV            | 1         | 1      | 1.12%   |
| IBM/Hitachi         | 1         | 2      | 1.12%   |
| Crucial             | 1         | 2      | 1.12%   |
| Apple               | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 2.13%   |
| SanDisk SDSSDA120G 120GB             | 2         | 2.13%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.13%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.13%   |
| KESU USB 3.1 256GB                   | 2         | 2.13%   |
| Unknown                              | 2         | 2.13%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.06%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.06%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.06%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.06%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.06%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.06%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.06%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.06%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1.06%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.06%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.06%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.06%   |
| USB3.0 Super Speed 500GB             | 1         | 1.06%   |
| Unknown USDU1  32GB                  | 1         | 1.06%   |
| Unknown SLD64G  64GB                 | 1         | 1.06%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.06%   |
| Unknown MMC Card  64GB               | 1         | 1.06%   |
| Unknown HAG2e  16GB                  | 1         | 1.06%   |
| Unknown 064G38  64GB                 | 1         | 1.06%   |
| Unknown (CF) Card 32GB               | 1         | 1.06%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 1.06%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.06%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.06%   |
| Toshiba MK3252GSX 320GB              | 1         | 1.06%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.06%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.06%   |
| Seagate ST96812AS 64GB               | 1         | 1.06%   |
| Seagate ST9500325AS 500GB            | 1         | 1.06%   |
| Seagate ST9120822AS 120GB            | 1         | 1.06%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.06%   |
| Seagate ST380012A 80GB               | 1         | 1.06%   |
| Seagate ST3500413AS 500GB            | 1         | 1.06%   |
| Seagate ST3320820SCE 320GB           | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 27.78%  |
| Seagate             | 10        | 12     | 27.78%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| HGST                | 2         | 2      | 5.56%   |
| Fujitsu             | 2         | 2      | 5.56%   |
| USB3.0              | 1         | 1      | 2.78%   |
| Unknown             | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Maxtor              | 1         | 1      | 2.78%   |
| IBM/Hitachi         | 1         | 2      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 32        | 39     | 38.55%  |
| SSD     | 27        | 31     | 32.53%  |
| MMC     | 10        | 10     | 12.05%  |
| NVMe    | 10        | 13     | 12.05%  |
| Unknown | 4         | 4      | 4.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 68     | 67.47%  |
| NVMe | 10        | 12     | 12.05%  |
| MMC  | 10        | 10     | 12.05%  |
| SAS  | 7         | 7      | 8.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 62     | 86.21%  |
| 0.51-1.0   | 6         | 6      | 10.34%  |
| 1.01-2.0   | 1         | 1      | 1.72%   |
| 4.01-10.0  | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 22.67%  |
| 251-500        | 13        | 17.33%  |
| 51-100         | 13        | 17.33%  |
| 1-20           | 11        | 14.67%  |
| 21-50          | 8         | 10.67%  |
| 501-1000       | 6         | 8%      |
| 1001-2000      | 4         | 5.33%   |
| More than 3000 | 2         | 2.67%   |
| Unknown        | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 66.67%  |
| 21-50          | 11        | 14.67%  |
| 51-100         | 4         | 5.33%   |
| 251-500        | 3         | 4%      |
| 101-250        | 3         | 4%      |
| 501-1000       | 2         | 2.67%   |
| More than 3000 | 1         | 1.33%   |
| Unknown        | 1         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 47        | 60     | 58.75%  |
| Detected | 17        | 18     | 21.25%  |
| Malfunc  | 16        | 19     | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 59.21%  |
| AMD                              | 11        | 14.47%  |
| Silicon Integrated Systems [SiS] | 5         | 6.58%   |
| SanDisk                          | 3         | 3.95%   |
| Samsung Electronics              | 3         | 3.95%   |
| VIA Technologies                 | 1         | 1.32%   |
| Silicon Motion                   | 1         | 1.32%   |
| Phison Electronics               | 1         | 1.32%   |
| Nvidia                           | 1         | 1.32%   |
| Micron/Crucial Technology        | 1         | 1.32%   |
| KIOXIA                           | 1         | 1.32%   |
| JMicron Technology               | 1         | 1.32%   |
| ASMedia Technology               | 1         | 1.32%   |
| ADATA Technology                 | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.79%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 5         | 5.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 5.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 4.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 4.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 3.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 3.3%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.2%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.2%    |
| Intel 82801DB (ICH4) IDE Controller                                              | 2         | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.2%    |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.1%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.1%    |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.1%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.1%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.1%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 1.1%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.1%    |
| Phison E12 NVMe Controller                                                       | 1         | 1.1%    |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.1%    |
| Nvidia MCP61 IDE                                                                 | 1         | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 52.5%   |
| IDE  | 26        | 32.5%   |
| NVMe | 9         | 11.25%  |
| RAID | 3         | 3.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 56        | 75.68%  |
| AMD          | 17        | 22.97%  |
| CentaurHauls | 1         | 1.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz             | 3         | 4.05%   |
| Intel Atom CPU N270 @ 1.60GHz               | 3         | 4.05%   |
| Intel Pentium M processor 1.70GHz           | 2         | 2.7%    |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 2.7%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 2.7%    |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.35%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.35%   |
| Intel Pentium III (Coppermine)              | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.35%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.35%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.35%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.35%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.35%   |
| Intel Pentium 4 CPU 1.80GHz                 | 1         | 1.35%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.35%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.35%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.35%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.35%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.35%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.35%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.35%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.35%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.35%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 10        | 13.51%  |
| Intel Celeron           | 8         | 10.81%  |
| Intel Core 2 Duo        | 7         | 9.46%   |
| Intel Core i5           | 6         | 8.11%   |
| Intel Pentium 4         | 4         | 5.41%   |
| Intel Core i3           | 4         | 5.41%   |
| Other                   | 3         | 4.05%   |
| Intel Pentium M         | 3         | 4.05%   |
| Intel Pentium Dual-Core | 3         | 4.05%   |
| AMD Ryzen 7             | 3         | 4.05%   |
| Intel Core i7           | 2         | 2.7%    |
| AMD Athlon              | 2         | 2.7%    |
| AMD A4                  | 2         | 2.7%    |
| Intel Pentium Silver    | 1         | 1.35%   |
| Intel Pentium III       | 1         | 1.35%   |
| Intel Pentium           | 1         | 1.35%   |
| Intel Genuine           | 1         | 1.35%   |
| Intel Core m3           | 1         | 1.35%   |
| Intel Core 2            | 1         | 1.35%   |
| CentaurHauls VIA Eden   | 1         | 1.35%   |
| AMD V120                | 1         | 1.35%   |
| AMD Ryzen 7 PRO         | 1         | 1.35%   |
| AMD Ryzen 5 PRO         | 1         | 1.35%   |
| AMD Ryzen 5             | 1         | 1.35%   |
| AMD Mobile Sempron      | 1         | 1.35%   |
| AMD E                   | 1         | 1.35%   |
| AMD C-70                | 1         | 1.35%   |
| AMD Athlon Neo          | 1         | 1.35%   |
| AMD Athlon II X2        | 1         | 1.35%   |
| AMD A8                  | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 33        | 44.59%  |
| 1      | 18        | 24.32%  |
| 4      | 17        | 22.97%  |
| 8      | 3         | 4.05%   |
| 16     | 1         | 1.35%   |
| 12     | 1         | 1.35%   |
| 6      | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 62.16%  |
| 2      | 28        | 37.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 79.73%  |
| 32-bit         | 15        | 20.27%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 12.16%  |
| 0x206a7    | 5         | 6.76%   |
| 0x1067a    | 5         | 6.76%   |
| 0x30678    | 4         | 5.41%   |
| 0x106c2    | 4         | 5.41%   |
| 0x706a1    | 3         | 4.05%   |
| 0xf27      | 2         | 2.7%    |
| 0x6fd      | 2         | 2.7%    |
| 0x406c4    | 2         | 2.7%    |
| 0x406c3    | 2         | 2.7%    |
| 0x40651    | 2         | 2.7%    |
| 0x10676    | 2         | 2.7%    |
| 0x0810100b | 2         | 2.7%    |
| 0x010000c8 | 2         | 2.7%    |
| 0xf49      | 1         | 1.35%   |
| 0xf12      | 1         | 1.35%   |
| 0xb0671    | 1         | 1.35%   |
| 0x906a3    | 1         | 1.35%   |
| 0x806e9    | 1         | 1.35%   |
| 0x806c1    | 1         | 1.35%   |
| 0x706a8    | 1         | 1.35%   |
| 0x6fb      | 1         | 1.35%   |
| 0x6f6      | 1         | 1.35%   |
| 0x6e8      | 1         | 1.35%   |
| 0x6d8      | 1         | 1.35%   |
| 0x6d6      | 1         | 1.35%   |
| 0x695      | 1         | 1.35%   |
| 0x68a      | 1         | 1.35%   |
| 0x406e3    | 1         | 1.35%   |
| 0x306c3    | 1         | 1.35%   |
| 0x306a9    | 1         | 1.35%   |
| 0x20655    | 1         | 1.35%   |
| 0x0a704103 | 1         | 1.35%   |
| 0x08701013 | 1         | 1.35%   |
| 0x08600106 | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x0800820d | 1         | 1.35%   |
| 0x07030106 | 1         | 1.35%   |
| 0x06006705 | 1         | 1.35%   |
| 0x0600111f | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 9         | 12.16%  |
| Penryn           | 7         | 9.46%   |
| SandyBridge      | 6         | 8.11%   |
| P6               | 5         | 6.76%   |
| Bonnell          | 5         | 6.76%   |
| NetBurst         | 4         | 5.41%   |
| Goldmont plus    | 4         | 5.41%   |
| Core             | 4         | 5.41%   |
| Haswell          | 3         | 4.05%   |
| Unknown          | 3         | 4.05%   |
| Zen+             | 2         | 2.7%    |
| Zen 2            | 2         | 2.7%    |
| Zen              | 2         | 2.7%    |
| K8 Hammer        | 2         | 2.7%    |
| K10              | 2         | 2.7%    |
| Bobcat           | 2         | 2.7%    |
| Westmere         | 1         | 1.35%   |
| TigerLake        | 1         | 1.35%   |
| Skylake          | 1         | 1.35%   |
| Puma             | 1         | 1.35%   |
| Piledriver       | 1         | 1.35%   |
| Nehalem          | 1         | 1.35%   |
| KabyLake         | 1         | 1.35%   |
| K6               | 1         | 1.35%   |
| IvyBridge        | 1         | 1.35%   |
| Goldmont         | 1         | 1.35%   |
| Excavator        | 1         | 1.35%   |
| Alderlake Hybrid | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 56.41%  |
| AMD                              | 18        | 23.08%  |
| Nvidia                           | 9         | 11.54%  |
| Silicon Integrated Systems [SiS] | 5         | 6.41%   |
| VIA Technologies                 | 1         | 1.28%   |
| S3 Graphics                      | 1         | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 5         | 5.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 4         | 4.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 4.71%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 3.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 3         | 3.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 3         | 3.53%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 3         | 3.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 3.53%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 2         | 2.35%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2         | 2.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 2.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 2.35%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.18%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 1.18%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 1.18%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1         | 1.18%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.18%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.18%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.18%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 1.18%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1         | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.18%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.18%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.18%   |
| Intel HD Graphics 610                                                                      | 1         | 1.18%   |
| Intel HD Graphics 515                                                                      | 1         | 1.18%   |
| Intel HD Graphics 500                                                                      | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 605]                                                        | 1         | 1.18%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 1         | 1.18%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 36        | 48.65%  |
| 1 x AMD         | 16        | 21.62%  |
| 1 x Nvidia      | 7         | 9.46%   |
| 1 x SiS         | 5         | 6.76%   |
| 2 x Intel       | 3         | 4.05%   |
| Intel + Nvidia  | 2         | 2.7%    |
| Intel + AMD     | 2         | 2.7%    |
| Other           | 1         | 1.35%   |
| 1 x VIA         | 1         | 1.35%   |
| 1 x S3 Graphics | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 60        | 81.08%  |
| Unknown     | 8         | 10.81%  |
| Proprietary | 6         | 8.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 66.22%  |
| 0.01-0.5   | 16        | 21.62%  |
| 1.01-2.0   | 5         | 6.76%   |
| 0.51-1.0   | 3         | 4.05%   |
| 3.01-4.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 10        | 16.39%  |
| AU Optronics            | 10        | 16.39%  |
| Chimei Innolux          | 7         | 11.48%  |
| LG Display              | 5         | 8.2%    |
| Philips                 | 4         | 6.56%   |
| Dell                    | 3         | 4.92%   |
| BOE                     | 3         | 4.92%   |
| Hewlett-Packard         | 2         | 3.28%   |
| HannStar                | 2         | 3.28%   |
| CPT                     | 2         | 3.28%   |
| Apple                   | 2         | 3.28%   |
| ViewSonic               | 1         | 1.64%   |
| VIE                     | 1         | 1.64%   |
| Orion                   | 1         | 1.64%   |
| MQP                     | 1         | 1.64%   |
| LG Philips              | 1         | 1.64%   |
| Iiyama                  | 1         | 1.64%   |
| Goldstar                | 1         | 1.64%   |
| Chi Mei Optoelectronics | 1         | 1.64%   |
| AOC                     | 1         | 1.64%   |
| Ancor Communications    | 1         | 1.64%   |
| Acer                    | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 3         | 4.92%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 3.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 3.28%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                | 1         | 1.64%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                            | 1         | 1.64%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch        | 1         | 1.64%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch        | 1         | 1.64%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch  | 1         | 1.64%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 1.64%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                      | 1         | 1.64%   |
| Orion ORION ORN120A 1920x540                                             | 1         | 1.64%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 1.64%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 1.64%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                   | 1         | 1.64%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 1.64%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch                | 1         | 1.64%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.64%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 1.64%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                     | 1         | 1.64%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 1.64%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                 | 1         | 1.64%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                       | 1         | 1.64%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 1.64%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 1.64%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 29.51%  |
| 1366x768 (WXGA)    | 17        | 27.87%  |
| 1280x800 (WXGA)    | 6         | 9.84%   |
| 1600x900 (HD+)     | 5         | 8.2%    |
| 1920x1200 (WUXGA)  | 4         | 6.56%   |
| 3840x2160 (4K)     | 2         | 3.28%   |
| 1280x1024 (SXGA)   | 2         | 3.28%   |
| 1024x600           | 2         | 3.28%   |
| 800x600            | 1         | 1.64%   |
| 2256x1504          | 1         | 1.64%   |
| 2160x1440          | 1         | 1.64%   |
| 1920x540           | 1         | 1.64%   |
| 1680x1050 (WSXGA+) | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 29.51%  |
| 24      | 8         | 13.11%  |
| 13      | 7         | 11.48%  |
| 11      | 4         | 6.56%   |
| 17      | 3         | 4.92%   |
| 14      | 3         | 4.92%   |
| 12      | 3         | 4.92%   |
| 23      | 2         | 3.28%   |
| 21      | 2         | 3.28%   |
| 10      | 2         | 3.28%   |
| 46      | 1         | 1.64%   |
| 40      | 1         | 1.64%   |
| 31      | 1         | 1.64%   |
| 27      | 1         | 1.64%   |
| 22      | 1         | 1.64%   |
| 20      | 1         | 1.64%   |
| 19      | 1         | 1.64%   |
| 18      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 41.67%  |
| 201-300     | 12        | 20%     |
| 501-600     | 10        | 16.67%  |
| 401-500     | 5         | 8.33%   |
| 351-400     | 3         | 5%      |
| 601-700     | 2         | 3.33%   |
| 801-900     | 1         | 1.67%   |
| 1001-1500   | 1         | 1.67%   |
| Unknown     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 68.97%  |
| 16/10 | 12        | 20.69%  |
| 5/4   | 2         | 3.45%   |
| 3/2   | 2         | 3.45%   |
| 4/3   | 1         | 1.72%   |
| 32/9  | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 29.51%  |
| 81-90          | 9         | 14.75%  |
| 201-250        | 8         | 13.11%  |
| 251-300        | 5         | 8.2%    |
| 51-60          | 4         | 6.56%   |
| 141-150        | 3         | 4.92%   |
| 71-80          | 2         | 3.28%   |
| 61-70          | 2         | 3.28%   |
| 41-50          | 2         | 3.28%   |
| 151-200        | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |
| 351-500        | 1         | 1.64%   |
| 301-350        | 1         | 1.64%   |
| 121-130        | 1         | 1.64%   |
| Unknown        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 36.07%  |
| 51-100  | 22        | 36.07%  |
| 121-160 | 10        | 16.39%  |
| 161-240 | 5         | 8.2%    |
| 1-50    | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 87.84%  |
| 0     | 5         | 6.76%   |
| 2     | 3         | 4.05%   |
| 3     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 38.46%  |
| Intel                            | 22        | 18.8%   |
| Qualcomm Atheros                 | 17        | 14.53%  |
| Broadcom                         | 7         | 5.98%   |
| Silicon Integrated Systems [SiS] | 4         | 3.42%   |
| Marvell Technology Group         | 4         | 3.42%   |
| Broadcom Limited                 | 4         | 3.42%   |
| Samsung Electronics              | 2         | 1.71%   |
| Ralink Technology                | 2         | 1.71%   |
| Xiaomi                           | 1         | 0.85%   |
| Ralink                           | 1         | 0.85%   |
| Motorola PCS                     | 1         | 0.85%   |
| MediaTek                         | 1         | 0.85%   |
| LG Electronics                   | 1         | 0.85%   |
| JMicron Technology               | 1         | 0.85%   |
| IBM                              | 1         | 0.85%   |
| Guillemot                        | 1         | 0.85%   |
| D-Link System                    | 1         | 0.85%   |
| Accton Technology                | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 19        | 14.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 8.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 2.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 1.55%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.55%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.55%   |
| Intel Wireless 7265                                                     | 2         | 1.55%   |
| Intel Wireless 3165                                                     | 2         | 1.55%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.78%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 31.03%  |
| Qualcomm Atheros      | 16        | 27.59%  |
| Realtek Semiconductor | 12        | 20.69%  |
| Broadcom Limited      | 3         | 5.17%   |
| Broadcom              | 3         | 5.17%   |
| Ralink Technology     | 2         | 3.45%   |
| Ralink                | 1         | 1.72%   |
| MediaTek              | 1         | 1.72%   |
| Guillemot             | 1         | 1.72%   |
| D-Link System         | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 6.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 6.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 3         | 5.17%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 5.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 5.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 5.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 3.45%   |
| Intel Wireless 7265                                                         | 2         | 3.45%   |
| Intel Wireless 3165                                                         | 2         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 1.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.72%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 1.72%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.72%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter               | 1         | 1.72%   |
| Intel WiFi Link 5100                                                        | 1         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 1.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.72%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 1.72%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 1.72%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter        | 1         | 1.72%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 1.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 1.72%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 38        | 60.32%  |
| Intel                            | 6         | 9.52%   |
| Marvell Technology Group         | 4         | 6.35%   |
| Broadcom                         | 4         | 6.35%   |
| Silicon Integrated Systems [SiS] | 3         | 4.76%   |
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

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 30.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 17.46%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 4.76%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2         | 3.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.17%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.59%   |
| Motorola PCS moto g62 5G                                          | 1         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 1.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.59%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.59%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 1.59%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.59%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.59%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.59%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.59%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 48.8%   |
| WiFi     | 56        | 44.8%   |
| Modem    | 7         | 5.6%    |
| Unknown  | 1         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 55.56%  |
| Ethernet | 32        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 39        | 52.7%   |
| 1     | 28        | 37.84%  |
| 0     | 5         | 6.76%   |
| 3     | 2         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 85.14%  |
| Yes  | 11        | 14.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 31.03%  |
| Qualcomm Atheros Communications | 6         | 20.69%  |
| Realtek Semiconductor           | 5         | 17.24%  |
| Apple                           | 2         | 6.9%    |
| Alps Electric                   | 2         | 6.9%    |
| Toshiba                         | 1         | 3.45%   |
| MediaTek                        | 1         | 3.45%   |
| Hewlett-Packard                 | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| ASUSTek Computer                | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 13.79%  |
| Intel Bluetooth wireless interface                  | 4         | 13.79%  |
| Realtek Bluetooth Radio                             | 3         | 10.34%  |
| Intel AX200 Bluetooth                               | 3         | 10.34%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.9%    |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 6.9%    |
| Toshiba Askey for                                   | 1         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.45%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.45%   |
| MediaTek Wireless_Device                            | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.45%   |
| Intel AX210 Bluetooth                               | 1         | 3.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 3.45%   |
| Apple Bluetooth Host Controller                     | 1         | 3.45%   |
| Apple Bluetooth HCI                                 | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 58.97%  |
| AMD                              | 18        | 23.08%  |
| Nvidia                           | 6         | 7.69%   |
| Silicon Integrated Systems [SiS] | 4         | 5.13%   |
| VIA Technologies                 | 1         | 1.28%   |
| Shenzhen Rapoo Technology        | 1         | 1.28%   |
| Logitech                         | 1         | 1.28%   |
| ESS Technology                   | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 7.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 4.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.26%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 3.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.19%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.19%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.19%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.13%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.13%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.13%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.13%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.06%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 1.06%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.06%   |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1         | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia Audio device                                                                               | 1         | 1.06%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.06%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.06%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.06%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 27        | 33.33%  |
| Samsung Electronics | 14        | 17.28%  |
| SK hynix            | 10        | 12.35%  |
| Kingston            | 7         | 8.64%   |
| Elpida              | 3         | 3.7%    |
| A-DATA Technology   | 3         | 3.7%    |
| Unknown (ABCD)      | 2         | 2.47%   |
| Team                | 2         | 2.47%   |
| Micron Technology   | 2         | 2.47%   |
| Crucial             | 2         | 2.47%   |
| Unknown             | 2         | 2.47%   |
| Transcend           | 1         | 1.23%   |
| Toshiba             | 1         | 1.23%   |
| Teikon              | 1         | 1.23%   |
| S                   | 1         | 1.23%   |
| Ramaxel Technology  | 1         | 1.23%   |
| M                   | 1         | 1.23%   |
| G.Skill             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 7.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.53%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 2.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Unknown                                                          | 2         | 2.35%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.18%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.18%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.18%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.18%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.18%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1.18%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.18%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.18%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.18%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.18%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.18%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.18%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.18%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.18%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s                  | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 32.43%  |
| DDR4    | 14        | 18.92%  |
| DDR2    | 13        | 17.57%  |
| SDRAM   | 8         | 10.81%  |
| DDR     | 5         | 6.76%   |
| Unknown | 3         | 4.05%   |
| LPDDR4  | 2         | 2.7%    |
| LPDDR3  | 2         | 2.7%    |
| DRAM    | 2         | 2.7%    |
| DDR5    | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 68.49%  |
| DIMM         | 19        | 26.03%  |
| Row Of Chips | 2         | 2.74%   |
| Unknown      | 2         | 2.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 24        | 30.38%  |
| 4096  | 20        | 25.32%  |
| 8192  | 12        | 15.19%  |
| 1024  | 12        | 15.19%  |
| 512   | 5         | 6.33%   |
| 16384 | 3         | 3.8%    |
| 32768 | 2         | 2.53%   |
| 256   | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 15        | 19.74%  |
| 1600    | 11        | 14.47%  |
| 1333    | 7         | 9.21%   |
| 2667    | 6         | 7.89%   |
| 1334    | 5         | 6.58%   |
| 3200    | 4         | 5.26%   |
| 2400    | 4         | 5.26%   |
| 1067    | 3         | 3.95%   |
| 266     | 3         | 3.95%   |
| 3600    | 2         | 2.63%   |
| 1867    | 2         | 2.63%   |
| 1066    | 2         | 2.63%   |
| 800     | 2         | 2.63%   |
| 667     | 2         | 2.63%   |
| 533     | 2         | 2.63%   |
| 5600    | 1         | 1.32%   |
| 4199    | 1         | 1.32%   |
| 3266    | 1         | 1.32%   |
| 2666    | 1         | 1.32%   |
| 2048    | 1         | 1.32%   |
| 400     | 1         | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 15.63%  |
| Microdia                               | 4         | 12.5%   |
| IMC Networks                           | 4         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 9.38%   |
| Ricoh                                  | 2         | 6.25%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Bison Electronics                      | 2         | 6.25%   |
| Suyin                                  | 1         | 3.13%   |
| Silicon Motion                         | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| KYE Systems (Mouse Systems)            | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |
| ALi                                    | 1         | 3.13%   |
| Alcor Micro                            | 1         | 3.13%   |
| Acer                                   | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 6.25%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.13%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.13%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.13%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.13%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.13%   |
| Realtek HP Wide Vision HD Camera                            | 1         | 3.13%   |
| Quanta Chromebook HD Camera                                 | 1         | 3.13%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.13%   |
| Logitech HD Webcam C525                                     | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.13%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.13%   |
| IMC Networks Integrated Camera                              | 1         | 3.13%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.13%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.13%   |
| Chicony Integrated Camera                                   | 1         | 3.13%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 3.13%   |
| Chicony HP Webcam                                           | 1         | 3.13%   |
| Chicony HP HD Webcam                                        | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 3.13%   |
| Bison Integrated Camera                                     | 1         | 3.13%   |
| Bison EasyCamera                                            | 1         | 3.13%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 3.13%   |
| ALi M5603 Video Camera Controller                           | 1         | 3.13%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 3.13%   |
| Acer HP Webcam-101                                          | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Synaptics                  | 2         | 40%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 20%     |
| Synaptics UWP WBDI                                | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 78.38%  |
| 1     | 9         | 12.16%  |
| 2     | 6         | 8.11%   |
| 4     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 44%     |
| Fingerprint reader       | 5         | 20%     |
| Flash memory             | 2         | 8%      |
| Communication controller | 2         | 8%      |
| Chipcard                 | 2         | 8%      |
| Network                  | 1         | 4%      |
| Net/wireless             | 1         | 4%      |
| Camera                   | 1         | 4%      |

