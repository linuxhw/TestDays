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

Total: 154

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.14.21-150500.53-default      | 26       | 23.21%  |
| 5.14.21-150500.55.19-default   | 18       | 16.07%  |
| 5.14.21-150500.55.36-default   | 14       | 12.5%   |
| 5.14.21-150500.55.39-default   | 13       | 11.61%  |
| 5.14.21-150500.55.7-default    | 9        | 8.04%   |
| 5.14.21-150500.55.31-default   | 8        | 7.14%   |
| 5.14.21-150500.55.28-default   | 7        | 6.25%   |
| 5.14.21-150500.55.12-default   | 4        | 3.57%   |
| 5.14.21-150500.52-default      | 4        | 3.57%   |
| 5.14.21-150400.24.18-default   | 2        | 1.79%   |
| 6.6.3-1-default                | 1        | 0.89%   |
| 6.5.4-1-default                | 1        | 0.89%   |
| 6.4.4-lp154.2.g919c802-default | 1        | 0.89%   |
| 5.14.21-150500.43-default      | 1        | 0.89%   |
| 5.14.21-150500.37-default      | 1        | 0.89%   |
| 5.14.21-150400.24.55-default   | 1        | 0.89%   |
| 5.14.21-150400.24.46-default   | 1        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.21 | 98       | 97.03%  |
| 6.6.3   | 1        | 0.99%   |
| 6.5.4   | 1        | 0.99%   |
| 6.4.4   | 1        | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 98       | 97.03%  |
| 6.6     | 1        | 0.99%   |
| 6.5     | 1        | 0.99%   |
| 6.4     | 1        | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 101      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 78       | 76.47%  |
| GNOME   | 17       | 16.67%  |
| XFCE    | 3        | 2.94%   |
| MATE    | 1        | 0.98%   |
| ICEWM   | 1        | 0.98%   |
| Budgie  | 1        | 0.98%   |
| Unknown | 1        | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 91       | 87.5%   |
| Wayland | 10       | 9.62%   |
| Tty     | 3        | 2.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 67.65%  |
| SDDM    | 26       | 25.49%  |
| LightDM | 5        | 4.9%    |
| XDM     | 2        | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 35       | 34.65%  |
| de_DE | 24       | 23.76%  |
| ru_RU | 7        | 6.93%   |
| pt_BR | 7        | 6.93%   |
| POSIX | 7        | 6.93%   |
| es_ES | 4        | 3.96%   |
| C     | 3        | 2.97%   |
| nl_NL | 2        | 1.98%   |
| it_IT | 2        | 1.98%   |
| fr_FR | 2        | 1.98%   |
| zh_CN | 1        | 0.99%   |
| sk_SK | 1        | 0.99%   |
| pl_PL | 1        | 0.99%   |
| es_DO | 1        | 0.99%   |
| en_GB | 1        | 0.99%   |
| el_GR | 1        | 0.99%   |
| da_DK | 1        | 0.99%   |
| ar_AE | 1        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 80       | 78.43%  |
| EFI  | 22       | 21.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 79       | 77.45%  |
| Ext4  | 20       | 19.61%  |
| Xfs   | 2        | 1.96%   |
| Zfs   | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 68       | 66.67%  |
| GPT     | 28       | 27.45%  |
| MBR     | 6        | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 86.27%  |
| Yes       | 14       | 13.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 88.12%  |
| Yes       | 12       | 11.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 21       | 20.79%  |
| ASUSTek Computer    | 21       | 20.79%  |
| Hewlett-Packard     | 13       | 12.87%  |
| ASRock              | 12       | 11.88%  |
| MSI                 | 10       | 9.9%    |
| Lenovo              | 6        | 5.94%   |
| Fujitsu             | 3        | 2.97%   |
| Dell                | 3        | 2.97%   |
| Biostar             | 2        | 1.98%   |
| Pegatron            | 1        | 0.99%   |
| OEM                 | 1        | 0.99%   |
| Intel               | 1        | 0.99%   |
| HC Technology.      | 1        | 0.99%   |
| Fujitsu Siemens     | 1        | 0.99%   |
| Foxconn             | 1        | 0.99%   |
| Colorful Technology | 1        | 0.99%   |
| AMI                 | 1        | 0.99%   |
| Alienware           | 1        | 0.99%   |
| Acer                | 1        | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| HP Z420 Workstation                         | 2        | 1.98%   |
| Gigabyte B550M DS3H                         | 2        | 1.98%   |
| ASUS M5A97 R2.0                             | 2        | 1.98%   |
| Pegatron NY603AA-ABA 300-1007               | 1        | 0.99%   |
| OEM B75                                     | 1        | 0.99%   |
| MSI MS-7D74                                 | 1        | 0.99%   |
| MSI MS-7D54                                 | 1        | 0.99%   |
| MSI MS-7C80                                 | 1        | 0.99%   |
| MSI MS-7C52                                 | 1        | 0.99%   |
| MSI MS-7C02                                 | 1        | 0.99%   |
| MSI MS-7B89                                 | 1        | 0.99%   |
| MSI MS-7B85                                 | 1        | 0.99%   |
| MSI MS-7A33                                 | 1        | 0.99%   |
| MSI MS-7978                                 | 1        | 0.99%   |
| MSI MS-7522                                 | 1        | 0.99%   |
| Lenovo V520S-08IKL Desktop 10NN000CBP       | 1        | 0.99%   |
| Lenovo ThinkCentre M92p 3227GQ8             | 1        | 0.99%   |
| Lenovo ThinkCentre M78 10BR0005US           | 1        | 0.99%   |
| Lenovo ThinkCentre M720t 10SQ0070GE         | 1        | 0.99%   |
| Lenovo ThinkCentre Edge 91Z 7075K7G         | 1        | 0.99%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T100BHMZ | 1        | 0.99%   |
| Intel Nobilis                               | 1        | 0.99%   |
| HP Z440 Workstation                         | 1        | 0.99%   |
| HP Z400 Workstation                         | 1        | 0.99%   |
| HP ProLiant ML310e Gen8                     | 1        | 0.99%   |
| HP ProLiant ML10 v2                         | 1        | 0.99%   |
| HP ProLiant MicroServer Gen8                | 1        | 0.99%   |
| HP ProDesk 400 G2 MT                        | 1        | 0.99%   |
| HP Pavilion Desktop TP01-4xxx               | 1        | 0.99%   |
| HP EliteDesk 800 G2 DM 35W                  | 1        | 0.99%   |
| HP Desktop M01-F3xxx                        | 1        | 0.99%   |
| HP Compaq Elite 8300 SFF                    | 1        | 0.99%   |
| HP Compaq 6000 Pro MT PC                    | 1        | 0.99%   |
| HC Technology. HCAR5000-MI                  | 1        | 0.99%   |
| Gigabyte Z97-HD3                            | 1        | 0.99%   |
| Gigabyte X670E AORUS MASTER                 | 1        | 0.99%   |
| Gigabyte H610M H DDR4                       | 1        | 0.99%   |
| Gigabyte H410M H V3                         | 1        | 0.99%   |
| Gigabyte GA-MA770-UD3                       | 1        | 0.99%   |
| Gigabyte GA-A75M-D2H                        | 1        | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Lenovo ThinkCentre         | 4        | 3.96%   |
| HP ProLiant                | 3        | 2.97%   |
| ASUS ROG                   | 3        | 2.97%   |
| HP Z420                    | 2        | 1.98%   |
| HP Compaq                  | 2        | 1.98%   |
| Gigabyte B550M             | 2        | 1.98%   |
| Gigabyte B450M             | 2        | 1.98%   |
| ASUS PRIME                 | 2        | 1.98%   |
| ASUS M5A97                 | 2        | 1.98%   |
| Pegatron NY603AA-ABA       | 1        | 0.99%   |
| OEM B75                    | 1        | 0.99%   |
| MSI MS-7D74                | 1        | 0.99%   |
| MSI MS-7D54                | 1        | 0.99%   |
| MSI MS-7C80                | 1        | 0.99%   |
| MSI MS-7C52                | 1        | 0.99%   |
| MSI MS-7C02                | 1        | 0.99%   |
| MSI MS-7B89                | 1        | 0.99%   |
| MSI MS-7B85                | 1        | 0.99%   |
| MSI MS-7A33                | 1        | 0.99%   |
| MSI MS-7978                | 1        | 0.99%   |
| MSI MS-7522                | 1        | 0.99%   |
| Lenovo V520S-08IKL         | 1        | 0.99%   |
| Lenovo IdeaCentre          | 1        | 0.99%   |
| Intel Nobilis              | 1        | 0.99%   |
| HP Z440                    | 1        | 0.99%   |
| HP Z400                    | 1        | 0.99%   |
| HP ProDesk                 | 1        | 0.99%   |
| HP Pavilion                | 1        | 0.99%   |
| HP EliteDesk               | 1        | 0.99%   |
| HP Desktop                 | 1        | 0.99%   |
| HC Technology. HCAR5000-MI | 1        | 0.99%   |
| Gigabyte Z97-HD3           | 1        | 0.99%   |
| Gigabyte X670E             | 1        | 0.99%   |
| Gigabyte H610M             | 1        | 0.99%   |
| Gigabyte H410M             | 1        | 0.99%   |
| Gigabyte GA-MA770-UD3      | 1        | 0.99%   |
| Gigabyte GA-A75M-D2H       | 1        | 0.99%   |
| Gigabyte GA-990XA-UD3      | 1        | 0.99%   |
| Gigabyte GA-880GMA-UD2H    | 1        | 0.99%   |
| Gigabyte G41MT-S2P         | 1        | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 11.88%  |
| 2020 | 11       | 10.89%  |
| 2015 | 9        | 8.91%   |
| 2012 | 9        | 8.91%   |
| 2021 | 8        | 7.92%   |
| 2013 | 8        | 7.92%   |
| 2010 | 7        | 6.93%   |
| 2011 | 6        | 5.94%   |
| 2022 | 5        | 4.95%   |
| 2014 | 5        | 4.95%   |
| 2023 | 4        | 3.96%   |
| 2009 | 4        | 3.96%   |
| 2016 | 3        | 2.97%   |
| 2008 | 3        | 2.97%   |
| 2007 | 3        | 2.97%   |
| 2019 | 2        | 1.98%   |
| 2017 | 1        | 0.99%   |
| 2006 | 1        | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 101      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 99       | 98.02%  |
| Enabled  | 2        | 1.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 27.45%  |
| 8.01-16.0   | 21       | 20.59%  |
| 4.01-8.0    | 17       | 16.67%  |
| 32.01-64.0  | 16       | 15.69%  |
| 3.01-4.0    | 12       | 11.76%  |
| 64.01-256.0 | 5        | 4.9%    |
| 24.01-32.0  | 3        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 44       | 40.37%  |
| 1.01-2.0   | 20       | 18.35%  |
| 4.01-8.0   | 19       | 17.43%  |
| 3.01-4.0   | 18       | 16.51%  |
| 0.51-1.0   | 3        | 2.75%   |
| 16.01-24.0 | 2        | 1.83%   |
| 8.01-16.0  | 2        | 1.83%   |
| 24.01-32.0 | 1        | 0.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 34.31%  |
| 2      | 29       | 28.43%  |
| 3      | 22       | 21.57%  |
| 4      | 8        | 7.84%   |
| 5      | 5        | 4.9%    |
| 6      | 3        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 54.46%  |
| No        | 46       | 45.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 99.01%  |
| No        | 1        | 0.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 61.17%  |
| Yes       | 40       | 38.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 69.31%  |
| Yes       | 31       | 30.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 26       | 25.74%  |
| USA          | 18       | 17.82%  |
| Russia       | 8        | 7.92%   |
| Brazil       | 7        | 6.93%   |
| Switzerland  | 3        | 2.97%   |
| Netherlands  | 3        | 2.97%   |
| Canada       | 3        | 2.97%   |
| UK           | 2        | 1.98%   |
| Sweden       | 2        | 1.98%   |
| Italy        | 2        | 1.98%   |
| Greece       | 2        | 1.98%   |
| Finland      | 2        | 1.98%   |
| Australia    | 2        | 1.98%   |
| Vietnam      | 1        | 0.99%   |
| Ukraine      | 1        | 0.99%   |
| Spain        | 1        | 0.99%   |
| South Korea  | 1        | 0.99%   |
| South Africa | 1        | 0.99%   |
| Slovenia     | 1        | 0.99%   |
| Slovakia     | 1        | 0.99%   |
| Portugal     | 1        | 0.99%   |
| Poland       | 1        | 0.99%   |
| Mexico       | 1        | 0.99%   |
| Martinique   | 1        | 0.99%   |
| Indonesia    | 1        | 0.99%   |
| Guatemala    | 1        | 0.99%   |
| Greenland    | 1        | 0.99%   |
| France       | 1        | 0.99%   |
| Colombia     | 1        | 0.99%   |
| China        | 1        | 0.99%   |
| Bulgaria     | 1        | 0.99%   |
| Belgium      | 1        | 0.99%   |
| Argentina    | 1        | 0.99%   |
| Algeria      | 1        | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| St Petersburg  | 2        | 1.92%   |
| Enschede       | 2        | 1.92%   |
| Cherry Hill    | 2        | 1.92%   |
| Bremen         | 2        | 1.92%   |
| Berlin         | 2        | 1.92%   |
| Zurich         | 1        | 0.96%   |
| Zuchwil        | 1        | 0.96%   |
| Zetel          | 1        | 0.96%   |
| Yakutsk        | 1        | 0.96%   |
| Wuppertal      | 1        | 0.96%   |
| West Bend      | 1        | 0.96%   |
| Warsaw         | 1        | 0.96%   |
| Warrenton      | 1        | 0.96%   |
| Waren          | 1        | 0.96%   |
| Vlkanova       | 1        | 0.96%   |
| Victoria       | 1        | 0.96%   |
| Västerås     | 1        | 0.96%   |
| Vantaa         | 1        | 0.96%   |
| Valencia       | 1        | 0.96%   |
| Timmins        | 1        | 0.96%   |
| Thessaloniki   | 1        | 0.96%   |
| The Villages   | 1        | 0.96%   |
| Tacoma         | 1        | 0.96%   |
| Sydney         | 1        | 0.96%   |
| Sumaré        | 1        | 0.96%   |
| Stuttgart      | 1        | 0.96%   |
| Stockholm      | 1        | 0.96%   |
| Staraya Russa  | 1        | 0.96%   |
| Sofia          | 1        | 0.96%   |
| Soest          | 1        | 0.96%   |
| Sisimiut       | 1        | 0.96%   |
| Shanghai       | 1        | 0.96%   |
| Sao Vicente    | 1        | 0.96%   |
| Sao Luís      | 1        | 0.96%   |
| Salt Lake City | 1        | 0.96%   |
| Saint-Etienne  | 1        | 0.96%   |
| Saint Paul     | 1        | 0.96%   |
| Sacramento     | 1        | 0.96%   |
| Rostov-on-Don  | 1        | 0.96%   |
| Rostock        | 1        | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives  | Percent |
|-----------------------------|----------|---------|---------|
| Seagate                     | 41       | 58      | 21.35%  |
| WDC                         | 33       | 66      | 17.19%  |
| Samsung Electronics         | 31       | 46      | 16.15%  |
| Kingston                    | 13       | 18      | 6.77%   |
| SanDisk                     | 9        | 11      | 4.69%   |
| Crucial                     | 9        | 11      | 4.69%   |
| Toshiba                     | 8        | 9       | 4.17%   |
| Hitachi                     | 8        | 7       | 4.17%   |
| Intenso                     | 5        | 6       | 2.6%    |
| XrayDisk                    | 2        | 2       | 1.04%   |
| SK hynix                    | 2        | 2       | 1.04%   |
| Silicon Motion              | 2        | 2       | 1.04%   |
| Leven                       | 2        | 2       | 1.04%   |
| Intel                       | 2        | 3       | 1.04%   |
| HGST                        | 2        | 3       | 1.04%   |
| A-DATA Technology           | 2        | 2       | 1.04%   |
| XSTAR                       | 1        | 1       | 0.52%   |
| Unknown                     | 1        | 1       | 0.52%   |
| Synology                    | 1        | 1       | 0.52%   |
| StoreJet                    | 1        | 1       | 0.52%   |
| SPCC                        | 1        | 1       | 0.52%   |
| SABRENT                     | 1        | 1       | 0.52%   |
| RESCUE                      | 1        | 1       | 0.52%   |
| Radeon                      | 1        | 1       | 0.52%   |
| PNY                         | 1        | 2       | 0.52%   |
| Micron Technology           | 1        | 2       | 0.52%   |
| KIOXIA                      | 1        | 1       | 0.52%   |
| Kingston Technology Company | 1        | 1       | 0.52%   |
| HS-SSD-E100                 | 1        | 1       | 0.52%   |
| HL-DT-ST                    | 1        | Unknown | 0.52%   |
| Hewlett-Packard             | 1        | 1       | 0.52%   |
| Fujitsu                     | 1        | 2       | 0.52%   |
| Fanxiang                    | 1        | 2       | 0.52%   |
| China                       | 1        | 1       | 0.52%   |
| ASMT                        | 1        | 2       | 0.52%   |
| AMD                         | 1        | 1       | 0.52%   |
| ADATA Technology            | 1        | 1       | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 7        | 3.18%   |
| Seagate ST500DM002-1BD142 500GB                   | 6        | 2.73%   |
| Seagate ST2000DM008-2FR102 2TB                    | 4        | 1.82%   |
| Kingston SA400S37480G 480GB SSD                   | 4        | 1.82%   |
| Samsung SSD 870 EVO 1TB                           | 3        | 1.36%   |
| Kingston SV300S37A120G 120GB SSD                  | 3        | 1.36%   |
| WDC WD10EZRX-00A8LB0 1TB                          | 2        | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 0.91%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 2        | 0.91%   |
| WDC WD1003FZEX-00K3CA0 1TB                        | 2        | 0.91%   |
| Toshiba HDWD130 3TB                               | 2        | 0.91%   |
| Toshiba DT01ACA050 500GB                          | 2        | 0.91%   |
| Seagate ST8000DM004-2U9188 8TB                    | 2        | 0.91%   |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2        | 0.91%   |
| Samsung SSD 860 EVO 4TB                           | 2        | 0.91%   |
| Samsung SSD 850 EVO 250GB                         | 2        | 0.91%   |
| Samsung SSD 840 EVO 120GB                         | 2        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 0.91%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 0.91%   |
| Crucial CT500MX500SSD1 500GB                      | 2        | 0.91%   |
| Crucial CT480BX500SSD1 480GB                      | 2        | 0.91%   |
| Crucial CT275MX300SSD1 275GB                      | 2        | 0.91%   |
| XSTAR SSD 128GB                                   | 1        | 0.45%   |
| XrayDisk 480GB SSD                                | 1        | 0.45%   |
| XrayDisk 128GB                                    | 1        | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                  | 1        | 0.45%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.45%   |
| WDC WD7500LPCX-60HWST0 752GB                      | 1        | 0.45%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 1        | 0.45%   |
| WDC WD5000BEKT-60KA9T0 500GB                      | 1        | 0.45%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1        | 0.45%   |
| WDC WD5000AAKX-7 500GB                            | 1        | 0.45%   |
| WDC WD5000AAKX-08ERMA0 500GB                      | 1        | 0.45%   |
| WDC WD5000AAKS-00A7B2 500GB                       | 1        | 0.45%   |
| WDC WD5000AAJS-00TKA0 500GB                       | 1        | 0.45%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 1        | 0.45%   |
| WDC WD3200AAKX-00ERMA0 320GB                      | 1        | 0.45%   |
| WDC WD3200AAJS-60Z0A0 320GB                       | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 40       | 56     | 39.22%  |
| WDC                 | 31       | 56     | 30.39%  |
| Hitachi             | 8        | 7      | 7.84%   |
| Toshiba             | 7        | 8      | 6.86%   |
| Samsung Electronics | 7        | 8      | 6.86%   |
| HGST                | 2        | 3      | 1.96%   |
| XrayDisk            | 1        | 1      | 0.98%   |
| Unknown             | 1        | 1      | 0.98%   |
| Synology            | 1        | 1      | 0.98%   |
| StoreJet            | 1        | 1      | 0.98%   |
| Hewlett-Packard     | 1        | 1      | 0.98%   |
| Fujitsu             | 1        | 2      | 0.98%   |
| ASMT                | 1        | 2      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 27     | 24.24%  |
| Kingston            | 12       | 17     | 18.18%  |
| Crucial             | 9        | 11     | 13.64%  |
| SanDisk             | 6        | 6      | 9.09%   |
| Intenso             | 4        | 4      | 6.06%   |
| WDC                 | 3        | 10     | 4.55%   |
| Leven               | 2        | 2      | 3.03%   |
| Intel               | 2        | 3      | 3.03%   |
| A-DATA Technology   | 2        | 2      | 3.03%   |
| XSTAR               | 1        | 1      | 1.52%   |
| XrayDisk            | 1        | 1      | 1.52%   |
| Toshiba             | 1        | 1      | 1.52%   |
| SPCC                | 1        | 1      | 1.52%   |
| SABRENT             | 1        | 1      | 1.52%   |
| Radeon              | 1        | 1      | 1.52%   |
| PNY                 | 1        | 2      | 1.52%   |
| Fanxiang            | 1        | 2      | 1.52%   |
| China               | 1        | 1      | 1.52%   |
| AMD                 | 1        | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 70       | 147    | 47.3%   |
| SSD     | 52       | 94     | 35.14%  |
| NVMe    | 21       | 27     | 14.19%  |
| Unknown | 5        | 5      | 3.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 93       | 232    | 74.4%   |
| NVMe | 21       | 27     | 16.8%   |
| SAS  | 11       | 14     | 8.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 62       | 117    | 44.29%  |
| 0.51-1.0   | 42       | 66     | 30%     |
| 1.01-2.0   | 19       | 35     | 13.57%  |
| 3.01-4.0   | 9        | 15     | 6.43%   |
| 4.01-10.0  | 4        | 4      | 2.86%   |
| 2.01-3.0   | 3        | 3      | 2.14%   |
| 10.01-20.0 | 1        | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 46       | 43.81%  |
| 1001-2000      | 23       | 21.9%   |
| 2001-3000      | 10       | 9.52%   |
| 251-500        | 8        | 7.62%   |
| 501-1000       | 8        | 7.62%   |
| 101-250        | 7        | 6.67%   |
| 1-20           | 1        | 0.95%   |
| 51-100         | 1        | 0.95%   |
| Unknown        | 1        | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 22.52%  |
| 51-100         | 22       | 19.82%  |
| 251-500        | 17       | 15.32%  |
| 1001-2000      | 14       | 12.61%  |
| 501-1000       | 13       | 11.71%  |
| 1-20           | 6        | 5.41%   |
| More than 3000 | 5        | 4.5%    |
| 21-50          | 5        | 4.5%    |
| 2001-3000      | 3        | 2.7%    |
| Unknown        | 1        | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 25%     |
| Toshiba MD04ACA400 4TB                           | 1        | 1      | 12.5%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1        | 1      | 12.5%   |
| Seagate ST4000NM0035-1V4107 4TB                  | 1        | 1      | 12.5%   |
| Samsung Electronics SSD 840 EVO 120GB            | 1        | 1      | 12.5%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1        | 1      | 12.5%   |
| Kingston SA400S37120G 120GB SSD                  | 1        | 3      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 57.14%  |
| Toshiba             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 2      | 14.29%  |
| Kingston            | 1        | 3      | 14.29%  |

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
| HDD  | 5        | 5      | 71.43%  |
| SSD  | 2        | 5      | 28.57%  |

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
| Detected | 70       | 186    | 63.64%  |
| Works    | 33       | 75     | 30%     |
| Malfunc  | 6        | 10     | 5.45%   |
| Failed   | 1        | 2      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 56       | 39.44%  |
| AMD                           | 44       | 30.99%  |
| Samsung Electronics           | 10       | 7.04%   |
| ASMedia Technology            | 6        | 4.23%   |
| Marvell Technology Group      | 4        | 2.82%   |
| JMicron Technology            | 4        | 2.82%   |
| SanDisk                       | 3        | 2.11%   |
| SK hynix                      | 2        | 1.41%   |
| Silicon Motion                | 2        | 1.41%   |
| Kingston Technology Company   | 2        | 1.41%   |
| VIA Technologies              | 1        | 0.7%    |
| Seagate Technology            | 1        | 0.7%    |
| Nvidia                        | 1        | 0.7%    |
| Micron Technology             | 1        | 0.7%    |
| KIOXIA                        | 1        | 0.7%    |
| Integrated Technology Express | 1        | 0.7%    |
| Broadcom / LSI                | 1        | 0.7%    |
| ADATA Technology              | 1        | 0.7%    |
| Adaptec                       | 1        | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 9.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 4.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 4.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 3.85%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 3.3%    |
| AMD FCH SATA Controller D                                                               | 5        | 2.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.2%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.1%    |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 2        | 1.1%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.1%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.1%    |
| AMD 600 Series Chipset SATA Controller                                                  | 2        | 1.1%    |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.55%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 0.55%   |
| SK hynix BC511 NVMe SSD                                                                 | 1        | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.55%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 90       | 61.22%  |
| IDE  | 27       | 18.37%  |
| NVMe | 21       | 14.29%  |
| RAID | 5        | 3.4%    |
| SAS  | 3        | 2.04%   |
| SCSI | 1        | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 56       | 55.45%  |
| AMD    | 45       | 44.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 4.95%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 2.97%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.97%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.97%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz          | 2        | 1.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.98%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.98%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.98%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.98%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.98%   |
| AMD FX-8370 Eight-Core Processor            | 2        | 1.98%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.99%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz         | 1        | 0.99%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.99%   |
| Intel Xeon CPU 3050 @ 2.13GHz               | 1        | 0.99%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.99%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.99%   |
| Intel Pentium CPU G850 @ 2.90GHz            | 1        | 0.99%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.99%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.99%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.99%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.99%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.99%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.99%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.99%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 0.99%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.99%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.99%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.99%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.99%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 1        | 0.99%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 1        | 0.99%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.99%   |
| Intel Core i3-7300 CPU @ 4.00GHz            | 1        | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 14.85%  |
| AMD Ryzen 5             | 11       | 10.89%  |
| Intel Core i7           | 10       | 9.9%    |
| Intel Xeon              | 8        | 7.92%   |
| AMD Ryzen 7             | 7        | 6.93%   |
| Other                   | 5        | 4.95%   |
| Intel Celeron           | 5        | 4.95%   |
| AMD Ryzen 9             | 5        | 4.95%   |
| AMD FX                  | 5        | 4.95%   |
| Intel Core i3           | 4        | 3.96%   |
| Intel Pentium           | 3        | 2.97%   |
| Intel Core 2 Quad       | 3        | 2.97%   |
| Intel Pentium Dual-Core | 2        | 1.98%   |
| AMD Ryzen 3             | 2        | 1.98%   |
| AMD Phenom II X4        | 2        | 1.98%   |
| AMD A8                  | 2        | 1.98%   |
| Intel Core 2 Duo        | 1        | 0.99%   |
| AMD Ryzen 3 PRO         | 1        | 0.99%   |
| AMD Phenom II X6        | 1        | 0.99%   |
| AMD Phenom              | 1        | 0.99%   |
| AMD Athlon X4           | 1        | 0.99%   |
| AMD Athlon II X4        | 1        | 0.99%   |
| AMD Athlon II X3        | 1        | 0.99%   |
| AMD Athlon II X2        | 1        | 0.99%   |
| AMD Athlon 64 X2        | 1        | 0.99%   |
| AMD Athlon              | 1        | 0.99%   |
| AMD A6                  | 1        | 0.99%   |
| AMD A4                  | 1        | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 39       | 38.61%  |
| 2      | 22       | 21.78%  |
| 6      | 17       | 16.83%  |
| 8      | 11       | 10.89%  |
| 12     | 6        | 5.94%   |
| 3      | 3        | 2.97%   |
| 16     | 2        | 1.98%   |
| 1      | 1        | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 99.01%  |
| 2      | 1        | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 56       | 55.45%  |
| 1      | 45       | 44.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 101      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 62.14%  |
| 0x1067a    | 3        | 2.91%   |
| 0x0a50000d | 3        | 2.91%   |
| 0xa0671    | 2        | 1.94%   |
| 0x906e9    | 2        | 1.94%   |
| 0x306c3    | 2        | 1.94%   |
| 0x206d7    | 2        | 1.94%   |
| 0x206a7    | 2        | 1.94%   |
| 0x08701021 | 2        | 1.94%   |
| 0x0800820d | 2        | 1.94%   |
| 0xb0671    | 1        | 0.97%   |
| 0xa0655    | 1        | 0.97%   |
| 0x906ed    | 1        | 0.97%   |
| 0x906ea    | 1        | 0.97%   |
| 0x706a1    | 1        | 0.97%   |
| 0x506e3    | 1        | 0.97%   |
| 0x306a9    | 1        | 0.97%   |
| 0x10677    | 1        | 0.97%   |
| 0x0a601203 | 1        | 0.97%   |
| 0x0a50000c | 1        | 0.97%   |
| 0x0a20120a | 1        | 0.97%   |
| 0x08701030 | 1        | 0.97%   |
| 0x08608103 | 1        | 0.97%   |
| 0x08101016 | 1        | 0.97%   |
| 0x08001138 | 1        | 0.97%   |
| 0x06003106 | 1        | 0.97%   |
| 0x06001119 | 1        | 0.97%   |
| 0x06000852 | 1        | 0.97%   |
| 0x01000095 | 1        | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 12       | 11.88%  |
| IvyBridge        | 9        | 8.91%   |
| Haswell          | 8        | 7.92%   |
| SandyBridge      | 7        | 6.93%   |
| KabyLake         | 7        | 6.93%   |
| K10              | 7        | 6.93%   |
| Penryn           | 6        | 5.94%   |
| Zen              | 5        | 4.95%   |
| Piledriver       | 5        | 4.95%   |
| Unknown          | 5        | 4.95%   |
| Zen 2            | 4        | 3.96%   |
| Zen+             | 3        | 2.97%   |
| Nehalem          | 3        | 2.97%   |
| CometLake        | 3        | 2.97%   |
| Skylake          | 2        | 1.98%   |
| Icelake          | 2        | 1.98%   |
| Excavator        | 2        | 1.98%   |
| Core             | 2        | 1.98%   |
| Westmere         | 1        | 0.99%   |
| Steamroller      | 1        | 0.99%   |
| K8 Hammer        | 1        | 0.99%   |
| K10 Llano        | 1        | 0.99%   |
| Goldmont plus    | 1        | 0.99%   |
| Goldmont         | 1        | 0.99%   |
| Bulldozer        | 1        | 0.99%   |
| Broadwell        | 1        | 0.99%   |
| Alderlake Hybrid | 1        | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 43       | 40.19%  |
| AMD                        | 35       | 32.71%  |
| Intel                      | 26       | 24.3%   |
| Matrox Electronics Systems | 3        | 2.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 4.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 4.5%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.7%    |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 2.7%    |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 3        | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.8%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.8%    |
| Intel HD Graphics 630                                                       | 2        | 1.8%    |
| Intel HD Graphics 530                                                       | 2        | 1.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.9%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.9%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.9%    |
| Nvidia NV34GL [Quadro NVS 280 PCI]                                          | 1        | 0.9%    |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.9%    |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.9%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.9%    |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.9%    |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.9%    |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.9%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.9%    |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.9%    |
| Nvidia GA100 [A100 SXM4 40GB]                                               | 1        | 0.9%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 39       | 38.24%  |
| 1 x AMD          | 31       | 30.39%  |
| 1 x Intel        | 23       | 22.55%  |
| 1 x Matrox       | 2        | 1.96%   |
| Intel + AMD      | 2        | 1.96%   |
| 2 x AMD          | 1        | 0.98%   |
| Nvidia + Matrox  | 1        | 0.98%   |
| Intel + Nvidia   | 1        | 0.98%   |
| AMD + 2 x Nvidia | 1        | 0.98%   |
| AMD + Nvidia     | 1        | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 70       | 68.63%  |
| Proprietary | 26       | 25.49%  |
| Unknown     | 6        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 65       | 61.32%  |
| 1.01-2.0   | 12       | 11.32%  |
| 0.01-0.5   | 9        | 8.49%   |
| 3.01-4.0   | 8        | 7.55%   |
| 5.01-6.0   | 4        | 3.77%   |
| 7.01-8.0   | 3        | 2.83%   |
| 8.01-16.0  | 2        | 1.89%   |
| 24.01-32.0 | 1        | 0.94%   |
| 2.01-3.0   | 1        | 0.94%   |
| 0.51-1.0   | 1        | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 18       | 17.31%  |
| Goldstar                | 14       | 13.46%  |
| AOC                     | 10       | 9.62%   |
| Hewlett-Packard         | 8        | 7.69%   |
| Dell                    | 6        | 5.77%   |
| Acer                    | 5        | 4.81%   |
| Unknown                 | 4        | 3.85%   |
| Philips                 | 4        | 3.85%   |
| Fujitsu Siemens         | 4        | 3.85%   |
| BenQ                    | 4        | 3.85%   |
| Ancor Communications    | 4        | 3.85%   |
| ViewSonic               | 2        | 1.92%   |
| Panasonic               | 2        | 1.92%   |
| Lenovo                  | 2        | 1.92%   |
| Iiyama                  | 2        | 1.92%   |
| Eizo                    | 2        | 1.92%   |
| ASUSTek Computer        | 2        | 1.92%   |
| ___                     | 1        | 0.96%   |
| Sun                     | 1        | 0.96%   |
| Sony                    | 1        | 0.96%   |
| RTK                     | 1        | 0.96%   |
| Plain Tree Systems      | 1        | 0.96%   |
| InnoView                | 1        | 0.96%   |
| Hitachi                 | 1        | 0.96%   |
| Gigabyte Technology     | 1        | 0.96%   |
| EDI                     | 1        | 0.96%   |
| Chi Mei Optoelectronics | 1        | 0.96%   |
| BBY                     | 1        | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 1.8%    |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.9%    |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch          | 1        | 0.9%    |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1        | 0.9%    |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1        | 0.9%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.9%    |
| Unknown LCD Monitor KON TV_MONITOR 1920x1080                          | 1        | 0.9%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.9%    |
| Sun X7149A SUN058A 1600x1200 400x300mm 19.7-inch                      | 1        | 0.9%    |
| Sony TV SNY2203 1920x1080 560x420mm 27.6-inch                         | 1        | 0.9%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 1        | 0.9%    |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 1        | 0.9%    |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1        | 0.9%    |
| Samsung Electronics SyncMaster SAM0427 1920x1200                      | 1        | 0.9%    |
| Samsung Electronics SyncMaster SAM0425 1920x1200 518x324mm 24.1-inch  | 1        | 0.9%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.9%    |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1        | 0.9%    |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch     | 1        | 0.9%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 0.9%    |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 1        | 0.9%    |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch     | 1        | 0.9%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 0.9%    |
| Samsung Electronics LCD Monitor SMS27A350H 1920x1080                  | 1        | 0.9%    |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch | 1        | 0.9%    |
| Samsung Electronics LCD Monitor SAM07C3 1920x1080 700x390mm 31.5-inch | 1        | 0.9%    |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                     | 1        | 0.9%    |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 1        | 0.9%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 0.9%    |
| RTK TV RTK0001 3840x2160                                              | 1        | 0.9%    |
| Plain Tree Systems Monitor PTS05DD 1024x768 304x228mm 15.0-inch       | 1        | 0.9%    |
| Philips PHL 326P1 PHL0957 2560x1440 698x393mm 31.5-inch               | 1        | 0.9%    |
| Philips LCD Monitor PHL 241E1 3840x1080                               | 1        | 0.9%    |
| Philips LCD Monitor PHL 241E1 1920x1080                               | 1        | 0.9%    |
| Philips LCD Monitor FTV                                               | 1        | 0.9%    |
| Philips FTV PHL0583 3840x2160 1440x810mm 65.0-inch                    | 1        | 0.9%    |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                   | 1        | 0.9%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1        | 0.9%    |
| Panasonic TV MEIA0C9 1920x1080 698x392mm 31.5-inch                    | 1        | 0.9%    |
| Lenovo LEN-E91-B LEN0005 1920x1080 476x268mm 21.5-inch                | 1        | 0.9%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1        | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 42.57%  |
| 3840x2160 (4K)     | 10       | 9.9%    |
| 1280x1024 (SXGA)   | 9        | 8.91%   |
| 2560x1440 (QHD)    | 6        | 5.94%   |
| 1920x1200 (WUXGA)  | 6        | 5.94%   |
| 1680x1050 (WSXGA+) | 4        | 3.96%   |
| 1440x900 (WXGA+)   | 4        | 3.96%   |
| 1366x768 (WXGA)    | 3        | 2.97%   |
| 3840x1080          | 2        | 1.98%   |
| 2560x1080          | 2        | 1.98%   |
| 1920x540           | 2        | 1.98%   |
| 1600x900 (HD+)     | 2        | 1.98%   |
| 1360x768           | 2        | 1.98%   |
| Unknown            | 2        | 1.98%   |
| 3440x1440          | 1        | 0.99%   |
| 2288x1287          | 1        | 0.99%   |
| 1600x1200          | 1        | 0.99%   |
| 1024x768 (XGA)     | 1        | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 21       | 21.21%  |
| 23      | 10       | 10.1%   |
| 27      | 9        | 9.09%   |
| 31      | 8        | 8.08%   |
| 21      | 8        | 8.08%   |
| Unknown | 8        | 8.08%   |
| 19      | 7        | 7.07%   |
| 17      | 4        | 4.04%   |
| 22      | 3        | 3.03%   |
| 18      | 3        | 3.03%   |
| 15      | 3        | 3.03%   |
| 72      | 2        | 2.02%   |
| 54      | 2        | 2.02%   |
| 34      | 2        | 2.02%   |
| 20      | 2        | 2.02%   |
| 142     | 1        | 1.01%   |
| 84      | 1        | 1.01%   |
| 65      | 1        | 1.01%   |
| 43      | 1        | 1.01%   |
| 35      | 1        | 1.01%   |
| 32      | 1        | 1.01%   |
| 25      | 1        | 1.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 37       | 38.54%  |
| 401-500        | 17       | 17.71%  |
| 601-700        | 9        | 9.38%   |
| Unknown        | 8        | 8.33%   |
| 351-400        | 7        | 7.29%   |
| 301-350        | 6        | 6.25%   |
| 701-800        | 3        | 3.13%   |
| 1501-2000      | 3        | 3.13%   |
| 1001-1500      | 3        | 3.13%   |
| More than 2000 | 1        | 1.04%   |
| 801-900        | 1        | 1.04%   |
| 901-1000       | 1        | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 61.96%  |
| 16/10   | 15       | 16.3%   |
| 5/4     | 7        | 7.61%   |
| Unknown | 5        | 5.43%   |
| 4/3     | 3        | 3.26%   |
| 21/9    | 3        | 3.26%   |
| 6/5     | 1        | 1.09%   |
| 1.00    | 1        | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 29.17%  |
| 351-500        | 13       | 13.54%  |
| 151-200        | 13       | 13.54%  |
| 251-300        | 9        | 9.38%   |
| 301-350        | 8        | 8.33%   |
| Unknown        | 8        | 8.33%   |
| More than 1000 | 7        | 7.29%   |
| 141-150        | 5        | 5.21%   |
| 101-110        | 3        | 3.13%   |
| 131-140        | 1        | 1.04%   |
| 501-1000       | 1        | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 65       | 69.15%  |
| 101-120 | 13       | 13.83%  |
| Unknown | 8        | 8.51%   |
| 1-50    | 5        | 5.32%   |
| 121-160 | 3        | 3.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 73       | 71.57%  |
| 2     | 18       | 17.65%  |
| 0     | 9        | 8.82%   |
| 3     | 2        | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 72       | 52.94%  |
| Intel                    | 32       | 23.53%  |
| Broadcom                 | 7        | 5.15%   |
| Qualcomm Atheros         | 6        | 4.41%   |
| Ralink Technology        | 3        | 2.21%   |
| MediaTek                 | 2        | 1.47%   |
| D-Link System            | 2        | 1.47%   |
| ASUSTek Computer         | 2        | 1.47%   |
| TP-Link                  | 1        | 0.74%   |
| Samsung Electronics      | 1        | 0.74%   |
| Ralink                   | 1        | 0.74%   |
| QLogic                   | 1        | 0.74%   |
| OPPO Electronics         | 1        | 0.74%   |
| Marvell Technology Group | 1        | 0.74%   |
| Linksys                  | 1        | 0.74%   |
| Belkin Components        | 1        | 0.74%   |
| Atmel                    | 1        | 0.74%   |
| ASIX Electronics         | 1        | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 57       | 35.4%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 3        | 1.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3        | 1.86%   |
| Intel I211 Gigabit Network Connection                                         | 3        | 1.86%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 1.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.24%   |
| Realtek RTL8187 Wireless Adapter                                              | 2        | 1.24%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 1.24%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.24%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2        | 1.24%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 1.24%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.24%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 1.24%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.24%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.24%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.62%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                   | 1        | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.62%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.62%   |
| Realtek Killer E2600 GbE Controller                                           | 1        | 0.62%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.62%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 0.62%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.62%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.62%   |
| QLogic ISP8324 1/10GbE Converged Network Controller                           | 1        | 0.62%   |
| QLogic 8300 Series 10GbE Converged Network Adapter (iSCSI)                    | 1        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 35.56%  |
| Intel                 | 11       | 24.44%  |
| Qualcomm Atheros      | 4        | 8.89%   |
| Ralink Technology     | 3        | 6.67%   |
| MediaTek              | 2        | 4.44%   |
| D-Link System         | 2        | 4.44%   |
| ASUSTek Computer      | 2        | 4.44%   |
| TP-Link               | 1        | 2.22%   |
| Ralink                | 1        | 2.22%   |
| Linksys               | 1        | 2.22%   |
| Broadcom              | 1        | 2.22%   |
| Belkin Components     | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 3        | 6.52%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3        | 6.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 4.35%   |
| Realtek RTL8187 Wireless Adapter                                              | 2        | 4.35%   |
| Realtek 802.11ac NIC                                                          | 2        | 4.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 4.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 4.35%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 2.17%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                   | 1        | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 2.17%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2.17%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 2.17%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 2.17%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 2.17%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1        | 2.17%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]        | 1        | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 2.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1        | 2.17%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1        | 2.17%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.E1) [Ralink RT2070]     | 1        | 2.17%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.17%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU]       | 1        | 2.17%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                      | 1        | 2.17%   |
| ASUS 802.11n WLAN Adapter                                                     | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 67       | 62.04%  |
| Intel                    | 27       | 25%     |
| Broadcom                 | 6        | 5.56%   |
| Qualcomm Atheros         | 3        | 2.78%   |
| Samsung Electronics      | 1        | 0.93%   |
| QLogic                   | 1        | 0.93%   |
| OPPO Electronics         | 1        | 0.93%   |
| Marvell Technology Group | 1        | 0.93%   |
| ASIX Electronics         | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 57       | 50.44%  |
| Realtek RTL8125 2.5GbE Controller                                      | 7        | 6.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 5.31%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 2.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 2.65%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.77%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 1.77%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.77%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2        | 1.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.88%   |
| Realtek Killer E2600 GbE Controller                                    | 1        | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.88%   |
| QLogic ISP8324 1/10GbE Converged Network Controller                    | 1        | 0.88%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1        | 0.88%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1        | 0.88%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.88%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.88%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.88%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.88%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.88%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.88%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.88%   |
| Intel 82567LF-2 Gigabit Network Connection                             | 1        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.88%   |
| Intel 82541PI Gigabit Ethernet Controller                              | 1        | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 0.88%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                | 1        | 0.88%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                       | 1        | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 100      | 70.42%  |
| WiFi     | 40       | 28.17%  |
| Modem    | 1        | 0.7%    |
| Unknown  | 1        | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 89       | 83.18%  |
| WiFi     | 18       | 16.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 62.38%  |
| 2     | 31       | 30.69%  |
| 3     | 3        | 2.97%   |
| 0     | 2        | 1.98%   |
| 8     | 1        | 0.99%   |
| 4     | 1        | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 57.84%  |
| Yes  | 43       | 42.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 32.26%  |
| Cambridge Silicon Radio | 9        | 29.03%  |
| Realtek Semiconductor   | 8        | 25.81%  |
| TP-Link                 | 1        | 3.23%   |
| MediaTek                | 1        | 3.23%   |
| IMC Networks            | 1        | 3.23%   |
| ASUSTek Computer        | 1        | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 29.03%  |
| Realtek Bluetooth Radio                             | 8        | 25.81%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 9.68%   |
| Intel AX210 Bluetooth                               | 2        | 6.45%   |
| Intel AX200 Bluetooth                               | 2        | 6.45%   |
| TP-Link UB500 Adapter                               | 1        | 3.23%   |
| MediaTek Wireless_Device                            | 1        | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.23%   |
| Intel AX201 Bluetooth                               | 1        | 3.23%   |
| IMC Networks Wireless_Device                        | 1        | 3.23%   |
| ASUS BCM20702A0                                     | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 52       | 32.3%   |
| Intel                                | 51       | 31.68%  |
| Nvidia                               | 40       | 24.84%  |
| C-Media Electronics                  | 5        | 3.11%   |
| Sennheiser Communications            | 2        | 1.24%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.62%   |
| Texas Instruments                    | 1        | 0.62%   |
| Sony                                 | 1        | 0.62%   |
| RODE Microphones                     | 1        | 0.62%   |
| ONN                                  | 1        | 0.62%   |
| Micro Star International             | 1        | 0.62%   |
| Logitech                             | 1        | 0.62%   |
| HiBy                                 | 1        | 0.62%   |
| GN Netcom                            | 1        | 0.62%   |
| FiiO Electronics Technology          | 1        | 0.62%   |
| Creative Labs                        | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 6.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 5.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 4.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 4.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 3.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 2.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 2.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.63%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.11%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.58%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.58%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 3        | 1.58%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.58%   |
| Sennheiser Communications Headset [PC 8]                                   | 2        | 1.05%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.05%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.05%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 2        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 1.05%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 1        | 0.53%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 7        | 18.92%  |
| Unknown             | 5        | 13.51%  |
| Samsung Electronics | 5        | 13.51%  |
| Kingston            | 5        | 13.51%  |
| SK hynix            | 3        | 8.11%   |
| Micron Technology   | 2        | 5.41%   |
| Hewlett-Packard     | 2        | 5.41%   |
| G.Skill             | 2        | 5.41%   |
| Crucial             | 2        | 5.41%   |
| Unknown (ABCD)      | 1        | 2.7%    |
| Team                | 1        | 2.7%    |
| Lexar               | 1        | 2.7%    |
| A-DATA Technology   | 1        | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 2.63%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 2.63%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                      | 1        | 2.63%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 2.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 2.63%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 2.63%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3200MT/s            | 1        | 2.63%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 2.63%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 2.63%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 2.63%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                     | 1        | 2.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s            | 1        | 2.63%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s            | 1        | 2.63%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 1        | 2.63%   |
| Samsung RAM M378A2G43CB3-CWE 16GB DIMM DDR4 3200MT/s           | 1        | 2.63%   |
| Micron RAM 8ATF1G64HZ-2G3B2 8GB DIMM DDR4 2667MT/s             | 1        | 2.63%   |
| Micron RAM 36JSZF1G72PZ-1G4D1 8GB DIMM DDR3 1333MT/s           | 1        | 2.63%   |
| Lexar RAM LD4AS016G-3200ST 16GB SODIMM DDR4 3200MT/s           | 1        | 2.63%   |
| Kingston RAM KHX2933C17D4/16G 16GB DIMM DDR4 2933MT/s          | 1        | 2.63%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s            | 1        | 2.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 1        | 2.63%   |
| Kingston RAM KF1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 1        | 2.63%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 2.63%   |
| HP RAM 669238-071 4GB DIMM DDR3 1600MT/s                       | 1        | 2.63%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                       | 1        | 2.63%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 1        | 2.63%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s           | 1        | 2.63%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s        | 1        | 2.63%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s       | 1        | 2.63%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 1        | 2.63%   |
| Corsair RAM CMK96GX5M2B5600C40 48GB DIMM DDR5 4800MT/s         | 1        | 2.63%   |
| Corsair RAM CMK32GX4M2Z2400C16 16GB DIMM DDR4 2400MT/s         | 1        | 2.63%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 1        | 2.63%   |
| Corsair RAM CMK32GX4M2A2133C13 16GB DIMM DDR4 2133MT/s         | 1        | 2.63%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 1        | 2.63%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s          | 1        | 2.63%   |
| A-DATA RAM Module 32GB DIMM DDR4 3200MT/s                      | 1        | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 54.29%  |
| DDR3    | 9        | 25.71%  |
| SDRAM   | 2        | 5.71%   |
| LPDDR4  | 1        | 2.86%   |
| DDR5    | 1        | 2.86%   |
| DDR2    | 1        | 2.86%   |
| DDR     | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 97.06%  |
| SODIMM | 1        | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 11       | 30.56%  |
| 8192  | 10       | 27.78%  |
| 4096  | 6        | 16.67%  |
| 2048  | 6        | 16.67%  |
| 32768 | 2        | 5.56%   |
| 49152 | 1        | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 8        | 22.22%  |
| 1600    | 5        | 13.89%  |
| 1333    | 5        | 13.89%  |
| 2933    | 2        | 5.56%   |
| 2667    | 2        | 5.56%   |
| 2400    | 2        | 5.56%   |
| 4800    | 1        | 2.78%   |
| 3866    | 1        | 2.78%   |
| 3666    | 1        | 2.78%   |
| 3600    | 1        | 2.78%   |
| 3534    | 1        | 2.78%   |
| 3066    | 1        | 2.78%   |
| 2133    | 1        | 2.78%   |
| 1867    | 1        | 2.78%   |
| 1334    | 1        | 2.78%   |
| 800     | 1        | 2.78%   |
| 533     | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 5        | 35.71%  |
| Hewlett-Packard     | 3        | 21.43%  |
| Brother Industries  | 3        | 21.43%  |
| Xerox               | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Pantum              | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Xerox WorkCentre 3220      | 1        | 7.14%   |
| Seiko Epson XP-4200 Series | 1        | 7.14%   |
| Seiko Epson XP-4100 Series | 1        | 7.14%   |
| Seiko Epson WF-4830 Series | 1        | 7.14%   |
| Seiko Epson L300 Series    | 1        | 7.14%   |
| Seiko Epson ET-2820 Series | 1        | 7.14%   |
| Samsung Phaser 3121        | 1        | 7.14%   |
| Pantum P2200-series        | 1        | 7.14%   |
| HP LaserJet 1200           | 1        | 7.14%   |
| HP LaserJet 1018           | 1        | 7.14%   |
| HP Ink Tank 310 series     | 1        | 7.14%   |
| Brother MFC-7360N          | 1        | 7.14%   |
| Brother HL-L3230CDW series | 1        | 7.14%   |
| Brother DCP-L2520DW        | 1        | 7.14%   |

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
| Logitech                | 6        | 42.86%  |
| Microdia                | 2        | 14.29%  |
| Z-Star Microelectronics | 1        | 7.14%   |
| Trust                   | 1        | 7.14%   |
| Realtek Semiconductor   | 1        | 7.14%   |
| Microsoft               | 1        | 7.14%   |
| Creative Technology     | 1        | 7.14%   |
| Chicony Electronics     | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Integrated Camera          | 1        | 7.14%   |
| Trust WB-6250X Webcam             | 1        | 7.14%   |
| Realtek USB 2.0 Camera            | 1        | 7.14%   |
| Microsoft LifeCam HD-3000         | 1        | 7.14%   |
| Microdia Webcam Vitade AF         | 1        | 7.14%   |
| Microdia USB 2.0 Camera           | 1        | 7.14%   |
| Logitech Webcam Pro 9000          | 1        | 7.14%   |
| Logitech QuickCam Vision Pro      | 1        | 7.14%   |
| Logitech QuickCam Pro 9000        | 1        | 7.14%   |
| Logitech HD Webcam C615           | 1        | 7.14%   |
| Logitech CrystalCam               | 1        | 7.14%   |
| Logitech BCC950 ConferenceCam     | 1        | 7.14%   |
| Creative VF0530 Live! Cam Chat IM | 1        | 7.14%   |
| Chicony CNF8050 Webcam            | 1        | 7.14%   |

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
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 84       | 79.25%  |
| 1     | 16       | 15.09%  |
| 2     | 6        | 5.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 9        | 39.13%  |
| Net/wireless          | 6        | 26.09%  |
| Sound                 | 2        | 8.7%    |
| Unassigned class      | 1        | 4.35%   |
| Net/ethernet          | 1        | 4.35%   |
| Multimedia controller | 1        | 4.35%   |
| Fingerprint reader    | 1        | 4.35%   |
| Chipcard              | 1        | 4.35%   |
| Card reader           | 1        | 4.35%   |

