openSUSE Leap-15.5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.5.

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

Total: 205

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z97-HD3                     | [85dee8d963](https://linux-hardware.org/?probe=85dee8d963) | May 07, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [42a7c6fb23](https://linux-hardware.org/?probe=42a7c6fb23) | May 06, 2024 |
| Dell          | 0NW6H5 A00                  | [3fafaee792](https://linux-hardware.org/?probe=3fafaee792) | May 05, 2024 |
| Dell          | 0NW6H5 A00                  | [ed934b8b61](https://linux-hardware.org/?probe=ed934b8b61) | May 05, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [a1541c5122](https://linux-hardware.org/?probe=a1541c5122) | May 02, 2024 |
| ASRock        | Z390 Taichi Ultimate        | [8f95604689](https://linux-hardware.org/?probe=8f95604689) | Apr 24, 2024 |
| HP            | 158B                        | [38acb31ca9](https://linux-hardware.org/?probe=38acb31ca9) | Apr 24, 2024 |
| Biostar       | A960D+V2                    | [e6d3b07d8e](https://linux-hardware.org/?probe=e6d3b07d8e) | Apr 23, 2024 |
| ASRock        | Z790 PG SONIC               | [6426fb59eb](https://linux-hardware.org/?probe=6426fb59eb) | Apr 22, 2024 |
| Gigabyte      | Z97-HD3                     | [0247606ff3](https://linux-hardware.org/?probe=0247606ff3) | Apr 21, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [cf7eac1515](https://linux-hardware.org/?probe=cf7eac1515) | Apr 21, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [542fb126b0](https://linux-hardware.org/?probe=542fb126b0) | Apr 20, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [8a42c0cd30](https://linux-hardware.org/?probe=8a42c0cd30) | Apr 18, 2024 |
| ASUSTek       | PRIME X570-P                | [e7bc6ac35e](https://linux-hardware.org/?probe=e7bc6ac35e) | Apr 17, 2024 |
| Gigabyte      | Z370M D3H-CF                | [f14f8b8b13](https://linux-hardware.org/?probe=f14f8b8b13) | Apr 17, 2024 |
| Gigabyte      | P55-UD5                     | [736814c1df](https://linux-hardware.org/?probe=736814c1df) | Apr 13, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | [fb483fb3bc](https://linux-hardware.org/?probe=fb483fb3bc) | Apr 10, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME      | [0de5191161](https://linux-hardware.org/?probe=0de5191161) | Apr 08, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [ea4485f45b](https://linux-hardware.org/?probe=ea4485f45b) | Apr 08, 2024 |
| HP            | ProLiant ML350 G6           | [3a9aaf0732](https://linux-hardware.org/?probe=3a9aaf0732) | Apr 07, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [92dd5d1690](https://linux-hardware.org/?probe=92dd5d1690) | Apr 07, 2024 |
| HP            | 3048h                       | [98a7ae878b](https://linux-hardware.org/?probe=98a7ae878b) | Apr 06, 2024 |
| HP            | ProLiant ML350 G6           | [d70516fc56](https://linux-hardware.org/?probe=d70516fc56) | Apr 06, 2024 |
| ASUSTek       | M5A97 R2.0                  | [bb4170e7fc](https://linux-hardware.org/?probe=bb4170e7fc) | Apr 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | [9dc48f27f9](https://linux-hardware.org/?probe=9dc48f27f9) | Apr 01, 2024 |
| Gigabyte      | EP35-DS3                    | [3d93a78c1b](https://linux-hardware.org/?probe=3d93a78c1b) | Mar 31, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [cf27d76a8a](https://linux-hardware.org/?probe=cf27d76a8a) | Mar 29, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [21456be41e](https://linux-hardware.org/?probe=21456be41e) | Mar 26, 2024 |
| Gigabyte      | 970A-UD3P                   | [b9faafe90e](https://linux-hardware.org/?probe=b9faafe90e) | Mar 25, 2024 |
| GEEKOM        | Mini IT11                   | [959133190b](https://linux-hardware.org/?probe=959133190b) | Mar 24, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | [8fa61ae34a](https://linux-hardware.org/?probe=8fa61ae34a) | Mar 24, 2024 |
| Dell          | 0M9KCM A02                  | [e612c937ca](https://linux-hardware.org/?probe=e612c937ca) | Mar 22, 2024 |
| ASRock        | Z790 Riptide WiFi           | [a03071be8b](https://linux-hardware.org/?probe=a03071be8b) | Mar 21, 2024 |
| ASRock        | Z790 Riptide WiFi           | [b8d5bc7323](https://linux-hardware.org/?probe=b8d5bc7323) | Mar 21, 2024 |
| ASRock        | B560 Pro4                   | [a34877f66c](https://linux-hardware.org/?probe=a34877f66c) | Mar 21, 2024 |
| ASUSTek       | Pro WS W680-ACE             | [c1ef51d3b0](https://linux-hardware.org/?probe=c1ef51d3b0) | Mar 19, 2024 |
| HP            | 2B29                        | [0db8d7c93c](https://linux-hardware.org/?probe=0db8d7c93c) | Mar 13, 2024 |
| ASUSTek       | P8B75-V                     | [6529cfcd8e](https://linux-hardware.org/?probe=6529cfcd8e) | Mar 11, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9793665868](https://linux-hardware.org/?probe=9793665868) | Mar 08, 2024 |
| Gigabyte      | B250M-D3H-CF                | [97c41f0fd8](https://linux-hardware.org/?probe=97c41f0fd8) | Mar 04, 2024 |
| HC Technol... | HCAR5000-MI                 | [548005c028](https://linux-hardware.org/?probe=548005c028) | Mar 02, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [146b43cf79](https://linux-hardware.org/?probe=146b43cf79) | Mar 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [8464bee9a7](https://linux-hardware.org/?probe=8464bee9a7) | Feb 29, 2024 |
| HP            | 3031h                       | [7f8ca0e8e8](https://linux-hardware.org/?probe=7f8ca0e8e8) | Feb 29, 2024 |
| ASRock        | B550M-ITX/ac                | [2934279a7d](https://linux-hardware.org/?probe=2934279a7d) | Feb 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [cc59cfab4f](https://linux-hardware.org/?probe=cc59cfab4f) | Feb 27, 2024 |
| Dell          | 0J3C2F A02                  | [e757c4ef0c](https://linux-hardware.org/?probe=e757c4ef0c) | Feb 21, 2024 |
| ASUSTek       | A68HM-K                     | [5ba603ce75](https://linux-hardware.org/?probe=5ba603ce75) | Feb 21, 2024 |
| Dell          | 0C522T A01                  | [aa4b8ca306](https://linux-hardware.org/?probe=aa4b8ca306) | Feb 12, 2024 |
| Intel         | DH87RL AAG74240-403         | [8d65745585](https://linux-hardware.org/?probe=8d65745585) | Feb 05, 2024 |
| ASRock        | B75 Pro3                    | [d15b9f0cc9](https://linux-hardware.org/?probe=d15b9f0cc9) | Feb 04, 2024 |
| HP            | ProLiant ML10 v2            | [b16f323611](https://linux-hardware.org/?probe=b16f323611) | Jan 28, 2024 |
| HP            | 0B4Ch D                     | [d41cb5632c](https://linux-hardware.org/?probe=d41cb5632c) | Jan 28, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [af91485fb2](https://linux-hardware.org/?probe=af91485fb2) | Jan 25, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [343af19ed9](https://linux-hardware.org/?probe=343af19ed9) | Jan 24, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [195dbfe0e7](https://linux-hardware.org/?probe=195dbfe0e7) | Jan 20, 2024 |
| MSI           | B450 TOMAHAWK               | [9bed697ae6](https://linux-hardware.org/?probe=9bed697ae6) | Jan 18, 2024 |
| MSI           | B450 TOMAHAWK               | [d0f45c11a7](https://linux-hardware.org/?probe=d0f45c11a7) | Jan 18, 2024 |
| MSI           | B450M MORTAR MAX            | [c2c3082933](https://linux-hardware.org/?probe=c2c3082933) | Jan 16, 2024 |
| ASRock        | B450 Pro4                   | [b082a9bd9f](https://linux-hardware.org/?probe=b082a9bd9f) | Jan 14, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [0e9f707dea](https://linux-hardware.org/?probe=0e9f707dea) | Jan 06, 2024 |
| HP            | 8AB6 SMVB                   | [b846966b99](https://linux-hardware.org/?probe=b846966b99) | Jan 04, 2024 |
| HP            | 0B4Ch D                     | [b7d97486fb](https://linux-hardware.org/?probe=b7d97486fb) | Jan 01, 2024 |
| HP            | 0B4Ch D                     | [7b5d790450](https://linux-hardware.org/?probe=7b5d790450) | Dec 28, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [cb215ce5f6](https://linux-hardware.org/?probe=cb215ce5f6) | Dec 28, 2023 |
| MSI           | B150 GAMING M3              | [2b312f609c](https://linux-hardware.org/?probe=2b312f609c) | Dec 27, 2023 |
| Gigabyte      | Z97-HD3                     | [a271d8355d](https://linux-hardware.org/?probe=a271d8355d) | Dec 26, 2023 |
| Foxconn       | 2ABF                        | [d12d3a2f21](https://linux-hardware.org/?probe=d12d3a2f21) | Dec 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | [51cee07e16](https://linux-hardware.org/?probe=51cee07e16) | Dec 22, 2023 |
| Gigabyte      | GA-990XA-UD3                | [f8215b7e03](https://linux-hardware.org/?probe=f8215b7e03) | Dec 21, 2023 |
| ASUSTek       | P8H61                       | [e0b9ef0f5e](https://linux-hardware.org/?probe=e0b9ef0f5e) | Dec 18, 2023 |
| ASUSTek       | P8H61                       | [e83b933182](https://linux-hardware.org/?probe=e83b933182) | Dec 18, 2023 |
| ASUSTek       | M3A78                       | [d2c14973f1](https://linux-hardware.org/?probe=d2c14973f1) | Dec 10, 2023 |
| HP            | 3397                        | [f840ce3d4e](https://linux-hardware.org/?probe=f840ce3d4e) | Dec 08, 2023 |
| Dell          | 0GM819                      | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| AMI           | Intel                       | [7fdef1f7fc](https://linux-hardware.org/?probe=7fdef1f7fc) | Dec 04, 2023 |
| ASUSTek       | M4A88T-M LE                 | [a2f1655886](https://linux-hardware.org/?probe=a2f1655886) | Dec 01, 2023 |
| MSI           | B450M-A PRO MAX             | [9accd13cb5](https://linux-hardware.org/?probe=9accd13cb5) | Nov 30, 2023 |
| ASUSTek       | M4A88T-M LE                 | [1e982d5ac9](https://linux-hardware.org/?probe=1e982d5ac9) | Nov 30, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [f6e7c5e8a3](https://linux-hardware.org/?probe=f6e7c5e8a3) | Nov 29, 2023 |
| HP            | 0B4Ch D                     | [84e4d06443](https://linux-hardware.org/?probe=84e4d06443) | Nov 26, 2023 |
| HP            | 0B4Ch D                     | [8104fc2789](https://linux-hardware.org/?probe=8104fc2789) | Nov 26, 2023 |
| HP            | 212B                        | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| ASUSTek       | M3A78                       | [c4895d59da](https://linux-hardware.org/?probe=c4895d59da) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | [50eb6f63d8](https://linux-hardware.org/?probe=50eb6f63d8) | Nov 23, 2023 |
| Biostar       | TF570 SLI A2+               | [052c9cc626](https://linux-hardware.org/?probe=052c9cc626) | Nov 23, 2023 |
| HC Technol... | HCAR5000-MI                 | [718e30ca5e](https://linux-hardware.org/?probe=718e30ca5e) | Nov 22, 2023 |
| ASRock        | B250M-HDV                   | [1d8de35042](https://linux-hardware.org/?probe=1d8de35042) | Nov 21, 2023 |
| Gigabyte      | Z97-HD3                     | [4949cbc96a](https://linux-hardware.org/?probe=4949cbc96a) | Nov 19, 2023 |
| Gigabyte      | Z97-HD3                     | [36ce4210e3](https://linux-hardware.org/?probe=36ce4210e3) | Nov 19, 2023 |
| ASUSTek       | M3A78                       | [a6392d3aae](https://linux-hardware.org/?probe=a6392d3aae) | Nov 19, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [5cdf728f08](https://linux-hardware.org/?probe=5cdf728f08) | Nov 15, 2023 |
| Gigabyte      | H410M H V3                  | [6406ede8d4](https://linux-hardware.org/?probe=6406ede8d4) | Nov 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [9222374410](https://linux-hardware.org/?probe=9222374410) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| ASUSTek       | GA35DX                      | [1a9eef3748](https://linux-hardware.org/?probe=1a9eef3748) | Nov 02, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [9893d57e1b](https://linux-hardware.org/?probe=9893d57e1b) | Nov 01, 2023 |
| ASUSTek       | M5A87                       | [b254c30981](https://linux-hardware.org/?probe=b254c30981) | Nov 01, 2023 |
| MSI           | X370 GAMING PRO             | [c8ba0de51d](https://linux-hardware.org/?probe=c8ba0de51d) | Oct 31, 2023 |
| HP            | ProLiant ML310e Gen8        | [fa410ee23c](https://linux-hardware.org/?probe=fa410ee23c) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | [16417bdac2](https://linux-hardware.org/?probe=16417bdac2) | Oct 29, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| ASUSTek       | GA35DX                      | [ae8894002e](https://linux-hardware.org/?probe=ae8894002e) | Oct 27, 2023 |
| Gigabyte      | GA-990XA-UD3                | [0990fc4382](https://linux-hardware.org/?probe=0990fc4382) | Oct 26, 2023 |
| Gigabyte      | B85M-D2V                    | [572daeb059](https://linux-hardware.org/?probe=572daeb059) | Oct 19, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [e550587c85](https://linux-hardware.org/?probe=e550587c85) | Oct 14, 2023 |
| MSI           | B450 TOMAHAWK               | [729234c285](https://linux-hardware.org/?probe=729234c285) | Oct 14, 2023 |
| HP            | 3048h                       | [79350e657a](https://linux-hardware.org/?probe=79350e657a) | Oct 12, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | B550M DS3H                  | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [541d9a0542](https://linux-hardware.org/?probe=541d9a0542) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| ASUSTek       | P5Q3                        | [5d51aca6b2](https://linux-hardware.org/?probe=5d51aca6b2) | Oct 08, 2023 |
| ASUSTek       | P5Q3                        | [9beb6f3b26](https://linux-hardware.org/?probe=9beb6f3b26) | Oct 08, 2023 |
| Gigabyte      | B450M DS3H V2               | [4f2f37c5ba](https://linux-hardware.org/?probe=4f2f37c5ba) | Oct 08, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f6fc0aee5b](https://linux-hardware.org/?probe=f6fc0aee5b) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [c0c10b1767](https://linux-hardware.org/?probe=c0c10b1767) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK               | [7d321bffa1](https://linux-hardware.org/?probe=7d321bffa1) | Oct 07, 2023 |
| ASRock        | FM2A68M-DG3+                | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ab02b2a3e7](https://linux-hardware.org/?probe=ab02b2a3e7) | Oct 04, 2023 |
| HP            | 198E                        | [a311728a5f](https://linux-hardware.org/?probe=a311728a5f) | Sep 29, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [013801fc61](https://linux-hardware.org/?probe=013801fc61) | Sep 28, 2023 |
| Gigabyte      | H610M H DDR4                | [c09e747a85](https://linux-hardware.org/?probe=c09e747a85) | Sep 27, 2023 |
| OEM           | B75 Ver:1.41                | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| HP            | 0B4Ch D                     | [f5ed151e3e](https://linux-hardware.org/?probe=f5ed151e3e) | Sep 24, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| ASRock        | Z590M Pro4                  | [d63be526d2](https://linux-hardware.org/?probe=d63be526d2) | Sep 18, 2023 |
| ASUSTek       | B75M-PLUS                   | [6cc800f5dc](https://linux-hardware.org/?probe=6cc800f5dc) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| HP            | 0B4Ch D                     | [de53daa0f8](https://linux-hardware.org/?probe=de53daa0f8) | Sep 12, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| ASUSTek       | H110M-D                     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Alienware     | 07JNH0 A00                  | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Dell          | 0427JK A00                  | [d6a8fc3557](https://linux-hardware.org/?probe=d6a8fc3557) | Sep 08, 2023 |
| ASUSTek       | B75M-PLUS                   | [394dd17b98](https://linux-hardware.org/?probe=394dd17b98) | Sep 07, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| ASRock        | Z490 Phantom Gaming 4/ac    | [5fa23571c9](https://linux-hardware.org/?probe=5fa23571c9) | Sep 04, 2023 |
| Alienware     | 07JNH0 A00                  | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| Gigabyte      | B75M-D3P                    | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Gigabyte      | 990FXA-UD3                  | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| Colorful T... | A320M-K PRO YV14            | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [58d50740e7](https://linux-hardware.org/?probe=58d50740e7) | Aug 24, 2023 |
| ASRock        | B550M-ITX/ac                | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| ASRock        | B550M-HDV                   | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| Gigabyte      | GA-MA770-UD3                | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| ASUSTek       | M4A77TD                     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| Alienware     | 07JNH0 A00                  | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Intel         | DX58OG AAG10926-205         | [cb3a9289f9](https://linux-hardware.org/?probe=cb3a9289f9) | Aug 13, 2023 |
| HP            | 1589                        | [1a38154020](https://linux-hardware.org/?probe=1a38154020) | Aug 12, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [c2b7b4e760](https://linux-hardware.org/?probe=c2b7b4e760) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| ASUSTek       | Z97-PRO/USB                 | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| HP            | ProLiant MicroServer Gen... | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Dell          | 082WXT A03                  | [27a50c4491](https://linux-hardware.org/?probe=27a50c4491) | Aug 03, 2023 |
| MSI           | X370 GAMING PRO             | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Biostar       | A320MH                      | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HP            | 3048h                       | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| Gigabyte      | B550M DS3H                  | [9d891afae0](https://linux-hardware.org/?probe=9d891afae0) | Jul 26, 2023 |
| HP            | 1589                        | [5c0bd1ec07](https://linux-hardware.org/?probe=5c0bd1ec07) | Jul 24, 2023 |
| MSI           | X58 Pro-E                   | [01f822dec1](https://linux-hardware.org/?probe=01f822dec1) | Jul 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [7b6300dfc7](https://linux-hardware.org/?probe=7b6300dfc7) | Jul 20, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [65da6837ae](https://linux-hardware.org/?probe=65da6837ae) | Jul 20, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [a2779c6ac8](https://linux-hardware.org/?probe=a2779c6ac8) | Jul 19, 2023 |
| ASUSTek       | P5B-Deluxe                  | [fe065234a9](https://linux-hardware.org/?probe=fe065234a9) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| Gigabyte      | G41MT-S2P                   | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [78f620581b](https://linux-hardware.org/?probe=78f620581b) | Jul 14, 2023 |
| MSI           | B450 TOMAHAWK               | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | [c00debe968](https://linux-hardware.org/?probe=c00debe968) | Jul 08, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | [a72d3eff75](https://linux-hardware.org/?probe=a72d3eff75) | Jul 08, 2023 |
| HP            | 8B3B A                      | [b003988978](https://linux-hardware.org/?probe=b003988978) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [427fc931a0](https://linux-hardware.org/?probe=427fc931a0) | Jul 04, 2023 |
| HP            | 8055                        | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| HP            | 1589                        | [dcb3289360](https://linux-hardware.org/?probe=dcb3289360) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| Gigabyte      | EG45M-DS2H                  | [b9b25df5a3](https://linux-hardware.org/?probe=b9b25df5a3) | Jun 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| ASRock        | A320M-HD                    | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Pegatron      | JESSE                       | [fa09a247a7](https://linux-hardware.org/?probe=fa09a247a7) | Jun 19, 2023 |
| Acer          | Aspire TC-780               | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | [ed8bd3839f](https://linux-hardware.org/?probe=ed8bd3839f) | Jun 12, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| ASUSTek       | Z77-A                       | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| ASRock        | J3355B-ITX                  | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASUSTek       | Z77-A                       | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASRock        | B450M Pro4 R2.0             | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| ASRock        | J3355B-ITX                  | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9b0a8de7a1](https://linux-hardware.org/?probe=9b0a8de7a1) | Feb 02, 2023 |
| Fujitsu Si... | D2399 S26361-D2399          | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.14.21-150500.53-default      | 30       | 19.11%  |
| 5.14.21-150500.55.52-default   | 24       | 15.29%  |
| 5.14.21-150500.55.19-default   | 18       | 11.46%  |
| 5.14.21-150500.55.36-default   | 15       | 9.55%   |
| 5.14.21-150500.55.39-default   | 13       | 8.28%   |
| 5.14.21-150500.55.7-default    | 9        | 5.73%   |
| 5.14.21-150500.55.49-default   | 8        | 5.1%    |
| 5.14.21-150500.55.31-default   | 8        | 5.1%    |
| 5.14.21-150500.55.28-default   | 7        | 4.46%   |
| 5.14.21-150500.55.59-default   | 4        | 2.55%   |
| 5.14.21-150500.55.12-default   | 4        | 2.55%   |
| 5.14.21-150500.52-default      | 4        | 2.55%   |
| 5.14.21-150500.55.44-default   | 3        | 1.91%   |
| 5.14.21-150400.24.18-default   | 2        | 1.27%   |
| 6.6.3-1-default                | 1        | 0.64%   |
| 6.5.9-lp155.2-default          | 1        | 0.64%   |
| 6.5.4-1-default                | 1        | 0.64%   |
| 6.4.4-lp154.2.g919c802-default | 1        | 0.64%   |
| 5.14.21-150500.43-default      | 1        | 0.64%   |
| 5.14.21-150500.37-default      | 1        | 0.64%   |
| 5.14.21-150400.24.55-default   | 1        | 0.64%   |
| 5.14.21-150400.24.46-default   | 1        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.21 | 135      | 97.12%  |
| 6.6.3   | 1        | 0.72%   |
| 6.5.9   | 1        | 0.72%   |
| 6.5.4   | 1        | 0.72%   |
| 6.4.4   | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 135      | 97.12%  |
| 6.5     | 2        | 1.44%   |
| 6.6     | 1        | 0.72%   |
| 6.4     | 1        | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 139      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 113      | 80.14%  |
| GNOME   | 19       | 13.48%  |
| XFCE    | 3        | 2.13%   |
| MATE    | 2        | 1.42%   |
| Unknown | 2        | 1.42%   |
| ICEWM   | 1        | 0.71%   |
| Budgie  | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 126      | 88.73%  |
| Wayland | 10       | 7.04%   |
| Tty     | 6        | 4.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 91       | 64.54%  |
| SDDM    | 41       | 29.08%  |
| LightDM | 6        | 4.26%   |
| XDM     | 2        | 1.42%   |
| GDM     | 1        | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 48       | 34.29%  |
| de_DE | 36       | 25.71%  |
| POSIX | 11       | 7.86%   |
| ru_RU | 9        | 6.43%   |
| pt_BR | 8        | 5.71%   |
| nl_NL | 4        | 2.86%   |
| es_ES | 4        | 2.86%   |
| pl_PL | 3        | 2.14%   |
| fr_FR | 3        | 2.14%   |
| C     | 3        | 2.14%   |
| it_IT | 2        | 1.43%   |
| en_GB | 2        | 1.43%   |
| zh_CN | 1        | 0.71%   |
| sk_SK | 1        | 0.71%   |
| fi_FI | 1        | 0.71%   |
| es_DO | 1        | 0.71%   |
| el_GR | 1        | 0.71%   |
| da_DK | 1        | 0.71%   |
| ar_AE | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 106      | 75.71%  |
| EFI  | 34       | 24.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 105      | 74.47%  |
| Ext4  | 30       | 21.28%  |
| Xfs   | 5        | 3.55%   |
| Zfs   | 1        | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 64.29%  |
| GPT     | 42       | 30%     |
| MBR     | 8        | 5.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 86.43%  |
| Yes       | 19       | 13.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 84.89%  |
| Yes       | 21       | 15.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 32       | 23.02%  |
| Gigabyte Technology | 26       | 18.71%  |
| Hewlett-Packard     | 17       | 12.23%  |
| ASRock              | 17       | 12.23%  |
| MSI                 | 13       | 9.35%   |
| Lenovo              | 7        | 5.04%   |
| Dell                | 7        | 5.04%   |
| Fujitsu             | 4        | 2.88%   |
| Biostar             | 3        | 2.16%   |
| Intel               | 2        | 1.44%   |
| HC Technology.      | 2        | 1.44%   |
| Pegatron            | 1        | 0.72%   |
| OEM                 | 1        | 0.72%   |
| GEEKOM              | 1        | 0.72%   |
| Fujitsu Siemens     | 1        | 0.72%   |
| Foxconn             | 1        | 0.72%   |
| Colorful Technology | 1        | 0.72%   |
| AMI                 | 1        | 0.72%   |
| Alienware           | 1        | 0.72%   |
| Acer                | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS M5A97 R2.0                             | 3        | 2.16%   |
| HP Z420 Workstation                         | 2        | 1.44%   |
| HC Technology. HCAR5000-MI                  | 2        | 1.44%   |
| Gigabyte B550M DS3H                         | 2        | 1.44%   |
| ASUS ROG STRIX X570-E GAMING                | 2        | 1.44%   |
| Pegatron NY603AA-ABA 300-1007               | 1        | 0.72%   |
| OEM B75                                     | 1        | 0.72%   |
| MSI MS-7D74                                 | 1        | 0.72%   |
| MSI MS-7D54                                 | 1        | 0.72%   |
| MSI MS-7C95                                 | 1        | 0.72%   |
| MSI MS-7C91                                 | 1        | 0.72%   |
| MSI MS-7C80                                 | 1        | 0.72%   |
| MSI MS-7C52                                 | 1        | 0.72%   |
| MSI MS-7C02                                 | 1        | 0.72%   |
| MSI MS-7B89                                 | 1        | 0.72%   |
| MSI MS-7B85                                 | 1        | 0.72%   |
| MSI MS-7B17                                 | 1        | 0.72%   |
| MSI MS-7A33                                 | 1        | 0.72%   |
| MSI MS-7978                                 | 1        | 0.72%   |
| MSI MS-7522                                 | 1        | 0.72%   |
| Lenovo V520S-08IKL Desktop 10NN000CBP       | 1        | 0.72%   |
| Lenovo ThinkCentre M92p 3227GQ8             | 1        | 0.72%   |
| Lenovo ThinkCentre M78 10BR0005US           | 1        | 0.72%   |
| Lenovo ThinkCentre M720t 10SQ0070GE         | 1        | 0.72%   |
| Lenovo ThinkCentre M700 10KN003LBP          | 1        | 0.72%   |
| Lenovo ThinkCentre Edge 91Z 7075K7G         | 1        | 0.72%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T100BHMZ | 1        | 0.72%   |
| Intel Nobilis                               | 1        | 0.72%   |
| Intel DH87RL AAG74240-403                   | 1        | 0.72%   |
| HP Z820 Workstation                         | 1        | 0.72%   |
| HP Z440 Workstation                         | 1        | 0.72%   |
| HP Z400 Workstation                         | 1        | 0.72%   |
| HP ProLiant ML350 G6                        | 1        | 0.72%   |
| HP ProLiant ML310e Gen8                     | 1        | 0.72%   |
| HP ProLiant ML10 v2                         | 1        | 0.72%   |
| HP ProLiant MicroServer Gen8                | 1        | 0.72%   |
| HP ProDesk 400 G2 MT                        | 1        | 0.72%   |
| HP Pavilion Desktop TP01-4xxx               | 1        | 0.72%   |
| HP EliteDesk 800 G2 DM 35W                  | 1        | 0.72%   |
| HP Desktop M01-F3xxx                        | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Lenovo ThinkCentre         | 5        | 3.6%    |
| Dell OptiPlex              | 5        | 3.6%    |
| ASUS ROG                   | 5        | 3.6%    |
| ASUS PRIME                 | 5        | 3.6%    |
| HP ProLiant                | 4        | 2.88%   |
| HP Compaq                  | 3        | 2.16%   |
| ASUS M5A97                 | 3        | 2.16%   |
| HP Z420                    | 2        | 1.44%   |
| HC Technology. HCAR5000-MI | 2        | 1.44%   |
| Gigabyte B550M             | 2        | 1.44%   |
| Gigabyte B450M             | 2        | 1.44%   |
| Fujitsu ESPRIMO            | 2        | 1.44%   |
| ASRock Z790                | 2        | 1.44%   |
| ASRock Z390                | 2        | 1.44%   |
| Pegatron NY603AA-ABA       | 1        | 0.72%   |
| OEM B75                    | 1        | 0.72%   |
| MSI MS-7D74                | 1        | 0.72%   |
| MSI MS-7D54                | 1        | 0.72%   |
| MSI MS-7C95                | 1        | 0.72%   |
| MSI MS-7C91                | 1        | 0.72%   |
| MSI MS-7C80                | 1        | 0.72%   |
| MSI MS-7C52                | 1        | 0.72%   |
| MSI MS-7C02                | 1        | 0.72%   |
| MSI MS-7B89                | 1        | 0.72%   |
| MSI MS-7B85                | 1        | 0.72%   |
| MSI MS-7B17                | 1        | 0.72%   |
| MSI MS-7A33                | 1        | 0.72%   |
| MSI MS-7978                | 1        | 0.72%   |
| MSI MS-7522                | 1        | 0.72%   |
| Lenovo V520S-08IKL         | 1        | 0.72%   |
| Lenovo IdeaCentre          | 1        | 0.72%   |
| Intel Nobilis              | 1        | 0.72%   |
| Intel DH87RL               | 1        | 0.72%   |
| HP Z820                    | 1        | 0.72%   |
| HP Z440                    | 1        | 0.72%   |
| HP Z400                    | 1        | 0.72%   |
| HP ProDesk                 | 1        | 0.72%   |
| HP Pavilion                | 1        | 0.72%   |
| HP EliteDesk               | 1        | 0.72%   |
| HP Desktop                 | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 15       | 10.79%  |
| 2020 | 13       | 9.35%   |
| 2012 | 13       | 9.35%   |
| 2015 | 12       | 8.63%   |
| 2013 | 11       | 7.91%   |
| 2021 | 10       | 7.19%   |
| 2010 | 9        | 6.47%   |
| 2022 | 7        | 5.04%   |
| 2011 | 7        | 5.04%   |
| 2023 | 6        | 4.32%   |
| 2014 | 6        | 4.32%   |
| 2019 | 5        | 3.6%    |
| 2016 | 5        | 3.6%    |
| 2009 | 5        | 3.6%    |
| 2008 | 5        | 3.6%    |
| 2017 | 4        | 2.88%   |
| 2007 | 4        | 2.88%   |
| 2024 | 1        | 0.72%   |
| 2006 | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 139      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 136      | 97.84%  |
| Enabled  | 3        | 2.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 139      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 23.57%  |
| 32.01-64.0  | 28       | 20%     |
| 8.01-16.0   | 27       | 19.29%  |
| 4.01-8.0    | 24       | 17.14%  |
| 3.01-4.0    | 14       | 10%     |
| 64.01-256.0 | 10       | 7.14%   |
| 24.01-32.0  | 3        | 2.14%   |
| 1.01-2.0    | 1        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 58       | 38.41%  |
| 4.01-8.0   | 28       | 18.54%  |
| 3.01-4.0   | 28       | 18.54%  |
| 1.01-2.0   | 26       | 17.22%  |
| 8.01-16.0  | 5        | 3.31%   |
| 0.51-1.0   | 3        | 1.99%   |
| 16.01-24.0 | 2        | 1.32%   |
| 24.01-32.0 | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 32.86%  |
| 2      | 38       | 27.14%  |
| 3      | 33       | 23.57%  |
| 4      | 11       | 7.86%   |
| 5      | 6        | 4.29%   |
| 6      | 5        | 3.57%   |
| 8      | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 81       | 58.27%  |
| No        | 58       | 41.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 61.7%   |
| Yes       | 54       | 38.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 66.91%  |
| Yes       | 46       | 33.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Germany                | 40       | 28.78%  |
| USA                    | 28       | 20.14%  |
| Russia                 | 10       | 7.19%   |
| Brazil                 | 8        | 5.76%   |
| Switzerland            | 4        | 2.88%   |
| Netherlands            | 4        | 2.88%   |
| Poland                 | 3        | 2.16%   |
| Greece                 | 3        | 2.16%   |
| Finland                | 3        | 2.16%   |
| Canada                 | 3        | 2.16%   |
| UK                     | 2        | 1.44%   |
| Sweden                 | 2        | 1.44%   |
| Italy                  | 2        | 1.44%   |
| France                 | 2        | 1.44%   |
| Belgium                | 2        | 1.44%   |
| Australia              | 2        | 1.44%   |
| Vietnam                | 1        | 0.72%   |
| Ukraine                | 1        | 0.72%   |
| Spain                  | 1        | 0.72%   |
| South Korea            | 1        | 0.72%   |
| South Africa           | 1        | 0.72%   |
| Slovenia               | 1        | 0.72%   |
| Slovakia               | 1        | 0.72%   |
| Portugal               | 1        | 0.72%   |
| Mexico                 | 1        | 0.72%   |
| Martinique             | 1        | 0.72%   |
| Indonesia              | 1        | 0.72%   |
| Hong Kong              | 1        | 0.72%   |
| Guatemala              | 1        | 0.72%   |
| Greenland              | 1        | 0.72%   |
| Colombia               | 1        | 0.72%   |
| China                  | 1        | 0.72%   |
| Bulgaria               | 1        | 0.72%   |
| Bosnia and Herzegovina | 1        | 0.72%   |
| Austria                | 1        | 0.72%   |
| Argentina              | 1        | 0.72%   |
| Algeria                | 1        | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Munich             | 3        | 2.1%    |
| Zurich             | 2        | 1.4%    |
| St Petersburg      | 2        | 1.4%    |
| Sacramento         | 2        | 1.4%    |
| Nuremberg          | 2        | 1.4%    |
| Enschede           | 2        | 1.4%    |
| Cherry Hill        | 2        | 1.4%    |
| Bremen             | 2        | 1.4%    |
| Berlin             | 2        | 1.4%    |
| Zuchwil            | 1        | 0.7%    |
| Zetel              | 1        | 0.7%    |
| Yakutsk            | 1        | 0.7%    |
| Wuppertal          | 1        | 0.7%    |
| West Hills         | 1        | 0.7%    |
| West Bend          | 1        | 0.7%    |
| Warsaw             | 1        | 0.7%    |
| Warrenton          | 1        | 0.7%    |
| Waren              | 1        | 0.7%    |
| Vlkanova           | 1        | 0.7%    |
| Vienna             | 1        | 0.7%    |
| Victoria           | 1        | 0.7%    |
| Västerås         | 1        | 0.7%    |
| Vantaa             | 1        | 0.7%    |
| Valencia           | 1        | 0.7%    |
| Usinsk             | 1        | 0.7%    |
| Timmins            | 1        | 0.7%    |
| Thessaloniki       | 1        | 0.7%    |
| The Villages       | 1        | 0.7%    |
| Tacoma             | 1        | 0.7%    |
| Sydney             | 1        | 0.7%    |
| Sumaré            | 1        | 0.7%    |
| Stuttgart          | 1        | 0.7%    |
| Stockholm          | 1        | 0.7%    |
| Staraya Russa      | 1        | 0.7%    |
| Soltau             | 1        | 0.7%    |
| Sofia              | 1        | 0.7%    |
| Soest              | 1        | 0.7%    |
| Sisimiut           | 1        | 0.7%    |
| Shanghai           | 1        | 0.7%    |
| Sesto San Giovanni | 1        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives  | Percent |
|-----------------------------|----------|---------|---------|
| Seagate                     | 50       | 77      | 18.73%  |
| Samsung Electronics         | 44       | 75      | 16.48%  |
| WDC                         | 42       | 82      | 15.73%  |
| Kingston                    | 18       | 25      | 6.74%   |
| Crucial                     | 15       | 17      | 5.62%   |
| Sandisk                     | 12       | 17      | 4.49%   |
| Hitachi                     | 11       | 11      | 4.12%   |
| Toshiba                     | 10       | 12      | 3.75%   |
| Intenso                     | 7        | 8       | 2.62%   |
| Silicon Motion              | 5        | 5       | 1.87%   |
| A-DATA Technology           | 4        | 4       | 1.5%    |
| Unknown                     | 3        | 3       | 1.12%   |
| SK hynix                    | 3        | 3       | 1.12%   |
| Intel                       | 3        | 4       | 1.12%   |
| XrayDisk                    | 2        | 2       | 0.75%   |
| SPCC                        | 2        | 2       | 0.75%   |
| SABRENT                     | 2        | 2       | 0.75%   |
| Phison Electronics          | 2        | 2       | 0.75%   |
| Micron Technology           | 2        | 3       | 0.75%   |
| Leven                       | 2        | 2       | 0.75%   |
| Kingston Technology Company | 2        | 3       | 0.75%   |
| HGST                        | 2        | 3       | 0.75%   |
| Hewlett-Packard             | 2        | 2       | 0.75%   |
| XSTAR                       | 1        | 1       | 0.37%   |
| T-FORCE                     | 1        | 1       | 0.37%   |
| Synology                    | 1        | 1       | 0.37%   |
| StoreJet                    | 1        | 1       | 0.37%   |
| RESCUE                      | 1        | 1       | 0.37%   |
| Radeon                      | 1        | 1       | 0.37%   |
| PNY                         | 1        | 2       | 0.37%   |
| Netac                       | 1        | 2       | 0.37%   |
| Micron/Crucial Technology   | 1        | 1       | 0.37%   |
| LITEON                      | 1        | 1       | 0.37%   |
| KIOXIA                      | 1        | 1       | 0.37%   |
| HS-SSD-E100                 | 1        | 1       | 0.37%   |
| HL-DT-ST                    | 1        | Unknown | 0.37%   |
| Fujitsu                     | 1        | 2       | 0.37%   |
| FIKWOT                      | 1        | 1       | 0.37%   |
| Fanxiang                    | 1        | 2       | 0.37%   |
| China                       | 1        | 1       | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 9        | 2.94%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5        | 1.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4        | 1.31%   |
| Samsung SSD 870 EVO 1TB                               | 4        | 1.31%   |
| Kingston SA400S37480G 480GB SSD                       | 4        | 1.31%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3        | 0.98%   |
| Kingston SV300S37A120G 120GB SSD                      | 3        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                       | 3        | 0.98%   |
| Kingston SA400S37120G 120GB SSD                       | 3        | 0.98%   |
| Crucial CT275MX300SSD1 275GB                          | 3        | 0.98%   |
| WDC WD10EZRX-00A8LB0 1TB                              | 2        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 0.65%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 2        | 0.65%   |
| WDC WD1003FZEX-00K3CA0 1TB                            | 2        | 0.65%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2        | 0.65%   |
| Toshiba HDWD130 3TB                                   | 2        | 0.65%   |
| Toshiba DT01ACA100 1TB                                | 2        | 0.65%   |
| Toshiba DT01ACA050 500GB                              | 2        | 0.65%   |
| Seagate ST8000DM004-2U9188 8TB                        | 2        | 0.65%   |
| Seagate ST3500418AS 500GB                             | 2        | 0.65%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                        | 2        | 0.65%   |
| Sandisk WD Black SN850 512GB                          | 2        | 0.65%   |
| Samsung SSD 990 PRO 2TB                               | 2        | 0.65%   |
| Samsung SSD 870 EVO 2TB                               | 2        | 0.65%   |
| Samsung SSD 860 EVO 4TB                               | 2        | 0.65%   |
| Samsung SSD 850 EVO 500GB                             | 2        | 0.65%   |
| Samsung SSD 850 EVO 250GB                             | 2        | 0.65%   |
| Samsung SSD 840 EVO 250GB                             | 2        | 0.65%   |
| Samsung SSD 840 EVO 120GB                             | 2        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 2        | 0.65%   |
| Samsung HD502HJ 500GB                                 | 2        | 0.65%   |
| SABRENT Disk 1TB                                      | 2        | 0.65%   |
| Hitachi HDS721050CLA662 500GB                         | 2        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                          | 2        | 0.65%   |
| Crucial CT480BX500SSD1 480GB                          | 2        | 0.65%   |
| Crucial CT250MX500SSD1 250GB                          | 2        | 0.65%   |
| Crucial CT1000BX500SSD1 1TB                           | 2        | 0.65%   |
| XSTAR SSD 128GB                                       | 1        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 75     | 37.12%  |
| WDC                 | 40       | 71     | 30.3%   |
| Samsung Electronics | 11       | 12     | 8.33%   |
| Hitachi             | 11       | 11     | 8.33%   |
| Toshiba             | 9        | 11     | 6.82%   |
| Unknown             | 2        | 2      | 1.52%   |
| SABRENT             | 2        | 2      | 1.52%   |
| HGST                | 2        | 3      | 1.52%   |
| XrayDisk            | 1        | 1      | 0.76%   |
| Synology            | 1        | 1      | 0.76%   |
| Hewlett-Packard     | 1        | 1      | 0.76%   |
| Fujitsu             | 1        | 2      | 0.76%   |
| ASMT                | 1        | 2      | 0.76%   |
| Apple               | 1        | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 40     | 23.47%  |
| Kingston            | 17       | 23     | 17.35%  |
| Crucial             | 15       | 17     | 15.31%  |
| SanDisk             | 6        | 6      | 6.12%   |
| Intenso             | 6        | 6      | 6.12%   |
| WDC                 | 4        | 11     | 4.08%   |
| A-DATA Technology   | 4        | 4      | 4.08%   |
| Intel               | 3        | 4      | 3.06%   |
| SPCC                | 2        | 2      | 2.04%   |
| Leven               | 2        | 2      | 2.04%   |
| XSTAR               | 1        | 1      | 1.02%   |
| XrayDisk            | 1        | 1      | 1.02%   |
| Toshiba             | 1        | 1      | 1.02%   |
| StoreJet            | 1        | 1      | 1.02%   |
| SK hynix            | 1        | 1      | 1.02%   |
| Radeon              | 1        | 1      | 1.02%   |
| PNY                 | 1        | 2      | 1.02%   |
| Netac               | 1        | 2      | 1.02%   |
| Micron Technology   | 1        | 1      | 1.02%   |
| LITEON              | 1        | 1      | 1.02%   |
| Hewlett-Packard     | 1        | 1      | 1.02%   |
| FIKWOT              | 1        | 1      | 1.02%   |
| Fanxiang            | 1        | 2      | 1.02%   |
| China               | 1        | 1      | 1.02%   |
| BAITITON            | 1        | 1      | 1.02%   |
| AMD                 | 1        | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 94       | 195    | 43.93%  |
| SSD     | 78       | 134    | 36.45%  |
| NVMe    | 36       | 55     | 16.82%  |
| Unknown | 6        | 6      | 2.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 128      | 317    | 71.91%  |
| NVMe | 36       | 55     | 20.22%  |
| SAS  | 14       | 18     | 7.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 84       | 148    | 43.52%  |
| 0.51-1.0   | 56       | 91     | 29.02%  |
| 1.01-2.0   | 27       | 51     | 13.99%  |
| 3.01-4.0   | 15       | 24     | 7.77%   |
| 4.01-10.0  | 5        | 9      | 2.59%   |
| 2.01-3.0   | 4        | 4      | 2.07%   |
| 10.01-20.0 | 2        | 2      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 58       | 40%     |
| 1001-2000      | 27       | 18.62%  |
| 2001-3000      | 18       | 12.41%  |
| 251-500        | 13       | 8.97%   |
| 501-1000       | 13       | 8.97%   |
| 101-250        | 10       | 6.9%    |
| 51-100         | 3        | 2.07%   |
| Unknown        | 2        | 1.38%   |
| 1-20           | 1        | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 37       | 24.34%  |
| 51-100         | 25       | 16.45%  |
| 501-1000       | 21       | 13.82%  |
| 251-500        | 20       | 13.16%  |
| 1001-2000      | 18       | 11.84%  |
| 21-50          | 10       | 6.58%   |
| More than 3000 | 8        | 5.26%   |
| 1-20           | 7        | 4.61%   |
| 2001-3000      | 4        | 2.63%   |
| Unknown        | 2        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 22.22%  |
| Kingston SA400S37120G 120GB SSD                  | 2        | 4      | 22.22%  |
| Toshiba MD04ACA400 4TB                           | 1        | 1      | 11.11%  |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1        | 1      | 11.11%  |
| Seagate ST4000NM0035-1V4107 4TB                  | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 840 EVO 120GB            | 1        | 1      | 11.11%  |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 50%     |
| Kingston            | 2        | 4      | 25%     |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 80%     |
| Toshiba | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 62.5%   |
| SSD  | 3        | 6      | 37.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 93       | 260    | 62.84%  |
| Works    | 47       | 117    | 31.76%  |
| Malfunc  | 7        | 11     | 4.73%   |
| Failed   | 1        | 2      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 83       | 41.09%  |
| AMD                           | 55       | 27.23%  |
| Samsung Electronics           | 16       | 7.92%   |
| ASMedia Technology            | 8        | 3.96%   |
| SanDisk                       | 6        | 2.97%   |
| JMicron Technology            | 6        | 2.97%   |
| Silicon Motion                | 5        | 2.48%   |
| Marvell Technology Group      | 4        | 1.98%   |
| Kingston Technology Company   | 3        | 1.49%   |
| SK hynix                      | 2        | 0.99%   |
| Phison Electronics            | 2        | 0.99%   |
| Broadcom / LSI                | 2        | 0.99%   |
| VIA Technologies              | 1        | 0.5%    |
| Seagate Technology            | 1        | 0.5%    |
| Nvidia                        | 1        | 0.5%    |
| Micron/Crucial Technology     | 1        | 0.5%    |
| Micron Technology             | 1        | 0.5%    |
| KIOXIA                        | 1        | 0.5%    |
| Integrated Technology Express | 1        | 0.5%    |
| ADATA Technology              | 1        | 0.5%    |
| Adaptec                       | 1        | 0.5%    |
| Unknown                       | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 9.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10       | 3.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 10       | 3.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9        | 3.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9        | 3.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 9        | 3.53%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8        | 3.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7        | 2.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6        | 2.35%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5        | 1.96%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 1.96%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4        | 1.57%   |
| Intel SATA Controller [RAID Mode]                                              | 4        | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4        | 1.57%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.18%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 1.18%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 3        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 3        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 3        | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 0.78%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 2        | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2        | 0.78%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 0.78%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2        | 0.78%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.78%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 123      | 58.57%  |
| NVMe | 36       | 17.14%  |
| IDE  | 36       | 17.14%  |
| RAID | 10       | 4.76%   |
| SAS  | 4        | 1.9%    |
| SCSI | 1        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 83       | 59.71%  |
| AMD    | 56       | 40.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 4.32%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 2.16%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 2.16%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 2.16%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 2.16%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.16%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.16%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz          | 2        | 1.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.44%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.44%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.44%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2        | 1.44%   |
| AMD FX-8370 Eight-Core Processor            | 2        | 1.44%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.44%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.72%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz         | 1        | 0.72%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.72%   |
| Intel Xeon CPU 3050 @ 2.13GHz               | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.72%   |
| Intel Pentium CPU G850 @ 2.90GHz            | 1        | 0.72%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.72%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.72%   |
| Intel Core i9-9900X CPU @ 3.50GHz           | 1        | 0.72%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.72%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.72%   |
| Intel Core i7-8086K CPU @ 4.00GHz           | 1        | 0.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.72%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i7-14700K                        | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 15.11%  |
| Intel Core i7           | 17       | 12.23%  |
| AMD Ryzen 5             | 12       | 8.63%   |
| Other                   | 10       | 7.19%   |
| Intel Xeon              | 10       | 7.19%   |
| AMD Ryzen 7             | 9        | 6.47%   |
| AMD FX                  | 8        | 5.76%   |
| AMD Ryzen 9             | 7        | 5.04%   |
| Intel Core i3           | 6        | 4.32%   |
| Intel Celeron           | 5        | 3.6%    |
| Intel Core 2 Quad       | 4        | 2.88%   |
| Intel Pentium           | 3        | 2.16%   |
| Intel Core 2 Duo        | 3        | 2.16%   |
| AMD A8                  | 3        | 2.16%   |
| Intel Pentium Dual-Core | 2        | 1.44%   |
| Intel Core i9           | 2        | 1.44%   |
| AMD Ryzen 3             | 2        | 1.44%   |
| AMD Phenom II X4        | 2        | 1.44%   |
| AMD A4                  | 2        | 1.44%   |
| AMD Ryzen 5 PRO         | 1        | 0.72%   |
| AMD Ryzen 3 PRO         | 1        | 0.72%   |
| AMD Phenom II X6        | 1        | 0.72%   |
| AMD Phenom              | 1        | 0.72%   |
| AMD Athlon X4           | 1        | 0.72%   |
| AMD Athlon II X4        | 1        | 0.72%   |
| AMD Athlon II X3        | 1        | 0.72%   |
| AMD Athlon II X2        | 1        | 0.72%   |
| AMD Athlon 64 X2        | 1        | 0.72%   |
| AMD Athlon              | 1        | 0.72%   |
| AMD A6                  | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 53       | 38.13%  |
| 2      | 26       | 18.71%  |
| 6      | 23       | 16.55%  |
| 8      | 14       | 10.07%  |
| 12     | 9        | 6.47%   |
| 16     | 5        | 3.6%    |
| 3      | 3        | 2.16%   |
| 1      | 3        | 2.16%   |
| 24     | 1        | 0.72%   |
| 20     | 1        | 0.72%   |
| 10     | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 97.84%  |
| 2      | 3        | 2.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 84       | 60.43%  |
| 1      | 55       | 39.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 139      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 84       | 59.57%  |
| 0x1067a    | 5        | 3.55%   |
| 0xb0671    | 4        | 2.84%   |
| 0xa0671    | 3        | 2.13%   |
| 0x906e9    | 3        | 2.13%   |
| 0x506e3    | 3        | 2.13%   |
| 0x306c3    | 3        | 2.13%   |
| 0x0a50000d | 3        | 2.13%   |
| 0x906ea    | 2        | 1.42%   |
| 0x206d7    | 2        | 1.42%   |
| 0x206a7    | 2        | 1.42%   |
| 0x08701021 | 2        | 1.42%   |
| 0x08608103 | 2        | 1.42%   |
| 0x0800820d | 2        | 1.42%   |
| 0x06001119 | 2        | 1.42%   |
| 0xa0655    | 1        | 0.71%   |
| 0x906ed    | 1        | 0.71%   |
| 0x806c2    | 1        | 0.71%   |
| 0x706a1    | 1        | 0.71%   |
| 0x50654    | 1        | 0.71%   |
| 0x306a9    | 1        | 0.71%   |
| 0x106e5    | 1        | 0.71%   |
| 0x10677    | 1        | 0.71%   |
| 0x0a601203 | 1        | 0.71%   |
| 0x0a50000c | 1        | 0.71%   |
| 0x0a20120e | 1        | 0.71%   |
| 0x0a20120a | 1        | 0.71%   |
| 0x08701030 | 1        | 0.71%   |
| 0x08600106 | 1        | 0.71%   |
| 0x08101016 | 1        | 0.71%   |
| 0x08001138 | 1        | 0.71%   |
| 0x06003106 | 1        | 0.71%   |
| 0x06000852 | 1        | 0.71%   |
| 0x01000095 | 1        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 14       | 10.07%  |
| KabyLake         | 12       | 8.63%   |
| IvyBridge        | 11       | 7.91%   |
| SandyBridge      | 10       | 7.19%   |
| Piledriver       | 9        | 6.47%   |
| Penryn           | 9        | 6.47%   |
| Haswell          | 9        | 6.47%   |
| Zen 2            | 7        | 5.04%   |
| K10              | 7        | 5.04%   |
| Unknown          | 7        | 5.04%   |
| Skylake          | 6        | 4.32%   |
| Zen              | 5        | 3.6%    |
| Nehalem          | 5        | 3.6%    |
| Alderlake Hybrid | 4        | 2.88%   |
| Zen+             | 3        | 2.16%   |
| Icelake          | 3        | 2.16%   |
| CometLake        | 3        | 2.16%   |
| Westmere         | 2        | 1.44%   |
| Excavator        | 2        | 1.44%   |
| Core             | 2        | 1.44%   |
| TigerLake        | 1        | 0.72%   |
| Steamroller      | 1        | 0.72%   |
| Puma             | 1        | 0.72%   |
| K8 Hammer        | 1        | 0.72%   |
| K10 Llano        | 1        | 0.72%   |
| Goldmont plus    | 1        | 0.72%   |
| Goldmont         | 1        | 0.72%   |
| Bulldozer        | 1        | 0.72%   |
| Broadwell        | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 56       | 38.1%   |
| AMD                        | 49       | 33.33%  |
| Intel                      | 39       | 26.53%  |
| Matrox Electronics Systems | 3        | 2.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.31%   |
| Intel HD Graphics 530                                                       | 5        | 3.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 3.31%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 2.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.65%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4        | 2.65%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.99%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 1.99%   |
| Intel HD Graphics 630                                                       | 3        | 1.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.99%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.32%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.32%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.32%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.32%   |
| AMD Lucienne                                                                | 2        | 1.32%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.66%   |
| Nvidia NV34GL [Quadro NVS 280 PCI]                                          | 1        | 0.66%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.66%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.66%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 0.66%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.66%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.66%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.66%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 52       | 36.88%  |
| 1 x AMD          | 45       | 31.91%  |
| 1 x Intel        | 35       | 24.82%  |
| 1 x Matrox       | 2        | 1.42%   |
| Intel + AMD      | 2        | 1.42%   |
| 2 x AMD          | 1        | 0.71%   |
| Nvidia + Matrox  | 1        | 0.71%   |
| Intel + Nvidia   | 1        | 0.71%   |
| AMD + 2 x Nvidia | 1        | 0.71%   |
| AMD + Nvidia     | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 99       | 69.23%  |
| Proprietary | 37       | 25.87%  |
| Unknown     | 7        | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 60.96%  |
| 3.01-4.0   | 12       | 8.22%   |
| 1.01-2.0   | 12       | 8.22%   |
| 0.01-0.5   | 12       | 8.22%   |
| 8.01-16.0  | 6        | 4.11%   |
| 7.01-8.0   | 5        | 3.42%   |
| 5.01-6.0   | 4        | 2.74%   |
| 0.51-1.0   | 3        | 2.05%   |
| 24.01-32.0 | 1        | 0.68%   |
| 2.01-3.0   | 1        | 0.68%   |
| 16.01-24.0 | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 25       | 17.01%  |
| Goldstar                | 19       | 12.93%  |
| Dell                    | 13       | 8.84%   |
| AOC                     | 12       | 8.16%   |
| Hewlett-Packard         | 10       | 6.8%    |
| Acer                    | 9        | 6.12%   |
| BenQ                    | 8        | 5.44%   |
| Philips                 | 6        | 4.08%   |
| Ancor Communications    | 6        | 4.08%   |
| Fujitsu Siemens         | 5        | 3.4%    |
| ViewSonic               | 4        | 2.72%   |
| Unknown                 | 4        | 2.72%   |
| Panasonic               | 2        | 1.36%   |
| Lenovo                  | 2        | 1.36%   |
| Iiyama                  | 2        | 1.36%   |
| Eizo                    | 2        | 1.36%   |
| ASUSTek Computer        | 2        | 1.36%   |
| ___                     | 1        | 0.68%   |
| TTK                     | 1        | 0.68%   |
| Sun                     | 1        | 0.68%   |
| Sony                    | 1        | 0.68%   |
| RTK                     | 1        | 0.68%   |
| PXO                     | 1        | 0.68%   |
| Plain Tree Systems      | 1        | 0.68%   |
| MStar                   | 1        | 0.68%   |
| LSC                     | 1        | 0.68%   |
| LG Electronics          | 1        | 0.68%   |
| InnoView                | 1        | 0.68%   |
| Hitachi                 | 1        | 0.68%   |
| Gigabyte Technology     | 1        | 0.68%   |
| EDI                     | 1        | 0.68%   |
| Chi Mei Optoelectronics | 1        | 0.68%   |
| BBY                     | 1        | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 1.92%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 2        | 1.28%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                         | 2        | 1.28%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 0.64%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch          | 1        | 0.64%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.64%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch           | 1        | 0.64%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch          | 1        | 0.64%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                   | 1        | 0.64%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.64%   |
| Unknown LCD Monitor KON TV_MONITOR 1920x1080                           | 1        | 0.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.64%   |
| TTK CCL250i TTK8541 1600x1200 408x306mm 20.1-inch                      | 1        | 0.64%   |
| Sun X7149A SUN058A 1600x1200 400x300mm 19.7-inch                       | 1        | 0.64%   |
| Sony TV SNY2203 1920x1080 560x420mm 27.6-inch                          | 1        | 0.64%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch      | 1        | 0.64%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch      | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0427 1920x1200                       | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0425 1920x1200 518x324mm 24.1-inch   | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch   | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 1        | 0.64%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch    | 1        | 0.64%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch      | 1        | 0.64%   |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch      | 1        | 0.64%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 598x336mm 27.0-inch      | 1        | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.64%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.64%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 0.64%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch      | 1        | 0.64%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 480x270mm 21.7-inch      | 1        | 0.64%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SMS27A350H 1920x1080                   | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch  | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1210x680mm 54.6-inch | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM07C3 1920x1080 890x500mm 40.2-inch  | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.64%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 1        | 0.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 41.96%  |
| 3840x2160 (4K)     | 18       | 12.59%  |
| 1280x1024 (SXGA)   | 11       | 7.69%   |
| 2560x1440 (QHD)    | 9        | 6.29%   |
| 1920x1200 (WUXGA)  | 8        | 5.59%   |
| 1440x900 (WXGA+)   | 6        | 4.2%    |
| 1680x1050 (WSXGA+) | 5        | 3.5%    |
| 1366x768 (WXGA)    | 4        | 2.8%    |
| 3840x1080          | 3        | 2.1%    |
| 1600x900 (HD+)     | 3        | 2.1%    |
| 1600x1200          | 3        | 2.1%    |
| Unknown            | 3        | 2.1%    |
| 2560x1080          | 2        | 1.4%    |
| 1920x540           | 2        | 1.4%    |
| 1360x768           | 2        | 1.4%    |
| 1024x768 (XGA)     | 2        | 1.4%    |
| 3440x1440          | 1        | 0.7%    |
| 2288x1287          | 1        | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 30       | 21.28%  |
| 27      | 17       | 12.06%  |
| 23      | 14       | 9.93%   |
| 19      | 11       | 7.8%    |
| Unknown | 11       | 7.8%    |
| 21      | 10       | 7.09%   |
| 31      | 9        | 6.38%   |
| 17      | 5        | 3.55%   |
| 22      | 4        | 2.84%   |
| 18      | 4        | 2.84%   |
| 15      | 4        | 2.84%   |
| 54      | 3        | 2.13%   |
| 20      | 3        | 2.13%   |
| 84      | 2        | 1.42%   |
| 72      | 2        | 1.42%   |
| 34      | 2        | 1.42%   |
| 32      | 2        | 1.42%   |
| 142     | 1        | 0.71%   |
| 65      | 1        | 0.71%   |
| 52      | 1        | 0.71%   |
| 50      | 1        | 0.71%   |
| 43      | 1        | 0.71%   |
| 36      | 1        | 0.71%   |
| 35      | 1        | 0.71%   |
| 25      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 57       | 41.3%   |
| 401-500        | 25       | 18.12%  |
| 601-700        | 11       | 7.97%   |
| Unknown        | 11       | 7.97%   |
| 351-400        | 8        | 5.8%    |
| 301-350        | 8        | 5.8%    |
| 1001-1500      | 6        | 4.35%   |
| 701-800        | 5        | 3.62%   |
| 1501-2000      | 4        | 2.9%    |
| More than 2000 | 1        | 0.72%   |
| 801-900        | 1        | 0.72%   |
| 901-1000       | 1        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 85       | 63.91%  |
| 16/10   | 20       | 15.04%  |
| 5/4     | 9        | 6.77%   |
| Unknown | 8        | 6.02%   |
| 4/3     | 6        | 4.51%   |
| 21/9    | 3        | 2.26%   |
| 6/5     | 1        | 0.75%   |
| 1.00    | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 31.16%  |
| 151-200        | 17       | 12.32%  |
| 301-350        | 16       | 11.59%  |
| 351-500        | 15       | 10.87%  |
| More than 1000 | 11       | 7.97%   |
| 251-300        | 11       | 7.97%   |
| Unknown        | 11       | 7.97%   |
| 141-150        | 7        | 5.07%   |
| 101-110        | 4        | 2.9%    |
| 501-1000       | 2        | 1.45%   |
| 131-140        | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 93       | 68.38%  |
| 101-120 | 16       | 11.76%  |
| Unknown | 11       | 8.09%   |
| 1-50    | 8        | 5.88%   |
| 121-160 | 6        | 4.41%   |
| 161-240 | 2        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 104      | 74.29%  |
| 2     | 23       | 16.43%  |
| 0     | 10       | 7.14%   |
| 3     | 3        | 2.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 94       | 48.96%  |
| Intel                    | 56       | 29.17%  |
| Broadcom                 | 9        | 4.69%   |
| Qualcomm Atheros         | 7        | 3.65%   |
| Ralink Technology        | 3        | 1.56%   |
| OPPO Electronics         | 2        | 1.04%   |
| MediaTek                 | 2        | 1.04%   |
| D-Link System            | 2        | 1.04%   |
| ASUSTek Computer         | 2        | 1.04%   |
| Aquantia                 | 2        | 1.04%   |
| Wilocity                 | 1        | 0.52%   |
| TP-Link                  | 1        | 0.52%   |
| Samsung Electronics      | 1        | 0.52%   |
| Ralink                   | 1        | 0.52%   |
| QLogic                   | 1        | 0.52%   |
| Marvell Technology Group | 1        | 0.52%   |
| Linksys                  | 1        | 0.52%   |
| DisplayLink              | 1        | 0.52%   |
| Broadcom Limited         | 1        | 0.52%   |
| Belkin Components        | 1        | 0.52%   |
| AVM                      | 1        | 0.52%   |
| Atmel                    | 1        | 0.52%   |
| ASIX Electronics         | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 71       | 31.42%  |
| Realtek RTL8125 2.5GbE Controller                                              | 10       | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9        | 3.98%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 2.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 5        | 2.21%   |
| Intel I211 Gigabit Network Connection                                          | 5        | 2.21%   |
| Intel Ethernet Connection (7) I219-V                                           | 5        | 2.21%   |
| Intel 82574L Gigabit Network Connection                                        | 4        | 1.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                            | 3        | 1.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 3        | 1.33%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 1.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 0.88%   |
| Realtek RTL8187 Wireless Adapter                                               | 2        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2        | 0.88%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2        | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 0.88%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.88%   |
| Intel Ethernet Controller I226-V                                               | 2        | 0.88%   |
| Intel Ethernet Controller I225-V                                               | 2        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 0.88%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2        | 0.88%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.88%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                             | 1        | 0.44%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                          | 1        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1        | 0.44%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1        | 0.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1        | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.44%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1        | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 33.33%  |
| Intel                 | 17       | 28.33%  |
| Qualcomm Atheros      | 5        | 8.33%   |
| Ralink Technology     | 3        | 5%      |
| MediaTek              | 2        | 3.33%   |
| D-Link System         | 2        | 3.33%   |
| Broadcom              | 2        | 3.33%   |
| ASUSTek Computer      | 2        | 3.33%   |
| Wilocity              | 1        | 1.67%   |
| TP-Link               | 1        | 1.67%   |
| Ralink                | 1        | 1.67%   |
| Linksys               | 1        | 1.67%   |
| Broadcom Limited      | 1        | 1.67%   |
| Belkin Components     | 1        | 1.67%   |
| AVM                   | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 5        | 8.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 3        | 4.92%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 4.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 3        | 4.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 3.28%   |
| Realtek RTL8187 Wireless Adapter                                                              | 2        | 3.28%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 3.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.28%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                            | 1        | 1.64%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1        | 1.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.64%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                                   | 1        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.64%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.64%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.64%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                                     | 1        | 1.64%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                               | 1        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 1.64%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]                 | 1        | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.64%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1        | 1.64%   |
| Intel Wireless 8260                                                                           | 1        | 1.64%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                               | 1        | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.64%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]                          | 1        | 1.64%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.E1) [Ralink RT2070]                     | 1        | 1.64%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1        | 1.64%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 87       | 56.86%  |
| Intel                    | 47       | 30.72%  |
| Broadcom                 | 7        | 4.58%   |
| Qualcomm Atheros         | 3        | 1.96%   |
| OPPO Electronics         | 2        | 1.31%   |
| Aquantia                 | 2        | 1.31%   |
| Samsung Electronics      | 1        | 0.65%   |
| QLogic                   | 1        | 0.65%   |
| Marvell Technology Group | 1        | 0.65%   |
| DisplayLink              | 1        | 0.65%   |
| ASIX Electronics         | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 71       | 43.56%  |
| Realtek RTL8125 2.5GbE Controller                                              | 10       | 6.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9        | 5.52%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 3.68%   |
| Intel I211 Gigabit Network Connection                                          | 5        | 3.07%   |
| Intel Ethernet Connection (7) I219-V                                           | 5        | 3.07%   |
| Intel 82574L Gigabit Network Connection                                        | 4        | 2.45%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 1.23%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2        | 1.23%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 1.23%   |
| Intel Ethernet Controller I226-V                                               | 2        | 1.23%   |
| Intel Ethernet Controller I225-V                                               | 2        | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 1.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2        | 1.23%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.61%   |
| Realtek Killer E2600 GbE Controller                                            | 1        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.61%   |
| QLogic ISP8324 1/10GbE Converged Network Controller                            | 1        | 0.61%   |
| OPPO SM8350-MTP _SN:9338D66C                                                   | 1        | 0.61%   |
| OPPO CPH2591                                                                   | 1        | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1        | 0.61%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.61%   |
| Intel Ethernet Controller I226-LM                                              | 1        | 0.61%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.61%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1        | 0.61%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (13) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 138      | 71.5%   |
| WiFi     | 53       | 27.46%  |
| Modem    | 1        | 0.52%   |
| Unknown  | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 125      | 86.21%  |
| WiFi     | 20       | 13.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 61.87%  |
| 2     | 40       | 28.78%  |
| 3     | 8        | 5.76%   |
| 0     | 2        | 1.44%   |
| 8     | 1        | 0.72%   |
| 5     | 1        | 0.72%   |
| 4     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 57.86%  |
| Yes  | 59       | 42.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 16       | 34.78%  |
| Cambridge Silicon Radio    | 12       | 26.09%  |
| Realtek Semiconductor      | 10       | 21.74%  |
| TP-Link                    | 2        | 4.35%   |
| ASUSTek Computer           | 2        | 4.35%   |
| MediaTek                   | 1        | 2.17%   |
| Integrated System Solution | 1        | 2.17%   |
| IMC Networks               | 1        | 2.17%   |
| Broadcom                   | 1        | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 26.09%  |
| Realtek Bluetooth Radio                               | 9        | 19.57%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 6.52%   |
| Intel AX210 Bluetooth                                 | 3        | 6.52%   |
| Intel AX200 Bluetooth                                 | 3        | 6.52%   |
| TP-Link UB500 Adapter                                 | 2        | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 4.35%   |
| Intel Bluetooth Device                                | 2        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 4.35%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 2.17%   |
| MediaTek Wireless_Device                              | 1        | 2.17%   |
| Intel AX201 Bluetooth                                 | 1        | 2.17%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.17%   |
| IMC Networks Wireless_Device                          | 1        | 2.17%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1        | 2.17%   |
| ASUS Bluetooth Device                                 | 1        | 2.17%   |
| ASUS BCM20702A0                                       | 1        | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 76       | 33.93%  |
| AMD                                  | 67       | 29.91%  |
| Nvidia                               | 52       | 23.21%  |
| C-Media Electronics                  | 8        | 3.57%   |
| Creative Labs                        | 3        | 1.34%   |
| DSEA A/S                             | 2        | 0.89%   |
| VIA Technologies                     | 1        | 0.45%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.45%   |
| Texas Instruments                    | 1        | 0.45%   |
| Sony                                 | 1        | 0.45%   |
| Schiit Audio                         | 1        | 0.45%   |
| RODE Microphones                     | 1        | 0.45%   |
| Plantronics                          | 1        | 0.45%   |
| ONN                                  | 1        | 0.45%   |
| Micro Star International             | 1        | 0.45%   |
| Logitech                             | 1        | 0.45%   |
| HiBy                                 | 1        | 0.45%   |
| GN Netcom                            | 1        | 0.45%   |
| FiiO Electronics Technology          | 1        | 0.45%   |
| Elgato Systems                       | 1        | 0.45%   |
| BR25                                 | 1        | 0.45%   |
| ASUSTek Computer                     | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 5.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 5.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 4.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 2.69%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 2.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.92%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.92%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 1.92%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.92%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.54%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 1.54%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4        | 1.54%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.15%   |
| Nvidia Audio device                                                        | 3        | 1.15%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.15%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.77%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 12       | 22.22%  |
| Unknown             | 8        | 14.81%  |
| Kingston            | 8        | 14.81%  |
| SK hynix            | 5        | 9.26%   |
| Samsung Electronics | 5        | 9.26%   |
| G.Skill             | 3        | 5.56%   |
| Crucial             | 3        | 5.56%   |
| Micron Technology   | 2        | 3.7%    |
| Hewlett-Packard     | 2        | 3.7%    |
| Unknown (ABCD)      | 1        | 1.85%   |
| Unknown (0x0B45)    | 1        | 1.85%   |
| Team                | 1        | 1.85%   |
| Lexar               | 1        | 1.85%   |
| A-DATA Technology   | 1        | 1.85%   |
| Unknown             | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2        | 3.57%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1        | 1.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.79%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1        | 1.79%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                        | 1        | 1.79%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.79%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1        | 1.79%   |
| Unknown RAM Module 2GB DIMM                                      | 1        | 1.79%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1        | 1.79%   |
| Unknown (0x0B45) RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1        | 1.79%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s               | 1        | 1.79%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 1.79%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM 1333MT/s               | 1        | 1.79%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8192MB DIMM DDR4 3200MT/s          | 1        | 1.79%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 1        | 1.79%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1        | 1.79%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s             | 1        | 1.79%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                       | 1        | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s              | 1        | 1.79%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s              | 1        | 1.79%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 1        | 1.79%   |
| Samsung RAM M378A2G43CB3-CWE 16GB DIMM DDR4 3200MT/s             | 1        | 1.79%   |
| Micron RAM 8ATF1G64HZ-2G3B2 8GB DIMM DDR4 2667MT/s               | 1        | 1.79%   |
| Micron RAM 36JSZF1G72PZ-1G4D1 8GB DIMM DDR3 1333MT/s             | 1        | 1.79%   |
| Lexar RAM LD4AS016G-3200ST 16GB SODIMM DDR4 3200MT/s             | 1        | 1.79%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s                   | 1        | 1.79%   |
| Kingston RAM KHX2933C17D4/16G 16GB DIMM DDR4 2933MT/s            | 1        | 1.79%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s              | 1        | 1.79%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 1        | 1.79%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 1        | 1.79%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 1        | 1.79%   |
| Kingston RAM KF1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 1        | 1.79%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s            | 1        | 1.79%   |
| HP RAM 669238-071 4GB DIMM DDR3 1600MT/s                         | 1        | 1.79%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                         | 1        | 1.79%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 1        | 1.79%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 1        | 1.79%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s             | 1        | 1.79%   |
| Crucial RAM CT8G4DFD824A.M16FF 8GB DIMM DDR4 2400MT/s            | 1        | 1.79%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s          | 1        | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 56.86%  |
| DDR3    | 11       | 21.57%  |
| DDR5    | 3        | 5.88%   |
| SDRAM   | 2        | 3.92%   |
| DDR2    | 2        | 3.92%   |
| Unknown | 2        | 3.92%   |
| LPDDR4  | 1        | 1.96%   |
| DDR     | 1        | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 47       | 94%     |
| SODIMM | 3        | 6%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 30.77%  |
| 16384 | 15       | 28.85%  |
| 2048  | 9        | 17.31%  |
| 4096  | 8        | 15.38%  |
| 32768 | 3        | 5.77%   |
| 49152 | 1        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 12       | 22.64%  |
| 2400    | 6        | 11.32%  |
| 1600    | 6        | 11.32%  |
| 1333    | 5        | 9.43%   |
| 800     | 3        | 5.66%   |
| 5600    | 2        | 3.77%   |
| 3600    | 2        | 3.77%   |
| 2933    | 2        | 3.77%   |
| 2667    | 2        | 3.77%   |
| 2133    | 2        | 3.77%   |
| 4800    | 1        | 1.89%   |
| 3866    | 1        | 1.89%   |
| 3800    | 1        | 1.89%   |
| 3666    | 1        | 1.89%   |
| 3534    | 1        | 1.89%   |
| 3066    | 1        | 1.89%   |
| 3000    | 1        | 1.89%   |
| 1867    | 1        | 1.89%   |
| 1334    | 1        | 1.89%   |
| 533     | 1        | 1.89%   |
| Unknown | 1        | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 5        | 31.25%  |
| Brother Industries  | 5        | 31.25%  |
| Hewlett-Packard     | 3        | 18.75%  |
| Xerox               | 1        | 6.25%   |
| Samsung Electronics | 1        | 6.25%   |
| Pantum              | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Xerox WorkCentre 3220            | 1        | 6.25%   |
| Seiko Epson XP-4200 Series       | 1        | 6.25%   |
| Seiko Epson XP-4100 Series       | 1        | 6.25%   |
| Seiko Epson WF-4830 Series       | 1        | 6.25%   |
| Seiko Epson L300 Series          | 1        | 6.25%   |
| Seiko Epson ET-2820 Series       | 1        | 6.25%   |
| Samsung Phaser 3121              | 1        | 6.25%   |
| Pantum P2200-series              | 1        | 6.25%   |
| HP LaserJet 1200                 | 1        | 6.25%   |
| HP LaserJet 1018                 | 1        | 6.25%   |
| HP Ink Tank 310 series           | 1        | 6.25%   |
| Brother Printer                  | 1        | 6.25%   |
| Brother MFC-7360N                | 1        | 6.25%   |
| Brother HL-L3230CDW series       | 1        | 6.25%   |
| Brother DCP-L2520DW              | 1        | 6.25%   |
| Brother DCP-7057 scanner/printer | 1        | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 50%     |
| Canon CanoScan LiDE 220                       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 10       | 47.62%  |
| Microdia                | 2        | 9.52%   |
| Generalplus Technology  | 2        | 9.52%   |
| Z-Star Microelectronics | 1        | 4.76%   |
| Trust                   | 1        | 4.76%   |
| Realtek Semiconductor   | 1        | 4.76%   |
| Microsoft               | 1        | 4.76%   |
| Jieli Technology        | 1        | 4.76%   |
| Creative Technology     | 1        | 4.76%   |
| Chicony Electronics     | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Generalplus CAMERA - UVC          | 2        | 9.52%   |
| Z-Star Integrated Camera          | 1        | 4.76%   |
| Trust WB-6250X Webcam             | 1        | 4.76%   |
| Realtek USB 2.0 Camera            | 1        | 4.76%   |
| Microsoft LifeCam HD-3000         | 1        | 4.76%   |
| Microdia Webcam Vitade AF         | 1        | 4.76%   |
| Microdia USB 2.0 Camera           | 1        | 4.76%   |
| Logitech Webcam Pro 9000          | 1        | 4.76%   |
| Logitech Webcam C270              | 1        | 4.76%   |
| Logitech QuickCam Vision Pro      | 1        | 4.76%   |
| Logitech QuickCam Pro 9000        | 1        | 4.76%   |
| Logitech QuickCam Orbit/Sphere AF | 1        | 4.76%   |
| Logitech HD Webcam C615           | 1        | 4.76%   |
| Logitech HD Webcam C525           | 1        | 4.76%   |
| Logitech CrystalCam               | 1        | 4.76%   |
| Logitech C922 Pro Stream Webcam   | 1        | 4.76%   |
| Logitech BCC950 ConferenceCam     | 1        | 4.76%   |
| Jieli USB PHY 2.0                 | 1        | 4.76%   |
| Creative VF0530 Live! Cam Chat IM | 1        | 4.76%   |
| Chicony CNF8050 Webcam            | 1        | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| AuthenTec AES2501 Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 50%     |
| CHERRY           | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 50%     |
| CHERRY SmartCard Reader Keyboard KC 1000 SC            | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 113      | 77.93%  |
| 1     | 25       | 17.24%  |
| 2     | 7        | 4.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 12       | 37.5%   |
| Graphics card         | 10       | 31.25%  |
| Sound                 | 2        | 6.25%   |
| Multimedia controller | 2        | 6.25%   |
| Unassigned class      | 1        | 3.13%   |
| Net/ethernet          | 1        | 3.13%   |
| Fingerprint reader    | 1        | 3.13%   |
| Chipcard              | 1        | 3.13%   |
| Card reader           | 1        | 3.13%   |
| Bluetooth             | 1        | 3.13%   |

