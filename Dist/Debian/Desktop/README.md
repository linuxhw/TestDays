Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 6353

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | MS-7708                     | [9170f4dd42](https://linux-hardware.org/?probe=9170f4dd42) | Nov 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c8c8d15e25](https://linux-hardware.org/?probe=c8c8d15e25) | Nov 06, 2023 |
| Gigabyte      | B85M-D3H                    | [42cbdffa93](https://linux-hardware.org/?probe=42cbdffa93) | Nov 05, 2023 |
| Shuttle       | FH87                        | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| Gigabyte      | Z68XP-UD3                   | [01e74da42d](https://linux-hardware.org/?probe=01e74da42d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| MSI           | PRO B760M-P DDR4            | [5b5425c6d8](https://linux-hardware.org/?probe=5b5425c6d8) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Gigabyte      | B450 AORUS M                | [62798aa8cf](https://linux-hardware.org/?probe=62798aa8cf) | Nov 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| Apple         | Mac-F221BEC8                | [03f4055831](https://linux-hardware.org/?probe=03f4055831) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| ASRock        | H61M-HVS                    | [fbbb34a0cb](https://linux-hardware.org/?probe=fbbb34a0cb) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [9495d53da4](https://linux-hardware.org/?probe=9495d53da4) | Nov 03, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [18f018a8ae](https://linux-hardware.org/?probe=18f018a8ae) | Nov 03, 2023 |
| HP            | 18E7                        | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | 18E7                        | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| Unknown       | X99-GT                      | [751ea1add9](https://linux-hardware.org/?probe=751ea1add9) | Nov 02, 2023 |
| MSI           | B450M-A PRO MAX             | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| ASRock        | X570 Taichi                 | [5ce5b321b0](https://linux-hardware.org/?probe=5ce5b321b0) | Nov 02, 2023 |
| ASRock        | Z77 WS                      | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| ASRockRack    | X470D4U                     | [553af2a3c2](https://linux-hardware.org/?probe=553af2a3c2) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [1ca6496a6c](https://linux-hardware.org/?probe=1ca6496a6c) | Nov 01, 2023 |
| ASUSTek       | CM6870                      | [ae34108b69](https://linux-hardware.org/?probe=ae34108b69) | Nov 01, 2023 |
| HP            | 83EE                        | [c32478cd8d](https://linux-hardware.org/?probe=c32478cd8d) | Nov 01, 2023 |
| HP            | 83EE                        | [37c7c72156](https://linux-hardware.org/?probe=37c7c72156) | Nov 01, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [0026b681e2](https://linux-hardware.org/?probe=0026b681e2) | Nov 01, 2023 |
| Unknown       | Unknown                     | [c7ce75613c](https://linux-hardware.org/?probe=c7ce75613c) | Nov 01, 2023 |
| Gigabyte      | X570 GAMING X               | [fee5d3eded](https://linux-hardware.org/?probe=fee5d3eded) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [34fe4c8733](https://linux-hardware.org/?probe=34fe4c8733) | Nov 01, 2023 |
| Unknown       | Unknown                     | [3c4e0eb4fc](https://linux-hardware.org/?probe=3c4e0eb4fc) | Nov 01, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Gigabyte      | H610M H DDR4                | [6e876b597c](https://linux-hardware.org/?probe=6e876b597c) | Oct 31, 2023 |
| Gigabyte      | H610M H DDR4                | [01f9a9c872](https://linux-hardware.org/?probe=01f9a9c872) | Oct 31, 2023 |
| ASUSTek       | P8H61-M LE                  | [86dd25c85a](https://linux-hardware.org/?probe=86dd25c85a) | Oct 31, 2023 |
| ASUSTek       | P8Z77-M                     | [69cd55a4dc](https://linux-hardware.org/?probe=69cd55a4dc) | Oct 31, 2023 |
| Dell          | 0NW6H5 A00                  | [3f76d752df](https://linux-hardware.org/?probe=3f76d752df) | Oct 31, 2023 |
| ASRock        | H61M-HVS                    | [eccf9444b3](https://linux-hardware.org/?probe=eccf9444b3) | Oct 31, 2023 |
| Gigabyte      | H97M-HD3                    | [0d712d2765](https://linux-hardware.org/?probe=0d712d2765) | Oct 30, 2023 |
| Intel         | X99                         | [426c412f62](https://linux-hardware.org/?probe=426c412f62) | Oct 30, 2023 |
| Dell          | 0NW6H5 A00                  | [51694ddd7c](https://linux-hardware.org/?probe=51694ddd7c) | Oct 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [64bc9621da](https://linux-hardware.org/?probe=64bc9621da) | Oct 30, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | [fca3ef2e73](https://linux-hardware.org/?probe=fca3ef2e73) | Oct 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [a7a54fb14a](https://linux-hardware.org/?probe=a7a54fb14a) | Oct 29, 2023 |
| ASUSTek       | M4A88T-M                    | [af4673599a](https://linux-hardware.org/?probe=af4673599a) | Oct 29, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9ca810aaa6](https://linux-hardware.org/?probe=9ca810aaa6) | Oct 29, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [e0b8432cdc](https://linux-hardware.org/?probe=e0b8432cdc) | Oct 29, 2023 |
| ASRock        | AM1B-M                      | [098a155bab](https://linux-hardware.org/?probe=098a155bab) | Oct 29, 2023 |
| Apple         | Mac-F221BEC8                | [4db0be5324](https://linux-hardware.org/?probe=4db0be5324) | Oct 29, 2023 |
| ASRock        | B450 Steel Legend           | [967ed7a2b9](https://linux-hardware.org/?probe=967ed7a2b9) | Oct 28, 2023 |
| ASRock        | B550M-ITX/ac                | [1643900d75](https://linux-hardware.org/?probe=1643900d75) | Oct 28, 2023 |
| Intel         | JSL MRD                     | [689d88c57b](https://linux-hardware.org/?probe=689d88c57b) | Oct 28, 2023 |
| ECS           | H61H2-M12                   | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
| Shenzhen M... | TH80                        | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [eb1a1b2e44](https://linux-hardware.org/?probe=eb1a1b2e44) | Oct 27, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [5dac9d85f1](https://linux-hardware.org/?probe=5dac9d85f1) | Oct 27, 2023 |
| ASUSTek       | P6TD DELUXE                 | [46049da51f](https://linux-hardware.org/?probe=46049da51f) | Oct 27, 2023 |
| Dell          | 0VD5HY A07                  | [3db7e99c4a](https://linux-hardware.org/?probe=3db7e99c4a) | Oct 27, 2023 |
| Dell          | 0GTK4K A02                  | [df85a996c9](https://linux-hardware.org/?probe=df85a996c9) | Oct 27, 2023 |
| Supermicro    | X10DAI                      | [11b1e48497](https://linux-hardware.org/?probe=11b1e48497) | Oct 27, 2023 |
| Gigabyte      | F2A68HM-H                   | [607a31a8ef](https://linux-hardware.org/?probe=607a31a8ef) | Oct 27, 2023 |
| Foxconn       | P35A01                      | [e63e8acdaa](https://linux-hardware.org/?probe=e63e8acdaa) | Oct 27, 2023 |
| Dell          | 0K240Y A04                  | [5bf155abe0](https://linux-hardware.org/?probe=5bf155abe0) | Oct 26, 2023 |
| ASUSTek       | P8P67 PRO                   | [a1916cc782](https://linux-hardware.org/?probe=a1916cc782) | Oct 26, 2023 |
| ASUSTek       | P5G41T-M LE                 | [ca332e91ff](https://linux-hardware.org/?probe=ca332e91ff) | Oct 26, 2023 |
| MSI           | B450M PRO-VDH MAX           | [df61e58a34](https://linux-hardware.org/?probe=df61e58a34) | Oct 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [f38d8a7556](https://linux-hardware.org/?probe=f38d8a7556) | Oct 26, 2023 |
| MSI           | MEG X570 UNIFY              | [f1bcad7519](https://linux-hardware.org/?probe=f1bcad7519) | Oct 26, 2023 |
| Pegatron      | Benicia                     | [62373f17e0](https://linux-hardware.org/?probe=62373f17e0) | Oct 25, 2023 |
| ASRock        | J4125-ITX                   | [b124e800d6](https://linux-hardware.org/?probe=b124e800d6) | Oct 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [6ae562130f](https://linux-hardware.org/?probe=6ae562130f) | Oct 25, 2023 |
| Dell          | 0VD5HY A04                  | [36249c99ec](https://linux-hardware.org/?probe=36249c99ec) | Oct 25, 2023 |
| Gigabyte      | B450M H                     | [102b9b2a5b](https://linux-hardware.org/?probe=102b9b2a5b) | Oct 25, 2023 |
| Unknown       | 1.1                         | [4a673ae7d0](https://linux-hardware.org/?probe=4a673ae7d0) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [889bd1ff38](https://linux-hardware.org/?probe=889bd1ff38) | Oct 24, 2023 |
| MSI           | Z87-G43 GAMING              | [31129675c0](https://linux-hardware.org/?probe=31129675c0) | Oct 24, 2023 |
| Gigabyte      | X570 GAMING X               | [78716080bb](https://linux-hardware.org/?probe=78716080bb) | Oct 24, 2023 |
| MSI           | A320M-A PRO                 | [851db330be](https://linux-hardware.org/?probe=851db330be) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| Gigabyte      | H170-D3HP-CF                | [0135013a3b](https://linux-hardware.org/?probe=0135013a3b) | Oct 24, 2023 |
| AZW           | Gemini M                    | [31ec911dd7](https://linux-hardware.org/?probe=31ec911dd7) | Oct 23, 2023 |
| Gigabyte      | MZBSWAP-00                  | [1d274146ba](https://linux-hardware.org/?probe=1d274146ba) | Oct 23, 2023 |
| HP            | 8055                        | [aeee934c45](https://linux-hardware.org/?probe=aeee934c45) | Oct 23, 2023 |
| Biostar       | B450MH                      | [d082b0cf9d](https://linux-hardware.org/?probe=d082b0cf9d) | Oct 23, 2023 |
| Google        | Panther                     | [85ecb9a52b](https://linux-hardware.org/?probe=85ecb9a52b) | Oct 22, 2023 |
| Gigabyte      | B85M-D3H                    | [93e9d3b857](https://linux-hardware.org/?probe=93e9d3b857) | Oct 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [8bc4a56151](https://linux-hardware.org/?probe=8bc4a56151) | Oct 22, 2023 |
| MSI           | B760 GAMING PLUS WIFI       | [817e15f7e6](https://linux-hardware.org/?probe=817e15f7e6) | Oct 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [9908be161f](https://linux-hardware.org/?probe=9908be161f) | Oct 22, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | [6e6e6c3ecf](https://linux-hardware.org/?probe=6e6e6c3ecf) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3eafc2c647](https://linux-hardware.org/?probe=3eafc2c647) | Oct 21, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ec48996f11](https://linux-hardware.org/?probe=ec48996f11) | Oct 21, 2023 |
| Gigabyte      | 990FXA-UD5                  | [98a242f151](https://linux-hardware.org/?probe=98a242f151) | Oct 21, 2023 |
| Gigabyte      | B650 GAMING X AX            | [eb853298f9](https://linux-hardware.org/?probe=eb853298f9) | Oct 21, 2023 |
| ASRock        | H77 Pro4/MVP                | [102735d7e5](https://linux-hardware.org/?probe=102735d7e5) | Oct 21, 2023 |
| Intel         | DH61HO AAG62445-102         | [b2814c5578](https://linux-hardware.org/?probe=b2814c5578) | Oct 21, 2023 |
| Gigabyte      | 970A-DS3P                   | [10fab00c5f](https://linux-hardware.org/?probe=10fab00c5f) | Oct 21, 2023 |
| Gigabyte      | B85M-D3H                    | [5a47896ccd](https://linux-hardware.org/?probe=5a47896ccd) | Oct 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [e8216f74dc](https://linux-hardware.org/?probe=e8216f74dc) | Oct 20, 2023 |
| Shuttle       | FH67                        | [8c36120faa](https://linux-hardware.org/?probe=8c36120faa) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [e02418f8c1](https://linux-hardware.org/?probe=e02418f8c1) | Oct 20, 2023 |
| ASRock        | B550 Pro4                   | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [d7d89d2b1b](https://linux-hardware.org/?probe=d7d89d2b1b) | Oct 19, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| MSI           | H110M PRO-VD                | [d0664cf154](https://linux-hardware.org/?probe=d0664cf154) | Oct 19, 2023 |
| Lenovo        | 3708 NOK                    | [398302b1e5](https://linux-hardware.org/?probe=398302b1e5) | Oct 19, 2023 |
| ASUSTek       | A68HM-K                     | [d8abffeee6](https://linux-hardware.org/?probe=d8abffeee6) | Oct 18, 2023 |
| Gigabyte      | H510M H                     | [a0282a457d](https://linux-hardware.org/?probe=a0282a457d) | Oct 18, 2023 |
| Gigabyte      | G31M-S2L                    | [4d40f6adef](https://linux-hardware.org/?probe=4d40f6adef) | Oct 18, 2023 |
| ASUSTek       | PRIME Z270-P                | [07d65e0ac6](https://linux-hardware.org/?probe=07d65e0ac6) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [fb949d7410](https://linux-hardware.org/?probe=fb949d7410) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8f79e82a3a](https://linux-hardware.org/?probe=8f79e82a3a) | Oct 17, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Acer          | Aspire TC-886 V:2.0         | [808704ebf0](https://linux-hardware.org/?probe=808704ebf0) | Oct 17, 2023 |
| Gigabyte      | Z270-Gaming K3              | [6827d26220](https://linux-hardware.org/?probe=6827d26220) | Oct 17, 2023 |
| ASUSTek       | PRIME H410M-R               | [aa10d84f78](https://linux-hardware.org/?probe=aa10d84f78) | Oct 17, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [da5796de02](https://linux-hardware.org/?probe=da5796de02) | Oct 17, 2023 |
| Gigabyte      | H81M-DS2                    | [9240952796](https://linux-hardware.org/?probe=9240952796) | Oct 16, 2023 |
| MSI           | PRO B660-A DDR4             | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | [bad56db313](https://linux-hardware.org/?probe=bad56db313) | Oct 16, 2023 |
| Dell          | 09KPNV A00                  | [13db34ae64](https://linux-hardware.org/?probe=13db34ae64) | Oct 16, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [6b4ccf6ef7](https://linux-hardware.org/?probe=6b4ccf6ef7) | Oct 15, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [e040ec5e03](https://linux-hardware.org/?probe=e040ec5e03) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| Gigabyte      | B450 AORUS M                | [68075a7e8f](https://linux-hardware.org/?probe=68075a7e8f) | Oct 15, 2023 |
| HP            | 2820h                       | [6b9bbe3a64](https://linux-hardware.org/?probe=6b9bbe3a64) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| ASUSTek       | PRIME Z370-P                | [c8c0c21213](https://linux-hardware.org/?probe=c8c0c21213) | Oct 14, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [3954c51f20](https://linux-hardware.org/?probe=3954c51f20) | Oct 14, 2023 |
| HP            | 2B38                        | [24fb745c2e](https://linux-hardware.org/?probe=24fb745c2e) | Oct 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [0e5e9d0e0f](https://linux-hardware.org/?probe=0e5e9d0e0f) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| ASUSTek       | B75M-PLUS                   | [c1baca90e6](https://linux-hardware.org/?probe=c1baca90e6) | Oct 13, 2023 |
| HP            | 8714                        | [1379aae868](https://linux-hardware.org/?probe=1379aae868) | Oct 13, 2023 |
| Inventec      | D CLASS A02                 | [e978ca79f0](https://linux-hardware.org/?probe=e978ca79f0) | Oct 13, 2023 |
| Gigabyte      | H510M H                     | [f5edac9c7d](https://linux-hardware.org/?probe=f5edac9c7d) | Oct 13, 2023 |
| ASUSTek       | H110M-R                     | [6b5ff499ec](https://linux-hardware.org/?probe=6b5ff499ec) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [5cf8ab4b64](https://linux-hardware.org/?probe=5cf8ab4b64) | Oct 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Dell          | 0200DY A01                  | [4e207b6ab6](https://linux-hardware.org/?probe=4e207b6ab6) | Oct 12, 2023 |
| ASRock        | Z790M-ITX WiFi              | [7f65a85252](https://linux-hardware.org/?probe=7f65a85252) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| Dell          | 0CRH6C A02                  | [865292ecae](https://linux-hardware.org/?probe=865292ecae) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9972c1fc42](https://linux-hardware.org/?probe=9972c1fc42) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| MSI           | X470 GAMING PRO             | [24f5b87752](https://linux-hardware.org/?probe=24f5b87752) | Oct 11, 2023 |
| Dell          | 09CKT0 A03                  | [27c33c2ec5](https://linux-hardware.org/?probe=27c33c2ec5) | Oct 11, 2023 |
| ASUSTek       | B85-PLUS                    | [62e3b0f03f](https://linux-hardware.org/?probe=62e3b0f03f) | Oct 11, 2023 |
| HP            | 8714                        | [ab691c5017](https://linux-hardware.org/?probe=ab691c5017) | Oct 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [f4bae74275](https://linux-hardware.org/?probe=f4bae74275) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [21bc932110](https://linux-hardware.org/?probe=21bc932110) | Oct 10, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [3e2e0d58df](https://linux-hardware.org/?probe=3e2e0d58df) | Oct 10, 2023 |
| Unknown       | Unknown                     | [5e866a9155](https://linux-hardware.org/?probe=5e866a9155) | Oct 10, 2023 |
| Intel         | JSL MRD                     | [52918e7bbc](https://linux-hardware.org/?probe=52918e7bbc) | Oct 10, 2023 |
| Unknown       | Unknown                     | [73219cd20b](https://linux-hardware.org/?probe=73219cd20b) | Oct 10, 2023 |
| ASUSTek       | Z170M-PLUS                  | [dc37b22fc2](https://linux-hardware.org/?probe=dc37b22fc2) | Oct 09, 2023 |
| Centerm       | C32A                        | [8943d70e57](https://linux-hardware.org/?probe=8943d70e57) | Oct 09, 2023 |
| ASUSTek       | P5KPL-AM IN/GB              | [a1db2cd9a7](https://linux-hardware.org/?probe=a1db2cd9a7) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K               | [c21d708813](https://linux-hardware.org/?probe=c21d708813) | Oct 09, 2023 |
| Gigabyte      | G41MT-S2P                   | [3988bb6847](https://linux-hardware.org/?probe=3988bb6847) | Oct 09, 2023 |
| ASRock        | H410M-HVS                   | [bf5a178b35](https://linux-hardware.org/?probe=bf5a178b35) | Oct 09, 2023 |
| Gigabyte      | G31M-ES2L                   | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [94f6dd97ae](https://linux-hardware.org/?probe=94f6dd97ae) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [1756f5ba93](https://linux-hardware.org/?probe=1756f5ba93) | Oct 08, 2023 |
| HP            | 2B29                        | [ce7319c9ca](https://linux-hardware.org/?probe=ce7319c9ca) | Oct 08, 2023 |
| HP            | ProLiant MicroServer        | [1c7c472122](https://linux-hardware.org/?probe=1c7c472122) | Oct 07, 2023 |
| HP            | 0B4Ch D                     | [dfc53e2c91](https://linux-hardware.org/?probe=dfc53e2c91) | Oct 07, 2023 |
| HP            | 2B29                        | [63a83750e6](https://linux-hardware.org/?probe=63a83750e6) | Oct 07, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a5904a1aeb](https://linux-hardware.org/?probe=a5904a1aeb) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| Gigabyte      | B150M-HD3-CF                | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [765a6eb640](https://linux-hardware.org/?probe=765a6eb640) | Oct 07, 2023 |
| AWOW          | AL34                        | [8933a81f53](https://linux-hardware.org/?probe=8933a81f53) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e7cd82de49](https://linux-hardware.org/?probe=e7cd82de49) | Oct 07, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [b838717a3d](https://linux-hardware.org/?probe=b838717a3d) | Oct 07, 2023 |
| HP            | 2B38                        | [da8ed40a89](https://linux-hardware.org/?probe=da8ed40a89) | Oct 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | [096a49de1b](https://linux-hardware.org/?probe=096a49de1b) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16098f839a](https://linux-hardware.org/?probe=16098f839a) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5295ac09d9](https://linux-hardware.org/?probe=5295ac09d9) | Oct 06, 2023 |
| Packard Be... | MCP73PV                     | [dc24306f2f](https://linux-hardware.org/?probe=dc24306f2f) | Oct 05, 2023 |
| Biostar       | B450MH                      | [b47659f758](https://linux-hardware.org/?probe=b47659f758) | Oct 05, 2023 |
| ECS           | H61H2-M13                   | [7a5404c2d6](https://linux-hardware.org/?probe=7a5404c2d6) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | [3f46a7499f](https://linux-hardware.org/?probe=3f46a7499f) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6ff82127e5](https://linux-hardware.org/?probe=6ff82127e5) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8a1928378](https://linux-hardware.org/?probe=b8a1928378) | Oct 04, 2023 |
| ASRock        | X370 Pro4                   | [feb4dbcc8a](https://linux-hardware.org/?probe=feb4dbcc8a) | Oct 04, 2023 |
| Gigabyte      | X570S AERO G                | [5ddc45085a](https://linux-hardware.org/?probe=5ddc45085a) | Oct 04, 2023 |
| AZW           | SEi                         | [84632f00e7](https://linux-hardware.org/?probe=84632f00e7) | Oct 04, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [a74a8b1c25](https://linux-hardware.org/?probe=a74a8b1c25) | Oct 04, 2023 |
| HP            | 8594                        | [320d02db05](https://linux-hardware.org/?probe=320d02db05) | Oct 04, 2023 |
| Unknown       | Unknown                     | [bceb27e642](https://linux-hardware.org/?probe=bceb27e642) | Oct 04, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [30b0594383](https://linux-hardware.org/?probe=30b0594383) | Oct 04, 2023 |
| Gigabyte      | B550M DS3H                  | [6c95b1e3b2](https://linux-hardware.org/?probe=6c95b1e3b2) | Oct 04, 2023 |
| Packard Be... | MCP73PV                     | [2ecd860fef](https://linux-hardware.org/?probe=2ecd860fef) | Oct 03, 2023 |
| Unknown       | Unknown                     | [3493650868](https://linux-hardware.org/?probe=3493650868) | Oct 03, 2023 |
| Gigabyte      | 5MMSV-RHD                   | [ec5e1c9b31](https://linux-hardware.org/?probe=ec5e1c9b31) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c77065abde](https://linux-hardware.org/?probe=c77065abde) | Oct 03, 2023 |
| ECS           | H61H2-M13                   | [df2309fcb0](https://linux-hardware.org/?probe=df2309fcb0) | Oct 03, 2023 |
| Gigabyte      | B85M-D3H                    | [a6aa43cf26](https://linux-hardware.org/?probe=a6aa43cf26) | Oct 03, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [04f08384ff](https://linux-hardware.org/?probe=04f08384ff) | Oct 03, 2023 |
| Gigabyte      | A320M-H-CF                  | [10ebab5a3f](https://linux-hardware.org/?probe=10ebab5a3f) | Oct 02, 2023 |
| ASRock        | X670E Pro RS                | [da95378bd3](https://linux-hardware.org/?probe=da95378bd3) | Oct 02, 2023 |
| HP            | 212B                        | [079a0c34d3](https://linux-hardware.org/?probe=079a0c34d3) | Oct 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [49375c2b21](https://linux-hardware.org/?probe=49375c2b21) | Oct 02, 2023 |
| Dell          | 0NDYHG A01                  | [c84e2b4e06](https://linux-hardware.org/?probe=c84e2b4e06) | Oct 02, 2023 |
| MSI           | MEG Z690I UNIFY             | [660b0653a3](https://linux-hardware.org/?probe=660b0653a3) | Oct 02, 2023 |
| Gigabyte      | 970A-DS3P FX                | [8f0d72cf69](https://linux-hardware.org/?probe=8f0d72cf69) | Oct 01, 2023 |
| Pegatron      | 2ACD                        | [a1babb46d5](https://linux-hardware.org/?probe=a1babb46d5) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [e9ec306962](https://linux-hardware.org/?probe=e9ec306962) | Oct 01, 2023 |
| ASRock        | J4105-ITX                   | [ee4a3e4056](https://linux-hardware.org/?probe=ee4a3e4056) | Oct 01, 2023 |
| HP            | 8055                        | [260bebafcd](https://linux-hardware.org/?probe=260bebafcd) | Oct 01, 2023 |
| HP            | ProLiant MicroServer Gen... | [aeb0b469c8](https://linux-hardware.org/?probe=aeb0b469c8) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| Google        | Jerry                       | [467be71aaf](https://linux-hardware.org/?probe=467be71aaf) | Sep 30, 2023 |
| ASRock        | 4Core1600-GLAN              | [aefbc14017](https://linux-hardware.org/?probe=aefbc14017) | Sep 30, 2023 |
| Lenovo        | 0B98401 PRO                 | [17bb772d78](https://linux-hardware.org/?probe=17bb772d78) | Sep 29, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3473652871](https://linux-hardware.org/?probe=3473652871) | Sep 29, 2023 |
| ASRock        | H81M-HG4                    | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Pegatron      | JESSE                       | [3f6cf71237](https://linux-hardware.org/?probe=3f6cf71237) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| ASRock        | B450 Pro4 R2.0              | [82562e75c3](https://linux-hardware.org/?probe=82562e75c3) | Sep 28, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [89d08f5ea8](https://linux-hardware.org/?probe=89d08f5ea8) | Sep 28, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [576c14796a](https://linux-hardware.org/?probe=576c14796a) | Sep 28, 2023 |
| Shenzhen M... | F7BAA                       | [a59f2cf9f2](https://linux-hardware.org/?probe=a59f2cf9f2) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [47a0a8627c](https://linux-hardware.org/?probe=47a0a8627c) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | [15a7321226](https://linux-hardware.org/?probe=15a7321226) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | [18bf7cff74](https://linux-hardware.org/?probe=18bf7cff74) | Sep 27, 2023 |
| Unknown       | Unknown                     | [2bf5f64c14](https://linux-hardware.org/?probe=2bf5f64c14) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-USB3L              | [f160911c14](https://linux-hardware.org/?probe=f160911c14) | Sep 27, 2023 |
| Lenovo        | 0B98401 PRO                 | [2cdf3dac45](https://linux-hardware.org/?probe=2cdf3dac45) | Sep 27, 2023 |
| YANYU         | H17SL                       | [5966ae64d0](https://linux-hardware.org/?probe=5966ae64d0) | Sep 26, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [64dcffc72f](https://linux-hardware.org/?probe=64dcffc72f) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS440           | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| Intel         | DP35DP AAD81073-206         | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [19858af3cd](https://linux-hardware.org/?probe=19858af3cd) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| MSI           | MS-7318                     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [14c3077129](https://linux-hardware.org/?probe=14c3077129) | Sep 24, 2023 |
| MSI           | Z370-A PRO                  | [77c3039fdc](https://linux-hardware.org/?probe=77c3039fdc) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Gigabyte      | B85M-D3H                    | [e568bc8439](https://linux-hardware.org/?probe=e568bc8439) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e96b971928](https://linux-hardware.org/?probe=e96b971928) | Sep 23, 2023 |
| Dell          | 0NW6H5 A00                  | [c3221c93ca](https://linux-hardware.org/?probe=c3221c93ca) | Sep 23, 2023 |
| HP            | 1905                        | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| Dell          | 0PC5F7 A01                  | [887558c8f3](https://linux-hardware.org/?probe=887558c8f3) | Sep 23, 2023 |
| Dell          | 03KWTV A02                  | [991ec32c75](https://linux-hardware.org/?probe=991ec32c75) | Sep 23, 2023 |
| Gigabyte      | B250M-Gaming5-CF            | [f18f8ef020](https://linux-hardware.org/?probe=f18f8ef020) | Sep 23, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [b402f89894](https://linux-hardware.org/?probe=b402f89894) | Sep 22, 2023 |
| Shenzhen M... | F6BFC                       | [9a906f1b75](https://linux-hardware.org/?probe=9a906f1b75) | Sep 22, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| MSI           | X470 GAMING PLUS            | [d22a656bef](https://linux-hardware.org/?probe=d22a656bef) | Sep 22, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [2137a7a54b](https://linux-hardware.org/?probe=2137a7a54b) | Sep 22, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| ASUSTek       | P7P55D                      | [ff8d00073e](https://linux-hardware.org/?probe=ff8d00073e) | Sep 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [f870f9e3ac](https://linux-hardware.org/?probe=f870f9e3ac) | Sep 21, 2023 |
| MSI           | MS-7318                     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS PRO              | [81d1af1a96](https://linux-hardware.org/?probe=81d1af1a96) | Sep 20, 2023 |
| NetGear       | ReadyDATA 5200              | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | [0c99fa225e](https://linux-hardware.org/?probe=0c99fa225e) | Sep 20, 2023 |
| iEi           | SAT3 V1.03                  | [d303736416](https://linux-hardware.org/?probe=d303736416) | Sep 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| CWWK          | MINIPC-G12                  | [003a19cc19](https://linux-hardware.org/?probe=003a19cc19) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | [6ded2501bf](https://linux-hardware.org/?probe=6ded2501bf) | Sep 20, 2023 |
| BESSTAR Te... | HM90                        | [bbb35ce98b](https://linux-hardware.org/?probe=bbb35ce98b) | Sep 20, 2023 |
| ASRock        | X399 Taichi                 | [ff02c716c1](https://linux-hardware.org/?probe=ff02c716c1) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d9002e7e3](https://linux-hardware.org/?probe=6d9002e7e3) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c53d44303e](https://linux-hardware.org/?probe=c53d44303e) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| Gigabyte      | H81M-DS2                    | [85d35b008d](https://linux-hardware.org/?probe=85d35b008d) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | [03da63d741](https://linux-hardware.org/?probe=03da63d741) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [b06b302844](https://linux-hardware.org/?probe=b06b302844) | Sep 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [0ddcc2944f](https://linux-hardware.org/?probe=0ddcc2944f) | Sep 19, 2023 |
| ASRock        | B550 Pro4                   | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| HP            | 82A2                        | [cc179a17a8](https://linux-hardware.org/?probe=cc179a17a8) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a64dc1766a](https://linux-hardware.org/?probe=a64dc1766a) | Sep 18, 2023 |
| MSI           | MS-7366                     | [96731b6fc6](https://linux-hardware.org/?probe=96731b6fc6) | Sep 18, 2023 |
| ASUSTek       | J1800I-C                    | [970e148d8d](https://linux-hardware.org/?probe=970e148d8d) | Sep 18, 2023 |
| MSI           | H81M-P33                    | [d0287bbd0f](https://linux-hardware.org/?probe=d0287bbd0f) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [3faff3c0aa](https://linux-hardware.org/?probe=3faff3c0aa) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [cfa7fbd3fe](https://linux-hardware.org/?probe=cfa7fbd3fe) | Sep 18, 2023 |
| MSI           | X79A-GD45                   | [85a9bad81b](https://linux-hardware.org/?probe=85a9bad81b) | Sep 17, 2023 |
| AZW           | U59                         | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Gigabyte      | H97-HD3                     | [ac1361d323](https://linux-hardware.org/?probe=ac1361d323) | Sep 17, 2023 |
| Supermicro    | X9DR3-F                     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| HP            | 1905                        | [688c5ddf16](https://linux-hardware.org/?probe=688c5ddf16) | Sep 17, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [b07ec8f845](https://linux-hardware.org/?probe=b07ec8f845) | Sep 17, 2023 |
| HP            | 1905                        | [562179ca0e](https://linux-hardware.org/?probe=562179ca0e) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| MSI           | B460M-A PRO                 | [b2d52a5d1c](https://linux-hardware.org/?probe=b2d52a5d1c) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6a908941cd](https://linux-hardware.org/?probe=6a908941cd) | Sep 16, 2023 |
| ASRock        | B450M Pro4                  | [3974827c3e](https://linux-hardware.org/?probe=3974827c3e) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [effa0104c0](https://linux-hardware.org/?probe=effa0104c0) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [72ec01815f](https://linux-hardware.org/?probe=72ec01815f) | Sep 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [923d176004](https://linux-hardware.org/?probe=923d176004) | Sep 15, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [caba916cf4](https://linux-hardware.org/?probe=caba916cf4) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [2f12035902](https://linux-hardware.org/?probe=2f12035902) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [c46a08bb48](https://linux-hardware.org/?probe=c46a08bb48) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [aa351597ea](https://linux-hardware.org/?probe=aa351597ea) | Sep 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | [e9d6d94486](https://linux-hardware.org/?probe=e9d6d94486) | Sep 15, 2023 |
| JINGSHA       | X99-D8I                     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | PRIME H510M-A               | [b66654e80e](https://linux-hardware.org/?probe=b66654e80e) | Sep 14, 2023 |
| ASUSTek       | P8H61/USB3                  | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [5923e88c3b](https://linux-hardware.org/?probe=5923e88c3b) | Sep 13, 2023 |
| SolidRun      | CEX7 Platform               | [2a695cf7f9](https://linux-hardware.org/?probe=2a695cf7f9) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [f6bc099f62](https://linux-hardware.org/?probe=f6bc099f62) | Sep 13, 2023 |
| SolidRun      | CEX7 Platform               | [06b4774756](https://linux-hardware.org/?probe=06b4774756) | Sep 13, 2023 |
| ASUSTek       | H110M-R                     | [3530c6e606](https://linux-hardware.org/?probe=3530c6e606) | Sep 13, 2023 |
| Supermicro    | X11SSH-F                    | [3a9630bdc5](https://linux-hardware.org/?probe=3a9630bdc5) | Sep 13, 2023 |
| Dell          | 01XK1W A00                  | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Gigabyte      | H110M-H-CF                  | [31cc220aae](https://linux-hardware.org/?probe=31cc220aae) | Sep 12, 2023 |
| Dell          | 02N3WF A01                  | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| MSI           | PRO B760M-A WIFI            | [87577c165a](https://linux-hardware.org/?probe=87577c165a) | Sep 12, 2023 |
| ASUSTek       | H110M-K                     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| MSI           | H510M-A PRO                 | [f1a2a6d936](https://linux-hardware.org/?probe=f1a2a6d936) | Sep 12, 2023 |
| Gigabyte      | GA-870A-UD3                 | [b3acd03fb0](https://linux-hardware.org/?probe=b3acd03fb0) | Sep 12, 2023 |
| Dell          | 0GM819                      | [9917a9587a](https://linux-hardware.org/?probe=9917a9587a) | Sep 12, 2023 |
| ASRock        | B560M-HDV                   | [4df04c540a](https://linux-hardware.org/?probe=4df04c540a) | Sep 11, 2023 |
| Gigabyte      | M68MT-S2                    | [cb129260e1](https://linux-hardware.org/?probe=cb129260e1) | Sep 11, 2023 |
| ECS           | G31T-M9                     | [9d2ba7fe88](https://linux-hardware.org/?probe=9d2ba7fe88) | Sep 11, 2023 |
| Gigabyte      | GA-M56S-S3                  | [df2602c134](https://linux-hardware.org/?probe=df2602c134) | Sep 11, 2023 |
| Gigabyte      | P85-D3                      | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | MS-B9091                    | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7d22cd1af1](https://linux-hardware.org/?probe=7d22cd1af1) | Sep 11, 2023 |
| HP            | 8643 SMVB                   | [867d0c64be](https://linux-hardware.org/?probe=867d0c64be) | Sep 11, 2023 |
| MSI           | 970A-G46                    | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [6db516900f](https://linux-hardware.org/?probe=6db516900f) | Sep 10, 2023 |
| ASRock        | H81M-HG4                    | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| MSI           | Z370-A PRO                  | [b23d13eddc](https://linux-hardware.org/?probe=b23d13eddc) | Sep 10, 2023 |
| HP            | 876C SMVB                   | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| Shenzhen M... | HX90G                       | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| ASUSTek       | TS10                        | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| MSI           | B350 TOMAHAWK               | [2a7d4dfb14](https://linux-hardware.org/?probe=2a7d4dfb14) | Sep 09, 2023 |
| Gigabyte      | B85M-D3H                    | [9e26f5a8d3](https://linux-hardware.org/?probe=9e26f5a8d3) | Sep 09, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [b3957e19eb](https://linux-hardware.org/?probe=b3957e19eb) | Sep 09, 2023 |
| AZW           | U59                         | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| ASRock        | J3455-ITX                   | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| MSI           | MS-B9091                    | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e9fc2a82f](https://linux-hardware.org/?probe=5e9fc2a82f) | Sep 09, 2023 |
| ASRock        | AB350 Gaming-ITX/ac         | [a4e0bc39ba](https://linux-hardware.org/?probe=a4e0bc39ba) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | [9b24a3d874](https://linux-hardware.org/?probe=9b24a3d874) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| MSI           | MS-B1711                    | [4c68221aae](https://linux-hardware.org/?probe=4c68221aae) | Sep 08, 2023 |
| HP            | 83E0                        | [44faaa5738](https://linux-hardware.org/?probe=44faaa5738) | Sep 08, 2023 |
| Acer          | Veriton M2632G V:1.0        | [a0363f72e3](https://linux-hardware.org/?probe=a0363f72e3) | Sep 08, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e30ef028b9](https://linux-hardware.org/?probe=e30ef028b9) | Sep 08, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [69c2d2f0d0](https://linux-hardware.org/?probe=69c2d2f0d0) | Sep 08, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [8a5a4accb2](https://linux-hardware.org/?probe=8a5a4accb2) | Sep 08, 2023 |
| Gigabyte      | H610M H DDR4                | [72516e7752](https://linux-hardware.org/?probe=72516e7752) | Sep 07, 2023 |
| Intel         | HM570                       | [ea25bde02e](https://linux-hardware.org/?probe=ea25bde02e) | Sep 07, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [7684d60e85](https://linux-hardware.org/?probe=7684d60e85) | Sep 07, 2023 |
| Gigabyte      | Z790 UD                     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [a97cdf671b](https://linux-hardware.org/?probe=a97cdf671b) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [5a4f7a4641](https://linux-hardware.org/?probe=5a4f7a4641) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [6c90c83d67](https://linux-hardware.org/?probe=6c90c83d67) | Sep 04, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| HP            | 1825                        | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9259a8f3f3](https://linux-hardware.org/?probe=9259a8f3f3) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [91d7a53a1b](https://linux-hardware.org/?probe=91d7a53a1b) | Sep 01, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Unknown       | Unknown                     | [3e3433226b](https://linux-hardware.org/?probe=3e3433226b) | Sep 01, 2023 |
| Dell          | 0GM819                      | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| HP            | 1495                        | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| Gigabyte      | X570S AERO G                | [f367356391](https://linux-hardware.org/?probe=f367356391) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| Intel         | DG41TY AAE47335-301         | [1f8897e1a2](https://linux-hardware.org/?probe=1f8897e1a2) | Aug 29, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 82A2                        | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [89e3ba3d7d](https://linux-hardware.org/?probe=89e3ba3d7d) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0150e826ac](https://linux-hardware.org/?probe=0150e826ac) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| ASUSTek       | Z170-A                      | [eadbc95dc7](https://linux-hardware.org/?probe=eadbc95dc7) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [3add2f8945](https://linux-hardware.org/?probe=3add2f8945) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| HP            | 158A                        | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Unknown       | Unknown                     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| MSI           | MAG B560 TORPEDO            | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acc3f87d28](https://linux-hardware.org/?probe=acc3f87d28) | Aug 23, 2023 |
| ASRock        | FM2A68M-HD+                 | [6811a2231b](https://linux-hardware.org/?probe=6811a2231b) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [5663c30e5e](https://linux-hardware.org/?probe=5663c30e5e) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [5a9553b9a2](https://linux-hardware.org/?probe=5a9553b9a2) | Aug 22, 2023 |
| Supermicro    | H12SSL-i                    | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| ASRock        | J4125B-ITX                  | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Inspur        | H110H4-EM                   | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| Unknown       | Unknown                     | [4d4fcc02f3](https://linux-hardware.org/?probe=4d4fcc02f3) | Aug 21, 2023 |
| Dell          | 06X1TJ A00                  | [85ba56b138](https://linux-hardware.org/?probe=85ba56b138) | Aug 20, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| MSI           | B450M BAZOOKA               | [569655b0f2](https://linux-hardware.org/?probe=569655b0f2) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [8b6ec2d9e2](https://linux-hardware.org/?probe=8b6ec2d9e2) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| MSI           | KA790GX-M                   | [050157c33b](https://linux-hardware.org/?probe=050157c33b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [cf83ce90b0](https://linux-hardware.org/?probe=cf83ce90b0) | Aug 19, 2023 |
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Dell          | 06X1TJ A00                  | [9580f6451c](https://linux-hardware.org/?probe=9580f6451c) | Aug 19, 2023 |
| HP            | 8266                        | [22a06599a1](https://linux-hardware.org/?probe=22a06599a1) | Aug 19, 2023 |
| Dell          | 0PU052                      | [2b5816a194](https://linux-hardware.org/?probe=2b5816a194) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| HP            | 3047h                       | [a6a9afac2a](https://linux-hardware.org/?probe=a6a9afac2a) | Aug 18, 2023 |
| HP            | 3047h                       | [762697d775](https://linux-hardware.org/?probe=762697d775) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5f5f5280d8](https://linux-hardware.org/?probe=5f5f5280d8) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ASUSTek       | CM1630                      | [c1fd29e307](https://linux-hardware.org/?probe=c1fd29e307) | Aug 18, 2023 |
| Intel         | X99H                        | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [1742c682fc](https://linux-hardware.org/?probe=1742c682fc) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| Lenovo        | 1036 NO DPK                 | [61eb0b10f6](https://linux-hardware.org/?probe=61eb0b10f6) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a247bcbeb2](https://linux-hardware.org/?probe=a247bcbeb2) | Aug 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [780b9a9e3a](https://linux-hardware.org/?probe=780b9a9e3a) | Aug 15, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [48ae062db8](https://linux-hardware.org/?probe=48ae062db8) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS            | [5297d177b4](https://linux-hardware.org/?probe=5297d177b4) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Dell          | 0CT017                      | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Unknown       | Unknown                     | [14114ca4aa](https://linux-hardware.org/?probe=14114ca4aa) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Unknown       | Unknown                     | [946d81eb9d](https://linux-hardware.org/?probe=946d81eb9d) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Foxconn       | 2ADA                        | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| Biostar       | B365MHC                     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| ASRock        | FM2A68M-DG3+                | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Lenovo        | 1036 NO DPK                 | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Intel         | H61                         | [7b2774c1a1](https://linux-hardware.org/?probe=7b2774c1a1) | Aug 03, 2023 |
| Intel         | H61                         | [8d450f7e6e](https://linux-hardware.org/?probe=8d450f7e6e) | Aug 03, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H V2               | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| ASUSTek       | Z170-A                      | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54462345a7](https://linux-hardware.org/?probe=54462345a7) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | H97M-PLUS                   | [940e14c90d](https://linux-hardware.org/?probe=940e14c90d) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Unknown       | Unknown                     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [37e282ff80](https://linux-hardware.org/?probe=37e282ff80) | Jul 30, 2023 |
| ASRockRack    | X470D4U                     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | [d9c029afa4](https://linux-hardware.org/?probe=d9c029afa4) | Jul 28, 2023 |
| Dell          | 06X1TJ A00                  | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Intel         | X99H                        | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| ASRock        | N68C-GS FX                  | [6b35cdc0ae](https://linux-hardware.org/?probe=6b35cdc0ae) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| Lenovo        | 1036 NO DPK                 | [725aae77c4](https://linux-hardware.org/?probe=725aae77c4) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| MSI           | Z77A-GD65                   | [4df7cd69af](https://linux-hardware.org/?probe=4df7cd69af) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Dell          | 0KWVT8 A03                  | [77fd7def41](https://linux-hardware.org/?probe=77fd7def41) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| ASRock        | B550M Steel Legend          | [6e0eb8c7f5](https://linux-hardware.org/?probe=6e0eb8c7f5) | Jul 19, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Unknown       | Unknown                     | [32816fb789](https://linux-hardware.org/?probe=32816fb789) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| Unknown       | Unknown                     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| MSI           | 2A9C                        | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| MSI           | H81M-P33                    | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| Biostar       | B450MH                      | [22909715b3](https://linux-hardware.org/?probe=22909715b3) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Unknown       | Unknown                     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Unknown       | Unknown                     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| MSI           | MAG B550M MORTAR            | [74239bf89d](https://linux-hardware.org/?probe=74239bf89d) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Google        | Guado                       | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| ASRock        | B550M Steel Legend          | [c353f8ceea](https://linux-hardware.org/?probe=c353f8ceea) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| MSI           | H170M PRO-VDH               | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| MSI           | MAG B550M MORTAR            | [b9ff94a143](https://linux-hardware.org/?probe=b9ff94a143) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Apple         | Mac-F221BEC8                | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [eda9b7d2e8](https://linux-hardware.org/?probe=eda9b7d2e8) | Jul 10, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 09KPNV A01                  | [596389ea27](https://linux-hardware.org/?probe=596389ea27) | Jul 10, 2023 |
| HP            | 2B38                        | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| AZW           | U59                         | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| AZW           | MINI S                      | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| ASRock        | B550 Taichi Razer Editio... | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e177e22bff](https://linux-hardware.org/?probe=e177e22bff) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Gigabyte      | H61M-DS2                    | [b0c1a875c3](https://linux-hardware.org/?probe=b0c1a875c3) | Jul 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d58bb46843](https://linux-hardware.org/?probe=d58bb46843) | Jul 05, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| MSI           | MAG B560 TORPEDO            | [1327fb98ac](https://linux-hardware.org/?probe=1327fb98ac) | Jul 04, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| Lenovo        | 3706 SDK0J40697 WIN 3305... | [35e0dd6624](https://linux-hardware.org/?probe=35e0dd6624) | Jul 03, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| ASUSTek       | Z87-A                       | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| ASRock        | B450 Pro4                   | [304cab93f1](https://linux-hardware.org/?probe=304cab93f1) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Shuttle       | FS61                        | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| OEM           | Unknown                     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| AMI           | Cherry Trail CR             | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| Dell          | 0PU052                      | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| Biostar       | X370GTN                     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Biostar       | TH55B HD                    | [5fbef8b11a](https://linux-hardware.org/?probe=5fbef8b11a) | Jun 25, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASUSTek       | K30BF_M32BF                 | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| HP            | 3397                        | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| Acer          | Aspire X1700                | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| HP            | 1998                        | [efcccef24e](https://linux-hardware.org/?probe=efcccef24e) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1998                        | [71bee9f013](https://linux-hardware.org/?probe=71bee9f013) | Jun 21, 2023 |
| HP            | 1588h                       | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| ASRock        | X570 Extreme4               | [3ff2c9e4cc](https://linux-hardware.org/?probe=3ff2c9e4cc) | Jun 21, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| MSI           | H81M-P33                    | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0CRH6C A02                  | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| Dell          | 0PU052                      | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| MSI           | B350M MORTAR                | [dde719cb99](https://linux-hardware.org/?probe=dde719cb99) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Intel         | H81                         | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| AZW           | U59                         | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | 2B38                        | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [d10c160695](https://linux-hardware.org/?probe=d10c160695) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | 1589                        | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| HP            | 2820h                       | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 2504     | 54.25%  |
| Debian 10               | 751      | 16.27%  |
| Debian 12               | 686      | 14.86%  |
| Debian Testing          | 231      | 5%      |
| Debian 9                | 148      | 3.21%   |
| Debian                  | 129      | 2.79%   |
| Debian Unstable         | 116      | 2.51%   |
| Debian 8                | 25       | 0.54%   |
| Debian 11-updates       | 16       | 0.35%   |
| Debian 7                | 5        | 0.11%   |
| Debian Testing/unstable | 2        | 0.04%   |
| Debian Sid              | 1        | 0.02%   |
| Debian 6                | 1        | 0.02%   |
| Debian 23               | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 4392     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.0-7-amd64       | 513      | 10.23%  |
| 5.10.0-8-amd64       | 240      | 4.78%   |
| 5.10.0-21-amd64      | 180      | 3.59%   |
| 6.1.0-4-amd64        | 152      | 3.03%   |
| 5.10.0-9-amd64       | 123      | 2.45%   |
| 5.10.0-2-amd64       | 118      | 2.35%   |
| 5.10.0-19-amd64      | 104      | 2.07%   |
| 5.10.0-20-amd64      | 103      | 2.05%   |
| 6.1.0-9-amd64        | 97       | 1.93%   |
| 6.1.0-10-amd64       | 91       | 1.81%   |
| 5.10.0-23-amd64      | 91       | 1.81%   |
| 5.10.0-13-amd64      | 87       | 1.73%   |
| 6.1.0-13-amd64       | 85       | 1.69%   |
| 5.10.0-18-amd64      | 83       | 1.65%   |
| 5.10.0-10-amd64      | 74       | 1.48%   |
| 5.10.0-11-amd64      | 73       | 1.46%   |
| 5.10.0-16-amd64      | 69       | 1.38%   |
| 6.1.0-11-amd64       | 66       | 1.32%   |
| 6.1.0-12-amd64       | 60       | 1.2%    |
| 4.19.0-6-amd64       | 56       | 1.12%   |
| 4.19.0-16-amd64      | 52       | 1.04%   |
| 4.19.0-14-amd64      | 52       | 1.04%   |
| 5.10.0-14-amd64      | 50       | 1%      |
| 4.19.0-13-amd64      | 50       | 1%      |
| 4.19.0-9-amd64       | 48       | 0.96%   |
| 4.19.0-17-amd64      | 48       | 0.96%   |
| 4.19.0-8-amd64       | 47       | 0.94%   |
| 5.10.0-17-amd64      | 43       | 0.86%   |
| 5.10.0-15-amd64      | 43       | 0.86%   |
| 5.10.0-22-amd64      | 42       | 0.84%   |
| 4.19.0-12-amd64      | 38       | 0.76%   |
| 5.15.0-2-amd64       | 37       | 0.74%   |
| 4.19.0-10-amd64      | 34       | 0.68%   |
| 4.9.0-8-amd64        | 31       | 0.62%   |
| 6.1.0-7-amd64        | 30       | 0.6%    |
| 5.10.0-12-amd64      | 29       | 0.58%   |
| 5.6.0-2-amd64        | 28       | 0.56%   |
| 6.0.0-6-amd64        | 20       | 0.4%    |
| 5.18.0-2-amd64       | 20       | 0.4%    |
| 5.16.0-0.bpo.4-amd64 | 20       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2138     | 44.69%  |
| 6.1.0    | 650      | 13.59%  |
| 4.19.0   | 521      | 10.89%  |
| 4.9.0    | 110      | 2.3%    |
| 6.0.0    | 93       | 1.94%   |
| 5.18.0   | 79       | 1.65%   |
| 5.9.0    | 59       | 1.23%   |
| 5.16.0   | 59       | 1.23%   |
| 5.15.0   | 57       | 1.19%   |
| 5.8.0    | 55       | 1.15%   |
| 5.7.0    | 54       | 1.13%   |
| 5.6.0    | 48       | 1%      |
| 5.4.0    | 45       | 0.94%   |
| 5.13.19  | 44       | 0.92%   |
| 5.19.0   | 41       | 0.86%   |
| 6.2.16   | 36       | 0.75%   |
| 6.4.0    | 33       | 0.69%   |
| 5.14.0   | 33       | 0.69%   |
| 5.17.0   | 25       | 0.52%   |
| 6.5.0    | 22       | 0.46%   |
| 5.15.107 | 19       | 0.4%    |
| 5.15.102 | 19       | 0.4%    |
| 5.11.22  | 19       | 0.4%    |
| 6.3.0    | 18       | 0.38%   |
| 5.3.0    | 18       | 0.38%   |
| 5.15.74  | 15       | 0.31%   |
| 5.5.0    | 14       | 0.29%   |
| 5.15.83  | 14       | 0.29%   |
| 5.15.39  | 13       | 0.27%   |
| 5.15.35  | 13       | 0.27%   |
| 5.15.85  | 12       | 0.25%   |
| 5.15.30  | 11       | 0.23%   |
| 5.15.53  | 10       | 0.21%   |
| 3.16.0   | 10       | 0.21%   |
| 5.4.106  | 9        | 0.19%   |
| 5.15.108 | 9        | 0.19%   |
| 4.18.0   | 9        | 0.19%   |
| 5.2.0    | 8        | 0.17%   |
| 5.15.104 | 8        | 0.17%   |
| 5.4.44   | 7        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2170     | 45.65%  |
| 6.1     | 667      | 14.03%  |
| 4.19    | 532      | 11.19%  |
| 5.15    | 209      | 4.4%    |
| 4.9     | 116      | 2.44%   |
| 6.0     | 105      | 2.21%   |
| 5.4     | 98       | 2.06%   |
| 5.18    | 84       | 1.77%   |
| 5.16    | 64       | 1.35%   |
| 5.9     | 62       | 1.3%    |
| 5.8     | 61       | 1.28%   |
| 5.7     | 58       | 1.22%   |
| 6.2     | 54       | 1.14%   |
| 5.13    | 54       | 1.14%   |
| 5.6     | 52       | 1.09%   |
| 5.19    | 49       | 1.03%   |
| 6.4     | 42       | 0.88%   |
| 5.14    | 36       | 0.76%   |
| 5.11    | 31       | 0.65%   |
| 5.3     | 30       | 0.63%   |
| 5.17    | 29       | 0.61%   |
| 6.5     | 26       | 0.55%   |
| 6.3     | 22       | 0.46%   |
| 5.5     | 17       | 0.36%   |
| 4.15    | 11       | 0.23%   |
| 4.18    | 10       | 0.21%   |
| 3.16    | 10       | 0.21%   |
| 5.2     | 8        | 0.17%   |
| 5.0     | 8        | 0.17%   |
| 4.1     | 7        | 0.15%   |
| 4.17    | 5        | 0.11%   |
| 5.12    | 3        | 0.06%   |
| 5.1     | 3        | 0.06%   |
| 4.16    | 3        | 0.06%   |
| 4.20    | 2        | 0.04%   |
| 4.14    | 2        | 0.04%   |
| 4.13    | 2        | 0.04%   |
| 2.6     | 2        | 0.04%   |
| 96.5    | 1        | 0.02%   |
| 6.6     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 4261     | 97%     |
| i686        | 97       | 2.21%   |
| armv7l      | 8        | 0.18%   |
| ppc64       | 7        | 0.16%   |
| riscv64     | 6        | 0.14%   |
| aarch64     | 3        | 0.07%   |
| ppc64le     | 2        | 0.05%   |
| mips64      | 2        | 0.05%   |
| loongarch64 | 2        | 0.05%   |
| i586        | 2        | 0.05%   |
| sparc64     | 1        | 0.02%   |
| sh4a        | 1        | 0.02%   |
| armv6l      | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1586     | 35.3%   |
| GNOME             | 876      | 19.5%   |
| KDE5              | 554      | 12.33%  |
| XFCE              | 528      | 11.75%  |
| MATE              | 217      | 4.83%   |
| X-Cinnamon        | 167      | 3.72%   |
| Cinnamon          | 113      | 2.52%   |
| LXDE              | 112      | 2.49%   |
| KDE               | 79       | 1.76%   |
| LXQt              | 74       | 1.65%   |
| i3                | 37       | 0.82%   |
| openbox           | 34       | 0.76%   |
| GNOME Flashback   | 23       | 0.51%   |
| lightdm-xsession  | 18       | 0.4%    |
| Trinity           | 15       | 0.33%   |
| Budgie            | 15       | 0.33%   |
| GNOME Classic     | 14       | 0.31%   |
| awesome           | 5        | 0.11%   |
| sway              | 4        | 0.09%   |
| KDE4              | 4        | 0.09%   |
| fluxbox           | 4        | 0.09%   |
| Enlightenment     | 2        | 0.04%   |
| dwm               | 2        | 0.04%   |
| xmonad            | 1        | 0.02%   |
| x-session-manager | 1        | 0.02%   |
| UKUI              | 1        | 0.02%   |
| i3-with-shmlog    | 1        | 0.02%   |
| GNUstep           | 1        | 0.02%   |
| gnome-xorg        | 1        | 0.02%   |
| e16-session       | 1        | 0.02%   |
| default           | 1        | 0.02%   |
| Cutefish          | 1        | 0.02%   |
| /etc/X11/Xsession | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 2326     | 51.97%  |
| Unknown     | 943      | 21.07%  |
| Tty         | 678      | 15.15%  |
| Wayland     | 524      | 11.71%  |
| Web         | 3        | 0.07%   |
| Unspecified | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2259     | 50.4%   |
| LightDM | 708      | 15.8%   |
| SDDM    | 499      | 11.13%  |
| GDM     | 498      | 11.11%  |
| TDM     | 250      | 5.58%   |
| GDM3    | 210      | 4.69%   |
| SLiM    | 17       | 0.38%   |
| XDM     | 16       | 0.36%   |
| NODM    | 9        | 0.2%    |
| LXDM    | 5        | 0.11%   |
| KDM     | 5        | 0.11%   |
| WDM     | 3        | 0.07%   |
| Ly      | 2        | 0.04%   |
| SU      | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1550     | 34.85%  |
| ru_RU   | 865      | 19.45%  |
| Unknown | 306      | 6.88%   |
| de_DE   | 269      | 6.05%   |
| fr_FR   | 207      | 4.65%   |
| en_GB   | 205      | 4.61%   |
| pt_BR   | 136      | 3.06%   |
| es_ES   | 126      | 2.83%   |
| it_IT   | 93       | 2.09%   |
| en_CA   | 71       | 1.6%    |
| C       | 64       | 1.44%   |
| en_AU   | 62       | 1.39%   |
| pl_PL   | 44       | 0.99%   |
| es_AR   | 25       | 0.56%   |
| en_IN   | 24       | 0.54%   |
| zh_CN   | 23       | 0.52%   |
| hu_HU   | 23       | 0.52%   |
| en_IE   | 22       | 0.49%   |
| es_MX   | 19       | 0.43%   |
| es_VE   | 18       | 0.4%    |
| de_AT   | 18       | 0.4%    |
| ja_JP   | 17       | 0.38%   |
| en_ZA   | 17       | 0.38%   |
| nl_BE   | 14       | 0.31%   |
| nl_NL   | 13       | 0.29%   |
| pt_PT   | 12       | 0.27%   |
| cs_CZ   | 11       | 0.25%   |
| de_CH   | 10       | 0.22%   |
| fr_BE   | 9        | 0.2%    |
| es_CL   | 9        | 0.2%    |
| en_NZ   | 9        | 0.2%    |
| sv_SE   | 8        | 0.18%   |
| fi_FI   | 8        | 0.18%   |
| en_DK   | 7        | 0.16%   |
| ca_ES   | 7        | 0.16%   |
| ru_UA   | 6        | 0.13%   |
| es_PE   | 6        | 0.13%   |
| en_HK   | 6        | 0.13%   |
| el_GR   | 6        | 0.13%   |
| uk_UA   | 5        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2720     | 61.03%  |
| EFI  | 1737     | 38.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 3098     | 69.7%   |
| Overlay    | 813      | 18.29%  |
| Btrfs      | 188      | 4.23%   |
| Zfs        | 113      | 2.54%   |
| Unknown    | 82       | 1.84%   |
| Xfs        | 71       | 1.6%    |
| Ext3       | 25       | 0.56%   |
| Tmpfs      | 24       | 0.54%   |
| Ext2       | 10       | 0.22%   |
| Rootfs     | 8        | 0.18%   |
| Aufs       | 4        | 0.09%   |
| F2fs       | 3        | 0.07%   |
| XXXXXXX    | 2        | 0.04%   |
| Jfs        | 2        | 0.04%   |
| XXXXX      | 1        | 0.02%   |
| Fuse.sshfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 2173     | 48.49%  |
| MBR     | 1436     | 32.05%  |
| Unknown | 872      | 19.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3574     | 80.24%  |
| Yes       | 880      | 19.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2786     | 62.75%  |
| Yes       | 1654     | 37.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1174     | 26.73%  |
| Gigabyte Technology                  | 737      | 16.78%  |
| MSI                                  | 463      | 10.54%  |
| ASRock                               | 429      | 9.77%   |
| Dell                                 | 287      | 6.53%   |
| Hewlett-Packard                      | 268      | 6.1%    |
| Lenovo                               | 144      | 3.28%   |
| Intel                                | 138      | 3.14%   |
| Unknown                              | 102      | 2.32%   |
| ECS                                  | 59       | 1.34%   |
| Fujitsu                              | 52       | 1.18%   |
| Foxconn                              | 43       | 0.98%   |
| AZW                                  | 41       | 0.93%   |
| Supermicro                           | 40       | 0.91%   |
| Acer                                 | 38       | 0.87%   |
| ASRockRack                           | 36       | 0.82%   |
| Biostar                              | 27       | 0.61%   |
| Pegatron                             | 25       | 0.57%   |
| Huanan                               | 16       | 0.36%   |
| Shuttle                              | 15       | 0.34%   |
| Apple                                | 14       | 0.32%   |
| Inventec                             | 13       | 0.3%    |
| BESSTAR Tech                         | 12       | 0.27%   |
| Google                               | 11       | 0.25%   |
| Fujitsu Siemens                      | 11       | 0.25%   |
| Positivo                             | 10       | 0.23%   |
| Medion                               | 10       | 0.23%   |
| Shenzhen Meigao Electronic Equipment | 9        | 0.2%    |
| IceWhale Technology                  | 6        | 0.14%   |
| Packard Bell                         | 5        | 0.11%   |
| Hardkernel                           | 5        | 0.11%   |
| AMI                                  | 5        | 0.11%   |
| Techvision                           | 4        | 0.09%   |
| PCWare                               | 4        | 0.09%   |
| Gateway                              | 4        | 0.09%   |
| Alienware                            | 4        | 0.09%   |
| YANYU                                | 3        | 0.07%   |
| Wistron                              | 3        | 0.07%   |
| PC Engines                           | 3        | 0.07%   |
| OEM                                  | 3        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 137      | 3.12%   |
| Unknown                           | 109      | 2.48%   |
| ASUS S20 K29                      | 55       | 1.25%   |
| MSI MS-7996                       | 45       | 1.02%   |
| MSI MS-7817                       | 27       | 0.61%   |
| ECS G31T-M9                       | 25       | 0.57%   |
| Gigabyte H81M-S2V                 | 24       | 0.55%   |
| Dell OptiPlex 7010                | 20       | 0.46%   |
| ASUS PRIME H510M-A                | 20       | 0.46%   |
| ASRock H470M-HVS                  | 20       | 0.46%   |
| Gigabyte B450M DS3H               | 18       | 0.41%   |
| ASUS TUF Gaming X570-PLUS         | 18       | 0.41%   |
| ECS H61H2-M13                     | 17       | 0.39%   |
| ASUS PRIME A320M-K                | 17       | 0.39%   |
| Gigabyte H410M S2H                | 16       | 0.36%   |
| ASUS P8H61-M LX3 R2.0             | 15       | 0.34%   |
| MSI MS-7C56                       | 14       | 0.32%   |
| MSI MS-7B79                       | 14       | 0.32%   |
| Lenovo ThinkCentre M55p 8808D8U   | 14       | 0.32%   |
| ASUS PRIME B450M-A                | 14       | 0.32%   |
| ASRock B450M Pro4                 | 14       | 0.32%   |
| ASUS PRIME B450M-K                | 13       | 0.3%    |
| ASUS H110M-R                      | 13       | 0.3%    |
| MSI MS-7C02                       | 12       | 0.27%   |
| AZW U59                           | 12       | 0.27%   |
| AZW MINI S                        | 12       | 0.27%   |
| MSI MS-7C91                       | 11       | 0.25%   |
| MSI MS-7A34                       | 11       | 0.25%   |
| HP Z420 Workstation               | 11       | 0.25%   |
| HP ProLiant MicroServer Gen8      | 11       | 0.25%   |
| Gigabyte B450M S2H                | 11       | 0.25%   |
| ASUS PRIME B450-PLUS              | 11       | 0.25%   |
| ASUS P8H67-M                      | 11       | 0.25%   |
| ASRock B450 Pro4                  | 11       | 0.25%   |
| Intel Jasper Lake Client Platform | 10       | 0.23%   |
| HP ProLiant MicroServer           | 10       | 0.23%   |
| HP Compaq Elite 8300 SFF          | 10       | 0.23%   |
| Gigabyte GA-78LMT-USB3            | 10       | 0.23%   |
| Dell OptiPlex 9020                | 10       | 0.23%   |
| ASUS ROG STRIX B550-F GAMING      | 10       | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 257      | 5.85%   |
| Dell OptiPlex          | 155      | 3.53%   |
| ASUS All               | 137      | 3.12%   |
| ASUS ROG               | 109      | 2.48%   |
| Unknown                | 109      | 2.48%   |
| Lenovo ThinkCentre     | 82       | 1.87%   |
| ASUS TUF               | 72       | 1.64%   |
| HP Compaq              | 68       | 1.55%   |
| Dell Precision         | 59       | 1.34%   |
| ASUS S20               | 55       | 1.25%   |
| MSI MS-7996            | 45       | 1.02%   |
| Gigabyte B450M         | 41       | 0.93%   |
| HP EliteDesk           | 38       | 0.87%   |
| ASUS P8H61-M           | 36       | 0.82%   |
| Gigabyte X570          | 32       | 0.73%   |
| HP ProLiant            | 31       | 0.71%   |
| Fujitsu ESPRIMO        | 28       | 0.64%   |
| MSI MS-7817            | 27       | 0.61%   |
| Lenovo ThinkStation    | 26       | 0.59%   |
| Gigabyte B550          | 26       | 0.59%   |
| ASUS PRO               | 26       | 0.59%   |
| HP ProDesk             | 25       | 0.57%   |
| ECS G31T-M9            | 25       | 0.57%   |
| Gigabyte H81M-S2V      | 24       | 0.55%   |
| ASRock B450M           | 24       | 0.55%   |
| Acer Aspire            | 24       | 0.55%   |
| ASRock B450            | 22       | 0.5%    |
| Gigabyte H410M         | 21       | 0.48%   |
| Gigabyte B450          | 20       | 0.46%   |
| ASRock H470M-HVS       | 20       | 0.46%   |
| Gigabyte GA-78LMT-USB3 | 19       | 0.43%   |
| ASUS M5A78L-M          | 19       | 0.43%   |
| Gigabyte B550M         | 18       | 0.41%   |
| ASUS P5G41T-M          | 18       | 0.41%   |
| Gigabyte A320M-S2H     | 17       | 0.39%   |
| ECS H61H2-M13          | 17       | 0.39%   |
| Dell XPS               | 17       | 0.39%   |
| Dell Vostro            | 17       | 0.39%   |
| ASRock X570            | 16       | 0.36%   |
| Lenovo IdeaCentre      | 15       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 420      | 9.56%   |
| 2020    | 407      | 9.27%   |
| 2012    | 381      | 8.67%   |
| 2013    | 346      | 7.88%   |
| 2019    | 312      | 7.1%    |
| 2021    | 299      | 6.81%   |
| 2011    | 271      | 6.17%   |
| 2014    | 259      | 5.9%    |
| 2017    | 233      | 5.31%   |
| 2009    | 217      | 4.94%   |
| 2015    | 213      | 4.85%   |
| 2022    | 203      | 4.62%   |
| 2010    | 198      | 4.51%   |
| 2016    | 175      | 3.98%   |
| 2008    | 153      | 3.48%   |
| 2007    | 125      | 2.85%   |
| 2023    | 52       | 1.18%   |
| 2006    | 47       | 1.07%   |
| Unknown | 33       | 0.75%   |
| 2005    | 25       | 0.57%   |
| 2004    | 10       | 0.23%   |
| 2003    | 6        | 0.14%   |
| 2001    | 3        | 0.07%   |
| 2002    | 2        | 0.05%   |
| 2000    | 2        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4392     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4317     | 98.09%  |
| Enabled  | 84       | 1.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4373     | 99.57%  |
| Yes  | 19       | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 899      | 20.12%  |
| 4.01-8.0        | 708      | 15.85%  |
| 8.01-16.0       | 682      | 15.26%  |
| 32.01-64.0      | 681      | 15.24%  |
| 3.01-4.0        | 653      | 14.62%  |
| 64.01-256.0     | 393      | 8.8%    |
| 1.01-2.0        | 172      | 3.85%   |
| 24.01-32.0      | 125      | 2.8%    |
| 2.01-3.0        | 72       | 1.61%   |
| 0.51-1.0        | 32       | 0.72%   |
| More than 256.0 | 21       | 0.47%   |
| Unknown         | 15       | 0.34%   |
| 0.01-0.5        | 14       | 0.31%   |
| 0               | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 1000     | 20.98%  |
| 1.01-2.0        | 976      | 20.47%  |
| 2.01-3.0        | 785      | 16.47%  |
| 4.01-8.0        | 756      | 15.86%  |
| 3.01-4.0        | 481      | 10.09%  |
| 8.01-16.0       | 313      | 6.57%   |
| 0.01-0.5        | 188      | 3.94%   |
| 16.01-24.0      | 121      | 2.54%   |
| 32.01-64.0      | 63       | 1.32%   |
| 24.01-32.0      | 44       | 0.92%   |
| 64.01-256.0     | 21       | 0.44%   |
| Unknown         | 18       | 0.38%   |
| More than 256.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1950     | 43%     |
| 2       | 1063     | 23.44%  |
| 3       | 608      | 13.41%  |
| 4       | 395      | 8.71%   |
| 5       | 186      | 4.1%    |
| 6       | 117      | 2.58%   |
| 7       | 61       | 1.35%   |
| 8       | 45       | 0.99%   |
| 0       | 27       | 0.6%    |
| 9       | 26       | 0.57%   |
| 10      | 15       | 0.33%   |
| 11      | 9        | 0.2%    |
| 13      | 6        | 0.13%   |
| 12      | 6        | 0.13%   |
| 19      | 3        | 0.07%   |
| 29      | 2        | 0.04%   |
| 27      | 2        | 0.04%   |
| 17      | 2        | 0.04%   |
| 16      | 2        | 0.04%   |
| 14      | 2        | 0.04%   |
| Unknown | 2        | 0.04%   |
| 46      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 28      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |
| 21      | 1        | 0.02%   |
| 18      | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2888     | 65.19%  |
| Yes       | 1542     | 34.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4351     | 99.07%  |
| No        | 41       | 0.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2990     | 67.57%  |
| Yes       | 1435     | 32.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3278     | 73.81%  |
| Yes       | 1163     | 26.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 981      | 22.29%  |
| USA          | 654      | 14.86%  |
| Germany      | 450      | 10.22%  |
| France       | 264      | 6%      |
| Brazil       | 210      | 4.77%   |
| Spain        | 178      | 4.04%   |
| Italy        | 146      | 3.32%   |
| UK           | 145      | 3.29%   |
| Canada       | 115      | 2.61%   |
| Australia    | 87       | 1.98%   |
| Poland       | 77       | 1.75%   |
| Netherlands  | 71       | 1.61%   |
| China        | 51       | 1.16%   |
| Switzerland  | 49       | 1.11%   |
| Austria      | 48       | 1.09%   |
| Belgium      | 44       | 1%      |
| Hungary      | 43       | 0.98%   |
| Argentina    | 41       | 0.93%   |
| Ukraine      | 37       | 0.84%   |
| Finland      | 37       | 0.84%   |
| Sweden       | 36       | 0.82%   |
| Mexico       | 34       | 0.77%   |
| India        | 31       | 0.7%    |
| Czechia      | 31       | 0.7%    |
| Portugal     | 28       | 0.64%   |
| Norway       | 27       | 0.61%   |
| Romania      | 24       | 0.55%   |
| Bulgaria     | 24       | 0.55%   |
| Venezuela    | 23       | 0.52%   |
| Japan        | 23       | 0.52%   |
| South Africa | 20       | 0.45%   |
| Turkey       | 17       | 0.39%   |
| Malaysia     | 17       | 0.39%   |
| Denmark      | 17       | 0.39%   |
| Greece       | 15       | 0.34%   |
| Belarus      | 15       | 0.34%   |
| Taiwan       | 14       | 0.32%   |
| Slovakia     | 13       | 0.3%    |
| New Zealand  | 12       | 0.27%   |
| Ireland      | 12       | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 670      | 14.68%  |
| Moscow            | 75       | 1.64%   |
| St Petersburg     | 53       | 1.16%   |
| Paris             | 37       | 0.81%   |
| Vienna            | 34       | 0.75%   |
| Sao Paulo         | 30       | 0.66%   |
| Berlin            | 30       | 0.66%   |
| Falkenstein       | 27       | 0.59%   |
| Bangor            | 26       | 0.57%   |
| Madrid            | 24       | 0.53%   |
| Rio de Janeiro    | 23       | 0.5%    |
| Barcelona         | 22       | 0.48%   |
| Seville           | 21       | 0.46%   |
| Amsterdam         | 20       | 0.44%   |
| Toronto           | 19       | 0.42%   |
| Melbourne         | 19       | 0.42%   |
| Frankfurt am Main | 19       | 0.42%   |
| Sydney            | 18       | 0.39%   |
| Milan             | 17       | 0.37%   |
| Budapest          | 16       | 0.35%   |
| Brisbane          | 16       | 0.35%   |
| Zurich            | 15       | 0.33%   |
| Yekaterinburg     | 15       | 0.33%   |
| Hamburg           | 15       | 0.33%   |
| Munich            | 14       | 0.31%   |
| Warsaw            | 13       | 0.28%   |
| Perm              | 13       | 0.28%   |
| Chicago           | 13       | 0.28%   |
| Ufa               | 12       | 0.26%   |
| New York          | 12       | 0.26%   |
| Kyiv              | 12       | 0.26%   |
| Kuala Lumpur      | 12       | 0.26%   |
| Helsinki          | 12       | 0.26%   |
| Cologne           | 12       | 0.26%   |
| Beijing           | 12       | 0.26%   |
| Valencia          | 11       | 0.24%   |
| Stuttgart         | 11       | 0.24%   |
| Stockholm         | 11       | 0.24%   |
| Sofia             | 11       | 0.24%   |
| Nuremberg         | 11       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1444     | 2762   | 18.39%  |
| Seagate                     | 1371     | 2529   | 17.46%  |
| Samsung Electronics         | 1142     | 1856   | 14.54%  |
| Kingston                    | 540      | 705    | 6.88%   |
| Toshiba                     | 496      | 914    | 6.32%   |
| Crucial                     | 452      | 611    | 5.76%   |
| SanDisk                     | 273      | 372    | 3.48%   |
| Hitachi                     | 270      | 399    | 3.44%   |
| Intel                       | 146      | 206    | 1.86%   |
| HGST                        | 120      | 261    | 1.53%   |
| A-DATA Technology           | 120      | 162    | 1.53%   |
| China                       | 109      | 129    | 1.39%   |
| Unknown                     | 100      | 150    | 1.27%   |
| SPCC                        | 65       | 72     | 0.83%   |
| Corsair                     | 57       | 79     | 0.73%   |
| Transcend                   | 55       | 66     | 0.7%    |
| Phison                      | 54       | 77     | 0.69%   |
| PNY                         | 52       | 96     | 0.66%   |
| Maxtor                      | 51       | 59     | 0.65%   |
| OCZ                         | 50       | 61     | 0.64%   |
| Hewlett-Packard             | 44       | 76     | 0.56%   |
| Patriot                     | 39       | 50     | 0.5%    |
| Micron Technology           | 38       | 48     | 0.48%   |
| Netac                       | 35       | 114    | 0.45%   |
| SK hynix                    | 34       | 56     | 0.43%   |
| Intenso                     | 31       | 43     | 0.39%   |
| Gigabyte Technology         | 31       | 35     | 0.39%   |
| GOODRAM                     | 29       | 55     | 0.37%   |
| Unknown                     | 25       | 26     | 0.32%   |
| Kingston Technology Company | 22       | 30     | 0.28%   |
| Silicon Motion              | 21       | 26     | 0.27%   |
| XPG                         | 19       | 32     | 0.24%   |
| Plextor                     | 19       | 25     | 0.24%   |
| Apacer                      | 19       | 23     | 0.24%   |
| JMicron Technology          | 17       | 19     | 0.22%   |
| Micron/Crucial Technology   | 16       | 21     | 0.2%    |
| LITEON                      | 16       | 20     | 0.2%    |
| Team                        | 14       | 21     | 0.18%   |
| Phison Electronics          | 14       | 25     | 0.18%   |
| KIOXIA                      | 12       | 14     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 127      | 1.36%   |
| Seagate ST500DM002-1BD142 500GB  | 117      | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB   | 97       | 1.04%   |
| Crucial CT480BX500SSD1 480GB     | 88       | 0.94%   |
| Toshiba DT01ACA050 500GB         | 84       | 0.9%    |
| Toshiba DT01ACA100 1TB           | 67       | 0.72%   |
| Kingston SA400S37480G 480GB SSD  | 67       | 0.72%   |
| Kingston SV300S37A120G 120GB SSD | 65       | 0.69%   |
| Samsung SSD 860 EVO 500GB        | 64       | 0.68%   |
| Samsung SSD 860 EVO 1TB          | 60       | 0.64%   |
| Kingston SA400S37120G 120GB SSD  | 60       | 0.64%   |
| Samsung SSD 860 EVO 250GB        | 59       | 0.63%   |
| Samsung SSD 850 EVO 250GB        | 59       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB   | 57       | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB         | 56       | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB   | 56       | 0.6%    |
| Crucial CT240BX500SSD1 240GB     | 55       | 0.59%   |
| Crucial CT500MX500SSD1 500GB     | 54       | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB   | 53       | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB     | 53       | 0.57%   |
| Samsung SSD 850 EVO 500GB        | 52       | 0.56%   |
| Crucial CT1000MX500SSD1 1TB      | 50       | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB   | 49       | 0.52%   |
| Toshiba HDWD110 1TB              | 46       | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB   | 46       | 0.49%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 41       | 0.44%   |
| Hitachi HDS721050CLA362 500GB    | 40       | 0.43%   |
| Samsung SSD 980 PRO 1TB          | 39       | 0.42%   |
| Seagate ST2000DM006-2DM164 2TB   | 35       | 0.37%   |
| Samsung SSD 870 EVO 500GB        | 34       | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB         | 32       | 0.34%   |
| Toshiba DT01ACA200 2TB           | 32       | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB         | 31       | 0.33%   |
| Seagate ST3500418AS 500GB        | 31       | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB   | 31       | 0.33%   |
| SanDisk NVMe SSD Drive 1TB       | 31       | 0.33%   |
| Crucial CT250MX500SSD1 250GB     | 29       | 0.31%   |
| WDC WD40EFRX-68N32N0 4TB         | 28       | 0.3%    |
| Seagate ST1000DM003-1SB102 1TB   | 28       | 0.3%    |
| WDC WD30EFRX-68EUZN0 3TB         | 27       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1344     | 2460   | 35.74%  |
| WDC                 | 1258     | 2430   | 33.46%  |
| Toshiba             | 452      | 841    | 12.02%  |
| Hitachi             | 270      | 399    | 7.18%   |
| Samsung Electronics | 168      | 227    | 4.47%   |
| HGST                | 120      | 261    | 3.19%   |
| Maxtor              | 50       | 58     | 1.33%   |
| Unknown             | 22       | 29     | 0.59%   |
| Hewlett-Packard     | 10       | 26     | 0.27%   |
| Fujitsu             | 6        | 7      | 0.16%   |
| ASMT                | 5        | 8      | 0.13%   |
| Apple               | 5        | 6      | 0.13%   |
| Intenso             | 4        | 5      | 0.11%   |
| HPE                 | 4        | 9      | 0.11%   |
| External            | 4        | 6      | 0.11%   |
| ASMedia             | 3        | 3      | 0.08%   |
| QNAP                | 2        | 3      | 0.05%   |
| WD MediaMax         | 1        | 6      | 0.03%   |
| USB 3.0             | 1        | 2      | 0.03%   |
| USB                 | 1        | 1      | 0.03%   |
| Synology            | 1        | 1      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SSK                 | 1        | 1      | 0.03%   |
| SD                  | 1        | 1      | 0.03%   |
| SABRENT             | 1        | 2      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| pqi                 | 1        | 1      | 0.03%   |
| Pear 2TB            | 1        | 1      | 0.03%   |
| NAS                 | 1        | 10     | 0.03%   |
| MaxDigital          | 1        | 4      | 0.03%   |
| MARSHAL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| JMicron Technology  | 1        | 2      | 0.03%   |
| Innodisk            | 1        | 1      | 0.03%   |
| IBM/Hitachi         | 1        | 1      | 0.03%   |
| IBM H0              | 1        | 1      | 0.03%   |
| IBM                 | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 629      | 927    | 21.95%  |
| Kingston            | 476      | 614    | 16.61%  |
| Crucial             | 399      | 533    | 13.92%  |
| SanDisk             | 180      | 243    | 6.28%   |
| WDC                 | 164      | 210    | 5.72%   |
| China               | 107      | 127    | 3.73%   |
| A-DATA Technology   | 88       | 115    | 3.07%   |
| Intel               | 79       | 108    | 2.76%   |
| SPCC                | 56       | 60     | 1.95%   |
| OCZ                 | 50       | 61     | 1.74%   |
| Transcend           | 49       | 59     | 1.71%   |
| PNY                 | 40       | 81     | 1.4%    |
| Toshiba             | 33       | 43     | 1.15%   |
| Netac               | 32       | 111    | 1.12%   |
| Patriot             | 29       | 34     | 1.01%   |
| GOODRAM             | 26       | 39     | 0.91%   |
| Intenso             | 25       | 33     | 0.87%   |
| Micron Technology   | 23       | 29     | 0.8%    |
| Corsair             | 22       | 27     | 0.77%   |
| Hewlett-Packard     | 17       | 23     | 0.59%   |
| Gigabyte Technology | 15       | 17     | 0.52%   |
| Apacer              | 15       | 17     | 0.52%   |
| Plextor             | 14       | 20     | 0.49%   |
| Team                | 12       | 16     | 0.42%   |
| LITEON              | 12       | 16     | 0.42%   |
| KingDian            | 11       | 12     | 0.38%   |
| Unknown             | 11       | 12     | 0.38%   |
| SK hynix            | 10       | 12     | 0.35%   |
| Seagate             | 10       | 12     | 0.35%   |
| Unknown             | 8        | 11     | 0.28%   |
| SABRENT             | 8        | 8      | 0.28%   |
| Mushkin             | 8        | 9      | 0.28%   |
| Hajaan              | 8        | 11     | 0.28%   |
| LITEONIT            | 7        | 12     | 0.24%   |
| NGFF                | 6        | 6      | 0.21%   |
| Drevo               | 6        | 6      | 0.21%   |
| AMD                 | 6        | 6      | 0.21%   |
| Xinhaike            | 5        | 8      | 0.17%   |
| T-FORCE             | 5        | 7      | 0.17%   |
| KingSpec            | 5        | 6      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2887     | 6843   | 43.96%  |
| SSD     | 2374     | 3889   | 36.14%  |
| NVMe    | 1170     | 1874   | 17.81%  |
| Unknown | 88       | 168    | 1.34%   |
| MMC     | 49       | 59     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3944     | 10261  | 72.59%  |
| NVMe | 1156     | 1848   | 21.28%  |
| SAS  | 284      | 665    | 5.23%   |
| MMC  | 49       | 59     | 0.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 3005     | 5080    | 50.66%  |
| 0.51-1.0   | 1439     | 2407    | 24.26%  |
| 1.01-2.0   | 625      | 1110    | 10.54%  |
| 3.01-4.0   | 325      | 721     | 5.48%   |
| 4.01-10.0  | 243      | 725     | 4.1%    |
| 2.01-3.0   | 225      | 420     | 3.79%   |
| 10.01-20.0 | 68       | 268     | 1.15%   |
| 20.01-50.0 | 1        | 1       | 0.02%   |
| 0          | 1        | Unknown | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 911      | 19.96%  |
| 101-250        | 727      | 15.93%  |
| 251-500        | 603      | 13.21%  |
| 501-1000       | 600      | 13.15%  |
| More than 3000 | 537      | 11.77%  |
| 1001-2000      | 415      | 9.09%   |
| 51-100         | 245      | 5.37%   |
| 2001-3000      | 226      | 4.95%   |
| 1-20           | 166      | 3.64%   |
| 21-50          | 133      | 2.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1187     | 25.43%  |
| Unknown        | 911      | 19.52%  |
| 101-250        | 477      | 10.22%  |
| 21-50          | 412      | 8.83%   |
| 251-500        | 368      | 7.88%   |
| 51-100         | 340      | 7.28%   |
| 501-1000       | 335      | 7.18%   |
| 1001-2000      | 267      | 5.72%   |
| More than 3000 | 241      | 5.16%   |
| 2001-3000      | 121      | 2.59%   |
| 0              | 9        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 31       | 46     | 2.99%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 21       | 37     | 2.03%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 21     | 1.93%   |
| Hitachi HDS721050CLA362 500GB    | 12       | 14     | 1.16%   |
| Seagate ST1000DM003-9YN162 1TB   | 11       | 12     | 1.06%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 9        | 9      | 0.87%   |
| Seagate ST3500418AS 500GB        | 9        | 15     | 0.87%   |
| Seagate ST31000528AS 1TB         | 9        | 11     | 0.87%   |
| Seagate ST3250318AS 250GB        | 8        | 9      | 0.77%   |
| Seagate ST31500341AS 1TB         | 8        | 14     | 0.77%   |
| Toshiba DT01ACA100 1TB           | 7        | 9      | 0.68%   |
| Toshiba DT01ACA050 500GB         | 7        | 8      | 0.68%   |
| Seagate ST3250410AS 250GB        | 7        | 8      | 0.68%   |
| Seagate ST3160815AS 160GB        | 7        | 9      | 0.68%   |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB   | 7        | 7      | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB      | 6        | 8      | 0.58%   |
| WDC WD3200AAJS-00L7A0 320GB      | 6        | 6      | 0.58%   |
| WDC WD20EARX-00PASB0 2TB         | 6        | 8      | 0.58%   |
| WDC WD20EARS-00MVWB0 2TB         | 6        | 6      | 0.58%   |
| Seagate ST3320613AS 320GB        | 6        | 6      | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 7      | 0.58%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 5      | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 5        | 6      | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB         | 5        | 16     | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB          | 5        | 5      | 0.48%   |
| WDC WD10EADS-00M2B0 1TB          | 5        | 5      | 0.48%   |
| Seagate ST3500413AS 500GB        | 5        | 6      | 0.48%   |
| Seagate ST31000524AS 1TB         | 5        | 5      | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB   | 5        | 7      | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 6      | 0.48%   |
| Samsung Electronics HD103UJ 1TB  | 5        | 6      | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB         | 4        | 13     | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB         | 4        | 4      | 0.39%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 4        | 4      | 0.39%   |
| WDC WD2002FAEX-007BA0 2TB        | 4        | 5      | 0.39%   |
| WDC WD10EALX-009BA0 1TB          | 4        | 5      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 290      | 413    | 29.53%  |
| WDC                 | 277      | 412    | 28.21%  |
| Samsung Electronics | 90       | 103    | 9.16%   |
| Hitachi             | 67       | 92     | 6.82%   |
| Toshiba             | 47       | 58     | 4.79%   |
| Kingston            | 42       | 50     | 4.28%   |
| Intel               | 25       | 33     | 2.55%   |
| Crucial             | 21       | 27     | 2.14%   |
| Maxtor              | 20       | 22     | 2.04%   |
| A-DATA Technology   | 18       | 25     | 1.83%   |
| SanDisk             | 12       | 15     | 1.22%   |
| HGST                | 9        | 10     | 0.92%   |
| OCZ                 | 8        | 9      | 0.81%   |
| Corsair             | 5        | 5      | 0.51%   |
| China               | 5        | 5      | 0.51%   |
| SK hynix            | 4        | 8      | 0.41%   |
| Micron Technology   | 4        | 4      | 0.41%   |
| KingDian            | 4        | 4      | 0.41%   |
| SPCC                | 3        | 3      | 0.31%   |
| Transcend           | 2        | 2      | 0.2%    |
| LITEONIT            | 2        | 2      | 0.2%    |
| LITEON              | 2        | 2      | 0.2%    |
| Hewlett-Packard     | 2        | 3      | 0.2%    |
| Apacer              | 2        | 2      | 0.2%    |
| ZHITAI              | 1        | 1      | 0.1%    |
| Western Digital     | 1        | 2      | 0.1%    |
| Unknown             | 1        | 1      | 0.1%    |
| Teclast             | 1        | 1      | 0.1%    |
| SSSTC               | 1        | 1      | 0.1%    |
| ShiJi               | 1        | 1      | 0.1%    |
| PNY                 | 1        | 1      | 0.1%    |
| Plextor             | 1        | 2      | 0.1%    |
| Patriot             | 1        | 1      | 0.1%    |
| Netac               | 1        | 1      | 0.1%    |
| Mushkin             | 1        | 1      | 0.1%    |
| KingSpec            | 1        | 1      | 0.1%    |
| Intenso             | 1        | 1      | 0.1%    |
| IBM                 | 1        | 1      | 0.1%    |
| Hypertec            | 1        | 1      | 0.1%    |
| HS-SSD-C100         | 1        | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 290      | 413    | 38.46%  |
| WDC                 | 265      | 398    | 35.15%  |
| Hitachi             | 67       | 92     | 8.89%   |
| Samsung Electronics | 51       | 57     | 6.76%   |
| Toshiba             | 45       | 56     | 5.97%   |
| Maxtor              | 20       | 22     | 2.65%   |
| HGST                | 9        | 10     | 1.19%   |
| Hewlett-Packard     | 2        | 3      | 0.27%   |
| Unknown             | 1        | 1      | 0.13%   |
| IBM                 | 1        | 1      | 0.13%   |
| Fujitsu             | 1        | 2      | 0.13%   |
| ASMT                | 1        | 2      | 0.13%   |
| Apple               | 1        | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 680      | 1058   | 75.06%  |
| SSD  | 197      | 236    | 21.74%  |
| NVMe | 29       | 40     | 3.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 3      | 10%     |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 5%      |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 5%      |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 5%      |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 5%      |
| Seagate ST3500630A 500GB                         | 1        | 1      | 5%      |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 5%      |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 5%      |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 5%      |
| Samsung Electronics SP0802N 80GB                 | 1        | 1      | 5%      |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 5%      |
| Samsung Electronics HD253GJ 250GB                | 1        | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB                  | 1        | 2      | 5%      |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 5%      |
| Inland SATA SSD 128GB                            | 1        | 1      | 5%      |
| HGST HUH728080ALN600 8TB                         | 1        | 1      | 5%      |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 5%      |
| Hewlett-Packard SSD S700 500GB                   | 1        | 2      | 5%      |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 30%     |
| Samsung Electronics | 6        | 8      | 30%     |
| WDC                 | 2        | 2      | 10%     |
| HGST                | 2        | 2      | 10%     |
| Intel               | 1        | 1      | 5%      |
| Inland              | 1        | 1      | 5%      |
| Hewlett-Packard     | 1        | 2      | 5%      |
| Crucial             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 3157     | 8144   | 60.57%  |
| Detected | 1166     | 3329   | 22.37%  |
| Malfunc  | 867      | 1334   | 16.63%  |
| Failed   | 20       | 24     | 0.38%   |
| Limited  | 2        | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2902     | 46.03%  |
| AMD                              | 1310     | 20.78%  |
| Samsung Electronics              | 479      | 7.6%    |
| ASMedia Technology               | 242      | 3.84%   |
| SanDisk                          | 183      | 2.9%    |
| Marvell Technology Group         | 161      | 2.55%   |
| Phison Electronics               | 149      | 2.36%   |
| JMicron Technology               | 123      | 1.95%   |
| Nvidia                           | 97       | 1.54%   |
| Kingston Technology Company      | 96       | 1.52%   |
| Micron/Crucial Technology        | 78       | 1.24%   |
| Silicon Motion                   | 53       | 0.84%   |
| LSI Logic / Symbios Logic        | 52       | 0.82%   |
| ADATA Technology                 | 49       | 0.78%   |
| VIA Technologies                 | 47       | 0.75%   |
| Broadcom / LSI                   | 42       | 0.67%   |
| Silicon Image                    | 24       | 0.38%   |
| Toshiba America Info Systems     | 22       | 0.35%   |
| SK hynix                         | 21       | 0.33%   |
| Adaptec                          | 21       | 0.33%   |
| MAXIO Technology (Hangzhou)      | 19       | 0.3%    |
| Micron Technology                | 16       | 0.25%   |
| KIOXIA                           | 16       | 0.25%   |
| Realtek Semiconductor            | 15       | 0.24%   |
| Seagate Technology               | 13       | 0.21%   |
| Lite-On Technology               | 10       | 0.16%   |
| INNOGRIT                         | 6        | 0.1%    |
| Silicon Integrated Systems [SiS] | 5        | 0.08%   |
| IBM                              | 5        | 0.08%   |
| Hewlett-Packard                  | 5        | 0.08%   |
| Biwin Storage Technology         | 5        | 0.08%   |
| Integrated Technology Express    | 4        | 0.06%   |
| HighPoint Technologies           | 4        | 0.06%   |
| Yangtze Memory Technologies      | 3        | 0.05%   |
| Shenzhen Longsys Electronics     | 3        | 0.05%   |
| Loongson Technology              | 3        | 0.05%   |
| 3ware                            | 3        | 0.05%   |
| Transcend                        | 2        | 0.03%   |
| Solidigm                         | 2        | 0.03%   |
| Netac Technology                 | 2        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 776      | 9.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 349      | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 290      | 3.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 267      | 3.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 227      | 2.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 221      | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 215      | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 212      | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 212      | 2.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 171      | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 164      | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 163      | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 161      | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 136      | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 109      | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 108      | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 106      | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 100      | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 100      | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 99       | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 96       | 1.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 79       | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 75       | 0.95%   |
| Phison E12 NVMe Controller                                                              | 74       | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 64       | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 63       | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 63       | 0.8%    |
| AMD 300 Series Chipset SATA Controller                                                  | 63       | 0.8%    |
| AMD FCH SATA Controller D                                                               | 62       | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 56       | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 56       | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 56       | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 52       | 0.66%   |
| Nvidia MCP61 SATA Controller                                                            | 50       | 0.64%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 46       | 0.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 45       | 0.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 45       | 0.57%   |
| Nvidia MCP61 IDE                                                                        | 44       | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 44       | 0.56%   |
| AMD X370 Series Chipset SATA Controller                                                 | 44       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3565     | 57.77%  |
| NVMe | 1153     | 18.68%  |
| IDE  | 1046     | 16.95%  |
| RAID | 277      | 4.49%   |
| SAS  | 97       | 1.57%   |
| SCSI | 33       | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2933     | 66.78%  |
| AMD                   | 1418     | 32.29%  |
| ARM                   | 8        | 0.18%   |
| Unknown               | 8        | 0.18%   |
| CentaurHauls          | 7        | 0.16%   |
| CHRP IBM,8233-E8B     | 5        | 0.11%   |
| sifive,bullet0        | 3        | 0.07%   |
| sifive,u74-mc         | 2        | 0.05%   |
| Marvell Semiconductor | 2        | 0.05%   |
| Loongson              | 2        | 0.05%   |
| CHRP IBM,9131-52A     | 2        | 0.05%   |
| PowerNV FP5466G2      | 1        | 0.02%   |
| PowerNV C829UAG3      | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 74       | 1.68%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 67       | 1.52%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 51       | 1.16%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 46       | 1.04%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 44       | 1%      |
| Intel Core i7-4790 CPU @ 3.60GHz            | 42       | 0.95%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 42       | 0.95%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 41       | 0.93%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 39       | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 38       | 0.86%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 38       | 0.86%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 38       | 0.86%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 37       | 0.84%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 35       | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 34       | 0.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 34       | 0.77%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 34       | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 33       | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 32       | 0.73%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 31       | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 31       | 0.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 31       | 0.7%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 30       | 0.68%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 30       | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 29       | 0.66%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 29       | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 29       | 0.66%   |
| AMD FX-8350 Eight-Core Processor            | 29       | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 28       | 0.63%   |
| Intel Celeron N5105 @ 2.00GHz               | 27       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 27       | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 27       | 0.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 26       | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 26       | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 26       | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.54%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 24       | 0.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 24       | 0.54%   |
| AMD FX-6300 Six-Core Processor              | 24       | 0.54%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 23       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 670      | 15.22%  |
| Intel Core i7           | 435      | 9.88%   |
| Intel Core i3           | 356      | 8.09%   |
| AMD Ryzen 5             | 329      | 7.47%   |
| Intel Xeon              | 295      | 6.7%    |
| AMD Ryzen 7             | 264      | 6%      |
| Intel Celeron           | 244      | 5.54%   |
| Intel Pentium           | 221      | 5.02%   |
| Other                   | 216      | 4.91%   |
| AMD Ryzen 9             | 167      | 3.79%   |
| Intel Core 2 Duo        | 163      | 3.7%    |
| AMD FX                  | 131      | 2.98%   |
| Intel Pentium Dual-Core | 82       | 1.86%   |
| AMD Ryzen 3             | 74       | 1.68%   |
| Intel Core 2 Quad       | 70       | 1.59%   |
| Intel Atom              | 42       | 0.95%   |
| Intel Core 2            | 40       | 0.91%   |
| AMD Ryzen Threadripper  | 39       | 0.89%   |
| Intel Core i9           | 38       | 0.86%   |
| AMD Phenom II X4        | 37       | 0.84%   |
| AMD Athlon 64 X2        | 35       | 0.79%   |
| AMD Athlon II X2        | 34       | 0.77%   |
| AMD Athlon              | 33       | 0.75%   |
| AMD A10                 | 31       | 0.7%    |
| AMD A8                  | 29       | 0.66%   |
| Intel Pentium 4         | 28       | 0.64%   |
| Intel Pentium Gold      | 27       | 0.61%   |
| AMD Ryzen 5 PRO         | 20       | 0.45%   |
| AMD GX                  | 20       | 0.45%   |
| AMD Phenom II X6        | 19       | 0.43%   |
| Intel Pentium Dual      | 16       | 0.36%   |
| AMD Athlon II X4        | 15       | 0.34%   |
| AMD Sempron             | 13       | 0.3%    |
| AMD A4                  | 13       | 0.3%    |
| Intel Pentium D         | 12       | 0.27%   |
| Intel Pentium Silver    | 11       | 0.25%   |
| AMD Phenom              | 11       | 0.25%   |
| AMD A6                  | 11       | 0.25%   |
| AMD E                   | 10       | 0.23%   |
| AMD Athlon 64           | 10       | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1502     | 34.07%  |
| 2       | 1247     | 28.29%  |
| 6       | 640      | 14.52%  |
| 8       | 440      | 9.98%   |
| 12      | 146      | 3.31%   |
| 1       | 140      | 3.18%   |
| 16      | 127      | 2.88%   |
| 3       | 50       | 1.13%   |
| 10      | 38       | 0.86%   |
| 24      | 25       | 0.57%   |
| 32      | 14       | 0.32%   |
| 14      | 9        | 0.2%    |
| Unknown | 8        | 0.18%   |
| 18      | 5        | 0.11%   |
| 22      | 4        | 0.09%   |
| 64      | 3        | 0.07%   |
| 44      | 3        | 0.07%   |
| 20      | 3        | 0.07%   |
| 36      | 2        | 0.05%   |
| 28      | 1        | 0.02%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4306     | 97.97%  |
| 2       | 79       | 1.8%    |
| Unknown | 8        | 0.18%   |
| 16      | 1        | 0.02%   |
| 0       | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2405     | 54.67%  |
| 1       | 1979     | 44.99%  |
| Unknown | 8        | 0.18%   |
| 4       | 6        | 0.14%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4272     | 97.14%  |
| Unknown        | 83       | 1.89%   |
| 32-bit         | 43       | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1064     | 23.51%  |
| 0x306c3    | 352      | 7.78%   |
| 0x206a7    | 210      | 4.64%   |
| 0x1067a    | 203      | 4.49%   |
| 0x306a9    | 195      | 4.31%   |
| 0x506e3    | 163      | 3.6%    |
| 0x906ea    | 143      | 3.16%   |
| 0x08701021 | 135      | 2.98%   |
| 0xa0653    | 93       | 2.06%   |
| 0x906e9    | 93       | 2.06%   |
| 0x0800820d | 70       | 1.55%   |
| 0x08108109 | 69       | 1.52%   |
| 0x0a201016 | 61       | 1.35%   |
| 0xa0655    | 53       | 1.17%   |
| 0xa0671    | 47       | 1.04%   |
| 0x906c0    | 46       | 1.02%   |
| 0x010000c8 | 45       | 0.99%   |
| 0x90672    | 44       | 0.97%   |
| 0x08701013 | 41       | 0.91%   |
| 0x906ed    | 38       | 0.84%   |
| 0x0a50000d | 38       | 0.84%   |
| 0x06000852 | 36       | 0.8%    |
| 0x0a601203 | 35       | 0.77%   |
| 0x08101016 | 35       | 0.77%   |
| 0x306f2    | 34       | 0.75%   |
| 0x6fd      | 31       | 0.69%   |
| 0x206d7    | 31       | 0.69%   |
| 0x306e4    | 30       | 0.66%   |
| 0x08001137 | 30       | 0.66%   |
| 0x6fb      | 29       | 0.64%   |
| 0x06003106 | 29       | 0.64%   |
| 0x0a20120a | 28       | 0.62%   |
| 0x08001138 | 27       | 0.6%    |
| 0x906eb    | 26       | 0.57%   |
| 0x106a5    | 24       | 0.53%   |
| 0x08600106 | 24       | 0.53%   |
| 0x0a201009 | 23       | 0.51%   |
| 0x06001119 | 23       | 0.51%   |
| 0x6f2      | 22       | 0.49%   |
| 0x10676    | 22       | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 514      | 11.65%  |
| KabyLake         | 396      | 8.98%   |
| SandyBridge      | 301      | 6.82%   |
| Zen 2            | 284      | 6.44%   |
| Penryn           | 284      | 6.44%   |
| IvyBridge        | 279      | 6.32%   |
| Zen 3            | 247      | 5.6%    |
| Skylake          | 232      | 5.26%   |
| Zen+             | 207      | 4.69%   |
| CometLake        | 177      | 4.01%   |
| Unknown          | 177      | 4.01%   |
| Zen              | 148      | 3.35%   |
| K10              | 146      | 3.31%   |
| Core             | 136      | 3.08%   |
| Piledriver       | 132      | 2.99%   |
| Westmere         | 72       | 1.63%   |
| Alderlake Hybrid | 66       | 1.5%    |
| Silvermont       | 62       | 1.41%   |
| Nehalem          | 60       | 1.36%   |
| Tremont          | 58       | 1.31%   |
| K8 Hammer        | 58       | 1.31%   |
| NetBurst         | 50       | 1.13%   |
| Goldmont plus    | 43       | 0.97%   |
| Steamroller      | 37       | 0.84%   |
| Bulldozer        | 31       | 0.7%    |
| Broadwell        | 31       | 0.7%    |
| Bonnell          | 29       | 0.66%   |
| Goldmont         | 28       | 0.63%   |
| Jaguar           | 22       | 0.5%    |
| Excavator        | 22       | 0.5%    |
| Icelake          | 20       | 0.45%   |
| Bobcat           | 20       | 0.45%   |
| Puma             | 11       | 0.25%   |
| TigerLake        | 8        | 0.18%   |
| K6               | 7        | 0.16%   |
| P6               | 6        | 0.14%   |
| K10 Llano        | 6        | 0.14%   |
| Gracemont        | 4        | 0.09%   |
| Geode            | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1765     | 37.97%  |
| Nvidia                                       | 1507     | 32.42%  |
| AMD                                          | 1223     | 26.31%  |
| ASPEED Technology                            | 85       | 1.83%   |
| Matrox Electronics Systems                   | 47       | 1.01%   |
| VIA Technologies                             | 11       | 0.24%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.06%   |
| Loongson Technology                          | 3        | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| Silicon Motion                               | 1        | 0.02%   |
| Cirrus Logic                                 | 1        | 0.02%   |
| ATI Technologies                             | 1        | 0.02%   |
| 3DLabs                                       | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 244      | 5.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 158      | 3.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 155      | 3.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 135      | 2.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 106      | 2.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 105      | 2.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 96       | 2.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 90       | 1.89%   |
| Intel HD Graphics 530                                                                    | 89       | 1.87%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 85       | 1.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 83       | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 81       | 1.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 78       | 1.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 70       | 1.47%   |
| Intel HD Graphics 630                                                                    | 62       | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 61       | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 60       | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 55       | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 53       | 1.11%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 52       | 1.09%   |
| Intel JasperLake [UHD Graphics]                                                          | 49       | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                               | 47       | 0.99%   |
| Intel HD Graphics 510                                                                    | 46       | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 44       | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 39       | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 38       | 0.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 38       | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38       | 0.8%    |
| AMD Raphael                                                                              | 38       | 0.8%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 37       | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 36       | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 36       | 0.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 36       | 0.76%   |
| Intel AlderLake-S GT1                                                                    | 35       | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 34       | 0.71%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 34       | 0.71%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 33       | 0.69%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 30       | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 29       | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29       | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1575     | 35.44%  |
| 1 x Nvidia                        | 1358     | 30.56%  |
| 1 x AMD                           | 1085     | 24.41%  |
| Intel + Nvidia                    | 77       | 1.73%   |
| 1 x ASPEED                        | 67       | 1.51%   |
| 2 x AMD                           | 57       | 1.28%   |
| Other                             | 45       | 1.01%   |
| 1 x Matrox                        | 45       | 1.01%   |
| AMD + Nvidia                      | 39       | 0.88%   |
| Intel + AMD                       | 26       | 0.59%   |
| 2 x Nvidia                        | 16       | 0.36%   |
| 1 x VIA                           | 11       | 0.25%   |
| Nvidia + ASPEED                   | 11       | 0.25%   |
| 2 x Intel                         | 6        | 0.14%   |
| AMD + ASPEED                      | 6        | 0.14%   |
| AMD + Matrox                      | 4        | 0.09%   |
| 1 x SiS                           | 3        | 0.07%   |
| Intel + 2 x Nvidia                | 3        | 0.07%   |
| 3 x AMD                           | 1        | 0.02%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.02%   |
| 2 x Loongson Technology           | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.02%   |
| 1 x XGI                           | 1        | 0.02%   |
| 1 x Silicon Motion                | 1        | 0.02%   |
| 1 x Loongson Technology           | 1        | 0.02%   |
| 1 x Cirrus Logic                  | 1        | 0.02%   |
| AMD + Loongson Technology         | 1        | 0.02%   |
| AMD + 3DLabs                      | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2587     | 58.19%  |
| Unknown     | 1108     | 24.92%  |
| Proprietary | 751      | 16.89%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2698     | 60.12%  |
| 1.01-2.0   | 405      | 9.02%   |
| 0.51-1.0   | 297      | 6.62%   |
| 0.01-0.5   | 288      | 6.42%   |
| 3.01-4.0   | 277      | 6.17%   |
| 7.01-8.0   | 254      | 5.66%   |
| 5.01-6.0   | 116      | 2.58%   |
| 8.01-16.0  | 82       | 1.83%   |
| 2.01-3.0   | 43       | 0.96%   |
| 16.01-24.0 | 20       | 0.45%   |
| 4.01-5.0   | 6        | 0.13%   |
| 32.01-64.0 | 1        | 0.02%   |
| 24.01-32.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 556      | 15.63%  |
| Dell                 | 419      | 11.78%  |
| Goldstar             | 348      | 9.78%   |
| Hewlett-Packard      | 230      | 6.46%   |
| Acer                 | 221      | 6.21%   |
| BenQ                 | 212      | 5.96%   |
| Philips              | 179      | 5.03%   |
| AOC                  | 174      | 4.89%   |
| Ancor Communications | 162      | 4.55%   |
| Iiyama               | 83       | 2.33%   |
| ViewSonic            | 81       | 2.28%   |
| Unknown              | 75       | 2.11%   |
| ASUSTek Computer     | 62       | 1.74%   |
| Lenovo               | 59       | 1.66%   |
| LG Electronics       | 52       | 1.46%   |
| Eizo                 | 41       | 1.15%   |
| Sony                 | 36       | 1.01%   |
| NEC Computers        | 28       | 0.79%   |
| Unknown              | 23       | 0.65%   |
| Fujitsu Siemens      | 22       | 0.62%   |
| Medion               | 19       | 0.53%   |
| Sceptre Tech         | 16       | 0.45%   |
| Vizio                | 15       | 0.42%   |
| Vestel Elektronik    | 13       | 0.37%   |
| HannStar             | 13       | 0.37%   |
| MSI                  | 12       | 0.34%   |
| Idek Iiyama          | 10       | 0.28%   |
| Hitachi              | 10       | 0.28%   |
| Belinea              | 10       | 0.28%   |
| RTK                  | 9        | 0.25%   |
| Panasonic            | 9        | 0.25%   |
| HPN                  | 9        | 0.25%   |
| Toshiba              | 8        | 0.22%   |
| HKC                  | 8        | 0.22%   |
| CHR                  | 8        | 0.22%   |
| Apple                | 8        | 0.22%   |
| Packard Bell         | 7        | 0.2%    |
| Mi                   | 7        | 0.2%    |
| ONN                  | 6        | 0.17%   |
| MStar                | 6        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 36       | 0.95%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 32       | 0.84%   |
| Unknown                                                               | 23       | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16       | 0.42%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 15       | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 13       | 0.34%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 12       | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 11       | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 11       | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 11       | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 10       | 0.26%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 10       | 0.26%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 10       | 0.26%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 9        | 0.24%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 9        | 0.24%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.24%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 9        | 0.24%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.21%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 8        | 0.21%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 8        | 0.21%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 8        | 0.21%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 7        | 0.18%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 7        | 0.18%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 7        | 0.18%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 7        | 0.18%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 7        | 0.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 7        | 0.18%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 7        | 0.18%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 7        | 0.18%   |
| CHR CH7511B CHR7511 800x600 519x324mm 24.1-inch                       | 7        | 0.18%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 7        | 0.18%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                     | 7        | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 7        | 0.18%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 6        | 0.16%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 6        | 0.16%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 6        | 0.16%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 6        | 0.16%   |
| Dell E178FP DELA027 1280x1024 338x270mm 17.0-inch                     | 6        | 0.16%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 6        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1466     | 41.67%  |
| 3840x2160 (4K)     | 332      | 9.44%   |
| 1280x1024 (SXGA)   | 290      | 8.24%   |
| 2560x1440 (QHD)    | 273      | 7.76%   |
| 1680x1050 (WSXGA+) | 173      | 4.92%   |
| 1920x1200 (WUXGA)  | 127      | 3.61%   |
| Unknown            | 125      | 3.55%   |
| 1366x768 (WXGA)    | 112      | 3.18%   |
| 1600x900 (HD+)     | 92       | 2.62%   |
| 1440x900 (WXGA+)   | 92       | 2.62%   |
| 2560x1080          | 62       | 1.76%   |
| 3440x1440          | 57       | 1.62%   |
| 3840x1080          | 43       | 1.22%   |
| 1360x768           | 39       | 1.11%   |
| 2288x1287          | 38       | 1.08%   |
| 1024x768 (XGA)     | 34       | 0.97%   |
| 1600x1200          | 29       | 0.82%   |
| 1920x540           | 16       | 0.45%   |
| 4480x1440          | 12       | 0.34%   |
| 2560x1600          | 10       | 0.28%   |
| 3200x1080          | 7        | 0.2%    |
| 5760x2160          | 6        | 0.17%   |
| 5760x1080          | 6        | 0.17%   |
| 3840x1600          | 6        | 0.17%   |
| 1280x720 (HD)      | 6        | 0.17%   |
| 7680x2160          | 5        | 0.14%   |
| 3840x1200          | 4        | 0.11%   |
| 1400x1050          | 4        | 0.11%   |
| 3360x1050          | 3        | 0.09%   |
| 2048x1152          | 3        | 0.09%   |
| 6400x2160          | 2        | 0.06%   |
| 5760x1200          | 2        | 0.06%   |
| 5360x1440          | 2        | 0.06%   |
| 3600x1080          | 2        | 0.06%   |
| 2720x768           | 2        | 0.06%   |
| 2560x1024          | 2        | 0.06%   |
| 2048x1536          | 2        | 0.06%   |
| 1280x800 (WXGA)    | 2        | 0.06%   |
| 7680x4320          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 509      | 14.5%   |
| 27      | 470      | 13.39%  |
| 23      | 414      | 11.79%  |
| Unknown | 361      | 10.28%  |
| 21      | 355      | 10.11%  |
| 19      | 219      | 6.24%   |
| 17      | 145      | 4.13%   |
| 18      | 130      | 3.7%    |
| 31      | 122      | 3.47%   |
| 22      | 111      | 3.16%   |
| 20      | 106      | 3.02%   |
| 34      | 89       | 2.53%   |
| 15      | 69       | 1.97%   |
| 84      | 50       | 1.42%   |
| 142     | 36       | 1.03%   |
| 32      | 32       | 0.91%   |
| 25      | 32       | 0.91%   |
| 72      | 30       | 0.85%   |
| 54      | 26       | 0.74%   |
| 40      | 23       | 0.66%   |
| 28      | 18       | 0.51%   |
| 26      | 18       | 0.51%   |
| 52      | 14       | 0.4%    |
| 29      | 11       | 0.31%   |
| 48      | 10       | 0.28%   |
| 39      | 9        | 0.26%   |
| 35      | 8        | 0.23%   |
| 16      | 8        | 0.23%   |
| 13      | 8        | 0.23%   |
| 65      | 7        | 0.2%    |
| 43      | 6        | 0.17%   |
| 42      | 6        | 0.17%   |
| 33      | 6        | 0.17%   |
| 46      | 5        | 0.14%   |
| 37      | 5        | 0.14%   |
| 12      | 5        | 0.14%   |
| 49      | 4        | 0.11%   |
| 38      | 4        | 0.11%   |
| 36      | 4        | 0.11%   |
| 75      | 3        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1285     | 37.79%  |
| 401-500        | 776      | 22.82%  |
| Unknown        | 361      | 10.62%  |
| 601-700        | 208      | 6.12%   |
| 301-350        | 205      | 6.03%   |
| 351-400        | 157      | 4.62%   |
| 701-800        | 129      | 3.79%   |
| 1501-2000      | 85       | 2.5%    |
| 1001-1500      | 76       | 2.24%   |
| 801-900        | 46       | 1.35%   |
| More than 2000 | 37       | 1.09%   |
| 201-300        | 17       | 0.5%    |
| 901-1000       | 16       | 0.47%   |
| 101-200        | 2        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1993     | 60.95%  |
| 16/10   | 394      | 12.05%  |
| Unknown | 319      | 9.76%   |
| 5/4     | 267      | 8.17%   |
| 21/9    | 114      | 3.49%   |
| 4/3     | 85       | 2.6%    |
| 1.00    | 39       | 1.19%   |
| 3/2     | 25       | 0.76%   |
| 6/5     | 15       | 0.46%   |
| 32/9    | 11       | 0.34%   |
| 2.00    | 2        | 0.06%   |
| 1.96    | 2        | 0.06%   |
| 0.56    | 2        | 0.06%   |
| 2.65    | 1        | 0.03%   |
| 11/10   | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1115     | 32.38%  |
| 301-350        | 480      | 13.94%  |
| 151-200        | 420      | 12.2%   |
| Unknown        | 361      | 10.49%  |
| 351-500        | 280      | 8.13%   |
| 141-150        | 227      | 6.59%   |
| 251-300        | 198      | 5.75%   |
| More than 1000 | 185      | 5.37%   |
| 501-1000       | 69       | 2%      |
| 101-110        | 59       | 1.71%   |
| 131-140        | 14       | 0.41%   |
| 111-120        | 11       | 0.32%   |
| 71-80          | 9        | 0.26%   |
| 121-130        | 7        | 0.2%    |
| 81-90          | 4        | 0.12%   |
| 1-40           | 2        | 0.06%   |
| 41-50          | 1        | 0.03%   |
| 91-100         | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1960     | 59.7%   |
| 101-120       | 583      | 17.76%  |
| Unknown       | 362      | 11.03%  |
| 121-160       | 162      | 4.93%   |
| 1-50          | 140      | 4.26%   |
| 161-240       | 73       | 2.22%   |
| More than 240 | 3        | 0.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2511     | 56.29%  |
| 0     | 1302     | 29.19%  |
| 2     | 579      | 12.98%  |
| 3     | 64       | 1.43%   |
| 4     | 5        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2705     | 45.33%  |
| Intel                             | 1816     | 30.43%  |
| Qualcomm Atheros                  | 326      | 5.46%   |
| Broadcom                          | 163      | 2.73%   |
| Ralink Technology                 | 106      | 1.78%   |
| Nvidia                            | 81       | 1.36%   |
| MediaTek                          | 71       | 1.19%   |
| TP-Link                           | 70       | 1.17%   |
| Ralink                            | 46       | 0.77%   |
| Marvell Technology Group          | 39       | 0.65%   |
| Broadcom Limited                  | 39       | 0.65%   |
| Aquantia                          | 39       | 0.65%   |
| Mellanox Technologies             | 25       | 0.42%   |
| ASIX Electronics                  | 25       | 0.42%   |
| D-Link System                     | 24       | 0.4%    |
| Samsung Electronics               | 23       | 0.39%   |
| Qualcomm Atheros Communications   | 23       | 0.39%   |
| Microsoft                         | 18       | 0.3%    |
| VIA Technologies                  | 17       | 0.28%   |
| Huawei Technologies               | 17       | 0.28%   |
| D-Link                            | 17       | 0.28%   |
| ASUSTek Computer                  | 17       | 0.28%   |
| American Megatrends               | 15       | 0.25%   |
| Edimax Technology                 | 13       | 0.22%   |
| NetGear                           | 12       | 0.2%    |
| 3Com                              | 11       | 0.18%   |
| QinHeng Electronics               | 10       | 0.17%   |
| Xiaomi                            | 9        | 0.15%   |
| Gemtek                            | 8        | 0.13%   |
| Belkin Components                 | 8        | 0.13%   |
| Sigma Designs                     | 7        | 0.12%   |
| Texas Instruments                 | 5        | 0.08%   |
| Sundance Technology Inc / IC Plus | 5        | 0.08%   |
| Linksys                           | 5        | 0.08%   |
| IMC Networks                      | 5        | 0.08%   |
| IBM                               | 5        | 0.08%   |
| Emulex                            | 5        | 0.08%   |
| DisplayLink                       | 5        | 0.08%   |
| ZTE WCDMA Technologies MSM        | 4        | 0.07%   |
| Wilocity                          | 4        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2176     | 32.47%  |
| Realtek RTL8125 2.5GbE Controller                                 | 230      | 3.43%   |
| Intel I211 Gigabit Network Connection                             | 226      | 3.37%   |
| Intel Wi-Fi 6 AX200                                               | 154      | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 131      | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 130      | 1.94%   |
| Intel Ethernet Controller I225-V                                  | 124      | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 118      | 1.76%   |
| Intel Ethernet Connection I217-LM                                 | 93       | 1.39%   |
| Intel I210 Gigabit Network Connection                             | 85       | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 74       | 1.1%    |
| Intel 82574L Gigabit Network Connection                           | 69       | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 62       | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 52       | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 52       | 0.78%   |
| Intel Wireless 3165                                               | 48       | 0.72%   |
| Nvidia MCP61 Ethernet                                             | 46       | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 45       | 0.67%   |
| Intel Ethernet Connection (14) I219-V                             | 45       | 0.67%   |
| Intel Wireless-AC 9260                                            | 44       | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 43       | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 43       | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 39       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 38       | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 35       | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35       | 0.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 35       | 0.52%   |
| Intel I350 Gigabit Network Connection                             | 35       | 0.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 33       | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32       | 0.48%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 31       | 0.46%   |
| Realtek 802.11ac NIC                                              | 30       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28       | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27       | 0.4%    |
| Intel Wireless 7260                                               | 26       | 0.39%   |
| Intel Ethernet Controller I226-V                                  | 25       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 565      | 37.02%  |
| Realtek Semiconductor                 | 302      | 19.79%  |
| Qualcomm Atheros                      | 165      | 10.81%  |
| Ralink Technology                     | 106      | 6.95%   |
| MediaTek                              | 66       | 4.33%   |
| TP-Link                               | 65       | 4.26%   |
| Broadcom                              | 49       | 3.21%   |
| Ralink                                | 46       | 3.01%   |
| Qualcomm Atheros Communications       | 23       | 1.51%   |
| D-Link                                | 17       | 1.11%   |
| ASUSTek Computer                      | 17       | 1.11%   |
| Microsoft                             | 15       | 0.98%   |
| Edimax Technology                     | 13       | 0.85%   |
| NetGear                               | 12       | 0.79%   |
| D-Link System                         | 12       | 0.79%   |
| Belkin Components                     | 8        | 0.52%   |
| Broadcom Limited                      | 7        | 0.46%   |
| Gemtek                                | 6        | 0.39%   |
| Linksys                               | 5        | 0.33%   |
| IMC Networks                          | 5        | 0.33%   |
| Wilocity                              | 4        | 0.26%   |
| Marvell Technology Group              | 3        | 0.2%    |
| AVM                                   | 3        | 0.2%    |
| ZyDAS                                 | 1        | 0.07%   |
| Xiaomi                                | 1        | 0.07%   |
| TRENDnet                              | 1        | 0.07%   |
| Tenda                                 | 1        | 0.07%   |
| Sitecom Europe                        | 1        | 0.07%   |
| PLANEX                                | 1        | 0.07%   |
| Micro Star International              | 1        | 0.07%   |
| Fiberline                             | 1        | 0.07%   |
| Encore Electronics                    | 1        | 0.07%   |
| CyberTAN Technology                   | 1        | 0.07%   |
| BUFFALO                               | 1        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 154      | 10.01%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 62       | 4.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 52       | 3.38%   |
| Intel Wireless 3165                                            | 48       | 3.12%   |
| Intel Wireless-AC 9260                                         | 44       | 2.86%   |
| Ralink MT7601U Wireless Adapter                                | 43       | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35       | 2.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 35       | 2.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 33       | 2.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 2.08%   |
| Realtek 802.11ac NIC                                           | 30       | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 27       | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 27       | 1.76%   |
| Intel Wireless 7260                                            | 26       | 1.69%   |
| Ralink RT5370 Wireless Adapter                                 | 22       | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 22       | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 22       | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 21       | 1.37%   |
| Intel Wireless 7265                                            | 21       | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                | 20       | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 19       | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17       | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 17       | 1.11%   |
| Intel Wireless 8260                                            | 17       | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16       | 1.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 15       | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 15       | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15       | 0.98%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 15       | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 14       | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14       | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 13       | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 13       | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 12       | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12       | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 11       | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11       | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10       | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 10       | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2603     | 53.83%  |
| Intel                                  | 1510     | 31.22%  |
| Qualcomm Atheros                       | 175      | 3.62%   |
| Broadcom                               | 119      | 2.46%   |
| Nvidia                                 | 81       | 1.67%   |
| Aquantia                               | 39       | 0.81%   |
| Marvell Technology Group               | 37       | 0.77%   |
| Broadcom Limited                       | 32       | 0.66%   |
| ASIX Electronics                       | 25       | 0.52%   |
| Samsung Electronics                    | 23       | 0.48%   |
| Mellanox Technologies                  | 23       | 0.48%   |
| VIA Technologies                       | 17       | 0.35%   |
| American Megatrends                    | 15       | 0.31%   |
| Huawei Technologies                    | 12       | 0.25%   |
| D-Link System                          | 12       | 0.25%   |
| 3Com                                   | 11       | 0.23%   |
| Xiaomi                                 | 8        | 0.17%   |
| TP-Link                                | 5        | 0.1%    |
| Sundance Technology Inc / IC Plus      | 5        | 0.1%    |
| IBM                                    | 5        | 0.1%    |
| Emulex                                 | 5        | 0.1%    |
| DisplayLink                            | 5        | 0.1%    |
| Silicon Integrated Systems [SiS]       | 4        | 0.08%   |
| Qualcomm                               | 4        | 0.08%   |
| QLogic                                 | 4        | 0.08%   |
| Motorola PCS                           | 4        | 0.08%   |
| MediaTek                               | 4        | 0.08%   |
| ICS Advent                             | 4        | 0.08%   |
| OPPO Electronics                       | 3        | 0.06%   |
| Microsoft                              | 3        | 0.06%   |
| Insyde Software                        | 3        | 0.06%   |
| Google                                 | 3        | 0.06%   |
| ADMtek                                 | 3        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.04%   |
| SysKonnect                             | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| Solarflare Communications              | 2        | 0.04%   |
| Microchip Technology                   | 2        | 0.04%   |
| Loongson Technology                    | 2        | 0.04%   |
| Lenovo                                 | 2        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2176     | 42.88%  |
| Realtek RTL8125 2.5GbE Controller                                 | 230      | 4.53%   |
| Intel I211 Gigabit Network Connection                             | 226      | 4.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 131      | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 130      | 2.56%   |
| Intel Ethernet Controller I225-V                                  | 124      | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 118      | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 93       | 1.83%   |
| Intel I210 Gigabit Network Connection                             | 85       | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 74       | 1.46%   |
| Intel 82574L Gigabit Network Connection                           | 69       | 1.36%   |
| Intel Ethernet Connection (7) I219-V                              | 52       | 1.02%   |
| Nvidia MCP61 Ethernet                                             | 46       | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 45       | 0.89%   |
| Intel Ethernet Connection (14) I219-V                             | 45       | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 43       | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 39       | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 38       | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35       | 0.69%   |
| Intel I350 Gigabit Network Connection                             | 35       | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32       | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 31       | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28       | 0.55%   |
| Intel Ethernet Controller I226-V                                  | 25       | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 24       | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 23       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 23       | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 23       | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 21       | 0.41%   |
| Intel Ethernet Controller X550                                    | 20       | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18       | 0.35%   |
| Intel 82566DM Gigabit Network Connection                          | 18       | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18       | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17       | 0.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 17       | 0.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 16       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4351     | 74.2%   |
| WiFi     | 1429     | 24.37%  |
| Modem    | 74       | 1.26%   |
| Unknown  | 10       | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3793     | 86.01%  |
| WiFi     | 617      | 13.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2782     | 62.9%   |
| 2     | 1211     | 27.38%  |
| 3     | 248      | 5.61%   |
| 4     | 71       | 1.61%   |
| 0     | 36       | 0.81%   |
| 6     | 29       | 0.66%   |
| 5     | 22       | 0.5%    |
| 7     | 7        | 0.16%   |
| 8     | 6        | 0.14%   |
| 9     | 4        | 0.09%   |
| 12    | 3        | 0.07%   |
| 33    | 1        | 0.02%   |
| 21    | 1        | 0.02%   |
| 17    | 1        | 0.02%   |
| 13    | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3705     | 83.31%  |
| Yes     | 741      | 16.66%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 526      | 43.65%  |
| Cambridge Silicon Radio         | 244      | 20.25%  |
| Realtek Semiconductor           | 100      | 8.3%    |
| ASUSTek Computer                | 80       | 6.64%   |
| Broadcom                        | 62       | 5.15%   |
| MediaTek                        | 47       | 3.9%    |
| Qualcomm Atheros Communications | 44       | 3.65%   |
| IMC Networks                    | 26       | 2.16%   |
| TP-Link                         | 15       | 1.24%   |
| Apple                           | 14       | 1.16%   |
| Foxconn / Hon Hai               | 13       | 1.08%   |
| Lite-On Technology              | 4        | 0.33%   |
| Integrated System Solution      | 4        | 0.33%   |
| Belkin Components               | 4        | 0.33%   |
| Edimax Technology               | 3        | 0.25%   |
| Dynex                           | 3        | 0.25%   |
| Realtek                         | 2        | 0.17%   |
| Micro Star International        | 2        | 0.17%   |
| Actions                         | 2        | 0.17%   |
| Toshiba                         | 1        | 0.08%   |
| Sitecom Europe                  | 1        | 0.08%   |
| SINO WEALTH                     | 1        | 0.08%   |
| Qcom                            | 1        | 0.08%   |
| Microsoft                       | 1        | 0.08%   |
| Kensington                      | 1        | 0.08%   |
| HTC (High Tech Computer)        | 1        | 0.08%   |
| Hewlett-Packard                 | 1        | 0.08%   |
| Com One                         | 1        | 0.08%   |
| Unknown                         | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 244      | 20.23%  |
| Intel AX200 Bluetooth                                    | 148      | 12.27%  |
| Intel Bluetooth wireless interface                       | 122      | 10.12%  |
| Realtek Bluetooth Radio                                  | 84       | 6.97%   |
| Intel Wireless-AC 3168 Bluetooth                         | 59       | 4.89%   |
| MediaTek Wireless_Device                                 | 47       | 3.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 45       | 3.73%   |
| Intel AX201 Bluetooth                                    | 44       | 3.65%   |
| Intel AX210 Bluetooth                                    | 42       | 3.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 42       | 3.48%   |
| Intel Bluetooth Device                                   | 32       | 2.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 28       | 2.32%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 26       | 2.16%   |
| Qualcomm Atheros  Bluetooth Device                       | 18       | 1.49%   |
| TP-Link UB500 Adapter                                    | 15       | 1.24%   |
| IMC Networks Bluetooth Radio                             | 15       | 1.24%   |
| ASUS Bluetooth Adapter                                   | 12       | 1%      |
| ASUS ASUS USB-BT500                                      | 12       | 1%      |
| Realtek  Bluetooth 4.2 Adapter                           | 11       | 0.91%   |
| Foxconn / Hon Hai Wireless_Device                        | 10       | 0.83%   |
| ASUS Bluetooth Radio                                     | 10       | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 7        | 0.58%   |
| IMC Networks Bluetooth Device                            | 7        | 0.58%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 7        | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 6        | 0.5%    |
| Apple Bluetooth Host Controller                          | 6        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                        | 5        | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)          | 5        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 5        | 0.41%   |
| ASUS BCM20702A0                                          | 5        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5        | 0.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 4        | 0.33%   |
| ASUS Qualcomm Bluetooth 4.1                              | 4        | 0.33%   |
| ASUS Bluetooth Device                                    | 4        | 0.33%   |
| Realtek RTL8821A Bluetooth                               | 3        | 0.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 3        | 0.25%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 0.25%   |
| Lite-On Bluetooth Device                                 | 3        | 0.25%   |
| Integrated System Solution Bluetooth Device              | 3        | 0.25%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2680     | 40.45%  |
| AMD                                          | 1617     | 24.41%  |
| Nvidia                                       | 1414     | 21.34%  |
| C-Media Electronics                          | 151      | 2.28%   |
| Creative Labs                                | 72       | 1.09%   |
| Logitech                                     | 71       | 1.07%   |
| ASUSTek Computer                             | 44       | 0.66%   |
| Texas Instruments                            | 30       | 0.45%   |
| Micro Star International                     | 28       | 0.42%   |
| Generalplus Technology                       | 27       | 0.41%   |
| Focusrite-Novation                           | 26       | 0.39%   |
| GN Netcom                                    | 24       | 0.36%   |
| KTMicro                                      | 23       | 0.35%   |
| JMTek                                        | 23       | 0.35%   |
| VIA Technologies                             | 22       | 0.33%   |
| Creative Technology                          | 20       | 0.3%    |
| Kingston Technology                          | 18       | 0.27%   |
| SteelSeries ApS                              | 16       | 0.24%   |
| Plantronics                                  | 16       | 0.24%   |
| Dell                                         | 13       | 0.2%    |
| Corsair                                      | 13       | 0.2%    |
| Razer USA                                    | 12       | 0.18%   |
| Blue Microphones                             | 12       | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 11       | 0.17%   |
| Realtek Semiconductor                        | 11       | 0.17%   |
| BEHRINGER International                      | 11       | 0.17%   |
| GYROCOM C&C                                  | 9        | 0.14%   |
| RODE Microphones                             | 8        | 0.12%   |
| Yamaha                                       | 7        | 0.11%   |
| Jieli Technology                             | 7        | 0.11%   |
| Giga-Byte Technology                         | 7        | 0.11%   |
| Cambridge Silicon Radio                      | 7        | 0.11%   |
| Tenx Technology                              | 6        | 0.09%   |
| Samson Technologies                          | 6        | 0.09%   |
| M-Audio                                      | 6        | 0.09%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.08%   |
| Sennheiser Communications                    | 5        | 0.08%   |
| Microsoft                                    | 5        | 0.08%   |
| Samsung Electronics                          | 4        | 0.06%   |
| Musical Fidelity                             | 4        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 387      | 4.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 372      | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 299      | 3.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 288      | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 284      | 3.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 248      | 3.19%   |
| Intel 200 Series PCH HD Audio                                              | 234      | 3.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 214      | 2.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 208      | 2.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 194      | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 166      | 2.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 163      | 2.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 133      | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 126      | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 119      | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 115      | 1.48%   |
| AMD FCH Azalia Controller                                                  | 111      | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 107      | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 106      | 1.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94       | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 93       | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 90       | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 89       | 1.14%   |
| Nvidia High Definition Audio Controller                                    | 77       | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 77       | 0.99%   |
| Intel Comet Lake PCH cAVS                                                  | 72       | 0.93%   |
| Intel Alder Lake-S HD Audio Controller                                     | 72       | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 68       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 66       | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 64       | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 64       | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 64       | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 61       | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 61       | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 60       | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 59       | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 56       | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 55       | 0.71%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 54       | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 53       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 775      | 19.14%  |
| Unknown                      | 628      | 15.51%  |
| Crucial                      | 439      | 10.84%  |
| Samsung Electronics          | 408      | 10.07%  |
| Corsair                      | 360      | 8.89%   |
| SK hynix                     | 333      | 8.22%   |
| G.Skill                      | 287      | 7.09%   |
| Micron Technology            | 150      | 3.7%    |
| Patriot                      | 90       | 2.22%   |
| A-DATA Technology            | 78       | 1.93%   |
| Unknown                      | 52       | 1.28%   |
| Team                         | 37       | 0.91%   |
| Unknown (ABCD)               | 30       | 0.74%   |
| AMD                          | 29       | 0.72%   |
| Ramaxel Technology           | 27       | 0.67%   |
| Nanya Technology             | 27       | 0.67%   |
| Elpida                       | 22       | 0.54%   |
| Hikvision                    | 21       | 0.52%   |
| Transcend                    | 20       | 0.49%   |
| Smart                        | 16       | 0.4%    |
| Apacer                       | 12       | 0.3%    |
| GOODRAM                      | 11       | 0.27%   |
| Hewlett-Packard              | 10       | 0.25%   |
| GeIL                         | 9        | 0.22%   |
| Timetec                      | 8        | 0.2%    |
| Micro Memory Bank            | 8        | 0.2%    |
| Avant                        | 8        | 0.2%    |
| Qimonda                      | 7        | 0.17%   |
| Patriot Memory (PDP Systems) | 6        | 0.15%   |
| Unknown (0x5846)             | 5        | 0.12%   |
| Toshiba                      | 5        | 0.12%   |
| Kingmax                      | 5        | 0.12%   |
| Unknown (AB)                 | 4        | 0.1%    |
| PNY                          | 4        | 0.1%    |
| KLEVV                        | 4        | 0.1%    |
| 48spaces                     | 4        | 0.1%    |
| V-Color                      | 3        | 0.07%   |
| Unknown (0x0E9D)             | 3        | 0.07%   |
| Unknown (0x0B45)             | 3        | 0.07%   |
| Unifosa                      | 3        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 54       | 1.21%   |
| Unknown                                                        | 52       | 1.17%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s          | 38       | 0.85%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s         | 36       | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 36       | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 31       | 0.69%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s          | 31       | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 30       | 0.67%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 29       | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 27       | 0.6%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 25       | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 24       | 0.54%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s           | 24       | 0.54%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 22       | 0.49%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 21       | 0.47%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 19       | 0.43%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.4%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 18       | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 17       | 0.38%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s            | 16       | 0.36%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 16       | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 15       | 0.34%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 15       | 0.34%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 15       | 0.34%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 15       | 0.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 15       | 0.34%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 15       | 0.34%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 15       | 0.34%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 15       | 0.34%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 15       | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 14       | 0.31%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 14       | 0.31%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 14       | 0.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 13       | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 13       | 0.29%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 13       | 0.29%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 13       | 0.29%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 13       | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1664     | 45.85%  |
| DDR3         | 1166     | 32.13%  |
| Unknown      | 253      | 6.97%   |
| DDR2         | 198      | 5.46%   |
| SDRAM        | 184      | 5.07%   |
| DDR5         | 70       | 1.93%   |
| LPDDR4       | 44       | 1.21%   |
| DDR          | 40       | 1.1%    |
| DRAM         | 8        | 0.22%   |
| LPDDR3       | 1        | 0.03%   |
| DDR2 FB-DIMM | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 3221     | 89.97%  |
| SODIMM       | 319      | 8.91%   |
| Row Of Chips | 14       | 0.39%   |
| RIMM         | 12       | 0.34%   |
| FB-DIMM      | 9        | 0.25%   |
| Unknown      | 4        | 0.11%   |
| Chip         | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 1286     | 32.55%  |
| 4096    | 867      | 21.94%  |
| 16384   | 668      | 16.91%  |
| 2048    | 606      | 15.34%  |
| 32768   | 275      | 6.96%   |
| 1024    | 186      | 4.71%   |
| 512     | 44       | 1.11%   |
| 256     | 6        | 0.15%   |
| 65536   | 5        | 0.13%   |
| 128     | 2        | 0.05%   |
| 49152   | 1        | 0.03%   |
| 24576   | 1        | 0.03%   |
| 6144    | 1        | 0.03%   |
| 1536    | 1        | 0.03%   |
| 64      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 679      | 17.17%  |
| 1333    | 414      | 10.47%  |
| 3200    | 368      | 9.3%    |
| 2667    | 294      | 7.43%   |
| 2400    | 238      | 6.02%   |
| 3600    | 215      | 5.44%   |
| 2133    | 212      | 5.36%   |
| 800     | 165      | 4.17%   |
| Unknown | 135      | 3.41%   |
| 667     | 109      | 2.76%   |
| 1866    | 96       | 2.43%   |
| 2666    | 85       | 2.15%   |
| 1867    | 62       | 1.57%   |
| 3400    | 58       | 1.47%   |
| 3000    | 57       | 1.44%   |
| 3733    | 54       | 1.37%   |
| 1066    | 50       | 1.26%   |
| 2933    | 48       | 1.21%   |
| 1800    | 48       | 1.21%   |
| 4800    | 36       | 0.91%   |
| 1067    | 33       | 0.83%   |
| 3800    | 30       | 0.76%   |
| 2866    | 27       | 0.68%   |
| 3266    | 25       | 0.63%   |
| 3466    | 24       | 0.61%   |
| 3533    | 20       | 0.51%   |
| 533     | 20       | 0.51%   |
| 400     | 20       | 0.51%   |
| 6000    | 19       | 0.48%   |
| 1334    | 19       | 0.48%   |
| 4333    | 16       | 0.4%    |
| 3866    | 15       | 0.38%   |
| 3933    | 14       | 0.35%   |
| 3666    | 14       | 0.35%   |
| 3534    | 13       | 0.33%   |
| 3100    | 13       | 0.33%   |
| 2800    | 13       | 0.33%   |
| 2048    | 13       | 0.33%   |
| 5200    | 10       | 0.25%   |
| 3500    | 10       | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 54       | 30.34%  |
| Brother Industries    | 37       | 20.79%  |
| Canon                 | 24       | 13.48%  |
| Samsung Electronics   | 14       | 7.87%   |
| Seiko Epson           | 8        | 4.49%   |
| Dymo-CoStar           | 6        | 3.37%   |
| Prolific Technology   | 5        | 2.81%   |
| Lexmark International | 5        | 2.81%   |
| Zebra                 | 4        | 2.25%   |
| Xerox                 | 4        | 2.25%   |
| Pantum                | 3        | 1.69%   |
| QinHeng Electronics   | 2        | 1.12%   |
| Kyocera               | 2        | 1.12%   |
| STMicroelectronics    | 1        | 0.56%   |
| Ricoh                 | 1        | 0.56%   |
| Printer               | 1        | 0.56%   |
| Oki Data              | 1        | 0.56%   |
| nemonic               | 1        | 0.56%   |
| Konica Minolta        | 1        | 0.56%   |
| GODEX INTERNATIONAL   | 1        | 0.56%   |
| Dell                  | 1        | 0.56%   |
| Datamax-O'Neil        | 1        | 0.56%   |
| Apple                 | 1        | 0.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 3.37%   |
| Prolific PL2305 Parallel Port                             | 5        | 2.81%   |
| HP LaserJet 1200                                          | 5        | 2.81%   |
| Xerox B205                                                | 3        | 1.69%   |
| Samsung ML-1660 Series                                    | 3        | 1.69%   |
| HP LaserJet M101-M106                                     | 3        | 1.69%   |
| Brother HL-52x0 series                                    | 3        | 1.69%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.12%   |
| Samsung M2020 Series                                      | 2        | 1.12%   |
| QinHeng CH340S                                            | 2        | 1.12%   |
| Pantum P2500W series                                      | 2        | 1.12%   |
| Lexmark International CS417dn                             | 2        | 1.12%   |
| HP LaserJet Pro M404-M405                                 | 2        | 1.12%   |
| HP LaserJet P1005                                         | 2        | 1.12%   |
| HP LaserJet M14-M17                                       | 2        | 1.12%   |
| HP LaserJet 400 M401a                                     | 2        | 1.12%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.12%   |
| HP ENVY 4520 series                                       | 2        | 1.12%   |
| HP DeskJet 2700 series                                    | 2        | 1.12%   |
| HP DeskJet 2130 series                                    | 2        | 1.12%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.12%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2        | 1.12%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.12%   |
| Canon MF4410                                              | 2        | 1.12%   |
| Canon MF3010                                              | 2        | 1.12%   |
| Canon LiDE 400                                            | 2        | 1.12%   |
| Brother MFC-7460DN                                        | 2        | 1.12%   |
| Brother HL-3040CN series                                  | 2        | 1.12%   |
| Brother HL-1110 series                                    | 2        | 1.12%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.56%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.56%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.56%   |
| Zebra Printer                                             | 1        | 0.56%   |
| Xerox Phaser 3260                                         | 1        | 0.56%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.56%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.56%   |
| Seiko Epson XP-15000 Series                               | 1        | 0.56%   |
| Seiko Epson Printer                                       | 1        | 0.56%   |
| Seiko Epson M105 Series                                   | 1        | 0.56%   |
| Seiko Epson ET-4850 Series                                | 1        | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 32       | 64%     |
| Seiko Epson        | 9        | 18%     |
| Hewlett-Packard    | 4        | 8%      |
| AGFA-Gevaert NV    | 2        | 4%      |
| Ultima Electronics | 1        | 2%      |
| Plustek            | 1        | 2%      |
| Mustek Systems     | 1        | 2%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 14%     |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6        | 12%     |
| Canon CanoScan LiDE 220                                                               | 4        | 8%      |
| Canon CanoScan LiDE 210                                                               | 4        | 8%      |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 2        | 4%      |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 4%      |
| Canon CanoScan LiDE 60                                                                | 2        | 4%      |
| Canon CanoScan LIDE 25                                                                | 2        | 4%      |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 4%      |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2%      |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 2%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2%      |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 2%      |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 2%      |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 2%      |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 2%      |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 2%      |
| Plustek 1200dpi USB Scanner                                                           | 1        | 2%      |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 2%      |
| HP ScanJet Pro 2500 f1                                                                | 1        | 2%      |
| HP ScanJet 82x0C                                                                      | 1        | 2%      |
| HP ScanJet 3970c                                                                      | 1        | 2%      |
| HP Scanjet 300                                                                        | 1        | 2%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 2%      |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2%      |
| Canon CanoScan 8800F                                                                  | 1        | 2%      |
| Canon CanoScan 5600F                                                                  | 1        | 2%      |
| Canon CanoScan 4400F                                                                  | 1        | 2%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 286      | 42.69%  |
| Microdia                               | 49       | 7.31%   |
| Microsoft                              | 40       | 5.97%   |
| Generalplus Technology                 | 28       | 4.18%   |
| Samsung Electronics                    | 26       | 3.88%   |
| Sunplus Innovation Technology          | 25       | 3.73%   |
| Creative Technology                    | 17       | 2.54%   |
| Apple                                  | 15       | 2.24%   |
| Z-Star Microelectronics                | 14       | 2.09%   |
| KYE Systems (Mouse Systems)            | 14       | 2.09%   |
| Jieli Technology                       | 14       | 2.09%   |
| GEMBIRD                                | 10       | 1.49%   |
| ARC International                      | 10       | 1.49%   |
| Chicony Electronics                    | 9        | 1.34%   |
| Realtek Semiconductor                  | 6        | 0.9%    |
| MacroSilicon                           | 5        | 0.75%   |
| Huawei Technologies                    | 5        | 0.75%   |
| Hewlett-Packard                        | 5        | 0.75%   |
| HD 2MP WEBCAM                          | 4        | 0.6%    |
| Genesys Logic                          | 4        | 0.6%    |
| Cubeternet                             | 4        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.6%    |
| AVerMedia Technologies                 | 4        | 0.6%    |
| Trust                                  | 3        | 0.45%   |
| Razer USA                              | 3        | 0.45%   |
| Quanta                                 | 3        | 0.45%   |
| Novatek Microelectronics               | 3        | 0.45%   |
| Google                                 | 3        | 0.45%   |
| Aveo Technology                        | 3        | 0.45%   |
| Xiongmai                               | 2        | 0.3%    |
| Valve Software                         | 2        | 0.3%    |
| ValueHD                                | 2        | 0.3%    |
| Tobii Technology AB                    | 2        | 0.3%    |
| Syntek                                 | 2        | 0.3%    |
| Sunplus IT                             | 2        | 0.3%    |
| Ruision                                | 2        | 0.3%    |
| Nintendo                               | 2        | 0.3%    |
| IMC Networks                           | 2        | 0.3%    |
| Arkmicro Technologies                  | 2        | 0.3%    |
| Xiaomi                                 | 1        | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 76       | 11.28%  |
| Logitech HD Pro Webcam C920                       | 40       | 5.93%   |
| Logitech C922 Pro Stream Webcam                   | 29       | 4.3%    |
| Samsung Galaxy series, misc. (MTP mode)           | 25       | 3.71%   |
| Microsoft LifeCam HD-3000                         | 22       | 3.26%   |
| Generalplus GENERAL WEBCAM                        | 19       | 2.82%   |
| Logitech Webcam C170                              | 16       | 2.37%   |
| Logitech HD Webcam C525                           | 16       | 2.37%   |
| Microdia USB 2.0 Camera                           | 15       | 2.23%   |
| Logitech Webcam C310                              | 14       | 2.08%   |
| Jieli USB PHY 2.0                                 | 14       | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 14       | 2.08%   |
| Microdia Webcam Vitade AF                         | 12       | 1.78%   |
| Logitech C920 PRO HD Webcam                       | 11       | 1.63%   |
| Sunplus Full HD webcam                            | 10       | 1.48%   |
| Logitech HD Webcam C910                           | 9        | 1.34%   |
| Logitech HD Webcam C615                           | 9        | 1.34%   |
| Z-Star Venus USB2.0 Camera                        | 8        | 1.19%   |
| Sunplus MTD Camera                                | 7        | 1.04%   |
| ARC International Camera                          | 7        | 1.04%   |
| Microdia Camera                                   | 6        | 0.89%   |
| Logitech BRIO Ultra HD Webcam                     | 6        | 0.89%   |
| KYE Systems (Mouse Systems) Genius Webcam         | 6        | 0.89%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 6        | 0.89%   |
| GEMBIRD USB2.0 PC CAMERA                          | 6        | 0.89%   |
| Microdia Integrated Camera                        | 5        | 0.74%   |
| Logitech Webcam C925e                             | 5        | 0.74%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera        | 5        | 0.74%   |
| Huawei UVC Camera                                 | 5        | 0.74%   |
| Microsoft LifeCam HD-5000                         | 4        | 0.59%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 0.59%   |
| MacroSilicon USB Video                            | 4        | 0.59%   |
| Logitech Webcam C210                              | 4        | 0.59%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                       | 4        | 0.59%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4        | 0.59%   |
| Creative Live! Cam Chat HD [VF0700]               | 4        | 0.59%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 4        | 0.59%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 3        | 0.45%   |
| Realtek Full HD webcam                            | 3        | 0.45%   |
| Razer USA Gaming Webcam [Kiyo]                    | 3        | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Synaptics             | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 33.33%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 6        | 14.29%  |
| Gemalto (was Gemplus)      | 5        | 11.9%   |
| Alcor Micro                | 5        | 11.9%   |
| Realtek Semiconductor      | 4        | 9.52%   |
| Cherry                     | 4        | 9.52%   |
| Clay Logic                 | 3        | 7.14%   |
| Chicony Electronics        | 3        | 7.14%   |
| Yubico.com                 | 2        | 4.76%   |
| Reiner SCT Kartensysteme   | 2        | 4.76%   |
| Aladdin Knowledge Systems  | 2        | 4.76%   |
| Advanced Card Systems      | 2        | 4.76%   |
| OmniKey                    | 1        | 2.38%   |
| Lenovo                     | 1        | 2.38%   |
| Feitian Technologies       | 1        | 2.38%   |
| Athena Smartcard Solutions | 1        | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 9.52%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 9.52%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 9.52%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 7.14%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 4.76%   |
| Clay Logic Nitrokey Pro                                                    | 2        | 4.76%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 2        | 4.76%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 4.76%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 2.38%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.38%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 2.38%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.38%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.38%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.38%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.38%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.38%   |
| Feitian Technologies SCR301                                                | 1        | 2.38%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.38%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 2.38%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 2.38%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 2.38%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.38%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.38%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2897     | 64.98%  |
| 1     | 1339     | 30.04%  |
| 2     | 191      | 4.28%   |
| 3     | 21       | 0.47%   |
| 5     | 4        | 0.09%   |
| 4     | 3        | 0.07%   |
| 6     | 2        | 0.04%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1190     | 69.47%  |
| Net/wireless             | 160      | 9.34%   |
| Communication controller | 85       | 4.96%   |
| Unassigned class         | 80       | 4.67%   |
| Sound                    | 34       | 1.98%   |
| Multimedia controller    | 33       | 1.93%   |
| Bluetooth                | 25       | 1.46%   |
| Chipcard                 | 19       | 1.11%   |
| Net/ethernet             | 18       | 1.05%   |
| Camera                   | 15       | 0.88%   |
| Card reader              | 12       | 0.7%    |
| Storage/raid             | 10       | 0.58%   |
| Network                  | 7        | 0.41%   |
| Storage/ide              | 6        | 0.35%   |
| Modem                    | 5        | 0.29%   |
| Dvb card                 | 4        | 0.23%   |
| Tv card                  | 3        | 0.18%   |
| Fingerprint reader       | 3        | 0.18%   |
| Storage                  | 2        | 0.12%   |
| Wireless                 | 1        | 0.06%   |
| Storage/nvme             | 1        | 0.06%   |

