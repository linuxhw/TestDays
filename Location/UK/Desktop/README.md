Linux in UK - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 5061

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY NOK                | [26332591d7](https://linux-hardware.org/?probe=26332591d7) | Nov 06, 2023 |
| GMKtec        | NucBox K2                   | [a88d491579](https://linux-hardware.org/?probe=a88d491579) | Nov 06, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [d95f04dd2c](https://linux-hardware.org/?probe=d95f04dd2c) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [f48ca40214](https://linux-hardware.org/?probe=f48ca40214) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [5196f9303d](https://linux-hardware.org/?probe=5196f9303d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| Gigabyte      | GA-970A-DS3                 | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [4e3cd50b3f](https://linux-hardware.org/?probe=4e3cd50b3f) | Nov 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | 03TJ75 A00                  | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [1ca6496a6c](https://linux-hardware.org/?probe=1ca6496a6c) | Nov 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [801d83a570](https://linux-hardware.org/?probe=801d83a570) | Nov 01, 2023 |
| HP            | 0A58h                       | [9dd3c3fdfb](https://linux-hardware.org/?probe=9dd3c3fdfb) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Unknown       | Unknown                     | [c7ce75613c](https://linux-hardware.org/?probe=c7ce75613c) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| MSI           | Z87-G45 GAMING              | [962f4ccb9e](https://linux-hardware.org/?probe=962f4ccb9e) | Oct 31, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| HP            | 0A58h                       | [f7c62b9410](https://linux-hardware.org/?probe=f7c62b9410) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| Intel         | H311 DS3 V1.0               | [2eabffe817](https://linux-hardware.org/?probe=2eabffe817) | Oct 31, 2023 |
| Gigabyte      | B365M DS3H                  | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9ca810aaa6](https://linux-hardware.org/?probe=9ca810aaa6) | Oct 29, 2023 |
| Biostar       | G31D-M7                     | [192416033b](https://linux-hardware.org/?probe=192416033b) | Oct 28, 2023 |
| ASRock        | B450 Steel Legend           | [967ed7a2b9](https://linux-hardware.org/?probe=967ed7a2b9) | Oct 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| MSI           | PRO Z790-P WIFI             | [60372b59fe](https://linux-hardware.org/?probe=60372b59fe) | Oct 28, 2023 |
| HP            | 2AF3                        | [f7c7d92cea](https://linux-hardware.org/?probe=f7c7d92cea) | Oct 28, 2023 |
| MSI           | B450M MORTAR MAX            | [ab3b2be8f5](https://linux-hardware.org/?probe=ab3b2be8f5) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | [8f83740c8d](https://linux-hardware.org/?probe=8f83740c8d) | Oct 26, 2023 |
| Foxconn       | 2AA9h                       | [dade54701d](https://linux-hardware.org/?probe=dade54701d) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [8926585836](https://linux-hardware.org/?probe=8926585836) | Oct 26, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b75faeaf8a](https://linux-hardware.org/?probe=b75faeaf8a) | Oct 25, 2023 |
| ASRock        | A520M-ITX/ac                | [8a5e0bd9d6](https://linux-hardware.org/?probe=8a5e0bd9d6) | Oct 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [f88a2686e9](https://linux-hardware.org/?probe=f88a2686e9) | Oct 25, 2023 |
| ASUSTek       | Z170-P                      | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Acer          | Aspire XC-1760              | [8a5c420847](https://linux-hardware.org/?probe=8a5c420847) | Oct 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [268b32d9bf](https://linux-hardware.org/?probe=268b32d9bf) | Oct 24, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2d6bcd74d8](https://linux-hardware.org/?probe=2d6bcd74d8) | Oct 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | [95b5ac0a0e](https://linux-hardware.org/?probe=95b5ac0a0e) | Oct 24, 2023 |
| Gigabyte      | B365M DS3H                  | [87102526a5](https://linux-hardware.org/?probe=87102526a5) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| Gigabyte      | A520I AC                    | [fc82aed364](https://linux-hardware.org/?probe=fc82aed364) | Oct 23, 2023 |
| Gigabyte      | H310M H x.x                 | [d8c12e782e](https://linux-hardware.org/?probe=d8c12e782e) | Oct 23, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [98a242f151](https://linux-hardware.org/?probe=98a242f151) | Oct 21, 2023 |
| Lenovo        | ThinkServer TS140           | [b52eba9a1b](https://linux-hardware.org/?probe=b52eba9a1b) | Oct 21, 2023 |
| ASRock        | X570 Pro4                   | [f350ad7b18](https://linux-hardware.org/?probe=f350ad7b18) | Oct 20, 2023 |
| MSI           | G41TM-P31                   | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Pegatron      | Benicia                     | [c8ec5c8db0](https://linux-hardware.org/?probe=c8ec5c8db0) | Oct 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Acer          | Aspire TC-1760              | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [534b565ca1](https://linux-hardware.org/?probe=534b565ca1) | Oct 18, 2023 |
| HP            | 3646h                       | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| HP            | 2B44                        | [9ec07b67b2](https://linux-hardware.org/?probe=9ec07b67b2) | Oct 18, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| Gigabyte      | H310M H x.x                 | [98b06c3d78](https://linux-hardware.org/?probe=98b06c3d78) | Oct 17, 2023 |
| Shenzhen M... | F7BSC                       | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| HP            | ProLiant ML350 Gen9         | [468a686a40](https://linux-hardware.org/?probe=468a686a40) | Oct 15, 2023 |
| ASRock        | B85M                        | [1712e16d1c](https://linux-hardware.org/?probe=1712e16d1c) | Oct 15, 2023 |
| Dell          | 0MWYPT A01                  | [67933e3dd7](https://linux-hardware.org/?probe=67933e3dd7) | Oct 14, 2023 |
| Dell          | 0Y2K8N A01                  | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| Gigabyte      | Z170M-D3H-CF                | [c090855f1d](https://linux-hardware.org/?probe=c090855f1d) | Oct 13, 2023 |
| Inventec      | DQ Class A02                | [675695eef9](https://linux-hardware.org/?probe=675695eef9) | Oct 12, 2023 |
| Intel         | X99-P4 V1.0                 | [afe1fd91c2](https://linux-hardware.org/?probe=afe1fd91c2) | Oct 12, 2023 |
| ASUSTek       | Q170M-C                     | [07a8a2d89f](https://linux-hardware.org/?probe=07a8a2d89f) | Oct 12, 2023 |
| Gigabyte      | A320M-H-CF                  | [a549a213f1](https://linux-hardware.org/?probe=a549a213f1) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| MSI           | X470 GAMING PLUS            | [5d9cf3ae21](https://linux-hardware.org/?probe=5d9cf3ae21) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Dell          | 03NVJ6 A02                  | [0f40b40836](https://linux-hardware.org/?probe=0f40b40836) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Gigabyte      | B550M DS3H                  | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [22d9a872fe](https://linux-hardware.org/?probe=22d9a872fe) | Oct 10, 2023 |
| Lenovo        | SHARKBAY NOK                | [b14d9fc84b](https://linux-hardware.org/?probe=b14d9fc84b) | Oct 10, 2023 |
| Dell          | 03NVJ6 A02                  | [8f7a44301e](https://linux-hardware.org/?probe=8f7a44301e) | Oct 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec66d208a0](https://linux-hardware.org/?probe=ec66d208a0) | Oct 10, 2023 |
| Gigabyte      | Z690 UD DDR4                | [8b0cd9f9f7](https://linux-hardware.org/?probe=8b0cd9f9f7) | Oct 10, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ac48da1d5c](https://linux-hardware.org/?probe=ac48da1d5c) | Oct 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [165a7d4ae1](https://linux-hardware.org/?probe=165a7d4ae1) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Acer          | Aspire TC-1760              | [c9e56d83be](https://linux-hardware.org/?probe=c9e56d83be) | Oct 08, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [7623527bdb](https://linux-hardware.org/?probe=7623527bdb) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [71ab2a6c8b](https://linux-hardware.org/?probe=71ab2a6c8b) | Oct 07, 2023 |
| MSI           | Z97 PC Mate                 | [6e2fa2dc88](https://linux-hardware.org/?probe=6e2fa2dc88) | Oct 07, 2023 |
| Dell          | 0WR7PY A02                  | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| Gigabyte      | B550 GAMING X V2            | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [b00d1d81e3](https://linux-hardware.org/?probe=b00d1d81e3) | Oct 05, 2023 |
| HP            | 8350                        | [28bfb834e4](https://linux-hardware.org/?probe=28bfb834e4) | Oct 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cbf93da8d0](https://linux-hardware.org/?probe=cbf93da8d0) | Oct 04, 2023 |
| Dell          | 0VNM11 A00                  | [127d9678c2](https://linux-hardware.org/?probe=127d9678c2) | Oct 04, 2023 |
| ECS           | GF8100VM-M5                 | [4534c53242](https://linux-hardware.org/?probe=4534c53242) | Oct 03, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab5cf455ba](https://linux-hardware.org/?probe=ab5cf455ba) | Oct 03, 2023 |
| IP3 Tech      | IB8                         | [ca4d58a353](https://linux-hardware.org/?probe=ca4d58a353) | Oct 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c5223b1e21](https://linux-hardware.org/?probe=c5223b1e21) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [06f658c722](https://linux-hardware.org/?probe=06f658c722) | Oct 02, 2023 |
| Gigabyte      | H310M H x.x                 | [3c76ca2934](https://linux-hardware.org/?probe=3c76ca2934) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| Intel         | D33217CK G76541-302         | [d1aab6a8d0](https://linux-hardware.org/?probe=d1aab6a8d0) | Sep 29, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [c602f8fba9](https://linux-hardware.org/?probe=c602f8fba9) | Sep 29, 2023 |
| ASUSTek       | P8H61-MX USB3               | [5d1175b3f3](https://linux-hardware.org/?probe=5d1175b3f3) | Sep 28, 2023 |
| HP            | 3397                        | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H61-MX USB3               | [31fe0087b8](https://linux-hardware.org/?probe=31fe0087b8) | Sep 28, 2023 |
| Lenovo        | ThinkServer TS140           | [0e08685628](https://linux-hardware.org/?probe=0e08685628) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS140           | [461eeadd52](https://linux-hardware.org/?probe=461eeadd52) | Sep 26, 2023 |
| BESSTAR Te... | UM700                       | [efd53d662d](https://linux-hardware.org/?probe=efd53d662d) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [e7a6f47b2f](https://linux-hardware.org/?probe=e7a6f47b2f) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [8b10c3ad64](https://linux-hardware.org/?probe=8b10c3ad64) | Sep 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6185e37a03](https://linux-hardware.org/?probe=6185e37a03) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| HP            | 1998                        | [f2c4af4cb6](https://linux-hardware.org/?probe=f2c4af4cb6) | Sep 22, 2023 |
| HP            | 1998                        | [ef51f7d583](https://linux-hardware.org/?probe=ef51f7d583) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [d9d063b9e8](https://linux-hardware.org/?probe=d9d063b9e8) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | GA-970A-DS3                 | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| Dell          | 0GY6Y8 A02                  | [92b6ccd3ad](https://linux-hardware.org/?probe=92b6ccd3ad) | Sep 21, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [6aae39a72b](https://linux-hardware.org/?probe=6aae39a72b) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| Unknown       | Unknown                     | [043be725eb](https://linux-hardware.org/?probe=043be725eb) | Sep 21, 2023 |
| Dell          | 0RY206                      | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| MSI           | Z270 GAMING M5              | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [85d131b5fc](https://linux-hardware.org/?probe=85d131b5fc) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Unknown       | Unknown                     | [2d2ec7d22c](https://linux-hardware.org/?probe=2d2ec7d22c) | Sep 18, 2023 |
| Gigabyte      | Z97P-D3                     | [3baa74b1a6](https://linux-hardware.org/?probe=3baa74b1a6) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| HP            | 0A9Ch                       | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| Intel         | JSL MRD                     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| HP            | 2B36                        | [ac92866980](https://linux-hardware.org/?probe=ac92866980) | Sep 11, 2023 |
| Dell          | 0GXM1W A01                  | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [dc3c32cc6a](https://linux-hardware.org/?probe=dc3c32cc6a) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| ASUSTek       | M4A87TD/USB3                | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| ASRock        | A520M-ITX/ac                | [0429117716](https://linux-hardware.org/?probe=0429117716) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| HP            | 1497                        | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| ASRock        | Z87 Pro4                    | [89b861e771](https://linux-hardware.org/?probe=89b861e771) | Sep 06, 2023 |
| HP            | 1497                        | [66bc78bedb](https://linux-hardware.org/?probe=66bc78bedb) | Sep 05, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [dcb565d513](https://linux-hardware.org/?probe=dcb565d513) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| ASUSTek       | A88XM-E                     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [15826e3d9e](https://linux-hardware.org/?probe=15826e3d9e) | Sep 04, 2023 |
| Unknown       | Unknown                     | [a0e83b70f5](https://linux-hardware.org/?probe=a0e83b70f5) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| MSI           | B560M PRO-E                 | [17eed28ecb](https://linux-hardware.org/?probe=17eed28ecb) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| MSI           | A320M-A PRO M2              | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | 0P01GV A03                  | [ef4d28f614](https://linux-hardware.org/?probe=ef4d28f614) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Dell          | 0D6H9T A00                  | [9830dce088](https://linux-hardware.org/?probe=9830dce088) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| AZW           | MINI S                      | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| ASUSTek       | PRIME Z270-P                | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d97cedcf3c](https://linux-hardware.org/?probe=d97cedcf3c) | Aug 28, 2023 |
| HC Technol... | HCAR5000-MI                 | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b217724e7](https://linux-hardware.org/?probe=2b217724e7) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [306a487e6d](https://linux-hardware.org/?probe=306a487e6d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| Dell          | 0RY206                      | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | [88e192b5f0](https://linux-hardware.org/?probe=88e192b5f0) | Aug 27, 2023 |
| HP            | 843C                        | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | [fc3a889045](https://linux-hardware.org/?probe=fc3a889045) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| MSI           | A320M-A PRO                 | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [3add2f8945](https://linux-hardware.org/?probe=3add2f8945) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [3ddae42f27](https://linux-hardware.org/?probe=3ddae42f27) | Aug 25, 2023 |
| MSI           | B550-A PRO                  | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [3a0ddb0171](https://linux-hardware.org/?probe=3a0ddb0171) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [fe7b3d01bb](https://linux-hardware.org/?probe=fe7b3d01bb) | Aug 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | [e5301a4a98](https://linux-hardware.org/?probe=e5301a4a98) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| HP            | 8054                        | [d5582dbf37](https://linux-hardware.org/?probe=d5582dbf37) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| Pegatron      | 2A94h                       | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| MSI           | Indio                       | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Dell          | 0KP561                      | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| Dell          | 0VRWRC A00                  | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| Gigabyte      | Z590 VISION G               | [0954ff78e7](https://linux-hardware.org/?probe=0954ff78e7) | Aug 16, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [c3d834a0df](https://linux-hardware.org/?probe=c3d834a0df) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| MSI           | 970A-G46                    | [d1b6347c9a](https://linux-hardware.org/?probe=d1b6347c9a) | Aug 15, 2023 |
| Dell          | 0RY206                      | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B450 GAMING X               | [d6cfe894c9](https://linux-hardware.org/?probe=d6cfe894c9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [a4f97e45f1](https://linux-hardware.org/?probe=a4f97e45f1) | Aug 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [a737674e04](https://linux-hardware.org/?probe=a737674e04) | Aug 12, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ee14fdafcf](https://linux-hardware.org/?probe=ee14fdafcf) | Aug 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [67414922e3](https://linux-hardware.org/?probe=67414922e3) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [8d27e3953f](https://linux-hardware.org/?probe=8d27e3953f) | Aug 09, 2023 |
| Dell          | 02YYK5 A00                  | [14382141e9](https://linux-hardware.org/?probe=14382141e9) | Aug 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [691838cd8c](https://linux-hardware.org/?probe=691838cd8c) | Aug 09, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| MSI           | 970A-G43                    | [68384da884](https://linux-hardware.org/?probe=68384da884) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| Gigabyte      | H81M-S2H                    | [247f361473](https://linux-hardware.org/?probe=247f361473) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Gigabyte      | H81M-S2H                    | [f74b524df1](https://linux-hardware.org/?probe=f74b524df1) | Aug 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [cc7ae6c4e9](https://linux-hardware.org/?probe=cc7ae6c4e9) | Aug 04, 2023 |
| Gigabyte      | B450 GAMING X               | [bb292f568a](https://linux-hardware.org/?probe=bb292f568a) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B760-A GAMING ... | [f629b6e16e](https://linux-hardware.org/?probe=f629b6e16e) | Aug 03, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [04f8c42dba](https://linux-hardware.org/?probe=04f8c42dba) | Aug 02, 2023 |
| Supermicro    | X9DAi                       | [d7390704d8](https://linux-hardware.org/?probe=d7390704d8) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| Gigabyte      | H81M-S2H                    | [0e5d30b504](https://linux-hardware.org/?probe=0e5d30b504) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| HP            | 3398                        | [c271d5d40e](https://linux-hardware.org/?probe=c271d5d40e) | Jul 31, 2023 |
| MSI           | H81M-P33                    | [d5cb55a484](https://linux-hardware.org/?probe=d5cb55a484) | Jul 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [07a919f178](https://linux-hardware.org/?probe=07a919f178) | Jul 31, 2023 |
| Dell          | 0CU409                      | [7b665ec8f2](https://linux-hardware.org/?probe=7b665ec8f2) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2b75ad8b2c](https://linux-hardware.org/?probe=2b75ad8b2c) | Jul 30, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [2ba45b1cfa](https://linux-hardware.org/?probe=2ba45b1cfa) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [fecdf7e593](https://linux-hardware.org/?probe=fecdf7e593) | Jul 29, 2023 |
| Dell          | 0PU052                      | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [4895ec9de1](https://linux-hardware.org/?probe=4895ec9de1) | Jul 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| ASRock        | B450M Steel Legend          | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| MSI           | A68HM-E33 V2                | [858b41037e](https://linux-hardware.org/?probe=858b41037e) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [5be0e1a212](https://linux-hardware.org/?probe=5be0e1a212) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [4c4109b8f3](https://linux-hardware.org/?probe=4c4109b8f3) | Jul 23, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [d89bdeec87](https://linux-hardware.org/?probe=d89bdeec87) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [5072be5d0f](https://linux-hardware.org/?probe=5072be5d0f) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| Gigabyte      | H81M-DS2V                   | [f27670217e](https://linux-hardware.org/?probe=f27670217e) | Jul 22, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [9f52ae219f](https://linux-hardware.org/?probe=9f52ae219f) | Jul 22, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| MSI           | Z97 PC Mate                 | [a131a7a5fb](https://linux-hardware.org/?probe=a131a7a5fb) | Jul 21, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [6b8d5cb0c1](https://linux-hardware.org/?probe=6b8d5cb0c1) | Jul 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [1ee2e5b63d](https://linux-hardware.org/?probe=1ee2e5b63d) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [db1e3d03e2](https://linux-hardware.org/?probe=db1e3d03e2) | Jul 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [4dacb4cf51](https://linux-hardware.org/?probe=4dacb4cf51) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| Dell          | 073MMW A03                  | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASRock        | A320M-HDV R3.0              | [8e41b4b86d](https://linux-hardware.org/?probe=8e41b4b86d) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | [dc3bdab530](https://linux-hardware.org/?probe=dc3bdab530) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [2b9ee1f8b7](https://linux-hardware.org/?probe=2b9ee1f8b7) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | [fc3514e9a6](https://linux-hardware.org/?probe=fc3514e9a6) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| ASUSTek       | P5E-V HDMI                  | [460e520a69](https://linux-hardware.org/?probe=460e520a69) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f8ffcb4828](https://linux-hardware.org/?probe=f8ffcb4828) | Jul 12, 2023 |
| ASUSTek       | A88XM-E                     | [e951c1d4f4](https://linux-hardware.org/?probe=e951c1d4f4) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [db34bf69af](https://linux-hardware.org/?probe=db34bf69af) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | [059cda8a87](https://linux-hardware.org/?probe=059cda8a87) | Jul 11, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [59c50a4a34](https://linux-hardware.org/?probe=59c50a4a34) | Jul 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [0b6dcc1ea9](https://linux-hardware.org/?probe=0b6dcc1ea9) | Jul 09, 2023 |
| Unknown       | Unknown                     | [26896deb1e](https://linux-hardware.org/?probe=26896deb1e) | Jul 09, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | [84e16d3238](https://linux-hardware.org/?probe=84e16d3238) | Jul 09, 2023 |
| Dell          | 01TKCC A01                  | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Acer          | Nitro N50-620               | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [703f0e9012](https://linux-hardware.org/?probe=703f0e9012) | Jul 08, 2023 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [53d1debf85](https://linux-hardware.org/?probe=53d1debf85) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| Lenovo        | IdeaCentre B320             | [58bb7cf40a](https://linux-hardware.org/?probe=58bb7cf40a) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [9a6e78196d](https://linux-hardware.org/?probe=9a6e78196d) | Jul 06, 2023 |
| HP            | 3398                        | [3124ceac21](https://linux-hardware.org/?probe=3124ceac21) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Gigabyte      | H110-D3A-CF                 | [bd9c7a22d6](https://linux-hardware.org/?probe=bd9c7a22d6) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [da18aba906](https://linux-hardware.org/?probe=da18aba906) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [f9688a073f](https://linux-hardware.org/?probe=f9688a073f) | Jul 04, 2023 |
| Apple         | Mac-F4208DA9 PVT            | [6c2cdc1c76](https://linux-hardware.org/?probe=6c2cdc1c76) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [ed7caf91c0](https://linux-hardware.org/?probe=ed7caf91c0) | Jul 03, 2023 |
| Acer          | Aspire M3910                | [837d0f7852](https://linux-hardware.org/?probe=837d0f7852) | Jul 03, 2023 |
| Gigabyte      | H81M-S2H                    | [cf3da29bba](https://linux-hardware.org/?probe=cf3da29bba) | Jul 03, 2023 |
| ASUSTek       | WS X299 PRO_SE              | [d31cedc2ad](https://linux-hardware.org/?probe=d31cedc2ad) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [1b82430294](https://linux-hardware.org/?probe=1b82430294) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| Gigabyte      | B85-HD3                     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d9b6645cae](https://linux-hardware.org/?probe=d9b6645cae) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dea1298c2e](https://linux-hardware.org/?probe=dea1298c2e) | Jul 01, 2023 |
| Intel         | B85 V5.56                   | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Intel         | X99H                        | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Gigabyte      | H81M-S2H                    | [fe8b1af179](https://linux-hardware.org/?probe=fe8b1af179) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | [e1ed0643fb](https://linux-hardware.org/?probe=e1ed0643fb) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | [0e98c1f04a](https://linux-hardware.org/?probe=0e98c1f04a) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [ddb283952b](https://linux-hardware.org/?probe=ddb283952b) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| Gigabyte      | H81M-S2H                    | [9cb1b45a65](https://linux-hardware.org/?probe=9cb1b45a65) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| Dell          | 0P01GV A03                  | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| HP            | 859B                        | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| Unknown       | Unknown                     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| ASRock        | A320M-HDV R3.0              | [a9cd7361e6](https://linux-hardware.org/?probe=a9cd7361e6) | Jun 23, 2023 |
| ASRock        | Z87M Pro4                   | [762b33c8e7](https://linux-hardware.org/?probe=762b33c8e7) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [184b19f00c](https://linux-hardware.org/?probe=184b19f00c) | Jun 23, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | H81M-S2H                    | [36f8057a1d](https://linux-hardware.org/?probe=36f8057a1d) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| AZW           | GTi                         | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| Dell          | 0YXT71 A01                  | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [160f6f4afb](https://linux-hardware.org/?probe=160f6f4afb) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [3d5cabad57](https://linux-hardware.org/?probe=3d5cabad57) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| ASUSTek       | A88XM-E                     | [1302a62eeb](https://linux-hardware.org/?probe=1302a62eeb) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Unknown       | Unknown                     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| Gigabyte      | H81M-S2H                    | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| Dell          | 0NNNCT A01                  | [1a1e7426a3](https://linux-hardware.org/?probe=1a1e7426a3) | Jun 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| ASRock        | H510M-HDV                   | [27ca3c6650](https://linux-hardware.org/?probe=27ca3c6650) | May 27, 2023 |
| ASUSTek       | Z170M-PLUS                  | [0577b02521](https://linux-hardware.org/?probe=0577b02521) | May 27, 2023 |
| ASRock        | H510M-HDV                   | [c6315a675c](https://linux-hardware.org/?probe=c6315a675c) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 8437                        | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | 970A-DS3P                   | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| SYWZ          | S200 Series                 | [6878838d6f](https://linux-hardware.org/?probe=6878838d6f) | May 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| Samsung       | DeskTop System              | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| ASRock        | X470 Taichi                 | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| HP            | 3398                        | [a49cbc797b](https://linux-hardware.org/?probe=a49cbc797b) | May 18, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| MSI           | A68HM-E33 V2                | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| ASUSTek       | Z170M-PLUS                  | [2d1acb409a](https://linux-hardware.org/?probe=2d1acb409a) | May 13, 2023 |
| ASUSTek       | M5A78L/USB3                 | [edc8069ae1](https://linux-hardware.org/?probe=edc8069ae1) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ec1f5e50b8](https://linux-hardware.org/?probe=ec1f5e50b8) | May 11, 2023 |
| Biostar       | H110MHV3                    | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| ASUSTek       | P8B75-M LE                  | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| ASUSTek       | Z170-K                      | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| MSI           | MS-7502 Fab D               | [ca5881d77e](https://linux-hardware.org/?probe=ca5881d77e) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| MSI           | B350 PC MATE                | [cabb24b0e7](https://linux-hardware.org/?probe=cabb24b0e7) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| ASUSTek       | M5A99X EVO                  | [f5499886e9](https://linux-hardware.org/?probe=f5499886e9) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [369bf3dc68](https://linux-hardware.org/?probe=369bf3dc68) | May 07, 2023 |
| Acer          | Predator PO3-620            | [9ef46f7f3e](https://linux-hardware.org/?probe=9ef46f7f3e) | May 06, 2023 |
| MSI           | MS-7502 Fab D               | [9b80139aca](https://linux-hardware.org/?probe=9b80139aca) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [64aa7fb49b](https://linux-hardware.org/?probe=64aa7fb49b) | May 05, 2023 |
| HP            | 304Ah                       | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| HP            | 21EF                        | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |
| HP            | 1589                        | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [e8c596445b](https://linux-hardware.org/?probe=e8c596445b) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [372a18076a](https://linux-hardware.org/?probe=372a18076a) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| Gigabyte      | H310M H x.x                 | [7996838ce9](https://linux-hardware.org/?probe=7996838ce9) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Apple         | Mac-F221BEC8                | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| ASRock        | B450M Pro4                  | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Acer          | Aspire M3970                | [87a55abfa7](https://linux-hardware.org/?probe=87a55abfa7) | May 01, 2023 |
| ASUSTek       | H81-PLUS                    | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| HP            | 1998                        | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| Gigabyte      | H410M H V2                  | [8a23a0fef0](https://linux-hardware.org/?probe=8a23a0fef0) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [c8fe6ab042](https://linux-hardware.org/?probe=c8fe6ab042) | Apr 28, 2023 |
| ASRock        | B450 Steel Legend           | [9130280424](https://linux-hardware.org/?probe=9130280424) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| HP            | 1589                        | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Apple         | Mac-F221BEC8                | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| Intel         | DQ67OW AAG12528-307         | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| HP            | 18E9                        | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | H61M-S2-B3                  | [cd95f8ec71](https://linux-hardware.org/?probe=cd95f8ec71) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Intel         | HM570                       | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | [70d478e2eb](https://linux-hardware.org/?probe=70d478e2eb) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | [2931b721a3](https://linux-hardware.org/?probe=2931b721a3) | Apr 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| MSI           | A88XM-E35                   | [c26812e2e1](https://linux-hardware.org/?probe=c26812e2e1) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| ASUSTek       | H81M-K                      | [5aa26aea52](https://linux-hardware.org/?probe=5aa26aea52) | Apr 22, 2023 |
| HP            | 18E5                        | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| HP            | ProLiant MicroServer        | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Acer          | Aspire M3970                | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| Unknown       | Unknown                     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [ff7225c921](https://linux-hardware.org/?probe=ff7225c921) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | [a70cdf4848](https://linux-hardware.org/?probe=a70cdf4848) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c5ceac2597](https://linux-hardware.org/?probe=c5ceac2597) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| AZW           | Speed S                     | [7cf5e54f5b](https://linux-hardware.org/?probe=7cf5e54f5b) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | [44222bc590](https://linux-hardware.org/?probe=44222bc590) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | [592c412bd9](https://linux-hardware.org/?probe=592c412bd9) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [00ee6cd73f](https://linux-hardware.org/?probe=00ee6cd73f) | Apr 15, 2023 |
| Acer          | Aspire M3970                | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| Dell          | 00V62H A00                  | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Shuttle       | FH67                        | [daa2f39981](https://linux-hardware.org/?probe=daa2f39981) | Apr 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| HP            | 805F                        | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Dell          | 0PU052                      | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| ASUSTek       | A88XM-A                     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| Acer          | Aspire XC-895 V:1.0         | [ef0fbbe0aa](https://linux-hardware.org/?probe=ef0fbbe0aa) | Apr 08, 2023 |
| Dell          | 0KRC95 A01                  | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Dell          | 0P01GV A03                  | [5dc44169d0](https://linux-hardware.org/?probe=5dc44169d0) | Apr 07, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [a0584206ea](https://linux-hardware.org/?probe=a0584206ea) | Apr 06, 2023 |
| Dell          | 0HN7XN A01                  | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| HP            | 0A9Ch                       | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [b5740f3323](https://linux-hardware.org/?probe=b5740f3323) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b7068fce05](https://linux-hardware.org/?probe=b7068fce05) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS M                | [ed948ed552](https://linux-hardware.org/?probe=ed948ed552) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Pegatron      | JESSE                       | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fb4f4da720](https://linux-hardware.org/?probe=fb4f4da720) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [77b1f3bc3e](https://linux-hardware.org/?probe=77b1f3bc3e) | Apr 02, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| AZW           | U59                         | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [16e982e5cb](https://linux-hardware.org/?probe=16e982e5cb) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Acer          | Predator PO3-610            | [c5fd8fda48](https://linux-hardware.org/?probe=c5fd8fda48) | Apr 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| Acer          | H57M01                      | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [1146b0ebfc](https://linux-hardware.org/?probe=1146b0ebfc) | Apr 01, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [49917003da](https://linux-hardware.org/?probe=49917003da) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [3bf5fd0cfd](https://linux-hardware.org/?probe=3bf5fd0cfd) | Mar 30, 2023 |
| IP3 Tech      | IB8                         | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| ASRock        | X399 Taichi                 | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a37020a71d](https://linux-hardware.org/?probe=a37020a71d) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| HP            | 1998                        | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| Gigabyte      | GA-970A-DS3                 | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [d32441b2c3](https://linux-hardware.org/?probe=d32441b2c3) | Mar 21, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| HP            | 3397                        | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [06d89bd973](https://linux-hardware.org/?probe=06d89bd973) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Unknown       | Unknown                     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASUSTek       | P5W DH Deluxe               | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Google        | Teemo                       | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| Dell          | 02M8NY A02                  | [b3c31072bb](https://linux-hardware.org/?probe=b3c31072bb) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | PRIME X470-PRO              | [686fb235ce](https://linux-hardware.org/?probe=686fb235ce) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Dell          | 0DFRFW A01                  | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Gigabyte      | H170M-D3H-CF                | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | A520M H                     | [d841d9761a](https://linux-hardware.org/?probe=d841d9761a) | Mar 11, 2023 |
| Dell          | 08NPPY A00                  | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [382901fcd7](https://linux-hardware.org/?probe=382901fcd7) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [2f86f93df5](https://linux-hardware.org/?probe=2f86f93df5) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Gigabyte      | A520M H                     | [9bcfd20d80](https://linux-hardware.org/?probe=9bcfd20d80) | Mar 10, 2023 |
| Foxconn       | ETON                        | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [519310d05f](https://linux-hardware.org/?probe=519310d05f) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Foxconn       | ETON                        | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | [30b6242c17](https://linux-hardware.org/?probe=30b6242c17) | Mar 07, 2023 |
| Gigabyte      | A520M DS3H                  | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| Gigabyte      | Z690 GAMING X               | [b8dc3dd82b](https://linux-hardware.org/?probe=b8dc3dd82b) | Mar 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c5809ffd96](https://linux-hardware.org/?probe=c5809ffd96) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| Gigabyte      | 970A-DS3P                   | [8812bcfc2b](https://linux-hardware.org/?probe=8812bcfc2b) | Mar 06, 2023 |
| ASUSTek       | Z97-DELUXE/USB              | [46d851b146](https://linux-hardware.org/?probe=46d851b146) | Mar 06, 2023 |
| MSI           | Z77A-G43                    | [6a0179b36e](https://linux-hardware.org/?probe=6a0179b36e) | Mar 05, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [53d547f79c](https://linux-hardware.org/?probe=53d547f79c) | Mar 05, 2023 |
| Dell          | 0P01GV A03                  | [b53bbf2061](https://linux-hardware.org/?probe=b53bbf2061) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | [621391a7e0](https://linux-hardware.org/?probe=621391a7e0) | Mar 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [48f407dbf7](https://linux-hardware.org/?probe=48f407dbf7) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [3edae4d4f7](https://linux-hardware.org/?probe=3edae4d4f7) | Mar 03, 2023 |
| Dell          | 018D1Y A00                  | [5af7b05e04](https://linux-hardware.org/?probe=5af7b05e04) | Mar 02, 2023 |
| HP            | 1998                        | [269c6134f1](https://linux-hardware.org/?probe=269c6134f1) | Mar 01, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [784ef5ef12](https://linux-hardware.org/?probe=784ef5ef12) | Mar 01, 2023 |
| ASRock        | X370 Pro4                   | [cd39348090](https://linux-hardware.org/?probe=cd39348090) | Mar 01, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [48e150f274](https://linux-hardware.org/?probe=48e150f274) | Feb 28, 2023 |
| AZW           | Speed S                     | [e44ff0faf0](https://linux-hardware.org/?probe=e44ff0faf0) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| ASRock        | Z97 Pro3                    | [506d56faff](https://linux-hardware.org/?probe=506d56faff) | Feb 28, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASRock        | Z97 Pro3                    | [626e67df35](https://linux-hardware.org/?probe=626e67df35) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Gigabyte      | B650 GAMING X AX            | [c2b3e01a45](https://linux-hardware.org/?probe=c2b3e01a45) | Feb 27, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f15e5303f6](https://linux-hardware.org/?probe=f15e5303f6) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| Gigabyte      | M68M-S2P                    | [15b2fe94ae](https://linux-hardware.org/?probe=15b2fe94ae) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [d78e737aaf](https://linux-hardware.org/?probe=d78e737aaf) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| Dell          | 0GXM1W A00                  | [e7edf0f7c3](https://linux-hardware.org/?probe=e7edf0f7c3) | Feb 23, 2023 |
| HP            | 1497                        | [478a5730f6](https://linux-hardware.org/?probe=478a5730f6) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | [8f307a87e5](https://linux-hardware.org/?probe=8f307a87e5) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | [781c058256](https://linux-hardware.org/?probe=781c058256) | Feb 23, 2023 |
| Gigabyte      | H81M-S2H                    | [c3d9b18f7c](https://linux-hardware.org/?probe=c3d9b18f7c) | Feb 23, 2023 |
| Biostar       | B450MH                      | [7bd9274f23](https://linux-hardware.org/?probe=7bd9274f23) | Feb 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | [b184665592](https://linux-hardware.org/?probe=b184665592) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [375a3684e2](https://linux-hardware.org/?probe=375a3684e2) | Feb 19, 2023 |
| MSI           | Z390-A PRO                  | [0bcbc517ca](https://linux-hardware.org/?probe=0bcbc517ca) | Feb 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [e7e9625ffc](https://linux-hardware.org/?probe=e7e9625ffc) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [d0bb58e003](https://linux-hardware.org/?probe=d0bb58e003) | Feb 18, 2023 |
| AAEON         | PICO-APL3 V1.0              | [4ef4f86a2e](https://linux-hardware.org/?probe=4ef4f86a2e) | Feb 17, 2023 |
| Acer          | Batman A01                  | [d7aaa8f1c8](https://linux-hardware.org/?probe=d7aaa8f1c8) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Dell          | 0XPDFK A01                  | [146c38cbdf](https://linux-hardware.org/?probe=146c38cbdf) | Feb 16, 2023 |
| ASRock        | P67 Pro3                    | [37eb433eb3](https://linux-hardware.org/?probe=37eb433eb3) | Feb 15, 2023 |
| HP            | 1497                        | [1d55830595](https://linux-hardware.org/?probe=1d55830595) | Feb 15, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5b6ce8f332](https://linux-hardware.org/?probe=5b6ce8f332) | Feb 15, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [02bd82be1d](https://linux-hardware.org/?probe=02bd82be1d) | Feb 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac367ae940](https://linux-hardware.org/?probe=ac367ae940) | Feb 14, 2023 |
| Unknown       | Unknown                     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| ASUSTek       | PRIME B350M-E               | [84a46ec9ce](https://linux-hardware.org/?probe=84a46ec9ce) | Feb 14, 2023 |
| Intel         | D525MW AAE93082-401         | [6ab285c781](https://linux-hardware.org/?probe=6ab285c781) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | [762dd6fa2e](https://linux-hardware.org/?probe=762dd6fa2e) | Feb 13, 2023 |
| ASUSTek       | P8Z68-V LE                  | [dcf82ccac5](https://linux-hardware.org/?probe=dcf82ccac5) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [cd29998b19](https://linux-hardware.org/?probe=cd29998b19) | Feb 13, 2023 |
| Acer          | H57M01                      | [4efe549cf2](https://linux-hardware.org/?probe=4efe549cf2) | Feb 12, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4f04a42167](https://linux-hardware.org/?probe=4f04a42167) | Feb 12, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Dell          | 0J3C2F A00                  | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| HP            | 82A2                        | [fe327d8caa](https://linux-hardware.org/?probe=fe327d8caa) | Feb 11, 2023 |
| MSI           | PRO Z690-P DDR4             | [61d03fad19](https://linux-hardware.org/?probe=61d03fad19) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| Gigabyte      | H310M H x.x                 | [a166b37ae5](https://linux-hardware.org/?probe=a166b37ae5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [9523b275e8](https://linux-hardware.org/?probe=9523b275e8) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| Dell          | 0CRH6C A00                  | [fe0e64b291](https://linux-hardware.org/?probe=fe0e64b291) | Feb 08, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ba0666ad0b](https://linux-hardware.org/?probe=ba0666ad0b) | Feb 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [770e825eba](https://linux-hardware.org/?probe=770e825eba) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [5755b9feb0](https://linux-hardware.org/?probe=5755b9feb0) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [bb6bee6af9](https://linux-hardware.org/?probe=bb6bee6af9) | Feb 05, 2023 |
| MSI           | Z77A-G43                    | [b85e438d00](https://linux-hardware.org/?probe=b85e438d00) | Feb 04, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [a4b17f9deb](https://linux-hardware.org/?probe=a4b17f9deb) | Feb 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [395e2c6424](https://linux-hardware.org/?probe=395e2c6424) | Feb 03, 2023 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [ea223a4d57](https://linux-hardware.org/?probe=ea223a4d57) | Feb 03, 2023 |
| MSI           | Z77A-G43                    | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| HP            | 2ADE                        | [b3735eb6c9](https://linux-hardware.org/?probe=b3735eb6c9) | Feb 02, 2023 |
| MSI           | X399 SLI PLUS               | [33f2d92922](https://linux-hardware.org/?probe=33f2d92922) | Feb 02, 2023 |
| AMI           | Cherry Trail CR             | [162e744903](https://linux-hardware.org/?probe=162e744903) | Feb 01, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3f9519f358](https://linux-hardware.org/?probe=3f9519f358) | Jan 31, 2023 |
| Dell          | 0P01GV A03                  | [b029e941fb](https://linux-hardware.org/?probe=b029e941fb) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7743588036](https://linux-hardware.org/?probe=7743588036) | Jan 30, 2023 |
| ASUSTek       | PRIME X570-P                | [a05f6f2f6c](https://linux-hardware.org/?probe=a05f6f2f6c) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0082cca600](https://linux-hardware.org/?probe=0082cca600) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | [04ed0bd8b1](https://linux-hardware.org/?probe=04ed0bd8b1) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | [873725bb74](https://linux-hardware.org/?probe=873725bb74) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | [f489fe4f5d](https://linux-hardware.org/?probe=f489fe4f5d) | Jan 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5a7b54907f](https://linux-hardware.org/?probe=5a7b54907f) | Jan 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [845b3c6990](https://linux-hardware.org/?probe=845b3c6990) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d7469767f6](https://linux-hardware.org/?probe=d7469767f6) | Jan 28, 2023 |
| ASRock        | A320M-HDV R4.0              | [f447127e74](https://linux-hardware.org/?probe=f447127e74) | Jan 28, 2023 |
| HP            | 2B17                        | [8746c148c7](https://linux-hardware.org/?probe=8746c148c7) | Jan 28, 2023 |
| Dell          | 0CU409                      | [5da09834b4](https://linux-hardware.org/?probe=5da09834b4) | Jan 27, 2023 |
| Dell          | 0CU409                      | [06b8ea0f8e](https://linux-hardware.org/?probe=06b8ea0f8e) | Jan 27, 2023 |
| Dell          | 0XPDFK A01                  | [4611591cc9](https://linux-hardware.org/?probe=4611591cc9) | Jan 27, 2023 |
| HP            | 212A                        | [5b9c217d02](https://linux-hardware.org/?probe=5b9c217d02) | Jan 27, 2023 |
| HP            | 1497                        | [21a3e07346](https://linux-hardware.org/?probe=21a3e07346) | Jan 26, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7fb86baa0e](https://linux-hardware.org/?probe=7fb86baa0e) | Jan 26, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [fb83192f84](https://linux-hardware.org/?probe=fb83192f84) | Jan 26, 2023 |
| Gigabyte      | H310M H x.x                 | [64ccdd32f5](https://linux-hardware.org/?probe=64ccdd32f5) | Jan 25, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [68c58308b8](https://linux-hardware.org/?probe=68c58308b8) | Jan 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| ASUSTek       | PRIME X570-P                | [c8c9f53754](https://linux-hardware.org/?probe=c8c9f53754) | Jan 24, 2023 |
| ASUSTek       | Z87-WS                      | [da3028df45](https://linux-hardware.org/?probe=da3028df45) | Jan 23, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| Dell          | 0TP406                      | [e169f52d32](https://linux-hardware.org/?probe=e169f52d32) | Jan 23, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [4a6f5a78f9](https://linux-hardware.org/?probe=4a6f5a78f9) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| Gigabyte      | H310M H x.x                 | [ac375e0fa7](https://linux-hardware.org/?probe=ac375e0fa7) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| HP            | 1905                        | [aaa3a9557c](https://linux-hardware.org/?probe=aaa3a9557c) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [6419184e6e](https://linux-hardware.org/?probe=6419184e6e) | Jan 21, 2023 |
| ASUSTek       | M4N78-AM                    | [cf65d9f981](https://linux-hardware.org/?probe=cf65d9f981) | Jan 21, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [db131543b4](https://linux-hardware.org/?probe=db131543b4) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| Dell          | 03NVJ6 A03                  | [4269f0e624](https://linux-hardware.org/?probe=4269f0e624) | Jan 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [9301fd6936](https://linux-hardware.org/?probe=9301fd6936) | Jan 19, 2023 |
| HP            | 2AF3                        | [ac7c491076](https://linux-hardware.org/?probe=ac7c491076) | Jan 19, 2023 |
| HP            | 3396                        | [456080afe8](https://linux-hardware.org/?probe=456080afe8) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4545e31cd2](https://linux-hardware.org/?probe=4545e31cd2) | Jan 18, 2023 |
| ASUSTek       | PRIME H510M-A               | [0ccab4b1e3](https://linux-hardware.org/?probe=0ccab4b1e3) | Jan 18, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [1c05ac2e28](https://linux-hardware.org/?probe=1c05ac2e28) | Jan 17, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [83b98e5580](https://linux-hardware.org/?probe=83b98e5580) | Jan 17, 2023 |
| Dell          | 0KRC95 A01                  | [4d39406938](https://linux-hardware.org/?probe=4d39406938) | Jan 16, 2023 |
| Gigabyte      | H310M H x.x                 | [64b395004f](https://linux-hardware.org/?probe=64b395004f) | Jan 16, 2023 |
| Biostar       | H310MHP                     | [6495c0927b](https://linux-hardware.org/?probe=6495c0927b) | Jan 16, 2023 |
| Gigabyte      | EP45-DS4                    | [ef63262326](https://linux-hardware.org/?probe=ef63262326) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| Gigabyte      | EP45-DS4                    | [9feae23438](https://linux-hardware.org/?probe=9feae23438) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Gigabyte      | H310M H x.x                 | [0b80c9ddfb](https://linux-hardware.org/?probe=0b80c9ddfb) | Jan 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [85048ce95d](https://linux-hardware.org/?probe=85048ce95d) | Jan 15, 2023 |
| Unknown       | Unknown                     | [0579b343cb](https://linux-hardware.org/?probe=0579b343cb) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| ASUSTek       | P8H77-M PRO                 | [6b0992e510](https://linux-hardware.org/?probe=6b0992e510) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| HP            | 805A                        | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| Dell          | 0P01GV A03                  | [0d1982257b](https://linux-hardware.org/?probe=0d1982257b) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | [4e45aef7b0](https://linux-hardware.org/?probe=4e45aef7b0) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| Gigabyte      | B650E AORUS MASTER          | [7a9514375b](https://linux-hardware.org/?probe=7a9514375b) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | [bb92fab8d3](https://linux-hardware.org/?probe=bb92fab8d3) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| AZW           | Green G3                    | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
| ASRock        | B450M Steel Legend          | [8309c81fdf](https://linux-hardware.org/?probe=8309c81fdf) | Jan 12, 2023 |
| ASRock        | X670E Steel Legend          | [508efb9c99](https://linux-hardware.org/?probe=508efb9c99) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| Dell          | 0Y5DDC A00                  | [76d5a2b12b](https://linux-hardware.org/?probe=76d5a2b12b) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [2dadad3f74](https://linux-hardware.org/?probe=2dadad3f74) | Jan 12, 2023 |
| Gigabyte      | B450 AORUS M                | [a1f2661396](https://linux-hardware.org/?probe=a1f2661396) | Jan 11, 2023 |
| Dell          | 0HN7XN A01                  | [f0ba373485](https://linux-hardware.org/?probe=f0ba373485) | Jan 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [f91cb1b0e7](https://linux-hardware.org/?probe=f91cb1b0e7) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [74cafb7a17](https://linux-hardware.org/?probe=74cafb7a17) | Jan 10, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d1c53542d8](https://linux-hardware.org/?probe=d1c53542d8) | Jan 10, 2023 |
| Gigabyte      | H61N-USB3                   | [fd5a06c33f](https://linux-hardware.org/?probe=fd5a06c33f) | Jan 09, 2023 |
| Dell          | 0D883F A06                  | [cae316a9ad](https://linux-hardware.org/?probe=cae316a9ad) | Jan 09, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [c434b0e62f](https://linux-hardware.org/?probe=c434b0e62f) | Jan 09, 2023 |
| ASUSTek       | PRIME B360M-A               | [d903601066](https://linux-hardware.org/?probe=d903601066) | Jan 09, 2023 |
| HP            | 0AA4h                       | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [22df883df4](https://linux-hardware.org/?probe=22df883df4) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [0e705ced6f](https://linux-hardware.org/?probe=0e705ced6f) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [46ae333889](https://linux-hardware.org/?probe=46ae333889) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Dell          | 0P01GV A03                  | [c343ff064d](https://linux-hardware.org/?probe=c343ff064d) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [24b5e0ba8e](https://linux-hardware.org/?probe=24b5e0ba8e) | Jan 07, 2023 |
| ASRock        | AB350 Pro4                  | [f70583b34b](https://linux-hardware.org/?probe=f70583b34b) | Jan 07, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [e7ee03968d](https://linux-hardware.org/?probe=e7ee03968d) | Jan 07, 2023 |
| Dell          | 09M8Y8 A01                  | [f6d81f424d](https://linux-hardware.org/?probe=f6d81f424d) | Jan 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 481      | 13.79%  |
| Ubuntu 18.04                 | 277      | 7.94%   |
| Ubuntu 22.04                 | 204      | 5.85%   |
| Zorin 16                     | 90       | 2.58%   |
| Arch Rolling                 | 90       | 2.58%   |
| Debian 11                    | 73       | 2.09%   |
| OpenMandriva 4.2             | 68       | 1.95%   |
| ArcoLinux Rolling            | 67       | 1.92%   |
| Pop!_OS 22.04                | 59       | 1.69%   |
| KDE neon 20.04               | 56       | 1.61%   |
| OpenMandriva 4.3             | 54       | 1.55%   |
| Manjaro                      | 53       | 1.52%   |
| Linux Mint 20.3              | 53       | 1.52%   |
| Pop!_OS 20.04                | 48       | 1.38%   |
| Linux Mint 20.2              | 46       | 1.32%   |
| Pop!_OS 21.04                | 45       | 1.29%   |
| Linux Mint 21.1              | 43       | 1.23%   |
| Pop!_OS 20.10                | 41       | 1.18%   |
| Zorin 15                     | 37       | 1.06%   |
| Ubuntu 19.04                 | 37       | 1.06%   |
| Linux Mint 19.3              | 37       | 1.06%   |
| Arch                         | 36       | 1.03%   |
| Xubuntu 20.04                | 35       | 1%      |
| OpenMandriva 23.01           | 35       | 1%      |
| Linux Mint 20.1              | 35       | 1%      |
| Ubuntu 19.10                 | 33       | 0.95%   |
| OpenMandriva 23.03           | 33       | 0.95%   |
| Ubuntu 21.10                 | 31       | 0.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 31       | 0.89%   |
| Kubuntu 20.04                | 29       | 0.83%   |
| Linux Mint 20                | 26       | 0.75%   |
| Fedora 36                    | 26       | 0.75%   |
| Fedora 38                    | 25       | 0.72%   |
| Debian 10                    | 25       | 0.72%   |
| Ubuntu 21.04                 | 24       | 0.69%   |
| Ubuntu 20.10                 | 24       | 0.69%   |
| Fedora 37                    | 24       | 0.69%   |
| Linux Mint 21                | 23       | 0.66%   |
| KDE neon 22.04               | 23       | 0.66%   |
| Debian 12                    | 23       | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1125     | 34.25%  |
| Linux Mint    | 301      | 9.16%   |
| OpenMandriva  | 226      | 6.88%   |
| Pop!_OS       | 205      | 6.24%   |
| Fedora        | 163      | 4.96%   |
| Debian        | 145      | 4.41%   |
| Zorin         | 129      | 3.93%   |
| Arch          | 126      | 3.84%   |
| Manjaro       | 91       | 2.77%   |
| Kubuntu       | 85       | 2.59%   |
| KDE neon      | 82       | 2.5%    |
| ArcoLinux     | 67       | 2.04%   |
| Xubuntu       | 60       | 1.83%   |
| Gentoo        | 44       | 1.34%   |
| ROSA          | 42       | 1.28%   |
| openSUSE      | 41       | 1.25%   |
| Clear Linux   | 23       | 0.7%    |
| Ubuntu MATE   | 22       | 0.67%   |
| Nobara        | 21       | 0.64%   |
| Elementary    | 21       | 0.64%   |
| Ubuntu Unity  | 20       | 0.61%   |
| Endless       | 19       | 0.58%   |
| Kali          | 16       | 0.49%   |
| Lubuntu       | 14       | 0.43%   |
| CentOS        | 14       | 0.43%   |
| BlackPanther  | 14       | 0.43%   |
| Slackware     | 10       | 0.3%    |
| MX            | 10       | 0.3%    |
| LMDE          | 10       | 0.3%    |
| Garuda Linux  | 9        | 0.27%   |
| EndeavourOS   | 9        | 0.27%   |
| SteamOS       | 8        | 0.24%   |
| RHEL          | 8        | 0.24%   |
| NixOS         | 7        | 0.21%   |
| Xero          | 5        | 0.15%   |
| Reborn OS     | 5        | 0.15%   |
| Peppermint    | 5        | 0.15%   |
| UbuntuDDE     | 4        | 0.12%   |
| Ubuntu Budgie | 4        | 0.12%   |
| Makulu        | 4        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 68       | 1.7%    |
| 5.4.0-42-generic         | 65       | 1.63%   |
| 5.16.7-desktop-1omv4003  | 51       | 1.28%   |
| 5.4.0-48-generic         | 39       | 0.98%   |
| 6.1.1-desktop-1omv2290   | 33       | 0.83%   |
| 6.2.6-desktop-1omv2390   | 32       | 0.8%    |
| 5.4.0-52-generic         | 32       | 0.8%    |
| 5.4.0-29-generic         | 31       | 0.78%   |
| 5.4.0-26-generic         | 30       | 0.75%   |
| 5.15.0-56-generic        | 29       | 0.73%   |
| 5.3.0-28-generic         | 27       | 0.68%   |
| 5.4.0-37-generic         | 26       | 0.65%   |
| 5.15.0-52-generic        | 24       | 0.6%    |
| 5.15.0-46-generic        | 24       | 0.6%    |
| 5.3.0-40-generic         | 23       | 0.58%   |
| 5.4.0-66-generic         | 22       | 0.55%   |
| 5.4.0-65-generic         | 22       | 0.55%   |
| 5.15.0-58-generic        | 22       | 0.55%   |
| 5.4.0-47-generic         | 21       | 0.53%   |
| 5.4.0-40-generic         | 21       | 0.53%   |
| 5.4.0-74-generic         | 20       | 0.5%    |
| 5.4.0-33-generic         | 20       | 0.5%    |
| 5.13.0-39-generic        | 20       | 0.5%    |
| 5.8.0-7630-generic       | 19       | 0.48%   |
| 5.13.0-7614-generic      | 19       | 0.48%   |
| 5.11.0-7620-generic      | 19       | 0.48%   |
| 5.4.0-58-generic         | 18       | 0.45%   |
| 5.4.0-54-generic         | 18       | 0.45%   |
| 5.3.0-46-generic         | 18       | 0.45%   |
| 5.11.0-40-generic        | 18       | 0.45%   |
| 5.4.0-72-generic         | 17       | 0.43%   |
| 5.15.0-48-generic        | 17       | 0.43%   |
| 5.11.0-25-generic        | 17       | 0.43%   |
| 5.4.0-91-generic         | 16       | 0.4%    |
| 5.4.0-7634-generic       | 16       | 0.4%    |
| 5.15.0-69-generic        | 16       | 0.4%    |
| 5.15.0-53-generic        | 16       | 0.4%    |
| 6.2.6-76060206-generic   | 15       | 0.38%   |
| 5.19.0-46-generic        | 15       | 0.38%   |
| 5.19.0-35-generic        | 15       | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 665      | 18.09%  |
| 5.15.0  | 311      | 8.46%   |
| 4.15.0  | 191      | 5.2%    |
| 5.11.0  | 170      | 4.62%   |
| 5.8.0   | 161      | 4.38%   |
| 5.13.0  | 157      | 4.27%   |
| 5.3.0   | 145      | 3.94%   |
| 5.19.0  | 103      | 2.8%    |
| 5.0.0   | 90       | 2.45%   |
| 5.10.0  | 82       | 2.23%   |
| 6.2.0   | 77       | 2.09%   |
| 4.18.0  | 74       | 2.01%   |
| 5.10.14 | 68       | 1.85%   |
| 5.16.7  | 51       | 1.39%   |
| 6.2.6   | 49       | 1.33%   |
| 6.1.1   | 37       | 1.01%   |
| 6.1.0   | 32       | 0.87%   |
| 4.19.0  | 26       | 0.71%   |
| 5.17.5  | 16       | 0.44%   |
| 5.14.0  | 16       | 0.44%   |
| 6.4.11  | 15       | 0.41%   |
| 4.9.60  | 14       | 0.38%   |
| 6.5.5   | 13       | 0.35%   |
| 5.9.16  | 12       | 0.33%   |
| 5.18.0  | 12       | 0.33%   |
| 6.0.0   | 11       | 0.3%    |
| 4.4.0   | 11       | 0.3%    |
| 6.0.12  | 10       | 0.27%   |
| 5.18.12 | 10       | 0.27%   |
| 5.16.13 | 10       | 0.27%   |
| 4.18.16 | 10       | 0.27%   |
| 6.5.0   | 9        | 0.24%   |
| 5.19.5  | 9        | 0.24%   |
| 4.9.20  | 9        | 0.24%   |
| 6.3.9   | 8        | 0.22%   |
| 6.2.12  | 8        | 0.22%   |
| 6.0.8   | 8        | 0.22%   |
| 5.8.6   | 8        | 0.22%   |
| 5.6.14  | 8        | 0.22%   |
| 5.16.11 | 8        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 708      | 19.65%  |
| 5.15    | 388      | 10.77%  |
| 5.10    | 215      | 5.97%   |
| 5.11    | 204      | 5.66%   |
| 5.8     | 200      | 5.55%   |
| 4.15    | 192      | 5.33%   |
| 5.13    | 191      | 5.3%    |
| 5.3     | 169      | 4.69%   |
| 6.2     | 164      | 4.55%   |
| 5.19    | 144      | 4%      |
| 6.1     | 123      | 3.41%   |
| 5.0     | 93       | 2.58%   |
| 5.16    | 86       | 2.39%   |
| 4.18    | 85       | 2.36%   |
| 6.0     | 57       | 1.58%   |
| 6.4     | 54       | 1.5%    |
| 6.5     | 48       | 1.33%   |
| 5.18    | 48       | 1.33%   |
| 5.14    | 45       | 1.25%   |
| 6.3     | 43       | 1.19%   |
| 5.17    | 43       | 1.19%   |
| 5.9     | 42       | 1.17%   |
| 4.9     | 38       | 1.05%   |
| 5.12    | 37       | 1.03%   |
| 4.19    | 37       | 1.03%   |
| 5.6     | 36       | 1%      |
| 5.7     | 32       | 0.89%   |
| 5.5     | 19       | 0.53%   |
| 4.4     | 13       | 0.36%   |
| 5.2     | 12       | 0.33%   |
| 5.1     | 7        | 0.19%   |
| 4.1     | 7        | 0.19%   |
| 3.10    | 6        | 0.17%   |
| 4.14    | 4        | 0.11%   |
| 4.13    | 4        | 0.11%   |
| 6.6     | 2        | 0.06%   |
| 4.20    | 2        | 0.06%   |
| 3.13    | 2        | 0.06%   |
| 4.12    | 1        | 0.03%   |
| 4.10    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3067     | 97.89%  |
| i686    | 62       | 1.98%   |
| armv7l  | 2        | 0.06%   |
| riscv64 | 1        | 0.03%   |
| aarch64 | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 1449     | 43.84%  |
| KDE5             | 584      | 17.67%  |
| Unknown          | 438      | 13.25%  |
| X-Cinnamon       | 250      | 7.56%   |
| XFCE             | 212      | 6.41%   |
| KDE              | 85       | 2.57%   |
| MATE             | 75       | 2.27%   |
| Cinnamon         | 40       | 1.21%   |
| KDE4             | 22       | 0.67%   |
| Unity            | 21       | 0.64%   |
| Pantheon         | 20       | 0.61%   |
| LXQt             | 17       | 0.51%   |
| LXDE             | 16       | 0.48%   |
| i3               | 11       | 0.33%   |
| GNOME Flashback  | 10       | 0.3%    |
| Deepin           | 9        | 0.27%   |
| sway             | 6        | 0.18%   |
| Budgie           | 6        | 0.18%   |
| openbox          | 4        | 0.12%   |
| lightdm-xsession | 4        | 0.12%   |
| Hyprland         | 4        | 0.12%   |
| GNOME Classic    | 3        | 0.09%   |
| xmonad           | 2        | 0.06%   |
| qtile            | 2        | 0.06%   |
| icewm            | 2        | 0.06%   |
| chadwm           | 2        | 0.06%   |
| bspwm            | 2        | 0.06%   |
| awesome          | 2        | 0.06%   |
| xubuntu          | 1        | 0.03%   |
| WindowMaker      | 1        | 0.03%   |
| mwm              | 1        | 0.03%   |
| LeftWM           | 1        | 0.03%   |
| enlightenment    | 1        | 0.03%   |
| DWM              | 1        | 0.03%   |
| Cutefish         | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2518     | 77.81%  |
| Wayland | 412      | 12.73%  |
| Unknown | 194      | 6%      |
| Tty     | 111      | 3.43%   |
| Web     | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1819     | 55.32%  |
| SDDM    | 499      | 15.18%  |
| GDM3    | 335      | 10.19%  |
| GDM     | 260      | 7.91%   |
| LightDM | 254      | 7.73%   |
| TDM     | 80       | 2.43%   |
| KDM     | 20       | 0.61%   |
| XDM     | 8        | 0.24%   |
| SLiM    | 4        | 0.12%   |
| LXDM    | 4        | 0.12%   |
| Ly      | 2        | 0.06%   |
| XINIT   | 1        | 0.03%   |
| MDM     | 1        | 0.03%   |
| GREETD  | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_GB          | 2360     | 73.2%   |
| en_US          | 373      | 11.57%  |
| Unknown        | 364      | 11.29%  |
| C              | 50       | 1.55%   |
| pl_PL          | 19       | 0.59%   |
| ru_RU          | 7        | 0.22%   |
| POSIX          | 7        | 0.22%   |
| en_IE          | 6        | 0.19%   |
| C.UTF8         | 4        | 0.12%   |
| ro_RO          | 3        | 0.09%   |
| en_CA          | 3        | 0.09%   |
| de_DE          | 3        | 0.09%   |
| nl_NL          | 2        | 0.06%   |
| lt_LT          | 2        | 0.06%   |
| hu_HU          | 2        | 0.06%   |
| en_ZA          | 2        | 0.06%   |
| zh_CN          | 1        | 0.03%   |
| wbp_AU         | 1        | 0.03%   |
| us             | 1        | 0.03%   |
| uk_UA          | 1        | 0.03%   |
| sk_SK          | 1        | 0.03%   |
| pt_PT          | 1        | 0.03%   |
| pt_BR          | 1        | 0.03%   |
| it_IT          | 1        | 0.03%   |
| fr_FR          | 1        | 0.03%   |
| fi_FI          | 1        | 0.03%   |
| et_EE          | 1        | 0.03%   |
| en_US.utf-8    | 1        | 0.03%   |
| en_SG          | 1        | 0.03%   |
| en_IN          | 1        | 0.03%   |
| en_GB.iso88591 | 1        | 0.03%   |
| cs_CZ          | 1        | 0.03%   |
| bg_BG          | 1        | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1881     | 58.53%  |
| EFI  | 1333     | 41.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 2433     | 74.95%  |
| Btrfs    | 284      | 8.75%   |
| Overlay  | 232      | 7.15%   |
| Unknown  | 110      | 3.39%   |
| Tmpfs    | 76       | 2.34%   |
| Xfs      | 53       | 1.63%   |
| Zfs      | 29       | 0.89%   |
| Ext2     | 12       | 0.37%   |
| Ext3     | 8        | 0.25%   |
| F2fs     | 5        | 0.15%   |
| XXXX     | 1        | 0.03%   |
| Reiserfs | 1        | 0.03%   |
| ExX4     | 1        | 0.03%   |
| Aufs     | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1836     | 56.95%  |
| GPT     | 1088     | 33.75%  |
| MBR     | 300      | 9.31%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2555     | 79.08%  |
| Yes       | 676      | 20.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2194     | 68.39%  |
| Yes       | 1014     | 31.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 829      | 26.48%  |
| Gigabyte Technology                  | 560      | 17.89%  |
| MSI                                  | 377      | 12.04%  |
| Dell                                 | 360      | 11.5%   |
| ASRock                               | 229      | 7.31%   |
| Hewlett-Packard                      | 218      | 6.96%   |
| Lenovo                               | 105      | 3.35%   |
| Intel                                | 74       | 2.36%   |
| Acer                                 | 66       | 2.11%   |
| Foxconn                              | 35       | 1.12%   |
| Fujitsu                              | 28       | 0.89%   |
| Unknown                              | 28       | 0.89%   |
| Pegatron                             | 24       | 0.77%   |
| Apple                                | 22       | 0.7%    |
| Biostar                              | 19       | 0.61%   |
| Packard Bell                         | 16       | 0.51%   |
| AZW                                  | 14       | 0.45%   |
| Medion                               | 13       | 0.42%   |
| Alienware                            | 9        | 0.29%   |
| Shuttle                              | 8        | 0.26%   |
| Fujitsu Siemens                      | 8        | 0.26%   |
| ECS                                  | 7        | 0.22%   |
| Supermicro                           | 6        | 0.19%   |
| Inventec                             | 6        | 0.19%   |
| AMI                                  | 5        | 0.16%   |
| TYAN Computer                        | 4        | 0.13%   |
| Shenzhen Meigao Electronic Equipment | 4        | 0.13%   |
| OEM_MB                               | 3        | 0.1%    |
| Huanan                               | 3        | 0.1%    |
| Wistron                              | 2        | 0.06%   |
| SYWZ                                 | 2        | 0.06%   |
| Seeed Studio                         | 2        | 0.06%   |
| MiTAC                                | 2        | 0.06%   |
| Google                               | 2        | 0.06%   |
| EVGA                                 | 2        | 0.06%   |
| Entroware                            | 2        | 0.06%   |
| BESSTAR Tech                         | 2        | 0.06%   |
| ASRockRack                           | 2        | 0.06%   |
| Advent                               | 2        | 0.06%   |
| ABIT                                 | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 79       | 2.52%   |
| Dell OptiPlex 7010               | 35       | 1.12%   |
| MSI MS-7C02                      | 29       | 0.93%   |
| Unknown                          | 29       | 0.93%   |
| ASUS M5A78L-M/USB3               | 23       | 0.73%   |
| MSI MS-7C37                      | 22       | 0.7%    |
| Dell OptiPlex 755                | 21       | 0.67%   |
| ASUS TUF Gaming X570-PLUS        | 21       | 0.67%   |
| Dell OptiPlex 780                | 20       | 0.64%   |
| ASUS ROG STRIX B450-F GAMING     | 20       | 0.64%   |
| Dell OptiPlex 790                | 17       | 0.54%   |
| Gigabyte X570 AORUS ELITE        | 15       | 0.48%   |
| Gigabyte 970A-DS3P               | 15       | 0.48%   |
| ASUS ROG STRIX B550-F GAMING     | 15       | 0.48%   |
| ASUS PRIME A320M-K               | 15       | 0.48%   |
| MSI MS-7C91                      | 14       | 0.45%   |
| Dell OptiPlex 3020               | 13       | 0.42%   |
| MSI MS-7B79                      | 12       | 0.38%   |
| Gigabyte GA-78LMT-USB3           | 12       | 0.38%   |
| Gigabyte B450M DS3H              | 12       | 0.38%   |
| ASUS PRIME B450-PLUS             | 12       | 0.38%   |
| HP ProLiant MicroServer          | 11       | 0.35%   |
| HP EliteDesk 800 G1 SFF          | 11       | 0.35%   |
| Gigabyte A320M-S2H               | 11       | 0.35%   |
| ASUS ROG CROSSHAIR VIII HERO     | 11       | 0.35%   |
| MSI MS-7B85                      | 10       | 0.32%   |
| MSI MS-7A34                      | 10       | 0.32%   |
| MSI MS-7721                      | 10       | 0.32%   |
| Gigabyte GA-78LMT-USB3 6.0       | 10       | 0.32%   |
| Dell Vostro 200                  | 10       | 0.32%   |
| MSI MS-7B89                      | 9        | 0.29%   |
| MSI MS-7758                      | 9        | 0.29%   |
| MSI MS-7693                      | 9        | 0.29%   |
| Gigabyte H61M-DS2 DVI            | 9        | 0.29%   |
| Dell Precision WorkStation T3500 | 9        | 0.29%   |
| Dell OptiPlex 9020               | 9        | 0.29%   |
| Dell OptiPlex 3050               | 9        | 0.29%   |
| ASUS PRIME B450M-A               | 9        | 0.29%   |
| MSI MS-7C56                      | 8        | 0.26%   |
| MSI MS-7A38                      | 8        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 207      | 6.61%   |
| ASUS ROG               | 157      | 5.01%   |
| ASUS PRIME             | 140      | 4.47%   |
| ASUS All               | 79       | 2.52%   |
| HP Compaq              | 70       | 2.24%   |
| Lenovo ThinkCentre     | 69       | 2.2%    |
| Dell Precision         | 57       | 1.82%   |
| ASUS TUF               | 52       | 1.66%   |
| Acer Aspire            | 46       | 1.47%   |
| Gigabyte X570          | 40       | 1.28%   |
| Dell Inspiron          | 35       | 1.12%   |
| ASUS M5A78L-M          | 33       | 1.05%   |
| MSI MS-7C02            | 29       | 0.93%   |
| HP EliteDesk           | 29       | 0.93%   |
| Unknown                | 29       | 0.93%   |
| Gigabyte GA-78LMT-USB3 | 27       | 0.86%   |
| Dell Vostro            | 24       | 0.77%   |
| MSI MS-7C37            | 22       | 0.7%    |
| HP ProLiant            | 22       | 0.7%    |
| Gigabyte B450          | 21       | 0.67%   |
| Fujitsu ESPRIMO        | 21       | 0.67%   |
| HP ProDesk             | 19       | 0.61%   |
| ASUS SABERTOOTH        | 19       | 0.61%   |
| Gigabyte Z390          | 17       | 0.54%   |
| Gigabyte B450M         | 17       | 0.54%   |
| Gigabyte 970A-DS3P     | 16       | 0.51%   |
| ASUS Maximus           | 16       | 0.51%   |
| Gigabyte B550          | 15       | 0.48%   |
| Gigabyte A320M-S2H     | 15       | 0.48%   |
| MSI MS-7C91            | 14       | 0.45%   |
| Gigabyte B550M         | 14       | 0.45%   |
| ASUS P8Z77-V           | 13       | 0.42%   |
| Packard Bell IMEDIA    | 12       | 0.38%   |
| MSI MS-7B79            | 12       | 0.38%   |
| ASUS M5A97             | 12       | 0.38%   |
| Dell XPS               | 11       | 0.35%   |
| ASRock X570            | 11       | 0.35%   |
| ASRock B450M           | 11       | 0.35%   |
| MSI MS-7B85            | 10       | 0.32%   |
| MSI MS-7A34            | 10       | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 334      | 10.67%  |
| 2012    | 296      | 9.45%   |
| 2019    | 256      | 8.18%   |
| 2013    | 244      | 7.79%   |
| 2014    | 241      | 7.7%    |
| 2020    | 221      | 7.06%   |
| 2011    | 220      | 7.03%   |
| 2017    | 203      | 6.48%   |
| 2010    | 187      | 5.97%   |
| 2009    | 150      | 4.79%   |
| 2021    | 127      | 4.06%   |
| 2015    | 126      | 4.02%   |
| 2016    | 117      | 3.74%   |
| 2008    | 112      | 3.58%   |
| 2007    | 99       | 3.16%   |
| 2022    | 97       | 3.1%    |
| 2006    | 45       | 1.44%   |
| 2023    | 24       | 0.77%   |
| 2005    | 19       | 0.61%   |
| 2004    | 6        | 0.19%   |
| Unknown | 3        | 0.1%    |
| 2003    | 2        | 0.06%   |
| 2002    | 2        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3131     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3053     | 97.04%  |
| Enabled  | 93       | 2.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3129     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 854      | 26.58%  |
| 32.01-64.0      | 577      | 17.96%  |
| 8.01-16.0       | 563      | 17.52%  |
| 4.01-8.0        | 435      | 13.54%  |
| 3.01-4.0        | 384      | 11.95%  |
| 64.01-256.0     | 170      | 5.29%   |
| 24.01-32.0      | 87       | 2.71%   |
| 1.01-2.0        | 82       | 2.55%   |
| 2.01-3.0        | 38       | 1.18%   |
| 0.51-1.0        | 16       | 0.5%    |
| More than 256.0 | 6        | 0.19%   |
| 0.01-0.5        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1236     | 34.3%   |
| 2.01-3.0    | 853      | 23.67%  |
| 4.01-8.0    | 538      | 14.93%  |
| 3.01-4.0    | 456      | 12.66%  |
| 0.51-1.0    | 210      | 5.83%   |
| 8.01-16.0   | 196      | 5.44%   |
| 0.01-0.5    | 43       | 1.19%   |
| 16.01-24.0  | 37       | 1.03%   |
| 24.01-32.0  | 16       | 0.44%   |
| 32.01-64.0  | 13       | 0.36%   |
| 64.01-256.0 | 3        | 0.08%   |
| Unknown     | 2        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1126     | 34.02%  |
| 2       | 929      | 28.07%  |
| 3       | 523      | 15.8%   |
| 4       | 334      | 10.09%  |
| 5       | 192      | 5.8%    |
| 6       | 96       | 2.9%    |
| 7       | 36       | 1.09%   |
| 0       | 23       | 0.69%   |
| 8       | 17       | 0.51%   |
| 9       | 10       | 0.3%    |
| 11      | 7        | 0.21%   |
| 10      | 6        | 0.18%   |
| 12      | 5        | 0.15%   |
| 29      | 1        | 0.03%   |
| 25      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 20      | 1        | 0.03%   |
| 13      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1618     | 50.72%  |
| Yes       | 1572     | 49.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3087     | 98.56%  |
| No        | 45       | 1.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1647     | 51.53%  |
| Yes       | 1549     | 48.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2113     | 66.22%  |
| Yes       | 1078     | 33.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| UK      | 3131     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| London              | 194      | 5.54%   |
| Manchester          | 96       | 2.74%   |
| Bristol             | 59       | 1.68%   |
| Birmingham          | 54       | 1.54%   |
| Sheffield           | 49       | 1.4%    |
| Nottingham          | 46       | 1.31%   |
| Glasgow             | 41       | 1.17%   |
| Leeds               | 38       | 1.08%   |
| Edinburgh           | 37       | 1.06%   |
| Liverpool           | 33       | 0.94%   |
| Islington           | 31       | 0.88%   |
| Derby               | 30       | 0.86%   |
| Norwich             | 29       | 0.83%   |
| Croydon             | 26       | 0.74%   |
| Cambridge           | 26       | 0.74%   |
| Reading             | 25       | 0.71%   |
| Milton Keynes       | 25       | 0.71%   |
| Cardiff             | 25       | 0.71%   |
| Southampton         | 24       | 0.68%   |
| Newcastle upon Tyne | 22       | 0.63%   |
| Bradford            | 21       | 0.6%    |
| Stockport           | 20       | 0.57%   |
| York                | 18       | 0.51%   |
| Swindon             | 18       | 0.51%   |
| Leicester           | 18       | 0.51%   |
| Hackney             | 18       | 0.51%   |
| Stoke-on-Trent      | 17       | 0.49%   |
| Gloucester          | 17       | 0.49%   |
| Wolverhampton       | 16       | 0.46%   |
| Sunderland          | 16       | 0.46%   |
| Rotherham           | 16       | 0.46%   |
| Wigan               | 15       | 0.43%   |
| Portsmouth          | 15       | 0.43%   |
| Plymouth            | 15       | 0.43%   |
| Gillingham          | 15       | 0.43%   |
| Telford             | 14       | 0.4%    |
| Peterborough        | 14       | 0.4%    |
| Bolton              | 14       | 0.4%    |
| Warrington          | 13       | 0.37%   |
| Coventry            | 13       | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1181     | 2127   | 19.38%  |
| WDC                         | 1058     | 1956   | 17.36%  |
| Samsung Electronics         | 901      | 1660   | 14.79%  |
| Crucial                     | 398      | 593    | 6.53%   |
| SanDisk                     | 369      | 557    | 6.06%   |
| Toshiba                     | 319      | 508    | 5.24%   |
| Kingston                    | 296      | 425    | 4.86%   |
| Hitachi                     | 234      | 345    | 3.84%   |
| Phison                      | 109      | 153    | 1.79%   |
| Intel                       | 87       | 147    | 1.43%   |
| China                       | 78       | 105    | 1.28%   |
| Unknown                     | 62       | 102    | 1.02%   |
| A-DATA Technology           | 62       | 88     | 1.02%   |
| OCZ                         | 57       | 67     | 0.94%   |
| Maxtor                      | 56       | 87     | 0.92%   |
| HGST                        | 51       | 76     | 0.84%   |
| Corsair                     | 42       | 58     | 0.69%   |
| Micron/Crucial Technology   | 39       | 62     | 0.64%   |
| Silicon Motion              | 38       | 51     | 0.62%   |
| Phison Electronics          | 35       | 70     | 0.57%   |
| PNY                         | 34       | 41     | 0.56%   |
| SK hynix                    | 25       | 31     | 0.41%   |
| Transcend                   | 24       | 28     | 0.39%   |
| Patriot                     | 21       | 31     | 0.34%   |
| Micron Technology           | 21       | 22     | 0.34%   |
| Integral                    | 21       | 25     | 0.34%   |
| Gigabyte Technology         | 19       | 28     | 0.31%   |
| SABRENT                     | 17       | 21     | 0.28%   |
| Kingston Technology Company | 17       | 17     | 0.28%   |
| JMicron Technology          | 17       | 26     | 0.28%   |
| LITEON                      | 15       | 19     | 0.25%   |
| ASMT                        | 15       | 22     | 0.25%   |
| Apple                       | 15       | 18     | 0.25%   |
| ADATA Technology            | 15       | 18     | 0.25%   |
| SPCC                        | 13       | 21     | 0.21%   |
| KIOXIA-EXCERIA              | 13       | 19     | 0.21%   |
| Netac                       | 12       | 19     | 0.2%    |
| Drevo                       | 12       | 21     | 0.2%    |
| Lexar                       | 11       | 12     | 0.18%   |
| Hewlett-Packard             | 11       | 17     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST3500312CS 500GB                          | 92       | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                     | 87       | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB                     | 85       | 1.17%   |
| Samsung SSD 850 EVO 250GB                          | 79       | 1.09%   |
| Kingston SA400S37240G 240GB SSD                    | 73       | 1%      |
| Seagate ST500DM002-1BD142 500GB                    | 57       | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 57       | 0.78%   |
| Crucial CT1000MX500SSD1 1TB                        | 56       | 0.77%   |
| Samsung SSD 850 EVO 500GB                          | 54       | 0.74%   |
| Crucial CT500MX500SSD1 500GB                       | 51       | 0.7%    |
| Seagate ST4000DM004-2CV104 4TB                     | 49       | 0.67%   |
| Samsung SSD 860 EVO 1TB                            | 49       | 0.67%   |
| Kingston SA400S37120G 120GB SSD                    | 45       | 0.62%   |
| Samsung SSD 860 EVO 500GB                          | 43       | 0.59%   |
| Samsung NVMe SSD Drive 500GB                       | 41       | 0.56%   |
| Toshiba DT01ACA100 1TB                             | 38       | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB                       | 37       | 0.51%   |
| Seagate ST2000DM006-2DM164 2TB                     | 36       | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                     | 36       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                     | 35       | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 33       | 0.45%   |
| Toshiba HDWD130 3TB                                | 33       | 0.45%   |
| Seagate ST3500418AS 500GB                          | 32       | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                     | 32       | 0.44%   |
| Samsung NVMe SSD Drive 1TB                         | 32       | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB                     | 31       | 0.43%   |
| Samsung HD103SJ 1TB                                | 31       | 0.43%   |
| Crucial CT240BX500SSD1 240GB                       | 31       | 0.43%   |
| Samsung SSD 840 EVO 250GB                          | 30       | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                   | 30       | 0.41%   |
| Toshiba HDWD110 1TB                                | 29       | 0.4%    |
| SanDisk SSD PLUS 480GB                             | 29       | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                         | 29       | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 28       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 26       | 0.36%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 26       | 0.36%   |
| Toshiba DT01ACA200 2TB                             | 26       | 0.36%   |
| Phison Sabrent 256GB                               | 25       | 0.34%   |
| SanDisk SSD PLUS 240GB                             | 24       | 0.33%   |
| Samsung SSD 870 QVO 1TB                            | 24       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1145     | 2037   | 38.66%  |
| WDC                 | 923      | 1699   | 31.16%  |
| Toshiba             | 285      | 449    | 9.62%   |
| Hitachi             | 234      | 345    | 7.9%    |
| Samsung Electronics | 180      | 268    | 6.08%   |
| HGST                | 50       | 75     | 1.69%   |
| Maxtor              | 49       | 79     | 1.65%   |
| Unknown             | 24       | 31     | 0.81%   |
| Hewlett-Packard     | 10       | 16     | 0.34%   |
| Fujitsu             | 10       | 18     | 0.34%   |
| Apple               | 9        | 11     | 0.3%    |
| ASMT                | 6        | 10     | 0.2%    |
| WD MediaMax         | 4        | 4      | 0.14%   |
| HPE                 | 4        | 7      | 0.14%   |
| External            | 3        | 3      | 0.1%    |
| ASMT109x            | 3        | 5      | 0.1%    |
| USB3.0              | 2        | 3      | 0.07%   |
| USB                 | 2        | 2      | 0.07%   |
| SSK                 | 2        | 2      | 0.07%   |
| RSH-339             | 2        | 2      | 0.07%   |
| ExcelStor           | 2        | 4      | 0.07%   |
| TDAS                | 1        | 8      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| KESU                | 1        | 5      | 0.03%   |
| JMicron Technology  | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Advantech           | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 514      | 836    | 23.19%  |
| Crucial             | 355      | 539    | 16.02%  |
| Kingston            | 264      | 378    | 11.91%  |
| SanDisk             | 262      | 355    | 11.82%  |
| WDC                 | 121      | 175    | 5.46%   |
| China               | 76       | 103    | 3.43%   |
| OCZ                 | 57       | 67     | 2.57%   |
| A-DATA Technology   | 50       | 69     | 2.26%   |
| Intel               | 41       | 51     | 1.85%   |
| PNY                 | 33       | 40     | 1.49%   |
| Toshiba             | 28       | 33     | 1.26%   |
| Corsair             | 26       | 35     | 1.17%   |
| Transcend           | 22       | 26     | 0.99%   |
| Integral            | 21       | 25     | 0.95%   |
| Patriot             | 20       | 30     | 0.9%    |
| SABRENT             | 17       | 21     | 0.77%   |
| Seagate             | 15       | 21     | 0.68%   |
| LITEON              | 15       | 19     | 0.68%   |
| Gigabyte Technology | 15       | 22     | 0.68%   |
| Micron Technology   | 14       | 14     | 0.63%   |
| SK hynix            | 13       | 15     | 0.59%   |
| Drevo               | 12       | 21     | 0.54%   |
| SPCC                | 10       | 18     | 0.45%   |
| Netac               | 10       | 15     | 0.45%   |
| KIOXIA-EXCERIA      | 10       | 16     | 0.45%   |
| LITEONIT            | 9        | 11     | 0.41%   |
| Lexar               | 9        | 10     | 0.41%   |
| Vaseky              | 8        | 12     | 0.36%   |
| Team                | 8        | 8      | 0.36%   |
| ASMT                | 8        | 11     | 0.36%   |
| Unknown             | 8        | 9      | 0.36%   |
| ORTIAL              | 7        | 8      | 0.32%   |
| Maxtor              | 7        | 8      | 0.32%   |
| XUM                 | 6        | 6      | 0.27%   |
| Unknown             | 6        | 12     | 0.27%   |
| TO Exter            | 6        | 7      | 0.27%   |
| TCSUNBOW            | 6        | 9      | 0.27%   |
| Apple               | 5        | 6      | 0.23%   |
| Plextor             | 4        | 6      | 0.18%   |
| KingSpec            | 4        | 7      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2180     | 5101   | 44.33%  |
| SSD     | 1738     | 3198   | 35.34%  |
| NVMe    | 899      | 1615   | 18.28%  |
| Unknown | 86       | 123    | 1.75%   |
| MMC     | 15       | 19     | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2862     | 7938   | 70.54%  |
| NVMe | 892      | 1596   | 21.99%  |
| SAS  | 288      | 503    | 7.1%    |
| MMC  | 15       | 19     | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2109     | 4087   | 47.38%  |
| 0.51-1.0        | 1174     | 1997   | 26.38%  |
| 1.01-2.0        | 587      | 1019   | 13.19%  |
| 3.01-4.0        | 214      | 429    | 4.81%   |
| 2.01-3.0        | 192      | 339    | 4.31%   |
| 4.01-10.0       | 146      | 349    | 3.28%   |
| 10.01-20.0      | 27       | 77     | 0.61%   |
| More than 100.0 | 1        | 1      | 0.02%   |
| 0               | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 726      | 21.32%  |
| 251-500        | 536      | 15.74%  |
| 501-1000       | 533      | 15.65%  |
| More than 3000 | 450      | 13.22%  |
| 1001-2000      | 412      | 12.1%   |
| 1-20           | 210      | 6.17%   |
| 2001-3000      | 199      | 5.84%   |
| 51-100         | 154      | 4.52%   |
| Unknown        | 113      | 3.32%   |
| 21-50          | 72       | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1164     | 32.89%  |
| 21-50          | 457      | 12.91%  |
| 101-250        | 398      | 11.25%  |
| 51-100         | 345      | 9.75%   |
| 251-500        | 303      | 8.56%   |
| 501-1000       | 282      | 7.97%   |
| 1001-2000      | 222      | 6.27%   |
| More than 3000 | 172      | 4.86%   |
| Unknown        | 113      | 3.19%   |
| 2001-3000      | 82       | 2.32%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 6        | 6      | 1.52%   |
| Samsung Electronics HD103UJ 1TB          | 6        | 8      | 1.52%   |
| Seagate ST3500418AS 500GB                | 5        | 5      | 1.27%   |
| Seagate ST3500312CS 500GB                | 5        | 7      | 1.27%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 4        | 11     | 1.02%   |
| Seagate ST2000DM001-1CH164 2TB           | 4        | 5      | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 4        | 7      | 1.02%   |
| Samsung Electronics SSD 960 EVO 250GB    | 4        | 5      | 1.02%   |
| Samsung Electronics HD103SJ 1TB          | 4        | 5      | 1.02%   |
| WDC WD6400AAKS-22A7B2 640GB              | 3        | 3      | 0.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3        | 3      | 0.76%   |
| Toshiba DT01ACA050 500GB                 | 3        | 4      | 0.76%   |
| Seagate ST500LM021-1KJ152 500GB          | 3        | 3      | 0.76%   |
| Seagate ST3500620AS 500GB                | 3        | 4      | 0.76%   |
| Seagate ST2000DM006-2DM164 2TB           | 3        | 3      | 0.76%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 3        | 4      | 0.76%   |
| Samsung Electronics SSD 840 Series 120GB | 3        | 3      | 0.76%   |
| Intel SSDPEKKW512G7 512GB                | 3        | 6      | 0.76%   |
| Hitachi HUA723030ALA640 3TB              | 3        | 4      | 0.76%   |
| Hitachi HDT721010SLA360 1TB              | 3        | 3      | 0.76%   |
| Hitachi HDS721010CLA332 1TB              | 3        | 3      | 0.76%   |
| Hitachi HDP725050GLA360 500GB            | 3        | 3      | 0.76%   |
| Crucial CT480M500SSD1 480GB              | 3        | 3      | 0.76%   |
| WDC WD800JD-00HKA0 80GB                  | 2        | 2      | 0.51%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2        | 2      | 0.51%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 2        | 19     | 0.51%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 2        | 4      | 0.51%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2        | 2      | 0.51%   |
| WDC WD40EZRZ-00WN9B0 4TB                 | 2        | 2      | 0.51%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2        | 2      | 0.51%   |
| WDC WD30PURX-64P6ZY0 3TB                 | 2        | 3      | 0.51%   |
| WDC WD30EZRX-00SPEB0 3TB                 | 2        | 2      | 0.51%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 2        | 2      | 0.51%   |
| WDC WD10EZEX-60ZF5A0 1TB                 | 2        | 3      | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 2        | 2      | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 2        | 2      | 0.51%   |
| WDC WD10EARS-00Y5B1 1TB                  | 2        | 3      | 0.51%   |
| WDC WD10EADS-00L5B1 1TB                  | 2        | 2      | 0.51%   |
| WD MediaMax WL5000GSA12872B 5TB          | 2        | 2      | 0.51%   |
| Unknown MM0500EBKAE 500GB                | 2        | 2      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 105      | 158    | 28.38%  |
| Seagate             | 93       | 121    | 25.14%  |
| Samsung Electronics | 43       | 59     | 11.62%  |
| Hitachi             | 35       | 55     | 9.46%   |
| Crucial             | 17       | 23     | 4.59%   |
| Toshiba             | 15       | 20     | 4.05%   |
| Intel               | 10       | 19     | 2.7%    |
| SanDisk             | 8        | 12     | 2.16%   |
| Kingston            | 6        | 9      | 1.62%   |
| A-DATA Technology   | 5        | 6      | 1.35%   |
| Maxtor              | 4        | 5      | 1.08%   |
| Corsair             | 3        | 7      | 0.81%   |
| WD MediaMax         | 2        | 2      | 0.54%   |
| Unknown             | 2        | 2      | 0.54%   |
| Micron Technology   | 2        | 2      | 0.54%   |
| HGST                | 2        | 2      | 0.54%   |
| Hewlett-Packard     | 2        | 2      | 0.54%   |
| Drevo               | 2        | 8      | 0.54%   |
| China               | 2        | 2      | 0.54%   |
| VENO                | 1        | 1      | 0.27%   |
| SK hynix            | 1        | 1      | 0.27%   |
| OCZ                 | 1        | 1      | 0.27%   |
| Mushkin             | 1        | 1      | 0.27%   |
| LITEON              | 1        | 1      | 0.27%   |
| Lexar               | 1        | 1      | 0.27%   |
| KingSpec            | 1        | 1      | 0.27%   |
| faspeed             | 1        | 1      | 0.27%   |
| BIWIN               | 1        | 1      | 0.27%   |
| BAITITON            | 1        | 4      | 0.27%   |
| AGI                 | 1        | 1      | 0.27%   |
| Unknown             | 1        | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 101      | 153    | 36.86%  |
| Seagate             | 93       | 121    | 33.94%  |
| Hitachi             | 35       | 55     | 12.77%  |
| Samsung Electronics | 19       | 27     | 6.93%   |
| Toshiba             | 14       | 19     | 5.11%   |
| Maxtor              | 4        | 5      | 1.46%   |
| WD MediaMax         | 2        | 2      | 0.73%   |
| Unknown             | 2        | 2      | 0.73%   |
| HGST                | 2        | 2      | 0.73%   |
| Hewlett-Packard     | 2        | 2      | 0.73%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 234      | 388    | 71.12%  |
| SSD  | 72       | 108    | 21.88%  |
| NVMe | 23       | 33     | 6.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB      | 1        | 1      | 14.29%  |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 14.29%  |
| Seagate ST3160815AS 160GB             | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1        | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 42.86%  |
| Toshiba             | 2        | 2      | 28.57%  |
| Seagate             | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2069     | 6259   | 58.43%  |
| Works    | 1151     | 3260   | 32.5%   |
| Malfunc  | 315      | 529    | 8.9%    |
| Failed   | 6        | 8      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1839     | 40.04%  |
| AMD                              | 1167     | 25.41%  |
| Samsung Electronics              | 377      | 8.21%   |
| ASMedia Technology               | 189      | 4.11%   |
| SanDisk                          | 168      | 3.66%   |
| Phison Electronics               | 161      | 3.51%   |
| Marvell Technology Group         | 107      | 2.33%   |
| Nvidia                           | 105      | 2.29%   |
| JMicron Technology               | 88       | 1.92%   |
| Micron/Crucial Technology        | 84       | 1.83%   |
| Kingston Technology Company      | 48       | 1.05%   |
| Silicon Motion                   | 42       | 0.91%   |
| ADATA Technology                 | 33       | 0.72%   |
| Seagate Technology               | 24       | 0.52%   |
| LSI Logic / Symbios Logic        | 20       | 0.44%   |
| Silicon Image                    | 19       | 0.41%   |
| Broadcom / LSI                   | 19       | 0.41%   |
| VIA Technologies                 | 17       | 0.37%   |
| Toshiba America Info Systems     | 13       | 0.28%   |
| SK hynix                         | 12       | 0.26%   |
| Realtek Semiconductor            | 9        | 0.2%    |
| Adaptec                          | 9        | 0.2%    |
| Micron Technology                | 8        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.17%   |
| KIOXIA                           | 6        | 0.13%   |
| Silicon Integrated Systems [SiS] | 3        | 0.07%   |
| Shenzhen Longsys Electronics     | 3        | 0.07%   |
| Integrated Technology Express    | 3        | 0.07%   |
| Hewlett-Packard                  | 3        | 0.07%   |
| Solidigm                         | 2        | 0.04%   |
| INNOGRIT                         | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Initio                           | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |
| Advanced System Products         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 692      | 11.82%  |
| AMD 400 Series Chipset SATA Controller                                                  | 240      | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 221      | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 220      | 3.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 181      | 3.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 178      | 3.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 156      | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 145      | 2.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 136      | 2.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 133      | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 130      | 2.22%   |
| AMD 500 Series Chipset SATA Controller                                                  | 129      | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 125      | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 123      | 2.1%    |
| Phison E12 NVMe Controller                                                              | 95       | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 90       | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 88       | 1.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 70       | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 66       | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 65       | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 60       | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 60       | 1.02%   |
| Nvidia MCP61 SATA Controller                                                            | 59       | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 56       | 0.96%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 55       | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 54       | 0.92%   |
| AMD FCH SATA Controller D                                                               | 53       | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 52       | 0.89%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 50       | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 49       | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 48       | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 47       | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 45       | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 43       | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 38       | 0.65%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 37       | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 35       | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 35       | 0.6%    |
| AMD FCH IDE Controller                                                                  | 33       | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 32       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2529     | 56.18%  |
| NVMe | 894      | 19.86%  |
| IDE  | 806      | 17.9%   |
| RAID | 218      | 4.84%   |
| SAS  | 33       | 0.73%   |
| SCSI | 22       | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1861     | 59.44%  |
| AMD                   | 1265     | 40.4%   |
| ARM                   | 2        | 0.06%   |
| sifive,u74-mc         | 1        | 0.03%   |
| Marvell Semiconductor | 1        | 0.03%   |
| CentaurHauls          | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 82       | 2.6%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 56       | 1.77%   |
| AMD FX-8350 Eight-Core Processor            | 46       | 1.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 45       | 1.43%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 38       | 1.2%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 37       | 1.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 36       | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 36       | 1.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 36       | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 35       | 1.11%   |
| AMD FX-6300 Six-Core Processor              | 34       | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 33       | 1.05%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 32       | 1.01%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 29       | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 28       | 0.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 28       | 0.89%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 28       | 0.89%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 26       | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 25       | 0.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.76%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.73%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 23       | 0.73%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 22       | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 22       | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 22       | 0.7%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 22       | 0.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 21       | 0.67%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 21       | 0.67%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 21       | 0.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 21       | 0.67%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 20       | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 18       | 0.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 18       | 0.57%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 17       | 0.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 17       | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 17       | 0.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 17       | 0.54%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 16       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 480      | 15.25%  |
| Intel Core i5           | 475      | 15.09%  |
| AMD Ryzen 5             | 284      | 9.02%   |
| AMD Ryzen 7             | 222      | 7.05%   |
| Intel Core i3           | 175      | 5.56%   |
| Intel Xeon              | 164      | 5.21%   |
| AMD FX                  | 157      | 4.99%   |
| AMD Ryzen 9             | 149      | 4.73%   |
| Intel Core 2 Duo        | 110      | 3.5%    |
| Other                   | 90       | 2.86%   |
| Intel Pentium           | 68       | 2.16%   |
| Intel Celeron           | 67       | 2.13%   |
| Intel Core 2 Quad       | 66       | 2.1%    |
| AMD Ryzen 3             | 52       | 1.65%   |
| Intel Pentium Dual-Core | 42       | 1.33%   |
| AMD Athlon II X2        | 42       | 1.33%   |
| AMD A10                 | 41       | 1.3%    |
| AMD A8                  | 40       | 1.27%   |
| Intel Core i9           | 36       | 1.14%   |
| AMD Phenom II X4        | 34       | 1.08%   |
| AMD Ryzen Threadripper  | 29       | 0.92%   |
| AMD Athlon 64 X2        | 25       | 0.79%   |
| AMD A6                  | 24       | 0.76%   |
| Intel Core 2            | 23       | 0.73%   |
| Intel Pentium 4         | 21       | 0.67%   |
| Intel Atom              | 20       | 0.64%   |
| AMD A4                  | 18       | 0.57%   |
| Intel Pentium Dual      | 17       | 0.54%   |
| Intel Pentium D         | 17       | 0.54%   |
| AMD Athlon II X4        | 17       | 0.54%   |
| AMD Athlon              | 16       | 0.51%   |
| AMD Phenom II X6        | 15       | 0.48%   |
| AMD Phenom              | 14       | 0.44%   |
| AMD Turion II Neo       | 9        | 0.29%   |
| AMD Sempron             | 7        | 0.22%   |
| AMD Phenom II X2        | 7        | 0.22%   |
| AMD Athlon II X3        | 7        | 0.22%   |
| AMD Athlon X4           | 6        | 0.19%   |
| AMD Athlon 64           | 6        | 0.19%   |
| AMD Ryzen 7 PRO         | 5        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1140     | 36.22%  |
| 2       | 767      | 24.37%  |
| 6       | 471      | 14.97%  |
| 8       | 365      | 11.6%   |
| 12      | 109      | 3.46%   |
| 16      | 87       | 2.76%   |
| 1       | 83       | 2.64%   |
| 3       | 66       | 2.1%    |
| 10      | 23       | 0.73%   |
| 24      | 17       | 0.54%   |
| 14      | 6        | 0.19%   |
| 32      | 5        | 0.16%   |
| 28      | 2        | 0.06%   |
| 64      | 1        | 0.03%   |
| 44      | 1        | 0.03%   |
| 36      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 18      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3076     | 98.24%  |
| 2       | 54       | 1.72%   |
| Unknown | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1886     | 60.1%   |
| 1       | 1251     | 39.87%  |
| Unknown | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3074     | 97.84%  |
| Unknown        | 50       | 1.59%   |
| 32-bit         | 18       | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 869      | 26.37%  |
| 0x306c3    | 237      | 7.19%   |
| 0x206a7    | 155      | 4.7%    |
| 0x08701021 | 140      | 4.25%   |
| 0x306a9    | 135      | 4.1%    |
| 0x1067a    | 110      | 3.34%   |
| 0x506e3    | 99       | 3%      |
| 0x06000852 | 82       | 2.49%   |
| 0x0800820d | 77       | 2.34%   |
| 0x010000c8 | 73       | 2.21%   |
| 0x906ea    | 67       | 2.03%   |
| 0x06001119 | 57       | 1.73%   |
| 0x08701013 | 55       | 1.67%   |
| 0x906e9    | 51       | 1.55%   |
| 0x0a201016 | 37       | 1.12%   |
| 0x6fb      | 36       | 1.09%   |
| 0x08001138 | 36       | 1.09%   |
| 0x10676    | 31       | 0.94%   |
| 0x6fd      | 29       | 0.88%   |
| 0x206c2    | 29       | 0.88%   |
| 0x906ed    | 28       | 0.85%   |
| 0x06003106 | 27       | 0.82%   |
| 0xa0655    | 26       | 0.79%   |
| 0x0a201009 | 26       | 0.79%   |
| 0x206d7    | 25       | 0.76%   |
| 0x106a5    | 25       | 0.76%   |
| 0x0a601203 | 25       | 0.76%   |
| 0x0a20120a | 24       | 0.73%   |
| 0x08108109 | 24       | 0.73%   |
| 0x08001137 | 22       | 0.67%   |
| 0x306f2    | 20       | 0.61%   |
| 0x106e5    | 20       | 0.61%   |
| 0x010000db | 20       | 0.61%   |
| 0x20655    | 19       | 0.58%   |
| 0x0600063e | 18       | 0.55%   |
| 0x90672    | 16       | 0.49%   |
| 0x306e4    | 16       | 0.49%   |
| 0x906ec    | 15       | 0.46%   |
| 0x20652    | 15       | 0.46%   |
| 0xa0671    | 14       | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 342      | 10.86%  |
| Zen 2            | 279      | 8.86%   |
| KabyLake         | 250      | 7.94%   |
| SandyBridge      | 230      | 7.3%    |
| IvyBridge        | 194      | 6.16%   |
| Piledriver       | 192      | 6.1%    |
| Penryn           | 183      | 5.81%   |
| Zen 3            | 167      | 5.3%    |
| K10              | 159      | 5.05%   |
| Skylake          | 153      | 4.86%   |
| Zen+             | 152      | 4.83%   |
| Zen              | 117      | 3.72%   |
| Core             | 109      | 3.46%   |
| Unknown          | 79       | 2.51%   |
| Westmere         | 77       | 2.45%   |
| Nehalem          | 61       | 1.94%   |
| CometLake        | 55       | 1.75%   |
| NetBurst         | 42       | 1.33%   |
| K8 Hammer        | 41       | 1.3%    |
| Steamroller      | 39       | 1.24%   |
| Alderlake Hybrid | 32       | 1.02%   |
| Bulldozer        | 29       | 0.92%   |
| Excavator        | 27       | 0.86%   |
| Silvermont       | 26       | 0.83%   |
| Broadwell        | 16       | 0.51%   |
| Icelake          | 15       | 0.48%   |
| Bonnell          | 15       | 0.48%   |
| Tremont          | 10       | 0.32%   |
| Jaguar           | 10       | 0.32%   |
| Bobcat           | 10       | 0.32%   |
| Goldmont plus    | 9        | 0.29%   |
| Goldmont         | 9        | 0.29%   |
| K10 Llano        | 6        | 0.19%   |
| K6               | 4        | 0.13%   |
| Gracemont        | 4        | 0.13%   |
| TigerLake        | 3        | 0.1%    |
| Puma             | 3        | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1447     | 42.63%  |
| AMD                                          | 1032     | 30.41%  |
| Intel                                        | 891      | 26.25%  |
| Matrox Electronics Systems                   | 8        | 0.24%   |
| ASPEED Technology                            | 6        | 0.18%   |
| ATI Technologies                             | 4        | 0.12%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| VIA Technologies                             | 1        | 0.03%   |
| Alliance Semiconductor                       | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 166      | 4.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 151      | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 114      | 3.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 110      | 3.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 73       | 2.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 63       | 1.78%   |
| Intel HD Graphics 530                                                       | 60       | 1.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 59       | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 58       | 1.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 56       | 1.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 51       | 1.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 50       | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 50       | 1.41%   |
| Nvidia GT218 [GeForce 210]                                                  | 46       | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 45       | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 45       | 1.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 44       | 1.24%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 42       | 1.19%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 42       | 1.19%   |
| Intel HD Graphics 630                                                       | 35       | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 33       | 0.93%   |
| Nvidia GF119 [GeForce GT 610]                                               | 32       | 0.9%    |
| AMD RS780L [Radeon 3000]                                                    | 32       | 0.9%    |
| AMD Raphael                                                                 | 32       | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 31       | 0.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 31       | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 29       | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 28       | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 27       | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 25       | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 24       | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 24       | 0.68%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 24       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 24       | 0.68%   |
| Intel Core Processor Integrated Graphics Controller                         | 23       | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 23       | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 22       | 0.62%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 22       | 0.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 22       | 0.62%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 21       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| 1 x Nvidia                           | 1308     | 40.94%  |
| 1 x AMD                              | 904      | 28.29%  |
| 1 x Intel                            | 717      | 22.44%  |
| Intel + Nvidia                       | 67       | 2.1%    |
| 2 x AMD                              | 60       | 1.88%   |
| AMD + Nvidia                         | 41       | 1.28%   |
| 2 x Nvidia                           | 29       | 0.91%   |
| Intel + AMD                          | 24       | 0.75%   |
| Other                                | 8        | 0.25%   |
| 1 x Matrox                           | 7        | 0.22%   |
| 2 x Intel                            | 6        | 0.19%   |
| 1 x ASPEED                           | 4        | 0.13%   |
| 2 x AMD + 1 x Nvidia                 | 3        | 0.09%   |
| Intel + AMD + 1 x Nvidia             | 3        | 0.09%   |
| 1 x SiS                              | 2        | 0.06%   |
| 3 x AMD                              | 1        | 0.03%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1        | 0.03%   |
| 1 x XGI                              | 1        | 0.03%   |
| 1 x VIA                              | 1        | 0.03%   |
| Nvidia + ASPEED                      | 1        | 0.03%   |
| 1 x Intel + 3 x Nvidia               | 1        | 0.03%   |
| Intel + 2 x Nvidia                   | 1        | 0.03%   |
| Intel + 2 x AMD                      | 1        | 0.03%   |
| Intel + AMD + 3 x Nvidia             | 1        | 0.03%   |
| AMD + SiS                            | 1        | 0.03%   |
| AMD + Matrox                         | 1        | 0.03%   |
| AMD + ASPEED                         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2161     | 66.86%  |
| Proprietary | 891      | 27.57%  |
| Unknown     | 180      | 5.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1259     | 38.22%  |
| 1.01-2.0   | 464      | 14.09%  |
| 0.51-1.0   | 348      | 10.56%  |
| 0.01-0.5   | 345      | 10.47%  |
| 7.01-8.0   | 325      | 9.87%   |
| 3.01-4.0   | 255      | 7.74%   |
| 8.01-16.0  | 127      | 3.86%   |
| 5.01-6.0   | 113      | 3.43%   |
| 2.01-3.0   | 42       | 1.28%   |
| 16.01-24.0 | 13       | 0.39%   |
| 4.01-5.0   | 2        | 0.06%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 437      | 13.25%  |
| Samsung Electronics  | 417      | 12.64%  |
| Acer                 | 290      | 8.79%   |
| BenQ                 | 217      | 6.58%   |
| AOC                  | 216      | 6.55%   |
| Goldstar             | 208      | 6.31%   |
| Hewlett-Packard      | 206      | 6.25%   |
| Iiyama               | 141      | 4.28%   |
| Ancor Communications | 119      | 3.61%   |
| Philips              | 87       | 2.64%   |
| ViewSonic            | 71       | 2.15%   |
| Sony                 | 66       | 2%      |
| ASUSTek Computer     | 64       | 1.94%   |
| Unknown              | 60       | 1.82%   |
| HannStar             | 49       | 1.49%   |
| Lenovo               | 44       | 1.33%   |
| LG Electronics       | 43       | 1.3%    |
| Panasonic            | 33       | 1%      |
| Toshiba              | 32       | 0.97%   |
| Vestel Elektronik    | 29       | 0.88%   |
| MSI                  | 29       | 0.88%   |
| NEC Computers        | 25       | 0.76%   |
| Gigabyte Technology  | 22       | 0.67%   |
| OEM                  | 17       | 0.52%   |
| Idek Iiyama          | 16       | 0.49%   |
| CVT                  | 15       | 0.45%   |
| MiTAC                | 13       | 0.39%   |
| Hitachi              | 13       | 0.39%   |
| Pixio                | 12       | 0.36%   |
| Eizo                 | 12       | 0.36%   |
| MStar                | 11       | 0.33%   |
| Fujitsu Siemens      | 11       | 0.33%   |
| Sharp                | 10       | 0.3%    |
| Unknown              | 10       | 0.3%    |
| HKC                  | 9        | 0.27%   |
| HPN                  | 8        | 0.24%   |
| HannStar Display     | 8        | 0.24%   |
| GNR                  | 8        | 0.24%   |
| Vestel               | 7        | 0.21%   |
| Packard Bell         | 7        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                       | 28       | 0.79%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 19       | 0.54%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 18       | 0.51%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 18       | 0.51%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 17       | 0.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 16       | 0.45%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 16       | 0.45%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                       | 15       | 0.42%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 13       | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 12       | 0.34%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                      | 12       | 0.34%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 11       | 0.31%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                      | 11       | 0.31%   |
| Toshiba 24W_LCD_TV TSB3700 1920x1080 706x398mm 31.9-inch               | 10       | 0.28%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                  | 10       | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 10       | 0.28%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                     | 10       | 0.28%   |
| Unknown                                                                | 10       | 0.28%   |
| Sony TV SNYE903 1920x1080                                              | 9        | 0.25%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                      | 9        | 0.25%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                     | 9        | 0.25%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 8        | 0.23%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                      | 8        | 0.23%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                      | 8        | 0.23%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 8        | 0.23%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 8        | 0.23%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 8        | 0.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 8        | 0.23%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                        | 7        | 0.2%    |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 7        | 0.2%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 7        | 0.2%    |
| MiTAC MTC26T42 SZM0308 1280x720 708x398mm 32.0-inch                    | 7        | 0.2%    |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                   | 7        | 0.2%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 7        | 0.2%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 7        | 0.2%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 7        | 0.2%    |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 7        | 0.2%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 6        | 0.17%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 6        | 0.17%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 6        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1414     | 43.95%  |
| 3840x2160 (4K)     | 362      | 11.25%  |
| 2560x1440 (QHD)    | 267      | 8.3%    |
| 1280x1024 (SXGA)   | 220      | 6.84%   |
| 1680x1050 (WSXGA+) | 149      | 4.63%   |
| 1440x900 (WXGA+)   | 104      | 3.23%   |
| Unknown            | 99       | 3.08%   |
| 1920x1200 (WUXGA)  | 95       | 2.95%   |
| 3440x1440          | 78       | 2.42%   |
| 3840x1080          | 51       | 1.59%   |
| 1360x768           | 49       | 1.52%   |
| 1600x900 (HD+)     | 47       | 1.46%   |
| 1920x540           | 41       | 1.27%   |
| 2560x1080          | 38       | 1.18%   |
| 1366x768 (WXGA)    | 33       | 1.03%   |
| 1024x768 (XGA)     | 25       | 0.78%   |
| 1600x1200          | 22       | 0.68%   |
| 1280x720 (HD)      | 18       | 0.56%   |
| 2288x1287          | 9        | 0.28%   |
| 5120x1440          | 8        | 0.25%   |
| 2560x1600          | 8        | 0.25%   |
| 5760x1080          | 7        | 0.22%   |
| 7680x2160          | 5        | 0.16%   |
| 3840x1200          | 5        | 0.16%   |
| 5760x2160          | 4        | 0.12%   |
| 3840x1600          | 4        | 0.12%   |
| 3200x1080          | 4        | 0.12%   |
| 2048x1152          | 4        | 0.12%   |
| 4480x1440          | 3        | 0.09%   |
| 6400x2160          | 2        | 0.06%   |
| 4480x1080          | 2        | 0.06%   |
| 3360x1080          | 2        | 0.06%   |
| 3360x1050          | 2        | 0.06%   |
| 3120x1050          | 2        | 0.06%   |
| 2944x1080          | 2        | 0.06%   |
| 2048x1080          | 2        | 0.06%   |
| 1280x800 (WXGA)    | 2        | 0.06%   |
| 7680x1440          | 1        | 0.03%   |
| 7280x1440          | 1        | 0.03%   |
| 6880x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 467      | 14.27%  |
| 24      | 448      | 13.69%  |
| Unknown | 433      | 13.23%  |
| 23      | 362      | 11.06%  |
| 21      | 339      | 10.36%  |
| 19      | 181      | 5.53%   |
| 31      | 136      | 4.16%   |
| 17      | 111      | 3.39%   |
| 22      | 96       | 2.93%   |
| 84      | 90       | 2.75%   |
| 34      | 84       | 2.57%   |
| 20      | 65       | 1.99%   |
| 18      | 60       | 1.83%   |
| 72      | 52       | 1.59%   |
| 32      | 40       | 1.22%   |
| 15      | 34       | 1.04%   |
| 26      | 27       | 0.82%   |
| 25      | 21       | 0.64%   |
| 40      | 20       | 0.61%   |
| 54      | 17       | 0.52%   |
| 48      | 15       | 0.46%   |
| 39      | 15       | 0.46%   |
| 33      | 14       | 0.43%   |
| 28      | 14       | 0.43%   |
| 52      | 12       | 0.37%   |
| 60      | 10       | 0.31%   |
| 46      | 10       | 0.31%   |
| 65      | 8        | 0.24%   |
| 55      | 8        | 0.24%   |
| 35      | 8        | 0.24%   |
| 29      | 7        | 0.21%   |
| 142     | 6        | 0.18%   |
| 43      | 6        | 0.18%   |
| 42      | 6        | 0.18%   |
| 37      | 6        | 0.18%   |
| 14      | 6        | 0.18%   |
| 57      | 5        | 0.15%   |
| 12      | 5        | 0.15%   |
| 36      | 4        | 0.12%   |
| 30      | 4        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1162     | 36.56%  |
| 401-500        | 639      | 20.11%  |
| Unknown        | 433      | 13.62%  |
| 601-700        | 220      | 6.92%   |
| 301-350        | 144      | 4.53%   |
| 701-800        | 143      | 4.5%    |
| 1501-2000      | 141      | 4.44%   |
| 351-400        | 119      | 3.74%   |
| 1001-1500      | 97       | 3.05%   |
| 801-900        | 47       | 1.48%   |
| 901-1000       | 14       | 0.44%   |
| 201-300        | 13       | 0.41%   |
| More than 2000 | 6        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1862     | 61.68%  |
| Unknown | 384      | 12.72%  |
| 16/10   | 355      | 11.76%  |
| 5/4     | 205      | 6.79%   |
| 21/9    | 104      | 3.44%   |
| 4/3     | 52       | 1.72%   |
| 32/9    | 21       | 0.7%    |
| 3/2     | 15       | 0.5%    |
| 1.00    | 10       | 0.33%   |
| 6/5     | 9        | 0.3%    |
| 3.20    | 2        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 977      | 30.46%  |
| 301-350        | 483      | 15.06%  |
| Unknown        | 433      | 13.5%   |
| 151-200        | 365      | 11.38%  |
| 351-500        | 293      | 9.14%   |
| More than 1000 | 211      | 6.58%   |
| 251-300        | 169      | 5.27%   |
| 141-150        | 134      | 4.18%   |
| 501-1000       | 86       | 2.68%   |
| 101-110        | 34       | 1.06%   |
| 71-80          | 5        | 0.16%   |
| 111-120        | 5        | 0.16%   |
| 131-140        | 3        | 0.09%   |
| 81-90          | 2        | 0.06%   |
| 41-50          | 2        | 0.06%   |
| 121-130        | 2        | 0.06%   |
| 91-100         | 2        | 0.06%   |
| 51-60          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1699     | 55.54%  |
| 101-120       | 571      | 18.67%  |
| Unknown       | 433      | 14.15%  |
| 121-160       | 159      | 5.2%    |
| 1-50          | 139      | 4.54%   |
| 161-240       | 57       | 1.86%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2454     | 75.62%  |
| 2     | 502      | 15.47%  |
| 0     | 215      | 6.63%   |
| 3     | 67       | 2.06%   |
| 4     | 7        | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1810     | 39.4%   |
| Intel                            | 1417     | 30.84%  |
| Qualcomm Atheros                 | 268      | 5.83%   |
| Broadcom                         | 225      | 4.9%    |
| Ralink Technology                | 152      | 3.31%   |
| Nvidia                           | 89       | 1.94%   |
| TP-Link                          | 73       | 1.59%   |
| Ralink                           | 66       | 1.44%   |
| MediaTek                         | 56       | 1.22%   |
| Microsoft                        | 36       | 0.78%   |
| Marvell Technology Group         | 36       | 0.78%   |
| Broadcom Limited                 | 36       | 0.78%   |
| Belkin Components                | 25       | 0.54%   |
| Aquantia                         | 24       | 0.52%   |
| NetGear                          | 23       | 0.5%    |
| Qualcomm Atheros Communications  | 22       | 0.48%   |
| Samsung Electronics              | 19       | 0.41%   |
| Edimax Technology                | 16       | 0.35%   |
| Huawei Technologies              | 15       | 0.33%   |
| ASIX Electronics                 | 12       | 0.26%   |
| ASUSTek Computer                 | 10       | 0.22%   |
| Mellanox Technologies            | 8        | 0.17%   |
| D-Link System                    | 8        | 0.17%   |
| D-Link                           | 8        | 0.17%   |
| Xiaomi                           | 7        | 0.15%   |
| VIA Technologies                 | 6        | 0.13%   |
| IMC Networks                     | 6        | 0.13%   |
| DisplayLink                      | 6        | 0.13%   |
| OPPO Electronics                 | 5        | 0.11%   |
| Google                           | 5        | 0.11%   |
| Apple                            | 5        | 0.11%   |
| ZTE WCDMA Technologies MSM       | 4        | 0.09%   |
| Texas Instruments                | 4        | 0.09%   |
| Silicon Integrated Systems [SiS] | 4        | 0.09%   |
| OnePlus Technology (Shenzhen)    | 4        | 0.09%   |
| Motorola PCS                     | 4        | 0.09%   |
| Microchip Technology             | 4        | 0.09%   |
| Gemtek                           | 4        | 0.09%   |
| Emulex                           | 4        | 0.09%   |
| Arduino SA                       | 4        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1401     | 26.73%  |
| Intel I211 Gigabit Network Connection                             | 256      | 4.88%   |
| Intel Wi-Fi 6 AX200                                               | 166      | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 145      | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 141      | 2.69%   |
| Intel Ethernet Connection (2) I219-V                              | 127      | 2.42%   |
| Intel Ethernet Controller I225-V                                  | 87       | 1.66%   |
| Intel Ethernet Connection I217-LM                                 | 73       | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 61       | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 60       | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 58       | 1.11%   |
| Ralink MT7601U Wireless Adapter                                   | 57       | 1.09%   |
| Realtek 802.11ac NIC                                              | 54       | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 52       | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 51       | 0.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 49       | 0.93%   |
| Intel Wireless-AC 9260                                            | 45       | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 44       | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41       | 0.78%   |
| Ralink RT5370 Wireless Adapter                                    | 40       | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 40       | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 39       | 0.74%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 37       | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36       | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36       | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32       | 0.61%   |
| Intel Wireless 7260                                               | 32       | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 28       | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 28       | 0.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 26       | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 25       | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 25       | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23       | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 21       | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21       | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 21       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 491      | 29.02%  |
| Realtek Semiconductor           | 405      | 23.94%  |
| Qualcomm Atheros                | 156      | 9.22%   |
| Ralink Technology               | 152      | 8.98%   |
| Broadcom                        | 103      | 6.09%   |
| TP-Link                         | 73       | 4.31%   |
| Ralink                          | 65       | 3.84%   |
| MediaTek                        | 51       | 3.01%   |
| Microsoft                       | 36       | 2.13%   |
| Belkin Components               | 24       | 1.42%   |
| NetGear                         | 23       | 1.36%   |
| Qualcomm Atheros Communications | 22       | 1.3%    |
| Edimax Technology               | 16       | 0.95%   |
| Broadcom Limited                | 16       | 0.95%   |
| ASUSTek Computer                | 10       | 0.59%   |
| D-Link                          | 8        | 0.47%   |
| D-Link System                   | 7        | 0.41%   |
| IMC Networks                    | 6        | 0.35%   |
| Gemtek                          | 4        | 0.24%   |
| ZyDAS                           | 3        | 0.18%   |
| TRENDnet                        | 3        | 0.18%   |
| Sitecom Europe                  | 3        | 0.18%   |
| Linksys                         | 3        | 0.18%   |
| Wilocity                        | 2        | 0.12%   |
| Philips (or NXP)                | 2        | 0.12%   |
| Marvell Technology Group        | 2        | 0.12%   |
| Wacom                           | 1        | 0.06%   |
| Texas Instruments               | 1        | 0.06%   |
| Micro Star International        | 1        | 0.06%   |
| Dell                            | 1        | 0.06%   |
| CyberTAN Technology             | 1        | 0.06%   |
| AboCom Systems                  | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 166      | 9.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 61       | 3.54%   |
| Ralink MT7601U Wireless Adapter                                | 57       | 3.3%    |
| Realtek 802.11ac NIC                                           | 54       | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 51       | 2.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 49       | 2.84%   |
| Intel Wireless-AC 9260                                         | 45       | 2.61%   |
| Ralink RT5370 Wireless Adapter                                 | 40       | 2.32%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 40       | 2.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 37       | 2.14%   |
| Intel Wireless 7260                                            | 32       | 1.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28       | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 28       | 1.62%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 26       | 1.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 25       | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23       | 1.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 21       | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21       | 1.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 21       | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 21       | 1.22%   |
| Intel Wireless 3165                                            | 21       | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 20       | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                | 19       | 1.1%    |
| Intel Wireless 8260                                            | 19       | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 18       | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 16       | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 16       | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 16       | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16       | 0.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 16       | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16       | 0.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 15       | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 14       | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14       | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 14       | 0.81%   |
| Intel Wireless 7265                                            | 14       | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 13       | 0.75%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 13       | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                  | 12       | 0.7%    |
| Microsoft Xbox 360 Wireless Adapter                            | 12       | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1626     | 48.51%  |
| Intel                                  | 1177     | 35.11%  |
| Broadcom                               | 129      | 3.85%   |
| Qualcomm Atheros                       | 122      | 3.64%   |
| Nvidia                                 | 89       | 2.66%   |
| Marvell Technology Group               | 34       | 1.01%   |
| Aquantia                               | 24       | 0.72%   |
| Broadcom Limited                       | 20       | 0.6%    |
| Samsung Electronics                    | 19       | 0.57%   |
| Huawei Technologies                    | 13       | 0.39%   |
| ASIX Electronics                       | 12       | 0.36%   |
| Xiaomi                                 | 7        | 0.21%   |
| Mellanox Technologies                  | 7        | 0.21%   |
| VIA Technologies                       | 6        | 0.18%   |
| DisplayLink                            | 6        | 0.18%   |
| OPPO Electronics                       | 5        | 0.15%   |
| MediaTek                               | 5        | 0.15%   |
| Google                                 | 5        | 0.15%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.12%   |
| Silicon Integrated Systems [SiS]       | 4        | 0.12%   |
| Emulex                                 | 4        | 0.12%   |
| Apple                                  | 4        | 0.12%   |
| T & A Mobile Phones                    | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| Motorola PCS                           | 3        | 0.09%   |
| 3Com                                   | 3        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |
| Microchip Technology                   | 2        | 0.06%   |
| Lenovo                                 | 2        | 0.06%   |
| HMD Global                             | 2        | 0.06%   |
| SysKonnect                             | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Solarflare Communications              | 1        | 0.03%   |
| Research In Motion                     | 1        | 0.03%   |
| Qualcomm                               | 1        | 0.03%   |
| QLogic                                 | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |
| HTC (High Tech Computer)               | 1        | 0.03%   |
| D-Link System                          | 1        | 0.03%   |
| Belkin Components                      | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1401     | 40.35%  |
| Intel I211 Gigabit Network Connection                             | 256      | 7.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 145      | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 141      | 4.06%   |
| Intel Ethernet Connection (2) I219-V                              | 127      | 3.66%   |
| Intel Ethernet Controller I225-V                                  | 87       | 2.51%   |
| Intel Ethernet Connection I217-LM                                 | 73       | 2.1%    |
| Intel Ethernet Connection (7) I219-V                              | 60       | 1.73%   |
| Intel 82579V Gigabit Network Connection                           | 58       | 1.67%   |
| Nvidia MCP61 Ethernet                                             | 52       | 1.5%    |
| Intel Ethernet Connection (2) I218-V                              | 44       | 1.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41       | 1.18%   |
| Intel Ethernet Connection I217-V                                  | 39       | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36       | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36       | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32       | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 25       | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.66%   |
| Intel 82562V-2 10/100 Network Connection                          | 20       | 0.58%   |
| Intel 82578DM Gigabit Network Connection                          | 19       | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17       | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17       | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 17       | 0.49%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 17       | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15       | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14       | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12       | 0.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12       | 0.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 12       | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 11       | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 11       | 0.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 11       | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10       | 0.29%   |
| Intel 82578DC Gigabit Network Connection                          | 10       | 0.29%   |
| Intel I350 Gigabit Network Connection                             | 9        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3086     | 65.97%  |
| WiFi     | 1548     | 33.09%  |
| Modem    | 34       | 0.73%   |
| Unknown  | 10       | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2413     | 73.77%  |
| WiFi     | 858      | 26.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1914     | 60.25%  |
| 2     | 1039     | 32.7%   |
| 3     | 148      | 4.66%   |
| 0     | 34       | 1.07%   |
| 4     | 22       | 0.69%   |
| 5     | 15       | 0.47%   |
| 6     | 4        | 0.13%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2741     | 86.11%  |
| Yes  | 442      | 13.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 426      | 38.1%   |
| Cambridge Silicon Radio         | 269      | 24.06%  |
| Broadcom                        | 88       | 7.87%   |
| Realtek Semiconductor           | 75       | 6.71%   |
| ASUSTek Computer                | 73       | 6.53%   |
| Qualcomm Atheros Communications | 31       | 2.77%   |
| MediaTek                        | 29       | 2.59%   |
| Apple                           | 27       | 2.42%   |
| IMC Networks                    | 15       | 1.34%   |
| TP-Link                         | 14       | 1.25%   |
| Belkin Components               | 14       | 1.25%   |
| Foxconn / Hon Hai               | 11       | 0.98%   |
| Lite-On Technology              | 9        | 0.81%   |
| Integrated System Solution      | 9        | 0.81%   |
| Logitech                        | 5        | 0.45%   |
| Micro Star International        | 4        | 0.36%   |
| HTC (High Tech Computer)        | 4        | 0.36%   |
| Dell                            | 4        | 0.36%   |
| Hewlett-Packard                 | 2        | 0.18%   |
| Unknown                         | 2        | 0.18%   |
| Taiyo Yuden                     | 1        | 0.09%   |
| SINO WEALTH                     | 1        | 0.09%   |
| Realtek                         | 1        | 0.09%   |
| Edimax Technology               | 1        | 0.09%   |
| D-Link                          | 1        | 0.09%   |
| Cypress Semiconductor           | 1        | 0.09%   |
| Creative Technology             | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 269      | 24.04%  |
| Intel AX200 Bluetooth                                                | 143      | 12.78%  |
| Intel Bluetooth wireless interface                                   | 88       | 7.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 71       | 6.34%   |
| Realtek Bluetooth Radio                                              | 59       | 5.27%   |
| Intel AX210 Bluetooth                                                | 44       | 3.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 43       | 3.84%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 34       | 3.04%   |
| Intel AX201 Bluetooth                                                | 34       | 3.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 30       | 2.68%   |
| MediaTek Wireless_Device                                             | 29       | 2.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 27       | 2.41%   |
| TP-Link UB500 Adapter                                                | 14       | 1.25%   |
| Intel Bluetooth Device                                               | 13       | 1.16%   |
| IMC Networks Bluetooth Radio                                         | 12       | 1.07%   |
| Apple Bluetooth Host Controller                                      | 11       | 0.98%   |
| Qualcomm Atheros  Bluetooth Device                                   | 10       | 0.89%   |
| ASUS BCM20702A0                                                      | 10       | 0.89%   |
| Realtek RTL8821A Bluetooth                                           | 8        | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                                    | 8        | 0.71%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 8        | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 8        | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.63%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.63%   |
| ASUS Bluetooth Radio                                                 | 7        | 0.63%   |
| Apple Bluetooth HCI                                                  | 7        | 0.63%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 6        | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 6        | 0.54%   |
| Integrated System Solution Bluetooth Device                          | 6        | 0.54%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 5        | 0.45%   |
| Lite-On Bluetooth Device                                             | 5        | 0.45%   |
| Belkin Components Bluetooth Mini Dongle                              | 5        | 0.45%   |
| ASUS Bluetooth Device                                                | 5        | 0.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.36%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 4        | 0.36%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3        | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3        | 0.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3        | 0.27%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 3        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1754     | 31.93%  |
| AMD                                          | 1449     | 26.37%  |
| Nvidia                                       | 1371     | 24.95%  |
| C-Media Electronics                          | 157      | 2.86%   |
| Creative Labs                                | 94       | 1.71%   |
| Logitech                                     | 58       | 1.06%   |
| Texas Instruments                            | 46       | 0.84%   |
| Razer USA                                    | 34       | 0.62%   |
| ASUSTek Computer                             | 33       | 0.6%    |
| Focusrite-Novation                           | 32       | 0.58%   |
| Micro Star International                     | 28       | 0.51%   |
| SteelSeries ApS                              | 26       | 0.47%   |
| Creative Technology                          | 25       | 0.46%   |
| JMTek                                        | 22       | 0.4%    |
| Kingston Technology                          | 17       | 0.31%   |
| Corsair                                      | 17       | 0.31%   |
| Blue Microphones                             | 17       | 0.31%   |
| VIA Technologies                             | 15       | 0.27%   |
| BEHRINGER International                      | 12       | 0.22%   |
| Realtek Semiconductor                        | 11       | 0.2%    |
| Generalplus Technology                       | 11       | 0.2%    |
| Thesycon Systemsoftware & Consulting         | 10       | 0.18%   |
| GN Netcom                                    | 10       | 0.18%   |
| Tenx Technology                              | 9        | 0.16%   |
| Plantronics                                  | 9        | 0.16%   |
| Sennheiser Communications                    | 8        | 0.15%   |
| KTMicro                                      | 7        | 0.13%   |
| Samson Technologies                          | 6        | 0.11%   |
| FiiO Electronics Technology                  | 6        | 0.11%   |
| Dell                                         | 6        | 0.11%   |
| Cambridge Silicon Radio                      | 6        | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.09%   |
| XMOS                                         | 5        | 0.09%   |
| Valve Software                               | 5        | 0.09%   |
| GYROCOM C&C                                  | 5        | 0.09%   |
| DSEA A/S                                     | 5        | 0.09%   |
| Astro Gaming                                 | 5        | 0.09%   |
| Asahi Kasei Microsystems                     | 5        | 0.09%   |
| AKAI Professional M.I.                       | 5        | 0.09%   |
| Unknown                                      | 4        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 376      | 5.83%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 249      | 3.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 232      | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 213      | 3.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 190      | 2.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 190      | 2.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 154      | 2.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 149      | 2.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 148      | 2.29%   |
| Intel 200 Series PCH HD Audio                                              | 147      | 2.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 142      | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 134      | 2.08%   |
| AMD FCH Azalia Controller                                                  | 121      | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 105      | 1.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 97       | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 96       | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94       | 1.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 92       | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 86       | 1.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 80       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 79       | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 75       | 1.16%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 71       | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 65       | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 65       | 1.01%   |
| AMD Navi 10 HDMI Audio                                                     | 65       | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 62       | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 60       | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 57       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 56       | 0.87%   |
| Nvidia GM206 High Definition Audio Controller                              | 55       | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 54       | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 53       | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53       | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 52       | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 51       | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 50       | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 49       | 0.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 48       | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 48       | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 468      | 26.88%  |
| Kingston                     | 225      | 12.92%  |
| Unknown                      | 217      | 12.46%  |
| Crucial                      | 196      | 11.26%  |
| SK hynix                     | 142      | 8.16%   |
| Samsung Electronics          | 142      | 8.16%   |
| Micron Technology            | 93       | 5.34%   |
| G.Skill                      | 43       | 2.47%   |
| A-DATA Technology            | 34       | 1.95%   |
| Team                         | 26       | 1.49%   |
| Patriot                      | 17       | 0.98%   |
| Nanya Technology             | 15       | 0.86%   |
| Ramaxel Technology           | 14       | 0.8%    |
| Elpida                       | 13       | 0.75%   |
| Unknown                      | 8        | 0.46%   |
| Unknown (ABCD)               | 7        | 0.4%    |
| Transcend                    | 6        | 0.34%   |
| ASint Technology             | 5        | 0.29%   |
| A Force                      | 5        | 0.29%   |
| Timetec                      | 4        | 0.23%   |
| Qimonda                      | 4        | 0.23%   |
| KLEVV                        | 4        | 0.23%   |
| Hewlett-Packard              | 4        | 0.23%   |
| Apacer                       | 4        | 0.23%   |
| Lexar Co Limited             | 3        | 0.17%   |
| CSX                          | 3        | 0.17%   |
| Thermaltake                  | 2        | 0.11%   |
| Patriot Memory (PDP Systems) | 2        | 0.11%   |
| Lexar                        | 2        | 0.11%   |
| Infineon                     | 2        | 0.11%   |
| GOODRAM                      | 2        | 0.11%   |
| Axiom                        | 2        | 0.11%   |
| Wilk Elektronik              | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (9B0D)               | 1        | 0.06%   |
| Unknown (83CB)               | 1        | 0.06%   |
| Unknown (0x5846)             | 1        | 0.06%   |
| Unknown (0x4000000000000000) | 1        | 0.06%   |
| Unknown (0x0E9D)             | 1        | 0.06%   |
| Unknown (0x0B15)             | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 44       | 2.29%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 22       | 1.15%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 18       | 0.94%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 17       | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 15       | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 14       | 0.73%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 11       | 0.57%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s         | 11       | 0.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 10       | 0.52%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 10       | 0.52%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s          | 9        | 0.47%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s          | 9        | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 8        | 0.42%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 8        | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 8        | 0.42%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s         | 8        | 0.42%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s         | 8        | 0.42%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 8        | 0.42%   |
| Unknown                                                        | 8        | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 7        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 7        | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.36%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 7        | 0.36%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 7        | 0.36%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 7        | 0.36%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s          | 7        | 0.36%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 7        | 0.36%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s           | 7        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 6        | 0.31%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 6        | 0.31%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.31%   |
| Samsung RAM M3 78T2863QZS-CF7 1024MB DIMM DDR2 800MT/s         | 6        | 0.31%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 6        | 0.31%   |
| Crucial RAM CT8G4DFD824A.C16FHP 8GB DIMM DDR4 2400MT/s         | 6        | 0.31%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s          | 6        | 0.31%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 6        | 0.31%   |
| Corsair RAM CMK32GX4M2Z3200C16 16GB DIMM DDR4 3200MT/s         | 6        | 0.31%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 6        | 0.31%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 6        | 0.31%   |
| Corsair RAM CMK16GX4M2Z3600C18 8GB DIMM DDR4 3600MT/s          | 6        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 728      | 47.8%   |
| DDR3    | 483      | 31.71%  |
| Unknown | 99       | 6.5%    |
| DDR2    | 89       | 5.84%   |
| SDRAM   | 58       | 3.81%   |
| DDR5    | 40       | 2.63%   |
| DDR     | 17       | 1.12%   |
| LPDDR4  | 8        | 0.53%   |
| LPDDR5  | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1388     | 93.47%  |
| SODIMM       | 83       | 5.59%   |
| RIMM         | 6        | 0.4%    |
| FB-DIMM      | 6        | 0.4%    |
| Row Of Chips | 2        | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 612      | 37.2%   |
| 4096   | 367      | 22.31%  |
| 16384  | 291      | 17.69%  |
| 2048   | 204      | 12.4%   |
| 32768  | 85       | 5.17%   |
| 1024   | 74       | 4.5%    |
| 512    | 7        | 0.43%   |
| 131072 | 1        | 0.06%   |
| 49152  | 1        | 0.06%   |
| 256    | 1        | 0.06%   |
| 16     | 1        | 0.06%   |
| 13     | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 274      | 16.05%  |
| 1333    | 188      | 11.01%  |
| 3200    | 152      | 8.9%    |
| 3600    | 127      | 7.44%   |
| 2400    | 121      | 7.09%   |
| 2133    | 75       | 4.39%   |
| 2667    | 70       | 4.1%    |
| 800     | 66       | 3.87%   |
| 667     | 54       | 3.16%   |
| 3400    | 44       | 2.58%   |
| 3000    | 42       | 2.46%   |
| 1867    | 36       | 2.11%   |
| 3733    | 32       | 1.87%   |
| 1800    | 32       | 1.87%   |
| 2933    | 28       | 1.64%   |
| 2800    | 27       | 1.58%   |
| 3533    | 23       | 1.35%   |
| 2666    | 23       | 1.35%   |
| 1866    | 22       | 1.29%   |
| 1066    | 20       | 1.17%   |
| Unknown | 19       | 1.11%   |
| 3800    | 16       | 0.94%   |
| 4800    | 14       | 0.82%   |
| 3266    | 14       | 0.82%   |
| 400     | 13       | 0.76%   |
| 533     | 12       | 0.7%    |
| 6000    | 10       | 0.59%   |
| 3666    | 10       | 0.59%   |
| 2048    | 10       | 0.59%   |
| 1067    | 8        | 0.47%   |
| 49926   | 7        | 0.41%   |
| 3534    | 6        | 0.35%   |
| 3100    | 6        | 0.35%   |
| 2000    | 6        | 0.35%   |
| 3007    | 5        | 0.29%   |
| 2733    | 5        | 0.29%   |
| 1648    | 5        | 0.29%   |
| 6400    | 4        | 0.23%   |
| 5200    | 4        | 0.23%   |
| 3933    | 4        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 67       | 46.53%  |
| Canon                 | 25       | 17.36%  |
| Seiko Epson           | 13       | 9.03%   |
| Samsung Electronics   | 12       | 8.33%   |
| Brother Industries    | 12       | 8.33%   |
| Prolific Technology   | 3        | 2.08%   |
| QinHeng Electronics   | 2        | 1.39%   |
| Dymo-CoStar           | 2        | 1.39%   |
| Seiko Instruments     | 1        | 0.69%   |
| Ricoh                 | 1        | 0.69%   |
| Pantum                | 1        | 0.69%   |
| Oki Data              | 1        | 0.69%   |
| Lexmark International | 1        | 0.69%   |
| Kyocera               | 1        | 0.69%   |
| Dell                  | 1        | 0.69%   |
| Apple                 | 1        | 0.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson Printer                  | 6        | 4.14%   |
| HP ENVY 4520 series                  | 5        | 3.45%   |
| Canon PIXMA MG2500 Series            | 5        | 3.45%   |
| HP ENVY 5000 series                  | 4        | 2.76%   |
| HP DeskJet 2600 series               | 4        | 2.76%   |
| Prolific PL2305 Parallel Port        | 3        | 2.07%   |
| HP DeskJet 2130 series               | 3        | 2.07%   |
| Seiko Epson XP-240 Series            | 2        | 1.38%   |
| Seiko Epson XP-200 Series            | 2        | 1.38%   |
| Samsung ML-2250 Series               | 2        | 1.38%   |
| Samsung ML-216x Series Laser Printer | 2        | 1.38%   |
| Samsung M2020 Series                 | 2        | 1.38%   |
| QinHeng CH340S                       | 2        | 1.38%   |
| HP OfficeJet 3830 series             | 2        | 1.38%   |
| HP LaserJet 200 colorMFP M276nw      | 2        | 1.38%   |
| HP Deskjet F2280 series              | 2        | 1.38%   |
| HP DeskJet 3630 series               | 2        | 1.38%   |
| HP DeskJet 2700 series               | 2        | 1.38%   |
| HP Deskjet 1000 J110 series          | 2        | 1.38%   |
| HP Color LaserJet CP1215             | 2        | 1.38%   |
| Canon TS3100 series                  | 2        | 1.38%   |
| Canon PIXMA MX920 Series             | 2        | 1.38%   |
| Canon PIXMA MP495                    | 2        | 1.38%   |
| Canon MG5700 series                  | 2        | 1.38%   |
| Canon iP7200 series                  | 2        | 1.38%   |
| Brother HL-3140CW series             | 2        | 1.38%   |
| Seiko Instruments SLP-450 Driver     | 1        | 0.69%   |
| Seiko Epson XP-211 214 216 Series    | 1        | 0.69%   |
| Seiko Epson WF-3520 Series           | 1        | 0.69%   |
| Seiko Epson WF-2010 Series           | 1        | 0.69%   |
| Seiko Epson L355 Series              | 1        | 0.69%   |
| Samsung SCX-4300 Series              | 1        | 0.69%   |
| Samsung SCX-4200 series              | 1        | 0.69%   |
| Samsung SCX-3400 Series              | 1        | 0.69%   |
| Samsung ML-1865                      | 1        | 0.69%   |
| Samsung C48x Series                  | 1        | 0.69%   |
| Samsung C43x Series                  | 1        | 0.69%   |
| Ricoh SP C260SFNw                    | 1        | 0.69%   |
| Pantum P2200W series                 | 1        | 0.69%   |
| Oki Data USB Device                  | 1        | 0.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 21       | 63.64%  |
| Seiko Epson        | 7        | 21.21%  |
| Ultima Electronics | 2        | 6.06%   |
| Mustek Systems     | 1        | 3.03%   |
| Hewlett-Packard    | 1        | 3.03%   |
| AGFA-Gevaert NV    | 1        | 3.03%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5        | 15.15%  |
| Canon CanoScan LiDE 220                                                               | 4        | 12.12%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 9.09%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 6.06%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 6.06%   |
| Canon CanoScan LIDE 25                                                                | 2        | 6.06%   |
| Canon CanoScan LiDE 200                                                               | 2        | 6.06%   |
| Seiko Epson Scanner                                                                   | 1        | 3.03%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 3.03%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 3.03%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 3.03%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 3.03%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1        | 3.03%   |
| HP Scanjet G2710                                                                      | 1        | 3.03%   |
| Canon CanoScan LiDE 90                                                                | 1        | 3.03%   |
| Canon CanoScan LiDE 70                                                                | 1        | 3.03%   |
| Canon CanoScan LiDE 210                                                               | 1        | 3.03%   |
| Canon CanoScan LiDE 110                                                               | 1        | 3.03%   |
| Canon CanoScan LiDE 100                                                               | 1        | 3.03%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1        | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 241      | 35.34%  |
| Microdia                      | 61       | 8.94%   |
| Microsoft                     | 57       | 8.36%   |
| ARC International             | 25       | 3.67%   |
| Samsung Electronics           | 24       | 3.52%   |
| Apple                         | 21       | 3.08%   |
| Generalplus Technology        | 20       | 2.93%   |
| Sunplus Innovation Technology | 19       | 2.79%   |
| Realtek Semiconductor         | 19       | 2.79%   |
| GEMBIRD                       | 16       | 2.35%   |
| Creative Technology           | 15       | 2.2%    |
| Chicony Electronics           | 15       | 2.2%    |
| MacroSilicon                  | 14       | 2.05%   |
| Z-Star Microelectronics       | 11       | 1.61%   |
| Razer USA                     | 10       | 1.47%   |
| Aveo Technology               | 9        | 1.32%   |
| Huawei Technologies           | 8        | 1.17%   |
| Hewlett-Packard               | 8        | 1.17%   |
| WCM_USB                       | 5        | 0.73%   |
| Tobii Technology AB           | 5        | 0.73%   |
| SunplusIT                     | 4        | 0.59%   |
| Lenovo                        | 4        | 0.59%   |
| KYE Systems (Mouse Systems)   | 4        | 0.59%   |
| Genesys Logic                 | 4        | 0.59%   |
| Valve Software                | 3        | 0.44%   |
| Trust                         | 3        | 0.44%   |
| OmniVision Technologies       | 3        | 0.44%   |
| Arkmicro Technologies         | 3        | 0.44%   |
| YGTek                         | 2        | 0.29%   |
| ValueHD                       | 2        | 0.29%   |
| Sonix Technology              | 2        | 0.29%   |
| Quanta                        | 2        | 0.29%   |
| Oculus VR                     | 2        | 0.29%   |
| Nokia Mobile Phones           | 2        | 0.29%   |
| Linux Foundation              | 2        | 0.29%   |
| LG Electronics                | 2        | 0.29%   |
| Leap Motion                   | 2        | 0.29%   |
| HTC (High Tech Computer)      | 2        | 0.29%   |
| Google                        | 2        | 0.29%   |
| Cubeternet                    | 2        | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 68       | 9.87%   |
| Logitech Webcam C270                              | 50       | 7.26%   |
| Microsoft LifeCam HD-3000                         | 28       | 4.06%   |
| ARC International Camera                          | 25       | 3.63%   |
| Samsung Galaxy series, misc. (MTP mode)           | 24       | 3.48%   |
| Microdia Webcam Vitade AF                         | 23       | 3.34%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 21       | 3.05%   |
| Microsoft LifeCam Cinema                          | 16       | 2.32%   |
| Logitech C922 Pro Stream Webcam                   | 16       | 2.32%   |
| Microdia USB 2.0 Camera                           | 15       | 2.18%   |
| MacroSilicon USB Video                            | 14       | 2.03%   |
| Logitech HD Webcam C615                           | 12       | 1.74%   |
| Realtek Full HD webcam                            | 10       | 1.45%   |
| Generalplus GENERAL WEBCAM                        | 10       | 1.45%   |
| Logitech Webcam C930e                             | 9        | 1.31%   |
| Logitech C920 PRO HD Webcam                       | 9        | 1.31%   |
| Logitech Webcam Pro 9000                          | 8        | 1.16%   |
| Logitech BRIO 4K Stream Edition                   | 8        | 1.16%   |
| Huawei UVC Camera                                 | 8        | 1.16%   |
| GEMBIRD USB2.0 PC CAMERA                          | 8        | 1.16%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 8        | 1.16%   |
| Sunplus Full HD webcam                            | 7        | 1.02%   |
| Microdia Sonix USB 2.0 Camera                     | 7        | 1.02%   |
| Logitech B525 HD Webcam                           | 7        | 1.02%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 7        | 1.02%   |
| Razer USA Gaming Webcam [Kiyo]                    | 6        | 0.87%   |
| Microdia Camera                                   | 6        | 0.87%   |
| Logitech Webcam C310                              | 6        | 0.87%   |
| HP Webcam HD 2300                                 | 6        | 0.87%   |
| WCM_USB WEB CAM                                   | 5        | 0.73%   |
| Tobii AB EyeChip                                  | 5        | 0.73%   |
| Logitech Webcam C925e                             | 5        | 0.73%   |
| Logitech StreamCam                                | 5        | 0.73%   |
| Logitech QuickCam Pro 9000                        | 5        | 0.73%   |
| Logitech HD Webcam C525                           | 5        | 0.73%   |
| Logitech BRIO Ultra HD Webcam                     | 5        | 0.73%   |
| Aveo USB2.0 Camera                                | 5        | 0.73%   |
| Z-Star Venus USB2.0 Camera                        | 4        | 0.58%   |
| Microsoft LifeCam Studio                          | 4        | 0.58%   |
| Logitech Webcam C250                              | 4        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 9        | 47.37%  |
| Synaptics                  | 5        | 26.32%  |
| STMicroelectronics         | 2        | 10.53%  |
| Shenzhen Goodix Technology | 1        | 5.26%   |
| LighTuning Technology      | 1        | 5.26%   |
| AuthenTec                  | 1        | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]  | 9        | 47.37%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 5        | 26.32%  |
| STMicroelectronics Fingerprint Reader        | 2        | 10.53%  |
| Shenzhen Goodix  Fingerprint Device          | 1        | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor    | 1        | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor         | 1        | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 6        | 46.15%  |
| OmniKey                   | 2        | 15.38%  |
| Yubico.com                | 1        | 7.69%   |
| Lenovo                    | 1        | 7.69%   |
| Hewlett-Packard           | 1        | 7.69%   |
| Bit4id                    | 1        | 7.69%   |
| Aladdin Knowledge Systems | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                  | 4        | 30.77%  |
| Alcor Micro AU9540 Smartcard Reader           | 2        | 15.38%  |
| Yubico.com Yubikey 4/5 CCID                   | 1        | 7.69%   |
| OmniKey CardMan 3021 / 3121                   | 1        | 7.69%   |
| OmniKey 3x21 Smart Card Reader                | 1        | 7.69%   |
| Lenovo Smartcard Keyboard                     | 1        | 7.69%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon) | 1        | 7.69%   |
| Bit4id miniLector EVO                         | 1        | 7.69%   |
| Aladdin Knowledge Systems Token JC            | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2604     | 80.17%  |
| 1     | 531      | 16.35%  |
| 2     | 83       | 2.56%   |
| 3     | 17       | 0.52%   |
| 4     | 7        | 0.22%   |
| 5     | 3        | 0.09%   |
| 7     | 2        | 0.06%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 265      | 36.3%   |
| Net/wireless             | 207      | 28.36%  |
| Communication controller | 50       | 6.85%   |
| Unassigned class         | 46       | 6.3%    |
| Sound                    | 37       | 5.07%   |
| Multimedia controller    | 30       | 4.11%   |
| Fingerprint reader       | 18       | 2.47%   |
| Bluetooth                | 18       | 2.47%   |
| Camera                   | 17       | 2.33%   |
| Chipcard                 | 10       | 1.37%   |
| Storage/raid             | 8        | 1.1%    |
| Network                  | 7        | 0.96%   |
| Net/ethernet             | 7        | 0.96%   |
| Modem                    | 3        | 0.41%   |
| Storage/ide              | 2        | 0.27%   |
| Card reader              | 2        | 0.27%   |
| Unclassified device      | 1        | 0.14%   |
| Storage                  | 1        | 0.14%   |
| Dvb card                 | 1        | 0.14%   |

