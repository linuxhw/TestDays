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

Total: 139

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
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
| NixOS 22.05                      | 37        | 34.91%  |
| NixOS 21.11                      | 18        | 16.98%  |
| NixOS 22.11                      | 16        | 15.09%  |
| NixOS                            | 5         | 4.72%   |
| NixOS 21.05pre-git               | 2         | 1.89%   |
| NixOS 20.09pre-git               | 2         | 1.89%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.94%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.94%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.94%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.94%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.94%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.94%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.94%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.94%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.94%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.94%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.94%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.94%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.94%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.94%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.94%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.94%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.94%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.94%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.94%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.94%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.94%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.94%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.94%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.94%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.94%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 99        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.74          | 4         | 3.57%   |
| 5.15.43          | 4         | 3.57%   |
| 5.15.72          | 3         | 2.68%   |
| 5.15.68          | 3         | 2.68%   |
| 5.15.47          | 3         | 2.68%   |
| 5.15.26          | 3         | 2.68%   |
| 5.8.1-zen1       | 2         | 1.79%   |
| 5.19.14          | 2         | 1.79%   |
| 5.18.19          | 2         | 1.79%   |
| 5.17.1           | 2         | 1.79%   |
| 5.16.8-zen1      | 2         | 1.79%   |
| 5.16.15          | 2         | 1.79%   |
| 5.15.64          | 2         | 1.79%   |
| 5.15.32          | 2         | 1.79%   |
| 5.15.25          | 2         | 1.79%   |
| 5.13.7           | 2         | 1.79%   |
| 5.13.2           | 2         | 1.79%   |
| 5.12.15          | 2         | 1.79%   |
| 5.10.102         | 2         | 1.79%   |
| 6.0.8-zen1       | 1         | 0.89%   |
| 6.0.6            | 1         | 0.89%   |
| 6.0.2-xanmod1-tt | 1         | 0.89%   |
| 6.0.2            | 1         | 0.89%   |
| 6.0.0-xanmod1    | 1         | 0.89%   |
| 5.8.4            | 1         | 0.89%   |
| 5.8.16-hardened  | 1         | 0.89%   |
| 5.8.11           | 1         | 0.89%   |
| 5.8.10           | 1         | 0.89%   |
| 5.7.4            | 1         | 0.89%   |
| 5.7.19           | 1         | 0.89%   |
| 5.7.17           | 1         | 0.89%   |
| 5.4.94           | 1         | 0.89%   |
| 5.4.72           | 1         | 0.89%   |
| 5.4.69           | 1         | 0.89%   |
| 5.4.50           | 1         | 0.89%   |
| 5.4.47           | 1         | 0.89%   |
| 5.4.24           | 1         | 0.89%   |
| 5.4.209          | 1         | 0.89%   |
| 5.4.187          | 1         | 0.89%   |
| 5.19.5           | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 4         | 3.57%   |
| 5.15.43  | 4         | 3.57%   |
| 5.15.72  | 3         | 2.68%   |
| 5.15.68  | 3         | 2.68%   |
| 5.15.47  | 3         | 2.68%   |
| 5.15.26  | 3         | 2.68%   |
| 6.0.2    | 2         | 1.79%   |
| 5.8.1    | 2         | 1.79%   |
| 5.19.14  | 2         | 1.79%   |
| 5.18.19  | 2         | 1.79%   |
| 5.17.1   | 2         | 1.79%   |
| 5.16.8   | 2         | 1.79%   |
| 5.16.15  | 2         | 1.79%   |
| 5.15.64  | 2         | 1.79%   |
| 5.15.32  | 2         | 1.79%   |
| 5.15.25  | 2         | 1.79%   |
| 5.13.7   | 2         | 1.79%   |
| 5.13.2   | 2         | 1.79%   |
| 5.12.15  | 2         | 1.79%   |
| 5.11.16  | 2         | 1.79%   |
| 5.10.102 | 2         | 1.79%   |
| 6.0.8    | 1         | 0.89%   |
| 6.0.6    | 1         | 0.89%   |
| 6.0.0    | 1         | 0.89%   |
| 5.8.4    | 1         | 0.89%   |
| 5.8.16   | 1         | 0.89%   |
| 5.8.11   | 1         | 0.89%   |
| 5.8.10   | 1         | 0.89%   |
| 5.7.4    | 1         | 0.89%   |
| 5.7.19   | 1         | 0.89%   |
| 5.7.17   | 1         | 0.89%   |
| 5.4.94   | 1         | 0.89%   |
| 5.4.72   | 1         | 0.89%   |
| 5.4.69   | 1         | 0.89%   |
| 5.4.50   | 1         | 0.89%   |
| 5.4.47   | 1         | 0.89%   |
| 5.4.24   | 1         | 0.89%   |
| 5.4.209  | 1         | 0.89%   |
| 5.4.187  | 1         | 0.89%   |
| 5.19.5   | 1         | 0.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 39        | 35.45%  |
| 5.10    | 14        | 12.73%  |
| 5.16    | 8         | 7.27%   |
| 5.4     | 7         | 6.36%   |
| 5.19    | 7         | 6.36%   |
| 5.8     | 6         | 5.45%   |
| 6.0     | 5         | 4.55%   |
| 5.18    | 5         | 4.55%   |
| 5.13    | 4         | 3.64%   |
| 5.7     | 3         | 2.73%   |
| 5.17    | 3         | 2.73%   |
| 5.12    | 3         | 2.73%   |
| 5.14    | 2         | 1.82%   |
| 5.11    | 2         | 1.82%   |
| 4.19    | 2         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 96        | 96.97%  |
| aarch64 | 3         | 3.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 73        | 72.28%  |
| XFCE         | 6         | 5.94%   |
| GNOME        | 5         | 4.95%   |
| sway         | 4         | 3.96%   |
| KDE5         | 4         | 3.96%   |
| KDE          | 4         | 3.96%   |
| none+xmonad  | 2         | 1.98%   |
| none+i3      | 1         | 0.99%   |
| none+bspwm   | 1         | 0.99%   |
| none+awesome | 1         | 0.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 63.46%  |
| X11     | 20        | 19.23%  |
| Wayland | 10        | 9.62%   |
| Tty     | 8         | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 76        | 76%     |
| LightDM | 10        | 10%     |
| SDDM    | 9         | 9%      |
| GDM     | 5         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 52.53%  |
| en_US   | 32        | 32.32%  |
| en_GB   | 3         | 3.03%   |
| ru_RU   | 2         | 2.02%   |
| fr_FR   | 2         | 2.02%   |
| en_DK   | 2         | 2.02%   |
| de_CH   | 2         | 2.02%   |
| ro_RO   | 1         | 1.01%   |
| pt_BR   | 1         | 1.01%   |
| it_IT   | 1         | 1.01%   |
| en_AU   | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 84        | 83.17%  |
| BIOS | 17        | 16.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 49        | 48.51%  |
| Btrfs   | 17        | 16.83%  |
| Zfs     | 10        | 9.9%    |
| Tmpfs   | 10        | 9.9%    |
| Xfs     | 8         | 7.92%   |
| Unknown | 6         | 5.94%   |
| Ext2    | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 92        | 91.09%  |
| Unknown | 8         | 7.92%   |
| MBR     | 1         | 0.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 73%     |
| Yes       | 27        | 27%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 65.66%  |
| Yes       | 34        | 34.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 22        | 22.22%  |
| ASUSTek Computer        | 22        | 22.22%  |
| Dell                    | 15        | 15.15%  |
| MSI                     | 8         | 8.08%   |
| Hewlett-Packard         | 6         | 6.06%   |
| Gigabyte Technology     | 5         | 5.05%   |
| ASRock                  | 4         | 4.04%   |
| Acer                    | 3         | 3.03%   |
| Raspberry Pi Foundation | 2         | 2.02%   |
| Apple                   | 2         | 2.02%   |
| Toshiba                 | 1         | 1.01%   |
| Teclast                 | 1         | 1.01%   |
| Supermicro              | 1         | 1.01%   |
| Pine Microsystems       | 1         | 1.01%   |
| OBSIDIAN-PC             | 1         | 1.01%   |
| Intel                   | 1         | 1.01%   |
| Hardkernel              | 1         | 1.01%   |
| GPD                     | 1         | 1.01%   |
| Framework               | 1         | 1.01%   |
| EVGA                    | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| MSI MS-7C37                              | 2         | 2.02%   |
| Dell Latitude 7420                       | 2         | 2.02%   |
| Toshiba Satellite L50-B                  | 1         | 1.01%   |
| Teclast F5                               | 1         | 1.01%   |
| Supermicro X8DT6                         | 1         | 1.01%   |
| RPi Raspberry Pi 3 Model B+              | 1         | 1.01%   |
| RPi Raspberry Pi                         | 1         | 1.01%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.01%   |
| OBSIDIAN-PC N13_N140ZU                   | 1         | 1.01%   |
| MSI MS-7C95                              | 1         | 1.01%   |
| MSI MS-7C84                              | 1         | 1.01%   |
| MSI MS-7C35                              | 1         | 1.01%   |
| MSI MS-7B89                              | 1         | 1.01%   |
| MSI MS-7B09                              | 1         | 1.01%   |
| MSI Bravo 15 B5DD                        | 1         | 1.01%   |
| Lenovo Yoga Slim 7 13ACN5 82CY           | 1         | 1.01%   |
| Lenovo Yoga 520-14IKB 81C8               | 1         | 1.01%   |
| Lenovo ThinkPad X390 20Q0CTO1WW          | 1         | 1.01%   |
| Lenovo ThinkPad X260 20F5S6MF02          | 1         | 1.01%   |
| Lenovo ThinkPad X260 20F5S4BY00          | 1         | 1.01%   |
| Lenovo ThinkPad X250 20CLS18S0T          | 1         | 1.01%   |
| Lenovo ThinkPad X230 23243E9             | 1         | 1.01%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 1.01%   |
| Lenovo ThinkPad T580 20L90024PB          | 1         | 1.01%   |
| Lenovo ThinkPad T540p 20BE005YMH         | 1         | 1.01%   |
| Lenovo ThinkPad T490 20N2000LUK          | 1         | 1.01%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 1.01%   |
| Lenovo ThinkPad T460p 20FWCTO1WW         | 1         | 1.01%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW     | 1         | 1.01%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS    | 1         | 1.01%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK    | 1         | 1.01%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT     | 1         | 1.01%   |
| Lenovo ThinkPad E470 20H1006JIX          | 1         | 1.01%   |
| Lenovo Legion S7 15ACH6 82K8             | 1         | 1.01%   |
| Lenovo Legion 5 17ARH05H 82GN            | 1         | 1.01%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS        | 1         | 1.01%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.01%   |
| Intel NUC11PAHi7                         | 1         | 1.01%   |
| HP ZBook Studio G5                       | 1         | 1.01%   |
| HP Spectre x360 Convertible 15-eb0xxx    | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 16        | 16.16%  |
| ASUS ROG                 | 6         | 6.06%   |
| ASUS PRIME               | 5         | 5.05%   |
| Dell XPS                 | 4         | 4.04%   |
| Dell Inspiron            | 4         | 4.04%   |
| Dell Precision           | 3         | 3.03%   |
| Dell Latitude            | 3         | 3.03%   |
| RPi Raspberry            | 2         | 2.02%   |
| MSI MS-7C37              | 2         | 2.02%   |
| Lenovo Yoga              | 2         | 2.02%   |
| Lenovo Legion            | 2         | 2.02%   |
| HP ProBook               | 2         | 2.02%   |
| ASUS ZenBook             | 2         | 2.02%   |
| Acer Aspire              | 2         | 2.02%   |
| Toshiba Satellite        | 1         | 1.01%   |
| Teclast F5               | 1         | 1.01%   |
| Supermicro X8DT6         | 1         | 1.01%   |
| Pine Microsystems Pine64 | 1         | 1.01%   |
| OBSIDIAN-PC N13          | 1         | 1.01%   |
| MSI MS-7C95              | 1         | 1.01%   |
| MSI MS-7C84              | 1         | 1.01%   |
| MSI MS-7C35              | 1         | 1.01%   |
| MSI MS-7B89              | 1         | 1.01%   |
| MSI MS-7B09              | 1         | 1.01%   |
| MSI Bravo                | 1         | 1.01%   |
| Lenovo IdeaPadFlex       | 1         | 1.01%   |
| Lenovo IdeaPad           | 1         | 1.01%   |
| Intel NUC11PAHi7         | 1         | 1.01%   |
| HP ZBook                 | 1         | 1.01%   |
| HP Spectre               | 1         | 1.01%   |
| HP EliteDesk             | 1         | 1.01%   |
| HP EliteBook             | 1         | 1.01%   |
| Hardkernel ODROID-H2     | 1         | 1.01%   |
| GPD MicroPC              | 1         | 1.01%   |
| Gigabyte X570            | 1         | 1.01%   |
| Gigabyte X470            | 1         | 1.01%   |
| Gigabyte Sabre           | 1         | 1.01%   |
| Gigabyte H97M-D3H        | 1         | 1.01%   |
| Gigabyte B550I           | 1         | 1.01%   |
| Framework Laptop         | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 22        | 22.22%  |
| 2019    | 17        | 17.17%  |
| 2021    | 12        | 12.12%  |
| 2018    | 12        | 12.12%  |
| 2016    | 10        | 10.1%   |
| 2017    | 6         | 6.06%   |
| 2015    | 4         | 4.04%   |
| 2014    | 4         | 4.04%   |
| 2013    | 3         | 3.03%   |
| 2012    | 3         | 3.03%   |
| Unknown | 3         | 3.03%   |
| 2022    | 2         | 2.02%   |
| 2010    | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 49        | 49.49%  |
| Desktop        | 36        | 36.36%  |
| Convertible    | 7         | 7.07%   |
| System on chip | 2         | 2.02%   |
| Server         | 2         | 2.02%   |
| Phone          | 1         | 1.01%   |
| Mini pc        | 1         | 1.01%   |
| All in one     | 1         | 1.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 99        | 99%     |
| Enabled  | 1         | 1%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 98.99%  |
| Yes  | 1         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 29        | 28.71%  |
| 16.01-24.0  | 22        | 21.78%  |
| 8.01-16.0   | 16        | 15.84%  |
| 64.01-256.0 | 15        | 14.85%  |
| 4.01-8.0    | 8         | 7.92%   |
| 24.01-32.0  | 5         | 4.95%   |
| 3.01-4.0    | 4         | 3.96%   |
| 1.01-2.0    | 1         | 0.99%   |
| 0.51-1.0    | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 26.85%  |
| 8.01-16.0   | 21        | 19.44%  |
| 3.01-4.0    | 15        | 13.89%  |
| 2.01-3.0    | 13        | 12.04%  |
| 1.01-2.0    | 8         | 7.41%   |
| 32.01-64.0  | 6         | 5.56%   |
| 24.01-32.0  | 5         | 4.63%   |
| 16.01-24.0  | 5         | 4.63%   |
| 0.51-1.0    | 4         | 3.7%    |
| 64.01-256.0 | 1         | 0.93%   |
| 0.01-0.5    | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 51.96%  |
| 2      | 28        | 27.45%  |
| 3      | 9         | 8.82%   |
| 6      | 4         | 3.92%   |
| 5      | 3         | 2.94%   |
| 17     | 1         | 0.98%   |
| 11     | 1         | 0.98%   |
| 8      | 1         | 0.98%   |
| 4      | 1         | 0.98%   |
| 0      | 1         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 88.89%  |
| Yes       | 11        | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 79.21%  |
| No        | 21        | 20.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 69.7%   |
| No        | 30        | 30.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 68.32%  |
| No        | 32        | 31.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 17.17%  |
| Germany     | 12        | 12.12%  |
| France      | 9         | 9.09%   |
| UK          | 8         | 8.08%   |
| Poland      | 7         | 7.07%   |
| Russia      | 6         | 6.06%   |
| Ukraine     | 5         | 5.05%   |
| Canada      | 5         | 5.05%   |
| Italy       | 4         | 4.04%   |
| Switzerland | 3         | 3.03%   |
| Austria     | 3         | 3.03%   |
| Czechia     | 2         | 2.02%   |
| Belgium     | 2         | 2.02%   |
| Uruguay     | 1         | 1.01%   |
| Sweden      | 1         | 1.01%   |
| Spain       | 1         | 1.01%   |
| Serbia      | 1         | 1.01%   |
| Romania     | 1         | 1.01%   |
| Portugal    | 1         | 1.01%   |
| New Zealand | 1         | 1.01%   |
| Netherlands | 1         | 1.01%   |
| Iraq        | 1         | 1.01%   |
| Iran        | 1         | 1.01%   |
| India       | 1         | 1.01%   |
| Hungary     | 1         | 1.01%   |
| Denmark     | 1         | 1.01%   |
| Colombia    | 1         | 1.01%   |
| Brazil      | 1         | 1.01%   |
| Australia   | 1         | 1.01%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Marki              | 4         | 3.88%   |
| Vienna             | 3         | 2.91%   |
| Plymouth           | 3         | 2.91%   |
| Kharkiv            | 3         | 2.91%   |
| Frankfurt am Main  | 3         | 2.91%   |
| South Deerfield    | 2         | 1.94%   |
| Schaafheim         | 2         | 1.94%   |
| Richardson         | 2         | 1.94%   |
| Milwaukee          | 2         | 1.94%   |
| Lyon               | 2         | 1.94%   |
| London             | 2         | 1.94%   |
| Halifax            | 2         | 1.94%   |
| Gdansk             | 2         | 1.94%   |
| Darmstadt          | 2         | 1.94%   |
| Chelyabinsk        | 2         | 1.94%   |
| Woodford           | 1         | 0.97%   |
| Wellington         | 1         | 0.97%   |
| Villeurbanne       | 1         | 0.97%   |
| Verneuil-sur-Seine | 1         | 0.97%   |
| Valpacos           | 1         | 0.97%   |
| Trento             | 1         | 0.97%   |
| Tottenham          | 1         | 0.97%   |
| Tolyatti           | 1         | 0.97%   |
| Tehran             | 1         | 0.97%   |
| Székesfehérvár  | 1         | 0.97%   |
| Stockholm          | 1         | 0.97%   |
| Southampton        | 1         | 0.97%   |
| Sindelfingen       | 1         | 0.97%   |
| Saratov            | 1         | 0.97%   |
| San Gabriel        | 1         | 0.97%   |
| Riegelsberg        | 1         | 0.97%   |
| Rho                | 1         | 0.97%   |
| Redwood City       | 1         | 0.97%   |
| Ramenskoye         | 1         | 0.97%   |
| Prague             | 1         | 0.97%   |
| Popice             | 1         | 0.97%   |
| Pittsburgh         | 1         | 0.97%   |
| Pisa               | 1         | 0.97%   |
| Perth              | 1         | 0.97%   |
| Paris              | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 45        | 89     | 29.61%  |
| WDC                         | 13        | 25     | 8.55%   |
| Toshiba                     | 13        | 21     | 8.55%   |
| Seagate                     | 12        | 24     | 7.89%   |
| Sandisk                     | 9         | 14     | 5.92%   |
| Crucial                     | 9         | 11     | 5.92%   |
| Kingston                    | 8         | 8      | 5.26%   |
| Intel                       | 8         | 11     | 5.26%   |
| SK hynix                    | 6         | 7      | 3.95%   |
| Unknown                     | 4         | 6      | 2.63%   |
| HGST                        | 3         | 10     | 1.97%   |
| Transcend                   | 2         | 2      | 1.32%   |
| Plextor                     | 2         | 2      | 1.32%   |
| Phison Electronics          | 2         | 3      | 1.32%   |
| Micron Technology           | 2         | 2      | 1.32%   |
| KIOXIA                      | 2         | 3      | 1.32%   |
| Apple                       | 2         | 5      | 1.32%   |
| Teclast                     | 1         | 1      | 0.66%   |
| Phison                      | 1         | 1      | 0.66%   |
| Lexar                       | 1         | 1      | 0.66%   |
| Kingston Technology Company | 1         | 1      | 0.66%   |
| INNOVATION IT               | 1         | 1      | 0.66%   |
| China                       | 1         | 1      | 0.66%   |
| BIWIN                       | 1         | 1      | 0.66%   |
| ASMT                        | 1         | 1      | 0.66%   |
| ASMedia                     | 1         | 1      | 0.66%   |
| ADATA Technology            | 1         | 2      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB              | 5         | 2.84%   |
| SanDisk SSD PLUS 240GB               | 3         | 1.7%    |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 1.7%    |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.7%    |
| Samsung SSD 970 EVO 500GB            | 3         | 1.7%    |
| Crucial CT1000MX500SSD1 1TB          | 3         | 1.7%    |
| Unknown MMC Card  32GB               | 2         | 1.14%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB | 2         | 1.14%   |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 1.14%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.14%   |
| Samsung SSD 970 EVO 1TB              | 2         | 1.14%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.14%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.14%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.14%   |
| Samsung SSD 860 EVO 2TB              | 2         | 1.14%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.14%   |
| Samsung PM9A1 NVMe 1024GB            | 2         | 1.14%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.14%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 1.14%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.14%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.57%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.57%   |
| WDC WDS200T1X0E-00AFY0 2TB           | 1         | 0.57%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.57%   |
| WDC WD120EMFZ-11A6JA0 12TB           | 1         | 0.57%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1         | 0.57%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.57%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.57%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.57%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.57%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.57%   |
| Unknown MMC Card  8GB                | 1         | 0.57%   |
| Unknown MMC Card  16GB               | 1         | 0.57%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 0.57%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 0.57%   |
| Toshiba TR150 960GB SSD              | 1         | 0.57%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 24     | 37.5%   |
| Toshiba | 8         | 15     | 25%     |
| WDC     | 7         | 17     | 21.88%  |
| HGST    | 3         | 10     | 9.38%   |
| ASMT    | 1         | 1      | 3.13%   |
| Apple   | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 47     | 36.07%  |
| Crucial             | 8         | 10     | 13.11%  |
| SanDisk             | 6         | 10     | 9.84%   |
| Kingston            | 5         | 5      | 8.2%    |
| Intel               | 5         | 7      | 8.2%    |
| WDC                 | 2         | 3      | 3.28%   |
| Transcend           | 2         | 2      | 3.28%   |
| Apple               | 2         | 4      | 3.28%   |
| Toshiba             | 1         | 1      | 1.64%   |
| Teclast             | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| Plextor             | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 1      | 1.64%   |
| INNOVATION IT       | 1         | 1      | 1.64%   |
| China               | 1         | 1      | 1.64%   |
| BIWIN               | 1         | 1      | 1.64%   |
| ASMedia             | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 59        | 83     | 42.75%  |
| SSD  | 51        | 97     | 36.96%  |
| HDD  | 24        | 68     | 17.39%  |
| MMC  | 4         | 6      | 2.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 59        | 83     | 47.97%  |
| SATA | 56        | 159    | 45.53%  |
| SAS  | 4         | 6      | 3.25%   |
| MMC  | 4         | 6      | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 69     | 47.62%  |
| 0.51-1.0   | 23        | 39     | 27.38%  |
| 1.01-2.0   | 8         | 11     | 9.52%   |
| 2.01-3.0   | 5         | 7      | 5.95%   |
| 4.01-10.0  | 5         | 29     | 5.95%   |
| 3.01-4.0   | 2         | 4      | 2.38%   |
| 10.01-20.0 | 1         | 6      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 57        | 57%     |
| 1-20           | 17        | 17%     |
| 501-1000       | 7         | 7%      |
| 2001-3000      | 6         | 6%      |
| 101-250        | 6         | 6%      |
| More than 3000 | 2         | 2%      |
| 251-500        | 2         | 2%      |
| 1001-2000      | 2         | 2%      |
| 21-50          | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 57        | 57%     |
| 1-20           | 22        | 22%     |
| 101-250        | 7         | 7%      |
| 251-500        | 4         | 4%      |
| 1001-2000      | 3         | 3%      |
| 501-1000       | 3         | 3%      |
| More than 3000 | 1         | 1%      |
| 21-50          | 1         | 1%      |
| 2001-3000      | 1         | 1%      |
| 51-100         | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 10%     |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 10%     |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 10%     |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 2      | 10%     |
| SanDisk SSD PLUS 240GB                         | 1         | 2      | 10%     |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 10%     |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 10%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 10%     |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 10%     |
| ASMT 2115 16GB                                 | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 20%     |
| Samsung Electronics | 2         | 2      | 20%     |
| SK hynix            | 1         | 1      | 10%     |
| Seagate             | 1         | 2      | 10%     |
| SanDisk             | 1         | 2      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| ASMT                | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| Seagate | 1         | 2      | 25%     |
| ASMT    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 5      | 40%     |
| HDD  | 4         | 5      | 40%     |
| NVMe | 2         | 2      | 20%     |

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
| Works    | 92        | 218    | 81.42%  |
| Detected | 13        | 24     | 11.5%   |
| Malfunc  | 8         | 12     | 7.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 34.48%  |
| Samsung Electronics          | 30        | 20.69%  |
| AMD                          | 24        | 16.55%  |
| SanDisk                      | 8         | 5.52%   |
| SK hynix                     | 5         | 3.45%   |
| Kingston Technology Company  | 5         | 3.45%   |
| Toshiba America Info Systems | 4         | 2.76%   |
| ASMedia Technology           | 4         | 2.76%   |
| Phison Electronics           | 3         | 2.07%   |
| Broadcom / LSI               | 3         | 2.07%   |
| LSI Logic / Symbios Logic    | 2         | 1.38%   |
| KIOXIA                       | 2         | 1.38%   |
| Shenzhen Longsys Electronics | 1         | 0.69%   |
| Micron/Crucial Technology    | 1         | 0.69%   |
| Micron Technology            | 1         | 0.69%   |
| Lite-On Technology           | 1         | 0.69%   |
| ADATA Technology             | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 19        | 12.34%  |
| AMD FCH SATA Controller [AHCI mode]                                           | 16        | 10.39%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 6         | 3.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 3.9%    |
| AMD 500 Series Chipset SATA Controller                                        | 6         | 3.9%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 5         | 3.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 2.6%    |
| ASMedia ASM1062 Serial ATA Controller                                         | 4         | 2.6%    |
| Phison E12 NVMe Controller                                                    | 3         | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 1.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 1.95%   |
| Intel Comet Lake SATA AHCI Controller                                         | 3         | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                        | 3         | 1.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 1.3%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 1.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                | 2         | 1.3%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 2         | 1.3%    |
| Samsung NVMe SSD Controller 980                                               | 2         | 1.3%    |
| Samsung Electronics SATA controller                                           | 2         | 1.3%    |
| KIOXIA NVMe SSD Controller BG4                                                | 2         | 1.3%    |
| Kingston Company A2000 NVMe SSD                                               | 2         | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.3%    |
| Intel Non-Volatile memory controller                                          | 2         | 1.3%    |
| Intel Comet Lake PCH-H RAID                                                   | 2         | 1.3%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.3%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 2         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 1.3%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                  | 2         | 1.3%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 0.65%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.65%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                   | 1         | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 0.65%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 61        | 43.88%  |
| NVMe | 60        | 43.17%  |
| RAID | 10        | 7.19%   |
| SAS  | 5         | 3.6%    |
| IDE  | 3         | 2.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 63.64%  |
| AMD    | 33        | 33.33%  |
| ARM    | 3         | 3.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 5.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 4.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 4.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 3.03%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 3.03%   |
| ARM Processor                              | 3         | 3.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 3.03%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 3.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 2.02%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 2.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 2.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 2.02%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 2.02%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 2.02%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 2.02%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 2.02%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 1.01%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.01%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 1.01%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 1.01%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 1.01%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.01%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 1.01%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 1.01%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.01%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.01%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 1         | 1.01%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 1         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 1.01%   |
| Intel Core i5-7600K CPU @ 3.80GHz          | 1         | 1.01%   |
| Intel Core i5-6600 CPU @ 3.30GHz           | 1         | 1.01%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 1         | 1.01%   |
| Intel Core i5-4570S CPU @ 2.90GHz          | 1         | 1.01%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 27        | 27.27%  |
| Other                  | 14        | 14.14%  |
| Intel Core i5          | 13        | 13.13%  |
| AMD Ryzen 7            | 13        | 13.13%  |
| AMD Ryzen 5            | 8         | 8.08%   |
| AMD Ryzen 9            | 6         | 6.06%   |
| Intel Xeon             | 5         | 5.05%   |
| Intel Core i3          | 3         | 3.03%   |
| Intel Celeron          | 3         | 3.03%   |
| AMD Ryzen 7 PRO        | 3         | 3.03%   |
| AMD Ryzen Threadripper | 2         | 2.02%   |
| Intel Core i9          | 1         | 1.01%   |
| AMD FX                 | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 34        | 34.34%  |
| 8       | 20        | 20.2%   |
| 6       | 16        | 16.16%  |
| 2       | 14        | 14.14%  |
| 12      | 6         | 6.06%   |
| Unknown | 3         | 3.03%   |
| 16      | 2         | 2.02%   |
| 10      | 2         | 2.02%   |
| 32      | 1         | 1.01%   |
| 24      | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 94        | 94.95%  |
| Unknown | 3         | 3.03%   |
| 2       | 2         | 2.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 86        | 86.87%  |
| 1       | 10        | 10.1%   |
| Unknown | 3         | 3.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 99%     |
| Unknown        | 1         | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 16.83%  |
| 0x0a50000c | 7         | 6.93%   |
| 0x08701021 | 7         | 6.93%   |
| 0x806c1    | 6         | 5.94%   |
| 0x806ea    | 5         | 4.95%   |
| 0x906ea    | 4         | 3.96%   |
| 0x806ec    | 4         | 3.96%   |
| 0x506e3    | 4         | 3.96%   |
| 0x306c3    | 4         | 3.96%   |
| 0x08701013 | 4         | 3.96%   |
| 0x806eb    | 3         | 2.97%   |
| 0x306a9    | 3         | 2.97%   |
| 0x08600106 | 3         | 2.97%   |
| 0x906e9    | 2         | 1.98%   |
| 0x906a3    | 2         | 1.98%   |
| 0x806e9    | 2         | 1.98%   |
| 0x706a1    | 2         | 1.98%   |
| 0x406e3    | 2         | 1.98%   |
| 0x306d4    | 2         | 1.98%   |
| 0x0a201204 | 2         | 1.98%   |
| 0x0a201009 | 2         | 1.98%   |
| 0xa0653    | 1         | 0.99%   |
| 0xa0652    | 1         | 0.99%   |
| 0x806d1    | 1         | 0.99%   |
| 0x406f1    | 1         | 0.99%   |
| 0x40661    | 1         | 0.99%   |
| 0x40651    | 1         | 0.99%   |
| 0x306f2    | 1         | 0.99%   |
| 0x206c2    | 1         | 0.99%   |
| 0x0a50000b | 1         | 0.99%   |
| 0x08600104 | 1         | 0.99%   |
| 0x08301025 | 1         | 0.99%   |
| 0x0800820d | 1         | 0.99%   |
| 0x08001137 | 1         | 0.99%   |
| 0x06000852 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 22.22%  |
| Zen 2            | 17        | 17.17%  |
| Zen 3            | 12        | 12.12%  |
| Skylake          | 9         | 9.09%   |
| TigerLake        | 7         | 7.07%   |
| Haswell          | 7         | 7.07%   |
| Unknown          | 4         | 4.04%   |
| IvyBridge        | 3         | 3.03%   |
| Goldmont plus    | 3         | 3.03%   |
| CometLake        | 3         | 3.03%   |
| Broadwell        | 3         | 3.03%   |
| Zen+             | 2         | 2.02%   |
| Westmere         | 2         | 2.02%   |
| Alderlake Hybrid | 2         | 2.02%   |
| Zen              | 1         | 1.01%   |
| Piledriver       | 1         | 1.01%   |
| Icelake          | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 50        | 40.65%  |
| Nvidia                     | 42        | 34.15%  |
| AMD                        | 29        | 23.58%  |
| Matrox Electronics Systems | 2         | 1.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 8         | 6.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 4.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 4.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 4.03%   |
| Intel UHD Graphics 620                                                                | 4         | 3.23%   |
| Intel HD Graphics 530                                                                 | 4         | 3.23%   |
| AMD Renoir                                                                            | 4         | 3.23%   |
| Nvidia GP108M [GeForce MX150]                                                         | 3         | 2.42%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 2.42%   |
| Intel HD Graphics 620                                                                 | 3         | 2.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 2.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 2.42%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 2         | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.61%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.61%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 2         | 1.61%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 1.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.61%   |
| Intel HD Graphics 630                                                                 | 2         | 1.61%   |
| Intel HD Graphics 5500                                                                | 2         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 1.61%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.61%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.81%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.81%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.81%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                 | 1         | 0.81%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 1         | 0.81%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 1         | 0.81%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 31.31%  |
| 1 x Nvidia     | 17        | 17.17%  |
| 1 x AMD        | 17        | 17.17%  |
| Intel + Nvidia | 16        | 16.16%  |
| AMD + Nvidia   | 9         | 9.09%   |
| Other          | 4         | 4.04%   |
| 1 x Matrox     | 2         | 2.02%   |
| Intel + AMD    | 2         | 2.02%   |
| 2 x AMD        | 1         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 70        | 70.71%  |
| Proprietary | 22        | 22.22%  |
| Unknown     | 7         | 7.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 64.36%  |
| 7.01-8.0   | 10        | 9.9%    |
| 1.01-2.0   | 9         | 8.91%   |
| 0.01-0.5   | 9         | 8.91%   |
| 3.01-4.0   | 6         | 5.94%   |
| 8.01-16.0  | 1         | 0.99%   |
| 0.51-1.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 19        | 17.59%  |
| AU Optronics         | 13        | 12.04%  |
| Goldstar             | 9         | 8.33%   |
| Samsung Electronics  | 8         | 7.41%   |
| LG Display           | 8         | 7.41%   |
| BOE                  | 8         | 7.41%   |
| Chimei Innolux       | 5         | 4.63%   |
| Acer                 | 5         | 4.63%   |
| Sharp                | 4         | 3.7%    |
| PANDA                | 4         | 3.7%    |
| Ancor Communications | 3         | 2.78%   |
| InfoVision           | 2         | 1.85%   |
| Hewlett-Packard      | 2         | 1.85%   |
| CSO                  | 2         | 1.85%   |
| Apple                | 2         | 1.85%   |
| AOC                  | 2         | 1.85%   |
| Vizio                | 1         | 0.93%   |
| Unknown (AAA)        | 1         | 0.93%   |
| Philips              | 1         | 0.93%   |
| Panasonic            | 1         | 0.93%   |
| MPI                  | 1         | 0.93%   |
| Lenovo               | 1         | 0.93%   |
| JDI                  | 1         | 0.93%   |
| Iiyama               | 1         | 0.93%   |
| HVR                  | 1         | 0.93%   |
| Eizo                 | 1         | 0.93%   |
| BenQ                 | 1         | 0.93%   |
| ASUSTek Computer     | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 1.79%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 1.79%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 1.79%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 1.79%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 1.79%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 1.79%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1         | 0.89%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.89%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.89%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.89%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.89%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.89%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.89%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.89%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.89%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 0.89%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.89%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 0.89%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 0.89%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 0.89%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 0.89%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1         | 0.89%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD045C 1366x768 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.89%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.89%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.89%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 0.89%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 41.35%  |
| 3840x2160 (4K)     | 20        | 19.23%  |
| 2560x1440 (QHD)    | 12        | 11.54%  |
| 1366x768 (WXGA)    | 7         | 6.73%   |
| 2560x1080          | 4         | 3.85%   |
| 1920x1200 (WUXGA)  | 4         | 3.85%   |
| 1280x1024 (SXGA)   | 3         | 2.88%   |
| 2880x1800          | 2         | 1.92%   |
| 2560x1600          | 2         | 1.92%   |
| 3840x2400          | 1         | 0.96%   |
| 3440x1440          | 1         | 0.96%   |
| 2256x1504          | 1         | 0.96%   |
| 2160x1200          | 1         | 0.96%   |
| 1680x1050 (WSXGA+) | 1         | 0.96%   |
| 1440x900 (WXGA+)   | 1         | 0.96%   |
| 1280x720 (HD)      | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 18.69%  |
| 27      | 14        | 13.08%  |
| 14      | 12        | 11.21%  |
| 13      | 12        | 11.21%  |
| 24      | 10        | 9.35%   |
| 23      | 9         | 8.41%   |
| 17      | 6         | 5.61%   |
| 34      | 5         | 4.67%   |
| 12      | 4         | 3.74%   |
| 31      | 3         | 2.8%    |
| 25      | 2         | 1.87%   |
| 21      | 2         | 1.87%   |
| 84      | 1         | 0.93%   |
| 49      | 1         | 0.93%   |
| 46      | 1         | 0.93%   |
| 22      | 1         | 0.93%   |
| 16      | 1         | 0.93%   |
| 11      | 1         | 0.93%   |
| 8       | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 37.86%  |
| 501-600     | 31        | 30.1%   |
| 201-300     | 13        | 12.62%  |
| 701-800     | 5         | 4.85%   |
| 601-700     | 4         | 3.88%   |
| 401-500     | 3         | 2.91%   |
| 351-400     | 3         | 2.91%   |
| 1001-1500   | 2         | 1.94%   |
| 1501-2000   | 1         | 0.97%   |
| 101-200     | 1         | 0.97%   |
| Unknown     | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 74.16%  |
| 16/10 | 13        | 14.61%  |
| 21/9  | 5         | 5.62%   |
| 5/4   | 3         | 3.37%   |
| 4/3   | 1         | 1.12%   |
| 3/2   | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 18.52%  |
| 81-90          | 17        | 15.74%  |
| 201-250        | 17        | 15.74%  |
| 301-350        | 14        | 12.96%  |
| 351-500        | 8         | 7.41%   |
| 71-80          | 7         | 6.48%   |
| 251-300        | 6         | 5.56%   |
| 61-70          | 4         | 3.7%    |
| 141-150        | 3         | 2.78%   |
| More than 1000 | 2         | 1.85%   |
| 151-200        | 2         | 1.85%   |
| 121-130        | 2         | 1.85%   |
| 51-60          | 1         | 0.93%   |
| 1-40           | 1         | 0.93%   |
| 131-140        | 1         | 0.93%   |
| 111-120        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 28        | 28.28%  |
| 121-160       | 25        | 25.25%  |
| 161-240       | 23        | 23.23%  |
| 101-120       | 11        | 11.11%  |
| More than 240 | 9         | 9.09%   |
| 1-50          | 2         | 2.02%   |
| Unknown       | 1         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 59.22%  |
| 2     | 22        | 21.36%  |
| 0     | 16        | 15.53%  |
| 3     | 4         | 3.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 47.95%  |
| Realtek Semiconductor             | 52        | 35.62%  |
| Qualcomm Atheros                  | 5         | 3.42%   |
| Broadcom                          | 3         | 2.05%   |
| Microsoft                         | 2         | 1.37%   |
| MediaTek                          | 2         | 1.37%   |
| Aquantia                          | 2         | 1.37%   |
| TP-Link                           | 1         | 0.68%   |
| Texas Instruments                 | 1         | 0.68%   |
| Standard Microsystems             | 1         | 0.68%   |
| Qualcomm                          | 1         | 0.68%   |
| Pulse-Eight                       | 1         | 0.68%   |
| Oculus VR                         | 1         | 0.68%   |
| Lenovo                            | 1         | 0.68%   |
| ICS Advent                        | 1         | 0.68%   |
| Fibocom                           | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 19.53%  |
| Intel Wi-Fi 6 AX200                                               | 15        | 8.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 8.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.96%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.96%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.78%   |
| Intel Wireless-AC 9260                                            | 3         | 1.78%   |
| Intel Wireless 8260                                               | 3         | 1.78%   |
| Intel Wireless 7260                                               | 3         | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.78%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.78%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.18%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.18%   |
| Intel Wireless 7265                                               | 2         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.18%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.18%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.59%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.59%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.59%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 78.57%  |
| Qualcomm Atheros      | 4         | 5.71%   |
| Realtek Semiconductor | 2         | 2.86%   |
| Microsoft             | 2         | 2.86%   |
| MediaTek              | 2         | 2.86%   |
| Broadcom              | 2         | 2.86%   |
| TP-Link               | 1         | 1.43%   |
| Qualcomm              | 1         | 1.43%   |
| Fibocom               | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 15        | 21.43%  |
| Intel Wi-Fi 6 AX201                                           | 4         | 5.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 5.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 4.29%   |
| Intel Wireless-AC 9260                                        | 3         | 4.29%   |
| Intel Wireless 8260                                           | 3         | 4.29%   |
| Intel Wireless 7260                                           | 3         | 4.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 4.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 4.29%   |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 2.86%   |
| Intel Wireless 8265 / 8275                                    | 2         | 2.86%   |
| Intel Wireless 7265                                           | 2         | 2.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 2.86%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 2.86%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.43%   |
| Qualcomm QCA6390 Wireless Network Adapter                     | 1         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.43%   |
| Intel Wireless 3165                                           | 1         | 1.43%   |
| Intel Wireless 3160                                           | 1         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 1.43%   |
| Fibocom L830-EB-00 LTE WWAN Modem                             | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 50        | 54.95%  |
| Intel                 | 33        | 36.26%  |
| Broadcom              | 2         | 2.2%    |
| Aquantia              | 2         | 2.2%    |
| Standard Microsystems | 1         | 1.1%    |
| Qualcomm Atheros      | 1         | 1.1%    |
| Lenovo                | 1         | 1.1%    |
| ICS Advent            | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 34.74%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 14.74%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 5         | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.16%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 3.16%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.11%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.11%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.11%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.11%   |
| Standard Microsystems Ethernet controller                         | 1         | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.05%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.05%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.05%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.05%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.05%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.05%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 52.63%  |
| WiFi     | 68        | 44.74%  |
| Modem    | 4         | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 53.4%   |
| Ethernet | 48        | 46.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 48.48%  |
| 2     | 43        | 43.43%  |
| 0     | 4         | 4.04%   |
| 3     | 3         | 3.03%   |
| 4     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 76.24%  |
| Yes  | 24        | 23.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 71.43%  |
| Realtek Semiconductor           | 4         | 5.71%   |
| Qualcomm Atheros Communications | 3         | 4.29%   |
| ASUSTek Computer                | 3         | 4.29%   |
| Cambridge Silicon Radio         | 2         | 2.86%   |
| Broadcom                        | 2         | 2.86%   |
| Apple                           | 2         | 2.86%   |
| MediaTek                        | 1         | 1.43%   |
| Lite-On Technology              | 1         | 1.43%   |
| HTC (High Tech Computer)        | 1         | 1.43%   |
| Foxconn / Hon Hai               | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 13        | 18.57%  |
| Intel Bluetooth wireless interface                                   | 10        | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 12.86%  |
| Intel AX201 Bluetooth                                                | 8         | 11.43%  |
| Realtek Bluetooth Radio                                              | 4         | 5.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 4.29%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 2.86%   |
| Intel Bluetooth Device                                               | 2         | 2.86%   |
| Intel AX210 Bluetooth                                                | 2         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 2.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.43%   |
| MediaTek Wireless_Device                                             | 1         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 1.43%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.43%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 1.43%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.43%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 1.43%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 61        | 37.89%  |
| AMD                                  | 36        | 22.36%  |
| Nvidia                               | 28        | 17.39%  |
| C-Media Electronics                  | 6         | 3.73%   |
| Texas Instruments                    | 3         | 1.86%   |
| Sennheiser Communications            | 3         | 1.86%   |
| Synaptics                            | 2         | 1.24%   |
| Realtek Semiconductor                | 2         | 1.24%   |
| Lenovo                               | 2         | 1.24%   |
| Kingston Technology                  | 2         | 1.24%   |
| Creative Technology                  | 2         | 1.24%   |
| Unknown                              | 1         | 0.62%   |
| Trust                                | 1         | 0.62%   |
| Thomann                              | 1         | 0.62%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.62%   |
| Sony                                 | 1         | 0.62%   |
| Schiit Audio                         | 1         | 0.62%   |
| Satechi                              | 1         | 0.62%   |
| Razer USA                            | 1         | 0.62%   |
| PreSonus Audio Electronics           | 1         | 0.62%   |
| GYROCOM C&C                          | 1         | 0.62%   |
| Creative Labs                        | 1         | 0.62%   |
| Corsair                              | 1         | 0.62%   |
| Antlion Audio                        | 1         | 0.62%   |
| (LCS) USB Audio Device               | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16        | 8.51%   |
| AMD Family 17h/19h HD Audio Controller                              | 12        | 6.38%   |
| Intel Sunrise Point-LP HD Audio                                     | 10        | 5.32%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 10        | 5.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 7         | 3.72%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 3.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 6         | 3.19%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 5         | 2.66%   |
| Intel Cannon Lake PCH cAVS                                          | 5         | 2.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 5         | 2.66%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                     | 3         | 1.6%    |
| Nvidia GK104 HDMI Audio Controller                                  | 3         | 1.6%    |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.6%    |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 3         | 1.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 1.6%    |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 1.06%   |
| Synaptics KM-HIFI-384KHZ                                            | 2         | 1.06%   |
| Sennheiser Communications Headset [PC 8]                            | 2         | 1.06%   |
| Realtek Semiconductor USB Audio                                     | 2         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.06%   |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1.06%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 1.06%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 2         | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 1.06%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 1.06%   |
| C-Media Electronics USB Advanced Audio Device                       | 2         | 1.06%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 2         | 1.06%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 26.79%  |
| Kingston            | 16        | 14.29%  |
| Micron Technology   | 14        | 12.5%   |
| Corsair             | 14        | 12.5%   |
| Crucial             | 10        | 8.93%   |
| SK hynix            | 7         | 6.25%   |
| G.Skill             | 7         | 6.25%   |
| Unknown (ABCD)      | 3         | 2.68%   |
| Unknown             | 3         | 2.68%   |
| Team                | 2         | 1.79%   |
| Goodram             | 2         | 1.79%   |
| Strontium           | 1         | 0.89%   |
| Avant               | 1         | 0.89%   |
| AMD                 | 1         | 0.89%   |
| A-DATA Technology   | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 2.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.65%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 2         | 1.65%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.65%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.65%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.65%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.65%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.65%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.65%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 1.65%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.83%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.83%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.83%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.83%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.83%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.83%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.83%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2048MB Row Of Chips 6400MT/s     | 1         | 0.83%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.83%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.83%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.83%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.83%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.83%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.83%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                   | 1         | 0.83%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.83%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.83%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 0.83%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s             | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 65        | 69.15%  |
| DDR3   | 16        | 17.02%  |
| LPDDR4 | 9         | 9.57%   |
| LPDDR5 | 2         | 2.13%   |
| LPDDR3 | 2         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 48.96%  |
| DIMM         | 35        | 36.46%  |
| Row Of Chips | 11        | 11.46%  |
| RIMM         | 1         | 1.04%   |
| Chip         | 1         | 1.04%   |
| Unknown      | 1         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 41        | 39.81%  |
| 16384 | 36        | 34.95%  |
| 32768 | 12        | 11.65%  |
| 4096  | 12        | 11.65%  |
| 2048  | 2         | 1.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 30        | 28.85%  |
| 2667  | 14        | 13.46%  |
| 2133  | 10        | 9.62%   |
| 1600  | 10        | 9.62%   |
| 2400  | 9         | 8.65%   |
| 3600  | 6         | 5.77%   |
| 4267  | 4         | 3.85%   |
| 3000  | 3         | 2.88%   |
| 6400  | 2         | 1.92%   |
| 4266  | 2         | 1.92%   |
| 3733  | 2         | 1.92%   |
| 3334  | 2         | 1.92%   |
| 1333  | 2         | 1.92%   |
| 3866  | 1         | 0.96%   |
| 3400  | 1         | 0.96%   |
| 3266  | 1         | 0.96%   |
| 2933  | 1         | 0.96%   |
| 2134  | 1         | 0.96%   |
| 2132  | 1         | 0.96%   |
| 1867  | 1         | 0.96%   |
| 1066  | 1         | 0.96%   |

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
| Chicony Electronics           | 12        | 19.67%  |
| Microdia                      | 9         | 14.75%  |
| Logitech                      | 7         | 11.48%  |
| IMC Networks                  | 7         | 11.48%  |
| Acer                          | 7         | 11.48%  |
| Realtek Semiconductor         | 5         | 8.2%    |
| Sunplus Innovation Technology | 3         | 4.92%   |
| Quanta                        | 3         | 4.92%   |
| MacroSilicon                  | 2         | 3.28%   |
| Apple                         | 2         | 3.28%   |
| Syntek                        | 1         | 1.64%   |
| SunplusIT                     | 1         | 1.64%   |
| Lite-On Technology            | 1         | 1.64%   |
| 2M UVC CAMERA                 | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 8         | 12.7%   |
| Microdia Integrated_Webcam_HD        | 5         | 7.94%   |
| IMC Networks USB2.0 HD UVC WebCam    | 4         | 6.35%   |
| Acer Integrated Camera               | 4         | 6.35%   |
| IMC Networks Integrated Camera       | 3         | 4.76%   |
| Chicony HP HD Camera                 | 3         | 4.76%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 3.17%   |
| Realtek Integrated_Webcam_HD         | 2         | 3.17%   |
| MacroSilicon USB Video               | 2         | 3.17%   |
| Acer Integrated IR Camera            | 2         | 3.17%   |
| Syntek Integrated Camera             | 1         | 1.59%   |
| SunplusIT HP TrueVision HD Camera    | 1         | 1.59%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.59%   |
| Realtek Lenovo easy camera           | 1         | 1.59%   |
| Realtek Laptop Camera                | 1         | 1.59%   |
| Realtek Integrated Webcam            | 1         | 1.59%   |
| Quanta VGA WebCam                    | 1         | 1.59%   |
| Quanta HP True Vision HD Camera      | 1         | 1.59%   |
| Quanta HD WebCam                     | 1         | 1.59%   |
| Microdia USB 2.0 Camera              | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.59%   |
| Microdia Integrated Webcam           | 1         | 1.59%   |
| Microdia Camera                      | 1         | 1.59%   |
| Logitech Webcam C930e                | 1         | 1.59%   |
| Logitech Webcam C310                 | 1         | 1.59%   |
| Logitech Webcam C270                 | 1         | 1.59%   |
| Logitech Webcam C120                 | 1         | 1.59%   |
| Logitech StreamCam                   | 1         | 1.59%   |
| Logitech HD Pro Webcam C920          | 1         | 1.59%   |
| Logitech C930c                       | 1         | 1.59%   |
| Lite-On HP HD Camera                 | 1         | 1.59%   |
| Chicony USB2.0 Camera                | 1         | 1.59%   |
| Apple iPhone 5/5C/5S/6/SE            | 1         | 1.59%   |
| Apple FaceTime HD Camera (Built-in)  | 1         | 1.59%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 1.59%   |
| Acer SunplusIT Integrated Camera     | 1         | 1.59%   |
| Acer HD Webcam                       | 1         | 1.59%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam  | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 43.75%  |
| Validity Sensors           | 5         | 31.25%  |
| Shenzhen Goodix Technology | 4         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 25%     |
| Shenzhen Goodix Fingerprint Reader                | 3         | 18.75%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 12.5%   |
| Unknown                                           | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 6.25%   |

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
| 0     | 58        | 57.43%  |
| 1     | 27        | 26.73%  |
| 2     | 15        | 14.85%  |
| 4     | 1         | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 13        | 22.41%  |
| Fingerprint reader       | 13        | 22.41%  |
| Chipcard                 | 8         | 13.79%  |
| Multimedia controller    | 7         | 12.07%  |
| Unassigned class         | 3         | 5.17%   |
| Net/wireless             | 3         | 5.17%   |
| Camera                   | 3         | 5.17%   |
| Bluetooth                | 3         | 5.17%   |
| Network                  | 1         | 1.72%   |
| Modem                    | 1         | 1.72%   |
| Dvb card                 | 1         | 1.72%   |
| Communication controller | 1         | 1.72%   |
| Card reader              | 1         | 1.72%   |

