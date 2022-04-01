NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 72

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [051ac4ce21](https://linux-hardware.org/?probe=051ac4ce21) | Jan 13, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 21.11                      | 12        | 21.43%  |
| NixOS 22.05                      | 9         | 16.07%  |
| NixOS                            | 5         | 8.93%   |
| NixOS 21.05pre-git               | 2         | 3.57%   |
| NixOS 20.09pre-git               | 2         | 3.57%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.79%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.79%   |
| NixOS 21.11.20210528.540dccb     | 1         | 1.79%   |
| NixOS 21.05.git.62d4591722f      | 1         | 1.79%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 1.79%   |
| NixOS 21.05.993.93963c27b93      | 1         | 1.79%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.79%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 1.79%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.79%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.79%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 1.79%   |
| NixOS 21.05.20210929.ee90403     | 1         | 1.79%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 1.79%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.79%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 1.79%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 1.79%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 1.79%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 1.79%   |
| NixOS 21.03.20201007.420f89c     | 1         | 1.79%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.79%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 1.79%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 1.79%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.79%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.79%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.79%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.26                | 3         | 5.26%   |
| 5.8.1-zen1             | 2         | 3.51%   |
| 5.16.8-zen1            | 2         | 3.51%   |
| 5.15.25                | 2         | 3.51%   |
| 5.13.7                 | 2         | 3.51%   |
| 5.13.2                 | 2         | 3.51%   |
| 5.12.15                | 2         | 3.51%   |
| 5.10.102               | 2         | 3.51%   |
| 5.8.4                  | 1         | 1.75%   |
| 5.8.16-hardened        | 1         | 1.75%   |
| 5.8.11                 | 1         | 1.75%   |
| 5.8.10                 | 1         | 1.75%   |
| 5.7.4                  | 1         | 1.75%   |
| 5.7.19                 | 1         | 1.75%   |
| 5.7.17                 | 1         | 1.75%   |
| 5.4.94                 | 1         | 1.75%   |
| 5.4.72                 | 1         | 1.75%   |
| 5.4.69                 | 1         | 1.75%   |
| 5.4.50                 | 1         | 1.75%   |
| 5.4.47                 | 1         | 1.75%   |
| 5.4.24                 | 1         | 1.75%   |
| 5.16.7                 | 1         | 1.75%   |
| 5.16.3                 | 1         | 1.75%   |
| 5.16.10                | 1         | 1.75%   |
| 5.15.7                 | 1         | 1.75%   |
| 5.15.4                 | 1         | 1.75%   |
| 5.15.3                 | 1         | 1.75%   |
| 5.15.22                | 1         | 1.75%   |
| 5.15.18                | 1         | 1.75%   |
| 5.15.12                | 1         | 1.75%   |
| 5.15.0                 | 1         | 1.75%   |
| 5.14.9                 | 1         | 1.75%   |
| 5.14.16-lqx1           | 1         | 1.75%   |
| 5.12.7                 | 1         | 1.75%   |
| 5.11.16-zen1           | 1         | 1.75%   |
| 5.11.16-xanmod1-cacule | 1         | 1.75%   |
| 5.10.99                | 1         | 1.75%   |
| 5.10.69                | 1         | 1.75%   |
| 5.10.66                | 1         | 1.75%   |
| 5.10.62                | 1         | 1.75%   |
| 5.10.57                | 1         | 1.75%   |
| 5.10.52                | 1         | 1.75%   |
| 5.10.43                | 1         | 1.75%   |
| 5.10.35                | 1         | 1.75%   |
| 5.10.30                | 1         | 1.75%   |
| 5.10.17                | 1         | 1.75%   |
| 4.19.57                | 1         | 1.75%   |
| 4.19.116               | 1         | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.26  | 3         | 5.26%   |
| 5.8.1    | 2         | 3.51%   |
| 5.16.8   | 2         | 3.51%   |
| 5.15.25  | 2         | 3.51%   |
| 5.13.7   | 2         | 3.51%   |
| 5.13.2   | 2         | 3.51%   |
| 5.12.15  | 2         | 3.51%   |
| 5.11.16  | 2         | 3.51%   |
| 5.10.102 | 2         | 3.51%   |
| 5.8.4    | 1         | 1.75%   |
| 5.8.16   | 1         | 1.75%   |
| 5.8.11   | 1         | 1.75%   |
| 5.8.10   | 1         | 1.75%   |
| 5.7.4    | 1         | 1.75%   |
| 5.7.19   | 1         | 1.75%   |
| 5.7.17   | 1         | 1.75%   |
| 5.4.94   | 1         | 1.75%   |
| 5.4.72   | 1         | 1.75%   |
| 5.4.69   | 1         | 1.75%   |
| 5.4.50   | 1         | 1.75%   |
| 5.4.47   | 1         | 1.75%   |
| 5.4.24   | 1         | 1.75%   |
| 5.16.7   | 1         | 1.75%   |
| 5.16.3   | 1         | 1.75%   |
| 5.16.10  | 1         | 1.75%   |
| 5.15.7   | 1         | 1.75%   |
| 5.15.4   | 1         | 1.75%   |
| 5.15.3   | 1         | 1.75%   |
| 5.15.22  | 1         | 1.75%   |
| 5.15.18  | 1         | 1.75%   |
| 5.15.12  | 1         | 1.75%   |
| 5.15.0   | 1         | 1.75%   |
| 5.14.9   | 1         | 1.75%   |
| 5.14.16  | 1         | 1.75%   |
| 5.12.7   | 1         | 1.75%   |
| 5.10.99  | 1         | 1.75%   |
| 5.10.69  | 1         | 1.75%   |
| 5.10.66  | 1         | 1.75%   |
| 5.10.62  | 1         | 1.75%   |
| 5.10.57  | 1         | 1.75%   |
| 5.10.52  | 1         | 1.75%   |
| 5.10.43  | 1         | 1.75%   |
| 5.10.35  | 1         | 1.75%   |
| 5.10.30  | 1         | 1.75%   |
| 5.10.17  | 1         | 1.75%   |
| 4.19.57  | 1         | 1.75%   |
| 4.19.116 | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 21.05%  |
| 5.10    | 12        | 21.05%  |
| 5.8     | 6         | 10.53%  |
| 5.4     | 6         | 10.53%  |
| 5.16    | 5         | 8.77%   |
| 5.13    | 4         | 7.02%   |
| 5.7     | 3         | 5.26%   |
| 5.12    | 3         | 5.26%   |
| 5.14    | 2         | 3.51%   |
| 5.11    | 2         | 3.51%   |
| 4.19    | 2         | 3.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 81.48%  |
| KDE     | 4         | 7.41%   |
| XFCE    | 2         | 3.7%    |
| sway    | 2         | 3.7%    |
| GNOME   | 2         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 77.78%  |
| X11     | 7         | 12.96%  |
| Wayland | 3         | 5.56%   |
| Tty     | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 92.59%  |
| SDDM    | 2         | 3.7%    |
| LightDM | 1         | 1.85%   |
| GDM     | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 66.67%  |
| en_US   | 12        | 22.22%  |
| ru_RU   | 2         | 3.7%    |
| en_GB   | 2         | 3.7%    |
| pt_BR   | 1         | 1.85%   |
| en_DK   | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 81.82%  |
| BIOS | 10        | 18.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 28        | 50.91%  |
| Btrfs   | 9         | 16.36%  |
| Tmpfs   | 8         | 14.55%  |
| Unknown | 5         | 9.09%   |
| Xfs     | 3         | 5.45%   |
| Zfs     | 1         | 1.82%   |
| Ext2    | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 50        | 92.59%  |
| Unknown | 4         | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 70.37%  |
| Yes       | 16        | 29.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 57.41%  |
| Yes       | 23        | 42.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 24.07%  |
| Lenovo              | 12        | 22.22%  |
| MSI                 | 7         | 12.96%  |
| Hewlett-Packard     | 5         | 9.26%   |
| Gigabyte Technology | 4         | 7.41%   |
| Dell                | 4         | 7.41%   |
| ASRock              | 3         | 5.56%   |
| Teclast             | 1         | 1.85%   |
| OBSIDIAN-PC         | 1         | 1.85%   |
| HARDKERNEL          | 1         | 1.85%   |
| GPD                 | 1         | 1.85%   |
| EVGA                | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 2         | 3.7%    |
| Teclast F5                            | 1         | 1.85%   |
| OBSIDIAN-PC N13_N140ZU                | 1         | 1.85%   |
| MSI MS-7C95                           | 1         | 1.85%   |
| MSI MS-7C84                           | 1         | 1.85%   |
| MSI MS-7B89                           | 1         | 1.85%   |
| MSI MS-7B09                           | 1         | 1.85%   |
| MSI Bravo 15 B5DD                     | 1         | 1.85%   |
| Lenovo Yoga 520-14IKB 81C8            | 1         | 1.85%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 1.85%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 1.85%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 1.85%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 1.85%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 1.85%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 1.85%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 1.85%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 1.85%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 1.85%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 1.85%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 1.85%   |
| HP ZBook Studio G5                    | 1         | 1.85%   |
| HP Spectre x360 Convertible 15-eb0xxx | 1         | 1.85%   |
| HP ProBook 445 G7                     | 1         | 1.85%   |
| HP EliteDesk 800 G2 DM 35W            | 1         | 1.85%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 1.85%   |
| HARDKERNEL ODROID-H2                  | 1         | 1.85%   |
| GPD MicroPC                           | 1         | 1.85%   |
| Gigabyte X570 AORUS ELITE             | 1         | 1.85%   |
| Gigabyte X470 AORUS ULTRA GAMING      | 1         | 1.85%   |
| Gigabyte Sabre 15                     | 1         | 1.85%   |
| Gigabyte H97M-D3H                     | 1         | 1.85%   |
| EVGA X299 FTW K                       | 1         | 1.85%   |
| Dell XPS 15 9550                      | 1         | 1.85%   |
| Dell Precision Tower 7810             | 1         | 1.85%   |
| Dell Latitude 7420                    | 1         | 1.85%   |
| Dell Inspiron 7391 2n1                | 1         | 1.85%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 1.85%   |
| ASUS Z170-P                           | 1         | 1.85%   |
| ASUS TUF GAMING X570-PLUS             | 1         | 1.85%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 1.85%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 1.85%   |
| ASUS ROG STRIX B550-I GAMING          | 1         | 1.85%   |
| ASUS ROG STRIX B550-F GAMING          | 1         | 1.85%   |
| ASUS PRO-Q77 IU                       | 1         | 1.85%   |
| ASUS Pro WS W480-ACE                  | 1         | 1.85%   |
| ASUS PRIME Z390-A                     | 1         | 1.85%   |
| ASUS PRIME Z270-K                     | 1         | 1.85%   |
| ASUS P8Z77-V LK                       | 1         | 1.85%   |
| ASUS All Series                       | 1         | 1.85%   |
| ASRock X570 Taichi                    | 1         | 1.85%   |
| ASRock TRX40 Creator                  | 1         | 1.85%   |
| ASRock B450 Gaming-ITX/ac             | 1         | 1.85%   |
| Acer Aspire E5-576G                   | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 10        | 18.52%  |
| ASUS ROG             | 4         | 7.41%   |
| MSI MS-7C37          | 2         | 3.7%    |
| ASUS PRIME           | 2         | 3.7%    |
| Teclast F5           | 1         | 1.85%   |
| OBSIDIAN-PC N13      | 1         | 1.85%   |
| MSI MS-7C95          | 1         | 1.85%   |
| MSI MS-7C84          | 1         | 1.85%   |
| MSI MS-7B89          | 1         | 1.85%   |
| MSI MS-7B09          | 1         | 1.85%   |
| MSI Bravo            | 1         | 1.85%   |
| Lenovo Yoga          | 1         | 1.85%   |
| Lenovo Legion        | 1         | 1.85%   |
| HP ZBook             | 1         | 1.85%   |
| HP Spectre           | 1         | 1.85%   |
| HP ProBook           | 1         | 1.85%   |
| HP EliteDesk         | 1         | 1.85%   |
| HP EliteBook         | 1         | 1.85%   |
| HARDKERNEL ODROID-H2 | 1         | 1.85%   |
| GPD MicroPC          | 1         | 1.85%   |
| Gigabyte X570        | 1         | 1.85%   |
| Gigabyte X470        | 1         | 1.85%   |
| Gigabyte Sabre       | 1         | 1.85%   |
| Gigabyte H97M-D3H    | 1         | 1.85%   |
| EVGA X299            | 1         | 1.85%   |
| Dell XPS             | 1         | 1.85%   |
| Dell Precision       | 1         | 1.85%   |
| Dell Latitude        | 1         | 1.85%   |
| Dell Inspiron        | 1         | 1.85%   |
| ASUS ZenBook         | 1         | 1.85%   |
| ASUS Z170-P          | 1         | 1.85%   |
| ASUS TUF             | 1         | 1.85%   |
| ASUS PRO-Q77         | 1         | 1.85%   |
| ASUS Pro             | 1         | 1.85%   |
| ASUS P8Z77-V         | 1         | 1.85%   |
| ASUS All             | 1         | 1.85%   |
| ASRock X570          | 1         | 1.85%   |
| ASRock TRX40         | 1         | 1.85%   |
| ASRock B450          | 1         | 1.85%   |
| Acer Aspire          | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 14        | 25.93%  |
| 2019 | 11        | 20.37%  |
| 2018 | 9         | 16.67%  |
| 2021 | 4         | 7.41%   |
| 2017 | 4         | 7.41%   |
| 2016 | 4         | 7.41%   |
| 2015 | 4         | 7.41%   |
| 2014 | 2         | 3.7%    |
| 2013 | 1         | 1.85%   |
| 2012 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 26        | 48.15%  |
| Notebook    | 24        | 44.44%  |
| Convertible | 4         | 7.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 17        | 31.48%  |
| 16.01-24.0  | 17        | 31.48%  |
| 64.01-256.0 | 10        | 18.52%  |
| 8.01-16.0   | 5         | 9.26%   |
| 4.01-8.0    | 4         | 7.41%   |
| 24.01-32.0  | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 28.57%  |
| 8.01-16.0  | 15        | 26.79%  |
| 3.01-4.0   | 8         | 14.29%  |
| 32.01-64.0 | 4         | 7.14%   |
| 2.01-3.0   | 4         | 7.14%   |
| 1.01-2.0   | 4         | 7.14%   |
| 24.01-32.0 | 3         | 5.36%   |
| 16.01-24.0 | 2         | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 43.64%  |
| 2      | 17        | 30.91%  |
| 3      | 6         | 10.91%  |
| 6      | 3         | 5.45%   |
| 5      | 2         | 3.64%   |
| 8      | 1         | 1.82%   |
| 4      | 1         | 1.82%   |
| 0      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 90.74%  |
| Yes       | 5         | 9.26%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 83.64%  |
| No        | 9         | 16.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 64.81%  |
| No        | 19        | 35.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 63.64%  |
| No        | 20        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 7         | 12.96%  |
| Poland      | 6         | 11.11%  |
| Ukraine     | 5         | 9.26%   |
| UK          | 5         | 9.26%   |
| Russia      | 5         | 9.26%   |
| USA         | 3         | 5.56%   |
| Canada      | 3         | 5.56%   |
| Austria     | 3         | 5.56%   |
| Netherlands | 2         | 3.7%    |
| France      | 2         | 3.7%    |
| Belgium     | 2         | 3.7%    |
| Uruguay     | 1         | 1.85%   |
| Switzerland | 1         | 1.85%   |
| Spain       | 1         | 1.85%   |
| Serbia      | 1         | 1.85%   |
| Portugal    | 1         | 1.85%   |
| New Zealand | 1         | 1.85%   |
| Hungary     | 1         | 1.85%   |
| Denmark     | 1         | 1.85%   |
| Czechia     | 1         | 1.85%   |
| Colombia    | 1         | 1.85%   |
| Brazil      | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Marki             | 4         | 7.02%   |
| Vienna            | 3         | 5.26%   |
| Kharkiv           | 3         | 5.26%   |
| London            | 2         | 3.51%   |
| Gdansk            | 2         | 3.51%   |
| Chelyabinsk       | 2         | 3.51%   |
| Bensheim          | 2         | 3.51%   |
| Wellington        | 1         | 1.75%   |
| Vernouillet       | 1         | 1.75%   |
| Valpacos          | 1         | 1.75%   |
| Tottenham         | 1         | 1.75%   |
| Srednyaya Akhtuba | 1         | 1.75%   |
| Southampton       | 1         | 1.75%   |
| Sindelfingen      | 1         | 1.75%   |
| Schaafheim        | 1         | 1.75%   |
| San Gabriel       | 1         | 1.75%   |
| Samara            | 1         | 1.75%   |
| Redwood City      | 1         | 1.75%   |
| Ramenskoye        | 1         | 1.75%   |
| QuÃ©bec         | 1         | 1.75%   |
| Osasco            | 1         | 1.75%   |
| Numansdorp        | 1         | 1.75%   |
| Mykolayiv         | 1         | 1.75%   |
| Montreal          | 1         | 1.75%   |
| Montevideo        | 1         | 1.75%   |
| Mons              | 1         | 1.75%   |
| Melsele           | 1         | 1.75%   |
| Melrose           | 1         | 1.75%   |
| Kuybyshev         | 1         | 1.75%   |
| Kiel              | 1         | 1.75%   |
| Karlsruhe         | 1         | 1.75%   |
| Irpin             | 1         | 1.75%   |
| Halifax           | 1         | 1.75%   |
| Getafe            | 1         | 1.75%   |
| Frankfurt am Main | 1         | 1.75%   |
| Esbjerg           | 1         | 1.75%   |
| Enschede          | 1         | 1.75%   |
| Elsenfeld         | 1         | 1.75%   |
| Dolni Dunajovice  | 1         | 1.75%   |
| Cergy             | 1         | 1.75%   |
| Cartagena         | 1         | 1.75%   |
| Budapest          | 1         | 1.75%   |
| Belgrade          | 1         | 1.75%   |
| Bedford           | 1         | 1.75%   |
| Arlesheim         | 1         | 1.75%   |
| Andover           | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 41     | 28.74%  |
| WDC                 | 7         | 14     | 8.05%   |
| Seagate             | 7         | 8      | 8.05%   |
| Kingston            | 7         | 7      | 8.05%   |
| Crucial             | 7         | 9      | 8.05%   |
| Intel               | 6         | 9      | 6.9%    |
| Toshiba             | 5         | 8      | 5.75%   |
| SanDisk             | 4         | 8      | 4.6%    |
| SK Hynix            | 3         | 4      | 3.45%   |
| Transcend           | 2         | 2      | 2.3%    |
| PLEXTOR             | 2         | 2      | 2.3%    |
| Micron Technology   | 2         | 2      | 2.3%    |
| HGST                | 2         | 4      | 2.3%    |
| Unknown             | 1         | 1      | 1.15%   |
| Teclast             | 1         | 1      | 1.15%   |
| Phison              | 1         | 1      | 1.15%   |
| Lexar               | 1         | 1      | 1.15%   |
| KIOXIA              | 1         | 1      | 1.15%   |
| INNOVATION IT       | 1         | 1      | 1.15%   |
| BIWIN               | 1         | 1      | 1.15%   |
| ASMT                | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 970 EVO 500GB            | 3         | 2.88%   |
| Samsung SSD 860 EVO 1TB              | 3         | 2.88%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 2.88%   |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 1.92%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 1.92%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.92%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.92%   |
| Samsung SSD 860 EVO 2TB              | 2         | 1.92%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 1.92%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.92%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.96%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.96%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.96%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.96%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.96%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.96%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.96%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.96%   |
| Unknown MMC Card  32GB               | 1         | 0.96%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 0.96%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 0.96%   |
| Toshiba TR150 960GB SSD              | 1         | 0.96%   |
| Toshiba KBG40ZNS512G NVMe 512GB      | 1         | 0.96%   |
| Toshiba HDWL120 2TB                  | 1         | 0.96%   |
| Toshiba HDWE160 6TB                  | 1         | 0.96%   |
| Toshiba HDWD120 2TB                  | 1         | 0.96%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.96%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB | 1         | 0.96%   |
| SK Hynix NVMe SSD Drive 1TB          | 1         | 0.96%   |
| SK Hynix NVMe SSD Drive 1024GB       | 1         | 0.96%   |
| SK Hynix HFM001TD3JX013N 1TB         | 1         | 0.96%   |
| Seagate ST3000VX010-2H916L 3TB       | 1         | 0.96%   |
| Seagate ST3000DM001-1CH166 3TB       | 1         | 0.96%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.96%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 0.96%   |
| SanDisk Ultra II 960GB SSD           | 1         | 0.96%   |
| SanDisk SSD PLUS 240GB               | 1         | 0.96%   |
| SanDisk SSD PLUS 240 GB              | 1         | 0.96%   |
| SanDisk SSD PLUS 120 GB              | 1         | 0.96%   |
| SanDisk SDSSDHII240G 240GB           | 1         | 0.96%   |
| SanDisk SDSSDA240G 240GB             | 1         | 0.96%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 0.96%   |
| Samsung SSD 980 PRO 1TB              | 1         | 0.96%   |
| Samsung SSD 970 PRO 512GB            | 1         | 0.96%   |
| Samsung SSD 970 EVO 1TB              | 1         | 0.96%   |
| Samsung SSD 960 EVO 1TB              | 1         | 0.96%   |
| Samsung SSD 870 EVO 500GB            | 1         | 0.96%   |
| Samsung SSD 860 EVO 500GB            | 1         | 0.96%   |
| Samsung SSD 850 EVO 250GB            | 1         | 0.96%   |
| Samsung SSD 850 EVO 120GB            | 1         | 0.96%   |
| Samsung SSD 840 EVO 250GB            | 1         | 0.96%   |
| Samsung Portable SSD T5 500GB        | 1         | 0.96%   |
| Samsung PM9A1 NVMe 1024GB            | 1         | 0.96%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 0.96%   |
| Samsung NVMe SSD Drive 500GB         | 1         | 0.96%   |
| Samsung NVMe SSD Drive 1TB           | 1         | 0.96%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 1         | 0.96%   |
| Samsung MZVLB512HAJQ-000H1 512GB     | 1         | 0.96%   |
| Samsung MZVLB512HAJQ-00000 512GB     | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 38.89%  |
| WDC     | 5         | 10     | 27.78%  |
| Toshiba | 3         | 6      | 16.67%  |
| HGST    | 2         | 4      | 11.11%  |
| ASMT    | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 28.21%  |
| Crucial             | 7         | 9      | 17.95%  |
| Kingston            | 5         | 5      | 12.82%  |
| Intel               | 4         | 6      | 10.26%  |
| SanDisk             | 3         | 6      | 7.69%   |
| Transcend           | 2         | 2      | 5.13%   |
| WDC                 | 1         | 2      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| Teclast             | 1         | 1      | 2.56%   |
| PLEXTOR             | 1         | 1      | 2.56%   |
| Micron Technology   | 1         | 1      | 2.56%   |
| INNOVATION IT       | 1         | 1      | 2.56%   |
| BIWIN               | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 44     | 41.25%  |
| SSD  | 32        | 52     | 40%     |
| HDD  | 14        | 29     | 17.5%   |
| MMC  | 1         | 1      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 79     | 49.3%   |
| NVMe | 33        | 44     | 46.48%  |
| SAS  | 2         | 2      | 2.82%   |
| MMC  | 1         | 1      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 33     | 43.4%   |
| 0.51-1.0   | 17        | 26     | 32.08%  |
| 1.01-2.0   | 6         | 9      | 11.32%  |
| 2.01-3.0   | 4         | 5      | 7.55%   |
| 4.01-10.0  | 2         | 6      | 3.77%   |
| 3.01-4.0   | 1         | 2      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 72.22%  |
| 1-20       | 5         | 9.26%   |
| 501-1000   | 4         | 7.41%   |
| 101-250    | 2         | 3.7%    |
| 1001-2000  | 2         | 3.7%    |
| 251-500    | 1         | 1.85%   |
| 2001-3000  | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| Unknown   | 39        | 72.22%  |
| 1-20      | 8         | 14.81%  |
| 101-250   | 3         | 5.56%   |
| 251-500   | 2         | 3.7%    |
| 1001-2000 | 1         | 1.85%   |
| 501-1000  | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SK Hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 20%     |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 20%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 20%     |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 20%     |
| ASMT 2115 1TB                                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK Hynix            | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Micron Technology   | 1         | 1      | 20%     |
| Intel               | 1         | 1      | 20%     |
| ASMT                | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| ASMT   | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 40%     |
| SSD  | 2         | 2      | 40%     |
| HDD  | 1         | 1      | 20%     |

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
| Works    | 48        | 109    | 81.36%  |
| Detected | 7         | 12     | 11.86%  |
| Malfunc  | 4         | 5      | 6.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 27        | 34.62%  |
| Samsung Electronics          | 17        | 21.79%  |
| AMD                          | 16        | 20.51%  |
| SK Hynix                     | 3         | 3.85%   |
| Sandisk                      | 3         | 3.85%   |
| Kingston Technology Company  | 3         | 3.85%   |
| KIOXIA                       | 2         | 2.56%   |
| ASMedia Technology           | 2         | 2.56%   |
| Shenzhen Longsys Electronics | 1         | 1.28%   |
| Phison Electronics           | 1         | 1.28%   |
| Micron Technology            | 1         | 1.28%   |
| LSI Logic / Symbios Logic    | 1         | 1.28%   |
| Lite-On Technology           | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 16.47%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 14.12%  |
| SK Hynix Gold P31 SSD                                                          | 3         | 3.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 3.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 3.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 3.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.35%   |
| KIOXIA Non-Volatile memory controller                                          | 2         | 2.35%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 2.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.35%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 2.35%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 1.18%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.18%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.18%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.18%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.18%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1         | 1.18%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.18%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.18%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.18%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1         | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.18%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 51.28%  |
| NVMe | 34        | 43.59%  |
| RAID | 2         | 2.56%   |
| SAS  | 1         | 1.28%   |
| IDE  | 1         | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 59.26%  |
| AMD    | 22        | 40.74%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz              | 3         | 5.56%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3         | 5.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 2         | 3.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz             | 2         | 3.7%    |
| Intel Celeron N4100 CPU @ 1.10GHz              | 2         | 3.7%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 2         | 3.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics         | 2         | 3.7%    |
| AMD Ryzen 7 3800X 8-Core Processor             | 2         | 3.7%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 2         | 3.7%    |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1         | 1.85%   |
| Intel Xeon E-2176M CPU @ 2.70GHz               | 1         | 1.85%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1         | 1.85%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1         | 1.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.85%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 1.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.85%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1         | 1.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 1         | 1.85%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1         | 1.85%   |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 1.85%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1         | 1.85%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1         | 1.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.85%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1         | 1.85%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.85%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 1         | 1.85%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.85%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1         | 1.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1         | 1.85%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 16        | 29.63%  |
| AMD Ryzen 7            | 9         | 16.67%  |
| Intel Core i5          | 6         | 11.11%  |
| AMD Ryzen 5            | 6         | 11.11%  |
| Intel Xeon             | 3         | 5.56%   |
| Intel Celeron          | 3         | 5.56%   |
| AMD Ryzen 7 PRO        | 3         | 5.56%   |
| Intel Core i3          | 2         | 3.7%    |
| AMD Ryzen Threadripper | 2         | 3.7%    |
| AMD Ryzen 9            | 2         | 3.7%    |
| Other                  | 1         | 1.85%   |
| Intel Core i9          | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 20        | 37.04%  |
| 8      | 12        | 22.22%  |
| 6      | 10        | 18.52%  |
| 2      | 5         | 9.26%   |
| 12     | 2         | 3.7%    |
| 10     | 2         | 3.7%    |
| 32     | 1         | 1.85%   |
| 24     | 1         | 1.85%   |
| 16     | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 98.15%  |
| 2      | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 47        | 87.04%  |
| 1      | 7         | 12.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 10.91%  |
| 0x08701021 | 5         | 9.09%   |
| 0x806ea    | 4         | 7.27%   |
| 0x806ec    | 3         | 5.45%   |
| 0x506e3    | 3         | 5.45%   |
| 0x0a50000c | 3         | 5.45%   |
| 0x08701013 | 3         | 5.45%   |
| 0x08600106 | 3         | 5.45%   |
| 0x906ea    | 2         | 3.64%   |
| 0x906e9    | 2         | 3.64%   |
| 0x806eb    | 2         | 3.64%   |
| 0x706a1    | 2         | 3.64%   |
| 0x306c3    | 2         | 3.64%   |
| 0x306a9    | 2         | 3.64%   |
| 0xa0652    | 1         | 1.82%   |
| 0x806c1    | 1         | 1.82%   |
| 0x406f1    | 1         | 1.82%   |
| 0x406e3    | 1         | 1.82%   |
| 0x306f2    | 1         | 1.82%   |
| 0x306d4    | 1         | 1.82%   |
| 0x0a50000b | 1         | 1.82%   |
| 0x0a201204 | 1         | 1.82%   |
| 0x0a201009 | 1         | 1.82%   |
| 0x08600104 | 1         | 1.82%   |
| 0x08301025 | 1         | 1.82%   |
| 0x0800820d | 1         | 1.82%   |
| 0x08001137 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Zen 2         | 14        | 25.93%  |
| KabyLake      | 13        | 24.07%  |
| Zen 3         | 6         | 11.11%  |
| Skylake       | 6         | 11.11%  |
| Haswell       | 3         | 5.56%   |
| Goldmont plus | 3         | 5.56%   |
| IvyBridge     | 2         | 3.7%    |
| CometLake     | 2         | 3.7%    |
| Broadwell     | 2         | 3.7%    |
| Zen+          | 1         | 1.85%   |
| Zen           | 1         | 1.85%   |
| TigerLake     | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 26        | 37.68%  |
| Intel  | 26        | 37.68%  |
| AMD    | 17        | 24.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5         | 7.14%   |
| Intel HD Graphics 530                                            | 4         | 5.71%   |
| AMD Renoir                                                       | 4         | 5.71%   |
| AMD Cezanne                                                      | 4         | 5.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                       | 3         | 4.29%   |
| Intel UHD Graphics 620                                           | 3         | 4.29%   |
| Intel GeminiLake [UHD Graphics 600]                              | 3         | 4.29%   |
| Nvidia GP108M [GeForce MX150]                                    | 2         | 2.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2         | 2.86%   |
| Nvidia GK104 [GeForce GTX 760]                                   | 2         | 2.86%   |
| Intel HD Graphics 630                                            | 2         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                             | 2         | 2.86%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2         | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2         | 2.86%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                       | 1         | 1.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                       | 1         | 1.43%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1         | 1.43%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1         | 1.43%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1         | 1.43%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1         | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 1.43%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                            | 1         | 1.43%   |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1         | 1.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1         | 1.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1         | 1.43%   |
| Nvidia GM206 [GeForce GTX 960]                                   | 1         | 1.43%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 1         | 1.43%   |
| Nvidia GM108M [GeForce 940MX]                                    | 1         | 1.43%   |
| Nvidia GM107M [GeForce GTX 960M]                                 | 1         | 1.43%   |
| Nvidia GK208M [GeForce GT 730M]                                  | 1         | 1.43%   |
| Nvidia GK107 [NVS 510]                                           | 1         | 1.43%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1         | 1.43%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                  | 1         | 1.43%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                  | 1         | 1.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1         | 1.43%   |
| Intel UHD P630 Graphics                                          | 1         | 1.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                        | 1         | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                              | 1         | 1.43%   |
| Intel HD Graphics 620                                            | 1         | 1.43%   |
| Intel HD Graphics 5500                                           | 1         | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                             | 1         | 1.43%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1         | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller      | 1         | 1.43%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                   | 1         | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 31.48%  |
| 1 x Nvidia     | 12        | 22.22%  |
| 1 x AMD        | 10        | 18.52%  |
| Intel + Nvidia | 8         | 14.81%  |
| AMD + Nvidia   | 6         | 11.11%  |
| 2 x AMD        | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 74.07%  |
| Proprietary | 13        | 24.07%  |
| Unknown     | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 63.64%  |
| 7.01-8.0   | 7         | 12.73%  |
| 0.01-0.5   | 7         | 12.73%  |
| 1.01-2.0   | 3         | 5.45%   |
| 3.01-4.0   | 2         | 3.64%   |
| 0.51-1.0   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 11        | 17.46%  |
| Goldstar             | 8         | 12.7%   |
| Chimei Innolux       | 5         | 7.94%   |
| AU Optronics         | 5         | 7.94%   |
| Samsung Electronics  | 4         | 6.35%   |
| LG Display           | 4         | 6.35%   |
| PANDA                | 3         | 4.76%   |
| BOE                  | 3         | 4.76%   |
| Acer                 | 3         | 4.76%   |
| AOC                  | 2         | 3.17%   |
| Ancor Communications | 2         | 3.17%   |
| Unknown (AAA)        | 1         | 1.59%   |
| Sharp                | 1         | 1.59%   |
| Panasonic            | 1         | 1.59%   |
| MPI                  | 1         | 1.59%   |
| Lenovo               | 1         | 1.59%   |
| JDI                  | 1         | 1.59%   |
| InfoVision           | 1         | 1.59%   |
| Iiyama               | 1         | 1.59%   |
| HVR                  | 1         | 1.59%   |
| Hewlett-Packard      | 1         | 1.59%   |
| Eizo                 | 1         | 1.59%   |
| BenQ                 | 1         | 1.59%   |
| ASUSTek Computer     | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 2         | 3.08%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 3.08%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 3.08%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 3.08%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 1.54%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.54%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1         | 1.54%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 1.54%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.54%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.54%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 1.54%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.54%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 1         | 1.54%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1         | 1.54%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.54%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.54%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.54%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.54%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1         | 1.54%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1         | 1.54%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.54%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1         | 1.54%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1         | 1.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.54%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 1.54%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 1         | 1.54%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1         | 1.54%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.54%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1         | 1.54%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1         | 1.54%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.54%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1         | 1.54%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1         | 1.54%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.54%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 1         | 1.54%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1384 1920x1080 293x165mm 13.2-inch      | 1         | 1.54%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| BOE LCD Monitor BOE08D8 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                 | 1         | 1.54%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch        | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch        | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 1         | 1.54%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 1         | 1.54%   |
| AOC 2770 AOC2770 1920x1080 598x336mm 27.0-inch                        | 1         | 1.54%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1         | 1.54%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1         | 1.54%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 1         | 1.54%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 28        | 47.46%  |
| 3840x2160 (4K)   | 14        | 23.73%  |
| 2560x1440 (QHD)  | 8         | 13.56%  |
| 2560x1080        | 4         | 6.78%   |
| 1280x1024 (SXGA) | 2         | 3.39%   |
| 3440x1440        | 1         | 1.69%   |
| 2160x1200        | 1         | 1.69%   |
| 1280x720 (HD)    | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 12        | 19.35%  |
| 15      | 8         | 12.9%   |
| 14      | 8         | 12.9%   |
| 23      | 6         | 9.68%   |
| 34      | 5         | 8.06%   |
| 13      | 5         | 8.06%   |
| 24      | 4         | 6.45%   |
| 17      | 4         | 6.45%   |
| 31      | 2         | 3.23%   |
| 21      | 2         | 3.23%   |
| 12      | 2         | 3.23%   |
| 25      | 1         | 1.61%   |
| 11      | 1         | 1.61%   |
| 8       | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 20        | 33.9%   |
| 301-350     | 19        | 32.2%   |
| 201-300     | 6         | 10.17%  |
| 701-800     | 5         | 8.47%   |
| 601-700     | 3         | 5.08%   |
| 401-500     | 2         | 3.39%   |
| 351-400     | 2         | 3.39%   |
| 101-200     | 1         | 1.69%   |
| Unknown     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 80%     |
| 21/9  | 5         | 10%     |
| 5/4   | 2         | 4%      |
| 16/10 | 2         | 4%      |
| 4/3   | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 12        | 19.05%  |
| 81-90          | 10        | 15.87%  |
| 201-250        | 10        | 15.87%  |
| 101-110        | 8         | 12.7%   |
| 351-500        | 7         | 11.11%  |
| 71-80          | 3         | 4.76%   |
| 61-70          | 2         | 3.17%   |
| 251-300        | 2         | 3.17%   |
| 151-200        | 2         | 3.17%   |
| 141-150        | 2         | 3.17%   |
| 121-130        | 2         | 3.17%   |
| 51-60          | 1         | 1.59%   |
| 1-40           | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 29.31%  |
| 161-240       | 15        | 25.86%  |
| 121-160       | 15        | 25.86%  |
| 101-120       | 6         | 10.34%  |
| More than 240 | 4         | 6.9%    |
| Unknown       | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 56.36%  |
| 2     | 13        | 23.64%  |
| 0     | 8         | 14.55%  |
| 3     | 3         | 5.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 41        | 48.81%  |
| Realtek Semiconductor             | 32        | 38.1%   |
| Qualcomm Atheros                  | 2         | 2.38%   |
| Microsoft                         | 2         | 2.38%   |
| Aquantia                          | 2         | 2.38%   |
| TP-Link                           | 1         | 1.19%   |
| Texas Instruments                 | 1         | 1.19%   |
| Oculus VR                         | 1         | 1.19%   |
| FIBOCOM                           | 1         | 1.19%   |
| Ericsson Business Mobile Networks | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 22.45%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 11.22%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 5         | 5.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 3.06%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 2.04%   |
| Intel Wireless-AC 9260                                            | 2         | 2.04%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.04%   |
| Intel Wireless 8260                                               | 2         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.02%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.02%   |
| Oculus VR Rift S                                                  | 1         | 1.02%   |
| Intel Wireless 7265                                               | 1         | 1.02%   |
| Intel Wireless 7260                                               | 1         | 1.02%   |
| Intel Wireless 3165                                               | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.02%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.02%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.02%   |
| FIBOCOM L830-EB                                                   | 1         | 1.02%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 1.02%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.02%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 30        | 78.95%  |
| Realtek Semiconductor             | 2         | 5.26%   |
| Microsoft                         | 2         | 5.26%   |
| TP-Link                           | 1         | 2.63%   |
| Qualcomm Atheros                  | 1         | 2.63%   |
| FIBOCOM                           | 1         | 2.63%   |
| Ericsson Business Mobile Networks | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 11        | 28.95%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3         | 7.89%   |
| Microsoft Xbox 360 Wireless Adapter                        | 2         | 5.26%   |
| Intel Wireless-AC 9260                                     | 2         | 5.26%   |
| Intel Wireless 8265 / 8275                                 | 2         | 5.26%   |
| Intel Wireless 8260                                        | 2         | 5.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 5.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 5.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.63%   |
| Intel Wireless 7265                                        | 1         | 2.63%   |
| Intel Wireless 7260                                        | 1         | 2.63%   |
| Intel Wireless 3165                                        | 1         | 2.63%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.63%   |
| FIBOCOM L830-EB                                            | 1         | 2.63%   |
| Ericsson Business Mobile Networks N5321 gw                 | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 54.55%  |
| Intel                 | 22        | 40%     |
| Aquantia              | 2         | 3.64%   |
| Qualcomm Atheros      | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 37.93%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 12.07%  |
| Intel I211 Gigabit Network Connection                             | 5         | 8.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.17%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.45%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.72%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.72%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 55.42%  |
| WiFi     | 35        | 42.17%  |
| Modem    | 2         | 2.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 53.13%  |
| WiFi     | 30        | 46.88%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 48.15%  |
| 2     | 25        | 46.3%   |
| 3     | 2         | 3.7%    |
| 0     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 77.78%  |
| Yes  | 12        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 75%     |
| ASUSTek Computer                | 3         | 8.33%   |
| Realtek Semiconductor           | 2         | 5.56%   |
| Cambridge Silicon Radio         | 2         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 2.78%   |
| HTC (High Tech Computer)        | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 9         | 25%     |
| Intel Bluetooth wireless interface                  | 6         | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 8.33%   |
| Intel AX201 Bluetooth                               | 3         | 8.33%   |
| Realtek Bluetooth Radio                             | 2         | 5.56%   |
| Intel Bluetooth Device                              | 2         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 5.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.78%   |
| HTC (High Tech Computer) BCM920703 Bluetooth 4.1    | 1         | 2.78%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 32        | 35.16%  |
| AMD                                  | 23        | 25.27%  |
| Nvidia                               | 19        | 20.88%  |
| C-Media Electronics                  | 2         | 2.2%    |
| Unknown                              | 1         | 1.1%    |
| Trust                                | 1         | 1.1%    |
| Thomann                              | 1         | 1.1%    |
| Thesycon Systemsoftware & Consulting | 1         | 1.1%    |
| Texas Instruments                    | 1         | 1.1%    |
| Sony                                 | 1         | 1.1%    |
| Sennheiser Communications            | 1         | 1.1%    |
| Realtek Semiconductor                | 1         | 1.1%    |
| PreSonus Audio Electronics           | 1         | 1.1%    |
| Lenovo                               | 1         | 1.1%    |
| Kingston Technology                  | 1         | 1.1%    |
| GYROCOM C&C                          | 1         | 1.1%    |
| Creative Technology                  | 1         | 1.1%    |
| Creative Labs                        | 1         | 1.1%    |
| Corsair                              | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 12        | 11.01%  |
| AMD Family 17h/19h HD Audio Controller                              | 8         | 7.34%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 7         | 6.42%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 5.5%    |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 4.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 4         | 3.67%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3         | 2.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 2.75%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 3         | 2.75%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.83%   |
| Nvidia TU106 High Definition Audio Controller                       | 2         | 1.83%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 1.83%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 1.83%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 1.83%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 1.83%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 1.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 1.83%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 1.83%   |
| C-Media Electronics USB Advanced Audio Device                       | 2         | 1.83%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2         | 1.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 2         | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2         | 1.83%   |
| Unknown USB Audio                                                   | 1         | 0.92%   |
| Trust USB microphone                                                | 1         | 0.92%   |
| Thomann SC450USB                                                    | 1         | 0.92%   |
| Thesycon Systemsoftware & Consulting D30 Pro                        | 1         | 0.92%   |
| Texas Instruments PCM2902 Audio Codec                               | 1         | 0.92%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 0.92%   |
| Sennheiser Communications Headset [PC 8]                            | 1         | 0.92%   |
| Realtek Semiconductor USB Audio                                     | 1         | 0.92%   |
| PreSonus Audio Electronics AudioBox                                 | 1         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 0.92%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 0.92%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 0.92%   |
| Nvidia GM204 High Definition Audio Controller                       | 1         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 0.92%   |
| Nvidia Audio device                                                 | 1         | 0.92%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                        | 1         | 0.92%   |
| Kingston Technology HyperX 7.1 Audio                                | 1         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 0.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 0.92%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.92%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1         | 0.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 0.92%   |
| GYROCOM C&C Fiio E10                                                | 1         | 0.92%   |
| Creative Technology Sound BlasterX G1                               | 1         | 0.92%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]          | 1         | 0.92%   |
| Corsair HS70 Pro Wireless Gaming Headset                            | 1         | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 24.14%  |
| Kingston            | 9         | 15.52%  |
| Micron Technology   | 8         | 13.79%  |
| Corsair             | 8         | 13.79%  |
| G.Skill             | 5         | 8.62%   |
| Crucial             | 5         | 8.62%   |
| Unknown (ABCD)      | 3         | 5.17%   |
| GOODRAM             | 2         | 3.45%   |
| Unknown             | 1         | 1.72%   |
| Strontium           | 1         | 1.72%   |
| Avant               | 1         | 1.72%   |
| AMD                 | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 3.08%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 3.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 3.08%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s           | 2         | 3.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 2         | 3.08%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s              | 2         | 3.08%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                 | 2         | 3.08%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s              | 2         | 3.08%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                       | 1         | 1.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 1.54%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                  | 1         | 1.54%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 1.54%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.54%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.54%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.54%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 1.54%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.54%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 1.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.54%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.54%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s                | 1         | 1.54%   |
| Samsung RAM K4EBE3 4EC-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.54%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.54%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 1         | 1.54%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.54%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s                | 1         | 1.54%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 1         | 1.54%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.54%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s                | 1         | 1.54%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                | 1         | 1.54%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s              | 1         | 1.54%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s                 | 1         | 1.54%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.54%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s               | 1         | 1.54%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.54%   |
| GOODRAM RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.54%   |
| GOODRAM RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s               | 1         | 1.54%   |
| GOODRAM RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s                 | 1         | 1.54%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                 | 1         | 1.54%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.54%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1333MT/s                   | 1         | 1.54%   |
| Crucial RAM CT16G4SFD824A.C16FBD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.54%   |
| Crucial RAM CT16G4SFD8213.M16FB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.54%   |
| Crucial RAM BLS4G3D1609DS1S00. 4096MB DIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s            | 1         | 1.54%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s         | 1         | 1.54%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s               | 1         | 1.54%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s               | 1         | 1.54%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 1.54%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s           | 1         | 1.54%   |
| Corsair RAM CMK16GX4M2D3600C18 8192MB DIMM DDR4 3600MT/s            | 1         | 1.54%   |
| Corsair RAM CMD64GX4M4A2666C15 16384MB DIMM DDR4 2133MT/s           | 1         | 1.54%   |
| Avant RAM J642GU42J2320NQ 16384MB SODIMM DDR4 3200MT/s              | 1         | 1.54%   |
| AMD RAM R9432G3206S2S 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 76.47%  |
| DDR3   | 6         | 11.76%  |
| LPDDR4 | 4         | 7.84%   |
| LPDDR3 | 2         | 3.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 46.15%  |
| DIMM         | 23        | 44.23%  |
| Row Of Chips | 3         | 5.77%   |
| RIMM         | 1         | 1.92%   |
| Chip         | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 23        | 41.82%  |
| 8192  | 20        | 36.36%  |
| 32768 | 7         | 12.73%  |
| 4096  | 5         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 18        | 32.14%  |
| 2133  | 8         | 14.29%  |
| 2400  | 6         | 10.71%  |
| 1600  | 6         | 10.71%  |
| 2667  | 5         | 8.93%   |
| 3600  | 3         | 5.36%   |
| 3334  | 2         | 3.57%   |
| 4267  | 1         | 1.79%   |
| 3733  | 1         | 1.79%   |
| 3533  | 1         | 1.79%   |
| 3466  | 1         | 1.79%   |
| 3400  | 1         | 1.79%   |
| 3266  | 1         | 1.79%   |
| 2933  | 1         | 1.79%   |
| 1333  | 1         | 1.79%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 25%     |
| Logitech                      | 5         | 15.63%  |
| Acer                          | 4         | 12.5%   |
| Microdia                      | 3         | 9.38%   |
| Realtek Semiconductor         | 2         | 6.25%   |
| Quanta                        | 2         | 6.25%   |
| MacroSilicon                  | 2         | 6.25%   |
| IMC Networks                  | 2         | 6.25%   |
| SunplusIT                     | 1         | 3.13%   |
| Sunplus Innovation Technology | 1         | 3.13%   |
| Lite-On Technology            | 1         | 3.13%   |
| Apple                         | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Chicony Integrated Camera         | 5         | 15.15%  |
| MacroSilicon MiraBox Capture      | 2         | 6.06%   |
| Chicony HP HD Camera              | 2         | 6.06%   |
| Acer Integrated Camera            | 2         | 6.06%   |
| SunplusIT MTD camera              | 1         | 3.03%   |
| Sunplus Integrated_Webcam_FHD     | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD      | 1         | 3.03%   |
| Realtek EasyCamera                | 1         | 3.03%   |
| Quanta HP True Vision HD Camera   | 1         | 3.03%   |
| Quanta HD WebCam                  | 1         | 3.03%   |
| Microdia USB 2.0 Camera           | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD     | 1         | 3.03%   |
| Microdia Camera                   | 1         | 3.03%   |
| Logitech Webcam C930e             | 1         | 3.03%   |
| Logitech Webcam C310              | 1         | 3.03%   |
| Logitech Webcam C270              | 1         | 3.03%   |
| Logitech HD Pro Webcam C920       | 1         | 3.03%   |
| Logitech C930c                    | 1         | 3.03%   |
| Lite-On HP HD Camera              | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 3.03%   |
| IMC Networks Integrated Camera    | 1         | 3.03%   |
| Chicony USB2.0 Camera             | 1         | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE         | 1         | 3.03%   |
| Acer SunplusIT Integrated Camera  | 1         | 3.03%   |
| Acer Integrated IR Camera         | 1         | 3.03%   |
| Acer HD Webcam                    | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 66.67%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 33.33%  |
| Unknown                                           | 2         | 22.22%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 7         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 31        | 57.41%  |
| 1     | 13        | 24.07%  |
| 2     | 9         | 16.67%  |
| 4     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 23.53%  |
| Fingerprint reader    | 8         | 23.53%  |
| Chipcard              | 6         | 17.65%  |
| Multimedia controller | 4         | 11.76%  |
| Unassigned class      | 3         | 8.82%   |
| Net/wireless          | 2         | 5.88%   |
| Camera                | 2         | 5.88%   |
| Network               | 1         | 2.94%   |

