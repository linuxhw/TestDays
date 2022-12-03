Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 5614

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | Notebook    | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | Notebook    | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 500                         | Notebook    | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Samsung       | NC10                        | Notebook    | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Dell          | 500                         | Notebook    | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| Gigabyte      | H81M-D2W                    | Desktop     | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASRock        | 775Dual-VSTA                | Desktop     | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Nvidia        | Tegra                       | Soc         | [bf3fee013b](https://linux-hardware.org/?probe=bf3fee013b) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| Acer          | Unknown                     | Notebook    | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | Notebook    | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| eMachines     | EL1358G                     | Desktop     | [eebc968f87](https://linux-hardware.org/?probe=eebc968f87) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | Notebook    | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| Alienware     | 17 R4                       | Notebook    | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| LG Electro... | LE50-5BC6H1                 | Notebook    | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cc16c01563](https://linux-hardware.org/?probe=cc16c01563) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b841f9332](https://linux-hardware.org/?probe=9b841f9332) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| Toshiba       | NB205                       | Notebook    | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [a193b562fa](https://linux-hardware.org/?probe=a193b562fa) | Jul 22, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [5128fcd55d](https://linux-hardware.org/?probe=5128fcd55d) | Jul 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | Notebook    | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | 1496                        | Desktop     | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [8a5a5a0987](https://linux-hardware.org/?probe=8a5a5a0987) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| Toshiba       | NB205                       | Notebook    | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | 07T4MC A02                  | Desktop     | [88de707c31](https://linux-hardware.org/?probe=88de707c31) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | Notebook    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | Notebook    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| Dell          | 500                         | Notebook    | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | Notebook    | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [5e9cdd75c7](https://linux-hardware.org/?probe=5e9cdd75c7) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | Notebook    | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| HP            | 15                          | Notebook    | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [fc761acd97](https://linux-hardware.org/?probe=fc761acd97) | Jun 18, 2022 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [89d99d840f](https://linux-hardware.org/?probe=89d99d840f) | Jun 17, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | Desktop     | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | Notebook    | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [535126df2b](https://linux-hardware.org/?probe=535126df2b) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | Notebook    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [5eaef9db5a](https://linux-hardware.org/?probe=5eaef9db5a) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [0ce0f27bac](https://linux-hardware.org/?probe=0ce0f27bac) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Unknown       | Unknown                     | Soc         | [0c5a37efd2](https://linux-hardware.org/?probe=0c5a37efd2) | Jun 05, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| HP            | 1497                        | Desktop     | [4b9a65b621](https://linux-hardware.org/?probe=4b9a65b621) | May 23, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| IBM           | ThinkPad T43 2668F5G        | Notebook    | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | Notebook    | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| Dell          | Latitude E6410              | Notebook    | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | A7K                         | Notebook    | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | Desktop     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [6dbe28a107](https://linux-hardware.org/?probe=6dbe28a107) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| HP            | 09F8h                       | Desktop     | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | Notebook    | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| eMachines     | MCP61PM-GM                  | Desktop     | [16c4522843](https://linux-hardware.org/?probe=16c4522843) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | Notebook    | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| HP            | Compaq 6730s                | Notebook    | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fe40f7c199](https://linux-hardware.org/?probe=fe40f7c199) | Apr 13, 2022 |
| Dell          | Precision 7550              | Notebook    | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [14ae36ec3e](https://linux-hardware.org/?probe=14ae36ec3e) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [1f1a2dbacc](https://linux-hardware.org/?probe=1f1a2dbacc) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0a0a02bac3](https://linux-hardware.org/?probe=0a0a02bac3) | Apr 04, 2022 |
| Wortmann      | M7x0S                       | Notebook    | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | Desktop     | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Dell          | 0WM839 A00                  | All in one  | [b5edf6760d](https://linux-hardware.org/?probe=b5edf6760d) | Apr 02, 2022 |
| Shuttle       | FH61V                       | Desktop     | [05c1b046da](https://linux-hardware.org/?probe=05c1b046da) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [b89bd4d737](https://linux-hardware.org/?probe=b89bd4d737) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [65009176b4](https://linux-hardware.org/?probe=65009176b4) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [d3f3139ac2](https://linux-hardware.org/?probe=d3f3139ac2) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [647fd89862](https://linux-hardware.org/?probe=647fd89862) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Acer          | Aspire one                  | Notebook    | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da62c7238d](https://linux-hardware.org/?probe=da62c7238d) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Lenovo        | 36FD SDK0J40709 WIN 3259... | All in one  | [75410d5871](https://linux-hardware.org/?probe=75410d5871) | Mar 27, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| Dell          | Latitude E6400              | Notebook    | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d755a1a962](https://linux-hardware.org/?probe=d755a1a962) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2cfe733664](https://linux-hardware.org/?probe=2cfe733664) | Mar 22, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R510/P510                   | Notebook    | [5ec1b197a4](https://linux-hardware.org/?probe=5ec1b197a4) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Toshiba       | NB205                       | Notebook    | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Teclast       | F15 Plus                    | Notebook    | [9d3b8151f2](https://linux-hardware.org/?probe=9d3b8151f2) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [69cae65bf4](https://linux-hardware.org/?probe=69cae65bf4) | Mar 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [67a1970f50](https://linux-hardware.org/?probe=67a1970f50) | Mar 16, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Gigabyte      | 8IPE775/-G                  | Desktop     | [7888ddbc2b](https://linux-hardware.org/?probe=7888ddbc2b) | Mar 13, 2022 |
| Dell          | 0RW199                      | Desktop     | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2c17897902](https://linux-hardware.org/?probe=2c17897902) | Mar 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Dell          | Latitude E6400              | Notebook    | [bcacefe427](https://linux-hardware.org/?probe=bcacefe427) | Mar 08, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [4e626b238b](https://linux-hardware.org/?probe=4e626b238b) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | Notebook    | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | Notebook    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Dell          | 0Y958C A00                  | Desktop     | [e2abde1282](https://linux-hardware.org/?probe=e2abde1282) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | Notebook    | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| MSI           | G41M-P25                    | Desktop     | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | Notebook    | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [e7013b772d](https://linux-hardware.org/?probe=e7013b772d) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Gateway       | M-6307                      | Notebook    | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| ASUSTek       | A2D                         | Notebook    | [6fbba6195d](https://linux-hardware.org/?probe=6fbba6195d) | Feb 17, 2022 |
| Lenovo        | ThinkPad R500 2716A54       | Notebook    | [9aa87e9270](https://linux-hardware.org/?probe=9aa87e9270) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [354434e81d](https://linux-hardware.org/?probe=354434e81d) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| HP            | x2 210 G2                   | Tablet      | [6cab74e68a](https://linux-hardware.org/?probe=6cab74e68a) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| Khadas        | VIM2                        | Soc         | [c3e2b43e74](https://linux-hardware.org/?probe=c3e2b43e74) | Feb 13, 2022 |
| Dell          | 0FH884                      | Desktop     | [bd2aa894cc](https://linux-hardware.org/?probe=bd2aa894cc) | Feb 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [33d5b7046b](https://linux-hardware.org/?probe=33d5b7046b) | Feb 13, 2022 |
| Samsung       | 900X1B                      | Notebook    | [c609dfc310](https://linux-hardware.org/?probe=c609dfc310) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| HP            | ProBook 655 G1              | Notebook    | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [d455b09330](https://linux-hardware.org/?probe=d455b09330) | Feb 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| HP            | x2 210 G2                   | Tablet      | [8ff26bf040](https://linux-hardware.org/?probe=8ff26bf040) | Feb 08, 2022 |
| Acer          | TravelMate 8172             | Notebook    | [76e402e3d6](https://linux-hardware.org/?probe=76e402e3d6) | Feb 07, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b4fe3a7a24](https://linux-hardware.org/?probe=b4fe3a7a24) | Feb 07, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| HP            | 1497                        | Desktop     | [2a41e081da](https://linux-hardware.org/?probe=2a41e081da) | Feb 06, 2022 |
| Acer          | Aspire 5100                 | Notebook    | [191eb6224a](https://linux-hardware.org/?probe=191eb6224a) | Feb 06, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| IBM           | ThinkPad T43 2668BU7        | Notebook    | [2586bf5e87](https://linux-hardware.org/?probe=2586bf5e87) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [84845ef09c](https://linux-hardware.org/?probe=84845ef09c) | Feb 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [fc7d07dba8](https://linux-hardware.org/?probe=fc7d07dba8) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| HP            | 872E                        | Mini pc     | [8366a84cdb](https://linux-hardware.org/?probe=8366a84cdb) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [533e06f8ac](https://linux-hardware.org/?probe=533e06f8ac) | Feb 02, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [28280d252b](https://linux-hardware.org/?probe=28280d252b) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [8eab19298c](https://linux-hardware.org/?probe=8eab19298c) | Feb 01, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [172fc399f5](https://linux-hardware.org/?probe=172fc399f5) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| HP            | EliteBook 725 G2            | Notebook    | [d49dd26324](https://linux-hardware.org/?probe=d49dd26324) | Feb 01, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [346195c820](https://linux-hardware.org/?probe=346195c820) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [460a295f83](https://linux-hardware.org/?probe=460a295f83) | Jan 30, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [bea5e134d8](https://linux-hardware.org/?probe=bea5e134d8) | Jan 30, 2022 |
| Gateway       | MT6831                      | Notebook    | [36947a389a](https://linux-hardware.org/?probe=36947a389a) | Jan 30, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Acer          | AOD257                      | Notebook    | [4d8476adb1](https://linux-hardware.org/?probe=4d8476adb1) | Jan 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [e18b673cd3](https://linux-hardware.org/?probe=e18b673cd3) | Jan 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [c969e228f3](https://linux-hardware.org/?probe=c969e228f3) | Jan 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| ASRock        | M3A UCC                     | Desktop     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| HP            | 1497                        | Desktop     | [3a3b4fe530](https://linux-hardware.org/?probe=3a3b4fe530) | Jan 27, 2022 |
| Pegatron      | Benicia                     | Desktop     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ca6be0ae4b](https://linux-hardware.org/?probe=ca6be0ae4b) | Jan 26, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [8a951a4419](https://linux-hardware.org/?probe=8a951a4419) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| HP            | G42                         | Notebook    | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | Notebook    | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [d914fce08c](https://linux-hardware.org/?probe=d914fce08c) | Jan 24, 2022 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [db13a3f215](https://linux-hardware.org/?probe=db13a3f215) | Jan 24, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [9a38c32175](https://linux-hardware.org/?probe=9a38c32175) | Jan 24, 2022 |
| HP            | G60                         | Notebook    | [acd0e22a1a](https://linux-hardware.org/?probe=acd0e22a1a) | Jan 23, 2022 |
| MSI           | U90/U100                    | Notebook    | [a87163f5ea](https://linux-hardware.org/?probe=a87163f5ea) | Jan 23, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | Notebook    | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| Intel         | DG965MQ AAD37419-302        | Desktop     | [0c7117815f](https://linux-hardware.org/?probe=0c7117815f) | Jan 23, 2022 |
| MSI           | U90/U100                    | Notebook    | [a005adaf94](https://linux-hardware.org/?probe=a005adaf94) | Jan 23, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [75d4eef3ba](https://linux-hardware.org/?probe=75d4eef3ba) | Jan 22, 2022 |
| ASUSTek       | K8V-MXG                     | Desktop     | [504cbc919c](https://linux-hardware.org/?probe=504cbc919c) | Jan 21, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | Notebook    | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | Notebook    | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| ASUSTek       | K8V-MXG                     | Desktop     | [d4138da396](https://linux-hardware.org/?probe=d4138da396) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b6de24e7df](https://linux-hardware.org/?probe=b6de24e7df) | Jan 20, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [452df44e84](https://linux-hardware.org/?probe=452df44e84) | Jan 20, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | Notebook    | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 1885      | 50.07%  |
| Xubuntu 18.04 | 1012      | 26.88%  |
| Xubuntu 22.04 | 238       | 6.32%   |
| Xubuntu 19.10 | 199       | 5.29%   |
| Xubuntu 21.10 | 96        | 2.55%   |
| Xubuntu 16.04 | 95        | 2.52%   |
| Xubuntu 20.10 | 93        | 2.47%   |
| Xubuntu 21.04 | 79        | 2.1%    |
| Xubuntu 19.04 | 26        | 0.69%   |
| Xubuntu 22.10 | 14        | 0.37%   |
| Xubuntu 18.10 | 11        | 0.29%   |
| Xubuntu 17.10 | 6         | 0.16%   |
| Xubuntu       | 6         | 0.16%   |
| Xubuntu 14.04 | 3         | 0.08%   |
| Xubuntu 17.04 | 2         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 3647      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 155       | 3.6%    |
| 5.4.0-48-generic    | 65        | 1.51%   |
| 5.4.0-58-generic    | 60        | 1.4%    |
| 5.4.0-52-generic    | 59        | 1.37%   |
| 5.3.0-46-generic    | 59        | 1.37%   |
| 5.11.0-27-generic   | 50        | 1.16%   |
| 5.4.0-65-generic    | 48        | 1.12%   |
| 5.3.0-40-generic    | 48        | 1.12%   |
| 5.4.0-29-generic    | 46        | 1.07%   |
| 5.4.0-54-generic    | 45        | 1.05%   |
| 5.4.0-47-generic    | 42        | 0.98%   |
| 5.4.0-42-lowlatency | 40        | 0.93%   |
| 5.15.0-52-generic   | 40        | 0.93%   |
| 5.4.0-26-generic    | 38        | 0.88%   |
| 5.3.0-42-generic    | 38        | 0.88%   |
| 5.3.0-28-generic    | 36        | 0.84%   |
| 5.4.0-40-generic    | 35        | 0.81%   |
| 5.0.0-37-generic    | 35        | 0.81%   |
| 5.3.0-51-generic    | 34        | 0.79%   |
| 5.4.0-37-generic    | 33        | 0.77%   |
| 5.4.0-66-generic    | 31        | 0.72%   |
| 5.15.0-47-generic   | 31        | 0.72%   |
| 4.15.0-99-generic   | 31        | 0.72%   |
| 5.4.0-89-generic    | 30        | 0.7%    |
| 5.4.0-31-generic    | 30        | 0.7%    |
| 5.15.0-48-generic   | 29        | 0.67%   |
| 5.4.0-72-generic    | 28        | 0.65%   |
| 5.3.0-53-generic    | 28        | 0.65%   |
| 5.15.0-46-generic   | 28        | 0.65%   |
| 5.4.0-29-lowlatency | 27        | 0.63%   |
| 5.4.0-91-generic    | 26        | 0.6%    |
| 5.4.0-81-generic    | 26        | 0.6%    |
| 5.8.0-53-generic    | 25        | 0.58%   |
| 5.4.0-33-generic    | 25        | 0.58%   |
| 5.13.0-39-generic   | 25        | 0.58%   |
| 5.8.0-43-generic    | 24        | 0.56%   |
| 5.4.0-56-generic    | 24        | 0.56%   |
| 5.13.0-30-generic   | 24        | 0.56%   |
| 5.11.0-37-generic   | 24        | 0.56%   |
| 5.4.0-77-generic    | 23        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1547      | 40.32%  |
| 4.15.0  | 470       | 12.25%  |
| 5.3.0   | 438       | 11.42%  |
| 5.11.0  | 275       | 7.17%   |
| 5.15.0  | 263       | 6.85%   |
| 5.8.0   | 255       | 6.65%   |
| 5.13.0  | 221       | 5.76%   |
| 5.0.0   | 107       | 2.79%   |
| 4.4.0   | 46        | 1.2%    |
| 4.18.0  | 25        | 0.65%   |
| 5.19.0  | 16        | 0.42%   |
| 4.13.0  | 9         | 0.23%   |
| 5.17.0  | 8         | 0.21%   |
| 4.10.0  | 6         | 0.16%   |
| 5.6.0   | 5         | 0.13%   |
| 5.14.0  | 5         | 0.13%   |
| 5.10.0  | 5         | 0.13%   |
| 5.9.8   | 3         | 0.08%   |
| 5.9.16  | 3         | 0.08%   |
| 5.18.0  | 3         | 0.08%   |
| 5.15.1  | 3         | 0.08%   |
| 5.11.16 | 3         | 0.08%   |
| 4.8.0   | 3         | 0.08%   |
| 6.0.0   | 2         | 0.05%   |
| 5.9.0   | 2         | 0.05%   |
| 5.7.7   | 2         | 0.05%   |
| 5.7.6   | 2         | 0.05%   |
| 5.7.1   | 2         | 0.05%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.19  | 2         | 0.05%   |
| 5.5.19  | 2         | 0.05%   |
| 5.16.9  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.13.7  | 2         | 0.05%   |
| 5.12.12 | 2         | 0.05%   |
| 5.12.10 | 2         | 0.05%   |
| 5.11.6  | 2         | 0.05%   |
| 5.11.11 | 2         | 0.05%   |
| 4.9.253 | 2         | 0.05%   |
| 4.4.254 | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1554      | 40.54%  |
| 4.15    | 470       | 12.26%  |
| 5.3     | 440       | 11.48%  |
| 5.11    | 282       | 7.36%   |
| 5.15    | 274       | 7.15%   |
| 5.8     | 260       | 6.78%   |
| 5.13    | 225       | 5.87%   |
| 5.0     | 109       | 2.84%   |
| 4.4     | 49        | 1.28%   |
| 4.18    | 25        | 0.65%   |
| 5.19    | 18        | 0.47%   |
| 5.10    | 15        | 0.39%   |
| 5.9     | 11        | 0.29%   |
| 5.7     | 10        | 0.26%   |
| 5.14    | 10        | 0.26%   |
| 5.6     | 9         | 0.23%   |
| 5.17    | 9         | 0.23%   |
| 4.13    | 9         | 0.23%   |
| 5.12    | 8         | 0.21%   |
| 4.19    | 7         | 0.18%   |
| 4.10    | 6         | 0.16%   |
| 5.18    | 5         | 0.13%   |
| 5.16    | 5         | 0.13%   |
| 6.0     | 4         | 0.1%    |
| 4.9     | 4         | 0.1%    |
| 5.5     | 3         | 0.08%   |
| 4.8     | 3         | 0.08%   |
| 5.2     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 4.20    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3125      | 85.55%  |
| i686    | 491       | 13.44%  |
| aarch64 | 29        | 0.79%   |
| armv7l  | 8         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 3524      | 96.44%  |
| GNOME           | 89        | 2.44%   |
| i3              | 8         | 0.22%   |
| KDE5            | 7         | 0.19%   |
| Cinnamon        | 7         | 0.19%   |
| Unity           | 4         | 0.11%   |
| GNOME Flashback | 4         | 0.11%   |
| X-Cinnamon      | 2         | 0.05%   |
| MATE            | 2         | 0.05%   |
| LXQt            | 2         | 0.05%   |
| xmonad          | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |
| Unknown         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3586      | 98.25%  |
| Tty     | 44        | 1.21%   |
| Wayland | 15        | 0.41%   |
| Web     | 3         | 0.08%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2073      | 55.06%  |
| LightDM | 1084      | 28.79%  |
| TDM     | 508       | 13.49%  |
| GDM     | 46        | 1.22%   |
| GDM3    | 41        | 1.09%   |
| SDDM    | 7         | 0.19%   |
| XDM     | 4         | 0.11%   |
| SLiM    | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1169      | 31.89%  |
| de_DE   | 374       | 10.2%   |
| fr_FR   | 314       | 8.57%   |
| it_IT   | 253       | 6.9%    |
| pt_BR   | 189       | 5.16%   |
| ru_RU   | 172       | 4.69%   |
| en_GB   | 136       | 3.71%   |
| C       | 130       | 3.55%   |
| es_ES   | 101       | 2.76%   |
| en_CA   | 86        | 2.35%   |
| Unknown | 81        | 2.21%   |
| en_AU   | 67        | 1.83%   |
| pl_PL   | 55        | 1.5%    |
| es_AR   | 40        | 1.09%   |
| nl_NL   | 37        | 1.01%   |
| hu_HU   | 37        | 1.01%   |
| ja_JP   | 35        | 0.95%   |
| cs_CZ   | 29        | 0.79%   |
| en_IN   | 21        | 0.57%   |
| es_MX   | 20        | 0.55%   |
| pt_PT   | 16        | 0.44%   |
| fr_BE   | 16        | 0.44%   |
| fi_FI   | 16        | 0.44%   |
| sv_SE   | 14        | 0.38%   |
| sk_SK   | 14        | 0.38%   |
| ru_UA   | 14        | 0.38%   |
| tr_TR   | 13        | 0.35%   |
| en_ZA   | 13        | 0.35%   |
| el_GR   | 12        | 0.33%   |
| de_CH   | 12        | 0.33%   |
| de_AT   | 12        | 0.33%   |
| zh_TW   | 11        | 0.3%    |
| fr_CA   | 11        | 0.3%    |
| es_CO   | 11        | 0.3%    |
| nl_BE   | 9         | 0.25%   |
| zh_CN   | 8         | 0.22%   |
| es_VE   | 8         | 0.22%   |
| ca_ES   | 7         | 0.19%   |
| bg_BG   | 7         | 0.19%   |
| es_PE   | 6         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2444      | 66.29%  |
| EFI  | 1243      | 33.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3357      | 91.77%  |
| Overlay | 146       | 3.99%   |
| Btrfs   | 63        | 1.72%   |
| Zfs     | 33        | 0.9%    |
| Unknown | 24        | 0.66%   |
| Xfs     | 15        | 0.41%   |
| Ext2    | 11        | 0.3%    |
| Ext3    | 7         | 0.19%   |
| Ufs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2461      | 66.89%  |
| GPT     | 775       | 21.07%  |
| MBR     | 443       | 12.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3103      | 83.37%  |
| Yes       | 619       | 16.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2443      | 65.81%  |
| Yes       | 1269      | 34.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 576       | 15.79%  |
| ASUSTek Computer        | 554       | 15.19%  |
| Dell                    | 446       | 12.23%  |
| Lenovo                  | 426       | 11.68%  |
| Acer                    | 243       | 6.66%   |
| Gigabyte Technology     | 206       | 5.65%   |
| MSI                     | 164       | 4.5%    |
| ASRock                  | 139       | 3.81%   |
| Toshiba                 | 95        | 2.6%    |
| Apple                   | 66        | 1.81%   |
| Intel                   | 62        | 1.7%    |
| Samsung Electronics     | 55        | 1.51%   |
| Sony                    | 45        | 1.23%   |
| Medion                  | 42        | 1.15%   |
| Unknown                 | 37        | 1.01%   |
| Fujitsu Siemens         | 30        | 0.82%   |
| Fujitsu                 | 30        | 0.82%   |
| ECS                     | 28        | 0.77%   |
| Packard Bell            | 25        | 0.69%   |
| Foxconn                 | 20        | 0.55%   |
| Positivo                | 16        | 0.44%   |
| Raspberry Pi Foundation | 15        | 0.41%   |
| Notebook                | 15        | 0.41%   |
| Google                  | 15        | 0.41%   |
| Pegatron                | 13        | 0.36%   |
| eMachines               | 13        | 0.36%   |
| Clevo                   | 13        | 0.36%   |
| IBM                     | 12        | 0.33%   |
| Supermicro              | 10        | 0.27%   |
| HUAWEI                  | 10        | 0.27%   |
| AMI                     | 9         | 0.25%   |
| LG Electronics          | 8         | 0.22%   |
| Gateway                 | 8         | 0.22%   |
| Biostar                 | 8         | 0.22%   |
| ZOTAC                   | 7         | 0.19%   |
| NEC Computers           | 6         | 0.16%   |
| GPU Company             | 6         | 0.16%   |
| Alienware               | 6         | 0.16%   |
| Semp Toshiba            | 5         | 0.14%   |
| OEM                     | 5         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 57        | 1.56%   |
| ASUS All Series                        | 25        | 0.69%   |
| HP Pavilion dv6                        | 17        | 0.47%   |
| HP Notebook                            | 17        | 0.47%   |
| Gigabyte H410M S2H                     | 15        | 0.41%   |
| Dell OptiPlex 7010                     | 15        | 0.41%   |
| Dell OptiPlex 755                      | 11        | 0.3%    |
| Dell Latitude D630                     | 11        | 0.3%    |
| HP 15                                  | 10        | 0.27%   |
| ECS G31T-M9                            | 9         | 0.25%   |
| HP Pavilion 15                         | 8         | 0.22%   |
| Dell OptiPlex 780                      | 8         | 0.22%   |
| Dell OptiPlex 760                      | 8         | 0.22%   |
| Dell OptiPlex 390                      | 8         | 0.22%   |
| ASRock N68C-S UCC                      | 8         | 0.22%   |
| HP Pavilion dv6500                     | 7         | 0.19%   |
| Dell Latitude E6430                    | 7         | 0.19%   |
| MSI MS-7C37                            | 6         | 0.16%   |
| HP Pavilion g6                         | 6         | 0.16%   |
| HP Pavilion dv7                        | 6         | 0.16%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.16%   |
| ASUS TUF Gaming X570-PLUS              | 6         | 0.16%   |
| MSI MS-7B89                            | 5         | 0.14%   |
| MSI MS-7B79                            | 5         | 0.14%   |
| MSI MS-7A38                            | 5         | 0.14%   |
| MSI MS-7721                            | 5         | 0.14%   |
| HP EliteDesk 800 G1 SFF                | 5         | 0.14%   |
| HP EliteBook 840 G3                    | 5         | 0.14%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.14%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.14%   |
| Dell OptiPlex GX620                    | 5         | 0.14%   |
| Dell Latitude E6520                    | 5         | 0.14%   |
| ASUS M5A78L-M/USB3                     | 5         | 0.14%   |
| ASUS 1005HA                            | 5         | 0.14%   |
| Acer Aspire one                        | 5         | 0.14%   |
| Acer AO751h                            | 5         | 0.14%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 4         | 0.11%   |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 4         | 0.11%   |
| Positivo Mobile                        | 4         | 0.11%   |
| MSI MS-7C02                            | 4         | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 211       | 5.79%   |
| Acer Aspire           | 154       | 4.22%   |
| Dell Inspiron         | 122       | 3.35%   |
| Dell Latitude         | 110       | 3.02%   |
| HP Pavilion           | 106       | 2.91%   |
| HP Compaq             | 106       | 2.91%   |
| Dell OptiPlex         | 93        | 2.55%   |
| Toshiba Satellite     | 80        | 2.19%   |
| Lenovo IdeaPad        | 64        | 1.75%   |
| Unknown               | 57        | 1.56%   |
| HP EliteBook          | 56        | 1.54%   |
| HP ProBook            | 43        | 1.18%   |
| ASUS PRIME            | 41        | 1.12%   |
| Lenovo ThinkCentre    | 38        | 1.04%   |
| HP Laptop             | 36        | 0.99%   |
| Dell Precision        | 34        | 0.93%   |
| ASUS VivoBook         | 33        | 0.9%    |
| ASUS All              | 25        | 0.69%   |
| ASUS TUF              | 20        | 0.55%   |
| Dell Vostro           | 19        | 0.52%   |
| HP Notebook           | 18        | 0.49%   |
| Dell XPS              | 18        | 0.49%   |
| HP ProDesk            | 17        | 0.47%   |
| Acer Extensa          | 16        | 0.44%   |
| RPi Raspberry         | 15        | 0.41%   |
| Gigabyte H410M        | 15        | 0.41%   |
| Fujitsu Siemens AMILO | 15        | 0.41%   |
| ASUS ROG              | 15        | 0.41%   |
| Acer Veriton          | 15        | 0.41%   |
| Packard Bell EasyNote | 14        | 0.38%   |
| Dell PowerEdge        | 14        | 0.38%   |
| HP ENVY               | 13        | 0.36%   |
| HP EliteDesk          | 12        | 0.33%   |
| Fujitsu LIFEBOOK      | 12        | 0.33%   |
| Dell Studio           | 12        | 0.33%   |
| HP Presario           | 11        | 0.3%    |
| HP Mini               | 11        | 0.3%    |
| HP 255                | 11        | 0.3%    |
| HP 15                 | 11        | 0.3%    |
| Fujitsu ESPRIMO       | 11        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 310       | 8.5%    |
| 2011    | 310       | 8.5%    |
| 2010    | 281       | 7.7%    |
| 2008    | 280       | 7.68%   |
| 2013    | 272       | 7.46%   |
| 2009    | 256       | 7.02%   |
| 2007    | 252       | 6.91%   |
| 2019    | 220       | 6.03%   |
| 2018    | 202       | 5.54%   |
| 2014    | 199       | 5.46%   |
| 2017    | 188       | 5.15%   |
| 2020    | 186       | 5.1%    |
| 2015    | 145       | 3.98%   |
| 2016    | 143       | 3.92%   |
| 2006    | 142       | 3.89%   |
| 2021    | 107       | 2.93%   |
| 2005    | 67        | 1.84%   |
| Unknown | 34        | 0.93%   |
| 2004    | 16        | 0.44%   |
| 2022    | 15        | 0.41%   |
| 2003    | 15        | 0.41%   |
| 2001    | 4         | 0.11%   |
| 2002    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1991      | 54.59%  |
| Desktop        | 1453      | 39.84%  |
| Mini pc        | 47        | 1.29%   |
| All in one     | 41        | 1.12%   |
| System on chip | 35        | 0.96%   |
| Convertible    | 34        | 0.93%   |
| Server         | 31        | 0.85%   |
| Tablet         | 14        | 0.38%   |
| Firewall       | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3465      | 94.59%  |
| Enabled  | 198       | 5.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3631      | 99.56%  |
| Yes  | 16        | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 983       | 26.55%  |
| 4.01-8.0        | 691       | 18.66%  |
| 8.01-16.0       | 500       | 13.5%   |
| 16.01-24.0      | 465       | 12.56%  |
| 1.01-2.0        | 456       | 12.31%  |
| 32.01-64.0      | 189       | 5.1%    |
| 0.51-1.0        | 146       | 3.94%   |
| 2.01-3.0        | 143       | 3.86%   |
| 64.01-256.0     | 75        | 2.03%   |
| 24.01-32.0      | 41        | 1.11%   |
| 0.01-0.5        | 12        | 0.32%   |
| More than 256.0 | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1704      | 42.24%  |
| 0.51-1.0   | 824       | 20.43%  |
| 2.01-3.0   | 715       | 17.72%  |
| 4.01-8.0   | 313       | 7.76%   |
| 3.01-4.0   | 256       | 6.35%   |
| 0.01-0.5   | 115       | 2.85%   |
| 8.01-16.0  | 87        | 2.16%   |
| 16.01-24.0 | 10        | 0.25%   |
| 24.01-32.0 | 7         | 0.17%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2328      | 62.15%  |
| 2      | 897       | 23.95%  |
| 3      | 282       | 7.53%   |
| 4      | 109       | 2.91%   |
| 5      | 47        | 1.25%   |
| 0      | 43        | 1.15%   |
| 6      | 19        | 0.51%   |
| 7      | 12        | 0.32%   |
| 10     | 4         | 0.11%   |
| 8      | 3         | 0.08%   |
| 9      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1950      | 53.05%  |
| No        | 1726      | 46.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3323      | 91.07%  |
| No        | 326       | 8.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2636      | 71.73%  |
| No        | 1039      | 28.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2110      | 57.18%  |
| Yes       | 1580      | 42.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 573       | 15.64%  |
| Germany      | 454       | 12.39%  |
| France       | 328       | 8.95%   |
| Italy        | 281       | 7.67%   |
| Russia       | 222       | 6.06%   |
| Brazil       | 213       | 5.81%   |
| Canada       | 141       | 3.85%   |
| UK           | 137       | 3.74%   |
| Spain        | 120       | 3.28%   |
| Netherlands  | 90        | 2.46%   |
| Australia    | 76        | 2.07%   |
| Poland       | 66        | 1.8%    |
| Ukraine      | 54        | 1.47%   |
| Argentina    | 53        | 1.45%   |
| Belgium      | 47        | 1.28%   |
| Hungary      | 43        | 1.17%   |
| Japan        | 41        | 1.12%   |
| Mexico       | 40        | 1.09%   |
| Czechia      | 40        | 1.09%   |
| Finland      | 39        | 1.06%   |
| Sweden       | 36        | 0.98%   |
| Portugal     | 34        | 0.93%   |
| Greece       | 32        | 0.87%   |
| India        | 31        | 0.85%   |
| Indonesia    | 27        | 0.74%   |
| Bulgaria     | 25        | 0.68%   |
| Austria      | 24        | 0.66%   |
| Turkey       | 21        | 0.57%   |
| Romania      | 21        | 0.57%   |
| Slovakia     | 18        | 0.49%   |
| Switzerland  | 17        | 0.46%   |
| Iran         | 16        | 0.44%   |
| Taiwan       | 15        | 0.41%   |
| Norway       | 15        | 0.41%   |
| Colombia     | 14        | 0.38%   |
| South Africa | 13        | 0.35%   |
| Israel       | 12        | 0.33%   |
| Venezuela    | 11        | 0.3%    |
| Denmark      | 10        | 0.27%   |
| Chile        | 10        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 47        | 1.22%   |
| Berlin            | 42        | 1.09%   |
| Moscow            | 38        | 0.98%   |
| Rome              | 33        | 0.85%   |
| Milan             | 30        | 0.78%   |
| Voronezh          | 27        | 0.7%    |
| Sao Paulo         | 25        | 0.65%   |
| Sydney            | 24        | 0.62%   |
| Amsterdam         | 23        | 0.6%    |
| Madrid            | 21        | 0.54%   |
| Athens            | 21        | 0.54%   |
| Warsaw            | 20        | 0.52%   |
| St Petersburg     | 20        | 0.52%   |
| Munich            | 20        | 0.52%   |
| Hamburg           | 20        | 0.52%   |
| Budapest          | 20        | 0.52%   |
| Québec           | 19        | 0.49%   |
| Helsinki          | 17        | 0.44%   |
| Rio de Janeiro    | 16        | 0.41%   |
| Genoa             | 16        | 0.41%   |
| Barcelona         | 16        | 0.41%   |
| Oryol             | 15        | 0.39%   |
| Montreal          | 15        | 0.39%   |
| Kyiv              | 15        | 0.39%   |
| Melbourne         | 14        | 0.36%   |
| Turin             | 13        | 0.34%   |
| Buenos Aires      | 13        | 0.34%   |
| Vancouver         | 12        | 0.31%   |
| Tehran            | 12        | 0.31%   |
| Sofia             | 12        | 0.31%   |
| Prague            | 12        | 0.31%   |
| Leipzig           | 12        | 0.31%   |
| Toronto           | 11        | 0.28%   |
| Frankfurt am Main | 11        | 0.28%   |
| Belo Horizonte    | 11        | 0.28%   |
| Yokohama          | 10        | 0.26%   |
| Vienna            | 10        | 0.26%   |
| Lisbon            | 10        | 0.26%   |
| Cologne           | 10        | 0.26%   |
| Stuttgart         | 9         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 929       | 1348   | 18.51%  |
| WDC                 | 868       | 1247   | 17.29%  |
| Samsung Electronics | 666       | 937    | 13.27%  |
| Toshiba             | 357       | 445    | 7.11%   |
| Hitachi             | 302       | 395    | 6.02%   |
| Unknown             | 244       | 308    | 4.86%   |
| Kingston            | 223       | 285    | 4.44%   |
| SanDisk             | 172       | 214    | 3.43%   |
| Crucial             | 133       | 177    | 2.65%   |
| HGST                | 102       | 119    | 2.03%   |
| Intel               | 93        | 134    | 1.85%   |
| SK hynix            | 75        | 87     | 1.49%   |
| Fujitsu             | 66        | 83     | 1.31%   |
| A-DATA Technology   | 66        | 85     | 1.31%   |
| Maxtor              | 59        | 84     | 1.18%   |
| China               | 51        | 61     | 1.02%   |
| Micron Technology   | 37        | 41     | 0.74%   |
| PNY                 | 32        | 42     | 0.64%   |
| Patriot             | 30        | 35     | 0.6%    |
| OCZ                 | 27        | 34     | 0.54%   |
| Transcend           | 26        | 28     | 0.52%   |
| Phison              | 24        | 34     | 0.48%   |
| Intenso             | 24        | 31     | 0.48%   |
| Apple               | 18        | 26     | 0.36%   |
| KIOXIA              | 17        | 21     | 0.34%   |
| SPCC                | 16        | 23     | 0.32%   |
| LITEON              | 15        | 17     | 0.3%    |
| LITEONIT            | 14        | 17     | 0.28%   |
| Apacer              | 14        | 20     | 0.28%   |
| Unknown             | 13        | 13     | 0.26%   |
| Silicon Motion      | 12        | 13     | 0.24%   |
| ASMT                | 12        | 18     | 0.24%   |
| KingDian            | 11        | 17     | 0.22%   |
| JMicron Technology  | 10        | 10     | 0.2%    |
| Lexar               | 9         | 9      | 0.18%   |
| Hewlett-Packard     | 9         | 13     | 0.18%   |
| USB3.0              | 7         | 10     | 0.14%   |
| Smartbuy            | 7         | 7      | 0.14%   |
| Plextor             | 7         | 8      | 0.14%   |
| KingSpec            | 7         | 9      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 63        | 1.14%   |
| Unknown MMC Card  32GB                 | 49        | 0.89%   |
| Seagate ST500DM002-1BD142 500GB        | 48        | 0.87%   |
| Samsung SSD 860 EVO 500GB              | 40        | 0.73%   |
| Kingston SA400S37480G 480GB SSD        | 37        | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 32        | 0.58%   |
| Unknown MMC Card  64GB                 | 30        | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 30        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB         | 30        | 0.55%   |
| Samsung SSD 850 EVO 250GB              | 30        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB        | 29        | 0.53%   |
| Toshiba MQ01ABF050 500GB               | 26        | 0.47%   |
| Toshiba MQ01ABD100 1TB                 | 26        | 0.47%   |
| Samsung SSD 850 EVO 500GB              | 26        | 0.47%   |
| Kingston SA400S37120G 120GB SSD        | 24        | 0.44%   |
| Seagate ST1000LM035-1RK172 1TB         | 23        | 0.42%   |
| Unknown SD/MMC/MS PRO 8GB              | 22        | 0.4%    |
| Seagate ST3500418AS 500GB              | 22        | 0.4%    |
| Seagate Expansion 1TB                  | 22        | 0.4%    |
| Toshiba DT01ACA100 1TB                 | 21        | 0.38%   |
| HGST HTS721010A9E630 1TB               | 21        | 0.38%   |
| HGST HTS541010A9E680 1TB               | 20        | 0.36%   |
| Seagate ST9500325AS 500GB              | 19        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB         | 19        | 0.35%   |
| Unknown MMC Card  128GB                | 18        | 0.33%   |
| Seagate ST31000528AS 1TB               | 18        | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB         | 18        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB         | 18        | 0.33%   |
| Samsung SSD 860 EVO 1TB                | 18        | 0.33%   |
| Unknown MMC Card  16GB                 | 17        | 0.31%   |
| Samsung SSD 860 EVO 250GB              | 17        | 0.31%   |
| Kingston SV300S37A120G 120GB SSD       | 17        | 0.31%   |
| WDC WD10JPVX-22JC3T0 1TB               | 16        | 0.29%   |
| Seagate ST9320325AS 320GB              | 16        | 0.29%   |
| Seagate ST500LT012-9WS142 500GB        | 16        | 0.29%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 16        | 0.29%   |
| Hitachi HDS721010CLA332 1TB            | 16        | 0.29%   |
| Crucial CT240BX500SSD1 240GB           | 16        | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB         | 15        | 0.27%   |
| Seagate ST31000524AS 1TB               | 15        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 912       | 1322   | 33.07%  |
| WDC                 | 761       | 1089   | 27.59%  |
| Toshiba             | 303       | 382    | 10.99%  |
| Hitachi             | 302       | 395    | 10.95%  |
| Samsung Electronics | 182       | 255    | 6.6%    |
| HGST                | 102       | 119    | 3.7%    |
| Fujitsu             | 64        | 81     | 2.32%   |
| Maxtor              | 57        | 82     | 2.07%   |
| Unknown             | 23        | 25     | 0.83%   |
| ASMT                | 12        | 18     | 0.44%   |
| IBM/Hitachi         | 7         | 7      | 0.25%   |
| Intenso             | 5         | 6      | 0.18%   |
| USB3.0              | 3         | 5      | 0.11%   |
| Apple               | 3         | 4      | 0.11%   |
| WD MediaMax         | 2         | 2      | 0.07%   |
| Inateck             | 2         | 2      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| Hewlett-Packard     | 2         | 2      | 0.07%   |
| ExcelStor           | 2         | 2      | 0.07%   |
| Apricorn            | 2         | 3      | 0.07%   |
| SAGE                | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 4      | 0.04%   |
| ICY BOX             | 1         | 1      | 0.04%   |
| HPE                 | 1         | 4      | 0.04%   |
| Ext Hard            | 1         | 1      | 0.04%   |
| CLOVER              | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |
| ACASIS              | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 343       | 459    | 23.14%  |
| Kingston            | 200       | 253    | 13.5%   |
| SanDisk             | 134       | 172    | 9.04%   |
| Crucial             | 123       | 167    | 8.3%    |
| WDC                 | 75        | 96     | 5.06%   |
| A-DATA Technology   | 55        | 73     | 3.71%   |
| China               | 51        | 61     | 3.44%   |
| Intel               | 49        | 73     | 3.31%   |
| PNY                 | 31        | 41     | 2.09%   |
| Patriot             | 30        | 35     | 2.02%   |
| Toshiba             | 27        | 33     | 1.82%   |
| Micron Technology   | 27        | 30     | 1.82%   |
| OCZ                 | 26        | 32     | 1.75%   |
| Transcend           | 24        | 24     | 1.62%   |
| SK hynix            | 21        | 21     | 1.42%   |
| Intenso             | 17        | 19     | 1.15%   |
| SPCC                | 16        | 23     | 1.08%   |
| LITEON              | 15        | 17     | 1.01%   |
| LITEONIT            | 14        | 17     | 0.94%   |
| Apacer              | 13        | 19     | 0.88%   |
| KingDian            | 11        | 17     | 0.74%   |
| Apple               | 10        | 14     | 0.67%   |
| Unknown             | 8         | 9      | 0.54%   |
| Lexar               | 8         | 8      | 0.54%   |
| Smartbuy            | 7         | 7      | 0.47%   |
| Plextor             | 7         | 8      | 0.47%   |
| KingSpec            | 6         | 8      | 0.4%    |
| GOODRAM             | 6         | 8      | 0.4%    |
| Corsair             | 6         | 6      | 0.4%    |
| TO Exter            | 5         | 6      | 0.34%   |
| Team                | 5         | 9      | 0.34%   |
| Mushkin             | 5         | 5      | 0.34%   |
| JMicron Technology  | 5         | 5      | 0.34%   |
| Hewlett-Packard     | 5         | 8      | 0.34%   |
| USB3.0              | 4         | 5      | 0.27%   |
| Pioneer             | 4         | 4      | 0.27%   |
| Netac               | 4         | 6      | 0.27%   |
| FORESEE             | 4         | 5      | 0.27%   |
| Drevo               | 4         | 4      | 0.27%   |
| Vaseky              | 3         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2325      | 3819   | 51.99%  |
| SSD     | 1332      | 1900   | 29.79%  |
| NVMe    | 521       | 674    | 11.65%  |
| MMC     | 221       | 284    | 4.94%   |
| Unknown | 73        | 94     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3139      | 5545   | 76.92%  |
| NVMe | 514       | 665    | 12.59%  |
| MMC  | 221       | 284    | 5.42%   |
| SAS  | 207       | 277    | 5.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2585      | 3896   | 67.67%  |
| 0.51-1.0   | 837       | 1175   | 21.91%  |
| 1.01-2.0   | 214       | 336    | 5.6%    |
| 3.01-4.0   | 70        | 119    | 1.83%   |
| 2.01-3.0   | 58        | 108    | 1.52%   |
| 4.01-10.0  | 50        | 78     | 1.31%   |
| 10.01-20.0 | 5         | 6      | 0.13%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1190      | 31.32%  |
| 251-500        | 849       | 22.35%  |
| 501-1000       | 482       | 12.69%  |
| 51-100         | 357       | 9.4%    |
| 21-50          | 257       | 6.76%   |
| 1001-2000      | 242       | 6.37%   |
| 1-20           | 173       | 4.55%   |
| More than 3000 | 137       | 3.61%   |
| 2001-3000      | 87        | 2.29%   |
| Unknown        | 25        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1638      | 41.49%  |
| 21-50          | 671       | 17%     |
| 101-250        | 492       | 12.46%  |
| 51-100         | 456       | 11.55%  |
| 251-500        | 274       | 6.94%   |
| 501-1000       | 196       | 4.96%   |
| 1001-2000      | 99        | 2.51%   |
| More than 3000 | 59        | 1.49%   |
| 2001-3000      | 38        | 0.96%   |
| Unknown        | 25        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 7      | 2.55%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 6      | 2.18%   |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.82%   |
| Seagate ST9500325AS 500GB           | 5         | 7      | 1.82%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 1.45%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 1.09%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 4      | 1.09%   |
| Samsung Electronics HM321HI 320GB   | 3         | 4      | 1.09%   |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 1.09%   |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 1.09%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 1.09%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 1.09%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.73%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.73%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.73%   |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.73%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.73%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.73%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.73%   |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.73%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.73%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.73%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.73%   |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.73%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.73%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.73%   |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.73%   |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.73%   |
| Samsung Electronics HD103SI 1TB     | 2         | 2      | 0.73%   |
| Samsung Electronics HD081GJ 80GB    | 2         | 2      | 0.73%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 0.73%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.73%   |
| KingDian S100 32GB SSD              | 2         | 4      | 0.73%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 3      | 0.73%   |
| Hitachi HTS725032A9A364 320GB       | 2         | 2      | 0.73%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 2      | 0.73%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 3      | 0.73%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 2      | 0.73%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 90     | 29.1%   |
| WDC                 | 56        | 64     | 20.9%   |
| Toshiba             | 26        | 32     | 9.7%    |
| Hitachi             | 26        | 33     | 9.7%    |
| Samsung Electronics | 19        | 26     | 7.09%   |
| HGST                | 9         | 10     | 3.36%   |
| Maxtor              | 6         | 6      | 2.24%   |
| Kingston            | 6         | 7      | 2.24%   |
| SK hynix            | 5         | 5      | 1.87%   |
| Intel               | 4         | 5      | 1.49%   |
| Fujitsu             | 4         | 5      | 1.49%   |
| Crucial             | 3         | 3      | 1.12%   |
| A-DATA Technology   | 3         | 4      | 1.12%   |
| SanDisk             | 2         | 2      | 0.75%   |
| OCZ                 | 2         | 2      | 0.75%   |
| Micron Technology   | 2         | 2      | 0.75%   |
| KingDian            | 2         | 4      | 0.75%   |
| Unknown             | 1         | 1      | 0.37%   |
| SSSTC               | 1         | 1      | 0.37%   |
| SPCC                | 1         | 1      | 0.37%   |
| Neo Forza           | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 1      | 0.37%   |
| LDLC                | 1         | 1      | 0.37%   |
| ICY BOX             | 1         | 1      | 0.37%   |
| FORESEE             | 1         | 1      | 0.37%   |
| Drevo               | 1         | 1      | 0.37%   |
| Corsair             | 1         | 1      | 0.37%   |
| China               | 1         | 1      | 0.37%   |
| Avant               | 1         | 1      | 0.37%   |
| ASMT                | 1         | 4      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |
| Apacer              | 1         | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 90     | 35.78%  |
| WDC                 | 53        | 61     | 24.31%  |
| Hitachi             | 26        | 33     | 11.93%  |
| Toshiba             | 25        | 31     | 11.47%  |
| Samsung Electronics | 15        | 21     | 6.88%   |
| HGST                | 9         | 10     | 4.13%   |
| Maxtor              | 6         | 6      | 2.75%   |
| Fujitsu             | 4         | 5      | 1.83%   |
| ICY BOX             | 1         | 1      | 0.46%   |
| ASMT                | 1         | 4      | 0.46%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 205       | 262    | 81.03%  |
| SSD  | 46        | 54     | 18.18%  |
| NVMe | 2         | 2      | 0.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1         | 1      | 25%     |
| Toshiba DT01ACA200 2TB           | 1         | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2595      | 4806   | 67.81%  |
| Works    | 981       | 1643   | 25.63%  |
| Malfunc  | 247       | 318    | 6.45%   |
| Failed   | 4         | 4      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2530      | 61.53%  |
| AMD                              | 631       | 15.35%  |
| Samsung Electronics              | 183       | 4.45%   |
| Nvidia                           | 139       | 3.38%   |
| SanDisk                          | 77        | 1.87%   |
| JMicron Technology               | 63        | 1.53%   |
| ASMedia Technology               | 61        | 1.48%   |
| VIA Technologies                 | 52        | 1.26%   |
| SK hynix                         | 47        | 1.14%   |
| Marvell Technology Group         | 45        | 1.09%   |
| Silicon Integrated Systems [SiS] | 38        | 0.92%   |
| Phison Electronics               | 29        | 0.71%   |
| Kingston Technology Company      | 27        | 0.66%   |
| Toshiba America Info Systems     | 25        | 0.61%   |
| KIOXIA                           | 19        | 0.46%   |
| Silicon Motion                   | 17        | 0.41%   |
| ADATA Technology                 | 15        | 0.36%   |
| LSI Logic / Symbios Logic        | 14        | 0.34%   |
| Micron/Crucial Technology        | 12        | 0.29%   |
| Micron Technology                | 11        | 0.27%   |
| Silicon Image                    | 9         | 0.22%   |
| Realtek Semiconductor            | 8         | 0.19%   |
| Broadcom / LSI                   | 8         | 0.19%   |
| Adaptec                          | 7         | 0.17%   |
| ULi Electronics                  | 6         | 0.15%   |
| Hewlett-Packard                  | 6         | 0.15%   |
| Apple                            | 5         | 0.12%   |
| Union Memory (Shenzhen)          | 4         | 0.1%    |
| Promise Technology               | 4         | 0.1%    |
| Integrated Technology Express    | 4         | 0.1%    |
| Seagate Technology               | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| Lite-On Technology               | 2         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 373       | 7.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 167       | 3.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 161       | 3.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 150       | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 134       | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 123       | 2.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 122       | 2.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 114       | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 109       | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 106       | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 102       | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 100       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 91        | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 90        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 86        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 74        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 64        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 63        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 60        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 60        | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 59        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 59        | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 58        | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 57        | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 56        | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 53        | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 52        | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 50        | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 48        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 42        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42        | 0.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 39        | 0.75%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 37        | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 37        | 0.71%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 37        | 0.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 36        | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 36        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 35        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2450      | 55.92%  |
| IDE  | 1156      | 26.39%  |
| NVMe | 509       | 11.62%  |
| RAID | 242       | 5.52%   |
| SAS  | 13        | 0.3%    |
| SCSI | 11        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2817      | 77.24%  |
| AMD          | 789       | 21.63%  |
| ARM          | 37        | 1.01%   |
| CentaurHauls | 4         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 31        | 0.85%   |
| ARM Processor                           | 29        | 0.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 26        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 25        | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 23        | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz             | 21        | 0.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 21        | 0.57%   |
| Intel Atom CPU N450 @ 1.66GHz           | 21        | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 19        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 19        | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 19        | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 19        | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 19        | 0.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 18        | 0.49%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 18        | 0.49%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 18        | 0.49%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.49%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 17        | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 17        | 0.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.46%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 17        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 16        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 0.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 16        | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 15        | 0.41%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 15        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 15        | 0.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 14        | 0.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 14        | 0.38%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 14        | 0.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 14        | 0.38%   |
| AMD Ryzen 5 3600 6-Core Processor       | 14        | 0.38%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 14        | 0.38%   |
| Intel Pentium M processor 1.73GHz       | 13        | 0.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 13        | 0.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 13        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 603       | 16.47%  |
| Intel Core i7           | 463       | 12.65%  |
| Intel Core 2 Duo        | 304       | 8.3%    |
| Intel Core i3           | 283       | 7.73%   |
| Intel Celeron           | 232       | 6.34%   |
| Intel Atom              | 173       | 4.73%   |
| Intel Pentium           | 116       | 3.17%   |
| Other                   | 111       | 3.03%   |
| AMD Ryzen 5             | 105       | 2.87%   |
| Intel Xeon              | 92        | 2.51%   |
| Intel Pentium Dual-Core | 83        | 2.27%   |
| AMD Ryzen 7             | 77        | 2.1%    |
| Intel Pentium Dual      | 62        | 1.69%   |
| Intel Pentium 4         | 62        | 1.69%   |
| Intel Genuine           | 57        | 1.56%   |
| Intel Core 2            | 51        | 1.39%   |
| Intel Core 2 Quad       | 50        | 1.37%   |
| AMD FX                  | 49        | 1.34%   |
| AMD A8                  | 44        | 1.2%    |
| AMD Athlon 64 X2        | 41        | 1.12%   |
| AMD E1                  | 31        | 0.85%   |
| AMD A6                  | 30        | 0.82%   |
| Intel Pentium M         | 27        | 0.74%   |
| AMD Athlon II X2        | 27        | 0.74%   |
| AMD Ryzen 9             | 26        | 0.71%   |
| AMD Ryzen 3             | 26        | 0.71%   |
| AMD Phenom II X4        | 26        | 0.71%   |
| Intel Celeron M         | 24        | 0.66%   |
| AMD A4                  | 22        | 0.6%    |
| AMD A10                 | 21        | 0.57%   |
| AMD Turion 64 X2 Mobile | 20        | 0.55%   |
| AMD Sempron             | 19        | 0.52%   |
| AMD E                   | 19        | 0.52%   |
| AMD Athlon              | 18        | 0.49%   |
| Intel Pentium D         | 17        | 0.46%   |
| AMD E2                  | 16        | 0.44%   |
| AMD Athlon 64           | 16        | 0.44%   |
| Intel Core i9           | 15        | 0.41%   |
| AMD Ryzen 7 PRO         | 14        | 0.38%   |
| Intel Pentium Silver    | 11        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1799      | 49.19%  |
| 4       | 1117      | 30.54%  |
| 1       | 335       | 9.16%   |
| 6       | 183       | 5%      |
| 8       | 140       | 3.83%   |
| 12      | 31        | 0.85%   |
| 16      | 17        | 0.46%   |
| 3       | 17        | 0.46%   |
| 10      | 6         | 0.16%   |
| Unknown | 4         | 0.11%   |
| 64      | 2         | 0.05%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |
| 14      | 2         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3603      | 98.79%  |
| 2       | 41        | 1.12%   |
| Unknown | 3         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1852      | 50.71%  |
| 2       | 1796      | 49.18%  |
| Unknown | 4         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3433      | 94.11%  |
| 32-bit         | 188       | 5.15%   |
| Unknown        | 26        | 0.71%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 613       | 16.38%  |
| 0x206a7    | 252       | 6.73%   |
| 0x306a9    | 230       | 6.14%   |
| 0x1067a    | 229       | 6.12%   |
| 0x306c3    | 145       | 3.87%   |
| 0x6fd      | 139       | 3.71%   |
| 0x20655    | 83        | 2.22%   |
| 0x10676    | 79        | 2.11%   |
| 0x40651    | 64        | 1.71%   |
| 0x30678    | 60        | 1.6%    |
| 0x506e3    | 59        | 1.58%   |
| 0x906ea    | 57        | 1.52%   |
| 0x406c4    | 54        | 1.44%   |
| 0x106ca    | 51        | 1.36%   |
| 0x6fb      | 50        | 1.34%   |
| 0x406e3    | 49        | 1.31%   |
| 0x010000c8 | 49        | 1.31%   |
| 0x806ea    | 46        | 1.23%   |
| 0x6f6      | 46        | 1.23%   |
| 0x106c2    | 45        | 1.2%    |
| 0x20652    | 44        | 1.18%   |
| 0x806ec    | 41        | 1.1%    |
| 0x306d4    | 40        | 1.07%   |
| 0x806e9    | 39        | 1.04%   |
| 0x906e9    | 38        | 1.02%   |
| 0x806c1    | 37        | 0.99%   |
| 0x06000852 | 36        | 0.96%   |
| 0x6e8      | 35        | 0.94%   |
| 0x6d8      | 33        | 0.88%   |
| 0x08108109 | 33        | 0.88%   |
| 0x406c3    | 31        | 0.83%   |
| 0x05000119 | 31        | 0.83%   |
| 0x106e5    | 30        | 0.8%    |
| 0x08701021 | 30        | 0.8%    |
| 0x0800820d | 30        | 0.8%    |
| 0x07030105 | 28        | 0.75%   |
| 0x0700010f | 26        | 0.69%   |
| 0x06001119 | 25        | 0.67%   |
| 0x03000027 | 24        | 0.64%   |
| 0xa0652    | 23        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 343       | 9.38%   |
| KabyLake         | 310       | 8.48%   |
| SandyBridge      | 291       | 7.96%   |
| Core             | 287       | 7.85%   |
| IvyBridge        | 269       | 7.36%   |
| Haswell          | 248       | 6.78%   |
| Silvermont       | 165       | 4.51%   |
| Westmere         | 161       | 4.4%    |
| Skylake          | 133       | 3.64%   |
| K8 Hammer        | 125       | 3.42%   |
| Bonnell          | 122       | 3.34%   |
| K10              | 107       | 2.93%   |
| P6               | 97        | 2.65%   |
| Zen 2            | 93        | 2.54%   |
| Zen+             | 88        | 2.41%   |
| NetBurst         | 88        | 2.41%   |
| Piledriver       | 69        | 1.89%   |
| Unknown          | 62        | 1.7%    |
| CometLake        | 52        | 1.42%   |
| Broadwell        | 52        | 1.42%   |
| Zen              | 51        | 1.39%   |
| TigerLake        | 48        | 1.31%   |
| Nehalem          | 47        | 1.29%   |
| Bobcat           | 46        | 1.26%   |
| Puma             | 37        | 1.01%   |
| Goldmont plus    | 35        | 0.96%   |
| Zen 3            | 34        | 0.93%   |
| Excavator        | 34        | 0.93%   |
| Jaguar           | 30        | 0.82%   |
| Goldmont         | 30        | 0.82%   |
| IceLake          | 29        | 0.79%   |
| K10 Llano        | 26        | 0.71%   |
| Steamroller      | 13        | 0.36%   |
| K8 & K10 hybrid  | 11        | 0.3%    |
| Bulldozer        | 10        | 0.27%   |
| K6               | 6         | 0.16%   |
| Alderlake Hybrid | 5         | 0.14%   |
| Tremont          | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2033      | 50.27%  |
| Nvidia                           | 1039      | 25.69%  |
| AMD                              | 900       | 22.26%  |
| Silicon Integrated Systems [SiS] | 24        | 0.59%   |
| Matrox Electronics Systems       | 21        | 0.52%   |
| VIA Technologies                 | 18        | 0.45%   |
| ASPEED Technology                | 7         | 0.17%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 213       | 4.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 139       | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 115       | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 99        | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 91        | 2.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 85        | 1.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 78        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 78        | 1.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 73        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 68        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 67        | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59        | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 55        | 1.28%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 55        | 1.28%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 53        | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 51        | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 1.16%   |
| Intel HD Graphics 620                                                                    | 45        | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 1.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 44        | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44        | 1.02%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 42        | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.93%   |
| Intel HD Graphics 5500                                                                   | 36        | 0.84%   |
| AMD Renoir                                                                               | 36        | 0.84%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.79%   |
| Intel HD Graphics 530                                                                    | 34        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 33        | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.63%   |
| Intel HD Graphics 630                                                                    | 26        | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 26        | 0.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 0.6%    |
| Intel HD Graphics 500                                                                    | 24        | 0.56%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 24        | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 23        | 0.53%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 22        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 1657      | 45.16%  |
| 1 x Nvidia                           | 735       | 20.03%  |
| 1 x AMD                              | 725       | 19.76%  |
| Intel + Nvidia                       | 259       | 7.06%   |
| Intel + AMD                          | 79        | 2.15%   |
| 2 x AMD                              | 63        | 1.72%   |
| Other                                | 44        | 1.2%    |
| AMD + Nvidia                         | 25        | 0.68%   |
| 1 x SiS                              | 24        | 0.65%   |
| 1 x VIA                              | 18        | 0.49%   |
| 1 x Matrox                           | 15        | 0.41%   |
| 2 x Nvidia                           | 5         | 0.14%   |
| Nvidia + ASPEED                      | 5         | 0.14%   |
| Nvidia + Matrox                      | 3         | 0.08%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.03%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.03%   |
| 2 x Intel                            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia                 | 1         | 0.03%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.03%   |
| 1 x S3 Graphics                      | 1         | 0.03%   |
| Intel + 2 x AMD                      | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2938      | 79.97%  |
| Proprietary | 558       | 15.19%  |
| Unknown     | 178       | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1840      | 49.42%  |
| 0.01-0.5   | 764       | 20.52%  |
| 1.01-2.0   | 434       | 11.66%  |
| 0.51-1.0   | 343       | 9.21%   |
| 3.01-4.0   | 188       | 5.05%   |
| 7.01-8.0   | 71        | 1.91%   |
| 5.01-6.0   | 46        | 1.24%   |
| 8.01-16.0  | 18        | 0.48%   |
| 2.01-3.0   | 14        | 0.38%   |
| 4.01-5.0   | 2         | 0.05%   |
| 16.01-24.0 | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 557       | 14.86%  |
| AU Optronics            | 409       | 10.91%  |
| LG Display              | 323       | 8.62%   |
| Chimei Innolux          | 212       | 5.66%   |
| Dell                    | 202       | 5.39%   |
| BOE                     | 187       | 4.99%   |
| Goldstar                | 183       | 4.88%   |
| Hewlett-Packard         | 142       | 3.79%   |
| Acer                    | 136       | 3.63%   |
| Philips                 | 98        | 2.61%   |
| Chi Mei Optoelectronics | 98        | 2.61%   |
| AOC                     | 92        | 2.45%   |
| Lenovo                  | 91        | 2.43%   |
| Ancor Communications    | 72        | 1.92%   |
| BenQ                    | 68        | 1.81%   |
| LG Philips              | 66        | 1.76%   |
| Apple                   | 52        | 1.39%   |
| HannStar                | 49        | 1.31%   |
| ViewSonic               | 48        | 1.28%   |
| Iiyama                  | 39        | 1.04%   |
| Unknown                 | 37        | 0.99%   |
| Sony                    | 35        | 0.93%   |
| LG Electronics          | 34        | 0.91%   |
| InfoVision              | 31        | 0.83%   |
| Sharp                   | 29        | 0.77%   |
| Fujitsu Siemens         | 25        | 0.67%   |
| CPT                     | 23        | 0.61%   |
| Panasonic               | 22        | 0.59%   |
| NEC Computers           | 21        | 0.56%   |
| Toshiba                 | 17        | 0.45%   |
| PANDA                   | 17        | 0.45%   |
| Eizo                    | 16        | 0.43%   |
| Medion                  | 14        | 0.37%   |
| ASUSTek Computer        | 14        | 0.37%   |
| Vizio                   | 12        | 0.32%   |
| Quanta Display          | 10        | 0.27%   |
| Vestel Elektronik       | 9         | 0.24%   |
| Lenovo Group Limited    | 8         | 0.21%   |
| DENON                   | 8         | 0.21%   |
| Seiko/Epson             | 7         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.57%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 20        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.41%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 15        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.34%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 10        | 0.26%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.26%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 9         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.23%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 9         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.21%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 8         | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.18%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.18%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.18%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 7         | 0.18%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 6         | 0.16%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 6         | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1224      | 33.5%   |
| 1366x768 (WXGA)    | 815       | 22.3%   |
| 1280x800 (WXGA)    | 238       | 6.51%   |
| 1280x1024 (SXGA)   | 214       | 5.86%   |
| 1600x900 (HD+)     | 179       | 4.9%    |
| 1440x900 (WXGA+)   | 172       | 4.71%   |
| 1680x1050 (WSXGA+) | 143       | 3.91%   |
| 3840x2160 (4K)     | 135       | 3.69%   |
| 1920x1200 (WUXGA)  | 79        | 2.16%   |
| 2560x1440 (QHD)    | 74        | 2.03%   |
| 1024x600           | 66        | 1.81%   |
| Unknown            | 58        | 1.59%   |
| 1024x768 (XGA)     | 42        | 1.15%   |
| 1360x768           | 41        | 1.12%   |
| 3840x1080          | 22        | 0.6%    |
| 1920x540           | 14        | 0.38%   |
| 1600x1200          | 13        | 0.36%   |
| 2560x1080          | 12        | 0.33%   |
| 2560x1600          | 11        | 0.3%    |
| 3440x1440          | 9         | 0.25%   |
| 1280x720 (HD)      | 9         | 0.25%   |
| 2288x1287          | 7         | 0.19%   |
| 3200x1080          | 6         | 0.16%   |
| 1400x1050          | 5         | 0.14%   |
| 5120x1440          | 4         | 0.11%   |
| 3840x1200          | 4         | 0.11%   |
| 3200x1800 (QHD+)   | 4         | 0.11%   |
| 2880x1800          | 4         | 0.11%   |
| 2160x1440          | 3         | 0.08%   |
| 2048x1152          | 3         | 0.08%   |
| 4480x1440          | 2         | 0.05%   |
| 3840x2400          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3200x900           | 2         | 0.05%   |
| 2960x1050          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 800x600            | 1         | 0.03%   |
| 800x480            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 917       | 24.59%  |
| 14      | 282       | 7.56%   |
| Unknown | 282       | 7.56%   |
| 17      | 279       | 7.48%   |
| 13      | 247       | 6.62%   |
| 23      | 221       | 5.93%   |
| 24      | 198       | 5.31%   |
| 21      | 195       | 5.23%   |
| 19      | 182       | 4.88%   |
| 27      | 150       | 4.02%   |
| 18      | 116       | 3.11%   |
| 20      | 91        | 2.44%   |
| 22      | 79        | 2.12%   |
| 10      | 74        | 1.98%   |
| 12      | 69        | 1.85%   |
| 31      | 67        | 1.8%    |
| 11      | 62        | 1.66%   |
| 84      | 28        | 0.75%   |
| 72      | 21        | 0.56%   |
| 54      | 20        | 0.54%   |
| 26      | 17        | 0.46%   |
| 40      | 14        | 0.38%   |
| 32      | 14        | 0.38%   |
| 25      | 13        | 0.35%   |
| 16      | 13        | 0.35%   |
| 34      | 12        | 0.32%   |
| 52      | 8         | 0.21%   |
| 48      | 8         | 0.21%   |
| 28      | 8         | 0.21%   |
| 37      | 6         | 0.16%   |
| 8       | 4         | 0.11%   |
| 49      | 3         | 0.08%   |
| 47      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 74      | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 60      | 2         | 0.05%   |
| 57      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1406      | 38.17%  |
| 501-600        | 549       | 14.9%   |
| 401-500        | 544       | 14.77%  |
| 201-300        | 332       | 9.01%   |
| 351-400        | 311       | 8.44%   |
| Unknown        | 282       | 7.65%   |
| 601-700        | 99        | 2.69%   |
| 1501-2000      | 52        | 1.41%   |
| 1001-1500      | 50        | 1.36%   |
| 701-800        | 27        | 0.73%   |
| 801-900        | 23        | 0.62%   |
| 101-200        | 5         | 0.14%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2272      | 65.51%  |
| 16/10   | 602       | 17.36%  |
| Unknown | 257       | 7.41%   |
| 5/4     | 205       | 5.91%   |
| 4/3     | 73        | 2.1%    |
| 3/2     | 22        | 0.63%   |
| 21/9    | 17        | 0.49%   |
| 6/5     | 9         | 0.26%   |
| 32/9    | 4         | 0.12%   |
| 1.00    | 4         | 0.12%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 915       | 24.67%  |
| 201-250        | 563       | 15.18%  |
| 81-90          | 421       | 11.35%  |
| 151-200        | 353       | 9.52%   |
| Unknown        | 282       | 7.6%    |
| 141-150        | 193       | 5.2%    |
| 301-350        | 159       | 4.29%   |
| 121-130        | 129       | 3.48%   |
| 351-500        | 101       | 2.72%   |
| More than 1000 | 96        | 2.59%   |
| 71-80          | 92        | 2.48%   |
| 251-300        | 90        | 2.43%   |
| 41-50          | 73        | 1.97%   |
| 61-70          | 64        | 1.73%   |
| 51-60          | 63        | 1.7%    |
| 131-140        | 45        | 1.21%   |
| 501-1000       | 33        | 0.89%   |
| 91-100         | 22        | 0.59%   |
| 111-120        | 10        | 0.27%   |
| 1-40           | 5         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1407      | 39.17%  |
| 101-120       | 1033      | 28.76%  |
| 121-160       | 667       | 18.57%  |
| Unknown       | 282       | 7.85%   |
| 161-240       | 89        | 2.48%   |
| 1-50          | 85        | 2.37%   |
| More than 240 | 29        | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3070      | 82.75%  |
| 2     | 439       | 11.83%  |
| 0     | 166       | 4.47%   |
| 3     | 31        | 0.84%   |
| 4     | 4         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1874      | 33.38%  |
| Intel                             | 1484      | 26.43%  |
| Qualcomm Atheros                  | 723       | 12.88%  |
| Broadcom                          | 419       | 7.46%   |
| Marvell Technology Group          | 132       | 2.35%   |
| Nvidia                            | 114       | 2.03%   |
| Broadcom Limited                  | 114       | 2.03%   |
| Ralink Technology                 | 87        | 1.55%   |
| Ralink                            | 79        | 1.41%   |
| TP-Link                           | 62        | 1.1%    |
| VIA Technologies                  | 39        | 0.69%   |
| Qualcomm Atheros Communications   | 35        | 0.62%   |
| Silicon Integrated Systems [SiS]  | 32        | 0.57%   |
| Samsung Electronics               | 30        | 0.53%   |
| Huawei Technologies               | 28        | 0.5%    |
| D-Link System                     | 26        | 0.46%   |
| MediaTek                          | 25        | 0.45%   |
| NetGear                           | 22        | 0.39%   |
| JMicron Technology                | 21        | 0.37%   |
| Sierra Wireless                   | 16        | 0.29%   |
| D-Link                            | 16        | 0.29%   |
| Ericsson Business Mobile Networks | 15        | 0.27%   |
| Attansic Technology               | 14        | 0.25%   |
| ASUSTek Computer                  | 11        | 0.2%    |
| ASIX Electronics                  | 11        | 0.2%    |
| Xiaomi                            | 10        | 0.18%   |
| Edimax Technology                 | 10        | 0.18%   |
| Lenovo                            | 9         | 0.16%   |
| DisplayLink                       | 9         | 0.16%   |
| Aquantia                          | 9         | 0.16%   |
| Dell                              | 8         | 0.14%   |
| AMD                               | 8         | 0.14%   |
| Belkin Components                 | 7         | 0.12%   |
| Qualcomm                          | 6         | 0.11%   |
| Microsoft                         | 6         | 0.11%   |
| Fibocom                           | 6         | 0.11%   |
| ULi Electronics                   | 5         | 0.09%   |
| Sitecom Europe                    | 5         | 0.09%   |
| Linksys                           | 5         | 0.09%   |
| HTC (High Tech Computer)          | 5         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1180      | 18.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 321       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 163       | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 108       | 1.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 90        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 89        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 88        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 84        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                     | 84        | 1.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 1.06%   |
| Intel Wireless 7260                                                     | 65        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 58        | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 56        | 0.86%   |
| Intel Wireless 8265 / 8275                                              | 56        | 0.86%   |
| Intel Ethernet Connection I217-LM                                       | 54        | 0.83%   |
| Intel Wireless 7265                                                     | 53        | 0.81%   |
| Nvidia MCP61 Ethernet                                                   | 52        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 0.78%   |
| Intel I211 Gigabit Network Connection                                   | 46        | 0.71%   |
| Intel Wireless 3165                                                     | 45        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 40        | 0.61%   |
| Intel Wireless 8260                                                     | 38        | 0.58%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 37        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                 | 37        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 33        | 0.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 32        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                         | 31        | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 30        | 0.46%   |
| Intel Ethernet Connection (2) I219-V                                    | 30        | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                       | 28        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1002      | 35.63%  |
| Qualcomm Atheros                      | 585       | 20.8%   |
| Realtek Semiconductor                 | 480       | 17.07%  |
| Broadcom                              | 253       | 9%      |
| Ralink Technology                     | 87        | 3.09%   |
| Ralink                                | 79        | 2.81%   |
| TP-Link                               | 58        | 2.06%   |
| Broadcom Limited                      | 55        | 1.96%   |
| Qualcomm Atheros Communications       | 35        | 1.24%   |
| NetGear                               | 22        | 0.78%   |
| D-Link System                         | 18        | 0.64%   |
| Sierra Wireless                       | 16        | 0.57%   |
| MediaTek                              | 16        | 0.57%   |
| D-Link                                | 15        | 0.53%   |
| Edimax Technology                     | 10        | 0.36%   |
| ASUSTek Computer                      | 10        | 0.36%   |
| Belkin Components                     | 7         | 0.25%   |
| Microsoft                             | 6         | 0.21%   |
| Fibocom                               | 6         | 0.21%   |
| Sitecom Europe                        | 5         | 0.18%   |
| Linksys                               | 5         | 0.18%   |
| Dell                                  | 5         | 0.18%   |
| ZyDAS                                 | 4         | 0.14%   |
| IMC Networks                          | 4         | 0.14%   |
| Hewlett-Packard                       | 4         | 0.14%   |
| AVM                                   | 4         | 0.14%   |
| TRENDnet                              | 3         | 0.11%   |
| Qualcomm                              | 3         | 0.11%   |
| Marvell Technology Group              | 3         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Xiaomi                                | 1         | 0.04%   |
| Winbond Electronics                   | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |
| AboCom Systems                        | 1         | 0.04%   |
| 3Com                                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 108       | 3.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 90        | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 89        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 88        | 3.1%    |
| Intel Wi-Fi 6 AX200                                                     | 84        | 2.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 2.43%   |
| Intel Wireless 7260                                                     | 65        | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 58        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 56        | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 56        | 1.97%   |
| Intel Wireless 7265                                                     | 53        | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 1.79%   |
| Intel Wireless 3165                                                     | 45        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 1.51%   |
| Intel Wireless 8260                                                     | 38        | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 1.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 37        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 33        | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 1.13%   |
| Qualcomm Atheros AR9271 802.11n                                         | 31        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 1.06%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 27        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 27        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 27        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 26        | 0.91%   |
| Intel Wireless-AC 9260                                                  | 25        | 0.88%   |
| Intel Wireless 3160                                                     | 25        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 24        | 0.84%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 24        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 21        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1669      | 47.51%  |
| Intel                            | 854       | 24.31%  |
| Qualcomm Atheros                 | 225       | 6.4%    |
| Broadcom                         | 206       | 5.86%   |
| Marvell Technology Group         | 129       | 3.67%   |
| Nvidia                           | 113       | 3.22%   |
| Broadcom Limited                 | 60        | 1.71%   |
| VIA Technologies                 | 39        | 1.11%   |
| Silicon Integrated Systems [SiS] | 30        | 0.85%   |
| Samsung Electronics              | 29        | 0.83%   |
| JMicron Technology               | 21        | 0.6%    |
| Huawei Technologies              | 18        | 0.51%   |
| Attansic Technology              | 14        | 0.4%    |
| ASIX Electronics                 | 11        | 0.31%   |
| MediaTek                         | 10        | 0.28%   |
| Xiaomi                           | 9         | 0.26%   |
| Lenovo                           | 9         | 0.26%   |
| DisplayLink                      | 9         | 0.26%   |
| Aquantia                         | 9         | 0.26%   |
| D-Link System                    | 8         | 0.23%   |
| TP-Link                          | 4         | 0.11%   |
| LG Electronics                   | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.09%   |
| Qualcomm                         | 3         | 0.09%   |
| IBM                              | 3         | 0.09%   |
| Apple                            | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| National Semiconductor           | 2         | 0.06%   |
| Motorola PCS                     | 2         | 0.06%   |
| Insyde Software                  | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| Hangzhou Silan Microelectronics  | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1180      | 33.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 321       | 9.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 163       | 4.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 84        | 2.36%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 1.52%   |
| Nvidia MCP61 Ethernet                                             | 52        | 1.46%   |
| Intel I211 Gigabit Network Connection                             | 46        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 1.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 32        | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 30        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27        | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 25        | 0.7%    |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 23        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 19        | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 18        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17        | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.48%   |
| Intel 82573L Gigabit Ethernet Controller                          | 17        | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 17        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.45%   |
| Intel PRO/100 VE Network Connection                               | 16        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 15        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 15        | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 15        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3318      | 54.76%  |
| WiFi     | 2634      | 43.47%  |
| Modem    | 101       | 1.67%   |
| Unknown  | 6         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2084      | 55.4%   |
| Ethernet | 1675      | 44.52%  |
| Modem    | 2         | 0.05%   |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2052      | 56.02%  |
| 1     | 1431      | 39.07%  |
| 0     | 103       | 2.81%   |
| 3     | 55        | 1.5%    |
| 4     | 17        | 0.46%   |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.03%   |
| 8     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3180      | 85.95%  |
| Yes  | 520       | 14.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 604       | 37.68%  |
| Broadcom                        | 164       | 10.23%  |
| Qualcomm Atheros Communications | 151       | 9.42%   |
| Realtek Semiconductor           | 141       | 8.8%    |
| Cambridge Silicon Radio         | 109       | 6.8%    |
| Apple                           | 58        | 3.62%   |
| Lite-On Technology              | 56        | 3.49%   |
| Dell                            | 52        | 3.24%   |
| IMC Networks                    | 50        | 3.12%   |
| Foxconn / Hon Hai               | 50        | 3.12%   |
| Hewlett-Packard                 | 47        | 2.93%   |
| ASUSTek Computer                | 25        | 1.56%   |
| Toshiba                         | 19        | 1.19%   |
| Ralink                          | 16        | 1%      |
| Alps Electric                   | 13        | 0.81%   |
| Integrated System Solution      | 7         | 0.44%   |
| Realtek                         | 6         | 0.37%   |
| Ralink Technology               | 6         | 0.37%   |
| Foxconn International           | 5         | 0.31%   |
| MediaTek                        | 4         | 0.25%   |
| Chicony Electronics             | 4         | 0.25%   |
| Edimax Technology               | 3         | 0.19%   |
| Qcom                            | 2         | 0.12%   |
| Fujitsu                         | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Syntek                          | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Conwise Technology              | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 268       | 16.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 109       | 6.8%    |
| Intel AX201 Bluetooth                                                               | 84        | 5.24%   |
| Intel AX200 Bluetooth                                                               | 84        | 5.24%   |
| Realtek Bluetooth Radio                                                             | 82        | 5.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 4.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 62        | 3.87%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 39        | 2.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 33        | 2.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 30        | 1.87%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 28        | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 26        | 1.62%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 22        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 22        | 1.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 19        | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 19        | 1.18%   |
| Apple Bluetooth HCI                                                                 | 19        | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 1.06%   |
| Lite-On Bluetooth Device                                                            | 17        | 1.06%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 16        | 1%      |
| IMC Networks Bluetooth Device                                                       | 16        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 0.94%   |
| Apple Bluetooth Host Controller                                                     | 15        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 14        | 0.87%   |
| Broadcom BCM2045 Bluetooth                                                          | 14        | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 14        | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.81%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 12        | 0.75%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 0.75%   |
| Intel AX210 Bluetooth                                                               | 11        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.69%   |
| Toshiba Integrated Bluetooth HCI                                                    | 10        | 0.62%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 10        | 0.62%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.62%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2603      | 55.15%  |
| AMD                                  | 864       | 18.31%  |
| Nvidia                               | 748       | 15.85%  |
| C-Media Electronics                  | 69        | 1.46%   |
| Creative Labs                        | 51        | 1.08%   |
| VIA Technologies                     | 46        | 0.97%   |
| Silicon Integrated Systems [SiS]     | 38        | 0.81%   |
| Logitech                             | 27        | 0.57%   |
| Texas Instruments                    | 25        | 0.53%   |
| GN Netcom                            | 15        | 0.32%   |
| M-Audio                              | 12        | 0.25%   |
| Focusrite-Novation                   | 12        | 0.25%   |
| Plantronics                          | 10        | 0.21%   |
| JMTek                                | 10        | 0.21%   |
| Generalplus Technology               | 10        | 0.21%   |
| Yamaha                               | 9         | 0.19%   |
| Lenovo                               | 9         | 0.19%   |
| Creative Technology                  | 9         | 0.19%   |
| Sennheiser Communications            | 7         | 0.15%   |
| Realtek Semiconductor                | 7         | 0.15%   |
| ULi Electronics                      | 6         | 0.13%   |
| BEHRINGER International              | 6         | 0.13%   |
| ASUSTek Computer                     | 5         | 0.11%   |
| SAVITECH                             | 4         | 0.08%   |
| Ensoniq                              | 4         | 0.08%   |
| AKAI Professional M.I.               | 4         | 0.08%   |
| Xilinx                               | 3         | 0.06%   |
| Tenx Technology                      | 3         | 0.06%   |
| TEAC                                 | 3         | 0.06%   |
| Roland                               | 3         | 0.06%   |
| Kingston Technology                  | 3         | 0.06%   |
| Elite Silicon                        | 3         | 0.06%   |
| EGO SYStems                          | 3         | 0.06%   |
| DigiTech                             | 3         | 0.06%   |
| Digidesign                           | 3         | 0.06%   |
| Corsair                              | 3         | 0.06%   |
| ZOOM                                 | 2         | 0.04%   |
| XMOS                                 | 2         | 0.04%   |
| Unknown                              | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 323       | 5.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 266       | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 257       | 4.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 202       | 3.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 175       | 3.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 175       | 3.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 168       | 3.09%   |
| AMD FCH Azalia Controller                                                                         | 157       | 2.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 147       | 2.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 143       | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 141       | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 112       | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 77        | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 77        | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 74        | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 71        | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 69        | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 69        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 68        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 67        | 1.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 64        | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 63        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 63        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 61        | 1.12%   |
| Nvidia MCP61 High Definition Audio                                                                | 56        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 55        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 53        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 49        | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 48        | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 47        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 46        | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 46        | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 43        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 40        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 39        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 36        | 0.66%   |
| AMD Wrestler HDMI Audio                                                                           | 36        | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 35        | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 35        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 373       | 21.05%  |
| SK hynix                                         | 306       | 17.27%  |
| Unknown                                          | 289       | 16.31%  |
| Kingston                                         | 193       | 10.89%  |
| Micron Technology                                | 141       | 7.96%   |
| Crucial                                          | 101       | 5.7%    |
| Corsair                                          | 68        | 3.84%   |
| G.Skill                                          | 48        | 2.71%   |
| Elpida                                           | 41        | 2.31%   |
| Nanya Technology                                 | 27        | 1.52%   |
| Ramaxel Technology                               | 26        | 1.47%   |
| A-DATA Technology                                | 25        | 1.41%   |
| Unknown (ABCD)                                   | 19        | 1.07%   |
| Smart                                            | 12        | 0.68%   |
| Transcend                                        | 11        | 0.62%   |
| Team                                             | 10        | 0.56%   |
| Goodram                                          | 9         | 0.51%   |
| Apacer                                           | 5         | 0.28%   |
| Unknown                                          | 5         | 0.28%   |
| Patriot                                          | 4         | 0.23%   |
| Avant                                            | 4         | 0.23%   |
| Unifosa                                          | 3         | 0.17%   |
| 48spaces                                         | 3         | 0.17%   |
| Teikon                                           | 2         | 0.11%   |
| Super Talent                                     | 2         | 0.11%   |
| Qimonda                                          | 2         | 0.11%   |
| PNY                                              | 2         | 0.11%   |
| Neo Forza                                        | 2         | 0.11%   |
| High Bridge                                      | 2         | 0.11%   |
| GeIL                                             | 2         | 0.11%   |
| ASint Technology                                 | 2         | 0.11%   |
| Walton Chaintech                                 | 1         | 0.06%   |
| V-GeN                                            | 1         | 0.06%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.06%   |
| Unknown (0x7FA8000000000000)                     | 1         | 0.06%   |
| Unknown (0x7F7FB5FFFFFFFFFF)                     | 1         | 0.06%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.06%   |
| Unknown (0x0043415455000000)                     | 1         | 0.06%   |
| Toshiba                                          | 1         | 0.06%   |
| Timetec                                          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.79%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 15        | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 11        | 0.58%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 11        | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 11        | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 7         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 7         | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.37%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.37%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.31%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 6         | 0.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.31%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 6         | 0.31%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 616       | 39.64%  |
| DDR4    | 542       | 34.88%  |
| DDR2    | 160       | 10.3%   |
| SDRAM   | 73        | 4.7%    |
| Unknown | 52        | 3.35%   |
| LPDDR4  | 51        | 3.28%   |
| LPDDR3  | 27        | 1.74%   |
| DDR     | 24        | 1.54%   |
| DRAM    | 7         | 0.45%   |
| EEPROM  | 1         | 0.06%   |
| DDR5    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 899       | 58.99%  |
| DIMM         | 551       | 36.15%  |
| Row Of Chips | 56        | 3.67%   |
| Chip         | 10        | 0.66%   |
| Unknown      | 5         | 0.33%   |
| FB-DIMM      | 3         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 514       | 30.69%  |
| 8192    | 469       | 28%     |
| 2048    | 354       | 21.13%  |
| 16384   | 182       | 10.87%  |
| 1024    | 108       | 6.45%   |
| 32768   | 29        | 1.73%   |
| 512     | 13        | 0.78%   |
| 1536    | 2         | 0.12%   |
| 65536   | 1         | 0.06%   |
| 256     | 1         | 0.06%   |
| 1       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 376       | 22.86%  |
| 2667    | 227       | 13.8%   |
| 3200    | 138       | 8.39%   |
| 1333    | 128       | 7.78%   |
| 2400    | 108       | 6.57%   |
| 667     | 88        | 5.35%   |
| 800     | 71        | 4.32%   |
| Unknown | 69        | 4.19%   |
| 2133    | 61        | 3.71%   |
| 1334    | 61        | 3.71%   |
| 1066    | 31        | 1.88%   |
| 3600    | 28        | 1.7%    |
| 1867    | 25        | 1.52%   |
| 1067    | 25        | 1.52%   |
| 4199    | 17        | 1.03%   |
| 1866    | 16        | 0.97%   |
| 3266    | 15        | 0.91%   |
| 533     | 15        | 0.91%   |
| 4267    | 13        | 0.79%   |
| 3000    | 13        | 0.79%   |
| 2666    | 13        | 0.79%   |
| 2048    | 12        | 0.73%   |
| 1800    | 11        | 0.67%   |
| 975     | 8         | 0.49%   |
| 400     | 7         | 0.43%   |
| 3400    | 5         | 0.3%    |
| 49926   | 4         | 0.24%   |
| 3800    | 4         | 0.24%   |
| 3733    | 4         | 0.24%   |
| 2733    | 4         | 0.24%   |
| 2200    | 4         | 0.24%   |
| 2000    | 4         | 0.24%   |
| 333     | 4         | 0.24%   |
| 4266    | 3         | 0.18%   |
| 2800    | 3         | 0.18%   |
| 2448    | 3         | 0.18%   |
| 4800    | 2         | 0.12%   |
| 2187    | 2         | 0.12%   |
| 2134    | 2         | 0.12%   |
| 1648    | 2         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 49        | 39.84%  |
| Brother Industries    | 24        | 19.51%  |
| Canon                 | 21        | 17.07%  |
| Samsung Electronics   | 10        | 8.13%   |
| Seiko Epson           | 5         | 4.07%   |
| Zebra                 | 4         | 3.25%   |
| QinHeng Electronics   | 2         | 1.63%   |
| Prolific Technology   | 2         | 1.63%   |
| STMicroelectronics    | 1         | 0.81%   |
| Pantum                | 1         | 0.81%   |
| Minolta               | 1         | 0.81%   |
| Lexmark International | 1         | 0.81%   |
| Kyocera               | 1         | 0.81%   |
| Dymo-CoStar           | 1         | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 3.23%   |
| HP LaserJet 400 M401dne                                               | 4         | 3.23%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.42%   |
| Brother HL-5370DW series                                              | 3         | 2.42%   |
| Seiko Epson L222 Series                                               | 2         | 1.61%   |
| QinHeng CH340S                                                        | 2         | 1.61%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.61%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.61%   |
| HP LaserJet P1006                                                     | 2         | 1.61%   |
| HP LaserJet 1320                                                      | 2         | 1.61%   |
| HP LaserJet 1020                                                      | 2         | 1.61%   |
| HP ENVY 4520 series                                                   | 2         | 1.61%   |
| HP DeskJet 3700 series                                                | 2         | 1.61%   |
| HP Deskjet 3050A                                                      | 2         | 1.61%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.61%   |
| Canon LBP6000                                                         | 2         | 1.61%   |
| Brother HL-L2320D series                                              | 2         | 1.61%   |
| Brother HL-5340 series                                                | 2         | 1.61%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.61%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.81%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.81%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.81%   |
| Seiko Epson L3160 Series                                              | 1         | 0.81%   |
| Seiko Epson ET-2600 Series                                            | 1         | 0.81%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.81%   |
| Samsung SF-760 Series                                                 | 1         | 0.81%   |
| Samsung SCX-4200 series                                               | 1         | 0.81%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.81%   |
| Samsung SCX-3400 Series                                               | 1         | 0.81%   |
| Samsung ML-2525W Series                                               | 1         | 0.81%   |
| Samsung ML-1740 Printer                                               | 1         | 0.81%   |
| Samsung M2070 Series                                                  | 1         | 0.81%   |
| Samsung M2020 Series                                                  | 1         | 0.81%   |
| Samsung C48x Series                                                   | 1         | 0.81%   |
| Pantum P2000                                                          | 1         | 0.81%   |
| Minolta PagePro 1300W                                                 | 1         | 0.81%   |
| Lexmark International E360d                                           | 1         | 0.81%   |
| Kyocera Mita FS-920                                                   | 1         | 0.81%   |
| HP PSC 750xi                                                          | 1         | 0.81%   |
| HP OfficeJet Reflash                                                  | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 21        | 67.74%  |
| Seiko Epson     | 5         | 16.13%  |
| Hewlett-Packard | 5         | 16.13%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 9.68%   |
| Canon CanoScan LIDE 25                                      | 3         | 9.68%   |
| Canon CanoScan N650U/N656U                                  | 2         | 6.45%   |
| Canon CanoScan LiDE 220                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 210                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 120                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 110                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 100                                     | 2         | 6.45%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 3.23%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 3.23%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 3.23%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 3.23%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 3.23%   |
| HP ScanJet 82x0C                                            | 1         | 3.23%   |
| HP ScanJet 5590                                             | 1         | 3.23%   |
| HP ScanJet 3570c                                            | 1         | 3.23%   |
| HP Scanjet 200                                              | 1         | 3.23%   |
| HP PSC 1200                                                 | 1         | 3.23%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 3.23%   |
| Canon CanoScan LiDE 90                                      | 1         | 3.23%   |
| Canon CanoScan LiDE 200                                     | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 476       | 25.25%  |
| Microdia                               | 144       | 7.64%   |
| Realtek Semiconductor                  | 125       | 6.63%   |
| Acer                                   | 123       | 6.53%   |
| IMC Networks                           | 120       | 6.37%   |
| Suyin                                  | 111       | 5.89%   |
| Logitech                               | 98        | 5.2%    |
| Sunplus Innovation Technology          | 89        | 4.72%   |
| Quanta                                 | 63        | 3.34%   |
| Cheng Uei Precision Industry (Foxlink) | 58        | 3.08%   |
| Apple                                  | 49        | 2.6%    |
| Silicon Motion                         | 43        | 2.28%   |
| Alcor Micro                            | 42        | 2.23%   |
| Syntek                                 | 38        | 2.02%   |
| Ricoh                                  | 37        | 1.96%   |
| Lite-On Technology                     | 35        | 1.86%   |
| Z-Star Microelectronics                | 22        | 1.17%   |
| Samsung Electronics                    | 22        | 1.17%   |
| Microsoft                              | 19        | 1.01%   |
| Lenovo                                 | 14        | 0.74%   |
| ALi                                    | 13        | 0.69%   |
| Luxvisions Innotech Limited            | 11        | 0.58%   |
| Importek                               | 10        | 0.53%   |
| Primax Electronics                     | 9         | 0.48%   |
| OmniVision Technologies                | 7         | 0.37%   |
| Generalplus Technology                 | 7         | 0.37%   |
| GEMBIRD                                | 7         | 0.37%   |
| MacroSilicon                           | 6         | 0.32%   |
| DigiTech                               | 6         | 0.32%   |
| USB Camera                             | 5         | 0.27%   |
| Jieli Technology                       | 5         | 0.27%   |
| Cubeternet                             | 5         | 0.27%   |
| Creative Technology                    | 5         | 0.27%   |
| Sunplus Technology                     | 4         | 0.21%   |
| KYE Systems (Mouse Systems)            | 4         | 0.21%   |
| ARC International                      | 4         | 0.21%   |
| Unknown                                | 3         | 0.16%   |
| Trust                                  | 3         | 0.16%   |
| Genesys Logic                          | 3         | 0.16%   |
| Arkmicro Technologies                  | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 70        | 3.7%    |
| Realtek Integrated_Webcam_HD                     | 32        | 1.69%   |
| Chicony USB 2.0 Camera                           | 31        | 1.64%   |
| Microdia Integrated_Webcam_HD                    | 30        | 1.59%   |
| Chicony HD WebCam                                | 25        | 1.32%   |
| Logitech Webcam C270                             | 23        | 1.22%   |
| IMC Networks USB2.0 HD UVC WebCam                | 23        | 1.22%   |
| Realtek USB Camera                               | 22        | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)          | 21        | 1.11%   |
| Acer Integrated Camera                           | 21        | 1.11%   |
| Sunplus Integrated_Webcam_HD                     | 20        | 1.06%   |
| IMC Networks Integrated Camera                   | 19        | 1%      |
| Chicony TOSHIBA Web Camera - HD                  | 19        | 1%      |
| Alcor Micro USB 2.0 Camera                       | 19        | 1%      |
| Microdia Sonix USB 2.0 Camera                    | 18        | 0.95%   |
| Logitech HD Pro Webcam C920                      | 18        | 0.95%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE                        | 18        | 0.95%   |
| Suyin HP TrueVision HD                           | 17        | 0.9%    |
| Chicony HP Truevision HD                         | 17        | 0.9%    |
| Acer Lenovo EasyCamera                           | 17        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 16        | 0.85%   |
| Apple Built-in iSight                            | 16        | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 15        | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.79%   |
| Lite-On Integrated Camera                        | 14        | 0.74%   |
| Microdia Integrated Webcam                       | 13        | 0.69%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.63%   |
| Suyin Acer CrystalEye Webcam                     | 12        | 0.63%   |
| Sunplus HD WebCam                                | 12        | 0.63%   |
| Quanta HP Webcam                                 | 12        | 0.63%   |
| IMC Networks UVC VGA Webcam                      | 12        | 0.63%   |
| Acer SunplusIT Integrated Camera                 | 12        | 0.63%   |
| Acer BisonCam, NB Pro                            | 12        | 0.63%   |
| Lite-On HP HD Camera                             | 11        | 0.58%   |
| Chicony HP HD Camera                             | 11        | 0.58%   |
| Acer HD Webcam                                   | 11        | 0.58%   |
| Syntek Integrated Camera                         | 10        | 0.53%   |
| Suyin 1.3M HD WebCam                             | 10        | 0.53%   |
| Chicony WebCam                                   | 10        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 119       | 37.9%   |
| Synaptics                  | 61        | 19.43%  |
| AuthenTec                  | 52        | 16.56%  |
| Upek                       | 25        | 7.96%   |
| STMicroelectronics         | 18        | 5.73%   |
| Shenzhen Goodix Technology | 17        | 5.41%   |
| LighTuning Technology      | 11        | 3.5%    |
| Elan Microelectronics      | 8         | 2.55%   |
| Samsung Electronics        | 2         | 0.64%   |
| DigitalPersona             | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 8.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 8.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 7.32%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 6.69%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 5.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 4.46%   |
| AuthenTec AES2810                                                          | 14        | 4.46%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.5%    |
| Validity Sensors VFS491                                                    | 11        | 3.5%    |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 3.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 3.18%   |
| Unknown                                                                    | 9         | 2.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.55%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.55%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.23%   |
| AuthenTec AES1600                                                          | 7         | 2.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.91%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.91%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.27%   |
| Synaptics  WBDI                                                            | 4         | 1.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.96%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.96%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.96%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.64%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.64%   |
| Synaptics WBDI Device                                                      | 2         | 0.64%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.64%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.64%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.32%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.32%   |
| Samsung Fingerprint Device                                                 | 1         | 0.32%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 60        | 33.9%   |
| Alcor Micro               | 46        | 25.99%  |
| O2 Micro                  | 27        | 15.25%  |
| Upek                      | 15        | 8.47%   |
| Lenovo                    | 15        | 8.47%   |
| OmniKey                   | 3         | 1.69%   |
| Reiner SCT Kartensysteme  | 2         | 1.13%   |
| Gemalto (was Gemplus)     | 2         | 1.13%   |
| In Focus Systems          | 1         | 0.56%   |
| Fujitsu Siemens Computers | 1         | 0.56%   |
| Chicony Electronics       | 1         | 0.56%   |
| Cherry                    | 1         | 0.56%   |
| C3PO                      | 1         | 0.56%   |
| Aktiv                     | 1         | 0.56%   |
| Advanced Card Systems     | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 25.99%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 15.25%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 11.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 8.47%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 7.91%   |
| Broadcom 5880                                                                | 14        | 7.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.08%   |
| Broadcom 58200                                                               | 9         | 5.08%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 3.39%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.13%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.56%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.56%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.56%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.56%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.56%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.56%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.56%   |
| Aktiv Rutoken lite                                                           | 1         | 0.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2728      | 73.69%  |
| 1     | 776       | 20.96%  |
| 2     | 158       | 4.27%   |
| 3     | 24        | 0.65%   |
| 4     | 11        | 0.3%    |
| 5     | 3         | 0.08%   |
| 10    | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 313       | 26.98%  |
| Graphics card            | 234       | 20.17%  |
| Chipcard                 | 169       | 14.57%  |
| Net/wireless             | 135       | 11.64%  |
| Communication controller | 51        | 4.4%    |
| Modem                    | 46        | 3.97%   |
| Camera                   | 33        | 2.84%   |
| Multimedia controller    | 32        | 2.76%   |
| Unassigned class         | 25        | 2.16%   |
| Bluetooth                | 23        | 1.98%   |
| Storage                  | 22        | 1.9%    |
| Sound                    | 21        | 1.81%   |
| Card reader              | 19        | 1.64%   |
| Flash memory             | 16        | 1.38%   |
| Network                  | 7         | 0.6%    |
| Net/ethernet             | 6         | 0.52%   |
| Dvb card                 | 3         | 0.26%   |
| Storage/raid             | 2         | 0.17%   |
| Video                    | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

