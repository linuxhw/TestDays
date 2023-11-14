Linux in Colombia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 425

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 198E                        | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [4236902f3d](https://linux-hardware.org/?probe=4236902f3d) | Nov 03, 2023 |
| Dell          | 0200DY A02                  | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [385c30cad6](https://linux-hardware.org/?probe=385c30cad6) | Oct 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [e3db582993](https://linux-hardware.org/?probe=e3db582993) | Oct 31, 2023 |
| Dell          | 08NPPY A01                  | [62bc2b3e7a](https://linux-hardware.org/?probe=62bc2b3e7a) | Oct 28, 2023 |
| Lenovo        | 0B98409 STD                 | [b89f42b23f](https://linux-hardware.org/?probe=b89f42b23f) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Intel         | X79G V2.x                   | [49d37b87cf](https://linux-hardware.org/?probe=49d37b87cf) | Oct 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| ASUSTek       | H81M-A                      | [0702e52c02](https://linux-hardware.org/?probe=0702e52c02) | Oct 14, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4ba8548e96](https://linux-hardware.org/?probe=4ba8548e96) | Oct 14, 2023 |
| Lenovo        | ThinkCentre M90 5485AK7     | [02e02dbca5](https://linux-hardware.org/?probe=02e02dbca5) | Oct 11, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6ff82127e5](https://linux-hardware.org/?probe=6ff82127e5) | Oct 05, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| Gigabyte      | H61M-S1                     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| Intel         | DG31PR AAD97573-301         | [359e7817c3](https://linux-hardware.org/?probe=359e7817c3) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Intel         | X79G V2.x                   | [658431c5b8](https://linux-hardware.org/?probe=658431c5b8) | Aug 22, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| Intel         | DH61CR AAG14064-207         | [25d122723f](https://linux-hardware.org/?probe=25d122723f) | Aug 15, 2023 |
| Intel         | DH61CR AAG14064-207         | [ae4eca1596](https://linux-hardware.org/?probe=ae4eca1596) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | B85M                        | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| HP            | 2820h                       | [ecbafa25c0](https://linux-hardware.org/?probe=ecbafa25c0) | Jul 10, 2023 |
| HP            | 2820h                       | [9d4f48820d](https://linux-hardware.org/?probe=9d4f48820d) | Jul 10, 2023 |
| HP            | 304Ah                       | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| ASRock        | H55M                        | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| ASUSTek       | PRIME H410M-E               | [cc8a15081a](https://linux-hardware.org/?probe=cc8a15081a) | Jun 22, 2023 |
| Acer          | Veriton X490G               | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Gigabyte      | H61M-HD2                    | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASRock        | B450M-HDV R4.0              | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [87a75f9dd9](https://linux-hardware.org/?probe=87a75f9dd9) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [a375533daa](https://linux-hardware.org/?probe=a375533daa) | May 05, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2dffd7bed6](https://linux-hardware.org/?probe=2dffd7bed6) | Apr 30, 2023 |
| Pegatron      | 2A73h                       | [f4578519ad](https://linux-hardware.org/?probe=f4578519ad) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| ASUSTek       | M4N98TD EVO                 | [a2423b5193](https://linux-hardware.org/?probe=a2423b5193) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [592d9de1cb](https://linux-hardware.org/?probe=592d9de1cb) | Mar 23, 2023 |
| HP            | 18E9                        | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| Lenovo        | MAHOBAY NOK                 | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| HP            | 1850                        | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| HP            | 1850                        | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Biostar       | H61MHV                      | [9f184e6e93](https://linux-hardware.org/?probe=9f184e6e93) | Mar 11, 2023 |
| Intel         | DH61BF AAG81311-101         | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | 806A                        | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| HP            | 2ADE                        | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| HP            | 18E9                        | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| HP            | 1497                        | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e4496f3ff8](https://linux-hardware.org/?probe=e4496f3ff8) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Unknown       | X79A                        | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [edbd391f2d](https://linux-hardware.org/?probe=edbd391f2d) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| ASRock        | G965M-S                     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [e7107ee8b4](https://linux-hardware.org/?probe=e7107ee8b4) | Jan 06, 2023 |
| Gigabyte      | A520M DS3H                  | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Intel         | DH61BF AAG81311-101         | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| HP            | 18E9                        | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| HP            | 339A                        | [ea5cacd50e](https://linux-hardware.org/?probe=ea5cacd50e) | Nov 29, 2022 |
| Dell          | 0HJ054                      | [0e3d082d5a](https://linux-hardware.org/?probe=0e3d082d5a) | Nov 22, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| MSI           | GF615M-P33                  | [1a298da454](https://linux-hardware.org/?probe=1a298da454) | Nov 09, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| BESSTAR Te... | TH50                        | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASRock        | B550M Pro4                  | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Dell          | 054KM3 A01                  | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| MSI           | H81M-E33                    | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Gigabyte      | H61M-HD2                    | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Pegatron      | 2A73h                       | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| ASUSTek       | PRIME Z390-A                | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| Supermicro    | X7DA8                       | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASRock        | Z77 Extreme4                | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | 1587h                       | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| MSI           | B150A GAMING PRO            | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| MSI           | 760GM-P23                   | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| ASUSTek       | PRIME X570-P                | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| ASUSTek       | PRIME B550M-K               | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Gigabyte      | H81M-H                      | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| ASRock        | G41M-VS3                    | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| HP            | 0B4Ch D                     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | PRIME B550M-K               | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| ASUSTek       | Z97-A                       | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| ECS           | G31T-M7                     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | 18E9                        | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| MSI           | B350M GAMING PRO            | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| Gigabyte      | G31M-S2C                    | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Pegatron      | 2AEE                        | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| HP            | 304Ah                       | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 304Ah                       | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| Intel         | DB75EN AAG39650-303         | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Intel         | DH55HC AAE70933-505         | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| MSI           | MS-7309                     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASRock        | Wolfdale1333-D667           | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| ECS           | H81H3-M4                    | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| ASRock        | G965M-S                     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Intel         | H61                         | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| Dell          | 0G3HR7 A00                  | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Intel         | DH55HC AAE70933-505         | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Dell          | 0G3HR7 A00                  | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Gigabyte      | H61M-S1                     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| ASRock        | Wolfdale1333-D667           | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| Intel         | DP67DE AAG10217-205         | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| MSI           | A320M-A PRO MAX             | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Dell          | 0HN7XN A01                  | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| ECS           | H81H3-M4                    | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| ASUSTek       | PRIME H310M-E               | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| Intel         | H61                         | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| MSI           | B450M BAZOOKA V2            | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Biostar       | H61MHV                      | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| Gigabyte      | 970A-UD3                    | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| PCSMART       | Unknown                     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| ASRock        | G41M-VS3                    | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ECS           | H81H3-M4                    | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| ASRock        | AB350M-HDV                  | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| ASRock        | 960GM-VGS3 FX               | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| ASRock        | A320M-HDV                   | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| ASRock        | G31M-GS                     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| MSI           | H81M-E33                    | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| Intel         | 945GCT-M                    | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | 0MM599                      | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| ASUSTek       | M4A87TD EVO                 | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Gigabyte      | AM1M-S2H                    | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Dell          | 0D6H9T A01                  | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| MSI           | A68HM-E33                   | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| Gigabyte      | X570 UD                     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| ECS           | H81H3-M4                    | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| Hardkernel    | ODROID-H2                   | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| ASRock        | N68C-S UCC                  | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ECS           | H81H3-M4                    | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| Biostar       | N68S3+                      | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| Dell          | 054KM3 A00                  | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| MSI           | A55M-P35                    | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| ASRock        | G41M-VS3                    | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| MSI           | H110M PRO-VH PLUS           | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| ASRock        | G965M-S                     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| ECS           | H81H3-M4                    | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| MSI           | 970A-G43 PLUS               | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Gigabyte      | G31M-S2C                    | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| MSI           | MS-7309                     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Unknown       | Unknown                     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| HP            | 3048h                       | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| MSI           | K9N6PGM2-V2                 | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| Intel         | DH61WW AAG23116-302         | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| ASUSTek       | PRIME H310-PLUS             | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Dell          | 0P301D A00                  | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| ASRock        | G41M-VS3                    | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Unknown       | GSUO H61V10C                | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Pegatron      | 2AAE                        | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| MSI           | MS-7309                     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| HP            | ProLiant ML115 G1           | [8f0d70a883](https://linux-hardware.org/?probe=8f0d70a883) | Jul 29, 2019 |
| Dell          | OptiPlex GX260              | [6c061a7a15](https://linux-hardware.org/?probe=6c061a7a15) | Jul 23, 2019 |
| ASUSTek       | H81M-K                      | [b124f401f6](https://linux-hardware.org/?probe=b124f401f6) | Jul 17, 2019 |
| Intel         | DH55HC AAE70933-501         | [3462cd0ccd](https://linux-hardware.org/?probe=3462cd0ccd) | Jul 07, 2019 |
| MSI           | MS-7191                     | [d753273d7b](https://linux-hardware.org/?probe=d753273d7b) | Jul 03, 2019 |
| Dell          | 0RY206                      | [aed7ab6e58](https://linux-hardware.org/?probe=aed7ab6e58) | Jun 28, 2019 |
| Gigabyte      | H81M-H                      | [bebf195e43](https://linux-hardware.org/?probe=bebf195e43) | Jun 18, 2019 |
| ASRock        | K8Upgrade-VM800             | [83cccbaf1a](https://linux-hardware.org/?probe=83cccbaf1a) | Jun 03, 2019 |
| ASRock        | G965M-S                     | [30b8a56200](https://linux-hardware.org/?probe=30b8a56200) | May 30, 2019 |
| Dell          | 0TT708 A01                  | [b732db0128](https://linux-hardware.org/?probe=b732db0128) | May 24, 2019 |
| Dell          | 0TT708 A01                  | [fbe3c00bb0](https://linux-hardware.org/?probe=fbe3c00bb0) | May 24, 2019 |
| Unknown       | 775i65G                     | [0b6fd94458](https://linux-hardware.org/?probe=0b6fd94458) | May 19, 2019 |
| Unknown       | 775i65G                     | [2b8a659310](https://linux-hardware.org/?probe=2b8a659310) | May 18, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [29cf71291b](https://linux-hardware.org/?probe=29cf71291b) | Apr 21, 2019 |
| Biostar       | A55MLV                      | [38fd682351](https://linux-hardware.org/?probe=38fd682351) | Apr 19, 2019 |
| HP            | 0A60h                       | [c59eb70baf](https://linux-hardware.org/?probe=c59eb70baf) | Apr 11, 2019 |
| HP            | 0A60h                       | [bd74dccea9](https://linux-hardware.org/?probe=bd74dccea9) | Apr 10, 2019 |
| ASUSTek       | H81M-K                      | [c5178f5550](https://linux-hardware.org/?probe=c5178f5550) | Apr 04, 2019 |
| ASUSTek       | H81M-K                      | [ef3d04377e](https://linux-hardware.org/?probe=ef3d04377e) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [be751979a7](https://linux-hardware.org/?probe=be751979a7) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [b9c1d97ec1](https://linux-hardware.org/?probe=b9c1d97ec1) | Apr 01, 2019 |
| Biostar       | A55MLV                      | [138e3baa2d](https://linux-hardware.org/?probe=138e3baa2d) | Mar 29, 2019 |
| ASUSTek       | H81M-K                      | [d3f5c5ac28](https://linux-hardware.org/?probe=d3f5c5ac28) | Mar 29, 2019 |
| Intel         | DH61CR AAG14064-207         | [2c44dea441](https://linux-hardware.org/?probe=2c44dea441) | Mar 17, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [8d9fa49be1](https://linux-hardware.org/?probe=8d9fa49be1) | Feb 09, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [5dcbf55671](https://linux-hardware.org/?probe=5dcbf55671) | Feb 09, 2019 |
| ASRock        | Wolfdale1333-D667           | [f67c3262d4](https://linux-hardware.org/?probe=f67c3262d4) | Dec 10, 2018 |
| ASRock        | Wolfdale1333-D667           | [06bcad286b](https://linux-hardware.org/?probe=06bcad286b) | Nov 18, 2018 |
| Pegatron      | 2A73h                       | [9ab888ea4f](https://linux-hardware.org/?probe=9ab888ea4f) | Jun 19, 2018 |
| HP            | 2ADE                        | [af28bb9a2f](https://linux-hardware.org/?probe=af28bb9a2f) | Dec 01, 2017 |
| HP            | 2ADE                        | [a2ab5f4392](https://linux-hardware.org/?probe=a2ab5f4392) | Dec 01, 2017 |
| HP            | 0A54h                       | [1f795e5896](https://linux-hardware.org/?probe=1f795e5896) | Jun 29, 2017 |
| HP            | 0A54h                       | [ef67a7d651](https://linux-hardware.org/?probe=ef67a7d651) | Feb 05, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 33       | 10.75%  |
| Ubuntu 18.04        | 31       | 10.1%   |
| Ubuntu 22.04        | 15       | 4.89%   |
| OpenMandriva 4.3    | 14       | 4.56%   |
| Fedora 38           | 10       | 3.26%   |
| Linux Mint 20.3     | 9        | 2.93%   |
| Linux Mint 20.2     | 8        | 2.61%   |
| KDE neon 20.04      | 7        | 2.28%   |
| ArcoLinux Rolling   | 7        | 2.28%   |
| Arch Rolling        | 7        | 2.28%   |
| Zorin 15            | 6        | 1.95%   |
| OpenMandriva 4.2    | 6        | 1.95%   |
| Fedora 37           | 6        | 1.95%   |
| OpenMandriva 23.08  | 5        | 1.63%   |
| Manjaro             | 5        | 1.63%   |
| Linux Mint 19.3     | 5        | 1.63%   |
| KDE neon 22.04      | 5        | 1.63%   |
| Fedora 35           | 5        | 1.63%   |
| Debian 11           | 5        | 1.63%   |
| Zorin 16            | 4        | 1.3%    |
| Xubuntu 20.04       | 4        | 1.3%    |
| Fedora 36           | 4        | 1.3%    |
| Zorin 12            | 3        | 0.98%   |
| Ubuntu 19.04        | 3        | 0.98%   |
| ROSA R11            | 3        | 0.98%   |
| ROSA 12.2           | 3        | 0.98%   |
| OpenMandriva 23.03  | 3        | 0.98%   |
| OpenMandriva 23.01  | 3        | 0.98%   |
| Nobara 36           | 3        | 0.98%   |
| Linux Mint 21.1     | 3        | 0.98%   |
| Kubuntu 20.04       | 3        | 0.98%   |
| Fedora 32           | 3        | 0.98%   |
| Elementary 6.1      | 3        | 0.98%   |
| Arch                | 3        | 0.98%   |
| Xubuntu 22.04       | 2        | 0.65%   |
| Ubuntu Unity 16.04  | 2        | 0.65%   |
| Ubuntu Budgie 20.04 | 2        | 0.65%   |
| Ubuntu 19.10        | 2        | 0.65%   |
| ROSA R10            | 2        | 0.65%   |
| ROSA 12.4           | 2        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 85       | 29.21%  |
| OpenMandriva  | 32       | 11%     |
| Linux Mint    | 31       | 10.65%  |
| Fedora        | 29       | 9.97%   |
| Zorin         | 13       | 4.47%   |
| KDE neon      | 12       | 4.12%   |
| ROSA          | 10       | 3.44%   |
| Arch          | 10       | 3.44%   |
| Manjaro       | 8        | 2.75%   |
| Xubuntu       | 7        | 2.41%   |
| Debian        | 7        | 2.41%   |
| ArcoLinux     | 7        | 2.41%   |
| Kubuntu       | 5        | 1.72%   |
| Elementary    | 4        | 1.37%   |
| Ubuntu Unity  | 3        | 1.03%   |
| Pop!_OS       | 3        | 1.03%   |
| openSUSE      | 3        | 1.03%   |
| Nobara        | 3        | 1.03%   |
| Lubuntu       | 3        | 1.03%   |
| Ubuntu Budgie | 2        | 0.69%   |
| Endless       | 2        | 0.69%   |
| Deepin        | 2        | 0.69%   |
| BlackPanther  | 2        | 0.69%   |
| Xero          | 1        | 0.34%   |
| Rocky Linux   | 1        | 0.34%   |
| Reborn OS     | 1        | 0.34%   |
| Parrot        | 1        | 0.34%   |
| MX            | 1        | 0.34%   |
| LMDE          | 1        | 0.34%   |
| Kali          | 1        | 0.34%   |
| CentOS        | 1        | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 13       | 3.86%   |
| 5.4.0-42-generic                   | 7        | 2.08%   |
| 5.10.14-desktop-1omv4002           | 6        | 1.78%   |
| 6.4.11-desktop-1omv2390            | 5        | 1.48%   |
| 5.19.0-35-generic                  | 5        | 1.48%   |
| 5.15.0-56-generic                  | 5        | 1.48%   |
| 5.4.0-72-generic                   | 4        | 1.19%   |
| 5.4.0-58-generic                   | 4        | 1.19%   |
| 5.0.0-32-generic                   | 4        | 1.19%   |
| 6.2.6-desktop-1omv2390             | 3        | 0.89%   |
| 6.2.0-35-generic                   | 3        | 0.89%   |
| 6.1.1-desktop-1omv2290             | 3        | 0.89%   |
| 5.4.0-48-generic                   | 3        | 0.89%   |
| 5.4.0-45-generic                   | 3        | 0.89%   |
| 5.4.0-122-generic                  | 3        | 0.89%   |
| 5.19.0-41-generic                  | 3        | 0.89%   |
| 5.15.0-67-generic                  | 3        | 0.89%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3        | 0.89%   |
| 4.18.0-16-generic                  | 3        | 0.89%   |
| 4.15.0-54-generic                  | 3        | 0.89%   |
| 6.4.13-200.fc38.x86_64             | 2        | 0.59%   |
| 6.4.10-200.fc38.x86_64             | 2        | 0.59%   |
| 6.3.8-200.fc38.x86_64              | 2        | 0.59%   |
| 6.1.18-200.fc37.x86_64             | 2        | 0.59%   |
| 5.8.0-48-generic                   | 2        | 0.59%   |
| 5.8.0-43-generic                   | 2        | 0.59%   |
| 5.4.0-97-generic                   | 2        | 0.59%   |
| 5.4.0-88-generic                   | 2        | 0.59%   |
| 5.4.0-70-generic                   | 2        | 0.59%   |
| 5.4.0-60-generic                   | 2        | 0.59%   |
| 5.4.0-52-generic                   | 2        | 0.59%   |
| 5.4.0-47-generic                   | 2        | 0.59%   |
| 5.4.0-40-generic                   | 2        | 0.59%   |
| 5.4.0-37-generic                   | 2        | 0.59%   |
| 5.4.0-31-generic                   | 2        | 0.59%   |
| 5.4.0-144-generic                  | 2        | 0.59%   |
| 5.4.0-125-generic                  | 2        | 0.59%   |
| 5.4.0-121-generic                  | 2        | 0.59%   |
| 5.4.0-107-generic                  | 2        | 0.59%   |
| 5.3.0-59-generic                   | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 64       | 20.06%  |
| 5.15.0  | 25       | 7.84%   |
| 4.15.0  | 17       | 5.33%   |
| 5.16.7  | 13       | 4.08%   |
| 5.19.0  | 12       | 3.76%   |
| 5.0.0   | 11       | 3.45%   |
| 5.3.0   | 10       | 3.13%   |
| 5.13.0  | 10       | 3.13%   |
| 5.8.0   | 8        | 2.51%   |
| 4.18.0  | 8        | 2.51%   |
| 6.2.0   | 6        | 1.88%   |
| 5.11.0  | 6        | 1.88%   |
| 5.10.14 | 6        | 1.88%   |
| 6.4.11  | 5        | 1.57%   |
| 6.1.1   | 4        | 1.25%   |
| 5.10.0  | 4        | 1.25%   |
| 6.2.6   | 3        | 0.94%   |
| 5.8.5   | 3        | 0.94%   |
| 5.8.18  | 3        | 0.94%   |
| 5.12.4  | 3        | 0.94%   |
| 5.10.74 | 3        | 0.94%   |
| 6.5.7   | 2        | 0.63%   |
| 6.4.13  | 2        | 0.63%   |
| 6.4.10  | 2        | 0.63%   |
| 6.3.8   | 2        | 0.63%   |
| 6.2.15  | 2        | 0.63%   |
| 6.1.18  | 2        | 0.63%   |
| 6.0.10  | 2        | 0.63%   |
| 5.17.5  | 2        | 0.63%   |
| 5.15.12 | 2        | 0.63%   |
| 5.14.1  | 2        | 0.63%   |
| 5.13.19 | 2        | 0.63%   |
| 4.19.0  | 2        | 0.63%   |
| 4.18.16 | 2        | 0.63%   |
| 6.5.6   | 1        | 0.31%   |
| 6.5.5   | 1        | 0.31%   |
| 6.5.0   | 1        | 0.31%   |
| 6.4.7   | 1        | 0.31%   |
| 6.3.9   | 1        | 0.31%   |
| 6.3.7   | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 67       | 21.41%  |
| 5.15    | 31       | 9.9%    |
| 5.10    | 19       | 6.07%   |
| 5.16    | 17       | 5.43%   |
| 4.15    | 17       | 5.43%   |
| 5.8     | 15       | 4.79%   |
| 6.1     | 13       | 4.15%   |
| 6.2     | 12       | 3.83%   |
| 5.19    | 12       | 3.83%   |
| 5.13    | 12       | 3.83%   |
| 5.3     | 11       | 3.51%   |
| 5.0     | 11       | 3.51%   |
| 4.18    | 10       | 3.19%   |
| 6.4     | 9        | 2.88%   |
| 6.3     | 7        | 2.24%   |
| 5.14    | 7        | 2.24%   |
| 5.11    | 7        | 2.24%   |
| 6.5     | 5        | 1.6%    |
| 6.0     | 5        | 1.6%    |
| 5.12    | 5        | 1.6%    |
| 5.17    | 4        | 1.28%   |
| 4.9     | 4        | 1.28%   |
| 5.9     | 2        | 0.64%   |
| 5.6     | 2        | 0.64%   |
| 5.18    | 2        | 0.64%   |
| 4.19    | 2        | 0.64%   |
| 5.7     | 1        | 0.32%   |
| 5.2     | 1        | 0.32%   |
| 4.12    | 1        | 0.32%   |
| 4.10    | 1        | 0.32%   |
| 4.1     | 1        | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 279      | 97.89%  |
| i686   | 6        | 2.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 117      | 40.07%  |
| KDE5          | 62       | 21.23%  |
| Unknown       | 25       | 8.56%   |
| X-Cinnamon    | 21       | 7.19%   |
| XFCE          | 19       | 6.51%   |
| KDE           | 10       | 3.42%   |
| MATE          | 6        | 2.05%   |
| Pantheon      | 4        | 1.37%   |
| LXQt          | 4        | 1.37%   |
| KDE4          | 4        | 1.37%   |
| Cinnamon      | 4        | 1.37%   |
| Unity         | 3        | 1.03%   |
| i3            | 3        | 1.03%   |
| Deepin        | 3        | 1.03%   |
| GNOME Classic | 2        | 0.68%   |
| Budgie        | 2        | 0.68%   |
| ubuntu=GNOME  | 1        | 0.34%   |
| LXDE          | 1        | 0.34%   |
| awesome       | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 222      | 75.51%  |
| Wayland | 53       | 18.03%  |
| Unknown | 14       | 4.76%   |
| Tty     | 5        | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 148      | 50.68%  |
| SDDM    | 51       | 17.47%  |
| GDM     | 33       | 11.3%   |
| LightDM | 27       | 9.25%   |
| GDM3    | 22       | 7.53%   |
| TDM     | 6        | 2.05%   |
| KDM     | 4        | 1.37%   |
| SLiM    | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CO   | 149      | 50.85%  |
| en_US   | 77       | 26.28%  |
| Unknown | 34       | 11.6%   |
| es_ES   | 22       | 7.51%   |
| C       | 4        | 1.37%   |
| es_MX   | 3        | 1.02%   |
| pt_BR   | 2        | 0.68%   |
| en_GB   | 2        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 174      | 60.63%  |
| EFI  | 113      | 39.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 205      | 70.45%  |
| Btrfs   | 38       | 13.06%  |
| Overlay | 30       | 10.31%  |
| Tmpfs   | 6        | 2.06%   |
| Xfs     | 5        | 1.72%   |
| Unknown | 5        | 1.72%   |
| Zfs     | 1        | 0.34%   |
| Ext2    | 1        | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 148      | 51.21%  |
| GPT     | 92       | 31.83%  |
| MBR     | 49       | 16.96%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 241      | 81.69%  |
| Yes       | 54       | 18.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 59.17%  |
| Yes       | 118      | 40.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 57       | 20%     |
| Gigabyte Technology | 53       | 18.6%   |
| ASRock              | 32       | 11.23%  |
| MSI                 | 30       | 10.53%  |
| Hewlett-Packard     | 30       | 10.53%  |
| Intel               | 19       | 6.67%   |
| Dell                | 15       | 5.26%   |
| Lenovo              | 11       | 3.86%   |
| ECS                 | 6        | 2.11%   |
| Biostar             | 6        | 2.11%   |
| Pegatron            | 5        | 1.75%   |
| Unknown             | 5        | 1.75%   |
| Foxconn             | 4        | 1.4%    |
| Acer                | 3        | 1.05%   |
| PCSMART             | 2        | 0.7%    |
| Supermicro          | 1        | 0.35%   |
| PCChips             | 1        | 0.35%   |
| MACHINIST           | 1        | 0.35%   |
| Intel X79           | 1        | 0.35%   |
| Hardkernel          | 1        | 0.35%   |
| BESSTAR Tech        | 1        | 0.35%   |
| Apple               | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte B450M DS3H                | 7        | 2.46%   |
| Unknown                            | 7        | 2.46%   |
| ASUS All Series                    | 5        | 1.75%   |
| MSI MS-7817                        | 4        | 1.4%    |
| MSI MS-7309                        | 4        | 1.4%    |
| Gigabyte H81M-H                    | 4        | 1.4%    |
| HP ProDesk 400 G1 SFF              | 3        | 1.05%   |
| Gigabyte H61M-HD2                  | 3        | 1.05%   |
| Gigabyte GA-78LMT-USB3             | 3        | 1.05%   |
| Gigabyte G31M-ES2C                 | 3        | 1.05%   |
| ECS G31T-M7                        | 3        | 1.05%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 1.05%   |
| ASUS PRIME A320M-K                 | 3        | 1.05%   |
| ASUS M5A78L-M/USB3                 | 3        | 1.05%   |
| ASRock Wolfdale1333-D667           | 3        | 1.05%   |
| ASRock G965M-S                     | 3        | 1.05%   |
| ASRock G41M-VS3                    | 3        | 1.05%   |
| MSI MS-7C37                        | 2        | 0.7%    |
| Intel H61                          | 2        | 0.7%    |
| Intel DH61CR AAG14064-207          | 2        | 0.7%    |
| HP Compaq Pro 4300 SFF PC          | 2        | 0.7%    |
| HP Compaq dc7700 Small Form Factor | 2        | 0.7%    |
| Gigabyte X399 AORUS PRO            | 2        | 0.7%    |
| Gigabyte H61M-S1                   | 2        | 0.7%    |
| Gigabyte B550 AORUS PRO AC         | 2        | 0.7%    |
| Gigabyte A520M DS3H                | 2        | 0.7%    |
| ECS H81H3-M4                       | 2        | 0.7%    |
| Dell Vostro 430                    | 2        | 0.7%    |
| Biostar H61MHV                     | 2        | 0.7%    |
| ASUS TUF B450M-PLUS GAMING         | 2        | 0.7%    |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.7%    |
| ASUS PRIME X570-P                  | 2        | 0.7%    |
| ASUS PRIME H410M-E                 | 2        | 0.7%    |
| ASUS PRIME H310M-E                 | 2        | 0.7%    |
| ASUS PRIME B450M-A II              | 2        | 0.7%    |
| ASRock Z77 Extreme4                | 2        | 0.7%    |
| ASRock H55M                        | 2        | 0.7%    |
| ASRock H110M-HDV R3.0              | 2        | 0.7%    |
| ASRock B450M-HDV R4.0              | 2        | 0.7%    |
| Supermicro X7DA8                   | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 18       | 6.32%   |
| HP Compaq                | 13       | 4.56%   |
| Lenovo ThinkCentre       | 9        | 3.16%   |
| Gigabyte B450M           | 8        | 2.81%   |
| Dell OptiPlex            | 8        | 2.81%   |
| ASUS TUF                 | 7        | 2.46%   |
| ASUS ROG                 | 7        | 2.46%   |
| Unknown                  | 7        | 2.46%   |
| HP ProDesk               | 6        | 2.11%   |
| ASUS All                 | 5        | 1.75%   |
| MSI MS-7817              | 4        | 1.4%    |
| MSI MS-7309              | 4        | 1.4%    |
| HP ProLiant              | 4        | 1.4%    |
| Gigabyte H81M-H          | 4        | 1.4%    |
| Gigabyte B550            | 4        | 1.4%    |
| Gigabyte X399            | 3        | 1.05%   |
| Gigabyte H61M-HD2        | 3        | 1.05%   |
| Gigabyte GA-78LMT-USB3   | 3        | 1.05%   |
| Gigabyte G31M-ES2C       | 3        | 1.05%   |
| ECS G31T-M7              | 3        | 1.05%   |
| Dell Vostro              | 3        | 1.05%   |
| ASUS M5A78L-M            | 3        | 1.05%   |
| ASRock Wolfdale1333-D667 | 3        | 1.05%   |
| ASRock G965M-S           | 3        | 1.05%   |
| ASRock G41M-VS3          | 3        | 1.05%   |
| MSI MS-7C37              | 2        | 0.7%    |
| Intel H61                | 2        | 0.7%    |
| Intel DH61CR             | 2        | 0.7%    |
| Intel DH55HC             | 2        | 0.7%    |
| Intel DG41RQ             | 2        | 0.7%    |
| Gigabyte H61M-S1         | 2        | 0.7%    |
| Gigabyte B550M           | 2        | 0.7%    |
| Gigabyte A520M           | 2        | 0.7%    |
| ECS H81H3-M4             | 2        | 0.7%    |
| Biostar H61MHV           | 2        | 0.7%    |
| ASUS SABERTOOTH          | 2        | 0.7%    |
| ASUS M4A87TD             | 2        | 0.7%    |
| ASRock Z77               | 2        | 0.7%    |
| ASRock H55M              | 2        | 0.7%    |
| ASRock H110M-HDV         | 2        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 32       | 11.23%  |
| 2010 | 31       | 10.88%  |
| 2018 | 26       | 9.12%   |
| 2013 | 26       | 9.12%   |
| 2020 | 23       | 8.07%   |
| 2011 | 20       | 7.02%   |
| 2019 | 16       | 5.61%   |
| 2017 | 16       | 5.61%   |
| 2009 | 15       | 5.26%   |
| 2008 | 15       | 5.26%   |
| 2007 | 11       | 3.86%   |
| 2021 | 10       | 3.51%   |
| 2014 | 10       | 3.51%   |
| 2006 | 10       | 3.51%   |
| 2015 | 9        | 3.16%   |
| 2016 | 7        | 2.46%   |
| 2022 | 3        | 1.05%   |
| 2023 | 2        | 0.7%    |
| 2005 | 2        | 0.7%    |
| 2003 | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 285      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 278      | 96.86%  |
| Enabled  | 9        | 3.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 285      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 64       | 22.3%   |
| 3.01-4.0    | 60       | 20.91%  |
| 4.01-8.0    | 55       | 19.16%  |
| 16.01-24.0  | 46       | 16.03%  |
| 32.01-64.0  | 28       | 9.76%   |
| 1.01-2.0    | 19       | 6.62%   |
| 24.01-32.0  | 5        | 1.74%   |
| 2.01-3.0    | 4        | 1.39%   |
| 64.01-256.0 | 4        | 1.39%   |
| 0.51-1.0    | 2        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 113      | 35.76%  |
| 2.01-3.0  | 76       | 24.05%  |
| 3.01-4.0  | 51       | 16.14%  |
| 4.01-8.0  | 43       | 13.61%  |
| 0.51-1.0  | 22       | 6.96%   |
| 8.01-16.0 | 9        | 2.85%   |
| 0.01-0.5  | 2        | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 49.15%  |
| 2      | 84       | 28.47%  |
| 3      | 42       | 14.24%  |
| 4      | 13       | 4.41%   |
| 5      | 6        | 2.03%   |
| 6      | 3        | 1.02%   |
| 8      | 1        | 0.34%   |
| 0      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 172      | 59.93%  |
| Yes       | 115      | 40.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 285      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 60.42%  |
| Yes       | 114      | 39.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 80.28%  |
| Yes       | 57       | 19.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Colombia | 285      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bogotá              | 111      | 37.76%  |
| Medellín            | 55       | 18.71%  |
| Santiago de Cali     | 22       | 7.48%   |
| Bucaramanga          | 15       | 5.1%    |
| Barranquilla         | 13       | 4.42%   |
| Pasto                | 7        | 2.38%   |
| Pereira              | 6        | 2.04%   |
| Valledupar           | 5        | 1.7%    |
| Ibague               | 5        | 1.7%    |
| Cúcuta              | 5        | 1.7%    |
| Armenia              | 4        | 1.36%   |
| Villavicencio        | 3        | 1.02%   |
| Tunja                | 3        | 1.02%   |
| Chia                 | 3        | 1.02%   |
| Soledad              | 2        | 0.68%   |
| Santa Marta          | 2        | 0.68%   |
| Palmira              | 2        | 0.68%   |
| Montería            | 2        | 0.68%   |
| Manizales            | 2        | 0.68%   |
| Calarcá             | 2        | 0.68%   |
| Bello                | 2        | 0.68%   |
| Zipacon              | 1        | 0.34%   |
| Villagarzon          | 1        | 0.34%   |
| Tuluá               | 1        | 0.34%   |
| Soacha               | 1        | 0.34%   |
| Rionegro             | 1        | 0.34%   |
| Puerto Carreño      | 1        | 0.34%   |
| Popayán             | 1        | 0.34%   |
| Ocaña               | 1        | 0.34%   |
| Mompos               | 1        | 0.34%   |
| La Loma              | 1        | 0.34%   |
| Jamundi              | 1        | 0.34%   |
| Ipiales              | 1        | 0.34%   |
| Guadalajara de Buga  | 1        | 0.34%   |
| Fusagasuga           | 1        | 0.34%   |
| Envigado             | 1        | 0.34%   |
| El Carmen de Bolivar | 1        | 0.34%   |
| Donmatias            | 1        | 0.34%   |
| Choachi              | 1        | 0.34%   |
| Cartagena            | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 93       | 130    | 19.14%  |
| Seagate                     | 73       | 110    | 15.02%  |
| Toshiba                     | 59       | 76     | 12.14%  |
| Hitachi                     | 46       | 57     | 9.47%   |
| Samsung Electronics         | 38       | 50     | 7.82%   |
| Kingston                    | 36       | 62     | 7.41%   |
| A-DATA Technology           | 21       | 27     | 4.32%   |
| Maxtor                      | 17       | 18     | 3.5%    |
| Crucial                     | 16       | 18     | 3.29%   |
| SanDisk                     | 12       | 14     | 2.47%   |
| HGST                        | 6        | 7      | 1.23%   |
| Unknown                     | 5        | 5      | 1.03%   |
| Phison                      | 5        | 9      | 1.03%   |
| Lexar                       | 5        | 5      | 1.03%   |
| XPG                         | 4        | 5      | 0.82%   |
| Team                        | 4        | 4      | 0.82%   |
| Gigabyte Technology         | 4        | 5      | 0.82%   |
| XrayDisk                    | 3        | 3      | 0.62%   |
| Realtek Semiconductor       | 3        | 3      | 0.62%   |
| PNY                         | 3        | 4      | 0.62%   |
| JMicron Technology          | 3        | 3      | 0.62%   |
| Corsair                     | 3        | 4      | 0.62%   |
| Transcend                   | 2        | 3      | 0.41%   |
| SK hynix                    | 2        | 3      | 0.41%   |
| Hewlett-Packard             | 2        | 2      | 0.41%   |
| Fujitsu                     | 2        | 2      | 0.41%   |
| Fanxiang                    | 2        | 2      | 0.41%   |
| China                       | 2        | 3      | 0.41%   |
| ADATA Technology            | 2        | 2      | 0.41%   |
| XSTAR                       | 1        | 1      | 0.21%   |
| SUPERSONIC                  | 1        | 1      | 0.21%   |
| Micron/Crucial Technology   | 1        | 2      | 0.21%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.21%   |
| KingSpec                    | 1        | 1      | 0.21%   |
| KingFast                    | 1        | 1      | 0.21%   |
| KingDian                    | 1        | 1      | 0.21%   |
| KINGBANK                    | 1        | 1      | 0.21%   |
| Intel                       | 1        | 1      | 0.21%   |
| ExcelStor                   | 1        | 1      | 0.21%   |
| DTECHCO                     | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 26       | 4.98%   |
| Kingston SA400S37240G 240GB SSD     | 11       | 2.11%   |
| Toshiba DT01ACA200 2TB              | 9        | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB      | 8        | 1.53%   |
| Kingston SA400S37120G 120GB SSD     | 8        | 1.53%   |
| Toshiba HDWD110 1TB                 | 7        | 1.34%   |
| Toshiba DT01ACA050 500GB            | 7        | 1.34%   |
| Kingston SV300S37A120G 120GB SSD    | 7        | 1.34%   |
| WDC WD10EZEX-08WN4A0 1TB            | 6        | 1.15%   |
| Hitachi HDS721050CLA362 500GB       | 6        | 1.15%   |
| Crucial CT240BX500SSD1 240GB        | 6        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB     | 5        | 0.96%   |
| Hitachi HDS721616PLA380 164GB       | 5        | 0.96%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 4        | 0.77%   |
| Lexar 128GB SSD                     | 4        | 0.77%   |
| Kingston SA400S37480G 480GB SSD     | 4        | 0.77%   |
| A-DATA SU650 120GB SSD              | 4        | 0.77%   |
| A-DATA SU630 240GB SSD              | 4        | 0.77%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 0.57%   |
| Unknown SD/MMC/MS PRO 16GB          | 3        | 0.57%   |
| Toshiba MQ01ABD100 1TB              | 3        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.57%   |
| Seagate ST3500413AS 500GB           | 3        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 0.57%   |
| Seagate ST1000DM003-1SB102 1TB      | 3        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.57%   |
| Samsung HD322HJ 320GB               | 3        | 0.57%   |
| Maxtor STM3160215AS 160GB           | 3        | 0.57%   |
| Crucial CT480BX500SSD1 480GB        | 3        | 0.57%   |
| A-DATA SU650 512GB SSD              | 3        | 0.57%   |
| XPG NVMe SSD Drive 1024GB           | 2        | 0.38%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD    | 2        | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.38%   |
| WDC WD800JD-75MSA3 80GB             | 2        | 0.38%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.38%   |
| WDC WD5000AVVS-63ZWB0 500GB         | 2        | 0.38%   |
| WDC WD5000AURX-63UY4Y0 500GB        | 2        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 80       | 106    | 26.23%  |
| Seagate             | 73       | 109    | 23.93%  |
| Toshiba             | 59       | 76     | 19.34%  |
| Hitachi             | 46       | 57     | 15.08%  |
| Samsung Electronics | 17       | 21     | 5.57%   |
| Maxtor              | 17       | 18     | 5.57%   |
| HGST                | 6        | 7      | 1.97%   |
| Unknown             | 3        | 3      | 0.98%   |
| Fujitsu             | 2        | 2      | 0.66%   |
| ExcelStor           | 1        | 1      | 0.33%   |
| Apple               | 1        | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 33       | 56     | 26.19%  |
| A-DATA Technology   | 19       | 25     | 15.08%  |
| WDC                 | 14       | 22     | 11.11%  |
| Crucial             | 14       | 16     | 11.11%  |
| Samsung Electronics | 9        | 10     | 7.14%   |
| SanDisk             | 6        | 8      | 4.76%   |
| Lexar               | 5        | 5      | 3.97%   |
| Team                | 3        | 3      | 2.38%   |
| Gigabyte Technology | 3        | 4      | 2.38%   |
| Transcend           | 2        | 3      | 1.59%   |
| SK hynix            | 2        | 3      | 1.59%   |
| PNY                 | 2        | 3      | 1.59%   |
| Corsair             | 2        | 3      | 1.59%   |
| China               | 2        | 3      | 1.59%   |
| XSTAR               | 1        | 1      | 0.79%   |
| XrayDisk            | 1        | 1      | 0.79%   |
| Unknown             | 1        | 1      | 0.79%   |
| Seagate             | 1        | 1      | 0.79%   |
| KingSpec            | 1        | 1      | 0.79%   |
| KingFast            | 1        | 1      | 0.79%   |
| KingDian            | 1        | 1      | 0.79%   |
| Hewlett-Packard     | 1        | 1      | 0.79%   |
| DTECHCO             | 1        | 1      | 0.79%   |
| Unknown             | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 222      | 401    | 56.92%  |
| SSD     | 112      | 174    | 28.72%  |
| NVMe    | 52       | 71     | 13.33%  |
| Unknown | 4        | 4      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 264      | 571    | 81.23%  |
| NVMe | 51       | 69     | 15.69%  |
| SAS  | 10       | 10     | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 195      | 328    | 54.78%  |
| 0.51-1.0   | 122      | 183    | 34.27%  |
| 1.01-2.0   | 26       | 36     | 7.3%    |
| 2.01-3.0   | 5        | 7      | 1.4%    |
| 4.01-10.0  | 5        | 9      | 1.4%    |
| 3.01-4.0   | 3        | 12     | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 69       | 22.48%  |
| 501-1000       | 58       | 18.89%  |
| 251-500        | 54       | 17.59%  |
| 1001-2000      | 34       | 11.07%  |
| 1-20           | 28       | 9.12%   |
| 51-100         | 26       | 8.47%   |
| More than 3000 | 12       | 3.91%   |
| 2001-3000      | 10       | 3.26%   |
| Unknown        | 9        | 2.93%   |
| 21-50          | 7        | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 117      | 36.91%  |
| 21-50          | 49       | 15.46%  |
| 101-250        | 43       | 13.56%  |
| 51-100         | 40       | 12.62%  |
| 251-500        | 21       | 6.62%   |
| 501-1000       | 19       | 5.99%   |
| 1001-2000      | 10       | 3.15%   |
| Unknown        | 9        | 2.84%   |
| More than 3000 | 6        | 1.89%   |
| 2001-3000      | 3        | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 2        | 2      | 2.67%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 2.67%   |
| Hitachi HDS721050CLA362 500GB         | 2        | 2      | 2.67%   |
| XrayDisk SSD 256GB                    | 1        | 1      | 1.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1        | 2      | 1.33%   |
| WDC WD800JD-75MSA3 80GB               | 1        | 1      | 1.33%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 1.33%   |
| WDC WD800BD-22MRA1 80GB               | 1        | 1      | 1.33%   |
| WDC WD6400AAKS-65Z7B0 640GB           | 1        | 1      | 1.33%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1        | 1      | 1.33%   |
| WDC WD5000AAKS-08V0A0 500GB           | 1        | 1      | 1.33%   |
| WDC WD3200AVJS-63B6A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAJS-65M0A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD20EZRX-00DC0B0 2TB              | 1        | 1      | 1.33%   |
| WDC WD2003FYPS-27W9B0 2TB             | 1        | 1      | 1.33%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 1      | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EALX-008EA0 1TB               | 1        | 2      | 1.33%   |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 1.33%   |
| WDC WD1001FAES-75W7A0 1TB             | 1        | 1      | 1.33%   |
| Toshiba MQ01ABD075 752GB              | 1        | 1      | 1.33%   |
| Toshiba HDWD110 1TB                   | 1        | 1      | 1.33%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.33%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.33%   |
| Toshiba DT01ABA200V 2TB               | 1        | 1      | 1.33%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 1.33%   |
| Seagate ST9500325AS 500GB             | 1        | 1      | 1.33%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 1.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 1.33%   |
| Seagate ST3320613AS 320GB             | 1        | 3      | 1.33%   |
| Seagate ST3320311CS 320GB             | 1        | 2      | 1.33%   |
| Seagate ST3250820AS 250GB             | 1        | 1      | 1.33%   |
| Seagate ST3120026AS 120GB             | 1        | 1      | 1.33%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.33%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 22     | 24.24%  |
| Seagate             | 15       | 23     | 22.73%  |
| Hitachi             | 13       | 15     | 19.7%   |
| Samsung Electronics | 6        | 6      | 9.09%   |
| Toshiba             | 5        | 5      | 7.58%   |
| Maxtor              | 4        | 4      | 6.06%   |
| XrayDisk            | 1        | 1      | 1.52%   |
| SK hynix            | 1        | 1      | 1.52%   |
| Kingston            | 1        | 1      | 1.52%   |
| HGST                | 1        | 1      | 1.52%   |
| Fujitsu             | 1        | 1      | 1.52%   |
| Crucial             | 1        | 1      | 1.52%   |
| A-DATA Technology   | 1        | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 20     | 25.86%  |
| Seagate             | 15       | 23     | 25.86%  |
| Hitachi             | 13       | 15     | 22.41%  |
| Toshiba             | 5        | 5      | 8.62%   |
| Samsung Electronics | 4        | 4      | 6.9%    |
| Maxtor              | 4        | 4      | 6.9%    |
| HGST                | 1        | 1      | 1.72%   |
| Fujitsu             | 1        | 1      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 51       | 73     | 86.44%  |
| SSD  | 6        | 7      | 10.17%  |
| NVMe | 2        | 2      | 3.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Maxtor STM380211AS 80GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| Maxtor | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 172      | 394    | 52.92%  |
| Works    | 93       | 173    | 28.62%  |
| Malfunc  | 59       | 82     | 18.15%  |
| Failed   | 1        | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 173      | 48.46%  |
| AMD                         | 94       | 26.33%  |
| Nvidia                      | 15       | 4.2%    |
| Samsung Electronics         | 14       | 3.92%   |
| ASMedia Technology          | 9        | 2.52%   |
| SanDisk                     | 8        | 2.24%   |
| Phison Electronics          | 7        | 1.96%   |
| Realtek Semiconductor       | 6        | 1.68%   |
| VIA Technologies            | 5        | 1.4%    |
| Kingston Technology Company | 5        | 1.4%    |
| ADATA Technology            | 5        | 1.4%    |
| MAXIO Technology (Hangzhou) | 3        | 0.84%   |
| JMicron Technology          | 3        | 0.84%   |
| Silicon Motion              | 2        | 0.56%   |
| Micron/Crucial Technology   | 2        | 0.56%   |
| Marvell Technology Group    | 2        | 0.56%   |
| INNOGRIT                    | 2        | 0.56%   |
| Micron Technology           | 1        | 0.28%   |
| Hewlett-Packard             | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 41       | 8.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 30       | 6.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 26       | 5.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 4.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 4.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 17       | 3.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14       | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14       | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.05%   |
| Nvidia MCP61 SATA Controller                                                            | 10       | 2.05%   |
| Nvidia MCP61 IDE                                                                        | 9        | 1.85%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 1.85%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.44%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.44%   |
| Phison E12 NVMe Controller                                                              | 5        | 1.03%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 0.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.82%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 0.62%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 3        | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 3        | 0.62%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 3        | 0.62%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.62%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3        | 0.62%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 193      | 52.88%  |
| IDE  | 105      | 28.77%  |
| NVMe | 51       | 13.97%  |
| RAID | 16       | 4.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 175      | 61.4%   |
| AMD    | 110      | 38.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 2.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 7        | 2.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6        | 2.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 2.09%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 6        | 2.09%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 2.09%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 1.74%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 1.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.74%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 1.74%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 4        | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.39%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 1.39%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 1.39%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 1.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.39%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 4        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.39%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.39%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.39%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.05%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.05%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 3        | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.05%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.05%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.05%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 1.05%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.05%   |
| AMD Phenom II X6 1100T Processor            | 3        | 1.05%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.05%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 3        | 1.05%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.7%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i5-3470T CPU @ 2.90GHz           | 2        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 46       | 16.03%  |
| AMD Ryzen 5             | 34       | 11.85%  |
| Intel Core i7           | 29       | 10.1%   |
| Intel Core i3           | 24       | 8.36%   |
| AMD FX                  | 15       | 5.23%   |
| AMD Ryzen 7             | 14       | 4.88%   |
| Intel Core 2 Duo        | 12       | 4.18%   |
| Intel Xeon              | 11       | 3.83%   |
| Intel Pentium Dual-Core | 11       | 3.83%   |
| Intel Celeron           | 10       | 3.48%   |
| Other                   | 7        | 2.44%   |
| Intel Pentium Dual      | 7        | 2.44%   |
| AMD Ryzen 3             | 7        | 2.44%   |
| Intel Pentium           | 6        | 2.09%   |
| Intel Core 2 Quad       | 5        | 1.74%   |
| AMD Phenom II X6        | 5        | 1.74%   |
| AMD Athlon II X2        | 5        | 1.74%   |
| AMD Athlon 64 X2        | 5        | 1.74%   |
| Intel Core 2            | 3        | 1.05%   |
| AMD Sempron             | 3        | 1.05%   |
| AMD Ryzen Threadripper  | 3        | 1.05%   |
| AMD Phenom              | 3        | 1.05%   |
| AMD Athlon              | 3        | 1.05%   |
| Intel Pentium D         | 2        | 0.7%    |
| Intel Pentium 4         | 2        | 0.7%    |
| AMD Ryzen 9             | 2        | 0.7%    |
| AMD Phenom II X4        | 2        | 0.7%    |
| AMD A8                  | 2        | 0.7%    |
| AMD A4                  | 2        | 0.7%    |
| Intel Core i9           | 1        | 0.35%   |
| Intel Celeron D         | 1        | 0.35%   |
| Intel Atom              | 1        | 0.35%   |
| AMD Athlon II X3        | 1        | 0.35%   |
| AMD Athlon 64           | 1        | 0.35%   |
| AMD A6                  | 1        | 0.35%   |
| AMD A10                 | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 98       | 34.39%  |
| 4      | 97       | 34.04%  |
| 6      | 45       | 15.79%  |
| 8      | 19       | 6.67%   |
| 1      | 10       | 3.51%   |
| 3      | 7        | 2.46%   |
| 12     | 4        | 1.4%    |
| 16     | 3        | 1.05%   |
| 14     | 1        | 0.35%   |
| 10     | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 281      | 98.6%   |
| 2      | 4        | 1.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 147      | 51.22%  |
| 1      | 140      | 48.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 281      | 98.6%   |
| Unknown        | 2        | 0.7%    |
| 64-bit         | 1        | 0.35%   |
| 32-bit         | 1        | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 20.27%  |
| 0x306c3    | 22       | 7.56%   |
| 0x206a7    | 18       | 6.19%   |
| 0x306a9    | 16       | 5.5%    |
| 0x1067a    | 14       | 4.81%   |
| 0x08701021 | 11       | 3.78%   |
| 0x08108109 | 11       | 3.78%   |
| 0x06000852 | 10       | 3.44%   |
| 0x6fd      | 9        | 3.09%   |
| 0x906e9    | 7        | 2.41%   |
| 0x506e3    | 6        | 2.06%   |
| 0x10676    | 6        | 2.06%   |
| 0xa0653    | 5        | 1.72%   |
| 0x0a50000c | 5        | 1.72%   |
| 0x010000dc | 5        | 1.72%   |
| 0x010000c8 | 5        | 1.72%   |
| 0x906ea    | 4        | 1.37%   |
| 0x0800820d | 4        | 1.37%   |
| 0xf65      | 3        | 1.03%   |
| 0xa0671    | 3        | 1.03%   |
| 0xa0655    | 3        | 1.03%   |
| 0x6fb      | 3        | 1.03%   |
| 0x20655    | 3        | 1.03%   |
| 0x20652    | 3        | 1.03%   |
| 0x106e5    | 3        | 1.03%   |
| 0x08001138 | 3        | 1.03%   |
| 0x6f6      | 2        | 0.69%   |
| 0x0a50000d | 2        | 0.69%   |
| 0x0a20120a | 2        | 0.69%   |
| 0x08701013 | 2        | 0.69%   |
| 0x08001137 | 2        | 0.69%   |
| 0x06001119 | 2        | 0.69%   |
| 0x06000822 | 2        | 0.69%   |
| 0x03000027 | 2        | 0.69%   |
| 0x01000083 | 2        | 0.69%   |
| 0xf64      | 1        | 0.34%   |
| 0xf49      | 1        | 0.34%   |
| 0xf27      | 1        | 0.34%   |
| 0x906ed    | 1        | 0.34%   |
| 0x906eb    | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 27       | 9.44%   |
| Penryn           | 24       | 8.39%   |
| IvyBridge        | 24       | 8.39%   |
| SandyBridge      | 23       | 8.04%   |
| Zen+             | 18       | 6.29%   |
| Zen 2            | 18       | 6.29%   |
| K10              | 18       | 6.29%   |
| Core             | 17       | 5.94%   |
| Piledriver       | 16       | 5.59%   |
| KabyLake         | 16       | 5.59%   |
| Zen 3            | 15       | 5.24%   |
| K8 Hammer        | 10       | 3.5%    |
| CometLake        | 9        | 3.15%   |
| Zen              | 8        | 2.8%    |
| Westmere         | 8        | 2.8%    |
| Skylake          | 7        | 2.45%   |
| NetBurst         | 7        | 2.45%   |
| Nehalem          | 4        | 1.4%    |
| Icelake          | 3        | 1.05%   |
| K10 Llano        | 2        | 0.7%    |
| Bulldozer        | 2        | 0.7%    |
| Broadwell        | 2        | 0.7%    |
| Unknown          | 2        | 0.7%    |
| TigerLake        | 1        | 0.35%   |
| Steamroller      | 1        | 0.35%   |
| Jaguar           | 1        | 0.35%   |
| Goldmont plus    | 1        | 0.35%   |
| Bonnell          | 1        | 0.35%   |
| Alderlake Hybrid | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 108      | 35.76%  |
| AMD                        | 98       | 32.45%  |
| Nvidia                     | 90       | 29.8%   |
| Matrox Electronics Systems | 4        | 1.32%   |
| VIA Technologies           | 2        | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 4.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 3.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 3.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 12       | 3.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 3.58%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 9        | 2.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 2.61%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.28%   |
| Intel HD Graphics 530                                                       | 6        | 1.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.95%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 1.95%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 1.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.63%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 4        | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.3%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 4        | 1.3%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.3%    |
| Intel HD Graphics 630                                                       | 4        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                         | 4        | 1.3%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 4        | 1.3%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.98%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.98%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 0.98%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 0.98%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 0.98%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 0.98%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 100      | 34.48%  |
| 1 x AMD         | 90       | 31.03%  |
| 1 x Nvidia      | 85       | 29.31%  |
| 2 x AMD         | 4        | 1.38%   |
| 1 x Matrox      | 3        | 1.03%   |
| 1 x VIA         | 2        | 0.69%   |
| Intel + Nvidia  | 2        | 0.69%   |
| Intel + AMD     | 2        | 0.69%   |
| Nvidia + Matrox | 1        | 0.34%   |
| AMD + Nvidia    | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 236      | 81.94%  |
| Proprietary | 40       | 13.89%  |
| Unknown     | 12       | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 130      | 44.67%  |
| 1.01-2.0   | 45       | 15.46%  |
| 0.51-1.0   | 37       | 12.71%  |
| 0.01-0.5   | 36       | 12.37%  |
| 3.01-4.0   | 14       | 4.81%   |
| 7.01-8.0   | 12       | 4.12%   |
| 5.01-6.0   | 8        | 2.75%   |
| 8.01-16.0  | 5        | 1.72%   |
| 2.01-3.0   | 4        | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 77       | 29.17%  |
| Goldstar             | 50       | 18.94%  |
| Hewlett-Packard      | 35       | 13.26%  |
| Dell                 | 20       | 7.58%   |
| Acer                 | 14       | 5.3%    |
| AOC                  | 10       | 3.79%   |
| ViewSonic            | 5        | 1.89%   |
| LG Electronics       | 5        | 1.89%   |
| Lenovo               | 4        | 1.52%   |
| ASUSTek Computer     | 4        | 1.52%   |
| Unknown              | 3        | 1.14%   |
| Sceptre Tech         | 3        | 1.14%   |
| SANYO                | 3        | 1.14%   |
| SAC                  | 3        | 1.14%   |
| RTK                  | 3        | 1.14%   |
| MSI                  | 3        | 1.14%   |
| Ancor Communications | 3        | 1.14%   |
| NCS                  | 2        | 0.76%   |
| Envision             | 2        | 0.76%   |
| BenQ                 | 2        | 0.76%   |
| Westinghouse         | 1        | 0.38%   |
| Unknown (XXX)        | 1        | 0.38%   |
| SMC                  | 1        | 0.38%   |
| SKG                  | 1        | 0.38%   |
| PEGA                 | 1        | 0.38%   |
| MStar                | 1        | 0.38%   |
| KOA                  | 1        | 0.38%   |
| HKC                  | 1        | 0.38%   |
| HannStar             | 1        | 0.38%   |
| Estecom              | 1        | 0.38%   |
| DENON                | 1        | 0.38%   |
| CVT                  | 1        | 0.38%   |
| AGO                  | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 5        | 1.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 1.83%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 1.47%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 4        | 1.47%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 4        | 1.47%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                 | 4        | 1.47%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 4        | 1.47%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 1.1%    |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 3        | 1.1%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3        | 1.1%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.1%    |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 3        | 1.1%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 1.1%    |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 3        | 1.1%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.73%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                    | 2        | 0.73%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2        | 0.73%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.73%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 2        | 0.73%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 2        | 0.73%   |
| RTK Verbatim M14 RTK0001 1920x1080 300x190mm 14.0-inch                | 2        | 0.73%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 2        | 0.73%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 2        | 0.73%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                 | 2        | 0.73%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 2        | 0.73%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 2        | 0.73%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.73%   |
| Goldstar ULTRAWIDE GSM5BF8 2560x1080 673x284mm 28.8-inch              | 2        | 0.73%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 2        | 0.73%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 2        | 0.73%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 2        | 0.73%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 2        | 0.73%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                      | 2        | 0.73%   |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                    | 2        | 0.73%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 2        | 0.73%   |
| Acer AL1716 ACRAD51 1280x1024 340x270mm 17.1-inch                     | 2        | 0.73%   |
| Westinghouse WDE LCM-17v2 WDE1702 1280x1024 338x270mm 17.0-inch       | 1        | 0.37%   |
| ViewSonic VX2768-PC-mhd VSC083A 1920x1080 598x336mm 27.0-inch         | 1        | 0.37%   |
| ViewSonic VX2739 Series VSC3F24 1920x1080 598x336mm 27.0-inch         | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 89       | 34.1%   |
| 1366x768 (WXGA)    | 40       | 15.33%  |
| 1600x900 (HD+)     | 23       | 8.81%   |
| 1440x900 (WXGA+)   | 23       | 8.81%   |
| 1280x1024 (SXGA)   | 22       | 8.43%   |
| 3840x2160 (4K)     | 14       | 5.36%   |
| 1360x768           | 10       | 3.83%   |
| 2560x1440 (QHD)    | 9        | 3.45%   |
| 1680x1050 (WSXGA+) | 9        | 3.45%   |
| 2560x1080          | 5        | 1.92%   |
| 1920x1200 (WUXGA)  | 3        | 1.15%   |
| 1024x768 (XGA)     | 3        | 1.15%   |
| Unknown            | 3        | 1.15%   |
| 3840x1080          | 2        | 0.77%   |
| 1280x720 (HD)      | 2        | 0.77%   |
| 3440x1440          | 1        | 0.38%   |
| 3200x1080          | 1        | 0.38%   |
| 1920x540           | 1        | 0.38%   |
| 1152x864           | 1        | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 42       | 15.91%  |
| 21      | 39       | 14.77%  |
| 19      | 38       | 14.39%  |
| 23      | 24       | 9.09%   |
| 20      | 17       | 6.44%   |
| Unknown | 17       | 6.44%   |
| 17      | 15       | 5.68%   |
| 27      | 13       | 4.92%   |
| 24      | 11       | 4.17%   |
| 31      | 10       | 3.79%   |
| 22      | 8        | 3.03%   |
| 15      | 5        | 1.89%   |
| 72      | 3        | 1.14%   |
| 54      | 3        | 1.14%   |
| 34      | 3        | 1.14%   |
| 28      | 3        | 1.14%   |
| 84      | 2        | 0.76%   |
| 48      | 2        | 0.76%   |
| 12      | 2        | 0.76%   |
| 60      | 1        | 0.38%   |
| 52      | 1        | 0.38%   |
| 46      | 1        | 0.38%   |
| 40      | 1        | 0.38%   |
| 32      | 1        | 0.38%   |
| 16      | 1        | 0.38%   |
| 13      | 1        | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 137      | 52.9%   |
| 501-600     | 42       | 16.22%  |
| 301-350     | 18       | 6.95%   |
| Unknown     | 17       | 6.56%   |
| 601-700     | 15       | 5.79%   |
| 351-400     | 9        | 3.47%   |
| 1001-1500   | 8        | 3.09%   |
| 1501-2000   | 5        | 1.93%   |
| 701-800     | 4        | 1.54%   |
| 201-300     | 3        | 1.16%   |
| 801-900     | 1        | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 171      | 67.59%  |
| 16/10   | 33       | 13.04%  |
| 5/4     | 19       | 7.51%   |
| Unknown | 16       | 6.32%   |
| 4/3     | 6        | 2.37%   |
| 21/9    | 6        | 2.37%   |
| 32/9    | 2        | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 26.72%  |
| 151-200        | 64       | 24.43%  |
| 141-150        | 52       | 19.85%  |
| Unknown        | 17       | 6.49%   |
| 351-500        | 14       | 5.34%   |
| 301-350        | 13       | 4.96%   |
| More than 1000 | 11       | 4.2%    |
| 251-300        | 7        | 2.67%   |
| 101-110        | 3        | 1.15%   |
| 501-1000       | 3        | 1.15%   |
| 71-80          | 2        | 0.76%   |
| 131-140        | 2        | 0.76%   |
| 111-120        | 2        | 0.76%   |
| 81-90          | 1        | 0.38%   |
| 121-130        | 1        | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 166      | 65.35%  |
| 101-120 | 49       | 19.29%  |
| Unknown | 17       | 6.69%   |
| 1-50    | 14       | 5.51%   |
| 121-160 | 5        | 1.97%   |
| 161-240 | 3        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 246      | 85.42%  |
| 2     | 22       | 7.64%   |
| 0     | 16       | 5.56%   |
| 3     | 4        | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 186      | 46.73%  |
| Intel                             | 65       | 16.33%  |
| Qualcomm Atheros                  | 34       | 8.54%   |
| Ralink Technology                 | 23       | 5.78%   |
| Broadcom                          | 15       | 3.77%   |
| TP-Link                           | 13       | 3.27%   |
| Nvidia                            | 12       | 3.02%   |
| Broadcom Limited                  | 6        | 1.51%   |
| Ralink                            | 5        | 1.26%   |
| Qualcomm Atheros Communications   | 5        | 1.26%   |
| Marvell Technology Group          | 4        | 1.01%   |
| Xiaomi                            | 3        | 0.75%   |
| Samsung Electronics               | 3        | 0.75%   |
| Mercucys                          | 3        | 0.75%   |
| MediaTek                          | 3        | 0.75%   |
| VIA Technologies                  | 2        | 0.5%    |
| Sundance Technology Inc / IC Plus | 2        | 0.5%    |
| Motorola PCS                      | 2        | 0.5%    |
| ICS Advent                        | 2        | 0.5%    |
| D-Link System                     | 2        | 0.5%    |
| Wistron NeWeb                     | 1        | 0.25%   |
| Qualcomm                          | 1        | 0.25%   |
| OPPO Electronics                  | 1        | 0.25%   |
| Mellanox Technologies             | 1        | 0.25%   |
| LG Electronics                    | 1        | 0.25%   |
| Huawei Technologies               | 1        | 0.25%   |
| Encore Electronics                | 1        | 0.25%   |
| Aquantia                          | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 137      | 32.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 19       | 4.44%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 2.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 10       | 2.34%   |
| Ralink MT7601U Wireless Adapter                                            | 9        | 2.1%    |
| Nvidia MCP61 Ethernet                                                      | 9        | 2.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8        | 1.87%   |
| Intel I211 Gigabit Network Connection                                      | 8        | 1.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 6        | 1.4%    |
| Intel Wi-Fi 6 AX200                                                        | 6        | 1.4%    |
| Intel Ethernet Controller I225-V                                           | 6        | 1.4%    |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 1.4%    |
| Qualcomm Atheros AR9271 802.11n                                            | 5        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 5        | 1.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4        | 0.93%   |
| TP-Link 802.11 NIC                                                         | 4        | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 4        | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 0.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 3        | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 3        | 0.7%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                  | 3        | 0.7%    |
| Ralink RT5370 Wireless Adapter                                             | 3        | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 3        | 0.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 3        | 0.7%    |
| Mercucys 802.11n NIC                                                       | 3        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 0.7%    |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2        | 0.47%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 2        | 0.47%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 2        | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2        | 0.47%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                       | 2        | 0.47%   |
| Realtek 802.11ac NIC                                                       | 2        | 0.47%   |
| Ralink RT2561/RT61 rev B 802.11g                                           | 2        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.47%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 22.95%  |
| Ralink Technology               | 23       | 18.85%  |
| Intel                           | 21       | 17.21%  |
| Qualcomm Atheros                | 15       | 12.3%   |
| TP-Link                         | 13       | 10.66%  |
| Ralink                          | 5        | 4.1%    |
| Qualcomm Atheros Communications | 5        | 4.1%    |
| Mercucys                        | 3        | 2.46%   |
| MediaTek                        | 3        | 2.46%   |
| Wistron NeWeb                   | 1        | 0.82%   |
| LG Electronics                  | 1        | 0.82%   |
| Encore Electronics              | 1        | 0.82%   |
| D-Link System                   | 1        | 0.82%   |
| Broadcom Limited                | 1        | 0.82%   |
| Broadcom                        | 1        | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink RT2870/RT3070 Wireless Adapter                          | 10       | 8.2%    |
| Ralink MT7601U Wireless Adapter                                | 9        | 7.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6        | 4.92%   |
| Intel Wi-Fi 6 AX200                                            | 6        | 4.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 5        | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5        | 4.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 3.28%   |
| TP-Link 802.11 NIC                                             | 4        | 3.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 3        | 2.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3        | 2.46%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 3        | 2.46%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 2.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3        | 2.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 2.46%   |
| Mercucys 802.11n NIC                                           | 3        | 2.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 2.46%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 2        | 1.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.64%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter           | 2        | 1.64%   |
| Realtek 802.11ac NIC                                           | 2        | 1.64%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2        | 1.64%   |
| Intel Wireless 7265                                            | 2        | 1.64%   |
| Intel Centrino Wireless-N 2230                                 | 2        | 1.64%   |
| Wistron NeWeb AR9170+AR9104 802.11abgn Wireless Adapter        | 1        | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.82%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                        | 1        | 0.82%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 0.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 0.82%   |
| Ralink RT3072 Wireless Adapter                                 | 1        | 0.82%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.82%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 0.82%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 1        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 173      | 57.48%  |
| Intel                             | 55       | 18.27%  |
| Qualcomm Atheros                  | 19       | 6.31%   |
| Broadcom                          | 14       | 4.65%   |
| Nvidia                            | 12       | 3.99%   |
| Broadcom Limited                  | 5        | 1.66%   |
| Marvell Technology Group          | 4        | 1.33%   |
| Xiaomi                            | 3        | 1%      |
| Samsung Electronics               | 3        | 1%      |
| VIA Technologies                  | 2        | 0.66%   |
| Sundance Technology Inc / IC Plus | 2        | 0.66%   |
| ICS Advent                        | 2        | 0.66%   |
| Qualcomm                          | 1        | 0.33%   |
| OPPO Electronics                  | 1        | 0.33%   |
| Motorola PCS                      | 1        | 0.33%   |
| Mellanox Technologies             | 1        | 0.33%   |
| Huawei Technologies               | 1        | 0.33%   |
| D-Link System                     | 1        | 0.33%   |
| Aquantia                          | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 137      | 44.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 19       | 6.23%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 3.93%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 2.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8        | 2.62%   |
| Intel I211 Gigabit Network Connection                                      | 8        | 2.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 2.3%    |
| Intel Ethernet Controller I225-V                                           | 6        | 1.97%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 1.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 4        | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 0.98%   |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.98%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2        | 0.66%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 2        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.66%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.66%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.66%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.66%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 0.66%   |
| Intel Ethernet Connection (12) I219-V                                      | 2        | 0.66%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.66%   |
| Intel 82566DM Gigabit Network Connection                                   | 2        | 0.66%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 2        | 0.66%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.66%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                           | 2        | 0.66%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.66%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                    | 2        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.33%   |
| Qualcomm Redmi Note 8                                                      | 1        | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 285      | 71.43%  |
| WiFi     | 113      | 28.32%  |
| Unknown  | 1        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 229      | 78.97%  |
| WiFi     | 61       | 21.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 213      | 74.48%  |
| 2     | 67       | 23.43%  |
| 3     | 3        | 1.05%   |
| 0     | 2        | 0.7%    |
| 7     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 252      | 86.6%   |
| Yes  | 39       | 13.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 29       | 50.88%  |
| Intel                   | 20       | 35.09%  |
| MediaTek                | 2        | 3.51%   |
| IMC Networks            | 2        | 3.51%   |
| Realtek Semiconductor   | 1        | 1.75%   |
| Dell                    | 1        | 1.75%   |
| Broadcom                | 1        | 1.75%   |
| Apple                   | 1        | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29       | 50.88%  |
| Intel AX200 Bluetooth                               | 6        | 10.53%  |
| Intel Bluetooth wireless interface                  | 4        | 7.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3        | 5.26%   |
| MediaTek Wireless_Device                            | 2        | 3.51%   |
| Intel AX201 Bluetooth                               | 2        | 3.51%   |
| Realtek Bluetooth Radio                             | 1        | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.75%   |
| Intel AX210 Bluetooth                               | 1        | 1.75%   |
| IMC Networks Wireless_Device                        | 1        | 1.75%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.75%   |
| Dell Wireless 365 Bluetooth                         | 1        | 1.75%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.75%   |
| Apple Bluetooth HCI                                 | 1        | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 168      | 38.36%  |
| AMD                                  | 128      | 29.22%  |
| Nvidia                               | 89       | 20.32%  |
| C-Media Electronics                  | 10       | 2.28%   |
| Generalplus Technology               | 5        | 1.14%   |
| VIA Technologies                     | 4        | 0.91%   |
| Logitech                             | 4        | 0.91%   |
| Creative Labs                        | 4        | 0.91%   |
| M-Audio                              | 3        | 0.68%   |
| JMTek                                | 3        | 0.68%   |
| Texas Instruments                    | 2        | 0.46%   |
| Kingston Technology                  | 2        | 0.46%   |
| Blue Microphones                     | 2        | 0.46%   |
| Turtle Beach                         | 1        | 0.23%   |
| Trust                                | 1        | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.23%   |
| SteelSeries ApS                      | 1        | 0.23%   |
| Realtek Semiconductor                | 1        | 0.23%   |
| Razer USA                            | 1        | 0.23%   |
| HiBy                                 | 1        | 0.23%   |
| GN Netcom                            | 1        | 0.23%   |
| Giga-Byte Technology                 | 1        | 0.23%   |
| Earth Computer Technologies          | 1        | 0.23%   |
| Drop                                 | 1        | 0.23%   |
| Creative Technology                  | 1        | 0.23%   |
| Corsair                              | 1        | 0.23%   |
| Avid Technology                      | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 37       | 7.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 30       | 5.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 5.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 25       | 4.85%   |
| AMD Starship/Matisse HD Audio Controller                                          | 24       | 4.66%   |
| AMD Family 17h/19h HD Audio Controller                                            | 24       | 4.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12       | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 12       | 2.33%   |
| Nvidia High Definition Audio Controller                                           | 11       | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11       | 2.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11       | 2.14%   |
| Nvidia MCP61 High Definition Audio                                                | 10       | 1.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 1.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 8        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 7        | 1.36%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 1.36%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.17%   |
| Intel Comet Lake PCH-V cAVS                                                       | 6        | 1.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 1.17%   |
| AMD Navi 10 HDMI Audio                                                            | 6        | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 0.97%   |
| Generalplus Technology USB Audio Device                                           | 5        | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 5        | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 0.78%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 0.78%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.58%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 33       | 18.64%  |
| Corsair             | 20       | 11.3%   |
| Samsung Electronics | 19       | 10.73%  |
| A-DATA Technology   | 17       | 9.6%    |
| Kingston            | 15       | 8.47%   |
| SK hynix            | 10       | 5.65%   |
| Crucial             | 10       | 5.65%   |
| Micron Technology   | 6        | 3.39%   |
| G.Skill             | 6        | 3.39%   |
| Team                | 5        | 2.82%   |
| Super Talent        | 5        | 2.82%   |
| GeIL                | 4        | 2.26%   |
| Ramaxel Technology  | 3        | 1.69%   |
| Patriot             | 3        | 1.69%   |
| PNY                 | 2        | 1.13%   |
| Nanya Technology    | 2        | 1.13%   |
| Kreton              | 2        | 1.13%   |
| Hewlett-Packard     | 2        | 1.13%   |
| Avant               | 2        | 1.13%   |
| Unknown (AD8A)      | 1        | 0.56%   |
| Transcend           | 1        | 0.56%   |
| Sesame              | 1        | 0.56%   |
| PUSKILL             | 1        | 0.56%   |
| Kllisre             | 1        | 0.56%   |
| Golden Empire       | 1        | 0.56%   |
| Elpida              | 1        | 0.56%   |
| CSX                 | 1        | 0.56%   |
| Atermiter           | 1        | 0.56%   |
| Apacer              | 1        | 0.56%   |
| Unknown             | 1        | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s  | 5        | 2.54%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 4        | 2.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 4        | 2.03%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s     | 3        | 1.52%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s   | 3        | 1.52%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.52%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 3        | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.02%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 1.02%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 2        | 1.02%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 2        | 1.02%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 1.02%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s         | 2        | 1.02%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 1.02%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s    | 2        | 1.02%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s     | 2        | 1.02%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 2        | 1.02%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s | 2        | 1.02%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s  | 2        | 1.02%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 1.02%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s            | 2        | 1.02%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s           | 2        | 1.02%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s        | 2        | 1.02%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s              | 1        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 0.51%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 1        | 0.51%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.51%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.51%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.51%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 1        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 200MT/s               | 1        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                | 1        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 58       | 40.85%  |
| DDR3    | 48       | 33.8%   |
| SDRAM   | 14       | 9.86%   |
| DDR2    | 10       | 7.04%   |
| Unknown | 6        | 4.23%   |
| DDR     | 4        | 2.82%   |
| LPDDR4  | 1        | 0.7%    |
| DRAM    | 1        | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 131      | 94.24%  |
| SODIMM       | 7        | 5.04%   |
| Row Of Chips | 1        | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 54       | 32.93%  |
| 4096  | 37       | 22.56%  |
| 2048  | 34       | 20.73%  |
| 16384 | 22       | 13.41%  |
| 32768 | 9        | 5.49%   |
| 1024  | 7        | 4.27%   |
| 512   | 1        | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 33       | 20.37%  |
| 1333    | 23       | 14.2%   |
| 3600    | 15       | 9.26%   |
| 3200    | 12       | 7.41%   |
| 2133    | 9        | 5.56%   |
| Unknown | 9        | 5.56%   |
| 2400    | 8        | 4.94%   |
| 3000    | 6        | 3.7%    |
| 800     | 6        | 3.7%    |
| 2667    | 4        | 2.47%   |
| 1867    | 4        | 2.47%   |
| 3800    | 3        | 1.85%   |
| 667     | 3        | 1.85%   |
| 3733    | 2        | 1.23%   |
| 3400    | 2        | 1.23%   |
| 3266    | 2        | 1.23%   |
| 2666    | 2        | 1.23%   |
| 1866    | 2        | 1.23%   |
| 1800    | 2        | 1.23%   |
| 1334    | 2        | 1.23%   |
| 400     | 2        | 1.23%   |
| 333     | 2        | 1.23%   |
| 3500    | 1        | 0.62%   |
| 3100    | 1        | 0.62%   |
| 3066    | 1        | 0.62%   |
| 2800    | 1        | 0.62%   |
| 2176    | 1        | 0.62%   |
| 1400    | 1        | 0.62%   |
| 1066    | 1        | 0.62%   |
| 533     | 1        | 0.62%   |
| 200     | 1        | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 26.67%  |
| Seiko Epson         | 3        | 20%     |
| Samsung Electronics | 2        | 13.33%  |
| Ricoh               | 1        | 6.67%   |
| Prolific Technology | 1        | 6.67%   |
| Philips (or NXP)    | 1        | 6.67%   |
| Canon               | 1        | 6.67%   |
| Brother Industries  | 1        | 6.67%   |
| BESTEASY            | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Seiko Epson L120 Series                                | 2        | 13.33%  |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1        | 6.67%   |
| Samsung ML-2010P Mono Laser Printer                    | 1        | 6.67%   |
| Samsung Composite Device                               | 1        | 6.67%   |
| Ricoh Printing Support                                 | 1        | 6.67%   |
| Prolific PL2305 Parallel Port                          | 1        | 6.67%   |
| Philips (or NXP) USB Printer                           | 1        | 6.67%   |
| HP LaserJet CP 1025nw                                  | 1        | 6.67%   |
| HP LaserJet 1020                                       | 1        | 6.67%   |
| HP Laser 107a                                          | 1        | 6.67%   |
| HP Deskjet 2540 series                                 | 1        | 6.67%   |
| Canon G3000 series                                     | 1        | 6.67%   |
| Brother DCP-T710W                                      | 1        | 6.67%   |
| BESTEASY BE-G42S                                       | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 14       | 23.33%  |
| KYE Systems (Mouse Systems) | 8        | 13.33%  |
| Microdia                    | 6        | 10%     |
| Microsoft                   | 4        | 6.67%   |
| Cubeternet                  | 4        | 6.67%   |
| Chicony Electronics         | 4        | 6.67%   |
| Generalplus Technology      | 3        | 5%      |
| Huawei Technologies         | 2        | 3.33%   |
| GEMBIRD                     | 2        | 3.33%   |
| Arkmicro Technologies       | 2        | 3.33%   |
| WaveRider Communications    | 1        | 1.67%   |
| Unknown                     | 1        | 1.67%   |
| Trust                       | 1        | 1.67%   |
| Samsung Electronics         | 1        | 1.67%   |
| Realtek Semiconductor       | 1        | 1.67%   |
| Pixart Imaging              | 1        | 1.67%   |
| OmniVision Technologies     | 1        | 1.67%   |
| Hewlett-Packard             | 1        | 1.67%   |
| HD 2MP WEBCAM               | 1        | 1.67%   |
| Bison Electronics           | 1        | 1.67%   |
| Unknown                     | 1        | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                                             | 4        | 6.67%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                           | 3        | 5%      |
| Generalplus GENERAL WEBCAM                                          | 3        | 5%      |
| Cubeternet GL-UPC822 UVC WebCam                                     | 3        | 5%      |
| Chicony HP High Definition 1MP Webcam                               | 3        | 5%      |
| Microdia USB 2.0 Camera                                             | 2        | 3.33%   |
| Microdia Integrated Camera                                          | 2        | 3.33%   |
| Logitech Webcam C930e                                               | 2        | 3.33%   |
| Logitech Webcam C170                                                | 2        | 3.33%   |
| Logitech HD Pro Webcam C920                                         | 2        | 3.33%   |
| Huawei UVC Camera                                                   | 2        | 3.33%   |
| GEMBIRD USB2.0 PC CAMERA                                            | 2        | 3.33%   |
| WaveRider USB 2.0 Camera                                            | 1        | 1.67%   |
| Unknown HD camera                                                   | 1        | 1.67%   |
| Trust Full HD Webcam                                                | 1        | 1.67%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 1.67%   |
| Realtek NexiGo N660P FHD Webcam                                     | 1        | 1.67%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 1        | 1.67%   |
| OmniVision Monitor Webcam                                           | 1        | 1.67%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 1.67%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                 | 1        | 1.67%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.67%   |
| Microsoft LifeCam Cinema                                            | 1        | 1.67%   |
| Microdia Webcam Vitade AF                                           | 1        | 1.67%   |
| Microdia Sonix USB 2.0 Camera                                       | 1        | 1.67%   |
| Logitech Webcam C270                                                | 1        | 1.67%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 1.67%   |
| Logitech C505 HD Webcam                                             | 1        | 1.67%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.67%   |
| KYE Systems (Mouse Systems) Genius iLook 1321 V2                    | 1        | 1.67%   |
| KYE Systems (Mouse Systems) FaceCam 320X                            | 1        | 1.67%   |
| KYE Systems (Mouse Systems) FaceCam 310                             | 1        | 1.67%   |
| KYE Systems (Mouse Systems) FaceCam 2020                            | 1        | 1.67%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 1.67%   |
| HP Webcam HD-2200                                                   | 1        | 1.67%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                                         | 1        | 1.67%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.67%   |
| Chicony HP WebCam                                                   | 1        | 1.67%   |
| Bison Integrated Camera                                             | 1        | 1.67%   |
| Arkmicro Webcam Carrefour                                           | 1        | 1.67%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 244      | 84.72%  |
| 1     | 40       | 13.89%  |
| 2     | 3        | 1.04%   |
| 4     | 1        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 18       | 36.73%  |
| Graphics card            | 18       | 36.73%  |
| Communication controller | 4        | 8.16%   |
| Storage/raid             | 2        | 4.08%   |
| Multimedia controller    | 2        | 4.08%   |
| Unassigned class         | 1        | 2.04%   |
| Sound                    | 1        | 2.04%   |
| Network                  | 1        | 2.04%   |
| Card reader              | 1        | 2.04%   |
| Camera                   | 1        | 2.04%   |

