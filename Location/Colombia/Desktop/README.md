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

Total: 406

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 33       | 11.22%  |
| Ubuntu 18.04        | 30       | 10.2%   |
| Ubuntu 22.04        | 14       | 4.76%   |
| OpenMandriva 4.3    | 14       | 4.76%   |
| Fedora 38           | 9        | 3.06%   |
| Linux Mint 20.3     | 8        | 2.72%   |
| Linux Mint 20.2     | 8        | 2.72%   |
| KDE neon 20.04      | 7        | 2.38%   |
| Zorin 15            | 6        | 2.04%   |
| OpenMandriva 4.2    | 6        | 2.04%   |
| Fedora 37           | 6        | 2.04%   |
| ArcoLinux Rolling   | 6        | 2.04%   |
| Arch Rolling        | 6        | 2.04%   |
| Linux Mint 19.3     | 5        | 1.7%    |
| Fedora 35           | 5        | 1.7%    |
| Debian 11           | 5        | 1.7%    |
| Zorin 16            | 4        | 1.36%   |
| Xubuntu 20.04       | 4        | 1.36%   |
| Manjaro             | 4        | 1.36%   |
| KDE neon 22.04      | 4        | 1.36%   |
| Fedora 36           | 4        | 1.36%   |
| Zorin 12            | 3        | 1.02%   |
| Ubuntu 19.04        | 3        | 1.02%   |
| ROSA R11            | 3        | 1.02%   |
| ROSA 12.2           | 3        | 1.02%   |
| OpenMandriva 23.03  | 3        | 1.02%   |
| OpenMandriva 23.01  | 3        | 1.02%   |
| Nobara 36           | 3        | 1.02%   |
| Linux Mint 21.1     | 3        | 1.02%   |
| Kubuntu 20.04       | 3        | 1.02%   |
| Fedora 32           | 3        | 1.02%   |
| Elementary 6.1      | 3        | 1.02%   |
| Arch                | 3        | 1.02%   |
| Xubuntu 22.04       | 2        | 0.68%   |
| Ubuntu Unity 16.04  | 2        | 0.68%   |
| Ubuntu Budgie 20.04 | 2        | 0.68%   |
| Ubuntu 19.10        | 2        | 0.68%   |
| ROSA R10            | 2        | 0.68%   |
| ROSA 12.4           | 2        | 0.68%   |
| OpenMandriva 4.50   | 2        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 83       | 29.75%  |
| Linux Mint    | 29       | 10.39%  |
| OpenMandriva  | 28       | 10.04%  |
| Fedora        | 28       | 10.04%  |
| Zorin         | 13       | 4.66%   |
| KDE neon      | 12       | 4.3%    |
| ROSA          | 10       | 3.58%   |
| Arch          | 9        | 3.23%   |
| Xubuntu       | 7        | 2.51%   |
| Manjaro       | 7        | 2.51%   |
| Debian        | 7        | 2.51%   |
| ArcoLinux     | 6        | 2.15%   |
| Kubuntu       | 5        | 1.79%   |
| Elementary    | 4        | 1.43%   |
| Ubuntu Unity  | 3        | 1.08%   |
| Pop!_OS       | 3        | 1.08%   |
| openSUSE      | 3        | 1.08%   |
| Nobara        | 3        | 1.08%   |
| Lubuntu       | 3        | 1.08%   |
| Ubuntu Budgie | 2        | 0.72%   |
| Endless       | 2        | 0.72%   |
| Deepin        | 2        | 0.72%   |
| BlackPanther  | 2        | 0.72%   |
| Xero          | 1        | 0.36%   |
| Rocky Linux   | 1        | 0.36%   |
| Reborn OS     | 1        | 0.36%   |
| Parrot        | 1        | 0.36%   |
| MX            | 1        | 0.36%   |
| LMDE          | 1        | 0.36%   |
| Kali          | 1        | 0.36%   |
| CentOS        | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 13       | 4.06%   |
| 5.4.0-42-generic                   | 7        | 2.19%   |
| 5.10.14-desktop-1omv4002           | 6        | 1.88%   |
| 5.19.0-35-generic                  | 5        | 1.56%   |
| 5.15.0-56-generic                  | 5        | 1.56%   |
| 5.4.0-72-generic                   | 4        | 1.25%   |
| 5.4.0-58-generic                   | 4        | 1.25%   |
| 5.0.0-32-generic                   | 4        | 1.25%   |
| 6.2.6-desktop-1omv2390             | 3        | 0.94%   |
| 6.1.1-desktop-1omv2290             | 3        | 0.94%   |
| 5.4.0-48-generic                   | 3        | 0.94%   |
| 5.4.0-45-generic                   | 3        | 0.94%   |
| 5.4.0-122-generic                  | 3        | 0.94%   |
| 5.19.0-41-generic                  | 3        | 0.94%   |
| 5.15.0-67-generic                  | 3        | 0.94%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3        | 0.94%   |
| 4.18.0-16-generic                  | 3        | 0.94%   |
| 4.15.0-54-generic                  | 3        | 0.94%   |
| 6.4.13-200.fc38.x86_64             | 2        | 0.63%   |
| 6.4.10-200.fc38.x86_64             | 2        | 0.63%   |
| 6.3.8-200.fc38.x86_64              | 2        | 0.63%   |
| 6.1.18-200.fc37.x86_64             | 2        | 0.63%   |
| 5.8.0-48-generic                   | 2        | 0.63%   |
| 5.8.0-43-generic                   | 2        | 0.63%   |
| 5.4.0-97-generic                   | 2        | 0.63%   |
| 5.4.0-88-generic                   | 2        | 0.63%   |
| 5.4.0-70-generic                   | 2        | 0.63%   |
| 5.4.0-60-generic                   | 2        | 0.63%   |
| 5.4.0-52-generic                   | 2        | 0.63%   |
| 5.4.0-47-generic                   | 2        | 0.63%   |
| 5.4.0-40-generic                   | 2        | 0.63%   |
| 5.4.0-37-generic                   | 2        | 0.63%   |
| 5.4.0-31-generic                   | 2        | 0.63%   |
| 5.4.0-144-generic                  | 2        | 0.63%   |
| 5.4.0-125-generic                  | 2        | 0.63%   |
| 5.4.0-121-generic                  | 2        | 0.63%   |
| 5.4.0-107-generic                  | 2        | 0.63%   |
| 5.3.0-59-generic                   | 2        | 0.63%   |
| 5.3.0-46-generic                   | 2        | 0.63%   |
| 5.3.0-42-generic                   | 2        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 63       | 20.79%  |
| 5.15.0  | 24       | 7.92%   |
| 4.15.0  | 16       | 5.28%   |
| 5.16.7  | 13       | 4.29%   |
| 5.19.0  | 12       | 3.96%   |
| 5.0.0   | 11       | 3.63%   |
| 5.3.0   | 10       | 3.3%    |
| 5.13.0  | 10       | 3.3%    |
| 5.8.0   | 8        | 2.64%   |
| 4.18.0  | 8        | 2.64%   |
| 5.11.0  | 6        | 1.98%   |
| 5.10.14 | 6        | 1.98%   |
| 6.1.1   | 4        | 1.32%   |
| 5.10.0  | 4        | 1.32%   |
| 6.2.6   | 3        | 0.99%   |
| 6.2.0   | 3        | 0.99%   |
| 5.8.5   | 3        | 0.99%   |
| 5.8.18  | 3        | 0.99%   |
| 5.12.4  | 3        | 0.99%   |
| 5.10.74 | 3        | 0.99%   |
| 6.4.13  | 2        | 0.66%   |
| 6.4.10  | 2        | 0.66%   |
| 6.3.8   | 2        | 0.66%   |
| 6.2.15  | 2        | 0.66%   |
| 6.1.18  | 2        | 0.66%   |
| 6.0.10  | 2        | 0.66%   |
| 5.17.5  | 2        | 0.66%   |
| 5.15.12 | 2        | 0.66%   |
| 5.14.1  | 2        | 0.66%   |
| 5.13.19 | 2        | 0.66%   |
| 4.19.0  | 2        | 0.66%   |
| 4.18.16 | 2        | 0.66%   |
| 6.4.7   | 1        | 0.33%   |
| 6.4.11  | 1        | 0.33%   |
| 6.3.9   | 1        | 0.33%   |
| 6.3.7   | 1        | 0.33%   |
| 6.3.6   | 1        | 0.33%   |
| 6.3.5   | 1        | 0.33%   |
| 6.3.4   | 1        | 0.33%   |
| 6.3.12  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 66       | 22.22%  |
| 5.15    | 30       | 10.1%   |
| 5.10    | 19       | 6.4%    |
| 5.16    | 17       | 5.72%   |
| 4.15    | 16       | 5.39%   |
| 5.8     | 15       | 5.05%   |
| 6.1     | 12       | 4.04%   |
| 5.19    | 12       | 4.04%   |
| 5.13    | 12       | 4.04%   |
| 5.3     | 11       | 3.7%    |
| 5.0     | 11       | 3.7%    |
| 4.18    | 10       | 3.37%   |
| 6.2     | 9        | 3.03%   |
| 6.3     | 7        | 2.36%   |
| 5.14    | 7        | 2.36%   |
| 5.11    | 7        | 2.36%   |
| 6.4     | 5        | 1.68%   |
| 6.0     | 5        | 1.68%   |
| 5.12    | 5        | 1.68%   |
| 5.17    | 4        | 1.35%   |
| 4.9     | 4        | 1.35%   |
| 5.9     | 2        | 0.67%   |
| 5.6     | 2        | 0.67%   |
| 5.18    | 2        | 0.67%   |
| 4.19    | 2        | 0.67%   |
| 5.7     | 1        | 0.34%   |
| 5.2     | 1        | 0.34%   |
| 4.12    | 1        | 0.34%   |
| 4.10    | 1        | 0.34%   |
| 4.1     | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 267      | 97.8%   |
| i686   | 6        | 2.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 111      | 39.93%  |
| KDE5          | 59       | 21.22%  |
| Unknown       | 25       | 8.99%   |
| X-Cinnamon    | 20       | 7.19%   |
| XFCE          | 16       | 5.76%   |
| KDE           | 10       | 3.6%    |
| MATE          | 6        | 2.16%   |
| Pantheon      | 4        | 1.44%   |
| KDE4          | 4        | 1.44%   |
| Cinnamon      | 4        | 1.44%   |
| Unity         | 3        | 1.08%   |
| LXQt          | 3        | 1.08%   |
| i3            | 3        | 1.08%   |
| Deepin        | 3        | 1.08%   |
| GNOME Classic | 2        | 0.72%   |
| Budgie        | 2        | 0.72%   |
| ubuntu=GNOME  | 1        | 0.36%   |
| LXDE          | 1        | 0.36%   |
| awesome       | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 214      | 76.16%  |
| Wayland | 48       | 17.08%  |
| Unknown | 14       | 4.98%   |
| Tty     | 5        | 1.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 145      | 51.97%  |
| SDDM    | 46       | 16.49%  |
| GDM     | 31       | 11.11%  |
| LightDM | 25       | 8.96%   |
| GDM3    | 21       | 7.53%   |
| TDM     | 6        | 2.15%   |
| KDM     | 4        | 1.43%   |
| SLiM    | 1        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CO   | 141      | 50.18%  |
| en_US   | 73       | 25.98%  |
| Unknown | 34       | 12.1%   |
| es_ES   | 22       | 7.83%   |
| C       | 4        | 1.42%   |
| es_MX   | 3        | 1.07%   |
| pt_BR   | 2        | 0.71%   |
| en_GB   | 2        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 164      | 59.64%  |
| EFI  | 111      | 40.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 198      | 71.22%  |
| Btrfs   | 37       | 13.31%  |
| Overlay | 27       | 9.71%   |
| Xfs     | 5        | 1.8%    |
| Unknown | 5        | 1.8%    |
| Tmpfs   | 4        | 1.44%   |
| Zfs     | 1        | 0.36%   |
| Ext2    | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 145      | 52.54%  |
| GPT     | 85       | 30.8%   |
| MBR     | 46       | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 233      | 82.62%  |
| Yes       | 49       | 17.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 59.42%  |
| Yes       | 112      | 40.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 54       | 19.78%  |
| Gigabyte Technology | 52       | 19.05%  |
| ASRock              | 32       | 11.72%  |
| MSI                 | 30       | 10.99%  |
| Hewlett-Packard     | 29       | 10.62%  |
| Intel               | 17       | 6.23%   |
| Dell                | 13       | 4.76%   |
| Lenovo              | 9        | 3.3%    |
| ECS                 | 6        | 2.2%    |
| Biostar             | 6        | 2.2%    |
| Pegatron            | 5        | 1.83%   |
| Unknown             | 5        | 1.83%   |
| Foxconn             | 4        | 1.47%   |
| Acer                | 3        | 1.1%    |
| PCSMART             | 2        | 0.73%   |
| Supermicro          | 1        | 0.37%   |
| PCChips             | 1        | 0.37%   |
| Intel X79           | 1        | 0.37%   |
| Hardkernel          | 1        | 0.37%   |
| BESSTAR Tech        | 1        | 0.37%   |
| Apple               | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte B450M DS3H                | 7        | 2.56%   |
| Unknown                            | 7        | 2.56%   |
| MSI MS-7817                        | 4        | 1.47%   |
| MSI MS-7309                        | 4        | 1.47%   |
| Gigabyte H81M-H                    | 4        | 1.47%   |
| ASUS All Series                    | 4        | 1.47%   |
| HP ProDesk 400 G1 SFF              | 3        | 1.1%    |
| Gigabyte H61M-HD2                  | 3        | 1.1%    |
| Gigabyte GA-78LMT-USB3             | 3        | 1.1%    |
| Gigabyte G31M-ES2C                 | 3        | 1.1%    |
| ECS G31T-M7                        | 3        | 1.1%    |
| ASUS ROG STRIX B550-F GAMING       | 3        | 1.1%    |
| ASUS PRIME A320M-K                 | 3        | 1.1%    |
| ASUS M5A78L-M/USB3                 | 3        | 1.1%    |
| ASRock Wolfdale1333-D667           | 3        | 1.1%    |
| ASRock G965M-S                     | 3        | 1.1%    |
| ASRock G41M-VS3                    | 3        | 1.1%    |
| MSI MS-7C37                        | 2        | 0.73%   |
| Intel H61                          | 2        | 0.73%   |
| Intel DH61CR AAG14064-207          | 2        | 0.73%   |
| HP Compaq Pro 4300 SFF PC          | 2        | 0.73%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.73%   |
| Gigabyte X399 AORUS PRO            | 2        | 0.73%   |
| Gigabyte B550 AORUS PRO AC         | 2        | 0.73%   |
| Gigabyte A520M DS3H                | 2        | 0.73%   |
| ECS H81H3-M4                       | 2        | 0.73%   |
| Dell Vostro 430                    | 2        | 0.73%   |
| Biostar H61MHV                     | 2        | 0.73%   |
| ASUS TUF B450M-PLUS GAMING         | 2        | 0.73%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.73%   |
| ASUS PRIME X570-P                  | 2        | 0.73%   |
| ASUS PRIME H410M-E                 | 2        | 0.73%   |
| ASUS PRIME H310M-E                 | 2        | 0.73%   |
| ASRock Z77 Extreme4                | 2        | 0.73%   |
| ASRock H55M                        | 2        | 0.73%   |
| ASRock H110M-HDV R3.0              | 2        | 0.73%   |
| ASRock B450M-HDV R4.0              | 2        | 0.73%   |
| Supermicro X7DA8                   | 1        | 0.37%   |
| Pegatron p6740la                   | 1        | 0.37%   |
| Pegatron CQ2722LA                  | 1        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 17       | 6.23%   |
| HP Compaq                | 13       | 4.76%   |
| Gigabyte B450M           | 8        | 2.93%   |
| Lenovo ThinkCentre       | 7        | 2.56%   |
| ASUS TUF                 | 7        | 2.56%   |
| ASUS ROG                 | 7        | 2.56%   |
| Unknown                  | 7        | 2.56%   |
| Dell OptiPlex            | 6        | 2.2%    |
| HP ProDesk               | 5        | 1.83%   |
| MSI MS-7817              | 4        | 1.47%   |
| MSI MS-7309              | 4        | 1.47%   |
| HP ProLiant              | 4        | 1.47%   |
| Gigabyte H81M-H          | 4        | 1.47%   |
| Gigabyte B550            | 4        | 1.47%   |
| ASUS All                 | 4        | 1.47%   |
| Gigabyte X399            | 3        | 1.1%    |
| Gigabyte H61M-HD2        | 3        | 1.1%    |
| Gigabyte GA-78LMT-USB3   | 3        | 1.1%    |
| Gigabyte G31M-ES2C       | 3        | 1.1%    |
| ECS G31T-M7              | 3        | 1.1%    |
| Dell Vostro              | 3        | 1.1%    |
| ASUS M5A78L-M            | 3        | 1.1%    |
| ASRock Wolfdale1333-D667 | 3        | 1.1%    |
| ASRock G965M-S           | 3        | 1.1%    |
| ASRock G41M-VS3          | 3        | 1.1%    |
| MSI MS-7C37              | 2        | 0.73%   |
| Intel H61                | 2        | 0.73%   |
| Intel DH61CR             | 2        | 0.73%   |
| Intel DH55HC             | 2        | 0.73%   |
| Gigabyte B550M           | 2        | 0.73%   |
| Gigabyte A520M           | 2        | 0.73%   |
| ECS H81H3-M4             | 2        | 0.73%   |
| Biostar H61MHV           | 2        | 0.73%   |
| ASUS SABERTOOTH          | 2        | 0.73%   |
| ASUS M4A87TD             | 2        | 0.73%   |
| ASRock Z77               | 2        | 0.73%   |
| ASRock H55M              | 2        | 0.73%   |
| ASRock H110M-HDV         | 2        | 0.73%   |
| ASRock B450M-HDV         | 2        | 0.73%   |
| Supermicro X7DA8         | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 31       | 11.36%  |
| 2010 | 29       | 10.62%  |
| 2018 | 26       | 9.52%   |
| 2013 | 24       | 8.79%   |
| 2020 | 22       | 8.06%   |
| 2011 | 20       | 7.33%   |
| 2017 | 16       | 5.86%   |
| 2019 | 15       | 5.49%   |
| 2008 | 15       | 5.49%   |
| 2009 | 13       | 4.76%   |
| 2007 | 11       | 4.03%   |
| 2021 | 10       | 3.66%   |
| 2014 | 10       | 3.66%   |
| 2015 | 9        | 3.3%    |
| 2006 | 9        | 3.3%    |
| 2016 | 6        | 2.2%    |
| 2022 | 3        | 1.1%    |
| 2005 | 2        | 0.73%   |
| 2023 | 1        | 0.37%   |
| 2003 | 1        | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 273      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 266      | 96.73%  |
| Enabled  | 9        | 3.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 273      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 63       | 22.91%  |
| 3.01-4.0    | 56       | 20.36%  |
| 4.01-8.0    | 51       | 18.55%  |
| 16.01-24.0  | 45       | 16.36%  |
| 32.01-64.0  | 27       | 9.82%   |
| 1.01-2.0    | 18       | 6.55%   |
| 24.01-32.0  | 5        | 1.82%   |
| 2.01-3.0    | 4        | 1.45%   |
| 64.01-256.0 | 4        | 1.45%   |
| 0.51-1.0    | 2        | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 107      | 35.55%  |
| 2.01-3.0  | 73       | 24.25%  |
| 3.01-4.0  | 48       | 15.95%  |
| 4.01-8.0  | 42       | 13.95%  |
| 0.51-1.0  | 21       | 6.98%   |
| 8.01-16.0 | 8        | 2.66%   |
| 0.01-0.5  | 2        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 48.58%  |
| 2      | 82       | 29.08%  |
| 3      | 40       | 14.18%  |
| 4      | 13       | 4.61%   |
| 5      | 5        | 1.77%   |
| 6      | 3        | 1.06%   |
| 8      | 1        | 0.35%   |
| 0      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 162      | 58.91%  |
| Yes       | 113      | 41.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 273      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 60.14%  |
| Yes       | 110      | 39.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 223      | 80.51%  |
| Yes       | 54       | 19.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Colombia | 273      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bogotá              | 109      | 38.93%  |
| Medellín            | 53       | 18.93%  |
| Santiago de Cali     | 22       | 7.86%   |
| Bucaramanga          | 14       | 5%      |
| Barranquilla         | 11       | 3.93%   |
| Pereira              | 6        | 2.14%   |
| Pasto                | 5        | 1.79%   |
| Cúcuta              | 5        | 1.79%   |
| Valledupar           | 4        | 1.43%   |
| Ibague               | 4        | 1.43%   |
| Armenia              | 4        | 1.43%   |
| Villavicencio        | 3        | 1.07%   |
| Tunja                | 3        | 1.07%   |
| Chia                 | 3        | 1.07%   |
| Soledad              | 2        | 0.71%   |
| Santa Marta          | 2        | 0.71%   |
| Palmira              | 2        | 0.71%   |
| Montería            | 2        | 0.71%   |
| Manizales            | 2        | 0.71%   |
| Calarcá             | 2        | 0.71%   |
| Bello                | 2        | 0.71%   |
| Villagarzon          | 1        | 0.36%   |
| Tuluá               | 1        | 0.36%   |
| Rionegro             | 1        | 0.36%   |
| Puerto Carreño      | 1        | 0.36%   |
| Popayán             | 1        | 0.36%   |
| Mompos               | 1        | 0.36%   |
| La Loma              | 1        | 0.36%   |
| Jamundi              | 1        | 0.36%   |
| Ipiales              | 1        | 0.36%   |
| Guadalajara de Buga  | 1        | 0.36%   |
| Fusagasuga           | 1        | 0.36%   |
| Envigado             | 1        | 0.36%   |
| El Carmen de Bolivar | 1        | 0.36%   |
| Donmatias            | 1        | 0.36%   |
| Choachi              | 1        | 0.36%   |
| Cartagena            | 1        | 0.36%   |
| Buenaventura         | 1        | 0.36%   |
| Barrio San Luis      | 1        | 0.36%   |
| Barbosa              | 1        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 88       | 121    | 18.88%  |
| Seagate                     | 72       | 106    | 15.45%  |
| Toshiba                     | 57       | 73     | 12.23%  |
| Hitachi                     | 44       | 54     | 9.44%   |
| Samsung Electronics         | 35       | 44     | 7.51%   |
| Kingston                    | 34       | 55     | 7.3%    |
| A-DATA Technology           | 21       | 26     | 4.51%   |
| Maxtor                      | 16       | 17     | 3.43%   |
| Crucial                     | 16       | 18     | 3.43%   |
| SanDisk                     | 12       | 14     | 2.58%   |
| HGST                        | 6        | 7      | 1.29%   |
| Unknown                     | 5        | 5      | 1.07%   |
| Phison                      | 5        | 8      | 1.07%   |
| Lexar                       | 5        | 5      | 1.07%   |
| XPG                         | 4        | 5      | 0.86%   |
| Team                        | 4        | 4      | 0.86%   |
| Gigabyte Technology         | 4        | 5      | 0.86%   |
| Realtek Semiconductor       | 3        | 3      | 0.64%   |
| PNY                         | 3        | 4      | 0.64%   |
| JMicron Technology          | 3        | 3      | 0.64%   |
| Corsair                     | 3        | 4      | 0.64%   |
| XrayDisk                    | 2        | 2      | 0.43%   |
| Transcend                   | 2        | 3      | 0.43%   |
| SK hynix                    | 2        | 3      | 0.43%   |
| Fujitsu                     | 2        | 2      | 0.43%   |
| China                       | 2        | 2      | 0.43%   |
| ADATA Technology            | 2        | 2      | 0.43%   |
| XSTAR                       | 1        | 1      | 0.21%   |
| SUPERSONIC                  | 1        | 1      | 0.21%   |
| Micron/Crucial Technology   | 1        | 2      | 0.21%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.21%   |
| KingSpec                    | 1        | 1      | 0.21%   |
| KingFast                    | 1        | 1      | 0.21%   |
| KingDian                    | 1        | 1      | 0.21%   |
| KINGBANK                    | 1        | 1      | 0.21%   |
| Intel                       | 1        | 1      | 0.21%   |
| Hewlett-Packard             | 1        | 1      | 0.21%   |
| Fanxiang                    | 1        | 1      | 0.21%   |
| ExcelStor                   | 1        | 1      | 0.21%   |
| Apple                       | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 25       | 5%      |
| Kingston SA400S37240G 240GB SSD     | 10       | 2%      |
| Toshiba DT01ACA200 2TB              | 9        | 1.8%    |
| Seagate ST1000DM010-2EP102 1TB      | 8        | 1.6%    |
| Toshiba HDWD110 1TB                 | 7        | 1.4%    |
| Toshiba DT01ACA050 500GB            | 7        | 1.4%    |
| Kingston SV300S37A120G 120GB SSD    | 7        | 1.4%    |
| Kingston SA400S37120G 120GB SSD     | 7        | 1.4%    |
| WDC WD10EZEX-08WN4A0 1TB            | 6        | 1.2%    |
| Hitachi HDS721050CLA362 500GB       | 6        | 1.2%    |
| Crucial CT240BX500SSD1 240GB        | 6        | 1.2%    |
| Seagate ST500DM002-1BD142 500GB     | 5        | 1%      |
| Hitachi HDS721616PLA380 160GB       | 5        | 1%      |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 4        | 0.8%    |
| Lexar 128GB SSD                     | 4        | 0.8%    |
| Kingston SA400S37480G 480GB SSD     | 4        | 0.8%    |
| A-DATA SU650 120GB SSD              | 4        | 0.8%    |
| A-DATA SU630 240GB SSD              | 4        | 0.8%    |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 0.6%    |
| Unknown SD/MMC/MS PRO 1GB           | 3        | 0.6%    |
| Toshiba MQ01ABD100 1TB              | 3        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB     | 3        | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.6%    |
| Seagate ST3500413AS 500GB           | 3        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB      | 3        | 0.6%    |
| Samsung SSD 850 EVO 250GB           | 3        | 0.6%    |
| Samsung HD322HJ 320GB               | 3        | 0.6%    |
| Maxtor STM3160215AS 160GB           | 3        | 0.6%    |
| Crucial CT480BX500SSD1 480GB        | 3        | 0.6%    |
| A-DATA SU650 512GB SSD              | 3        | 0.6%    |
| XPG NVMe SSD Drive 1024GB           | 2        | 0.4%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD    | 2        | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.4%    |
| WDC WD800JD-75MSA3 80GB             | 2        | 0.4%    |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.4%    |
| WDC WD5000AVVS-63ZWB0 500GB         | 2        | 0.4%    |
| WDC WD5000AURX-63UY4Y0 500GB        | 2        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 75       | 98     | 25.6%   |
| Seagate             | 72       | 105    | 24.57%  |
| Toshiba             | 57       | 73     | 19.45%  |
| Hitachi             | 44       | 54     | 15.02%  |
| Samsung Electronics | 16       | 20     | 5.46%   |
| Maxtor              | 16       | 17     | 5.46%   |
| HGST                | 6        | 7      | 2.05%   |
| Unknown             | 3        | 3      | 1.02%   |
| Fujitsu             | 2        | 2      | 0.68%   |
| ExcelStor           | 1        | 1      | 0.34%   |
| Apple               | 1        | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 31       | 50     | 25.2%   |
| A-DATA Technology   | 19       | 24     | 15.45%  |
| WDC                 | 14       | 21     | 11.38%  |
| Crucial             | 14       | 16     | 11.38%  |
| Samsung Electronics | 9        | 9      | 7.32%   |
| SanDisk             | 6        | 8      | 4.88%   |
| Lexar               | 5        | 5      | 4.07%   |
| Team                | 3        | 3      | 2.44%   |
| Gigabyte Technology | 3        | 4      | 2.44%   |
| Transcend           | 2        | 3      | 1.63%   |
| SK hynix            | 2        | 3      | 1.63%   |
| PNY                 | 2        | 3      | 1.63%   |
| JMicron Technology  | 2        | 2      | 1.63%   |
| Corsair             | 2        | 3      | 1.63%   |
| China               | 2        | 2      | 1.63%   |
| XSTAR               | 1        | 1      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |
| Seagate             | 1        | 1      | 0.81%   |
| KingSpec            | 1        | 1      | 0.81%   |
| KingFast            | 1        | 1      | 0.81%   |
| KingDian            | 1        | 1      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 215      | 381    | 57.18%  |
| SSD     | 108      | 163    | 28.72%  |
| NVMe    | 49       | 62     | 13.03%  |
| Unknown | 4        | 4      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 253      | 538    | 81.09%  |
| NVMe | 49       | 62     | 15.71%  |
| SAS  | 10       | 10     | 3.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 186      | 306    | 54.07%  |
| 0.51-1.0   | 118      | 176    | 34.3%   |
| 1.01-2.0   | 27       | 37     | 7.85%   |
| 2.01-3.0   | 5        | 6      | 1.45%   |
| 4.01-10.0  | 5        | 8      | 1.45%   |
| 3.01-4.0   | 3        | 11     | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 67       | 22.79%  |
| 501-1000       | 58       | 19.73%  |
| 251-500        | 49       | 16.67%  |
| 1001-2000      | 33       | 11.22%  |
| 1-20           | 25       | 8.5%    |
| 51-100         | 25       | 8.5%    |
| More than 3000 | 11       | 3.74%   |
| 2001-3000      | 10       | 3.4%    |
| Unknown        | 9        | 3.06%   |
| 21-50          | 7        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 113      | 37.42%  |
| 21-50          | 46       | 15.23%  |
| 101-250        | 40       | 13.25%  |
| 51-100         | 37       | 12.25%  |
| 251-500        | 21       | 6.95%   |
| 501-1000       | 18       | 5.96%   |
| 1001-2000      | 10       | 3.31%   |
| Unknown        | 9        | 2.98%   |
| More than 3000 | 5        | 1.66%   |
| 2001-3000      | 3        | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 2        | 2      | 2.94%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 2.94%   |
| Hitachi HDS721050CLA362 500GB         | 2        | 2      | 2.94%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1        | 2      | 1.47%   |
| WDC WD800JD-75MSA3 80GB               | 1        | 1      | 1.47%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 1.47%   |
| WDC WD800BD-22MRA1 80GB               | 1        | 1      | 1.47%   |
| WDC WD6400AAKS-65Z7B0 640GB           | 1        | 1      | 1.47%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1        | 1      | 1.47%   |
| WDC WD5000AAKS-08V0A0 500GB           | 1        | 1      | 1.47%   |
| WDC WD3200AVJS-63B6A0 320GB           | 1        | 1      | 1.47%   |
| WDC WD3200AAJS-65M0A0 320GB           | 1        | 1      | 1.47%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1        | 1      | 1.47%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 1.47%   |
| WDC WD20EZRX-00DC0B0 2TB              | 1        | 1      | 1.47%   |
| WDC WD2003FYPS-27W9B0 2TB             | 1        | 1      | 1.47%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 1      | 1.47%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.47%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1        | 1      | 1.47%   |
| WDC WD10EALX-008EA0 1TB               | 1        | 2      | 1.47%   |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 1.47%   |
| WDC WD1001FAES-75W7A0 1TB             | 1        | 1      | 1.47%   |
| Toshiba MQ01ABD075 752GB              | 1        | 1      | 1.47%   |
| Toshiba HDWD110 1TB                   | 1        | 1      | 1.47%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.47%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.47%   |
| Toshiba DT01ABA200V 2TB               | 1        | 1      | 1.47%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 1.47%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 1.47%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 1.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 1.47%   |
| Seagate ST3320613AS 320GB             | 1        | 3      | 1.47%   |
| Seagate ST3320311CS 320GB             | 1        | 2      | 1.47%   |
| Seagate ST3250820AS 250GB             | 1        | 1      | 1.47%   |
| Seagate ST3120026AS 120GB             | 1        | 1      | 1.47%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.47%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 2      | 1.47%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 25.42%  |
| Seagate             | 14       | 22     | 23.73%  |
| Hitachi             | 11       | 13     | 18.64%  |
| Toshiba             | 5        | 5      | 8.47%   |
| Samsung Electronics | 5        | 5      | 8.47%   |
| Maxtor              | 3        | 3      | 5.08%   |
| SK hynix            | 1        | 1      | 1.69%   |
| Kingston            | 1        | 1      | 1.69%   |
| HGST                | 1        | 1      | 1.69%   |
| Fujitsu             | 1        | 1      | 1.69%   |
| Crucial             | 1        | 1      | 1.69%   |
| A-DATA Technology   | 1        | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 19     | 26.92%  |
| Seagate             | 14       | 22     | 26.92%  |
| Hitachi             | 11       | 13     | 21.15%  |
| Toshiba             | 5        | 5      | 9.62%   |
| Samsung Electronics | 3        | 3      | 5.77%   |
| Maxtor              | 3        | 3      | 5.77%   |
| HGST                | 1        | 1      | 1.92%   |
| Fujitsu             | 1        | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 47       | 67     | 87.04%  |
| SSD  | 5        | 6      | 9.26%   |
| NVMe | 2        | 2      | 3.7%    |

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
| Detected | 168      | 367    | 54.02%  |
| Works    | 88       | 167    | 28.3%   |
| Malfunc  | 54       | 75     | 17.36%  |
| Failed   | 1        | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 164      | 47.81%  |
| AMD                         | 93       | 27.11%  |
| Nvidia                      | 14       | 4.08%   |
| Samsung Electronics         | 12       | 3.5%    |
| ASMedia Technology          | 9        | 2.62%   |
| SanDisk                     | 8        | 2.33%   |
| Phison Electronics          | 7        | 2.04%   |
| Realtek Semiconductor       | 6        | 1.75%   |
| VIA Technologies            | 5        | 1.46%   |
| Kingston Technology Company | 5        | 1.46%   |
| ADATA Technology            | 5        | 1.46%   |
| JMicron Technology          | 3        | 0.87%   |
| Silicon Motion              | 2        | 0.58%   |
| Micron/Crucial Technology   | 2        | 0.58%   |
| MAXIO Technology (Hangzhou) | 2        | 0.58%   |
| Marvell Technology Group    | 2        | 0.58%   |
| INNOGRIT                    | 2        | 0.58%   |
| Micron Technology           | 1        | 0.29%   |
| Hewlett-Packard             | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40       | 8.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28       | 6.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 5.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 4.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 4.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 17       | 3.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 2.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 2.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.15%   |
| Nvidia MCP61 SATA Controller                                                            | 10       | 2.15%   |
| Nvidia MCP61 IDE                                                                        | 9        | 1.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.5%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.5%    |
| AMD FCH SATA Controller D                                                               | 7        | 1.5%    |
| Phison E12 NVMe Controller                                                              | 5        | 1.07%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.86%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.64%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 3        | 0.64%   |
| Kingston Company NVMe Controller                                                        | 3        | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.64%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3        | 0.64%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 53.85%  |
| IDE  | 99       | 28.21%  |
| NVMe | 49       | 13.96%  |
| RAID | 14       | 3.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 165      | 60.44%  |
| AMD    | 108      | 39.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 2.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 7        | 2.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 2.18%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 2.18%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 1.82%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 5        | 1.82%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 1.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 1.82%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 4        | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.45%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 1.45%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 1.45%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 1.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.45%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.45%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.45%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.09%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.09%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.09%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.09%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 1.09%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.09%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.09%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 3        | 1.09%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.09%   |
| AMD Phenom II X6 1100T Processor            | 3        | 1.09%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.09%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 3        | 1.09%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.73%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.73%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.73%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.73%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 2        | 0.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 45       | 16.36%  |
| AMD Ryzen 5             | 33       | 12%     |
| Intel Core i7           | 27       | 9.82%   |
| Intel Core i3           | 23       | 8.36%   |
| AMD FX                  | 15       | 5.45%   |
| AMD Ryzen 7             | 14       | 5.09%   |
| Intel Pentium Dual-Core | 11       | 4%      |
| Intel Xeon              | 10       | 3.64%   |
| Intel Core 2 Duo        | 10       | 3.64%   |
| Intel Celeron           | 9        | 3.27%   |
| Other                   | 7        | 2.55%   |
| Intel Pentium Dual      | 7        | 2.55%   |
| AMD Ryzen 3             | 7        | 2.55%   |
| Intel Pentium           | 5        | 1.82%   |
| AMD Phenom II X6        | 5        | 1.82%   |
| AMD Athlon II X2        | 5        | 1.82%   |
| AMD Athlon 64 X2        | 5        | 1.82%   |
| Intel Core 2 Quad       | 4        | 1.45%   |
| Intel Core 2            | 3        | 1.09%   |
| AMD Ryzen Threadripper  | 3        | 1.09%   |
| AMD Phenom              | 3        | 1.09%   |
| AMD Athlon              | 3        | 1.09%   |
| Intel Pentium D         | 2        | 0.73%   |
| Intel Pentium 4         | 2        | 0.73%   |
| AMD Sempron             | 2        | 0.73%   |
| AMD Ryzen 9             | 2        | 0.73%   |
| AMD Phenom II X4        | 2        | 0.73%   |
| AMD A8                  | 2        | 0.73%   |
| AMD A4                  | 2        | 0.73%   |
| Intel Core i9           | 1        | 0.36%   |
| Intel Celeron D         | 1        | 0.36%   |
| Intel Atom              | 1        | 0.36%   |
| AMD Athlon II X3        | 1        | 0.36%   |
| AMD Athlon 64           | 1        | 0.36%   |
| AMD A6                  | 1        | 0.36%   |
| AMD A10                 | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 93       | 34.07%  |
| 2      | 93       | 34.07%  |
| 6      | 44       | 16.12%  |
| 8      | 19       | 6.96%   |
| 1      | 9        | 3.3%    |
| 3      | 7        | 2.56%   |
| 12     | 4        | 1.47%   |
| 16     | 3        | 1.1%    |
| 10     | 1        | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 269      | 98.53%  |
| 2      | 4        | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 143      | 52%     |
| 1      | 132      | 48%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 269      | 98.53%  |
| Unknown        | 2        | 0.73%   |
| 64-bit         | 1        | 0.37%   |
| 32-bit         | 1        | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 17.92%  |
| 0x306c3    | 21       | 7.53%   |
| 0x206a7    | 18       | 6.45%   |
| 0x306a9    | 16       | 5.73%   |
| 0x1067a    | 14       | 5.02%   |
| 0x08701021 | 11       | 3.94%   |
| 0x08108109 | 11       | 3.94%   |
| 0x06000852 | 10       | 3.58%   |
| 0x6fd      | 9        | 3.23%   |
| 0x906e9    | 6        | 2.15%   |
| 0x506e3    | 6        | 2.15%   |
| 0x10676    | 6        | 2.15%   |
| 0xa0653    | 5        | 1.79%   |
| 0x0a50000c | 5        | 1.79%   |
| 0x010000dc | 5        | 1.79%   |
| 0x010000c8 | 5        | 1.79%   |
| 0x906ea    | 4        | 1.43%   |
| 0x0800820d | 4        | 1.43%   |
| 0xf65      | 3        | 1.08%   |
| 0xa0671    | 3        | 1.08%   |
| 0xa0655    | 3        | 1.08%   |
| 0x6fb      | 3        | 1.08%   |
| 0x20655    | 3        | 1.08%   |
| 0x106e5    | 3        | 1.08%   |
| 0x08001138 | 3        | 1.08%   |
| 0x6f6      | 2        | 0.72%   |
| 0x20652    | 2        | 0.72%   |
| 0x0a50000d | 2        | 0.72%   |
| 0x0a20120a | 2        | 0.72%   |
| 0x08701013 | 2        | 0.72%   |
| 0x08001137 | 2        | 0.72%   |
| 0x06001119 | 2        | 0.72%   |
| 0x06000822 | 2        | 0.72%   |
| 0x03000027 | 2        | 0.72%   |
| 0x01000083 | 2        | 0.72%   |
| 0xf64      | 1        | 0.36%   |
| 0xf49      | 1        | 0.36%   |
| 0xf27      | 1        | 0.36%   |
| 0x906ed    | 1        | 0.36%   |
| 0x906eb    | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 24       | 8.76%   |
| SandyBridge      | 23       | 8.39%   |
| IvyBridge        | 23       | 8.39%   |
| Penryn           | 22       | 8.03%   |
| Zen+             | 18       | 6.57%   |
| Zen 2            | 18       | 6.57%   |
| K10              | 18       | 6.57%   |
| Piledriver       | 16       | 5.84%   |
| Core             | 16       | 5.84%   |
| KabyLake         | 15       | 5.47%   |
| Zen 3            | 14       | 5.11%   |
| K8 Hammer        | 9        | 3.28%   |
| CometLake        | 9        | 3.28%   |
| Zen              | 8        | 2.92%   |
| Westmere         | 7        | 2.55%   |
| Skylake          | 7        | 2.55%   |
| NetBurst         | 7        | 2.55%   |
| Nehalem          | 4        | 1.46%   |
| Icelake          | 3        | 1.09%   |
| K10 Llano        | 2        | 0.73%   |
| Bulldozer        | 2        | 0.73%   |
| Unknown          | 2        | 0.73%   |
| TigerLake        | 1        | 0.36%   |
| Steamroller      | 1        | 0.36%   |
| Jaguar           | 1        | 0.36%   |
| Goldmont plus    | 1        | 0.36%   |
| Broadwell        | 1        | 0.36%   |
| Bonnell          | 1        | 0.36%   |
| Alderlake Hybrid | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 100      | 34.48%  |
| AMD                        | 96       | 33.1%   |
| Nvidia                     | 88       | 30.34%  |
| Matrox Electronics Systems | 4        | 1.38%   |
| VIA Technologies           | 2        | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 12       | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 3.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 3.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 3.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 3.39%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 9        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 2.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 2.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.37%   |
| Intel HD Graphics 530                                                       | 6        | 2.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 2.03%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 2.03%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 1.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.36%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.36%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 4        | 1.36%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.36%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 4        | 1.36%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.36%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 1.02%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 1.02%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.02%   |
| Intel HD Graphics 630                                                       | 3        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.02%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 1.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.02%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 92       | 33.09%  |
| 1 x AMD         | 88       | 31.65%  |
| 1 x Nvidia      | 83       | 29.86%  |
| 2 x AMD         | 4        | 1.44%   |
| 1 x Matrox      | 3        | 1.08%   |
| 1 x VIA         | 2        | 0.72%   |
| Intel + Nvidia  | 2        | 0.72%   |
| Intel + AMD     | 2        | 0.72%   |
| Nvidia + Matrox | 1        | 0.36%   |
| AMD + Nvidia    | 1        | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 224      | 81.16%  |
| Proprietary | 40       | 14.49%  |
| Unknown     | 12       | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 121      | 43.53%  |
| 1.01-2.0   | 44       | 15.83%  |
| 0.51-1.0   | 37       | 13.31%  |
| 0.01-0.5   | 35       | 12.59%  |
| 3.01-4.0   | 14       | 5.04%   |
| 7.01-8.0   | 10       | 3.6%    |
| 5.01-6.0   | 8        | 2.88%   |
| 8.01-16.0  | 5        | 1.8%    |
| 2.01-3.0   | 4        | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 74       | 29.13%  |
| Goldstar             | 49       | 19.29%  |
| Hewlett-Packard      | 34       | 13.39%  |
| Dell                 | 19       | 7.48%   |
| Acer                 | 14       | 5.51%   |
| AOC                  | 9        | 3.54%   |
| ViewSonic            | 5        | 1.97%   |
| LG Electronics       | 5        | 1.97%   |
| ASUSTek Computer     | 4        | 1.57%   |
| Unknown              | 3        | 1.18%   |
| Sceptre Tech         | 3        | 1.18%   |
| SANYO                | 3        | 1.18%   |
| SAC                  | 3        | 1.18%   |
| RTK                  | 3        | 1.18%   |
| MSI                  | 3        | 1.18%   |
| Ancor Communications | 3        | 1.18%   |
| NCS                  | 2        | 0.79%   |
| Lenovo               | 2        | 0.79%   |
| Envision             | 2        | 0.79%   |
| BenQ                 | 2        | 0.79%   |
| Westinghouse         | 1        | 0.39%   |
| Unknown (XXX)        | 1        | 0.39%   |
| SMC                  | 1        | 0.39%   |
| SKG                  | 1        | 0.39%   |
| PEGA                 | 1        | 0.39%   |
| MStar                | 1        | 0.39%   |
| KOA                  | 1        | 0.39%   |
| HKC                  | 1        | 0.39%   |
| HannStar             | 1        | 0.39%   |
| Estecom              | 1        | 0.39%   |
| DENON                | 1        | 0.39%   |
| AGO                  | 1        | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 5        | 1.9%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 1.9%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 1.52%   |
| Goldstar LG HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch              | 4        | 1.52%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 4        | 1.52%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 1.14%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 3        | 1.14%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 3        | 1.14%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3        | 1.14%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.14%   |
| SAC LED MONITOR SAC952D 1920x1080 480x260mm 21.5-inch                 | 3        | 1.14%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 3        | 1.14%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 1.14%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 3        | 1.14%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.76%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                    | 2        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2        | 0.76%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.76%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 2        | 0.76%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 2        | 0.76%   |
| RTK DR1602 RTK0001 2560x1600 344x215mm 16.0-inch                      | 2        | 0.76%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 2        | 0.76%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 2        | 0.76%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 2        | 0.76%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                  | 2        | 0.76%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.76%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 2        | 0.76%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 2        | 0.76%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 2        | 0.76%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 2        | 0.76%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                      | 2        | 0.76%   |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                    | 2        | 0.76%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 2        | 0.76%   |
| Acer AL1716 ACRAD51 1280x1024 340x270mm 17.1-inch                     | 2        | 0.76%   |
| Westinghouse WDE LCM-17v2 WDE1702 1280x1024 338x270mm 17.0-inch       | 1        | 0.38%   |
| ViewSonic VX2768-PC-mhd VSC083A 1920x1080 598x336mm 27.0-inch         | 1        | 0.38%   |
| ViewSonic VX2739 Series VSC3F24 1920x1080 598x336mm 27.0-inch         | 1        | 0.38%   |
| ViewSonic VG2239 Series VSCC42B 1920x1080 477x268mm 21.5-inch         | 1        | 0.38%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 85       | 33.86%  |
| 1366x768 (WXGA)    | 39       | 15.54%  |
| 1440x900 (WXGA+)   | 22       | 8.76%   |
| 1280x1024 (SXGA)   | 22       | 8.76%   |
| 1600x900 (HD+)     | 21       | 8.37%   |
| 3840x2160 (4K)     | 14       | 5.58%   |
| 1360x768           | 10       | 3.98%   |
| 2560x1440 (QHD)    | 9        | 3.59%   |
| 1680x1050 (WSXGA+) | 8        | 3.19%   |
| 2560x1080          | 4        | 1.59%   |
| 1920x1200 (WUXGA)  | 3        | 1.2%    |
| 1024x768 (XGA)     | 3        | 1.2%    |
| Unknown            | 3        | 1.2%    |
| 3840x1080          | 2        | 0.8%    |
| 1280x720 (HD)      | 2        | 0.8%    |
| 3440x1440          | 1        | 0.4%    |
| 3200x1080          | 1        | 0.4%    |
| 1920x540           | 1        | 0.4%    |
| 1152x864           | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 41       | 16.14%  |
| 21      | 37       | 14.57%  |
| 19      | 37       | 14.57%  |
| 23      | 23       | 9.06%   |
| Unknown | 17       | 6.69%   |
| 17      | 15       | 5.91%   |
| 20      | 14       | 5.51%   |
| 27      | 13       | 5.12%   |
| 24      | 11       | 4.33%   |
| 31      | 10       | 3.94%   |
| 22      | 8        | 3.15%   |
| 15      | 4        | 1.57%   |
| 72      | 3        | 1.18%   |
| 54      | 3        | 1.18%   |
| 34      | 3        | 1.18%   |
| 84      | 2        | 0.79%   |
| 48      | 2        | 0.79%   |
| 28      | 2        | 0.79%   |
| 12      | 2        | 0.79%   |
| 60      | 1        | 0.39%   |
| 52      | 1        | 0.39%   |
| 46      | 1        | 0.39%   |
| 40      | 1        | 0.39%   |
| 32      | 1        | 0.39%   |
| 16      | 1        | 0.39%   |
| 13      | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 130      | 52.21%  |
| 501-600     | 41       | 16.47%  |
| 301-350     | 17       | 6.83%   |
| Unknown     | 17       | 6.83%   |
| 601-700     | 14       | 5.62%   |
| 351-400     | 9        | 3.61%   |
| 1001-1500   | 8        | 3.21%   |
| 1501-2000   | 5        | 2.01%   |
| 701-800     | 4        | 1.61%   |
| 201-300     | 3        | 1.2%    |
| 801-900     | 1        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 165      | 67.9%   |
| 16/10   | 30       | 12.35%  |
| 5/4     | 19       | 7.82%   |
| Unknown | 16       | 6.58%   |
| 4/3     | 6        | 2.47%   |
| 21/9    | 5        | 2.06%   |
| 32/9    | 2        | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 68       | 26.98%  |
| 151-200        | 59       | 23.41%  |
| 141-150        | 51       | 20.24%  |
| Unknown        | 17       | 6.75%   |
| 351-500        | 14       | 5.56%   |
| 301-350        | 13       | 5.16%   |
| More than 1000 | 11       | 4.37%   |
| 251-300        | 6        | 2.38%   |
| 501-1000       | 3        | 1.19%   |
| 71-80          | 2        | 0.79%   |
| 131-140        | 2        | 0.79%   |
| 111-120        | 2        | 0.79%   |
| 101-110        | 2        | 0.79%   |
| 81-90          | 1        | 0.4%    |
| 121-130        | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 159      | 65.16%  |
| 101-120 | 47       | 19.26%  |
| Unknown | 17       | 6.97%   |
| 1-50    | 14       | 5.74%   |
| 121-160 | 4        | 1.64%   |
| 161-240 | 3        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 234      | 84.78%  |
| 2     | 22       | 7.97%   |
| 0     | 16       | 5.8%    |
| 3     | 4        | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 177      | 46.21%  |
| Intel                             | 62       | 16.19%  |
| Qualcomm Atheros                  | 33       | 8.62%   |
| Ralink Technology                 | 23       | 6.01%   |
| Broadcom                          | 15       | 3.92%   |
| TP-Link                           | 13       | 3.39%   |
| Nvidia                            | 11       | 2.87%   |
| Broadcom Limited                  | 6        | 1.57%   |
| Ralink                            | 5        | 1.31%   |
| Qualcomm Atheros Communications   | 5        | 1.31%   |
| Marvell Technology Group          | 4        | 1.04%   |
| Xiaomi                            | 3        | 0.78%   |
| Samsung Electronics               | 3        | 0.78%   |
| Mercucys                          | 3        | 0.78%   |
| MediaTek                          | 3        | 0.78%   |
| VIA Technologies                  | 2        | 0.52%   |
| Motorola PCS                      | 2        | 0.52%   |
| ICS Advent                        | 2        | 0.52%   |
| D-Link System                     | 2        | 0.52%   |
| Wistron NeWeb                     | 1        | 0.26%   |
| Sundance Technology Inc / IC Plus | 1        | 0.26%   |
| Qualcomm                          | 1        | 0.26%   |
| OPPO Electronics                  | 1        | 0.26%   |
| Mellanox Technologies             | 1        | 0.26%   |
| LG Electronics                    | 1        | 0.26%   |
| Huawei Technologies               | 1        | 0.26%   |
| Encore Electronics                | 1        | 0.26%   |
| Aquantia                          | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129      | 31.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19       | 4.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 2.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 10       | 2.44%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 2.2%    |
| Nvidia MCP61 Ethernet                                             | 9        | 2.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8        | 1.95%   |
| Intel I211 Gigabit Network Connection                             | 8        | 1.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 1.71%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 1.46%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 1.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 4        | 0.98%   |
| TP-Link 802.11n NIC                                               | 4        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.73%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.73%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 3        | 0.73%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3        | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 3        | 0.73%   |
| Mercucys 802.11n NIC                                              | 3        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.73%   |
| Intel 82578DC Gigabit Network Connection                          | 3        | 0.73%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.49%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 2        | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.49%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter              | 2        | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.49%   |
| Realtek 802.11ac NIC                                              | 2        | 0.49%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 26       | 22.03%  |
| Ralink Technology               | 23       | 19.49%  |
| Intel                           | 20       | 16.95%  |
| Qualcomm Atheros                | 14       | 11.86%  |
| TP-Link                         | 13       | 11.02%  |
| Ralink                          | 5        | 4.24%   |
| Qualcomm Atheros Communications | 5        | 4.24%   |
| Mercucys                        | 3        | 2.54%   |
| MediaTek                        | 3        | 2.54%   |
| Wistron NeWeb                   | 1        | 0.85%   |
| LG Electronics                  | 1        | 0.85%   |
| Encore Electronics              | 1        | 0.85%   |
| D-Link System                   | 1        | 0.85%   |
| Broadcom Limited                | 1        | 0.85%   |
| Broadcom                        | 1        | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink RT2870/RT3070 Wireless Adapter                          | 10       | 8.47%   |
| Ralink MT7601U Wireless Adapter                                | 9        | 7.63%   |
| Intel Wi-Fi 6 AX200                                            | 6        | 5.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 4.24%   |
| Qualcomm Atheros AR9271 802.11n                                | 5        | 4.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 3.39%   |
| TP-Link 802.11n NIC                                            | 4        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 3.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 3        | 2.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 3        | 2.54%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3        | 2.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 2.54%   |
| Mercucys 802.11n NIC                                           | 3        | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 2.54%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 2        | 1.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.69%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter           | 2        | 1.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2        | 1.69%   |
| Realtek 802.11ac NIC                                           | 2        | 1.69%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2        | 1.69%   |
| Intel Wireless 7265                                            | 2        | 1.69%   |
| Wistron NeWeb AR9170+AR9104 802.11abgn Wireless Adapter        | 1        | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.85%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                        | 1        | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.85%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 0.85%   |
| Ralink RT3072 Wireless Adapter                                 | 1        | 0.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.85%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 0.85%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 1        | 0.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 165      | 57.29%  |
| Intel                             | 52       | 18.06%  |
| Qualcomm Atheros                  | 19       | 6.6%    |
| Broadcom                          | 14       | 4.86%   |
| Nvidia                            | 11       | 3.82%   |
| Broadcom Limited                  | 5        | 1.74%   |
| Marvell Technology Group          | 4        | 1.39%   |
| Xiaomi                            | 3        | 1.04%   |
| Samsung Electronics               | 3        | 1.04%   |
| VIA Technologies                  | 2        | 0.69%   |
| ICS Advent                        | 2        | 0.69%   |
| Sundance Technology Inc / IC Plus | 1        | 0.35%   |
| Qualcomm                          | 1        | 0.35%   |
| OPPO Electronics                  | 1        | 0.35%   |
| Motorola PCS                      | 1        | 0.35%   |
| Mellanox Technologies             | 1        | 0.35%   |
| Huawei Technologies               | 1        | 0.35%   |
| D-Link System                     | 1        | 0.35%   |
| Aquantia                          | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 129      | 44.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 19       | 6.53%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 4.12%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 3.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8        | 2.75%   |
| Intel I211 Gigabit Network Connection                                      | 8        | 2.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 2.41%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.06%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 2.06%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 4        | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.03%   |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 1.03%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.69%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.69%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.69%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.69%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.69%   |
| Intel Ethernet Connection (12) I219-V                                      | 2        | 0.69%   |
| Intel 82566DM Gigabit Network Connection                                   | 2        | 0.69%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 2        | 0.69%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.69%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                           | 2        | 0.69%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.69%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                    | 2        | 0.69%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.34%   |
| Qualcomm Android                                                           | 1        | 0.34%   |
| OPPO OnePlus Nord                                                          | 1        | 0.34%   |
| Motorola PCS motorola edge 20 lite                                         | 1        | 0.34%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                      | 1        | 0.34%   |
| Marvell Group 88E8070 based Ethernet Controller                            | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 273      | 71.28%  |
| WiFi     | 109      | 28.46%  |
| Unknown  | 1        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 218      | 78.42%  |
| WiFi     | 60       | 21.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 204      | 74.45%  |
| 2     | 64       | 23.36%  |
| 3     | 3        | 1.09%   |
| 0     | 2        | 0.73%   |
| 7     | 1        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 239      | 86.59%  |
| Yes  | 37       | 13.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 27       | 50%     |
| Intel                   | 19       | 35.19%  |
| MediaTek                | 2        | 3.7%    |
| IMC Networks            | 2        | 3.7%    |
| Realtek Semiconductor   | 1        | 1.85%   |
| Dell                    | 1        | 1.85%   |
| Broadcom                | 1        | 1.85%   |
| Apple                   | 1        | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 27       | 50%     |
| Intel AX200 Bluetooth                               | 6        | 11.11%  |
| Intel Bluetooth wireless interface                  | 4        | 7.41%   |
| Intel Bluetooth Device                              | 3        | 5.56%   |
| MediaTek Wireless_Device                            | 2        | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 3.7%    |
| Intel AX201 Bluetooth                               | 2        | 3.7%    |
| Realtek Bluetooth Radio                             | 1        | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.85%   |
| Intel AX210 Bluetooth                               | 1        | 1.85%   |
| IMC Networks Wireless_Device                        | 1        | 1.85%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.85%   |
| Dell Wireless 365 Bluetooth                         | 1        | 1.85%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.85%   |
| Apple Bluetooth HCI                                 | 1        | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 158      | 37.44%  |
| AMD                                  | 126      | 29.86%  |
| Nvidia                               | 87       | 20.62%  |
| C-Media Electronics                  | 9        | 2.13%   |
| Generalplus Technology               | 5        | 1.18%   |
| VIA Technologies                     | 4        | 0.95%   |
| Logitech                             | 4        | 0.95%   |
| Creative Labs                        | 4        | 0.95%   |
| M-Audio                              | 3        | 0.71%   |
| JMTek                                | 3        | 0.71%   |
| Texas Instruments                    | 2        | 0.47%   |
| Kingston Technology                  | 2        | 0.47%   |
| Turtle Beach                         | 1        | 0.24%   |
| Trust                                | 1        | 0.24%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.24%   |
| SteelSeries ApS                      | 1        | 0.24%   |
| Realtek Semiconductor                | 1        | 0.24%   |
| Razer USA                            | 1        | 0.24%   |
| OLKB                                 | 1        | 0.24%   |
| HiBy                                 | 1        | 0.24%   |
| GN Netcom                            | 1        | 0.24%   |
| Giga-Byte Technology                 | 1        | 0.24%   |
| Earth Computer Technologies          | 1        | 0.24%   |
| Creative Technology                  | 1        | 0.24%   |
| Corsair                              | 1        | 0.24%   |
| Blue Microphones                     | 1        | 0.24%   |
| Avid Technology                      | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 36       | 7.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 28       | 5.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 5.24%   |
| AMD Starship/Matisse HD Audio Controller                                          | 24       | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                            | 23       | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 21       | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12       | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 12       | 2.42%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11       | 2.22%   |
| Nvidia MCP61 High Definition Audio                                                | 10       | 2.02%   |
| Nvidia High Definition Audio Controller                                           | 10       | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 10       | 2.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 1.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 8        | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 7        | 1.41%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.21%   |
| Intel Comet Lake PCH-V cAVS                                                       | 6        | 1.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 1.21%   |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.21%   |
| AMD Navi 10 HDMI Audio                                                            | 6        | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 1.01%   |
| Generalplus Technology USB Audio Device                                           | 5        | 1.01%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 5        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 0.81%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 0.81%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.6%    |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 30       | 18.29%  |
| Corsair             | 19       | 11.59%  |
| Samsung Electronics | 18       | 10.98%  |
| A-DATA Technology   | 16       | 9.76%   |
| Kingston            | 14       | 8.54%   |
| Crucial             | 10       | 6.1%    |
| SK hynix            | 9        | 5.49%   |
| G.Skill             | 6        | 3.66%   |
| Team                | 5        | 3.05%   |
| Micron Technology   | 5        | 3.05%   |
| Super Talent        | 4        | 2.44%   |
| GeIL                | 4        | 2.44%   |
| Ramaxel Technology  | 3        | 1.83%   |
| Patriot             | 3        | 1.83%   |
| PNY                 | 2        | 1.22%   |
| Nanya Technology    | 2        | 1.22%   |
| Kreton              | 2        | 1.22%   |
| Hewlett-Packard     | 2        | 1.22%   |
| Avant               | 2        | 1.22%   |
| Unknown (AD8A)      | 1        | 0.61%   |
| Transcend           | 1        | 0.61%   |
| Sesame              | 1        | 0.61%   |
| Kllisre             | 1        | 0.61%   |
| Golden Empire       | 1        | 0.61%   |
| CSX                 | 1        | 0.61%   |
| Apacer              | 1        | 0.61%   |
| Unknown             | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                      | 4        | 2.17%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 4        | 2.17%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s  | 4        | 2.17%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s     | 3        | 1.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.63%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 3        | 1.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.09%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 1.09%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 2        | 1.09%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 2        | 1.09%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 1.09%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s         | 2        | 1.09%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 1.09%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s    | 2        | 1.09%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s    | 2        | 1.09%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s | 2        | 1.09%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 1.09%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s  | 2        | 1.09%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 1.09%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3200MT/s           | 2        | 1.09%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 2        | 1.09%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s        | 2        | 1.09%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s              | 1        | 0.54%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 1        | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.54%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 200MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 42.86%  |
| DDR3    | 45       | 33.83%  |
| SDRAM   | 13       | 9.77%   |
| DDR2    | 8        | 6.02%   |
| Unknown | 6        | 4.51%   |
| DDR     | 3        | 2.26%   |
| LPDDR4  | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 122      | 93.85%  |
| SODIMM       | 7        | 5.38%   |
| Row Of Chips | 1        | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 51       | 33.33%  |
| 4096  | 35       | 22.88%  |
| 2048  | 31       | 20.26%  |
| 16384 | 20       | 13.07%  |
| 32768 | 9        | 5.88%   |
| 1024  | 6        | 3.92%   |
| 512   | 1        | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 20%     |
| 1333    | 22       | 14.67%  |
| 3600    | 14       | 9.33%   |
| 3200    | 12       | 8%      |
| Unknown | 9        | 6%      |
| 2133    | 8        | 5.33%   |
| 2400    | 7        | 4.67%   |
| 3000    | 5        | 3.33%   |
| 800     | 5        | 3.33%   |
| 2667    | 4        | 2.67%   |
| 3800    | 3        | 2%      |
| 1867    | 3        | 2%      |
| 3733    | 2        | 1.33%   |
| 3400    | 2        | 1.33%   |
| 3266    | 2        | 1.33%   |
| 2666    | 2        | 1.33%   |
| 1866    | 2        | 1.33%   |
| 1800    | 2        | 1.33%   |
| 1334    | 2        | 1.33%   |
| 667     | 2        | 1.33%   |
| 333     | 2        | 1.33%   |
| 3500    | 1        | 0.67%   |
| 3333    | 1        | 0.67%   |
| 3100    | 1        | 0.67%   |
| 3066    | 1        | 0.67%   |
| 2800    | 1        | 0.67%   |
| 2176    | 1        | 0.67%   |
| 1066    | 1        | 0.67%   |
| 533     | 1        | 0.67%   |
| 400     | 1        | 0.67%   |
| 200     | 1        | 0.67%   |

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
| HP Laser 107w                                          | 1        | 6.67%   |
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
| Logitech                    | 14       | 24.56%  |
| Microdia                    | 6        | 10.53%  |
| KYE Systems (Mouse Systems) | 6        | 10.53%  |
| Microsoft                   | 4        | 7.02%   |
| Cubeternet                  | 4        | 7.02%   |
| Chicony Electronics         | 4        | 7.02%   |
| Generalplus Technology      | 3        | 5.26%   |
| Huawei Technologies         | 2        | 3.51%   |
| Arkmicro Technologies       | 2        | 3.51%   |
| WaveRider Communications    | 1        | 1.75%   |
| Unknown                     | 1        | 1.75%   |
| Trust                       | 1        | 1.75%   |
| Samsung Electronics         | 1        | 1.75%   |
| Realtek Semiconductor       | 1        | 1.75%   |
| Pixart Imaging              | 1        | 1.75%   |
| OmniVision Technologies     | 1        | 1.75%   |
| KYE Systems                 | 1        | 1.75%   |
| Hewlett-Packard             | 1        | 1.75%   |
| GEMBIRD                     | 1        | 1.75%   |
| 2M UVC CAMERA               | 1        | 1.75%   |
| Unknown                     | 1        | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                                             | 4        | 7.02%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                           | 3        | 5.26%   |
| Generalplus CAMERA - UVC                                            | 3        | 5.26%   |
| Cubeternet GL-UPC822 UVC WebCam                                     | 3        | 5.26%   |
| Chicony HP High Definition 1MP Webcam                               | 3        | 5.26%   |
| Microdia Integrated Camera                                          | 2        | 3.51%   |
| Microdia GC02M2                                                     | 2        | 3.51%   |
| Logitech Webcam C930e                                               | 2        | 3.51%   |
| Logitech Webcam C170                                                | 2        | 3.51%   |
| Logitech HD Pro Webcam C920                                         | 2        | 3.51%   |
| Huawei HiCamera                                                     | 2        | 3.51%   |
| WaveRider USB 2.0 Camera                                            | 1        | 1.75%   |
| Unknown HD camera                                                   | 1        | 1.75%   |
| Trust Full HD Webcam                                                | 1        | 1.75%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 1.75%   |
| Realtek Streamplify CAM                                             | 1        | 1.75%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 1        | 1.75%   |
| OmniVision Monitor Webcam                                           | 1        | 1.75%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 1.75%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                 | 1        | 1.75%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.75%   |
| Microsoft LifeCam Cinema                                            | 1        | 1.75%   |
| Microdia Webcam Vitade AF                                           | 1        | 1.75%   |
| Microdia Sonix USB 2.0 Camera                                       | 1        | 1.75%   |
| Logitech Webcam C270                                                | 1        | 1.75%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 1.75%   |
| Logitech C505 HD Webcam                                             | 1        | 1.75%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.75%   |
| KYE Systems Genius iLook 1321 V2                                    | 1        | 1.75%   |
| KYE Systems (Mouse Systems) FaceCam 310                             | 1        | 1.75%   |
| KYE Systems (Mouse Systems) FaceCam 2020                            | 1        | 1.75%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 1.75%   |
| HP Webcam HD-2200                                                   | 1        | 1.75%   |
| GEMBIRD USB2.0 PC CAMERA                                            | 1        | 1.75%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.75%   |
| Chicony HP WebCam                                                   | 1        | 1.75%   |
| Arkmicro Webcam Carrefour                                           | 1        | 1.75%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 1.75%   |
| 2M UVC CAMERA Web Camera                                            | 1        | 1.75%   |
| Unknown                                                             | 1        | 1.75%   |

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
| 0     | 233      | 84.42%  |
| 1     | 39       | 14.13%  |
| 2     | 3        | 1.09%   |
| 4     | 1        | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 18       | 37.5%   |
| Graphics card            | 17       | 35.42%  |
| Communication controller | 4        | 8.33%   |
| Storage/raid             | 2        | 4.17%   |
| Multimedia controller    | 2        | 4.17%   |
| Unassigned class         | 1        | 2.08%   |
| Sound                    | 1        | 2.08%   |
| Network                  | 1        | 2.08%   |
| Card reader              | 1        | 2.08%   |
| Camera                   | 1        | 2.08%   |

