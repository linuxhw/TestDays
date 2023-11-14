Linux Mint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 11654

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B450M MORTAR TITANIUM       | [a22610f17c](https://linux-hardware.org/?probe=a22610f17c) | Nov 06, 2023 |
| Unknown       | HX90                        | [bc832d475f](https://linux-hardware.org/?probe=bc832d475f) | Nov 06, 2023 |
| Unknown       | HX90                        | [91269ec2b8](https://linux-hardware.org/?probe=91269ec2b8) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [9e50325ddd](https://linux-hardware.org/?probe=9e50325ddd) | Nov 06, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| HP            | 198E                        | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Dell          | 042P49 A02                  | [b8808915ed](https://linux-hardware.org/?probe=b8808915ed) | Nov 05, 2023 |
| MSI           | Z77 MPower                  | [9a199b462a](https://linux-hardware.org/?probe=9a199b462a) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [f48ca40214](https://linux-hardware.org/?probe=f48ca40214) | Nov 05, 2023 |
| ASUSTek       | PRIME J4005I-C              | [76b89da142](https://linux-hardware.org/?probe=76b89da142) | Nov 05, 2023 |
| Alienware     | 0N43JM A01                  | [7bd0e03c1b](https://linux-hardware.org/?probe=7bd0e03c1b) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [60f590c96c](https://linux-hardware.org/?probe=60f590c96c) | Nov 05, 2023 |
| ASUSTek       | Maximus IX FORMULA          | [45e65903ff](https://linux-hardware.org/?probe=45e65903ff) | Nov 04, 2023 |
| Gigabyte      | H510M S2H V2                | [29fc753f1e](https://linux-hardware.org/?probe=29fc753f1e) | Nov 04, 2023 |
| Unknown       | Unknown                     | [f1e059fa93](https://linux-hardware.org/?probe=f1e059fa93) | Nov 04, 2023 |
| HP            | 21D0                        | [160964fbab](https://linux-hardware.org/?probe=160964fbab) | Nov 04, 2023 |
| HP            | 8767 A                      | [307b4eb17b](https://linux-hardware.org/?probe=307b4eb17b) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e6f4957064](https://linux-hardware.org/?probe=e6f4957064) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [03f8b26adb](https://linux-hardware.org/?probe=03f8b26adb) | Nov 04, 2023 |
| Gigabyte      | 945GM-S2                    | [f71f764594](https://linux-hardware.org/?probe=f71f764594) | Nov 04, 2023 |
| HP            | 8767 A                      | [a9d65549d2](https://linux-hardware.org/?probe=a9d65549d2) | Nov 04, 2023 |
| ECS           | A890GXM-A2                  | [3e5d819c23](https://linux-hardware.org/?probe=3e5d819c23) | Nov 03, 2023 |
| ECS           | A890GXM-A2                  | [9fb5c6d4d3](https://linux-hardware.org/?probe=9fb5c6d4d3) | Nov 03, 2023 |
| Gigabyte      | H510M S2H V2                | [2d4845b6b9](https://linux-hardware.org/?probe=2d4845b6b9) | Nov 03, 2023 |
| ASUSTek       | PRIME Z370-A                | [ae66cf41f9](https://linux-hardware.org/?probe=ae66cf41f9) | Nov 03, 2023 |
| ASUSTek       | PRIME Z370-A                | [92b484d86d](https://linux-hardware.org/?probe=92b484d86d) | Nov 03, 2023 |
| HP            | 843B                        | [8fdaf74414](https://linux-hardware.org/?probe=8fdaf74414) | Nov 03, 2023 |
| HP            | 843B                        | [ba22079238](https://linux-hardware.org/?probe=ba22079238) | Nov 03, 2023 |
| HP            | 21D0                        | [c634d51a77](https://linux-hardware.org/?probe=c634d51a77) | Nov 03, 2023 |
| ASUSTek       | G20AJ                       | [f9942dbf89](https://linux-hardware.org/?probe=f9942dbf89) | Nov 03, 2023 |
| Medion        | MS-7848                     | [ced5528ea5](https://linux-hardware.org/?probe=ced5528ea5) | Nov 03, 2023 |
| ASUSTek       | G20AJ                       | [ca1a60e2df](https://linux-hardware.org/?probe=ca1a60e2df) | Nov 02, 2023 |
| Dell          | 096JG8 A00                  | [eb001cdbf5](https://linux-hardware.org/?probe=eb001cdbf5) | Nov 02, 2023 |
| ASRock        | 990FX Extreme3              | [ad8e4a9dae](https://linux-hardware.org/?probe=ad8e4a9dae) | Nov 02, 2023 |
| AMI           | Intel                       | [8685e22886](https://linux-hardware.org/?probe=8685e22886) | Nov 01, 2023 |
| HP            | 822A                        | [59c055e360](https://linux-hardware.org/?probe=59c055e360) | Nov 01, 2023 |
| ASRock        | B450M Steel Legend          | [ebfb135726](https://linux-hardware.org/?probe=ebfb135726) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | [f54d8e7dea](https://linux-hardware.org/?probe=f54d8e7dea) | Nov 01, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [4fc590fe55](https://linux-hardware.org/?probe=4fc590fe55) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [bbbdb78ae3](https://linux-hardware.org/?probe=bbbdb78ae3) | Nov 01, 2023 |
| Dell          | 0RF705                      | [b287691e11](https://linux-hardware.org/?probe=b287691e11) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | [9a2f1f7750](https://linux-hardware.org/?probe=9a2f1f7750) | Nov 01, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [a31e5e0862](https://linux-hardware.org/?probe=a31e5e0862) | Nov 01, 2023 |
| HP            | 1497                        | [0fd6a908fe](https://linux-hardware.org/?probe=0fd6a908fe) | Nov 01, 2023 |
| AMI           | Intel                       | [fa89237919](https://linux-hardware.org/?probe=fa89237919) | Nov 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | [d73c8ca742](https://linux-hardware.org/?probe=d73c8ca742) | Nov 01, 2023 |
| Sapphire      | PE-AM2RS690V2               | [2b2de28f02](https://linux-hardware.org/?probe=2b2de28f02) | Nov 01, 2023 |
| MSI           | B550 GAMING GEN3            | [bd3efc9d84](https://linux-hardware.org/?probe=bd3efc9d84) | Nov 01, 2023 |
| Medion        | MS-7800                     | [8ebfbd5941](https://linux-hardware.org/?probe=8ebfbd5941) | Nov 01, 2023 |
| ASUSTek       | B85M-E                      | [6709fd475b](https://linux-hardware.org/?probe=6709fd475b) | Nov 01, 2023 |
| MSI           | H110M ECO                   | [d2f60e8bc9](https://linux-hardware.org/?probe=d2f60e8bc9) | Nov 01, 2023 |
| HP            | 2B2C                        | [1ed40f19d9](https://linux-hardware.org/?probe=1ed40f19d9) | Nov 01, 2023 |
| MSI           | Z87-G45 GAMING              | [962f4ccb9e](https://linux-hardware.org/?probe=962f4ccb9e) | Oct 31, 2023 |
| AMD           | A88K                        | [963e38ef9a](https://linux-hardware.org/?probe=963e38ef9a) | Oct 31, 2023 |
| Gigabyte      | B450M S2H                   | [d099ae69e8](https://linux-hardware.org/?probe=d099ae69e8) | Oct 31, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | [d2072a9949](https://linux-hardware.org/?probe=d2072a9949) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [16c9a49c7d](https://linux-hardware.org/?probe=16c9a49c7d) | Oct 31, 2023 |
| ASUSTek       | P8H67-M EVO                 | [64a6524677](https://linux-hardware.org/?probe=64a6524677) | Oct 31, 2023 |
| Gigabyte      | Z97P-D3                     | [cf26456a24](https://linux-hardware.org/?probe=cf26456a24) | Oct 31, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [56e4a560bc](https://linux-hardware.org/?probe=56e4a560bc) | Oct 31, 2023 |
| ASRock        | B450M Pro4                  | [3880922e48](https://linux-hardware.org/?probe=3880922e48) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [25aa8e9401](https://linux-hardware.org/?probe=25aa8e9401) | Oct 31, 2023 |
| ASUSTek       | P8H67-M LE                  | [d4a5c11db9](https://linux-hardware.org/?probe=d4a5c11db9) | Oct 31, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | [95a0ff1bb1](https://linux-hardware.org/?probe=95a0ff1bb1) | Oct 31, 2023 |
| Intel         | H311 DS3 V1.0               | [2eabffe817](https://linux-hardware.org/?probe=2eabffe817) | Oct 31, 2023 |
| ASUSTek       | H81M-C/BR                   | [b92870ed6a](https://linux-hardware.org/?probe=b92870ed6a) | Oct 31, 2023 |
| ASUSTek       | PRIME X570-PRO              | [0251ada092](https://linux-hardware.org/?probe=0251ada092) | Oct 30, 2023 |
| Cincoze       | DX-1000.01.001              | [fb33e90b93](https://linux-hardware.org/?probe=fb33e90b93) | Oct 30, 2023 |
| ASUSTek       | B85M-G                      | [e4b4cf1229](https://linux-hardware.org/?probe=e4b4cf1229) | Oct 30, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [a2faa2b06a](https://linux-hardware.org/?probe=a2faa2b06a) | Oct 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [28ddca3b76](https://linux-hardware.org/?probe=28ddca3b76) | Oct 30, 2023 |
| MSI           | Z87-G45 GAMING              | [731cb3b152](https://linux-hardware.org/?probe=731cb3b152) | Oct 30, 2023 |
| MSI           | Z490-A PRO                  | [449c0df691](https://linux-hardware.org/?probe=449c0df691) | Oct 30, 2023 |
| ASRockRack    | C236 WS                     | [1e6fea20e9](https://linux-hardware.org/?probe=1e6fea20e9) | Oct 30, 2023 |
| ASRock        | H61M-DGS R2.0               | [d8bd0d7795](https://linux-hardware.org/?probe=d8bd0d7795) | Oct 30, 2023 |
| Gigabyte      | F2A88X-D3H                  | [aa9ef029e5](https://linux-hardware.org/?probe=aa9ef029e5) | Oct 30, 2023 |
| ASRock        | G41M-VS3                    | [908b330ba2](https://linux-hardware.org/?probe=908b330ba2) | Oct 29, 2023 |
| ASUSTek       | Z87-DELUXE                  | [00b15965c5](https://linux-hardware.org/?probe=00b15965c5) | Oct 29, 2023 |
| Biostar       | H610MH                      | [82198b27e1](https://linux-hardware.org/?probe=82198b27e1) | Oct 29, 2023 |
| Foxconn       | 2ADA                        | [ce19056aa6](https://linux-hardware.org/?probe=ce19056aa6) | Oct 29, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [67a61bc860](https://linux-hardware.org/?probe=67a61bc860) | Oct 29, 2023 |
| ASUSTek       | M4N72-E                     | [199a901e5c](https://linux-hardware.org/?probe=199a901e5c) | Oct 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [db992da5fa](https://linux-hardware.org/?probe=db992da5fa) | Oct 28, 2023 |
| HP            | 8918                        | [12336ce9fe](https://linux-hardware.org/?probe=12336ce9fe) | Oct 28, 2023 |
| ASRock        | Z97 Killer                  | [b26c6bcd4b](https://linux-hardware.org/?probe=b26c6bcd4b) | Oct 28, 2023 |
| ASUSTek       | P8H67-M EVO                 | [a4bed1729d](https://linux-hardware.org/?probe=a4bed1729d) | Oct 28, 2023 |
| Gigabyte      | 970A-DS3P                   | [e9d377b8cd](https://linux-hardware.org/?probe=e9d377b8cd) | Oct 28, 2023 |
| Dell          | 08NPPY A01                  | [62bc2b3e7a](https://linux-hardware.org/?probe=62bc2b3e7a) | Oct 28, 2023 |
| HC Technol... | HCAR5000-MI                 | [0c3d1e964a](https://linux-hardware.org/?probe=0c3d1e964a) | Oct 27, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [637a5897b7](https://linux-hardware.org/?probe=637a5897b7) | Oct 27, 2023 |
| Dell          | 040DDP A01                  | [6d081e2627](https://linux-hardware.org/?probe=6d081e2627) | Oct 27, 2023 |
| HP            | 8399                        | [35351ed170](https://linux-hardware.org/?probe=35351ed170) | Oct 27, 2023 |
| MSI           | Z170A PC MATE               | [e76ead66bc](https://linux-hardware.org/?probe=e76ead66bc) | Oct 27, 2023 |
| ASUSTek       | CM6850                      | [b6819e8599](https://linux-hardware.org/?probe=b6819e8599) | Oct 27, 2023 |
| Dell          | 0NW6H5 A00                  | [95858bf436](https://linux-hardware.org/?probe=95858bf436) | Oct 26, 2023 |
| Dell          | 0RY007                      | [56af1be7cc](https://linux-hardware.org/?probe=56af1be7cc) | Oct 26, 2023 |
| Gigabyte      | 945GM-S2                    | [baaa212a39](https://linux-hardware.org/?probe=baaa212a39) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | [ab3b2be8f5](https://linux-hardware.org/?probe=ab3b2be8f5) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | [8f83740c8d](https://linux-hardware.org/?probe=8f83740c8d) | Oct 26, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [0a305499ef](https://linux-hardware.org/?probe=0a305499ef) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [8926585836](https://linux-hardware.org/?probe=8926585836) | Oct 26, 2023 |
| ASUSTek       | P5K-V                       | [d49d2a9835](https://linux-hardware.org/?probe=d49d2a9835) | Oct 26, 2023 |
| Dell          | 0N4YC8 A00                  | [f54b1a097e](https://linux-hardware.org/?probe=f54b1a097e) | Oct 26, 2023 |
| Gigabyte      | B560M DS3H V2               | [b66ca0672b](https://linux-hardware.org/?probe=b66ca0672b) | Oct 25, 2023 |
| Gigabyte      | B560M DS3H V2               | [64908ddca3](https://linux-hardware.org/?probe=64908ddca3) | Oct 25, 2023 |
| Intel         | JSL MRD                     | [4cf2468a9c](https://linux-hardware.org/?probe=4cf2468a9c) | Oct 25, 2023 |
| MSI           | H81M-P33                    | [f59a3c2021](https://linux-hardware.org/?probe=f59a3c2021) | Oct 25, 2023 |
| ASUSTek       | Leonite2                    | [f2ac570d7b](https://linux-hardware.org/?probe=f2ac570d7b) | Oct 25, 2023 |
| Intel         | DX79TO AAG28805-401         | [75e8f73b6a](https://linux-hardware.org/?probe=75e8f73b6a) | Oct 25, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [138843c6dc](https://linux-hardware.org/?probe=138843c6dc) | Oct 25, 2023 |
| Gigabyte      | 945GM-S2                    | [259ddccf1b](https://linux-hardware.org/?probe=259ddccf1b) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [e0dc5536a8](https://linux-hardware.org/?probe=e0dc5536a8) | Oct 25, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [56826e6464](https://linux-hardware.org/?probe=56826e6464) | Oct 25, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b4e2c4d9b6](https://linux-hardware.org/?probe=b4e2c4d9b6) | Oct 25, 2023 |
| Gigabyte      | 990FXA-UD7                  | [eb3960a181](https://linux-hardware.org/?probe=eb3960a181) | Oct 25, 2023 |
| ASRock        | H87M Pro4                   | [64ba15c5e5](https://linux-hardware.org/?probe=64ba15c5e5) | Oct 24, 2023 |
| ASRock        | H87M Pro4                   | [4677d3d0b8](https://linux-hardware.org/?probe=4677d3d0b8) | Oct 24, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3b5b639e73](https://linux-hardware.org/?probe=3b5b639e73) | Oct 24, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [279929b8c5](https://linux-hardware.org/?probe=279929b8c5) | Oct 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [61d3768e3f](https://linux-hardware.org/?probe=61d3768e3f) | Oct 24, 2023 |
| Dell          | 0200DY A01                  | [9b6ccf43a5](https://linux-hardware.org/?probe=9b6ccf43a5) | Oct 24, 2023 |
| Gigabyte      | A520I AC                    | [fc82aed364](https://linux-hardware.org/?probe=fc82aed364) | Oct 23, 2023 |
| Intel         | H61 V124                    | [2405df9db3](https://linux-hardware.org/?probe=2405df9db3) | Oct 23, 2023 |
| HP            | 81C9                        | [39a3586ed1](https://linux-hardware.org/?probe=39a3586ed1) | Oct 23, 2023 |
| HP            | 8876 11                     | [e7f8609b12](https://linux-hardware.org/?probe=e7f8609b12) | Oct 23, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [48de72a7a6](https://linux-hardware.org/?probe=48de72a7a6) | Oct 23, 2023 |
| ASRock        | H61M-DGS R2.0               | [24d1406cad](https://linux-hardware.org/?probe=24d1406cad) | Oct 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d3e630e86d](https://linux-hardware.org/?probe=d3e630e86d) | Oct 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b981ef3e39](https://linux-hardware.org/?probe=b981ef3e39) | Oct 23, 2023 |
| Dell          | 09KPNV A00                  | [e7d2257726](https://linux-hardware.org/?probe=e7d2257726) | Oct 23, 2023 |
| AZW           | BT3 X                       | [c1e3c10fc4](https://linux-hardware.org/?probe=c1e3c10fc4) | Oct 23, 2023 |
| AZW           | BT3 X                       | [78328e112b](https://linux-hardware.org/?probe=78328e112b) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [948da1d335](https://linux-hardware.org/?probe=948da1d335) | Oct 22, 2023 |
| ASUSTek       | PRIME B450M-K II            | [4123085fec](https://linux-hardware.org/?probe=4123085fec) | Oct 22, 2023 |
| Gigabyte      | B550M DS3H                  | [8bfba005ad](https://linux-hardware.org/?probe=8bfba005ad) | Oct 22, 2023 |
| Gigabyte      | B550M DS3H                  | [6677da99ae](https://linux-hardware.org/?probe=6677da99ae) | Oct 22, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [8a9d0ba0e6](https://linux-hardware.org/?probe=8a9d0ba0e6) | Oct 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b3113ef419](https://linux-hardware.org/?probe=b3113ef419) | Oct 22, 2023 |
| Unknown       | GB01                        | [5c0f72d3f0](https://linux-hardware.org/?probe=5c0f72d3f0) | Oct 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [588ad7e7ef](https://linux-hardware.org/?probe=588ad7e7ef) | Oct 22, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [ec2248edc2](https://linux-hardware.org/?probe=ec2248edc2) | Oct 22, 2023 |
| Gigabyte      | Z490 VISION D               | [fb9dd530e9](https://linux-hardware.org/?probe=fb9dd530e9) | Oct 21, 2023 |
| Acer          | Aspire M3450                | [7bbabe59d7](https://linux-hardware.org/?probe=7bbabe59d7) | Oct 21, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [d3298d136b](https://linux-hardware.org/?probe=d3298d136b) | Oct 21, 2023 |
| MSI           | H81M-P33                    | [04b9d686b6](https://linux-hardware.org/?probe=04b9d686b6) | Oct 21, 2023 |
| MSI           | B550-A PRO                  | [8db756bae3](https://linux-hardware.org/?probe=8db756bae3) | Oct 21, 2023 |
| Gigabyte      | B75M-D3H                    | [eb8522ff13](https://linux-hardware.org/?probe=eb8522ff13) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [87212fc8b1](https://linux-hardware.org/?probe=87212fc8b1) | Oct 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [57a08b87d8](https://linux-hardware.org/?probe=57a08b87d8) | Oct 21, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| ASRock        | FM2A68M-HD+                 | [aed5514f95](https://linux-hardware.org/?probe=aed5514f95) | Oct 21, 2023 |
| ASRock        | FM2A68M-HD+                 | [4aa0e3a887](https://linux-hardware.org/?probe=4aa0e3a887) | Oct 21, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [07a0ae59da](https://linux-hardware.org/?probe=07a0ae59da) | Oct 21, 2023 |
| HP            | 2215                        | [d244e54a96](https://linux-hardware.org/?probe=d244e54a96) | Oct 21, 2023 |
| Dell          | 0RY007                      | [084ad13415](https://linux-hardware.org/?probe=084ad13415) | Oct 21, 2023 |
| Gigabyte      | B75M-D3H                    | [deb1dc3eaa](https://linux-hardware.org/?probe=deb1dc3eaa) | Oct 21, 2023 |
| Acer          | Aspire M3450                | [f1c898ed29](https://linux-hardware.org/?probe=f1c898ed29) | Oct 21, 2023 |
| Dell          | 0KC9NP A01                  | [c38e54817a](https://linux-hardware.org/?probe=c38e54817a) | Oct 20, 2023 |
| Packard Be... | IMEDIA S2380                | [905b7ea7f0](https://linux-hardware.org/?probe=905b7ea7f0) | Oct 20, 2023 |
| ASUSTek       | H81M-E                      | [6577940606](https://linux-hardware.org/?probe=6577940606) | Oct 20, 2023 |
| ASUSTek       | H81M-E                      | [86b16af8d5](https://linux-hardware.org/?probe=86b16af8d5) | Oct 20, 2023 |
| Dell          | 0KV3RP A00                  | [aa258ef607](https://linux-hardware.org/?probe=aa258ef607) | Oct 20, 2023 |
| ASRock        | Q1900-ITX                   | [d4d8b74595](https://linux-hardware.org/?probe=d4d8b74595) | Oct 20, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b50515e464](https://linux-hardware.org/?probe=b50515e464) | Oct 20, 2023 |
| MSI           | H510M-A PRO                 | [f927a69d11](https://linux-hardware.org/?probe=f927a69d11) | Oct 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [7cd181ad3b](https://linux-hardware.org/?probe=7cd181ad3b) | Oct 20, 2023 |
| Dell          | 0XCR8D A03                  | [84eb6ce25e](https://linux-hardware.org/?probe=84eb6ce25e) | Oct 20, 2023 |
| MSI           | MS-7309                     | [2d1eefe4be](https://linux-hardware.org/?probe=2d1eefe4be) | Oct 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [95c5dfe865](https://linux-hardware.org/?probe=95c5dfe865) | Oct 19, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [87d2e5945b](https://linux-hardware.org/?probe=87d2e5945b) | Oct 19, 2023 |
| Dell          | 073MMW A02                  | [1c1ea56be3](https://linux-hardware.org/?probe=1c1ea56be3) | Oct 19, 2023 |
| ASUSTek       | M4A78LT-M                   | [cc8d1f7fb2](https://linux-hardware.org/?probe=cc8d1f7fb2) | Oct 19, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b7f7dc5f46](https://linux-hardware.org/?probe=b7f7dc5f46) | Oct 19, 2023 |
| Pegatron      | Benicia                     | [c8ec5c8db0](https://linux-hardware.org/?probe=c8ec5c8db0) | Oct 19, 2023 |
| Fujitsu Si... | D2828-A1 S26361-D2828-A1    | [c04e21ae93](https://linux-hardware.org/?probe=c04e21ae93) | Oct 19, 2023 |
| Pegatron      | 2AC2                        | [d8eafcf145](https://linux-hardware.org/?probe=d8eafcf145) | Oct 19, 2023 |
| Pegatron      | 2AC2                        | [bc37a84914](https://linux-hardware.org/?probe=bc37a84914) | Oct 19, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8f7a837f4f](https://linux-hardware.org/?probe=8f7a837f4f) | Oct 19, 2023 |
| ASUSTek       | PRIME B450M-A               | [ad5d949eba](https://linux-hardware.org/?probe=ad5d949eba) | Oct 19, 2023 |
| MSI           | Z590-A PRO                  | [804682ff68](https://linux-hardware.org/?probe=804682ff68) | Oct 19, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [9998c3eea0](https://linux-hardware.org/?probe=9998c3eea0) | Oct 19, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [1748fce718](https://linux-hardware.org/?probe=1748fce718) | Oct 18, 2023 |
| ASUSTek       | PRIME Z370-P                | [aa01fa43ac](https://linux-hardware.org/?probe=aa01fa43ac) | Oct 18, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [070de2c38f](https://linux-hardware.org/?probe=070de2c38f) | Oct 18, 2023 |
| MSI           | H77MA-G43                   | [b741ca0ecc](https://linux-hardware.org/?probe=b741ca0ecc) | Oct 18, 2023 |
| EPSON DIRE... | MR4400E                     | [3c07bfb5a0](https://linux-hardware.org/?probe=3c07bfb5a0) | Oct 18, 2023 |
| Dell          | 0NKW6Y A02                  | [5810a2ef0a](https://linux-hardware.org/?probe=5810a2ef0a) | Oct 17, 2023 |
| Dell          | 0NKW6Y A02                  | [ad07e33f54](https://linux-hardware.org/?probe=ad07e33f54) | Oct 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [c9f674352d](https://linux-hardware.org/?probe=c9f674352d) | Oct 17, 2023 |
| ASRock        | A320M-HD                    | [27d26a4a15](https://linux-hardware.org/?probe=27d26a4a15) | Oct 17, 2023 |
| ASUSTek       | P5K-V                       | [ca8e1433c5](https://linux-hardware.org/?probe=ca8e1433c5) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [78e9e09f46](https://linux-hardware.org/?probe=78e9e09f46) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | [54150823a1](https://linux-hardware.org/?probe=54150823a1) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | [e567a72b4c](https://linux-hardware.org/?probe=e567a72b4c) | Oct 17, 2023 |
| Dell          | 09KPNV A00                  | [f739f7caf6](https://linux-hardware.org/?probe=f739f7caf6) | Oct 17, 2023 |
| EPSON DIRE... | MR4400E                     | [8559cb634e](https://linux-hardware.org/?probe=8559cb634e) | Oct 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [c2191c4438](https://linux-hardware.org/?probe=c2191c4438) | Oct 17, 2023 |
| ASUSTek       | H61M-A/BR                   | [c615f7ee38](https://linux-hardware.org/?probe=c615f7ee38) | Oct 17, 2023 |
| ASUSTek       | X500MA                      | [2ffe0522e1](https://linux-hardware.org/?probe=2ffe0522e1) | Oct 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [61c4ebff0f](https://linux-hardware.org/?probe=61c4ebff0f) | Oct 16, 2023 |
| ASRock        | B550 Steel Legend           | [dba8d15f50](https://linux-hardware.org/?probe=dba8d15f50) | Oct 16, 2023 |
| Intel         | H61                         | [2bd77947d1](https://linux-hardware.org/?probe=2bd77947d1) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5b226d6424](https://linux-hardware.org/?probe=5b226d6424) | Oct 16, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [7edc965933](https://linux-hardware.org/?probe=7edc965933) | Oct 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [084e18e78d](https://linux-hardware.org/?probe=084e18e78d) | Oct 15, 2023 |
| HP            | 8055                        | [5fe9038a50](https://linux-hardware.org/?probe=5fe9038a50) | Oct 15, 2023 |
| Pegatron      | 2ACD                        | [45315e3a0c](https://linux-hardware.org/?probe=45315e3a0c) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [066851473c](https://linux-hardware.org/?probe=066851473c) | Oct 15, 2023 |
| HP            | 8055                        | [8a74853b61](https://linux-hardware.org/?probe=8a74853b61) | Oct 15, 2023 |
| MSI           | B450M PRO-M2                | [d6e1f3c3b8](https://linux-hardware.org/?probe=d6e1f3c3b8) | Oct 15, 2023 |
| HP            | 212B                        | [8a59414060](https://linux-hardware.org/?probe=8a59414060) | Oct 15, 2023 |
| MSI           | B450M PRO-M2                | [c99b37a865](https://linux-hardware.org/?probe=c99b37a865) | Oct 15, 2023 |
| Shuttle       | FD37V10                     | [929e944dd3](https://linux-hardware.org/?probe=929e944dd3) | Oct 15, 2023 |
| Shuttle       | FD37V10                     | [d9043c11bd](https://linux-hardware.org/?probe=d9043c11bd) | Oct 15, 2023 |
| Gigabyte      | B85M-D3H                    | [3fca075f42](https://linux-hardware.org/?probe=3fca075f42) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [b9f47c0a25](https://linux-hardware.org/?probe=b9f47c0a25) | Oct 15, 2023 |
| Dell          | 0NW6H5 A00                  | [54a3d7c0ea](https://linux-hardware.org/?probe=54a3d7c0ea) | Oct 15, 2023 |
| ONDA          | H110CD3 VER1.01             | [df23b03be3](https://linux-hardware.org/?probe=df23b03be3) | Oct 15, 2023 |
| ECS           | G31T-M                      | [8f11ce9a6a](https://linux-hardware.org/?probe=8f11ce9a6a) | Oct 15, 2023 |
| Unknown       | Unknown                     | [b45f1baf7a](https://linux-hardware.org/?probe=b45f1baf7a) | Oct 14, 2023 |
| BESSTAR Te... | UM250 V1.0                  | [b4697a227f](https://linux-hardware.org/?probe=b4697a227f) | Oct 14, 2023 |
| MSI           | MAG B550 TORPEDO            | [2bb3baf0f6](https://linux-hardware.org/?probe=2bb3baf0f6) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eaf16e3ac3](https://linux-hardware.org/?probe=eaf16e3ac3) | Oct 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [e44d1b7e3c](https://linux-hardware.org/?probe=e44d1b7e3c) | Oct 14, 2023 |
| ASRock        | H55M-LE                     | [444d608969](https://linux-hardware.org/?probe=444d608969) | Oct 14, 2023 |
| Gigabyte      | Z97N-WIFI                   | [560c190c99](https://linux-hardware.org/?probe=560c190c99) | Oct 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [618fcf6a1e](https://linux-hardware.org/?probe=618fcf6a1e) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | [4280b509c6](https://linux-hardware.org/?probe=4280b509c6) | Oct 14, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4ba8548e96](https://linux-hardware.org/?probe=4ba8548e96) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | [06aa8e692c](https://linux-hardware.org/?probe=06aa8e692c) | Oct 14, 2023 |
| Dell          | 0WR7PY A02                  | [bcdb61bd85](https://linux-hardware.org/?probe=bcdb61bd85) | Oct 14, 2023 |
| Intel         | DH55HC AAE70933-501         | [447110886e](https://linux-hardware.org/?probe=447110886e) | Oct 14, 2023 |
| Gigabyte      | Z170M-D3H-CF                | [c090855f1d](https://linux-hardware.org/?probe=c090855f1d) | Oct 13, 2023 |
| Unknown       | MZ-B75-S                    | [6d58c79c33](https://linux-hardware.org/?probe=6d58c79c33) | Oct 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | [88f08528f7](https://linux-hardware.org/?probe=88f08528f7) | Oct 13, 2023 |
| ASRock        | H61M-DGS R2.0               | [8ca3e29982](https://linux-hardware.org/?probe=8ca3e29982) | Oct 13, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | [dbc150b2b5](https://linux-hardware.org/?probe=dbc150b2b5) | Oct 13, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [f164204da9](https://linux-hardware.org/?probe=f164204da9) | Oct 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [662889cd52](https://linux-hardware.org/?probe=662889cd52) | Oct 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [99092f3766](https://linux-hardware.org/?probe=99092f3766) | Oct 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [0723750e07](https://linux-hardware.org/?probe=0723750e07) | Oct 12, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [0400bae582](https://linux-hardware.org/?probe=0400bae582) | Oct 12, 2023 |
| ASRock        | A320M-HD R4.0               | [1b1dd0c7fd](https://linux-hardware.org/?probe=1b1dd0c7fd) | Oct 12, 2023 |
| Dell          | 00V62H A01                  | [4957e141ac](https://linux-hardware.org/?probe=4957e141ac) | Oct 12, 2023 |
| HP            | 82F2                        | [6a5c62ec30](https://linux-hardware.org/?probe=6a5c62ec30) | Oct 12, 2023 |
| HP            | 82F2                        | [ebf3c3339a](https://linux-hardware.org/?probe=ebf3c3339a) | Oct 12, 2023 |
| MSI           | PRO B650M-A WIFI            | [d20a5d2c71](https://linux-hardware.org/?probe=d20a5d2c71) | Oct 12, 2023 |
| ASUSTek       | Z87-K                       | [55af6adcc5](https://linux-hardware.org/?probe=55af6adcc5) | Oct 11, 2023 |
| HP            | 81C9                        | [279889bb45](https://linux-hardware.org/?probe=279889bb45) | Oct 11, 2023 |
| HP            | 8437                        | [ac8d6773a3](https://linux-hardware.org/?probe=ac8d6773a3) | Oct 11, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [a6e6952b42](https://linux-hardware.org/?probe=a6e6952b42) | Oct 11, 2023 |
| Foxconn       | 2AB1                        | [d30d9f59a8](https://linux-hardware.org/?probe=d30d9f59a8) | Oct 11, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [a646cc1cc1](https://linux-hardware.org/?probe=a646cc1cc1) | Oct 10, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [d731fb0868](https://linux-hardware.org/?probe=d731fb0868) | Oct 10, 2023 |
| Gigabyte      | Z97P-D3                     | [e8d34cd0b9](https://linux-hardware.org/?probe=e8d34cd0b9) | Oct 10, 2023 |
| Gigabyte      | H81M-S2V                    | [bad4423bfe](https://linux-hardware.org/?probe=bad4423bfe) | Oct 10, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [24e0ada60a](https://linux-hardware.org/?probe=24e0ada60a) | Oct 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec66d208a0](https://linux-hardware.org/?probe=ec66d208a0) | Oct 10, 2023 |
| Gigabyte      | Z690 UD DDR4                | [8b0cd9f9f7](https://linux-hardware.org/?probe=8b0cd9f9f7) | Oct 10, 2023 |
| NF-M2S        | ABIT                        | [d34c0b839e](https://linux-hardware.org/?probe=d34c0b839e) | Oct 09, 2023 |
| MSI           | PRO B660-A DDR4             | [8c734131f3](https://linux-hardware.org/?probe=8c734131f3) | Oct 09, 2023 |
| ASRock        | H97 Anniversary             | [c9e7861ff4](https://linux-hardware.org/?probe=c9e7861ff4) | Oct 09, 2023 |
| Dell          | 0WMJ54 A01                  | [58b4471d7e](https://linux-hardware.org/?probe=58b4471d7e) | Oct 09, 2023 |
| ASUSTek       | P5B                         | [c572658076](https://linux-hardware.org/?probe=c572658076) | Oct 09, 2023 |
| MSI           | MAG B660M MORTAR WIFI       | [51302ad94d](https://linux-hardware.org/?probe=51302ad94d) | Oct 09, 2023 |
| MACHINIST     | E5-MR9A V1.0                | [4be00bee3e](https://linux-hardware.org/?probe=4be00bee3e) | Oct 09, 2023 |
| ASRock        | A320M-HD R4.0               | [84fc58ce28](https://linux-hardware.org/?probe=84fc58ce28) | Oct 08, 2023 |
| Intel         | DG41WV AAE90316-102         | [c666aa6077](https://linux-hardware.org/?probe=c666aa6077) | Oct 08, 2023 |
| ASUSTek       | H81M-A/BR                   | [b580accff5](https://linux-hardware.org/?probe=b580accff5) | Oct 08, 2023 |
| MACHINIST     | E5-MR9A V1.0                | [68e7f53229](https://linux-hardware.org/?probe=68e7f53229) | Oct 08, 2023 |
| ASUSTek       | B85M-G                      | [b87a632a3b](https://linux-hardware.org/?probe=b87a632a3b) | Oct 08, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [fb4e034718](https://linux-hardware.org/?probe=fb4e034718) | Oct 08, 2023 |
| HP            | 18E7                        | [ec69c74dde](https://linux-hardware.org/?probe=ec69c74dde) | Oct 08, 2023 |
| ASRock        | Z77 Extreme4                | [e1cfe6d474](https://linux-hardware.org/?probe=e1cfe6d474) | Oct 08, 2023 |
| MSI           | X58 Pro-E                   | [939bfb5fe4](https://linux-hardware.org/?probe=939bfb5fe4) | Oct 08, 2023 |
| MSI           | X58 Pro-E                   | [fcf3cf909a](https://linux-hardware.org/?probe=fcf3cf909a) | Oct 08, 2023 |
| MSI           | MAG B660M MORTAR WIFI       | [dbeecdf3ee](https://linux-hardware.org/?probe=dbeecdf3ee) | Oct 08, 2023 |
| HP            | 81C9                        | [9c1de82ad4](https://linux-hardware.org/?probe=9c1de82ad4) | Oct 08, 2023 |
| Dell          | 0TTDMJ A00                  | [9dd974d98f](https://linux-hardware.org/?probe=9dd974d98f) | Oct 07, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [100eb19d44](https://linux-hardware.org/?probe=100eb19d44) | Oct 07, 2023 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | [bad5263013](https://linux-hardware.org/?probe=bad5263013) | Oct 07, 2023 |
| HP            | 158A                        | [c2cb1b9180](https://linux-hardware.org/?probe=c2cb1b9180) | Oct 07, 2023 |
| HP            | 21D0                        | [2a90ec5b5a](https://linux-hardware.org/?probe=2a90ec5b5a) | Oct 07, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [c2dac7521b](https://linux-hardware.org/?probe=c2dac7521b) | Oct 07, 2023 |
| Dell          | 0PU052                      | [c32b862792](https://linux-hardware.org/?probe=c32b862792) | Oct 07, 2023 |
| Foxconn       | 2AB1                        | [718bd3f802](https://linux-hardware.org/?probe=718bd3f802) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | [839ad0c4b6](https://linux-hardware.org/?probe=839ad0c4b6) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | [f3e7c14b62](https://linux-hardware.org/?probe=f3e7c14b62) | Oct 07, 2023 |
| ASUSTek       | M5A88-V EVO                 | [58f48d2153](https://linux-hardware.org/?probe=58f48d2153) | Oct 07, 2023 |
| ASUSTek       | B85M-G                      | [dbe9a8352b](https://linux-hardware.org/?probe=dbe9a8352b) | Oct 07, 2023 |
| Dell          | 0NW6H5 A00                  | [665a7ff2eb](https://linux-hardware.org/?probe=665a7ff2eb) | Oct 06, 2023 |
| Pegatron      | 2AC2                        | [34169e1b27](https://linux-hardware.org/?probe=34169e1b27) | Oct 06, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [dcc7e8da51](https://linux-hardware.org/?probe=dcc7e8da51) | Oct 06, 2023 |
| ASUSTek       | P8H77-M PRO                 | [355bc3fdfc](https://linux-hardware.org/?probe=355bc3fdfc) | Oct 06, 2023 |
| Gigabyte      | GA-A75M-S2V                 | [3da2ab0f79](https://linux-hardware.org/?probe=3da2ab0f79) | Oct 06, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8ad2fc1fd8](https://linux-hardware.org/?probe=8ad2fc1fd8) | Oct 06, 2023 |
| Unknown       | Unknown                     | [dd213b27e1](https://linux-hardware.org/?probe=dd213b27e1) | Oct 06, 2023 |
| Unknown       | 1.0                         | [f0cef2eaac](https://linux-hardware.org/?probe=f0cef2eaac) | Oct 06, 2023 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | [06814a2a87](https://linux-hardware.org/?probe=06814a2a87) | Oct 06, 2023 |
| Gigabyte      | GA-A75M-S2V                 | [aa3a892278](https://linux-hardware.org/?probe=aa3a892278) | Oct 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [a2df1f8024](https://linux-hardware.org/?probe=a2df1f8024) | Oct 05, 2023 |
| ASUSTek       | M4A78T-E                    | [2eadbdec5d](https://linux-hardware.org/?probe=2eadbdec5d) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d5b22876c6](https://linux-hardware.org/?probe=d5b22876c6) | Oct 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [80010c71e1](https://linux-hardware.org/?probe=80010c71e1) | Oct 04, 2023 |
| ASUSTek       | Z87-K                       | [60f9987e7d](https://linux-hardware.org/?probe=60f9987e7d) | Oct 04, 2023 |
| ASRock        | Z97 Extreme4                | [eec7dacbba](https://linux-hardware.org/?probe=eec7dacbba) | Oct 04, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [9272efa028](https://linux-hardware.org/?probe=9272efa028) | Oct 04, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [dcdb58537e](https://linux-hardware.org/?probe=dcdb58537e) | Oct 04, 2023 |
| Acer          | Aspire G7760                | [a6d77a2162](https://linux-hardware.org/?probe=a6d77a2162) | Oct 04, 2023 |
| HP            | 18E7                        | [13028106c6](https://linux-hardware.org/?probe=13028106c6) | Oct 04, 2023 |
| HP            | 1905                        | [c4c0e2e0b9](https://linux-hardware.org/?probe=c4c0e2e0b9) | Oct 04, 2023 |
| ASRock        | B450M Pro4                  | [67198e4902](https://linux-hardware.org/?probe=67198e4902) | Oct 04, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [9e62c6ffa3](https://linux-hardware.org/?probe=9e62c6ffa3) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [8d69a9df41](https://linux-hardware.org/?probe=8d69a9df41) | Oct 03, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ae9334124d](https://linux-hardware.org/?probe=ae9334124d) | Oct 03, 2023 |
| Gigabyte      | 945GM-S2                    | [a445c2511c](https://linux-hardware.org/?probe=a445c2511c) | Oct 03, 2023 |
| Gigabyte      | 945GM-S2                    | [49cddeaaea](https://linux-hardware.org/?probe=49cddeaaea) | Oct 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f289b8e738](https://linux-hardware.org/?probe=f289b8e738) | Oct 03, 2023 |
| Dell          | 0NK5PH A00                  | [acf4a7170d](https://linux-hardware.org/?probe=acf4a7170d) | Oct 03, 2023 |
| Pegatron      | 2AC2                        | [847357e51f](https://linux-hardware.org/?probe=847357e51f) | Oct 03, 2023 |
| Intel         | H61                         | [977f3d58ab](https://linux-hardware.org/?probe=977f3d58ab) | Oct 03, 2023 |
| Medion        | MS-7713                     | [511fe2eef1](https://linux-hardware.org/?probe=511fe2eef1) | Oct 02, 2023 |
| HP            | 3397                        | [d147b43cb6](https://linux-hardware.org/?probe=d147b43cb6) | Oct 02, 2023 |
| Gigabyte      | H77M-D3H                    | [1d1c00db51](https://linux-hardware.org/?probe=1d1c00db51) | Oct 02, 2023 |
| Dell          | 0WMJ54 A01                  | [479028c9e5](https://linux-hardware.org/?probe=479028c9e5) | Oct 02, 2023 |
| ASUSTek       | P5K-V                       | [899f52c343](https://linux-hardware.org/?probe=899f52c343) | Oct 02, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7a0bb156df](https://linux-hardware.org/?probe=7a0bb156df) | Oct 02, 2023 |
| Dell          | 0J3C2F A00                  | [b08d3ee33c](https://linux-hardware.org/?probe=b08d3ee33c) | Oct 02, 2023 |
| Dell          | 0Y2K8N A01                  | [21d6bfc066](https://linux-hardware.org/?probe=21d6bfc066) | Oct 02, 2023 |
| ASUSTek       | A88XM-A/USB                 | [5a154d10af](https://linux-hardware.org/?probe=5a154d10af) | Oct 01, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [4869929ae9](https://linux-hardware.org/?probe=4869929ae9) | Oct 01, 2023 |
| ASRock        | H61M-DGS R2.0               | [44eaf9c58d](https://linux-hardware.org/?probe=44eaf9c58d) | Oct 01, 2023 |
| ASUSTek       | A55BM-K                     | [532e0b0654](https://linux-hardware.org/?probe=532e0b0654) | Sep 30, 2023 |
| ASRock        | B75 Pro3-M                  | [05c68ef556](https://linux-hardware.org/?probe=05c68ef556) | Sep 30, 2023 |
| ASRock        | H61M-DGS R2.0               | [6074f655ad](https://linux-hardware.org/?probe=6074f655ad) | Sep 30, 2023 |
| ASUSTek       | P8H77-M PRO                 | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| Unknown       | Phitronics N68C-M           | [72b5c903d3](https://linux-hardware.org/?probe=72b5c903d3) | Sep 30, 2023 |
| ASUSTek       | P5B                         | [cb521fc290](https://linux-hardware.org/?probe=cb521fc290) | Sep 29, 2023 |
| Dell          | 0Y2K8N A01                  | [46ac9f9904](https://linux-hardware.org/?probe=46ac9f9904) | Sep 29, 2023 |
| Intel         | D33217CK G76541-302         | [d1aab6a8d0](https://linux-hardware.org/?probe=d1aab6a8d0) | Sep 29, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f79a27e406](https://linux-hardware.org/?probe=f79a27e406) | Sep 29, 2023 |
| MSI           | MAG B550M MORTAR            | [ed0e5eee5a](https://linux-hardware.org/?probe=ed0e5eee5a) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a40dc4964e](https://linux-hardware.org/?probe=a40dc4964e) | Sep 28, 2023 |
| Biostar       | B450MH                      | [e932e22b99](https://linux-hardware.org/?probe=e932e22b99) | Sep 28, 2023 |
| HP            | 843C                        | [4af4a9e798](https://linux-hardware.org/?probe=4af4a9e798) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1f3c152dc3](https://linux-hardware.org/?probe=1f3c152dc3) | Sep 28, 2023 |
| Gigabyte      | F2A88X-D3H                  | [13e1dcb2be](https://linux-hardware.org/?probe=13e1dcb2be) | Sep 28, 2023 |
| HP            | 8265                        | [2ae07c2008](https://linux-hardware.org/?probe=2ae07c2008) | Sep 28, 2023 |
| Intel         | X99H                        | [d5390cf599](https://linux-hardware.org/?probe=d5390cf599) | Sep 28, 2023 |
| Positivo      | POS-RIH470EM 11179450       | [cf8e3e73bb](https://linux-hardware.org/?probe=cf8e3e73bb) | Sep 27, 2023 |
| HP            | 2ADE                        | [b701a5c589](https://linux-hardware.org/?probe=b701a5c589) | Sep 27, 2023 |
| HP            | 3398                        | [fed07fc26f](https://linux-hardware.org/?probe=fed07fc26f) | Sep 27, 2023 |
| HP            | 3398                        | [5f4cd7d05b](https://linux-hardware.org/?probe=5f4cd7d05b) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | [d656cacdd8](https://linux-hardware.org/?probe=d656cacdd8) | Sep 26, 2023 |
| AZW           | Green G2                    | [cb9b97f24b](https://linux-hardware.org/?probe=cb9b97f24b) | Sep 26, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [def181c0e4](https://linux-hardware.org/?probe=def181c0e4) | Sep 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | [d94b85c889](https://linux-hardware.org/?probe=d94b85c889) | Sep 26, 2023 |
| ASRock        | H61M-DGS R2.0               | [5ace4ce0ad](https://linux-hardware.org/?probe=5ace4ce0ad) | Sep 26, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3e59f9341a](https://linux-hardware.org/?probe=3e59f9341a) | Sep 26, 2023 |
| ASRock        | H61M-HVS                    | [44c939ded2](https://linux-hardware.org/?probe=44c939ded2) | Sep 26, 2023 |
| ASRock        | H61M-HVS                    | [79309ad820](https://linux-hardware.org/?probe=79309ad820) | Sep 26, 2023 |
| BESSTAR Te... | UM700                       | [efd53d662d](https://linux-hardware.org/?probe=efd53d662d) | Sep 25, 2023 |
| ASUSTek       | P7P55D LE                   | [f47493454f](https://linux-hardware.org/?probe=f47493454f) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [e7a6f47b2f](https://linux-hardware.org/?probe=e7a6f47b2f) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [8b10c3ad64](https://linux-hardware.org/?probe=8b10c3ad64) | Sep 25, 2023 |
| HP            | 2ADE                        | [ec7d683b49](https://linux-hardware.org/?probe=ec7d683b49) | Sep 25, 2023 |
| Gigabyte      | H310M M.2 x.x               | [69cccf347a](https://linux-hardware.org/?probe=69cccf347a) | Sep 25, 2023 |
| HP            | 0B4Ch D                     | [8aeccd1d55](https://linux-hardware.org/?probe=8aeccd1d55) | Sep 25, 2023 |
| Gigabyte      | 970A-DS3P                   | [6dc2bcb097](https://linux-hardware.org/?probe=6dc2bcb097) | Sep 25, 2023 |
| ASUSTek       | P8H77-M PRO                 | [3afc2a0804](https://linux-hardware.org/?probe=3afc2a0804) | Sep 24, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [67b0050938](https://linux-hardware.org/?probe=67b0050938) | Sep 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [da4274c691](https://linux-hardware.org/?probe=da4274c691) | Sep 24, 2023 |
| HP            | 18E7                        | [6257920a37](https://linux-hardware.org/?probe=6257920a37) | Sep 24, 2023 |
| HP            | 843B                        | [4e11e8ae1a](https://linux-hardware.org/?probe=4e11e8ae1a) | Sep 24, 2023 |
| MSI           | B550-A PRO                  | [3fce945550](https://linux-hardware.org/?probe=3fce945550) | Sep 23, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [de5a55aa7b](https://linux-hardware.org/?probe=de5a55aa7b) | Sep 23, 2023 |
| ASRock        | N68C-GS FX                  | [f1d9cc16ad](https://linux-hardware.org/?probe=f1d9cc16ad) | Sep 23, 2023 |
| HP            | 81C9                        | [12bbb1608c](https://linux-hardware.org/?probe=12bbb1608c) | Sep 23, 2023 |
| HP            | 1494                        | [bb1123c49e](https://linux-hardware.org/?probe=bb1123c49e) | Sep 23, 2023 |
| BESSTAR Te... | HM80                        | [909cdffc4d](https://linux-hardware.org/?probe=909cdffc4d) | Sep 23, 2023 |
| HP            | 2B34                        | [101780dee0](https://linux-hardware.org/?probe=101780dee0) | Sep 23, 2023 |
| MSI           | B460M PRO-VDH               | [c5429120bb](https://linux-hardware.org/?probe=c5429120bb) | Sep 23, 2023 |
| HP            | 1494                        | [0e1ff4e8d5](https://linux-hardware.org/?probe=0e1ff4e8d5) | Sep 23, 2023 |
| ASRock        | Z68 Pro3                    | [6f9b69be0e](https://linux-hardware.org/?probe=6f9b69be0e) | Sep 22, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [c545236a4c](https://linux-hardware.org/?probe=c545236a4c) | Sep 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [759b15046b](https://linux-hardware.org/?probe=759b15046b) | Sep 22, 2023 |
| ASRock        | B450 Pro4                   | [667afb7552](https://linux-hardware.org/?probe=667afb7552) | Sep 22, 2023 |
| HP            | 1998                        | [f2c4af4cb6](https://linux-hardware.org/?probe=f2c4af4cb6) | Sep 22, 2023 |
| HP            | 1998                        | [ef51f7d583](https://linux-hardware.org/?probe=ef51f7d583) | Sep 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [20d494d943](https://linux-hardware.org/?probe=20d494d943) | Sep 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [6e8c507d61](https://linux-hardware.org/?probe=6e8c507d61) | Sep 22, 2023 |
| ASUSTek       | PRIME B365M-A               | [17bbb23241](https://linux-hardware.org/?probe=17bbb23241) | Sep 22, 2023 |
| Dell          | 0Y2MRG A00                  | [c5880f7fa9](https://linux-hardware.org/?probe=c5880f7fa9) | Sep 22, 2023 |
| Gigabyte      | F2A88X-D3H                  | [106ba73af5](https://linux-hardware.org/?probe=106ba73af5) | Sep 22, 2023 |
| ASRock        | Z68 Pro3                    | [19c8215a05](https://linux-hardware.org/?probe=19c8215a05) | Sep 22, 2023 |
| ASRock        | H61M-DGS R2.0               | [96847f97e6](https://linux-hardware.org/?probe=96847f97e6) | Sep 21, 2023 |
| ASRock        | H310M-HDV                   | [0ac59e2ff6](https://linux-hardware.org/?probe=0ac59e2ff6) | Sep 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [f87766b547](https://linux-hardware.org/?probe=f87766b547) | Sep 21, 2023 |
| HP            | 0B40h                       | [b9c00a29ab](https://linux-hardware.org/?probe=b9c00a29ab) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [459e666cd3](https://linux-hardware.org/?probe=459e666cd3) | Sep 21, 2023 |
| Dell          | 08WKV3 A00                  | [55942db040](https://linux-hardware.org/?probe=55942db040) | Sep 21, 2023 |
| Unknown       | Unknown                     | [043be725eb](https://linux-hardware.org/?probe=043be725eb) | Sep 21, 2023 |
| Intel         | H55                         | [03693f8574](https://linux-hardware.org/?probe=03693f8574) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [dfb78764ea](https://linux-hardware.org/?probe=dfb78764ea) | Sep 20, 2023 |
| ASRock        | Z270 Extreme4               | [0df72a698a](https://linux-hardware.org/?probe=0df72a698a) | Sep 20, 2023 |
| Intel         | DG31PR AAD97573-205         | [a25329cfdb](https://linux-hardware.org/?probe=a25329cfdb) | Sep 20, 2023 |
| ASUSTek       | P7H55-M SI                  | [26648aff1a](https://linux-hardware.org/?probe=26648aff1a) | Sep 20, 2023 |
| Acer          | EG43M                       | [77e78183b9](https://linux-hardware.org/?probe=77e78183b9) | Sep 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [8b6f78da91](https://linux-hardware.org/?probe=8b6f78da91) | Sep 20, 2023 |
| Dell          | 00V62H A01                  | [71d11373aa](https://linux-hardware.org/?probe=71d11373aa) | Sep 20, 2023 |
| MSI           | B350M MORTAR                | [b19e745af2](https://linux-hardware.org/?probe=b19e745af2) | Sep 19, 2023 |
| wpc           | zrd616                      | [f218d73abb](https://linux-hardware.org/?probe=f218d73abb) | Sep 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c7ab5c00f8](https://linux-hardware.org/?probe=c7ab5c00f8) | Sep 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | [717867b71c](https://linux-hardware.org/?probe=717867b71c) | Sep 19, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [7273c8eb2e](https://linux-hardware.org/?probe=7273c8eb2e) | Sep 19, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [49963f0f8a](https://linux-hardware.org/?probe=49963f0f8a) | Sep 19, 2023 |
| ASRock        | 880GMH/U3S3                 | [8b16ba21ae](https://linux-hardware.org/?probe=8b16ba21ae) | Sep 19, 2023 |
| ASRock        | B450 Steel Legend           | [b294855348](https://linux-hardware.org/?probe=b294855348) | Sep 19, 2023 |
| Dell          | 06CV2N A01                  | [da4e39cb06](https://linux-hardware.org/?probe=da4e39cb06) | Sep 19, 2023 |
| ASUSTek       | P5K-E                       | [233a59e640](https://linux-hardware.org/?probe=233a59e640) | Sep 18, 2023 |
| HP            | 82F2                        | [e4fe8b67fc](https://linux-hardware.org/?probe=e4fe8b67fc) | Sep 18, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9a7a68b69f](https://linux-hardware.org/?probe=9a7a68b69f) | Sep 18, 2023 |
| Unknown       | Unknown                     | [77f967302f](https://linux-hardware.org/?probe=77f967302f) | Sep 18, 2023 |
| MSI           | PRO B550M-VC WIFI           | [53009e9a02](https://linux-hardware.org/?probe=53009e9a02) | Sep 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f6b5fab580](https://linux-hardware.org/?probe=f6b5fab580) | Sep 18, 2023 |
| Unknown       | Unknown                     | [2d2ec7d22c](https://linux-hardware.org/?probe=2d2ec7d22c) | Sep 18, 2023 |
| Alienware     | 07W25T A00                  | [8a56672ca9](https://linux-hardware.org/?probe=8a56672ca9) | Sep 18, 2023 |
| Unknown       | Unknown                     | [faa59f7ab3](https://linux-hardware.org/?probe=faa59f7ab3) | Sep 18, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | [0ac4289831](https://linux-hardware.org/?probe=0ac4289831) | Sep 18, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [4a0a0d006c](https://linux-hardware.org/?probe=4a0a0d006c) | Sep 17, 2023 |
| ASUSTek       | EB1501P                     | [70cb61d1dc](https://linux-hardware.org/?probe=70cb61d1dc) | Sep 17, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a0ba042279](https://linux-hardware.org/?probe=a0ba042279) | Sep 17, 2023 |
| Foxconn       | 2AB1                        | [d259729a06](https://linux-hardware.org/?probe=d259729a06) | Sep 16, 2023 |
| Gigabyte      | EP45T-DS3                   | [0e22b4fe1d](https://linux-hardware.org/?probe=0e22b4fe1d) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [293bc3eab9](https://linux-hardware.org/?probe=293bc3eab9) | Sep 16, 2023 |
| HP            | 0B54h D                     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| HP            | 2ADE                        | [5b1bf011de](https://linux-hardware.org/?probe=5b1bf011de) | Sep 16, 2023 |
| Dell          | 0Y56T3 A01                  | [0ecd730eca](https://linux-hardware.org/?probe=0ecd730eca) | Sep 16, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [cfa86cec4f](https://linux-hardware.org/?probe=cfa86cec4f) | Sep 15, 2023 |
| ASRock        | B450 Pro4                   | [b3d56132ec](https://linux-hardware.org/?probe=b3d56132ec) | Sep 15, 2023 |
| Dell          | 0F896N A02                  | [f893a6292d](https://linux-hardware.org/?probe=f893a6292d) | Sep 15, 2023 |
| Gigabyte      | B450 AORUS M                | [119acd8c0d](https://linux-hardware.org/?probe=119acd8c0d) | Sep 15, 2023 |
| MSI           | MAG B550M MORTAR            | [2ba464818a](https://linux-hardware.org/?probe=2ba464818a) | Sep 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [cbe7fd494b](https://linux-hardware.org/?probe=cbe7fd494b) | Sep 14, 2023 |
| ASUSTek       | M2N-E SLI                   | [21e27c3e56](https://linux-hardware.org/?probe=21e27c3e56) | Sep 14, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [9df835f343](https://linux-hardware.org/?probe=9df835f343) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| Unknown       | Unknown                     | [f3ebb86644](https://linux-hardware.org/?probe=f3ebb86644) | Sep 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [775b7ba530](https://linux-hardware.org/?probe=775b7ba530) | Sep 13, 2023 |
| ASUSTek       | Leonite2                    | [6e387e015f](https://linux-hardware.org/?probe=6e387e015f) | Sep 13, 2023 |
| Dell          | 07T4MC A06                  | [393a33da8c](https://linux-hardware.org/?probe=393a33da8c) | Sep 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [bfe7424686](https://linux-hardware.org/?probe=bfe7424686) | Sep 11, 2023 |
| HP            | 18E7                        | [a553a173be](https://linux-hardware.org/?probe=a553a173be) | Sep 11, 2023 |
| Cincoze       | DX-1000.01.001              | [561f581c95](https://linux-hardware.org/?probe=561f581c95) | Sep 11, 2023 |
| ASRock        | B450 Pro4                   | [6ced8d357d](https://linux-hardware.org/?probe=6ced8d357d) | Sep 11, 2023 |
| Intel         | DG31PR AAD97573-205         | [486d89ed3a](https://linux-hardware.org/?probe=486d89ed3a) | Sep 11, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [7f5f0fccd0](https://linux-hardware.org/?probe=7f5f0fccd0) | Sep 11, 2023 |
| HP            | 1632                        | [5f095c2346](https://linux-hardware.org/?probe=5f095c2346) | Sep 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [9b6033dd39](https://linux-hardware.org/?probe=9b6033dd39) | Sep 10, 2023 |
| MSI           | MAG B560 TORPEDO            | [5828591d02](https://linux-hardware.org/?probe=5828591d02) | Sep 10, 2023 |
| MSI           | 2A9C                        | [2416e50c09](https://linux-hardware.org/?probe=2416e50c09) | Sep 10, 2023 |
| Dell          | 07T4MC A06                  | [ec26895704](https://linux-hardware.org/?probe=ec26895704) | Sep 10, 2023 |
| Unknown       | Unknown                     | [bc06d42fa2](https://linux-hardware.org/?probe=bc06d42fa2) | Sep 10, 2023 |
| Unknown       | Unknown                     | [2f9aef143e](https://linux-hardware.org/?probe=2f9aef143e) | Sep 10, 2023 |
| ASRock        | H61M-DGS R2.0               | [7512caafc3](https://linux-hardware.org/?probe=7512caafc3) | Sep 09, 2023 |
| Gigabyte      | 990FXA-UD3                  | [8ce4063e5b](https://linux-hardware.org/?probe=8ce4063e5b) | Sep 09, 2023 |
| HP            | 18E7                        | [26c9e200d8](https://linux-hardware.org/?probe=26c9e200d8) | Sep 09, 2023 |
| ASUSTek       | PRIME B760M-K D4            | [4e97e7f757](https://linux-hardware.org/?probe=4e97e7f757) | Sep 09, 2023 |
| HP            | 802F                        | [55c261e6d1](https://linux-hardware.org/?probe=55c261e6d1) | Sep 08, 2023 |
| MSI           | B350M MORTAR                | [8a9ac77214](https://linux-hardware.org/?probe=8a9ac77214) | Sep 08, 2023 |
| MSI           | FM2-A85XMA-E35              | [ea1d2d5910](https://linux-hardware.org/?probe=ea1d2d5910) | Sep 08, 2023 |
| ASUSTek       | M4A78T-E                    | [cd885cee58](https://linux-hardware.org/?probe=cd885cee58) | Sep 08, 2023 |
| Dell          | 04Y8V0 A02                  | [aa2d2a4c29](https://linux-hardware.org/?probe=aa2d2a4c29) | Sep 08, 2023 |
| ASUSTek       | H87-PLUS                    | [9cbcec0d39](https://linux-hardware.org/?probe=9cbcec0d39) | Sep 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [81c167f9f9](https://linux-hardware.org/?probe=81c167f9f9) | Sep 08, 2023 |
| Dell          | 0F896N A02                  | [5d295c0d33](https://linux-hardware.org/?probe=5d295c0d33) | Sep 08, 2023 |
| ECS           | BSWI-D2                     | [0bf71b9f12](https://linux-hardware.org/?probe=0bf71b9f12) | Sep 08, 2023 |
| HP            | 81C9                        | [177d24b85a](https://linux-hardware.org/?probe=177d24b85a) | Sep 07, 2023 |
| Gigabyte      | 970A-DS3P                   | [e7bb031798](https://linux-hardware.org/?probe=e7bb031798) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [36a4c33de8](https://linux-hardware.org/?probe=36a4c33de8) | Sep 07, 2023 |
| Unknown       | Unknown                     | [b0fccd6eb5](https://linux-hardware.org/?probe=b0fccd6eb5) | Sep 07, 2023 |
| Gateway       | IPISB-VR                    | [4bed351eee](https://linux-hardware.org/?probe=4bed351eee) | Sep 07, 2023 |
| ASRock        | 775Dual-VSTA                | [05af667eb0](https://linux-hardware.org/?probe=05af667eb0) | Sep 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [67934ce24a](https://linux-hardware.org/?probe=67934ce24a) | Sep 07, 2023 |
| Lenovo        | NOK                         | [30f2c89249](https://linux-hardware.org/?probe=30f2c89249) | Sep 07, 2023 |
| Dell          | 0Y2MRG A00                  | [34ae665da1](https://linux-hardware.org/?probe=34ae665da1) | Sep 07, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [907edde95a](https://linux-hardware.org/?probe=907edde95a) | Sep 07, 2023 |
| HP            | 18E5                        | [b0210e782a](https://linux-hardware.org/?probe=b0210e782a) | Sep 07, 2023 |
| ASRock        | Z87 Pro4                    | [89b861e771](https://linux-hardware.org/?probe=89b861e771) | Sep 06, 2023 |
| HP            | 81B3                        | [b04c59ca3e](https://linux-hardware.org/?probe=b04c59ca3e) | Sep 06, 2023 |
| Dell          | 0HMX8D A01                  | [48fa151690](https://linux-hardware.org/?probe=48fa151690) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8d4c48dd2f](https://linux-hardware.org/?probe=8d4c48dd2f) | Sep 06, 2023 |
| HP            | 21F5                        | [af9bc6bde6](https://linux-hardware.org/?probe=af9bc6bde6) | Sep 06, 2023 |
| Biostar       | G31-M7 TE                   | [2ef74da3f9](https://linux-hardware.org/?probe=2ef74da3f9) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [21a1983dcc](https://linux-hardware.org/?probe=21a1983dcc) | Sep 06, 2023 |
| Unknown       | Unknown                     | [7fd153d869](https://linux-hardware.org/?probe=7fd153d869) | Sep 06, 2023 |
| Unknown       | Unknown                     | [6508e8eeb8](https://linux-hardware.org/?probe=6508e8eeb8) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | [69a1288adb](https://linux-hardware.org/?probe=69a1288adb) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | [f00617a2cf](https://linux-hardware.org/?probe=f00617a2cf) | Sep 06, 2023 |
| Dell          | 0Y2MRG A00                  | [ad6d3dd867](https://linux-hardware.org/?probe=ad6d3dd867) | Sep 06, 2023 |
| Gigabyte      | H410M H V3                  | [c7bdf1cee6](https://linux-hardware.org/?probe=c7bdf1cee6) | Sep 06, 2023 |
| AZW           | U59                         | [0971b3ceb2](https://linux-hardware.org/?probe=0971b3ceb2) | Sep 06, 2023 |
| Foxconn       | 2AB1                        | [bf3a43c945](https://linux-hardware.org/?probe=bf3a43c945) | Sep 06, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [7c51242294](https://linux-hardware.org/?probe=7c51242294) | Sep 06, 2023 |
| HP            | 81C9                        | [e80c7bf9d5](https://linux-hardware.org/?probe=e80c7bf9d5) | Sep 05, 2023 |
| ASUSTek       | M3N78-VM                    | [0e8a4a2220](https://linux-hardware.org/?probe=0e8a4a2220) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [4322b8da26](https://linux-hardware.org/?probe=4322b8da26) | Sep 05, 2023 |
| HP            | 1497                        | [66bc78bedb](https://linux-hardware.org/?probe=66bc78bedb) | Sep 05, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [6644f7f91e](https://linux-hardware.org/?probe=6644f7f91e) | Sep 05, 2023 |
| MSI           | P55-GD65                    | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| MSI           | PRO B760M-G DDR4            | [a8f42a3c96](https://linux-hardware.org/?probe=a8f42a3c96) | Sep 05, 2023 |
| Foxconn       | 2AB1                        | [5c43d49876](https://linux-hardware.org/?probe=5c43d49876) | Sep 05, 2023 |
| Gigabyte      | H310M H                     | [47b2450a3e](https://linux-hardware.org/?probe=47b2450a3e) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [8a98029595](https://linux-hardware.org/?probe=8a98029595) | Sep 05, 2023 |
| ASUSTek       | TALAS                       | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| Dell          | 06D7TR A02                  | [a99e7ffcb1](https://linux-hardware.org/?probe=a99e7ffcb1) | Sep 04, 2023 |
| HP            | 2ADE                        | [f7b01f93c4](https://linux-hardware.org/?probe=f7b01f93c4) | Sep 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [39c78902f1](https://linux-hardware.org/?probe=39c78902f1) | Sep 04, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [3462791aa1](https://linux-hardware.org/?probe=3462791aa1) | Sep 04, 2023 |
| Dell          | 0773VG A00                  | [426a2f4142](https://linux-hardware.org/?probe=426a2f4142) | Sep 04, 2023 |
| ASRock        | H61M-DGS R2.0               | [3edb7718df](https://linux-hardware.org/?probe=3edb7718df) | Sep 04, 2023 |
| Dell          | 0M6C7G A00                  | [8645b925c9](https://linux-hardware.org/?probe=8645b925c9) | Sep 04, 2023 |
| Hardkernel    | ODROID-H3                   | [30f66c7581](https://linux-hardware.org/?probe=30f66c7581) | Sep 04, 2023 |
| MSI           | B360M BAZOOKA               | [bdb68056ae](https://linux-hardware.org/?probe=bdb68056ae) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484AEF    | [ccffd7e998](https://linux-hardware.org/?probe=ccffd7e998) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d8b388ed5f](https://linux-hardware.org/?probe=d8b388ed5f) | Sep 03, 2023 |
| Dell          | 0VHWTR A02                  | [be2e4d0e02](https://linux-hardware.org/?probe=be2e4d0e02) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [ca5351b378](https://linux-hardware.org/?probe=ca5351b378) | Sep 03, 2023 |
| Gigabyte      | H310M H                     | [ab3739f4e8](https://linux-hardware.org/?probe=ab3739f4e8) | Sep 03, 2023 |
| Dell          | 096JG8 A01                  | [eaac06d18a](https://linux-hardware.org/?probe=eaac06d18a) | Sep 03, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [43a2fbe118](https://linux-hardware.org/?probe=43a2fbe118) | Sep 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [70f99195d8](https://linux-hardware.org/?probe=70f99195d8) | Sep 02, 2023 |
| ASUSTek       | P5P43TD                     | [f21550a5b3](https://linux-hardware.org/?probe=f21550a5b3) | Sep 02, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [48c352470d](https://linux-hardware.org/?probe=48c352470d) | Sep 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [b9765f73b1](https://linux-hardware.org/?probe=b9765f73b1) | Sep 02, 2023 |
| Hardkernel    | ODROID-H3                   | [33a04d3a73](https://linux-hardware.org/?probe=33a04d3a73) | Sep 02, 2023 |
| Positivo      | POS-EIH610EX 11189814       | [e6a9006a72](https://linux-hardware.org/?probe=e6a9006a72) | Sep 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0cfb9de0cf](https://linux-hardware.org/?probe=0cfb9de0cf) | Sep 01, 2023 |
| HP            | 3397                        | [181c80a502](https://linux-hardware.org/?probe=181c80a502) | Sep 01, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [e7a06bde4e](https://linux-hardware.org/?probe=e7a06bde4e) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | [e222369e70](https://linux-hardware.org/?probe=e222369e70) | Sep 01, 2023 |
| HP            | 339A                        | [e4423b3eb7](https://linux-hardware.org/?probe=e4423b3eb7) | Sep 01, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| MSI           | Z390-A PRO                  | [183c66be85](https://linux-hardware.org/?probe=183c66be85) | Sep 01, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [6434195348](https://linux-hardware.org/?probe=6434195348) | Sep 01, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6f84a1d68f](https://linux-hardware.org/?probe=6f84a1d68f) | Sep 01, 2023 |
| Gigabyte      | X570 UD                     | [17e3dd86e8](https://linux-hardware.org/?probe=17e3dd86e8) | Sep 01, 2023 |
| Foxconn       | 2AB1                        | [c140c2b911](https://linux-hardware.org/?probe=c140c2b911) | Sep 01, 2023 |
| Dell          | 0P01GV A03                  | [ef4d28f614](https://linux-hardware.org/?probe=ef4d28f614) | Aug 31, 2023 |
| MSI           | X299 SLI PLUS               | [572982299a](https://linux-hardware.org/?probe=572982299a) | Aug 31, 2023 |
| ASUSTek       | H81M-K                      | [4b7cee7673](https://linux-hardware.org/?probe=4b7cee7673) | Aug 31, 2023 |
| MSI           | B360M BAZOOKA               | [7d7d03eb25](https://linux-hardware.org/?probe=7d7d03eb25) | Aug 31, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [0464aa909a](https://linux-hardware.org/?probe=0464aa909a) | Aug 31, 2023 |
| HP            | 843B                        | [472228092a](https://linux-hardware.org/?probe=472228092a) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | [408707e9e6](https://linux-hardware.org/?probe=408707e9e6) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | [b00577f6ea](https://linux-hardware.org/?probe=b00577f6ea) | Aug 31, 2023 |
| Dell          | 08WKV3 A00                  | [31138e2c0a](https://linux-hardware.org/?probe=31138e2c0a) | Aug 31, 2023 |
| ASUSTek       | P6T6 WS REVOLUTION          | [cff4daa814](https://linux-hardware.org/?probe=cff4daa814) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [c5469a2eaf](https://linux-hardware.org/?probe=c5469a2eaf) | Aug 30, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [3aefc3000a](https://linux-hardware.org/?probe=3aefc3000a) | Aug 30, 2023 |
| MSI           | H510M-A PRO                 | [afb724c8da](https://linux-hardware.org/?probe=afb724c8da) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | [3240f39404](https://linux-hardware.org/?probe=3240f39404) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | [14fce9ff7f](https://linux-hardware.org/?probe=14fce9ff7f) | Aug 30, 2023 |
| Gigabyte      | Z77-D3H                     | [b61285544c](https://linux-hardware.org/?probe=b61285544c) | Aug 30, 2023 |
| Unknown       | Unknown                     | [abdd8929db](https://linux-hardware.org/?probe=abdd8929db) | Aug 29, 2023 |
| Gigabyte      | B650M DS3H                  | [bd11422cd5](https://linux-hardware.org/?probe=bd11422cd5) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M57 6087D44     | [0b30efa677](https://linux-hardware.org/?probe=0b30efa677) | Aug 29, 2023 |
| Gigabyte      | H81M-D2V                    | [079adcbbe9](https://linux-hardware.org/?probe=079adcbbe9) | Aug 29, 2023 |
| HP            | 8953                        | [7f0a271e35](https://linux-hardware.org/?probe=7f0a271e35) | Aug 29, 2023 |
| Dell          | 0JCTF8 A00                  | [c76c74b017](https://linux-hardware.org/?probe=c76c74b017) | Aug 29, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [183437f6de](https://linux-hardware.org/?probe=183437f6de) | Aug 29, 2023 |
| ASUSTek       | A68HM-PLUS                  | [599a95cff7](https://linux-hardware.org/?probe=599a95cff7) | Aug 29, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [0af7d6ee0b](https://linux-hardware.org/?probe=0af7d6ee0b) | Aug 28, 2023 |
| MSI           | H310M PRO-VD                | [ebcf95d8ae](https://linux-hardware.org/?probe=ebcf95d8ae) | Aug 28, 2023 |
| MSI           | H310M PRO-VD                | [ef8ecfcb2e](https://linux-hardware.org/?probe=ef8ecfcb2e) | Aug 28, 2023 |
| Gigabyte      | EX58-UD5                    | [8c1bc17ecf](https://linux-hardware.org/?probe=8c1bc17ecf) | Aug 28, 2023 |
| ASUSTek       | P5Q                         | [8b814da79a](https://linux-hardware.org/?probe=8b814da79a) | Aug 28, 2023 |
| Dell          | 0TTDMJ A00                  | [3dc47e2b77](https://linux-hardware.org/?probe=3dc47e2b77) | Aug 28, 2023 |
| HP            | 1791                        | [09c2abafde](https://linux-hardware.org/?probe=09c2abafde) | Aug 28, 2023 |
| Dell          | 0J3C2F A02                  | [fcc6b1f4f5](https://linux-hardware.org/?probe=fcc6b1f4f5) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | [8ed8031a41](https://linux-hardware.org/?probe=8ed8031a41) | Aug 28, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [60fddabe34](https://linux-hardware.org/?probe=60fddabe34) | Aug 28, 2023 |
| HP            | 0AACh                       | [3522f0be02](https://linux-hardware.org/?probe=3522f0be02) | Aug 28, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [cbf222bbf8](https://linux-hardware.org/?probe=cbf222bbf8) | Aug 28, 2023 |
| Gateway       | RS780                       | [aecf72fc15](https://linux-hardware.org/?probe=aecf72fc15) | Aug 27, 2023 |
| ASRock        | B450M-HDV                   | [3d2effa8c5](https://linux-hardware.org/?probe=3d2effa8c5) | Aug 27, 2023 |
| HP            | 21D0                        | [c6cd8d13bc](https://linux-hardware.org/?probe=c6cd8d13bc) | Aug 27, 2023 |
| Gigabyte      | B75M-D3H                    | [215ff35620](https://linux-hardware.org/?probe=215ff35620) | Aug 27, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [a27df9649c](https://linux-hardware.org/?probe=a27df9649c) | Aug 27, 2023 |
| Dell          | 03NVJ6 A01                  | [00a28522c2](https://linux-hardware.org/?probe=00a28522c2) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | [033aa63d16](https://linux-hardware.org/?probe=033aa63d16) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | [e5600a4d2f](https://linux-hardware.org/?probe=e5600a4d2f) | Aug 27, 2023 |
| HP            | 1905                        | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| Dell          | 0782GW A00                  | [038c293f3b](https://linux-hardware.org/?probe=038c293f3b) | Aug 26, 2023 |
| Dell          | 0782GW A00                  | [4b8fa7c22e](https://linux-hardware.org/?probe=4b8fa7c22e) | Aug 26, 2023 |
| HP            | 3397                        | [59d80acf6f](https://linux-hardware.org/?probe=59d80acf6f) | Aug 26, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [6f81752b36](https://linux-hardware.org/?probe=6f81752b36) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c859974eed](https://linux-hardware.org/?probe=c859974eed) | Aug 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a29a9ddeb6](https://linux-hardware.org/?probe=a29a9ddeb6) | Aug 26, 2023 |
| Fujitsu Si... | MS-7275-VB                  | [2b7a6dab27](https://linux-hardware.org/?probe=2b7a6dab27) | Aug 26, 2023 |
| MSI           | MAG B550 TORPEDO            | [01062889f6](https://linux-hardware.org/?probe=01062889f6) | Aug 26, 2023 |
| HP            | 1589                        | [3c19bc74f7](https://linux-hardware.org/?probe=3c19bc74f7) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [b031f8f693](https://linux-hardware.org/?probe=b031f8f693) | Aug 25, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [fc8e4dd4ff](https://linux-hardware.org/?probe=fc8e4dd4ff) | Aug 25, 2023 |
| Fujitsu Si... | MS-7275-VB                  | [2a67da7ab4](https://linux-hardware.org/?probe=2a67da7ab4) | Aug 25, 2023 |
| Dell          | 0T656F A01                  | [fe9ddfe6d0](https://linux-hardware.org/?probe=fe9ddfe6d0) | Aug 25, 2023 |
| Gigabyte      | Z68MX-UD2H-B3               | [93cce7551b](https://linux-hardware.org/?probe=93cce7551b) | Aug 25, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [43686cdaa0](https://linux-hardware.org/?probe=43686cdaa0) | Aug 25, 2023 |
| ASRock        | 775Dual-VSTA                | [8d36dd0fbb](https://linux-hardware.org/?probe=8d36dd0fbb) | Aug 25, 2023 |
| Unknown       | HX90                        | [305cd9a7ed](https://linux-hardware.org/?probe=305cd9a7ed) | Aug 25, 2023 |
| ASUSTek       | M11AD                       | [a107c7eb20](https://linux-hardware.org/?probe=a107c7eb20) | Aug 25, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [a36ead7d8d](https://linux-hardware.org/?probe=a36ead7d8d) | Aug 25, 2023 |
| HP            | 3047h                       | [d5b03c1a66](https://linux-hardware.org/?probe=d5b03c1a66) | Aug 24, 2023 |
| Dell          | 0M017G A00                  | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [6788c79a8b](https://linux-hardware.org/?probe=6788c79a8b) | Aug 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [b490084efc](https://linux-hardware.org/?probe=b490084efc) | Aug 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [e75a175580](https://linux-hardware.org/?probe=e75a175580) | Aug 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [ff1bdfd1e3](https://linux-hardware.org/?probe=ff1bdfd1e3) | Aug 24, 2023 |
| ASUSTek       | B85M-G                      | [5f108773ec](https://linux-hardware.org/?probe=5f108773ec) | Aug 24, 2023 |
| MSI           | PRO B660-A DDR4             | [8cab090504](https://linux-hardware.org/?probe=8cab090504) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c15e2ed529](https://linux-hardware.org/?probe=c15e2ed529) | Aug 24, 2023 |
| MSI           | MAG Z390M MORTAR            | [91de6baf4d](https://linux-hardware.org/?probe=91de6baf4d) | Aug 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [fae1a274d9](https://linux-hardware.org/?probe=fae1a274d9) | Aug 23, 2023 |
| Gigabyte      | M68M-S2P                    | [25729bd4f8](https://linux-hardware.org/?probe=25729bd4f8) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [210fe127bf](https://linux-hardware.org/?probe=210fe127bf) | Aug 23, 2023 |
| Dell          | 0F896N A02                  | [3c1e848d33](https://linux-hardware.org/?probe=3c1e848d33) | Aug 23, 2023 |
| HP            | 212B                        | [a186c2ccf3](https://linux-hardware.org/?probe=a186c2ccf3) | Aug 23, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [62ac8a7715](https://linux-hardware.org/?probe=62ac8a7715) | Aug 23, 2023 |
| Gigabyte      | B450 AORUS M                | [38849e44bb](https://linux-hardware.org/?probe=38849e44bb) | Aug 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [d094cbc19c](https://linux-hardware.org/?probe=d094cbc19c) | Aug 23, 2023 |
| ASUSTek       | PRIME B550M-A               | [df5037fab5](https://linux-hardware.org/?probe=df5037fab5) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [443006ec08](https://linux-hardware.org/?probe=443006ec08) | Aug 22, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [b4aa1b8daa](https://linux-hardware.org/?probe=b4aa1b8daa) | Aug 22, 2023 |
| MSI           | B450-A PRO MAX              | [352d5c780f](https://linux-hardware.org/?probe=352d5c780f) | Aug 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [156c7f4eae](https://linux-hardware.org/?probe=156c7f4eae) | Aug 21, 2023 |
| MSI           | B450-A PRO MAX              | [c0e3693248](https://linux-hardware.org/?probe=c0e3693248) | Aug 21, 2023 |
| ASRock        | H61M-HVGS                   | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| HP            | 8054                        | [d5582dbf37](https://linux-hardware.org/?probe=d5582dbf37) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | [88f3fb7f10](https://linux-hardware.org/?probe=88f3fb7f10) | Aug 20, 2023 |
| Gigabyte      | G41M-ES2L                   | [a38d849208](https://linux-hardware.org/?probe=a38d849208) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [04efd4ddec](https://linux-hardware.org/?probe=04efd4ddec) | Aug 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [b2e1bdd7a8](https://linux-hardware.org/?probe=b2e1bdd7a8) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | [3bed885307](https://linux-hardware.org/?probe=3bed885307) | Aug 20, 2023 |
| HP            | 18E4                        | [e7d94d93c6](https://linux-hardware.org/?probe=e7d94d93c6) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3803f61627](https://linux-hardware.org/?probe=3803f61627) | Aug 20, 2023 |
| Unknown       | Unknown                     | [4bd818cb75](https://linux-hardware.org/?probe=4bd818cb75) | Aug 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [86f9b36e03](https://linux-hardware.org/?probe=86f9b36e03) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | [774ca523db](https://linux-hardware.org/?probe=774ca523db) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [a5af576c52](https://linux-hardware.org/?probe=a5af576c52) | Aug 19, 2023 |
| Dell          | 0200DY A02                  | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [676140f030](https://linux-hardware.org/?probe=676140f030) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [825225e1c4](https://linux-hardware.org/?probe=825225e1c4) | Aug 19, 2023 |
| Dell          | 0M017G A00                  | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | [31c15ac9dd](https://linux-hardware.org/?probe=31c15ac9dd) | Aug 18, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [6947635a16](https://linux-hardware.org/?probe=6947635a16) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | [73867661a3](https://linux-hardware.org/?probe=73867661a3) | Aug 18, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e9b5fbc6ba](https://linux-hardware.org/?probe=e9b5fbc6ba) | Aug 18, 2023 |
| Biostar       | A68MHE                      | [9295c879b8](https://linux-hardware.org/?probe=9295c879b8) | Aug 18, 2023 |
| Gigabyte      | F2A68HM-H                   | [82923ee337](https://linux-hardware.org/?probe=82923ee337) | Aug 18, 2023 |
| HP            | 0B40h                       | [27ee0e32c4](https://linux-hardware.org/?probe=27ee0e32c4) | Aug 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [4368fbfada](https://linux-hardware.org/?probe=4368fbfada) | Aug 17, 2023 |
| ASRock        | B450 Steel Legend           | [6c31be997f](https://linux-hardware.org/?probe=6c31be997f) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | [93f7041d2f](https://linux-hardware.org/?probe=93f7041d2f) | Aug 17, 2023 |
| Lenovo        | 0B98401 PRO                 | [58afba6baf](https://linux-hardware.org/?probe=58afba6baf) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [db86583c86](https://linux-hardware.org/?probe=db86583c86) | Aug 17, 2023 |
| HP            | 2B43                        | [2c3ffc174e](https://linux-hardware.org/?probe=2c3ffc174e) | Aug 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | [3135a88431](https://linux-hardware.org/?probe=3135a88431) | Aug 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [f2209034c0](https://linux-hardware.org/?probe=f2209034c0) | Aug 16, 2023 |
| ASUSTek       | PRIME B360M-D               | [cf1c4e8c82](https://linux-hardware.org/?probe=cf1c4e8c82) | Aug 16, 2023 |
| ASRock        | H61M-DGS R2.0               | [ccd21d7858](https://linux-hardware.org/?probe=ccd21d7858) | Aug 16, 2023 |
| HP            | 1998                        | [b44d5aaf94](https://linux-hardware.org/?probe=b44d5aaf94) | Aug 16, 2023 |
| Dell          | 0WR7PY A02                  | [bc22beda8a](https://linux-hardware.org/?probe=bc22beda8a) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [6738589baa](https://linux-hardware.org/?probe=6738589baa) | Aug 16, 2023 |
| Gigabyte      | F2A88X-D3H                  | [0b6b39fa2d](https://linux-hardware.org/?probe=0b6b39fa2d) | Aug 16, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [0daae7dcb4](https://linux-hardware.org/?probe=0daae7dcb4) | Aug 16, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [c3b704f3f0](https://linux-hardware.org/?probe=c3b704f3f0) | Aug 16, 2023 |
| HP            | 8054                        | [7a1fbf5ac4](https://linux-hardware.org/?probe=7a1fbf5ac4) | Aug 16, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [016846c4b8](https://linux-hardware.org/?probe=016846c4b8) | Aug 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [6aa6913c91](https://linux-hardware.org/?probe=6aa6913c91) | Aug 16, 2023 |
| ASUSTek       | Leonite2                    | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Gigabyte      | X99-Designare EX-CF         | [41452cd53d](https://linux-hardware.org/?probe=41452cd53d) | Aug 15, 2023 |
| MSI           | 970A-G46                    | [d1b6347c9a](https://linux-hardware.org/?probe=d1b6347c9a) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [32a347b989](https://linux-hardware.org/?probe=32a347b989) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [26a0de5b36](https://linux-hardware.org/?probe=26a0de5b36) | Aug 15, 2023 |
| ASUSTek       | PRIME B250M-K               | [e54e05ccb1](https://linux-hardware.org/?probe=e54e05ccb1) | Aug 15, 2023 |
| Gigabyte      | X570 UD                     | [290298fd99](https://linux-hardware.org/?probe=290298fd99) | Aug 15, 2023 |
| Dell          | 0J3C2F A02                  | [3fdd81216b](https://linux-hardware.org/?probe=3fdd81216b) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [daed613536](https://linux-hardware.org/?probe=daed613536) | Aug 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [bf753b0310](https://linux-hardware.org/?probe=bf753b0310) | Aug 14, 2023 |
| ASUSTek       | H110T                       | [48d641f85c](https://linux-hardware.org/?probe=48d641f85c) | Aug 14, 2023 |
| MSI           | MS-B1831                    | [25e33380e5](https://linux-hardware.org/?probe=25e33380e5) | Aug 14, 2023 |
| Gigabyte      | P55A-UD3                    | [b950177908](https://linux-hardware.org/?probe=b950177908) | Aug 14, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [a8f732a826](https://linux-hardware.org/?probe=a8f732a826) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0be611b499](https://linux-hardware.org/?probe=0be611b499) | Aug 14, 2023 |
| HP            | 225E                        | [293a079528](https://linux-hardware.org/?probe=293a079528) | Aug 14, 2023 |
| HP            | 225E                        | [0a353f94ec](https://linux-hardware.org/?probe=0a353f94ec) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c342e06960](https://linux-hardware.org/?probe=c342e06960) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | [fd4109923b](https://linux-hardware.org/?probe=fd4109923b) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | [c2d8da14dd](https://linux-hardware.org/?probe=c2d8da14dd) | Aug 14, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | [b6e0b821b8](https://linux-hardware.org/?probe=b6e0b821b8) | Aug 14, 2023 |
| Gigabyte      | B550M DS3H                  | [aadb9e5aab](https://linux-hardware.org/?probe=aadb9e5aab) | Aug 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [7decc8ad48](https://linux-hardware.org/?probe=7decc8ad48) | Aug 13, 2023 |
| ASRock        | H81M-VG4 R2.0               | [498a7e3ab4](https://linux-hardware.org/?probe=498a7e3ab4) | Aug 13, 2023 |
| Gigabyte      | B450 GAMING X               | [d6cfe894c9](https://linux-hardware.org/?probe=d6cfe894c9) | Aug 13, 2023 |
| Intel         | H61                         | [0f81745861](https://linux-hardware.org/?probe=0f81745861) | Aug 13, 2023 |
| ASUSTek       | H170I-PRO                   | [c88cafa2a4](https://linux-hardware.org/?probe=c88cafa2a4) | Aug 13, 2023 |
| Intel         | H61                         | [cbf83ef64b](https://linux-hardware.org/?probe=cbf83ef64b) | Aug 13, 2023 |
| Foxconn       | 2AB1                        | [fdff550fcd](https://linux-hardware.org/?probe=fdff550fcd) | Aug 13, 2023 |
| ASUSTek       | GRYPHON Z87                 | [df9fab1b5b](https://linux-hardware.org/?probe=df9fab1b5b) | Aug 13, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [eedc2f2406](https://linux-hardware.org/?probe=eedc2f2406) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [5f03e49c03](https://linux-hardware.org/?probe=5f03e49c03) | Aug 13, 2023 |
| BESSTAR Te... | TH50                        | [dd2c1243af](https://linux-hardware.org/?probe=dd2c1243af) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | [6af1365446](https://linux-hardware.org/?probe=6af1365446) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | [70e9fe8cdb](https://linux-hardware.org/?probe=70e9fe8cdb) | Aug 12, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [8ba1a47cc3](https://linux-hardware.org/?probe=8ba1a47cc3) | Aug 12, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [adb95a05c5](https://linux-hardware.org/?probe=adb95a05c5) | Aug 12, 2023 |
| HP            | ProLiant ML350 G5           | [e9e8c3e5a7](https://linux-hardware.org/?probe=e9e8c3e5a7) | Aug 12, 2023 |
| Gigabyte      | B450 AORUS M                | [f4a323eb82](https://linux-hardware.org/?probe=f4a323eb82) | Aug 11, 2023 |
| Dell          | 0KV3RP A00                  | [47c45a45e5](https://linux-hardware.org/?probe=47c45a45e5) | Aug 11, 2023 |
| Gigabyte      | A520M DS3H AC               | [c53eeb4caf](https://linux-hardware.org/?probe=c53eeb4caf) | Aug 11, 2023 |
| HP            | 339A                        | [2ecbd957da](https://linux-hardware.org/?probe=2ecbd957da) | Aug 11, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [a1c6469145](https://linux-hardware.org/?probe=a1c6469145) | Aug 11, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [f711709f3f](https://linux-hardware.org/?probe=f711709f3f) | Aug 11, 2023 |
| MSI           | H310M PRO-VD                | [f542bb8447](https://linux-hardware.org/?probe=f542bb8447) | Aug 10, 2023 |
| ASUSTek       | P8Z68-V                     | [cff11cda6f](https://linux-hardware.org/?probe=cff11cda6f) | Aug 10, 2023 |
| MSI           | B450M PRO-M2 MAX            | [07e0bad7da](https://linux-hardware.org/?probe=07e0bad7da) | Aug 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [67414922e3](https://linux-hardware.org/?probe=67414922e3) | Aug 10, 2023 |
| ASRock        | H61M-DGS R2.0               | [4f05b77547](https://linux-hardware.org/?probe=4f05b77547) | Aug 10, 2023 |
| Gigabyte      | B365M H                     | [b23c1e6e73](https://linux-hardware.org/?probe=b23c1e6e73) | Aug 10, 2023 |
| AMI           | T3 MRD                      | [7a77a54bfd](https://linux-hardware.org/?probe=7a77a54bfd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [0638b1c2dd](https://linux-hardware.org/?probe=0638b1c2dd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [ff98e5f807](https://linux-hardware.org/?probe=ff98e5f807) | Aug 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [1e856f651d](https://linux-hardware.org/?probe=1e856f651d) | Aug 09, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e315608a65](https://linux-hardware.org/?probe=e315608a65) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [aadaab77db](https://linux-hardware.org/?probe=aadaab77db) | Aug 09, 2023 |
| MSI           | Z97-G43                     | [b6edd8931f](https://linux-hardware.org/?probe=b6edd8931f) | Aug 09, 2023 |
| MSI           | B350 GAMING PLUS            | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | [9326dd9736](https://linux-hardware.org/?probe=9326dd9736) | Aug 09, 2023 |
| ASUSTek       | P8H67-M LX                  | [62d3166469](https://linux-hardware.org/?probe=62d3166469) | Aug 09, 2023 |
| Gigabyte      | F2A88X-D3H                  | [7b0c19a9a2](https://linux-hardware.org/?probe=7b0c19a9a2) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0b1144add1](https://linux-hardware.org/?probe=0b1144add1) | Aug 09, 2023 |
| Gigabyte      | F2A88X-D3H                  | [f0d580edb4](https://linux-hardware.org/?probe=f0d580edb4) | Aug 09, 2023 |
| Biostar       | X370GT3                     | [6c4e484a34](https://linux-hardware.org/?probe=6c4e484a34) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [dace48c9ec](https://linux-hardware.org/?probe=dace48c9ec) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [e4c0e430b2](https://linux-hardware.org/?probe=e4c0e430b2) | Aug 09, 2023 |
| Gigabyte      | B85M-DS3H                   | [950bc73be5](https://linux-hardware.org/?probe=950bc73be5) | Aug 09, 2023 |
| Itautec       | ST 4273 ST-4273 Custom 0... | [2e2f861c7c](https://linux-hardware.org/?probe=2e2f861c7c) | Aug 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [691838cd8c](https://linux-hardware.org/?probe=691838cd8c) | Aug 09, 2023 |
| ASRock        | H61M-HVGS                   | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| MSI           | MAG B550M MORTAR            | [6c50235cbc](https://linux-hardware.org/?probe=6c50235cbc) | Aug 08, 2023 |
| MSI           | Z270 PC MATE                | [aa107173a1](https://linux-hardware.org/?probe=aa107173a1) | Aug 08, 2023 |
| ASUSTek       | P5G41T-M                    | [9eccce625b](https://linux-hardware.org/?probe=9eccce625b) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [1ad6abed83](https://linux-hardware.org/?probe=1ad6abed83) | Aug 08, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [a79335e604](https://linux-hardware.org/?probe=a79335e604) | Aug 07, 2023 |
| ASRock        | Z97 Extreme4                | [27c70b528b](https://linux-hardware.org/?probe=27c70b528b) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e703e9ae63](https://linux-hardware.org/?probe=e703e9ae63) | Aug 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ef73e2e520](https://linux-hardware.org/?probe=ef73e2e520) | Aug 07, 2023 |
| MSI           | A520M-A PRO                 | [009a1819fa](https://linux-hardware.org/?probe=009a1819fa) | Aug 07, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| HP            | 3397                        | [3cf9a90333](https://linux-hardware.org/?probe=3cf9a90333) | Aug 07, 2023 |
| HP            | 212B                        | [b7de4a2b0a](https://linux-hardware.org/?probe=b7de4a2b0a) | Aug 07, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | [db512d60d0](https://linux-hardware.org/?probe=db512d60d0) | Aug 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [31c3da5150](https://linux-hardware.org/?probe=31c3da5150) | Aug 07, 2023 |
| Unknown       | Unknown                     | [e2427beca2](https://linux-hardware.org/?probe=e2427beca2) | Aug 07, 2023 |
| Dell          | 0NW6H5 A00                  | [f8511d64fc](https://linux-hardware.org/?probe=f8511d64fc) | Aug 07, 2023 |
| MSI           | 970A-G43                    | [68384da884](https://linux-hardware.org/?probe=68384da884) | Aug 06, 2023 |
| Gigabyte      | EP35-DS4                    | [761d545a1e](https://linux-hardware.org/?probe=761d545a1e) | Aug 06, 2023 |
| ASRock        | H61M-DGS R2.0               | [032b99ac4f](https://linux-hardware.org/?probe=032b99ac4f) | Aug 06, 2023 |
| Gigabyte      | B450M GAMING                | [570d622bb5](https://linux-hardware.org/?probe=570d622bb5) | Aug 06, 2023 |
| Lenovo        | ThinkCentre M57 6072BJU     | [9c0231c0f3](https://linux-hardware.org/?probe=9c0231c0f3) | Aug 06, 2023 |
| Gigabyte      | H81M-S2H                    | [247f361473](https://linux-hardware.org/?probe=247f361473) | Aug 06, 2023 |
| MSI           | Z490-A PRO                  | [151339db32](https://linux-hardware.org/?probe=151339db32) | Aug 06, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | [4a97a86dd8](https://linux-hardware.org/?probe=4a97a86dd8) | Aug 06, 2023 |
| Gigabyte      | Z590 GAMING X               | [a8c865c9bb](https://linux-hardware.org/?probe=a8c865c9bb) | Aug 06, 2023 |
| ASUSTek       | Z87-PRO                     | [9d39447e43](https://linux-hardware.org/?probe=9d39447e43) | Aug 05, 2023 |
| HP            | 1588h                       | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| MSI           | Z490-A PRO                  | [0698c83c6e](https://linux-hardware.org/?probe=0698c83c6e) | Aug 05, 2023 |
| MSI           | PRO B550M-VC WIFI           | [f1727289ea](https://linux-hardware.org/?probe=f1727289ea) | Aug 05, 2023 |
| Gigabyte      | Z590 GAMING X               | [231ad3947e](https://linux-hardware.org/?probe=231ad3947e) | Aug 05, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [85d2740423](https://linux-hardware.org/?probe=85d2740423) | Aug 05, 2023 |
| MSI           | A68HM GRENADE               | [a186d8863f](https://linux-hardware.org/?probe=a186d8863f) | Aug 05, 2023 |
| Dell          | 0K83V0 A00                  | [e8fbfe7be1](https://linux-hardware.org/?probe=e8fbfe7be1) | Aug 05, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [9ffeb0adcd](https://linux-hardware.org/?probe=9ffeb0adcd) | Aug 04, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [4a2c7a9f15](https://linux-hardware.org/?probe=4a2c7a9f15) | Aug 04, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [2886f9202b](https://linux-hardware.org/?probe=2886f9202b) | Aug 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [15826fe271](https://linux-hardware.org/?probe=15826fe271) | Aug 04, 2023 |
| ASRock        | 4CoreDual-SATA2             | [6495cadf19](https://linux-hardware.org/?probe=6495cadf19) | Aug 04, 2023 |
| MSI           | Z490-A PRO                  | [71e97069b6](https://linux-hardware.org/?probe=71e97069b6) | Aug 04, 2023 |
| Gigabyte      | H81M-S2H                    | [f74b524df1](https://linux-hardware.org/?probe=f74b524df1) | Aug 04, 2023 |
| ASUSTek       | P5G41T-M LX3                | [f82f03bf86](https://linux-hardware.org/?probe=f82f03bf86) | Aug 04, 2023 |
| ASUSTek       | B85-PRO GAMER               | [d4bb94e07e](https://linux-hardware.org/?probe=d4bb94e07e) | Aug 04, 2023 |
| ASRock        | Z97 Extreme4                | [4252e9a028](https://linux-hardware.org/?probe=4252e9a028) | Aug 04, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | [2b5c5c52e8](https://linux-hardware.org/?probe=2b5c5c52e8) | Aug 04, 2023 |
| ASUSTek       | H97M-E                      | [5636598221](https://linux-hardware.org/?probe=5636598221) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [f29d0b0571](https://linux-hardware.org/?probe=f29d0b0571) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [1db8a01118](https://linux-hardware.org/?probe=1db8a01118) | Aug 03, 2023 |
| OEM           | B75 Ver:1.44                | [6dcf79b752](https://linux-hardware.org/?probe=6dcf79b752) | Aug 03, 2023 |
| ASUSTek       | B85-PRO GAMER               | [e888742592](https://linux-hardware.org/?probe=e888742592) | Aug 03, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [38f7c8653b](https://linux-hardware.org/?probe=38f7c8653b) | Aug 03, 2023 |
| Gigabyte      | B450 GAMING X               | [bb292f568a](https://linux-hardware.org/?probe=bb292f568a) | Aug 03, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [04f8c42dba](https://linux-hardware.org/?probe=04f8c42dba) | Aug 02, 2023 |
| ASRock        | 775Dual-VSTA                | [7241233996](https://linux-hardware.org/?probe=7241233996) | Aug 02, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [8395f61392](https://linux-hardware.org/?probe=8395f61392) | Aug 02, 2023 |
| ASUSTek       | P5B-VM SE                   | [d5bb32f2de](https://linux-hardware.org/?probe=d5bb32f2de) | Aug 02, 2023 |
| Dell          | 0NKW6Y A01                  | [6bae407930](https://linux-hardware.org/?probe=6bae407930) | Aug 02, 2023 |
| ASUSTek       | P5B                         | [a918b28119](https://linux-hardware.org/?probe=a918b28119) | Aug 02, 2023 |
| Gigabyte      | H81M-H                      | [8c4c50cef9](https://linux-hardware.org/?probe=8c4c50cef9) | Aug 02, 2023 |
| Gateway       | DX4840                      | [7268035f51](https://linux-hardware.org/?probe=7268035f51) | Aug 01, 2023 |
| Gigabyte      | H81M-S2H                    | [0e5d30b504](https://linux-hardware.org/?probe=0e5d30b504) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [00311486d2](https://linux-hardware.org/?probe=00311486d2) | Aug 01, 2023 |
| HP            | 339A                        | [782fefbccd](https://linux-hardware.org/?probe=782fefbccd) | Aug 01, 2023 |
| Lenovo        | 3188 SDK0J40709 WIN 3259... | [59e7f97f2d](https://linux-hardware.org/?probe=59e7f97f2d) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [22e8927934](https://linux-hardware.org/?probe=22e8927934) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [046b3ffe68](https://linux-hardware.org/?probe=046b3ffe68) | Aug 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | [244a32825d](https://linux-hardware.org/?probe=244a32825d) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1090d19a71](https://linux-hardware.org/?probe=1090d19a71) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | [49e503da8e](https://linux-hardware.org/?probe=49e503da8e) | Aug 01, 2023 |
| ASRock        | 970M Pro3                   | [567efcf41e](https://linux-hardware.org/?probe=567efcf41e) | Aug 01, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [a8627dac81](https://linux-hardware.org/?probe=a8627dac81) | Aug 01, 2023 |
| Gigabyte      | F2A68HM-H                   | [08e1a2a1e1](https://linux-hardware.org/?probe=08e1a2a1e1) | Aug 01, 2023 |
| ASUSTek       | P8H67-M                     | [7bebd786bd](https://linux-hardware.org/?probe=7bebd786bd) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d58cf2a585](https://linux-hardware.org/?probe=d58cf2a585) | Jul 31, 2023 |
| Dell          | 0D8M0M A00                  | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [c7f6e64888](https://linux-hardware.org/?probe=c7f6e64888) | Jul 31, 2023 |
| System76      | Thelio Mira thelio-mira-... | [685230003a](https://linux-hardware.org/?probe=685230003a) | Jul 31, 2023 |
| ASRock        | ALiveSATA2-GLAN             | [3c4fbfa426](https://linux-hardware.org/?probe=3c4fbfa426) | Jul 31, 2023 |
| Unknown       | Phitronics N68C-M           | [0c596c95da](https://linux-hardware.org/?probe=0c596c95da) | Jul 31, 2023 |
| Intel         | DG41WV AAE90316-102         | [fa7d425224](https://linux-hardware.org/?probe=fa7d425224) | Jul 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [80ab0f5cd2](https://linux-hardware.org/?probe=80ab0f5cd2) | Jul 30, 2023 |
| Dell          | 0M863N A00                  | [3c403d83cc](https://linux-hardware.org/?probe=3c403d83cc) | Jul 30, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [63017a7eb1](https://linux-hardware.org/?probe=63017a7eb1) | Jul 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4070a9350d](https://linux-hardware.org/?probe=4070a9350d) | Jul 30, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [2c1deb7640](https://linux-hardware.org/?probe=2c1deb7640) | Jul 30, 2023 |
| ASRock        | 4CoreDual-SATA2             | [44438ab71e](https://linux-hardware.org/?probe=44438ab71e) | Jul 30, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [2ba45b1cfa](https://linux-hardware.org/?probe=2ba45b1cfa) | Jul 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [1d7b13f2e9](https://linux-hardware.org/?probe=1d7b13f2e9) | Jul 30, 2023 |
| Unknown       | GSUO H61V10C                | [9fd25cd0ba](https://linux-hardware.org/?probe=9fd25cd0ba) | Jul 29, 2023 |
| ASUSTek       | H81M-PLUS                   | [fde88e808d](https://linux-hardware.org/?probe=fde88e808d) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | [c980146db6](https://linux-hardware.org/?probe=c980146db6) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | [a9a2ac74bc](https://linux-hardware.org/?probe=a9a2ac74bc) | Jul 29, 2023 |
| ASRock        | H61M-DGS R2.0               | [9d6da42aec](https://linux-hardware.org/?probe=9d6da42aec) | Jul 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | [a294c01e5d](https://linux-hardware.org/?probe=a294c01e5d) | Jul 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [fecdf7e593](https://linux-hardware.org/?probe=fecdf7e593) | Jul 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | [8e5c19146b](https://linux-hardware.org/?probe=8e5c19146b) | Jul 29, 2023 |
| HP            | 1825                        | [7bd4e99efa](https://linux-hardware.org/?probe=7bd4e99efa) | Jul 28, 2023 |
| ASUSTek       | P5G41T-M LX3                | [356e8a0637](https://linux-hardware.org/?probe=356e8a0637) | Jul 28, 2023 |
| Digitron      | G31T-M7                     | [7b926165d9](https://linux-hardware.org/?probe=7b926165d9) | Jul 28, 2023 |
| HP            | 829D                        | [35b5c3a375](https://linux-hardware.org/?probe=35b5c3a375) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NOK                 | [ffb2276d18](https://linux-hardware.org/?probe=ffb2276d18) | Jul 28, 2023 |
| Lenovo        | No DPK                      | [c6af16725d](https://linux-hardware.org/?probe=c6af16725d) | Jul 28, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [04fcfe86e9](https://linux-hardware.org/?probe=04fcfe86e9) | Jul 27, 2023 |
| Gigabyte      | H110-D3A-CF                 | [87a06556a6](https://linux-hardware.org/?probe=87a06556a6) | Jul 27, 2023 |
| ASUSTek       | M5A78L-M LE                 | [b7c8e3ad22](https://linux-hardware.org/?probe=b7c8e3ad22) | Jul 27, 2023 |
| ASUSTek       | P8H67-M PRO                 | [a9c6664e68](https://linux-hardware.org/?probe=a9c6664e68) | Jul 27, 2023 |
| ASRock        | H61M-DGS R2.0               | [0a92529b68](https://linux-hardware.org/?probe=0a92529b68) | Jul 27, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [63e4d8c8d4](https://linux-hardware.org/?probe=63e4d8c8d4) | Jul 27, 2023 |
| ASRock        | A320M-HD                    | [26e141980a](https://linux-hardware.org/?probe=26e141980a) | Jul 27, 2023 |
| Intel         | H55                         | [83f249e836](https://linux-hardware.org/?probe=83f249e836) | Jul 27, 2023 |
| HP            | 1497                        | [370799b635](https://linux-hardware.org/?probe=370799b635) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | [ac730fa4ed](https://linux-hardware.org/?probe=ac730fa4ed) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | [57d93857f1](https://linux-hardware.org/?probe=57d93857f1) | Jul 26, 2023 |
| HP            | 806A                        | [e188cb594c](https://linux-hardware.org/?probe=e188cb594c) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [4b0210f463](https://linux-hardware.org/?probe=4b0210f463) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [5d7532050c](https://linux-hardware.org/?probe=5d7532050c) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M                    | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | [cf57b5785a](https://linux-hardware.org/?probe=cf57b5785a) | Jul 26, 2023 |
| Gigabyte      | Z77X-D3H                    | [80c9076b8b](https://linux-hardware.org/?probe=80c9076b8b) | Jul 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [865eacc7bb](https://linux-hardware.org/?probe=865eacc7bb) | Jul 25, 2023 |
| ASUSTek       | H61M-E                      | [849a99d897](https://linux-hardware.org/?probe=849a99d897) | Jul 25, 2023 |
| Unknown       | HX90                        | [ba2a06600a](https://linux-hardware.org/?probe=ba2a06600a) | Jul 25, 2023 |
| ASUSTek       | P8B75-M LE                  | [b30f6c221b](https://linux-hardware.org/?probe=b30f6c221b) | Jul 25, 2023 |
| Apple         | Mac-F221BEC8                | [8d712af013](https://linux-hardware.org/?probe=8d712af013) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| Dell          | 0X501H A00                  | [407c19b590](https://linux-hardware.org/?probe=407c19b590) | Jul 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [5be0e1a212](https://linux-hardware.org/?probe=5be0e1a212) | Jul 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [8f1677af63](https://linux-hardware.org/?probe=8f1677af63) | Jul 24, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [a3284cc458](https://linux-hardware.org/?probe=a3284cc458) | Jul 24, 2023 |
| ASRock        | B550M-C                     | [faf557738b](https://linux-hardware.org/?probe=faf557738b) | Jul 24, 2023 |
| ASRock        | B550M-C                     | [fb855f74ff](https://linux-hardware.org/?probe=fb855f74ff) | Jul 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| ASRock        | B450M Pro4                  | [73886dba95](https://linux-hardware.org/?probe=73886dba95) | Jul 24, 2023 |
| Samsung       | DeskTop System              | [c1d4c8efb2](https://linux-hardware.org/?probe=c1d4c8efb2) | Jul 24, 2023 |
| ASRock        | H61M-DGS R2.0               | [d78b20715a](https://linux-hardware.org/?probe=d78b20715a) | Jul 24, 2023 |
| MSI           | B450M-A PRO MAX             | [5d16b13584](https://linux-hardware.org/?probe=5d16b13584) | Jul 24, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [83ac887605](https://linux-hardware.org/?probe=83ac887605) | Jul 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [fc09bdf7bb](https://linux-hardware.org/?probe=fc09bdf7bb) | Jul 23, 2023 |
| Unknown       | HX90                        | [25aeb91b82](https://linux-hardware.org/?probe=25aeb91b82) | Jul 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [42d8ff9a34](https://linux-hardware.org/?probe=42d8ff9a34) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| ASUSTek       | P8B75-M LE                  | [5215522010](https://linux-hardware.org/?probe=5215522010) | Jul 23, 2023 |
| MSI           | X570-A PRO                  | [e5f595daf8](https://linux-hardware.org/?probe=e5f595daf8) | Jul 23, 2023 |
| MSI           | X570-A PRO                  | [5ab7441e06](https://linux-hardware.org/?probe=5ab7441e06) | Jul 22, 2023 |
| Gigabyte      | G33M-S2                     | [cf3b586958](https://linux-hardware.org/?probe=cf3b586958) | Jul 22, 2023 |
| Gigabyte      | G33M-S2                     | [ce4d4f4137](https://linux-hardware.org/?probe=ce4d4f4137) | Jul 22, 2023 |
| Dell          | 09KPNV A00                  | [1adb0ad898](https://linux-hardware.org/?probe=1adb0ad898) | Jul 22, 2023 |
| Gigabyte      | 990FXA-UD7                  | [3600f5bc63](https://linux-hardware.org/?probe=3600f5bc63) | Jul 22, 2023 |
| HP            | 2AA6 PVT                    | [de8572b8cf](https://linux-hardware.org/?probe=de8572b8cf) | Jul 22, 2023 |
| Dell          | 0NW6H5 A00                  | [25ab3b442b](https://linux-hardware.org/?probe=25ab3b442b) | Jul 22, 2023 |
| Lenovo        | 3111 NOK                    | [d1793854b3](https://linux-hardware.org/?probe=d1793854b3) | Jul 22, 2023 |
| ASUSTek       | Z97-A-USB31                 | [e1a7b869aa](https://linux-hardware.org/?probe=e1a7b869aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M57 6087D44     | [2bf0872f6a](https://linux-hardware.org/?probe=2bf0872f6a) | Jul 21, 2023 |
| Intel         | H61                         | [5a977f0aa9](https://linux-hardware.org/?probe=5a977f0aa9) | Jul 21, 2023 |
| Gigabyte      | F2A88X-D3H                  | [77e4930b14](https://linux-hardware.org/?probe=77e4930b14) | Jul 21, 2023 |
| Gigabyte      | PA65-UD3-B3                 | [fc4238904c](https://linux-hardware.org/?probe=fc4238904c) | Jul 21, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [16423d4124](https://linux-hardware.org/?probe=16423d4124) | Jul 21, 2023 |
| MSI           | H61M-P31/W8                 | [7313dd64c7](https://linux-hardware.org/?probe=7313dd64c7) | Jul 21, 2023 |
| Gigabyte      | 970A-DS3P                   | [566421a903](https://linux-hardware.org/?probe=566421a903) | Jul 21, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [19d3473310](https://linux-hardware.org/?probe=19d3473310) | Jul 21, 2023 |
| MSI           | Z87-G43 GAMING              | [99dadfd3f5](https://linux-hardware.org/?probe=99dadfd3f5) | Jul 21, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [6b8d5cb0c1](https://linux-hardware.org/?probe=6b8d5cb0c1) | Jul 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [97f8d99cd9](https://linux-hardware.org/?probe=97f8d99cd9) | Jul 21, 2023 |
| Gigabyte      | 970A-DS3P                   | [be9d638406](https://linux-hardware.org/?probe=be9d638406) | Jul 21, 2023 |
| Unknown       | 1.0                         | [4cb2129904](https://linux-hardware.org/?probe=4cb2129904) | Jul 21, 2023 |
| ASUSTek       | Z170-A                      | [8cc4789f9b](https://linux-hardware.org/?probe=8cc4789f9b) | Jul 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [1ee2e5b63d](https://linux-hardware.org/?probe=1ee2e5b63d) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [5bfb20e968](https://linux-hardware.org/?probe=5bfb20e968) | Jul 20, 2023 |
| Intel         | DH67BL AAG10189-209         | [8065e7b83a](https://linux-hardware.org/?probe=8065e7b83a) | Jul 20, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [83b0b1f0c2](https://linux-hardware.org/?probe=83b0b1f0c2) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [aad0018c0e](https://linux-hardware.org/?probe=aad0018c0e) | Jul 20, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [4d512121a4](https://linux-hardware.org/?probe=4d512121a4) | Jul 20, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [ceda2054b7](https://linux-hardware.org/?probe=ceda2054b7) | Jul 19, 2023 |
| HP            | 18E4                        | [4668ecbc61](https://linux-hardware.org/?probe=4668ecbc61) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [805d981913](https://linux-hardware.org/?probe=805d981913) | Jul 19, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [3da3da07e9](https://linux-hardware.org/?probe=3da3da07e9) | Jul 19, 2023 |
| Unknown       | Unknown                     | [5aebab18d6](https://linux-hardware.org/?probe=5aebab18d6) | Jul 19, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [2986780209](https://linux-hardware.org/?probe=2986780209) | Jul 19, 2023 |
| Dell          | 02YRK5 A03                  | [a1f7c7f053](https://linux-hardware.org/?probe=a1f7c7f053) | Jul 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [97c2950df7](https://linux-hardware.org/?probe=97c2950df7) | Jul 19, 2023 |
| Gigabyte      | B75-D3V                     | [ad01a23df5](https://linux-hardware.org/?probe=ad01a23df5) | Jul 19, 2023 |
| Dell          | 0FDY5C A00                  | [62a75d2633](https://linux-hardware.org/?probe=62a75d2633) | Jul 19, 2023 |
| MSI           | MAG Z590 TORPEDO            | [73bad4fbb8](https://linux-hardware.org/?probe=73bad4fbb8) | Jul 19, 2023 |
| Dell          | 0NW6H5 A00                  | [ca19ff4ba2](https://linux-hardware.org/?probe=ca19ff4ba2) | Jul 18, 2023 |
| ECS           | GeForce7050M-M              | [fc26acb7f8](https://linux-hardware.org/?probe=fc26acb7f8) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [b3d68108a2](https://linux-hardware.org/?probe=b3d68108a2) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [fbb58d4f7c](https://linux-hardware.org/?probe=fbb58d4f7c) | Jul 18, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [90a2c4e2d0](https://linux-hardware.org/?probe=90a2c4e2d0) | Jul 18, 2023 |
| ASRock        | H370M Pro4                  | [7682b57f64](https://linux-hardware.org/?probe=7682b57f64) | Jul 18, 2023 |
| Pegatron      | 2AC2                        | [ca392ce4f9](https://linux-hardware.org/?probe=ca392ce4f9) | Jul 18, 2023 |
| Gigabyte      | A520I AC                    | [6b2d9fd82f](https://linux-hardware.org/?probe=6b2d9fd82f) | Jul 18, 2023 |
| HP            | 2B18                        | [4f4a235f08](https://linux-hardware.org/?probe=4f4a235f08) | Jul 17, 2023 |
| Gigabyte      | H310M H                     | [06451fbeab](https://linux-hardware.org/?probe=06451fbeab) | Jul 17, 2023 |
| ASRock        | H170 Pro4S                  | [e1a51f73cc](https://linux-hardware.org/?probe=e1a51f73cc) | Jul 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [db1e3d03e2](https://linux-hardware.org/?probe=db1e3d03e2) | Jul 17, 2023 |
| MSI           | MEG X570S ACE MAX           | [e6141dfd65](https://linux-hardware.org/?probe=e6141dfd65) | Jul 17, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [3aae0336e1](https://linux-hardware.org/?probe=3aae0336e1) | Jul 17, 2023 |
| Samsung       | DeskTop System              | [715ff16efc](https://linux-hardware.org/?probe=715ff16efc) | Jul 17, 2023 |
| MSI           | B550-A PRO                  | [185329f8bc](https://linux-hardware.org/?probe=185329f8bc) | Jul 17, 2023 |
| Acer          | TDPS05 R3700                | [78a7951688](https://linux-hardware.org/?probe=78a7951688) | Jul 17, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [873ac7ddf1](https://linux-hardware.org/?probe=873ac7ddf1) | Jul 17, 2023 |
| MSI           | H110M GAMING                | [92d9042c75](https://linux-hardware.org/?probe=92d9042c75) | Jul 16, 2023 |
| MSI           | H110M GAMING                | [2367d795f2](https://linux-hardware.org/?probe=2367d795f2) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | [4ad55cf9da](https://linux-hardware.org/?probe=4ad55cf9da) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [21950296b4](https://linux-hardware.org/?probe=21950296b4) | Jul 16, 2023 |
| Gigabyte      | A520I AC                    | [aa37608316](https://linux-hardware.org/?probe=aa37608316) | Jul 16, 2023 |
| Dell          | 08WXMX A02                  | [7d6238272f](https://linux-hardware.org/?probe=7d6238272f) | Jul 15, 2023 |
| ASRock        | A320M-HDV R3.0              | [8e41b4b86d](https://linux-hardware.org/?probe=8e41b4b86d) | Jul 15, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [649fb482b4](https://linux-hardware.org/?probe=649fb482b4) | Jul 15, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [b84898fc8a](https://linux-hardware.org/?probe=b84898fc8a) | Jul 15, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [6758dfb731](https://linux-hardware.org/?probe=6758dfb731) | Jul 15, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e8f1a169a1](https://linux-hardware.org/?probe=e8f1a169a1) | Jul 15, 2023 |
| POWERX        | G41                         | [70a6d4e6bf](https://linux-hardware.org/?probe=70a6d4e6bf) | Jul 15, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [01550c5b66](https://linux-hardware.org/?probe=01550c5b66) | Jul 15, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2d8d666772](https://linux-hardware.org/?probe=2d8d666772) | Jul 15, 2023 |
| Intel         | JSL MRD                     | [83febcc3b7](https://linux-hardware.org/?probe=83febcc3b7) | Jul 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [2be21e12f5](https://linux-hardware.org/?probe=2be21e12f5) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [67d2492c01](https://linux-hardware.org/?probe=67d2492c01) | Jul 14, 2023 |
| Dell          | 0T656F A02                  | [9455dc5a07](https://linux-hardware.org/?probe=9455dc5a07) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [8e63dc029e](https://linux-hardware.org/?probe=8e63dc029e) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | [718dc0f09e](https://linux-hardware.org/?probe=718dc0f09e) | Jul 14, 2023 |
| Biostar       | A960D+V2                    | [2896f9267c](https://linux-hardware.org/?probe=2896f9267c) | Jul 13, 2023 |
| Lenovo        | ThinkCentre M90p 3853W1B    | [72b02c6cc1](https://linux-hardware.org/?probe=72b02c6cc1) | Jul 13, 2023 |
| Positivo      | POS-EAA75DE                 | [3307527ada](https://linux-hardware.org/?probe=3307527ada) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [74ef14c05b](https://linux-hardware.org/?probe=74ef14c05b) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [b937fd31a8](https://linux-hardware.org/?probe=b937fd31a8) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | [b575153979](https://linux-hardware.org/?probe=b575153979) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | [05e8a2652e](https://linux-hardware.org/?probe=05e8a2652e) | Jul 13, 2023 |
| Dell          | 04YP6J A03                  | [55d6cad717](https://linux-hardware.org/?probe=55d6cad717) | Jul 13, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [b2756cbab5](https://linux-hardware.org/?probe=b2756cbab5) | Jul 13, 2023 |
| MSI           | B360M PRO-VDH               | [d37d431806](https://linux-hardware.org/?probe=d37d431806) | Jul 13, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [38facb34d4](https://linux-hardware.org/?probe=38facb34d4) | Jul 12, 2023 |
| MSI           | MEG X570S ACE MAX           | [a6e0425c53](https://linux-hardware.org/?probe=a6e0425c53) | Jul 12, 2023 |
| Gigabyte      | F2A78M-D3H                  | [aaabeff261](https://linux-hardware.org/?probe=aaabeff261) | Jul 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f99bab3454](https://linux-hardware.org/?probe=f99bab3454) | Jul 12, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [f7e7c29964](https://linux-hardware.org/?probe=f7e7c29964) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | [b3770db2e8](https://linux-hardware.org/?probe=b3770db2e8) | Jul 12, 2023 |
| ASUSTek       | A88XM-E                     | [e951c1d4f4](https://linux-hardware.org/?probe=e951c1d4f4) | Jul 12, 2023 |
| ASUSTek       | PRIME B450M-A               | [8857b11281](https://linux-hardware.org/?probe=8857b11281) | Jul 11, 2023 |
| Gigabyte      | 990FXA-UD7                  | [c489c76cf6](https://linux-hardware.org/?probe=c489c76cf6) | Jul 11, 2023 |
| HP            | 806A                        | [2e3d0da353](https://linux-hardware.org/?probe=2e3d0da353) | Jul 11, 2023 |
| Unknown       | 1.0                         | [73e4a885a4](https://linux-hardware.org/?probe=73e4a885a4) | Jul 11, 2023 |
| ASUSTek       | M4A78                       | [d9adfecb80](https://linux-hardware.org/?probe=d9adfecb80) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [db34bf69af](https://linux-hardware.org/?probe=db34bf69af) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [059cda8a87](https://linux-hardware.org/?probe=059cda8a87) | Jul 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Linux Mint 20.3   | 1241     | 15.89%  |
| Linux Mint 21.1   | 1015     | 12.99%  |
| Linux Mint 20.1   | 921      | 11.79%  |
| Linux Mint 20.2   | 912      | 11.67%  |
| Linux Mint 19.3   | 870      | 11.14%  |
| Linux Mint 20     | 798      | 10.22%  |
| Linux Mint 21     | 499      | 6.39%   |
| Linux Mint 21.2   | 475      | 6.08%   |
| Linux Mint 19.1   | 404      | 5.17%   |
| Linux Mint 19.2   | 324      | 4.15%   |
| Linux Mint 19     | 154      | 1.97%   |
| Linux Mint 18.3   | 136      | 1.74%   |
| Linux Mint 18.2   | 32       | 0.41%   |
| Linux Mint 18.1   | 12       | 0.15%   |
| Linux Mint 18     | 10       | 0.13%   |
| Linux Mint 17.3   | 5        | 0.06%   |
| Linux Mint 17.1   | 2        | 0.03%   |
| Linux Mint 21.2.1 | 1        | 0.01%   |
| Linux Mint 13     | 1        | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Mint | 7157     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-91-generic  | 240      | 2.7%    |
| 5.15.0-56-generic | 226      | 2.55%   |
| 5.4.0-58-generic  | 212      | 2.39%   |
| 5.15.0-76-generic | 165      | 1.86%   |
| 5.4.0-74-generic  | 149      | 1.68%   |
| 5.4.0-42-generic  | 149      | 1.68%   |
| 5.4.0-65-generic  | 148      | 1.67%   |
| 5.15.0-58-generic | 136      | 1.53%   |
| 5.4.0-77-generic  | 132      | 1.49%   |
| 5.15.0-67-generic | 128      | 1.44%   |
| 5.15.0-60-generic | 125      | 1.41%   |
| 5.4.0-81-generic  | 115      | 1.3%    |
| 5.0.0-32-generic  | 114      | 1.28%   |
| 5.4.0-72-generic  | 113      | 1.27%   |
| 5.4.0-88-generic  | 112      | 1.26%   |
| 5.4.0-66-generic  | 112      | 1.26%   |
| 4.15.0-54-generic | 109      | 1.23%   |
| 5.4.0-90-generic  | 105      | 1.18%   |
| 5.4.0-70-generic  | 105      | 1.18%   |
| 5.4.0-122-generic | 105      | 1.18%   |
| 5.4.0-107-generic | 104      | 1.17%   |
| 5.4.0-73-generic  | 102      | 1.15%   |
| 5.15.0-78-generic | 102      | 1.15%   |
| 4.15.0-20-generic | 102      | 1.15%   |
| 5.15.0-69-generic | 99       | 1.12%   |
| 5.4.0-80-generic  | 98       | 1.1%    |
| 5.4.0-89-generic  | 91       | 1.03%   |
| 5.15.0-52-generic | 91       | 1.03%   |
| 5.15.0-71-generic | 90       | 1.01%   |
| 5.4.0-100-generic | 89       | 1%      |
| 5.4.0-26-generic  | 85       | 0.96%   |
| 5.4.0-109-generic | 80       | 0.9%    |
| 5.4.0-48-generic  | 76       | 0.86%   |
| 5.4.0-121-generic | 75       | 0.85%   |
| 5.15.0-41-generic | 73       | 0.82%   |
| 4.15.0-46-generic | 70       | 0.79%   |
| 5.15.0-72-generic | 67       | 0.76%   |
| 5.15.0-86-generic | 66       | 0.74%   |
| 5.15.0-73-generic | 66       | 0.74%   |
| 5.15.0-48-generic | 65       | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 3552     | 46.52%  |
| 5.15.0  | 1802     | 23.6%   |
| 4.15.0  | 902      | 11.81%  |
| 5.3.0   | 355      | 4.65%   |
| 5.0.0   | 192      | 2.51%   |
| 5.13.0  | 125      | 1.64%   |
| 5.8.0   | 99       | 1.3%    |
| 5.19.0  | 86       | 1.13%   |
| 6.2.0   | 74       | 0.97%   |
| 5.11.0  | 72       | 0.94%   |
| 4.4.0   | 36       | 0.47%   |
| 4.10.0  | 36       | 0.47%   |
| 4.13.0  | 26       | 0.34%   |
| 4.18.0  | 23       | 0.3%    |
| 4.8.0   | 17       | 0.22%   |
| 6.1.0   | 12       | 0.16%   |
| 5.14.0  | 12       | 0.16%   |
| 6.0.0   | 9        | 0.12%   |
| 5.17.0  | 6        | 0.08%   |
| 5.9.0   | 5        | 0.07%   |
| 5.10.0  | 5        | 0.07%   |
| 6.4.11  | 4        | 0.05%   |
| 5.3.6   | 4        | 0.05%   |
| 6.5.7   | 3        | 0.04%   |
| 6.5.0   | 3        | 0.04%   |
| 6.4.0   | 3        | 0.04%   |
| 6.3.7   | 3        | 0.04%   |
| 6.3.4   | 3        | 0.04%   |
| 6.2.12  | 3        | 0.04%   |
| 5.4.1   | 3        | 0.04%   |
| 5.16.0  | 3        | 0.04%   |
| 5.12.0  | 3        | 0.04%   |
| 5.0.9   | 3        | 0.04%   |
| 4.20.17 | 3        | 0.04%   |
| 4.11.0  | 3        | 0.04%   |
| 6.5.3   | 2        | 0.03%   |
| 6.4.10  | 2        | 0.03%   |
| 6.3.9   | 2        | 0.03%   |
| 6.2.8   | 2        | 0.03%   |
| 6.2.13  | 2        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 3559     | 46.64%  |
| 5.15    | 1812     | 23.75%  |
| 4.15    | 903      | 11.83%  |
| 5.3     | 361      | 4.73%   |
| 5.0     | 203      | 2.66%   |
| 5.13    | 128      | 1.68%   |
| 5.8     | 103      | 1.35%   |
| 5.19    | 89       | 1.17%   |
| 6.2     | 85       | 1.11%   |
| 5.11    | 78       | 1.02%   |
| 4.4     | 36       | 0.47%   |
| 4.10    | 36       | 0.47%   |
| 4.13    | 27       | 0.35%   |
| 4.18    | 24       | 0.31%   |
| 6.1     | 19       | 0.25%   |
| 4.8     | 17       | 0.22%   |
| 5.10    | 14       | 0.18%   |
| 5.17    | 13       | 0.17%   |
| 5.14    | 13       | 0.17%   |
| 6.0     | 12       | 0.16%   |
| 6.4     | 11       | 0.14%   |
| 6.3     | 10       | 0.13%   |
| 6.5     | 9        | 0.12%   |
| 5.9     | 8        | 0.1%    |
| 5.7     | 8        | 0.1%    |
| 4.20    | 8        | 0.1%    |
| 5.16    | 6        | 0.08%   |
| 5.12    | 5        | 0.07%   |
| 5.18    | 4        | 0.05%   |
| 5.6     | 3        | 0.04%   |
| 5.5     | 3        | 0.04%   |
| 5.2     | 3        | 0.04%   |
| 4.14    | 3        | 0.04%   |
| 4.11    | 3        | 0.04%   |
| 4.19    | 2        | 0.03%   |
| 4.16    | 2        | 0.03%   |
| 4.12    | 2        | 0.03%   |
| 3.19    | 2        | 0.03%   |
| 3.13    | 2        | 0.03%   |
| 6.6     | 1        | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 6971     | 97.32%  |
| i686   | 192      | 2.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| X-Cinnamon      | 4497     | 61.02%  |
| MATE            | 921      | 12.5%   |
| XFCE            | 628      | 8.52%   |
| Cinnamon        | 578      | 7.84%   |
| Unknown         | 537      | 7.29%   |
| GNOME           | 131      | 1.78%   |
| KDE5            | 31       | 0.42%   |
| KDE             | 22       | 0.3%    |
| LXDE            | 7        | 0.09%   |
| i3              | 3        | 0.04%   |
| Budgie          | 3        | 0.04%   |
| Pantheon        | 2        | 0.03%   |
| KDE4            | 2        | 0.03%   |
| Trinity         | 1        | 0.01%   |
| sway            | 1        | 0.01%   |
| qtile           | 1        | 0.01%   |
| LXQt            | 1        | 0.01%   |
| ICEWM           | 1        | 0.01%   |
| GNOME Flashback | 1        | 0.01%   |
| GNOME Classic   | 1        | 0.01%   |
| enlightenment   | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 7109     | 99.16%  |
| Tty     | 39       | 0.54%   |
| Wayland | 18       | 0.25%   |
| Unknown | 3        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4584     | 62.98%  |
| LightDM | 1831     | 25.16%  |
| TDM     | 775      | 10.65%  |
| MDM     | 42       | 0.58%   |
| SDDM    | 25       | 0.34%   |
| GDM     | 15       | 0.21%   |
| GDM3    | 4        | 0.05%   |
| LXDM    | 2        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1897     | 26.11%  |
| de_DE   | 1055     | 14.52%  |
| Unknown | 689      | 9.48%   |
| pt_BR   | 554      | 7.62%   |
| fr_FR   | 318      | 4.38%   |
| en_GB   | 306      | 4.21%   |
| ru_RU   | 304      | 4.18%   |
| it_IT   | 226      | 3.11%   |
| en_CA   | 188      | 2.59%   |
| C       | 181      | 2.49%   |
| es_ES   | 168      | 2.31%   |
| en_AU   | 142      | 1.95%   |
| pl_PL   | 131      | 1.8%    |
| nl_NL   | 93       | 1.28%   |
| es_AR   | 75       | 1.03%   |
| cs_CZ   | 51       | 0.7%    |
| de_AT   | 48       | 0.66%   |
| pt_PT   | 47       | 0.65%   |
| hu_HU   | 45       | 0.62%   |
| es_MX   | 44       | 0.61%   |
| ru_UA   | 39       | 0.54%   |
| fi_FI   | 38       | 0.52%   |
| en_ZA   | 36       | 0.5%    |
| en_IN   | 36       | 0.5%    |
| de_CH   | 33       | 0.45%   |
| sv_SE   | 30       | 0.41%   |
| sk_SK   | 30       | 0.41%   |
| fr_CA   | 28       | 0.39%   |
| en_NZ   | 26       | 0.36%   |
| fr_BE   | 24       | 0.33%   |
| tr_TR   | 23       | 0.32%   |
| es_VE   | 22       | 0.3%    |
| uk_UA   | 20       | 0.28%   |
| es_CL   | 20       | 0.28%   |
| es_CO   | 19       | 0.26%   |
| el_GR   | 19       | 0.26%   |
| nl_BE   | 18       | 0.25%   |
| en_PH   | 18       | 0.25%   |
| en_IE   | 18       | 0.25%   |
| ja_JP   | 15       | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 4177     | 57.32%  |
| EFI  | 3110     | 42.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 6323     | 86.99%  |
| Unknown | 512      | 7.04%   |
| Btrfs   | 155      | 2.13%   |
| Overlay | 148      | 2.04%   |
| Zfs     | 32       | 0.44%   |
| Tmpfs   | 30       | 0.41%   |
| Xfs     | 27       | 0.37%   |
| Ext2    | 19       | 0.26%   |
| Ext3    | 18       | 0.25%   |
| Jfs     | 2        | 0.03%   |
| Aufs    | 2        | 0.03%   |
| XXXX    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4656     | 64.1%   |
| GPT     | 1752     | 24.12%  |
| MBR     | 856      | 11.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6515     | 90.04%  |
| Yes       | 721      | 9.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5753     | 79.41%  |
| Yes       | 1492     | 20.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1730     | 24.17%  |
| Gigabyte Technology | 1218     | 17.02%  |
| MSI                 | 771      | 10.77%  |
| ASRock              | 654      | 9.14%   |
| Dell                | 596      | 8.33%   |
| Hewlett-Packard     | 561      | 7.84%   |
| Lenovo              | 256      | 3.58%   |
| Intel               | 203      | 2.84%   |
| Acer                | 130      | 1.82%   |
| Pegatron            | 105      | 1.47%   |
| Unknown             | 101      | 1.41%   |
| Foxconn             | 83       | 1.16%   |
| Biostar             | 80       | 1.12%   |
| Fujitsu             | 72       | 1.01%   |
| ECS                 | 66       | 0.92%   |
| Medion              | 56       | 0.78%   |
| Positivo            | 37       | 0.52%   |
| Fujitsu Siemens     | 29       | 0.41%   |
| PCWare              | 21       | 0.29%   |
| AZW                 | 20       | 0.28%   |
| Gateway             | 19       | 0.27%   |
| Apple               | 19       | 0.27%   |
| Shuttle             | 18       | 0.25%   |
| BESSTAR Tech        | 17       | 0.24%   |
| OEM                 | 15       | 0.21%   |
| AMI                 | 15       | 0.21%   |
| Packard Bell        | 14       | 0.2%    |
| Semp Toshiba        | 12       | 0.17%   |
| eMachines           | 12       | 0.17%   |
| AMD                 | 12       | 0.17%   |
| Alienware           | 12       | 0.17%   |
| Inventec            | 11       | 0.15%   |
| Huanan              | 11       | 0.15%   |
| Supermicro          | 9        | 0.13%   |
| Itautec             | 9        | 0.13%   |
| Megaware            | 7        | 0.1%    |
| PCChips             | 6        | 0.08%   |
| MACHINIST           | 5        | 0.07%   |
| ABIT                | 5        | 0.07%   |
| Wistron             | 4        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 154      | 2.15%   |
| Unknown                      | 113      | 1.58%   |
| Dell OptiPlex 790            | 36       | 0.5%    |
| ASUS M5A78L-M/USB3           | 34       | 0.48%   |
| Dell OptiPlex 780            | 33       | 0.46%   |
| Dell OptiPlex 7010           | 33       | 0.46%   |
| MSI MS-7693                  | 32       | 0.45%   |
| Gigabyte B450M DS3H          | 32       | 0.45%   |
| ASUS PRIME A320M-K           | 31       | 0.43%   |
| ASUS TUF Gaming X570-PLUS    | 30       | 0.42%   |
| MSI MS-7C02                  | 28       | 0.39%   |
| MSI MS-7C56                  | 27       | 0.38%   |
| MSI MS-7C37                  | 26       | 0.36%   |
| Dell OptiPlex 9020           | 26       | 0.36%   |
| Dell OptiPlex 3020           | 26       | 0.36%   |
| MSI MS-7B86                  | 25       | 0.35%   |
| MSI MS-7817                  | 25       | 0.35%   |
| MSI MS-7721                  | 23       | 0.32%   |
| HP Compaq Elite 8300 SFF     | 23       | 0.32%   |
| Gigabyte 970A-DS3P           | 22       | 0.31%   |
| Dell OptiPlex 755            | 22       | 0.31%   |
| MSI MS-7C91                  | 20       | 0.28%   |
| Gigabyte A320M-S2H           | 20       | 0.28%   |
| Dell OptiPlex 3010           | 20       | 0.28%   |
| ASUS ROG STRIX B450-F GAMING | 20       | 0.28%   |
| ASUS M5A97 R2.0              | 20       | 0.28%   |
| Intel H61                    | 19       | 0.27%   |
| Dell OptiPlex 990            | 19       | 0.27%   |
| MSI MS-7641                  | 18       | 0.25%   |
| HP EliteDesk 800 G1 SFF      | 18       | 0.25%   |
| Dell OptiPlex 390            | 18       | 0.25%   |
| ASUS M5A78L-M PLUS/USB3      | 18       | 0.25%   |
| ASRock B450M Pro4            | 18       | 0.25%   |
| HP Compaq 8200 Elite SFF PC  | 17       | 0.24%   |
| MSI MS-7B79                  | 16       | 0.22%   |
| Intel H55                    | 16       | 0.22%   |
| Dell OptiPlex 745            | 16       | 0.22%   |
| ASUS SABERTOOTH 990FX R2.0   | 16       | 0.22%   |
| Gigabyte B450 AORUS ELITE    | 15       | 0.21%   |
| ASUS PRIME B450M-A           | 15       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 372      | 5.2%    |
| ASUS PRIME             | 270      | 3.77%   |
| HP Compaq              | 238      | 3.33%   |
| Lenovo ThinkCentre     | 168      | 2.35%   |
| ASUS All               | 154      | 2.15%   |
| ASUS ROG               | 147      | 2.05%   |
| Unknown                | 113      | 1.58%   |
| ASUS TUF               | 112      | 1.56%   |
| Acer Aspire            | 89       | 1.24%   |
| ASUS M5A78L-M          | 82       | 1.15%   |
| Dell Inspiron          | 77       | 1.08%   |
| HP EliteDesk           | 68       | 0.95%   |
| Dell Precision         | 64       | 0.89%   |
| Fujitsu ESPRIMO        | 54       | 0.75%   |
| HP ProDesk             | 53       | 0.74%   |
| Gigabyte B450M         | 48       | 0.67%   |
| ASUS P8H61-M           | 46       | 0.64%   |
| Gigabyte B450          | 44       | 0.61%   |
| ASUS M5A97             | 42       | 0.59%   |
| Gigabyte GA-78LMT-USB3 | 36       | 0.5%    |
| ASRock B450M           | 35       | 0.49%   |
| Lenovo IdeaCentre      | 34       | 0.48%   |
| ASUS SABERTOOTH        | 34       | 0.48%   |
| MSI MS-7693            | 32       | 0.45%   |
| Gigabyte X570          | 32       | 0.45%   |
| HP Pavilion            | 31       | 0.43%   |
| Gigabyte B550          | 29       | 0.41%   |
| MSI MS-7C02            | 28       | 0.39%   |
| MSI MS-7C56            | 27       | 0.38%   |
| Gigabyte A320M-S2H     | 27       | 0.38%   |
| MSI MS-7C37            | 26       | 0.36%   |
| Acer Veriton           | 26       | 0.36%   |
| MSI MS-7B86            | 25       | 0.35%   |
| MSI MS-7817            | 25       | 0.35%   |
| Dell XPS               | 25       | 0.35%   |
| Gigabyte 970A-DS3P     | 24       | 0.34%   |
| Dell Vostro            | 24       | 0.34%   |
| MSI MS-7721            | 23       | 0.32%   |
| Gigabyte B550M         | 22       | 0.31%   |
| ASUS P8H67-M           | 22       | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 772      | 10.79%  |
| 2011    | 640      | 8.94%   |
| 2018    | 624      | 8.72%   |
| 2013    | 614      | 8.58%   |
| 2014    | 479      | 6.69%   |
| 2009    | 470      | 6.57%   |
| 2020    | 459      | 6.41%   |
| 2010    | 447      | 6.25%   |
| 2019    | 400      | 5.59%   |
| 2017    | 394      | 5.51%   |
| 2008    | 343      | 4.79%   |
| 2015    | 295      | 4.12%   |
| 2007    | 290      | 4.05%   |
| 2016    | 289      | 4.04%   |
| 2021    | 272      | 3.8%    |
| 2022    | 148      | 2.07%   |
| 2006    | 131      | 1.83%   |
| 2005    | 33       | 0.46%   |
| 2023    | 26       | 0.36%   |
| 2004    | 14       | 0.2%    |
| 2003    | 12       | 0.17%   |
| 2002    | 3        | 0.04%   |
| Unknown | 2        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7157     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6929     | 96.46%  |
| Enabled  | 254      | 3.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7154     | 99.96%  |
| Yes  | 3        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1715     | 23.46%  |
| 8.01-16.0       | 1469     | 20.1%   |
| 3.01-4.0        | 1265     | 17.31%  |
| 4.01-8.0        | 1207     | 16.51%  |
| 32.01-64.0      | 862      | 11.79%  |
| 1.01-2.0        | 269      | 3.68%   |
| 64.01-256.0     | 220      | 3.01%   |
| 24.01-32.0      | 150      | 2.05%   |
| 2.01-3.0        | 115      | 1.57%   |
| 0.51-1.0        | 34       | 0.47%   |
| More than 256.0 | 2        | 0.03%   |
| 0.01-0.5        | 1        | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 3003     | 37.06%  |
| 2.01-3.0   | 2170     | 26.78%  |
| 4.01-8.0   | 1036     | 12.79%  |
| 3.01-4.0   | 1002     | 12.37%  |
| 0.51-1.0   | 552      | 6.81%   |
| 8.01-16.0  | 255      | 3.15%   |
| 16.01-24.0 | 40       | 0.49%   |
| 0.01-0.5   | 23       | 0.28%   |
| 24.01-32.0 | 16       | 0.2%    |
| 32.01-64.0 | 3        | 0.04%   |
| Unknown    | 3        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2937     | 39.21%  |
| 2       | 2192     | 29.26%  |
| 3       | 1206     | 16.1%   |
| 4       | 612      | 8.17%   |
| 5       | 288      | 3.84%   |
| 6       | 116      | 1.55%   |
| 7       | 57       | 0.76%   |
| 0       | 37       | 0.49%   |
| 8       | 26       | 0.35%   |
| 9       | 11       | 0.15%   |
| 10      | 4        | 0.05%   |
| 14      | 2        | 0.03%   |
| 28      | 1        | 0.01%   |
| 22      | 1        | 0.01%   |
| Unknown | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3987     | 55.07%  |
| No        | 3253     | 44.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7072     | 98.78%  |
| No        | 87       | 1.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4088     | 56.17%  |
| Yes       | 3190     | 43.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5244     | 71.96%  |
| Yes       | 2043     | 28.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1295     | 18.01%  |
| Germany      | 1179     | 16.4%   |
| Brazil       | 768      | 10.68%  |
| Russia       | 435      | 6.05%   |
| France       | 336      | 4.67%   |
| UK           | 301      | 4.19%   |
| Canada       | 258      | 3.59%   |
| Italy        | 254      | 3.53%   |
| Spain        | 199      | 2.77%   |
| Netherlands  | 162      | 2.25%   |
| Australia    | 159      | 2.21%   |
| Poland       | 156      | 2.17%   |
| Ukraine      | 116      | 1.61%   |
| Argentina    | 87       | 1.21%   |
| Austria      | 76       | 1.06%   |
| Switzerland  | 75       | 1.04%   |
| Belgium      | 71       | 0.99%   |
| Czechia      | 68       | 0.95%   |
| Sweden       | 66       | 0.92%   |
| Mexico       | 59       | 0.82%   |
| Hungary      | 58       | 0.81%   |
| Finland      | 53       | 0.74%   |
| Portugal     | 51       | 0.71%   |
| India        | 44       | 0.61%   |
| South Africa | 43       | 0.6%    |
| Greece       | 43       | 0.6%    |
| Turkey       | 39       | 0.54%   |
| Romania      | 38       | 0.53%   |
| Slovakia     | 35       | 0.49%   |
| Denmark      | 34       | 0.47%   |
| Japan        | 31       | 0.43%   |
| Colombia     | 31       | 0.43%   |
| New Zealand  | 29       | 0.4%    |
| Belarus      | 28       | 0.39%   |
| Norway       | 26       | 0.36%   |
| Venezuela    | 25       | 0.35%   |
| Chile        | 25       | 0.35%   |
| Bulgaria     | 24       | 0.33%   |
| Serbia       | 23       | 0.32%   |
| Ireland      | 21       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sao Paulo         | 87       | 1.13%   |
| Moscow            | 81       | 1.06%   |
| Berlin            | 81       | 1.06%   |
| Rio de Janeiro    | 53       | 0.69%   |
| Hamburg           | 52       | 0.68%   |
| Vienna            | 46       | 0.6%    |
| Sydney            | 39       | 0.51%   |
| Paris             | 39       | 0.51%   |
| Munich            | 38       | 0.5%    |
| Amsterdam         | 37       | 0.48%   |
| St Petersburg     | 36       | 0.47%   |
| Frankfurt am Main | 36       | 0.47%   |
| Madrid            | 34       | 0.44%   |
| Warsaw            | 33       | 0.43%   |
| Rome              | 32       | 0.42%   |
| Montreal          | 32       | 0.42%   |
| Cologne           | 30       | 0.39%   |
| London            | 29       | 0.38%   |
| Kyiv              | 26       | 0.34%   |
| Chicago           | 25       | 0.33%   |
| Brisbane          | 25       | 0.33%   |
| Leipzig           | 24       | 0.31%   |
| Melbourne         | 23       | 0.3%    |
| Budapest          | 23       | 0.3%    |
| Brasília         | 23       | 0.3%    |
| New York          | 21       | 0.27%   |
| Helsinki          | 21       | 0.27%   |
| Toronto           | 20       | 0.26%   |
| Perth             | 20       | 0.26%   |
| Athens            | 20       | 0.26%   |
| Vancouver         | 19       | 0.25%   |
| Dresden           | 19       | 0.25%   |
| Stockholm         | 18       | 0.23%   |
| Porto Alegre      | 18       | 0.23%   |
| Milan             | 18       | 0.23%   |
| Curitiba          | 18       | 0.23%   |
| Belgrade          | 18       | 0.23%   |
| Barcelona         | 18       | 0.23%   |
| Manchester        | 17       | 0.22%   |
| Minsk             | 16       | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 2638     | 4474   | 20.32%  |
| Seagate                     | 2570     | 4282   | 19.8%   |
| Samsung Electronics         | 1866     | 3068   | 14.37%  |
| Kingston                    | 817      | 1145   | 6.29%   |
| Toshiba                     | 594      | 817    | 4.58%   |
| Crucial                     | 563      | 816    | 4.34%   |
| SanDisk                     | 555      | 803    | 4.27%   |
| Hitachi                     | 511      | 685    | 3.94%   |
| A-DATA Technology           | 183      | 251    | 1.41%   |
| China                       | 169      | 201    | 1.3%    |
| Intel                       | 154      | 216    | 1.19%   |
| Unknown                     | 140      | 239    | 1.08%   |
| Maxtor                      | 134      | 185    | 1.03%   |
| HGST                        | 124      | 179    | 0.96%   |
| Intenso                     | 119      | 165    | 0.92%   |
| PNY                         | 88       | 121    | 0.68%   |
| SPCC                        | 78       | 107    | 0.6%    |
| Patriot                     | 75       | 91     | 0.58%   |
| Phison                      | 74       | 106    | 0.57%   |
| OCZ                         | 73       | 93     | 0.56%   |
| Silicon Motion              | 64       | 95     | 0.49%   |
| Micron/Crucial Technology   | 61       | 110    | 0.47%   |
| Corsair                     | 60       | 74     | 0.46%   |
| SK hynix                    | 57       | 72     | 0.44%   |
| Micron Technology           | 55       | 70     | 0.42%   |
| Transcend                   | 51       | 77     | 0.39%   |
| GOODRAM                     | 46       | 62     | 0.35%   |
| JMicron Technology          | 38       | 53     | 0.29%   |
| Apacer                      | 35       | 41     | 0.27%   |
| Team                        | 34       | 53     | 0.26%   |
| Unknown                     | 33       | 48     | 0.25%   |
| XPG                         | 30       | 42     | 0.23%   |
| Phison Electronics          | 30       | 44     | 0.23%   |
| Realtek Semiconductor       | 29       | 39     | 0.22%   |
| Lexar                       | 29       | 38     | 0.22%   |
| KingSpec                    | 29       | 46     | 0.22%   |
| Fujitsu                     | 29       | 40     | 0.22%   |
| Plextor                     | 27       | 37     | 0.21%   |
| Kingston Technology Company | 27       | 31     | 0.21%   |
| ASMT                        | 26       | 38     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 210      | 1.4%    |
| Kingston SA400S37240G 240GB SSD                   | 206      | 1.37%   |
| Samsung SSD 850 EVO 250GB                         | 153      | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB                    | 147      | 0.98%   |
| Toshiba DT01ACA100 1TB                            | 138      | 0.92%   |
| Samsung SSD 860 EVO 500GB                         | 119      | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                    | 116      | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 113      | 0.75%   |
| Kingston SA400S37120G 120GB SSD                   | 105      | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB                    | 102      | 0.68%   |
| Seagate ST3500418AS 500GB                         | 100      | 0.66%   |
| Samsung SSD 850 EVO 500GB                         | 97       | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                  | 96       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB                    | 94       | 0.62%   |
| Samsung SSD 860 EVO 1TB                           | 91       | 0.6%    |
| Kingston SA400S37480G 480GB SSD                   | 83       | 0.55%   |
| Crucial CT240BX500SSD1 240GB                      | 79       | 0.53%   |
| Crucial CT500MX500SSD1 500GB                      | 78       | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                       | 78       | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 74       | 0.49%   |
| Samsung SSD 860 EVO 250GB                         | 71       | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 70       | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB                    | 69       | 0.46%   |
| Seagate ST31000528AS 1TB                          | 65       | 0.43%   |
| Toshiba HDWD110 1TB                               | 64       | 0.43%   |
| Seagate ST31000524AS 1TB                          | 60       | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                    | 60       | 0.4%    |
| Seagate Expansion 1TB                             | 60       | 0.4%    |
| Unknown SD/MMC/MS PRO 16GB                        | 59       | 0.39%   |
| Samsung NVMe SSD Drive 500GB                      | 57       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 55       | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 53       | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                    | 53       | 0.35%   |
| Toshiba DT01ACA200 2TB                            | 51       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                    | 51       | 0.34%   |
| SanDisk SSD PLUS 240GB                            | 51       | 0.34%   |
| Seagate ST3500413AS 500GB                         | 49       | 0.33%   |
| Toshiba DT01ACA050 500GB                          | 48       | 0.32%   |
| Seagate ST1000DM003-1SB102 1TB                    | 46       | 0.31%   |
| SanDisk SDSSDA240G 240GB                          | 45       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2519     | 4157   | 36.18%  |
| WDC                 | 2370     | 3977   | 34.04%  |
| Toshiba             | 551      | 750    | 7.91%   |
| Samsung Electronics | 527      | 757    | 7.57%   |
| Hitachi             | 511      | 685    | 7.34%   |
| Maxtor              | 131      | 182    | 1.88%   |
| HGST                | 124      | 179    | 1.78%   |
| Unknown             | 69       | 89     | 0.99%   |
| Fujitsu             | 28       | 39     | 0.4%    |
| Intenso             | 16       | 20     | 0.23%   |
| Hewlett-Packard     | 10       | 14     | 0.14%   |
| ASMT                | 9        | 17     | 0.13%   |
| ExcelStor           | 7        | 9      | 0.1%    |
| WD MediaMax         | 6        | 15     | 0.09%   |
| JMicron Technology  | 6        | 16     | 0.09%   |
| External            | 6        | 6      | 0.09%   |
| ASMedia             | 6        | 8      | 0.09%   |
| Apple               | 5        | 5      | 0.07%   |
| USB3.0              | 4        | 4      | 0.06%   |
| Pioneer             | 4        | 5      | 0.06%   |
| HPE                 | 4        | 5      | 0.06%   |
| Unknown             | 4        | 6      | 0.06%   |
| USB                 | 3        | 4      | 0.04%   |
| Maxone              | 3        | 4      | 0.04%   |
| LaCie               | 3        | 3      | 0.04%   |
| HGST HTS            | 3        | 4      | 0.04%   |
| ASMT109x            | 3        | 3      | 0.04%   |
| TDAS                | 2        | 7      | 0.03%   |
| SAGE                | 2        | 2      | 0.03%   |
| SABRENT             | 2        | 2      | 0.03%   |
| RSH-319             | 2        | 2      | 0.03%   |
| Maxtor 6            | 2        | 3      | 0.03%   |
| KESU                | 2        | 3      | 0.03%   |
| China               | 2        | 2      | 0.03%   |
| USB 3.0             | 1        | 4      | 0.01%   |
| TANDBERG            | 1        | 1      | 0.01%   |
| Synology            | 1        | 1      | 0.01%   |
| Storeva             | 1        | 1      | 0.01%   |
| SSK                 | 1        | 1      | 0.01%   |
| Quantum             | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 994      | 1544   | 21.95%  |
| Kingston            | 707      | 984    | 15.61%  |
| Crucial             | 517      | 740    | 11.42%  |
| SanDisk             | 417      | 585    | 9.21%   |
| WDC                 | 299      | 412    | 6.6%    |
| China               | 166      | 198    | 3.67%   |
| A-DATA Technology   | 151      | 208    | 3.33%   |
| Intenso             | 86       | 116    | 1.9%    |
| Intel               | 83       | 108    | 1.83%   |
| PNY                 | 80       | 112    | 1.77%   |
| OCZ                 | 72       | 91     | 1.59%   |
| Patriot             | 70       | 86     | 1.55%   |
| SPCC                | 69       | 97     | 1.52%   |
| Transcend           | 46       | 64     | 1.02%   |
| GOODRAM             | 45       | 61     | 0.99%   |
| Toshiba             | 42       | 56     | 0.93%   |
| Corsair             | 40       | 49     | 0.88%   |
| Micron Technology   | 38       | 51     | 0.84%   |
| Team                | 32       | 50     | 0.71%   |
| Apacer              | 32       | 38     | 0.71%   |
| KingSpec            | 28       | 45     | 0.62%   |
| Lexar               | 27       | 36     | 0.6%    |
| Plextor             | 24       | 31     | 0.53%   |
| SK hynix            | 23       | 27     | 0.51%   |
| Unknown             | 21       | 30     | 0.46%   |
| Seagate             | 17       | 32     | 0.38%   |
| LITEON              | 16       | 18     | 0.35%   |
| TO Exter            | 15       | 22     | 0.33%   |
| SABRENT             | 15       | 16     | 0.33%   |
| ASMT                | 15       | 19     | 0.33%   |
| Verbatim            | 13       | 16     | 0.29%   |
| KingDian            | 12       | 17     | 0.26%   |
| Netac               | 11       | 18     | 0.24%   |
| Leven               | 11       | 11     | 0.24%   |
| Hewlett-Packard     | 11       | 13     | 0.24%   |
| Gigabyte Technology | 11       | 21     | 0.24%   |
| AMD                 | 11       | 12     | 0.24%   |
| LITEONIT            | 10       | 10     | 0.22%   |
| Fanxiang            | 10       | 12     | 0.22%   |
| Smartbuy            | 9        | 13     | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 5262     | 11005  | 49.19%  |
| SSD     | 3761     | 6352   | 35.16%  |
| NVMe    | 1416     | 2234   | 13.24%  |
| Unknown | 221      | 343    | 2.07%   |
| MMC     | 38       | 56     | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 6712     | 16745  | 76.61%  |
| NVMe | 1405     | 2204   | 16.04%  |
| SAS  | 606      | 985    | 6.92%   |
| MMC  | 38       | 56     | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 5088     | 9436   | 51.57%  |
| 0.51-1.0        | 2813     | 4556   | 28.51%  |
| 1.01-2.0        | 1080     | 1845   | 10.95%  |
| 3.01-4.0        | 341      | 619    | 3.46%   |
| 2.01-3.0        | 309      | 490    | 3.13%   |
| 4.01-10.0       | 197      | 314    | 2%      |
| 10.01-20.0      | 36       | 94     | 0.36%   |
| 0               | 2        | 2      | 0.02%   |
| More than 100.0 | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1876     | 24.54%  |
| 251-500        | 1484     | 19.41%  |
| 501-1000       | 1271     | 16.63%  |
| 1001-2000      | 957      | 12.52%  |
| More than 3000 | 799      | 10.45%  |
| 2001-3000      | 463      | 6.06%   |
| 51-100         | 403      | 5.27%   |
| 21-50          | 182      | 2.38%   |
| 1-20           | 148      | 1.94%   |
| Unknown        | 62       | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1654     | 20.71%  |
| 21-50          | 1479     | 18.52%  |
| 101-250        | 1193     | 14.93%  |
| 51-100         | 1043     | 13.06%  |
| 251-500        | 773      | 9.68%   |
| 501-1000       | 745      | 9.33%   |
| 1001-2000      | 504      | 6.31%   |
| More than 3000 | 320      | 4.01%   |
| 2001-3000      | 215      | 2.69%   |
| Unknown        | 62       | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 30       | 35     | 3.29%   |
| Seagate ST3500418AS 500GB           | 20       | 24     | 2.19%   |
| Seagate ST31000528AS 1TB            | 11       | 13     | 1.2%    |
| WDC WD10EARS-00Y5B1 1TB             | 8        | 8      | 0.88%   |
| Seagate ST3500320AS 500GB           | 7        | 9      | 0.77%   |
| Seagate ST1000DM003-9YN162 1TB      | 7        | 8      | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 8      | 0.77%   |
| Samsung Electronics HD322HJ 320GB   | 7        | 16     | 0.77%   |
| Crucial CT525MX300SSD1 528GB        | 7        | 7      | 0.77%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6        | 7      | 0.66%   |
| Seagate ST31000524AS 1TB            | 6        | 7      | 0.66%   |
| Seagate ST2000DM001-1CH164 2TB      | 6        | 6      | 0.66%   |
| Samsung Electronics HD502HI 500GB   | 6        | 6      | 0.66%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 5        | 5      | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB         | 5        | 6      | 0.55%   |
| Toshiba DT01ACA100 1TB              | 5        | 6      | 0.55%   |
| Seagate ST3500413AS 500GB           | 5        | 7      | 0.55%   |
| Seagate ST3250318AS 250GB           | 5        | 6      | 0.55%   |
| Seagate ST2000DM001-9YN164 2TB      | 5        | 5      | 0.55%   |
| Seagate ST2000DL003-9VT166 2TB      | 5        | 6      | 0.55%   |
| Seagate ST1500DL003-9VT16L 1TB      | 5        | 5      | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 6      | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 4        | 4      | 0.44%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 4        | 4      | 0.44%   |
| WDC WD5000AAKS-00A7B0 500GB         | 4        | 4      | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4        | 7      | 0.44%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4        | 4      | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 4      | 0.44%   |
| WDC WD20EFRX-68EUZN0 2TB            | 4        | 7      | 0.44%   |
| WDC WD20EARX-00PASB0 2TB            | 4        | 4      | 0.44%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 4        | 4      | 0.44%   |
| Seagate ST9500325AS 500GB           | 4        | 4      | 0.44%   |
| Seagate ST500LT012-1DG142 500GB     | 4        | 4      | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4        | 4      | 0.44%   |
| Seagate ST320LT012-1DG14C 320GB     | 4        | 4      | 0.44%   |
| Seagate ST31500341AS 1TB            | 4        | 5      | 0.44%   |
| Seagate ST31000333AS 1TB            | 4        | 4      | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB      | 4        | 5      | 0.44%   |
| Seagate ST2000DM006-2DM164 2TB      | 4        | 4      | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 5      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 265      | 327    | 30.81%  |
| WDC                 | 245      | 312    | 28.49%  |
| Samsung Electronics | 98       | 125    | 11.4%   |
| Hitachi             | 62       | 74     | 7.21%   |
| Toshiba             | 27       | 28     | 3.14%   |
| Crucial             | 22       | 23     | 2.56%   |
| Maxtor              | 21       | 27     | 2.44%   |
| SanDisk             | 18       | 20     | 2.09%   |
| Kingston            | 18       | 20     | 2.09%   |
| Intel               | 10       | 10     | 1.16%   |
| Corsair             | 6        | 9      | 0.7%    |
| OCZ                 | 5        | 6      | 0.58%   |
| HGST                | 5        | 5      | 0.58%   |
| China               | 5        | 6      | 0.58%   |
| A-DATA Technology   | 5        | 5      | 0.58%   |
| Intenso             | 4        | 4      | 0.47%   |
| SPCC                | 3        | 4      | 0.35%   |
| Micron Technology   | 3        | 4      | 0.35%   |
| XPG                 | 2        | 3      | 0.23%   |
| Transcend           | 2        | 2      | 0.23%   |
| SK hynix            | 2        | 2      | 0.23%   |
| Plextor             | 2        | 2      | 0.23%   |
| LITEONIT            | 2        | 2      | 0.23%   |
| Leven               | 2        | 2      | 0.23%   |
| LDLC                | 2        | 2      | 0.23%   |
| Kingmax             | 2        | 2      | 0.23%   |
| XrayDisk            | 1        | 1      | 0.12%   |
| USB3.0              | 1        | 1      | 0.12%   |
| Unknown             | 1        | 1      | 0.12%   |
| tecmiyo             | 1        | 1      | 0.12%   |
| Team                | 1        | 1      | 0.12%   |
| s60                 | 1        | 1      | 0.12%   |
| PNY                 | 1        | 2      | 0.12%   |
| Patriot             | 1        | 1      | 0.12%   |
| Neo                 | 1        | 1      | 0.12%   |
| Mushkin             | 1        | 1      | 0.12%   |
| MDT                 | 1        | 1      | 0.12%   |
| LITEON              | 1        | 1      | 0.12%   |
| HS-SSD-E100         | 1        | 1      | 0.12%   |
| Hewlett-Packard     | 1        | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 265      | 327    | 37.91%  |
| WDC                 | 238      | 302    | 34.05%  |
| Samsung Electronics | 72       | 95     | 10.3%   |
| Hitachi             | 62       | 74     | 8.87%   |
| Toshiba             | 27       | 28     | 3.86%   |
| Maxtor              | 21       | 27     | 3%      |
| HGST                | 5        | 5      | 0.72%   |
| USB3.0              | 1        | 1      | 0.14%   |
| Unknown             | 1        | 1      | 0.14%   |
| MDT                 | 1        | 1      | 0.14%   |
| Hewlett-Packard     | 1        | 1      | 0.14%   |
| Fujitsu             | 1        | 2      | 0.14%   |
| FEASSO              | 1        | 2      | 0.14%   |
| ExcelStor           | 1        | 1      | 0.14%   |
| ASMedia             | 1        | 1      | 0.14%   |
| Unknown             | 1        | 2      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 631      | 870    | 79.67%  |
| SSD  | 138      | 155    | 17.42%  |
| NVMe | 23       | 28     | 2.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 25%     |
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 12.5%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 12.5%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 12.5%   |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 50%     |
| Toshiba             | 2        | 2      | 25%     |
| Hitachi             | 2        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 4840     | 13682  | 60.66%  |
| Works    | 2365     | 5247   | 29.64%  |
| Malfunc  | 766      | 1053   | 9.6%    |
| Failed   | 8        | 8      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 4531     | 47.06%  |
| AMD                              | 2259     | 23.46%  |
| Samsung Electronics              | 538      | 5.59%   |
| ASMedia Technology               | 324      | 3.36%   |
| Nvidia                           | 294      | 3.05%   |
| JMicron Technology               | 251      | 2.61%   |
| Marvell Technology Group         | 249      | 2.59%   |
| SanDisk                          | 224      | 2.33%   |
| Phison Electronics               | 151      | 1.57%   |
| Kingston Technology Company      | 147      | 1.53%   |
| Micron/Crucial Technology        | 115      | 1.19%   |
| Silicon Motion                   | 90       | 0.93%   |
| VIA Technologies                 | 89       | 0.92%   |
| ADATA Technology                 | 66       | 0.69%   |
| Realtek Semiconductor            | 45       | 0.47%   |
| SK hynix                         | 32       | 0.33%   |
| Silicon Image                    | 27       | 0.28%   |
| LSI Logic / Symbios Logic        | 25       | 0.26%   |
| Adaptec                          | 20       | 0.21%   |
| Micron Technology                | 18       | 0.19%   |
| MAXIO Technology (Hangzhou)      | 14       | 0.15%   |
| Broadcom / LSI                   | 14       | 0.15%   |
| Toshiba America Info Systems     | 13       | 0.14%   |
| KIOXIA                           | 13       | 0.14%   |
| Seagate Technology               | 12       | 0.12%   |
| Silicon Integrated Systems [SiS] | 11       | 0.11%   |
| Lite-On Technology               | 9        | 0.09%   |
| Integrated Technology Express    | 8        | 0.08%   |
| Shenzhen Longsys Electronics     | 5        | 0.05%   |
| HighPoint Technologies           | 5        | 0.05%   |
| Union Memory (Shenzhen)          | 4        | 0.04%   |
| Transcend                        | 4        | 0.04%   |
| ULi Electronics                  | 3        | 0.03%   |
| Hewlett-Packard                  | 3        | 0.03%   |
| OCZ Technology Group             | 2        | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.02%   |
| INNOGRIT                         | 2        | 0.02%   |
| TenaFe                           | 1        | 0.01%   |
| Sony                             | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1090     | 8.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 542      | 4.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 478      | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 447      | 3.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 411      | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 393      | 3.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 385      | 3.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 326      | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 324      | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 321      | 2.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 319      | 2.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 301      | 2.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 290      | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 265      | 2.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 264      | 2.1%    |
| Intel SATA Controller [RAID mode]                                                       | 248      | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 226      | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 226      | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 179      | 1.42%   |
| Nvidia MCP61 SATA Controller                                                            | 177      | 1.41%   |
| Nvidia MCP61 IDE                                                                        | 143      | 1.14%   |
| AMD FCH SATA Controller D                                                               | 133      | 1.06%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 129      | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 127      | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 108      | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 102      | 0.81%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 102      | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 93       | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 89       | 0.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 88       | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 87       | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 86       | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 84       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 83       | 0.66%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 81       | 0.64%   |
| Phison E12 NVMe Controller                                                              | 75       | 0.6%    |
| JMicron JMB368 IDE controller                                                           | 75       | 0.6%    |
| AMD FCH IDE Controller                                                                  | 75       | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 73       | 0.58%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 71       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 5427     | 56.07%  |
| IDE  | 2341     | 24.19%  |
| NVMe | 1412     | 14.59%  |
| RAID | 424      | 4.38%   |
| SAS  | 41       | 0.42%   |
| SCSI | 34       | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 4629     | 64.68%  |
| AMD          | 2526     | 35.29%  |
| CentaurHauls | 2        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 116      | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 108      | 1.5%    |
| AMD FX-8350 Eight-Core Processor            | 98       | 1.36%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 94       | 1.31%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 84       | 1.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 83       | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 82       | 1.14%   |
| AMD FX-6300 Six-Core Processor              | 80       | 1.11%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 78       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 78       | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 65       | 0.9%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 65       | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 63       | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 62       | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 60       | 0.83%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 60       | 0.83%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 58       | 0.81%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 56       | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 55       | 0.76%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 54       | 0.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 53       | 0.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 52       | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 49       | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 48       | 0.67%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 48       | 0.67%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 48       | 0.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 46       | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 43       | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 42       | 0.58%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 41       | 0.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 40       | 0.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 38       | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 37       | 0.51%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 36       | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 36       | 0.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 36       | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 35       | 0.49%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 35       | 0.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 33       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 33       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1313     | 18.28%  |
| Intel Core i7           | 877      | 12.21%  |
| AMD Ryzen 5             | 539      | 7.5%    |
| Intel Core i3           | 522      | 7.27%   |
| AMD FX                  | 383      | 5.33%   |
| AMD Ryzen 7             | 340      | 4.73%   |
| Intel Core 2 Duo        | 306      | 4.26%   |
| Intel Xeon              | 293      | 4.08%   |
| Intel Celeron           | 225      | 3.13%   |
| Intel Core 2 Quad       | 212      | 2.95%   |
| Intel Pentium           | 199      | 2.77%   |
| Other                   | 170      | 2.37%   |
| Intel Pentium Dual-Core | 158      | 2.2%    |
| AMD Ryzen 3             | 130      | 1.81%   |
| AMD Phenom II X4        | 124      | 1.73%   |
| AMD Ryzen 9             | 118      | 1.64%   |
| AMD Athlon II X2        | 100      | 1.39%   |
| AMD Athlon 64 X2        | 99       | 1.38%   |
| AMD A8                  | 80       | 1.11%   |
| AMD A10                 | 67       | 0.93%   |
| Intel Pentium Dual      | 65       | 0.9%    |
| AMD Athlon II X4        | 63       | 0.88%   |
| Intel Pentium 4         | 57       | 0.79%   |
| Intel Core 2            | 57       | 0.79%   |
| Intel Atom              | 57       | 0.79%   |
| AMD A4                  | 57       | 0.79%   |
| Intel Core i9           | 55       | 0.77%   |
| AMD A6                  | 54       | 0.75%   |
| Intel Pentium D         | 44       | 0.61%   |
| AMD Phenom II X6        | 42       | 0.58%   |
| AMD Athlon              | 40       | 0.56%   |
| AMD Phenom              | 31       | 0.43%   |
| AMD Sempron             | 28       | 0.39%   |
| AMD Athlon II X3        | 26       | 0.36%   |
| Intel Pentium Gold      | 25       | 0.35%   |
| AMD Athlon X4           | 24       | 0.33%   |
| AMD Ryzen 5 PRO         | 23       | 0.32%   |
| AMD Phenom II X2        | 18       | 0.25%   |
| AMD Ryzen Threadripper  | 16       | 0.22%   |
| AMD Athlon 64           | 14       | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2940     | 40.87%  |
| 2       | 2130     | 29.61%  |
| 6       | 908      | 12.62%  |
| 8       | 533      | 7.41%   |
| 1       | 232      | 3.23%   |
| 3       | 164      | 2.28%   |
| 12      | 145      | 2.02%   |
| 16      | 60       | 0.83%   |
| 10      | 44       | 0.61%   |
| 24      | 9        | 0.13%   |
| Unknown | 9        | 0.13%   |
| 14      | 7        | 0.1%    |
| 18      | 5        | 0.07%   |
| 20      | 3        | 0.04%   |
| 32      | 2        | 0.03%   |
| 64      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7095     | 99.13%  |
| 2      | 62       | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 3612     | 50.31%  |
| 1       | 3557     | 49.55%  |
| Unknown | 9        | 0.13%   |
| 8       | 1        | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 6781     | 93.88%  |
| Unknown        | 408      | 5.65%   |
| 32-bit         | 34       | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 784      | 10.63%  |
| 0x306c3    | 672      | 9.11%   |
| 0x206a7    | 535      | 7.25%   |
| 0x306a9    | 496      | 6.73%   |
| 0x1067a    | 436      | 5.91%   |
| 0x06000852 | 272      | 3.69%   |
| 0x506e3    | 263      | 3.57%   |
| 0x08701021 | 219      | 2.97%   |
| 0x010000c8 | 204      | 2.77%   |
| 0x906e9    | 188      | 2.55%   |
| 0x906ea    | 182      | 2.47%   |
| 0x0800820d | 164      | 2.22%   |
| 0x6fb      | 113      | 1.53%   |
| 0x06001119 | 111      | 1.51%   |
| 0x6fd      | 108      | 1.46%   |
| 0x08108109 | 88       | 1.19%   |
| 0xa0655    | 79       | 1.07%   |
| 0x08701013 | 78       | 1.06%   |
| 0x10676    | 77       | 1.04%   |
| 0x106e5    | 74       | 1%      |
| 0x010000db | 74       | 1%      |
| 0x0600063e | 72       | 0.98%   |
| 0x20655    | 66       | 0.89%   |
| 0xa0653    | 65       | 0.88%   |
| 0x08001138 | 58       | 0.79%   |
| 0x906ed    | 57       | 0.77%   |
| 0x06003106 | 55       | 0.75%   |
| 0xa0671    | 54       | 0.73%   |
| 0x20652    | 51       | 0.69%   |
| 0x0a201016 | 50       | 0.68%   |
| 0x306f2    | 49       | 0.66%   |
| 0x90672    | 47       | 0.64%   |
| 0x0a50000c | 47       | 0.64%   |
| 0x106a5    | 44       | 0.6%    |
| 0x08101016 | 44       | 0.6%    |
| 0x08001137 | 43       | 0.58%   |
| 0x03000027 | 42       | 0.57%   |
| 0x0a50000d | 41       | 0.56%   |
| 0x206d7    | 40       | 0.54%   |
| 0x206c2    | 40       | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 780      | 10.86%  |
| SandyBridge      | 607      | 8.45%   |
| Penryn           | 575      | 8%      |
| IvyBridge        | 570      | 7.93%   |
| KabyLake         | 537      | 7.47%   |
| K10              | 448      | 6.24%   |
| Piledriver       | 424      | 5.9%    |
| Zen 2            | 372      | 5.18%   |
| Core             | 313      | 4.36%   |
| Skylake          | 306      | 4.26%   |
| Zen+             | 292      | 4.06%   |
| Zen 3            | 259      | 3.61%   |
| Zen              | 232      | 3.23%   |
| Westmere         | 166      | 2.31%   |
| CometLake        | 164      | 2.28%   |
| K8 Hammer        | 142      | 1.98%   |
| Nehalem          | 134      | 1.87%   |
| Unknown          | 118      | 1.64%   |
| NetBurst         | 117      | 1.63%   |
| Bulldozer        | 79       | 1.1%    |
| Steamroller      | 73       | 1.02%   |
| Silvermont       | 67       | 0.93%   |
| Excavator        | 59       | 0.82%   |
| Alderlake Hybrid | 58       | 0.81%   |
| K10 Llano        | 45       | 0.63%   |
| Goldmont plus    | 40       | 0.56%   |
| Bonnell          | 39       | 0.54%   |
| Bobcat           | 35       | 0.49%   |
| Icelake          | 31       | 0.43%   |
| Goldmont         | 25       | 0.35%   |
| Jaguar           | 21       | 0.29%   |
| Broadwell        | 17       | 0.24%   |
| Tremont          | 16       | 0.22%   |
| Puma             | 10       | 0.14%   |
| TigerLake        | 7        | 0.1%    |
| K6               | 4        | 0.06%   |
| Gracemont        | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2951     | 38.79%  |
| Intel                                        | 2345     | 30.82%  |
| AMD                                          | 2257     | 29.67%  |
| VIA Technologies                             | 20       | 0.26%   |
| Matrox Electronics Systems                   | 14       | 0.18%   |
| Silicon Integrated Systems [SiS]             | 8        | 0.11%   |
| ATI Technologies                             | 6        | 0.08%   |
| S3 Graphics                                  | 3        | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.03%   |
| ASPEED Technology                            | 2        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 359      | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 310      | 3.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 242      | 3.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 228      | 2.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 194      | 2.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 174      | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 173      | 2.21%   |
| Intel HD Graphics 530                                                       | 159      | 2.03%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 124      | 1.58%   |
| Nvidia GT218 [GeForce 210]                                                  | 122      | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 118      | 1.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 109      | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 105      | 1.34%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 105      | 1.34%   |
| Intel HD Graphics 630                                                       | 96       | 1.23%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 89       | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 88       | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 81       | 1.03%   |
| AMD RS780L [Radeon 3000]                                                    | 77       | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                         | 76       | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 76       | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 72       | 0.92%   |
| Nvidia GK208B [GeForce GT 730]                                              | 69       | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 68       | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 68       | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 66       | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 64       | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 62       | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                               | 61       | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 59       | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 58       | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 53       | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 51       | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 50       | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 49       | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 43       | 0.55%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 42       | 0.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 40       | 0.51%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 40       | 0.51%   |
| Nvidia GF108 [GeForce GT 730]                                               | 39       | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 2773     | 38.27%  |
| 1 x Intel           | 2055     | 28.36%  |
| 1 x AMD             | 2053     | 28.33%  |
| 2 x AMD             | 100      | 1.38%   |
| Intel + Nvidia      | 70       | 0.97%   |
| AMD + Nvidia        | 63       | 0.87%   |
| Intel + AMD         | 44       | 0.61%   |
| 2 x Nvidia          | 34       | 0.47%   |
| 1 x VIA             | 20       | 0.28%   |
| 1 x Matrox          | 14       | 0.19%   |
| 1 x SiS             | 8        | 0.11%   |
| 3 x AMD             | 4        | 0.06%   |
| 1 x S3 Graphics     | 2        | 0.03%   |
| Nvidia + XGI        | 2        | 0.03%   |
| Nvidia + ASPEED     | 2        | 0.03%   |
| Intel + 2 x Nvidia  | 1        | 0.01%   |
| Intel + S3 Graphics | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 4809     | 65.82%  |
| Proprietary | 2170     | 29.7%   |
| Unknown     | 327      | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2351     | 31.81%  |
| 1.01-2.0   | 1302     | 17.62%  |
| 0.51-1.0   | 1027     | 13.9%   |
| 0.01-0.5   | 970      | 13.12%  |
| 3.01-4.0   | 672      | 9.09%   |
| 7.01-8.0   | 521      | 7.05%   |
| 5.01-6.0   | 277      | 3.75%   |
| 8.01-16.0  | 156      | 2.11%   |
| 2.01-3.0   | 93       | 1.26%   |
| 16.01-24.0 | 19       | 0.26%   |
| 4.01-5.0   | 3        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1254     | 16.8%   |
| Goldstar             | 784      | 10.5%   |
| Dell                 | 683      | 9.15%   |
| Acer                 | 576      | 7.71%   |
| Hewlett-Packard      | 520      | 6.96%   |
| AOC                  | 392      | 5.25%   |
| Ancor Communications | 353      | 4.73%   |
| BenQ                 | 335      | 4.49%   |
| Philips              | 315      | 4.22%   |
| LG Electronics       | 182      | 2.44%   |
| ViewSonic            | 152      | 2.04%   |
| Unknown              | 149      | 2%      |
| Iiyama               | 138      | 1.85%   |
| ASUSTek Computer     | 102      | 1.37%   |
| Lenovo               | 89       | 1.19%   |
| Sony                 | 88       | 1.18%   |
| Eizo                 | 78       | 1.04%   |
| Fujitsu Siemens      | 64       | 0.86%   |
| NEC Computers        | 63       | 0.84%   |
| HannStar             | 51       | 0.68%   |
| Vizio                | 43       | 0.58%   |
| Unknown              | 40       | 0.54%   |
| Sceptre Tech         | 35       | 0.47%   |
| Medion               | 35       | 0.47%   |
| Toshiba              | 34       | 0.46%   |
| MSI                  | 32       | 0.43%   |
| Vestel Elektronik    | 28       | 0.38%   |
| Panasonic            | 27       | 0.36%   |
| Idek Iiyama          | 24       | 0.32%   |
| Sharp                | 20       | 0.27%   |
| AUS                  | 20       | 0.27%   |
| Hitachi              | 19       | 0.25%   |
| Insignia             | 17       | 0.23%   |
| FUS                  | 17       | 0.23%   |
| Gigabyte Technology  | 16       | 0.21%   |
| Unknown (XXX)        | 15       | 0.2%    |
| Plain Tree Systems   | 15       | 0.2%    |
| Packard Bell         | 15       | 0.2%    |
| RTK                  | 14       | 0.19%   |
| Lenovo Group Limited | 14       | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 40       | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 39       | 0.49%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 31       | 0.39%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 28       | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 26       | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 23       | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 23       | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 21       | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 19       | 0.24%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 17       | 0.21%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 16       | 0.2%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 15       | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 15       | 0.19%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 14       | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 13       | 0.16%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 13       | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 12       | 0.15%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 12       | 0.15%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 12       | 0.15%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 12       | 0.15%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 12       | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 12       | 0.15%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 12       | 0.15%   |
| Unknown LCD Monitor SAMSUNG                                           | 11       | 0.14%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 11       | 0.14%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 11       | 0.14%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 11       | 0.14%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                     | 11       | 0.14%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 11       | 0.14%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 10       | 0.13%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 10       | 0.13%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 10       | 0.13%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 10       | 0.13%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 10       | 0.13%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 10       | 0.13%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 10       | 0.13%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 10       | 0.13%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 10       | 0.13%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                          | 10       | 0.13%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 10       | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 3207     | 43.41%  |
| 1280x1024 (SXGA)   | 578      | 7.82%   |
| 3840x2160 (4K)     | 509      | 6.89%   |
| 1680x1050 (WSXGA+) | 445      | 6.02%   |
| 1366x768 (WXGA)    | 370      | 5.01%   |
| 2560x1440 (QHD)    | 356      | 4.82%   |
| 1440x900 (WXGA+)   | 309      | 4.18%   |
| Unknown            | 263      | 3.56%   |
| 1600x900 (HD+)     | 242      | 3.28%   |
| 1920x1200 (WUXGA)  | 216      | 2.92%   |
| 1360x768           | 171      | 2.31%   |
| 2560x1080          | 103      | 1.39%   |
| 3840x1080          | 95       | 1.29%   |
| 3440x1440          | 86       | 1.16%   |
| 1024x768 (XGA)     | 66       | 0.89%   |
| 1600x1200          | 47       | 0.64%   |
| 1920x540           | 39       | 0.53%   |
| 1280x720 (HD)      | 26       | 0.35%   |
| 3200x1080          | 19       | 0.26%   |
| 3600x1080          | 15       | 0.2%    |
| 3840x1200          | 14       | 0.19%   |
| 2560x1600          | 13       | 0.18%   |
| 5760x1080          | 10       | 0.14%   |
| 4480x1440          | 9        | 0.12%   |
| 1280x960           | 9        | 0.12%   |
| 2288x1287          | 8        | 0.11%   |
| 5120x1440          | 7        | 0.09%   |
| 3840x1600          | 7        | 0.09%   |
| 3520x1080          | 7        | 0.09%   |
| 3360x1050          | 7        | 0.09%   |
| 2048x1152          | 7        | 0.09%   |
| 1152x864           | 7        | 0.09%   |
| 3286x1080          | 6        | 0.08%   |
| 1280x768           | 6        | 0.08%   |
| 5120x1080          | 5        | 0.07%   |
| 3280x1080          | 5        | 0.07%   |
| 2560x1024          | 5        | 0.07%   |
| 1280x800 (WXGA)    | 5        | 0.07%   |
| 3360x1080          | 4        | 0.05%   |
| 3120x1050          | 4        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1191     | 16.11%  |
| 24      | 871      | 11.78%  |
| 23      | 815      | 11.03%  |
| 27      | 787      | 10.65%  |
| 21      | 715      | 9.67%   |
| 19      | 511      | 6.91%   |
| 18      | 363      | 4.91%   |
| 22      | 293      | 3.96%   |
| 20      | 289      | 3.91%   |
| 17      | 276      | 3.73%   |
| 31      | 237      | 3.21%   |
| 34      | 156      | 2.11%   |
| 15      | 127      | 1.72%   |
| 84      | 97       | 1.31%   |
| 40      | 75       | 1.01%   |
| 72      | 66       | 0.89%   |
| 54      | 66       | 0.89%   |
| 32      | 66       | 0.89%   |
| 25      | 41       | 0.55%   |
| 26      | 29       | 0.39%   |
| 46      | 25       | 0.34%   |
| 16      | 22       | 0.3%    |
| 52      | 20       | 0.27%   |
| 28      | 18       | 0.24%   |
| 48      | 16       | 0.22%   |
| 37      | 16       | 0.22%   |
| 29      | 16       | 0.22%   |
| 65      | 14       | 0.19%   |
| 36      | 13       | 0.18%   |
| 39      | 12       | 0.16%   |
| 12      | 12       | 0.16%   |
| 33      | 11       | 0.15%   |
| 42      | 10       | 0.14%   |
| 47      | 9        | 0.12%   |
| 13      | 9        | 0.12%   |
| 74      | 8        | 0.11%   |
| 60      | 8        | 0.11%   |
| 55      | 8        | 0.11%   |
| 35      | 8        | 0.11%   |
| 38      | 7        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2303     | 31.99%  |
| 401-500        | 1850     | 25.7%   |
| Unknown        | 1191     | 16.55%  |
| 301-350        | 377      | 5.24%   |
| 601-700        | 360      | 5%      |
| 351-400        | 335      | 4.65%   |
| 701-800        | 245      | 3.4%    |
| 1001-1500      | 190      | 2.64%   |
| 1501-2000      | 179      | 2.49%   |
| 801-900        | 119      | 1.65%   |
| 201-300        | 25       | 0.35%   |
| 901-1000       | 19       | 0.26%   |
| More than 2000 | 5        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4050     | 58.32%  |
| Unknown | 1077     | 15.51%  |
| 16/10   | 898      | 12.93%  |
| 5/4     | 502      | 7.23%   |
| 21/9    | 171      | 2.46%   |
| 4/3     | 150      | 2.16%   |
| 3/2     | 41       | 0.59%   |
| 6/5     | 22       | 0.32%   |
| 32/9    | 20       | 0.29%   |
| 1.00    | 6        | 0.09%   |
| 1.96    | 4        | 0.06%   |
| 3.20    | 1        | 0.01%   |
| 2.00    | 1        | 0.01%   |
| 11/10   | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2176     | 29.96%  |
| Unknown        | 1191     | 16.4%   |
| 151-200        | 1019     | 14.03%  |
| 301-350        | 803      | 11.06%  |
| 141-150        | 530      | 7.3%    |
| 351-500        | 503      | 6.93%   |
| 251-300        | 322      | 4.43%   |
| More than 1000 | 317      | 4.37%   |
| 501-1000       | 193      | 2.66%   |
| 101-110        | 110      | 1.51%   |
| 131-140        | 40       | 0.55%   |
| 111-120        | 24       | 0.33%   |
| 71-80          | 13       | 0.18%   |
| 121-130        | 8        | 0.11%   |
| 81-90          | 7        | 0.1%    |
| 91-100         | 6        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4158     | 59.54%  |
| Unknown | 1191     | 17.05%  |
| 101-120 | 1059     | 15.16%  |
| 1-50    | 315      | 4.51%   |
| 121-160 | 184      | 2.63%   |
| 161-240 | 77       | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5850     | 80.13%  |
| 2     | 1011     | 13.85%  |
| 0     | 324      | 4.44%   |
| 3     | 104      | 1.42%   |
| 4     | 10       | 0.14%   |
| 6     | 1        | 0.01%   |
| 5     | 1        | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 4560     | 44.64%  |
| Intel                                  | 2495     | 24.42%  |
| Qualcomm Atheros                       | 665      | 6.51%   |
| Ralink Technology                      | 326      | 3.19%   |
| Broadcom                               | 297      | 2.91%   |
| Nvidia                                 | 238      | 2.33%   |
| TP-Link                                | 234      | 2.29%   |
| Ralink                                 | 162      | 1.59%   |
| MediaTek                               | 94       | 0.92%   |
| Marvell Technology Group               | 89       | 0.87%   |
| Qualcomm Atheros Communications        | 84       | 0.82%   |
| Broadcom Limited                       | 75       | 0.73%   |
| NetGear                                | 65       | 0.64%   |
| Samsung Electronics                    | 63       | 0.62%   |
| D-Link System                          | 62       | 0.61%   |
| D-Link                                 | 54       | 0.53%   |
| ASUSTek Computer                       | 52       | 0.51%   |
| VIA Technologies                       | 48       | 0.47%   |
| Xiaomi                                 | 39       | 0.38%   |
| Microsoft                              | 33       | 0.32%   |
| ASIX Electronics                       | 33       | 0.32%   |
| Linksys                                | 30       | 0.29%   |
| Aquantia                               | 30       | 0.29%   |
| Huawei Technologies                    | 27       | 0.26%   |
| IMC Networks                           | 25       | 0.24%   |
| Belkin Components                      | 25       | 0.24%   |
| Edimax Technology                      | 24       | 0.23%   |
| Motorola PCS                           | 19       | 0.19%   |
| AVM                                    | 19       | 0.19%   |
| Qualcomm                               | 15       | 0.15%   |
| Sundance Technology Inc / IC Plus      | 11       | 0.11%   |
| Sitecom Europe                         | 9        | 0.09%   |
| Tenda                                  | 8        | 0.08%   |
| OPPO Electronics                       | 8        | 0.08%   |
| Silicon Integrated Systems [SiS]       | 7        | 0.07%   |
| Microchip Technology                   | 7        | 0.07%   |
| DisplayLink                            | 7        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 6        | 0.06%   |
| Gemtek                                 | 6        | 0.06%   |
| Arduino SA                             | 6        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3604     | 31.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 345      | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 248      | 2.18%   |
| Intel Ethernet Connection (2) I219-V                              | 239      | 2.1%    |
| Intel I211 Gigabit Network Connection                             | 231      | 2.03%   |
| Intel Wi-Fi 6 AX200                                               | 224      | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 218      | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 155      | 1.36%   |
| Nvidia MCP61 Ethernet                                             | 149      | 1.31%   |
| Ralink MT7601U Wireless Adapter                                   | 142      | 1.25%   |
| Intel Ethernet Controller I225-V                                  | 130      | 1.14%   |
| Realtek 802.11ac NIC                                              | 121      | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 113      | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 109      | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 105      | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 102      | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 100      | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 96       | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 94       | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 91       | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 72       | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 71       | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                   | 67       | 0.59%   |
| Intel Wireless-AC 9260                                            | 63       | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 62       | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 61       | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 56       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 56       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 56       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 55       | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 53       | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 53       | 0.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 52       | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 51       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 50       | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 49       | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 49       | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 49       | 0.43%   |
| Intel Wireless 3165                                               | 46       | 0.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 898      | 25.87%  |
| Intel                                 | 795      | 22.9%   |
| Qualcomm Atheros                      | 336      | 9.68%   |
| Ralink Technology                     | 326      | 9.39%   |
| TP-Link                               | 232      | 6.68%   |
| Ralink                                | 162      | 4.67%   |
| Broadcom                              | 102      | 2.94%   |
| Qualcomm Atheros Communications       | 84       | 2.42%   |
| MediaTek                              | 78       | 2.25%   |
| NetGear                               | 65       | 1.87%   |
| D-Link                                | 53       | 1.53%   |
| ASUSTek Computer                      | 52       | 1.5%    |
| D-Link System                         | 39       | 1.12%   |
| Microsoft                             | 33       | 0.95%   |
| Linksys                               | 30       | 0.86%   |
| IMC Networks                          | 25       | 0.72%   |
| Edimax Technology                     | 24       | 0.69%   |
| Belkin Components                     | 22       | 0.63%   |
| AVM                                   | 19       | 0.55%   |
| Broadcom Limited                      | 15       | 0.43%   |
| Sitecom Europe                        | 9        | 0.26%   |
| Tenda                                 | 8        | 0.23%   |
| Gemtek                                | 6        | 0.17%   |
| ZyDAS                                 | 5        | 0.14%   |
| Texas Instruments                     | 5        | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5        | 0.14%   |
| ZyXEL Communications                  | 4        | 0.12%   |
| Marvell Technology Group              | 4        | 0.12%   |
| Accton Technology                     | 4        | 0.12%   |
| TRENDnet                              | 3        | 0.09%   |
| Mercucys                              | 3        | 0.09%   |
| Z-Com                                 | 2        | 0.06%   |
| Wacom                                 | 2        | 0.06%   |
| VIA Technologies                      | 2        | 0.06%   |
| Samsung Electronics                   | 2        | 0.06%   |
| Micro Star International              | 2        | 0.06%   |
| Guillemot                             | 2        | 0.06%   |
| Xiaomi                                | 1        | 0.03%   |
| Sagem                                 | 1        | 0.03%   |
| PLANEX                                | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 224      | 6.35%   |
| Ralink MT7601U Wireless Adapter                                | 142      | 4.03%   |
| Realtek 802.11ac NIC                                           | 121      | 3.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 105      | 2.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 96       | 2.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 94       | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 72       | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                | 67       | 1.9%    |
| Intel Wireless-AC 9260                                         | 63       | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 62       | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 61       | 1.73%   |
| Ralink RT5370 Wireless Adapter                                 | 56       | 1.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 53       | 1.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 52       | 1.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 51       | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 49       | 1.39%   |
| Intel Wireless 3165                                            | 46       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 44       | 1.25%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 42       | 1.19%   |
| Intel Wireless 7260                                            | 41       | 1.16%   |
| Intel Wireless 7265                                            | 38       | 1.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 38       | 1.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 37       | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 37       | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 33       | 0.94%   |
| Intel Wireless 8260                                            | 33       | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 31       | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 31       | 0.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 30       | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 27       | 0.77%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 27       | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 27       | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 26       | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 25       | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 25       | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 24       | 0.68%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 24       | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 23       | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                            | 23       | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 23       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 4219     | 55.62%  |
| Intel                                  | 2048     | 27%     |
| Qualcomm Atheros                       | 352      | 4.64%   |
| Nvidia                                 | 238      | 3.14%   |
| Broadcom                               | 197      | 2.6%    |
| Marvell Technology Group               | 85       | 1.12%   |
| Samsung Electronics                    | 61       | 0.8%    |
| Broadcom Limited                       | 60       | 0.79%   |
| VIA Technologies                       | 45       | 0.59%   |
| Xiaomi                                 | 38       | 0.5%    |
| ASIX Electronics                       | 33       | 0.44%   |
| Aquantia                               | 30       | 0.4%    |
| D-Link System                          | 23       | 0.3%    |
| MediaTek                               | 16       | 0.21%   |
| Huawei Technologies                    | 16       | 0.21%   |
| Motorola PCS                           | 14       | 0.18%   |
| Qualcomm                               | 13       | 0.17%   |
| Sundance Technology Inc / IC Plus      | 11       | 0.15%   |
| OPPO Electronics                       | 8        | 0.11%   |
| Silicon Integrated Systems [SiS]       | 7        | 0.09%   |
| DisplayLink                            | 7        | 0.09%   |
| Google                                 | 5        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.05%   |
| LG Electronics                         | 4        | 0.05%   |
| Apple                                  | 4        | 0.05%   |
| JMicron Technology                     | 3        | 0.04%   |
| ICS Advent                             | 3        | 0.04%   |
| 3Com                                   | 3        | 0.04%   |
| TP-Link                                | 2        | 0.03%   |
| Spreadtrum Communications              | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.03%   |
| Microchip Technology                   | 2        | 0.03%   |
| Mellanox Technologies                  | 2        | 0.03%   |
| HTC (High Tech Computer)               | 2        | 0.03%   |
| Belkin Components                      | 2        | 0.03%   |
| ADMtek                                 | 2        | 0.03%   |
| vivo                                   | 1        | 0.01%   |
| ULi Electronics                        | 1        | 0.01%   |
| Trendchip Technologies                 | 1        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3604     | 46.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 345      | 4.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 248      | 3.19%   |
| Intel Ethernet Connection (2) I219-V                              | 239      | 3.07%   |
| Intel I211 Gigabit Network Connection                             | 231      | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 218      | 2.8%    |
| Intel Ethernet Connection I217-LM                                 | 155      | 1.99%   |
| Nvidia MCP61 Ethernet                                             | 149      | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 130      | 1.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 113      | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 109      | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 102      | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 100      | 1.29%   |
| Intel Ethernet Connection I217-V                                  | 91       | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 71       | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 56       | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 56       | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 55       | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 53       | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 50       | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 49       | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 49       | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 43       | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 42       | 0.54%   |
| Intel 82578DM Gigabit Network Connection                          | 41       | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38       | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 38       | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 35       | 0.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 32       | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 31       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 29       | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 25       | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 24       | 0.31%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 23       | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 23       | 0.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 23       | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 22       | 0.28%   |
| Nvidia MCP77 Ethernet                                             | 22       | 0.28%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 22       | 0.28%   |
| Intel 82578DC Gigabit Network Connection                          | 21       | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7073     | 68.32%  |
| WiFi     | 3184     | 30.76%  |
| Modem    | 66       | 0.64%   |
| Unknown  | 29       | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5524     | 73.87%  |
| WiFi     | 1949     | 26.06%  |
| Unknown  | 4        | 0.05%   |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4985     | 69.18%  |
| 2     | 1950     | 27.06%  |
| 3     | 174      | 2.41%   |
| 0     | 69       | 0.96%   |
| 4     | 16       | 0.22%   |
| 5     | 8        | 0.11%   |
| 7     | 2        | 0.03%   |
| 10    | 1        | 0.01%   |
| 6     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 5648     | 77.57%  |
| Yes     | 1632     | 22.41%  |
| Unknown | 1        | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 716      | 34.13%  |
| Cambridge Silicon Radio         | 628      | 29.93%  |
| Realtek Semiconductor           | 193      | 9.2%    |
| Broadcom                        | 135      | 6.43%   |
| ASUSTek Computer                | 122      | 5.82%   |
| Qualcomm Atheros Communications | 68       | 3.24%   |
| MediaTek                        | 38       | 1.81%   |
| IMC Networks                    | 38       | 1.81%   |
| Lite-On Technology              | 21       | 1%      |
| TP-Link                         | 20       | 0.95%   |
| Apple                           | 20       | 0.95%   |
| Integrated System Solution      | 18       | 0.86%   |
| Foxconn / Hon Hai               | 11       | 0.52%   |
| Belkin Components               | 11       | 0.52%   |
| Edimax Technology               | 6        | 0.29%   |
| Ralink                          | 5        | 0.24%   |
| Dell                            | 5        | 0.24%   |
| Conwise Technology              | 5        | 0.24%   |
| Micro Star International        | 4        | 0.19%   |
| Logitech                        | 4        | 0.19%   |
| Dynex                           | 4        | 0.19%   |
| Unknown                         | 4        | 0.19%   |
| Realtek                         | 3        | 0.14%   |
| Roper                           | 2        | 0.1%    |
| Motorola PCS                    | 2        | 0.1%    |
| Kensington                      | 2        | 0.1%    |
| Hewlett-Packard                 | 2        | 0.1%    |
| Sitecom Europe                  | 1        | 0.05%   |
| SINO WEALTH                     | 1        | 0.05%   |
| Primax Electronics              | 1        | 0.05%   |
| Plugable                        | 1        | 0.05%   |
| Microsoft                       | 1        | 0.05%   |
| HTC (High Tech Computer)        | 1        | 0.05%   |
| Fujitsu Siemens Computers       | 1        | 0.05%   |
| D-Link System                   | 1        | 0.05%   |
| D-Link                          | 1        | 0.05%   |
| Cypress Semiconductor           | 1        | 0.05%   |
| Actions                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 627      | 29.79%  |
| Intel AX200 Bluetooth                                 | 199      | 9.45%   |
| Intel Bluetooth wireless interface                    | 168      | 7.98%   |
| Realtek Bluetooth Radio                               | 149      | 7.08%   |
| Intel Wireless-AC 3168 Bluetooth                      | 90       | 4.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 79       | 3.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 62       | 2.95%   |
| Intel AX210 Bluetooth                                 | 59       | 2.8%    |
| Intel AX201 Bluetooth                                 | 58       | 2.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 54       | 2.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 50       | 2.38%   |
| MediaTek Wireless_Device                              | 38       | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                        | 37       | 1.76%   |
| ASUS ASUS USB-BT500                                   | 25       | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 22       | 1.05%   |
| TP-Link UB500 Adapter                                 | 20       | 0.95%   |
| IMC Networks Bluetooth Radio                          | 19       | 0.9%    |
| Qualcomm Atheros  Bluetooth Device                    | 17       | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 15       | 0.71%   |
| Intel Bluetooth Device                                | 14       | 0.67%   |
| ASUS BCM20702A0                                       | 14       | 0.67%   |
| Lite-On Bluetooth Device                              | 12       | 0.57%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 12       | 0.57%   |
| Broadcom BCM2045 Bluetooth                            | 12       | 0.57%   |
| ASUS Bluetooth Radio                                  | 12       | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                     | 10       | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 9        | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 9        | 0.43%   |
| ASUS Qualcomm Bluetooth 4.1                           | 9        | 0.43%   |
| Realtek RTL8821A Bluetooth                            | 8        | 0.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 8        | 0.38%   |
| IMC Networks Wireless_Device                          | 8        | 0.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 7        | 0.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 7        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 7        | 0.33%   |
| Integrated System Solution Bluetooth Device           | 6        | 0.29%   |
| IMC Networks Bluetooth Device                         | 6        | 0.29%   |
| Apple Bluetooth Host Controller                       | 6        | 0.29%   |
| Ralink RT3290 Bluetooth                               | 5        | 0.24%   |
| Conwise CW6622                                        | 5        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 4390     | 37.49%  |
| AMD                                             | 3003     | 25.65%  |
| Nvidia                                          | 2723     | 23.26%  |
| C-Media Electronics                             | 316      | 2.7%    |
| Creative Labs                                   | 182      | 1.55%   |
| Logitech                                        | 117      | 1%      |
| Texas Instruments                               | 69       | 0.59%   |
| VIA Technologies                                | 64       | 0.55%   |
| Generalplus Technology                          | 63       | 0.54%   |
| Kingston Technology                             | 46       | 0.39%   |
| JMTek                                           | 46       | 0.39%   |
| GN Netcom                                       | 37       | 0.32%   |
| Creative Technology                             | 37       | 0.32%   |
| ASUSTek Computer                                | 36       | 0.31%   |
| Razer USA                                       | 28       | 0.24%   |
| Corsair                                         | 26       | 0.22%   |
| SteelSeries ApS                                 | 23       | 0.2%    |
| Focusrite-Novation                              | 23       | 0.2%    |
| Plantronics                                     | 19       | 0.16%   |
| Micro Star International                        | 19       | 0.16%   |
| Tenx Technology                                 | 17       | 0.15%   |
| Samson Technologies                             | 15       | 0.13%   |
| Realtek Semiconductor                           | 14       | 0.12%   |
| Sennheiser Communications                       | 13       | 0.11%   |
| Blue Microphones                                | 13       | 0.11%   |
| Silicon Integrated Systems [SiS]                | 11       | 0.09%   |
| M-Audio                                         | 11       | 0.09%   |
| Dell                                            | 11       | 0.09%   |
| BEHRINGER International                         | 11       | 0.09%   |
| XMOS                                            | 9        | 0.08%   |
| Sony                                            | 9        | 0.08%   |
| KTMicro                                         | 9        | 0.08%   |
| SAVITECH                                        | 8        | 0.07%   |
| Microsoft                                       | 8        | 0.07%   |
| Jieli Technology                                | 8        | 0.07%   |
| Ensoniq                                         | 8        | 0.07%   |
| Asahi Kasei Microsystems                        | 8        | 0.07%   |
| Yamaha                                          | 7        | 0.06%   |
| Syntek                                          | 6        | 0.05%   |
| Licensed by Sony Computer Entertainment America | 6        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 702      | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 685      | 5.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 585      | 4.31%   |
| AMD Starship/Matisse HD Audio Controller                                          | 471      | 3.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 401      | 2.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 401      | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 385      | 2.84%   |
| AMD Family 17h/19h HD Audio Controller                                            | 358      | 2.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 325      | 2.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 324      | 2.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 289      | 2.13%   |
| Intel 200 Series PCH HD Audio                                                     | 284      | 2.09%   |
| AMD FCH Azalia Controller                                                         | 280      | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 253      | 1.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 225      | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 224      | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 194      | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                        | 192      | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 187      | 1.38%   |
| Nvidia High Definition Audio Controller                                           | 175      | 1.29%   |
| Nvidia MCP61 High Definition Audio                                                | 172      | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 171      | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 164      | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                     | 143      | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 140      | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 130      | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 129      | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 129      | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                     | 127      | 0.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 126      | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 125      | 0.92%   |
| Nvidia GP108 High Definition Audio Controller                                     | 124      | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                                     | 122      | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 122      | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 120      | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 102      | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                | 90       | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                | 90       | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                     | 87       | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                                     | 87       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 560      | 16.83%  |
| Unknown             | 537      | 16.14%  |
| Corsair             | 403      | 12.11%  |
| SK hynix            | 294      | 8.83%   |
| Crucial             | 290      | 8.71%   |
| Samsung Electronics | 284      | 8.53%   |
| G.Skill             | 273      | 8.2%    |
| Micron Technology   | 128      | 3.85%   |
| A-DATA Technology   | 66       | 1.98%   |
| Team                | 57       | 1.71%   |
| Nanya Technology    | 48       | 1.44%   |
| Patriot             | 43       | 1.29%   |
| Ramaxel Technology  | 27       | 0.81%   |
| Unknown             | 27       | 0.81%   |
| Elpida              | 24       | 0.72%   |
| GOODRAM             | 20       | 0.6%    |
| AMD                 | 19       | 0.57%   |
| Unknown (ABCD)      | 18       | 0.54%   |
| Transcend           | 16       | 0.48%   |
| Kingmax             | 12       | 0.36%   |
| Unifosa             | 11       | 0.33%   |
| Smart               | 11       | 0.33%   |
| GeIL                | 10       | 0.3%    |
| PNY                 | 9        | 0.27%   |
| Apacer              | 9        | 0.27%   |
| Silicon Power       | 7        | 0.21%   |
| Teikon              | 5        | 0.15%   |
| Sesame              | 5        | 0.15%   |
| Multilaser          | 5        | 0.15%   |
| Atermiter           | 5        | 0.15%   |
| Wilk Elektronik     | 4        | 0.12%   |
| TakeMS              | 4        | 0.12%   |
| OCZ                 | 4        | 0.12%   |
| Kllisre             | 4        | 0.12%   |
| CSX                 | 4        | 0.12%   |
| Avant               | 4        | 0.12%   |
| V-Color             | 3        | 0.09%   |
| Unknown (0x8551)    | 3        | 0.09%   |
| Ramos Technology    | 3        | 0.09%   |
| Qumo                | 3        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 38       | 1.04%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 33       | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 30       | 0.82%   |
| Unknown                                                        | 27       | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 23       | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 23       | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 22       | 0.6%    |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 21       | 0.58%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 21       | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 21       | 0.58%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 20       | 0.55%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 20       | 0.55%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 20       | 0.55%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 18       | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 18       | 0.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 18       | 0.49%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 18       | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 17       | 0.47%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 16       | 0.44%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 15       | 0.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 15       | 0.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 15       | 0.41%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 14       | 0.38%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 14       | 0.38%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 14       | 0.38%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s         | 14       | 0.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 13       | 0.36%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 13       | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 12       | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 12       | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 12       | 0.33%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 12       | 0.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 12       | 0.33%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 12       | 0.33%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 12       | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 11       | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 11       | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                    | 11       | 0.3%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 11       | 0.3%    |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s          | 11       | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1211     | 41.42%  |
| DDR3         | 1068     | 36.53%  |
| Unknown      | 211      | 7.22%   |
| DDR2         | 189      | 6.46%   |
| SDRAM        | 142      | 4.86%   |
| DDR          | 39       | 1.33%   |
| DDR5         | 38       | 1.3%    |
| LPDDR4       | 22       | 0.75%   |
| DRAM         | 2        | 0.07%   |
| LPDDR3       | 1        | 0.03%   |
| DDR2 FB-DIMM | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2687     | 93.75%  |
| SODIMM       | 166      | 5.79%   |
| FB-DIMM      | 8        | 0.28%   |
| RIMM         | 3        | 0.1%    |
| Row Of Chips | 2        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1140     | 36.1%   |
| 4096  | 817      | 25.87%  |
| 2048  | 528      | 16.72%  |
| 16384 | 397      | 12.57%  |
| 1024  | 132      | 4.18%   |
| 32768 | 119      | 3.77%   |
| 512   | 20       | 0.63%   |
| 1536  | 2        | 0.06%   |
| 256   | 2        | 0.06%   |
| 16    | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 583      | 17.94%  |
| 1333    | 477      | 14.68%  |
| 3200    | 256      | 7.88%   |
| 2400    | 193      | 5.94%   |
| 3600    | 179      | 5.51%   |
| 800     | 149      | 4.58%   |
| 2133    | 146      | 4.49%   |
| 2667    | 137      | 4.22%   |
| 667     | 101      | 3.11%   |
| 1867    | 74       | 2.28%   |
| Unknown | 74       | 2.28%   |
| 1800    | 70       | 2.15%   |
| 3000    | 63       | 1.94%   |
| 1866    | 55       | 1.69%   |
| 2933    | 54       | 1.66%   |
| 3733    | 53       | 1.63%   |
| 3400    | 44       | 1.35%   |
| 2666    | 34       | 1.05%   |
| 1066    | 33       | 1.02%   |
| 3866    | 29       | 0.89%   |
| 3800    | 29       | 0.89%   |
| 3266    | 27       | 0.83%   |
| 3533    | 25       | 0.77%   |
| 2800    | 24       | 0.74%   |
| 3466    | 21       | 0.65%   |
| 400     | 20       | 0.62%   |
| 1067    | 19       | 0.58%   |
| 4800    | 16       | 0.49%   |
| 3666    | 14       | 0.43%   |
| 1334    | 14       | 0.43%   |
| 3534    | 13       | 0.4%    |
| 333     | 12       | 0.37%   |
| 2733    | 11       | 0.34%   |
| 2048    | 11       | 0.34%   |
| 2000    | 10       | 0.31%   |
| 1648    | 10       | 0.31%   |
| 1639    | 9        | 0.28%   |
| 533     | 8        | 0.25%   |
| 6000    | 7        | 0.22%   |
| 4000    | 7        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 184      | 35.05%  |
| Brother Industries       | 122      | 23.24%  |
| Canon                    | 80       | 15.24%  |
| Seiko Epson              | 46       | 8.76%   |
| Samsung Electronics      | 40       | 7.62%   |
| QinHeng Electronics      | 7        | 1.33%   |
| Prolific Technology      | 6        | 1.14%   |
| Pantum                   | 6        | 1.14%   |
| Dymo-CoStar              | 6        | 1.14%   |
| Xerox                    | 4        | 0.76%   |
| Ricoh                    | 4        | 0.76%   |
| Panasonic (Matsushita)   | 3        | 0.57%   |
| Seiko Instruments        | 2        | 0.38%   |
| Oki Data                 | 2        | 0.38%   |
| Lexmark International    | 2        | 0.38%   |
| Kyocera                  | 2        | 0.38%   |
| Dell                     | 2        | 0.38%   |
| Zebra                    | 1        | 0.19%   |
| Sato                     | 1        | 0.19%   |
| NXP Semiconductors       | 1        | 0.19%   |
| Magic Control Technology | 1        | 0.19%   |
| Fuji Xerox               | 1        | 0.19%   |
| Agere Systems (Lucent)   | 1        | 0.19%   |
| Unknown                  | 1        | 0.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP LaserJet 1020                   | 8        | 1.51%   |
| Brother Printer                    | 8        | 1.51%   |
| Samsung M2070 Series               | 7        | 1.32%   |
| Samsung M2020 Series               | 7        | 1.32%   |
| QinHeng CH340S                     | 7        | 1.32%   |
| HP DeskJet 2600 series             | 7        | 1.32%   |
| Canon LiDE 400                     | 7        | 1.32%   |
| Prolific PL2305 Parallel Port      | 6        | 1.13%   |
| HP LaserJet Professional P1102w    | 6        | 1.13%   |
| HP LaserJet P1005                  | 6        | 1.13%   |
| Brother HL-L2360D series           | 6        | 1.13%   |
| Seiko Epson ET-2710 Series         | 5        | 0.95%   |
| HP OfficeJet 5200 series           | 5        | 0.95%   |
| HP Officejet 4500 G510n-z          | 5        | 0.95%   |
| HP LaserJet 1018                   | 5        | 0.95%   |
| Brother HL-2270DW Laser Printer    | 5        | 0.95%   |
| Seiko Epson L210 Series            | 4        | 0.76%   |
| Samsung SCX-3400 Series            | 4        | 0.76%   |
| Samsung C48x Series                | 4        | 0.76%   |
| HP Officejet 4620 series           | 4        | 0.76%   |
| HP LaserJet Professional P 1102w   | 4        | 0.76%   |
| HP LaserJet P1102                  | 4        | 0.76%   |
| HP ENVY 5000 series                | 4        | 0.76%   |
| HP DeskJet F4200 series            | 4        | 0.76%   |
| HP Deskjet 2050 J510               | 4        | 0.76%   |
| Brother HL-1210W series            | 4        | 0.76%   |
| Brother DCP-7055 scanner/printer   | 4        | 0.76%   |
| Seiko Epson L3110 Series           | 3        | 0.57%   |
| Panasonic (Matsushita) KX-MB1500RU | 3        | 0.57%   |
| HP OfficeJet Pro 8020 series       | 3        | 0.57%   |
| HP OfficeJet Pro 69                | 3        | 0.57%   |
| HP LaserJet P2014                  | 3        | 0.57%   |
| HP ENVY 5540 series                | 3        | 0.57%   |
| HP ENVY 4520 series                | 3        | 0.57%   |
| HP DeskJet 3630 series             | 3        | 0.57%   |
| HP DeskJet 2700 series             | 3        | 0.57%   |
| HP Deskjet 2540 series             | 3        | 0.57%   |
| HP DeskJet 2130 series             | 3        | 0.57%   |
| Canon TR4500 series                | 3        | 0.57%   |
| Canon PIXMA MX530 Series           | 3        | 0.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 84       | 58.74%  |
| Seiko Epson                 | 28       | 19.58%  |
| Hewlett-Packard             | 15       | 10.49%  |
| Mustek Systems              | 6        | 4.2%    |
| Ultima Electronics          | 2        | 1.4%    |
| AGFA-Gevaert NV             | 2        | 1.4%    |
| Acer Peripherals (now BenQ) | 2        | 1.4%    |
| UMAX                        | 1        | 0.7%    |
| Salix Technology            | 1        | 0.7%    |
| Plustek                     | 1        | 0.7%    |
| Microtek International      | 1        | 0.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 13       | 9.09%   |
| Canon CanoScan LIDE 25                                                                | 10       | 6.99%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 5.59%   |
| Canon CanoScan LiDE 120                                                               | 8        | 5.59%   |
| Canon CanoScan LiDE 220                                                               | 7        | 4.9%    |
| Canon CanoScan LiDE 210                                                               | 7        | 4.9%    |
| Canon CanoScan LiDE 60                                                                | 5        | 3.5%    |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4        | 2.8%    |
| Mustek Systems ScanExpress 1200 UB                                                    | 4        | 2.8%    |
| Canon CanoScan LiDE 700F                                                              | 4        | 2.8%    |
| Canon CanoScan LiDE 200                                                               | 4        | 2.8%    |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3        | 2.1%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3        | 2.1%    |
| Canon CanoScan LiDE 90                                                                | 3        | 2.1%    |
| Canon CanoScan LiDE 100                                                               | 3        | 2.1%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 1.4%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2        | 1.4%    |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 2        | 1.4%    |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2        | 1.4%    |
| Mustek Systems SNAPSCAN e22                                                           | 2        | 1.4%    |
| HP ScanJet 3800c                                                                      | 2        | 1.4%    |
| HP Scanjet 300                                                                        | 2        | 1.4%    |
| HP ScanJet 2400c                                                                      | 2        | 1.4%    |
| HP ScanJet 2200c                                                                      | 2        | 1.4%    |
| Canon CanoScan N650U/N656U                                                            | 2        | 1.4%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 1.4%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2        | 1.4%    |
| Canon CanoScan 9000F Mark II                                                          | 2        | 1.4%    |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2        | 1.4%    |
| UMAX Astra 4400/4450                                                                  | 1        | 0.7%    |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 0.7%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 0.7%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 0.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 0.7%    |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1        | 0.7%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 0.7%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 0.7%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 0.7%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 0.7%    |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 0.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 496      | 34.81%  |
| Microdia                      | 135      | 9.47%   |
| Microsoft                     | 96       | 6.74%   |
| Samsung Electronics           | 69       | 4.84%   |
| Sunplus Innovation Technology | 47       | 3.3%    |
| Generalplus Technology        | 46       | 3.23%   |
| Z-Star Microelectronics       | 40       | 2.81%   |
| Chicony Electronics           | 40       | 2.81%   |
| Realtek Semiconductor         | 29       | 2.04%   |
| Creative Technology           | 29       | 2.04%   |
| Apple                         | 29       | 2.04%   |
| KYE Systems (Mouse Systems)   | 28       | 1.96%   |
| GEMBIRD                       | 25       | 1.75%   |
| ARC International             | 21       | 1.47%   |
| Aveo Technology               | 19       | 1.33%   |
| IMC Networks                  | 16       | 1.12%   |
| MacroSilicon                  | 15       | 1.05%   |
| Arkmicro Technologies         | 14       | 0.98%   |
| Cubeternet                    | 13       | 0.91%   |
| Jieli Technology              | 11       | 0.77%   |
| Sonix Technology              | 10       | 0.7%    |
| Genesys Logic                 | 10       | 0.7%    |
| LG Electronics                | 9        | 0.63%   |
| Alcor Micro                   | 9        | 0.63%   |
| Trust                         | 8        | 0.56%   |
| Hewlett-Packard               | 8        | 0.56%   |
| Guillemot                     | 8        | 0.56%   |
| Philips (or NXP)              | 7        | 0.49%   |
| Pixart Imaging                | 6        | 0.42%   |
| Novatek Microelectronics      | 6        | 0.42%   |
| Huawei Technologies           | 6        | 0.42%   |
| AVerMedia Technologies        | 6        | 0.42%   |
| SunplusIT                     | 5        | 0.35%   |
| Silicon Motion                | 5        | 0.35%   |
| HD 2MP WEBCAM                 | 5        | 0.35%   |
| WaveRider Communications      | 4        | 0.28%   |
| SHENZHEN EMEET TECHNOLOGY     | 4        | 0.28%   |
| HD USB Camera                 | 4        | 0.28%   |
| eMeet                         | 4        | 0.28%   |
| Asuscom Network               | 4        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 121      | 8.46%   |
| Samsung Galaxy series, misc. (MTP mode)           | 69       | 4.83%   |
| Logitech HD Pro Webcam C920                       | 51       | 3.57%   |
| Microsoft LifeCam HD-3000                         | 40       | 2.8%    |
| Microdia Webcam Vitade AF                         | 37       | 2.59%   |
| Microdia USB 2.0 Camera                           | 29       | 2.03%   |
| Logitech Webcam C310                              | 29       | 2.03%   |
| Logitech HD Webcam C525                           | 29       | 2.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 28       | 1.96%   |
| Logitech Webcam C170                              | 27       | 1.89%   |
| Generalplus GENERAL WEBCAM                        | 25       | 1.75%   |
| Sunplus Full HD webcam                            | 22       | 1.54%   |
| Microdia Camera                                   | 21       | 1.47%   |
| ARC International Camera                          | 21       | 1.47%   |
| Logitech HD Webcam C615                           | 19       | 1.33%   |
| Logitech C922 Pro Stream Webcam                   | 19       | 1.33%   |
| Logitech C920 PRO HD Webcam                       | 18       | 1.26%   |
| Microdia Sonix USB 2.0 Camera                     | 16       | 1.12%   |
| Z-Star Venus USB2.0 Camera                        | 15       | 1.05%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 15       | 1.05%   |
| Logitech Webcam C930e                             | 14       | 0.98%   |
| Logitech Webcam C210                              | 14       | 0.98%   |
| Sunplus MTD Camera                                | 13       | 0.91%   |
| Logitech BRIO Ultra HD Webcam                     | 13       | 0.91%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 13       | 0.91%   |
| Logitech Webcam C925e                             | 12       | 0.84%   |
| Chicony HP High Definition 1MP Webcam             | 12       | 0.84%   |
| Realtek Full HD webcam                            | 11       | 0.77%   |
| Microsoft LifeCam Cinema                          | 11       | 0.77%   |
| Logitech QuickCam Pro 9000                        | 11       | 0.77%   |
| Jieli USB PHY 2.0                                 | 11       | 0.77%   |
| IMC Networks XHC Camera                           | 11       | 0.77%   |
| Microsoft LifeCam HD-5000                         | 10       | 0.7%    |
| MacroSilicon USB Video                            | 10       | 0.7%    |
| GEMBIRD USB2.0 PC CAMERA                          | 10       | 0.7%    |
| Arkmicro USB2.0 PC CAMERA                         | 10       | 0.7%    |
| Microdia Integrated Camera                        | 9        | 0.63%   |
| Logitech HD Webcam C510                           | 9        | 0.63%   |
| Logitech Webcam Pro 9000                          | 8        | 0.56%   |
| Logitech Webcam C200                              | 8        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 4        | 26.67%  |
| STMicroelectronics         | 2        | 13.33%  |
| LighTuning Technology      | 2        | 13.33%  |
| AuthenTec                  | 2        | 13.33%  |
| Upek                       | 1        | 6.67%   |
| Synaptics                  | 1        | 6.67%   |
| Shenzhen Goodix Technology | 1        | 6.67%   |
| Microsoft                  | 1        | 6.67%   |
| Dell                       | 1        | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 4        | 26.67%  |
| STMicroelectronics Fingerprint Reader                  | 2        | 13.33%  |
| LighTuning Fingerprint Sensor                          | 2        | 13.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 6.67%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 6.67%   |
| Microsoft Fingerprint Reader                           | 1        | 6.67%   |
| Dell MS819 Wired Mouse With Fingerprint Reader         | 1        | 6.67%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1        | 6.67%   |
| AuthenTec AES1600                                      | 1        | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 14       | 30.43%  |
| OmniKey                           | 5        | 10.87%  |
| SCM Microsystems                  | 4        | 8.7%    |
| Gemalto (was Gemplus)             | 4        | 8.7%    |
| Advanced Card Systems             | 3        | 6.52%   |
| Reiner SCT Kartensysteme          | 2        | 4.35%   |
| Realtek Semiconductor             | 2        | 4.35%   |
| Chicony Electronics               | 2        | 4.35%   |
| VASCO Data Security International | 1        | 2.17%   |
| Precise Biometrics                | 1        | 2.17%   |
| In Focus Systems                  | 1        | 2.17%   |
| Hewlett-Packard                   | 1        | 2.17%   |
| Giesecke & Devrient               | 1        | 2.17%   |
| Fujitsu Siemens Computers         | 1        | 2.17%   |
| Bit4id                            | 1        | 2.17%   |
| Aladdin R.D.                      | 1        | 2.17%   |
| Aladdin Knowledge Systems         | 1        | 2.17%   |
| Aktiv                             | 1        | 2.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                                               | 7        | 15.22%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 7        | 15.22%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 8.7%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 6.52%   |
| OmniKey CardMan 3021 / 3121                                                | 3        | 6.52%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 2        | 4.35%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 4.35%   |
| Advanced Card Systems ACR122U                                              | 2        | 4.35%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 2.17%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.17%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 1        | 2.17%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.17%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                 | 1        | 2.17%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.17%   |
| OmniKey CardMan 1021                                                       | 1        | 2.17%   |
| In Focus Systems EMV Smartcard Reader                                      | 1        | 2.17%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 1        | 2.17%   |
| Giesecke & Devrient StarSign CUT                                           | 1        | 2.17%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.17%   |
| Bit4id miniLector-s                                                        | 1        | 2.17%   |
| Aladdin R.D. JaCarta                                                       | 1        | 2.17%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 2.17%   |
| Aktiv Rutoken lite                                                         | 1        | 2.17%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 5990     | 81.6%   |
| 1     | 1131     | 15.41%  |
| 2     | 170      | 2.32%   |
| 3     | 32       | 0.44%   |
| 4     | 10       | 0.14%   |
| 5     | 6        | 0.08%   |
| 6     | 2        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 512      | 32.99%  |
| Net/wireless             | 444      | 28.61%  |
| Communication controller | 149      | 9.6%    |
| Multimedia controller    | 63       | 4.06%   |
| Unassigned class         | 60       | 3.87%   |
| Sound                    | 54       | 3.48%   |
| Bluetooth                | 36       | 2.32%   |
| Network                  | 34       | 2.19%   |
| Chipcard                 | 31       | 2%      |
| Camera                   | 29       | 1.87%   |
| Net/ethernet             | 27       | 1.74%   |
| Storage/raid             | 23       | 1.48%   |
| Card reader              | 22       | 1.42%   |
| Storage/ide              | 21       | 1.35%   |
| Modem                    | 13       | 0.84%   |
| Fingerprint reader       | 12       | 0.77%   |
| Dvb card                 | 7        | 0.45%   |
| Firewire controller      | 5        | 0.32%   |
| Unclassified device      | 3        | 0.19%   |
| Tv card                  | 2        | 0.13%   |
| Storage/nvme             | 2        | 0.13%   |
| Storage/ata              | 2        | 0.13%   |
| Video                    | 1        | 0.06%   |

