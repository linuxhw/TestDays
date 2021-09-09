CentOS 8 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS_8/Desktop/README.md) and [notebooks](/Dist/CentOS_8/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 8750                        | Desktop     | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| Intel         | EAGLESTREAM E63448-400      | Server      | [7c59811abb](https://linux-hardware.org/?probe=7c59811abb) | Sep 08, 2021 |
| Dell          | Latitude 3420               | Notebook    | [1c1ef48be6](https://linux-hardware.org/?probe=1c1ef48be6) | Sep 06, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Dell          | Latitude E7450              | Notebook    | [090d2bd5c7](https://linux-hardware.org/?probe=090d2bd5c7) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Dell          | Latitude E7450              | Notebook    | [c2d943414c](https://linux-hardware.org/?probe=c2d943414c) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | Desktop     | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [9f3d5555ce](https://linux-hardware.org/?probe=9f3d5555ce) | Aug 26, 2021 |
| HP            | NOTEBOOKE 15-AY084TU        | Notebook    | [fe06a5029a](https://linux-hardware.org/?probe=fe06a5029a) | Aug 22, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [38843da0aa](https://linux-hardware.org/?probe=38843da0aa) | Aug 18, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | Desktop     | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [322b1fb2ba](https://linux-hardware.org/?probe=322b1fb2ba) | Aug 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [13bd66cba7](https://linux-hardware.org/?probe=13bd66cba7) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [775b415921](https://linux-hardware.org/?probe=775b415921) | Aug 08, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [e329149eb4](https://linux-hardware.org/?probe=e329149eb4) | Aug 06, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [d68ac72e1d](https://linux-hardware.org/?probe=d68ac72e1d) | Aug 03, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 0AECh D                     | Desktop     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [130fff31f2](https://linux-hardware.org/?probe=130fff31f2) | Jul 12, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [ff76aecb8e](https://linux-hardware.org/?probe=ff76aecb8e) | Jul 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8cf37f7d3d](https://linux-hardware.org/?probe=8cf37f7d3d) | Jul 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3ec82c9dc0](https://linux-hardware.org/?probe=3ec82c9dc0) | Jul 11, 2021 |
| COPELION I... | QX-350                      | Notebook    | [6fd40c02da](https://linux-hardware.org/?probe=6fd40c02da) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [4993490f00](https://linux-hardware.org/?probe=4993490f00) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [69346a0102](https://linux-hardware.org/?probe=69346a0102) | Jul 01, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [0b78463a71](https://linux-hardware.org/?probe=0b78463a71) | Jun 26, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| COPELION I... | QX-350                      | Notebook    | [afd819962a](https://linux-hardware.org/?probe=afd819962a) | Jun 16, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| COPELION I... | QX-350                      | Notebook    | [7672d01a80](https://linux-hardware.org/?probe=7672d01a80) | Jun 08, 2021 |
| COPELION I... | QX-350                      | Notebook    | [4181e36f84](https://linux-hardware.org/?probe=4181e36f84) | Jun 07, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [b9f5cb4e7c](https://linux-hardware.org/?probe=b9f5cb4e7c) | May 31, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [fa31d6f45c](https://linux-hardware.org/?probe=fa31d6f45c) | May 30, 2021 |
| Dell          | Latitude E6530              | Notebook    | [eaf1c46fce](https://linux-hardware.org/?probe=eaf1c46fce) | May 29, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| HP            | 872C                        | Mini pc     | [0e48c94f83](https://linux-hardware.org/?probe=0e48c94f83) | May 28, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [ef516b4f37](https://linux-hardware.org/?probe=ef516b4f37) | May 17, 2021 |
| HP            | 18E7                        | Desktop     | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [ce71038513](https://linux-hardware.org/?probe=ce71038513) | May 14, 2021 |
| Lenovo        | ThinkPad E490 20N8007NTX    | Notebook    | [e9efa41cf8](https://linux-hardware.org/?probe=e9efa41cf8) | May 12, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1fdc0880c5](https://linux-hardware.org/?probe=1fdc0880c5) | May 09, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| Intel         | S3210SH FRU Ver             | Server      | [591107ec98](https://linux-hardware.org/?probe=591107ec98) | May 04, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [9eb409c988](https://linux-hardware.org/?probe=9eb409c988) | May 02, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [cb93a75f6a](https://linux-hardware.org/?probe=cb93a75f6a) | Apr 28, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [1133f762f5](https://linux-hardware.org/?probe=1133f762f5) | Apr 15, 2021 |
| Dell          | Precision 3551              | Notebook    | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS20700    | Notebook    | [30edeadde3](https://linux-hardware.org/?probe=30edeadde3) | Apr 13, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0220... | Notebook    | [3aef8ed384](https://linux-hardware.org/?probe=3aef8ed384) | Apr 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | Notebook    | [c3c1d01480](https://linux-hardware.org/?probe=c3c1d01480) | Apr 09, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [523b31291c](https://linux-hardware.org/?probe=523b31291c) | Apr 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| HP            | Zbook 17 G2                 | Notebook    | [c974cb6fc7](https://linux-hardware.org/?probe=c974cb6fc7) | Apr 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | Notebook    | [3ab392c848](https://linux-hardware.org/?probe=3ab392c848) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [561d33760f](https://linux-hardware.org/?probe=561d33760f) | Mar 31, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [60fa73286f](https://linux-hardware.org/?probe=60fa73286f) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | Notebook    | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [18368633c1](https://linux-hardware.org/?probe=18368633c1) | Mar 19, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [59681c51ea](https://linux-hardware.org/?probe=59681c51ea) | Mar 19, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [096fcfddb5](https://linux-hardware.org/?probe=096fcfddb5) | Mar 14, 2021 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [7a38c478bb](https://linux-hardware.org/?probe=7a38c478bb) | Mar 12, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [ba68c7c065](https://linux-hardware.org/?probe=ba68c7c065) | Mar 09, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [b979ba17d1](https://linux-hardware.org/?probe=b979ba17d1) | Mar 07, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [47a56b26e5](https://linux-hardware.org/?probe=47a56b26e5) | Mar 07, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | Desktop     | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [fcc71c0314](https://linux-hardware.org/?probe=fcc71c0314) | Feb 13, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| Fujitsu       | D3488-A1 S26361-D3488-A1    | Server      | [86ab491564](https://linux-hardware.org/?probe=86ab491564) | Feb 08, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [032db5db0f](https://linux-hardware.org/?probe=032db5db0f) | Feb 03, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [91e6c3a3f5](https://linux-hardware.org/?probe=91e6c3a3f5) | Feb 03, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [494eafb565](https://linux-hardware.org/?probe=494eafb565) | Feb 03, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [dbf0836efc](https://linux-hardware.org/?probe=dbf0836efc) | Feb 02, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [b19f88f1bd](https://linux-hardware.org/?probe=b19f88f1bd) | Feb 02, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [59f3594f3d](https://linux-hardware.org/?probe=59f3594f3d) | Jan 28, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [6f498cb661](https://linux-hardware.org/?probe=6f498cb661) | Jan 27, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [17fef649e3](https://linux-hardware.org/?probe=17fef649e3) | Jan 25, 2021 |
| ASUSTek       | K54C                        | Notebook    | [ac91a40e03](https://linux-hardware.org/?probe=ac91a40e03) | Jan 24, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| Sony          | VPCEG15FB                   | Notebook    | [badcac9c3d](https://linux-hardware.org/?probe=badcac9c3d) | Jan 17, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [996727413b](https://linux-hardware.org/?probe=996727413b) | Jan 17, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [20c1a73c0e](https://linux-hardware.org/?probe=20c1a73c0e) | Jan 14, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | Board                       | Desktop     | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | Board                       | Desktop     | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | Board                       | Desktop     | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [6371149c87](https://linux-hardware.org/?probe=6371149c87) | Jan 08, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e105b05883](https://linux-hardware.org/?probe=e105b05883) | Jan 07, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [a1499db9fc](https://linux-hardware.org/?probe=a1499db9fc) | Jan 07, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [7f0fa0a296](https://linux-hardware.org/?probe=7f0fa0a296) | Jan 07, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | Desktop     | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1ad69ae9c9](https://linux-hardware.org/?probe=1ad69ae9c9) | Jan 04, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [dcd24f778c](https://linux-hardware.org/?probe=dcd24f778c) | Jan 03, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [f13f9a9cdc](https://linux-hardware.org/?probe=f13f9a9cdc) | Dec 31, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [752f1e24cf](https://linux-hardware.org/?probe=752f1e24cf) | Dec 31, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [16fc91341e](https://linux-hardware.org/?probe=16fc91341e) | Dec 31, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [91ed18105e](https://linux-hardware.org/?probe=91ed18105e) | Dec 31, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [34a96782e3](https://linux-hardware.org/?probe=34a96782e3) | Dec 28, 2020 |
| Dell          | XPS L521X                   | Notebook    | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| Dell          | Latitude E7240              | Notebook    | [39e57b6b18](https://linux-hardware.org/?probe=39e57b6b18) | Dec 28, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [384c4a8068](https://linux-hardware.org/?probe=384c4a8068) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | Desktop     | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [55e2883ca5](https://linux-hardware.org/?probe=55e2883ca5) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0220... | Notebook    | [048b297665](https://linux-hardware.org/?probe=048b297665) | Dec 23, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [c286ba7e5e](https://linux-hardware.org/?probe=c286ba7e5e) | Dec 18, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [809fb60059](https://linux-hardware.org/?probe=809fb60059) | Dec 18, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f5a111ab2](https://linux-hardware.org/?probe=5f5a111ab2) | Dec 16, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [814f906095](https://linux-hardware.org/?probe=814f906095) | Dec 15, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [813cd07e38](https://linux-hardware.org/?probe=813cd07e38) | Dec 14, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | Desktop     | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f050339a1d](https://linux-hardware.org/?probe=f050339a1d) | Dec 14, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [da43f75c0c](https://linux-hardware.org/?probe=da43f75c0c) | Dec 14, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [fa97344b41](https://linux-hardware.org/?probe=fa97344b41) | Dec 08, 2020 |
| Lenovo        | G70-70 80HW005XUK           | Notebook    | [a57125fe89](https://linux-hardware.org/?probe=a57125fe89) | Dec 07, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [4d423f3865](https://linux-hardware.org/?probe=4d423f3865) | Dec 07, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [a4512466f1](https://linux-hardware.org/?probe=a4512466f1) | Dec 06, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [fd5e2f0584](https://linux-hardware.org/?probe=fd5e2f0584) | Dec 05, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Dell          | Studio 1747                 | Notebook    | [dd0085228f](https://linux-hardware.org/?probe=dd0085228f) | Nov 29, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [a37a75cdcb](https://linux-hardware.org/?probe=a37a75cdcb) | Nov 29, 2020 |
| HP            | ZBook 15                    | Notebook    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [c58ad8f5e8](https://linux-hardware.org/?probe=c58ad8f5e8) | Nov 28, 2020 |
| BESSTAR Te... | AB1A                        | Mini pc     | [4b3cf9cdd0](https://linux-hardware.org/?probe=4b3cf9cdd0) | Nov 25, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [e217ea9f60](https://linux-hardware.org/?probe=e217ea9f60) | Nov 24, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [494f8123bb](https://linux-hardware.org/?probe=494f8123bb) | Nov 24, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| Lenovo        | ThinkPad X240 20AMS7XW00    | Notebook    | [b7783af763](https://linux-hardware.org/?probe=b7783af763) | Nov 19, 2020 |
| Sony          | VPCEH15FX                   | Notebook    | [cc8c7bc4c9](https://linux-hardware.org/?probe=cc8c7bc4c9) | Nov 19, 2020 |
| HP            | 81C9                        | Desktop     | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [574e7cc90c](https://linux-hardware.org/?probe=574e7cc90c) | Nov 18, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [778d8e5380](https://linux-hardware.org/?probe=778d8e5380) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [f55cd22b43](https://linux-hardware.org/?probe=f55cd22b43) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [b8d43abe6e](https://linux-hardware.org/?probe=b8d43abe6e) | Nov 18, 2020 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [026b32269e](https://linux-hardware.org/?probe=026b32269e) | Nov 17, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | Desktop     | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [0e0009bcfc](https://linux-hardware.org/?probe=0e0009bcfc) | Nov 13, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| CompuLab      | fit-PC3                     | Notebook    | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Lenovo        | ThinkPad T420 4238AB9       | Notebook    | [9c7ec388e0](https://linux-hardware.org/?probe=9c7ec388e0) | Nov 11, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| HP            | 1495                        | Desktop     | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | Desktop     | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | Desktop     | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | Desktop     | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [dbc5336b07](https://linux-hardware.org/?probe=dbc5336b07) | Nov 01, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d69c97a2c3](https://linux-hardware.org/?probe=d69c97a2c3) | Oct 30, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [98cd8695de](https://linux-hardware.org/?probe=98cd8695de) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [a0e3328769](https://linux-hardware.org/?probe=a0e3328769) | Oct 21, 2020 |
| Dell          | 0599V5 A09                  | Server      | [a98d12ad3e](https://linux-hardware.org/?probe=a98d12ad3e) | Oct 20, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [aed7cd4193](https://linux-hardware.org/?probe=aed7cd4193) | Oct 20, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | Desktop     | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| ASRock        | X99 Taichi                  | Desktop     | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [815d325e62](https://linux-hardware.org/?probe=815d325e62) | Oct 10, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [3b5beb4162](https://linux-hardware.org/?probe=3b5beb4162) | Oct 09, 2020 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50534bc0e0](https://linux-hardware.org/?probe=50534bc0e0) | Oct 01, 2020 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b00098bf37](https://linux-hardware.org/?probe=b00098bf37) | Sep 29, 2020 |
| ASUSTek       | X556UB                      | Notebook    | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [e4e1a6fb02](https://linux-hardware.org/?probe=e4e1a6fb02) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| Timi          | TM1709                      | Notebook    | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| Supermicro    | X11SPW-TF                   | Server      | [94ef768b34](https://linux-hardware.org/?probe=94ef768b34) | Sep 17, 2020 |
| Gigabyte      | P35V3                       | Notebook    | [55580f63c2](https://linux-hardware.org/?probe=55580f63c2) | Sep 14, 2020 |
| HP            | 8053                        | Desktop     | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Intel         | D54250WYK H13922-303        | Desktop     | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| Acer          | Spin SP513-51               | Convertible | [95af4b8dc9](https://linux-hardware.org/?probe=95af4b8dc9) | Aug 31, 2020 |
| HP            | 0B54h D                     | Desktop     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | Notebook    | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | Notebook    | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [2da17db4c1](https://linux-hardware.org/?probe=2da17db4c1) | Aug 19, 2020 |
| AZW           | U55                         | Mini pc     | [961d8fad80](https://linux-hardware.org/?probe=961d8fad80) | Aug 19, 2020 |
| AZW           | U55                         | Mini pc     | [6ee89b7a33](https://linux-hardware.org/?probe=6ee89b7a33) | Aug 19, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [23685585c9](https://linux-hardware.org/?probe=23685585c9) | Aug 14, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| ASRockRack    | EP2C622D16-2T               | Server      | [ef434d4b56](https://linux-hardware.org/?probe=ef434d4b56) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| MSI           | GE73VR 7RF                  | Notebook    | [8f05f68c7d](https://linux-hardware.org/?probe=8f05f68c7d) | Aug 04, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| ASUSTek       | Z10PA-D8 Series             | Server      | [da20c4ffdb](https://linux-hardware.org/?probe=da20c4ffdb) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | Desktop     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | Desktop     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| HP            | Notebook                    | Notebook    | [00a853f189](https://linux-hardware.org/?probe=00a853f189) | Aug 01, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [a161c57e9f](https://linux-hardware.org/?probe=a161c57e9f) | Jul 29, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [8907cdddd5](https://linux-hardware.org/?probe=8907cdddd5) | Jul 24, 2020 |
| Samsung       | R560                        | Notebook    | [4d35b24594](https://linux-hardware.org/?probe=4d35b24594) | Jul 23, 2020 |
| HP            | EliteBook 850 G3            | Notebook    | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [8566dd2843](https://linux-hardware.org/?probe=8566dd2843) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [116cbdcf22](https://linux-hardware.org/?probe=116cbdcf22) | Jul 09, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 0JP31P A16                  | Server      | [9d7f34d428](https://linux-hardware.org/?probe=9d7f34d428) | Jul 07, 2020 |
| Dell          | 0JP31P A16                  | Server      | [7e35e837e0](https://linux-hardware.org/?probe=7e35e837e0) | Jul 07, 2020 |
| Dell          | 073MMW A00                  | Desktop     | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [2fc3e05c67](https://linux-hardware.org/?probe=2fc3e05c67) | Jul 03, 2020 |
| Gigabyte      | EP45-DS3R                   | Desktop     | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| Unknown       | IPM31-AK                    | Desktop     | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| ASUSTek       | P8Z77-V                     | Desktop     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [8c28479e2e](https://linux-hardware.org/?probe=8c28479e2e) | Jun 19, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| MSI           | 2A9C                        | Desktop     | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [765261db4d](https://linux-hardware.org/?probe=765261db4d) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [08a9f86f96](https://linux-hardware.org/?probe=08a9f86f96) | Jun 17, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [620453a9dc](https://linux-hardware.org/?probe=620453a9dc) | Jun 16, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [3d59a7abfb](https://linux-hardware.org/?probe=3d59a7abfb) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [0fe6cc7ec2](https://linux-hardware.org/?probe=0fe6cc7ec2) | Jun 11, 2020 |
| ASRock        | X399 Professional Gaming    | Desktop     | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [0436cc9607](https://linux-hardware.org/?probe=0436cc9607) | Jun 03, 2020 |
| Intel         | DP45SG AAE27733-405         | Desktop     | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [54a9778aab](https://linux-hardware.org/?probe=54a9778aab) | May 30, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [764c88fff0](https://linux-hardware.org/?probe=764c88fff0) | May 30, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001JRT    | Notebook    | [a9b9b6f30e](https://linux-hardware.org/?probe=a9b9b6f30e) | May 29, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [6d648c7448](https://linux-hardware.org/?probe=6d648c7448) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [22c1a49189](https://linux-hardware.org/?probe=22c1a49189) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| Supermicro    | X10DAI                      | Desktop     | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [e99f24b527](https://linux-hardware.org/?probe=e99f24b527) | May 15, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [0420235572](https://linux-hardware.org/?probe=0420235572) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| ASUSTek       | X556UB                      | Notebook    | [ae412b00e1](https://linux-hardware.org/?probe=ae412b00e1) | May 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Medion        | P6622                       | Notebook    | [57721ffc8f](https://linux-hardware.org/?probe=57721ffc8f) | Apr 29, 2020 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [16dbe6c7cf](https://linux-hardware.org/?probe=16dbe6c7cf) | Apr 28, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [8d383c8ba6](https://linux-hardware.org/?probe=8d383c8ba6) | Apr 25, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [82c9bdc55a](https://linux-hardware.org/?probe=82c9bdc55a) | Apr 25, 2020 |
| Biostar       | A320MH                      | Desktop     | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [30d580cc9d](https://linux-hardware.org/?probe=30d580cc9d) | Apr 23, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [e18488f436](https://linux-hardware.org/?probe=e18488f436) | Apr 23, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| Intel         | S5000PSL                    | Server      | [0e19261b88](https://linux-hardware.org/?probe=0e19261b88) | Apr 21, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [d3f96f55f3](https://linux-hardware.org/?probe=d3f96f55f3) | Apr 15, 2020 |
| Lenovo        | ThinkPad T440 20B7004JUS    | Notebook    | [7e54937ed3](https://linux-hardware.org/?probe=7e54937ed3) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9439de5a1c](https://linux-hardware.org/?probe=9439de5a1c) | Apr 12, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| RM Educati... | RM                          | Notebook    | [548492cfc9](https://linux-hardware.org/?probe=548492cfc9) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [bb9f29477a](https://linux-hardware.org/?probe=bb9f29477a) | Apr 07, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | Desktop     | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| Dell          | 01V648 A04                  | Server      | [e27841554a](https://linux-hardware.org/?probe=e27841554a) | Mar 26, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [03322f98e6](https://linux-hardware.org/?probe=03322f98e6) | Mar 24, 2020 |
| Lenovo        | B50-70 80EU                 | Notebook    | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| HP            | 843F                        | Desktop     | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | Desktop     | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| RM Educati... | RM                          | Notebook    | [9b2c6616dd](https://linux-hardware.org/?probe=9b2c6616dd) | Mar 03, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f3e948ba19](https://linux-hardware.org/?probe=f3e948ba19) | Feb 29, 2020 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [d2b19a4a0f](https://linux-hardware.org/?probe=d2b19a4a0f) | Feb 24, 2020 |
| Acer          | One 14 Z2-485               | Notebook    | [d7c11b1573](https://linux-hardware.org/?probe=d7c11b1573) | Feb 24, 2020 |
| Acer          | One 14 Z2-485               | Notebook    | [22a7ce37ed](https://linux-hardware.org/?probe=22a7ce37ed) | Feb 24, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [f2997e7cab](https://linux-hardware.org/?probe=f2997e7cab) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d38140cd66](https://linux-hardware.org/?probe=d38140cd66) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [7d51d0400f](https://linux-hardware.org/?probe=7d51d0400f) | Feb 24, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Dell          | Precision 5510              | Notebook    | [97fdd683cd](https://linux-hardware.org/?probe=97fdd683cd) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Supermicro    | X10DAI                      | Desktop     | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [d256eaa680](https://linux-hardware.org/?probe=d256eaa680) | Feb 16, 2020 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [f86854d517](https://linux-hardware.org/?probe=f86854d517) | Feb 16, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [891cb66753](https://linux-hardware.org/?probe=891cb66753) | Feb 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10a7b3c4f3](https://linux-hardware.org/?probe=10a7b3c4f3) | Feb 01, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| Acer          | TravelMate P257-M           | Notebook    | [5dbe9649a7](https://linux-hardware.org/?probe=5dbe9649a7) | Jan 28, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| Dell          | 00NH4P A14                  | Server      | [ce13a1d7e9](https://linux-hardware.org/?probe=ce13a1d7e9) | Jan 25, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [e41e485e3b](https://linux-hardware.org/?probe=e41e485e3b) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | Desktop     | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| ASUSTek       | X550MJ                      | Notebook    | [16470618ab](https://linux-hardware.org/?probe=16470618ab) | Jan 09, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [5b5d5fc395](https://linux-hardware.org/?probe=5b5d5fc395) | Jan 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| Gigabyte      | EP45-DS4                    | Desktop     | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| AIC           | LIBRA                       | Server      | [2903921aeb](https://linux-hardware.org/?probe=2903921aeb) | Dec 17, 2019 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [46bfb60272](https://linux-hardware.org/?probe=46bfb60272) | Dec 14, 2019 |
| MSI           | H55M-E33                    | Desktop     | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | Desktop     | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | Studio 1747                 | Notebook    | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [c90b14d1e5](https://linux-hardware.org/?probe=c90b14d1e5) | Dec 03, 2019 |
| Dell          | Studio 1747                 | Notebook    | [57919c3018](https://linux-hardware.org/?probe=57919c3018) | Dec 02, 2019 |
| Dell          | Studio 1747                 | Notebook    | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| Dell          | 0PC5F7 A01                  | Desktop     | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | Desktop     | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [c96da5df5e](https://linux-hardware.org/?probe=c96da5df5e) | Nov 20, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [bf3a6bb4c3](https://linux-hardware.org/?probe=bf3a6bb4c3) | Nov 20, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [df76fe3ea4](https://linux-hardware.org/?probe=df76fe3ea4) | Nov 14, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [448a81eb7c](https://linux-hardware.org/?probe=448a81eb7c) | Nov 14, 2019 |
| HP            | ProLiant MicroServer        | Desktop     | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | Desktop     | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| HP            | Notebook                    | Notebook    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| Sony          | VPCEH26EN                   | Notebook    | [28024462ac](https://linux-hardware.org/?probe=28024462ac) | Oct 22, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| Gigabyte      | X58A-UD5                    | Desktop     | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |
| RM Educati... | RM                          | Notebook    | [4d22671841](https://linux-hardware.org/?probe=4d22671841) | Oct 03, 2019 |
| RM Educati... | RM                          | Notebook    | [4b2e9b1800](https://linux-hardware.org/?probe=4b2e9b1800) | Oct 02, 2019 |
| RM Educati... | RM                          | Notebook    | [43aad9067d](https://linux-hardware.org/?probe=43aad9067d) | Oct 02, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64              | 27        | 9.41%   |
| 4.18.0-193.6.3.el8_2.x86_64              | 24        | 8.36%   |
| 4.18.0-193.14.2.el8_2.x86_64             | 21        | 7.32%   |
| 4.18.0-193.28.1.el8_2.x86_64             | 20        | 6.97%   |
| 4.18.0-80.11.2.el8_0.x86_64              | 16        | 5.57%   |
| 4.18.0-147.5.1.el8_1.x86_64              | 16        | 5.57%   |
| 4.18.0-240.15.1.el8_3.x86_64             | 14        | 4.88%   |
| 4.18.0-240.1.1.el8_3.x86_64              | 14        | 4.88%   |
| 4.18.0-193.19.1.el8_2.x86_64             | 14        | 4.88%   |
| 4.18.0-240.22.1.el8_3.x86_64             | 12        | 4.18%   |
| 4.18.0-240.10.1.el8_3.x86_64             | 9         | 3.14%   |
| 4.18.0-305.12.1.el8_4.x86_64             | 7         | 2.44%   |
| 4.18.0-301.1.el8.x86_64                  | 7         | 2.44%   |
| 4.18.0-147.el8.x86_64                    | 7         | 2.44%   |
| 4.18.0-147.3.1.el8_1.x86_64              | 7         | 2.44%   |
| 4.18.0-294.el8.x86_64                    | 6         | 2.09%   |
| 4.18.0-80.el8.x86_64                     | 5         | 1.74%   |
| 4.18.0-277.el8.x86_64                    | 5         | 1.74%   |
| 4.18.0-315.el8.x86_64                    | 4         | 1.39%   |
| 4.18.0-305.3.1.el8.x86_64                | 4         | 1.39%   |
| 4.18.0-240.el8.x86_64                    | 4         | 1.39%   |
| 4.18.0-147.6.el8.x86_64                  | 4         | 1.39%   |
| 4.18.0-305.7.1.el8_4.x86_64              | 3         | 1.05%   |
| 4.18.0-305.10.2.el8_4.x86_64             | 3         | 1.05%   |
| 4.18.0-259.el8.x86_64                    | 3         | 1.05%   |
| 4.18.0-257.el8.x86_64                    | 3         | 1.05%   |
| 4.18.0-193.el8.x86_64                    | 3         | 1.05%   |
| 5.9.12-1.el8.elrepo.x86_64               | 2         | 0.7%    |
| 4.18.0-80.7.1.el8_0.x86_64               | 2         | 0.7%    |
| 4.18.0-269.el8.x86_64                    | 2         | 0.7%    |
| 4.18.0-193.10.el8.x86_64                 | 2         | 0.7%    |
| 4.18.0-177.el8.x86_64                    | 2         | 0.7%    |
| 5.9.1-1.el8.elrepo.x86_64                | 1         | 0.35%   |
| 5.8.11-1.el8.elrepo.x86_64               | 1         | 0.35%   |
| 5.4.61smp.24online                       | 1         | 0.35%   |
| 5.13.7-1.el8.elrepo.x86_64               | 1         | 0.35%   |
| 5.13.11-1.el8.elrepo.x86_64              | 1         | 0.35%   |
| 5.12.0-0.rc2.34.el8.x86_64+spr           | 1         | 0.35%   |
| 5.10.3-1.el8.elrepo.x86_64               | 1         | 0.35%   |
| 4.18.0-338.el8.x86_64                    | 1         | 0.35%   |
| 4.18.0-326.el8.x86_64                    | 1         | 0.35%   |
| 4.18.0-240.10.1.el8_3.centos.plus.x86_64 | 1         | 0.35%   |
| 4.18.0-193.14.2.el8_2.x86_64+debug       | 1         | 0.35%   |
| 4.18.0-168.el8.x86_64                    | 1         | 0.35%   |
| 4.18.0-151.el8.x86_64                    | 1         | 0.35%   |
| 4.18.0-144.el8.x86_64                    | 1         | 0.35%   |
| 3.10.0-1062.4.1.el7.x86_64               | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 244       | 96.06%  |
| 5.9.12  | 2         | 0.79%   |
| 5.9.1   | 1         | 0.39%   |
| 5.8.11  | 1         | 0.39%   |
| 5.4.61  | 1         | 0.39%   |
| 5.13.7  | 1         | 0.39%   |
| 5.13.11 | 1         | 0.39%   |
| 5.12.0  | 1         | 0.39%   |
| 5.10.3  | 1         | 0.39%   |
| 3.10.0  | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 244       | 96.06%  |
| 5.9     | 3         | 1.18%   |
| 5.13    | 2         | 0.79%   |
| 5.8     | 1         | 0.39%   |
| 5.4     | 1         | 0.39%   |
| 5.12    | 1         | 0.39%   |
| 5.10    | 1         | 0.39%   |
| 3.10    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 254       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 205       | 79.15%  |
| Unknown       | 31        | 11.97%  |
| GNOME Classic | 11        | 4.25%   |
| XFCE          | 6         | 2.32%   |
| KDE5          | 3         | 1.16%   |
| MATE          | 2         | 0.77%   |
| KDE           | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 142       | 53.18%  |
| X11     | 95        | 35.58%  |
| Unknown | 29        | 10.86%  |
| Web     | 1         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 162       | 62.31%  |
| GDM     | 95        | 36.54%  |
| LightDM | 2         | 0.77%   |
| SDDM    | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 142       | 54.41%  |
| Unknown     | 24        | 9.2%    |
| en_GB       | 21        | 8.05%   |
| de_DE       | 15        | 5.75%   |
| ru_RU       | 9         | 3.45%   |
| pt_BR       | 8         | 3.07%   |
| fr_FR       | 8         | 3.07%   |
| pl_PL       | 5         | 1.92%   |
| ko_KR       | 3         | 1.15%   |
| es_PE       | 3         | 1.15%   |
| en_CA       | 3         | 1.15%   |
| en_IN       | 2         | 0.77%   |
| en_AU       | 2         | 0.77%   |
| C           | 2         | 0.77%   |
| uk_UA       | 1         | 0.38%   |
| tr_TR       | 1         | 0.38%   |
| sl_SI       | 1         | 0.38%   |
| it_IT       | 1         | 0.38%   |
| hu_HU       | 1         | 0.38%   |
| fr_CA       | 1         | 0.38%   |
| fi_FI       | 1         | 0.38%   |
| es_MX       | 1         | 0.38%   |
| es_AR       | 1         | 0.38%   |
| en_US.utf-8 | 1         | 0.38%   |
| en_IE       | 1         | 0.38%   |
| de_LU       | 1         | 0.38%   |
| de_CH       | 1         | 0.38%   |
| da_DK       | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 144       | 56.03%  |
| BIOS | 113       | 43.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 229       | 90.16%  |
| Ext4 | 24        | 9.45%   |
| Ext3 | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 143       | 55%     |
| GPT     | 83        | 31.92%  |
| MBR     | 34        | 13.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 91.8%   |
| Yes       | 21        | 8.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 221       | 86.67%  |
| Yes       | 34        | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 39        | 15.35%  |
| ASUSTek Computer       | 37        | 14.57%  |
| Lenovo                 | 34        | 13.39%  |
| Dell                   | 33        | 12.99%  |
| Gigabyte Technology    | 29        | 11.42%  |
| MSI                    | 13        | 5.12%   |
| Intel                  | 12        | 4.72%   |
| Acer                   | 8         | 3.15%   |
| ASRock                 | 7         | 2.76%   |
| Supermicro             | 6         | 2.36%   |
| Samsung Electronics    | 4         | 1.57%   |
| Unknown                | 4         | 1.57%   |
| Sony                   | 3         | 1.18%   |
| Fujitsu                | 3         | 1.18%   |
| Foxconn                | 3         | 1.18%   |
| Apple                  | 3         | 1.18%   |
| ASRockRack             | 2         | 0.79%   |
| Toshiba                | 1         | 0.39%   |
| Timi                   | 1         | 0.39%   |
| RM Education           | 1         | 0.39%   |
| Packard Bell           | 1         | 0.39%   |
| Medion                 | 1         | 0.39%   |
| LG Electronics         | 1         | 0.39%   |
| HPE                    | 1         | 0.39%   |
| COPELION INTERNATIONAL | 1         | 0.39%   |
| CompuLab               | 1         | 0.39%   |
| Clevo                  | 1         | 0.39%   |
| Biostar                | 1         | 0.39%   |
| AZW                    | 1         | 0.39%   |
| AMI                    | 1         | 0.39%   |
| AIC                    | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 1.57%   |
| Supermicro SYS-7048A-T                            | 2         | 0.79%   |
| Lenovo Z50-70 20354                               | 2         | 0.79%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK             | 2         | 0.79%   |
| HP Notebook                                       | 2         | 0.79%   |
| HP Compaq 8200 Elite SFF PC                       | 2         | 0.79%   |
| Gigabyte X470 AORUS ULTRA GAMING                  | 2         | 0.79%   |
| Gigabyte A320M-S2H                                | 2         | 0.79%   |
| Dell Studio 1747                                  | 2         | 0.79%   |
| Dell OptiPlex 7010                                | 2         | 0.79%   |
| ASUS TUF B450M-PRO GAMING                         | 2         | 0.79%   |
| ASUS PRIME X570-P                                 | 2         | 0.79%   |
| ASUS All Series                                   | 2         | 0.79%   |
| Toshiba Satellite L15W-B                          | 1         | 0.39%   |
| Timi TM1709                                       | 1         | 0.39%   |
| Supermicro X9SCI/X9SCA                            | 1         | 0.39%   |
| Supermicro X8SIL                                  | 1         | 0.39%   |
| Supermicro X8SAX                                  | 1         | 0.39%   |
| Supermicro SYS-5019P-WTR                          | 1         | 0.39%   |
| Sony VPCEH26EN                                    | 1         | 0.39%   |
| Sony VPCEH15FX                                    | 1         | 0.39%   |
| Sony VPCEG15FB                                    | 1         | 0.39%   |
| Samsung R560                                      | 1         | 0.39%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B               | 1         | 0.39%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.39%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.39%   |
| RM Education RM                                   | 1         | 0.39%   |
| Packard Bell IMEDIA D3610 FR                      | 1         | 0.39%   |
| MSI MS-7C94                                       | 1         | 0.39%   |
| MSI MS-7C88                                       | 1         | 0.39%   |
| MSI MS-7C84                                       | 1         | 0.39%   |
| MSI MS-7C37                                       | 1         | 0.39%   |
| MSI MS-7C02                                       | 1         | 0.39%   |
| MSI MS-7A40                                       | 1         | 0.39%   |
| MSI MS-7A38                                       | 1         | 0.39%   |
| MSI MS-7A36                                       | 1         | 0.39%   |
| MSI MS-7918                                       | 1         | 0.39%   |
| MSI MS-7756                                       | 1         | 0.39%   |
| MSI MS-7636                                       | 1         | 0.39%   |
| MSI HPE-421f                                      | 1         | 0.39%   |
| MSI GE73VR 7RF                                    | 1         | 0.39%   |
| Medion P6622                                      | 1         | 0.39%   |
| LG Z435-GE40K                                     | 1         | 0.39%   |
| Lenovo V330-15IKB 81AX                            | 1         | 0.39%   |
| Lenovo ThinkPad X240 20AMS7XW00                   | 1         | 0.39%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00          | 1         | 0.39%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7CT01WW          | 1         | 0.39%   |
| Lenovo ThinkPad W540 20BHS20700                   | 1         | 0.39%   |
| Lenovo ThinkPad W540 20BG001KUK                   | 1         | 0.39%   |
| Lenovo ThinkPad T500 2242CTO                      | 1         | 0.39%   |
| Lenovo ThinkPad T490s 20NYS02900                  | 1         | 0.39%   |
| Lenovo ThinkPad T480s 20L8002WMX                  | 1         | 0.39%   |
| Lenovo ThinkPad T460p 20FXS02200                  | 1         | 0.39%   |
| Lenovo ThinkPad T440 20B7004JUS                   | 1         | 0.39%   |
| Lenovo ThinkPad T430s 2356CZ4                     | 1         | 0.39%   |
| Lenovo ThinkPad T420 4238AB9                      | 1         | 0.39%   |
| Lenovo ThinkPad P51 W10DG 20MNS08X00              | 1         | 0.39%   |
| Lenovo ThinkPad P50 20EN001PUS                    | 1         | 0.39%   |
| Lenovo ThinkPad E595 20NF0000GE                   | 1         | 0.39%   |
| Lenovo ThinkPad E590 20NBS03S00                   | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 19        | 7.48%   |
| HP EliteBook             | 9         | 3.54%   |
| Dell OptiPlex            | 8         | 3.15%   |
| Dell PowerEdge           | 7         | 2.76%   |
| ASUS PRIME               | 6         | 2.36%   |
| Lenovo IdeaPad           | 5         | 1.97%   |
| HP ProBook               | 5         | 1.97%   |
| Dell Latitude            | 5         | 1.97%   |
| ASUS TUF                 | 5         | 1.97%   |
| HP ZBook                 | 4         | 1.57%   |
| Dell Precision           | 4         | 1.57%   |
| Dell Inspiron            | 4         | 1.57%   |
| Acer Aspire              | 4         | 1.57%   |
| Unknown                  | 4         | 1.57%   |
| Lenovo ThinkCentre       | 3         | 1.18%   |
| HP Laptop                | 3         | 1.18%   |
| Dell XPS                 | 3         | 1.18%   |
| Supermicro SYS-7048A-T   | 2         | 0.79%   |
| Lenovo Z50-70            | 2         | 0.79%   |
| HP ProDesk               | 2         | 0.79%   |
| HP Notebook              | 2         | 0.79%   |
| HP EliteDesk             | 2         | 0.79%   |
| HP Compaq                | 2         | 0.79%   |
| Gigabyte X570            | 2         | 0.79%   |
| Gigabyte X470            | 2         | 0.79%   |
| Gigabyte A320M-S2H       | 2         | 0.79%   |
| Fujitsu CELSIUS          | 2         | 0.79%   |
| Dell Studio              | 2         | 0.79%   |
| ASUS ROG                 | 2         | 0.79%   |
| ASUS P8Z77-V             | 2         | 0.79%   |
| ASUS All                 | 2         | 0.79%   |
| Toshiba Satellite        | 1         | 0.39%   |
| Timi TM1709              | 1         | 0.39%   |
| Supermicro X9SCI         | 1         | 0.39%   |
| Supermicro X8SIL         | 1         | 0.39%   |
| Supermicro X8SAX         | 1         | 0.39%   |
| Supermicro SYS-5019P-WTR | 1         | 0.39%   |
| Sony VPCEH26EN           | 1         | 0.39%   |
| Sony VPCEH15FX           | 1         | 0.39%   |
| Sony VPCEG15FB           | 1         | 0.39%   |
| Samsung R560             | 1         | 0.39%   |
| Samsung 700Z3A           | 1         | 0.39%   |
| Samsung 500R4K           | 1         | 0.39%   |
| Samsung 270E5J           | 1         | 0.39%   |
| RM Education RM          | 1         | 0.39%   |
| Packard Bell IMEDIA      | 1         | 0.39%   |
| MSI MS-7C94              | 1         | 0.39%   |
| MSI MS-7C88              | 1         | 0.39%   |
| MSI MS-7C84              | 1         | 0.39%   |
| MSI MS-7C37              | 1         | 0.39%   |
| MSI MS-7C02              | 1         | 0.39%   |
| MSI MS-7A40              | 1         | 0.39%   |
| MSI MS-7A38              | 1         | 0.39%   |
| MSI MS-7A36              | 1         | 0.39%   |
| MSI MS-7918              | 1         | 0.39%   |
| MSI MS-7756              | 1         | 0.39%   |
| MSI MS-7636              | 1         | 0.39%   |
| MSI HPE-421f             | 1         | 0.39%   |
| MSI GE73VR               | 1         | 0.39%   |
| Medion P6622             | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 44        | 17.32%  |
| 2020 | 42        | 16.54%  |
| 2018 | 29        | 11.42%  |
| 2012 | 20        | 7.87%   |
| 2014 | 18        | 7.09%   |
| 2013 | 18        | 7.09%   |
| 2015 | 17        | 6.69%   |
| 2016 | 16        | 6.3%    |
| 2010 | 13        | 5.12%   |
| 2021 | 11        | 4.33%   |
| 2011 | 10        | 3.94%   |
| 2017 | 7         | 2.76%   |
| 2009 | 4         | 1.57%   |
| 2008 | 3         | 1.18%   |
| 2007 | 2         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 122       | 48.03%  |
| Notebook    | 101       | 39.76%  |
| Server      | 14        | 5.51%   |
| Mini pc     | 12        | 4.72%   |
| Convertible | 3         | 1.18%   |
| All in one  | 2         | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 238       | 93.7%   |
| Enabled  | 16        | 6.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 254       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 70        | 27.13%  |
| 16.01-24.0      | 52        | 20.16%  |
| 32.01-64.0      | 44        | 17.05%  |
| 3.01-4.0        | 34        | 13.18%  |
| 8.01-16.0       | 28        | 10.85%  |
| 64.01-256.0     | 19        | 7.36%   |
| 24.01-32.0      | 8         | 3.1%    |
| 1.01-2.0        | 2         | 0.78%   |
| More than 256.0 | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 87        | 30.74%  |
| 3.01-4.0    | 55        | 19.43%  |
| 4.01-8.0    | 53        | 18.73%  |
| 1.01-2.0    | 49        | 17.31%  |
| 8.01-16.0   | 21        | 7.42%   |
| 0.51-1.0    | 10        | 3.53%   |
| 16.01-24.0  | 3         | 1.06%   |
| 0.01-0.5    | 2         | 0.71%   |
| 32.01-64.0  | 1         | 0.35%   |
| 24.01-32.0  | 1         | 0.35%   |
| 64.01-256.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 134       | 52.55%  |
| 2      | 57        | 22.35%  |
| 3      | 28        | 10.98%  |
| 4      | 13        | 5.1%    |
| 6      | 6         | 2.35%   |
| 5      | 5         | 1.96%   |
| 7      | 3         | 1.18%   |
| 19     | 2         | 0.78%   |
| 8      | 2         | 0.78%   |
| 15     | 1         | 0.39%   |
| 13     | 1         | 0.39%   |
| 11     | 1         | 0.39%   |
| 10     | 1         | 0.39%   |
| 9      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 61.96%  |
| Yes       | 97        | 38.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 94.49%  |
| No        | 14        | 5.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 61.57%  |
| No        | 98        | 38.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 52.76%  |
| No        | 120       | 47.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 55        | 21.48%  |
| Germany      | 24        | 9.38%   |
| UK           | 13        | 5.08%   |
| Brazil       | 13        | 5.08%   |
| Russia       | 12        | 4.69%   |
| Sweden       | 9         | 3.52%   |
| India        | 9         | 3.52%   |
| France       | 9         | 3.52%   |
| Canada       | 9         | 3.52%   |
| Netherlands  | 6         | 2.34%   |
| China        | 6         | 2.34%   |
| Ukraine      | 5         | 1.95%   |
| Turkey       | 5         | 1.95%   |
| Poland       | 5         | 1.95%   |
| Mexico       | 5         | 1.95%   |
| Peru         | 4         | 1.56%   |
| Indonesia    | 4         | 1.56%   |
| Belgium      | 4         | 1.56%   |
| Spain        | 3         | 1.17%   |
| South Korea  | 3         | 1.17%   |
| South Africa | 3         | 1.17%   |
| Lithuania    | 3         | 1.17%   |
| Italy        | 3         | 1.17%   |
| Finland      | 3         | 1.17%   |
| Czechia      | 3         | 1.17%   |
| Switzerland  | 2         | 0.78%   |
| Serbia       | 2         | 0.78%   |
| Romania      | 2         | 0.78%   |
| Malaysia     | 2         | 0.78%   |
| Hong Kong    | 2         | 0.78%   |
| Belarus      | 2         | 0.78%   |
| Bangladesh   | 2         | 0.78%   |
| Austria      | 2         | 0.78%   |
| Australia    | 2         | 0.78%   |
| Vietnam      | 1         | 0.39%   |
| Thailand     | 1         | 0.39%   |
| Slovenia     | 1         | 0.39%   |
| Saudi Arabia | 1         | 0.39%   |
| Puerto Rico  | 1         | 0.39%   |
| Norway       | 1         | 0.39%   |
| Morocco      | 1         | 0.39%   |
| Luxembourg   | 1         | 0.39%   |
| Kenya        | 1         | 0.39%   |
| Israel       | 1         | 0.39%   |
| Ireland      | 1         | 0.39%   |
| Iran         | 1         | 0.39%   |
| Hungary      | 1         | 0.39%   |
| Greece       | 1         | 0.39%   |
| Egypt        | 1         | 0.39%   |
| Colombia     | 1         | 0.39%   |
| Burkina Faso | 1         | 0.39%   |
| Bulgaria     | 1         | 0.39%   |
| Argentina    | 1         | 0.39%   |
| Afghanistan  | 1         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Berlin               | 6         | 2.31%   |
| Sollentuna           | 4         | 1.54%   |
| S??o Paulo           | 4         | 1.54%   |
| Munich               | 4         | 1.54%   |
| Lima                 | 4         | 1.54%   |
| Istanbul             | 4         | 1.54%   |
| Chicago              | 4         | 1.54%   |
| Toronto              | 3         | 1.15%   |
| Portland             | 3         | 1.15%   |
| Moscow               | 3         | 1.15%   |
| Yangquan             | 2         | 0.77%   |
| Sydney               | 2         | 0.77%   |
| Prague               | 2         | 0.77%   |
| Phoenix              | 2         | 0.77%   |
| New York             | 2         | 0.77%   |
| Mexico City          | 2         | 0.77%   |
| Marylebone           | 2         | 0.77%   |
| Kyiv                 | 2         | 0.77%   |
| Khmelnytskyy         | 2         | 0.77%   |
| Helsinki             | 2         | 0.77%   |
| Hamburg              | 2         | 0.77%   |
| Gdansk               | 2         | 0.77%   |
| Dhaka                | 2         | 0.77%   |
| Denver               | 2         | 0.77%   |
| City of Saint Peters | 2         | 0.77%   |
| Central              | 2         | 0.77%   |
| Bogor                | 2         | 0.77%   |
| ? iauliai            | 2         | 0.77%   |
| Atlanta              | 2         | 0.77%   |
| Alexandria           | 2         | 0.77%   |
| Zaporizhzhia         | 1         | 0.38%   |
| Zapopan              | 1         | 0.38%   |
| Yekaterinburg        | 1         | 0.38%   |
| Yangpu               | 1         | 0.38%   |
| Wodzis?‚aw ??l?…ski  | 1         | 0.38%   |
| Whitley Bay          | 1         | 0.38%   |
| West Bromwich        | 1         | 0.38%   |
| Weilheim             | 1         | 0.38%   |
| Wayne                | 1         | 0.38%   |
| Warsaw               | 1         | 0.38%   |
| Vladivostok          | 1         | 0.38%   |
| Vitebsk              | 1         | 0.38%   |
| Vireux-Molhain       | 1         | 0.38%   |
| Vilnius              | 1         | 0.38%   |
| Viladecans           | 1         | 0.38%   |
| Vaugneray            | 1         | 0.38%   |
| Vancouver            | 1         | 0.38%   |
| Valatie              | 1         | 0.38%   |
| Val-des-Monts        | 1         | 0.38%   |
| Utrecht              | 1         | 0.38%   |
| Upplands Vasby       | 1         | 0.38%   |
| Umbauba              | 1         | 0.38%   |
| Turnhout             | 1         | 0.38%   |
| Tremembe             | 1         | 0.38%   |
| Tolosa               | 1         | 0.38%   |
| Tlalnepantla         | 1         | 0.38%   |
| Tirupati             | 1         | 0.38%   |
| Thane                | 1         | 0.38%   |
| Tel Aviv             | 1         | 0.38%   |
| Tehran               | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 68        | 175    | 16.71%  |
| Seagate                   | 67        | 114    | 16.46%  |
| Samsung Electronics       | 66        | 106    | 16.22%  |
| Kingston                  | 30        | 34     | 7.37%   |
| Toshiba                   | 23        | 33     | 5.65%   |
| SanDisk                   | 16        | 19     | 3.93%   |
| Unknown                   | 13        | 27     | 3.19%   |
| Hitachi                   | 11        | 24     | 2.7%    |
| HGST                      | 11        | 30     | 2.7%    |
| Crucial                   | 11        | 13     | 2.7%    |
| Intel                     | 9         | 10     | 2.21%   |
| A-DATA Technology         | 7         | 9      | 1.72%   |
| SK Hynix                  | 6         | 6      | 1.47%   |
| Micron Technology         | 5         | 6      | 1.23%   |
| SPCC                      | 4         | 4      | 0.98%   |
| Silicon Motion            | 4         | 4      | 0.98%   |
| PLEXTOR                   | 3         | 3      | 0.74%   |
| Phison                    | 3         | 3      | 0.74%   |
| Lenovo                    | 3         | 4      | 0.74%   |
| Apple                     | 3         | 3      | 0.74%   |
| XPG                       | 2         | 2      | 0.49%   |
| Union Memory              | 2         | 2      | 0.49%   |
| PNY                       | 2         | 2      | 0.49%   |
| Patriot                   | 2         | 6      | 0.49%   |
| OCZ                       | 2         | 3      | 0.49%   |
| Micron/Crucial Technology | 2         | 3      | 0.49%   |
| LITEON                    | 2         | 3      | 0.49%   |
| Lexar                     | 2         | 2      | 0.49%   |
| Gigabyte Technology       | 2         | 2      | 0.49%   |
| China                     | 2         | 5      | 0.49%   |
| Apacer                    | 2         | 2      | 0.49%   |
| ZEPLIN                    | 1         | 1      | 0.25%   |
| XrayDisk                  | 1         | 1      | 0.25%   |
| Verbatim                  | 1         | 1      | 0.25%   |
| V-GeN                     | 1         | 1      | 0.25%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.25%   |
| Transcend                 | 1         | 2      | 0.25%   |
| Team                      | 1         | 1      | 0.25%   |
| SSD                       | 1         | 1      | 0.25%   |
| SATADOM-SL                | 1         | 1      | 0.25%   |
| ROG                       | 1         | 1      | 0.25%   |
| Realtek Semiconductor     | 1         | 1      | 0.25%   |
| LITEONIT                  | 1         | 1      | 0.25%   |
| Linux                     | 1         | 1      | 0.25%   |
| KIOXIA-EXCERIA            | 1         | 2      | 0.25%   |
| KIOXIA                    | 1         | 1      | 0.25%   |
| KINGBANK                  | 1         | 1      | 0.25%   |
| Hewlett-Packard           | 1         | 1      | 0.25%   |
| G-DRIVE                   | 1         | 1      | 0.25%   |
| Dell                      | 1         | 1      | 0.25%   |
| Biostar                   | 1         | 1      | 0.25%   |
| ASMT                      | 1         | 1      | 0.25%   |
| 980Plus                   | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD      | 6         | 1.28%   |
| WDC WD20EARX-00PASB0 2TB             | 5         | 1.06%   |
| Toshiba DT01ACA100 1TB               | 5         | 1.06%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 1.06%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 1.06%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.85%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.85%   |
| Seagate ST500DM002-1BD142 500GB      | 4         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.85%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.64%   |
| WDC WD20EZRZ-00Z5HB0  2TB            | 3         | 0.64%   |
| Unknown MMC Card  32GB               | 3         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.64%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 0.64%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.64%   |
| Samsung SSD 860 EVO 1TB              | 3         | 0.64%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.64%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.64%   |
| Kingston SA400M8240G 240GB SSD       | 3         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 2         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2         | 0.43%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 2         | 0.43%   |
| WDC WD2002FAEX-007BA0 2TB            | 2         | 0.43%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.43%   |
| WDC WD1003FBYX-01Y7B0 1TB            | 2         | 0.43%   |
| Unknown HUH728080ALE601 8TB          | 2         | 0.43%   |
| Toshiba HDWL120 2TB                  | 2         | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.43%   |
| Seagate ST31000528AS 1TB             | 2         | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB       | 2         | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.43%   |
| Seagate Expansion Desk 2TB           | 2         | 0.43%   |
| Sandisk NVMe SSD Drive 1TB           | 2         | 0.43%   |
| Samsung SSD 970 PRO 512GB            | 2         | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.43%   |
| Samsung SSD 850 EVO M.2 500GB        | 2         | 0.43%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.43%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.43%   |
| Samsung SSD 840 PRO Series 256GB     | 2         | 0.43%   |
| Samsung SSD 840 EVO 120GB            | 2         | 0.43%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 0.43%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.43%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.43%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 2         | 0.43%   |
| Samsung MZ7LN256HMJP-000H1 256GB SSD | 2         | 0.43%   |
| Samsung HD103SI 1TB                  | 2         | 0.43%   |
| Phison NVMe SSD Drive 1TB            | 2         | 0.43%   |
| Patriot P200 256GB SSD               | 2         | 0.43%   |
| Lenovo SSD SL700 120G                | 2         | 0.43%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.43%   |
| Intel SSDSC2KW256G8 256GB            | 2         | 0.43%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 107    | 35.59%  |
| WDC                 | 61        | 160    | 34.46%  |
| Toshiba             | 19        | 29     | 10.73%  |
| Hitachi             | 11        | 24     | 6.21%   |
| HGST                | 11        | 30     | 6.21%   |
| Samsung Electronics | 6         | 6      | 3.39%   |
| Unknown             | 2         | 10     | 1.13%   |
| Apple               | 2         | 2      | 1.13%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Dell                | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 63     | 24.68%  |
| Kingston            | 30        | 34     | 19.48%  |
| Crucial             | 10        | 12     | 6.49%   |
| WDC                 | 9         | 12     | 5.84%   |
| SanDisk             | 9         | 11     | 5.84%   |
| Intel               | 8         | 9      | 5.19%   |
| A-DATA Technology   | 5         | 5      | 3.25%   |
| SPCC                | 4         | 4      | 2.6%    |
| SK Hynix            | 4         | 4      | 2.6%    |
| Toshiba             | 3         | 3      | 1.95%   |
| Micron Technology   | 3         | 3      | 1.95%   |
| PNY                 | 2         | 2      | 1.3%    |
| PLEXTOR             | 2         | 2      | 1.3%    |
| Patriot             | 2         | 6      | 1.3%    |
| OCZ                 | 2         | 3      | 1.3%    |
| LITEON              | 2         | 3      | 1.3%    |
| Lenovo              | 2         | 3      | 1.3%    |
| China               | 2         | 5      | 1.3%    |
| Apacer              | 2         | 2      | 1.3%    |
| XrayDisk            | 1         | 1      | 0.65%   |
| Verbatim            | 1         | 1      | 0.65%   |
| V-GeN               | 1         | 1      | 0.65%   |
| Transcend           | 1         | 2      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| SSD                 | 1         | 1      | 0.65%   |
| Seagate             | 1         | 1      | 0.65%   |
| SATADOM-SL          | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Linux               | 1         | 1      | 0.65%   |
| Lexar               | 1         | 1      | 0.65%   |
| KINGBANK            | 1         | 1      | 0.65%   |
| Biostar             | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 142       | 370    | 39.78%  |
| SSD     | 132       | 202    | 36.97%  |
| NVMe    | 66        | 87     | 18.49%  |
| Unknown | 9         | 11     | 2.52%   |
| MMC     | 8         | 13     | 2.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 223       | 567    | 72.4%   |
| NVMe | 66        | 87     | 21.43%  |
| SAS  | 11        | 16     | 3.57%   |
| MMC  | 8         | 13     | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 152       | 259    | 51.18%  |
| 0.51-1.0   | 80        | 122    | 26.94%  |
| 1.01-2.0   | 39        | 91     | 13.13%  |
| 4.01-10.0  | 9         | 30     | 3.03%   |
| 3.01-4.0   | 8         | 26     | 2.69%   |
| 2.01-3.0   | 6         | 24     | 2.02%   |
| 10.01-20.0 | 3         | 20     | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 22.31%  |
| 251-500        | 57        | 21.92%  |
| 501-1000       | 57        | 21.92%  |
| 1001-2000      | 27        | 10.38%  |
| More than 3000 | 19        | 7.31%   |
| 51-100         | 12        | 4.62%   |
| Unknown        | 10        | 3.85%   |
| 2001-3000      | 8         | 3.08%   |
| 21-50          | 7         | 2.69%   |
| 1-20           | 5         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 91        | 33.09%  |
| 21-50          | 58        | 21.09%  |
| 101-250        | 35        | 12.73%  |
| 51-100         | 31        | 11.27%  |
| 251-500        | 15        | 5.45%   |
| 501-1000       | 13        | 4.73%   |
| More than 3000 | 12        | 4.36%   |
| 1001-2000      | 10        | 3.64%   |
| Unknown        | 10        | 3.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                | 2         | 3      | 8.33%   |
| WDC WD6400AADS-00M2B0 640GB           | 1         | 1      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 4.17%   |
| WDC WD5000AACS-00G8B0 500GB           | 1         | 1      | 4.17%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1         | 1      | 4.17%   |
| WDC WD20EZRZ-00Z5HB0  2TB             | 1         | 1      | 4.17%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 4      | 4.17%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1         | 1      | 4.17%   |
| WDC WD1002FBYS-18A6B0 1TB             | 1         | 1      | 4.17%   |
| SK Hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 4.17%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 4.17%   |
| Seagate ST3400820AS 400GB             | 1         | 1      | 4.17%   |
| Seagate ST3000VM002-1ET166 3TB        | 1         | 1      | 4.17%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 4.17%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 4.17%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 840 EVO 250GB | 1         | 1      | 4.17%   |
| LITEON CV8-8E128-HP 128GB SSD         | 1         | 1      | 4.17%   |
| Intel SSDSA2M040G2GC 40GB             | 1         | 1      | 4.17%   |
| Hitachi HTS545032B9A302 320GB         | 1         | 1      | 4.17%   |
| HGST HDS724040ALE640 4TB              | 1         | 2      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 36.36%  |
| WDC                 | 6         | 11     | 27.27%  |
| Toshiba             | 2         | 3      | 9.09%   |
| SK Hynix            | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| LITEON              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |
| HGST                | 1         | 2      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 44.44%  |
| WDC     | 6         | 11     | 33.33%  |
| Toshiba | 2         | 3      | 11.11%  |
| Hitachi | 1         | 1      | 5.56%   |
| HGST    | 1         | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 25     | 81.82%  |
| SSD  | 4         | 4      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB | 1         | 1      | 50%     |
| Toshiba DT01ACA100 1TB       | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Toshiba | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 154       | 360    | 55%     |
| Works    | 103       | 291    | 36.79%  |
| Malfunc  | 21        | 29     | 7.5%    |
| Failed   | 2         | 3      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 197       | 55.34%  |
| AMD                           | 48        | 13.48%  |
| Samsung Electronics           | 30        | 8.43%   |
| ASMedia Technology            | 11        | 3.09%   |
| Marvell Technology Group      | 9         | 2.53%   |
| Sandisk                       | 7         | 1.97%   |
| LSI Logic / Symbios Logic     | 7         | 1.97%   |
| Broadcom / LSI                | 7         | 1.97%   |
| Silicon Motion                | 5         | 1.4%    |
| Phison Electronics            | 5         | 1.4%    |
| JMicron Technology            | 5         | 1.4%    |
| ADATA Technology              | 4         | 1.12%   |
| Union Memory (Shenzhen)       | 3         | 0.84%   |
| Micron/Crucial Technology     | 3         | 0.84%   |
| SK Hynix                      | 2         | 0.56%   |
| Micron Technology             | 2         | 0.56%   |
| KIOXIA                        | 2         | 0.56%   |
| Toshiba America Info Systems  | 1         | 0.28%   |
| Shenzhen Longsys Electronics  | 1         | 0.28%   |
| Seagate Technology            | 1         | 0.28%   |
| Realtek Semiconductor         | 1         | 0.28%   |
| Nvidia                        | 1         | 0.28%   |
| Lite-On Technology            | 1         | 0.28%   |
| Lenovo                        | 1         | 0.28%   |
| Integrated Technology Express | 1         | 0.28%   |
| Adaptec                       | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 36        | 8.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 4.61%   |
| Intel SATA Controller [RAID mode]                                                | 16        | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 3.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 2.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 2.67%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 10        | 2.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 2.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.46%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 6         | 1.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 6         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 1.46%   |
| AMD FCH SATA Controller D                                                        | 6         | 1.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 5         | 1.21%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 5         | 1.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.21%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.97%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.73%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.73%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.73%   |
| Samsung NVMe Controller                                                          | 3         | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 3         | 0.73%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3         | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.73%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 3         | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.73%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2         | 0.49%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.49%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2         | 0.49%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2         | 0.49%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.49%   |
| JMicron JMB368 IDE controller                                                    | 2         | 0.49%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.49%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 0.49%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2         | 0.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.49%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 0.49%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 2         | 0.49%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 200       | 59.17%  |
| NVMe | 65        | 19.23%  |
| RAID | 39        | 11.54%  |
| IDE  | 27        | 7.99%   |
| SAS  | 6         | 1.78%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 207       | 81.5%   |
| AMD    | 47        | 18.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 1.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.57%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 1.18%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.18%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 3         | 1.18%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 3         | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 1.18%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 0.78%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.78%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2         | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.78%   |
| Intel Core i7 CPU 950 @ 3.07GHz               | 2         | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-3470S CPU @ 2.90GHz             | 2         | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 2         | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.78%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.78%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 0.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.78%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.78%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.78%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz          | 1         | 0.39%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 1         | 0.39%   |
| Intel Xeon Platinum 8171M CPU @ 2.60GHz       | 1         | 0.39%   |
| Intel Xeon E-2224G CPU @ 3.50GHz              | 1         | 0.39%   |
| Intel Xeon E-2186M CPU @ 2.90GHz              | 1         | 0.39%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 1         | 0.39%   |
| Intel Xeon CPU X5670 @ 2.93GHz                | 1         | 0.39%   |
| Intel Xeon CPU X5450 @ 3.00GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5645 @ 2.40GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5606 @ 2.13GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5430 @ 2.66GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.39%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1         | 0.39%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1         | 0.39%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 1         | 0.39%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz            | 1         | 0.39%   |
| Intel Xeon CPU E31270 @ 3.40GHz               | 1         | 0.39%   |
| Intel Xeon CPU E31260L @ 2.40GHz              | 1         | 0.39%   |
| Intel Xeon CPU E31240 @ 3.30GHz               | 1         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 64        | 25.1%   |
| Intel Core i5           | 64        | 25.1%   |
| Intel Xeon              | 25        | 9.8%    |
| Intel Core i3           | 19        | 7.45%   |
| AMD Ryzen 5             | 12        | 4.71%   |
| AMD Ryzen 7             | 10        | 3.92%   |
| Intel Pentium           | 7         | 2.75%   |
| Intel Core 2 Quad       | 6         | 2.35%   |
| AMD Ryzen 9             | 6         | 2.35%   |
| Intel Celeron           | 5         | 1.96%   |
| AMD Ryzen 3             | 5         | 1.96%   |
| AMD FX                  | 5         | 1.96%   |
| Intel Core 2 Duo        | 3         | 1.18%   |
| AMD Ryzen 7 PRO         | 3         | 1.18%   |
| Other                   | 2         | 0.78%   |
| Intel Xeon Silver       | 2         | 0.78%   |
| Intel Genuine           | 2         | 0.78%   |
| Intel Core i9           | 2         | 0.78%   |
| Intel Atom              | 2         | 0.78%   |
| AMD Ryzen Threadripper  | 2         | 0.78%   |
| Intel Xeon Platinum     | 1         | 0.39%   |
| Intel Pentium Gold      | 1         | 0.39%   |
| Intel Pentium Dual-Core | 1         | 0.39%   |
| Intel Pentium Dual      | 1         | 0.39%   |
| AMD Turion II Neo       | 1         | 0.39%   |
| AMD Phenom II X4        | 1         | 0.39%   |
| AMD Opteron             | 1         | 0.39%   |
| AMD G                   | 1         | 0.39%   |
| AMD A4                  | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 110       | 43.14%  |
| 2      | 78        | 30.59%  |
| 6      | 25        | 9.8%    |
| 8      | 17        | 6.67%   |
| 12     | 11        | 4.31%   |
| 16     | 7         | 2.75%   |
| 1      | 2         | 0.78%   |
| 96     | 1         | 0.39%   |
| 52     | 1         | 0.39%   |
| 20     | 1         | 0.39%   |
| 10     | 1         | 0.39%   |
| 3      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 240       | 94.49%  |
| 2      | 14        | 5.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 183       | 71.48%  |
| 1      | 73        | 28.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 249       | 97.65%  |
| Unknown        | 6         | 2.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 24        | 9.3%    |
| 0x306c3    | 19        | 7.36%   |
| 0x206a7    | 17        | 6.59%   |
| 0x506e3    | 11        | 4.26%   |
| 0x40651    | 11        | 4.26%   |
| 0x806ea    | 10        | 3.88%   |
| Unknown    | 10        | 3.88%   |
| 0x906ea    | 9         | 3.49%   |
| 0x306d4    | 9         | 3.49%   |
| 0x08701021 | 9         | 3.49%   |
| 0x406e3    | 7         | 2.71%   |
| 0x906e9    | 6         | 2.33%   |
| 0x806ec    | 6         | 2.33%   |
| 0x106e5    | 6         | 2.33%   |
| 0x1067a    | 6         | 2.33%   |
| 0x0800820d | 6         | 2.33%   |
| 0x806e9    | 5         | 1.94%   |
| 0x306f2    | 5         | 1.94%   |
| 0x20655    | 5         | 1.94%   |
| 0x08701013 | 5         | 1.94%   |
| 0x06000852 | 5         | 1.94%   |
| 0x10676    | 4         | 1.55%   |
| 0xa0655    | 3         | 1.16%   |
| 0x906ed    | 3         | 1.16%   |
| 0x206d7    | 3         | 1.16%   |
| 0x206c2    | 3         | 1.16%   |
| 0x08101016 | 3         | 1.16%   |
| 0xa0652    | 2         | 0.78%   |
| 0x806c1    | 2         | 0.78%   |
| 0x706e5    | 2         | 0.78%   |
| 0x6fb      | 2         | 0.78%   |
| 0x50654    | 2         | 0.78%   |
| 0x406f1    | 2         | 0.78%   |
| 0x406c4    | 2         | 0.78%   |
| 0x30678    | 2         | 0.78%   |
| 0x20652    | 2         | 0.78%   |
| 0x106a5    | 2         | 0.78%   |
| 0x0810100b | 2         | 0.78%   |
| 0x08001137 | 2         | 0.78%   |
| 0xa0660    | 1         | 0.39%   |
| 0x906eb    | 1         | 0.39%   |
| 0x806f3    | 1         | 0.39%   |
| 0x6fd      | 1         | 0.39%   |
| 0x506c9    | 1         | 0.39%   |
| 0x50657    | 1         | 0.39%   |
| 0x406c3    | 1         | 0.39%   |
| 0x306e4    | 1         | 0.39%   |
| 0x106c2    | 1         | 0.39%   |
| 0x10677    | 1         | 0.39%   |
| 0x0a201009 | 1         | 0.39%   |
| 0x08701011 | 1         | 0.39%   |
| 0x08600106 | 1         | 0.39%   |
| 0x08600104 | 1         | 0.39%   |
| 0x08600103 | 1         | 0.39%   |
| 0x08108109 | 1         | 0.39%   |
| 0x08108102 | 1         | 0.39%   |
| 0x08001138 | 1         | 0.39%   |
| 0x08001129 | 1         | 0.39%   |
| 0x06006705 | 1         | 0.39%   |
| 0x0600611a | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 41        | 16.08%  |
| Haswell         | 35        | 13.73%  |
| IvyBridge       | 25        | 9.8%    |
| Skylake         | 22        | 8.63%   |
| SandyBridge     | 21        | 8.24%   |
| Zen 2           | 18        | 7.06%   |
| Westmere        | 12        | 4.71%   |
| Penryn          | 11        | 4.31%   |
| Broadwell       | 11        | 4.31%   |
| Zen             | 10        | 3.92%   |
| Zen+            | 9         | 3.53%   |
| Nehalem         | 8         | 3.14%   |
| CometLake       | 6         | 2.35%   |
| Silvermont      | 5         | 1.96%   |
| Piledriver      | 5         | 1.96%   |
| Core            | 3         | 1.18%   |
| TigerLake       | 2         | 0.78%   |
| K10             | 2         | 0.78%   |
| IceLake         | 2         | 0.78%   |
| Excavator       | 2         | 0.78%   |
| Zen 3           | 1         | 0.39%   |
| Sapphire Rapids | 1         | 0.39%   |
| Goldmont        | 1         | 0.39%   |
| Bonnell         | 1         | 0.39%   |
| Bobcat          | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 144       | 48.16%  |
| Nvidia                     | 88        | 29.43%  |
| AMD                        | 55        | 18.39%  |
| Matrox Electronics Systems | 6         | 2.01%   |
| ASPEED Technology          | 4         | 1.34%   |
| S3 Graphics                | 2         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 3.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 3.34%   |
| Intel UHD Graphics 620                                                                   | 10        | 3.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.34%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.34%   |
| Intel HD Graphics 530                                                                    | 7         | 2.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.34%   |
| Intel HD Graphics 630                                                                    | 4         | 1.34%   |
| Intel HD Graphics 620                                                                    | 4         | 1.34%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.34%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1%      |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1%      |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1%      |
| AMD Renoir                                                                               | 3         | 1%      |
| AMD Picasso                                                                              | 3         | 1%      |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2         | 0.67%   |
| Nvidia GT218 [GeForce G210]                                                              | 2         | 0.67%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 2         | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.67%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.67%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.67%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.67%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.67%   |
| Intel HD Graphics P530                                                                   | 2         | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.67%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 2         | 0.67%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.67%   |
| S3 Graphics Savage 4                                                                     | 1         | 0.33%   |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                                       | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.33%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.33%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1         | 0.33%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 102       | 39.84%  |
| 1 x Nvidia      | 59        | 23.05%  |
| 1 x AMD         | 44        | 17.19%  |
| Intel + Nvidia  | 28        | 10.94%  |
| Intel + AMD     | 10        | 3.91%   |
| 1 x Matrox      | 6         | 2.34%   |
| 1 x ASPEED      | 4         | 1.56%   |
| 1 x S3 Graphics | 2         | 0.78%   |
| 2 x AMD         | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 216       | 84.71%  |
| Proprietary | 26        | 10.2%   |
| Unknown     | 13        | 5.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 50.77%  |
| 1.01-2.0   | 41        | 15.77%  |
| 0.51-1.0   | 22        | 8.46%   |
| 0.01-0.5   | 22        | 8.46%   |
| 3.01-4.0   | 21        | 8.08%   |
| 7.01-8.0   | 14        | 5.38%   |
| 8.01-16.0  | 3         | 1.15%   |
| 5.01-6.0   | 2         | 0.77%   |
| 2.01-3.0   | 2         | 0.77%   |
| 4.01-5.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 12.96%  |
| Dell                    | 27        | 10%     |
| AU Optronics            | 25        | 9.26%   |
| Goldstar                | 20        | 7.41%   |
| Chimei Innolux          | 20        | 7.41%   |
| Hewlett-Packard         | 19        | 7.04%   |
| LG Display              | 18        | 6.67%   |
| BOE                     | 16        | 5.93%   |
| Acer                    | 12        | 4.44%   |
| BenQ                    | 6         | 2.22%   |
| ViewSonic               | 5         | 1.85%   |
| Lenovo                  | 5         | 1.85%   |
| Ancor Communications    | 5         | 1.85%   |
| Philips                 | 4         | 1.48%   |
| LG Electronics          | 4         | 1.48%   |
| Iiyama                  | 4         | 1.48%   |
| Eizo                    | 4         | 1.48%   |
| Sony                    | 3         | 1.11%   |
| Sharp                   | 3         | 1.11%   |
| Apple                   | 3         | 1.11%   |
| AOC                     | 3         | 1.11%   |
| Xiaomi                  | 2         | 0.74%   |
| Unknown                 | 2         | 0.74%   |
| PANDA                   | 2         | 0.74%   |
| Panasonic               | 2         | 0.74%   |
| Elo Touch               | 2         | 0.74%   |
| Xerox                   | 1         | 0.37%   |
| Westinghouse            | 1         | 0.37%   |
| VOXICON                 | 1         | 0.37%   |
| Vizio                   | 1         | 0.37%   |
| Sceptre Tech            | 1         | 0.37%   |
| RTK                     | 1         | 0.37%   |
| Onkyo                   | 1         | 0.37%   |
| NXP                     | 1         | 0.37%   |
| NEX                     | 1         | 0.37%   |
| NEC Computers           | 1         | 0.37%   |
| MStar                   | 1         | 0.37%   |
| MSI                     | 1         | 0.37%   |
| InfoVision              | 1         | 0.37%   |
| HannStar Display        | 1         | 0.37%   |
| HannStar                | 1         | 0.37%   |
| Gateway                 | 1         | 0.37%   |
| Element                 | 1         | 0.37%   |
| Chi Mei Optoelectronics | 1         | 0.37%   |
| AUS                     | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 3         | 1.04%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 3         | 1.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 3         | 1.04%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 2         | 0.69%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch  | 2         | 0.69%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 2         | 0.69%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.69%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 0.69%   |
| Hewlett-Packard ZR2440w HWP2955 1920x1080 520x320mm 24.0-inch         | 2         | 0.69%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 520x330mm 24.2-inch          | 2         | 0.69%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 2         | 0.69%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.69%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 2         | 0.69%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.69%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.69%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                   | 1         | 0.35%   |
| Westinghouse SK-26H520S WDE139C 1366x768 575x323mm 26.0-inch          | 1         | 0.35%   |
| VOXICON D32QO DUS3200 2560x1440 708x398mm 32.0-inch                   | 1         | 0.35%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                    | 1         | 0.35%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch             | 1         | 0.35%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1         | 0.35%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch         | 1         | 0.35%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch         | 1         | 0.35%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch            | 1         | 0.35%   |
| Unknown LCD Monitor XXX AAA 1366x768                                  | 1         | 0.35%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                             | 1         | 0.35%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.35%   |
| Sony TV *00 SNY7C04 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.35%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.35%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch         | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0564 1024x768 410x230mm 18.5-inch   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1         | 0.35%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch    | 1         | 0.35%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 530x300mm 24.0-inch    | 1         | 0.35%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch    | 1         | 0.35%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 0.35%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch     | 1         | 0.35%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.35%   |
| Samsung Electronics S24B300 SAM08CB 1920x1080 521x293mm 23.5-inch     | 1         | 0.35%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 480x270mm 21.7-inch     | 1         | 0.35%   |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor T22C300 1920x1080                     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x170mm 13.9-inch  | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 331x207mm 15.4-inch | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch  | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3147 1600x900 332x187mm 15.0-inch  | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 115       | 43.73%  |
| 1366x768 (WXGA)    | 37        | 14.07%  |
| 3840x2160 (4K)     | 22        | 8.37%   |
| 1920x1200 (WUXGA)  | 13        | 4.94%   |
| 1680x1050 (WSXGA+) | 12        | 4.56%   |
| 1600x900 (HD+)     | 11        | 4.18%   |
| 1280x1024 (SXGA)   | 10        | 3.8%    |
| 2560x1440 (QHD)    | 8         | 3.04%   |
| Unknown            | 8         | 3.04%   |
| 2560x1080          | 4         | 1.52%   |
| 2560x1600          | 3         | 1.14%   |
| 3840x1080          | 2         | 0.76%   |
| 3440x1440          | 2         | 0.76%   |
| 2880x1800          | 2         | 0.76%   |
| 1440x900 (WXGA+)   | 2         | 0.76%   |
| 1280x800 (WXGA)    | 2         | 0.76%   |
| 1024x768 (XGA)     | 2         | 0.76%   |
| 7280x2160          | 1         | 0.38%   |
| 5520x2160          | 1         | 0.38%   |
| 3840x1200          | 1         | 0.38%   |
| 3640x1920          | 1         | 0.38%   |
| 1600x1200          | 1         | 0.38%   |
| 1400x1050          | 1         | 0.38%   |
| 1360x768           | 1         | 0.38%   |
| 1280x960           | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 20.96%  |
| 27      | 29        | 10.66%  |
| 24      | 25        | 9.19%   |
| 23      | 23        | 8.46%   |
| 21      | 22        | 8.09%   |
| Unknown | 18        | 6.62%   |
| 13      | 17        | 6.25%   |
| 17      | 15        | 5.51%   |
| 14      | 12        | 4.41%   |
| 34      | 6         | 2.21%   |
| 22      | 6         | 2.21%   |
| 20      | 6         | 2.21%   |
| 31      | 5         | 1.84%   |
| 19      | 5         | 1.84%   |
| 32      | 4         | 1.47%   |
| 12      | 4         | 1.47%   |
| 18      | 3         | 1.1%    |
| 65      | 2         | 0.74%   |
| 40      | 2         | 0.74%   |
| 29      | 2         | 0.74%   |
| 25      | 2         | 0.74%   |
| 11      | 2         | 0.74%   |
| 84      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 52      | 1         | 0.37%   |
| 42      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 32.32%  |
| 501-600     | 72        | 27.38%  |
| 401-500     | 37        | 14.07%  |
| Unknown     | 18        | 6.84%   |
| 351-400     | 13        | 4.94%   |
| 701-800     | 10        | 3.8%    |
| 601-700     | 10        | 3.8%    |
| 201-300     | 10        | 3.8%    |
| 1001-1500   | 4         | 1.52%   |
| 801-900     | 2         | 0.76%   |
| 1501-2000   | 1         | 0.38%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 72.95%  |
| 16/10   | 28        | 11.48%  |
| Unknown | 16        | 6.56%   |
| 5/4     | 10        | 4.1%    |
| 21/9    | 6         | 2.46%   |
| 4/3     | 4         | 1.64%   |
| 3/2     | 2         | 0.82%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 56        | 20.82%  |
| 101-110        | 56        | 20.82%  |
| 301-350        | 29        | 10.78%  |
| 81-90          | 26        | 9.67%   |
| 151-200        | 18        | 6.69%   |
| Unknown        | 18        | 6.69%   |
| 351-500        | 17        | 6.32%   |
| 251-300        | 14        | 5.2%    |
| 141-150        | 9         | 3.35%   |
| 121-130        | 7         | 2.6%    |
| More than 1000 | 5         | 1.86%   |
| 61-70          | 4         | 1.49%   |
| 71-80          | 3         | 1.12%   |
| 501-1000       | 3         | 1.12%   |
| 51-60          | 2         | 0.74%   |
| 131-140        | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 104       | 40.15%  |
| 121-160       | 64        | 24.71%  |
| 101-120       | 57        | 22.01%  |
| Unknown       | 18        | 6.95%   |
| 161-240       | 11        | 4.25%   |
| More than 240 | 3         | 1.16%   |
| 1-50          | 2         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 180       | 69.5%   |
| 2     | 45        | 17.37%  |
| 0     | 28        | 10.81%  |
| 3     | 4         | 1.54%   |
| 6     | 1         | 0.39%   |
| 4     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 149       | 40.49%  |
| Realtek Semiconductor             | 130       | 35.33%  |
| Qualcomm Atheros                  | 33        | 8.97%   |
| Broadcom                          | 21        | 5.71%   |
| Ralink Technology                 | 7         | 1.9%    |
| Mellanox Technologies             | 4         | 1.09%   |
| Broadcom Limited                  | 4         | 1.09%   |
| Ralink                            | 3         | 0.82%   |
| ASIX Electronics                  | 3         | 0.82%   |
| D-Link System                     | 2         | 0.54%   |
| Aquantia                          | 2         | 0.54%   |
| Xiaomi                            | 1         | 0.27%   |
| TP-Link                           | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.27%   |
| Marvell Technology Group          | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 103       | 22.84%  |
| Intel I211 Gigabit Network Connection                             | 15        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.88%   |
| Intel Wireless 7260                                               | 12        | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.66%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2%      |
| Intel 82574L Gigabit Network Connection                           | 8         | 1.77%   |
| Intel I210 Gigabit Network Connection                             | 7         | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.11%   |
| Intel Wireless 8260                                               | 5         | 1.11%   |
| Intel Wireless 7265                                               | 5         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.89%   |
| Intel Wireless-AC 9260                                            | 4         | 0.89%   |
| Intel Wireless 3165                                               | 4         | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.89%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 4         | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                    | 3         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.67%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.44%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.44%   |
| Intel Wireless 3160                                               | 2         | 0.44%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.44%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 55.49%  |
| Qualcomm Atheros      | 26        | 15.85%  |
| Realtek Semiconductor | 22        | 13.41%  |
| Broadcom              | 10        | 6.1%    |
| Ralink Technology     | 7         | 4.27%   |
| Ralink                | 3         | 1.83%   |
| Broadcom Limited      | 2         | 1.22%   |
| TP-Link               | 1         | 0.61%   |
| Dell                  | 1         | 0.61%   |
| D-Link                | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 13        | 7.93%   |
| Intel Wireless 7260                                                                           | 12        | 7.32%   |
| Intel Wireless 8265 / 8275                                                                    | 9         | 5.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 7         | 4.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 3.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 5         | 3.05%   |
| Intel Wireless 8260                                                                           | 5         | 3.05%   |
| Intel Wireless 7265                                                                           | 5         | 3.05%   |
| Intel Wireless-AC 9260                                                                        | 4         | 2.44%   |
| Intel Wireless 3165                                                                           | 4         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 4         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.83%   |
| Ralink RT5370 Wireless Adapter                                                                | 3         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3         | 1.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 3         | 1.83%   |
| Intel Centrino Ultimate-N 6300                                                                | 3         | 1.83%   |
| Intel Centrino Advanced-N 6235                                                                | 3         | 1.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3         | 1.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 1.22%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 1.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 2         | 1.22%   |
| Intel Wireless 3160                                                                           | 2         | 1.22%   |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 1.22%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 2         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.61%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.61%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.61%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1         | 0.61%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.61%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.61%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 0.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 0.61%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                                                          | 1         | 0.61%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                          | 1         | 0.61%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                                       | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 124       | 47.15%  |
| Intel                         | 103       | 39.16%  |
| Broadcom                      | 12        | 4.56%   |
| Qualcomm Atheros              | 9         | 3.42%   |
| ASIX Electronics              | 3         | 1.14%   |
| D-Link System                 | 2         | 0.76%   |
| Broadcom Limited              | 2         | 0.76%   |
| Aquantia                      | 2         | 0.76%   |
| Xiaomi                        | 1         | 0.38%   |
| Sierra Wireless               | 1         | 0.38%   |
| OnePlus Technology (Shenzhen) | 1         | 0.38%   |
| Marvell Technology Group      | 1         | 0.38%   |
| ICS Advent                    | 1         | 0.38%   |
| DisplayLink                   | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 103       | 36.52%  |
| Intel I211 Gigabit Network Connection                                         | 15        | 5.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 13        | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 4.26%   |
| Intel Ethernet Connection I217-LM                                             | 10        | 3.55%   |
| Intel 82574L Gigabit Network Connection                                       | 8         | 2.84%   |
| Intel I210 Gigabit Network Connection                                         | 7         | 2.48%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4         | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 1.42%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 1.42%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.42%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 4         | 1.42%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.71%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.71%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.71%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.71%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.35%   |
| Sierra Wireless EM7345 4G LTE                                                 | 1         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.35%   |
| OnePlus (Shenzhen) IN2013                                                     | 1         | 0.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.35%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.35%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.35%   |
| Intel Ethernet Connection X722                                                | 1         | 0.35%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.35%   |
| Intel Ethernet Connection I217-V                                              | 1         | 0.35%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.35%   |
| Intel Ethernet Connection (3) I219-LM                                         | 1         | 0.35%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.35%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.35%   |
| Intel 82578DC Gigabit Network Connection                                      | 1         | 0.35%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.35%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.35%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1         | 0.35%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.35%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1         | 0.35%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 0.35%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 240       | 59.7%   |
| WiFi     | 157       | 39.05%  |
| Unknown  | 4         | 1%      |
| Modem    | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 207       | 61.42%  |
| WiFi     | 127       | 37.69%  |
| Unknown  | 2         | 0.59%   |
| Modem    | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 150       | 58.82%  |
| 1     | 78        | 30.59%  |
| 3     | 17        | 6.67%   |
| 4     | 4         | 1.57%   |
| 6     | 2         | 0.78%   |
| 5     | 2         | 0.78%   |
| 7     | 1         | 0.39%   |
| 0     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 239       | 93.73%  |
| Yes  | 16        | 6.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 52.94%  |
| Qualcomm Atheros Communications | 16        | 11.76%  |
| Realtek Semiconductor           | 14        | 10.29%  |
| Cambridge Silicon Radio         | 10        | 7.35%   |
| Broadcom                        | 10        | 7.35%   |
| Apple                           | 3         | 2.21%   |
| Lite-On Technology              | 2         | 1.47%   |
| IMC Networks                    | 2         | 1.47%   |
| Hewlett-Packard                 | 2         | 1.47%   |
| ASUSTek Computer                | 2         | 1.47%   |
| Toshiba                         | 1         | 0.74%   |
| Ralink                          | 1         | 0.74%   |
| Foxconn / Hon Hai               | 1         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 42        | 30.88%  |
| Intel Bluetooth wireless interface                  | 10        | 7.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 7.35%   |
| Realtek Bluetooth Radio                             | 8         | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 5.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 5.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 4.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 2.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.47%   |
| IMC Networks Bluetooth Device                       | 2         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.47%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.47%   |
| Toshiba Bluetooth Radio                             | 1         | 0.74%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.74%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.74%   |
| Realtek RTL8723A Bluetooth                          | 1         | 0.74%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.74%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.74%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.74%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.74%   |
| Broadcom BCM20702A0                                 | 1         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.74%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.74%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.74%   |
| ASUS BCM20702A0                                     | 1         | 0.74%   |
| Apple Bluetooth Host Controller                     | 1         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 189       | 56.42%  |
| Nvidia                   | 63        | 18.81%  |
| AMD                      | 61        | 18.21%  |
| Plantronics              | 3         | 0.9%    |
| Logitech                 | 3         | 0.9%    |
| GN Netcom                | 3         | 0.9%    |
| C-Media Electronics      | 3         | 0.9%    |
| Texas Instruments        | 2         | 0.6%    |
| Tenx Technology          | 1         | 0.3%    |
| SAVITECH                 | 1         | 0.3%    |
| Lynx                     | 1         | 0.3%    |
| Fry's Electronics        | 1         | 0.3%    |
| Creative Labs            | 1         | 0.3%    |
| Corsair                  | 1         | 0.3%    |
| AVID Technology          | 1         | 0.3%    |
| Asahi Kasei Microsystems | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 6.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 5.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 4.03%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 3.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 3.02%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.77%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 11        | 2.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 2.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.27%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 8         | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 1.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.76%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.51%   |
| Nvidia TU104 HD Audio Controller                                                                  | 5         | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.01%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.76%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.76%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Logitech H390 headset with microphone                                                             | 2         | 0.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.5%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.5%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.5%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.5%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 30        | 20.27%  |
| Samsung Electronics | 25        | 16.89%  |
| Kingston            | 21        | 14.19%  |
| Unknown             | 18        | 12.16%  |
| Crucial             | 14        | 9.46%   |
| Corsair             | 10        | 6.76%   |
| Micron Technology   | 9         | 6.08%   |
| G.Skill             | 5         | 3.38%   |
| A-DATA Technology   | 4         | 2.7%    |
| Team                | 3         | 2.03%   |
| Elpida              | 3         | 2.03%   |
| Ramaxel Technology  | 2         | 1.35%   |
| Nanya Technology    | 2         | 1.35%   |
| TwinMOS             | 1         | 0.68%   |
| AMD                 | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 1.95%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.3%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                            | 2         | 1.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2         | 1.3%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                         | 2         | 1.3%    |
| Unknown RAM Module 2GB DIMM SDRAM                               | 2         | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 1.3%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 2         | 1.3%    |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s        | 2         | 1.3%    |
| Unknown SODIMM 4GB SODIMM DDR2 667MT/s                          | 1         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1         | 0.65%   |
| Unknown RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.65%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s             | 1         | 0.65%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s             | 1         | 0.65%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s              | 1         | 0.65%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                           | 1         | 0.65%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.65%   |
| SK Hynix RAM Module 8GB DIMM DDR4 2133MT/s                      | 1         | 0.65%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.65%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.65%   |
| SK Hynix RAM Module 64GB DIMM 4800MT/s                          | 1         | 0.65%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.65%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s                     | 1         | 0.65%   |
| SK Hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s           | 1         | 0.65%   |
| SK Hynix RAM HMT851S6AMR6R-PB N0 4096MB Chip DDR3 1600MT/s      | 1         | 0.65%   |
| SK Hynix RAM HMT451U7AFR8A-PB 4096MB DIMM DDR3 1600MT/s         | 1         | 0.65%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1         | 0.65%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s         | 1         | 0.65%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s            | 1         | 0.65%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s       | 1         | 0.65%   |
| SK Hynix RAM HMT125S6AFP8C-G7 2048MB SODIMM DDR3 1066MT/s       | 1         | 0.65%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s            | 1         | 0.65%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s            | 1         | 0.65%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2666MT/s           | 1         | 0.65%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s      | 1         | 0.65%   |
| SK Hynix RAM HMA81GR7AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 1         | 0.65%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 0.65%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                       | 1         | 0.65%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                    | 1         | 0.65%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.65%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s        | 1         | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s           | 1         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.65%   |
| Samsung RAM M471A5143DB0-CPB 4096MB SODIMM DDR4 2133MT/s        | 1         | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 45.31%  |
| DDR3    | 52        | 40.63%  |
| Unknown | 9         | 7.03%   |
| DDR2    | 4         | 3.13%   |
| SDRAM   | 3         | 2.34%   |
| LPDDR4  | 1         | 0.78%   |
| LPDDR3  | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 69        | 53.91%  |
| SODIMM       | 54        | 42.19%  |
| Row Of Chips | 3         | 2.34%   |
| FB-DIMM      | 1         | 0.78%   |
| Chip         | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 48        | 35.56%  |
| 8192  | 39        | 28.89%  |
| 16384 | 25        | 18.52%  |
| 2048  | 14        | 10.37%  |
| 32768 | 6         | 4.44%   |
| 65536 | 1         | 0.74%   |
| 1024  | 1         | 0.74%   |
| 512   | 1         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 26.12%  |
| 2667    | 23        | 17.16%  |
| 1333    | 19        | 14.18%  |
| 2400    | 14        | 10.45%  |
| 2133    | 9         | 6.72%   |
| 2666    | 6         | 4.48%   |
| 3200    | 5         | 3.73%   |
| 3600    | 3         | 2.24%   |
| 1334    | 3         | 2.24%   |
| 667     | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 4800    | 1         | 0.75%   |
| 4267    | 1         | 0.75%   |
| 3466    | 1         | 0.75%   |
| 3000    | 1         | 0.75%   |
| 2933    | 1         | 0.75%   |
| 2800    | 1         | 0.75%   |
| 1800    | 1         | 0.75%   |
| 1067    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |
| 800     | 1         | 0.75%   |
| 400     | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Brother Industries | 2         | 40%     |
| Kyocera            | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP DeskJet 2130 series   | 2         | 40%     |
| Kyocera FS-1030D printer | 1         | 20%     |
| Brother MFC-J450DW       | 1         | 20%     |
| Brother HL-L2390DW       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 29.36%  |
| Microdia                               | 13        | 11.93%  |
| Acer                                   | 11        | 10.09%  |
| Lite-On Technology                     | 9         | 8.26%   |
| Logitech                               | 7         | 6.42%   |
| Realtek Semiconductor                  | 6         | 5.5%    |
| IMC Networks                           | 6         | 5.5%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.67%   |
| Sunplus Innovation Technology          | 3         | 2.75%   |
| Quanta                                 | 3         | 2.75%   |
| Syntek                                 | 2         | 1.83%   |
| Silicon Motion                         | 2         | 1.83%   |
| Microsoft                              | 2         | 1.83%   |
| Suyin                                  | 1         | 0.92%   |
| Sunplus Technology                     | 1         | 0.92%   |
| Samsung Electronics                    | 1         | 0.92%   |
| Intel                                  | 1         | 0.92%   |
| Hewlett-Packard                        | 1         | 0.92%   |
| Cubeternet                             | 1         | 0.92%   |
| Creative Technology                    | 1         | 0.92%   |
| Apple                                  | 1         | 0.92%   |
| Alcor Micro                            | 1         | 0.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 5         | 4.59%   |
| Lite-On HP HD Camera                      | 4         | 3.67%   |
| Acer Integrated Camera                    | 4         | 3.67%   |
| Microdia Integrated_Webcam_HD             | 3         | 2.75%   |
| Logitech HD Webcam C615                   | 3         | 2.75%   |
| Lite-On Integrated Camera                 | 3         | 2.75%   |
| IMC Networks Integrated Camera            | 3         | 2.75%   |
| Chicony USB2.0 VGA UVC WebCam             | 3         | 2.75%   |
| Chicony Integrated Camera (1280x720@30)   | 3         | 2.75%   |
| Chicony HP TrueVision HD                  | 3         | 2.75%   |
| Chicony HP HD Camera                      | 3         | 2.75%   |
| Chicony HD WebCam                         | 3         | 2.75%   |
| Acer Lenovo EasyCamera                    | 3         | 2.75%   |
| Microdia Laptop_Integrated_Webcam_HD      | 2         | 1.83%   |
| Microdia Laptop_Integrated_Webcam_2M      | 2         | 1.83%   |
| Logitech HD Pro Webcam C920               | 2         | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam         | 2         | 1.83%   |
| Chicony HP Webcam [2 MP Macro]            | 2         | 1.83%   |
| Chicony HP HD Webcam                      | 2         | 1.83%   |
| Syntek USB2.0 UVC PC Camera               | 1         | 0.92%   |
| Syntek Lenovo EasyCamera                  | 1         | 0.92%   |
| Suyin Sony Visual Communication Camera    | 1         | 0.92%   |
| Sunplus 1.3M WebCam                       | 1         | 0.92%   |
| Sunplus USB Video Device                  | 1         | 0.92%   |
| Sunplus Integrated_Webcam_FHD             | 1         | 0.92%   |
| Sunplus HD WebCam                         | 1         | 0.92%   |
| Silicon Motion WebCam SC-13HDL11431N      | 1         | 0.92%   |
| Silicon Motion ATIV VGA Camera            | 1         | 0.92%   |
| Samsung Galaxy A5 (MTP)                   | 1         | 0.92%   |
| Realtek USB Camera                        | 1         | 0.92%   |
| Realtek Laptop_Integrated_Webcam_FHD      | 1         | 0.92%   |
| Realtek Integrated Webcam                 | 1         | 0.92%   |
| Realtek HD Webcam - Realtek               | 1         | 0.92%   |
| Realtek HD Webcam                         | 1         | 0.92%   |
| Realtek FULL HD 1080P Webcam              | 1         | 0.92%   |
| Quanta HP TrueVision HD Camera            | 1         | 0.92%   |
| Quanta HD Webcam                          | 1         | 0.92%   |
| Quanta HD User Facing                     | 1         | 0.92%   |
| Microsoft LifeCam VX-500 [1357]           | 1         | 0.92%   |
| Microsoft LifeCam HD-3000                 | 1         | 0.92%   |
| Microdia Webcam SC-10HDD12636P            | 1         | 0.92%   |
| Microdia Sony Visual Communication Camera | 1         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_1.3M    | 1         | 0.92%   |
| Microdia Integrated Webcam                | 1         | 0.92%   |
| Microdia Camera                           | 1         | 0.92%   |
| Microdia ACR010 USB Webcam                | 1         | 0.92%   |
| Logitech Webcam C930e                     | 1         | 0.92%   |
| Logitech Webcam C270                      | 1         | 0.92%   |
| Lite-On HP Wide Vision FHD Camera         | 1         | 0.92%   |
| Lite-On HP HD Webcam                      | 1         | 0.92%   |
| Intel RealSense 3D Camera (Front F200)    | 1         | 0.92%   |
| IMC Networks EasyCamera                   | 1         | 0.92%   |
| HP Webcam HD 4310                         | 1         | 0.92%   |
| Cubeternet USB2.0 Camera                  | 1         | 0.92%   |
| Creative Live! Cam Chat HD [VF0700]       | 1         | 0.92%   |
| Chicony USB2.0 Camera                     | 1         | 0.92%   |
| Chicony USB 2.0 Camera                    | 1         | 0.92%   |
| Chicony TOSHIBA Web Camera - HD           | 1         | 0.92%   |
| Chicony Sony Visual Communication Camera  | 1         | 0.92%   |
| Chicony HP TrueVision HD Camera           | 1         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 61.29%  |
| Synaptics                  | 6         | 19.35%  |
| Upek                       | 2         | 6.45%   |
| Elan Microelectronics      | 2         | 6.45%   |
| Shenzhen Goodix Technology | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 22.58%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 6.45%   |
| Validity Sensors VFS491                                                    | 2         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.45%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Synaptics  WBDI                                                            | 1         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.23%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.23%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 4         | 40%     |
| Giesecke & Devrient | 2         | 20%     |
| Cherry              | 2         | 20%     |
| SCM Microsystems    | 1         | 10%     |
| Alcor Micro         | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Giesecke & Devrient StarSign CUT S                                           | 2         | 20%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 20%     |
| Broadcom 58200                                                               | 2         | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 166       | 64.59%  |
| 1     | 72        | 28.02%  |
| 2     | 12        | 4.67%   |
| 3     | 3         | 1.17%   |
| 4     | 2         | 0.78%   |
| 6     | 1         | 0.39%   |
| 5     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 27.43%  |
| Graphics card            | 21        | 18.58%  |
| Unassigned class         | 12        | 10.62%  |
| Communication controller | 11        | 9.73%   |
| Net/wireless             | 9         | 7.96%   |
| Storage/ide              | 5         | 4.42%   |
| Multimedia controller    | 5         | 4.42%   |
| Storage/raid             | 3         | 2.65%   |
| Sound                    | 3         | 2.65%   |
| Net/ethernet             | 3         | 2.65%   |
| Chipcard                 | 3         | 2.65%   |
| Storage                  | 2         | 1.77%   |
| Network                  | 2         | 1.77%   |
| Bluetooth                | 2         | 1.77%   |
| Camera                   | 1         | 0.88%   |

