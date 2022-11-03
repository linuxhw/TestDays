CentOS 8 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z87-A                       | [d57a581b09](https://linux-hardware.org/?probe=d57a581b09) | Sep 04, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6069a015bb](https://linux-hardware.org/?probe=6069a015bb) | Jul 03, 2022 |
| Dell          | 0HD5W2 A01                  | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Dell          | 0WN7Y6 A02                  | [3e2f6e6e1c](https://linux-hardware.org/?probe=3e2f6e6e1c) | Jun 22, 2022 |
| Unknown       | G41 Series                  | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Gigabyte      | H77N-WIFI                   | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| ASUSTek       | AT4NM10T-I                  | [c70d152830](https://linux-hardware.org/?probe=c70d152830) | May 29, 2022 |
| Unknown       | G41 Series                  | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| Unknown       | G41 Series                  | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| Unknown       | G41 Series                  | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| Unknown       | G41 Series                  | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| Gigabyte      | H410M H V3                  | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Unknown       | G41 Series                  | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| Daewoo Luc... | Solo Top                    | [6d961af923](https://linux-hardware.org/?probe=6d961af923) | Mar 03, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
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
| Unknown       | G41 Series                  | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| ASRock        | X570 Steel Legend           | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | 0C2KJT A00                  | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| Dell          | 0R038D A00                  | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| Gigabyte      | 970-GAMING                  | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
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
| ASUSTek       | TUF B450M-PRO GAMING        | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
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
| ASRock        | X570 Steel Legend           | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
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
| ASRock        | X570 Steel Legend           | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| ASUSTek       | GD30CI                      | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
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
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
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
| ASUSTek       | TUF Gaming X570-PLUS        | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| Intel         | DP45SG AAE27733-405         | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
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
| ASUSTek       | P8Z77-I DELUXE              | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
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


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 13       | 7.56%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 12       | 6.98%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 12       | 6.98%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9        | 5.23%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 9        | 5.23%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 9        | 5.23%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 8        | 4.65%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7        | 4.07%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 6        | 3.49%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 6        | 3.49%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 6        | 3.49%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6        | 3.49%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 5        | 2.91%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4        | 2.33%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4        | 2.33%   |
| 4.18.0-301.1.el8.x86_64      | 4        | 2.33%   |
| 4.18.0-147.el8.x86_64        | 4        | 2.33%   |
| 4.18.0-358.el8.x86_64        | 3        | 1.74%   |
| 4.18.0-80.el8.x86_64         | 2        | 1.16%   |
| 4.18.0-383.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-348.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-338.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-315.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2        | 1.16%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 1.16%   |
| 4.18.0-305.0.1.el8.x86_64    | 2        | 1.16%   |
| 4.18.0-294.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-277.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-240.el8.x86_64        | 2        | 1.16%   |
| 4.18.0-193.10.el8.x86_64     | 2        | 1.16%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 2        | 1.16%   |
| 5.18.0-1.el8.elrepo.x86_64   | 1        | 0.58%   |
| 5.13.11-1.el8.elrepo.x86_64  | 1        | 0.58%   |
| 5.10.3-1.el8.elrepo.x86_64   | 1        | 0.58%   |
| 4.18.0-80.7.1.el8_0.x86_64   | 1        | 0.58%   |
| 4.18.0-394.el8.x86_64        | 1        | 0.58%   |
| 4.18.0-373.el8.x86_64        | 1        | 0.58%   |
| 4.18.0-365.el8.x86_64        | 1        | 0.58%   |
| 4.18.0-326.el8.x86_64        | 1        | 0.58%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 1        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 148      | 97.37%  |
| 5.18.0  | 1        | 0.66%   |
| 5.13.11 | 1        | 0.66%   |
| 5.10.3  | 1        | 0.66%   |
| 3.10.0  | 1        | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 148      | 97.37%  |
| 5.18    | 1        | 0.66%   |
| 5.13    | 1        | 0.66%   |
| 5.10    | 1        | 0.66%   |
| 3.10    | 1        | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 151      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 112      | 72.73%  |
| Unknown       | 22       | 14.29%  |
| GNOME Classic | 11       | 7.14%   |
| XFCE          | 5        | 3.25%   |
| KDE5          | 4        | 2.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 73       | 46.2%   |
| X11     | 63       | 39.87%  |
| Unknown | 22       | 13.92%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 102      | 67.11%  |
| GDM     | 48       | 31.58%  |
| SDDM    | 1        | 0.66%   |
| LightDM | 1        | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 83       | 53.55%  |
| Unknown     | 13       | 8.39%   |
| en_GB       | 10       | 6.45%   |
| de_DE       | 9        | 5.81%   |
| pl_PL       | 6        | 3.87%   |
| pt_BR       | 4        | 2.58%   |
| ru_RU       | 3        | 1.94%   |
| fr_FR       | 3        | 1.94%   |
| en_IN       | 3        | 1.94%   |
| en_CA       | 3        | 1.94%   |
| es_PE       | 2        | 1.29%   |
| en_AU       | 2        | 1.29%   |
| uk_UA       | 1        | 0.65%   |
| tr_TR       | 1        | 0.65%   |
| sl_SI       | 1        | 0.65%   |
| ko_KR       | 1        | 0.65%   |
| it_IT       | 1        | 0.65%   |
| hu_HU       | 1        | 0.65%   |
| fr_CA       | 1        | 0.65%   |
| fi_FI       | 1        | 0.65%   |
| es_US       | 1        | 0.65%   |
| en_US.utf-8 | 1        | 0.65%   |
| de_LU       | 1        | 0.65%   |
| de_CH       | 1        | 0.65%   |
| cs_CZ       | 1        | 0.65%   |
| C           | 1        | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 81       | 53.29%  |
| EFI  | 71       | 46.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 133      | 87.5%   |
| Ext4    | 15       | 9.87%   |
| Unknown | 4        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 56.86%  |
| GPT     | 45       | 29.41%  |
| MBR     | 21       | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 85.53%  |
| Yes       | 22       | 14.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 90.07%  |
| Yes       | 15       | 9.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 25.17%  |
| Gigabyte Technology | 32       | 21.19%  |
| Dell                | 21       | 13.91%  |
| MSI                 | 15       | 9.93%   |
| Hewlett-Packard     | 14       | 9.27%   |
| ASRock              | 7        | 4.64%   |
| Supermicro          | 5        | 3.31%   |
| Intel               | 4        | 2.65%   |
| Unknown             | 4        | 2.65%   |
| Foxconn             | 3        | 1.99%   |
| Lenovo              | 2        | 1.32%   |
| Fujitsu             | 2        | 1.32%   |
| Packard Bell        | 1        | 0.66%   |
| Biostar             | 1        | 0.66%   |
| ASRockRack          | 1        | 0.66%   |
| Apple               | 1        | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 4        | 2.65%   |
| ASUS All Series                  | 3        | 1.99%   |
| Supermicro SYS-7048A-T           | 2        | 1.32%   |
| HP Compaq 8200 Elite SFF PC      | 2        | 1.32%   |
| Gigabyte X470 AORUS ULTRA GAMING | 2        | 1.32%   |
| Gigabyte A320M-S2H               | 2        | 1.32%   |
| Dell PowerEdge T40               | 2        | 1.32%   |
| Dell OptiPlex 9020               | 2        | 1.32%   |
| Dell OptiPlex 7010               | 2        | 1.32%   |
| ASUS TUF B450M-PRO GAMING        | 2        | 1.32%   |
| ASUS PRIME X570-PRO              | 2        | 1.32%   |
| ASUS PRIME X570-P                | 2        | 1.32%   |
| ASUS M5A99FX PRO R2.0            | 2        | 1.32%   |
| Supermicro X9SCI/X9SCA           | 1        | 0.66%   |
| Supermicro X8SIL                 | 1        | 0.66%   |
| Supermicro X8SAX                 | 1        | 0.66%   |
| Packard Bell IMEDIA D3610 FR     | 1        | 0.66%   |
| MSI MS-7C94                      | 1        | 0.66%   |
| MSI MS-7C88                      | 1        | 0.66%   |
| MSI MS-7C84                      | 1        | 0.66%   |
| MSI MS-7C83                      | 1        | 0.66%   |
| MSI MS-7C37                      | 1        | 0.66%   |
| MSI MS-7C02                      | 1        | 0.66%   |
| MSI MS-7A75                      | 1        | 0.66%   |
| MSI MS-7A40                      | 1        | 0.66%   |
| MSI MS-7A38                      | 1        | 0.66%   |
| MSI MS-7A36                      | 1        | 0.66%   |
| MSI MS-7918                      | 1        | 0.66%   |
| MSI MS-7793                      | 1        | 0.66%   |
| MSI MS-7756                      | 1        | 0.66%   |
| MSI MS-7636                      | 1        | 0.66%   |
| MSI HPE-421f                     | 1        | 0.66%   |
| Lenovo ThinkCentre M92p 3238AZ8  | 1        | 0.66%   |
| Lenovo IdeaCentre K410           | 1        | 0.66%   |
| Intel X99                        | 1        | 0.66%   |
| Intel DP45SG AAE27733-405        | 1        | 0.66%   |
| Intel DH55TC AAE70932-302        | 1        | 0.66%   |
| Intel D54250WYK H13922-303       | 1        | 0.66%   |
| HP Z800 Workstation              | 1        | 0.66%   |
| HP Z600 Workstation              | 1        | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 10       | 6.62%   |
| ASUS PRIME             | 7        | 4.64%   |
| ASUS TUF               | 5        | 3.31%   |
| Dell PowerEdge         | 4        | 2.65%   |
| Unknown                | 4        | 2.65%   |
| HP Compaq              | 3        | 1.99%   |
| Dell Precision         | 3        | 1.99%   |
| Dell Inspiron          | 3        | 1.99%   |
| ASUS ROG               | 3        | 1.99%   |
| ASUS All               | 3        | 1.99%   |
| Supermicro SYS-7048A-T | 2        | 1.32%   |
| HP ProDesk             | 2        | 1.32%   |
| Gigabyte Z370          | 2        | 1.32%   |
| Gigabyte X570          | 2        | 1.32%   |
| Gigabyte X470          | 2        | 1.32%   |
| Gigabyte A320M-S2H     | 2        | 1.32%   |
| ASUS P8Z77-V           | 2        | 1.32%   |
| ASUS M5A99FX           | 2        | 1.32%   |
| ASUS M5A78L-M          | 2        | 1.32%   |
| Supermicro X9SCI       | 1        | 0.66%   |
| Supermicro X8SIL       | 1        | 0.66%   |
| Supermicro X8SAX       | 1        | 0.66%   |
| Packard Bell IMEDIA    | 1        | 0.66%   |
| MSI MS-7C94            | 1        | 0.66%   |
| MSI MS-7C88            | 1        | 0.66%   |
| MSI MS-7C84            | 1        | 0.66%   |
| MSI MS-7C83            | 1        | 0.66%   |
| MSI MS-7C37            | 1        | 0.66%   |
| MSI MS-7C02            | 1        | 0.66%   |
| MSI MS-7A75            | 1        | 0.66%   |
| MSI MS-7A40            | 1        | 0.66%   |
| MSI MS-7A38            | 1        | 0.66%   |
| MSI MS-7A36            | 1        | 0.66%   |
| MSI MS-7918            | 1        | 0.66%   |
| MSI MS-7793            | 1        | 0.66%   |
| MSI MS-7756            | 1        | 0.66%   |
| MSI MS-7636            | 1        | 0.66%   |
| MSI HPE-421f           | 1        | 0.66%   |
| Lenovo ThinkCentre     | 1        | 0.66%   |
| Lenovo IdeaCentre      | 1        | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 21       | 13.91%  |
| 2012 | 18       | 11.92%  |
| 2018 | 16       | 10.6%   |
| 2013 | 15       | 9.93%   |
| 2017 | 12       | 7.95%   |
| 2010 | 12       | 7.95%   |
| 2016 | 11       | 7.28%   |
| 2020 | 8        | 5.3%    |
| 2011 | 8        | 5.3%    |
| 2009 | 7        | 4.64%   |
| 2015 | 6        | 3.97%   |
| 2014 | 6        | 3.97%   |
| 2008 | 5        | 3.31%   |
| 2007 | 4        | 2.65%   |
| 2021 | 2        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 151      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 150      | 99.34%  |
| Enabled  | 1        | 0.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 35       | 23.03%  |
| 32.01-64.0  | 30       | 19.74%  |
| 4.01-8.0    | 29       | 19.08%  |
| 3.01-4.0    | 18       | 11.84%  |
| 8.01-16.0   | 17       | 11.18%  |
| 64.01-256.0 | 16       | 10.53%  |
| 24.01-32.0  | 5        | 3.29%   |
| 2.01-3.0    | 1        | 0.66%   |
| 1.01-2.0    | 1        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 42       | 25%     |
| 4.01-8.0   | 35       | 20.83%  |
| 3.01-4.0   | 34       | 20.24%  |
| 1.01-2.0   | 28       | 16.67%  |
| 8.01-16.0  | 15       | 8.93%   |
| 0.51-1.0   | 8        | 4.76%   |
| 16.01-24.0 | 3        | 1.79%   |
| 0.01-0.5   | 2        | 1.19%   |
| 32.01-64.0 | 1        | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 36.36%  |
| 2      | 36       | 23.38%  |
| 3      | 27       | 17.53%  |
| 4      | 14       | 9.09%   |
| 6      | 5        | 3.25%   |
| 5      | 5        | 3.25%   |
| 7      | 3        | 1.95%   |
| 19     | 2        | 1.3%    |
| 9      | 2        | 1.3%    |
| 8      | 2        | 1.3%    |
| 15     | 1        | 0.65%   |
| 13     | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 59.21%  |
| Yes       | 62       | 40.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 151      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 67.32%  |
| Yes       | 50       | 32.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 68.21%  |
| Yes       | 48       | 31.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 33       | 21.85%  |
| Germany      | 16       | 10.6%   |
| India        | 10       | 6.62%   |
| Brazil       | 8        | 5.3%    |
| Russia       | 6        | 3.97%   |
| Poland       | 6        | 3.97%   |
| Canada       | 6        | 3.97%   |
| UK           | 5        | 3.31%   |
| France       | 4        | 2.65%   |
| Ukraine      | 3        | 1.99%   |
| Turkey       | 3        | 1.99%   |
| Switzerland  | 3        | 1.99%   |
| Sweden       | 3        | 1.99%   |
| Netherlands  | 3        | 1.99%   |
| Finland      | 3        | 1.99%   |
| Czechia      | 3        | 1.99%   |
| Romania      | 2        | 1.32%   |
| Peru         | 2        | 1.32%   |
| Italy        | 2        | 1.32%   |
| Indonesia    | 2        | 1.32%   |
| Hong Kong    | 2        | 1.32%   |
| China        | 2        | 1.32%   |
| Australia    | 2        | 1.32%   |
| Thailand     | 1        | 0.66%   |
| Taiwan       | 1        | 0.66%   |
| South Korea  | 1        | 0.66%   |
| South Africa | 1        | 0.66%   |
| Slovenia     | 1        | 0.66%   |
| Slovakia     | 1        | 0.66%   |
| Serbia       | 1        | 0.66%   |
| Saudi Arabia | 1        | 0.66%   |
| Portugal     | 1        | 0.66%   |
| Norway       | 1        | 0.66%   |
| Mexico       | 1        | 0.66%   |
| Malaysia     | 1        | 0.66%   |
| Luxembourg   | 1        | 0.66%   |
| Lithuania    | 1        | 0.66%   |
| Iran         | 1        | 0.66%   |
| Hungary      | 1        | 0.66%   |
| Greece       | 1        | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Portland            | 4        | 2.63%   |
| Berlin              | 4        | 2.63%   |
| Warsaw              | 2        | 1.32%   |
| Sydney              | 2        | 1.32%   |
| Sao Paulo           | 2        | 1.32%   |
| Prague              | 2        | 1.32%   |
| Munich              | 2        | 1.32%   |
| Moscow              | 2        | 1.32%   |
| Lima                | 2        | 1.32%   |
| Istanbul            | 2        | 1.32%   |
| Ernakulam           | 2        | 1.32%   |
| Central             | 2        | 1.32%   |
| Bengaluru           | 2        | 1.32%   |
| Alexandria          | 2        | 1.32%   |
| Zurich              | 1        | 0.66%   |
| Zaporizhzhia        | 1        | 0.66%   |
| Zapopan             | 1        | 0.66%   |
| Yozgat              | 1        | 0.66%   |
| Wodzisław Śląski | 1        | 0.66%   |
| West Bromwich       | 1        | 0.66%   |
| Waxhaw              | 1        | 0.66%   |
| Vitebsk             | 1        | 0.66%   |
| Vaugneray           | 1        | 0.66%   |
| Val-des-Monts       | 1        | 0.66%   |
| Tuusula             | 1        | 0.66%   |
| Tremembe            | 1        | 0.66%   |
| Tehran              | 1        | 0.66%   |
| Taubate             | 1        | 0.66%   |
| Tambov              | 1        | 0.66%   |
| Sunderland          | 1        | 0.66%   |
| Sundbyberg          | 1        | 0.66%   |
| Sucy-en-Brie        | 1        | 0.66%   |
| Stuttgart           | 1        | 0.66%   |
| Stockholm           | 1        | 0.66%   |
| Southlake           | 1        | 0.66%   |
| South Jordan        | 1        | 0.66%   |
| Sopot               | 1        | 0.66%   |
| Sollentuna          | 1        | 0.66%   |
| Shenzhen            | 1        | 0.66%   |
| Satu Mare           | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 64       | 185    | 22.54%  |
| Seagate                   | 53       | 107    | 18.66%  |
| Samsung Electronics       | 43       | 69     | 15.14%  |
| Kingston                  | 21       | 24     | 7.39%   |
| Hitachi                   | 11       | 13     | 3.87%   |
| Toshiba                   | 10       | 16     | 3.52%   |
| SanDisk                   | 8        | 9      | 2.82%   |
| Intel                     | 8        | 10     | 2.82%   |
| HGST                      | 6        | 26     | 2.11%   |
| Crucial                   | 6        | 7      | 2.11%   |
| Silicon Motion            | 5        | 5      | 1.76%   |
| Unknown                   | 4        | 12     | 1.41%   |
| A-DATA Technology         | 4        | 5      | 1.41%   |
| SPCC                      | 3        | 5      | 1.06%   |
| SK hynix                  | 3        | 4      | 1.06%   |
| Phison                    | 3        | 4      | 1.06%   |
| Micron Technology         | 3        | 5      | 1.06%   |
| XPG                       | 2        | 2      | 0.7%    |
| PNY                       | 2        | 3      | 0.7%    |
| OCZ                       | 2        | 3      | 0.7%    |
| Micron/Crucial Technology | 2        | 3      | 0.7%    |
| KIOXIA-EXCERIA            | 2        | 3      | 0.7%    |
| Gigabyte Technology       | 2        | 2      | 0.7%    |
| Apacer                    | 2        | 2      | 0.7%    |
| Verbatim                  | 1        | 1      | 0.35%   |
| V-GeN                     | 1        | 1      | 0.35%   |
| Team                      | 1        | 1      | 0.35%   |
| SSSTC                     | 1        | 1      | 0.35%   |
| SATADOM-SL                | 1        | 1      | 0.35%   |
| ROG                       | 1        | 1      | 0.35%   |
| Realtek Semiconductor     | 1        | 1      | 0.35%   |
| Plextor                   | 1        | 1      | 0.35%   |
| Patriot                   | 1        | 3      | 0.35%   |
| Lexar                     | 1        | 1      | 0.35%   |
| Hewlett-Packard           | 1        | 1      | 0.35%   |
| Dell                      | 1        | 1      | 0.35%   |
| China                     | 1        | 4      | 0.35%   |
| ASMT                      | 1        | 1      | 0.35%   |
| Apple                     | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD20EARX-00PASB0 2TB            | 6        | 1.71%   |
| Toshiba DT01ACA100 1TB              | 5        | 1.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 1.14%   |
| Seagate ST500DM002-1BD142 500GB     | 4        | 1.14%   |
| Seagate ST31000528AS 1TB            | 4        | 1.14%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.14%   |
| Kingston SA400S37480G 480GB SSD     | 4        | 1.14%   |
| Kingston SA400S37240G 240GB SSD     | 4        | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.85%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 0.85%   |
| Samsung SSD 970 PRO 512GB           | 3        | 0.85%   |
| Samsung SSD 860 EVO 500GB           | 3        | 0.85%   |
| Samsung SSD 860 EVO 1TB             | 3        | 0.85%   |
| Samsung SSD 840 EVO 250GB           | 3        | 0.85%   |
| Samsung NVMe SSD Drive 500GB        | 3        | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.57%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 2        | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.57%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2        | 0.57%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.57%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2        | 0.57%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 2        | 0.57%   |
| WDC WD2002FAEX-007BA0 2TB           | 2        | 0.57%   |
| Unknown HUH728080ALE601 8TB         | 2        | 0.57%   |
| Silicon Motion NVMe SSD Drive 512GB | 2        | 0.57%   |
| Seagate ST31000524AS 1TB            | 2        | 0.57%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 0.57%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.57%   |
| Seagate Expansion Desk 8TB          | 2        | 0.57%   |
| SanDisk NVMe SSD Drive 1TB          | 2        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB      | 2        | 0.57%   |
| Samsung SSD 850 EVO M.2 500GB       | 2        | 0.57%   |
| Samsung SSD 850 EVO 500GB           | 2        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 2        | 0.57%   |
| Samsung SSD 840 PRO Series 256GB    | 2        | 0.57%   |
| Samsung SSD 840 EVO 120GB           | 2        | 0.57%   |
| Samsung NVMe SSD Drive 512GB        | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 61       | 175    | 39.87%  |
| Seagate             | 52       | 106    | 33.99%  |
| Hitachi             | 11       | 13     | 7.19%   |
| Toshiba             | 10       | 16     | 6.54%   |
| Samsung Electronics | 7        | 7      | 4.58%   |
| HGST                | 6        | 26     | 3.92%   |
| Unknown             | 3        | 11     | 1.96%   |
| Hewlett-Packard     | 1        | 1      | 0.65%   |
| Dell                | 1        | 1      | 0.65%   |
| Apple               | 1        | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 42     | 26.8%   |
| Kingston            | 20       | 23     | 20.62%  |
| WDC                 | 7        | 10     | 7.22%   |
| Intel               | 7        | 8      | 7.22%   |
| SanDisk             | 5        | 6      | 5.15%   |
| Crucial             | 5        | 6      | 5.15%   |
| SPCC                | 3        | 5      | 3.09%   |
| SK hynix            | 3        | 4      | 3.09%   |
| PNY                 | 2        | 3      | 2.06%   |
| OCZ                 | 2        | 3      | 2.06%   |
| Micron Technology   | 2        | 3      | 2.06%   |
| Apacer              | 2        | 2      | 2.06%   |
| A-DATA Technology   | 2        | 2      | 2.06%   |
| Verbatim            | 1        | 1      | 1.03%   |
| V-GeN               | 1        | 1      | 1.03%   |
| Team                | 1        | 1      | 1.03%   |
| Seagate             | 1        | 1      | 1.03%   |
| SATADOM-SL          | 1        | 1      | 1.03%   |
| Plextor             | 1        | 1      | 1.03%   |
| Patriot             | 1        | 3      | 1.03%   |
| Lexar               | 1        | 1      | 1.03%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.03%   |
| China               | 1        | 4      | 1.03%   |
| ASMT                | 1        | 1      | 1.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 107      | 357    | 47.56%  |
| SSD     | 79       | 133    | 35.11%  |
| NVMe    | 38       | 53     | 16.89%  |
| Unknown | 1        | 1      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 141      | 477    | 75.4%   |
| NVMe | 38       | 53     | 20.32%  |
| SAS  | 8        | 14     | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 181    | 42.67%  |
| 0.51-1.0   | 63       | 110    | 28%     |
| 1.01-2.0   | 36       | 83     | 16%     |
| 4.01-10.0  | 11       | 29     | 4.89%   |
| 3.01-4.0   | 10       | 33     | 4.44%   |
| 2.01-3.0   | 6        | 32     | 2.67%   |
| 10.01-20.0 | 3        | 22     | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 35       | 22.29%  |
| 101-250        | 28       | 17.83%  |
| 251-500        | 26       | 16.56%  |
| 1001-2000      | 23       | 14.65%  |
| More than 3000 | 22       | 14.01%  |
| Unknown        | 7        | 4.46%   |
| 51-100         | 6        | 3.82%   |
| 21-50          | 4        | 2.55%   |
| 2001-3000      | 4        | 2.55%   |
| 1-20           | 2        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 47       | 28.83%  |
| 21-50          | 30       | 18.4%   |
| 101-250        | 22       | 13.5%   |
| 251-500        | 14       | 8.59%   |
| 51-100         | 14       | 8.59%   |
| More than 3000 | 12       | 7.36%   |
| 501-1000       | 9        | 5.52%   |
| 1001-2000      | 8        | 4.91%   |
| Unknown        | 7        | 4.29%   |

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
| SK hynix HFS128G32TND-N210A 128GB SSD | 1        | 1      | 4.35%   |
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
| SK hynix            | 1        | 1      | 4.76%   |
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
| Detected | 90       | 279    | 52.63%  |
| Works    | 61       | 236    | 35.67%  |
| Malfunc  | 19       | 27     | 11.11%  |
| Failed   | 1        | 2      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 102      | 45.33%  |
| AMD                            | 47       | 20.89%  |
| Samsung Electronics            | 16       | 7.11%   |
| ASMedia Technology             | 12       | 5.33%   |
| JMicron Technology             | 7        | 3.11%   |
| Silicon Motion                 | 6        | 2.67%   |
| Marvell Technology Group       | 6        | 2.67%   |
| Phison Electronics             | 5        | 2.22%   |
| LSI Logic / Symbios Logic      | 5        | 2.22%   |
| SanDisk                        | 3        | 1.33%   |
| Broadcom / LSI                 | 3        | 1.33%   |
| ADATA Technology               | 3        | 1.33%   |
| Micron/Crucial Technology      | 2        | 0.89%   |
| Micron Technology              | 2        | 0.89%   |
| Solid State Storage Technology | 1        | 0.44%   |
| Realtek Semiconductor          | 1        | 0.44%   |
| Nvidia                         | 1        | 0.44%   |
| KIOXIA                         | 1        | 0.44%   |
| Kingston Technology Company    | 1        | 0.44%   |
| Integrated Technology Express  | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32       | 11.51%  |
| Intel SATA Controller [RAID mode]                                              | 17       | 6.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12       | 4.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 11       | 3.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 3.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8        | 2.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 2.16%   |
| AMD FCH SATA Controller D                                                      | 6        | 2.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5        | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 5        | 1.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 5        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 1.8%    |
| JMicron JMB363 SATA/IDE Controller                                             | 4        | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.44%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 1.44%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.44%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.44%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 4        | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4        | 1.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.08%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3        | 1.08%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 3        | 1.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 3        | 1.08%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.08%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2        | 0.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2        | 0.72%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2        | 0.72%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2        | 0.72%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.72%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 51.46%  |
| NVMe | 38       | 18.45%  |
| IDE  | 30       | 14.56%  |
| RAID | 27       | 13.11%  |
| SAS  | 4        | 1.94%   |
| SCSI | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 68.87%  |
| AMD    | 47       | 31.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 3.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.29%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 2.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.63%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.63%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 1.97%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 1.97%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.97%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.97%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.97%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 2        | 1.32%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 1.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.32%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.32%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.32%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.32%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.32%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.32%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.32%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 2        | 1.32%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 1.32%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 2        | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.32%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.32%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.32%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.66%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.66%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.66%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.66%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.66%   |
| Intel Xeon CPU E5606 @ 2.13GHz              | 1        | 0.66%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.66%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.66%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 0.66%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.66%   |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.66%   |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 0.66%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz         | 1        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 19.08%  |
| Intel Core i7           | 26       | 17.11%  |
| Intel Xeon              | 18       | 11.84%  |
| AMD Ryzen 5             | 11       | 7.24%   |
| Intel Core 2 Quad       | 8        | 5.26%   |
| AMD Ryzen 9             | 8        | 5.26%   |
| AMD FX                  | 8        | 5.26%   |
| Intel Core i3           | 7        | 4.61%   |
| AMD Ryzen 7             | 7        | 4.61%   |
| Intel Core 2 Duo        | 5        | 3.29%   |
| AMD Ryzen 3             | 4        | 2.63%   |
| Intel Pentium           | 3        | 1.97%   |
| AMD Ryzen Threadripper  | 3        | 1.97%   |
| Intel Atom              | 2        | 1.32%   |
| AMD Ryzen 7 PRO         | 2        | 1.32%   |
| Intel Pentium Gold      | 1        | 0.66%   |
| Intel Pentium Dual-Core | 1        | 0.66%   |
| Intel Pentium Dual      | 1        | 0.66%   |
| Intel Genuine           | 1        | 0.66%   |
| Intel Core i9           | 1        | 0.66%   |
| Intel Celeron           | 1        | 0.66%   |
| AMD Turion II Neo       | 1        | 0.66%   |
| AMD Phenom II X4        | 1        | 0.66%   |
| AMD Opteron             | 1        | 0.66%   |
| AMD A4                  | 1        | 0.66%   |
| AMD A10                 | 1        | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 74       | 48.68%  |
| 2      | 22       | 14.47%  |
| 6      | 20       | 13.16%  |
| 8      | 14       | 9.21%   |
| 12     | 11       | 7.24%   |
| 16     | 7        | 4.61%   |
| 3      | 2        | 1.32%   |
| 1      | 2        | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 144      | 95.36%  |
| 2      | 7        | 4.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 90       | 58.82%  |
| 1      | 63       | 41.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 147      | 97.35%  |
| Unknown        | 4        | 2.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 15       | 9.8%    |
| 0x306c3    | 14       | 9.15%   |
| 0x08701021 | 11       | 7.19%   |
| 0x06000852 | 9        | 5.88%   |
| 0x206a7    | 8        | 5.23%   |
| 0x906ea    | 7        | 4.58%   |
| 0x506e3    | 7        | 4.58%   |
| 0x0800820d | 7        | 4.58%   |
| 0x1067a    | 6        | 3.92%   |
| 0x106e5    | 5        | 3.27%   |
| 0x08701013 | 5        | 3.27%   |
| Unknown    | 5        | 3.27%   |
| 0xa0655    | 4        | 2.61%   |
| 0x906e9    | 4        | 2.61%   |
| 0x6fb      | 4        | 2.61%   |
| 0x306f2    | 4        | 2.61%   |
| 0x6fd      | 3        | 1.96%   |
| 0x206c2    | 3        | 1.96%   |
| 0x08101016 | 3        | 1.96%   |
| 0x106a5    | 2        | 1.31%   |
| 0x10677    | 2        | 1.31%   |
| 0x0a201009 | 2        | 1.31%   |
| 0x08001137 | 2        | 1.31%   |
| 0xa0653    | 1        | 0.65%   |
| 0x906ed    | 1        | 0.65%   |
| 0x906eb    | 1        | 0.65%   |
| 0x406f1    | 1        | 0.65%   |
| 0x406c4    | 1        | 0.65%   |
| 0x40651    | 1        | 0.65%   |
| 0x306e4    | 1        | 0.65%   |
| 0x206d7    | 1        | 0.65%   |
| 0x20655    | 1        | 0.65%   |
| 0x20652    | 1        | 0.65%   |
| 0x106ca    | 1        | 0.65%   |
| 0x106c2    | 1        | 0.65%   |
| 0x10676    | 1        | 0.65%   |
| 0x08701011 | 1        | 0.65%   |
| 0x08600106 | 1        | 0.65%   |
| 0x08001138 | 1        | 0.65%   |
| 0x08001129 | 1        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 19       | 12.5%   |
| Zen 2       | 18       | 11.84%  |
| IvyBridge   | 16       | 10.53%  |
| KabyLake    | 13       | 8.55%   |
| SandyBridge | 10       | 6.58%   |
| Piledriver  | 10       | 6.58%   |
| Penryn      | 9        | 5.92%   |
| Zen         | 8        | 5.26%   |
| Skylake     | 8        | 5.26%   |
| Zen+        | 7        | 4.61%   |
| Nehalem     | 7        | 4.61%   |
| Core        | 7        | 4.61%   |
| Westmere    | 6        | 3.95%   |
| CometLake   | 5        | 3.29%   |
| Zen 3       | 2        | 1.32%   |
| K10         | 2        | 1.32%   |
| Bonnell     | 2        | 1.32%   |
| Silvermont  | 1        | 0.66%   |
| K10 Llano   | 1        | 0.66%   |
| Broadwell   | 1        | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 64       | 38.55%  |
| Intel                      | 58       | 34.94%  |
| AMD                        | 40       | 24.1%   |
| S3 Graphics                | 2        | 1.2%    |
| Matrox Electronics Systems | 1        | 0.6%    |
| ASPEED Technology          | 1        | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 7.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 6.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 6.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 3.59%   |
| Intel HD Graphics 530                                                       | 6        | 3.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.4%    |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.8%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.8%    |
| Intel HD Graphics 630                                                       | 3        | 1.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.8%    |
| Nvidia GT218 [GeForce G210]                                                 | 2        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.2%    |
| Nvidia GK107 [NVS 510]                                                      | 2        | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 2        | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.2%    |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.2%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.2%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.2%    |
| S3 Graphics Savage 4                                                        | 1        | 0.6%    |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                          | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU104GL [Quadro RTX 5000]                                            | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.6%    |
| Nvidia GT218 [NVS 300]                                                      | 1        | 0.6%    |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 0.6%    |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.6%    |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 59       | 38.82%  |
| 1 x Intel            | 48       | 31.58%  |
| 1 x AMD              | 34       | 22.37%  |
| Intel + AMD          | 3        | 1.97%   |
| 1 x S3 Graphics      | 2        | 1.32%   |
| 2 x AMD + 1 x ASPEED | 1        | 0.66%   |
| 2 x AMD              | 1        | 0.66%   |
| 1 x Matrox           | 1        | 0.66%   |
| Intel + 2 x Nvidia   | 1        | 0.66%   |
| Intel + Nvidia       | 1        | 0.66%   |
| AMD + Nvidia         | 1        | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 112      | 71.79%  |
| Proprietary | 28       | 17.95%  |
| Unknown     | 16       | 10.26%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 42.77%  |
| 1.01-2.0   | 25       | 15.72%  |
| 0.51-1.0   | 20       | 12.58%  |
| 7.01-8.0   | 15       | 9.43%   |
| 0.01-0.5   | 15       | 9.43%   |
| 3.01-4.0   | 8        | 5.03%   |
| 8.01-16.0  | 3        | 1.89%   |
| 5.01-6.0   | 2        | 1.26%   |
| 2.01-3.0   | 2        | 1.26%   |
| 4.01-5.0   | 1        | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 26       | 16.35%  |
| Dell                 | 25       | 15.72%  |
| Goldstar             | 19       | 11.95%  |
| Hewlett-Packard      | 17       | 10.69%  |
| Acer                 | 13       | 8.18%   |
| BenQ                 | 7        | 4.4%    |
| ViewSonic            | 6        | 3.77%   |
| Philips              | 5        | 3.14%   |
| LG Electronics       | 5        | 3.14%   |
| Eizo                 | 5        | 3.14%   |
| Ancor Communications | 5        | 3.14%   |
| Sony                 | 3        | 1.89%   |
| Iiyama               | 3        | 1.89%   |
| Xiaomi               | 2        | 1.26%   |
| Unknown              | 2        | 1.26%   |
| MStar                | 2        | 1.26%   |
| HPN                  | 2        | 1.26%   |
| AOC                  | 2        | 1.26%   |
| Xerox                | 1        | 0.63%   |
| Sceptre Tech         | 1        | 0.63%   |
| NEC Computers        | 1        | 0.63%   |
| Lenovo               | 1        | 0.63%   |
| Insignia             | 1        | 0.63%   |
| HannStar Display     | 1        | 0.63%   |
| HannStar             | 1        | 0.63%   |
| AUS                  | 1        | 0.63%   |
| ASUSTek Computer     | 1        | 0.63%   |
| Apple                | 1        | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 3        | 1.62%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 3        | 1.62%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                   | 2        | 1.08%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch | 2        | 1.08%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch  | 2        | 1.08%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 1.08%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 2        | 1.08%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch         | 2        | 1.08%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2        | 1.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 1.08%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 1.08%   |
| BenQ LCD Monitor GW2283 3840x1080                                    | 2        | 1.08%   |
| BenQ LCD Monitor GW2283                                              | 2        | 1.08%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                  | 1        | 0.54%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.54%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.54%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch        | 1        | 0.54%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch        | 1        | 0.54%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch           | 1        | 0.54%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch           | 1        | 0.54%   |
| Unknown LCD Monitor XXX AAA 1366x768                                 | 1        | 0.54%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                            | 1        | 0.54%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.54%   |
| Sony TV *00 SNY7C04 3840x2160 952x535mm 43.0-inch                    | 1        | 0.54%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                  | 1        | 0.54%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch        | 1        | 0.54%   |
| Samsung Electronics U28E850 SAM0CCD 3840x2160 608x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch | 1        | 0.54%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch   | 1        | 0.54%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch   | 1        | 0.54%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.54%   |
| Samsung Electronics S24B300 SAM08CB 1920x1080 521x293mm 23.5-inch    | 1        | 0.54%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch    | 1        | 0.54%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 43.59%  |
| 3840x2160 (4K)     | 18       | 11.54%  |
| 1920x1200 (WUXGA)  | 11       | 7.05%   |
| Unknown            | 11       | 7.05%   |
| 1680x1050 (WSXGA+) | 9        | 5.77%   |
| 2560x1440 (QHD)    | 7        | 4.49%   |
| 3840x1080          | 4        | 2.56%   |
| 1600x900 (HD+)     | 4        | 2.56%   |
| 3440x1440          | 3        | 1.92%   |
| 2560x1080          | 3        | 1.92%   |
| 1366x768 (WXGA)    | 3        | 1.92%   |
| 1024x768 (XGA)     | 3        | 1.92%   |
| 1600x1200          | 2        | 1.28%   |
| 1280x1024 (SXGA)   | 2        | 1.28%   |
| 7680x1080          | 1        | 0.64%   |
| 7280x2160          | 1        | 0.64%   |
| 5520x2160          | 1        | 0.64%   |
| 3840x1200          | 1        | 0.64%   |
| 3640x1920          | 1        | 0.64%   |
| 2560x1600          | 1        | 0.64%   |
| 1400x1050          | 1        | 0.64%   |
| 1280x960           | 1        | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 29       | 18.13%  |
| 24      | 24       | 15%     |
| 21      | 23       | 14.38%  |
| Unknown | 23       | 14.38%  |
| 23      | 19       | 11.88%  |
| 20      | 8        | 5%      |
| 34      | 4        | 2.5%    |
| 22      | 4        | 2.5%    |
| 15      | 4        | 2.5%    |
| 31      | 3        | 1.88%   |
| 19      | 3        | 1.88%   |
| 65      | 2        | 1.25%   |
| 52      | 2        | 1.25%   |
| 40      | 2        | 1.25%   |
| 32      | 2        | 1.25%   |
| 25      | 2        | 1.25%   |
| 84      | 1        | 0.63%   |
| 54      | 1        | 0.63%   |
| 49      | 1        | 0.63%   |
| 29      | 1        | 0.63%   |
| 18      | 1        | 0.63%   |
| 17      | 1        | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 63       | 42.28%  |
| 401-500     | 34       | 22.82%  |
| Unknown     | 23       | 15.44%  |
| 601-700     | 7        | 4.7%    |
| 701-800     | 6        | 4.03%   |
| 1001-1500   | 6        | 4.03%   |
| 301-350     | 5        | 3.36%   |
| 801-900     | 2        | 1.34%   |
| 351-400     | 2        | 1.34%   |
| 1501-2000   | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 85       | 59.86%  |
| Unknown | 22       | 15.49%  |
| 16/10   | 21       | 14.79%  |
| 4/3     | 6        | 4.23%   |
| 21/9    | 4        | 2.82%   |
| 5/4     | 3        | 2.11%   |
| 3/2     | 1        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 32.9%   |
| 301-350        | 29       | 18.71%  |
| Unknown        | 23       | 14.84%  |
| 151-200        | 15       | 9.68%   |
| 251-300        | 12       | 7.74%   |
| 351-500        | 10       | 6.45%   |
| More than 1000 | 7        | 4.52%   |
| 101-110        | 3        | 1.94%   |
| 141-150        | 2        | 1.29%   |
| 501-1000       | 2        | 1.29%   |
| 111-120        | 1        | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 79       | 55.24%  |
| 101-120 | 28       | 19.58%  |
| Unknown | 23       | 16.08%  |
| 121-160 | 5        | 3.5%    |
| 1-50    | 4        | 2.8%    |
| 161-240 | 4        | 2.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 58.6%   |
| 2     | 30       | 19.11%  |
| 0     | 28       | 17.83%  |
| 4     | 3        | 1.91%   |
| 3     | 3        | 1.91%   |
| 6     | 1        | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 84       | 38.89%  |
| Realtek Semiconductor     | 83       | 38.43%  |
| Qualcomm Atheros          | 12       | 5.56%   |
| Broadcom                  | 11       | 5.09%   |
| Ralink Technology         | 9        | 4.17%   |
| Mellanox Technologies     | 3        | 1.39%   |
| TP-Link                   | 2        | 0.93%   |
| D-Link System             | 2        | 0.93%   |
| Broadcom Limited          | 2        | 0.93%   |
| ASIX Electronics          | 2        | 0.93%   |
| Aquantia                  | 2        | 0.93%   |
| Spreadtrum Communications | 1        | 0.46%   |
| Ralink                    | 1        | 0.46%   |
| ICS Advent                | 1        | 0.46%   |
| DisplayLink               | 1        | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 66       | 27.27%  |
| Intel I211 Gigabit Network Connection                                         | 18       | 7.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 3.72%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 3.31%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 2.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6        | 2.48%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 2.48%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 2.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 6        | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 2.07%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 1.65%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.65%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 1.24%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 1.24%   |
| Intel Wireless-AC 9260                                                        | 3        | 1.24%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.24%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.24%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 1.24%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.83%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2        | 0.83%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.41%   |
| Spreadtrum Spreadtrum Phone                                                   | 1        | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 43.64%  |
| Ralink Technology     | 9        | 16.36%  |
| Realtek Semiconductor | 8        | 14.55%  |
| Qualcomm Atheros      | 6        | 10.91%  |
| Broadcom              | 5        | 9.09%   |
| TP-Link               | 2        | 3.64%   |
| Ralink                | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7        | 12.73%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 10.91%  |
| Ralink RT5370 Wireless Adapter                                 | 3        | 5.45%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 5.45%   |
| Intel Wireless-AC 9260                                         | 3        | 5.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 5.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2        | 3.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 3.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 3.64%   |
| Intel Wireless 8265 / 8275                                     | 2        | 3.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 1.82%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 1.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 1.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 1.82%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 1.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 1.82%   |
| Realtek 802.11ac WLAN Adapter                                  | 1        | 1.82%   |
| Realtek 802.11ac NIC                                           | 1        | 1.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 1.82%   |
| Ralink RT2770 Wireless Adapter                                 | 1        | 1.82%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 1.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1        | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.82%   |
| Intel Wireless 7265                                            | 1        | 1.82%   |
| Intel Wireless 7260                                            | 1        | 1.82%   |
| Intel Wireless 3165                                            | 1        | 1.82%   |
| Intel Wireless 3160                                            | 1        | 1.82%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 1.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1        | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 80       | 45.98%  |
| Intel                     | 71       | 40.8%   |
| Qualcomm Atheros          | 6        | 3.45%   |
| Broadcom                  | 6        | 3.45%   |
| D-Link System             | 2        | 1.15%   |
| Broadcom Limited          | 2        | 1.15%   |
| ASIX Electronics          | 2        | 1.15%   |
| Aquantia                  | 2        | 1.15%   |
| Spreadtrum Communications | 1        | 0.57%   |
| ICS Advent                | 1        | 0.57%   |
| DisplayLink               | 1        | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 66       | 35.87%  |
| Intel I211 Gigabit Network Connection                                         | 18       | 9.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 4.89%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6        | 3.26%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 3.26%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 2.72%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 2.17%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.17%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.63%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.09%   |
| Spreadtrum Spreadtrum Phone                                                   | 1        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.54%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.54%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.54%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.54%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.54%   |
| Intel 82578DC Gigabit Network Connection                                      | 1        | 0.54%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.54%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.54%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.54%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.54%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.54%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.54%   |
| DisplayLink HP Port Replicator (Composite Device)                             | 1        | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 151      | 73.66%  |
| WiFi     | 51       | 24.88%  |
| Unknown  | 3        | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 88.54%  |
| WiFi     | 17       | 10.83%  |
| Unknown  | 1        | 0.64%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 52.63%  |
| 2     | 53       | 34.87%  |
| 3     | 14       | 9.21%   |
| 5     | 2        | 1.32%   |
| 7     | 1        | 0.66%   |
| 4     | 1        | 0.66%   |
| 0     | 1        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 94.7%   |
| Yes  | 8        | 5.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 23       | 47.92%  |
| Cambridge Silicon Radio | 13       | 27.08%  |
| Broadcom                | 5        | 10.42%  |
| ASUSTek Computer        | 3        | 6.25%   |
| Realtek Semiconductor   | 2        | 4.17%   |
| IMC Networks            | 1        | 2.08%   |
| Apple                   | 1        | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 27.08%  |
| Intel AX200 Bluetooth                               | 7        | 14.58%  |
| Intel Wireless-AC 3168 Bluetooth                    | 6        | 12.5%   |
| Intel Bluetooth wireless interface                  | 5        | 10.42%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 6.25%   |
| Realtek Bluetooth Radio                             | 2        | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.08%   |
| IMC Networks Bluetooth Device                       | 1        | 2.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.08%   |
| ASUS Bluetooth Radio                                | 1        | 2.08%   |
| ASUS BCM20702A0                                     | 1        | 2.08%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 93       | 40.26%  |
| Nvidia              | 59       | 25.54%  |
| AMD                 | 59       | 25.54%  |
| Logitech            | 3        | 1.3%    |
| Creative Labs       | 3        | 1.3%    |
| C-Media Electronics | 3        | 1.3%    |
| Plantronics         | 2        | 0.87%   |
| Creative Technology | 2        | 0.87%   |
| Texas Instruments   | 1        | 0.43%   |
| NEC Computers       | 1        | 0.43%   |
| Lynx                | 1        | 0.43%   |
| JMTek               | 1        | 0.43%   |
| Fry's Electronics   | 1        | 0.43%   |
| Corsair             | 1        | 0.43%   |
| Avid Technology     | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 7.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 5.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12       | 4.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 4.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 4.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 3.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 3.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 3%      |
| Nvidia High Definition Audio Controller                                    | 6        | 2.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 2.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 2.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 1.87%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.5%    |
| Nvidia GF106 High Definition Audio Controller                              | 4        | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 1.5%    |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.75%   |
| Logitech H390 headset with microphone                                      | 2        | 0.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 0.75%   |
| Creative Technology Sound Blaster Play! 3                                  | 2        | 0.75%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.75%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 19.51%  |
| SK hynix            | 11       | 13.41%  |
| Kingston            | 11       | 13.41%  |
| Crucial             | 9        | 10.98%  |
| Corsair             | 9        | 10.98%  |
| Samsung Electronics | 6        | 7.32%   |
| G.Skill             | 6        | 7.32%   |
| Team                | 3        | 3.66%   |
| Micron Technology   | 3        | 3.66%   |
| A-DATA Technology   | 2        | 2.44%   |
| TwinMOS             | 1        | 1.22%   |
| Transcend           | 1        | 1.22%   |
| Ramaxel Technology  | 1        | 1.22%   |
| Nanya Technology    | 1        | 1.22%   |
| Elpida              | 1        | 1.22%   |
| Apacer              | 1        | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 2.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 2.38%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 2        | 2.38%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 2.38%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 2.38%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s             | 1        | 1.19%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 1.19%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                  | 1        | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s              | 1        | 1.19%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                 | 1        | 1.19%   |
| Unknown RAM Module 2048MB DIMM DDR2                     | 1        | 1.19%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 1        | 1.19%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s     | 1        | 1.19%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s        | 1        | 1.19%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s     | 1        | 1.19%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.19%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s              | 1        | 1.19%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 1.19%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s             | 1        | 1.19%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s   | 1        | 1.19%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 1.19%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s    | 1        | 1.19%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 1.19%   |
| SK hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s    | 1        | 1.19%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s    | 1        | 1.19%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s    | 1        | 1.19%   |
| SK hynix RAM HMA81GR7AFR8N-UH 8192MB DIMM DDR4 2400MT/s | 1        | 1.19%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.19%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s            | 1        | 1.19%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s    | 1        | 1.19%   |
| Samsung RAM M391B5273DH0-CK0 4096MB DIMM DDR3 1600MT/s  | 1        | 1.19%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s     | 1        | 1.19%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 667MT/s     | 1        | 1.19%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.19%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2048MB DIMM 1333MT/s        | 1        | 1.19%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.19%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 1        | 1.19%   |
| Micron RAM 4ATF51264AZ-2G6E1 4GB DIMM DDR4 2667MT/s     | 1        | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 39.13%  |
| DDR3    | 26       | 37.68%  |
| Unknown | 8        | 11.59%  |
| SDRAM   | 3        | 4.35%   |
| DDR2    | 3        | 4.35%   |
| DDR     | 2        | 2.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 65       | 94.2%   |
| SODIMM | 4        | 5.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 31.51%  |
| 4096  | 23       | 31.51%  |
| 16384 | 11       | 15.07%  |
| 2048  | 10       | 13.7%   |
| 32768 | 3        | 4.11%   |
| 1024  | 2        | 2.74%   |
| 512   | 1        | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 21.62%  |
| 1333    | 14       | 18.92%  |
| 2400    | 7        | 9.46%   |
| 2666    | 5        | 6.76%   |
| 3600    | 4        | 5.41%   |
| 3200    | 3        | 4.05%   |
| 2667    | 3        | 4.05%   |
| 2133    | 3        | 4.05%   |
| 667     | 3        | 4.05%   |
| Unknown | 3        | 4.05%   |
| 3466    | 2        | 2.7%    |
| 800     | 2        | 2.7%    |
| 3733    | 1        | 1.35%   |
| 3000    | 1        | 1.35%   |
| 2800    | 1        | 1.35%   |
| 2733    | 1        | 1.35%   |
| 2048    | 1        | 1.35%   |
| 1867    | 1        | 1.35%   |
| 1866    | 1        | 1.35%   |
| 1800    | 1        | 1.35%   |
| 400     | 1        | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 50%     |
| Brother Industries | 2        | 33.33%  |
| Kyocera            | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP DeskJet 2130 series   | 2        | 33.33%  |
| Kyocera FS-1030D printer | 1        | 16.67%  |
| HP Smart Install         | 1        | 16.67%  |
| Brother MFC-J450DW       | 1        | 16.67%  |
| Brother HL-L2390DW       | 1        | 16.67%  |

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
| Logitech              | 10       | 47.62%  |
| Microdia              | 4        | 19.05%  |
| Lenovo                | 2        | 9.52%   |
| Samsung Electronics   | 1        | 4.76%   |
| Realtek Semiconductor | 1        | 4.76%   |
| Cubeternet            | 1        | 4.76%   |
| Creative Technology   | 1        | 4.76%   |
| Chicony Electronics   | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Webcam C615                     | 3        | 14.29%  |
| Logitech HD Pro Webcam C920                 | 3        | 14.29%  |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 9.52%   |
| Microdia Camera                             | 2        | 9.52%   |
| Logitech Webcam C270                        | 2        | 9.52%   |
| Lenovo FHD Webcam                           | 2        | 9.52%   |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 4.76%   |
| Realtek Laptop_Integrated_Webcam_FHD        | 1        | 4.76%   |
| Logitech Webcam C930e                       | 1        | 4.76%   |
| Logitech StreamCam                          | 1        | 4.76%   |
| Cubeternet USB2.0 Camera                    | 1        | 4.76%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 4.76%   |
| Chicony HP Integrated Webcam                | 1        | 4.76%   |

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
| 0     | 121      | 77.56%  |
| 1     | 30       | 19.23%  |
| 2     | 5        | 3.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 39.02%  |
| Unassigned class         | 7        | 17.07%  |
| Storage/ide              | 7        | 17.07%  |
| Net/wireless             | 5        | 12.2%   |
| Sound                    | 2        | 4.88%   |
| Network                  | 2        | 4.88%   |
| Net/ethernet             | 1        | 2.44%   |
| Communication controller | 1        | 2.44%   |

