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

Total: 101

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
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
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
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
| NixOS 22.05                      | 25        | 30.86%  |
| NixOS 21.11                      | 18        | 22.22%  |
| NixOS                            | 5         | 6.17%   |
| NixOS 22.11                      | 3         | 3.7%    |
| NixOS 21.05pre-git               | 2         | 2.47%   |
| NixOS 20.09pre-git               | 2         | 2.47%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.23%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.23%   |
| NixOS 21.11.20210528.540dccb     | 1         | 1.23%   |
| NixOS 21.05.git.62d4591722f      | 1         | 1.23%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 1.23%   |
| NixOS 21.05.993.93963c27b93      | 1         | 1.23%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.23%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 1.23%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.23%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.23%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 1.23%   |
| NixOS 21.05.20210929.ee90403     | 1         | 1.23%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 1.23%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.23%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 1.23%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 1.23%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 1.23%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 1.23%   |
| NixOS 21.03.20201007.420f89c     | 1         | 1.23%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.23%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 1.23%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 1.23%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.23%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.23%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.23%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.43                | 4         | 4.88%   |
| 5.15.47                | 3         | 3.66%   |
| 5.15.26                | 3         | 3.66%   |
| 5.8.1-zen1             | 2         | 2.44%   |
| 5.17.1                 | 2         | 2.44%   |
| 5.16.8-zen1            | 2         | 2.44%   |
| 5.16.15                | 2         | 2.44%   |
| 5.15.25                | 2         | 2.44%   |
| 5.13.7                 | 2         | 2.44%   |
| 5.13.2                 | 2         | 2.44%   |
| 5.12.15                | 2         | 2.44%   |
| 5.10.102               | 2         | 2.44%   |
| 5.8.4                  | 1         | 1.22%   |
| 5.8.16-hardened        | 1         | 1.22%   |
| 5.8.11                 | 1         | 1.22%   |
| 5.8.10                 | 1         | 1.22%   |
| 5.7.4                  | 1         | 1.22%   |
| 5.7.19                 | 1         | 1.22%   |
| 5.7.17                 | 1         | 1.22%   |
| 5.4.94                 | 1         | 1.22%   |
| 5.4.72                 | 1         | 1.22%   |
| 5.4.69                 | 1         | 1.22%   |
| 5.4.50                 | 1         | 1.22%   |
| 5.4.47                 | 1         | 1.22%   |
| 5.4.24                 | 1         | 1.22%   |
| 5.4.209                | 1         | 1.22%   |
| 5.4.187                | 1         | 1.22%   |
| 5.19.0                 | 1         | 1.22%   |
| 5.18.7-zen1            | 1         | 1.22%   |
| 5.18.0                 | 1         | 1.22%   |
| 5.17.0                 | 1         | 1.22%   |
| 5.16.7                 | 1         | 1.22%   |
| 5.16.3                 | 1         | 1.22%   |
| 5.16.14                | 1         | 1.22%   |
| 5.16.10                | 1         | 1.22%   |
| 5.15.7                 | 1         | 1.22%   |
| 5.15.59                | 1         | 1.22%   |
| 5.15.50                | 1         | 1.22%   |
| 5.15.4                 | 1         | 1.22%   |
| 5.15.39                | 1         | 1.22%   |
| 5.15.34                | 1         | 1.22%   |
| 5.15.32                | 1         | 1.22%   |
| 5.15.3                 | 1         | 1.22%   |
| 5.15.22                | 1         | 1.22%   |
| 5.15.18                | 1         | 1.22%   |
| 5.15.12                | 1         | 1.22%   |
| 5.15.0                 | 1         | 1.22%   |
| 5.14.9                 | 1         | 1.22%   |
| 5.14.16-lqx1           | 1         | 1.22%   |
| 5.12.7                 | 1         | 1.22%   |
| 5.11.16-zen1           | 1         | 1.22%   |
| 5.11.16-xanmod1-cacule | 1         | 1.22%   |
| 5.10.99                | 1         | 1.22%   |
| 5.10.96                | 1         | 1.22%   |
| 5.10.69                | 1         | 1.22%   |
| 5.10.66                | 1         | 1.22%   |
| 5.10.62                | 1         | 1.22%   |
| 5.10.57                | 1         | 1.22%   |
| 5.10.52                | 1         | 1.22%   |
| 5.10.43                | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.43  | 4         | 4.88%   |
| 5.15.47  | 3         | 3.66%   |
| 5.15.26  | 3         | 3.66%   |
| 5.8.1    | 2         | 2.44%   |
| 5.17.1   | 2         | 2.44%   |
| 5.16.8   | 2         | 2.44%   |
| 5.16.15  | 2         | 2.44%   |
| 5.15.25  | 2         | 2.44%   |
| 5.13.7   | 2         | 2.44%   |
| 5.13.2   | 2         | 2.44%   |
| 5.12.15  | 2         | 2.44%   |
| 5.11.16  | 2         | 2.44%   |
| 5.10.102 | 2         | 2.44%   |
| 5.8.4    | 1         | 1.22%   |
| 5.8.16   | 1         | 1.22%   |
| 5.8.11   | 1         | 1.22%   |
| 5.8.10   | 1         | 1.22%   |
| 5.7.4    | 1         | 1.22%   |
| 5.7.19   | 1         | 1.22%   |
| 5.7.17   | 1         | 1.22%   |
| 5.4.94   | 1         | 1.22%   |
| 5.4.72   | 1         | 1.22%   |
| 5.4.69   | 1         | 1.22%   |
| 5.4.50   | 1         | 1.22%   |
| 5.4.47   | 1         | 1.22%   |
| 5.4.24   | 1         | 1.22%   |
| 5.4.209  | 1         | 1.22%   |
| 5.4.187  | 1         | 1.22%   |
| 5.19.0   | 1         | 1.22%   |
| 5.18.7   | 1         | 1.22%   |
| 5.18.0   | 1         | 1.22%   |
| 5.17.0   | 1         | 1.22%   |
| 5.16.7   | 1         | 1.22%   |
| 5.16.3   | 1         | 1.22%   |
| 5.16.14  | 1         | 1.22%   |
| 5.16.10  | 1         | 1.22%   |
| 5.15.7   | 1         | 1.22%   |
| 5.15.59  | 1         | 1.22%   |
| 5.15.50  | 1         | 1.22%   |
| 5.15.4   | 1         | 1.22%   |
| 5.15.39  | 1         | 1.22%   |
| 5.15.34  | 1         | 1.22%   |
| 5.15.32  | 1         | 1.22%   |
| 5.15.3   | 1         | 1.22%   |
| 5.15.22  | 1         | 1.22%   |
| 5.15.18  | 1         | 1.22%   |
| 5.15.12  | 1         | 1.22%   |
| 5.15.0   | 1         | 1.22%   |
| 5.14.9   | 1         | 1.22%   |
| 5.14.16  | 1         | 1.22%   |
| 5.12.7   | 1         | 1.22%   |
| 5.10.99  | 1         | 1.22%   |
| 5.10.96  | 1         | 1.22%   |
| 5.10.69  | 1         | 1.22%   |
| 5.10.66  | 1         | 1.22%   |
| 5.10.62  | 1         | 1.22%   |
| 5.10.57  | 1         | 1.22%   |
| 5.10.52  | 1         | 1.22%   |
| 5.10.43  | 1         | 1.22%   |
| 5.10.35  | 1         | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 29.63%  |
| 5.10    | 14        | 17.28%  |
| 5.16    | 8         | 9.88%   |
| 5.4     | 7         | 8.64%   |
| 5.8     | 6         | 7.41%   |
| 5.13    | 4         | 4.94%   |
| 5.7     | 3         | 3.7%    |
| 5.17    | 3         | 3.7%    |
| 5.12    | 3         | 3.7%    |
| 5.18    | 2         | 2.47%   |
| 5.14    | 2         | 2.47%   |
| 5.11    | 2         | 2.47%   |
| 4.19    | 2         | 2.47%   |
| 5.19    | 1         | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 75        | 98.68%  |
| aarch64 | 1         | 1.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 60        | 77.92%  |
| XFCE         | 5         | 6.49%   |
| KDE          | 4         | 5.19%   |
| sway         | 3         | 3.9%    |
| GNOME        | 3         | 3.9%    |
| none+xmonad  | 1         | 1.3%    |
| none+awesome | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 71.79%  |
| X11     | 12        | 15.38%  |
| Wayland | 7         | 8.97%   |
| Tty     | 3         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 84.42%  |
| LightDM | 8         | 10.39%  |
| SDDM    | 2         | 2.6%    |
| GDM     | 2         | 2.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 63.16%  |
| en_US   | 18        | 23.68%  |
| ru_RU   | 2         | 2.63%   |
| en_GB   | 2         | 2.63%   |
| en_DK   | 2         | 2.63%   |
| de_CH   | 2         | 2.63%   |
| ro_RO   | 1         | 1.32%   |
| pt_BR   | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 62        | 80.52%  |
| BIOS | 15        | 19.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 50%     |
| Btrfs   | 12        | 15.38%  |
| Tmpfs   | 9         | 11.54%  |
| Xfs     | 6         | 7.69%   |
| Unknown | 6         | 7.69%   |
| Zfs     | 5         | 6.41%   |
| Ext2    | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 70        | 89.74%  |
| Unknown | 7         | 8.97%   |
| MBR     | 1         | 1.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 72.73%  |
| Yes       | 21        | 27.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 61.84%  |
| Yes       | 29        | 38.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 19        | 25%     |
| Lenovo                  | 16        | 21.05%  |
| MSI                     | 8         | 10.53%  |
| Dell                    | 7         | 9.21%   |
| Hewlett-Packard         | 6         | 7.89%   |
| Gigabyte Technology     | 5         | 6.58%   |
| ASRock                  | 4         | 5.26%   |
| Acer                    | 2         | 2.63%   |
| Teclast                 | 1         | 1.32%   |
| Supermicro              | 1         | 1.32%   |
| Raspberry Pi Foundation | 1         | 1.32%   |
| OBSIDIAN-PC             | 1         | 1.32%   |
| Hardkernel              | 1         | 1.32%   |
| GPD                     | 1         | 1.32%   |
| Framework               | 1         | 1.32%   |
| EVGA                    | 1         | 1.32%   |
| Apple                   | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 2         | 2.63%   |
| Dell Latitude 7420                    | 2         | 2.63%   |
| Teclast F5                            | 1         | 1.32%   |
| Supermicro X8DT6                      | 1         | 1.32%   |
| RPi Raspberry Pi 3 Model B+           | 1         | 1.32%   |
| OBSIDIAN-PC N13_N140ZU                | 1         | 1.32%   |
| MSI MS-7C95                           | 1         | 1.32%   |
| MSI MS-7C84                           | 1         | 1.32%   |
| MSI MS-7C35                           | 1         | 1.32%   |
| MSI MS-7B89                           | 1         | 1.32%   |
| MSI MS-7B09                           | 1         | 1.32%   |
| MSI Bravo 15 B5DD                     | 1         | 1.32%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 1.32%   |
| Lenovo Yoga 520-14IKB 81C8            | 1         | 1.32%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 1.32%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 1.32%   |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 1.32%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 1.32%   |
| Lenovo ThinkPad X230 23243E9          | 1         | 1.32%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 1.32%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 1.32%   |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 1.32%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 1.32%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 1.32%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 1.32%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 1.32%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 1.32%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 1.32%   |
| HP ZBook Studio G5                    | 1         | 1.32%   |
| HP Spectre x360 Convertible 15-eb0xxx | 1         | 1.32%   |
| HP ProBook 450 G4                     | 1         | 1.32%   |
| HP ProBook 445 G7                     | 1         | 1.32%   |
| HP EliteDesk 800 G2 DM 35W            | 1         | 1.32%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 1.32%   |
| Hardkernel ODROID-H2                  | 1         | 1.32%   |
| GPD MicroPC                           | 1         | 1.32%   |
| Gigabyte X570 AORUS ELITE             | 1         | 1.32%   |
| Gigabyte X470 AORUS ULTRA GAMING      | 1         | 1.32%   |
| Gigabyte Sabre 15                     | 1         | 1.32%   |
| Gigabyte H97M-D3H                     | 1         | 1.32%   |
| Gigabyte B550I AORUS PRO AX           | 1         | 1.32%   |
| Framework Laptop                      | 1         | 1.32%   |
| EVGA X299 FTW K                       | 1         | 1.32%   |
| Dell XPS 15 9550                      | 1         | 1.32%   |
| Dell XPS 13 9310                      | 1         | 1.32%   |
| Dell XPS 13 9305                      | 1         | 1.32%   |
| Dell Precision Tower 7810             | 1         | 1.32%   |
| Dell Inspiron 7391 2n1                | 1         | 1.32%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 1.32%   |
| ASUS Z170-P                           | 1         | 1.32%   |
| ASUS TUF Gaming X570-PLUS             | 1         | 1.32%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 1.32%   |
| ASUS ROG STRIX Z390-F GAMING          | 1         | 1.32%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 1.32%   |
| ASUS ROG STRIX B550-I GAMING          | 1         | 1.32%   |
| ASUS ROG STRIX B550-F GAMING          | 1         | 1.32%   |
| ASUS ROG Flow X13 GV301QE_GV301QE     | 1         | 1.32%   |
| ASUS PRO602617                        | 1         | 1.32%   |
| ASUS PRO-Q77 IU                       | 1         | 1.32%   |
| ASUS Pro WS W480-ACE                  | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 13        | 17.11%  |
| ASUS ROG             | 6         | 7.89%   |
| ASUS PRIME           | 4         | 5.26%   |
| Dell XPS             | 3         | 3.95%   |
| MSI MS-7C37          | 2         | 2.63%   |
| Lenovo Yoga          | 2         | 2.63%   |
| HP ProBook           | 2         | 2.63%   |
| Dell Latitude        | 2         | 2.63%   |
| Teclast F5           | 1         | 1.32%   |
| Supermicro X8DT6     | 1         | 1.32%   |
| RPi Raspberry        | 1         | 1.32%   |
| OBSIDIAN-PC N13      | 1         | 1.32%   |
| MSI MS-7C95          | 1         | 1.32%   |
| MSI MS-7C84          | 1         | 1.32%   |
| MSI MS-7C35          | 1         | 1.32%   |
| MSI MS-7B89          | 1         | 1.32%   |
| MSI MS-7B09          | 1         | 1.32%   |
| MSI Bravo            | 1         | 1.32%   |
| Lenovo Legion        | 1         | 1.32%   |
| HP ZBook             | 1         | 1.32%   |
| HP Spectre           | 1         | 1.32%   |
| HP EliteDesk         | 1         | 1.32%   |
| HP EliteBook         | 1         | 1.32%   |
| Hardkernel ODROID-H2 | 1         | 1.32%   |
| GPD MicroPC          | 1         | 1.32%   |
| Gigabyte X570        | 1         | 1.32%   |
| Gigabyte X470        | 1         | 1.32%   |
| Gigabyte Sabre       | 1         | 1.32%   |
| Gigabyte H97M-D3H    | 1         | 1.32%   |
| Gigabyte B550I       | 1         | 1.32%   |
| Framework Laptop     | 1         | 1.32%   |
| EVGA X299            | 1         | 1.32%   |
| Dell Precision       | 1         | 1.32%   |
| Dell Inspiron        | 1         | 1.32%   |
| ASUS ZenBook         | 1         | 1.32%   |
| ASUS Z170-P          | 1         | 1.32%   |
| ASUS TUF             | 1         | 1.32%   |
| ASUS PRO602617       | 1         | 1.32%   |
| ASUS PRO-Q77         | 1         | 1.32%   |
| ASUS Pro             | 1         | 1.32%   |
| ASUS P8Z77-V         | 1         | 1.32%   |
| ASUS ASUSPRO         | 1         | 1.32%   |
| ASUS All             | 1         | 1.32%   |
| ASRock X570          | 1         | 1.32%   |
| ASRock TRX40         | 1         | 1.32%   |
| ASRock B450          | 1         | 1.32%   |
| ASRock AB350         | 1         | 1.32%   |
| Apple MacBookPro11   | 1         | 1.32%   |
| Acer Nitro           | 1         | 1.32%   |
| Acer Aspire          | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 20        | 26.32%  |
| 2019    | 14        | 18.42%  |
| 2018    | 10        | 13.16%  |
| 2016    | 9         | 11.84%  |
| 2021    | 7         | 9.21%   |
| 2017    | 5         | 6.58%   |
| 2015    | 4         | 5.26%   |
| 2014    | 2         | 2.63%   |
| 2012    | 2         | 2.63%   |
| 2013    | 1         | 1.32%   |
| 2010    | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 36        | 47.37%  |
| Desktop        | 34        | 44.74%  |
| Convertible    | 4         | 5.26%   |
| System on chip | 1         | 1.32%   |
| Server         | 1         | 1.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 76        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 98.68%  |
| Yes  | 1         | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 22        | 28.57%  |
| 16.01-24.0  | 20        | 25.97%  |
| 64.01-256.0 | 15        | 19.48%  |
| 8.01-16.0   | 9         | 11.69%  |
| 4.01-8.0    | 6         | 7.79%   |
| 24.01-32.0  | 3         | 3.9%    |
| 3.01-4.0    | 1         | 1.3%    |
| 0.51-1.0    | 1         | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 30%     |
| 8.01-16.0   | 19        | 23.75%  |
| 3.01-4.0    | 10        | 12.5%   |
| 2.01-3.0    | 7         | 8.75%   |
| 32.01-64.0  | 6         | 7.5%    |
| 1.01-2.0    | 5         | 6.25%   |
| 24.01-32.0  | 3         | 3.75%   |
| 16.01-24.0  | 3         | 3.75%   |
| 64.01-256.0 | 1         | 1.25%   |
| 0.51-1.0    | 1         | 1.25%   |
| 0.01-0.5    | 1         | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 50%     |
| 2      | 20        | 25.64%  |
| 3      | 9         | 11.54%  |
| 6      | 4         | 5.13%   |
| 5      | 2         | 2.56%   |
| 11     | 1         | 1.28%   |
| 8      | 1         | 1.28%   |
| 4      | 1         | 1.28%   |
| 0      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 88.16%  |
| Yes       | 9         | 11.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 82.05%  |
| No        | 14        | 17.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 65.79%  |
| No        | 26        | 34.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 64.94%  |
| No        | 27        | 35.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 15.79%  |
| UK          | 8         | 10.53%  |
| Germany     | 8         | 10.53%  |
| Poland      | 7         | 9.21%   |
| Russia      | 6         | 7.89%   |
| Ukraine     | 5         | 6.58%   |
| Canada      | 5         | 6.58%   |
| Switzerland | 3         | 3.95%   |
| Austria     | 3         | 3.95%   |
| France      | 2         | 2.63%   |
| Belgium     | 2         | 2.63%   |
| Uruguay     | 1         | 1.32%   |
| Sweden      | 1         | 1.32%   |
| Spain       | 1         | 1.32%   |
| Serbia      | 1         | 1.32%   |
| Romania     | 1         | 1.32%   |
| Portugal    | 1         | 1.32%   |
| New Zealand | 1         | 1.32%   |
| Netherlands | 1         | 1.32%   |
| Iran        | 1         | 1.32%   |
| India       | 1         | 1.32%   |
| Hungary     | 1         | 1.32%   |
| Denmark     | 1         | 1.32%   |
| Czechia     | 1         | 1.32%   |
| Colombia    | 1         | 1.32%   |
| Brazil      | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Marki              | 4         | 5.19%   |
| Vienna             | 3         | 3.9%    |
| Plymouth           | 3         | 3.9%    |
| Kharkiv            | 3         | 3.9%    |
| South Deerfield    | 2         | 2.6%    |
| Schaafheim         | 2         | 2.6%    |
| Richardson         | 2         | 2.6%    |
| London             | 2         | 2.6%    |
| Halifax            | 2         | 2.6%    |
| Gdansk             | 2         | 2.6%    |
| Darmstadt          | 2         | 2.6%    |
| Chelyabinsk        | 2         | 2.6%    |
| Woodford           | 1         | 1.3%    |
| Wellington         | 1         | 1.3%    |
| Verneuil-sur-Seine | 1         | 1.3%    |
| Valpacos           | 1         | 1.3%    |
| Tottenham          | 1         | 1.3%    |
| Tolyatti           | 1         | 1.3%    |
| Tehran             | 1         | 1.3%    |
| Székesfehérvár  | 1         | 1.3%    |
| Stockholm          | 1         | 1.3%    |
| Southampton        | 1         | 1.3%    |
| Sindelfingen       | 1         | 1.3%    |
| Saratov            | 1         | 1.3%    |
| San Gabriel        | 1         | 1.3%    |
| Redwood City       | 1         | 1.3%    |
| Ramenskoye         | 1         | 1.3%    |
| Popice             | 1         | 1.3%    |
| Ottawa             | 1         | 1.3%    |
| Osasco             | 1         | 1.3%    |
| Oberkempten        | 1         | 1.3%    |
| Oakville           | 1         | 1.3%    |
| Mykolayiv          | 1         | 1.3%    |
| Montreal           | 1         | 1.3%    |
| Montevideo         | 1         | 1.3%    |
| Mons               | 1         | 1.3%    |
| Melsele            | 1         | 1.3%    |
| Melrose            | 1         | 1.3%    |
| Lehrte             | 1         | 1.3%    |
| Kuybyshev          | 1         | 1.3%    |
| Krakow             | 1         | 1.3%    |
| Kiel               | 1         | 1.3%    |
| Karlsruhe          | 1         | 1.3%    |
| Islington          | 1         | 1.3%    |
| Irpin              | 1         | 1.3%    |
| Gurgaon            | 1         | 1.3%    |
| Goleta             | 1         | 1.3%    |
| Getafe             | 1         | 1.3%    |
| Esbjerg            | 1         | 1.3%    |
| Enschede           | 1         | 1.3%    |
| Dietikon           | 1         | 1.3%    |
| Didcot             | 1         | 1.3%    |
| Cluj-Napoca        | 1         | 1.3%    |
| Cergy              | 1         | 1.3%    |
| Cartagena          | 1         | 1.3%    |
| Belgrade           | 1         | 1.3%    |
| Bedford            | 1         | 1.3%    |
| Austin             | 1         | 1.3%    |
| Andover            | 1         | 1.3%    |
| Allschwil          | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 64     | 30.77%  |
| WDC                 | 13        | 25     | 11.11%  |
| Seagate             | 9         | 11     | 7.69%   |
| Toshiba             | 8         | 11     | 6.84%   |
| Crucial             | 8         | 10     | 6.84%   |
| Kingston            | 7         | 7      | 5.98%   |
| Intel               | 7         | 10     | 5.98%   |
| SanDisk             | 5         | 9      | 4.27%   |
| SK hynix            | 3         | 4      | 2.56%   |
| Unknown             | 2         | 2      | 1.71%   |
| Transcend           | 2         | 2      | 1.71%   |
| Plextor             | 2         | 2      | 1.71%   |
| Micron Technology   | 2         | 2      | 1.71%   |
| KIOXIA              | 2         | 2      | 1.71%   |
| HGST                | 2         | 4      | 1.71%   |
| Teclast             | 1         | 1      | 0.85%   |
| Phison Electronics  | 1         | 2      | 0.85%   |
| Phison              | 1         | 1      | 0.85%   |
| Lexar               | 1         | 1      | 0.85%   |
| INNOVATION IT       | 1         | 1      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| BIWIN               | 1         | 1      | 0.85%   |
| ASMT                | 1         | 1      | 0.85%   |
| Apple               | 1         | 2      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB              | 5         | 3.62%   |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 2.17%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 2.17%   |
| Samsung SSD 970 EVO 500GB            | 3         | 2.17%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 2.17%   |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 1.45%   |
| SanDisk SSD PLUS 240GB               | 2         | 1.45%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.45%   |
| Samsung SSD 970 EVO 1TB              | 2         | 1.45%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.45%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.45%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.45%   |
| Samsung SSD 860 EVO 2TB              | 2         | 1.45%   |
| Samsung PM9A1 NVMe 1024GB            | 2         | 1.45%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.45%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 1.45%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.45%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.72%   |
| WDC WDS200T1X0E-00AFY0 2TB           | 1         | 0.72%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.72%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.72%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.72%   |
| WDC WD120EMFZ-11A6JA0 12TB           | 1         | 0.72%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1         | 0.72%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.72%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.72%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.72%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.72%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 0.72%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.72%   |
| Unknown MMC Card  32GB               | 1         | 0.72%   |
| Unknown MMC Card  16GB               | 1         | 0.72%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 0.72%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 0.72%   |
| Toshiba TR150 960GB SSD              | 1         | 0.72%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.72%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.72%   |
| Toshiba KBG40ZNS512G NVMe 512GB      | 1         | 0.72%   |
| Toshiba HDWL120 2TB                  | 1         | 0.72%   |
| Toshiba HDWE160 6TB                  | 1         | 0.72%   |
| Toshiba HDWD130 3TB                  | 1         | 0.72%   |
| Toshiba HDWD120 2TB                  | 1         | 0.72%   |
| Teclast 256GB NS550-2242 SSD         | 1         | 0.72%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 0.72%   |
| SK hynix NVMe SSD Drive 1TB          | 1         | 0.72%   |
| SK hynix NVMe SSD Drive 1024GB       | 1         | 0.72%   |
| SK hynix HFM001TD3JX013N 1TB         | 1         | 0.72%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.72%   |
| Seagate ST3000VX010-2H916L 3TB       | 1         | 0.72%   |
| Seagate ST3000DM001-1CH166 3TB       | 1         | 0.72%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 0.72%   |
| Seagate Backup+ Hub BK 8TB           | 1         | 0.72%   |
| SanDisk Ultra II 960GB SSD           | 1         | 0.72%   |
| SanDisk SSD PLUS 240 GB              | 1         | 0.72%   |
| SanDisk SSD PLUS 120 GB              | 1         | 0.72%   |
| SanDisk SDSSDHII240G 240GB           | 1         | 0.72%   |
| SanDisk SDSSDA240G 240GB             | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 11     | 37.5%   |
| WDC     | 7         | 17     | 29.17%  |
| Toshiba | 5         | 8      | 20.83%  |
| HGST    | 2         | 4      | 8.33%   |
| ASMT    | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 29     | 32%     |
| Crucial             | 8         | 10     | 16%     |
| Kingston            | 5         | 5      | 10%     |
| Intel               | 5         | 7      | 10%     |
| SanDisk             | 4         | 7      | 8%      |
| WDC                 | 2         | 3      | 4%      |
| Transcend           | 2         | 2      | 4%      |
| Toshiba             | 1         | 1      | 2%      |
| Teclast             | 1         | 1      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| INNOVATION IT       | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| BIWIN               | 1         | 1      | 2%      |
| Apple               | 1         | 2      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 46        | 61     | 42.2%   |
| SSD  | 42        | 72     | 38.53%  |
| HDD  | 19        | 41     | 17.43%  |
| MMC  | 2         | 2      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 110    | 47.96%  |
| NVMe | 46        | 61     | 46.94%  |
| SAS  | 3         | 3      | 3.06%   |
| MMC  | 2         | 2      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 43     | 44.29%  |
| 0.51-1.0   | 22        | 38     | 31.43%  |
| 1.01-2.0   | 6         | 9      | 8.57%   |
| 2.01-3.0   | 5         | 6      | 7.14%   |
| 4.01-10.0  | 3         | 7      | 4.29%   |
| 3.01-4.0   | 2         | 4      | 2.86%   |
| 10.01-20.0 | 1         | 6      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 51        | 66.23%  |
| 1-20           | 11        | 14.29%  |
| 501-1000       | 5         | 6.49%   |
| 101-250        | 3         | 3.9%    |
| More than 3000 | 2         | 2.6%    |
| 2001-3000      | 2         | 2.6%    |
| 1001-2000      | 2         | 2.6%    |
| 251-500        | 1         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 51        | 66.23%  |
| 1-20           | 14        | 18.18%  |
| 101-250        | 4         | 5.19%   |
| 1001-2000      | 3         | 3.9%    |
| 251-500        | 2         | 2.6%    |
| 501-1000       | 2         | 2.6%    |
| More than 3000 | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 14.29%  |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 14.29%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 14.29%  |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 14.29%  |
| ASMT 2115 256GB                                | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 28.57%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SK hynix            | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| ASMT                | 1         | 1      | 14.29%  |

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
| SSD  | 3         | 3      | 42.86%  |
| NVMe | 2         | 2      | 28.57%  |
| HDD  | 2         | 2      | 28.57%  |

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
| Works    | 70        | 152    | 81.4%   |
| Detected | 10        | 17     | 11.63%  |
| Malfunc  | 6         | 7      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 32.73%  |
| Samsung Electronics          | 26        | 23.64%  |
| AMD                          | 21        | 19.09%  |
| SanDisk                      | 6         | 5.45%   |
| SK hynix                     | 3         | 2.73%   |
| Kingston Technology Company  | 3         | 2.73%   |
| ASMedia Technology           | 3         | 2.73%   |
| Toshiba America Info Systems | 2         | 1.82%   |
| Phison Electronics           | 2         | 1.82%   |
| LSI Logic / Symbios Logic    | 2         | 1.82%   |
| KIOXIA                       | 2         | 1.82%   |
| Shenzhen Longsys Electronics | 1         | 0.91%   |
| Micron Technology            | 1         | 0.91%   |
| Lite-On Technology           | 1         | 0.91%   |
| Broadcom / LSI               | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 15.97%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 12.61%  |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 4.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.36%   |
| SK hynix Gold P31 SSD                                                          | 3         | 2.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.52%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.52%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 2.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.68%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.68%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.68%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.68%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.68%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 0.84%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.84%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.84%   |
| Samsung Electronics SATA controller                                            | 1         | 0.84%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.84%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                 | 1         | 0.84%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1         | 0.84%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.84%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.84%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.84%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1         | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 0.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 0.84%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 1         | 0.84%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 0.84%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 47.22%  |
| NVMe | 47        | 43.52%  |
| RAID | 5         | 4.63%   |
| SAS  | 3         | 2.78%   |
| IDE  | 2         | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 60.53%  |
| AMD    | 29        | 38.16%  |
| ARM    | 1         | 1.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 4         | 5.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 3         | 3.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 3         | 3.95%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 3         | 3.95%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 3         | 3.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 2         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 2.63%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 2         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 2.63%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2         | 2.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 2         | 2.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 2         | 2.63%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2         | 2.63%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1         | 1.32%   |
| Intel Xeon E-2176M CPU @ 2.70GHz               | 1         | 1.32%   |
| Intel Xeon CPU L5640 @ 2.27GHz                 | 1         | 1.32%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 1.32%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1         | 1.32%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 1         | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 1         | 1.32%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.32%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.32%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1         | 1.32%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.32%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1         | 1.32%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1         | 1.32%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.32%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1         | 1.32%   |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 1.32%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1         | 1.32%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 1.32%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1         | 1.32%   |
| ARM Processor                                  | 1         | 1.32%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1         | 1.32%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.32%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.32%   |
| AMD Ryzen 9 5900HS with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.32%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 1         | 1.32%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 1         | 1.32%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 1         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.32%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1         | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1         | 1.32%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1         | 1.32%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 20        | 26.32%  |
| AMD Ryzen 7            | 12        | 15.79%  |
| Intel Core i5          | 10        | 13.16%  |
| AMD Ryzen 5            | 7         | 9.21%   |
| Other                  | 6         | 7.89%   |
| AMD Ryzen 9            | 5         | 6.58%   |
| Intel Xeon             | 4         | 5.26%   |
| Intel Core i3          | 3         | 3.95%   |
| Intel Celeron          | 3         | 3.95%   |
| AMD Ryzen 7 PRO        | 3         | 3.95%   |
| AMD Ryzen Threadripper | 2         | 2.63%   |
| Intel Core i9          | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 27        | 35.53%  |
| 8       | 16        | 21.05%  |
| 6       | 13        | 17.11%  |
| 2       | 9         | 11.84%  |
| 12      | 4         | 5.26%   |
| 16      | 2         | 2.63%   |
| 10      | 2         | 2.63%   |
| 32      | 1         | 1.32%   |
| 24      | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 73        | 96.05%  |
| 2       | 2         | 2.63%   |
| Unknown | 1         | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 67        | 88.16%  |
| 1       | 8         | 10.53%  |
| Unknown | 1         | 1.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 98.7%   |
| Unknown        | 1         | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 15.38%  |
| 0x08701021 | 6         | 7.69%   |
| 0x0a50000c | 5         | 6.41%   |
| 0x806ec    | 4         | 5.13%   |
| 0x806ea    | 4         | 5.13%   |
| 0x806c1    | 4         | 5.13%   |
| 0x08701013 | 4         | 5.13%   |
| 0x906ea    | 3         | 3.85%   |
| 0x506e3    | 3         | 3.85%   |
| 0x306c3    | 3         | 3.85%   |
| 0x306a9    | 3         | 3.85%   |
| 0x08600106 | 3         | 3.85%   |
| 0x906e9    | 2         | 2.56%   |
| 0x806eb    | 2         | 2.56%   |
| 0x706a1    | 2         | 2.56%   |
| 0x406e3    | 2         | 2.56%   |
| 0x0a201204 | 2         | 2.56%   |
| 0x0a201009 | 2         | 2.56%   |
| 0xa0653    | 1         | 1.28%   |
| 0xa0652    | 1         | 1.28%   |
| 0x806e9    | 1         | 1.28%   |
| 0x406f1    | 1         | 1.28%   |
| 0x40661    | 1         | 1.28%   |
| 0x306f2    | 1         | 1.28%   |
| 0x306d4    | 1         | 1.28%   |
| 0x0a50000b | 1         | 1.28%   |
| 0x08600104 | 1         | 1.28%   |
| 0x08301025 | 1         | 1.28%   |
| 0x0800820d | 1         | 1.28%   |
| 0x08001137 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 22.37%  |
| Zen 2         | 16        | 21.05%  |
| Zen 3         | 10        | 13.16%  |
| Skylake       | 7         | 9.21%   |
| TigerLake     | 5         | 6.58%   |
| Haswell       | 5         | 6.58%   |
| IvyBridge     | 3         | 3.95%   |
| Goldmont plus | 3         | 3.95%   |
| CometLake     | 3         | 3.95%   |
| Zen+          | 2         | 2.63%   |
| Broadwell     | 2         | 2.63%   |
| Zen           | 1         | 1.32%   |
| Westmere      | 1         | 1.32%   |
| Unknown       | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 35        | 38.04%  |
| Nvidia                     | 33        | 35.87%  |
| AMD                        | 23        | 25%     |
| Matrox Electronics Systems | 1         | 1.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                      | 6         | 6.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                        | 5         | 5.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5         | 5.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 5         | 5.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                       | 4         | 4.3%    |
| Intel HD Graphics 530                                            | 4         | 4.3%    |
| AMD Renoir                                                       | 4         | 4.3%    |
| Intel UHD Graphics 620                                           | 3         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                              | 3         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                             | 3         | 3.23%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 2         | 2.15%   |
| Nvidia GP108M [GeForce MX150]                                    | 2         | 2.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2         | 2.15%   |
| Nvidia GK104 [GeForce GTX 760]                                   | 2         | 2.15%   |
| Intel Skylake GT2 [HD Graphics 520]                              | 2         | 2.15%   |
| Intel HD Graphics 630                                            | 2         | 2.15%   |
| Intel HD Graphics 620                                            | 2         | 2.15%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2         | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                       | 1         | 1.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                       | 1         | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1         | 1.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1         | 1.08%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1         | 1.08%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                            | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 1.08%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                            | 1         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 1         | 1.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1         | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1         | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1         | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                   | 1         | 1.08%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 1         | 1.08%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                | 1         | 1.08%   |
| Nvidia GM108M [GeForce 940MX]                                    | 1         | 1.08%   |
| Nvidia GM108M [GeForce 930MX]                                    | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                 | 1         | 1.08%   |
| Nvidia GK208M [GeForce GT 730M]                                  | 1         | 1.08%   |
| Nvidia GK107 [NVS 510]                                           | 1         | 1.08%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                       | 1         | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                  | 1         | 1.08%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                   | 1         | 1.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                  | 1         | 1.08%   |
| Matrox Electronics Systems MGA G200eW WPCM450                    | 1         | 1.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1         | 1.08%   |
| Intel UHD P630 Graphics                                          | 1         | 1.08%   |
| Intel HD Graphics 5500                                           | 1         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                             | 1         | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller      | 1         | 1.08%   |
| Intel 3rd Gen Core processor Graphics Controller                 | 1         | 1.08%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                  | 1         | 1.08%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                   | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 32.89%  |
| 1 x Nvidia     | 17        | 22.37%  |
| 1 x AMD        | 15        | 19.74%  |
| Intel + Nvidia | 9         | 11.84%  |
| AMD + Nvidia   | 7         | 9.21%   |
| Other          | 1         | 1.32%   |
| 2 x AMD        | 1         | 1.32%   |
| 1 x Matrox     | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 73.68%  |
| Proprietary | 18        | 23.68%  |
| Unknown     | 2         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 65.38%  |
| 7.01-8.0   | 9         | 11.54%  |
| 0.01-0.5   | 8         | 10.26%  |
| 1.01-2.0   | 5         | 6.41%   |
| 3.01-4.0   | 3         | 3.85%   |
| 8.01-16.0  | 1         | 1.28%   |
| 0.51-1.0   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 16        | 19.05%  |
| AU Optronics         | 9         | 10.71%  |
| Goldstar             | 8         | 9.52%   |
| LG Display           | 6         | 7.14%   |
| Samsung Electronics  | 5         | 5.95%   |
| Chimei Innolux       | 5         | 5.95%   |
| PANDA                | 4         | 4.76%   |
| BOE                  | 4         | 4.76%   |
| Acer                 | 4         | 4.76%   |
| Sharp                | 3         | 3.57%   |
| InfoVision           | 2         | 2.38%   |
| Hewlett-Packard      | 2         | 2.38%   |
| AOC                  | 2         | 2.38%   |
| Ancor Communications | 2         | 2.38%   |
| Vizio                | 1         | 1.19%   |
| Unknown (AAA)        | 1         | 1.19%   |
| Panasonic            | 1         | 1.19%   |
| MPI                  | 1         | 1.19%   |
| Lenovo               | 1         | 1.19%   |
| JDI                  | 1         | 1.19%   |
| Iiyama               | 1         | 1.19%   |
| HVR                  | 1         | 1.19%   |
| Eizo                 | 1         | 1.19%   |
| BenQ                 | 1         | 1.19%   |
| ASUSTek Computer     | 1         | 1.19%   |
| Apple                | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 2.3%    |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 2.3%    |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 2         | 2.3%    |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 2.3%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 2.3%    |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 2.3%    |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                  | 1         | 1.15%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 1.15%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 1         | 1.15%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.15%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.15%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.15%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 1.15%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.15%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 1.15%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.15%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.15%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.15%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 1.15%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 1         | 1.15%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1         | 1.15%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.15%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.15%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.15%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch          | 1         | 1.15%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.15%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.15%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.15%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 1.15%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1         | 1.15%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1         | 1.15%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.15%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 1         | 1.15%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1         | 1.15%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1         | 1.15%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.15%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 1.15%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.15%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1         | 1.15%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.15%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1         | 1.15%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.15%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                     | 1         | 1.15%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1         | 1.15%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 1.15%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1         | 1.15%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.15%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 1         | 1.15%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 1         | 1.15%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                      | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch      | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1384 1920x1080 293x165mm 13.2-inch      | 1         | 1.15%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 34        | 42.5%   |
| 3840x2160 (4K)    | 14        | 17.5%   |
| 2560x1440 (QHD)   | 11        | 13.75%  |
| 2560x1080         | 4         | 5%      |
| 1366x768 (WXGA)   | 4         | 5%      |
| 1920x1200 (WUXGA) | 3         | 3.75%   |
| 1280x1024 (SXGA)  | 2         | 2.5%    |
| 3840x2400         | 1         | 1.25%   |
| 3440x1440         | 1         | 1.25%   |
| 2880x1800         | 1         | 1.25%   |
| 2560x1600         | 1         | 1.25%   |
| 2256x1504         | 1         | 1.25%   |
| 2160x1200         | 1         | 1.25%   |
| 1440x900 (WXGA+)  | 1         | 1.25%   |
| 1280x720 (HD)     | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 12        | 14.46%  |
| 13      | 11        | 13.25%  |
| 15      | 10        | 12.05%  |
| 14      | 10        | 12.05%  |
| 24      | 8         | 9.64%   |
| 23      | 8         | 9.64%   |
| 34      | 5         | 6.02%   |
| 17      | 5         | 6.02%   |
| 12      | 4         | 4.82%   |
| 31      | 2         | 2.41%   |
| 25      | 2         | 2.41%   |
| 21      | 2         | 2.41%   |
| 49      | 1         | 1.2%    |
| 11      | 1         | 1.2%    |
| 8       | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 27        | 33.75%  |
| 301-350     | 24        | 30%     |
| 201-300     | 13        | 16.25%  |
| 701-800     | 5         | 6.25%   |
| 601-700     | 3         | 3.75%   |
| 351-400     | 3         | 3.75%   |
| 401-500     | 2         | 2.5%    |
| 101-200     | 1         | 1.25%   |
| 1001-1500   | 1         | 1.25%   |
| Unknown     | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 73.53%  |
| 16/10 | 9         | 13.24%  |
| 21/9  | 5         | 7.35%   |
| 5/4   | 2         | 2.94%   |
| 4/3   | 1         | 1.47%   |
| 3/2   | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 16.67%  |
| 201-250        | 14        | 16.67%  |
| 301-350        | 12        | 14.29%  |
| 101-110        | 10        | 11.9%   |
| 71-80          | 7         | 8.33%   |
| 351-500        | 7         | 8.33%   |
| 251-300        | 5         | 5.95%   |
| 61-70          | 4         | 4.76%   |
| 151-200        | 2         | 2.38%   |
| 141-150        | 2         | 2.38%   |
| 121-130        | 2         | 2.38%   |
| More than 1000 | 1         | 1.19%   |
| 51-60          | 1         | 1.19%   |
| 1-40           | 1         | 1.19%   |
| 131-140        | 1         | 1.19%   |
| Unknown        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 28.57%  |
| 161-240       | 20        | 25.97%  |
| 121-160       | 19        | 24.68%  |
| 101-120       | 9         | 11.69%  |
| More than 240 | 5         | 6.49%   |
| 1-50          | 1         | 1.3%    |
| Unknown       | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 62.03%  |
| 2     | 17        | 21.52%  |
| 0     | 10        | 12.66%  |
| 3     | 3         | 3.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 57        | 49.57%  |
| Realtek Semiconductor             | 43        | 37.39%  |
| Qualcomm Atheros                  | 2         | 1.74%   |
| Microsoft                         | 2         | 1.74%   |
| Aquantia                          | 2         | 1.74%   |
| TP-Link                           | 1         | 0.87%   |
| Texas Instruments                 | 1         | 0.87%   |
| Standard Microsystems             | 1         | 0.87%   |
| Qualcomm                          | 1         | 0.87%   |
| Oculus VR                         | 1         | 0.87%   |
| MediaTek                          | 1         | 0.87%   |
| Fibocom                           | 1         | 0.87%   |
| Ericsson Business Mobile Networks | 1         | 0.87%   |
| Broadcom                          | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 21.05%  |
| Intel Wi-Fi 6 AX200                                               | 15        | 11.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 8.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.76%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.76%   |
| Intel Wireless 8260                                               | 3         | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.26%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.5%    |
| Intel Wireless-AC 9260                                            | 2         | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 2         | 1.5%    |
| Intel Wireless 7265                                               | 2         | 1.5%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.5%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.5%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.5%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.5%    |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.75%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.75%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.75%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.75%   |
| Oculus VR Rift S                                                  | 1         | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.75%   |
| Intel Wireless 7260                                               | 1         | 0.75%   |
| Intel Wireless 3165                                               | 1         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.75%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.75%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.75%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 0.75%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 0.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.75%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 42        | 79.25%  |
| Realtek Semiconductor             | 2         | 3.77%   |
| Microsoft                         | 2         | 3.77%   |
| TP-Link                           | 1         | 1.89%   |
| Qualcomm Atheros                  | 1         | 1.89%   |
| Qualcomm                          | 1         | 1.89%   |
| MediaTek                          | 1         | 1.89%   |
| Fibocom                           | 1         | 1.89%   |
| Ericsson Business Mobile Networks | 1         | 1.89%   |
| Broadcom                          | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 15        | 28.3%   |
| Intel Wireless 8260                                        | 3         | 5.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3         | 5.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 5.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 3         | 5.66%   |
| Microsoft Xbox 360 Wireless Adapter                        | 2         | 3.77%   |
| Intel Wireless-AC 9260                                     | 2         | 3.77%   |
| Intel Wireless 8265 / 8275                                 | 2         | 3.77%   |
| Intel Wireless 7265                                        | 2         | 3.77%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 3.77%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 3.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.89%   |
| Qualcomm QCA6390 Wireless Network Adapter                  | 1         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1         | 1.89%   |
| Intel Wireless 7260                                        | 1         | 1.89%   |
| Intel Wireless 3165                                        | 1         | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 1.89%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 1.89%   |
| Ericsson Business Mobile Networks N5321 gw                 | 1         | 1.89%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 41        | 55.41%  |
| Intel                 | 29        | 39.19%  |
| Aquantia              | 2         | 2.7%    |
| Standard Microsystems | 1         | 1.35%   |
| Qualcomm Atheros      | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 35.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 14.1%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 6.41%   |
| Intel I211 Gigabit Network Connection                             | 5         | 6.41%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.56%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.56%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.56%   |
| Standard Microsystems Ethernet controller                         | 1         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.28%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.28%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.28%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.28%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.28%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.28%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.28%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 55.17%  |
| WiFi     | 50        | 43.1%   |
| Modem    | 2         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 50.62%  |
| WiFi     | 40        | 49.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 48.68%  |
| 2     | 34        | 44.74%  |
| 3     | 3         | 3.95%   |
| 0     | 2         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 77.63%  |
| Yes  | 17        | 22.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 74.51%  |
| Realtek Semiconductor           | 3         | 5.88%   |
| ASUSTek Computer                | 3         | 5.88%   |
| Cambridge Silicon Radio         | 2         | 3.92%   |
| Broadcom                        | 2         | 3.92%   |
| Qualcomm Atheros Communications | 1         | 1.96%   |
| MediaTek                        | 1         | 1.96%   |
| HTC (High Tech Computer)        | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 13        | 25.49%  |
| Intel Bluetooth wireless interface                                   | 8         | 15.69%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 6         | 11.76%  |
| Intel AX201 Bluetooth                                                | 5         | 9.8%    |
| Realtek Bluetooth Radio                                              | 3         | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 3.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 3.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 3.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 3.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.96%   |
| MediaTek Wireless_Device                                             | 1         | 1.96%   |
| Intel AX210 Bluetooth                                                | 1         | 1.96%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.96%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 45        | 34.62%  |
| AMD                                  | 32        | 24.62%  |
| Nvidia                               | 24        | 18.46%  |
| C-Media Electronics                  | 4         | 3.08%   |
| Texas Instruments                    | 3         | 2.31%   |
| Sennheiser Communications            | 3         | 2.31%   |
| Synaptics                            | 2         | 1.54%   |
| Kingston Technology                  | 2         | 1.54%   |
| Unknown                              | 1         | 0.77%   |
| Trust                                | 1         | 0.77%   |
| Thomann                              | 1         | 0.77%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.77%   |
| Sony                                 | 1         | 0.77%   |
| Schiit Audio                         | 1         | 0.77%   |
| Satechi                              | 1         | 0.77%   |
| Realtek Semiconductor                | 1         | 0.77%   |
| PreSonus Audio Electronics           | 1         | 0.77%   |
| Lenovo                               | 1         | 0.77%   |
| GYROCOM C&C                          | 1         | 0.77%   |
| Creative Technology                  | 1         | 0.77%   |
| Creative Labs                        | 1         | 0.77%   |
| Corsair                              | 1         | 0.77%   |
| Antlion Audio                        | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16        | 10.53%  |
| AMD Family 17h/19h HD Audio Controller                              | 10        | 6.58%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 9         | 5.92%   |
| Intel Sunrise Point-LP HD Audio                                     | 7         | 4.61%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 5         | 3.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 5         | 3.29%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 4         | 2.63%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 1.97%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3         | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.97%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 1.97%   |
| Intel Cannon Lake PCH cAVS                                          | 3         | 1.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 1.97%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 1.32%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 1.32%   |
| Sennheiser Communications Headset [PC 8]                            | 2         | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 1.32%   |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 1.32%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 1.32%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 1.32%   |
| C-Media Electronics USB Advanced Audio Device                       | 2         | 1.32%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2         | 1.32%   |
| Unknown USB Audio                                                   | 1         | 0.66%   |
| Trust USB microphone                                                | 1         | 0.66%   |
| Thomann SC450USB                                                    | 1         | 0.66%   |
| Thesycon Systemsoftware & Consulting U90                            | 1         | 0.66%   |
| Texas Instruments PCM2902C Audio CODEC                              | 1         | 0.66%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 0.66%   |
| Sennheiser Communications Sennheiser SC630 for Lync                 | 1         | 0.66%   |
| Schiit Audio Schiit Modi 3+                                         | 1         | 0.66%   |
| Satechi Audio & PD Adapter                                          | 1         | 0.66%   |
| Realtek Semiconductor USB Audio                                     | 1         | 0.66%   |
| PreSonus Audio Electronics AudioBox                                 | 1         | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 0.66%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                       | 1         | 0.66%   |
| Nvidia GM200 High Definition Audio                                  | 1         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 0.66%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                        | 1         | 0.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 0.66%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.66%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 0.66%   |
| GYROCOM C&C Fiio E10                                                | 1         | 0.66%   |
| Creative Technology Sound BlasterX G1                               | 1         | 0.66%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]          | 1         | 0.66%   |
| Corsair HS70 Pro Wireless Gaming Headset                            | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 23.53%  |
| Corsair             | 13        | 15.29%  |
| Micron Technology   | 12        | 14.12%  |
| Kingston            | 12        | 14.12%  |
| G.Skill             | 7         | 8.24%   |
| Crucial             | 7         | 8.24%   |
| Unknown (ABCD)      | 3         | 3.53%   |
| Unknown             | 3         | 3.53%   |
| SK hynix            | 3         | 3.53%   |
| Goodram             | 2         | 2.35%   |
| Strontium           | 1         | 1.18%   |
| Avant               | 1         | 1.18%   |
| AMD                 | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s              | 3         | 3.26%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.17%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 2         | 2.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 2         | 2.17%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 2         | 2.17%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s              | 2         | 2.17%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                 | 2         | 2.17%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s              | 2         | 2.17%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.09%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.09%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                       | 1         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 1         | 1.09%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                  | 1         | 1.09%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s    | 1         | 1.09%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.09%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 1.09%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 1.09%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.09%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.09%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                      | 1         | 1.09%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.09%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 1.09%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.09%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 1.09%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.09%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.09%   |
| Samsung RAM M393B2K70CM0-CF8 16GB DIMM DDR3 1066MT/s                | 1         | 1.09%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s                | 1         | 1.09%   |
| Samsung RAM K4EBE3 4EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.09%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s             | 1         | 1.09%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.09%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 1         | 1.09%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.09%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s                  | 1         | 1.09%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s                | 1         | 1.09%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 1         | 1.09%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.09%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 1         | 1.09%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s              | 1         | 1.09%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s                 | 1         | 1.09%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8GB SODIMM DDR3 1600MT/s             | 1         | 1.09%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s               | 1         | 1.09%   |
| Kingston RAM 9965684-028.A00G 8GB DIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s               | 1         | 1.09%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.09%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s              | 1         | 1.09%   |
| Goodram RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.09%   |
| Goodram RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s               | 1         | 1.09%   |
| Goodram RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s                 | 1         | 1.09%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                 | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 52        | 71.23%  |
| DDR3   | 10        | 13.7%   |
| LPDDR4 | 9         | 12.33%  |
| LPDDR3 | 2         | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 43.24%  |
| DIMM         | 32        | 43.24%  |
| Row Of Chips | 7         | 9.46%   |
| RIMM         | 1         | 1.35%   |
| Chip         | 1         | 1.35%   |
| Unknown      | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 38.75%  |
| 16384 | 30        | 37.5%   |
| 32768 | 10        | 12.5%   |
| 4096  | 8         | 10%     |
| 2048  | 1         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 23        | 28.4%   |
| 2133  | 10        | 12.35%  |
| 2667  | 8         | 9.88%   |
| 1600  | 8         | 9.88%   |
| 3600  | 6         | 7.41%   |
| 2400  | 6         | 7.41%   |
| 4267  | 4         | 4.94%   |
| 3000  | 3         | 3.7%    |
| 4266  | 2         | 2.47%   |
| 3334  | 2         | 2.47%   |
| 3733  | 1         | 1.23%   |
| 3466  | 1         | 1.23%   |
| 3400  | 1         | 1.23%   |
| 3266  | 1         | 1.23%   |
| 2933  | 1         | 1.23%   |
| 2134  | 1         | 1.23%   |
| 2132  | 1         | 1.23%   |
| 1333  | 1         | 1.23%   |
| 1066  | 1         | 1.23%   |

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
| Chicony Electronics           | 11        | 25%     |
| Logitech                      | 6         | 13.64%  |
| IMC Networks                  | 6         | 13.64%  |
| Microdia                      | 5         | 11.36%  |
| Acer                          | 4         | 9.09%   |
| Realtek Semiconductor         | 3         | 6.82%   |
| Sunplus Innovation Technology | 2         | 4.55%   |
| Quanta                        | 2         | 4.55%   |
| MacroSilicon                  | 2         | 4.55%   |
| SunplusIT                     | 1         | 2.27%   |
| Lite-On Technology            | 1         | 2.27%   |
| Apple                         | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Chicony Integrated Camera           | 7         | 15.56%  |
| Microdia Integrated_Webcam_HD       | 3         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam   | 3         | 6.67%   |
| IMC Networks Integrated Camera      | 3         | 6.67%   |
| Chicony HP HD Camera                | 3         | 6.67%   |
| Sunplus Integrated_Webcam_FHD       | 2         | 4.44%   |
| MacroSilicon USB Video              | 2         | 4.44%   |
| SunplusIT HP TrueVision HD Camera   | 1         | 2.22%   |
| Realtek Laptop Camera               | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD        | 1         | 2.22%   |
| Realtek EasyCamera                  | 1         | 2.22%   |
| Quanta HP True Vision HD Camera     | 1         | 2.22%   |
| Quanta HD WebCam                    | 1         | 2.22%   |
| Microdia USB 2.0 Camera             | 1         | 2.22%   |
| Microdia Camera                     | 1         | 2.22%   |
| Logitech Webcam C930e               | 1         | 2.22%   |
| Logitech Webcam C310                | 1         | 2.22%   |
| Logitech Webcam C270                | 1         | 2.22%   |
| Logitech StreamCam                  | 1         | 2.22%   |
| Logitech HD Pro Webcam C920         | 1         | 2.22%   |
| Logitech C930c                      | 1         | 2.22%   |
| Lite-On HP HD Camera                | 1         | 2.22%   |
| Chicony USB2.0 Camera               | 1         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE           | 1         | 2.22%   |
| Acer ThinkPad P50 Integrated Camera | 1         | 2.22%   |
| Acer SunplusIT Integrated Camera    | 1         | 2.22%   |
| Acer Integrated IR Camera           | 1         | 2.22%   |
| Acer Integrated Camera              | 1         | 2.22%   |
| Acer HD Webcam                      | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 53.85%  |
| Validity Sensors           | 4         | 30.77%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 30.77%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 15.38%  |
| Unknown                                           | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 88.89%  |
| Yubico.com  | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 8         | 88.89%  |
| Yubico.com Yubikey 4 U2F+CCID       | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 59.21%  |
| 1     | 19        | 25%     |
| 2     | 11        | 14.47%  |
| 4     | 1         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 25%     |
| Graphics card            | 8         | 18.18%  |
| Chipcard                 | 7         | 15.91%  |
| Multimedia controller    | 5         | 11.36%  |
| Unassigned class         | 3         | 6.82%   |
| Net/wireless             | 3         | 6.82%   |
| Camera                   | 2         | 4.55%   |
| Bluetooth                | 2         | 4.55%   |
| Network                  | 1         | 2.27%   |
| Dvb card                 | 1         | 2.27%   |
| Communication controller | 1         | 2.27%   |

