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

Total: 108

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-121               | Notebook    | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Medion        | Cattle24 -1M                | Desktop     | [aa19188799](https://linux-hardware.org/?probe=aa19188799) | May 08, 2024 |
| Unknown       | HOTTAB                      | Desktop     | [aadecb497e](https://linux-hardware.org/?probe=aadecb497e) | May 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [708780fb6c](https://linux-hardware.org/?probe=708780fb6c) | May 05, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [d6fca9f7f5](https://linux-hardware.org/?probe=d6fca9f7f5) | Apr 13, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| Panasonic     | CF-S10CWHDS                 | Notebook    | [a4c273ab7b](https://linux-hardware.org/?probe=a4c273ab7b) | Mar 19, 2024 |
| MSI           | Alpha 17 C7VF               | Notebook    | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [ba11489894](https://linux-hardware.org/?probe=ba11489894) | Feb 23, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [08c95dbf39](https://linux-hardware.org/?probe=08c95dbf39) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c246a6b564](https://linux-hardware.org/?probe=c246a6b564) | Jan 30, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | Notebook    | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Matsushita... | CF-29LAQGZBM                | Notebook    | [433fd9b78e](https://linux-hardware.org/?probe=433fd9b78e) | Jan 11, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [a7ec902190](https://linux-hardware.org/?probe=a7ec902190) | Jan 10, 2024 |
| Irbis         | NB264                       | Notebook    | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | Notebook    | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
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
| Q4OS 4    | 43        | 47.78%  |
| Q4OS 5    | 25        | 27.78%  |
| Q4OS 3    | 16        | 17.78%  |
| Q4OS 2    | 5         | 5.56%   |
| Q4OS 4.11 | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 90        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.1.0-18-amd64       | 6         | 6.59%   |
| 5.10.0-21-amd64      | 6         | 6.59%   |
| 6.1.0-13-amd64       | 4         | 4.4%    |
| 5.10.0-23-amd64      | 4         | 4.4%    |
| 5.10.0-19-amd64      | 4         | 4.4%    |
| 5.10.0-21-686-pae    | 3         | 3.3%    |
| 5.10.0-12-amd64      | 3         | 3.3%    |
| 4.19.0-17-amd64      | 3         | 3.3%    |
| 6.1.0-21-amd64       | 2         | 2.2%    |
| 6.1.0-17-686-pae     | 2         | 2.2%    |
| 5.10.0-8-amd64       | 2         | 2.2%    |
| 5.10.0-14-686-pae    | 2         | 2.2%    |
| 5.10.0-10-686-pae    | 2         | 2.2%    |
| 6.6.8-x64v1-xanmod1  | 1         | 1.1%    |
| 6.5.1-060501-generic | 1         | 1.1%    |
| 6.5.0-4-amd64        | 1         | 1.1%    |
| 6.1.0-21-686-pae     | 1         | 1.1%    |
| 6.1.0-17-amd64       | 1         | 1.1%    |
| 6.1.0-16-686-pae     | 1         | 1.1%    |
| 6.1.0-12-amd64       | 1         | 1.1%    |
| 6.1.0-12-686-pae     | 1         | 1.1%    |
| 6.1.0-11-686-pae     | 1         | 1.1%    |
| 6.1.0-10-amd64       | 1         | 1.1%    |
| 6.1.0-10-686-pae     | 1         | 1.1%    |
| 6.0.0-1-amd64        | 1         | 1.1%    |
| 5.9.0-5-amd64        | 1         | 1.1%    |
| 5.6.0-1-amd64        | 1         | 1.1%    |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.1%    |
| 5.10.0-9-amd64       | 1         | 1.1%    |
| 5.10.0-9-686-pae     | 1         | 1.1%    |
| 5.10.0-8-686-pae     | 1         | 1.1%    |
| 5.10.0-28-amd64      | 1         | 1.1%    |
| 5.10.0-25-amd64      | 1         | 1.1%    |
| 5.10.0-23-686-pae    | 1         | 1.1%    |
| 5.10.0-20-amd64      | 1         | 1.1%    |
| 5.10.0-20-686-pae    | 1         | 1.1%    |
| 5.10.0-20-686        | 1         | 1.1%    |
| 5.10.0-17-amd64      | 1         | 1.1%    |
| 5.10.0-15-686-pae    | 1         | 1.1%    |
| 5.10.0-14-amd64      | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 40        | 44.44%  |
| 6.1.0   | 22        | 24.44%  |
| 4.19.0  | 17        | 18.89%  |
| 4.9.0   | 4         | 4.44%   |
| 6.6.8   | 1         | 1.11%   |
| 6.5.1   | 1         | 1.11%   |
| 6.5.0   | 1         | 1.11%   |
| 6.0.0   | 1         | 1.11%   |
| 5.9.0   | 1         | 1.11%   |
| 5.6.0   | 1         | 1.11%   |
| 5.18.0  | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 40        | 44.44%  |
| 6.1     | 22        | 24.44%  |
| 4.19    | 17        | 18.89%  |
| 4.9     | 4         | 4.44%   |
| 6.5     | 2         | 2.22%   |
| 6.6     | 1         | 1.11%   |
| 6.0     | 1         | 1.11%   |
| 5.9     | 1         | 1.11%   |
| 5.6     | 1         | 1.11%   |
| 5.18    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 61        | 67.78%  |
| i686   | 29        | 32.22%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| trinity  | 45        | 49.45%  |
| KDE5     | 40        | 43.96%  |
| KDE      | 2         | 2.2%    |
| XFCE     | 1         | 1.1%    |
| LXDE     | 1         | 1.1%    |
| Cinnamon | 1         | 1.1%    |
| Budgie   | 1         | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 97.78%  |
| Wayland | 1         | 1.11%   |
| Tty     | 1         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 45        | 50%     |
| SDDM    | 43        | 47.78%  |
| LightDM | 2         | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 35        | 38.89%  |
| de_DE   | 9         | 10%     |
| it_IT   | 8         | 8.89%   |
| en_GB   | 6         | 6.67%   |
| es_ES   | 5         | 5.56%   |
| hu_HU   | 3         | 3.33%   |
| fr_FR   | 3         | 3.33%   |
| Unknown | 3         | 3.33%   |
| ru_RU   | 2         | 2.22%   |
| pt_BR   | 2         | 2.22%   |
| sv_SE   | 1         | 1.11%   |
| sl_SI   | 1         | 1.11%   |
| sk_SK   | 1         | 1.11%   |
| pl_PL   | 1         | 1.11%   |
| hr_HR   | 1         | 1.11%   |
| fr_CA   | 1         | 1.11%   |
| es_VE   | 1         | 1.11%   |
| es_PE   | 1         | 1.11%   |
| es_AR   | 1         | 1.11%   |
| en_ZA   | 1         | 1.11%   |
| en_SG   | 1         | 1.11%   |
| en_IE   | 1         | 1.11%   |
| C       | 1         | 1.11%   |
| bg_BG   | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 56        | 62.22%  |
| EFI  | 34        | 37.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 96.67%  |
| Overlay | 2         | 2.22%   |
| Btrfs   | 1         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 51        | 56.67%  |
| GPT     | 38        | 42.22%  |
| Unknown | 1         | 1.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 86.67%  |
| Yes       | 12        | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 70%     |
| Yes       | 27        | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 14        | 15.56%  |
| MSI                            | 6         | 6.67%   |
| Lenovo                         | 6         | 6.67%   |
| ASUSTek Computer               | 6         | 6.67%   |
| Toshiba                        | 5         | 5.56%   |
| Acer                           | 5         | 5.56%   |
| Gigabyte Technology            | 4         | 4.44%   |
| ASRock                         | 4         | 4.44%   |
| Medion                         | 3         | 3.33%   |
| Intel                          | 3         | 3.33%   |
| Dell                           | 3         | 3.33%   |
| Apple                          | 3         | 3.33%   |
| TrekStor                       | 2         | 2.22%   |
| Sony                           | 2         | 2.22%   |
| IBM                            | 2         | 2.22%   |
| Google                         | 2         | 2.22%   |
| Unknown                        | 2         | 2.22%   |
| VXL                            | 1         | 1.11%   |
| Visual Land                    | 1         | 1.11%   |
| TECO Electric and Machinery    | 1         | 1.11%   |
| Qilive                         | 1         | 1.11%   |
| Phoenix/SiS                    | 1         | 1.11%   |
| Philco                         | 1         | 1.11%   |
| Panasonic                      | 1         | 1.11%   |
| Packard Bell                   | 1         | 1.11%   |
| Matsushita Electric Industrial | 1         | 1.11%   |
| JVC                            | 1         | 1.11%   |
| Irbis                          | 1         | 1.11%   |
| Fujitsu Siemens                | 1         | 1.11%   |
| Framework                      | 1         | 1.11%   |
| Foxconn                        | 1         | 1.11%   |
| Compaq                         | 1         | 1.11%   |
| Chuwi                          | 1         | 1.11%   |
| BESSTAR Tech                   | 1         | 1.11%   |
| AMI                            | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 3.33%   |
| TrekStor SurfTab wintron 7.0                | 2         | 2.22%   |
| Toshiba Satellite C660                      | 2         | 2.22%   |
| HP ProBook 650 G1                           | 2         | 2.22%   |
| VXL TC7500D Series                          | 1         | 1.11%   |
| Visual Land Premier 10                      | 1         | 1.11%   |
| Toshiba Satellite Pro L500                  | 1         | 1.11%   |
| Toshiba Satellite M70                       | 1         | 1.11%   |
| Toshiba Satellite L515                      | 1         | 1.11%   |
| TECO Electric and Machinery FUTRO S400      | 1         | 1.11%   |
| Sony VGN-P11Z_Q                             | 1         | 1.11%   |
| Sony VGN-FW21Z                              | 1         | 1.11%   |
| Qilive QW19141AMSP                          | 1         | 1.11%   |
| Phoenix/SiS M720SR                          | 1         | 1.11%   |
| Philco 14I                                  | 1         | 1.11%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.11%   |
| Packard Bell EasyNote LM81                  | 1         | 1.11%   |
| MSI U90/U100                                | 1         | 1.11%   |
| MSI U210                                    | 1         | 1.11%   |
| MSI MS-7C56                                 | 1         | 1.11%   |
| MSI MS-7597                                 | 1         | 1.11%   |
| MSI MS-7592                                 | 1         | 1.11%   |
| MSI Alpha 17 C7VF                           | 1         | 1.11%   |
| Medion P961x                                | 1         | 1.11%   |
| Medion P6620                                | 1         | 1.11%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.11%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 1.11%   |
| Lenovo ThinkPad 11e 20DAS0PS00              | 1         | 1.11%   |
| Lenovo IdeaPad S145-15AST 81N3              | 1         | 1.11%   |
| Lenovo IdeaPad 5 14IAL7 82SD                | 1         | 1.11%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 1.11%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 1.11%   |
| JVC J3N                                     | 1         | 1.11%   |
| Irbis NB264                                 | 1         | 1.11%   |
| Intel NUC5CPYB H61145-407                   | 1         | 1.11%   |
| Intel NUC12WSHi7                            | 1         | 1.11%   |
| Intel D845GRG AAA84341-206                  | 1         | 1.11%   |
| IBM ThinkPad T43 1875DMU                    | 1         | 1.11%   |
| IBM ThinkPad T42 2378FVU                    | 1         | 1.11%   |
| HP ProBook 6550b                            | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite                           | 5         | 5.56%   |
| Lenovo IdeaPad                              | 4         | 4.44%   |
| HP ProBook                                  | 4         | 4.44%   |
| Dell Latitude                               | 3         | 3.33%   |
| Acer Aspire                                 | 3         | 3.33%   |
| Unknown                                     | 3         | 3.33%   |
| TrekStor SurfTab                            | 2         | 2.22%   |
| Lenovo ThinkPad                             | 2         | 2.22%   |
| IBM ThinkPad                                | 2         | 2.22%   |
| HP Pavilion                                 | 2         | 2.22%   |
| VXL TC7500D                                 | 1         | 1.11%   |
| Visual Land Premier                         | 1         | 1.11%   |
| TECO Electric and Machinery FUTRO           | 1         | 1.11%   |
| Sony VGN-P11Z                               | 1         | 1.11%   |
| Sony VGN-FW21Z                              | 1         | 1.11%   |
| Qilive QW19141AMSP                          | 1         | 1.11%   |
| Phoenix/SiS M720SR                          | 1         | 1.11%   |
| Philco 14I                                  | 1         | 1.11%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.11%   |
| Packard Bell EasyNote                       | 1         | 1.11%   |
| MSI U90                                     | 1         | 1.11%   |
| MSI U210                                    | 1         | 1.11%   |
| MSI MS-7C56                                 | 1         | 1.11%   |
| MSI MS-7597                                 | 1         | 1.11%   |
| MSI MS-7592                                 | 1         | 1.11%   |
| MSI Alpha                                   | 1         | 1.11%   |
| Medion P961x                                | 1         | 1.11%   |
| Medion P6620                                | 1         | 1.11%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.11%   |
| JVC J3N                                     | 1         | 1.11%   |
| Irbis NB264                                 | 1         | 1.11%   |
| Intel NUC5CPYB                              | 1         | 1.11%   |
| Intel NUC12WSHi7                            | 1         | 1.11%   |
| Intel D845GRG                               | 1         | 1.11%   |
| HP Presario                                 | 1         | 1.11%   |
| HP OmniBook                                 | 1         | 1.11%   |
| HP Laptop                                   | 1         | 1.11%   |
| HP ENVY                                     | 1         | 1.11%   |
| HP EliteBook                                | 1         | 1.11%   |
| HP Compaq                                   | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 10        | 11.11%  |
| 2010    | 8         | 8.89%   |
| 2011    | 6         | 6.67%   |
| 2020    | 5         | 5.56%   |
| 2018    | 5         | 5.56%   |
| 2016    | 5         | 5.56%   |
| 2012    | 5         | 5.56%   |
| 2008    | 5         | 5.56%   |
| 2005    | 5         | 5.56%   |
| 2015    | 4         | 4.44%   |
| 2013    | 4         | 4.44%   |
| 2023    | 3         | 3.33%   |
| 2022    | 3         | 3.33%   |
| 2019    | 3         | 3.33%   |
| 2017    | 3         | 3.33%   |
| 2007    | 3         | 3.33%   |
| 2021    | 2         | 2.22%   |
| 2014    | 2         | 2.22%   |
| 2006    | 2         | 2.22%   |
| 2004    | 2         | 2.22%   |
| 2002    | 2         | 2.22%   |
| Unknown | 2         | 2.22%   |
| 2003    | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 58        | 64.44%  |
| Desktop     | 22        | 24.44%  |
| Tablet      | 3         | 3.33%   |
| Convertible | 3         | 3.33%   |
| Mini pc     | 3         | 3.33%   |
| All in one  | 1         | 1.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 86        | 95.56%  |
| Enabled  | 4         | 4.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 97.78%  |
| Yes  | 2         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 27        | 30%     |
| 4.01-8.0    | 13        | 14.44%  |
| 2.01-3.0    | 13        | 14.44%  |
| 1.01-2.0    | 10        | 11.11%  |
| 8.01-16.0   | 6         | 6.67%   |
| 0.51-1.0    | 6         | 6.67%   |
| 16.01-24.0  | 5         | 5.56%   |
| 0.01-0.5    | 5         | 5.56%   |
| 64.01-256.0 | 3         | 3.33%   |
| 32.01-64.0  | 1         | 1.11%   |
| 24.01-32.0  | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 34        | 36.96%  |
| 0.51-1.0  | 20        | 21.74%  |
| 2.01-3.0  | 16        | 17.39%  |
| 0.01-0.5  | 10        | 10.87%  |
| 4.01-8.0  | 7         | 7.61%   |
| 3.01-4.0  | 4         | 4.35%   |
| 8.01-16.0 | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 73.63%  |
| 2      | 16        | 17.58%  |
| 3      | 8         | 8.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 51.65%  |
| Yes       | 44        | 48.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 84.44%  |
| No        | 14        | 15.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 77.78%  |
| No        | 20        | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 60%     |
| Yes       | 36        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 17.78%  |
| Italy        | 9         | 10%     |
| Germany      | 8         | 8.89%   |
| UK           | 6         | 6.67%   |
| Spain        | 4         | 4.44%   |
| Switzerland  | 3         | 3.33%   |
| Kenya        | 3         | 3.33%   |
| Hungary      | 3         | 3.33%   |
| Brazil       | 3         | 3.33%   |
| Venezuela    | 2         | 2.22%   |
| Turkey       | 2         | 2.22%   |
| Slovenia     | 2         | 2.22%   |
| Russia       | 2         | 2.22%   |
| Romania      | 2         | 2.22%   |
| Poland       | 2         | 2.22%   |
| Netherlands  | 2         | 2.22%   |
| Mexico       | 2         | 2.22%   |
| France       | 2         | 2.22%   |
| Croatia      | 2         | 2.22%   |
| Canada       | 2         | 2.22%   |
| Belgium      | 2         | 2.22%   |
| Sweden       | 1         | 1.11%   |
| South Africa | 1         | 1.11%   |
| Slovakia     | 1         | 1.11%   |
| Singapore    | 1         | 1.11%   |
| Saudi Arabia | 1         | 1.11%   |
| Qatar        | 1         | 1.11%   |
| Peru         | 1         | 1.11%   |
| Bulgaria     | 1         | 1.11%   |
| Belarus      | 1         | 1.11%   |
| Argentina    | 1         | 1.11%   |
| Algeria      | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Jacksonville          | 6         | 6.67%   |
| Nairobi               | 3         | 3.33%   |
| Zurich                | 2         | 2.22%   |
| Swindon               | 2         | 2.22%   |
| Rostock               | 2         | 2.22%   |
| Morelia               | 2         | 2.22%   |
| Mesa                  | 2         | 2.22%   |
| Ljubljana             | 2         | 2.22%   |
| Drobeta-Turnu Severin | 2         | 2.22%   |
| Budapest              | 2         | 2.22%   |
| Bologna               | 2         | 2.22%   |
| Zagreb                | 1         | 1.11%   |
| West Corinth          | 1         | 1.11%   |
| Volgograd             | 1         | 1.11%   |
| Toalmas               | 1         | 1.11%   |
| The Hague             | 1         | 1.11%   |
| Tenbury Wells         | 1         | 1.11%   |
| Tellico Plains        | 1         | 1.11%   |
| Sosnowiec             | 1         | 1.11%   |
| Solingen              | 1         | 1.11%   |
| Sofia                 | 1         | 1.11%   |
| Sint-Pieters-Leeuw    | 1         | 1.11%   |
| Singapore             | 1         | 1.11%   |
| Sétif                | 1         | 1.11%   |
| Schermbeck            | 1         | 1.11%   |
| Savona                | 1         | 1.11%   |
| Sao Pedro da Aldeia   | 1         | 1.11%   |
| San Carlos del Zulia  | 1         | 1.11%   |
| Salsomaggiore Terme   | 1         | 1.11%   |
| Rome                  | 1         | 1.11%   |
| Rochdale              | 1         | 1.11%   |
| Rijeka                | 1         | 1.11%   |
| Puerto Cumarebo       | 1         | 1.11%   |
| Posadas               | 1         | 1.11%   |
| Osnabrück            | 1         | 1.11%   |
| Moscow                | 1         | 1.11%   |
| Mooresville           | 1         | 1.11%   |
| Montreal              | 1         | 1.11%   |
| Moirans               | 1         | 1.11%   |
| Mogilev               | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 13.89%  |
| Seagate             | 14        | 16     | 12.96%  |
| Samsung Electronics | 12        | 14     | 11.11%  |
| Unknown             | 9         | 9      | 8.33%   |
| SanDisk             | 8         | 10     | 7.41%   |
| Kingston            | 7         | 7      | 6.48%   |
| Toshiba             | 5         | 5      | 4.63%   |
| Hitachi             | 5         | 5      | 4.63%   |
| China               | 5         | 6      | 4.63%   |
| Fujitsu             | 3         | 3      | 2.78%   |
| A-DATA Technology   | 3         | 3      | 2.78%   |
| KESU                | 2         | 2      | 1.85%   |
| HGST                | 2         | 2      | 1.85%   |
| Crucial             | 2         | 3      | 1.85%   |
| Unknown             | 2         | 2      | 1.85%   |
| USB3.0              | 1         | 1      | 0.93%   |
| Unknown (CF)        | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| SPCC                | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| Maxtor              | 1         | 1      | 0.93%   |
| KIOXIA              | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 1      | 0.93%   |
| KBG40ZNV            | 1         | 1      | 0.93%   |
| IBM/Hitachi         | 1         | 2      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 1.77%   |
| SanDisk SDSSDA120G 120GB             | 2         | 1.77%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.77%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.77%   |
| KESU USB 3.1 256GB                   | 2         | 1.77%   |
| A-DATA SU630 240GB SSD               | 2         | 1.77%   |
| Unknown                              | 2         | 1.77%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.88%   |
| WDC WD800BD-22MRA1 80GB              | 1         | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.88%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 0.88%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.88%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.88%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.88%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 0.88%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.88%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 0.88%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 0.88%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 0.88%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 0.88%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.88%   |
| USB3.0 Super Speed 240GB             | 1         | 0.88%   |
| Unknown USDU1  32GB                  | 1         | 0.88%   |
| Unknown SLD64G  64GB                 | 1         | 0.88%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 0.88%   |
| Unknown S0J59X  128GB                | 1         | 0.88%   |
| Unknown MMC Card  64GB               | 1         | 0.88%   |
| Unknown HAG2e  16GB                  | 1         | 0.88%   |
| Unknown 064G38  64GB                 | 1         | 0.88%   |
| Unknown (CF) CARD 16GB               | 1         | 0.88%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 0.88%   |
| Toshiba MK8032GAX 80GB               | 1         | 0.88%   |
| Toshiba MK8025GAS 80GB               | 1         | 0.88%   |
| Toshiba MK6028GAL 64GB               | 1         | 0.88%   |
| Toshiba MK3276GSX 320GB              | 1         | 0.88%   |
| Toshiba MK3252GSX 320GB              | 1         | 0.88%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 0.88%   |
| Silicon Motion NVME SSD 512GB        | 1         | 0.88%   |
| Seagate ST96812AS 64GB               | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 26.09%  |
| Seagate             | 12        | 14     | 26.09%  |
| Toshiba             | 5         | 5      | 10.87%  |
| Hitachi             | 5         | 5      | 10.87%  |
| Fujitsu             | 3         | 3      | 6.52%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| Unknown (CF)        | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |
| Maxtor              | 1         | 1      | 2.17%   |
| IBM/Hitachi         | 1         | 2      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 20.59%  |
| Samsung Electronics | 6         | 6      | 17.65%  |
| SanDisk             | 5         | 7      | 14.71%  |
| China               | 5         | 6      | 14.71%  |
| WDC                 | 2         | 2      | 5.88%   |
| A-DATA Technology   | 2         | 2      | 5.88%   |
| USB3.0              | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| KingSpec            | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 42        | 49     | 41.58%  |
| SSD     | 32        | 37     | 31.68%  |
| NVMe    | 12        | 16     | 11.88%  |
| MMC     | 11        | 11     | 10.89%  |
| Unknown | 4         | 4      | 3.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 83     | 69.31%  |
| NVMe | 12        | 15     | 11.88%  |
| MMC  | 11        | 11     | 10.89%  |
| SAS  | 8         | 8      | 7.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 73     | 82.43%  |
| 0.51-1.0   | 10        | 10     | 13.51%  |
| 4.01-10.0  | 2         | 2      | 2.7%    |
| 1.01-2.0   | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 24.18%  |
| 51-100         | 18        | 19.78%  |
| 251-500        | 17        | 18.68%  |
| 1-20           | 10        | 10.99%  |
| 21-50          | 9         | 9.89%   |
| 501-1000       | 7         | 7.69%   |
| 1001-2000      | 5         | 5.49%   |
| More than 3000 | 2         | 2.2%    |
| Unknown        | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 68.13%  |
| 21-50          | 11        | 12.09%  |
| 51-100         | 6         | 6.59%   |
| 251-500        | 5         | 5.49%   |
| 101-250        | 3         | 3.3%    |
| 501-1000       | 2         | 2.2%    |
| More than 3000 | 1         | 1.1%    |
| Unknown        | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1         | 1      | 5%      |
| WDC WD400BD-23JMC0 40GB           | 1         | 1      | 5%      |
| WDC WD2500BEVT-60A23T0 250GB      | 1         | 1      | 5%      |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 5%      |
| WDC WD10EARS-00Y5B1 1TB           | 1         | 1      | 5%      |
| Toshiba MK3252GSX 320GB           | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB         | 1         | 1      | 5%      |
| Seagate ST9120822AS 120GB         | 1         | 1      | 5%      |
| Seagate ST3320820SCE 320GB        | 1         | 2      | 5%      |
| Samsung Electronics HM080GC 80GB  | 1         | 1      | 5%      |
| PNY 1TB SATA SSD                  | 1         | 1      | 5%      |
| Maxtor 6Y080L0 82GB               | 1         | 1      | 5%      |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1         | 2      | 5%      |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 5%      |
| Hitachi HTS543225L9SA00 250GB     | 1         | 1      | 5%      |
| Hitachi DK23CA-20 20GB            | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 5%      |
| HGST HTS541075A9E680 752GB        | 1         | 1      | 5%      |
| Fujitsu MHZ2160BH G2 160GB        | 1         | 1      | 5%      |
| Fujitsu MHY2080BH 80GB            | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 25%     |
| Seagate             | 3         | 4      | 15%     |
| Hitachi             | 3         | 3      | 15%     |
| HGST                | 2         | 2      | 10%     |
| Fujitsu             | 2         | 2      | 10%     |
| Toshiba             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| Maxtor              | 1         | 1      | 5%      |
| IBM/Hitachi         | 1         | 2      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 22.22%  |
| Seagate             | 3         | 4      | 16.67%  |
| Hitachi             | 3         | 3      | 16.67%  |
| HGST                | 2         | 2      | 11.11%  |
| Fujitsu             | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Maxtor              | 1         | 1      | 5.56%   |
| IBM/Hitachi         | 1         | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 89.47%  |
| SSD  | 2         | 2      | 10.53%  |

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
| Works    | 60        | 75     | 61.22%  |
| Detected | 19        | 20     | 19.39%  |
| Malfunc  | 19        | 22     | 19.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 58        | 62.37%  |
| AMD                              | 13        | 13.98%  |
| Silicon Integrated Systems [SiS] | 5         | 5.38%   |
| Samsung Electronics              | 4         | 4.3%    |
| SanDisk                          | 3         | 3.23%   |
| Micron/Crucial Technology        | 2         | 2.15%   |
| VIA Technologies                 | 1         | 1.08%   |
| Silicon Motion                   | 1         | 1.08%   |
| Phison Electronics               | 1         | 1.08%   |
| Nvidia                           | 1         | 1.08%   |
| KIOXIA                           | 1         | 1.08%   |
| JMicron Technology               | 1         | 1.08%   |
| ASMedia Technology               | 1         | 1.08%   |
| ADATA Technology                 | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 9.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 5.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 5.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 5         | 4.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 3.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 3         | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 2.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 2.73%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 2.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.82%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.82%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 2         | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.82%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.91%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.91%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 0.91%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.91%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.91%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 0.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.91%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.91%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.91%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.91%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 0.91%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.91%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 53.06%  |
| IDE  | 32        | 32.65%  |
| NVMe | 11        | 11.22%  |
| RAID | 3         | 3.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 69        | 76.67%  |
| AMD          | 20        | 22.22%  |
| CentaurHauls | 1         | 1.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz             | 3         | 3.33%   |
| Intel Atom CPU N270 @ 1.60GHz               | 3         | 3.33%   |
| Intel Pentium M processor 1.70GHz           | 2         | 2.22%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 2.22%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.22%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 2.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 2.22%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 2.22%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.22%   |
| AMD C-70 APU with Radeon HD Graphics        | 2         | 2.22%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.11%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.11%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.11%   |
| Intel Pentium III (Coppermine)              | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.11%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.11%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 1.11%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.11%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.11%   |
| Intel Pentium 4 CPU 1.80GHz                 | 1         | 1.11%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 1.11%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.11%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.11%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.11%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.11%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.11%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.11%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.11%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 12        | 13.33%  |
| Intel Core i5           | 9         | 10%     |
| Intel Core 2 Duo        | 9         | 10%     |
| Intel Celeron           | 9         | 10%     |
| Intel Pentium M         | 5         | 5.56%   |
| Other                   | 4         | 4.44%   |
| Intel Pentium Dual-Core | 4         | 4.44%   |
| Intel Pentium 4         | 4         | 4.44%   |
| Intel Core i3           | 4         | 4.44%   |
| AMD Ryzen 7             | 3         | 3.33%   |
| Intel Genuine           | 2         | 2.22%   |
| Intel Core i7           | 2         | 2.22%   |
| AMD C-70                | 2         | 2.22%   |
| AMD Athlon              | 2         | 2.22%   |
| AMD A4                  | 2         | 2.22%   |
| Intel Pentium Silver    | 1         | 1.11%   |
| Intel Pentium III       | 1         | 1.11%   |
| Intel Pentium           | 1         | 1.11%   |
| Intel Core m3           | 1         | 1.11%   |
| Intel Core 2            | 1         | 1.11%   |
| CentaurHauls VIA Eden   | 1         | 1.11%   |
| AMD V120                | 1         | 1.11%   |
| AMD Ryzen 9             | 1         | 1.11%   |
| AMD Ryzen 7 PRO         | 1         | 1.11%   |
| AMD Ryzen 5 PRO         | 1         | 1.11%   |
| AMD Ryzen 5             | 1         | 1.11%   |
| AMD Mobile Sempron      | 1         | 1.11%   |
| AMD E                   | 1         | 1.11%   |
| AMD Athlon Neo          | 1         | 1.11%   |
| AMD Athlon II X2        | 1         | 1.11%   |
| AMD A8                  | 1         | 1.11%   |
| AMD A6                  | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 48.89%  |
| 1      | 21        | 23.33%  |
| 4      | 17        | 18.89%  |
| 8      | 3         | 3.33%   |
| 16     | 2         | 2.22%   |
| 12     | 2         | 2.22%   |
| 6      | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 62.22%  |
| 2      | 34        | 37.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 78.89%  |
| 32-bit         | 19        | 21.11%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 14.44%  |
| 0x206a7    | 6         | 6.67%   |
| 0x106c2    | 6         | 6.67%   |
| 0x1067a    | 6         | 6.67%   |
| 0x30678    | 4         | 4.44%   |
| 0x706a1    | 3         | 3.33%   |
| 0x6fd      | 3         | 3.33%   |
| 0x10676    | 3         | 3.33%   |
| 0xf27      | 2         | 2.22%   |
| 0x906a3    | 2         | 2.22%   |
| 0x806e9    | 2         | 2.22%   |
| 0x6e8      | 2         | 2.22%   |
| 0x406c4    | 2         | 2.22%   |
| 0x406c3    | 2         | 2.22%   |
| 0x40651    | 2         | 2.22%   |
| 0x306c3    | 2         | 2.22%   |
| 0x0810100b | 2         | 2.22%   |
| 0x05000119 | 2         | 2.22%   |
| 0x010000c8 | 2         | 2.22%   |
| 0xf49      | 1         | 1.11%   |
| 0xf12      | 1         | 1.11%   |
| 0xb0671    | 1         | 1.11%   |
| 0x806c1    | 1         | 1.11%   |
| 0x706a8    | 1         | 1.11%   |
| 0x6fb      | 1         | 1.11%   |
| 0x6f6      | 1         | 1.11%   |
| 0x6d8      | 1         | 1.11%   |
| 0x6d6      | 1         | 1.11%   |
| 0x695      | 1         | 1.11%   |
| 0x68a      | 1         | 1.11%   |
| 0x406e3    | 1         | 1.11%   |
| 0x306a9    | 1         | 1.11%   |
| 0x20655    | 1         | 1.11%   |
| 0x0a704103 | 1         | 1.11%   |
| 0x0a601203 | 1         | 1.11%   |
| 0x08701013 | 1         | 1.11%   |
| 0x08600106 | 1         | 1.11%   |
| 0x08108102 | 1         | 1.11%   |
| 0x0800820d | 1         | 1.11%   |
| 0x07030106 | 1         | 1.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 9         | 10%     |
| Penryn           | 9         | 10%     |
| P6               | 8         | 8.89%   |
| SandyBridge      | 7         | 7.78%   |
| Bonnell          | 7         | 7.78%   |
| Goldmont plus    | 5         | 5.56%   |
| Core             | 5         | 5.56%   |
| NetBurst         | 4         | 4.44%   |
| Haswell          | 4         | 4.44%   |
| Unknown          | 4         | 4.44%   |
| Bobcat           | 3         | 3.33%   |
| Zen+             | 2         | 2.22%   |
| Zen 2            | 2         | 2.22%   |
| Zen              | 2         | 2.22%   |
| KabyLake         | 2         | 2.22%   |
| K8 Hammer        | 2         | 2.22%   |
| K10              | 2         | 2.22%   |
| Excavator        | 2         | 2.22%   |
| Alderlake Hybrid | 2         | 2.22%   |
| Westmere         | 1         | 1.11%   |
| TigerLake        | 1         | 1.11%   |
| Skylake          | 1         | 1.11%   |
| Puma             | 1         | 1.11%   |
| Piledriver       | 1         | 1.11%   |
| Nehalem          | 1         | 1.11%   |
| K6               | 1         | 1.11%   |
| IvyBridge        | 1         | 1.11%   |
| Goldmont         | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 56        | 58.95%  |
| AMD                              | 21        | 22.11%  |
| Nvidia                           | 11        | 11.58%  |
| Silicon Integrated Systems [SiS] | 5         | 5.26%   |
| VIA Technologies                 | 1         | 1.05%   |
| S3 Graphics                      | 1         | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 6         | 5.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 5         | 4.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 4.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 4         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 4         | 3.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 4         | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 3.85%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 2.88%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 3         | 2.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 3         | 2.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 2.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 2         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 2         | 1.92%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 2         | 1.92%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 2         | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 1.92%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 2         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 2         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 1.92%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 0.96%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 0.96%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 0.96%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 0.96%   |
| Nvidia GT216M [GeForce GT 330M]                                                            | 1         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 0.96%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1         | 0.96%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 0.96%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 0.96%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 0.96%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 0.96%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                            | 1         | 0.96%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1         | 0.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 0.96%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1         | 0.96%   |
| Intel HD Graphics 620                                                                      | 1         | 0.96%   |
| Intel HD Graphics 610                                                                      | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 43        | 47.78%  |
| 1 x AMD         | 18        | 20%     |
| 2 x Intel       | 8         | 8.89%   |
| 1 x Nvidia      | 8         | 8.89%   |
| 1 x SiS         | 5         | 5.56%   |
| Intel + Nvidia  | 2         | 2.22%   |
| Intel + AMD     | 2         | 2.22%   |
| Other           | 1         | 1.11%   |
| 1 x VIA         | 1         | 1.11%   |
| 1 x S3 Graphics | 1         | 1.11%   |
| AMD + Nvidia    | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 82.22%  |
| Unknown     | 9         | 10%     |
| Proprietary | 7         | 7.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 68.89%  |
| 0.01-0.5   | 19        | 21.11%  |
| 1.01-2.0   | 5         | 5.56%   |
| 0.51-1.0   | 3         | 3.33%   |
| 3.01-4.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 17.57%  |
| Samsung Electronics     | 11        | 14.86%  |
| Chimei Innolux          | 8         | 10.81%  |
| LG Display              | 6         | 8.11%   |
| Dell                    | 5         | 6.76%   |
| Philips                 | 4         | 5.41%   |
| BOE                     | 4         | 5.41%   |
| Hewlett-Packard         | 2         | 2.7%    |
| HannStar                | 2         | 2.7%    |
| CPT                     | 2         | 2.7%    |
| Apple                   | 2         | 2.7%    |
| AOC                     | 2         | 2.7%    |
| ViewSonic               | 1         | 1.35%   |
| VIE                     | 1         | 1.35%   |
| Orion                   | 1         | 1.35%   |
| MQP                     | 1         | 1.35%   |
| Medion                  | 1         | 1.35%   |
| LG Philips              | 1         | 1.35%   |
| InfoVision              | 1         | 1.35%   |
| Iiyama                  | 1         | 1.35%   |
| Goldstar                | 1         | 1.35%   |
| CSO                     | 1         | 1.35%   |
| Chi Mei Optoelectronics | 1         | 1.35%   |
| Ancor Communications    | 1         | 1.35%   |
| Acer                    | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 4.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 2.7%    |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 1.35%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 1.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1         | 1.35%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch       | 1         | 1.35%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 1.35%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch   | 1         | 1.35%   |
| Philips 170B4 PHL0817 1280x1024 338x270mm 17.0-inch                     | 1         | 1.35%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 1.35%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                    | 1         | 1.35%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch              | 1         | 1.35%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch             | 1         | 1.35%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 1.35%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch             | 1         | 1.35%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 1.35%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch             | 1         | 1.35%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch            | 1         | 1.35%   |
| Iiyama PLE2400WS IVM5601 1920x1200                                      | 1         | 1.35%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch              | 1         | 1.35%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1         | 1.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch               | 1         | 1.35%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 1.35%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 1.35%   |
| Dell UP2715K DEL40B6 2560x1440 600x340mm 27.2-inch                      | 1         | 1.35%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 1.35%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                      | 1         | 1.35%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                | 1         | 1.35%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1         | 1.35%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 380x210mm 17.1-inch                   | 1         | 1.35%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 1.35%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                    | 1         | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 30.14%  |
| 1366x768 (WXGA)    | 21        | 28.77%  |
| 1280x800 (WXGA)    | 6         | 8.22%   |
| 1920x1200 (WUXGA)  | 5         | 6.85%   |
| 1600x900 (HD+)     | 5         | 6.85%   |
| 3840x2160 (4K)     | 2         | 2.74%   |
| 1280x1024 (SXGA)   | 2         | 2.74%   |
| 1024x600           | 2         | 2.74%   |
| 800x600            | 1         | 1.37%   |
| 3440x1440          | 1         | 1.37%   |
| 2560x1440 (QHD)    | 1         | 1.37%   |
| 2256x1504          | 1         | 1.37%   |
| 2160x1440          | 1         | 1.37%   |
| 1920x540           | 1         | 1.37%   |
| 1680x1050 (WSXGA+) | 1         | 1.37%   |
| 1024x768 (XGA)     | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 31.08%  |
| 24      | 8         | 10.81%  |
| 13      | 8         | 10.81%  |
| 14      | 5         | 6.76%   |
| 11      | 5         | 6.76%   |
| 17      | 4         | 5.41%   |
| 21      | 3         | 4.05%   |
| 12      | 3         | 4.05%   |
| 27      | 2         | 2.7%    |
| 23      | 2         | 2.7%    |
| 10      | 2         | 2.7%    |
| 46      | 1         | 1.35%   |
| 40      | 1         | 1.35%   |
| 34      | 1         | 1.35%   |
| 31      | 1         | 1.35%   |
| 22      | 1         | 1.35%   |
| 20      | 1         | 1.35%   |
| 19      | 1         | 1.35%   |
| 18      | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 43.84%  |
| 201-300     | 14        | 19.18%  |
| 501-600     | 11        | 15.07%  |
| 401-500     | 6         | 8.22%   |
| 351-400     | 4         | 5.48%   |
| 601-700     | 2         | 2.74%   |
| 801-900     | 1         | 1.37%   |
| 701-800     | 1         | 1.37%   |
| 1001-1500   | 1         | 1.37%   |
| Unknown     | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 71.43%  |
| 16/10 | 12        | 17.14%  |
| 5/4   | 2         | 2.86%   |
| 4/3   | 2         | 2.86%   |
| 3/2   | 2         | 2.86%   |
| 32/9  | 1         | 1.43%   |
| 21/9  | 1         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 31.08%  |
| 81-90          | 11        | 14.86%  |
| 201-250        | 9         | 12.16%  |
| 51-60          | 5         | 6.76%   |
| 251-300        | 5         | 6.76%   |
| 71-80          | 3         | 4.05%   |
| 141-150        | 3         | 4.05%   |
| 61-70          | 2         | 2.7%    |
| 351-500        | 2         | 2.7%    |
| 41-50          | 2         | 2.7%    |
| 301-350        | 2         | 2.7%    |
| 151-200        | 2         | 2.7%    |
| 121-130        | 2         | 2.7%    |
| 501-1000       | 2         | 2.7%    |
| Unknown        | 1         | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 29        | 39.19%  |
| 51-100  | 23        | 31.08%  |
| 121-160 | 12        | 16.22%  |
| 161-240 | 7         | 9.46%   |
| 1-50    | 2         | 2.7%    |
| Unknown | 1         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 87.78%  |
| 0     | 6         | 6.67%   |
| 2     | 4         | 4.44%   |
| 3     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 53        | 37.86%  |
| Intel                            | 29        | 20.71%  |
| Qualcomm Atheros                 | 18        | 12.86%  |
| Broadcom                         | 10        | 7.14%   |
| Marvell Technology Group         | 5         | 3.57%   |
| Broadcom Limited                 | 5         | 3.57%   |
| Silicon Integrated Systems [SiS] | 4         | 2.86%   |
| Ralink Technology                | 3         | 2.14%   |
| Samsung Electronics              | 2         | 1.43%   |
| Xiaomi                           | 1         | 0.71%   |
| Ralink                           | 1         | 0.71%   |
| Qualcomm Technologies            | 1         | 0.71%   |
| Motorola PCS                     | 1         | 0.71%   |
| MediaTek                         | 1         | 0.71%   |
| LG Electronics                   | 1         | 0.71%   |
| JMicron Technology               | 1         | 0.71%   |
| IBM                              | 1         | 0.71%   |
| Guillemot                        | 1         | 0.71%   |
| D-Link System                    | 1         | 0.71%   |
| Accton Technology                | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 21        | 13.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 8.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 2.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.89%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 1.89%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 1.26%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.26%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.26%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.26%   |
| Intel Wireless 7265                                                     | 2         | 1.26%   |
| Intel Wireless 3165                                                     | 2         | 1.26%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.26%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.26%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.63%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.63%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 32.88%  |
| Qualcomm Atheros      | 17        | 23.29%  |
| Realtek Semiconductor | 16        | 21.92%  |
| Broadcom              | 5         | 6.85%   |
| Ralink Technology     | 3         | 4.11%   |
| Broadcom Limited      | 3         | 4.11%   |
| Ralink                | 1         | 1.37%   |
| Qualcomm Technologies | 1         | 1.37%   |
| MediaTek              | 1         | 1.37%   |
| Guillemot             | 1         | 1.37%   |
| D-Link System         | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 4         | 5.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 4         | 5.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 4         | 5.48%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                   | 4         | 5.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 4.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 4.11%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 4.11%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                 | 2         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 2.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 2         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 2         | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 2.74%   |
| Intel Wireless 7265                                                        | 2         | 2.74%   |
| Intel Wireless 3165                                                        | 2         | 2.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 2.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2         | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 1.37%   |
| Realtek RTL8187SE Wireless LAN Controller                                  | 1         | 1.37%   |
| Realtek RTL8187B Wireless Adapter                                          | 1         | 1.37%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 1.37%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 1         | 1.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1         | 1.37%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]           | 1         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 1.37%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]        | 1         | 1.37%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 1         | 1.37%   |
| Intel Wireless 8265 / 8275                                                 | 1         | 1.37%   |
| Intel WiFi Link 5100                                                       | 1         | 1.37%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 1         | 1.37%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1         | 1.37%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]  | 1         | 1.37%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 44        | 56.41%  |
| Intel                            | 10        | 12.82%  |
| Marvell Technology Group         | 5         | 6.41%   |
| Broadcom                         | 5         | 6.41%   |
| Silicon Integrated Systems [SiS] | 3         | 3.85%   |
| Samsung Electronics              | 2         | 2.56%   |
| Qualcomm Atheros                 | 2         | 2.56%   |
| Broadcom Limited                 | 2         | 2.56%   |
| Xiaomi                           | 1         | 1.28%   |
| Motorola PCS                     | 1         | 1.28%   |
| LG Electronics                   | 1         | 1.28%   |
| JMicron Technology               | 1         | 1.28%   |
| Accton Technology                | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 21        | 26.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 17.95%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 3.85%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 2         | 2.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 2.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 2.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 2.56%   |
| Intel Ethernet Connection I217-V                                       | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.28%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.28%   |
| Motorola PCS moto g(7) power                                           | 1         | 1.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 1.28%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.28%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                    | 1         | 1.28%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.28%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.28%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.28%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                     | 1         | 1.28%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                     | 1         | 1.28%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.28%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 1         | 1.28%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.28%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.28%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.28%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.28%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.28%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.28%   |
| Accton EN-1216 Ethernet Adapter                                        | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 49.35%  |
| WiFi     | 70        | 45.45%  |
| Modem    | 7         | 4.55%   |
| Unknown  | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 57.95%  |
| Ethernet | 37        | 42.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 54.44%  |
| 1     | 33        | 36.67%  |
| 0     | 6         | 6.67%   |
| 3     | 2         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 78.89%  |
| Yes  | 19        | 21.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 30.56%  |
| Realtek Semiconductor           | 6         | 16.67%  |
| Qualcomm Atheros Communications | 6         | 16.67%  |
| Apple                           | 2         | 5.56%   |
| Alps Electric                   | 2         | 5.56%   |
| Toshiba                         | 1         | 2.78%   |
| MediaTek                        | 1         | 2.78%   |
| IMC Networks                    | 1         | 2.78%   |
| Hewlett-Packard                 | 1         | 2.78%   |
| Foxconn / Hon Hai               | 1         | 2.78%   |
| Dell                            | 1         | 2.78%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |
| Broadcom                        | 1         | 2.78%   |
| ASUSTek Computer                | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 11.11%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 11.11%  |
| Intel Bluetooth wireless interface                  | 4         | 11.11%  |
| Intel AX200 Bluetooth                               | 3         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.56%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 5.56%   |
| Toshiba Askey for                                   | 1         | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.78%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2.78%   |
| MediaTek Wireless_Device                            | 1         | 2.78%   |
| Intel Bluetooth Device                              | 1         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.78%   |
| Intel AX211 Bluetooth                               | 1         | 2.78%   |
| Intel AX210 Bluetooth                               | 1         | 2.78%   |
| IMC Networks Bluetooth Module                       | 1         | 2.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.78%   |
| Dell Wireless 360 Bluetooth                         | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.78%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.78%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.78%   |
| Apple Bluetooth Host Controller                     | 1         | 2.78%   |
| Apple Bluetooth HCI                                 | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 59        | 61.46%  |
| AMD                              | 21        | 21.88%  |
| Nvidia                           | 8         | 8.33%   |
| Silicon Integrated Systems [SiS] | 4         | 4.17%   |
| VIA Technologies                 | 1         | 1.04%   |
| Shenzhen Rapoo Technology        | 1         | 1.04%   |
| Logitech                         | 1         | 1.04%   |
| ESS Technology                   | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 7.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 6.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 2.59%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 3         | 2.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 2.59%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 3         | 2.59%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 2.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.59%   |
| Nvidia Audio device                                                                               | 2         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.72%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.72%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.86%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.86%   |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1         | 0.86%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.86%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 32        | 33.33%  |
| Samsung Electronics | 19        | 19.79%  |
| SK hynix            | 12        | 12.5%   |
| Kingston            | 7         | 7.29%   |
| Unknown (ABCD)      | 3         | 3.13%   |
| Elpida              | 3         | 3.13%   |
| A-DATA Technology   | 3         | 3.13%   |
| Team                | 2         | 2.08%   |
| Micron Technology   | 2         | 2.08%   |
| Crucial             | 2         | 2.08%   |
| Corsair             | 2         | 2.08%   |
| Unknown             | 2         | 2.08%   |
| Transcend           | 1         | 1.04%   |
| Toshiba             | 1         | 1.04%   |
| Teikon              | 1         | 1.04%   |
| S                   | 1         | 1.04%   |
| Ramaxel Technology  | 1         | 1.04%   |
| M                   | 1         | 1.04%   |
| G.Skill             | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 7         | 7%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 3%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3%      |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 2%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2%      |
| Unknown                                                          | 2         | 2%      |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1%      |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1%      |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1%      |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1%      |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1%      |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1%      |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1%      |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1%      |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1%      |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1%      |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1%      |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1%      |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1%      |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1%      |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1%      |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1%      |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1%      |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 1%      |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1%      |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 1%      |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 31.46%  |
| DDR4    | 17        | 19.1%   |
| DDR2    | 17        | 19.1%   |
| SDRAM   | 9         | 10.11%  |
| DDR     | 6         | 6.74%   |
| LPDDR4  | 3         | 3.37%   |
| Unknown | 3         | 3.37%   |
| LPDDR3  | 2         | 2.25%   |
| DRAM    | 2         | 2.25%   |
| DDR5    | 2         | 2.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 72.73%  |
| DIMM         | 20        | 22.73%  |
| Row Of Chips | 2         | 2.27%   |
| Unknown      | 2         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 29        | 30.85%  |
| 4096  | 23        | 24.47%  |
| 8192  | 16        | 17.02%  |
| 1024  | 13        | 13.83%  |
| 512   | 6         | 6.38%   |
| 32768 | 3         | 3.19%   |
| 16384 | 3         | 3.19%   |
| 256   | 1         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 20%     |
| 1600    | 13        | 14.44%  |
| 1333    | 7         | 7.78%   |
| 3200    | 6         | 6.67%   |
| 2667    | 5         | 5.56%   |
| 1334    | 5         | 5.56%   |
| 1067    | 5         | 5.56%   |
| 667     | 5         | 5.56%   |
| 2400    | 4         | 4.44%   |
| 266     | 3         | 3.33%   |
| 5600    | 2         | 2.22%   |
| 3600    | 2         | 2.22%   |
| 3266    | 2         | 2.22%   |
| 1867    | 2         | 2.22%   |
| 1066    | 2         | 2.22%   |
| 800     | 2         | 2.22%   |
| 533     | 2         | 2.22%   |
| 4199    | 1         | 1.11%   |
| 2666    | 1         | 1.11%   |
| 2133    | 1         | 1.11%   |
| 2048    | 1         | 1.11%   |
| 400     | 1         | 1.11%   |

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
| Chicony Electronics                    | 5         | 11.9%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 11.9%   |
| Bison Electronics                      | 5         | 11.9%   |
| Microdia                               | 4         | 9.52%   |
| IMC Networks                           | 4         | 9.52%   |
| Ricoh                                  | 3         | 7.14%   |
| Suyin                                  | 2         | 4.76%   |
| Realtek Semiconductor                  | 2         | 4.76%   |
| Logitech                               | 2         | 4.76%   |
| Alcor Micro                            | 2         | 4.76%   |
| USB Camera CS                          | 1         | 2.38%   |
| Silicon Motion                         | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Luxvisions Innotech Limited            | 1         | 2.38%   |
| KYE Systems (Mouse Systems)            | 1         | 2.38%   |
| eMPIA Technology                       | 1         | 2.38%   |
| Apple                                  | 1         | 2.38%   |
| ALi                                    | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 4.65%   |
| Bison Integrated Camera                                     | 2         | 4.65%   |
| USB Camera CS USB Camera CS                                 | 1         | 2.33%   |
| Suyin HD WebCam                                             | 1         | 2.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.33%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 2.33%   |
| Ricoh Webcam 1000                                           | 1         | 2.33%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 2.33%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 2.33%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 2.33%   |
| Realtek HP Wide Vision HD Camera                            | 1         | 2.33%   |
| Quanta Chromebook HD Camera                                 | 1         | 2.33%   |
| Microdia Webcam Vitade AF                                   | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 2.33%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 2.33%   |
| Logitech HD Webcam C615                                     | 1         | 2.33%   |
| Logitech HD Webcam C525                                     | 1         | 2.33%   |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam              | 1         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.33%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 2.33%   |
| IMC Networks Integrated Camera                              | 1         | 2.33%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 2.33%   |
| eMPIA Lenovo EasyCamera                                     | 1         | 2.33%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 2.33%   |
| Chicony Integrated Camera                                   | 1         | 2.33%   |
| Chicony HP Wide Vision HD Camera                            | 1         | 2.33%   |
| Chicony HP Webcam                                           | 1         | 2.33%   |
| Chicony HP HD Webcam                                        | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP IR Camera         | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 2.33%   |
| Bison HP Webcam-101                                         | 1         | 2.33%   |
| Bison HD Webcam                                             | 1         | 2.33%   |
| Bison EasyCamera                                            | 1         | 2.33%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.33%   |
| ALi M5603 Video Camera Controller                           | 1         | 2.33%   |
| Alcor Micro USB 2.0 PC Camera                               | 1         | 2.33%   |
| Alcor Micro USB 2.0 PC cam                                  | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| Synaptics                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 14.29%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 14.29%  |
| Synaptics UWP WBDI                                          | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                       | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                         | 1         | 14.29%  |

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
| 0     | 65        | 72.22%  |
| 1     | 17        | 18.89%  |
| 2     | 7         | 7.78%   |
| 4     | 1         | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 42.86%  |
| Fingerprint reader       | 7         | 20%     |
| Net/wireless             | 3         | 8.57%   |
| Flash memory             | 2         | 5.71%   |
| Communication controller | 2         | 5.71%   |
| Chipcard                 | 2         | 5.71%   |
| Camera                   | 2         | 5.71%   |
| Network                  | 1         | 2.86%   |
| Multimedia controller    | 1         | 2.86%   |

