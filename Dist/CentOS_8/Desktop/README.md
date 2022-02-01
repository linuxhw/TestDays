CentOS 8 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| ASUSTek       | F1A55-M LX PLUS             | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| Unknown       | G41 Series                  | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| MSI           | Z270 GAMING PLUS            | [bd96b37321](https://linux-hardware.org/?probe=bd96b37321) | Jan 07, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [aad21a9d66](https://linux-hardware.org/?probe=aad21a9d66) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [fe889c0a84](https://linux-hardware.org/?probe=fe889c0a84) | Dec 15, 2021 |
| Unknown       | G41 Series                  | [45a2524e2b](https://linux-hardware.org/?probe=45a2524e2b) | Dec 11, 2021 |
| Unknown       | G41 Series                  | [77c738bc15](https://linux-hardware.org/?probe=77c738bc15) | Dec 09, 2021 |
| Unknown       | G41 Series                  | [8f861614bc](https://linux-hardware.org/?probe=8f861614bc) | Dec 06, 2021 |
| Unknown       | G41 Series                  | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| ASRock        | X570 Steel Legend           | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | 0C2KJT A00                  | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| Dell          | 0R038D A00                  | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [4e1b94d5c2](https://linux-hardware.org/?probe=4e1b94d5c2) | Nov 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| Gigabyte      | 970-GAMING                  | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
| Gigabyte      | 970-GAMING                  | [264e021ecb](https://linux-hardware.org/?probe=264e021ecb) | Oct 22, 2021 |
| ASUSTek       | KGPE-D16                    | [b5d2358b76](https://linux-hardware.org/?probe=b5d2358b76) | Oct 21, 2021 |
| Dell          | 0GTK4K A02                  | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| ASRock        | Z77 Extreme4                | [53b29edc51](https://linux-hardware.org/?probe=53b29edc51) | Oct 14, 2021 |
| ASRock        | Z77 Extreme4                | [0d69ee2560](https://linux-hardware.org/?probe=0d69ee2560) | Oct 10, 2021 |
| Gigabyte      | 970-GAMING                  | [9a4c250f63](https://linux-hardware.org/?probe=9a4c250f63) | Oct 06, 2021 |
| MSI           | FM2-A55M-E33                | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
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
| 4.18.0-147.8.1.el8_1.x86_64              | 13       | 8.07%   |
| 4.18.0-193.6.3.el8_2.x86_64              | 12       | 7.45%   |
| 4.18.0-193.14.2.el8_2.x86_64             | 12       | 7.45%   |
| 4.18.0-80.11.2.el8_0.x86_64              | 9        | 5.59%   |
| 4.18.0-193.28.1.el8_2.x86_64             | 9        | 5.59%   |
| 4.18.0-193.19.1.el8_2.x86_64             | 9        | 5.59%   |
| 4.18.0-348.2.1.el8_5.x86_64              | 7        | 4.35%   |
| 4.18.0-147.5.1.el8_1.x86_64              | 7        | 4.35%   |
| 4.18.0-240.22.1.el8_3.x86_64             | 6        | 3.73%   |
| 4.18.0-240.15.1.el8_3.x86_64             | 6        | 3.73%   |
| 4.18.0-240.10.1.el8_3.x86_64             | 6        | 3.73%   |
| 4.18.0-240.1.1.el8_3.x86_64              | 6        | 3.73%   |
| 4.18.0-305.19.1.el8_4.x86_64             | 5        | 3.11%   |
| 4.18.0-305.12.1.el8_4.x86_64             | 4        | 2.48%   |
| 4.18.0-301.1.el8.x86_64                  | 4        | 2.48%   |
| 4.18.0-147.el8.x86_64                    | 4        | 2.48%   |
| 4.18.0-315.el8.x86_64                    | 3        | 1.86%   |
| 4.18.0-80.el8.x86_64                     | 2        | 1.24%   |
| 4.18.0-348.7.1.el8_5.x86_64              | 2        | 1.24%   |
| 4.18.0-338.el8.x86_64                    | 2        | 1.24%   |
| 4.18.0-305.7.1.el8_4.x86_64              | 2        | 1.24%   |
| 4.18.0-305.10.2.el8_4.x86_64             | 2        | 1.24%   |
| 4.18.0-305.0.1.el8.x86_64                | 2        | 1.24%   |
| 4.18.0-294.el8.x86_64                    | 2        | 1.24%   |
| 4.18.0-277.el8.x86_64                    | 2        | 1.24%   |
| 4.18.0-240.el8.x86_64                    | 2        | 1.24%   |
| 4.18.0-193.10.el8.x86_64                 | 2        | 1.24%   |
| 4.18.0-147.3.1.el8_1.x86_64              | 2        | 1.24%   |
| 5.13.11-1.el8.elrepo.x86_64              | 1        | 0.62%   |
| 5.10.3-1.el8.elrepo.x86_64               | 1        | 0.62%   |
| 4.18.0-80.7.1.el8_0.x86_64               | 1        | 0.62%   |
| 4.18.0-358.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-348.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-326.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-305.25.1.el8_4.x86_64             | 1        | 0.62%   |
| 4.18.0-269.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-259.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-257.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-240.10.1.el8_3.centos.plus.x86_64 | 1        | 0.62%   |
| 4.18.0-193.14.2.el8_2.x86_64+debug       | 1        | 0.62%   |
| 4.18.0-177.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-168.el8.x86_64                    | 1        | 0.62%   |
| 4.18.0-147.6.el8.x86_64                  | 1        | 0.62%   |
| 4.18.0-144.el8.x86_64                    | 1        | 0.62%   |
| 3.10.0-1062.4.1.el7.x86_64               | 1        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 139      | 97.89%  |
| 5.13.11 | 1        | 0.7%    |
| 5.10.3  | 1        | 0.7%    |
| 3.10.0  | 1        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 139      | 97.89%  |
| 5.13    | 1        | 0.7%    |
| 5.10    | 1        | 0.7%    |
| 3.10    | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 142      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 107      | 73.79%  |
| Unknown       | 20       | 13.79%  |
| GNOME Classic | 10       | 6.9%    |
| XFCE          | 5        | 3.45%   |
| KDE5          | 3        | 2.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 70       | 46.98%  |
| X11     | 59       | 39.6%   |
| Unknown | 20       | 13.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 96       | 67.13%  |
| GDM     | 46       | 32.17%  |
| LightDM | 1        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 79       | 54.11%  |
| Unknown     | 12       | 8.22%   |
| en_GB       | 9        | 6.16%   |
| de_DE       | 8        | 5.48%   |
| pl_PL       | 5        | 3.42%   |
| pt_BR       | 4        | 2.74%   |
| ru_RU       | 3        | 2.05%   |
| fr_FR       | 3        | 2.05%   |
| en_CA       | 3        | 2.05%   |
| es_PE       | 2        | 1.37%   |
| en_IN       | 2        | 1.37%   |
| en_AU       | 2        | 1.37%   |
| uk_UA       | 1        | 0.68%   |
| tr_TR       | 1        | 0.68%   |
| sl_SI       | 1        | 0.68%   |
| ko_KR       | 1        | 0.68%   |
| it_IT       | 1        | 0.68%   |
| hu_HU       | 1        | 0.68%   |
| fr_CA       | 1        | 0.68%   |
| fi_FI       | 1        | 0.68%   |
| es_US       | 1        | 0.68%   |
| en_US.utf-8 | 1        | 0.68%   |
| de_LU       | 1        | 0.68%   |
| de_CH       | 1        | 0.68%   |
| cs_CZ       | 1        | 0.68%   |
| C           | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 77       | 53.85%  |
| EFI  | 66       | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 129      | 90.85%  |
| Ext4 | 13       | 9.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 81       | 56.25%  |
| GPT     | 43       | 29.86%  |
| MBR     | 20       | 13.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 90.21%  |
| Yes       | 14       | 9.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 89.44%  |
| Yes       | 15       | 10.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 34       | 23.94%  |
| Gigabyte Technology | 30       | 21.13%  |
| Dell                | 19       | 13.38%  |
| MSI                 | 15       | 10.56%  |
| Hewlett-Packard     | 14       | 9.86%   |
| ASRock              | 7        | 4.93%   |
| Supermicro          | 5        | 3.52%   |
| Unknown             | 4        | 2.82%   |
| Intel               | 3        | 2.11%   |
| Foxconn             | 3        | 2.11%   |
| Lenovo              | 2        | 1.41%   |
| Fujitsu             | 2        | 1.41%   |
| Packard Bell        | 1        | 0.7%    |
| Biostar             | 1        | 0.7%    |
| ASRockRack          | 1        | 0.7%    |
| Apple               | 1        | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 4        | 2.82%   |
| Supermicro SYS-7048A-T                  | 2        | 1.41%   |
| HP Compaq 8200 Elite SFF PC             | 2        | 1.41%   |
| Gigabyte X470 AORUS ULTRA GAMING        | 2        | 1.41%   |
| Gigabyte A320M-S2H                      | 2        | 1.41%   |
| Dell PowerEdge T40                      | 2        | 1.41%   |
| Dell OptiPlex 9020                      | 2        | 1.41%   |
| Dell OptiPlex 7010                      | 2        | 1.41%   |
| ASUS TUF B450M-PRO GAMING               | 2        | 1.41%   |
| ASUS PRIME X570-P                       | 2        | 1.41%   |
| ASUS M5A99FX PRO R2.0                   | 2        | 1.41%   |
| ASUS All Series                         | 2        | 1.41%   |
| Supermicro X9SCI/X9SCA                  | 1        | 0.7%    |
| Supermicro X8SIL                        | 1        | 0.7%    |
| Supermicro X8SAX                        | 1        | 0.7%    |
| Packard Bell IMEDIA D3610 FR            | 1        | 0.7%    |
| MSI MS-7C94                             | 1        | 0.7%    |
| MSI MS-7C88                             | 1        | 0.7%    |
| MSI MS-7C84                             | 1        | 0.7%    |
| MSI MS-7C83                             | 1        | 0.7%    |
| MSI MS-7C37                             | 1        | 0.7%    |
| MSI MS-7C02                             | 1        | 0.7%    |
| MSI MS-7A75                             | 1        | 0.7%    |
| MSI MS-7A40                             | 1        | 0.7%    |
| MSI MS-7A38                             | 1        | 0.7%    |
| MSI MS-7A36                             | 1        | 0.7%    |
| MSI MS-7918                             | 1        | 0.7%    |
| MSI MS-7793                             | 1        | 0.7%    |
| MSI MS-7756                             | 1        | 0.7%    |
| MSI MS-7636                             | 1        | 0.7%    |
| MSI HPE-421f                            | 1        | 0.7%    |
| Lenovo ThinkCentre M92p 3238AZ8         | 1        | 0.7%    |
| Lenovo IdeaCentre K410                  | 1        | 0.7%    |
| Intel DP45SG AAE27733-405               | 1        | 0.7%    |
| Intel DH55TC AAE70932-302               | 1        | 0.7%    |
| Intel D54250WYK H13922-303              | 1        | 0.7%    |
| HP Z800 Workstation                     | 1        | 0.7%    |
| HP Z600 Workstation                     | 1        | 0.7%    |
| HP Z210 Workstation                     | 1        | 0.7%    |
| HP Z2 Tower G5 Workstation              | 1        | 0.7%    |
| HP ProLiant MicroServer                 | 1        | 0.7%    |
| HP ProDesk 600 G1 SFF                   | 1        | 0.7%    |
| HP ProDesk 400 G2 MINI                  | 1        | 0.7%    |
| HP Pavilion Wave Desktop 600-a0xx       | 1        | 0.7%    |
| HP EliteDesk 800 G2 TWR                 | 1        | 0.7%    |
| HP Compaq dc7800p Convertible Minitower | 1        | 0.7%    |
| HP 290 G1 SFF Business PC               | 1        | 0.7%    |
| HP 20-r124d                             | 1        | 0.7%    |
| Gigabyte Z77X-UD5H                      | 1        | 0.7%    |
| Gigabyte Z77N-WIFI                      | 1        | 0.7%    |
| Gigabyte Z68P-DS3                       | 1        | 0.7%    |
| Gigabyte Z490 GAMING X                  | 1        | 0.7%    |
| Gigabyte Z390 DESIGNARE                 | 1        | 0.7%    |
| Gigabyte Z370 AORUS Gaming WIFI         | 1        | 0.7%    |
| Gigabyte Z170MX-Gaming 5                | 1        | 0.7%    |
| Gigabyte X58A-UD5                       | 1        | 0.7%    |
| Gigabyte X570 AORUS PRO WIFI            | 1        | 0.7%    |
| Gigabyte X570 AORUS MASTER              | 1        | 0.7%    |
| Gigabyte X399 AORUS Gaming 7            | 1        | 0.7%    |
| Gigabyte P35-DS4                        | 1        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 9        | 6.34%   |
| ASUS PRIME             | 6        | 4.23%   |
| ASUS TUF               | 5        | 3.52%   |
| Dell PowerEdge         | 4        | 2.82%   |
| Unknown                | 4        | 2.82%   |
| HP Compaq              | 3        | 2.11%   |
| Dell Inspiron          | 3        | 2.11%   |
| ASUS ROG               | 3        | 2.11%   |
| Supermicro SYS-7048A-T | 2        | 1.41%   |
| HP ProDesk             | 2        | 1.41%   |
| Gigabyte X570          | 2        | 1.41%   |
| Gigabyte X470          | 2        | 1.41%   |
| Gigabyte A320M-S2H     | 2        | 1.41%   |
| Dell Precision         | 2        | 1.41%   |
| ASUS P8Z77-V           | 2        | 1.41%   |
| ASUS M5A99FX           | 2        | 1.41%   |
| ASUS All               | 2        | 1.41%   |
| Supermicro X9SCI       | 1        | 0.7%    |
| Supermicro X8SIL       | 1        | 0.7%    |
| Supermicro X8SAX       | 1        | 0.7%    |
| Packard Bell IMEDIA    | 1        | 0.7%    |
| MSI MS-7C94            | 1        | 0.7%    |
| MSI MS-7C88            | 1        | 0.7%    |
| MSI MS-7C84            | 1        | 0.7%    |
| MSI MS-7C83            | 1        | 0.7%    |
| MSI MS-7C37            | 1        | 0.7%    |
| MSI MS-7C02            | 1        | 0.7%    |
| MSI MS-7A75            | 1        | 0.7%    |
| MSI MS-7A40            | 1        | 0.7%    |
| MSI MS-7A38            | 1        | 0.7%    |
| MSI MS-7A36            | 1        | 0.7%    |
| MSI MS-7918            | 1        | 0.7%    |
| MSI MS-7793            | 1        | 0.7%    |
| MSI MS-7756            | 1        | 0.7%    |
| MSI MS-7636            | 1        | 0.7%    |
| MSI HPE-421f           | 1        | 0.7%    |
| Lenovo ThinkCentre     | 1        | 0.7%    |
| Lenovo IdeaCentre      | 1        | 0.7%    |
| Intel DP45SG           | 1        | 0.7%    |
| Intel DH55TC           | 1        | 0.7%    |
| Intel D54250WYK        | 1        | 0.7%    |
| HP Z800                | 1        | 0.7%    |
| HP Z600                | 1        | 0.7%    |
| HP Z210                | 1        | 0.7%    |
| HP Z2                  | 1        | 0.7%    |
| HP ProLiant            | 1        | 0.7%    |
| HP Pavilion            | 1        | 0.7%    |
| HP EliteDesk           | 1        | 0.7%    |
| HP 290                 | 1        | 0.7%    |
| HP 20-r124d            | 1        | 0.7%    |
| Gigabyte Z77X-UD5H     | 1        | 0.7%    |
| Gigabyte Z77N-WIFI     | 1        | 0.7%    |
| Gigabyte Z68P-DS3      | 1        | 0.7%    |
| Gigabyte Z490          | 1        | 0.7%    |
| Gigabyte Z390          | 1        | 0.7%    |
| Gigabyte Z370          | 1        | 0.7%    |
| Gigabyte Z170MX-Gaming | 1        | 0.7%    |
| Gigabyte X58A-UD5      | 1        | 0.7%    |
| Gigabyte X399          | 1        | 0.7%    |
| Gigabyte P35-DS4       | 1        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 19       | 13.38%  |
| 2012 | 18       | 12.68%  |
| 2018 | 16       | 11.27%  |
| 2013 | 13       | 9.15%   |
| 2010 | 12       | 8.45%   |
| 2017 | 11       | 7.75%   |
| 2020 | 8        | 5.63%   |
| 2016 | 8        | 5.63%   |
| 2011 | 8        | 5.63%   |
| 2009 | 7        | 4.93%   |
| 2015 | 6        | 4.23%   |
| 2014 | 6        | 4.23%   |
| 2008 | 5        | 3.52%   |
| 2007 | 4        | 2.82%   |
| 2021 | 1        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 142      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 141      | 99.3%   |
| Enabled  | 1        | 0.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 142      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 22.92%  |
| 32.01-64.0  | 28       | 19.44%  |
| 4.01-8.0    | 27       | 18.75%  |
| 3.01-4.0    | 17       | 11.81%  |
| 8.01-16.0   | 17       | 11.81%  |
| 64.01-256.0 | 15       | 10.42%  |
| 24.01-32.0  | 5        | 3.47%   |
| 2.01-3.0    | 1        | 0.69%   |
| 1.01-2.0    | 1        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 40       | 25%     |
| 3.01-4.0   | 33       | 20.63%  |
| 4.01-8.0   | 31       | 19.38%  |
| 1.01-2.0   | 28       | 17.5%   |
| 8.01-16.0  | 15       | 9.38%   |
| 0.51-1.0   | 8        | 5%      |
| 16.01-24.0 | 2        | 1.25%   |
| 0.01-0.5   | 2        | 1.25%   |
| 32.01-64.0 | 1        | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 38.19%  |
| 2      | 32       | 22.22%  |
| 3      | 25       | 17.36%  |
| 4      | 12       | 8.33%   |
| 6      | 5        | 3.47%   |
| 5      | 5        | 3.47%   |
| 7      | 3        | 2.08%   |
| 19     | 2        | 1.39%   |
| 8      | 2        | 1.39%   |
| 15     | 1        | 0.69%   |
| 13     | 1        | 0.69%   |
| 9      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 59.44%  |
| Yes       | 58       | 40.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 142      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 65.97%  |
| Yes       | 49       | 34.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 68.31%  |
| Yes       | 45       | 31.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 32       | 22.54%  |
| Germany            | 14       | 9.86%   |
| India              | 9        | 6.34%   |
| Brazil             | 8        | 5.63%   |
| Canada             | 6        | 4.23%   |
| Russia             | 5        | 3.52%   |
| Poland             | 5        | 3.52%   |
| UK                 | 4        | 2.82%   |
| France             | 4        | 2.82%   |
| Ukraine            | 3        | 2.11%   |
| Turkey             | 3        | 2.11%   |
| Sweden             | 3        | 2.11%   |
| Netherlands        | 3        | 2.11%   |
| Finland            | 3        | 2.11%   |
| Czechia            | 3        | 2.11%   |
| Switzerland        | 2        | 1.41%   |
| Romania            | 2        | 1.41%   |
| Peru               | 2        | 1.41%   |
| Italy              | 2        | 1.41%   |
| Indonesia          | 2        | 1.41%   |
| Hong Kong          | 2        | 1.41%   |
| China              | 2        | 1.41%   |
| Australia          | 2        | 1.41%   |
| Thailand           | 1        | 0.7%    |
| Taiwan             | 1        | 0.7%    |
| South Korea        | 1        | 0.7%    |
| South Africa       | 1        | 0.7%    |
| Slovenia           | 1        | 0.7%    |
| Slovakia           | 1        | 0.7%    |
| Serbia             | 1        | 0.7%    |
| Saudi Arabia       | 1        | 0.7%    |
| Portugal           | 1        | 0.7%    |
| Norway             | 1        | 0.7%    |
| Mexico             | 1        | 0.7%    |
| Malaysia           | 1        | 0.7%    |
| Luxembourg         | 1        | 0.7%    |
| Lithuania          | 1        | 0.7%    |
| Iran               | 1        | 0.7%    |
| Hungary            | 1        | 0.7%    |
| Greece             | 1        | 0.7%    |
| Dominican Republic | 1        | 0.7%    |
| Colombia           | 1        | 0.7%    |
| Belarus            | 1        | 0.7%    |
| Bangladesh         | 1        | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Berlin              | 4        | 2.8%    |
| Istanbul            | 3        | 2.1%    |
| Sydney              | 2        | 1.4%    |
| S??o Paulo          | 2        | 1.4%    |
| Portland            | 2        | 1.4%    |
| Munich              | 2        | 1.4%    |
| Lima                | 2        | 1.4%    |
| Gdansk              | 2        | 1.4%    |
| Ernakulam           | 2        | 1.4%    |
| Chicago             | 2        | 1.4%    |
| Central             | 2        | 1.4%    |
| Brno                | 2        | 1.4%    |
| Alexandria          | 2        | 1.4%    |
| Zaporizhzhia        | 1        | 0.7%    |
| Zapopan             | 1        | 0.7%    |
| Yangquan            | 1        | 0.7%    |
| Wodzis?‚aw ??l?…ski | 1        | 0.7%    |
| West Valley City    | 1        | 0.7%    |
| West Bromwich       | 1        | 0.7%    |
| Wayne               | 1        | 0.7%    |
| Waxhaw              | 1        | 0.7%    |
| Warsaw              | 1        | 0.7%    |
| Vitebsk             | 1        | 0.7%    |
| Villa Bisono        | 1        | 0.7%    |
| Vaugneray           | 1        | 0.7%    |
| Valaparla           | 1        | 0.7%    |
| Val-des-Monts       | 1        | 0.7%    |
| Untersiemau         | 1        | 0.7%    |
| Tuusula             | 1        | 0.7%    |
| Tremembe            | 1        | 0.7%    |
| Toronto             | 1        | 0.7%    |
| Tirupati            | 1        | 0.7%    |
| Tehran              | 1        | 0.7%    |
| Taubate             | 1        | 0.7%    |
| Tambov              | 1        | 0.7%    |
| Sundbyberg          | 1        | 0.7%    |
| Stuttgart           | 1        | 0.7%    |
| Stockholm           | 1        | 0.7%    |
| Spijkenisse         | 1        | 0.7%    |
| Southlake           | 1        | 0.7%    |
| Sollentuna          | 1        | 0.7%    |
| Shenzhen            | 1        | 0.7%    |
| Seongdong-gu        | 1        | 0.7%    |
| Seattle             | 1        | 0.7%    |
| Satu Mare           | 1        | 0.7%    |
| Santa Rosa          | 1        | 0.7%    |
| Salem               | 1        | 0.7%    |
| Recea               | 1        | 0.7%    |
| Pretoria            | 1        | 0.7%    |
| Prague              | 1        | 0.7%    |
| Port Saint Lucie    | 1        | 0.7%    |
| Pogorze             | 1        | 0.7%    |
| Phoenix             | 1        | 0.7%    |
| Pato Branco         | 1        | 0.7%    |
| Novosibirsk         | 1        | 0.7%    |
| Newcastle upon Tyne | 1        | 0.7%    |
| New York            | 1        | 0.7%    |
| New Taipei          | 1        | 0.7%    |
| Nesttun             | 1        | 0.7%    |
| Mumbai              | 1        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 61       | 180    | 23.02%  |
| Seagate                   | 50       | 96     | 18.87%  |
| Samsung Electronics       | 42       | 70     | 15.85%  |
| Kingston                  | 19       | 22     | 7.17%   |
| Hitachi                   | 11       | 13     | 4.15%   |
| Toshiba                   | 8        | 13     | 3.02%   |
| SanDisk                   | 8        | 9      | 3.02%   |
| Intel                     | 7        | 9      | 2.64%   |
| HGST                      | 6        | 25     | 2.26%   |
| Crucial                   | 6        | 7      | 2.26%   |
| Unknown                   | 4        | 12     | 1.51%   |
| A-DATA Technology         | 4        | 5      | 1.51%   |
| Silicon Motion            | 3        | 3      | 1.13%   |
| XPG                       | 2        | 2      | 0.75%   |
| SPCC                      | 2        | 2      | 0.75%   |
| SK Hynix                  | 2        | 2      | 0.75%   |
| PNY                       | 2        | 3      | 0.75%   |
| Phison                    | 2        | 2      | 0.75%   |
| OCZ                       | 2        | 3      | 0.75%   |
| Micron/Crucial Technology | 2        | 3      | 0.75%   |
| Micron Technology         | 2        | 3      | 0.75%   |
| Gigabyte Technology       | 2        | 2      | 0.75%   |
| Apacer                    | 2        | 2      | 0.75%   |
| Verbatim                  | 1        | 1      | 0.38%   |
| V-GeN                     | 1        | 1      | 0.38%   |
| Team                      | 1        | 1      | 0.38%   |
| SSSTC                     | 1        | 1      | 0.38%   |
| SATADOM-SL                | 1        | 1      | 0.38%   |
| ROG                       | 1        | 1      | 0.38%   |
| Realtek Semiconductor     | 1        | 1      | 0.38%   |
| PLEXTOR                   | 1        | 1      | 0.38%   |
| Patriot                   | 1        | 3      | 0.38%   |
| Lexar                     | 1        | 1      | 0.38%   |
| KIOXIA-EXCERIA            | 1        | 2      | 0.38%   |
| Hewlett-Packard           | 1        | 1      | 0.38%   |
| Dell                      | 1        | 1      | 0.38%   |
| China                     | 1        | 4      | 0.38%   |
| ASMT                      | 1        | 1      | 0.38%   |
| Apple                     | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD20EARX-00PASB0 2TB             | 6        | 1.82%   |
| Toshiba DT01ACA100 1TB               | 5        | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.22%   |
| Seagate ST500DM002-1BD142 500GB      | 4        | 1.22%   |
| Seagate ST31000528AS 1TB             | 4        | 1.22%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.22%   |
| Kingston SA400S37240G 240GB SSD      | 4        | 1.22%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3        | 0.91%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB       | 3        | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB       | 3        | 0.91%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 0.91%   |
| Samsung SSD 970 PRO 512GB            | 3        | 0.91%   |
| Samsung SSD 860 EVO 500GB            | 3        | 0.91%   |
| Samsung SSD 860 EVO 1TB              | 3        | 0.91%   |
| Samsung SSD 840 EVO 250GB            | 3        | 0.91%   |
| Samsung NVMe SSD Drive 500GB         | 3        | 0.91%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2        | 0.61%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2        | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB             | 2        | 0.61%   |
| WDC WD2500AAJS-75M0A0 250GB          | 2        | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.61%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 2        | 0.61%   |
| WDC WD2002FAEX-007BA0 2TB            | 2        | 0.61%   |
| Unknown HUH728080ALE601 8TB          | 2        | 0.61%   |
| Seagate ST31000524AS 1TB             | 2        | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB       | 2        | 0.61%   |
| Seagate ST2000DM001-9YN164 2TB       | 2        | 0.61%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 0.61%   |
| Seagate Expansion Desk 8TB           | 2        | 0.61%   |
| Sandisk NVMe SSD Drive 1TB           | 2        | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB       | 2        | 0.61%   |
| Samsung SSD 850 EVO M.2 500GB        | 2        | 0.61%   |
| Samsung SSD 850 EVO 500GB            | 2        | 0.61%   |
| Samsung SSD 850 EVO 250GB            | 2        | 0.61%   |
| Samsung SSD 840 PRO Series 256GB     | 2        | 0.61%   |
| Samsung SSD 840 EVO 120GB            | 2        | 0.61%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 0.61%   |
| Samsung NVMe SSD Drive 250GB         | 2        | 0.61%   |
| Samsung MZ7LN256HMJP-000H1 256GB SSD | 2        | 0.61%   |
| Samsung HD103SI 1TB                  | 2        | 0.61%   |
| Kingston SA400S37120G 120GB SSD      | 2        | 0.61%   |
| Intel SSDSC2KG960G8 960GB            | 2        | 0.61%   |
| Hitachi HDS721010CLA332 1TB          | 2        | 0.61%   |
| HGST HTS721010A9E630 1TB             | 2        | 0.61%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.3%    |
| XPG GAMMIX S11 Pro 2TB               | 1        | 0.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.3%    |
| WDC WD7500BPVT-55HXZT3 752GB         | 1        | 0.3%    |
| WDC WD6400AADS-00M2B0 640GB          | 1        | 0.3%    |
| WDC WD5003AZEX-00MK2A0 500GB         | 1        | 0.3%    |
| WDC WD5002ABYS-01B1B0 500GB          | 1        | 0.3%    |
| WDC WD5001AALS-00L3B2 500GB          | 1        | 0.3%    |
| WDC WD5000LUCT-63C26Y0 500GB         | 1        | 0.3%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 0.3%    |
| WDC WD5000AAKX-753CA1 500GB          | 1        | 0.3%    |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.3%    |
| WDC WD5000AAKX-00U6AA0 500GB         | 1        | 0.3%    |
| WDC WD5000AAKS-60Z1A0 500GB          | 1        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 58       | 168    | 40.28%  |
| Seagate             | 49       | 95     | 34.03%  |
| Hitachi             | 11       | 13     | 7.64%   |
| Toshiba             | 8        | 13     | 5.56%   |
| Samsung Electronics | 6        | 6      | 4.17%   |
| HGST                | 6        | 25     | 4.17%   |
| Unknown             | 3        | 11     | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| Dell                | 1        | 1      | 0.69%   |
| Apple               | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 44     | 28.57%  |
| Kingston            | 19       | 22     | 20.88%  |
| WDC                 | 7        | 12     | 7.69%   |
| Intel               | 6        | 7      | 6.59%   |
| SanDisk             | 5        | 6      | 5.49%   |
| Crucial             | 5        | 6      | 5.49%   |
| SPCC                | 2        | 2      | 2.2%    |
| SK Hynix            | 2        | 2      | 2.2%    |
| PNY                 | 2        | 3      | 2.2%    |
| OCZ                 | 2        | 3      | 2.2%    |
| Apacer              | 2        | 2      | 2.2%    |
| A-DATA Technology   | 2        | 2      | 2.2%    |
| Verbatim            | 1        | 1      | 1.1%    |
| V-GeN               | 1        | 1      | 1.1%    |
| Team                | 1        | 1      | 1.1%    |
| Seagate             | 1        | 1      | 1.1%    |
| SATADOM-SL          | 1        | 1      | 1.1%    |
| PLEXTOR             | 1        | 1      | 1.1%    |
| Patriot             | 1        | 3      | 1.1%    |
| Micron Technology   | 1        | 1      | 1.1%    |
| Lexar               | 1        | 1      | 1.1%    |
| China               | 1        | 4      | 1.1%    |
| ASMT                | 1        | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 101      | 334    | 48.1%   |
| SSD     | 74       | 127    | 35.24%  |
| NVMe    | 34       | 48     | 16.19%  |
| Unknown | 1        | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 450    | 75.86%  |
| NVMe | 34       | 48     | 19.54%  |
| SAS  | 8        | 12     | 4.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 91       | 176    | 42.72%  |
| 0.51-1.0   | 58       | 95     | 27.23%  |
| 1.01-2.0   | 35       | 85     | 16.43%  |
| 4.01-10.0  | 12       | 33     | 5.63%   |
| 3.01-4.0   | 9        | 27     | 4.23%   |
| 2.01-3.0   | 5        | 23     | 2.35%   |
| 10.01-20.0 | 3        | 22     | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 34       | 22.97%  |
| 251-500        | 26       | 17.57%  |
| 101-250        | 26       | 17.57%  |
| More than 3000 | 21       | 14.19%  |
| 1001-2000      | 21       | 14.19%  |
| 51-100         | 6        | 4.05%   |
| Unknown        | 5        | 3.38%   |
| 2001-3000      | 4        | 2.7%    |
| 21-50          | 3        | 2.03%   |
| 1-20           | 2        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 45       | 29.22%  |
| 21-50          | 29       | 18.83%  |
| 101-250        | 22       | 14.29%  |
| 51-100         | 14       | 9.09%   |
| More than 3000 | 12       | 7.79%   |
| 251-500        | 11       | 7.14%   |
| 501-1000       | 9        | 5.84%   |
| 1001-2000      | 7        | 4.55%   |
| Unknown        | 5        | 3.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST2000DM001-9YN164 2TB        | 2        | 2      | 8.7%    |
| WDC WD6400AADS-00M2B0 640GB           | 1        | 1      | 4.35%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1        | 1      | 4.35%   |
| WDC WD5000AACS-00G8B0 500GB           | 1        | 1      | 4.35%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1        | 1      | 4.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 4.35%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 4      | 4.35%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1        | 1      | 4.35%   |
| WDC WD1002FBYS-18A6B0 1TB             | 1        | 1      | 4.35%   |
| WDC RFT030VQFF-KRM5P7 3TB             | 1        | 1      | 4.35%   |
| Toshiba MK2552GSX 250GB               | 1        | 1      | 4.35%   |
| SK Hynix HFS128G32TND-N210A 128GB SSD | 1        | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 4.35%   |
| Seagate ST3400820AS 400GB             | 1        | 1      | 4.35%   |
| Seagate ST3000VM002-1ET166 3TB        | 1        | 1      | 4.35%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 4.35%   |
| Intel SSDSA2M040G2GC 40GB             | 1        | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB         | 1        | 1      | 4.35%   |
| Hitachi HDT721010SLA360 1TB           | 1        | 1      | 4.35%   |
| HGST HDS724040ALE640 4TB              | 1        | 2      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 12     | 33.33%  |
| Seagate             | 7        | 7      | 33.33%  |
| Hitachi             | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| SK Hynix            | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Intel               | 1        | 1      | 4.76%   |
| HGST                | 1        | 2      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 12     | 38.89%  |
| Seagate | 7        | 7      | 38.89%  |
| Hitachi | 2        | 2      | 11.11%  |
| Toshiba | 1        | 1      | 5.56%   |
| HGST    | 1        | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 24     | 85%     |
| SSD  | 3        | 3      | 15%     |

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
| Detected | 84       | 260    | 52.17%  |
| Works    | 57       | 221    | 35.4%   |
| Malfunc  | 19       | 27     | 11.8%   |
| Failed   | 1        | 2      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 95       | 45.02%  |
| AMD                            | 45       | 21.33%  |
| Samsung Electronics            | 16       | 7.58%   |
| ASMedia Technology             | 12       | 5.69%   |
| Marvell Technology Group       | 6        | 2.84%   |
| JMicron Technology             | 6        | 2.84%   |
| LSI Logic / Symbios Logic      | 5        | 2.37%   |
| Silicon Motion                 | 4        | 1.9%    |
| Phison Electronics             | 4        | 1.9%    |
| Sandisk                        | 3        | 1.42%   |
| Broadcom / LSI                 | 3        | 1.42%   |
| ADATA Technology               | 3        | 1.42%   |
| Micron/Crucial Technology      | 2        | 0.95%   |
| Micron Technology              | 2        | 0.95%   |
| Solid State Storage Technology | 1        | 0.47%   |
| Realtek Semiconductor          | 1        | 0.47%   |
| Nvidia                         | 1        | 0.47%   |
| KIOXIA                         | 1        | 0.47%   |
| Integrated Technology Express  | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 11.79%  |
| Intel SATA Controller [RAID mode]                                                       | 16       | 6.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 4.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.28%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.9%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 1.52%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.14%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 1.14%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 3        | 1.14%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.14%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.14%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.14%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3        | 1.14%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.76%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.76%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.76%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.76%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 2        | 0.76%   |
| Solid State Storage NVMe Datacenter LJ1 SSD [3DNAND, Rainier Controller]                | 1        | 0.38%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.38%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.38%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.38%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.38%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.38%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1        | 0.38%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.38%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.38%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.38%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 0.38%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.38%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 99       | 51.56%  |
| NVMe | 34       | 17.71%  |
| IDE  | 29       | 15.1%   |
| RAID | 25       | 13.02%  |
| SAS  | 4        | 2.08%   |
| SCSI | 1        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 68.31%  |
| AMD    | 45       | 31.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 3.5%    |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.5%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 2.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.8%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.8%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 2.1%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 2.1%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.1%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 2.1%    |
| AMD FX-8350 Eight-Core Processor            | 3        | 2.1%    |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 2        | 1.4%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.4%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.4%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.4%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i7-10700F CPU @ 2.90GHz          | 2        | 1.4%    |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 1.4%    |
| Intel Core i5-3470S CPU @ 2.90GHz           | 2        | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.4%    |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.4%    |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.4%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.4%    |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.7%    |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.7%    |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.7%    |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5606 @ 2.13GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.7%    |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.7%    |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.7%    |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 0.7%    |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz         | 1        | 0.7%    |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.7%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.7%    |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 0.7%    |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.7%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.7%    |
| Intel Genuine CPU @ 2.20GHz                 | 1        | 0.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.7%    |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.7%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.7%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.7%    |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 0.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.7%    |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 0.7%    |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.7%    |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1        | 0.7%    |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.7%    |
| Intel Core i5-4460T CPU @ 1.90GHz           | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 18.88%  |
| Intel Core i7           | 25       | 17.48%  |
| Intel Xeon              | 16       | 11.19%  |
| AMD Ryzen 5             | 11       | 7.69%   |
| Intel Core 2 Quad       | 8        | 5.59%   |
| Intel Core i3           | 7        | 4.9%    |
| AMD Ryzen 9             | 7        | 4.9%    |
| AMD Ryzen 7             | 7        | 4.9%    |
| AMD FX                  | 7        | 4.9%    |
| Intel Core 2 Duo        | 5        | 3.5%    |
| AMD Ryzen 3             | 4        | 2.8%    |
| AMD Ryzen Threadripper  | 3        | 2.1%    |
| Intel Pentium           | 2        | 1.4%    |
| AMD Ryzen 7 PRO         | 2        | 1.4%    |
| Intel Pentium Gold      | 1        | 0.7%    |
| Intel Pentium Dual-Core | 1        | 0.7%    |
| Intel Pentium Dual      | 1        | 0.7%    |
| Intel Genuine           | 1        | 0.7%    |
| Intel Core i9           | 1        | 0.7%    |
| Intel Celeron           | 1        | 0.7%    |
| Intel Atom              | 1        | 0.7%    |
| AMD Turion II Neo       | 1        | 0.7%    |
| AMD Phenom II X4        | 1        | 0.7%    |
| AMD Opteron             | 1        | 0.7%    |
| AMD A4                  | 1        | 0.7%    |
| AMD A10                 | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 72       | 50.35%  |
| 2      | 21       | 14.69%  |
| 6      | 17       | 11.89%  |
| 8      | 14       | 9.79%   |
| 12     | 10       | 6.99%   |
| 16     | 6        | 4.2%    |
| 3      | 2        | 1.4%    |
| 1      | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 95.77%  |
| 2      | 6        | 4.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 83       | 57.64%  |
| 1      | 61       | 42.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 138      | 97.18%  |
| Unknown        | 4        | 2.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 15       | 10.42%  |
| 0x306c3    | 13       | 9.03%   |
| 0x08701021 | 10       | 6.94%   |
| 0x206a7    | 8        | 5.56%   |
| 0x06000852 | 8        | 5.56%   |
| 0x0800820d | 7        | 4.86%   |
| 0x906ea    | 6        | 4.17%   |
| 0x506e3    | 6        | 4.17%   |
| 0x1067a    | 6        | 4.17%   |
| 0x106e5    | 5        | 3.47%   |
| 0x08701013 | 5        | 3.47%   |
| Unknown    | 5        | 3.47%   |
| 0xa0655    | 4        | 2.78%   |
| 0x906e9    | 4        | 2.78%   |
| 0x6fb      | 4        | 2.78%   |
| 0x6fd      | 3        | 2.08%   |
| 0x306f2    | 3        | 2.08%   |
| 0x206c2    | 3        | 2.08%   |
| 0x08101016 | 3        | 2.08%   |
| 0x106a5    | 2        | 1.39%   |
| 0x10677    | 2        | 1.39%   |
| 0x0a201009 | 2        | 1.39%   |
| 0x08001137 | 2        | 1.39%   |
| 0x906ed    | 1        | 0.69%   |
| 0x906eb    | 1        | 0.69%   |
| 0x406f1    | 1        | 0.69%   |
| 0x406c4    | 1        | 0.69%   |
| 0x40651    | 1        | 0.69%   |
| 0x206d7    | 1        | 0.69%   |
| 0x20655    | 1        | 0.69%   |
| 0x20652    | 1        | 0.69%   |
| 0x106c2    | 1        | 0.69%   |
| 0x10676    | 1        | 0.69%   |
| 0x08701011 | 1        | 0.69%   |
| 0x08600106 | 1        | 0.69%   |
| 0x08001138 | 1        | 0.69%   |
| 0x08001129 | 1        | 0.69%   |
| 0x06001119 | 1        | 0.69%   |
| 0x03000027 | 1        | 0.69%   |
| 0x010000db | 1        | 0.69%   |
| 0x010000c8 | 1        | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 17       | 11.89%  |
| Haswell     | 17       | 11.89%  |
| IvyBridge   | 15       | 10.49%  |
| KabyLake    | 12       | 8.39%   |
| SandyBridge | 10       | 6.99%   |
| Piledriver  | 9        | 6.29%   |
| Penryn      | 9        | 6.29%   |
| Zen         | 8        | 5.59%   |
| Zen+        | 7        | 4.9%    |
| Skylake     | 7        | 4.9%    |
| Nehalem     | 7        | 4.9%    |
| Core        | 7        | 4.9%    |
| Westmere    | 6        | 4.2%    |
| CometLake   | 4        | 2.8%    |
| Zen 3       | 2        | 1.4%    |
| K10         | 2        | 1.4%    |
| Silvermont  | 1        | 0.7%    |
| K10 Llano   | 1        | 0.7%    |
| Broadwell   | 1        | 0.7%    |
| Bonnell     | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 60       | 38.71%  |
| Intel                      | 53       | 34.19%  |
| AMD                        | 38       | 24.52%  |
| S3 Graphics                | 2        | 1.29%   |
| Matrox Electronics Systems | 1        | 0.65%   |
| ASPEED Technology          | 1        | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 7.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 6.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 6.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 3.85%   |
| Intel HD Graphics 530                                                       | 5        | 3.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.92%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.92%   |
| Intel HD Graphics 630                                                       | 3        | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.92%   |
| Nvidia GT218 [GeForce G210]                                                 | 2        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.28%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 2        | 1.28%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.28%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.28%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.28%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.28%   |
| S3 Graphics Savage 4                                                        | 1        | 0.64%   |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                          | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.64%   |
| Nvidia TU104GL [Quadro RTX 5000]                                            | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.64%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 0.64%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 0.64%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.64%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.64%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.64%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.64%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.64%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.64%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.64%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                          | 1        | 0.64%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 0.64%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.64%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 0.64%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.64%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.64%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.64%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 0.64%   |
| Nvidia G92 [GeForce GT 230 OEM]                                             | 1        | 0.64%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.64%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 56       | 39.16%  |
| 1 x Intel            | 45       | 31.47%  |
| 1 x AMD              | 32       | 22.38%  |
| Intel + AMD          | 3        | 2.1%    |
| 1 x S3 Graphics      | 2        | 1.4%    |
| 2 x AMD + 1 x ASPEED | 1        | 0.7%    |
| 2 x AMD              | 1        | 0.7%    |
| 1 x Matrox           | 1        | 0.7%    |
| Intel + Nvidia       | 1        | 0.7%    |
| AMD + Nvidia         | 1        | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 108      | 75.52%  |
| Proprietary | 26       | 18.18%  |
| Unknown     | 9        | 6.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 41.22%  |
| 1.01-2.0   | 24       | 16.22%  |
| 0.51-1.0   | 18       | 12.16%  |
| 0.01-0.5   | 15       | 10.14%  |
| 7.01-8.0   | 14       | 9.46%   |
| 3.01-4.0   | 8        | 5.41%   |
| 8.01-16.0  | 3        | 2.03%   |
| 5.01-6.0   | 2        | 1.35%   |
| 2.01-3.0   | 2        | 1.35%   |
| 4.01-5.0   | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 24       | 16%     |
| Dell                 | 23       | 15.33%  |
| Goldstar             | 19       | 12.67%  |
| Hewlett-Packard      | 16       | 10.67%  |
| Acer                 | 12       | 8%      |
| ViewSonic            | 6        | 4%      |
| BenQ                 | 6        | 4%      |
| Philips              | 5        | 3.33%   |
| Ancor Communications | 5        | 3.33%   |
| LG Electronics       | 4        | 2.67%   |
| Eizo                 | 4        | 2.67%   |
| Sony                 | 3        | 2%      |
| Iiyama               | 3        | 2%      |
| Xiaomi               | 2        | 1.33%   |
| Unknown              | 2        | 1.33%   |
| MStar                | 2        | 1.33%   |
| HPN                  | 2        | 1.33%   |
| AOC                  | 2        | 1.33%   |
| Xerox                | 1        | 0.67%   |
| Sceptre Tech         | 1        | 0.67%   |
| NEC Computers        | 1        | 0.67%   |
| Lenovo               | 1        | 0.67%   |
| Insignia             | 1        | 0.67%   |
| HannStar Display     | 1        | 0.67%   |
| HannStar             | 1        | 0.67%   |
| AUS                  | 1        | 0.67%   |
| ASUSTek Computer     | 1        | 0.67%   |
| Apple                | 1        | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 3        | 1.73%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 3        | 1.73%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                     | 2        | 1.16%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 480x270mm 21.7-inch    | 2        | 1.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 1.16%   |
| MStar Demo MST0030 1920x540 1150x650mm 52.0-inch                       | 2        | 1.16%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 520x330mm 24.2-inch           | 2        | 1.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.16%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 1.16%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                    | 1        | 0.58%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch              | 1        | 0.58%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.58%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch          | 1        | 0.58%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch          | 1        | 0.58%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch             | 1        | 0.58%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch             | 1        | 0.58%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.58%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                              | 1        | 0.58%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.58%   |
| Sony TV *00 SNY7C04 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.58%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                    | 1        | 0.58%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch          | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch   | 1        | 0.58%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch     | 1        | 0.58%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch     | 1        | 0.58%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch      | 1        | 0.58%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch      | 1        | 0.58%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch      | 1        | 0.58%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics S24B300 SAM08CB 1920x1080 521x293mm 23.5-inch      | 1        | 0.58%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor T22C300 1920x1080                      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch  | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 700x390mm 31.5-inch  | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1060x590mm 47.8-inch | 1        | 0.58%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor C32JG5x 3640x1920                      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor C32F391                                | 1        | 0.58%   |
| Samsung Electronics EPSON PJ     SECA114 1600x1200                     | 1        | 0.58%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch               | 1        | 0.58%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1        | 0.58%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.58%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 1        | 0.58%   |
| Philips 200XW PHL084D 1680x1050 433x271mm 20.1-inch                    | 1        | 0.58%   |
| NEC Computers LCD52V NEC6656 1024x768 304x228mm 15.0-inch              | 1        | 0.58%   |
| LG Electronics LCD Monitor W2442                                       | 1        | 0.58%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 0.58%   |
| LG Electronics LCD Monitor LG IPS FULLHD                               | 1        | 0.58%   |
| LG Electronics LCD Monitor LG HDR WQHD                                 | 1        | 0.58%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch               | 1        | 0.58%   |
| Insignia NS-39L240A13 BBY0042 1920x1080 544x326mm 25.0-inch            | 1        | 0.58%   |
| Iiyama PLE2607WS IVM5608 1920x1200 550x344mm 25.5-inch                 | 1        | 0.58%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                 | 1        | 0.58%   |
| Iiyama PL2480H IVM610B 1920x1080 520x290mm 23.4-inch                   | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 66       | 44.9%   |
| 3840x2160 (4K)     | 17       | 11.56%  |
| 1920x1200 (WUXGA)  | 11       | 7.48%   |
| Unknown            | 10       | 6.8%    |
| 1680x1050 (WSXGA+) | 8        | 5.44%   |
| 2560x1440 (QHD)    | 7        | 4.76%   |
| 3840x1080          | 3        | 2.04%   |
| 2560x1080          | 3        | 2.04%   |
| 1600x900 (HD+)     | 3        | 2.04%   |
| 1366x768 (WXGA)    | 3        | 2.04%   |
| 1024x768 (XGA)     | 3        | 2.04%   |
| 2880x1800          | 2        | 1.36%   |
| 1280x1024 (SXGA)   | 2        | 1.36%   |
| 7680x1080          | 1        | 0.68%   |
| 7280x2160          | 1        | 0.68%   |
| 5520x2160          | 1        | 0.68%   |
| 3840x1200          | 1        | 0.68%   |
| 3640x1920          | 1        | 0.68%   |
| 2560x1600          | 1        | 0.68%   |
| 1600x1200          | 1        | 0.68%   |
| 1400x1050          | 1        | 0.68%   |
| 1280x960           | 1        | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 28       | 18.54%  |
| 24      | 23       | 15.23%  |
| Unknown | 22       | 14.57%  |
| 21      | 20       | 13.25%  |
| 23      | 19       | 12.58%  |
| 20      | 6        | 3.97%   |
| 22      | 4        | 2.65%   |
| 15      | 4        | 2.65%   |
| 34      | 3        | 1.99%   |
| 31      | 3        | 1.99%   |
| 19      | 3        | 1.99%   |
| 65      | 2        | 1.32%   |
| 52      | 2        | 1.32%   |
| 40      | 2        | 1.32%   |
| 32      | 2        | 1.32%   |
| 25      | 2        | 1.32%   |
| 84      | 1        | 0.66%   |
| 54      | 1        | 0.66%   |
| 49      | 1        | 0.66%   |
| 29      | 1        | 0.66%   |
| 18      | 1        | 0.66%   |
| 17      | 1        | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 63       | 44.68%  |
| 401-500     | 29       | 20.57%  |
| Unknown     | 22       | 15.6%   |
| 601-700     | 6        | 4.26%   |
| 1001-1500   | 6        | 4.26%   |
| 701-800     | 5        | 3.55%   |
| 301-350     | 5        | 3.55%   |
| 801-900     | 2        | 1.42%   |
| 351-400     | 2        | 1.42%   |
| 1501-2000   | 1        | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 82       | 61.65%  |
| Unknown | 21       | 15.79%  |
| 16/10   | 18       | 13.53%  |
| 4/3     | 5        | 3.76%   |
| 5/4     | 3        | 2.26%   |
| 21/9    | 3        | 2.26%   |
| 3/2     | 1        | 0.75%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 47       | 32.19%  |
| 301-350        | 28       | 19.18%  |
| Unknown        | 22       | 15.07%  |
| 151-200        | 13       | 8.9%    |
| 251-300        | 12       | 8.22%   |
| 351-500        | 9        | 6.16%   |
| More than 1000 | 7        | 4.79%   |
| 101-110        | 4        | 2.74%   |
| 141-150        | 2        | 1.37%   |
| 501-1000       | 2        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 75       | 55.15%  |
| 101-120 | 25       | 18.38%  |
| Unknown | 22       | 16.18%  |
| 161-240 | 5        | 3.68%   |
| 121-160 | 5        | 3.68%   |
| 1-50    | 4        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 60.42%  |
| 2     | 28       | 19.44%  |
| 0     | 22       | 15.28%  |
| 4     | 3        | 2.08%   |
| 3     | 3        | 2.08%   |
| 6     | 1        | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 80       | 38.83%  |
| Realtek Semiconductor     | 78       | 37.86%  |
| Qualcomm Atheros          | 11       | 5.34%   |
| Broadcom                  | 11       | 5.34%   |
| Ralink Technology         | 9        | 4.37%   |
| Mellanox Technologies     | 3        | 1.46%   |
| TP-Link                   | 2        | 0.97%   |
| D-Link System             | 2        | 0.97%   |
| Broadcom Limited          | 2        | 0.97%   |
| ASIX Electronics          | 2        | 0.97%   |
| Aquantia                  | 2        | 0.97%   |
| Spreadtrum Communications | 1        | 0.49%   |
| Ralink                    | 1        | 0.49%   |
| ICS Advent                | 1        | 0.49%   |
| DisplayLink               | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Desktops | Percent |
|------------------------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 61       | 26.41%  |
| Intel I211 Gigabit Network Connection                                                                                  | 17       | 7.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 8        | 3.46%   |
| Intel 82574L Gigabit Network Connection                                                                                | 8        | 3.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 6        | 2.6%    |
| Intel Wi-Fi 6 AX200                                                                                                    | 6        | 2.6%    |
| Intel Ethernet Connection I217-LM                                                                                      | 6        | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                                       | 6        | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 5        | 2.16%   |
| Intel Ethernet Connection (2) I219-V                                                                                   | 5        | 2.16%   |
| Intel I210 Gigabit Network Connection                                                                                  | 4        | 1.73%   |
| Intel 82579V Gigabit Network Connection                                                                                | 4        | 1.73%   |
| Ralink RT5370 Wireless Adapter                                                                                         | 3        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                                                                        | 3        | 1.3%    |
| Intel Wireless-AC 9260                                                                                                 | 3        | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                                                                                  | 3        | 1.3%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                                                     | 3        | 1.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                                             | 2        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                                              | 2        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                       | 2        | 0.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 2        | 0.87%   |
| Mellanox MT27500 Family [ConnectX-3]                                                                                   | 2        | 0.87%   |
| Intel Wireless 8265 / 8275                                                                                             | 2        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                                                                   | 2        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 2        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                                                                                   | 2        | 0.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                                          | 2        | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 2        | 0.87%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                                      | 2        | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                                           | 1        | 0.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                                                 | 1        | 0.43%   |
| Spreadtrum Spreadtrum Phone                                                                                            | 1        | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                                        | 1        | 0.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                                                        | 1        | 0.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                                                 | 1        | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                                                | 1        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                                                  | 1        | 0.43%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]                          | 1        | 0.43%   |
| Realtek 802.11ac NIC                                                                                                   | 1        | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                                  | 1        | 0.43%   |
| Ralink RT2770 Wireless Adapter                                                                                         | 1        | 0.43%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                                      | 1        | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                                              | 1        | 0.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1        | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                                              | 1        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                                              | 1        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                                         | 1        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                                         | 1        | 0.43%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 1        | 0.43%   |
| Intel Wireless 7265                                                                                                    | 1        | 0.43%   |
| Intel Wireless 7260                                                                                                    | 1        | 0.43%   |
| Intel Wireless 3165                                                                                                    | 1        | 0.43%   |
| Intel Wireless 3160                                                                                                    | 1        | 0.43%   |
| Intel Ethernet Connection I218-V                                                                                       | 1        | 0.43%   |
| Intel Ethernet Connection I217-V                                                                                       | 1        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                                                                  | 1        | 0.43%   |
| Intel Ethernet Connection (11) I219-V                                                                                  | 1        | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                                                                                 | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 23       | 42.59%  |
| Ralink Technology     | 9        | 16.67%  |
| Realtek Semiconductor | 8        | 14.81%  |
| Qualcomm Atheros      | 6        | 11.11%  |
| Broadcom              | 5        | 9.26%   |
| TP-Link               | 2        | 3.7%    |
| Ralink                | 1        | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 6        | 11.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 6        | 11.11%  |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 5.56%   |
| Intel Wireless-AC 9260                                                                        | 3        | 5.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 5.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 2        | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 3.7%    |
| Intel Wireless 8265 / 8275                                                                    | 2        | 3.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1        | 1.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.85%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.85%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.85%   |
| Ralink RT2770 Wireless Adapter                                                                | 1        | 1.85%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.85%   |
| Intel Wireless 7265                                                                           | 1        | 1.85%   |
| Intel Wireless 7260                                                                           | 1        | 1.85%   |
| Intel Wireless 3165                                                                           | 1        | 1.85%   |
| Intel Wireless 3160                                                                           | 1        | 1.85%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1        | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 75       | 45.73%  |
| Intel                     | 67       | 40.85%  |
| Broadcom                  | 6        | 3.66%   |
| Qualcomm Atheros          | 5        | 3.05%   |
| D-Link System             | 2        | 1.22%   |
| Broadcom Limited          | 2        | 1.22%   |
| ASIX Electronics          | 2        | 1.22%   |
| Aquantia                  | 2        | 1.22%   |
| Spreadtrum Communications | 1        | 0.61%   |
| ICS Advent                | 1        | 0.61%   |
| DisplayLink               | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 61       | 35.06%  |
| Intel I211 Gigabit Network Connection                                         | 17       | 9.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 4.6%    |
| Intel 82574L Gigabit Network Connection                                       | 8        | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6        | 3.45%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 2.87%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 2.87%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 2.3%    |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.3%    |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 1.15%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.15%   |
| Spreadtrum Spreadtrum Phone                                                   | 1        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.57%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.57%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.57%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.57%   |
| Intel 82578DC Gigabit Network Connection                                      | 1        | 0.57%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.57%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.57%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.57%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.57%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.57%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.57%   |
| DisplayLink HP Port Replicator (Composite Device)                             | 1        | 0.57%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.57%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                                | 1        | 0.57%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.57%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1        | 0.57%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.57%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                        | 1        | 0.57%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express               | 1        | 0.57%   |
| ASIX AX88772B                                                                 | 1        | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 72.82%  |
| WiFi     | 50       | 25.64%  |
| Unknown  | 3        | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 136      | 78.61%  |
| WiFi     | 36       | 20.81%  |
| Unknown  | 1        | 0.58%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 74       | 51.75%  |
| 2     | 50       | 34.97%  |
| 3     | 14       | 9.79%   |
| 5     | 2        | 1.4%    |
| 7     | 1        | 0.7%    |
| 4     | 1        | 0.7%    |
| 0     | 1        | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 94.41%  |
| Yes  | 8        | 5.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 22       | 48.89%  |
| Cambridge Silicon Radio | 11       | 24.44%  |
| Broadcom                | 5        | 11.11%  |
| ASUSTek Computer        | 3        | 6.67%   |
| Realtek Semiconductor   | 2        | 4.44%   |
| IMC Networks            | 1        | 2.22%   |
| Apple                   | 1        | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 24.44%  |
| Intel Bluetooth Device                              | 9        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                    | 6        | 13.33%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 8.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 6.67%   |
| Realtek Bluetooth Radio                             | 2        | 4.44%   |
| Intel Bluetooth wireless interface                  | 2        | 4.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.22%   |
| IMC Networks Bluetooth Device                       | 1        | 2.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.22%   |
| ASUS Bluetooth Radio                                | 1        | 2.22%   |
| ASUS BCM20702A0                                     | 1        | 2.22%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 88       | 40.18%  |
| AMD                 | 57       | 26.03%  |
| Nvidia              | 55       | 25.11%  |
| Logitech            | 3        | 1.37%   |
| C-Media Electronics | 3        | 1.37%   |
| Plantronics         | 2        | 0.91%   |
| Creative Technology | 2        | 0.91%   |
| Creative Labs       | 2        | 0.91%   |
| Texas Instruments   | 1        | 0.46%   |
| NEC Computers       | 1        | 0.46%   |
| Lynx                | 1        | 0.46%   |
| JMTek               | 1        | 0.46%   |
| Fry's Electronics   | 1        | 0.46%   |
| Corsair             | 1        | 0.46%   |
| AVID Technology     | 1        | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 18       | 7.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14       | 5.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12       | 4.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11       | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 3.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 10       | 3.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10       | 3.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8        | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 3.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 2.77%   |
| Nvidia High Definition Audio Controller                                                           | 6        | 2.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6        | 2.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5        | 1.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 5        | 1.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5        | 1.98%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4        | 1.58%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 1.58%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 4        | 1.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 1.58%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4        | 1.58%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 4        | 1.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2        | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2        | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.79%   |
| Logitech H390 headset with microphone                                                             | 2        | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 0.79%   |
| Creative Technology Sound Blaster Play! 3                                                         | 2        | 0.79%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2        | 0.79%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2        | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 0.79%   |
| Texas Instruments PCM2900B Audio CODEC                                                            | 1        | 0.4%    |
| Plantronics Blackwire 5220 Series                                                                 | 1        | 0.4%    |
| Plantronics Blackwire 3220 Series                                                                 | 1        | 0.4%    |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.4%    |
| Nvidia GM200 High Definition Audio                                                                | 1        | 0.4%    |
| Nvidia GK110 High Definition Audio Controller                                                     | 1        | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.4%    |
| NEC Computers uPD72010x USB 2.0 Controller                                                        | 1        | 0.4%    |
| Lynx Hilo                                                                                         | 1        | 0.4%    |
| Logitech ClearChat Pro USB                                                                        | 1        | 0.4%    |
| JMTek Sharkoon 7.1 Sound Extension                                                                | 1        | 0.4%    |
| Intel USB PnP Sound Device                                                                        | 1        | 0.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 0.4%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.4%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 18.99%  |
| SK Hynix            | 11       | 13.92%  |
| Kingston            | 11       | 13.92%  |
| Crucial             | 9        | 11.39%  |
| Corsair             | 8        | 10.13%  |
| Samsung Electronics | 6        | 7.59%   |
| G.Skill             | 6        | 7.59%   |
| Team                | 3        | 3.8%    |
| Micron Technology   | 2        | 2.53%   |
| A-DATA Technology   | 2        | 2.53%   |
| TwinMOS             | 1        | 1.27%   |
| Transcend           | 1        | 1.27%   |
| Ramaxel Technology  | 1        | 1.27%   |
| Nanya Technology    | 1        | 1.27%   |
| Elpida              | 1        | 1.27%   |
| Apacer              | 1        | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 2        | 2.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2        | 2.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 2        | 2.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 2        | 2.47%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s   | 2        | 2.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1        | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 1.23%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 1.23%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                    | 1        | 1.23%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1        | 1.23%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 1.23%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s        | 1        | 1.23%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s           | 1        | 1.23%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s         | 1        | 1.23%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 2400MT/s      | 1        | 1.23%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                 | 1        | 1.23%   |
| SK Hynix RAM Module 8GB DIMM DDR4 2133MT/s                 | 1        | 1.23%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s                | 1        | 1.23%   |
| SK Hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s      | 1        | 1.23%   |
| SK Hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1        | 1.23%   |
| SK Hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 1.23%   |
| SK Hynix RAM HMA81GR7AFR8N-UH 8192MB DIMM DDR4 2400MT/s    | 1        | 1.23%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                  | 1        | 1.23%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s               | 1        | 1.23%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s       | 1        | 1.23%   |
| Samsung RAM M391B5273DH0-CK0 4096MB DIMM DDR3 1600MT/s     | 1        | 1.23%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s        | 1        | 1.23%   |
| Samsung RAM M3 78T2953EZ3-CE6 1024MB DIMM SDRAM 667MT/s    | 1        | 1.23%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s      | 1        | 1.23%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2048MB DIMM DDR3 1333MT/s      | 1        | 1.23%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s         | 1        | 1.23%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s     | 1        | 1.23%   |
| Micron RAM 4ATF51264AZ-2G6E1 4096MB DIMM DDR4 2667MT/s     | 1        | 1.23%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s          | 1        | 1.23%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s        | 1        | 1.23%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 1        | 1.23%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s     | 1        | 1.23%   |
| Kingston RAM ACR512X64D3U16C11G 4096MB DIMM DDR3 1600MT/s  | 1        | 1.23%   |
| Kingston RAM 9965745-028.A00G 16384MB DIMM DDR4 2666MT/s   | 1        | 1.23%   |
| Kingston RAM 9965525-072.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.23%   |
| Kingston RAM 9905734-059.A00G 16GB DIMM DDR4 2666MT/s      | 1        | 1.23%   |
| Kingston RAM 9905702-021.A00G 8GB DIMM DDR4 2400MT/s       | 1        | 1.23%   |
| Kingston RAM 9905471-006.A01LF 4096MB DIMM 1333MT/s        | 1        | 1.23%   |
| Kingston RAM 9905403-189.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.23%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR 667MT/s        | 1        | 1.23%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s       | 1        | 1.23%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s      | 1        | 1.23%   |
| G.Skill RAM F4-3200C16-8GTZB 8192MB DIMM DDR4 3200MT/s     | 1        | 1.23%   |
| G.Skill RAM F4-2666C19-8GVR 8GB DIMM DDR4 2666MT/s         | 1        | 1.23%   |
| G.Skill RAM F4-2400C15-8GRR 8192MB DIMM DDR4 2400MT/s      | 1        | 1.23%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s       | 1        | 1.23%   |
| Elpida RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 1.23%   |
| Crucial RAM CT8G4DFS8213.C8FAD1 8GB DIMM DDR4 2133MT/s     | 1        | 1.23%   |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2133MT/s | 1        | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 26       | 39.39%  |
| DDR3    | 24       | 36.36%  |
| Unknown | 8        | 12.12%  |
| SDRAM   | 3        | 4.55%   |
| DDR2    | 3        | 4.55%   |
| DDR     | 2        | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 63       | 95.45%  |
| SODIMM | 3        | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 23       | 32.86%  |
| 8192  | 22       | 31.43%  |
| 16384 | 10       | 14.29%  |
| 2048  | 9        | 12.86%  |
| 32768 | 3        | 4.29%   |
| 1024  | 2        | 2.86%   |
| 512   | 1        | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 22.54%  |
| 1333    | 14       | 19.72%  |
| 2400    | 6        | 8.45%   |
| 3200    | 5        | 7.04%   |
| 2666    | 5        | 7.04%   |
| 3600    | 4        | 5.63%   |
| 2667    | 3        | 4.23%   |
| 2133    | 3        | 4.23%   |
| 667     | 3        | 4.23%   |
| Unknown | 3        | 4.23%   |
| 1800    | 2        | 2.82%   |
| 3466    | 1        | 1.41%   |
| 3000    | 1        | 1.41%   |
| 2800    | 1        | 1.41%   |
| 2733    | 1        | 1.41%   |
| 2048    | 1        | 1.41%   |
| 800     | 1        | 1.41%   |
| 400     | 1        | 1.41%   |

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
| Logitech              | 9        | 50%     |
| Microdia              | 3        | 16.67%  |
| Samsung Electronics   | 1        | 5.56%   |
| Realtek Semiconductor | 1        | 5.56%   |
| Lenovo                | 1        | 5.56%   |
| Cubeternet            | 1        | 5.56%   |
| Creative Technology   | 1        | 5.56%   |
| Chicony Electronics   | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Webcam C615                     | 3        | 16.67%  |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 11.11%  |
| Logitech Webcam C270                        | 2        | 11.11%  |
| Logitech HD Pro Webcam C920                 | 2        | 11.11%  |
| Samsung Galaxy A5 (MTP)                     | 1        | 5.56%   |
| Realtek Laptop_Integrated_Webcam_FHD        | 1        | 5.56%   |
| Microdia Camera                             | 1        | 5.56%   |
| Logitech Webcam C930e                       | 1        | 5.56%   |
| Logitech StreamCam                          | 1        | 5.56%   |
| Lenovo FHD Webcam                           | 1        | 5.56%   |
| Cubeternet USB2.0 Camera                    | 1        | 5.56%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 5.56%   |
| Chicony HP Integrated Webcam                | 1        | 5.56%   |

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
| 0     | 116      | 79.45%  |
| 1     | 26       | 17.81%  |
| 2     | 4        | 2.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 36.11%  |
| Unassigned class         | 6        | 16.67%  |
| Storage/ide              | 6        | 16.67%  |
| Net/wireless             | 5        | 13.89%  |
| Sound                    | 2        | 5.56%   |
| Network                  | 2        | 5.56%   |
| Net/ethernet             | 1        | 2.78%   |
| Communication controller | 1        | 2.78%   |

