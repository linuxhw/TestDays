NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 83

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 21.11                      | 18        | 27.27%  |
| NixOS 22.05                      | 13        | 19.7%   |
| NixOS                            | 5         | 7.58%   |
| NixOS 21.05pre-git               | 2         | 3.03%   |
| NixOS 20.09pre-git               | 2         | 3.03%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.52%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.52%   |
| NixOS 21.11.20210528.540dccb     | 1         | 1.52%   |
| NixOS 21.05.git.62d4591722f      | 1         | 1.52%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 1.52%   |
| NixOS 21.05.993.93963c27b93      | 1         | 1.52%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.52%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 1.52%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.52%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.52%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 1.52%   |
| NixOS 21.05.20210929.ee90403     | 1         | 1.52%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 1.52%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.52%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 1.52%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 1.52%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 1.52%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 1.52%   |
| NixOS 21.03.20201007.420f89c     | 1         | 1.52%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.52%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 1.52%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 1.52%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.52%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.52%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.52%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 64        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.26                | 3         | 4.48%   |
| 5.8.1-zen1             | 2         | 2.99%   |
| 5.17.1                 | 2         | 2.99%   |
| 5.16.8-zen1            | 2         | 2.99%   |
| 5.16.15                | 2         | 2.99%   |
| 5.15.25                | 2         | 2.99%   |
| 5.13.7                 | 2         | 2.99%   |
| 5.13.2                 | 2         | 2.99%   |
| 5.12.15                | 2         | 2.99%   |
| 5.10.102               | 2         | 2.99%   |
| 5.8.4                  | 1         | 1.49%   |
| 5.8.16-hardened        | 1         | 1.49%   |
| 5.8.11                 | 1         | 1.49%   |
| 5.8.10                 | 1         | 1.49%   |
| 5.7.4                  | 1         | 1.49%   |
| 5.7.19                 | 1         | 1.49%   |
| 5.7.17                 | 1         | 1.49%   |
| 5.4.94                 | 1         | 1.49%   |
| 5.4.72                 | 1         | 1.49%   |
| 5.4.69                 | 1         | 1.49%   |
| 5.4.50                 | 1         | 1.49%   |
| 5.4.47                 | 1         | 1.49%   |
| 5.4.24                 | 1         | 1.49%   |
| 5.4.187                | 1         | 1.49%   |
| 5.17.0                 | 1         | 1.49%   |
| 5.16.7                 | 1         | 1.49%   |
| 5.16.3                 | 1         | 1.49%   |
| 5.16.14                | 1         | 1.49%   |
| 5.16.10                | 1         | 1.49%   |
| 5.15.7                 | 1         | 1.49%   |
| 5.15.4                 | 1         | 1.49%   |
| 5.15.32                | 1         | 1.49%   |
| 5.15.3                 | 1         | 1.49%   |
| 5.15.22                | 1         | 1.49%   |
| 5.15.18                | 1         | 1.49%   |
| 5.15.12                | 1         | 1.49%   |
| 5.15.0                 | 1         | 1.49%   |
| 5.14.9                 | 1         | 1.49%   |
| 5.14.16-lqx1           | 1         | 1.49%   |
| 5.12.7                 | 1         | 1.49%   |
| 5.11.16-zen1           | 1         | 1.49%   |
| 5.11.16-xanmod1-cacule | 1         | 1.49%   |
| 5.10.99                | 1         | 1.49%   |
| 5.10.96                | 1         | 1.49%   |
| 5.10.69                | 1         | 1.49%   |
| 5.10.66                | 1         | 1.49%   |
| 5.10.62                | 1         | 1.49%   |
| 5.10.57                | 1         | 1.49%   |
| 5.10.52                | 1         | 1.49%   |
| 5.10.43                | 1         | 1.49%   |
| 5.10.35                | 1         | 1.49%   |
| 5.10.30                | 1         | 1.49%   |
| 5.10.17                | 1         | 1.49%   |
| 5.10.109               | 1         | 1.49%   |
| 4.19.57                | 1         | 1.49%   |
| 4.19.116               | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.26  | 3         | 4.48%   |
| 5.8.1    | 2         | 2.99%   |
| 5.17.1   | 2         | 2.99%   |
| 5.16.8   | 2         | 2.99%   |
| 5.16.15  | 2         | 2.99%   |
| 5.15.25  | 2         | 2.99%   |
| 5.13.7   | 2         | 2.99%   |
| 5.13.2   | 2         | 2.99%   |
| 5.12.15  | 2         | 2.99%   |
| 5.11.16  | 2         | 2.99%   |
| 5.10.102 | 2         | 2.99%   |
| 5.8.4    | 1         | 1.49%   |
| 5.8.16   | 1         | 1.49%   |
| 5.8.11   | 1         | 1.49%   |
| 5.8.10   | 1         | 1.49%   |
| 5.7.4    | 1         | 1.49%   |
| 5.7.19   | 1         | 1.49%   |
| 5.7.17   | 1         | 1.49%   |
| 5.4.94   | 1         | 1.49%   |
| 5.4.72   | 1         | 1.49%   |
| 5.4.69   | 1         | 1.49%   |
| 5.4.50   | 1         | 1.49%   |
| 5.4.47   | 1         | 1.49%   |
| 5.4.24   | 1         | 1.49%   |
| 5.4.187  | 1         | 1.49%   |
| 5.17.0   | 1         | 1.49%   |
| 5.16.7   | 1         | 1.49%   |
| 5.16.3   | 1         | 1.49%   |
| 5.16.14  | 1         | 1.49%   |
| 5.16.10  | 1         | 1.49%   |
| 5.15.7   | 1         | 1.49%   |
| 5.15.4   | 1         | 1.49%   |
| 5.15.32  | 1         | 1.49%   |
| 5.15.3   | 1         | 1.49%   |
| 5.15.22  | 1         | 1.49%   |
| 5.15.18  | 1         | 1.49%   |
| 5.15.12  | 1         | 1.49%   |
| 5.15.0   | 1         | 1.49%   |
| 5.14.9   | 1         | 1.49%   |
| 5.14.16  | 1         | 1.49%   |
| 5.12.7   | 1         | 1.49%   |
| 5.10.99  | 1         | 1.49%   |
| 5.10.96  | 1         | 1.49%   |
| 5.10.69  | 1         | 1.49%   |
| 5.10.66  | 1         | 1.49%   |
| 5.10.62  | 1         | 1.49%   |
| 5.10.57  | 1         | 1.49%   |
| 5.10.52  | 1         | 1.49%   |
| 5.10.43  | 1         | 1.49%   |
| 5.10.35  | 1         | 1.49%   |
| 5.10.30  | 1         | 1.49%   |
| 5.10.17  | 1         | 1.49%   |
| 5.10.109 | 1         | 1.49%   |
| 4.19.57  | 1         | 1.49%   |
| 4.19.116 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 14        | 20.9%   |
| 5.15    | 13        | 19.4%   |
| 5.16    | 8         | 11.94%  |
| 5.4     | 7         | 10.45%  |
| 5.8     | 6         | 8.96%   |
| 5.13    | 4         | 5.97%   |
| 5.7     | 3         | 4.48%   |
| 5.17    | 3         | 4.48%   |
| 5.12    | 3         | 4.48%   |
| 5.14    | 2         | 2.99%   |
| 5.11    | 2         | 2.99%   |
| 4.19    | 2         | 2.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 51        | 79.69%  |
| KDE         | 4         | 6.25%   |
| sway        | 3         | 4.69%   |
| GNOME       | 3         | 4.69%   |
| XFCE        | 2         | 3.13%   |
| none+xmonad | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 49        | 76.56%  |
| X11     | 8         | 12.5%   |
| Wayland | 5         | 7.81%   |
| Tty     | 2         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 90.63%  |
| SDDM    | 2         | 3.13%   |
| LightDM | 2         | 3.13%   |
| GDM     | 2         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 65.63%  |
| en_US   | 14        | 21.88%  |
| ru_RU   | 2         | 3.13%   |
| en_GB   | 2         | 3.13%   |
| en_DK   | 2         | 3.13%   |
| ro_RO   | 1         | 1.56%   |
| pt_BR   | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 53        | 81.54%  |
| BIOS | 12        | 18.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 34        | 52.31%  |
| Tmpfs   | 9         | 13.85%  |
| Btrfs   | 9         | 13.85%  |
| Unknown | 6         | 9.23%   |
| Xfs     | 4         | 6.15%   |
| Zfs     | 2         | 3.08%   |
| Ext2    | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 60        | 93.75%  |
| Unknown | 4         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 71.88%  |
| Yes       | 18        | 28.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 59.38%  |
| Yes       | 26        | 40.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 23.44%  |
| ASUSTek Computer    | 15        | 23.44%  |
| MSI                 | 7         | 10.94%  |
| Hewlett-Packard     | 6         | 9.38%   |
| Gigabyte Technology | 4         | 6.25%   |
| Dell                | 4         | 6.25%   |
| ASRock              | 3         | 4.69%   |
| Acer                | 2         | 3.13%   |
| Teclast             | 1         | 1.56%   |
| Supermicro          | 1         | 1.56%   |
| OBSIDIAN-PC         | 1         | 1.56%   |
| HARDKERNEL          | 1         | 1.56%   |
| GPD                 | 1         | 1.56%   |
| Framework           | 1         | 1.56%   |
| EVGA                | 1         | 1.56%   |
| Apple               | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 2         | 3.13%   |
| Teclast F5                            | 1         | 1.56%   |
| Supermicro X8DT6                      | 1         | 1.56%   |
| OBSIDIAN-PC N13_N140ZU                | 1         | 1.56%   |
| MSI MS-7C95                           | 1         | 1.56%   |
| MSI MS-7C84                           | 1         | 1.56%   |
| MSI MS-7B89                           | 1         | 1.56%   |
| MSI MS-7B09                           | 1         | 1.56%   |
| MSI Bravo 15 B5DD                     | 1         | 1.56%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 1.56%   |
| Lenovo Yoga 520-14IKB 81C8            | 1         | 1.56%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 1.56%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 1.56%   |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 1.56%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 1.56%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 1.56%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 1.56%   |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 1.56%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 1.56%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 1.56%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 1.56%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 1.56%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 1.56%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 1.56%   |
| HP ZBook Studio G5                    | 1         | 1.56%   |
| HP Spectre x360 Convertible 15-eb0xxx | 1         | 1.56%   |
| HP ProBook 450 G4                     | 1         | 1.56%   |
| HP ProBook 445 G7                     | 1         | 1.56%   |
| HP EliteDesk 800 G2 DM 35W            | 1         | 1.56%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 1.56%   |
| HARDKERNEL ODROID-H2                  | 1         | 1.56%   |
| GPD MicroPC                           | 1         | 1.56%   |
| Gigabyte X570 AORUS ELITE             | 1         | 1.56%   |
| Gigabyte X470 AORUS ULTRA GAMING      | 1         | 1.56%   |
| Gigabyte Sabre 15                     | 1         | 1.56%   |
| Gigabyte H97M-D3H                     | 1         | 1.56%   |
| Framework Laptop                      | 1         | 1.56%   |
| EVGA X299 FTW K                       | 1         | 1.56%   |
| Dell XPS 15 9550                      | 1         | 1.56%   |
| Dell Precision Tower 7810             | 1         | 1.56%   |
| Dell Latitude 7420                    | 1         | 1.56%   |
| Dell Inspiron 7391 2n1                | 1         | 1.56%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 1.56%   |
| ASUS Z170-P                           | 1         | 1.56%   |
| ASUS TUF GAMING X570-PLUS             | 1         | 1.56%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 1.56%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 1.56%   |
| ASUS ROG STRIX B550-I GAMING          | 1         | 1.56%   |
| ASUS ROG STRIX B550-F GAMING          | 1         | 1.56%   |
| ASUS ROG Flow X13 GV301QE_GV301QE     | 1         | 1.56%   |
| ASUS PRO-Q77 IU                       | 1         | 1.56%   |
| ASUS Pro WS W480-ACE                  | 1         | 1.56%   |
| ASUS PRIME Z390-A                     | 1         | 1.56%   |
| ASUS PRIME Z270-K                     | 1         | 1.56%   |
| ASUS PRIME X570-P                     | 1         | 1.56%   |
| ASUS P8Z77-V LK                       | 1         | 1.56%   |
| ASUS All Series                       | 1         | 1.56%   |
| ASRock X570 Taichi                    | 1         | 1.56%   |
| ASRock TRX40 Creator                  | 1         | 1.56%   |
| ASRock B450 Gaming-ITX/ac             | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 12        | 18.75%  |
| ASUS ROG             | 5         | 7.81%   |
| ASUS PRIME           | 3         | 4.69%   |
| MSI MS-7C37          | 2         | 3.13%   |
| Lenovo Yoga          | 2         | 3.13%   |
| HP ProBook           | 2         | 3.13%   |
| Teclast F5           | 1         | 1.56%   |
| Supermicro X8DT6     | 1         | 1.56%   |
| OBSIDIAN-PC N13      | 1         | 1.56%   |
| MSI MS-7C95          | 1         | 1.56%   |
| MSI MS-7C84          | 1         | 1.56%   |
| MSI MS-7B89          | 1         | 1.56%   |
| MSI MS-7B09          | 1         | 1.56%   |
| MSI Bravo            | 1         | 1.56%   |
| Lenovo Legion        | 1         | 1.56%   |
| HP ZBook             | 1         | 1.56%   |
| HP Spectre           | 1         | 1.56%   |
| HP EliteDesk         | 1         | 1.56%   |
| HP EliteBook         | 1         | 1.56%   |
| HARDKERNEL ODROID-H2 | 1         | 1.56%   |
| GPD MicroPC          | 1         | 1.56%   |
| Gigabyte X570        | 1         | 1.56%   |
| Gigabyte X470        | 1         | 1.56%   |
| Gigabyte Sabre       | 1         | 1.56%   |
| Gigabyte H97M-D3H    | 1         | 1.56%   |
| Framework Laptop     | 1         | 1.56%   |
| EVGA X299            | 1         | 1.56%   |
| Dell XPS             | 1         | 1.56%   |
| Dell Precision       | 1         | 1.56%   |
| Dell Latitude        | 1         | 1.56%   |
| Dell Inspiron        | 1         | 1.56%   |
| ASUS ZenBook         | 1         | 1.56%   |
| ASUS Z170-P          | 1         | 1.56%   |
| ASUS TUF             | 1         | 1.56%   |
| ASUS PRO-Q77         | 1         | 1.56%   |
| ASUS Pro             | 1         | 1.56%   |
| ASUS P8Z77-V         | 1         | 1.56%   |
| ASUS All             | 1         | 1.56%   |
| ASRock X570          | 1         | 1.56%   |
| ASRock TRX40         | 1         | 1.56%   |
| ASRock B450          | 1         | 1.56%   |
| Apple MacBookPro11   | 1         | 1.56%   |
| Acer Nitro           | 1         | 1.56%   |
| Acer Aspire          | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 15        | 23.44%  |
| 2019 | 13        | 20.31%  |
| 2018 | 9         | 14.06%  |
| 2021 | 7         | 10.94%  |
| 2016 | 7         | 10.94%  |
| 2017 | 4         | 6.25%   |
| 2015 | 4         | 6.25%   |
| 2014 | 2         | 3.13%   |
| 2013 | 1         | 1.56%   |
| 2012 | 1         | 1.56%   |
| 2010 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 31        | 48.44%  |
| Desktop     | 28        | 43.75%  |
| Convertible | 4         | 6.25%   |
| Server      | 1         | 1.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 64        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 19        | 29.69%  |
| 16.01-24.0  | 18        | 28.13%  |
| 64.01-256.0 | 12        | 18.75%  |
| 8.01-16.0   | 8         | 12.5%   |
| 4.01-8.0    | 5         | 7.81%   |
| 24.01-32.0  | 2         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 30.3%   |
| 8.01-16.0   | 17        | 25.76%  |
| 3.01-4.0    | 8         | 12.12%  |
| 32.01-64.0  | 5         | 7.58%   |
| 1.01-2.0    | 5         | 7.58%   |
| 2.01-3.0    | 4         | 6.06%   |
| 24.01-32.0  | 3         | 4.55%   |
| 16.01-24.0  | 3         | 4.55%   |
| 64.01-256.0 | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 46.15%  |
| 2      | 19        | 29.23%  |
| 3      | 7         | 10.77%  |
| 6      | 3         | 4.62%   |
| 5      | 2         | 3.08%   |
| 11     | 1         | 1.54%   |
| 8      | 1         | 1.54%   |
| 4      | 1         | 1.54%   |
| 0      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 90.63%  |
| Yes       | 6         | 9.38%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 81.54%  |
| No        | 12        | 18.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 67.19%  |
| No        | 21        | 32.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 64.62%  |
| No        | 23        | 35.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 8         | 12.5%   |
| Poland      | 7         | 10.94%  |
| USA         | 6         | 9.38%   |
| UK          | 6         | 9.38%   |
| Ukraine     | 5         | 7.81%   |
| Russia      | 5         | 7.81%   |
| Canada      | 4         | 6.25%   |
| Austria     | 3         | 4.69%   |
| Netherlands | 2         | 3.13%   |
| France      | 2         | 3.13%   |
| Belgium     | 2         | 3.13%   |
| Uruguay     | 1         | 1.56%   |
| Switzerland | 1         | 1.56%   |
| Sweden      | 1         | 1.56%   |
| Spain       | 1         | 1.56%   |
| Serbia      | 1         | 1.56%   |
| Romania     | 1         | 1.56%   |
| Portugal    | 1         | 1.56%   |
| New Zealand | 1         | 1.56%   |
| Iran        | 1         | 1.56%   |
| Hungary     | 1         | 1.56%   |
| Denmark     | 1         | 1.56%   |
| Czechia     | 1         | 1.56%   |
| Colombia    | 1         | 1.56%   |
| Brazil      | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Marki             | 4         | 5.97%   |
| Vienna            | 3         | 4.48%   |
| Kharkiv           | 3         | 4.48%   |
| Richardson        | 2         | 2.99%   |
| London            | 2         | 2.99%   |
| Gdansk            | 2         | 2.99%   |
| Chelyabinsk       | 2         | 2.99%   |
| Bensheim          | 2         | 2.99%   |
| Woodford          | 1         | 1.49%   |
| Wellington        | 1         | 1.49%   |
| Vernouillet       | 1         | 1.49%   |
| Valpacos          | 1         | 1.49%   |
| Tottenham         | 1         | 1.49%   |
| Tehran            | 1         | 1.49%   |
| Stockholm         | 1         | 1.49%   |
| Srednyaya Akhtuba | 1         | 1.49%   |
| Southampton       | 1         | 1.49%   |
| South Deerfield   | 1         | 1.49%   |
| Sindelfingen      | 1         | 1.49%   |
| Schaafheim        | 1         | 1.49%   |
| San Gabriel       | 1         | 1.49%   |
| Samara            | 1         | 1.49%   |
| Redwood City      | 1         | 1.49%   |
| Ramenskoye        | 1         | 1.49%   |
| QuÃ©bec         | 1         | 1.49%   |
| Osasco            | 1         | 1.49%   |
| Oakville          | 1         | 1.49%   |
| Numansdorp        | 1         | 1.49%   |
| Mykolayiv         | 1         | 1.49%   |
| Montreal          | 1         | 1.49%   |
| Montevideo        | 1         | 1.49%   |
| Mons              | 1         | 1.49%   |
| Melsele           | 1         | 1.49%   |
| Melrose           | 1         | 1.49%   |
| Lehrte            | 1         | 1.49%   |
| Kuybyshev         | 1         | 1.49%   |
| Krakow            | 1         | 1.49%   |
| Kiel              | 1         | 1.49%   |
| Karlsruhe         | 1         | 1.49%   |
| Irpin             | 1         | 1.49%   |
| Halifax           | 1         | 1.49%   |
| Getafe            | 1         | 1.49%   |
| Frankfurt am Main | 1         | 1.49%   |
| Esbjerg           | 1         | 1.49%   |
| Enschede          | 1         | 1.49%   |
| Elsenfeld         | 1         | 1.49%   |
| Dolni Dunajovice  | 1         | 1.49%   |
| Cluj-Napoca       | 1         | 1.49%   |
| Cergy             | 1         | 1.49%   |
| Cartagena         | 1         | 1.49%   |
| Budapest          | 1         | 1.49%   |
| Belgrade          | 1         | 1.49%   |
| Bedford           | 1         | 1.49%   |
| Arlesheim         | 1         | 1.49%   |
| Andover           | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 46     | 26.47%  |
| WDC                 | 12        | 24     | 11.76%  |
| Seagate             | 8         | 9      | 7.84%   |
| Crucial             | 8         | 10     | 7.84%   |
| Toshiba             | 7         | 10     | 6.86%   |
| Kingston            | 7         | 7      | 6.86%   |
| Intel               | 7         | 10     | 6.86%   |
| Sandisk             | 4         | 8      | 3.92%   |
| SK Hynix            | 3         | 4      | 2.94%   |
| Transcend           | 2         | 2      | 1.96%   |
| PLEXTOR             | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 2      | 1.96%   |
| HGST                | 2         | 4      | 1.96%   |
| Unknown             | 1         | 1      | 0.98%   |
| Teclast             | 1         | 1      | 0.98%   |
| Phison Electronics  | 1         | 2      | 0.98%   |
| Phison              | 1         | 1      | 0.98%   |
| Lexar               | 1         | 1      | 0.98%   |
| KIOXIA              | 1         | 1      | 0.98%   |
| INNOVATION IT       | 1         | 1      | 0.98%   |
| China               | 1         | 1      | 0.98%   |
| BIWIN               | 1         | 1      | 0.98%   |
| ASMT                | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 970 EVO 500GB            | 3         | 2.52%   |
| Samsung SSD 860 EVO 1TB              | 3         | 2.52%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 2.52%   |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 1.68%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 1.68%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.68%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.68%   |
| Samsung SSD 860 EVO 2TB              | 2         | 1.68%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 1.68%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.68%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.84%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.84%   |
| WDC WDS200T1X0E-00AFY0 2TB           | 1         | 0.84%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.84%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.84%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.84%   |
| WDC WD120EMFZ-11A6JA0 12TB           | 1         | 0.84%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1         | 0.84%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.84%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.84%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.84%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.84%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 0.84%   |
| Unknown MMC Card  32GB               | 1         | 0.84%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 0.84%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 0.84%   |
| Toshiba TR150 960GB SSD              | 1         | 0.84%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.84%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.84%   |
| Toshiba KBG40ZNS512G NVMe 512GB      | 1         | 0.84%   |
| Toshiba HDWL120 2TB                  | 1         | 0.84%   |
| Toshiba HDWE160 6TB                  | 1         | 0.84%   |
| Toshiba HDWD120 2TB                  | 1         | 0.84%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.84%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB | 1         | 0.84%   |
| SK Hynix NVMe SSD Drive 1TB          | 1         | 0.84%   |
| SK Hynix NVMe SSD Drive 1024GB       | 1         | 0.84%   |
| SK Hynix HFM001TD3JX013N 1TB         | 1         | 0.84%   |
| Seagate ST3000VX010-2H916L 3TB       | 1         | 0.84%   |
| Seagate ST3000DM001-1CH166 3TB       | 1         | 0.84%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 0.84%   |
| Seagate Backup+ Hub BK 4TB           | 1         | 0.84%   |
| SanDisk Ultra II 960GB SSD           | 1         | 0.84%   |
| SanDisk SSD PLUS 240GB               | 1         | 0.84%   |
| SanDisk SSD PLUS 240 GB              | 1         | 0.84%   |
| SanDisk SSD PLUS 120 GB              | 1         | 0.84%   |
| SanDisk SDSSDHII240G 240GB           | 1         | 0.84%   |
| SanDisk SDSSDA240G 240GB             | 1         | 0.84%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 0.84%   |
| Samsung SSD 980 PRO 1TB              | 1         | 0.84%   |
| Samsung SSD 970 PRO 512GB            | 1         | 0.84%   |
| Samsung SSD 970 EVO 1TB              | 1         | 0.84%   |
| Samsung SSD 960 EVO 1TB              | 1         | 0.84%   |
| Samsung SSD 870 EVO 500GB            | 1         | 0.84%   |
| Samsung SSD 870 EVO 1TB              | 1         | 0.84%   |
| Samsung SSD 860 EVO 500GB            | 1         | 0.84%   |
| Samsung SSD 850 EVO 250GB            | 1         | 0.84%   |
| Samsung SSD 850 EVO 120GB            | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 36.36%  |
| WDC     | 7         | 17     | 31.82%  |
| Toshiba | 4         | 7      | 18.18%  |
| HGST    | 2         | 4      | 9.09%   |
| ASMT    | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 20     | 26.67%  |
| Crucial             | 8         | 10     | 17.78%  |
| Kingston            | 5         | 5      | 11.11%  |
| Intel               | 5         | 7      | 11.11%  |
| SanDisk             | 3         | 6      | 6.67%   |
| WDC                 | 2         | 3      | 4.44%   |
| Transcend           | 2         | 2      | 4.44%   |
| Toshiba             | 1         | 1      | 2.22%   |
| Teclast             | 1         | 1      | 2.22%   |
| PLEXTOR             | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| INNOVATION IT       | 1         | 1      | 2.22%   |
| China               | 1         | 1      | 2.22%   |
| BIWIN               | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 38        | 50     | 40.86%  |
| SSD  | 37        | 61     | 39.78%  |
| HDD  | 17        | 38     | 18.28%  |
| MMC  | 1         | 1      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 96     | 49.4%   |
| NVMe | 38        | 50     | 45.78%  |
| SAS  | 3         | 3      | 3.61%   |
| MMC  | 1         | 1      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 37     | 43.75%  |
| 0.51-1.0   | 21        | 33     | 32.81%  |
| 1.01-2.0   | 6         | 9      | 9.38%   |
| 2.01-3.0   | 4         | 5      | 6.25%   |
| 3.01-4.0   | 2         | 3      | 3.13%   |
| 4.01-10.0  | 2         | 6      | 3.13%   |
| 10.01-20.0 | 1         | 6      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 45        | 70.31%  |
| 1-20           | 7         | 10.94%  |
| 501-1000       | 4         | 6.25%   |
| More than 3000 | 2         | 3.13%   |
| 101-250        | 2         | 3.13%   |
| 1001-2000      | 2         | 3.13%   |
| 251-500        | 1         | 1.56%   |
| 2001-3000      | 1         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 45        | 70.31%  |
| 1-20           | 10        | 15.63%  |
| 101-250        | 3         | 4.69%   |
| 251-500        | 2         | 3.13%   |
| 1001-2000      | 2         | 3.13%   |
| More than 3000 | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 16.67%  |
| SK Hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 16.67%  |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 16.67%  |
| ASMT 2115 1TB                                  | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 16.67%  |
| SK Hynix            | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |
| ASMT                | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| ASMT    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 33.33%  |
| SSD  | 2         | 2      | 33.33%  |
| HDD  | 2         | 2      | 33.33%  |

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
| Works    | 58        | 131    | 81.69%  |
| Detected | 8         | 13     | 11.27%  |
| Malfunc  | 5         | 6      | 7.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 34.44%  |
| Samsung Electronics          | 19        | 21.11%  |
| AMD                          | 17        | 18.89%  |
| Sandisk                      | 5         | 5.56%   |
| SK Hynix                     | 3         | 3.33%   |
| Kingston Technology Company  | 3         | 3.33%   |
| Phison Electronics           | 2         | 2.22%   |
| KIOXIA                       | 2         | 2.22%   |
| ASMedia Technology           | 2         | 2.22%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| Shenzhen Longsys Electronics | 1         | 1.11%   |
| Micron Technology            | 1         | 1.11%   |
| LSI Logic / Symbios Logic    | 1         | 1.11%   |
| Lite-On Technology           | 1         | 1.11%   |
| Broadcom / LSI               | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 15.31%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 13.27%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 4.08%   |
| SK Hynix Gold P31 SSD                                                          | 3         | 3.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 3.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 3.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 3.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.04%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.04%   |
| KIOXIA Non-Volatile memory controller                                          | 2         | 2.04%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.04%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 2.04%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 2.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.02%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 1.02%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.02%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.02%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.02%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.02%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.02%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.02%   |
| Samsung Electronics SATA controller                                            | 1         | 1.02%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.02%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1         | 1.02%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 1.02%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.02%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.02%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.02%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1         | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.02%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.02%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.02%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 1         | 1.02%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 48.89%  |
| NVMe | 39        | 43.33%  |
| RAID | 3         | 3.33%   |
| SAS  | 2         | 2.22%   |
| IDE  | 2         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 60.94%  |
| AMD    | 25        | 39.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz              | 3         | 4.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 3         | 4.69%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 3         | 4.69%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3         | 4.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 2         | 3.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 3.13%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 2         | 3.13%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 2         | 3.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 2         | 3.13%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2         | 3.13%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1         | 1.56%   |
| Intel Xeon E-2176M CPU @ 2.70GHz               | 1         | 1.56%   |
| Intel Xeon CPU L5640 @ 2.27GHz                 | 1         | 1.56%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1         | 1.56%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1         | 1.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1         | 1.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 1.56%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1         | 1.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 1.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 1.56%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 1         | 1.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.56%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1         | 1.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.56%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1         | 1.56%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1         | 1.56%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1         | 1.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 1.56%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1         | 1.56%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1         | 1.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.56%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1         | 1.56%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.56%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 1.56%   |
| AMD Ryzen 9 5900HS with Radeon Graphics        | 1         | 1.56%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.56%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 1         | 1.56%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 1         | 1.56%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 1         | 1.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.56%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1         | 1.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1         | 1.56%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 19        | 29.69%  |
| AMD Ryzen 7            | 11        | 17.19%  |
| Intel Core i5          | 8         | 12.5%   |
| AMD Ryzen 5            | 6         | 9.38%   |
| Intel Xeon             | 4         | 6.25%   |
| Intel Celeron          | 3         | 4.69%   |
| AMD Ryzen 9            | 3         | 4.69%   |
| AMD Ryzen 7 PRO        | 3         | 4.69%   |
| Other                  | 2         | 3.13%   |
| Intel Core i3          | 2         | 3.13%   |
| AMD Ryzen Threadripper | 2         | 3.13%   |
| Intel Core i9          | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 35.94%  |
| 8      | 15        | 23.44%  |
| 6      | 11        | 17.19%  |
| 2      | 7         | 10.94%  |
| 12     | 3         | 4.69%   |
| 10     | 2         | 3.13%   |
| 32     | 1         | 1.56%   |
| 24     | 1         | 1.56%   |
| 16     | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 96.88%  |
| 2      | 2         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 89.06%  |
| 1      | 7         | 10.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 15.38%  |
| 0x0a50000c | 5         | 7.69%   |
| 0x08701021 | 5         | 7.69%   |
| 0x806ea    | 4         | 6.15%   |
| 0x08701013 | 4         | 6.15%   |
| 0x806ec    | 3         | 4.62%   |
| 0x506e3    | 3         | 4.62%   |
| 0x08600106 | 3         | 4.62%   |
| 0x906ea    | 2         | 3.08%   |
| 0x906e9    | 2         | 3.08%   |
| 0x806eb    | 2         | 3.08%   |
| 0x706a1    | 2         | 3.08%   |
| 0x406e3    | 2         | 3.08%   |
| 0x306c3    | 2         | 3.08%   |
| 0x306a9    | 2         | 3.08%   |
| 0xa0653    | 1         | 1.54%   |
| 0xa0652    | 1         | 1.54%   |
| 0x806e9    | 1         | 1.54%   |
| 0x806c1    | 1         | 1.54%   |
| 0x406f1    | 1         | 1.54%   |
| 0x306f2    | 1         | 1.54%   |
| 0x306d4    | 1         | 1.54%   |
| 0x0a50000b | 1         | 1.54%   |
| 0x0a201204 | 1         | 1.54%   |
| 0x0a201009 | 1         | 1.54%   |
| 0x08600104 | 1         | 1.54%   |
| 0x08301025 | 1         | 1.54%   |
| 0x0800820d | 1         | 1.54%   |
| 0x08001137 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Zen 2         | 15        | 23.44%  |
| KabyLake      | 15        | 23.44%  |
| Zen 3         | 8         | 12.5%   |
| Skylake       | 7         | 10.94%  |
| Haswell       | 4         | 6.25%   |
| Goldmont plus | 3         | 4.69%   |
| CometLake     | 3         | 4.69%   |
| TigerLake     | 2         | 3.13%   |
| IvyBridge     | 2         | 3.13%   |
| Broadwell     | 2         | 3.13%   |
| Zen+          | 1         | 1.56%   |
| Zen           | 1         | 1.56%   |
| Westmere      | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 30        | 37.04%  |
| Intel                      | 30        | 37.04%  |
| AMD                        | 20        | 24.69%  |
| Matrox Electronics Systems | 1         | 1.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                      | 6         | 7.32%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5         | 6.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                       | 4         | 4.88%   |
| Intel HD Graphics 530                                            | 4         | 4.88%   |
| AMD Renoir                                                       | 4         | 4.88%   |
| Intel UHD Graphics 620                                           | 3         | 3.66%   |
| Intel GeminiLake [UHD Graphics 600]                              | 3         | 3.66%   |
| Nvidia GP108M [GeForce MX150]                                    | 2         | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2         | 2.44%   |
| Nvidia GK104 [GeForce GTX 760]                                   | 2         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                        | 2         | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                              | 2         | 2.44%   |
| Intel HD Graphics 630                                            | 2         | 2.44%   |
| Intel HD Graphics 620                                            | 2         | 2.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                             | 2         | 2.44%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2         | 2.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                       | 1         | 1.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                       | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1         | 1.22%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1         | 1.22%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1         | 1.22%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                            | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 1.22%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                            | 1         | 1.22%   |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1         | 1.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1         | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1         | 1.22%   |
| Nvidia GM206 [GeForce GTX 960]                                   | 1         | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 1         | 1.22%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                | 1         | 1.22%   |
| Nvidia GM108M [GeForce 940MX]                                    | 1         | 1.22%   |
| Nvidia GM108M [GeForce 930MX]                                    | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 960M]                                 | 1         | 1.22%   |
| Nvidia GK208M [GeForce GT 730M]                                  | 1         | 1.22%   |
| Nvidia GK107 [NVS 510]                                           | 1         | 1.22%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1         | 1.22%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                       | 1         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                  | 1         | 1.22%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                  | 1         | 1.22%   |
| Matrox Electronics Systems MGA G200eW WPCM450                    | 1         | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1         | 1.22%   |
| Intel UHD P630 Graphics                                          | 1         | 1.22%   |
| Intel HD Graphics 5500                                           | 1         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                             | 1         | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller      | 1         | 1.22%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                  | 1         | 1.22%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                   | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 31.25%  |
| 1 x Nvidia     | 14        | 21.88%  |
| 1 x AMD        | 12        | 18.75%  |
| Intel + Nvidia | 9         | 14.06%  |
| AMD + Nvidia   | 7         | 10.94%  |
| 2 x AMD        | 1         | 1.56%   |
| 1 x Matrox     | 1         | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 73.44%  |
| Proprietary | 16        | 25%     |
| Unknown     | 1         | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 63.08%  |
| 0.01-0.5   | 8         | 12.31%  |
| 7.01-8.0   | 7         | 10.77%  |
| 1.01-2.0   | 5         | 7.69%   |
| 3.01-4.0   | 3         | 4.62%   |
| 0.51-1.0   | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 12        | 16.9%   |
| Goldstar             | 8         | 11.27%  |
| LG Display           | 6         | 8.45%   |
| Chimei Innolux       | 5         | 7.04%   |
| AU Optronics         | 5         | 7.04%   |
| Samsung Electronics  | 4         | 5.63%   |
| PANDA                | 4         | 5.63%   |
| BOE                  | 4         | 5.63%   |
| Acer                 | 3         | 4.23%   |
| Sharp                | 2         | 2.82%   |
| InfoVision           | 2         | 2.82%   |
| AOC                  | 2         | 2.82%   |
| Ancor Communications | 2         | 2.82%   |
| Unknown (AAA)        | 1         | 1.41%   |
| Panasonic            | 1         | 1.41%   |
| MPI                  | 1         | 1.41%   |
| Lenovo               | 1         | 1.41%   |
| JDI                  | 1         | 1.41%   |
| Iiyama               | 1         | 1.41%   |
| HVR                  | 1         | 1.41%   |
| Hewlett-Packard      | 1         | 1.41%   |
| Eizo                 | 1         | 1.41%   |
| BenQ                 | 1         | 1.41%   |
| ASUSTek Computer     | 1         | 1.41%   |
| Apple                | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 2         | 2.74%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 2.74%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 2.74%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 2.74%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 1.37%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 1.37%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.37%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.37%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.37%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 1.37%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.37%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.37%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.37%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1         | 1.37%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.37%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.37%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.37%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 1.37%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1         | 1.37%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1         | 1.37%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 1         | 1.37%   |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch               | 1         | 1.37%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.37%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1         | 1.37%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.37%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1         | 1.37%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1         | 1.37%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.37%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1         | 1.37%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1         | 1.37%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.37%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                     | 1         | 1.37%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 1         | 1.37%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1384 1920x1080 293x165mm 13.2-inch      | 1         | 1.37%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.37%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch                 | 1         | 1.37%   |
| BOE LCD Monitor BOE08D8 1920x1080 344x194mm 15.5-inch                 | 1         | 1.37%   |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                 | 1         | 1.37%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch        | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch        | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 29        | 43.28%  |
| 3840x2160 (4K)    | 14        | 20.9%   |
| 2560x1440 (QHD)   | 8         | 11.94%  |
| 2560x1080         | 4         | 5.97%   |
| 1366x768 (WXGA)   | 2         | 2.99%   |
| 1280x1024 (SXGA)  | 2         | 2.99%   |
| 3440x1440         | 1         | 1.49%   |
| 2880x1800         | 1         | 1.49%   |
| 2560x1600         | 1         | 1.49%   |
| 2256x1504         | 1         | 1.49%   |
| 2160x1200         | 1         | 1.49%   |
| 1920x1200 (WUXGA) | 1         | 1.49%   |
| 1440x900 (WXGA+)  | 1         | 1.49%   |
| 1280x720 (HD)     | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 12        | 17.14%  |
| 15      | 10        | 14.29%  |
| 14      | 9         | 12.86%  |
| 13      | 8         | 11.43%  |
| 23      | 6         | 8.57%   |
| 34      | 5         | 7.14%   |
| 17      | 5         | 7.14%   |
| 24      | 4         | 5.71%   |
| 12      | 3         | 4.29%   |
| 31      | 2         | 2.86%   |
| 21      | 2         | 2.86%   |
| 25      | 1         | 1.43%   |
| 11      | 1         | 1.43%   |
| 8       | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 32.84%  |
| 501-600     | 20        | 29.85%  |
| 201-300     | 10        | 14.93%  |
| 701-800     | 5         | 7.46%   |
| 601-700     | 3         | 4.48%   |
| 351-400     | 3         | 4.48%   |
| 401-500     | 2         | 2.99%   |
| 101-200     | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 74.14%  |
| 16/10 | 6         | 10.34%  |
| 21/9  | 5         | 8.62%   |
| 5/4   | 2         | 3.45%   |
| 4/3   | 1         | 1.72%   |
| 3/2   | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 16.9%   |
| 301-350        | 12        | 16.9%   |
| 201-250        | 10        | 14.08%  |
| 101-110        | 10        | 14.08%  |
| 351-500        | 7         | 9.86%   |
| 71-80          | 5         | 7.04%   |
| 61-70          | 3         | 4.23%   |
| 251-300        | 2         | 2.82%   |
| 151-200        | 2         | 2.82%   |
| 141-150        | 2         | 2.82%   |
| 121-130        | 2         | 2.82%   |
| 51-60          | 1         | 1.41%   |
| 1-40           | 1         | 1.41%   |
| 131-140        | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 19        | 28.79%  |
| 51-100        | 18        | 27.27%  |
| 121-160       | 17        | 25.76%  |
| 101-120       | 7         | 10.61%  |
| More than 240 | 4         | 6.06%   |
| Unknown       | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 61.54%  |
| 2     | 13        | 20%     |
| 0     | 9         | 13.85%  |
| 3     | 3         | 4.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 49        | 50.52%  |
| Realtek Semiconductor             | 36        | 37.11%  |
| Qualcomm Atheros                  | 2         | 2.06%   |
| Microsoft                         | 2         | 2.06%   |
| Aquantia                          | 2         | 2.06%   |
| TP-Link                           | 1         | 1.03%   |
| Texas Instruments                 | 1         | 1.03%   |
| Oculus VR                         | 1         | 1.03%   |
| Fibocom                           | 1         | 1.03%   |
| Ericsson Business Mobile Networks | 1         | 1.03%   |
| Broadcom                          | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 22.12%  |
| Intel Wi-Fi 6 AX200                                               | 13        | 11.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 7.08%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.65%   |
| Intel Wireless 8260                                               | 3         | 2.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.65%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.77%   |
| Intel Wireless-AC 9260                                            | 2         | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.77%   |
| Intel Wireless 7265                                               | 2         | 1.77%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.77%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.77%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.88%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Oculus VR Rift S                                                  | 1         | 0.88%   |
| Intel Wireless 7260                                               | 1         | 0.88%   |
| Intel Wireless 3165                                               | 1         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.88%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.88%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.88%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.88%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 0.88%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 0.88%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.88%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 82.22%  |
| Realtek Semiconductor | 2         | 4.44%   |
| Microsoft             | 2         | 4.44%   |
| TP-Link               | 1         | 2.22%   |
| Qualcomm Atheros      | 1         | 2.22%   |
| Fibocom               | 1         | 2.22%   |
| Broadcom              | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 13        | 28.89%  |
| Intel Wireless 8260                                        | 3         | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3         | 6.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 3         | 6.67%   |
| Microsoft Xbox 360 Wireless Adapter                        | 2         | 4.44%   |
| Intel Wireless-AC 9260                                     | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                 | 2         | 4.44%   |
| Intel Wireless 7265                                        | 2         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 4.44%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 4.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.22%   |
| Intel Wireless 7260                                        | 1         | 2.22%   |
| Intel Wireless 3165                                        | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.22%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 2.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 54.84%  |
| Intel                 | 25        | 40.32%  |
| Aquantia              | 2         | 3.23%   |
| Qualcomm Atheros      | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 38.46%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 12.31%  |
| Intel I211 Gigabit Network Connection                             | 5         | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.62%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.08%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 3.08%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.08%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.54%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.54%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.54%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.54%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.54%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 53.54%  |
| WiFi     | 43        | 43.43%  |
| Modem    | 3         | 3.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 50.67%  |
| WiFi     | 37        | 49.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 48.44%  |
| 2     | 30        | 46.88%  |
| 3     | 2         | 3.13%   |
| 0     | 1         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 78.13%  |
| Yes  | 14        | 21.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 79.07%  |
| ASUSTek Computer                | 3         | 6.98%   |
| Realtek Semiconductor           | 2         | 4.65%   |
| Cambridge Silicon Radio         | 2         | 4.65%   |
| Qualcomm Atheros Communications | 1         | 2.33%   |
| HTC (High Tech Computer)        | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 11        | 25.58%  |
| Intel Bluetooth wireless interface                                   | 8         | 18.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5         | 11.63%  |
| Intel Bluetooth Device                                               | 4         | 9.3%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 6.98%   |
| Realtek Bluetooth Radio                                              | 2         | 4.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 4.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 4.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 2.33%   |
| Intel AX210 Bluetooth                                                | 1         | 2.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 2.33%   |
| ASUS ASUS USB-BT500                                                  | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 38        | 35.51%  |
| AMD                                  | 27        | 25.23%  |
| Nvidia                               | 21        | 19.63%  |
| C-Media Electronics                  | 3         | 2.8%    |
| Sennheiser Communications            | 2         | 1.87%   |
| Unknown                              | 1         | 0.93%   |
| Trust                                | 1         | 0.93%   |
| Thomann                              | 1         | 0.93%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.93%   |
| Texas Instruments                    | 1         | 0.93%   |
| Sony                                 | 1         | 0.93%   |
| Schiit Audio                         | 1         | 0.93%   |
| Realtek Semiconductor                | 1         | 0.93%   |
| PreSonus Audio Electronics           | 1         | 0.93%   |
| Lenovo                               | 1         | 0.93%   |
| Kingston Technology                  | 1         | 0.93%   |
| GYROCOM C&C                          | 1         | 0.93%   |
| Creative Technology                  | 1         | 0.93%   |
| Creative Labs                        | 1         | 0.93%   |
| Corsair                              | 1         | 0.93%   |
| Antlion Audio                        | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 13        | 10.24%  |
| AMD Family 17h/19h HD Audio Controller                                  | 10        | 7.87%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 9         | 7.09%   |
| Intel Sunrise Point-LP HD Audio                                         | 7         | 5.51%   |
| AMD Navi 10 HDMI Audio                                                  | 6         | 4.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 4         | 3.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 4         | 3.15%   |
| Nvidia GK104 HDMI Audio Controller                                      | 3         | 2.36%   |
| Intel Comet Lake PCH cAVS                                               | 3         | 2.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 3         | 2.36%   |
| Sennheiser Communications Headset [PC 8]                                | 2         | 1.57%   |
| Nvidia TU116 High Definition Audio Controller                           | 2         | 1.57%   |
| Nvidia TU106 High Definition Audio Controller                           | 2         | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                           | 2         | 1.57%   |
| Nvidia GP104 High Definition Audio Controller                           | 2         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 2         | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.57%   |
| Intel Cannon Lake PCH cAVS                                              | 2         | 1.57%   |
| Intel C610/X99 series chipset HD Audio Controller                       | 2         | 1.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 1.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 2         | 1.57%   |
| Intel 200 Series PCH HD Audio                                           | 2         | 1.57%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                              | 2         | 1.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 2         | 1.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 2         | 1.57%   |
| Unknown USB Audio                                                       | 1         | 0.79%   |
| Trust USB microphone                                                    | 1         | 0.79%   |
| Thomann SC450USB                                                        | 1         | 0.79%   |
| Thesycon Systemsoftware & Consulting D10s                               | 1         | 0.79%   |
| Texas Instruments PCM2902 Audio Codec                                   | 1         | 0.79%   |
| Sony DualShock 4 [CUH-ZCT2x]                                            | 1         | 0.79%   |
| Schiit Audio Schiit Modi 3+                                             | 1         | 0.79%   |
| Realtek Semiconductor USB Audio                                         | 1         | 0.79%   |
| PreSonus Audio Electronics AudioBox                                     | 1         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 0.79%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                         | 1         | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1         | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                           | 1         | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                           | 1         | 0.79%   |
| Nvidia GM200 High Definition Audio                                      | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                      | 1         | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 0.79%   |
| Nvidia Audio device                                                     | 1         | 0.79%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 0.79%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1         | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1         | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 0.79%   |
| Intel CM238 HD Audio Controller                                         | 1         | 0.79%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                       | 1         | 0.79%   |
| GYROCOM C&C Fiio E10                                                    | 1         | 0.79%   |
| Creative Technology Sound BlasterX G1                                   | 1         | 0.79%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]              | 1         | 0.79%   |
| Corsair HS70 Pro Wireless Gaming Headset                                | 1         | 0.79%   |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 0.79%   |
| C-Media Electronics Svive Essential mic                                 | 1         | 0.79%   |
| C-Media Electronics CM108 Audio Controller                              | 1         | 0.79%   |
| Antlion Audio Antlion USB Microphone                                    | 1         | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 25.35%  |
| Micron Technology   | 11        | 15.49%  |
| Kingston            | 9         | 12.68%  |
| Corsair             | 9         | 12.68%  |
| Crucial             | 7         | 9.86%   |
| G.Skill             | 6         | 8.45%   |
| Unknown (ABCD)      | 3         | 4.23%   |
| SK Hynix            | 2         | 2.82%   |
| GOODRAM             | 2         | 2.82%   |
| Unknown             | 1         | 1.41%   |
| Strontium           | 1         | 1.41%   |
| Avant               | 1         | 1.41%   |
| AMD                 | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s    | 2         | 2.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 2.56%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 2.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 2         | 2.56%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 2         | 2.56%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s              | 2         | 2.56%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                 | 2         | 2.56%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s              | 2         | 2.56%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                       | 1         | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR3 2400MT/s      | 1         | 1.28%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                  | 1         | 1.28%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 1.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.28%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 1.28%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.28%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.28%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.28%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.28%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.28%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 1.28%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.28%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 1.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.28%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.28%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.28%   |
| Samsung RAM M393B2K70CM0-CF8 16GB DIMM DDR3 1066MT/s                | 1         | 1.28%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s                | 1         | 1.28%   |
| Samsung RAM K4EBE3 4EC-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.28%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s             | 1         | 1.28%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.28%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 1         | 1.28%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.28%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.28%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.28%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s                  | 1         | 1.28%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s                | 1         | 1.28%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 1         | 1.28%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.28%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s                | 1         | 1.28%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                | 1         | 1.28%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s              | 1         | 1.28%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s              | 1         | 1.28%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.28%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s               | 1         | 1.28%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.28%   |
| GOODRAM RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.28%   |
| GOODRAM RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s               | 1         | 1.28%   |
| GOODRAM RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s                 | 1         | 1.28%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s              | 1         | 1.28%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 1         | 1.28%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.28%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1333MT/s                   | 1         | 1.28%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Crucial RAM CT16G4SFD824A.C16FBD 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.28%   |
| Crucial RAM CT16G4SFD8213.M16FB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.28%   |
| Crucial RAM CB16GS2666.C8ET 16384MB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s               | 1         | 1.28%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s            | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 45        | 73.77%  |
| DDR3   | 8         | 13.11%  |
| LPDDR4 | 6         | 9.84%   |
| LPDDR3 | 2         | 3.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 48.39%  |
| DIMM         | 26        | 41.94%  |
| Row Of Chips | 4         | 6.45%   |
| RIMM         | 1         | 1.61%   |
| Chip         | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 27        | 40.3%   |
| 8192  | 27        | 40.3%   |
| 32768 | 8         | 11.94%  |
| 4096  | 5         | 7.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 29.41%  |
| 2133  | 10        | 14.71%  |
| 2667  | 7         | 10.29%  |
| 1600  | 7         | 10.29%  |
| 2400  | 6         | 8.82%   |
| 3600  | 4         | 5.88%   |
| 4266  | 2         | 2.94%   |
| 3334  | 2         | 2.94%   |
| 4267  | 1         | 1.47%   |
| 3733  | 1         | 1.47%   |
| 3533  | 1         | 1.47%   |
| 3466  | 1         | 1.47%   |
| 3400  | 1         | 1.47%   |
| 3266  | 1         | 1.47%   |
| 3000  | 1         | 1.47%   |
| 2933  | 1         | 1.47%   |
| 1333  | 1         | 1.47%   |
| 1066  | 1         | 1.47%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 10        | 25.64%  |
| Logitech                      | 6         | 15.38%  |
| IMC Networks                  | 5         | 12.82%  |
| Acer                          | 4         | 10.26%  |
| Realtek Semiconductor         | 3         | 7.69%   |
| Microdia                      | 3         | 7.69%   |
| Quanta                        | 2         | 5.13%   |
| MacroSilicon                  | 2         | 5.13%   |
| SunplusIT                     | 1         | 2.56%   |
| Sunplus Innovation Technology | 1         | 2.56%   |
| Lite-On Technology            | 1         | 2.56%   |
| Apple                         | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Chicony Integrated Camera         | 6         | 15%     |
| IMC Networks Integrated Camera    | 3         | 7.5%    |
| Chicony HP HD Camera              | 3         | 7.5%    |
| MacroSilicon USB Video            | 2         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam | 2         | 5%      |
| Acer Integrated Camera            | 2         | 5%      |
| SunplusIT MTD camera              | 1         | 2.5%    |
| Sunplus Integrated_Webcam_FHD     | 1         | 2.5%    |
| Realtek Laptop Camera             | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD      | 1         | 2.5%    |
| Realtek EasyCamera                | 1         | 2.5%    |
| Quanta HP True Vision HD Camera   | 1         | 2.5%    |
| Quanta HD WebCam                  | 1         | 2.5%    |
| Microdia USB 2.0 Camera           | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD     | 1         | 2.5%    |
| Microdia Camera                   | 1         | 2.5%    |
| Logitech Webcam C930e             | 1         | 2.5%    |
| Logitech Webcam C310              | 1         | 2.5%    |
| Logitech Webcam C270              | 1         | 2.5%    |
| Logitech StreamCam                | 1         | 2.5%    |
| Logitech HD Pro Webcam C920       | 1         | 2.5%    |
| Logitech C930c                    | 1         | 2.5%    |
| Lite-On HP HD Camera              | 1         | 2.5%    |
| Chicony USB2.0 Camera             | 1         | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE         | 1         | 2.5%    |
| Acer SunplusIT Integrated Camera  | 1         | 2.5%    |
| Acer Integrated IR Camera         | 1         | 2.5%    |
| Acer HD Webcam                    | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 58.33%  |
| Validity Sensors           | 4         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 16.67%  |
| Unknown                                           | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 8         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 37        | 57.81%  |
| 1     | 16        | 25%     |
| 2     | 10        | 15.63%  |
| 4     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 28.21%  |
| Graphics card         | 8         | 20.51%  |
| Chipcard              | 7         | 17.95%  |
| Multimedia controller | 5         | 12.82%  |
| Unassigned class      | 3         | 7.69%   |
| Net/wireless          | 2         | 5.13%   |
| Camera                | 2         | 5.13%   |
| Network               | 1         | 2.56%   |

