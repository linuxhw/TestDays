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

Total: 116

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [b9c698a94c](https://linux-hardware.org/?probe=b9c698a94c) | Sep 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
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
| NixOS 22.05                      | 32        | 35.16%  |
| NixOS 21.11                      | 18        | 19.78%  |
| NixOS 22.11                      | 6         | 6.59%   |
| NixOS                            | 5         | 5.49%   |
| NixOS 21.05pre-git               | 2         | 2.2%    |
| NixOS 20.09pre-git               | 2         | 2.2%    |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.1%    |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.1%    |
| NixOS 21.11.20210528.540dccb     | 1         | 1.1%    |
| NixOS 21.05.git.62d4591722f      | 1         | 1.1%    |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 1.1%    |
| NixOS 21.05.993.93963c27b93      | 1         | 1.1%    |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.1%    |
| NixOS 21.05.3509.7daf35532d2     | 1         | 1.1%    |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.1%    |
| NixOS 21.05.2132.733682c3292     | 1         | 1.1%    |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 1.1%    |
| NixOS 21.05.20210929.ee90403     | 1         | 1.1%    |
| NixOS 21.05.20210430.c8dff32     | 1         | 1.1%    |
| NixOS 21.05.20210423.c21475e     | 1         | 1.1%    |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 1.1%    |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 1.1%    |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 1.1%    |
| NixOS 21.03.git.b4349c13a6d      | 1         | 1.1%    |
| NixOS 21.03.20201007.420f89c     | 1         | 1.1%    |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.1%    |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 1.1%    |
| NixOS 20.09.git.4a361b06a93      | 1         | 1.1%    |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.1%    |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.1%    |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.1%    |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.15.43         | 4         | 4.26%   |
| 5.15.47         | 3         | 3.19%   |
| 5.15.26         | 3         | 3.19%   |
| 5.8.1-zen1      | 2         | 2.13%   |
| 5.18.19         | 2         | 2.13%   |
| 5.17.1          | 2         | 2.13%   |
| 5.16.8-zen1     | 2         | 2.13%   |
| 5.16.15         | 2         | 2.13%   |
| 5.15.68         | 2         | 2.13%   |
| 5.15.64         | 2         | 2.13%   |
| 5.15.32         | 2         | 2.13%   |
| 5.15.25         | 2         | 2.13%   |
| 5.13.7          | 2         | 2.13%   |
| 5.13.2          | 2         | 2.13%   |
| 5.12.15         | 2         | 2.13%   |
| 5.10.102        | 2         | 2.13%   |
| 5.8.4           | 1         | 1.06%   |
| 5.8.16-hardened | 1         | 1.06%   |
| 5.8.11          | 1         | 1.06%   |
| 5.8.10          | 1         | 1.06%   |
| 5.7.4           | 1         | 1.06%   |
| 5.7.19          | 1         | 1.06%   |
| 5.7.17          | 1         | 1.06%   |
| 5.4.94          | 1         | 1.06%   |
| 5.4.72          | 1         | 1.06%   |
| 5.4.69          | 1         | 1.06%   |
| 5.4.50          | 1         | 1.06%   |
| 5.4.47          | 1         | 1.06%   |
| 5.4.24          | 1         | 1.06%   |
| 5.4.209         | 1         | 1.06%   |
| 5.4.187         | 1         | 1.06%   |
| 5.19.5          | 1         | 1.06%   |
| 5.19.11         | 1         | 1.06%   |
| 5.19.0          | 1         | 1.06%   |
| 5.18.7-zen1     | 1         | 1.06%   |
| 5.18.14-lqx2    | 1         | 1.06%   |
| 5.18.0          | 1         | 1.06%   |
| 5.17.0          | 1         | 1.06%   |
| 5.16.7          | 1         | 1.06%   |
| 5.16.3          | 1         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.43  | 4         | 4.26%   |
| 5.15.47  | 3         | 3.19%   |
| 5.15.26  | 3         | 3.19%   |
| 5.8.1    | 2         | 2.13%   |
| 5.18.19  | 2         | 2.13%   |
| 5.17.1   | 2         | 2.13%   |
| 5.16.8   | 2         | 2.13%   |
| 5.16.15  | 2         | 2.13%   |
| 5.15.68  | 2         | 2.13%   |
| 5.15.64  | 2         | 2.13%   |
| 5.15.32  | 2         | 2.13%   |
| 5.15.25  | 2         | 2.13%   |
| 5.13.7   | 2         | 2.13%   |
| 5.13.2   | 2         | 2.13%   |
| 5.12.15  | 2         | 2.13%   |
| 5.11.16  | 2         | 2.13%   |
| 5.10.102 | 2         | 2.13%   |
| 5.8.4    | 1         | 1.06%   |
| 5.8.16   | 1         | 1.06%   |
| 5.8.11   | 1         | 1.06%   |
| 5.8.10   | 1         | 1.06%   |
| 5.7.4    | 1         | 1.06%   |
| 5.7.19   | 1         | 1.06%   |
| 5.7.17   | 1         | 1.06%   |
| 5.4.94   | 1         | 1.06%   |
| 5.4.72   | 1         | 1.06%   |
| 5.4.69   | 1         | 1.06%   |
| 5.4.50   | 1         | 1.06%   |
| 5.4.47   | 1         | 1.06%   |
| 5.4.24   | 1         | 1.06%   |
| 5.4.209  | 1         | 1.06%   |
| 5.4.187  | 1         | 1.06%   |
| 5.19.5   | 1         | 1.06%   |
| 5.19.11  | 1         | 1.06%   |
| 5.19.0   | 1         | 1.06%   |
| 5.18.7   | 1         | 1.06%   |
| 5.18.14  | 1         | 1.06%   |
| 5.18.0   | 1         | 1.06%   |
| 5.17.0   | 1         | 1.06%   |
| 5.16.7   | 1         | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 30        | 32.61%  |
| 5.10    | 14        | 15.22%  |
| 5.16    | 8         | 8.7%    |
| 5.4     | 7         | 7.61%   |
| 5.8     | 6         | 6.52%   |
| 5.18    | 5         | 5.43%   |
| 5.13    | 4         | 4.35%   |
| 5.7     | 3         | 3.26%   |
| 5.19    | 3         | 3.26%   |
| 5.17    | 3         | 3.26%   |
| 5.12    | 3         | 3.26%   |
| 5.14    | 2         | 2.17%   |
| 5.11    | 2         | 2.17%   |
| 4.19    | 2         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 83        | 97.65%  |
| aarch64 | 2         | 2.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 69        | 79.31%  |
| XFCE         | 5         | 5.75%   |
| KDE          | 4         | 4.6%    |
| GNOME        | 4         | 4.6%    |
| sway         | 3         | 3.45%   |
| none+xmonad  | 1         | 1.15%   |
| none+awesome | 1         | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 63        | 71.59%  |
| X11     | 12        | 13.64%  |
| Wayland | 8         | 9.09%   |
| Tty     | 5         | 5.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 84.88%  |
| LightDM | 8         | 9.3%    |
| GDM     | 3         | 3.49%   |
| SDDM    | 2         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 60%     |
| en_US   | 24        | 28.24%  |
| ru_RU   | 2         | 2.35%   |
| en_GB   | 2         | 2.35%   |
| en_DK   | 2         | 2.35%   |
| de_CH   | 2         | 2.35%   |
| ro_RO   | 1         | 1.18%   |
| pt_BR   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 70        | 81.4%   |
| BIOS | 16        | 18.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 50.57%  |
| Btrfs   | 12        | 13.79%  |
| Tmpfs   | 10        | 11.49%  |
| Zfs     | 8         | 9.2%    |
| Xfs     | 6         | 6.9%    |
| Unknown | 6         | 6.9%    |
| Ext2    | 1         | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 79        | 90.8%   |
| Unknown | 7         | 8.05%   |
| MBR     | 1         | 1.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 72.09%  |
| Yes       | 24        | 27.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 63.53%  |
| Yes       | 31        | 36.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 21        | 24.71%  |
| Lenovo                  | 17        | 20%     |
| Dell                    | 11        | 12.94%  |
| MSI                     | 8         | 9.41%   |
| Hewlett-Packard         | 6         | 7.06%   |
| Gigabyte Technology     | 5         | 5.88%   |
| ASRock                  | 4         | 4.71%   |
| Raspberry Pi Foundation | 2         | 2.35%   |
| Acer                    | 2         | 2.35%   |
| Teclast                 | 1         | 1.18%   |
| Supermicro              | 1         | 1.18%   |
| OBSIDIAN-PC             | 1         | 1.18%   |
| Intel                   | 1         | 1.18%   |
| Hardkernel              | 1         | 1.18%   |
| GPD                     | 1         | 1.18%   |
| Framework               | 1         | 1.18%   |
| EVGA                    | 1         | 1.18%   |
| Apple                   | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 2         | 2.35%   |
| Dell Latitude 7420                    | 2         | 2.35%   |
| Teclast F5                            | 1         | 1.18%   |
| Supermicro X8DT6                      | 1         | 1.18%   |
| RPi Raspberry Pi 4 Model B Rev 1.5    | 1         | 1.18%   |
| RPi Raspberry Pi 3 Model B+           | 1         | 1.18%   |
| OBSIDIAN-PC N13_N140ZU                | 1         | 1.18%   |
| MSI MS-7C95                           | 1         | 1.18%   |
| MSI MS-7C84                           | 1         | 1.18%   |
| MSI MS-7C35                           | 1         | 1.18%   |
| MSI MS-7B89                           | 1         | 1.18%   |
| MSI MS-7B09                           | 1         | 1.18%   |
| MSI Bravo 15 B5DD                     | 1         | 1.18%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 1.18%   |
| Lenovo Yoga 520-14IKB 81C8            | 1         | 1.18%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 1.18%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 1.18%   |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 1.18%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 1.18%   |
| Lenovo ThinkPad X230 23243E9          | 1         | 1.18%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW | 1         | 1.18%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 1.18%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 1.18%   |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 1.18%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 1.18%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 1.18%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 1.18%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 1.18%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 1.18%   |
| Intel NUC11PAHi7                      | 1         | 1.18%   |
| HP ZBook Studio G5                    | 1         | 1.18%   |
| HP Spectre x360 Convertible 15-eb0xxx | 1         | 1.18%   |
| HP ProBook 450 G4                     | 1         | 1.18%   |
| HP ProBook 445 G7                     | 1         | 1.18%   |
| HP EliteDesk 800 G2 DM 35W            | 1         | 1.18%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 1.18%   |
| Hardkernel ODROID-H2                  | 1         | 1.18%   |
| GPD MicroPC                           | 1         | 1.18%   |
| Gigabyte X570 AORUS ELITE             | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 14        | 16.47%  |
| ASUS ROG             | 6         | 7.06%   |
| ASUS PRIME           | 5         | 5.88%   |
| Dell XPS             | 4         | 4.71%   |
| RPi Raspberry        | 2         | 2.35%   |
| MSI MS-7C37          | 2         | 2.35%   |
| Lenovo Yoga          | 2         | 2.35%   |
| HP ProBook           | 2         | 2.35%   |
| Dell Precision       | 2         | 2.35%   |
| Dell Latitude        | 2         | 2.35%   |
| Dell Inspiron        | 2         | 2.35%   |
| ASUS ZenBook         | 2         | 2.35%   |
| Teclast F5           | 1         | 1.18%   |
| Supermicro X8DT6     | 1         | 1.18%   |
| OBSIDIAN-PC N13      | 1         | 1.18%   |
| MSI MS-7C95          | 1         | 1.18%   |
| MSI MS-7C84          | 1         | 1.18%   |
| MSI MS-7C35          | 1         | 1.18%   |
| MSI MS-7B89          | 1         | 1.18%   |
| MSI MS-7B09          | 1         | 1.18%   |
| MSI Bravo            | 1         | 1.18%   |
| Lenovo Legion        | 1         | 1.18%   |
| Intel NUC11PAHi7     | 1         | 1.18%   |
| HP ZBook             | 1         | 1.18%   |
| HP Spectre           | 1         | 1.18%   |
| HP EliteDesk         | 1         | 1.18%   |
| HP EliteBook         | 1         | 1.18%   |
| Hardkernel ODROID-H2 | 1         | 1.18%   |
| GPD MicroPC          | 1         | 1.18%   |
| Gigabyte X570        | 1         | 1.18%   |
| Gigabyte X470        | 1         | 1.18%   |
| Gigabyte Sabre       | 1         | 1.18%   |
| Gigabyte H97M-D3H    | 1         | 1.18%   |
| Gigabyte B550I       | 1         | 1.18%   |
| Framework Laptop     | 1         | 1.18%   |
| EVGA X299            | 1         | 1.18%   |
| Dell PowerEdge       | 1         | 1.18%   |
| ASUS Z170-P          | 1         | 1.18%   |
| ASUS TUF             | 1         | 1.18%   |
| ASUS PRO602617       | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 21        | 24.71%  |
| 2019    | 14        | 16.47%  |
| 2018    | 12        | 14.12%  |
| 2021    | 9         | 10.59%  |
| 2016    | 9         | 10.59%  |
| 2017    | 5         | 5.88%   |
| 2015    | 4         | 4.71%   |
| 2013    | 3         | 3.53%   |
| 2014    | 2         | 2.35%   |
| 2012    | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| 2022    | 1         | 1.18%   |
| 2010    | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 40        | 47.06%  |
| Desktop        | 35        | 41.18%  |
| Convertible    | 5         | 5.88%   |
| System on chip | 2         | 2.35%   |
| Server         | 2         | 2.35%   |
| Mini pc        | 1         | 1.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 85        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 98.82%  |
| Yes  | 1         | 1.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 26        | 30.23%  |
| 16.01-24.0  | 20        | 23.26%  |
| 64.01-256.0 | 15        | 17.44%  |
| 8.01-16.0   | 12        | 13.95%  |
| 4.01-8.0    | 6         | 6.98%   |
| 24.01-32.0  | 4         | 4.65%   |
| 3.01-4.0    | 1         | 1.16%   |
| 1.01-2.0    | 1         | 1.16%   |
| 0.51-1.0    | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 27.17%  |
| 8.01-16.0   | 20        | 21.74%  |
| 3.01-4.0    | 13        | 14.13%  |
| 2.01-3.0    | 8         | 8.7%    |
| 32.01-64.0  | 6         | 6.52%   |
| 1.01-2.0    | 6         | 6.52%   |
| 16.01-24.0  | 5         | 5.43%   |
| 24.01-32.0  | 4         | 4.35%   |
| 0.51-1.0    | 3         | 3.26%   |
| 64.01-256.0 | 1         | 1.09%   |
| 0.01-0.5    | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 50%     |
| 2      | 23        | 26.14%  |
| 3      | 9         | 10.23%  |
| 6      | 4         | 4.55%   |
| 5      | 3         | 3.41%   |
| 17     | 1         | 1.14%   |
| 11     | 1         | 1.14%   |
| 8      | 1         | 1.14%   |
| 4      | 1         | 1.14%   |
| 0      | 1         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 89.41%  |
| Yes       | 9         | 10.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 80.46%  |
| No        | 17        | 19.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 65.88%  |
| No        | 29        | 34.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 65.52%  |
| No        | 30        | 34.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 13        | 15.29%  |
| Germany     | 11        | 12.94%  |
| UK          | 8         | 9.41%   |
| Poland      | 7         | 8.24%   |
| Russia      | 6         | 7.06%   |
| France      | 6         | 7.06%   |
| Ukraine     | 5         | 5.88%   |
| Canada      | 5         | 5.88%   |
| Switzerland | 3         | 3.53%   |
| Austria     | 3         | 3.53%   |
| Belgium     | 2         | 2.35%   |
| Uruguay     | 1         | 1.18%   |
| Sweden      | 1         | 1.18%   |
| Spain       | 1         | 1.18%   |
| Serbia      | 1         | 1.18%   |
| Romania     | 1         | 1.18%   |
| Portugal    | 1         | 1.18%   |
| New Zealand | 1         | 1.18%   |
| Netherlands | 1         | 1.18%   |
| Iraq        | 1         | 1.18%   |
| Iran        | 1         | 1.18%   |
| India       | 1         | 1.18%   |
| Hungary     | 1         | 1.18%   |
| Denmark     | 1         | 1.18%   |
| Czechia     | 1         | 1.18%   |
| Colombia    | 1         | 1.18%   |
| Brazil      | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Marki              | 4         | 4.6%    |
| Vienna             | 3         | 3.45%   |
| Plymouth           | 3         | 3.45%   |
| Kharkiv            | 3         | 3.45%   |
| South Deerfield    | 2         | 2.3%    |
| Schaafheim         | 2         | 2.3%    |
| Richardson         | 2         | 2.3%    |
| Lyon               | 2         | 2.3%    |
| London             | 2         | 2.3%    |
| Halifax            | 2         | 2.3%    |
| Gdansk             | 2         | 2.3%    |
| Frankfurt am Main  | 2         | 2.3%    |
| Darmstadt          | 2         | 2.3%    |
| Chelyabinsk        | 2         | 2.3%    |
| Woodford           | 1         | 1.15%   |
| Wellington         | 1         | 1.15%   |
| Villeurbanne       | 1         | 1.15%   |
| Verneuil-sur-Seine | 1         | 1.15%   |
| Valpacos           | 1         | 1.15%   |
| Tottenham          | 1         | 1.15%   |
| Tolyatti           | 1         | 1.15%   |
| Tehran             | 1         | 1.15%   |
| Székesfehérvár  | 1         | 1.15%   |
| Stockholm          | 1         | 1.15%   |
| Southampton        | 1         | 1.15%   |
| Sindelfingen       | 1         | 1.15%   |
| Saratov            | 1         | 1.15%   |
| San Gabriel        | 1         | 1.15%   |
| Redwood City       | 1         | 1.15%   |
| Ramenskoye         | 1         | 1.15%   |
| Popice             | 1         | 1.15%   |
| Ottawa             | 1         | 1.15%   |
| Osasco             | 1         | 1.15%   |
| Oberkempten        | 1         | 1.15%   |
| Oakville           | 1         | 1.15%   |
| Nantes             | 1         | 1.15%   |
| Mykolayiv          | 1         | 1.15%   |
| Montreal           | 1         | 1.15%   |
| Montevideo         | 1         | 1.15%   |
| Mons               | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 75     | 29.63%  |
| WDC                 | 13        | 25     | 9.63%   |
| Toshiba             | 12        | 17     | 8.89%   |
| Seagate             | 11        | 18     | 8.15%   |
| Crucial             | 9         | 11     | 6.67%   |
| Kingston            | 8         | 8      | 5.93%   |
| SanDisk             | 7         | 11     | 5.19%   |
| Intel               | 7         | 10     | 5.19%   |
| Unknown             | 3         | 3      | 2.22%   |
| SK hynix            | 3         | 4      | 2.22%   |
| HGST                | 3         | 7      | 2.22%   |
| Transcend           | 2         | 2      | 1.48%   |
| Plextor             | 2         | 2      | 1.48%   |
| Micron Technology   | 2         | 2      | 1.48%   |
| KIOXIA              | 2         | 3      | 1.48%   |
| Teclast             | 1         | 1      | 0.74%   |
| Phison Electronics  | 1         | 2      | 0.74%   |
| Phison              | 1         | 1      | 0.74%   |
| Lexar               | 1         | 1      | 0.74%   |
| INNOVATION IT       | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| BIWIN               | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |
| ASMedia             | 1         | 1      | 0.74%   |
| Apple               | 1         | 3      | 0.74%   |
| ADATA Technology    | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB              | 5         | 3.16%   |
| SanDisk SSD PLUS 240GB               | 3         | 1.9%    |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 1.9%    |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.9%    |
| Samsung SSD 970 EVO 500GB            | 3         | 1.9%    |
| Crucial CT1000MX500SSD1 1TB          | 3         | 1.9%    |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 1.27%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.27%   |
| Samsung SSD 970 EVO 1TB              | 2         | 1.27%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.27%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.27%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.27%   |
| Samsung SSD 860 EVO 2TB              | 2         | 1.27%   |
| Samsung PM9A1 NVMe 1024GB            | 2         | 1.27%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.27%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 1.27%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.27%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.63%   |
| WDC WDS200T1X0E-00AFY0 2TB           | 1         | 0.63%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.63%   |
| WDC WD120EMFZ-11A6JA0 12TB           | 1         | 0.63%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1         | 0.63%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.63%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.63%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.63%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.63%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 0.63%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.63%   |
| Unknown MMC Card  8GB                | 1         | 0.63%   |
| Unknown MMC Card  32GB               | 1         | 0.63%   |
| Unknown MMC Card  16GB               | 1         | 0.63%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 0.63%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 0.63%   |
| Toshiba TR150 960GB SSD              | 1         | 0.63%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.63%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.63%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 18     | 39.29%  |
| WDC     | 7         | 17     | 25%     |
| Toshiba | 7         | 12     | 25%     |
| HGST    | 3         | 7      | 10.71%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 36     | 32.73%  |
| Crucial             | 8         | 10     | 14.55%  |
| SanDisk             | 5         | 8      | 9.09%   |
| Kingston            | 5         | 5      | 9.09%   |
| Intel               | 5         | 7      | 9.09%   |
| WDC                 | 2         | 3      | 3.64%   |
| Transcend           | 2         | 2      | 3.64%   |
| Toshiba             | 1         | 1      | 1.82%   |
| Teclast             | 1         | 1      | 1.82%   |
| Plextor             | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| INNOVATION IT       | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| BIWIN               | 1         | 1      | 1.82%   |
| ASMT                | 1         | 1      | 1.82%   |
| ASMedia             | 1         | 1      | 1.82%   |
| Apple               | 1         | 3      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 72     | 43.33%  |
| SSD  | 44        | 83     | 36.67%  |
| HDD  | 21        | 54     | 17.5%   |
| MMC  | 3         | 3      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 72     | 48.15%  |
| SATA | 49        | 132    | 45.37%  |
| SAS  | 4         | 5      | 3.7%    |
| MMC  | 3         | 3      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 52     | 44%     |
| 0.51-1.0   | 23        | 40     | 30.67%  |
| 1.01-2.0   | 6         | 9      | 8%      |
| 2.01-3.0   | 5         | 7      | 6.67%   |
| 4.01-10.0  | 5         | 19     | 6.67%   |
| 3.01-4.0   | 2         | 4      | 2.67%   |
| 10.01-20.0 | 1         | 6      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 56        | 65.12%  |
| 1-20           | 14        | 16.28%  |
| 501-1000       | 5         | 5.81%   |
| 2001-3000      | 3         | 3.49%   |
| 101-250        | 3         | 3.49%   |
| More than 3000 | 2         | 2.33%   |
| 1001-2000      | 2         | 2.33%   |
| 251-500        | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 56        | 65.12%  |
| 1-20           | 18        | 20.93%  |
| 101-250        | 4         | 4.65%   |
| 1001-2000      | 3         | 3.49%   |
| 251-500        | 2         | 2.33%   |
| 501-1000       | 2         | 2.33%   |
| More than 3000 | 1         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 11.11%  |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 11.11%  |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 1      | 11.11%  |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 11.11%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 11.11%  |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 11.11%  |
| ASMT 2115 1TB                                  | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| SK hynix            | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Micron Technology   | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| ASMT                | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 5      | 55.56%  |
| NVMe | 2         | 2      | 22.22%  |
| HDD  | 2         | 2      | 22.22%  |

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
| Works    | 79        | 183    | 80.61%  |
| Detected | 12        | 20     | 12.24%  |
| Malfunc  | 7         | 9      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 42        | 33.07%  |
| Samsung Electronics          | 28        | 22.05%  |
| AMD                          | 22        | 17.32%  |
| SanDisk                      | 7         | 5.51%   |
| Toshiba America Info Systems | 4         | 3.15%   |
| Kingston Technology Company  | 4         | 3.15%   |
| SK hynix                     | 3         | 2.36%   |
| Broadcom / LSI               | 3         | 2.36%   |
| ASMedia Technology           | 3         | 2.36%   |
| Phison Electronics           | 2         | 1.57%   |
| LSI Logic / Symbios Logic    | 2         | 1.57%   |
| KIOXIA                       | 2         | 1.57%   |
| Shenzhen Longsys Electronics | 1         | 0.79%   |
| Micron/Crucial Technology    | 1         | 0.79%   |
| Micron Technology            | 1         | 0.79%   |
| Lite-On Technology           | 1         | 0.79%   |
| ADATA Technology             | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 19        | 13.97%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 11.03%  |
| AMD 500 Series Chipset SATA Controller                                           | 6         | 4.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 3.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 2.94%   |
| SK hynix Gold P31 SSD                                                            | 3         | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.21%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.21%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 2.21%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 2.21%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.47%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.47%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.47%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.47%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.47%   |
| Intel Comet Lake PCH-H RAID                                                      | 2         | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 1.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.47%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 1.47%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.74%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.74%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.74%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.74%   |
| Samsung Electronics SATA controller                                              | 1         | 0.74%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 0.74%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.74%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                   | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 54        | 43.9%   |
| NVMe | 53        | 43.09%  |
| RAID | 8         | 6.5%    |
| SAS  | 5         | 4.07%   |
| IDE  | 3         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 62.35%  |
| AMD    | 30        | 35.29%  |
| ARM    | 2         | 2.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 5.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 3.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 3.53%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 3.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 3.53%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 3.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 2.35%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 2.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 2.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 2.35%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 2.35%   |
| ARM Processor                              | 2         | 2.35%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 2.35%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 2.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 2         | 2.35%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 2.35%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 1.18%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.18%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 1.18%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 1.18%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 1.18%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 1         | 1.18%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 1.18%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.18%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 1.18%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.18%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.18%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 1.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 1         | 1.18%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 1.18%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 1         | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 1.18%   |
| Intel Core i5-7600K CPU @ 3.80GHz          | 1         | 1.18%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 1         | 1.18%   |
| Intel Core i5-4570S CPU @ 2.90GHz          | 1         | 1.18%   |
| Intel Core i5-3570K CPU @ 3.40GHz          | 1         | 1.18%   |
| Intel Core i5-3470T CPU @ 2.90GHz          | 1         | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 23        | 27.06%  |
| AMD Ryzen 7            | 12        | 14.12%  |
| Other                  | 10        | 11.76%  |
| Intel Core i5          | 10        | 11.76%  |
| AMD Ryzen 5            | 8         | 9.41%   |
| Intel Xeon             | 5         | 5.88%   |
| AMD Ryzen 9            | 5         | 5.88%   |
| Intel Core i3          | 3         | 3.53%   |
| Intel Celeron          | 3         | 3.53%   |
| AMD Ryzen 7 PRO        | 3         | 3.53%   |
| AMD Ryzen Threadripper | 2         | 2.35%   |
| Intel Core i9          | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 30        | 35.29%  |
| 8       | 17        | 20%     |
| 6       | 16        | 18.82%  |
| 2       | 9         | 10.59%  |
| 12      | 5         | 5.88%   |
| 16      | 2         | 2.35%   |
| 10      | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| 32      | 1         | 1.18%   |
| 24      | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 81        | 95.29%  |
| 2       | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 74        | 87.06%  |
| 1       | 9         | 10.59%  |
| Unknown | 2         | 2.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 98.84%  |
| Unknown        | 1         | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 16.09%  |
| 0x08701021 | 7         | 8.05%   |
| 0x806c1    | 5         | 5.75%   |
| 0x0a50000c | 5         | 5.75%   |
| 0x906ea    | 4         | 4.6%    |
| 0x806ec    | 4         | 4.6%    |
| 0x806ea    | 4         | 4.6%    |
| 0x306c3    | 4         | 4.6%    |
| 0x08701013 | 4         | 4.6%    |
| 0x506e3    | 3         | 3.45%   |
| 0x306a9    | 3         | 3.45%   |
| 0x08600106 | 3         | 3.45%   |
| 0x906e9    | 2         | 2.3%    |
| 0x806eb    | 2         | 2.3%    |
| 0x706a1    | 2         | 2.3%    |
| 0x406e3    | 2         | 2.3%    |
| 0x0a201204 | 2         | 2.3%    |
| 0x0a201009 | 2         | 2.3%    |
| 0xa0653    | 1         | 1.15%   |
| 0xa0652    | 1         | 1.15%   |
| 0x906a3    | 1         | 1.15%   |
| 0x806e9    | 1         | 1.15%   |
| 0x806d1    | 1         | 1.15%   |
| 0x406f1    | 1         | 1.15%   |
| 0x40661    | 1         | 1.15%   |
| 0x306f2    | 1         | 1.15%   |
| 0x306d4    | 1         | 1.15%   |
| 0x206c2    | 1         | 1.15%   |
| 0x0a50000b | 1         | 1.15%   |
| 0x08600104 | 1         | 1.15%   |
| 0x08301025 | 1         | 1.15%   |
| 0x0800820d | 1         | 1.15%   |
| 0x08001137 | 1         | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 22.35%  |
| Zen 2            | 17        | 20%     |
| Zen 3            | 10        | 11.76%  |
| Skylake          | 7         | 8.24%   |
| TigerLake        | 6         | 7.06%   |
| Haswell          | 6         | 7.06%   |
| IvyBridge        | 3         | 3.53%   |
| Goldmont plus    | 3         | 3.53%   |
| CometLake        | 3         | 3.53%   |
| Zen+             | 2         | 2.35%   |
| Westmere         | 2         | 2.35%   |
| Broadwell        | 2         | 2.35%   |
| Unknown          | 2         | 2.35%   |
| Zen              | 1         | 1.18%   |
| Icelake          | 1         | 1.18%   |
| Alderlake Hybrid | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 41        | 39.81%  |
| Nvidia                     | 37        | 35.92%  |
| AMD                        | 23        | 22.33%  |
| Matrox Electronics Systems | 2         | 1.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                   | 6         | 5.77%   |
| AMD Cezanne                                                 | 6         | 5.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]     | 5         | 4.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]     | 5         | 4.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 4         | 3.85%   |
| Intel HD Graphics 530                                       | 4         | 3.85%   |
| AMD Renoir                                                  | 4         | 3.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 3         | 2.88%   |
| Intel UHD Graphics 620                                      | 3         | 2.88%   |
| Intel GeminiLake [UHD Graphics 600]                         | 3         | 2.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                        | 3         | 2.88%   |
| Nvidia TU106 [GeForce RTX 2070]                             | 2         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                               | 2         | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                         | 2         | 1.92%   |
| Nvidia GK104 [GeForce GTX 760]                              | 2         | 1.92%   |
| Matrox Electronics Systems MGA G200eW WPCM450               | 2         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 2         | 1.92%   |
| Intel HD Graphics 630                                       | 2         | 1.92%   |
| Intel HD Graphics 620                                       | 2         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 2         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 2         | 1.92%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                    | 2         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                  | 1         | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                  | 1         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                          | 1         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                       | 1         | 0.96%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                       | 1         | 0.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                       | 1         | 0.96%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                       | 1         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                          | 1         | 0.96%   |
| Nvidia GP104 [GeForce GTX 1080]                             | 1         | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070]                             | 1         | 0.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                          | 1         | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                              | 1         | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                              | 1         | 0.96%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                           | 1         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                               | 1         | 0.96%   |
| Nvidia GM108M [GeForce 930MX]                               | 1         | 0.96%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 0.96%   |
| Nvidia GK208M [GeForce GT 730M]                             | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 31.76%  |
| 1 x Nvidia     | 17        | 20%     |
| 1 x AMD        | 15        | 17.65%  |
| Intel + Nvidia | 13        | 15.29%  |
| AMD + Nvidia   | 7         | 8.24%   |
| Other          | 3         | 3.53%   |
| 1 x Matrox     | 2         | 2.35%   |
| 2 x AMD        | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 74.12%  |
| Proprietary | 18        | 21.18%  |
| Unknown     | 4         | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 65.52%  |
| 7.01-8.0   | 9         | 10.34%  |
| 0.01-0.5   | 8         | 9.2%    |
| 1.01-2.0   | 6         | 6.9%    |
| 3.01-4.0   | 5         | 5.75%   |
| 8.01-16.0  | 1         | 1.15%   |
| 0.51-1.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 16        | 17.58%  |
| AU Optronics         | 10        | 10.99%  |
| Goldstar             | 8         | 8.79%   |
| Samsung Electronics  | 7         | 7.69%   |
| LG Display           | 7         | 7.69%   |
| Chimei Innolux       | 5         | 5.49%   |
| BOE                  | 5         | 5.49%   |
| Sharp                | 4         | 4.4%    |
| PANDA                | 4         | 4.4%    |
| Acer                 | 4         | 4.4%    |
| InfoVision           | 2         | 2.2%    |
| Hewlett-Packard      | 2         | 2.2%    |
| AOC                  | 2         | 2.2%    |
| Ancor Communications | 2         | 2.2%    |
| Vizio                | 1         | 1.1%    |
| Unknown (AAA)        | 1         | 1.1%    |
| Philips              | 1         | 1.1%    |
| Panasonic            | 1         | 1.1%    |
| MPI                  | 1         | 1.1%    |
| Lenovo               | 1         | 1.1%    |
| JDI                  | 1         | 1.1%    |
| Iiyama               | 1         | 1.1%    |
| HVR                  | 1         | 1.1%    |
| Eizo                 | 1         | 1.1%    |
| BenQ                 | 1         | 1.1%    |
| ASUSTek Computer     | 1         | 1.1%    |
| Apple                | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2         | 2.13%   |
| Dell U2717D DEL40EB 2560x1440 600x340mm 27.2-inch                       | 2         | 2.13%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 2         | 2.13%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                       | 2         | 2.13%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                       | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch          | 2         | 2.13%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                    | 2         | 2.13%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1         | 1.06%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch             | 1         | 1.06%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                 | 1         | 1.06%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1         | 1.06%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch       | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.06%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1         | 1.06%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 1.06%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1         | 1.06%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 1.06%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                 | 1         | 1.06%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                 | 1         | 1.06%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 1.06%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                | 1         | 1.06%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                        | 1         | 1.06%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.06%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1.06%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                   | 1         | 1.06%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch             | 1         | 1.06%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch                 | 1         | 1.06%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 42.53%  |
| 3840x2160 (4K)    | 17        | 19.54%  |
| 2560x1440 (QHD)   | 11        | 12.64%  |
| 2560x1080         | 4         | 4.6%    |
| 1366x768 (WXGA)   | 4         | 4.6%    |
| 1920x1200 (WUXGA) | 3         | 3.45%   |
| 2880x1800         | 2         | 2.3%    |
| 1280x1024 (SXGA)  | 2         | 2.3%    |
| 3840x2400         | 1         | 1.15%   |
| 3440x1440         | 1         | 1.15%   |
| 2560x1600         | 1         | 1.15%   |
| 2256x1504         | 1         | 1.15%   |
| 2160x1200         | 1         | 1.15%   |
| 1440x900 (WXGA+)  | 1         | 1.15%   |
| 1280x720 (HD)     | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 15.56%  |
| 27      | 13        | 14.44%  |
| 14      | 11        | 12.22%  |
| 13      | 11        | 12.22%  |
| 24      | 8         | 8.89%   |
| 23      | 8         | 8.89%   |
| 34      | 5         | 5.56%   |
| 17      | 5         | 5.56%   |
| 12      | 4         | 4.44%   |
| 31      | 2         | 2.22%   |
| 25      | 2         | 2.22%   |
| 21      | 2         | 2.22%   |
| 84      | 1         | 1.11%   |
| 49      | 1         | 1.11%   |
| 11      | 1         | 1.11%   |
| 8       | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 33.33%  |
| 501-600     | 28        | 32.18%  |
| 201-300     | 13        | 14.94%  |
| 701-800     | 5         | 5.75%   |
| 601-700     | 3         | 3.45%   |
| 351-400     | 3         | 3.45%   |
| 401-500     | 2         | 2.3%    |
| 1501-2000   | 1         | 1.15%   |
| 101-200     | 1         | 1.15%   |
| 1001-1500   | 1         | 1.15%   |
| Unknown     | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 55        | 74.32%  |
| 16/10 | 10        | 13.51%  |
| 21/9  | 5         | 6.76%   |
| 5/4   | 2         | 2.7%    |
| 4/3   | 1         | 1.35%   |
| 3/2   | 1         | 1.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 16.48%  |
| 201-250        | 14        | 15.38%  |
| 101-110        | 14        | 15.38%  |
| 301-350        | 13        | 14.29%  |
| 71-80          | 7         | 7.69%   |
| 351-500        | 7         | 7.69%   |
| 251-300        | 5         | 5.49%   |
| 61-70          | 4         | 4.4%    |
| More than 1000 | 2         | 2.2%    |
| 151-200        | 2         | 2.2%    |
| 141-150        | 2         | 2.2%    |
| 121-130        | 2         | 2.2%    |
| 51-60          | 1         | 1.1%    |
| 1-40           | 1         | 1.1%    |
| 131-140        | 1         | 1.1%    |
| Unknown        | 1         | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 23        | 27.38%  |
| 121-160       | 22        | 26.19%  |
| 161-240       | 21        | 25%     |
| 101-120       | 9         | 10.71%  |
| More than 240 | 7         | 8.33%   |
| 1-50          | 1         | 1.19%   |
| Unknown       | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 61.36%  |
| 2     | 18        | 20.45%  |
| 0     | 13        | 14.77%  |
| 3     | 3         | 3.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 63        | 50%     |
| Realtek Semiconductor             | 46        | 36.51%  |
| Qualcomm Atheros                  | 2         | 1.59%   |
| Microsoft                         | 2         | 1.59%   |
| Broadcom                          | 2         | 1.59%   |
| Aquantia                          | 2         | 1.59%   |
| TP-Link                           | 1         | 0.79%   |
| Texas Instruments                 | 1         | 0.79%   |
| Standard Microsystems             | 1         | 0.79%   |
| Qualcomm                          | 1         | 0.79%   |
| Pulse-Eight                       | 1         | 0.79%   |
| Oculus VR                         | 1         | 0.79%   |
| MediaTek                          | 1         | 0.79%   |
| FIBOCOM                           | 1         | 0.79%   |
| Ericsson Business Mobile Networks | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 19.73%  |
| Intel Wi-Fi 6 AX200                                               | 15        | 10.2%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 8.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.4%    |
| Intel I211 Gigabit Network Connection                             | 5         | 3.4%    |
| Intel Wireless-AC 9260                                            | 3         | 2.04%   |
| Intel Wireless 8260                                               | 3         | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.04%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.36%   |
| Intel Wireless 7265                                               | 2         | 1.36%   |
| Intel Wireless 7260                                               | 2         | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.36%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.36%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.36%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.68%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.68%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Pulse-Eight CEC Adapter                                           | 1         | 0.68%   |
| Oculus VR Rift S                                                  | 1         | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.68%   |
| Intel Wireless 3165                                               | 1         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 48        | 81.36%  |
| Realtek Semiconductor             | 2         | 3.39%   |
| Microsoft                         | 2         | 3.39%   |
| TP-Link                           | 1         | 1.69%   |
| Qualcomm Atheros                  | 1         | 1.69%   |
| Qualcomm                          | 1         | 1.69%   |
| MediaTek                          | 1         | 1.69%   |
| FIBOCOM                           | 1         | 1.69%   |
| Ericsson Business Mobile Networks | 1         | 1.69%   |
| Broadcom                          | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 15        | 25.42%  |
| Intel Wireless-AC 9260                                     | 3         | 5.08%   |
| Intel Wireless 8260                                        | 3         | 5.08%   |
| Intel Wi-Fi 6 AX201                                        | 3         | 5.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3         | 5.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 5.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 3         | 5.08%   |
| Microsoft Xbox 360 Wireless Adapter                        | 2         | 3.39%   |
| Intel Wireless 8265 / 8275                                 | 2         | 3.39%   |
| Intel Wireless 7265                                        | 2         | 3.39%   |
| Intel Wireless 7260                                        | 2         | 3.39%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 3.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.69%   |
| Qualcomm QCA6390 Wireless Network Adapter                  | 1         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1         | 1.69%   |
| Intel Wireless 3165                                        | 1         | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.69%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 1         | 1.69%   |
| FIBOCOM L830-EB                                            | 1         | 1.69%   |
| Ericsson Business Mobile Networks N5321 gw                 | 1         | 1.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 54.32%  |
| Intel                 | 32        | 39.51%  |
| Aquantia              | 2         | 2.47%   |
| Standard Microsystems | 1         | 1.23%   |
| Qualcomm Atheros      | 1         | 1.23%   |
| Broadcom              | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 34.12%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 15.29%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 5         | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.53%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 3.53%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.35%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.35%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.35%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.35%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.35%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.35%   |
| Standard Microsystems Ethernet controller                         | 1         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.18%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.18%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.18%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.18%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.18%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 70        | 54.26%  |
| WiFi     | 56        | 43.41%  |
| Modem    | 3         | 2.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 51.14%  |
| Ethernet | 43        | 48.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 41        | 48.24%  |
| 2     | 37        | 43.53%  |
| 3     | 3         | 3.53%   |
| 0     | 3         | 3.53%   |
| 4     | 1         | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 75.29%  |
| Yes  | 21        | 24.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 75.86%  |
| Realtek Semiconductor           | 3         | 5.17%   |
| ASUSTek Computer                | 3         | 5.17%   |
| Cambridge Silicon Radio         | 2         | 3.45%   |
| Broadcom                        | 2         | 3.45%   |
| Qualcomm Atheros Communications | 1         | 1.72%   |
| MediaTek                        | 1         | 1.72%   |
| HTC (High Tech Computer)        | 1         | 1.72%   |
| Apple                           | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 13        | 22.41%  |
| Intel Bluetooth wireless interface                                   | 9         | 15.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 7         | 12.07%  |
| Intel AX201 Bluetooth                                                | 7         | 12.07%  |
| Realtek Bluetooth Radio                                              | 3         | 5.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 5.17%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 5.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 3.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.72%   |
| MediaTek Wireless_Device                                             | 1         | 1.72%   |
| Intel Bluetooth Device                                               | 1         | 1.72%   |
| Intel AX210 Bluetooth                                                | 1         | 1.72%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.72%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.72%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 51        | 36.69%  |
| AMD                                  | 32        | 23.02%  |
| Nvidia                               | 26        | 18.71%  |
| C-Media Electronics                  | 4         | 2.88%   |
| Texas Instruments                    | 3         | 2.16%   |
| Synaptics                            | 2         | 1.44%   |
| Realtek Semiconductor                | 2         | 1.44%   |
| Kingston Technology                  | 2         | 1.44%   |
| DSEA A/S                             | 2         | 1.44%   |
| Unknown                              | 1         | 0.72%   |
| Trust                                | 1         | 0.72%   |
| Thomann                              | 1         | 0.72%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.72%   |
| Sony                                 | 1         | 0.72%   |
| Sennheiser Communications            | 1         | 0.72%   |
| Schiit Audio                         | 1         | 0.72%   |
| Satechi                              | 1         | 0.72%   |
| PreSonus Audio Electronics           | 1         | 0.72%   |
| Lenovo                               | 1         | 0.72%   |
| GYROCOM C&C                          | 1         | 0.72%   |
| Creative Technology                  | 1         | 0.72%   |
| Creative Labs                        | 1         | 0.72%   |
| Corsair                              | 1         | 0.72%   |
| Antlion Audio                        | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16        | 9.88%   |
| AMD Family 17h/19h HD Audio Controller                              | 10        | 6.17%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 9         | 5.56%   |
| Intel Sunrise Point-LP HD Audio                                     | 7         | 4.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 6         | 3.7%    |
| AMD Navi 10 HDMI Audio                                              | 6         | 3.7%    |
| Intel Cannon Lake PCH cAVS                                          | 5         | 3.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 5         | 3.09%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 4         | 2.47%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                     | 3         | 1.85%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.85%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 3         | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 1.85%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 1.23%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 1.23%   |
| Realtek Semiconductor USB Audio                                     | 2         | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 1.23%   |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 1.23%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 1.23%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 1.23%   |
| DSEA A/S Headset [PC 8]                                             | 2         | 1.23%   |
| C-Media Electronics USB Advanced Audio Device                       | 2         | 1.23%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2         | 1.23%   |
| Unknown USB Audio                                                   | 1         | 0.62%   |
| Trust USB microphone                                                | 1         | 0.62%   |
| Thomann SC450USB                                                    | 1         | 0.62%   |
| Thesycon Systemsoftware & Consulting D50s                           | 1         | 0.62%   |
| Texas Instruments PCM2902C Audio CODEC                              | 1         | 0.62%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 23.16%  |
| Kingston            | 14        | 14.74%  |
| Micron Technology   | 13        | 13.68%  |
| Corsair             | 13        | 13.68%  |
| Crucial             | 9         | 9.47%   |
| G.Skill             | 7         | 7.37%   |
| SK hynix            | 5         | 5.26%   |
| Unknown (ABCD)      | 3         | 3.16%   |
| Unknown             | 3         | 3.16%   |
| Goodram             | 2         | 2.11%   |
| Strontium           | 1         | 1.05%   |
| Avant               | 1         | 1.05%   |
| AMD                 | 1         | 1.05%   |
| A-DATA Technology   | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s              | 3         | 2.91%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s    | 2         | 1.94%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 1.94%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.94%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 2         | 1.94%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 2         | 1.94%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s              | 2         | 1.94%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s                 | 2         | 1.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                 | 2         | 1.94%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s              | 2         | 1.94%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.97%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.97%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                       | 1         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s     | 1         | 0.97%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                  | 1         | 0.97%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.97%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.97%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s           | 1         | 0.97%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 0.97%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.97%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.97%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 0.97%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 0.97%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                      | 1         | 0.97%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.97%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 0.97%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 0.97%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 0.97%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 0.97%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.97%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.97%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.97%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 0.97%   |
| Samsung RAM M393B2K70CM0-CF8 16GB DIMM DDR3 1066MT/s                | 1         | 0.97%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s                | 1         | 0.97%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 57        | 70.37%  |
| DDR3   | 12        | 14.81%  |
| LPDDR4 | 9         | 11.11%  |
| LPDDR3 | 2         | 2.47%   |
| LPDDR5 | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 45.12%  |
| DIMM         | 34        | 41.46%  |
| Row Of Chips | 8         | 9.76%   |
| RIMM         | 1         | 1.22%   |
| Chip         | 1         | 1.22%   |
| Unknown      | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 34        | 38.64%  |
| 8192  | 32        | 36.36%  |
| 32768 | 10        | 11.36%  |
| 4096  | 10        | 11.36%  |
| 2048  | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 25        | 28.09%  |
| 2667  | 10        | 11.24%  |
| 2133  | 10        | 11.24%  |
| 1600  | 9         | 10.11%  |
| 2400  | 7         | 7.87%   |
| 3600  | 6         | 6.74%   |
| 4267  | 4         | 4.49%   |
| 3000  | 3         | 3.37%   |
| 4266  | 2         | 2.25%   |
| 3334  | 2         | 2.25%   |
| 1333  | 2         | 2.25%   |
| 6400  | 1         | 1.12%   |
| 3733  | 1         | 1.12%   |
| 3466  | 1         | 1.12%   |
| 3400  | 1         | 1.12%   |
| 3266  | 1         | 1.12%   |
| 2933  | 1         | 1.12%   |
| 2134  | 1         | 1.12%   |
| 2132  | 1         | 1.12%   |
| 1066  | 1         | 1.12%   |

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
| Chicony Electronics           | 11        | 22%     |
| Microdia                      | 7         | 14%     |
| IMC Networks                  | 7         | 14%     |
| Logitech                      | 6         | 12%     |
| Acer                          | 5         | 10%     |
| Sunplus Innovation Technology | 3         | 6%      |
| Realtek Semiconductor         | 3         | 6%      |
| Quanta                        | 2         | 4%      |
| MacroSilicon                  | 2         | 4%      |
| SunplusIT                     | 1         | 2%      |
| Lite-On Technology            | 1         | 2%      |
| Apple                         | 1         | 2%      |
| 2M UVC CAMERA                 | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Chicony Integrated Camera           | 7         | 13.46%  |
| Microdia Integrated_Webcam_HD       | 4         | 7.69%   |
| IMC Networks USB2.0 HD UVC WebCam   | 4         | 7.69%   |
| IMC Networks Integrated Camera      | 3         | 5.77%   |
| Chicony HP HD Camera                | 3         | 5.77%   |
| Sunplus Integrated_Webcam_FHD       | 2         | 3.85%   |
| MacroSilicon USB Video              | 2         | 3.85%   |
| Acer Integrated IR Camera           | 2         | 3.85%   |
| Acer Integrated Camera              | 2         | 3.85%   |
| SunplusIT HP TrueVision HD Camera   | 1         | 1.92%   |
| Sunplus Integrated_Webcam_HD        | 1         | 1.92%   |
| Realtek Laptop Camera               | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD        | 1         | 1.92%   |
| Realtek EasyCamera                  | 1         | 1.92%   |
| Quanta HP True Vision HD Camera     | 1         | 1.92%   |
| Quanta HD WebCam                    | 1         | 1.92%   |
| Microdia USB 2.0 Camera             | 1         | 1.92%   |
| Microdia Integrated Webcam          | 1         | 1.92%   |
| Microdia Camera                     | 1         | 1.92%   |
| Logitech Webcam C930e               | 1         | 1.92%   |
| Logitech Webcam C310                | 1         | 1.92%   |
| Logitech Webcam C270                | 1         | 1.92%   |
| Logitech StreamCam                  | 1         | 1.92%   |
| Logitech HD Pro Webcam C920         | 1         | 1.92%   |
| Logitech C930c                      | 1         | 1.92%   |
| Lite-On HP HD Camera                | 1         | 1.92%   |
| Chicony USB2.0 Camera               | 1         | 1.92%   |
| Apple iPhone5/5C/5S/6               | 1         | 1.92%   |
| Acer ThinkPad P50 Integrated Camera | 1         | 1.92%   |
| Acer SunplusIT Integrated Camera    | 1         | 1.92%   |
| Acer HD Webcam                      | 1         | 1.92%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1         | 1.92%   |

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
| Alcor Micro | 8         | 80%     |
| Yubico.com  | 1         | 10%     |
| Broadcom    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 8         | 80%     |
| Yubico.com Yubikey 4/5 U2F+CCID                | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 58.62%  |
| 1     | 23        | 26.44%  |
| 2     | 12        | 13.79%  |
| 4     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 22.45%  |
| Graphics card            | 10        | 20.41%  |
| Chipcard                 | 8         | 16.33%  |
| Multimedia controller    | 5         | 10.2%   |
| Unassigned class         | 3         | 6.12%   |
| Net/wireless             | 3         | 6.12%   |
| Bluetooth                | 3         | 6.12%   |
| Camera                   | 2         | 4.08%   |
| Network                  | 1         | 2.04%   |
| Modem                    | 1         | 2.04%   |
| Dvb card                 | 1         | 2.04%   |
| Communication controller | 1         | 2.04%   |

