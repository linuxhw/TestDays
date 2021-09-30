CentOS 8 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=centos-8

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| Unknown       | Unknown                     | [7baf2629b9](https://linux-hardware.org/?probe=7baf2629b9) | Sep 26, 2021 |
| ASRock        | Z77 Extreme4                | [b603b360a4](https://linux-hardware.org/?probe=b603b360a4) | Sep 25, 2021 |
| Dell          | 0FM586                      | [5ec44ec202](https://linux-hardware.org/?probe=5ec44ec202) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [976ca14e35](https://linux-hardware.org/?probe=976ca14e35) | Sep 19, 2021 |
| ASRock        | Z77 Extreme4                | [36129a77bf](https://linux-hardware.org/?probe=36129a77bf) | Sep 18, 2021 |
| ASRock        | Z77 Extreme4                | [b59cb8f7f5](https://linux-hardware.org/?probe=b59cb8f7f5) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [4720c56d37](https://linux-hardware.org/?probe=4720c56d37) | Sep 15, 2021 |
| HP            | 8750                        | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| ASRock        | Z77 Extreme4                | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| MSI           | MAG B550M MORTAR            | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | [13bd66cba7](https://linux-hardware.org/?probe=13bd66cba7) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| ASRock        | A320M-HD                    | [775b415921](https://linux-hardware.org/?probe=775b415921) | Aug 08, 2021 |
| ASRock        | A320M-HD                    | [d68ac72e1d](https://linux-hardware.org/?probe=d68ac72e1d) | Aug 03, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | [ff76aecb8e](https://linux-hardware.org/?probe=ff76aecb8e) | Jul 12, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| ASRock        | A320M-HD                    | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| Dell          | 0M5DCD A00                  | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| Dell          | 0200DY A02                  | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| HP            | 18E7                        | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| MSI           | MAG B550M MORTAR            | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| ASUSTek       | PRIME X570-PRO              | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| ASUSTek       | Z97-E/USB                   | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| ASUSTek       | Z97-E/USB                   | [561d33760f](https://linux-hardware.org/?probe=561d33760f) | Mar 31, 2021 |
| ASRock        | X570 Steel Legend           | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| ASRock        | X570 Steel Legend           | [60fa73286f](https://linux-hardware.org/?probe=60fa73286f) | Mar 29, 2021 |
| Gigabyte      | Z490 GAMING X               | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| Dell          | 0NC2VH A01                  | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-R               | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| ASUSTek       | Z97-E/USB                   | [b979ba17d1](https://linux-hardware.org/?probe=b979ba17d1) | Mar 07, 2021 |
| ASUSTek       | Z97-E/USB                   | [47a56b26e5](https://linux-hardware.org/?probe=47a56b26e5) | Mar 07, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Supermicro    | X9SCI/X9SCA                 | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| ASUSTek       | Z97-E/USB                   | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| Gigabyte      | MZBSWMP-00                  | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| ASUSTek       | Z97-E/USB                   | [494eafb565](https://linux-hardware.org/?probe=494eafb565) | Feb 03, 2021 |
| ASUSTek       | Z97-E/USB                   | [59f3594f3d](https://linux-hardware.org/?probe=59f3594f3d) | Jan 28, 2021 |
| ASUSTek       | Z97-E/USB                   | [17fef649e3](https://linux-hardware.org/?probe=17fef649e3) | Jan 25, 2021 |
| ASRock        | X570 Steel Legend           | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [996727413b](https://linux-hardware.org/?probe=996727413b) | Jan 17, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [20c1a73c0e](https://linux-hardware.org/?probe=20c1a73c0e) | Jan 14, 2021 |
| ASUSTek       | GD30CI                      | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASRock        | X570 Steel Legend           | [6371149c87](https://linux-hardware.org/?probe=6371149c87) | Jan 08, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| ASRock        | X570 Steel Legend           | [dcd24f778c](https://linux-hardware.org/?probe=dcd24f778c) | Jan 03, 2021 |
| ASRock        | X570 Steel Legend           | [16fc91341e](https://linux-hardware.org/?probe=16fc91341e) | Dec 31, 2020 |
| ASRock        | X570 Steel Legend           | [91ed18105e](https://linux-hardware.org/?probe=91ed18105e) | Dec 31, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [34a96782e3](https://linux-hardware.org/?probe=34a96782e3) | Dec 28, 2020 |
| ASRock        | X570 Steel Legend           | [384c4a8068](https://linux-hardware.org/?probe=384c4a8068) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASRock        | X570 Steel Legend           | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| ASUSTek       | Z170-A                      | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| HP            | 81C9                        | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| ASUSTek       | PRIME X370-PRO              | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| ASUSTek       | PRIME X570-P                | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Supermicro    | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| ASUSTek       | P9X79                       | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| MSI           | B450I GAMING PLUS AC        | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | Berkeley                    | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| Gigabyte      | A320M-S2H-CF                | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| HP            | 8053                        | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Intel         | D54250WYK H13922-303        | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| HP            | 0B54h D                     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| ASUSTek       | Z97-E/USB                   | [2da17db4c1](https://linux-hardware.org/?probe=2da17db4c1) | Aug 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| MSI           | B350M PRO-VDH               | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| Gigabyte      | A320M-S2H-CF                | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| Gigabyte      | H97-HD3                     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| ASUSTek       | Z97-E/USB                   | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| Dell          | 0YXT71 A02                  | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 073MMW A00                  | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Gigabyte      | EP45-DS3R                   | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| Unknown       | IPM31-AK                    | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| ASUSTek       | P8Z77-V                     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| ASRock        | Z170 Extreme7+              | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| MSI           | 2A9C                        | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Packard Be... | MCP73VT-PM                  | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| ASRock        | X399 Professional Gaming    | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [0436cc9607](https://linux-hardware.org/?probe=0436cc9607) | Jun 03, 2020 |
| Intel         | DP45SG AAE27733-405         | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6d648c7448](https://linux-hardware.org/?probe=6d648c7448) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [22c1a49189](https://linux-hardware.org/?probe=22c1a49189) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| Dell          | 0YXT71 A02                  | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| Supermicro    | X10DAI                      | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| Lenovo        | MAHOBAY                     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| Foxconn       | 17A0                        | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Biostar       | A320MH                      | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Foxconn       | 2A8C                        | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| ASRockRack    | EP2C612 WS                  | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| Dell          | 0YXT71 A02                  | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [bb9f29477a](https://linux-hardware.org/?probe=bb9f29477a) | Apr 07, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| Gigabyte      | EX58-EXTREME                | [d2b19a4a0f](https://linux-hardware.org/?probe=d2b19a4a0f) | Feb 24, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Supermicro    | X10DAI                      | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| Gigabyte      | Z77X-UD5H                   | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Foxconn       | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| Gigabyte      | EP45-DS4                    | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| MSI           | H55M-E33                    | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | 0PC5F7 A01                  | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | Benicia                     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| HP            | ProLiant MicroServer        | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| ASUSTek       | Benicia                     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| Gigabyte      | X58A-UD5                    | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Desktops | Percent |
|------------------------------------------|----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64              | 13       | 9.09%   |
| 4.18.0-193.6.3.el8_2.x86_64              | 12       | 8.39%   |
| 4.18.0-193.14.2.el8_2.x86_64             | 12       | 8.39%   |
| 4.18.0-80.11.2.el8_0.x86_64              | 9        | 6.29%   |
| 4.18.0-193.28.1.el8_2.x86_64             | 9        | 6.29%   |
| 4.18.0-193.19.1.el8_2.x86_64             | 9        | 6.29%   |
| 4.18.0-147.5.1.el8_1.x86_64              | 7        | 4.9%    |
| 4.18.0-240.15.1.el8_3.x86_64             | 6        | 4.2%    |
| 4.18.0-240.10.1.el8_3.x86_64             | 6        | 4.2%    |
| 4.18.0-240.1.1.el8_3.x86_64              | 6        | 4.2%    |
| 4.18.0-240.22.1.el8_3.x86_64             | 5        | 3.5%    |
| 4.18.0-305.12.1.el8_4.x86_64             | 4        | 2.8%    |
| 4.18.0-301.1.el8.x86_64                  | 4        | 2.8%    |
| 4.18.0-147.el8.x86_64                    | 4        | 2.8%    |
| 4.18.0-315.el8.x86_64                    | 3        | 2.1%    |
| 4.18.0-80.el8.x86_64                     | 2        | 1.4%    |
| 4.18.0-305.7.1.el8_4.x86_64              | 2        | 1.4%    |
| 4.18.0-305.19.1.el8_4.x86_64             | 2        | 1.4%    |
| 4.18.0-305.10.2.el8_4.x86_64             | 2        | 1.4%    |
| 4.18.0-294.el8.x86_64                    | 2        | 1.4%    |
| 4.18.0-277.el8.x86_64                    | 2        | 1.4%    |
| 4.18.0-240.el8.x86_64                    | 2        | 1.4%    |
| 4.18.0-193.10.el8.x86_64                 | 2        | 1.4%    |
| 4.18.0-147.3.1.el8_1.x86_64              | 2        | 1.4%    |
| 5.13.11-1.el8.elrepo.x86_64              | 1        | 0.7%    |
| 5.10.3-1.el8.elrepo.x86_64               | 1        | 0.7%    |
| 4.18.0-80.7.1.el8_0.x86_64               | 1        | 0.7%    |
| 4.18.0-338.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-326.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-305.0.1.el8.x86_64                | 1        | 0.7%    |
| 4.18.0-269.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-259.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-257.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-240.10.1.el8_3.centos.plus.x86_64 | 1        | 0.7%    |
| 4.18.0-193.14.2.el8_2.x86_64+debug       | 1        | 0.7%    |
| 4.18.0-177.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-168.el8.x86_64                    | 1        | 0.7%    |
| 4.18.0-147.6.el8.x86_64                  | 1        | 0.7%    |
| 4.18.0-144.el8.x86_64                    | 1        | 0.7%    |
| 3.10.0-1062.4.1.el7.x86_64               | 1        | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 123      | 97.62%  |
| 5.13.11 | 1        | 0.79%   |
| 5.10.3  | 1        | 0.79%   |
| 3.10.0  | 1        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 123      | 97.62%  |
| 5.13    | 1        | 0.79%   |
| 5.10    | 1        | 0.79%   |
| 3.10    | 1        | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 126      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 93       | 72.09%  |
| Unknown       | 20       | 15.5%   |
| GNOME Classic | 9        | 6.98%   |
| XFCE          | 5        | 3.88%   |
| KDE5          | 2        | 1.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 62       | 46.97%  |
| X11     | 51       | 38.64%  |
| Unknown | 19       | 14.39%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 67.72%  |
| GDM     | 40       | 31.5%   |
| LightDM | 1        | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 70       | 53.85%  |
| Unknown     | 12       | 9.23%   |
| en_GB       | 9        | 6.92%   |
| de_DE       | 7        | 5.38%   |
| pl_PL       | 5        | 3.85%   |
| ru_RU       | 3        | 2.31%   |
| pt_BR       | 3        | 2.31%   |
| fr_FR       | 3        | 2.31%   |
| es_PE       | 2        | 1.54%   |
| en_CA       | 2        | 1.54%   |
| en_AU       | 2        | 1.54%   |
| uk_UA       | 1        | 0.77%   |
| tr_TR       | 1        | 0.77%   |
| sl_SI       | 1        | 0.77%   |
| ko_KR       | 1        | 0.77%   |
| it_IT       | 1        | 0.77%   |
| hu_HU       | 1        | 0.77%   |
| fr_CA       | 1        | 0.77%   |
| fi_FI       | 1        | 0.77%   |
| en_US.utf-8 | 1        | 0.77%   |
| de_LU       | 1        | 0.77%   |
| de_CH       | 1        | 0.77%   |
| C           | 1        | 0.77%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 67       | 53.17%  |
| EFI  | 59       | 46.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 114      | 90.48%  |
| Ext4 | 12       | 9.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 55.47%  |
| GPT     | 39       | 30.47%  |
| MBR     | 18       | 14.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 90.55%  |
| Yes       | 12       | 9.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 88.1%   |
| Yes       | 15       | 11.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 28       | 22.22%  |
| ASUSTek Computer    | 28       | 22.22%  |
| Dell                | 15       | 11.9%   |
| Hewlett-Packard     | 14       | 11.11%  |
| MSI                 | 12       | 9.52%   |
| ASRock              | 7        | 5.56%   |
| Supermicro          | 5        | 3.97%   |
| Intel               | 3        | 2.38%   |
| Foxconn             | 3        | 2.38%   |
| Unknown             | 3        | 2.38%   |
| Lenovo              | 2        | 1.59%   |
| Fujitsu             | 2        | 1.59%   |
| Packard Bell        | 1        | 0.79%   |
| Biostar             | 1        | 0.79%   |
| ASRockRack          | 1        | 0.79%   |
| Apple               | 1        | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 3        | 2.38%   |
| Supermicro SYS-7048A-T                  | 2        | 1.59%   |
| HP Compaq 8200 Elite SFF PC             | 2        | 1.59%   |
| Gigabyte X470 AORUS ULTRA GAMING        | 2        | 1.59%   |
| Gigabyte A320M-S2H                      | 2        | 1.59%   |
| Dell OptiPlex 7010                      | 2        | 1.59%   |
| ASUS TUF B450M-PRO GAMING               | 2        | 1.59%   |
| ASUS PRIME X570-P                       | 2        | 1.59%   |
| ASUS All Series                         | 2        | 1.59%   |
| Supermicro X9SCI/X9SCA                  | 1        | 0.79%   |
| Supermicro X8SIL                        | 1        | 0.79%   |
| Supermicro X8SAX                        | 1        | 0.79%   |
| Packard Bell IMEDIA D3610 FR            | 1        | 0.79%   |
| MSI MS-7C94                             | 1        | 0.79%   |
| MSI MS-7C88                             | 1        | 0.79%   |
| MSI MS-7C84                             | 1        | 0.79%   |
| MSI MS-7C37                             | 1        | 0.79%   |
| MSI MS-7C02                             | 1        | 0.79%   |
| MSI MS-7A40                             | 1        | 0.79%   |
| MSI MS-7A38                             | 1        | 0.79%   |
| MSI MS-7A36                             | 1        | 0.79%   |
| MSI MS-7918                             | 1        | 0.79%   |
| MSI MS-7756                             | 1        | 0.79%   |
| MSI MS-7636                             | 1        | 0.79%   |
| MSI HPE-421f                            | 1        | 0.79%   |
| Lenovo ThinkCentre M92p 3238AZ8         | 1        | 0.79%   |
| Lenovo IdeaCentre K410                  | 1        | 0.79%   |
| Intel DP45SG AAE27733-405               | 1        | 0.79%   |
| Intel DH55TC AAE70932-302               | 1        | 0.79%   |
| Intel D54250WYK H13922-303              | 1        | 0.79%   |
| HP Z800 Workstation                     | 1        | 0.79%   |
| HP Z600 Workstation                     | 1        | 0.79%   |
| HP Z210 Workstation                     | 1        | 0.79%   |
| HP Z2 Tower G5 Workstation              | 1        | 0.79%   |
| HP ProLiant MicroServer                 | 1        | 0.79%   |
| HP ProDesk 600 G1 SFF                   | 1        | 0.79%   |
| HP ProDesk 400 G2 MINI                  | 1        | 0.79%   |
| HP Pavilion Wave Desktop 600-a0xx       | 1        | 0.79%   |
| HP EliteDesk 800 G2 TWR                 | 1        | 0.79%   |
| HP Compaq dc7800p Convertible Minitower | 1        | 0.79%   |
| HP 290 G1 SFF Business PC               | 1        | 0.79%   |
| HP 20-r124d                             | 1        | 0.79%   |
| Gigabyte Z77X-UD5H                      | 1        | 0.79%   |
| Gigabyte Z77N-WIFI                      | 1        | 0.79%   |
| Gigabyte Z68P-DS3                       | 1        | 0.79%   |
| Gigabyte Z490 GAMING X                  | 1        | 0.79%   |
| Gigabyte Z390 DESIGNARE                 | 1        | 0.79%   |
| Gigabyte Z370 AORUS Gaming WIFI         | 1        | 0.79%   |
| Gigabyte Z170MX-Gaming 5                | 1        | 0.79%   |
| Gigabyte X58A-UD5                       | 1        | 0.79%   |
| Gigabyte X570 AORUS PRO WIFI            | 1        | 0.79%   |
| Gigabyte X570 AORUS MASTER              | 1        | 0.79%   |
| Gigabyte X399 AORUS Gaming 7            | 1        | 0.79%   |
| Gigabyte P35-DS4                        | 1        | 0.79%   |
| Gigabyte H97N-WIFI                      | 1        | 0.79%   |
| Gigabyte H97-HD3                        | 1        | 0.79%   |
| Gigabyte H77N-WIFI                      | 1        | 0.79%   |
| Gigabyte H57M-USB3                      | 1        | 0.79%   |
| Gigabyte H270M-DS3H                     | 1        | 0.79%   |
| Gigabyte GB-BACE-3160                   | 1        | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 8        | 6.35%   |
| ASUS PRIME             | 6        | 4.76%   |
| ASUS TUF               | 5        | 3.97%   |
| HP Compaq              | 3        | 2.38%   |
| Dell PowerEdge         | 3        | 2.38%   |
| ASUS ROG               | 3        | 2.38%   |
| Unknown                | 3        | 2.38%   |
| Supermicro SYS-7048A-T | 2        | 1.59%   |
| HP ProDesk             | 2        | 1.59%   |
| Gigabyte X570          | 2        | 1.59%   |
| Gigabyte X470          | 2        | 1.59%   |
| Gigabyte A320M-S2H     | 2        | 1.59%   |
| Dell Precision         | 2        | 1.59%   |
| Dell Inspiron          | 2        | 1.59%   |
| ASUS P8Z77-V           | 2        | 1.59%   |
| ASUS All               | 2        | 1.59%   |
| Supermicro X9SCI       | 1        | 0.79%   |
| Supermicro X8SIL       | 1        | 0.79%   |
| Supermicro X8SAX       | 1        | 0.79%   |
| Packard Bell IMEDIA    | 1        | 0.79%   |
| MSI MS-7C94            | 1        | 0.79%   |
| MSI MS-7C88            | 1        | 0.79%   |
| MSI MS-7C84            | 1        | 0.79%   |
| MSI MS-7C37            | 1        | 0.79%   |
| MSI MS-7C02            | 1        | 0.79%   |
| MSI MS-7A40            | 1        | 0.79%   |
| MSI MS-7A38            | 1        | 0.79%   |
| MSI MS-7A36            | 1        | 0.79%   |
| MSI MS-7918            | 1        | 0.79%   |
| MSI MS-7756            | 1        | 0.79%   |
| MSI MS-7636            | 1        | 0.79%   |
| MSI HPE-421f           | 1        | 0.79%   |
| Lenovo ThinkCentre     | 1        | 0.79%   |
| Lenovo IdeaCentre      | 1        | 0.79%   |
| Intel DP45SG           | 1        | 0.79%   |
| Intel DH55TC           | 1        | 0.79%   |
| Intel D54250WYK        | 1        | 0.79%   |
| HP Z800                | 1        | 0.79%   |
| HP Z600                | 1        | 0.79%   |
| HP Z210                | 1        | 0.79%   |
| HP Z2                  | 1        | 0.79%   |
| HP ProLiant            | 1        | 0.79%   |
| HP Pavilion            | 1        | 0.79%   |
| HP EliteDesk           | 1        | 0.79%   |
| HP 290                 | 1        | 0.79%   |
| HP 20-r124d            | 1        | 0.79%   |
| Gigabyte Z77X-UD5H     | 1        | 0.79%   |
| Gigabyte Z77N-WIFI     | 1        | 0.79%   |
| Gigabyte Z68P-DS3      | 1        | 0.79%   |
| Gigabyte Z490          | 1        | 0.79%   |
| Gigabyte Z390          | 1        | 0.79%   |
| Gigabyte Z370          | 1        | 0.79%   |
| Gigabyte Z170MX-Gaming | 1        | 0.79%   |
| Gigabyte X58A-UD5      | 1        | 0.79%   |
| Gigabyte X399          | 1        | 0.79%   |
| Gigabyte P35-DS4       | 1        | 0.79%   |
| Gigabyte H97N-WIFI     | 1        | 0.79%   |
| Gigabyte H97-HD3       | 1        | 0.79%   |
| Gigabyte H77N-WIFI     | 1        | 0.79%   |
| Gigabyte H57M-USB3     | 1        | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 17       | 13.49%  |
| 2018 | 17       | 13.49%  |
| 2019 | 16       | 12.7%   |
| 2013 | 16       | 12.7%   |
| 2014 | 10       | 7.94%   |
| 2010 | 10       | 7.94%   |
| 2016 | 7        | 5.56%   |
| 2012 | 7        | 5.56%   |
| 2021 | 5        | 3.97%   |
| 2015 | 4        | 3.17%   |
| 2011 | 4        | 3.17%   |
| 2009 | 4        | 3.17%   |
| 2017 | 3        | 2.38%   |
| 2008 | 3        | 2.38%   |
| 2007 | 3        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 126      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 125      | 99.21%  |
| Enabled  | 1        | 0.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 29       | 22.66%  |
| 32.01-64.0  | 26       | 20.31%  |
| 4.01-8.0    | 24       | 18.75%  |
| 8.01-16.0   | 15       | 11.72%  |
| 3.01-4.0    | 14       | 10.94%  |
| 64.01-256.0 | 13       | 10.16%  |
| 24.01-32.0  | 5        | 3.91%   |
| 2.01-3.0    | 1        | 0.78%   |
| 1.01-2.0    | 1        | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 35       | 24.82%  |
| 3.01-4.0   | 30       | 21.28%  |
| 4.01-8.0   | 27       | 19.15%  |
| 1.01-2.0   | 25       | 17.73%  |
| 8.01-16.0  | 12       | 8.51%   |
| 0.51-1.0   | 7        | 4.96%   |
| 16.01-24.0 | 2        | 1.42%   |
| 0.01-0.5   | 2        | 1.42%   |
| 32.01-64.0 | 1        | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 39.37%  |
| 2      | 27       | 21.26%  |
| 3      | 21       | 16.54%  |
| 4      | 9        | 7.09%   |
| 6      | 5        | 3.94%   |
| 5      | 5        | 3.94%   |
| 7      | 3        | 2.36%   |
| 19     | 2        | 1.57%   |
| 8      | 2        | 1.57%   |
| 15     | 1        | 0.79%   |
| 13     | 1        | 0.79%   |
| 9      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 59.06%  |
| Yes       | 52       | 40.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 126      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 66.14%  |
| Yes       | 43       | 33.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 69.84%  |
| Yes       | 38       | 30.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 27       | 21.43%  |
| Germany      | 13       | 10.32%  |
| Brazil       | 7        | 5.56%   |
| Canada       | 6        | 4.76%   |
| Russia       | 5        | 3.97%   |
| Poland       | 5        | 3.97%   |
| India        | 5        | 3.97%   |
| UK           | 4        | 3.17%   |
| France       | 4        | 3.17%   |
| Ukraine      | 3        | 2.38%   |
| Turkey       | 3        | 2.38%   |
| Sweden       | 3        | 2.38%   |
| Netherlands  | 3        | 2.38%   |
| Finland      | 3        | 2.38%   |
| Switzerland  | 2        | 1.59%   |
| Romania      | 2        | 1.59%   |
| Peru         | 2        | 1.59%   |
| Italy        | 2        | 1.59%   |
| Indonesia    | 2        | 1.59%   |
| Hong Kong    | 2        | 1.59%   |
| Czechia      | 2        | 1.59%   |
| China        | 2        | 1.59%   |
| Australia    | 2        | 1.59%   |
| Thailand     | 1        | 0.79%   |
| South Korea  | 1        | 0.79%   |
| South Africa | 1        | 0.79%   |
| Slovenia     | 1        | 0.79%   |
| Serbia       | 1        | 0.79%   |
| Saudi Arabia | 1        | 0.79%   |
| Norway       | 1        | 0.79%   |
| Mexico       | 1        | 0.79%   |
| Malaysia     | 1        | 0.79%   |
| Luxembourg   | 1        | 0.79%   |
| Lithuania    | 1        | 0.79%   |
| Iran         | 1        | 0.79%   |
| Hungary      | 1        | 0.79%   |
| Greece       | 1        | 0.79%   |
| Colombia     | 1        | 0.79%   |
| Belarus      | 1        | 0.79%   |
| Bangladesh   | 1        | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Berlin              | 4        | 3.15%   |
| Istanbul            | 3        | 2.36%   |
| Sydney              | 2        | 1.57%   |
| S??o Paulo          | 2        | 1.57%   |
| Portland            | 2        | 1.57%   |
| Munich              | 2        | 1.57%   |
| Lima                | 2        | 1.57%   |
| Gdansk              | 2        | 1.57%   |
| Chicago             | 2        | 1.57%   |
| Central             | 2        | 1.57%   |
| Alexandria          | 2        | 1.57%   |
| Zaporizhzhia        | 1        | 0.79%   |
| Zapopan             | 1        | 0.79%   |
| Yangquan            | 1        | 0.79%   |
| Wodzis?‚aw ??l?…ski | 1        | 0.79%   |
| West Bromwich       | 1        | 0.79%   |
| Wayne               | 1        | 0.79%   |
| Warsaw              | 1        | 0.79%   |
| Vitebsk             | 1        | 0.79%   |
| Vaugneray           | 1        | 0.79%   |
| Val-des-Monts       | 1        | 0.79%   |
| Tuusula             | 1        | 0.79%   |
| Tremembe            | 1        | 0.79%   |
| Toronto             | 1        | 0.79%   |
| Tirupati            | 1        | 0.79%   |
| Tehran              | 1        | 0.79%   |
| Taubate             | 1        | 0.79%   |
| Tambov              | 1        | 0.79%   |
| Sundbyberg          | 1        | 0.79%   |
| Stuttgart           | 1        | 0.79%   |
| Stockholm           | 1        | 0.79%   |
| Spijkenisse         | 1        | 0.79%   |
| Southlake           | 1        | 0.79%   |
| Sollentuna          | 1        | 0.79%   |
| Shenzhen            | 1        | 0.79%   |
| Seongdong-gu        | 1        | 0.79%   |
| Seattle             | 1        | 0.79%   |
| Satu Mare           | 1        | 0.79%   |
| Santa Rosa          | 1        | 0.79%   |
| Salem               | 1        | 0.79%   |
| Recea               | 1        | 0.79%   |
| Pretoria            | 1        | 0.79%   |
| Prague              | 1        | 0.79%   |
| Port Saint Lucie    | 1        | 0.79%   |
| Pogorze             | 1        | 0.79%   |
| Phoenix             | 1        | 0.79%   |
| Pato Branco         | 1        | 0.79%   |
| Novosibirsk         | 1        | 0.79%   |
| Newcastle upon Tyne | 1        | 0.79%   |
| New York            | 1        | 0.79%   |
| Nesttun             | 1        | 0.79%   |
| Mumbai              | 1        | 0.79%   |
| Moscow              | 1        | 0.79%   |
| Montreal            | 1        | 0.79%   |
| Mol?—tai            | 1        | 0.79%   |
| Milan               | 1        | 0.79%   |
| Maricopa            | 1        | 0.79%   |
| Maribor             | 1        | 0.79%   |
| Makkah              | 1        | 0.79%   |
| Mainz               | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 55       | 158    | 23.5%   |
| Seagate                   | 43       | 80     | 18.38%  |
| Samsung Electronics       | 39       | 67     | 16.67%  |
| Kingston                  | 17       | 20     | 7.26%   |
| Toshiba                   | 7        | 11     | 2.99%   |
| SanDisk                   | 7        | 8      | 2.99%   |
| Hitachi                   | 7        | 9      | 2.99%   |
| Intel                     | 5        | 6      | 2.14%   |
| HGST                      | 5        | 23     | 2.14%   |
| Unknown                   | 4        | 12     | 1.71%   |
| Crucial                   | 4        | 5      | 1.71%   |
| A-DATA Technology         | 4        | 5      | 1.71%   |
| Silicon Motion            | 3        | 3      | 1.28%   |
| XPG                       | 2        | 2      | 0.85%   |
| SPCC                      | 2        | 2      | 0.85%   |
| SK Hynix                  | 2        | 2      | 0.85%   |
| Phison                    | 2        | 2      | 0.85%   |
| OCZ                       | 2        | 3      | 0.85%   |
| Micron/Crucial Technology | 2        | 3      | 0.85%   |
| Micron Technology         | 2        | 3      | 0.85%   |
| Gigabyte Technology       | 2        | 2      | 0.85%   |
| Apacer                    | 2        | 2      | 0.85%   |
| Verbatim                  | 1        | 1      | 0.43%   |
| V-GeN                     | 1        | 1      | 0.43%   |
| Team                      | 1        | 1      | 0.43%   |
| SATADOM-SL                | 1        | 1      | 0.43%   |
| ROG                       | 1        | 1      | 0.43%   |
| Realtek Semiconductor     | 1        | 1      | 0.43%   |
| PNY                       | 1        | 1      | 0.43%   |
| PLEXTOR                   | 1        | 1      | 0.43%   |
| Patriot                   | 1        | 3      | 0.43%   |
| Lexar                     | 1        | 1      | 0.43%   |
| KIOXIA-EXCERIA            | 1        | 2      | 0.43%   |
| Hewlett-Packard           | 1        | 1      | 0.43%   |
| Dell                      | 1        | 1      | 0.43%   |
| China                     | 1        | 4      | 0.43%   |
| ASMT                      | 1        | 1      | 0.43%   |
| Apple                     | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD20EARX-00PASB0 2TB             | 5        | 1.73%   |
| Toshiba DT01ACA100 1TB               | 5        | 1.73%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.38%   |
| Seagate ST500DM002-1BD142 500GB      | 4        | 1.38%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3        | 1.04%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3        | 1.04%   |
| Seagate ST1000DM003-1ER162 1TB       | 3        | 1.04%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 1.04%   |
| Samsung SSD 860 EVO 500GB            | 3        | 1.04%   |
| Samsung SSD 860 EVO 1TB              | 3        | 1.04%   |
| Samsung SSD 840 EVO 250GB            | 3        | 1.04%   |
| Samsung NVMe SSD Drive 500GB         | 3        | 1.04%   |
| Kingston SA400S37240G 240GB SSD      | 3        | 1.04%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2        | 0.69%   |
| WDC WD40EFRX-68N32N0 4TB             | 2        | 0.69%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.69%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 2        | 0.69%   |
| WDC WD2002FAEX-007BA0 2TB            | 2        | 0.69%   |
| Unknown HUH728080ALE601 8TB          | 2        | 0.69%   |
| Seagate ST31000528AS 1TB             | 2        | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB       | 2        | 0.69%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.69%   |
| Seagate Expansion Desk 4TB           | 2        | 0.69%   |
| Sandisk NVMe SSD Drive 1TB           | 2        | 0.69%   |
| Samsung SSD 970 PRO 512GB            | 2        | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB       | 2        | 0.69%   |
| Samsung SSD 850 EVO M.2 500GB        | 2        | 0.69%   |
| Samsung SSD 850 EVO 500GB            | 2        | 0.69%   |
| Samsung SSD 840 PRO Series 256GB     | 2        | 0.69%   |
| Samsung SSD 840 EVO 120GB            | 2        | 0.69%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 0.69%   |
| Samsung NVMe SSD Drive 250GB         | 2        | 0.69%   |
| Samsung MZ7LN256HMJP-000H1 256GB SSD | 2        | 0.69%   |
| Samsung HD103SI 1TB                  | 2        | 0.69%   |
| Kingston SA400S37120G 120GB SSD      | 2        | 0.69%   |
| Intel SSDSC2KG960G8 960GB            | 2        | 0.69%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.35%   |
| XPG GAMMIX S11 Pro 512GB             | 1        | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.35%   |
| WDC WD7500BPVT-55HXZT3 752GB         | 1        | 0.35%   |
| WDC WD6400AADS-00M2B0 640GB          | 1        | 0.35%   |
| WDC WD5003AZEX-00MK2A0 500GB         | 1        | 0.35%   |
| WDC WD5002ABYS-01B1B0 500GB          | 1        | 0.35%   |
| WDC WD5001AALS-00L3B2 500GB          | 1        | 0.35%   |
| WDC WD5000LUCT-63C26Y0 500GB         | 1        | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 0.35%   |
| WDC WD5000AAKX-753CA1 500GB          | 1        | 0.35%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.35%   |
| WDC WD5000AAKX-00U6AA0 500GB         | 1        | 0.35%   |
| WDC WD5000AAKS-60Z1A0 500GB          | 1        | 0.35%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1        | 0.35%   |
| WDC WD5000AACS-00G8B0 500GB          | 1        | 0.35%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 1        | 0.35%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1        | 0.35%   |
| WDC WD4001FFSX-68JNUN0 4TB           | 1        | 0.35%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 148    | 41.94%  |
| Seagate             | 41       | 76     | 33.06%  |
| Toshiba             | 7        | 11     | 5.65%   |
| Hitachi             | 7        | 9      | 5.65%   |
| Samsung Electronics | 6        | 6      | 4.84%   |
| HGST                | 5        | 23     | 4.03%   |
| Unknown             | 3        | 11     | 2.42%   |
| Hewlett-Packard     | 1        | 1      | 0.81%   |
| Dell                | 1        | 1      | 0.81%   |
| Apple               | 1        | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 42     | 28.92%  |
| Kingston            | 17       | 20     | 20.48%  |
| WDC                 | 7        | 10     | 8.43%   |
| Intel               | 5        | 6      | 6.02%   |
| SanDisk             | 4        | 5      | 4.82%   |
| Crucial             | 4        | 5      | 4.82%   |
| SPCC                | 2        | 2      | 2.41%   |
| SK Hynix            | 2        | 2      | 2.41%   |
| OCZ                 | 2        | 3      | 2.41%   |
| Apacer              | 2        | 2      | 2.41%   |
| A-DATA Technology   | 2        | 2      | 2.41%   |
| Verbatim            | 1        | 1      | 1.2%    |
| V-GeN               | 1        | 1      | 1.2%    |
| Team                | 1        | 1      | 1.2%    |
| Seagate             | 1        | 1      | 1.2%    |
| SATADOM-SL          | 1        | 1      | 1.2%    |
| PNY                 | 1        | 1      | 1.2%    |
| PLEXTOR             | 1        | 1      | 1.2%    |
| Patriot             | 1        | 3      | 1.2%    |
| Micron Technology   | 1        | 1      | 1.2%    |
| Lexar               | 1        | 1      | 1.2%    |
| China               | 1        | 4      | 1.2%    |
| ASMT                | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 89       | 287    | 46.84%  |
| SSD     | 68       | 116    | 35.79%  |
| NVMe    | 30       | 43     | 15.79%  |
| Unknown | 3        | 4      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 117      | 396    | 75.97%  |
| NVMe | 30       | 43     | 19.48%  |
| SAS  | 7        | 11     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 81       | 157    | 44.02%  |
| 0.51-1.0   | 49       | 80     | 26.63%  |
| 1.01-2.0   | 29       | 77     | 15.76%  |
| 3.01-4.0   | 10       | 28     | 5.43%   |
| 4.01-10.0  | 8        | 26     | 4.35%   |
| 2.01-3.0   | 4        | 15     | 2.17%   |
| 10.01-20.0 | 3        | 20     | 1.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 29       | 22.14%  |
| 251-500        | 25       | 19.08%  |
| 101-250        | 23       | 17.56%  |
| 1001-2000      | 19       | 14.5%   |
| More than 3000 | 17       | 12.98%  |
| 51-100         | 5        | 3.82%   |
| Unknown        | 5        | 3.82%   |
| 2001-3000      | 4        | 3.05%   |
| 21-50          | 2        | 1.53%   |
| 1-20           | 2        | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 29.2%   |
| 21-50          | 26       | 18.98%  |
| 101-250        | 20       | 14.6%   |
| More than 3000 | 12       | 8.76%   |
| 51-100         | 11       | 8.03%   |
| 251-500        | 9        | 6.57%   |
| 501-1000       | 8        | 5.84%   |
| 1001-2000      | 6        | 4.38%   |
| Unknown        | 5        | 3.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD6400AADS-00M2B0 640GB           | 1        | 1      | 5.56%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1        | 1      | 5.56%   |
| WDC WD5000AACS-00G8B0 500GB           | 1        | 1      | 5.56%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1        | 1      | 5.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 5.56%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 4      | 5.56%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1        | 1      | 5.56%   |
| WDC WD1002FBYS-18A6B0 1TB             | 1        | 1      | 5.56%   |
| SK Hynix HFS128G32TND-N210A 128GB SSD | 1        | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 5.56%   |
| Seagate ST3400820AS 400GB             | 1        | 1      | 5.56%   |
| Seagate ST3000VM002-1ET166 3TB        | 1        | 1      | 5.56%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 1      | 5.56%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 5.56%   |
| Intel SSDSA2M040G2GC 40GB             | 1        | 1      | 5.56%   |
| HGST HDS724040ALE640 4TB              | 1        | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 11     | 37.5%   |
| Seagate             | 6        | 6      | 37.5%   |
| SK Hynix            | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| HGST                | 1        | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 11     | 46.15%  |
| Seagate | 6        | 6      | 46.15%  |
| HGST    | 1        | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 19     | 81.25%  |
| SSD  | 3        | 3      | 18.75%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 74       | 224    | 52.48%  |
| Works    | 51       | 202    | 36.17%  |
| Malfunc  | 15       | 22     | 10.64%  |
| Failed   | 1        | 2      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 86       | 45.5%   |
| AMD                           | 38       | 20.11%  |
| Samsung Electronics           | 15       | 7.94%   |
| ASMedia Technology            | 11       | 5.82%   |
| Marvell Technology Group      | 6        | 3.17%   |
| JMicron Technology            | 5        | 2.65%   |
| Silicon Motion                | 4        | 2.12%   |
| Phison Electronics            | 4        | 2.12%   |
| LSI Logic / Symbios Logic     | 4        | 2.12%   |
| Sandisk                       | 3        | 1.59%   |
| Broadcom / LSI                | 3        | 1.59%   |
| ADATA Technology              | 3        | 1.59%   |
| Micron/Crucial Technology     | 2        | 1.06%   |
| Realtek Semiconductor         | 1        | 0.53%   |
| Nvidia                        | 1        | 0.53%   |
| Micron Technology             | 1        | 0.53%   |
| KIOXIA                        | 1        | 0.53%   |
| Integrated Technology Express | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 11.76%  |
| Intel SATA Controller [RAID mode]                                                       | 16       | 6.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 5.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 4.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 3.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.52%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 2.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 1.68%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.26%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 1.26%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.26%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.26%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.26%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.84%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.84%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.84%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 2        | 0.84%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.84%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 2        | 0.84%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.42%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.42%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.42%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.42%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.42%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1        | 0.42%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.42%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.42%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.42%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.42%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 0.42%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.42%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1        | 0.42%   |
| KIOXIA Non-Volatile memory controller                                                   | 1        | 0.42%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.42%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 85       | 50%     |
| NVMe | 30       | 17.65%  |
| RAID | 25       | 14.71%  |
| IDE  | 25       | 14.71%  |
| SAS  | 4        | 2.35%   |
| SCSI | 1        | 0.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 88       | 69.84%  |
| AMD    | 38       | 30.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 3.94%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 3.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 3.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 3.15%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 2.36%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 2.36%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.36%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 2.36%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.57%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 1.57%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 2        | 1.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.57%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.57%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.57%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.57%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.57%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.79%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.79%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.79%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.79%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.79%   |
| Intel Xeon CPU E5606 @ 2.13GHz              | 1        | 0.79%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.79%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.79%   |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.79%   |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 0.79%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz         | 1        | 0.79%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.79%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.79%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.79%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 0.79%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.79%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.79%   |
| Intel Genuine CPU @ 2.20GHz                 | 1        | 0.79%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.79%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.79%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.79%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.79%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.79%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.79%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.79%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 0.79%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.79%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 0.79%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.79%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1        | 0.79%   |
| Intel Core i5-4460T CPU @ 1.90GHz           | 1        | 0.79%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.79%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.79%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 20.47%  |
| Intel Core i7           | 23       | 18.11%  |
| Intel Xeon              | 14       | 11.02%  |
| AMD Ryzen 5             | 10       | 7.87%   |
| Intel Core 2 Quad       | 7        | 5.51%   |
| AMD Ryzen 7             | 7        | 5.51%   |
| Intel Core i3           | 6        | 4.72%   |
| AMD Ryzen 9             | 6        | 4.72%   |
| AMD FX                  | 5        | 3.94%   |
| AMD Ryzen 3             | 4        | 3.15%   |
| Intel Core 2 Duo        | 3        | 2.36%   |
| AMD Ryzen Threadripper  | 3        | 2.36%   |
| Intel Pentium           | 2        | 1.57%   |
| AMD Ryzen 7 PRO         | 2        | 1.57%   |
| Intel Pentium Gold      | 1        | 0.79%   |
| Intel Pentium Dual-Core | 1        | 0.79%   |
| Intel Pentium Dual      | 1        | 0.79%   |
| Intel Genuine           | 1        | 0.79%   |
| Intel Core i9           | 1        | 0.79%   |
| Intel Celeron           | 1        | 0.79%   |
| Intel Atom              | 1        | 0.79%   |
| AMD Turion II Neo       | 1        | 0.79%   |
| AMD Phenom II X4        | 1        | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 66       | 51.97%  |
| 6      | 16       | 12.6%   |
| 2      | 16       | 12.6%   |
| 8      | 13       | 10.24%  |
| 12     | 9        | 7.09%   |
| 16     | 5        | 3.94%   |
| 3      | 1        | 0.79%   |
| 1      | 1        | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 96.03%  |
| 2      | 5        | 3.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 73       | 57.03%  |
| 1      | 55       | 42.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 122      | 96.83%  |
| Unknown        | 4        | 3.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 15       | 11.81%  |
| 0x306c3    | 12       | 9.45%   |
| 0x08701021 | 9        | 7.09%   |
| 0x206a7    | 8        | 6.3%    |
| 0x0800820d | 7        | 5.51%   |
| 0x506e3    | 6        | 4.72%   |
| 0x906ea    | 5        | 3.94%   |
| 0x1067a    | 5        | 3.94%   |
| 0x08701013 | 5        | 3.94%   |
| 0x06000852 | 5        | 3.94%   |
| 0x6fb      | 4        | 3.15%   |
| 0x106e5    | 4        | 3.15%   |
| Unknown    | 4        | 3.15%   |
| 0xa0655    | 3        | 2.36%   |
| 0x906e9    | 3        | 2.36%   |
| 0x306f2    | 3        | 2.36%   |
| 0x206c2    | 3        | 2.36%   |
| 0x08101016 | 3        | 2.36%   |
| 0x6fd      | 2        | 1.57%   |
| 0x106a5    | 2        | 1.57%   |
| 0x08001137 | 2        | 1.57%   |
| 0x906ed    | 1        | 0.79%   |
| 0x906eb    | 1        | 0.79%   |
| 0x406f1    | 1        | 0.79%   |
| 0x406c4    | 1        | 0.79%   |
| 0x40651    | 1        | 0.79%   |
| 0x206d7    | 1        | 0.79%   |
| 0x20652    | 1        | 0.79%   |
| 0x106c2    | 1        | 0.79%   |
| 0x10677    | 1        | 0.79%   |
| 0x10676    | 1        | 0.79%   |
| 0x0a201009 | 1        | 0.79%   |
| 0x08701011 | 1        | 0.79%   |
| 0x08600106 | 1        | 0.79%   |
| 0x08001138 | 1        | 0.79%   |
| 0x08001129 | 1        | 0.79%   |
| 0x010000db | 1        | 0.79%   |
| 0x010000c8 | 1        | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 16       | 12.6%   |
| Haswell     | 16       | 12.6%   |
| IvyBridge   | 15       | 11.81%  |
| SandyBridge | 10       | 7.87%   |
| KabyLake    | 10       | 7.87%   |
| Zen         | 8        | 6.3%    |
| Zen+        | 7        | 5.51%   |
| Skylake     | 7        | 5.51%   |
| Penryn      | 7        | 5.51%   |
| Nehalem     | 6        | 4.72%   |
| Core        | 6        | 4.72%   |
| Westmere    | 5        | 3.94%   |
| Piledriver  | 5        | 3.94%   |
| CometLake   | 3        | 2.36%   |
| K10         | 2        | 1.57%   |
| Zen 3       | 1        | 0.79%   |
| Silvermont  | 1        | 0.79%   |
| Broadwell   | 1        | 0.79%   |
| Bonnell     | 1        | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 51       | 37.5%   |
| Intel                      | 49       | 36.03%  |
| AMD                        | 33       | 24.26%  |
| S3 Graphics                | 2        | 1.47%   |
| Matrox Electronics Systems | 1        | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 7.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 7.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 5.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 4.41%   |
| Intel HD Graphics 530                                                       | 5        | 3.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.21%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.21%   |
| Nvidia GT218 [GeForce G210]                                                 | 2        | 1.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.47%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.47%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.47%   |
| Intel HD Graphics 630                                                       | 2        | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.47%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.47%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.47%   |
| S3 Graphics Savage 4                                                        | 1        | 0.74%   |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                          | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU104GL [Quadro RTX 5000]                                            | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.74%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 0.74%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 0.74%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.74%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.74%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.74%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.74%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                          | 1        | 0.74%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 0.74%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.74%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 0.74%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.74%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.74%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.74%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.74%   |
| Nvidia G92 [GeForce GT 230 OEM]                                             | 1        | 0.74%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.74%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 0.74%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 0.74%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller          | 1        | 0.74%   |
| Intel HD Graphics P530                                                      | 1        | 0.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 0.74%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 48       | 37.8%   |
| 1 x Intel       | 42       | 33.07%  |
| 1 x AMD         | 30       | 23.62%  |
| 1 x S3 Graphics | 2        | 1.57%   |
| Intel + AMD     | 2        | 1.57%   |
| 2 x AMD         | 1        | 0.79%   |
| 1 x Matrox      | 1        | 0.79%   |
| Intel + Nvidia  | 1        | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 96       | 75.59%  |
| Proprietary | 22       | 17.32%  |
| Unknown     | 9        | 7.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 43.08%  |
| 1.01-2.0   | 19       | 14.62%  |
| 0.51-1.0   | 16       | 12.31%  |
| 7.01-8.0   | 14       | 10.77%  |
| 0.01-0.5   | 13       | 10%     |
| 3.01-4.0   | 5        | 3.85%   |
| 8.01-16.0  | 3        | 2.31%   |
| 2.01-3.0   | 2        | 1.54%   |
| 5.01-6.0   | 1        | 0.77%   |
| 4.01-5.0   | 1        | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 22       | 17.19%  |
| Dell                 | 19       | 14.84%  |
| Goldstar             | 16       | 12.5%   |
| Hewlett-Packard      | 15       | 11.72%  |
| Acer                 | 9        | 7.03%   |
| BenQ                 | 6        | 4.69%   |
| ViewSonic            | 5        | 3.91%   |
| Ancor Communications | 5        | 3.91%   |
| LG Electronics       | 4        | 3.13%   |
| Eizo                 | 4        | 3.13%   |
| Sony                 | 3        | 2.34%   |
| Philips              | 3        | 2.34%   |
| Iiyama               | 3        | 2.34%   |
| Xiaomi               | 2        | 1.56%   |
| Unknown              | 2        | 1.56%   |
| Xerox                | 1        | 0.78%   |
| Sceptre Tech         | 1        | 0.78%   |
| NEC Computers        | 1        | 0.78%   |
| MStar                | 1        | 0.78%   |
| Lenovo               | 1        | 0.78%   |
| HannStar Display     | 1        | 0.78%   |
| HannStar             | 1        | 0.78%   |
| AUS                  | 1        | 0.78%   |
| Apple                | 1        | 0.78%   |
| AOC                  | 1        | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 3        | 2.05%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 3        | 2.05%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                     | 2        | 1.37%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch    | 2        | 1.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 2        | 1.37%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 520x330mm 24.2-inch           | 2        | 1.37%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 1.37%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                    | 1        | 0.68%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch              | 1        | 0.68%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.68%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch          | 1        | 0.68%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch          | 1        | 0.68%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch             | 1        | 0.68%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.68%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                              | 1        | 0.68%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.68%   |
| Sony TV *00 SNY7C04 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.68%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                    | 1        | 0.68%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch          | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch   | 1        | 0.68%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch     | 1        | 0.68%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch     | 1        | 0.68%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch      | 1        | 0.68%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch      | 1        | 0.68%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 0.68%   |
| Samsung Electronics S24B300 SAM08CB 1920x1080 521x293mm 23.5-inch      | 1        | 0.68%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch      | 1        | 0.68%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                      | 1        | 0.68%   |
| Samsung Electronics LCD Monitor T22C300 1920x1080                      | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0D42 1920x540                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch  | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1060x590mm 47.8-inch | 1        | 0.68%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                      | 1        | 0.68%   |
| Samsung Electronics LCD Monitor C32JG5x 3640x1920                      | 1        | 0.68%   |
| Samsung Electronics EPSON PJ     SECA114 1600x1200                     | 1        | 0.68%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch               | 1        | 0.68%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.68%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 1        | 0.68%   |
| NEC Computers LCD52V NEC6656 1024x768 304x228mm 15.0-inch              | 1        | 0.68%   |
| MStar TV_MONITOR MST0030 1440x900 1150x650mm 52.0-inch                 | 1        | 0.68%   |
| LG Electronics LCD Monitor W2442                                       | 1        | 0.68%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 0.68%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 0.68%   |
| LG Electronics LCD Monitor LG HDR WQHD                                 | 1        | 0.68%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch               | 1        | 0.68%   |
| Iiyama PLE2607WS IVM5608 1920x1200 550x344mm 25.5-inch                 | 1        | 0.68%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                 | 1        | 0.68%   |
| Iiyama PL2480H IVM610B 1920x1080 520x290mm 23.4-inch                   | 1        | 0.68%   |
| Iiyama PL2210HD IVM5612 1920x1080 477x268mm 21.5-inch                  | 1        | 0.68%   |
| Hewlett-Packard ZR2440w HWP2955 1920x1080 520x320mm 24.0-inch          | 1        | 0.68%   |
| Hewlett-Packard Z27i HWP3095 2560x1440 597x336mm 27.0-inch             | 1        | 0.68%   |
| Hewlett-Packard S2331 HWP2907 1920x1080 509x286mm 23.0-inch            | 1        | 0.68%   |
| Hewlett-Packard OMEN by HP 32 HPN3378 2560x1440 708x399mm 32.0-inch    | 1        | 0.68%   |
| Hewlett-Packard LCD Monitor ZR22w 3840x1080                            | 1        | 0.68%   |
| Hewlett-Packard LCD Monitor ZR22w                                      | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 43.75%  |
| 3840x2160 (4K)     | 15       | 11.72%  |
| 1920x1200 (WUXGA)  | 11       | 8.59%   |
| Unknown            | 9        | 7.03%   |
| 1680x1050 (WSXGA+) | 7        | 5.47%   |
| 2560x1440 (QHD)    | 6        | 4.69%   |
| 3840x1080          | 3        | 2.34%   |
| 2560x1080          | 3        | 2.34%   |
| 2880x1800          | 2        | 1.56%   |
| 1600x900 (HD+)     | 2        | 1.56%   |
| 1366x768 (WXGA)    | 2        | 1.56%   |
| 1280x1024 (SXGA)   | 2        | 1.56%   |
| 1024x768 (XGA)     | 2        | 1.56%   |
| 7280x2160          | 1        | 0.78%   |
| 5520x2160          | 1        | 0.78%   |
| 3840x1200          | 1        | 0.78%   |
| 3640x1920          | 1        | 0.78%   |
| 2560x1600          | 1        | 0.78%   |
| 1600x1200          | 1        | 0.78%   |
| 1400x1050          | 1        | 0.78%   |
| 1280x960           | 1        | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 25       | 19.38%  |
| 21      | 19       | 14.73%  |
| 24      | 18       | 13.95%  |
| 23      | 17       | 13.18%  |
| Unknown | 17       | 13.18%  |
| 22      | 4        | 3.1%    |
| 20      | 4        | 3.1%    |
| 34      | 3        | 2.33%   |
| 31      | 3        | 2.33%   |
| 19      | 3        | 2.33%   |
| 65      | 2        | 1.55%   |
| 40      | 2        | 1.55%   |
| 32      | 2        | 1.55%   |
| 25      | 2        | 1.55%   |
| 15      | 2        | 1.55%   |
| 84      | 1        | 0.78%   |
| 54      | 1        | 0.78%   |
| 52      | 1        | 0.78%   |
| 29      | 1        | 0.78%   |
| 18      | 1        | 0.78%   |
| 17      | 1        | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 56       | 45.9%   |
| 401-500     | 26       | 21.31%  |
| Unknown     | 17       | 13.93%  |
| 601-700     | 6        | 4.92%   |
| 701-800     | 5        | 4.1%    |
| 1001-1500   | 4        | 3.28%   |
| 301-350     | 3        | 2.46%   |
| 801-900     | 2        | 1.64%   |
| 351-400     | 2        | 1.64%   |
| 1501-2000   | 1        | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 72       | 62.07%  |
| 16/10   | 17       | 14.66%  |
| Unknown | 16       | 13.79%  |
| 4/3     | 4        | 3.45%   |
| 5/4     | 3        | 2.59%   |
| 21/9    | 3        | 2.59%   |
| 3/2     | 1        | 0.86%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 33.33%  |
| 301-350        | 25       | 19.84%  |
| Unknown        | 17       | 13.49%  |
| 251-300        | 11       | 8.73%   |
| 151-200        | 11       | 8.73%   |
| 351-500        | 9        | 7.14%   |
| More than 1000 | 5        | 3.97%   |
| 141-150        | 2        | 1.59%   |
| 101-110        | 2        | 1.59%   |
| 501-1000       | 2        | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 67       | 56.78%  |
| 101-120 | 22       | 18.64%  |
| Unknown | 17       | 14.41%  |
| 161-240 | 5        | 4.24%   |
| 121-160 | 5        | 4.24%   |
| 1-50    | 2        | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 59.38%  |
| 2     | 27       | 21.09%  |
| 0     | 21       | 16.41%  |
| 3     | 2        | 1.56%   |
| 6     | 1        | 0.78%   |
| 4     | 1        | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 73       | 40.56%  |
| Realtek Semiconductor | 67       | 37.22%  |
| Broadcom              | 10       | 5.56%   |
| Qualcomm Atheros      | 9        | 5%      |
| Ralink Technology     | 6        | 3.33%   |
| Mellanox Technologies | 3        | 1.67%   |
| D-Link System         | 2        | 1.11%   |
| Broadcom Limited      | 2        | 1.11%   |
| ASIX Electronics      | 2        | 1.11%   |
| Aquantia              | 2        | 1.11%   |
| TP-Link               | 1        | 0.56%   |
| Ralink                | 1        | 0.56%   |
| ICS Advent            | 1        | 0.56%   |
| DisplayLink           | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Desktops | Percent |
|------------------------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 53       | 25.98%  |
| Intel I211 Gigabit Network Connection                                                                                  | 16       | 7.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 8        | 3.92%   |
| Intel 82574L Gigabit Network Connection                                                                                | 7        | 3.43%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6        | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 5        | 2.45%   |
| Intel Ethernet Connection I217-LM                                                                                      | 5        | 2.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                                       | 5        | 2.45%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 4        | 1.96%   |
| Intel I210 Gigabit Network Connection                                                                                  | 4        | 1.96%   |
| Intel Ethernet Connection (2) I219-V                                                                                   | 4        | 1.96%   |
| Intel 82579V Gigabit Network Connection                                                                                | 4        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                                                                         | 3        | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                                                     | 3        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                       | 2        | 0.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 2        | 0.98%   |
| Mellanox MT27500 Family [ConnectX-3]                                                                                   | 2        | 0.98%   |
| Intel Wireless-AC 9260                                                                                                 | 2        | 0.98%   |
| Intel Wireless 8265 / 8275                                                                                             | 2        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                                                                   | 2        | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                                                                  | 2        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 2        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                                                                                   | 2        | 0.98%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                                          | 2        | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 2        | 0.98%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                                      | 2        | 0.98%   |
| TP-Link 802.11ac NIC                                                                                                   | 1        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                                        | 1        | 0.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                                             | 1        | 0.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                                                        | 1        | 0.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                                                 | 1        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                                                  | 1        | 0.49%   |
| Realtek 802.11ac WLAN Adapter                                                                                          | 1        | 0.49%   |
| Realtek 802.11ac NIC                                                                                                   | 1        | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                                  | 1        | 0.49%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                                      | 1        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 1        | 0.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                                              | 1        | 0.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                                              | 1        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                                              | 1        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                                              | 1        | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                                         | 1        | 0.49%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 1        | 0.49%   |
| Intel Wireless 7265                                                                                                    | 1        | 0.49%   |
| Intel Wireless 7260                                                                                                    | 1        | 0.49%   |
| Intel Wireless 3165                                                                                                    | 1        | 0.49%   |
| Intel Wireless 3160                                                                                                    | 1        | 0.49%   |
| Intel Ethernet Connection I218-V                                                                                       | 1        | 0.49%   |
| Intel Ethernet Connection I217-V                                                                                       | 1        | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                                                                  | 1        | 0.49%   |
| Intel Ethernet Connection (11) I219-V                                                                                  | 1        | 0.49%   |
| Intel Ethernet Connection (11) I219-LM                                                                                 | 1        | 0.49%   |
| Intel Centrino Advanced-N 6235                                                                                         | 1        | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                                        | 1        | 0.49%   |
| Intel 82578DC Gigabit Network Connection                                                                               | 1        | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                                                                     | 1        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                                                                             | 1        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 45.65%  |
| Realtek Semiconductor | 6        | 13.04%  |
| Ralink Technology     | 6        | 13.04%  |
| Qualcomm Atheros      | 6        | 13.04%  |
| Broadcom              | 5        | 10.87%  |
| TP-Link               | 1        | 2.17%   |
| Ralink                | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6        | 13.04%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5        | 10.87%  |
| Ralink RT5370 Wireless Adapter                                 | 3        | 6.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 6.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 4.35%   |
| Intel Wireless-AC 9260                                         | 2        | 4.35%   |
| Intel Wireless 8265 / 8275                                     | 2        | 4.35%   |
| TP-Link 802.11ac NIC                                           | 1        | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 2.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1        | 2.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 2.17%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 2.17%   |
| Realtek 802.11ac WLAN Adapter                                  | 1        | 2.17%   |
| Realtek 802.11ac NIC                                           | 1        | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 2.17%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 2.17%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1        | 2.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.17%   |
| Intel Wireless 7265                                            | 1        | 2.17%   |
| Intel Wireless 7260                                            | 1        | 2.17%   |
| Intel Wireless 3165                                            | 1        | 2.17%   |
| Intel Wireless 3160                                            | 1        | 2.17%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1        | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 65       | 44.83%  |
| Intel                 | 62       | 42.76%  |
| Broadcom              | 5        | 3.45%   |
| Qualcomm Atheros      | 3        | 2.07%   |
| D-Link System         | 2        | 1.38%   |
| Broadcom Limited      | 2        | 1.38%   |
| ASIX Electronics      | 2        | 1.38%   |
| Aquantia              | 2        | 1.38%   |
| ICS Advent            | 1        | 0.69%   |
| DisplayLink           | 1        | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 53       | 34.19%  |
| Intel I211 Gigabit Network Connection                                         | 16       | 10.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 5.16%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 4.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 3.23%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.23%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 2.58%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 2.58%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.58%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.29%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.29%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.29%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 1.29%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.65%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.65%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.65%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.65%   |
| Intel 82578DC Gigabit Network Connection                                      | 1        | 0.65%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.65%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.65%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.65%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.65%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.65%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.65%   |
| DisplayLink HP Port Replicator (Composite Device)                             | 1        | 0.65%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.65%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.65%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                                | 1        | 0.65%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.65%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.65%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                        | 1        | 0.65%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express               | 1        | 0.65%   |
| ASIX AX88772B                                                                 | 1        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 126      | 73.26%  |
| WiFi     | 43       | 25%     |
| Unknown  | 3        | 1.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 79.47%  |
| WiFi     | 30       | 19.87%  |
| Unknown  | 1        | 0.66%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 49.61%  |
| 2     | 45       | 35.43%  |
| 3     | 14       | 11.02%  |
| 5     | 2        | 1.57%   |
| 7     | 1        | 0.79%   |
| 4     | 1        | 0.79%   |
| 0     | 1        | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 96.06%  |
| Yes  | 5        | 3.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 20       | 52.63%  |
| Cambridge Silicon Radio | 8        | 21.05%  |
| Broadcom                | 5        | 13.16%  |
| ASUSTek Computer        | 3        | 7.89%   |
| IMC Networks            | 1        | 2.63%   |
| Apple                   | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 8        | 21.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 21.05%  |
| Intel AX200 Bluetooth                               | 6        | 15.79%  |
| Intel Bluetooth wireless interface                  | 4        | 10.53%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3        | 7.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 5.26%   |
| IMC Networks Bluetooth Device                       | 1        | 2.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.63%   |
| Broadcom BCM20702A0                                 | 1        | 2.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.63%   |
| ASUS Bluetooth Radio                                | 1        | 2.63%   |
| ASUS BCM20702A0                                     | 1        | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 80       | 42.11%  |
| AMD                 | 49       | 25.79%  |
| Nvidia              | 47       | 24.74%  |
| C-Media Electronics | 3        | 1.58%   |
| Plantronics         | 2        | 1.05%   |
| Logitech            | 2        | 1.05%   |
| Texas Instruments   | 1        | 0.53%   |
| Lynx                | 1        | 0.53%   |
| Fry's Electronics   | 1        | 0.53%   |
| Creative Technology | 1        | 0.53%   |
| Creative Labs       | 1        | 0.53%   |
| Corsair             | 1        | 0.53%   |
| AVID Technology     | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 16       | 7.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14       | 6.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12       | 5.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9        | 4.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 8        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 3.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8        | 3.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7        | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 3.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 3.18%   |
| Nvidia High Definition Audio Controller                                                           | 6        | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6        | 2.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5        | 2.27%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4        | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4        | 1.82%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 1.82%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4        | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 4        | 1.82%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 4        | 1.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.36%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3        | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.91%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2        | 0.91%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.91%   |
| Logitech H390 headset with microphone                                                             | 2        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 0.91%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2        | 0.91%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2        | 0.91%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2        | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 0.91%   |
| Texas Instruments PCM2900B Audio CODEC                                                            | 1        | 0.45%   |
| Plantronics Blackwire 5220 Series                                                                 | 1        | 0.45%   |
| Plantronics Blackwire 3220 Series                                                                 | 1        | 0.45%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.45%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1        | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.45%   |
| Lynx Hilo                                                                                         | 1        | 0.45%   |
| Intel USB PnP Sound Device                                                                        | 1        | 0.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 0.45%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 1        | 0.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.45%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 0.45%   |
| Fry's Electronics EDIFIER R19U                                                                    | 1        | 0.45%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1        | 0.45%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1        | 0.45%   |
| Corsair HS60 PRO Surround USB Sound Adapter                                                       | 1        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 17.81%  |
| SK Hynix            | 11       | 15.07%  |
| Kingston            | 9        | 12.33%  |
| Crucial             | 9        | 12.33%  |
| Corsair             | 8        | 10.96%  |
| Samsung Electronics | 6        | 8.22%   |
| G.Skill             | 5        | 6.85%   |
| Team                | 3        | 4.11%   |
| Micron Technology   | 2        | 2.74%   |
| TwinMOS             | 1        | 1.37%   |
| Transcend           | 1        | 1.37%   |
| Ramaxel Technology  | 1        | 1.37%   |
| Nanya Technology    | 1        | 1.37%   |
| Elpida              | 1        | 1.37%   |
| Apacer              | 1        | 1.37%   |
| A-DATA Technology   | 1        | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 2        | 2.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 2        | 2.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 2        | 2.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 2        | 2.67%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s       | 2        | 2.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1        | 1.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1        | 1.33%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                      | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                         | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 1        | 1.33%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s         | 1        | 1.33%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR2 2048MT/s         | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3200MT/s       | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s          | 1        | 1.33%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                       | 1        | 1.33%   |
| SK Hynix RAM Module 8GB DIMM DDR4 2133MT/s                  | 1        | 1.33%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s                 | 1        | 1.33%   |
| SK Hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s       | 1        | 1.33%   |
| SK Hynix RAM HMT451U7AFR8A-PB 4096MB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 1.33%   |
| SK Hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.33%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s     | 1        | 1.33%   |
| SK Hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.33%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s        | 1        | 1.33%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s        | 1        | 1.33%   |
| SK Hynix RAM HMA81GR7AFR8N-UH 8192MB DIMM DDR4 2400MT/s     | 1        | 1.33%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                   | 1        | 1.33%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                | 1        | 1.33%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s        | 1        | 1.33%   |
| Samsung RAM M391B5273DH0-CK0 4096MB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M378A1K43BB1-CPB 8192MB DIMM DDR4 2133MT/s      | 1        | 1.33%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 667MT/s         | 1        | 1.33%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2048MB DIMM DDR3 1333MT/s       | 1        | 1.33%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s          | 1        | 1.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 1        | 1.33%   |
| Micron RAM 4ATF51264AZ-2G6E1 4GB DIMM DDR4 2667MT/s         | 1        | 1.33%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s      | 1        | 1.33%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s    | 1        | 1.33%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s      | 1        | 1.33%   |
| Kingston RAM ACR512X64D3U16C11G 4096MB DIMM DDR3 1600MT/s   | 1        | 1.33%   |
| Kingston RAM 9965525-072.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| Kingston RAM 9905734-059.A00G 16GB DIMM DDR4 2666MT/s       | 1        | 1.33%   |
| Kingston RAM 9905702-021.A00G 8GB DIMM DDR4 2400MT/s        | 1        | 1.33%   |
| Kingston RAM 9905471-006.A01LF 4GB DIMM DDR3 1333MT/s       | 1        | 1.33%   |
| Kingston RAM 9905403-189.A00LF 4GB DIMM DDR3 1333MT/s       | 1        | 1.33%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s        | 1        | 1.33%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s       | 1        | 1.33%   |
| G.Skill RAM F4-3200C16-8GTZB 8192MB DIMM DDR4 3200MT/s      | 1        | 1.33%   |
| G.Skill RAM F4-2666C19-8GVR 8GB DIMM DDR4 2666MT/s          | 1        | 1.33%   |
| G.Skill RAM F4-2400C15-8GRR 8192MB DIMM DDR4 2400MT/s       | 1        | 1.33%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Elpida RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.33%   |
| Crucial RAM CT8G4DFS8213.C8FAD1 8GB DIMM DDR4 2133MT/s      | 1        | 1.33%   |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2133MT/s  | 1        | 1.33%   |
| Crucial RAM CT51264BA160B.C16F 4096MB DIMM DDR3 1600MT/s    | 1        | 1.33%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16384MB DIMM DDR4 2667MT/s | 1        | 1.33%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| Crucial RAM CB4GU2400.C8GT 4GB DIMM DDR4 2400MT/s           | 1        | 1.33%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s    | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 40%     |
| DDR4    | 22       | 36.67%  |
| Unknown | 8        | 13.33%  |
| SDRAM   | 3        | 5%      |
| DDR2    | 3        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 95%     |
| SODIMM | 3        | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 22       | 34.38%  |
| 8192  | 21       | 32.81%  |
| 16384 | 8        | 12.5%   |
| 2048  | 8        | 12.5%   |
| 32768 | 2        | 3.13%   |
| 1024  | 2        | 3.13%   |
| 512   | 1        | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 26.56%  |
| 1333    | 13       | 20.31%  |
| 2400    | 6        | 9.38%   |
| 3200    | 4        | 6.25%   |
| 2666    | 4        | 6.25%   |
| 3600    | 3        | 4.69%   |
| 2133    | 3        | 4.69%   |
| Unknown | 3        | 4.69%   |
| 2667    | 2        | 3.13%   |
| 667     | 2        | 3.13%   |
| 3466    | 1        | 1.56%   |
| 3000    | 1        | 1.56%   |
| 2800    | 1        | 1.56%   |
| 2048    | 1        | 1.56%   |
| 1800    | 1        | 1.56%   |
| 800     | 1        | 1.56%   |
| 400     | 1        | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Brother Industries | 2        | 40%     |
| Kyocera            | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP DeskJet 2130 series   | 2        | 40%     |
| Kyocera FS-1030D printer | 1        | 20%     |
| Brother MFC-J450DW       | 1        | 20%     |
| Brother HL-L2390DW       | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 7        | 50%     |
| Microdia              | 2        | 14.29%  |
| Samsung Electronics   | 1        | 7.14%   |
| Realtek Semiconductor | 1        | 7.14%   |
| Cubeternet            | 1        | 7.14%   |
| Creative Technology   | 1        | 7.14%   |
| Chicony Electronics   | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Webcam C615                     | 3        | 21.43%  |
| Logitech HD Pro Webcam C920                 | 2        | 14.29%  |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 7.14%   |
| Realtek Laptop_Integrated_Webcam_FHD        | 1        | 7.14%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 7.14%   |
| Microdia Camera                             | 1        | 7.14%   |
| Logitech Webcam C930e                       | 1        | 7.14%   |
| Logitech Webcam C270                        | 1        | 7.14%   |
| Cubeternet USB2.0 Camera                    | 1        | 7.14%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 7.14%   |
| Chicony HP Integrated Webcam                | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Giesecke & Devrient | 2        | 50%     |
| SCM Microsystems    | 1        | 25%     |
| Cherry              | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Giesecke & Devrient StarSign CUT S                     | 2        | 50%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC            | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 103      | 80.47%  |
| 1     | 21       | 16.41%  |
| 2     | 4        | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 37.93%  |
| Unassigned class         | 5        | 17.24%  |
| Storage/ide              | 5        | 17.24%  |
| Net/wireless             | 3        | 10.34%  |
| Network                  | 2        | 6.9%    |
| Sound                    | 1        | 3.45%   |
| Net/ethernet             | 1        | 3.45%   |
| Communication controller | 1        | 3.45%   |

