Debian 12 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

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

Total: 885

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | MS-7708                     | [9170f4dd42](https://linux-hardware.org/?probe=9170f4dd42) | Nov 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c8c8d15e25](https://linux-hardware.org/?probe=c8c8d15e25) | Nov 06, 2023 |
| Gigabyte      | B85M-D3H                    | [42cbdffa93](https://linux-hardware.org/?probe=42cbdffa93) | Nov 05, 2023 |
| Shuttle       | FH87                        | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| MSI           | PRO B760M-P DDR4            | [5b5425c6d8](https://linux-hardware.org/?probe=5b5425c6d8) | Nov 05, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| Apple         | Mac-F221BEC8                | [03f4055831](https://linux-hardware.org/?probe=03f4055831) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| ASRock        | H61M-HVS                    | [fbbb34a0cb](https://linux-hardware.org/?probe=fbbb34a0cb) | Nov 03, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [9495d53da4](https://linux-hardware.org/?probe=9495d53da4) | Nov 03, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [18f018a8ae](https://linux-hardware.org/?probe=18f018a8ae) | Nov 03, 2023 |
| HP            | 18E7                        | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | 18E7                        | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| Unknown       | X99-GT                      | [751ea1add9](https://linux-hardware.org/?probe=751ea1add9) | Nov 02, 2023 |
| MSI           | B450M-A PRO MAX             | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| ASRock        | X570 Taichi                 | [5ce5b321b0](https://linux-hardware.org/?probe=5ce5b321b0) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| ASRockRack    | X470D4U                     | [553af2a3c2](https://linux-hardware.org/?probe=553af2a3c2) | Nov 02, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [1ca6496a6c](https://linux-hardware.org/?probe=1ca6496a6c) | Nov 01, 2023 |
| ASUSTek       | CM6870                      | [ae34108b69](https://linux-hardware.org/?probe=ae34108b69) | Nov 01, 2023 |
| HP            | 83EE                        | [c32478cd8d](https://linux-hardware.org/?probe=c32478cd8d) | Nov 01, 2023 |
| HP            | 83EE                        | [37c7c72156](https://linux-hardware.org/?probe=37c7c72156) | Nov 01, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [0026b681e2](https://linux-hardware.org/?probe=0026b681e2) | Nov 01, 2023 |
| Unknown       | Unknown                     | [c7ce75613c](https://linux-hardware.org/?probe=c7ce75613c) | Nov 01, 2023 |
| Gigabyte      | X570 GAMING X               | [fee5d3eded](https://linux-hardware.org/?probe=fee5d3eded) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [34fe4c8733](https://linux-hardware.org/?probe=34fe4c8733) | Nov 01, 2023 |
| Unknown       | Unknown                     | [3c4e0eb4fc](https://linux-hardware.org/?probe=3c4e0eb4fc) | Nov 01, 2023 |
| Gigabyte      | H610M H DDR4                | [6e876b597c](https://linux-hardware.org/?probe=6e876b597c) | Oct 31, 2023 |
| Gigabyte      | H610M H DDR4                | [01f9a9c872](https://linux-hardware.org/?probe=01f9a9c872) | Oct 31, 2023 |
| ASUSTek       | P8Z77-M                     | [69cd55a4dc](https://linux-hardware.org/?probe=69cd55a4dc) | Oct 31, 2023 |
| Dell          | 0NW6H5 A00                  | [3f76d752df](https://linux-hardware.org/?probe=3f76d752df) | Oct 31, 2023 |
| ASRock        | H61M-HVS                    | [eccf9444b3](https://linux-hardware.org/?probe=eccf9444b3) | Oct 31, 2023 |
| Intel         | X99                         | [426c412f62](https://linux-hardware.org/?probe=426c412f62) | Oct 30, 2023 |
| Dell          | 0NW6H5 A00                  | [51694ddd7c](https://linux-hardware.org/?probe=51694ddd7c) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | [fca3ef2e73](https://linux-hardware.org/?probe=fca3ef2e73) | Oct 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [a7a54fb14a](https://linux-hardware.org/?probe=a7a54fb14a) | Oct 29, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9ca810aaa6](https://linux-hardware.org/?probe=9ca810aaa6) | Oct 29, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [e0b8432cdc](https://linux-hardware.org/?probe=e0b8432cdc) | Oct 29, 2023 |
| ASRock        | AM1B-M                      | [098a155bab](https://linux-hardware.org/?probe=098a155bab) | Oct 29, 2023 |
| Apple         | Mac-F221BEC8                | [4db0be5324](https://linux-hardware.org/?probe=4db0be5324) | Oct 29, 2023 |
| ASRock        | B450 Steel Legend           | [967ed7a2b9](https://linux-hardware.org/?probe=967ed7a2b9) | Oct 28, 2023 |
| ASRock        | B550M-ITX/ac                | [1643900d75](https://linux-hardware.org/?probe=1643900d75) | Oct 28, 2023 |
| Intel         | JSL MRD                     | [689d88c57b](https://linux-hardware.org/?probe=689d88c57b) | Oct 28, 2023 |
| ECS           | H61H2-M12                   | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
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
| Gigabyte      | B450M H                     | [102b9b2a5b](https://linux-hardware.org/?probe=102b9b2a5b) | Oct 25, 2023 |
| Unknown       | 1.1                         | [4a673ae7d0](https://linux-hardware.org/?probe=4a673ae7d0) | Oct 24, 2023 |
| MSI           | Z87-G43 GAMING              | [31129675c0](https://linux-hardware.org/?probe=31129675c0) | Oct 24, 2023 |
| Gigabyte      | X570 GAMING X               | [78716080bb](https://linux-hardware.org/?probe=78716080bb) | Oct 24, 2023 |
| MSI           | A320M-A PRO                 | [851db330be](https://linux-hardware.org/?probe=851db330be) | Oct 24, 2023 |
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
| ASUSTek       | TUF Gaming B550M-E          | [3eafc2c647](https://linux-hardware.org/?probe=3eafc2c647) | Oct 21, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ec48996f11](https://linux-hardware.org/?probe=ec48996f11) | Oct 21, 2023 |
| Gigabyte      | 990FXA-UD5                  | [98a242f151](https://linux-hardware.org/?probe=98a242f151) | Oct 21, 2023 |
| Gigabyte      | B650 GAMING X AX            | [eb853298f9](https://linux-hardware.org/?probe=eb853298f9) | Oct 21, 2023 |
| ASRock        | H77 Pro4/MVP                | [102735d7e5](https://linux-hardware.org/?probe=102735d7e5) | Oct 21, 2023 |
| Intel         | DH61HO AAG62445-102         | [b2814c5578](https://linux-hardware.org/?probe=b2814c5578) | Oct 21, 2023 |
| Gigabyte      | 970A-DS3P                   | [10fab00c5f](https://linux-hardware.org/?probe=10fab00c5f) | Oct 21, 2023 |
| Gigabyte      | B85M-D3H                    | [5a47896ccd](https://linux-hardware.org/?probe=5a47896ccd) | Oct 20, 2023 |
| Shuttle       | FH67                        | [8c36120faa](https://linux-hardware.org/?probe=8c36120faa) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [e02418f8c1](https://linux-hardware.org/?probe=e02418f8c1) | Oct 20, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [d7d89d2b1b](https://linux-hardware.org/?probe=d7d89d2b1b) | Oct 19, 2023 |
| MSI           | H110M PRO-VD                | [d0664cf154](https://linux-hardware.org/?probe=d0664cf154) | Oct 19, 2023 |
| Lenovo        | 3708 NOK                    | [398302b1e5](https://linux-hardware.org/?probe=398302b1e5) | Oct 19, 2023 |
| ASUSTek       | A68HM-K                     | [d8abffeee6](https://linux-hardware.org/?probe=d8abffeee6) | Oct 18, 2023 |
| Gigabyte      | H510M H                     | [a0282a457d](https://linux-hardware.org/?probe=a0282a457d) | Oct 18, 2023 |
| Gigabyte      | G31M-S2L                    | [4d40f6adef](https://linux-hardware.org/?probe=4d40f6adef) | Oct 18, 2023 |
| ASUSTek       | PRIME Z270-P                | [07d65e0ac6](https://linux-hardware.org/?probe=07d65e0ac6) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [fb949d7410](https://linux-hardware.org/?probe=fb949d7410) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8f79e82a3a](https://linux-hardware.org/?probe=8f79e82a3a) | Oct 17, 2023 |
| Acer          | Aspire TC-886 V:2.0         | [808704ebf0](https://linux-hardware.org/?probe=808704ebf0) | Oct 17, 2023 |
| Gigabyte      | Z270-Gaming K3              | [6827d26220](https://linux-hardware.org/?probe=6827d26220) | Oct 17, 2023 |
| ASUSTek       | PRIME H410M-R               | [aa10d84f78](https://linux-hardware.org/?probe=aa10d84f78) | Oct 17, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [da5796de02](https://linux-hardware.org/?probe=da5796de02) | Oct 17, 2023 |
| Gigabyte      | H81M-DS2                    | [9240952796](https://linux-hardware.org/?probe=9240952796) | Oct 16, 2023 |
| MSI           | PRO B660-A DDR4             | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | [bad56db313](https://linux-hardware.org/?probe=bad56db313) | Oct 16, 2023 |
| Dell          | 09KPNV A00                  | [13db34ae64](https://linux-hardware.org/?probe=13db34ae64) | Oct 16, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [6b4ccf6ef7](https://linux-hardware.org/?probe=6b4ccf6ef7) | Oct 15, 2023 |
| Gigabyte      | B450 AORUS M                | [68075a7e8f](https://linux-hardware.org/?probe=68075a7e8f) | Oct 15, 2023 |
| HP            | 2820h                       | [6b9bbe3a64](https://linux-hardware.org/?probe=6b9bbe3a64) | Oct 15, 2023 |
| ASUSTek       | PRIME Z370-P                | [c8c0c21213](https://linux-hardware.org/?probe=c8c0c21213) | Oct 14, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [3954c51f20](https://linux-hardware.org/?probe=3954c51f20) | Oct 14, 2023 |
| HP            | 2B38                        | [24fb745c2e](https://linux-hardware.org/?probe=24fb745c2e) | Oct 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [0e5e9d0e0f](https://linux-hardware.org/?probe=0e5e9d0e0f) | Oct 14, 2023 |
| ASUSTek       | B75M-PLUS                   | [c1baca90e6](https://linux-hardware.org/?probe=c1baca90e6) | Oct 13, 2023 |
| HP            | 8714                        | [1379aae868](https://linux-hardware.org/?probe=1379aae868) | Oct 13, 2023 |
| Inventec      | D CLASS A02                 | [e978ca79f0](https://linux-hardware.org/?probe=e978ca79f0) | Oct 13, 2023 |
| Gigabyte      | H510M H                     | [f5edac9c7d](https://linux-hardware.org/?probe=f5edac9c7d) | Oct 13, 2023 |
| ASUSTek       | H110M-R                     | [6b5ff499ec](https://linux-hardware.org/?probe=6b5ff499ec) | Oct 13, 2023 |
| Dell          | 0200DY A01                  | [4e207b6ab6](https://linux-hardware.org/?probe=4e207b6ab6) | Oct 12, 2023 |
| ASRock        | Z790M-ITX WiFi              | [7f65a85252](https://linux-hardware.org/?probe=7f65a85252) | Oct 12, 2023 |
| Dell          | 0CRH6C A02                  | [865292ecae](https://linux-hardware.org/?probe=865292ecae) | Oct 12, 2023 |
| ASUSTek       | B85-PLUS                    | [62e3b0f03f](https://linux-hardware.org/?probe=62e3b0f03f) | Oct 11, 2023 |
| HP            | 8714                        | [ab691c5017](https://linux-hardware.org/?probe=ab691c5017) | Oct 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [f4bae74275](https://linux-hardware.org/?probe=f4bae74275) | Oct 11, 2023 |
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
| ASUSTek       | ROG STRIX X570-E GAMING     | [94f6dd97ae](https://linux-hardware.org/?probe=94f6dd97ae) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [1756f5ba93](https://linux-hardware.org/?probe=1756f5ba93) | Oct 08, 2023 |
| HP            | 2B29                        | [ce7319c9ca](https://linux-hardware.org/?probe=ce7319c9ca) | Oct 08, 2023 |
| HP            | 0B4Ch D                     | [dfc53e2c91](https://linux-hardware.org/?probe=dfc53e2c91) | Oct 07, 2023 |
| HP            | 2B29                        | [63a83750e6](https://linux-hardware.org/?probe=63a83750e6) | Oct 07, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a5904a1aeb](https://linux-hardware.org/?probe=a5904a1aeb) | Oct 07, 2023 |
| Gigabyte      | B150M-HD3-CF                | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [765a6eb640](https://linux-hardware.org/?probe=765a6eb640) | Oct 07, 2023 |
| AWOW          | AL34                        | [8933a81f53](https://linux-hardware.org/?probe=8933a81f53) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e7cd82de49](https://linux-hardware.org/?probe=e7cd82de49) | Oct 07, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [b838717a3d](https://linux-hardware.org/?probe=b838717a3d) | Oct 07, 2023 |
| HP            | 2B38                        | [da8ed40a89](https://linux-hardware.org/?probe=da8ed40a89) | Oct 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | [096a49de1b](https://linux-hardware.org/?probe=096a49de1b) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16098f839a](https://linux-hardware.org/?probe=16098f839a) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5295ac09d9](https://linux-hardware.org/?probe=5295ac09d9) | Oct 06, 2023 |
| ECS           | H61H2-M13                   | [7a5404c2d6](https://linux-hardware.org/?probe=7a5404c2d6) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | [3f46a7499f](https://linux-hardware.org/?probe=3f46a7499f) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8a1928378](https://linux-hardware.org/?probe=b8a1928378) | Oct 04, 2023 |
| ASRock        | X370 Pro4                   | [feb4dbcc8a](https://linux-hardware.org/?probe=feb4dbcc8a) | Oct 04, 2023 |
| Gigabyte      | X570S AERO G                | [5ddc45085a](https://linux-hardware.org/?probe=5ddc45085a) | Oct 04, 2023 |
| AZW           | SEi                         | [84632f00e7](https://linux-hardware.org/?probe=84632f00e7) | Oct 04, 2023 |
| HP            | 8594                        | [320d02db05](https://linux-hardware.org/?probe=320d02db05) | Oct 04, 2023 |
| Unknown       | Unknown                     | [bceb27e642](https://linux-hardware.org/?probe=bceb27e642) | Oct 04, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [30b0594383](https://linux-hardware.org/?probe=30b0594383) | Oct 04, 2023 |
| Gigabyte      | B550M DS3H                  | [6c95b1e3b2](https://linux-hardware.org/?probe=6c95b1e3b2) | Oct 04, 2023 |
| Unknown       | Unknown                     | [3493650868](https://linux-hardware.org/?probe=3493650868) | Oct 03, 2023 |
| Gigabyte      | 5MMSV-RHD                   | [ec5e1c9b31](https://linux-hardware.org/?probe=ec5e1c9b31) | Oct 03, 2023 |
| ECS           | H61H2-M13                   | [df2309fcb0](https://linux-hardware.org/?probe=df2309fcb0) | Oct 03, 2023 |
| Gigabyte      | B85M-D3H                    | [a6aa43cf26](https://linux-hardware.org/?probe=a6aa43cf26) | Oct 03, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [04f08384ff](https://linux-hardware.org/?probe=04f08384ff) | Oct 03, 2023 |
| Gigabyte      | A320M-H-CF                  | [10ebab5a3f](https://linux-hardware.org/?probe=10ebab5a3f) | Oct 02, 2023 |
| HP            | 212B                        | [079a0c34d3](https://linux-hardware.org/?probe=079a0c34d3) | Oct 02, 2023 |
| Dell          | 0NDYHG A01                  | [c84e2b4e06](https://linux-hardware.org/?probe=c84e2b4e06) | Oct 02, 2023 |
| MSI           | MEG Z690I UNIFY             | [660b0653a3](https://linux-hardware.org/?probe=660b0653a3) | Oct 02, 2023 |
| Gigabyte      | 970A-DS3P FX                | [8f0d72cf69](https://linux-hardware.org/?probe=8f0d72cf69) | Oct 01, 2023 |
| ASRock        | J4105-ITX                   | [ee4a3e4056](https://linux-hardware.org/?probe=ee4a3e4056) | Oct 01, 2023 |
| HP            | 8055                        | [260bebafcd](https://linux-hardware.org/?probe=260bebafcd) | Oct 01, 2023 |
| HP            | ProLiant MicroServer Gen... | [aeb0b469c8](https://linux-hardware.org/?probe=aeb0b469c8) | Oct 01, 2023 |
| Google        | Jerry                       | [467be71aaf](https://linux-hardware.org/?probe=467be71aaf) | Sep 30, 2023 |
| Lenovo        | 0B98401 PRO                 | [17bb772d78](https://linux-hardware.org/?probe=17bb772d78) | Sep 29, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3473652871](https://linux-hardware.org/?probe=3473652871) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Pegatron      | JESSE                       | [3f6cf71237](https://linux-hardware.org/?probe=3f6cf71237) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| ASRock        | B450 Pro4 R2.0              | [82562e75c3](https://linux-hardware.org/?probe=82562e75c3) | Sep 28, 2023 |
| Shenzhen M... | F7BAA                       | [a59f2cf9f2](https://linux-hardware.org/?probe=a59f2cf9f2) | Sep 28, 2023 |
| MSI           | Z97 PC Mate                 | [15a7321226](https://linux-hardware.org/?probe=15a7321226) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | [18bf7cff74](https://linux-hardware.org/?probe=18bf7cff74) | Sep 27, 2023 |
| Unknown       | Unknown                     | [2bf5f64c14](https://linux-hardware.org/?probe=2bf5f64c14) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-USB3L              | [f160911c14](https://linux-hardware.org/?probe=f160911c14) | Sep 27, 2023 |
| Lenovo        | 0B98401 PRO                 | [2cdf3dac45](https://linux-hardware.org/?probe=2cdf3dac45) | Sep 27, 2023 |
| YANYU         | H17SL                       | [5966ae64d0](https://linux-hardware.org/?probe=5966ae64d0) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS440           | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [19858af3cd](https://linux-hardware.org/?probe=19858af3cd) | Sep 26, 2023 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [14c3077129](https://linux-hardware.org/?probe=14c3077129) | Sep 24, 2023 |
| MSI           | Z370-A PRO                  | [77c3039fdc](https://linux-hardware.org/?probe=77c3039fdc) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Gigabyte      | B85M-D3H                    | [e568bc8439](https://linux-hardware.org/?probe=e568bc8439) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e96b971928](https://linux-hardware.org/?probe=e96b971928) | Sep 23, 2023 |
| Dell          | 0NW6H5 A00                  | [c3221c93ca](https://linux-hardware.org/?probe=c3221c93ca) | Sep 23, 2023 |
| Dell          | 0PC5F7 A01                  | [887558c8f3](https://linux-hardware.org/?probe=887558c8f3) | Sep 23, 2023 |
| Dell          | 03KWTV A02                  | [991ec32c75](https://linux-hardware.org/?probe=991ec32c75) | Sep 23, 2023 |
| Gigabyte      | B250M-Gaming5-CF            | [f18f8ef020](https://linux-hardware.org/?probe=f18f8ef020) | Sep 23, 2023 |
| Shenzhen M... | F6BFC                       | [9a906f1b75](https://linux-hardware.org/?probe=9a906f1b75) | Sep 22, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| MSI           | X470 GAMING PLUS            | [d22a656bef](https://linux-hardware.org/?probe=d22a656bef) | Sep 22, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [2137a7a54b](https://linux-hardware.org/?probe=2137a7a54b) | Sep 22, 2023 |
| ASUSTek       | P7P55D                      | [ff8d00073e](https://linux-hardware.org/?probe=ff8d00073e) | Sep 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [f870f9e3ac](https://linux-hardware.org/?probe=f870f9e3ac) | Sep 21, 2023 |
| Gigabyte      | Z790 AERO G                 | [0c99fa225e](https://linux-hardware.org/?probe=0c99fa225e) | Sep 20, 2023 |
| iEi           | SAT3 V1.03                  | [d303736416](https://linux-hardware.org/?probe=d303736416) | Sep 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| CWWK          | MINIPC-G12                  | [003a19cc19](https://linux-hardware.org/?probe=003a19cc19) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | [6ded2501bf](https://linux-hardware.org/?probe=6ded2501bf) | Sep 20, 2023 |
| BESSTAR Te... | HM90                        | [bbb35ce98b](https://linux-hardware.org/?probe=bbb35ce98b) | Sep 20, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d9002e7e3](https://linux-hardware.org/?probe=6d9002e7e3) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c53d44303e](https://linux-hardware.org/?probe=c53d44303e) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| Gigabyte      | H81M-DS2                    | [85d35b008d](https://linux-hardware.org/?probe=85d35b008d) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | [03da63d741](https://linux-hardware.org/?probe=03da63d741) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [b06b302844](https://linux-hardware.org/?probe=b06b302844) | Sep 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [0ddcc2944f](https://linux-hardware.org/?probe=0ddcc2944f) | Sep 19, 2023 |
| HP            | 82A2                        | [cc179a17a8](https://linux-hardware.org/?probe=cc179a17a8) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a64dc1766a](https://linux-hardware.org/?probe=a64dc1766a) | Sep 18, 2023 |
| MSI           | MS-7366                     | [96731b6fc6](https://linux-hardware.org/?probe=96731b6fc6) | Sep 18, 2023 |
| ASUSTek       | J1800I-C                    | [970e148d8d](https://linux-hardware.org/?probe=970e148d8d) | Sep 18, 2023 |
| MSI           | H81M-P33                    | [d0287bbd0f](https://linux-hardware.org/?probe=d0287bbd0f) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [3faff3c0aa](https://linux-hardware.org/?probe=3faff3c0aa) | Sep 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [cfa7fbd3fe](https://linux-hardware.org/?probe=cfa7fbd3fe) | Sep 18, 2023 |
| AZW           | U59                         | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Gigabyte      | H97-HD3                     | [ac1361d323](https://linux-hardware.org/?probe=ac1361d323) | Sep 17, 2023 |
| HP            | 1905                        | [688c5ddf16](https://linux-hardware.org/?probe=688c5ddf16) | Sep 17, 2023 |
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
| ASUSTek       | M5A78L-M LE/USB3            | [923d176004](https://linux-hardware.org/?probe=923d176004) | Sep 15, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [caba916cf4](https://linux-hardware.org/?probe=caba916cf4) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [2f12035902](https://linux-hardware.org/?probe=2f12035902) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [c46a08bb48](https://linux-hardware.org/?probe=c46a08bb48) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [aa351597ea](https://linux-hardware.org/?probe=aa351597ea) | Sep 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | [e9d6d94486](https://linux-hardware.org/?probe=e9d6d94486) | Sep 15, 2023 |
| JINGSHA       | X99-D8I                     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | PRIME H510M-A               | [b66654e80e](https://linux-hardware.org/?probe=b66654e80e) | Sep 14, 2023 |
| ASUSTek       | P8H61/USB3                  | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| SolidRun      | CEX7 Platform               | [2a695cf7f9](https://linux-hardware.org/?probe=2a695cf7f9) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [f6bc099f62](https://linux-hardware.org/?probe=f6bc099f62) | Sep 13, 2023 |
| SolidRun      | CEX7 Platform               | [06b4774756](https://linux-hardware.org/?probe=06b4774756) | Sep 13, 2023 |
| ASUSTek       | H110M-R                     | [3530c6e606](https://linux-hardware.org/?probe=3530c6e606) | Sep 13, 2023 |
| Supermicro    | X11SSH-F                    | [3a9630bdc5](https://linux-hardware.org/?probe=3a9630bdc5) | Sep 13, 2023 |
| Gigabyte      | H110M-H-CF                  | [31cc220aae](https://linux-hardware.org/?probe=31cc220aae) | Sep 12, 2023 |
| Dell          | 02N3WF A01                  | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| ASUSTek       | H110M-K                     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| MSI           | H510M-A PRO                 | [f1a2a6d936](https://linux-hardware.org/?probe=f1a2a6d936) | Sep 12, 2023 |
| Gigabyte      | GA-870A-UD3                 | [b3acd03fb0](https://linux-hardware.org/?probe=b3acd03fb0) | Sep 12, 2023 |
| Dell          | 0GM819                      | [9917a9587a](https://linux-hardware.org/?probe=9917a9587a) | Sep 12, 2023 |
| ASRock        | B560M-HDV                   | [4df04c540a](https://linux-hardware.org/?probe=4df04c540a) | Sep 11, 2023 |
| Gigabyte      | M68MT-S2                    | [cb129260e1](https://linux-hardware.org/?probe=cb129260e1) | Sep 11, 2023 |
| ECS           | G31T-M9                     | [9d2ba7fe88](https://linux-hardware.org/?probe=9d2ba7fe88) | Sep 11, 2023 |
| Gigabyte      | GA-M56S-S3                  | [df2602c134](https://linux-hardware.org/?probe=df2602c134) | Sep 11, 2023 |
| MSI           | MS-B9091                    | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| HP            | 8643 SMVB                   | [867d0c64be](https://linux-hardware.org/?probe=867d0c64be) | Sep 11, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [6db516900f](https://linux-hardware.org/?probe=6db516900f) | Sep 10, 2023 |
| MSI           | Z370-A PRO                  | [b23d13eddc](https://linux-hardware.org/?probe=b23d13eddc) | Sep 10, 2023 |
| Shenzhen M... | HX90G                       | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| ASUSTek       | TS10                        | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| MSI           | B350 TOMAHAWK               | [2a7d4dfb14](https://linux-hardware.org/?probe=2a7d4dfb14) | Sep 09, 2023 |
| Gigabyte      | B85M-D3H                    | [9e26f5a8d3](https://linux-hardware.org/?probe=9e26f5a8d3) | Sep 09, 2023 |
| AZW           | U59                         | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| MSI           | MS-B9091                    | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e9fc2a82f](https://linux-hardware.org/?probe=5e9fc2a82f) | Sep 09, 2023 |
| ASRock        | AB350 Gaming-ITX/ac         | [a4e0bc39ba](https://linux-hardware.org/?probe=a4e0bc39ba) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | [9b24a3d874](https://linux-hardware.org/?probe=9b24a3d874) | Sep 09, 2023 |
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
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| HP            | 1825                        | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Dell          | 0GM819                      | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| HP            | 82A2                        | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Unknown       | Unknown                     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| MSI           | MAG B560 TORPEDO            | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Supermicro    | H12SSL-i                    | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
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
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Foxconn       | 2ADA                        | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Lenovo        | 1036 NO DPK                 | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| ASUSTek       | Z170-A                      | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Unknown       | Unknown                     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Intel         | X99H                        | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
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
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| Unknown       | Unknown                     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| MSI           | 2A9C                        | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| Unknown       | Unknown                     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| Google        | Guado                       | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| HP            | 2B38                        | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| ASRock        | B550 Taichi Razer Editio... | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Shenzhen M... | F6BFC                       | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| OEM           | Unknown                     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Dell          | 0PU052                      | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| Biostar       | X370GTN                     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| ASUSTek       | K30BF_M32BF                 | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Acer          | Aspire X1700                | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0CRH6C A02                  | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| ASUSTek       | P8H67-M                     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Intel         | H81                         | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | 2B38                        | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| ASUSTek       | PRIME B450M-A               | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| HP            | 2820h                       | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
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
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Gigabyte      | Z690 AERO G                 | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| ASUSTek       | H81M-C                      | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| MSI           | H110M PRO-VD                | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | E35M1-M                     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| Gigabyte      | M61PME-S2                   | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| ASRock        | H470M-HVS                   | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| ASUSTek       | P5B-VM SE                   | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASRock        | H470M-HVS                   | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| ASRock        | H470M-HVS                   | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ECS           | G31T-M9                     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| ASRock        | H470M-HVS                   | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| ASUSTek       | PRIME X470-PRO              | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Intel         | STK2M3W64CC H89289-506      | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| ASUSTek       | M4A88T-M                    | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| HP            | 8076 MVB,A                  | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| HP            | 82B4                        | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Intel         | D945GCPE AAD97209-201       | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| HP            | 3648h                       | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 6.1.0-4-amd64                    | 152      | 21.41%  |
| 6.1.0-9-amd64                    | 92       | 12.96%  |
| 6.1.0-10-amd64                   | 91       | 12.82%  |
| 6.1.0-13-amd64                   | 85       | 11.97%  |
| 6.1.0-11-amd64                   | 66       | 9.3%    |
| 6.1.0-12-amd64                   | 60       | 8.45%   |
| 6.1.0-7-amd64                    | 29       | 4.08%   |
| 6.1.0-6-amd64                    | 13       | 1.83%   |
| 6.1.0-3-amd64                    | 12       | 1.69%   |
| 6.1.0-5-amd64                    | 10       | 1.41%   |
| 6.4.0-0.deb12.2-amd64            | 9        | 1.27%   |
| 6.2.16-3-pve                     | 8        | 1.13%   |
| 6.2.16-14-pve                    | 6        | 0.85%   |
| 6.1.0-8-amd64                    | 6        | 0.85%   |
| 6.2.16-15-pve                    | 5        | 0.7%    |
| 6.2.16-12-pve                    | 5        | 0.7%    |
| 6.2.16-8-pve                     | 3        | 0.42%   |
| 6.2.16-6-pve                     | 3        | 0.42%   |
| 6.0.0-6-amd64                    | 3        | 0.42%   |
| 6.2.16-10-pve                    | 2        | 0.28%   |
| 6.0.0-2-amd64                    | 2        | 0.28%   |
| 96.5.7-srb-hydramd-g5608462499cf | 1        | 0.14%   |
| 6.5.7                            | 1        | 0.14%   |
| 6.5.5-2-liquorix-amd64           | 1        | 0.14%   |
| 6.5.3-amd64                      | 1        | 0.14%   |
| 6.5.0-0.deb12.1-rt-amd64         | 1        | 0.14%   |
| 6.4.6-1-liquorix-amd64           | 1        | 0.14%   |
| 6.4.3-1-liquorix-amd64           | 1        | 0.14%   |
| 6.4.11-1-liquorix-amd64          | 1        | 0.14%   |
| 6.4.10-3-liquorix-amd64          | 1        | 0.14%   |
| 6.4.0-1mx-ahs-amd64              | 1        | 0.14%   |
| 6.4.0-01280-g7116cae43716        | 1        | 0.14%   |
| 6.3.9-i7                         | 1        | 0.14%   |
| 6.3.5-x64v3-xanmod1              | 1        | 0.14%   |
| 6.3.3-tkg-cfs                    | 1        | 0.14%   |
| 6.3.0-1-amd64                    | 1        | 0.14%   |
| 6.3.0-0-amd64                    | 1        | 0.14%   |
| 6.2.8-x64v3-xanmod1              | 1        | 0.14%   |
| 6.2.16-5-pve                     | 1        | 0.14%   |
| 6.2.16-4-pve                     | 1        | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.0    | 604      | 87.54%  |
| 6.2.16   | 35       | 5.07%   |
| 6.4.0    | 11       | 1.59%   |
| 6.0.0    | 7        | 1.01%   |
| 5.10.0   | 4        | 0.58%   |
| 6.3.0    | 2        | 0.29%   |
| 96.5.7   | 1        | 0.14%   |
| 6.5.7    | 1        | 0.14%   |
| 6.5.5    | 1        | 0.14%   |
| 6.5.3    | 1        | 0.14%   |
| 6.5.0    | 1        | 0.14%   |
| 6.4.6    | 1        | 0.14%   |
| 6.4.3    | 1        | 0.14%   |
| 6.4.11   | 1        | 0.14%   |
| 6.4.10   | 1        | 0.14%   |
| 6.3.9    | 1        | 0.14%   |
| 6.3.5    | 1        | 0.14%   |
| 6.3.3    | 1        | 0.14%   |
| 6.2.8    | 1        | 0.14%   |
| 6.2.11   | 1        | 0.14%   |
| 6.1.9    | 1        | 0.14%   |
| 6.1.55   | 1        | 0.14%   |
| 6.1.52   | 1        | 0.14%   |
| 6.1.38   | 1        | 0.14%   |
| 6.1.27   | 1        | 0.14%   |
| 6.1.13   | 1        | 0.14%   |
| 6.1.11   | 1        | 0.14%   |
| 5.15.90  | 1        | 0.14%   |
| 5.15.108 | 1        | 0.14%   |
| 5.15.0   | 1        | 0.14%   |
| 5.10.142 | 1        | 0.14%   |
| 4.19.0   | 1        | 0.14%   |
| 4.1.42   | 1        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 611      | 88.55%  |
| 6.2     | 37       | 5.36%   |
| 6.4     | 15       | 2.17%   |
| 6.0     | 7        | 1.01%   |
| 6.3     | 5        | 0.72%   |
| 5.10    | 5        | 0.72%   |
| 6.5     | 4        | 0.58%   |
| 5.15    | 3        | 0.43%   |
| 96.5    | 1        | 0.14%   |
| 4.19    | 1        | 0.14%   |
| 4.1     | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 679      | 98.98%  |
| i686        | 2        | 0.29%   |
| armv7l      | 2        | 0.29%   |
| ppc64       | 1        | 0.15%   |
| loongarch64 | 1        | 0.15%   |
| aarch64     | 1        | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 252      | 36.57%  |
| GNOME             | 159      | 23.08%  |
| KDE5              | 120      | 17.42%  |
| XFCE              | 52       | 7.55%   |
| MATE              | 32       | 4.64%   |
| X-Cinnamon        | 30       | 4.35%   |
| LXQt              | 12       | 1.74%   |
| LXDE              | 11       | 1.6%    |
| i3                | 5        | 0.73%   |
| GNOME Flashback   | 4        | 0.58%   |
| Cinnamon          | 4        | 0.58%   |
| openbox           | 2        | 0.29%   |
| x-session-manager | 1        | 0.15%   |
| Trinity           | 1        | 0.15%   |
| GNOME Classic     | 1        | 0.15%   |
| dwm               | 1        | 0.15%   |
| Cutefish          | 1        | 0.15%   |
| Budgie            | 1        | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 271      | 39.16%  |
| Unknown | 202      | 29.19%  |
| Wayland | 157      | 22.69%  |
| Tty     | 62       | 8.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 388      | 56.15%  |
| LightDM | 105      | 15.2%   |
| GDM3    | 104      | 15.05%  |
| SDDM    | 85       | 12.3%   |
| LXDM    | 3        | 0.43%   |
| XDM     | 2        | 0.29%   |
| SLiM    | 2        | 0.29%   |
| Ly      | 1        | 0.14%   |
| GDM     | 1        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 230      | 33.48%  |
| ru_RU      | 174      | 25.33%  |
| de_DE      | 53       | 7.71%   |
| en_GB      | 34       | 4.95%   |
| Unknown    | 24       | 3.49%   |
| pt_BR      | 19       | 2.77%   |
| fr_FR      | 17       | 2.47%   |
| es_ES      | 16       | 2.33%   |
| en_CA      | 13       | 1.89%   |
| it_IT      | 12       | 1.75%   |
| pl_PL      | 9        | 1.31%   |
| en_IN      | 7        | 1.02%   |
| es_AR      | 6        | 0.87%   |
| en_ZA      | 6        | 0.87%   |
| en_AU      | 6        | 0.87%   |
| zh_CN      | 5        | 0.73%   |
| hu_HU      | 5        | 0.73%   |
| nl_NL      | 4        | 0.58%   |
| fi_FI      | 4        | 0.58%   |
| fr_BE      | 3        | 0.44%   |
| es_PE      | 3        | 0.44%   |
| en_IE      | 3        | 0.44%   |
| nl_BE      | 2        | 0.29%   |
| ja_JP      | 2        | 0.29%   |
| es_VE      | 2        | 0.29%   |
| es_CL      | 2        | 0.29%   |
| de_AT      | 2        | 0.29%   |
| ca_ES      | 2        | 0.29%   |
| C          | 2        | 0.29%   |
| zh_TW      | 1        | 0.15%   |
| sv_SE      | 1        | 0.15%   |
| pt_PT      | 1        | 0.15%   |
| nb_NO      | 1        | 0.15%   |
| lt_LT      | 1        | 0.15%   |
| ko_KR      | 1        | 0.15%   |
| it_IT@euro | 1        | 0.15%   |
| id_ID      | 1        | 0.15%   |
| fr_CA      | 1        | 0.15%   |
| et_EE      | 1        | 0.15%   |
| es_MX      | 1        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 392      | 56.89%  |
| EFI  | 297      | 43.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 435      | 62.95%  |
| Overlay | 182      | 26.34%  |
| Btrfs   | 36       | 5.21%   |
| Zfs     | 14       | 2.03%   |
| Tmpfs   | 13       | 1.88%   |
| Xfs     | 8        | 1.16%   |
| XXXXX   | 1        | 0.14%   |
| Ext3    | 1        | 0.14%   |
| Unknown | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 344      | 50%     |
| MBR     | 209      | 30.38%  |
| Unknown | 135      | 19.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 582      | 84.47%  |
| Yes       | 107      | 15.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 410      | 59.68%  |
| Yes       | 277      | 40.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 194      | 28.28%  |
| Gigabyte Technology                  | 121      | 17.64%  |
| MSI                                  | 70       | 10.2%   |
| ASRock                               | 65       | 9.48%   |
| Hewlett-Packard                      | 41       | 5.98%   |
| Lenovo                               | 36       | 5.25%   |
| Dell                                 | 29       | 4.23%   |
| Unknown                              | 18       | 2.62%   |
| Intel                                | 16       | 2.33%   |
| Fujitsu                              | 10       | 1.46%   |
| Supermicro                           | 8        | 1.17%   |
| Acer                                 | 7        | 1.02%   |
| Foxconn                              | 6        | 0.87%   |
| ECS                                  | 6        | 0.87%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.73%   |
| AZW                                  | 5        | 0.73%   |
| Biostar                              | 4        | 0.58%   |
| Shuttle                              | 3        | 0.44%   |
| Huanan                               | 3        | 0.44%   |
| Google                               | 3        | 0.44%   |
| BESSTAR Tech                         | 3        | 0.44%   |
| ASRockRack                           | 3        | 0.44%   |
| Apple                                | 3        | 0.44%   |
| Techvision                           | 2        | 0.29%   |
| Pegatron                             | 2        | 0.29%   |
| JINGSHA                              | 2        | 0.29%   |
| HC Technology.                       | 2        | 0.29%   |
| CWWK                                 | 2        | 0.29%   |
| YANYU                                | 1        | 0.15%   |
| SolidRun                             | 1        | 0.15%   |
| QTQD                                 | 1        | 0.15%   |
| PCWare                               | 1        | 0.15%   |
| OEM                                  | 1        | 0.15%   |
| Medion                               | 1        | 0.15%   |
| Loongson                             | 1        | 0.15%   |
| langchao                             | 1        | 0.15%   |
| JGINYUE                              | 1        | 0.15%   |
| Inventec                             | 1        | 0.15%   |
| Inspur                               | 1        | 0.15%   |
| iEi                                  | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 30       | 4.37%   |
| Unknown                             | 21       | 3.06%   |
| ASRock H470M-HVS                    | 20       | 2.92%   |
| Lenovo ThinkCentre M55p 8808D8U     | 12       | 1.75%   |
| ASUS PRIME B450M-K                  | 11       | 1.6%    |
| Gigabyte H81M-S2V                   | 8        | 1.17%   |
| MSI MS-7996                         | 7        | 1.02%   |
| Gigabyte A320M-S2H V2               | 7        | 1.02%   |
| ASUS S20 K29                        | 6        | 0.87%   |
| ASUS ProArt X670E-CREATOR WIFI      | 6        | 0.87%   |
| Gigabyte X570 GAMING X              | 5        | 0.73%   |
| Supermicro SYS-5019S-ML             | 4        | 0.58%   |
| ECS G31T-M9                         | 4        | 0.58%   |
| ASUS ROG STRIX X570-E GAMING        | 4        | 0.58%   |
| Lenovo ThinkStation P520 30BFS44D00 | 3        | 0.44%   |
| Intel X99                           | 3        | 0.44%   |
| Intel Jasper Lake Client Platform   | 3        | 0.44%   |
| Gigabyte M56S-S3                    | 3        | 0.44%   |
| Gigabyte B550M DS3H                 | 3        | 0.44%   |
| Gigabyte B450M H                    | 3        | 0.44%   |
| Gigabyte B450 AORUS ELITE           | 3        | 0.44%   |
| Dell OptiPlex 755                   | 3        | 0.44%   |
| Dell OptiPlex 7050                  | 3        | 0.44%   |
| ASUS ROG STRIX B550-F GAMING        | 3        | 0.44%   |
| ASUS PRIME B450M-A                  | 3        | 0.44%   |
| ASUS H110M-R                        | 3        | 0.44%   |
| Techvision TVI7309X                 | 2        | 0.29%   |
| Supermicro X8ST3                    | 2        | 0.29%   |
| MSI MS-7C56                         | 2        | 0.29%   |
| MSI MS-7C51                         | 2        | 0.29%   |
| MSI MS-7C37                         | 2        | 0.29%   |
| MSI MS-7C02                         | 2        | 0.29%   |
| MSI MS-7B86                         | 2        | 0.29%   |
| MSI MS-7B85                         | 2        | 0.29%   |
| MSI MS-7B79                         | 2        | 0.29%   |
| MSI MS-7A38                         | 2        | 0.29%   |
| MSI MS-7A34                         | 2        | 0.29%   |
| MSI MS-7817                         | 2        | 0.29%   |
| Huanan X99-F8 GAMING V2.0           | 2        | 0.29%   |
| HP Z230 Tower Workstation           | 2        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 47       | 6.85%   |
| ASUS All                | 30       | 4.37%   |
| ASUS ROG                | 27       | 3.94%   |
| Lenovo ThinkCentre      | 23       | 3.35%   |
| Unknown                 | 21       | 3.06%   |
| ASRock H470M-HVS        | 20       | 2.92%   |
| Dell OptiPlex           | 16       | 2.33%   |
| ASUS TUF                | 13       | 1.9%    |
| HP ProDesk              | 9        | 1.31%   |
| Lenovo ThinkStation     | 8        | 1.17%   |
| Gigabyte X570           | 8        | 1.17%   |
| Gigabyte H81M-S2V       | 8        | 1.17%   |
| MSI MS-7996             | 7        | 1.02%   |
| HP EliteDesk            | 7        | 1.02%   |
| Gigabyte B450M          | 7        | 1.02%   |
| Gigabyte B450           | 7        | 1.02%   |
| Gigabyte A320M-S2H      | 7        | 1.02%   |
| Gigabyte B550M          | 6        | 0.87%   |
| Fujitsu ESPRIMO         | 6        | 0.87%   |
| Dell Precision          | 6        | 0.87%   |
| ASUS S20                | 6        | 0.87%   |
| ASUS ProArt             | 6        | 0.87%   |
| HP Compaq               | 5        | 0.73%   |
| Acer Aspire             | 5        | 0.73%   |
| Supermicro SYS-5019S-ML | 4        | 0.58%   |
| ECS G31T-M9             | 4        | 0.58%   |
| ASUS P5G41T-M           | 4        | 0.58%   |
| Intel X99               | 3        | 0.44%   |
| Intel Jasper            | 3        | 0.44%   |
| Huanan X99-F8           | 3        | 0.44%   |
| Gigabyte M56S-S3        | 3        | 0.44%   |
| Gigabyte B550           | 3        | 0.44%   |
| Dell PowerEdge          | 3        | 0.44%   |
| ASUS Pro                | 3        | 0.44%   |
| ASUS H110M-R            | 3        | 0.44%   |
| ASRock X370             | 3        | 0.44%   |
| ASRock B450             | 3        | 0.44%   |
| Techvision TVI7309X     | 2        | 0.29%   |
| Supermicro X8ST3        | 2        | 0.29%   |
| MSI MS-7C56             | 2        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 67       | 9.77%   |
| 2022    | 66       | 9.62%   |
| 2021    | 66       | 9.62%   |
| 2020    | 61       | 8.89%   |
| 2019    | 48       | 7%      |
| 2014    | 45       | 6.56%   |
| 2012    | 39       | 5.69%   |
| 2015    | 34       | 4.96%   |
| 2013    | 34       | 4.96%   |
| 2023    | 33       | 4.81%   |
| 2009    | 31       | 4.52%   |
| 2017    | 30       | 4.37%   |
| 2007    | 29       | 4.23%   |
| 2016    | 28       | 4.08%   |
| 2010    | 26       | 3.79%   |
| 2011    | 22       | 3.21%   |
| 2008    | 20       | 2.92%   |
| Unknown | 6        | 0.87%   |
| 2002    | 1        | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 686      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 664      | 96.79%  |
| Enabled  | 22       | 3.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 684      | 99.71%  |
| Yes  | 2        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 143      | 20.63%  |
| 16.01-24.0      | 137      | 19.77%  |
| 4.01-8.0        | 107      | 15.44%  |
| 8.01-16.0       | 91       | 13.13%  |
| 3.01-4.0        | 84       | 12.12%  |
| 64.01-256.0     | 70       | 10.1%   |
| 24.01-32.0      | 23       | 3.32%   |
| 1.01-2.0        | 21       | 3.03%   |
| 2.01-3.0        | 7        | 1.01%   |
| More than 256.0 | 5        | 0.72%   |
| 0.51-1.0        | 4        | 0.58%   |
| Unknown         | 1        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 149      | 21.13%  |
| 4.01-8.0    | 147      | 20.85%  |
| 1.01-2.0    | 143      | 20.28%  |
| 2.01-3.0    | 107      | 15.18%  |
| 3.01-4.0    | 72       | 10.21%  |
| 8.01-16.0   | 40       | 5.67%   |
| 0.01-0.5    | 21       | 2.98%   |
| 16.01-24.0  | 14       | 1.99%   |
| 24.01-32.0  | 5        | 0.71%   |
| 32.01-64.0  | 4        | 0.57%   |
| 64.01-256.0 | 2        | 0.28%   |
| Unknown     | 1        | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 319      | 46.03%  |
| 2      | 177      | 25.54%  |
| 3      | 87       | 12.55%  |
| 4      | 51       | 7.36%   |
| 5      | 19       | 2.74%   |
| 6      | 16       | 2.31%   |
| 0      | 5        | 0.72%   |
| 8      | 4        | 0.58%   |
| 7      | 4        | 0.58%   |
| 9      | 3        | 0.43%   |
| 10     | 2        | 0.29%   |
| 32     | 1        | 0.14%   |
| 29     | 1        | 0.14%   |
| 27     | 1        | 0.14%   |
| 19     | 1        | 0.14%   |
| 17     | 1        | 0.14%   |
| 11     | 1        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 499      | 72.63%  |
| Yes       | 188      | 27.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 677      | 98.69%  |
| No        | 9        | 1.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 433      | 63.03%  |
| Yes       | 254      | 36.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 471      | 68.16%  |
| Yes       | 220      | 31.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 195      | 28.3%   |
| USA          | 105      | 15.24%  |
| Germany      | 78       | 11.32%  |
| Brazil       | 25       | 3.63%   |
| UK           | 23       | 3.34%   |
| France       | 21       | 3.05%   |
| Spain        | 20       | 2.9%    |
| Italy        | 18       | 2.61%   |
| Canada       | 16       | 2.32%   |
| Poland       | 14       | 2.03%   |
| Netherlands  | 11       | 1.6%    |
| India        | 9        | 1.31%   |
| Australia    | 8        | 1.16%   |
| Argentina    | 8        | 1.16%   |
| Hungary      | 7        | 1.02%   |
| Finland      | 7        | 1.02%   |
| Switzerland  | 6        | 0.87%   |
| Portugal     | 6        | 0.87%   |
| Belgium      | 6        | 0.87%   |
| Austria      | 6        | 0.87%   |
| South Africa | 5        | 0.73%   |
| Slovakia     | 5        | 0.73%   |
| Mexico       | 5        | 0.73%   |
| Japan        | 5        | 0.73%   |
| Sweden       | 4        | 0.58%   |
| Romania      | 4        | 0.58%   |
| Indonesia    | 4        | 0.58%   |
| Hong Kong    | 4        | 0.58%   |
| China        | 4        | 0.58%   |
| Peru         | 3        | 0.44%   |
| Norway       | 3        | 0.44%   |
| Greece       | 3        | 0.44%   |
| Czechia      | 3        | 0.44%   |
| Vietnam      | 2        | 0.29%   |
| Venezuela    | 2        | 0.29%   |
| Thailand     | 2        | 0.29%   |
| Singapore    | 2        | 0.29%   |
| Serbia       | 2        | 0.29%   |
| Philippines  | 2        | 0.29%   |
| Morocco      | 2        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 152      | 21.87%  |
| Bangor            | 17       | 2.45%   |
| Moscow            | 8        | 1.15%   |
| Frankfurt am Main | 8        | 1.15%   |
| St Petersburg     | 7        | 1.01%   |
| Paris             | 6        | 0.86%   |
| Ufa               | 5        | 0.72%   |
| Toronto           | 5        | 0.72%   |
| Manchester        | 5        | 0.72%   |
| Berlin            | 5        | 0.72%   |
| Vienna            | 4        | 0.58%   |
| Rozhanovce        | 4        | 0.58%   |
| Rio de Janeiro    | 4        | 0.58%   |
| Madrid            | 4        | 0.58%   |
| Hamburg           | 4        | 0.58%   |
| Gladbeck          | 4        | 0.58%   |
| Utrecht           | 3        | 0.43%   |
| Stockholm         | 3        | 0.43%   |
| Ruda Śląska     | 3        | 0.43%   |
| Ottawa            | 3        | 0.43%   |
| Milan             | 3        | 0.43%   |
| Lima              | 3        | 0.43%   |
| Budapest          | 3        | 0.43%   |
| Bonn              | 3        | 0.43%   |
| Amsterdam         | 3        | 0.43%   |
| Zurich            | 2        | 0.29%   |
| Verkhnyaya Salda  | 2        | 0.29%   |
| Veliky Novgorod   | 2        | 0.29%   |
| Tsukuba           | 2        | 0.29%   |
| Tel Aviv          | 2        | 0.29%   |
| Sydney            | 2        | 0.29%   |
| Stuttgart         | 2        | 0.29%   |
| Singapore         | 2        | 0.29%   |
| Sacramento        | 2        | 0.29%   |
| Roanoke           | 2        | 0.29%   |
| Richmond          | 2        | 0.29%   |
| Recife            | 2        | 0.29%   |
| Perm              | 2        | 0.29%   |
| Paderborn         | 2        | 0.29%   |
| Oslo              | 2        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 217      | 394    | 18.36%  |
| Samsung Electronics         | 168      | 255    | 14.21%  |
| Seagate                     | 157      | 244    | 13.28%  |
| Crucial                     | 81       | 96     | 6.85%   |
| Kingston                    | 77       | 83     | 6.51%   |
| Toshiba                     | 75       | 105    | 6.35%   |
| SanDisk                     | 49       | 58     | 4.15%   |
| Hitachi                     | 39       | 52     | 3.3%    |
| Netac                       | 26       | 27     | 2.2%    |
| Intel                       | 19       | 25     | 1.61%   |
| HGST                        | 17       | 63     | 1.44%   |
| China                       | 17       | 20     | 1.44%   |
| Unknown                     | 15       | 22     | 1.27%   |
| A-DATA Technology           | 13       | 15     | 1.1%    |
| Transcend                   | 10       | 16     | 0.85%   |
| SPCC                        | 10       | 11     | 0.85%   |
| Kingston Technology Company | 10       | 15     | 0.85%   |
| Silicon Motion              | 8        | 8      | 0.68%   |
| Micron Technology           | 8        | 9      | 0.68%   |
| Hewlett-Packard             | 8        | 10     | 0.68%   |
| GOODRAM                     | 8        | 16     | 0.68%   |
| SK hynix                    | 7        | 8      | 0.59%   |
| Corsair                     | 7        | 11     | 0.59%   |
| PNY                         | 6        | 8      | 0.51%   |
| Patriot                     | 6        | 6      | 0.51%   |
| MAXIO Technology (Hangzhou) | 6        | 7      | 0.51%   |
| Plextor                     | 5        | 5      | 0.42%   |
| Phison Electronics          | 5        | 11     | 0.42%   |
| Phison                      | 5        | 6      | 0.42%   |
| Maxtor                      | 5        | 5      | 0.42%   |
| KIOXIA-EXCERIA              | 5        | 5      | 0.42%   |
| XPG                         | 4        | 7      | 0.34%   |
| OCZ                         | 4        | 4      | 0.34%   |
| Micron/Crucial Technology   | 4        | 5      | 0.34%   |
| Gigabyte Technology         | 4        | 4      | 0.34%   |
| Apacer                      | 4        | 8      | 0.34%   |
| LITEON                      | 3        | 3      | 0.25%   |
| KIOXIA                      | 3        | 3      | 0.25%   |
| JMicron Technology          | 3        | 3      | 0.25%   |
| Intenso                     | 3        | 3      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Crucial CT480BX500SSD1 480GB                          | 22       | 1.59%   |
| Netac SSD 240GB                                       | 19       | 1.38%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 16       | 1.16%   |
| Crucial CT240BX500SSD1 240GB                          | 16       | 1.16%   |
| Kingston SA400S37240G 240GB SSD                       | 15       | 1.09%   |
| Toshiba HDWD110 1TB                                   | 14       | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB                        | 13       | 0.94%   |
| Seagate ST1000DM003-1ER162 1TB                        | 13       | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 13       | 0.94%   |
| Samsung SSD 980 PRO 1TB                               | 12       | 0.87%   |
| Toshiba DT01ACA100 1TB                                | 11       | 0.8%    |
| Toshiba DT01ACA050 500GB                              | 11       | 0.8%    |
| Samsung SSD 860 EVO 500GB                             | 11       | 0.8%    |
| Kingston SA400S37120G 120GB SSD                       | 11       | 0.8%    |
| Crucial CT1000MX500SSD1 1TB                           | 11       | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 10       | 0.72%   |
| Kingston SA400S37480G 480GB SSD                       | 10       | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 9        | 0.65%   |
| Seagate ST500DM002-1BD142 500GB                       | 9        | 0.65%   |
| Samsung SSD 870 EVO 500GB                             | 8        | 0.58%   |
| Samsung SSD 860 EVO 250GB                             | 8        | 0.58%   |
| Samsung SSD 850 EVO 500GB                             | 8        | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB                        | 7        | 0.51%   |
| Samsung SSD 980 1TB                                   | 7        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                          | 7        | 0.51%   |
| Samsung SSD 860 EVO 1TB                               | 7        | 0.51%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB               | 7        | 0.51%   |
| Crucial CT500MX500SSD1 500GB                          | 7        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB                        | 6        | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                            | 6        | 0.43%   |
| Samsung SSD 980 500GB                                 | 6        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB                        | 6        | 0.43%   |
| Samsung SSD 870 EVO 1TB                               | 6        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                      | 6        | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 5        | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 5        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB                              | 5        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 184      | 343    | 37.86%  |
| Seagate             | 151      | 238    | 31.07%  |
| Toshiba             | 69       | 99     | 14.2%   |
| Hitachi             | 39       | 52     | 8.02%   |
| HGST                | 17       | 63     | 3.5%    |
| Samsung Electronics | 10       | 13     | 2.06%   |
| Unknown             | 5        | 5      | 1.03%   |
| Maxtor              | 5        | 5      | 1.03%   |
| Hewlett-Packard     | 2        | 3      | 0.41%   |
| USB                 | 1        | 1      | 0.21%   |
| External            | 1        | 1      | 0.21%   |
| Apple               | 1        | 1      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 85       | 110    | 20%     |
| Crucial             | 68       | 77     | 16%     |
| Kingston            | 57       | 61     | 13.41%  |
| WDC                 | 27       | 36     | 6.35%   |
| Netac               | 25       | 26     | 5.88%   |
| SanDisk             | 21       | 23     | 4.94%   |
| China               | 17       | 20     | 4%      |
| Intel               | 11       | 15     | 2.59%   |
| SPCC                | 9        | 9      | 2.12%   |
| Transcend           | 8        | 14     | 1.88%   |
| GOODRAM             | 8        | 12     | 1.88%   |
| A-DATA Technology   | 8        | 9      | 1.88%   |
| PNY                 | 6        | 8      | 1.41%   |
| Patriot             | 5        | 5      | 1.18%   |
| Micron Technology   | 5        | 6      | 1.18%   |
| Hewlett-Packard     | 5        | 5      | 1.18%   |
| Plextor             | 4        | 4      | 0.94%   |
| OCZ                 | 4        | 4      | 0.94%   |
| LITEON              | 3        | 3      | 0.71%   |
| Intenso             | 3        | 3      | 0.71%   |
| Apacer              | 3        | 5      | 0.71%   |
| AMD                 | 3        | 3      | 0.71%   |
| Seagate             | 2        | 2      | 0.47%   |
| SABRENT             | 2        | 2      | 0.47%   |
| KingSpec            | 2        | 2      | 0.47%   |
| FORESEE             | 2        | 2      | 0.47%   |
| Fanxiang            | 2        | 2      | 0.47%   |
| Corsair             | 2        | 2      | 0.47%   |
| WDC WDS5            | 1        | 1      | 0.24%   |
| TrekStor            | 1        | 1      | 0.24%   |
| Toshiba             | 1        | 1      | 0.24%   |
| TO Exter            | 1        | 1      | 0.24%   |
| Timetec             | 1        | 2      | 0.24%   |
| Team                | 1        | 1      | 0.24%   |
| T-FORCE             | 1        | 2      | 0.24%   |
| SSSTC               | 1        | 1      | 0.24%   |
| Rogueware           | 1        | 2      | 0.24%   |
| OCZ-VERTEX3         | 1        | 1      | 0.24%   |
| NT-512              | 1        | 1      | 0.24%   |
| NGFF                | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 399      | 825    | 39.19%  |
| SSD     | 360      | 501    | 35.36%  |
| NVMe    | 241      | 370    | 23.67%  |
| Unknown | 13       | 21     | 1.28%   |
| MMC     | 5        | 7      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 585      | 1230   | 66.86%  |
| NVMe | 239      | 365    | 27.31%  |
| SAS  | 46       | 122    | 5.26%   |
| MMC  | 5        | 7      | 0.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 423      | 570    | 50.54%  |
| 0.51-1.0   | 214      | 308    | 25.57%  |
| 1.01-2.0   | 86       | 142    | 10.27%  |
| 3.01-4.0   | 46       | 100    | 5.5%    |
| 2.01-3.0   | 31       | 49     | 3.7%    |
| 4.01-10.0  | 30       | 142    | 3.58%   |
| 10.01-20.0 | 7        | 15     | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 186      | 26.72%  |
| 101-250        | 98       | 14.08%  |
| 501-1000       | 92       | 13.22%  |
| More than 3000 | 86       | 12.36%  |
| 251-500        | 78       | 11.21%  |
| 1001-2000      | 63       | 9.05%   |
| 2001-3000      | 36       | 5.17%   |
| 1-20           | 24       | 3.45%   |
| 51-100         | 20       | 2.87%   |
| 21-50          | 13       | 1.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 186      | 26.38%  |
| 1-20           | 166      | 23.55%  |
| 21-50          | 73       | 10.35%  |
| 101-250        | 70       | 9.93%   |
| 251-500        | 46       | 6.52%   |
| 501-1000       | 45       | 6.38%   |
| 51-100         | 39       | 5.53%   |
| 1001-2000      | 38       | 5.39%   |
| More than 3000 | 29       | 4.11%   |
| 2001-3000      | 13       | 1.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB        | 13       | 13     | 9.09%   |
| Seagate ST3250410AS 250GB           | 4        | 4      | 2.8%    |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 3      | 2.1%    |
| Seagate ST500DM002-1BD142 500GB     | 3        | 3      | 2.1%    |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 3      | 2.1%    |
| Maxtor STM3160815AS 160GB           | 3        | 3      | 2.1%    |
| WDC WD30EFRX-68EUZN0 3TB            | 2        | 2      | 1.4%    |
| WDC WD10EARS-00MVWB0 1TB            | 2        | 2      | 1.4%    |
| Seagate ST2000DX001-1CM164 2TB      | 2        | 3      | 1.4%    |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 2      | 1.4%    |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 2      | 1.4%    |
| Samsung Electronics SSD 970 EVO 1TB | 2        | 2      | 1.4%    |
| Hitachi HDS721050CLA362 500GB       | 2        | 4      | 1.4%    |
| Hitachi HDS721010CLA332 1TB         | 2        | 2      | 1.4%    |
| ZHITAI TiPlus5000 512GB             | 1        | 1      | 0.7%    |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 2      | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 0.7%    |
| WDC WD80EMAZ-00WJTA0 8TB            | 1        | 22     | 0.7%    |
| WDC WD800AAJS-60WAA0 80GB           | 1        | 1      | 0.7%    |
| WDC WD7500BPKX-80HPJT0 752GB        | 1        | 1      | 0.7%    |
| WDC WD5000AZLX-22JKKA0 500GB        | 1        | 2      | 0.7%    |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 1      | 0.7%    |
| WDC WD5000AAKS-00A7B0 500GB         | 1        | 1      | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 3      | 0.7%    |
| WDC WD400BD-60LRA0 40GB             | 1        | 1      | 0.7%    |
| WDC WD400BB-75CAA0 40GB             | 1        | 1      | 0.7%    |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 1      | 0.7%    |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 1      | 0.7%    |
| WDC WD2500AAKX-001CA0 250GB         | 1        | 1      | 0.7%    |
| WDC WD2500AAKS-00VSA0 250GB         | 1        | 2      | 0.7%    |
| WDC WD2500AAJS-00YZCA0 250GB        | 1        | 1      | 0.7%    |
| WDC WD2500AAJS-00B4A0 250GB         | 1        | 1      | 0.7%    |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 0.7%    |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 0.7%    |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 0.7%    |
| WDC WD1600AAJS-00B4A0 160GB         | 1        | 1      | 0.7%    |
| WDC WD15EARS-00Z5B1 1TB             | 1        | 1      | 0.7%    |
| WDC WD10JPVX-08JC3T5 1TB            | 1        | 1      | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 51       | 79     | 37.23%  |
| Seagate             | 29       | 35     | 21.17%  |
| Samsung Electronics | 15       | 16     | 10.95%  |
| Hitachi             | 9        | 12     | 6.57%   |
| Toshiba             | 5        | 5      | 3.65%   |
| Maxtor              | 4        | 4      | 2.92%   |
| Kingston            | 3        | 3      | 2.19%   |
| Intel               | 3        | 5      | 2.19%   |
| Crucial             | 3        | 3      | 2.19%   |
| SanDisk             | 2        | 2      | 1.46%   |
| ZHITAI              | 1        | 1      | 0.73%   |
| SSSTC               | 1        | 1      | 0.73%   |
| OCZ                 | 1        | 1      | 0.73%   |
| Netac               | 1        | 1      | 0.73%   |
| Mushkin             | 1        | 1      | 0.73%   |
| Micron Technology   | 1        | 1      | 0.73%   |
| LITEON              | 1        | 1      | 0.73%   |
| KingSpec            | 1        | 1      | 0.73%   |
| HS-SSD-C100         | 1        | 1      | 0.73%   |
| Corsair             | 1        | 1      | 0.73%   |
| China               | 1        | 1      | 0.73%   |
| Apple               | 1        | 1      | 0.73%   |
| A-DATA Technology   | 1        | 1      | 0.73%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 48       | 75     | 48%     |
| Seagate             | 29       | 35     | 29%     |
| Hitachi             | 9        | 12     | 9%      |
| Toshiba             | 5        | 5      | 5%      |
| Samsung Electronics | 4        | 5      | 4%      |
| Maxtor              | 4        | 4      | 4%      |
| Apple               | 1        | 1      | 1%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 89       | 137    | 70.63%  |
| SSD  | 31       | 34     | 24.6%   |
| NVMe | 6        | 6      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 464      | 1037   | 59.56%  |
| Detected | 191      | 508    | 24.52%  |
| Malfunc  | 122      | 177    | 15.66%  |
| Failed   | 1        | 1      | 0.13%   |
| Limited  | 1        | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 437      | 42.1%   |
| AMD                            | 223      | 21.48%  |
| Samsung Electronics            | 91       | 8.77%   |
| SanDisk                        | 42       | 4.05%   |
| ASMedia Technology             | 38       | 3.66%   |
| Kingston Technology Company    | 31       | 2.99%   |
| Phison Electronics             | 22       | 2.12%   |
| Micron/Crucial Technology      | 19       | 1.83%   |
| JMicron Technology             | 18       | 1.73%   |
| Marvell Technology Group       | 17       | 1.64%   |
| Nvidia                         | 11       | 1.06%   |
| Silicon Motion                 | 10       | 0.96%   |
| MAXIO Technology (Hangzhou)    | 8        | 0.77%   |
| ADATA Technology               | 8        | 0.77%   |
| Toshiba America Info Systems   | 7        | 0.67%   |
| SK hynix                       | 6        | 0.58%   |
| LSI Logic / Symbios Logic      | 6        | 0.58%   |
| KIOXIA                         | 5        | 0.48%   |
| Broadcom / LSI                 | 4        | 0.39%   |
| Silicon Image                  | 3        | 0.29%   |
| Micron Technology              | 3        | 0.29%   |
| Adaptec                        | 3        | 0.29%   |
| Yangtze Memory Technologies    | 2        | 0.19%   |
| VIA Technologies               | 2        | 0.19%   |
| Transcend                      | 2        | 0.19%   |
| Seagate Technology             | 2        | 0.19%   |
| Realtek Semiconductor          | 2        | 0.19%   |
| INNOGRIT                       | 2        | 0.19%   |
| HighPoint Technologies         | 2        | 0.19%   |
| Biwin Storage Technology       | 2        | 0.19%   |
| Solidigm                       | 1        | 0.1%    |
| Solid State Storage Technology | 1        | 0.1%    |
| Shenzhen Longsys Electronics   | 1        | 0.1%    |
| Radian Memory Systems          | 1        | 0.1%    |
| Netac Technology               | 1        | 0.1%    |
| Loongson Technology            | 1        | 0.1%    |
| IBM                            | 1        | 0.1%    |
| Hewlett-Packard                | 1        | 0.1%    |
| Artop Electronic               | 1        | 0.1%    |
| 3ware                          | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 135      | 10.81%  |
| AMD 400 Series Chipset SATA Controller                                                  | 62       | 4.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 61       | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 38       | 3.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 38       | 3.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 35       | 2.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 35       | 2.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 33       | 2.64%   |
| AMD 500 Series Chipset SATA Controller                                                  | 32       | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 30       | 2.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 22       | 1.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 20       | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 19       | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 1.44%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 17       | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 1.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 14       | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 13       | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 0.96%   |
| Phison E12 NVMe Controller                                                              | 11       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10       | 0.8%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 10       | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 0.72%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 9        | 0.72%   |
| AMD FCH SATA Controller D                                                               | 9        | 0.72%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 8        | 0.64%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 0.64%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 8        | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 7        | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 7        | 0.56%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 7        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 580      | 58.29%  |
| NVMe | 235      | 23.62%  |
| IDE  | 120      | 12.06%  |
| RAID | 48       | 4.82%   |
| SAS  | 9        | 0.9%    |
| SCSI | 3        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 443      | 64.58%  |
| AMD               | 237      | 34.55%  |
| ARM               | 3        | 0.44%   |
| Loongson          | 1        | 0.15%   |
| CHRP IBM,8233-E8B | 1        | 0.15%   |
| Unknown           | 1        | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 23       | 3.34%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 17       | 2.47%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 12       | 1.74%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 12       | 1.74%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 11       | 1.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 1.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 10       | 1.45%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 10       | 1.45%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 1.31%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 8        | 1.16%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 8        | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 1.16%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 7        | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 1.02%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 1.02%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 1.02%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 0.87%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 6        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 0.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 0.73%   |
| Intel Celeron N5105 @ 2.00GHz               | 5        | 0.73%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 5        | 0.73%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.73%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 4        | 0.58%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz         | 4        | 0.58%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 0.58%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 0.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.58%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 4        | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 0.58%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.58%   |
| Intel Celeron J6413 @ 1.80GHz               | 4        | 0.58%   |
| Intel 13th Gen Core i7-13700K               | 4        | 0.58%   |
| Intel 12th Gen Core i7-12700K               | 4        | 0.58%   |
| Intel 12th Gen Core i5-12400F               | 4        | 0.58%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 4        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 86       | 12.54%  |
| Intel Core i7           | 80       | 11.66%  |
| AMD Ryzen 5             | 63       | 9.18%   |
| Other                   | 61       | 8.89%   |
| AMD Ryzen 7             | 56       | 8.16%   |
| Intel Xeon              | 49       | 7.14%   |
| Intel Pentium           | 43       | 6.27%   |
| AMD Ryzen 9             | 37       | 5.39%   |
| Intel Celeron           | 34       | 4.96%   |
| Intel Core i3           | 33       | 4.81%   |
| AMD Ryzen 3             | 18       | 2.62%   |
| Intel Core 2 Duo        | 16       | 2.33%   |
| Intel Pentium Dual-Core | 14       | 2.04%   |
| Intel Core 2            | 14       | 2.04%   |
| AMD FX                  | 14       | 2.04%   |
| Intel Core 2 Quad       | 7        | 1.02%   |
| AMD Ryzen 5 PRO         | 6        | 0.87%   |
| AMD Athlon              | 5        | 0.73%   |
| Intel Core i9           | 4        | 0.58%   |
| AMD Phenom II X4        | 4        | 0.58%   |
| AMD Athlon 64 X2        | 4        | 0.58%   |
| Intel Pentium Gold      | 3        | 0.44%   |
| AMD Phenom II X6        | 3        | 0.44%   |
| AMD Phenom II X3        | 3        | 0.44%   |
| AMD Athlon II X3        | 3        | 0.44%   |
| AMD Athlon II X2        | 3        | 0.44%   |
| AMD A8                  | 3        | 0.44%   |
| Intel Pentium 4         | 2        | 0.29%   |
| AMD GX                  | 2        | 0.29%   |
| AMD EPYC                | 2        | 0.29%   |
| AMD A6                  | 2        | 0.29%   |
| Intel Pentium Silver    | 1        | 0.15%   |
| Intel Genuine           | 1        | 0.15%   |
| Intel Core m3           | 1        | 0.15%   |
| Intel Atom              | 1        | 0.15%   |
| AMD Ryzen Threadripper  | 1        | 0.15%   |
| AMD PRO A10             | 1        | 0.15%   |
| AMD Phenom              | 1        | 0.15%   |
| AMD G                   | 1        | 0.15%   |
| AMD E                   | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 223      | 32.46%  |
| 2      | 163      | 23.73%  |
| 8      | 99       | 14.41%  |
| 6      | 95       | 13.83%  |
| 12     | 35       | 5.09%   |
| 16     | 22       | 3.2%    |
| 3      | 11       | 1.6%    |
| 10     | 10       | 1.46%   |
| 1      | 10       | 1.46%   |
| 24     | 9        | 1.31%   |
| 14     | 6        | 0.87%   |
| 22     | 2        | 0.29%   |
| 36     | 1        | 0.15%   |
| 5      | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 677      | 98.54%  |
| 2      | 10       | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 417      | 60.7%   |
| 1      | 269      | 39.16%  |
| 4      | 1        | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 682      | 99.42%  |
| Unknown        | 3        | 0.44%   |
| 32-bit         | 1        | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 199      | 28.84%  |
| 0x306c3    | 58       | 8.41%   |
| 0x1067a    | 26       | 3.77%   |
| 0xa0655    | 22       | 3.19%   |
| 0x506e3    | 22       | 3.19%   |
| 0x906e9    | 19       | 2.75%   |
| 0x08108109 | 19       | 2.75%   |
| 0x0a50000d | 18       | 2.61%   |
| 0x0a601203 | 17       | 2.46%   |
| 0x206a7    | 16       | 2.32%   |
| 0x306a9    | 14       | 2.03%   |
| 0x906ea    | 13       | 1.88%   |
| 0x08701021 | 13       | 1.88%   |
| 0x90672    | 12       | 1.74%   |
| 0x6f2      | 12       | 1.74%   |
| 0xb0671    | 9        | 1.3%    |
| 0xa0653    | 9        | 1.3%    |
| 0x0a20120a | 9        | 1.3%    |
| 0x0800820d | 9        | 1.3%    |
| 0x06000852 | 7        | 1.01%   |
| 0x406f1    | 6        | 0.87%   |
| 0x0a201016 | 6        | 0.87%   |
| 0x08600106 | 6        | 0.87%   |
| 0x08101016 | 6        | 0.87%   |
| 0x0810100b | 6        | 0.87%   |
| 0x08001138 | 6        | 0.87%   |
| 0x906c0    | 5        | 0.72%   |
| 0x106a5    | 5        | 0.72%   |
| 0x90675    | 4        | 0.58%   |
| 0x10676    | 4        | 0.58%   |
| 0xb06f2    | 3        | 0.43%   |
| 0xb06e0    | 3        | 0.43%   |
| 0xa0671    | 3        | 0.43%   |
| 0x906ed    | 3        | 0.43%   |
| 0x706a1    | 3        | 0.43%   |
| 0x6fd      | 3        | 0.43%   |
| 0x50654    | 3        | 0.43%   |
| 0x306f2    | 3        | 0.43%   |
| 0x20655    | 3        | 0.43%   |
| 0x0a201009 | 3        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 90       | 13.08%  |
| Zen 3            | 61       | 8.87%   |
| KabyLake         | 55       | 7.99%   |
| Unknown          | 43       | 6.25%   |
| CometLake        | 42       | 6.1%    |
| Zen 2            | 41       | 5.96%   |
| Zen+             | 38       | 5.52%   |
| Skylake          | 38       | 5.52%   |
| Penryn           | 38       | 5.52%   |
| Alderlake Hybrid | 33       | 4.8%    |
| SandyBridge      | 24       | 3.49%   |
| IvyBridge        | 23       | 3.34%   |
| Zen              | 22       | 3.2%    |
| Core             | 21       | 3.05%   |
| K10              | 19       | 2.76%   |
| Piledriver       | 15       | 2.18%   |
| Nehalem          | 12       | 1.74%   |
| Tremont          | 11       | 1.6%    |
| Westmere         | 9        | 1.31%   |
| Broadwell        | 9        | 1.31%   |
| Silvermont       | 7        | 1.02%   |
| Goldmont plus    | 7        | 1.02%   |
| Excavator        | 5        | 0.73%   |
| TigerLake        | 4        | 0.58%   |
| K8 Hammer        | 4        | 0.58%   |
| Jaguar           | 3        | 0.44%   |
| Icelake          | 3        | 0.44%   |
| Gracemont        | 3        | 0.44%   |
| NetBurst         | 2        | 0.29%   |
| Bobcat           | 2        | 0.29%   |
| Steamroller      | 1        | 0.15%   |
| Puma             | 1        | 0.15%   |
| Goldmont         | 1        | 0.15%   |
| Bulldozer        | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 250      | 34.15%  |
| Nvidia                                       | 235      | 32.1%   |
| AMD                                          | 229      | 31.28%  |
| ASPEED Technology                            | 11       | 1.5%    |
| Matrox Electronics Systems                   | 5        | 0.68%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.14%   |
| Loongson Technology                          | 1        | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 40       | 5.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 23       | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 21       | 2.81%   |
| AMD Raphael                                                                 | 20       | 2.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 2.67%   |
| Nvidia GF108 [GeForce GT 730]                                               | 19       | 2.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 18       | 2.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16       | 2.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 16       | 2.14%   |
| Intel HD Graphics 530                                                       | 15       | 2.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 2.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 14       | 1.87%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 13       | 1.74%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13       | 1.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 12       | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 1.6%    |
| Intel AlderLake-S GT1                                                       | 11       | 1.47%   |
| ASPEED Technology ASPEED Graphics Family                                    | 11       | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 1.34%   |
| Intel HD Graphics 630                                                       | 10       | 1.34%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 10       | 1.34%   |
| Intel HD Graphics 510                                                       | 9        | 1.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 9        | 1.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 0.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 0.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 0.8%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 6        | 0.8%    |
| Intel JasperLake [UHD Graphics]                                             | 6        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 6        | 0.8%    |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 6        | 0.8%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 209      | 30.38%  |
| 1 x Nvidia              | 200      | 29.07%  |
| 1 x AMD                 | 194      | 28.2%   |
| Intel + Nvidia          | 23       | 3.34%   |
| 2 x AMD                 | 15       | 2.18%   |
| 1 x ASPEED              | 10       | 1.45%   |
| AMD + Nvidia            | 10       | 1.45%   |
| Other                   | 7        | 1.02%   |
| Intel + AMD             | 7        | 1.02%   |
| 1 x Matrox              | 5        | 0.73%   |
| 2 x Intel               | 3        | 0.44%   |
| 2 x Nvidia              | 1        | 0.15%   |
| 1 x XGI                 | 1        | 0.15%   |
| 1 x Loongson Technology | 1        | 0.15%   |
| AMD + Matrox            | 1        | 0.15%   |
| AMD + ASPEED            | 1        | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 411      | 59.83%  |
| Unknown     | 186      | 27.07%  |
| Proprietary | 90       | 13.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 448      | 65.12%  |
| 7.01-8.0   | 45       | 6.54%   |
| 3.01-4.0   | 45       | 6.54%   |
| 1.01-2.0   | 43       | 6.25%   |
| 0.01-0.5   | 40       | 5.81%   |
| 0.51-1.0   | 21       | 3.05%   |
| 8.01-16.0  | 19       | 2.76%   |
| 5.01-6.0   | 12       | 1.74%   |
| 16.01-24.0 | 9        | 1.31%   |
| 2.01-3.0   | 5        | 0.73%   |
| 4.01-5.0   | 1        | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 81       | 14.84%  |
| Dell                 | 65       | 11.9%   |
| Goldstar             | 51       | 9.34%   |
| Hewlett-Packard      | 42       | 7.69%   |
| Ancor Communications | 35       | 6.41%   |
| Acer                 | 30       | 5.49%   |
| BenQ                 | 29       | 5.31%   |
| AOC                  | 26       | 4.76%   |
| Philips              | 20       | 3.66%   |
| Lenovo               | 16       | 2.93%   |
| ASUSTek Computer     | 15       | 2.75%   |
| LG Electronics       | 10       | 1.83%   |
| ViewSonic            | 9        | 1.65%   |
| Sceptre Tech         | 9        | 1.65%   |
| Iiyama               | 9        | 1.65%   |
| Unknown              | 8        | 1.47%   |
| Sony                 | 7        | 1.28%   |
| Unknown              | 5        | 0.92%   |
| RTK                  | 4        | 0.73%   |
| Mi                   | 4        | 0.73%   |
| Fujitsu Siemens      | 4        | 0.73%   |
| Vizio                | 3        | 0.55%   |
| MiTAC                | 3        | 0.55%   |
| HKC                  | 3        | 0.55%   |
| Gigabyte Technology  | 3        | 0.55%   |
| Eizo                 | 3        | 0.55%   |
| Panasonic            | 2        | 0.37%   |
| MStar                | 2        | 0.37%   |
| MSD                  | 2        | 0.37%   |
| Medion               | 2        | 0.37%   |
| Idek Iiyama          | 2        | 0.37%   |
| Hitachi              | 2        | 0.37%   |
| HannStar             | 2        | 0.37%   |
| CHR                  | 2        | 0.37%   |
| YSD                  | 1        | 0.18%   |
| Yamaha               | 1        | 0.18%   |
| Vita                 | 1        | 0.18%   |
| TCT                  | 1        | 0.18%   |
| TCL                  | 1        | 0.18%   |
| Sceptre              | 1        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 15       | 2.6%    |
| Unknown                                                               | 8        | 1.39%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 4        | 0.69%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch            | 4        | 0.69%   |
| Ancor Communications ASUS VB178 ACI1714 1280x1024 338x270mm 17.0-inch | 4        | 0.69%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3        | 0.52%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.52%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 3        | 0.52%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 3        | 0.52%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 3        | 0.52%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 0.52%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2        | 0.35%   |
| Sceptre Tech Sceptre Y32 SPT0CAD 2560x1440 697x392mm 31.5-inch        | 2        | 0.35%   |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                | 2        | 0.35%   |
| Samsung Electronics SyncMaster SAM058B 1920x1080 531x298mm 24.0-inch  | 2        | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 950x540mm 43.0-inch | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 410x230mm 18.5-inch | 2        | 0.35%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 2        | 0.35%   |
| RTK FHD HDR RTK3B3A 1920x1080 344x195mm 15.6-inch                     | 2        | 0.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.35%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 2        | 0.35%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2        | 0.35%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 2        | 0.35%   |
| Lenovo T27hv-20 LEN62A9 2560x1440 597x336mm 27.0-inch                 | 2        | 0.35%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2        | 0.35%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 2        | 0.35%   |
| Hewlett-Packard Z27n HWP3216 2560x1440 597x336mm 27.0-inch            | 2        | 0.35%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.35%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.35%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.35%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 0.35%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.35%   |
| Dell G3223Q DEL428C 3840x2160 708x399mm 32.0-inch                     | 2        | 0.35%   |
| Dell E2414H DEL4091 1920x1080 531x299mm 24.0-inch                     | 2        | 0.35%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 2        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 238      | 44.65%  |
| 3840x2160 (4K)     | 63       | 11.82%  |
| 2560x1440 (QHD)    | 62       | 11.63%  |
| 1280x1024 (SXGA)   | 27       | 5.07%   |
| Unknown            | 19       | 3.56%   |
| 1680x1050 (WSXGA+) | 17       | 3.19%   |
| 1920x1200 (WUXGA)  | 14       | 2.63%   |
| 1600x900 (HD+)     | 13       | 2.44%   |
| 3440x1440          | 12       | 2.25%   |
| 1440x900 (WXGA+)   | 12       | 2.25%   |
| 1366x768 (WXGA)    | 11       | 2.06%   |
| 2560x1080          | 8        | 1.5%    |
| 1360x768           | 6        | 1.13%   |
| 3840x1080          | 5        | 0.94%   |
| 4480x1440          | 4        | 0.75%   |
| 1920x540           | 4        | 0.75%   |
| 2288x1287          | 3        | 0.56%   |
| 7680x2160          | 2        | 0.38%   |
| 3840x1600          | 2        | 0.38%   |
| 3840x1200          | 2        | 0.38%   |
| 7280x2160          | 1        | 0.19%   |
| 6400x2160          | 1        | 0.19%   |
| 6400x1440          | 1        | 0.19%   |
| 5760x2160          | 1        | 0.19%   |
| 3286x1080          | 1        | 0.19%   |
| 2720x768           | 1        | 0.19%   |
| 1600x1200          | 1        | 0.19%   |
| 1400x1050          | 1        | 0.19%   |
| 1024x768 (XGA)     | 1        | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 85       | 15.89%  |
| 27      | 83       | 15.51%  |
| 21      | 76       | 14.21%  |
| 23      | 59       | 11.03%  |
| Unknown | 46       | 8.6%    |
| 31      | 24       | 4.49%   |
| 19      | 20       | 3.74%   |
| 34      | 16       | 2.99%   |
| 17      | 16       | 2.99%   |
| 18      | 15       | 2.8%    |
| 20      | 14       | 2.62%   |
| 32      | 12       | 2.24%   |
| 22      | 8        | 1.5%    |
| 84      | 7        | 1.31%   |
| 15      | 6        | 1.12%   |
| 40      | 5        | 0.93%   |
| 52      | 4        | 0.75%   |
| 142     | 3        | 0.56%   |
| 72      | 3        | 0.56%   |
| 54      | 3        | 0.56%   |
| 46      | 3        | 0.56%   |
| 39      | 3        | 0.56%   |
| 28      | 3        | 0.56%   |
| 26      | 3        | 0.56%   |
| 49      | 2        | 0.37%   |
| 48      | 2        | 0.37%   |
| 42      | 2        | 0.37%   |
| 33      | 2        | 0.37%   |
| 16      | 2        | 0.37%   |
| 85      | 1        | 0.19%   |
| 65      | 1        | 0.19%   |
| 43      | 1        | 0.19%   |
| 41      | 1        | 0.19%   |
| 38      | 1        | 0.19%   |
| 37      | 1        | 0.19%   |
| 35      | 1        | 0.19%   |
| 14      | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 210      | 40.62%  |
| 401-500        | 121      | 23.4%   |
| Unknown        | 46       | 8.9%    |
| 601-700        | 32       | 6.19%   |
| 701-800        | 30       | 5.8%    |
| 301-350        | 22       | 4.26%   |
| 1001-1500      | 15       | 2.9%    |
| 351-400        | 11       | 2.13%   |
| 1501-2000      | 11       | 2.13%   |
| 801-900        | 9        | 1.74%   |
| 901-1000       | 6        | 1.16%   |
| More than 2000 | 3        | 0.58%   |
| 201-300        | 1        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 345      | 70.12%  |
| 16/10   | 46       | 9.35%   |
| Unknown | 41       | 8.33%   |
| 5/4     | 23       | 4.67%   |
| 21/9    | 22       | 4.47%   |
| 4/3     | 5        | 1.02%   |
| 1.00    | 4        | 0.81%   |
| 32/9    | 3        | 0.61%   |
| 6/5     | 2        | 0.41%   |
| 3/2     | 1        | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 180      | 34.03%  |
| 301-350        | 84       | 15.88%  |
| 351-500        | 59       | 11.15%  |
| 151-200        | 48       | 9.07%   |
| Unknown        | 46       | 8.7%    |
| 251-300        | 31       | 5.86%   |
| 141-150        | 27       | 5.1%    |
| More than 1000 | 25       | 4.73%   |
| 501-1000       | 18       | 3.4%    |
| 101-110        | 6        | 1.13%   |
| 131-140        | 3        | 0.57%   |
| 111-120        | 2        | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 271      | 53.77%  |
| 101-120 | 121      | 24.01%  |
| Unknown | 46       | 9.13%   |
| 121-160 | 31       | 6.15%   |
| 1-50    | 20       | 3.97%   |
| 161-240 | 15       | 2.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 394      | 57.27%  |
| 0     | 206      | 29.94%  |
| 2     | 77       | 11.19%  |
| 3     | 11       | 1.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 448      | 47.76%  |
| Intel                           | 278      | 29.64%  |
| Qualcomm Atheros                | 41       | 4.37%   |
| MediaTek                        | 29       | 3.09%   |
| Broadcom                        | 22       | 2.35%   |
| Ralink Technology               | 16       | 1.71%   |
| TP-Link                         | 13       | 1.39%   |
| Nvidia                          | 11       | 1.17%   |
| Aquantia                        | 10       | 1.07%   |
| QinHeng Electronics             | 6        | 0.64%   |
| Marvell Technology Group        | 6        | 0.64%   |
| ASIX Electronics                | 5        | 0.53%   |
| Samsung Electronics             | 4        | 0.43%   |
| ASUSTek Computer                | 4        | 0.43%   |
| Qualcomm Atheros Communications | 3        | 0.32%   |
| Mellanox Technologies           | 3        | 0.32%   |
| Broadcom Limited                | 3        | 0.32%   |
| Ralink                          | 2        | 0.21%   |
| Microchip Technology            | 2        | 0.21%   |
| D-Link System                   | 2        | 0.21%   |
| D-Link                          | 2        | 0.21%   |
| American Megatrends             | 2        | 0.21%   |
| 3Com                            | 2        | 0.21%   |
| Texas Instruments               | 1        | 0.11%   |
| SysKonnect                      | 1        | 0.11%   |
| Solarflare Communications       | 1        | 0.11%   |
| SEGGER                          | 1        | 0.11%   |
| Raspberry Pi                    | 1        | 0.11%   |
| Qualcomm                        | 1        | 0.11%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.11%   |
| NetGear                         | 1        | 0.11%   |
| Motorola PCS                    | 1        | 0.11%   |
| Microsoft                       | 1        | 0.11%   |
| MCS                             | 1        | 0.11%   |
| Loongson Technology             | 1        | 0.11%   |
| Linksys                         | 1        | 0.11%   |
| Insyde Software                 | 1        | 0.11%   |
| ICS Advent                      | 1        | 0.11%   |
| IBM                             | 1        | 0.11%   |
| Google                          | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 355      | 33.15%  |
| Realtek RTL8125 2.5GbE Controller                                   | 51       | 4.76%   |
| Intel Ethernet Controller I225-V                                    | 39       | 3.64%   |
| Intel Wi-Fi 6 AX200                                                 | 31       | 2.89%   |
| Intel I211 Gigabit Network Connection                               | 28       | 2.61%   |
| Intel Ethernet Connection (2) I219-V                                | 20       | 1.87%   |
| Intel Ethernet Connection I217-LM                                   | 18       | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 16       | 1.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 1.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 15       | 1.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 14       | 1.31%   |
| Intel I210 Gigabit Network Connection                               | 13       | 1.21%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 1.03%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 11       | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 10       | 0.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 10       | 0.93%   |
| Intel Ethernet Controller I226-V                                    | 10       | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 10       | 0.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 10       | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 9        | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                     | 7        | 0.65%   |
| Intel 82574L Gigabit Network Connection                             | 7        | 0.65%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 0.65%   |
| Realtek 802.11ac NIC                                                | 6        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 6        | 0.56%   |
| Intel Ethernet Connection I217-V                                    | 6        | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                              | 6        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 6        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 5        | 0.47%   |
| QinHeng USB Single Serial                                           | 5        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 5        | 0.47%   |
| Intel Wireless-AC 9260                                              | 5        | 0.47%   |
| Intel Wireless 7260                                                 | 5        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                               | 5        | 0.47%   |
| Intel 82579V Gigabit Network Connection                             | 5        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 5        | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 4        | 0.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 4        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 109      | 40.07%  |
| Realtek Semiconductor           | 57       | 20.96%  |
| MediaTek                        | 28       | 10.29%  |
| Qualcomm Atheros                | 22       | 8.09%   |
| Ralink Technology               | 16       | 5.88%   |
| TP-Link                         | 13       | 4.78%   |
| Broadcom                        | 8        | 2.94%   |
| ASUSTek Computer                | 4        | 1.47%   |
| Qualcomm Atheros Communications | 3        | 1.1%    |
| Ralink                          | 2        | 0.74%   |
| D-Link                          | 2        | 0.74%   |
| Broadcom Limited                | 2        | 0.74%   |
| NetGear                         | 1        | 0.37%   |
| Microsoft                       | 1        | 0.37%   |
| Marvell Technology Group        | 1        | 0.37%   |
| Linksys                         | 1        | 0.37%   |
| Edimax Technology               | 1        | 0.37%   |
| Belkin Components               | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31       | 11.31%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16       | 5.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 15       | 5.47%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 11       | 4.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10       | 3.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10       | 3.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10       | 3.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 10       | 3.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 9        | 3.28%   |
| Ralink MT7601U Wireless Adapter                                | 7        | 2.55%   |
| Realtek 802.11ac NIC                                           | 6        | 2.19%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5        | 1.82%   |
| Intel Wireless-AC 9260                                         | 5        | 1.82%   |
| Intel Wireless 7260                                            | 5        | 1.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 1.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 4        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 1.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4        | 1.46%   |
| Intel Wireless 7265                                            | 4        | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 1.09%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 1.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.09%   |
| Ralink RT5572 Wireless Adapter                                 | 3        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3        | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3        | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                | 3        | 1.09%   |
| Intel Wireless 3165                                            | 3        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3        | 1.09%   |
| TP-Link 802.11ac NIC                                           | 2        | 0.73%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 2        | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2        | 0.73%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2        | 0.73%   |
| Intel Wireless 8260                                            | 2        | 0.73%   |
| Intel Wireless 3160                                            | 2        | 0.73%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2        | 0.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 440      | 58.28%  |
| Intel                     | 219      | 29.01%  |
| Qualcomm Atheros          | 21       | 2.78%   |
| Broadcom                  | 15       | 1.99%   |
| Nvidia                    | 11       | 1.46%   |
| Aquantia                  | 10       | 1.32%   |
| Marvell Technology Group  | 5        | 0.66%   |
| ASIX Electronics          | 5        | 0.66%   |
| Samsung Electronics       | 4        | 0.53%   |
| Mellanox Technologies     | 3        | 0.4%    |
| D-Link System             | 2        | 0.26%   |
| American Megatrends       | 2        | 0.26%   |
| 3Com                      | 2        | 0.26%   |
| SysKonnect                | 1        | 0.13%   |
| Solarflare Communications | 1        | 0.13%   |
| Qualcomm                  | 1        | 0.13%   |
| Motorola PCS              | 1        | 0.13%   |
| Microchip Technology      | 1        | 0.13%   |
| MediaTek                  | 1        | 0.13%   |
| Loongson Technology       | 1        | 0.13%   |
| Insyde Software           | 1        | 0.13%   |
| ICS Advent                | 1        | 0.13%   |
| IBM                       | 1        | 0.13%   |
| Google                    | 1        | 0.13%   |
| Emulex                    | 1        | 0.13%   |
| DisplayLink               | 1        | 0.13%   |
| Broadcom Limited          | 1        | 0.13%   |
| ADMtek                    | 1        | 0.13%   |
| Accton Technology         | 1        | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 355      | 45.28%  |
| Realtek RTL8125 2.5GbE Controller                                   | 51       | 6.51%   |
| Intel Ethernet Controller I225-V                                    | 39       | 4.97%   |
| Intel I211 Gigabit Network Connection                               | 28       | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                | 20       | 2.55%   |
| Intel Ethernet Connection I217-LM                                   | 18       | 2.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 14       | 1.79%   |
| Intel I210 Gigabit Network Connection                               | 13       | 1.66%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 1.4%    |
| Intel Ethernet Controller I226-V                                    | 10       | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 1.02%   |
| Intel 82574L Gigabit Network Connection                             | 7        | 0.89%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 6        | 0.77%   |
| Intel Ethernet Connection I217-V                                    | 6        | 0.77%   |
| Intel Ethernet Connection (11) I219-LM                              | 6        | 0.77%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 6        | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 5        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                               | 5        | 0.64%   |
| Intel 82579V Gigabit Network Connection                             | 5        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 5        | 0.64%   |
| Nvidia MCP61 Ethernet                                               | 4        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                               | 4        | 0.51%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 4        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                       | 4        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 3        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 3        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 3        | 0.38%   |
| Nvidia MCP65 Ethernet                                               | 3        | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                               | 3        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                               | 3        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 2        | 0.26%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 2        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 677      | 71.94%  |
| WiFi     | 252      | 26.78%  |
| Modem    | 10       | 1.06%   |
| Unknown  | 2        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 579      | 83.31%  |
| WiFi     | 116      | 16.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 425      | 61.68%  |
| 2     | 204      | 29.61%  |
| 3     | 34       | 4.93%   |
| 4     | 13       | 1.89%   |
| 6     | 6        | 0.87%   |
| 0     | 5        | 0.73%   |
| 12    | 1        | 0.15%   |
| 9     | 1        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 532      | 77.44%  |
| Yes  | 155      | 22.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 97       | 42.73%  |
| Realtek Semiconductor           | 31       | 13.66%  |
| Cambridge Silicon Radio         | 29       | 12.78%  |
| MediaTek                        | 16       | 7.05%   |
| ASUSTek Computer                | 10       | 4.41%   |
| TP-Link                         | 8        | 3.52%   |
| Foxconn / Hon Hai               | 7        | 3.08%   |
| Broadcom                        | 7        | 3.08%   |
| IMC Networks                    | 5        | 2.2%    |
| Qualcomm Atheros Communications | 4        | 1.76%   |
| Apple                           | 4        | 1.76%   |
| Dynex                           | 2        | 0.88%   |
| Actions                         | 2        | 0.88%   |
| Realtek                         | 1        | 0.44%   |
| Lite-On Technology              | 1        | 0.44%   |
| Integrated System Solution      | 1        | 0.44%   |
| HTC (High Tech Computer)        | 1        | 0.44%   |
| Edimax Technology               | 1        | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 29       | 12.78%  |
| Realtek Bluetooth Radio                                              | 27       | 11.89%  |
| Intel AX200 Bluetooth                                                | 27       | 11.89%  |
| MediaTek Wireless_Device                                             | 16       | 7.05%   |
| Intel Bluetooth wireless interface                                   | 15       | 6.61%   |
| Intel Bluetooth Device                                               | 15       | 6.61%   |
| Intel AX201 Bluetooth                                                | 13       | 5.73%   |
| Intel AX210 Bluetooth                                                | 12       | 5.29%   |
| TP-Link UB500 Adapter                                                | 8        | 3.52%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8        | 3.52%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 3.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6        | 2.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 2.2%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 4        | 1.76%   |
| IMC Networks Bluetooth Radio                                         | 4        | 1.76%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 1.32%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 2        | 0.88%   |
| ASUS ASUS USB-BT500                                                  | 2        | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 2        | 0.88%   |
| Apple Bluetooth Host Controller                                      | 2        | 0.88%   |
| Actions general adapter                                              | 2        | 0.88%   |
| Realtek Bluetooth Radio                                              | 1        | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.44%   |
| Lite-On Bluetooth Device                                             | 1        | 0.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 0.44%   |
| Integrated System Solution Bluetooth Device                          | 1        | 0.44%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.44%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.44%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 1        | 0.44%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.44%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.44%   |
| ASUS BCM20702A0                                                      | 1        | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 415      | 38%     |
| AMD                                          | 280      | 25.64%  |
| Nvidia                                       | 227      | 20.79%  |
| C-Media Electronics                          | 28       | 2.56%   |
| Logitech                                     | 12       | 1.1%    |
| Creative Labs                                | 11       | 1.01%   |
| ASUSTek Computer                             | 11       | 1.01%   |
| Micro Star International                     | 7        | 0.64%   |
| Focusrite-Novation                           | 7        | 0.64%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.55%   |
| Texas Instruments                            | 6        | 0.55%   |
| JMTek                                        | 6        | 0.55%   |
| Jieli Technology                             | 6        | 0.55%   |
| Blue Microphones                             | 6        | 0.55%   |
| SteelSeries ApS                              | 5        | 0.46%   |
| Realtek Semiconductor                        | 5        | 0.46%   |
| Razer USA                                    | 4        | 0.37%   |
| GN Netcom                                    | 4        | 0.37%   |
| Generalplus Technology                       | 4        | 0.37%   |
| Corsair                                      | 4        | 0.37%   |
| Kingston Technology                          | 3        | 0.27%   |
| VIA Technologies                             | 2        | 0.18%   |
| Sony                                         | 2        | 0.18%   |
| Medeli Electronics                           | 2        | 0.18%   |
| Dell                                         | 2        | 0.18%   |
| DCMT Technology                              | 2        | 0.18%   |
| Yamaha                                       | 1        | 0.09%   |
| USB MICROPHONE                               | 1        | 0.09%   |
| Tenx Technology                              | 1        | 0.09%   |
| Tdlasunnic                                   | 1        | 0.09%   |
| Schiit Audio                                 | 1        | 0.09%   |
| Samson Technologies                          | 1        | 0.09%   |
| Plantronics                                  | 1        | 0.09%   |
| OPPO Electronics                             | 1        | 0.09%   |
| ONN                                          | 1        | 0.09%   |
| Native Instruments                           | 1        | 0.09%   |
| Loongson Technology                          | 1        | 0.09%   |
| Hewlett-Packard                              | 1        | 0.09%   |
| Global Sun Technology                        | 1        | 0.09%   |
| Giga-Byte Technology                         | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 87       | 6.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 69       | 5.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 61       | 4.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 51       | 3.88%   |
| Intel 200 Series PCH HD Audio                                              | 41       | 3.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 33       | 2.51%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 32       | 2.44%   |
| Intel Comet Lake PCH cAVS                                                  | 29       | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 28       | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 27       | 2.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 26       | 1.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 25       | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 24       | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23       | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23       | 1.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22       | 1.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21       | 1.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 19       | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 15       | 1.14%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 15       | 1.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 1.14%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 15       | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14       | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 14       | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14       | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                              | 13       | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13       | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 0.99%   |
| Nvidia GA102 High Definition Audio Controller                              | 12       | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 11       | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 0.76%   |
| ASUSTek Computer USB Audio                                                 | 10       | 0.76%   |
| AMD Navi 10 HDMI Audio                                                     | 10       | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 130      | 22%     |
| Unknown                                 | 76       | 12.86%  |
| Samsung Electronics                     | 63       | 10.66%  |
| Crucial                                 | 59       | 9.98%   |
| G.Skill                                 | 43       | 7.28%   |
| SK hynix                                | 41       | 6.94%   |
| Corsair                                 | 39       | 6.6%    |
| Hikvision                               | 18       | 3.05%   |
| A-DATA Technology                       | 18       | 3.05%   |
| Unknown                                 | 18       | 3.05%   |
| Micron Technology                       | 15       | 2.54%   |
| Patriot                                 | 10       | 1.69%   |
| Team                                    | 8        | 1.35%   |
| Micro Memory Bank                       | 8        | 1.35%   |
| AMD                                     | 4        | 0.68%   |
| Unknown (ABCD)                          | 3        | 0.51%   |
| Unknown (0x0E9D)                        | 3        | 0.51%   |
| Nanya Technology                        | 3        | 0.51%   |
| Transcend                               | 2        | 0.34%   |
| Toshiba                                 | 2        | 0.34%   |
| Smart                                   | 2        | 0.34%   |
| Silicon Power Computer & Communications | 2        | 0.34%   |
| Patriot Memory (PDP Systems)            | 2        | 0.34%   |
| Gigabyte Technology                     | 2        | 0.34%   |
| Elpida                                  | 2        | 0.34%   |
| Wodposit                                | 1        | 0.17%   |
| V-Color                                 | 1        | 0.17%   |
| Unknown (0x7FFF)                        | 1        | 0.17%   |
| Unknown (0x0B85)                        | 1        | 0.17%   |
| Shenzhen Mic                            | 1        | 0.17%   |
| Ramaxel Technology                      | 1        | 0.17%   |
| PUSKILL                                 | 1        | 0.17%   |
| KLEVV                                   | 1        | 0.17%   |
| KingSpec                                | 1        | 0.17%   |
| Kingmax                                 | 1        | 0.17%   |
| Kimtigo Semiconductor (HK) Limited      | 1        | 0.17%   |
| Hewlett-Packard                         | 1        | 0.17%   |
| GeIL                                    | 1        | 0.17%   |
| Avant                                   | 1        | 0.17%   |
| Atermiter                               | 1        | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s                          | 18       | 2.84%   |
| Unknown                                                                          | 18       | 2.84%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                            | 16       | 2.52%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10       | 1.58%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 10       | 1.58%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 8        | 1.26%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8        | 1.26%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s                           | 7        | 1.1%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                            | 7        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                             | 6        | 0.95%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 6        | 0.95%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6        | 0.95%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                             | 6        | 0.95%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                              | 5        | 0.79%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                         | 4        | 0.63%   |
| Unknown RAM Module 1GB DIMM SDRAM                                                | 4        | 0.63%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                              | 4        | 0.63%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                              | 4        | 0.63%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s                             | 4        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                                         | 3        | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                              | 3        | 0.47%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                              | 3        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s                   | 3        | 0.47%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s                             | 3        | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s                              | 3        | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s                              | 3        | 0.47%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s                             | 3        | 0.47%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s                           | 3        | 0.47%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s                            | 3        | 0.47%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s                             | 3        | 0.47%   |
| Crucial RAM 524D313238363441413636372E384648FFFF 1GB DIMM DDR2 667MT/s           | 3        | 0.47%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s                           | 3        | 0.47%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s                            | 3        | 0.47%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                                     | 3        | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                        | 2        | 0.32%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                             | 2        | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                                        | 2        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                         | 2        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                         | 2        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 285      | 52.1%   |
| DDR3    | 126      | 23.03%  |
| DDR5    | 37       | 6.76%   |
| DDR2    | 32       | 5.85%   |
| Unknown | 32       | 5.85%   |
| SDRAM   | 21       | 3.84%   |
| LPDDR4  | 7        | 1.28%   |
| DDR     | 6        | 1.1%    |
| LPDDR3  | 1        | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 478      | 88.03%  |
| SODIMM       | 58       | 10.68%  |
| Row Of Chips | 4        | 0.74%   |
| RIMM         | 2        | 0.37%   |
| FB-DIMM      | 1        | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 196      | 33.73%  |
| 16384 | 117      | 20.14%  |
| 4096  | 98       | 16.87%  |
| 2048  | 75       | 12.91%  |
| 32768 | 58       | 9.98%   |
| 1024  | 26       | 4.48%   |
| 512   | 8        | 1.38%   |
| 65536 | 1        | 0.17%   |
| 6144  | 1        | 0.17%   |
| 64    | 1        | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 76       | 13.06%  |
| 2667    | 66       | 11.34%  |
| 1600    | 65       | 11.17%  |
| 1333    | 46       | 7.9%    |
| 3600    | 42       | 7.22%   |
| 2400    | 31       | 5.33%   |
| 2133    | 31       | 5.33%   |
| 667     | 24       | 4.12%   |
| 1866    | 20       | 3.44%   |
| Unknown | 16       | 2.75%   |
| 800     | 15       | 2.58%   |
| 4800    | 13       | 2.23%   |
| 6000    | 11       | 1.89%   |
| 4333    | 10       | 1.72%   |
| 1066    | 9        | 1.55%   |
| 3733    | 8        | 1.37%   |
| 3400    | 8        | 1.37%   |
| 3000    | 8        | 1.37%   |
| 1867    | 8        | 1.37%   |
| 2666    | 7        | 1.2%    |
| 5200    | 6        | 1.03%   |
| 3266    | 5        | 0.86%   |
| 3800    | 3        | 0.52%   |
| 2866    | 3        | 0.52%   |
| 1067    | 3        | 0.52%   |
| 7000    | 2        | 0.34%   |
| 5600    | 2        | 0.34%   |
| 3933    | 2        | 0.34%   |
| 3534    | 2        | 0.34%   |
| 3334    | 2        | 0.34%   |
| 2933    | 2        | 0.34%   |
| 2800    | 2        | 0.34%   |
| 2733    | 2        | 0.34%   |
| 2465    | 2        | 0.34%   |
| 1800    | 2        | 0.34%   |
| 1648    | 2        | 0.34%   |
| 1639    | 2        | 0.34%   |
| 49926   | 1        | 0.17%   |
| 6800    | 1        | 0.17%   |
| 6400    | 1        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 7        | 29.17%  |
| Brother Industries  | 5        | 20.83%  |
| Hewlett-Packard     | 4        | 16.67%  |
| Samsung Electronics | 2        | 8.33%   |
| Dymo-CoStar         | 2        | 8.33%   |
| Zebra               | 1        | 4.17%   |
| Seiko Epson         | 1        | 4.17%   |
| Pantum              | 1        | 4.17%   |
| nemonic             | 1        | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon MF3010                           | 2        | 8.33%   |
| Zebra Printer                          | 1        | 4.17%   |
| Seiko Epson ET-4850 Series             | 1        | 4.17%   |
| Samsung M2070 Series                   | 1        | 4.17%   |
| Samsung M2020 Series                   | 1        | 4.17%   |
| Pantum P2500W series                   | 1        | 4.17%   |
| nemonic MIP-001                        | 1        | 4.17%   |
| HP Officejet 4500 G510a-f              | 1        | 4.17%   |
| HP LaserJet P2035                      | 1        | 4.17%   |
| HP Laser 107a                          | 1        | 4.17%   |
| HP ENVY 5540 series                    | 1        | 4.17%   |
| Dymo-CoStar DYMO LabelWriter DUO       | 1        | 4.17%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.17%   |
| Canon TS3100 series                    | 1        | 4.17%   |
| Canon PIXMA iP4300 Printer             | 1        | 4.17%   |
| Canon MF4010 series                    | 1        | 4.17%   |
| Canon LiDE 400                         | 1        | 4.17%   |
| Canon G3010 series                     | 1        | 4.17%   |
| Brother HL-L2390DW                     | 1        | 4.17%   |
| Brother HL-3040CN series               | 1        | 4.17%   |
| Brother HL-1110 series                 | 1        | 4.17%   |
| Brother DCP-L8450CDW                   | 1        | 4.17%   |
| Brother DCP-7030                       | 1        | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 57.14%  |
| Seiko Epson     | 1        | 14.29%  |
| Plustek         | 1        | 14.29%  |
| Hewlett-Packard | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 14.29%  |
| Plustek 1200dpi USB Scanner                       | 1        | 14.29%  |
| HP ScanJet 82x0C                                  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20                | 1        | 14.29%  |
| Canon CanoScan LIDE 25                            | 1        | 14.29%  |
| Canon CanoScan LiDE 220                           | 1        | 14.29%  |
| Canon CanoScan LiDE 210                           | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 42       | 40.38%  |
| Microsoft                     | 12       | 11.54%  |
| Microdia                      | 7        | 6.73%   |
| Generalplus Technology        | 5        | 4.81%   |
| Sunplus Innovation Technology | 4        | 3.85%   |
| Samsung Electronics           | 4        | 3.85%   |
| KYE Systems (Mouse Systems)   | 4        | 3.85%   |
| Z-Star Microelectronics       | 2        | 1.92%   |
| Realtek Semiconductor         | 2        | 1.92%   |
| Jieli Technology              | 2        | 1.92%   |
| Hewlett-Packard               | 2        | 1.92%   |
| ValueHD                       | 1        | 0.96%   |
| Tobii Technology AB           | 1        | 0.96%   |
| Suyin                         | 1        | 0.96%   |
| Ruision                       | 1        | 0.96%   |
| Quanta                        | 1        | 0.96%   |
| Magic Control Technology      | 1        | 0.96%   |
| MacroSilicon                  | 1        | 0.96%   |
| IMC Networks                  | 1        | 0.96%   |
| HD 2MP WEBCAM                 | 1        | 0.96%   |
| GEMBIRD                       | 1        | 0.96%   |
| EVGA                          | 1        | 0.96%   |
| eMeet                         | 1        | 0.96%   |
| Creative Technology           | 1        | 0.96%   |
| Chicony Electronics           | 1        | 0.96%   |
| AVerMedia Technologies        | 1        | 0.96%   |
| Aveo Technology               | 1        | 0.96%   |
| Apple                         | 1        | 0.96%   |
| Anker PowerConf C200          | 1        | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 11       | 10.58%  |
| Logitech HD Pro Webcam C920             | 9        | 8.65%   |
| Microsoft LifeCam HD-3000               | 6        | 5.77%   |
| Logitech C922 Pro Stream Webcam         | 5        | 4.81%   |
| Generalplus GENERAL WEBCAM              | 5        | 4.81%   |
| Samsung Galaxy series, misc. (MTP mode) | 4        | 3.85%   |
| Logitech C920 PRO HD Webcam             | 3        | 2.88%   |
| Sunplus MTD Camera                      | 2        | 1.92%   |
| Realtek Full HD webcam                  | 2        | 1.92%   |
| Microsoft Modern Webcam                 | 2        | 1.92%   |
| Microdia Webcam Vitade AF               | 2        | 1.92%   |
| Microdia USB 2.0 Camera                 | 2        | 1.92%   |
| Logitech HD Webcam C615                 | 2        | 1.92%   |
| Logitech HD Webcam C525                 | 2        | 1.92%   |
| Logitech CrystalCam                     | 2        | 1.92%   |
| Jieli USB PHY 2.0                       | 2        | 1.92%   |
| HP Webcam 3110                          | 2        | 1.92%   |
| Z-Star Venus USB2.0 Camera              | 1        | 0.96%   |
| Z-Star A4 TECH USB2.0 PC Camera E       | 1        | 0.96%   |
| ValueHD PTZOptics                       | 1        | 0.96%   |
| Tobii AB EyeChip                        | 1        | 0.96%   |
| Suyin HD Camera                         | 1        | 0.96%   |
| Sunplus USB 2.0 Camera                  | 1        | 0.96%   |
| Sunplus Full HD webcam                  | 1        | 0.96%   |
| Ruision UVC Camera                      | 1        | 0.96%   |
| Quanta RGB-IR Camera                    | 1        | 0.96%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 1        | 0.96%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 1        | 0.96%   |
| Microsoft LifeCam VX-800                | 1        | 0.96%   |
| Microsoft LifeCam HD-5000               | 1        | 0.96%   |
| Microdia Sonix USB 2.0 Camera           | 1        | 0.96%   |
| Microdia PC-LM1E                        | 1        | 0.96%   |
| Microdia Camera                         | 1        | 0.96%   |
| Magic Control j5 WebCam JVCU435         | 1        | 0.96%   |
| MacroSilicon USB Video                  | 1        | 0.96%   |
| Logitech Webcam C310                    | 1        | 0.96%   |
| Logitech Webcam C170                    | 1        | 0.96%   |
| Logitech StreamCam                      | 1        | 0.96%   |
| Logitech QuickCam Pro 4000              | 1        | 0.96%   |
| Logitech C930c                          | 1        | 0.96%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 40%     |
| SCM Microsystems      | 1        | 20%     |
| OmniKey               | 1        | 20%     |
| Cherry                | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 40%     |
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 20%     |
| OmniKey CardMan 3021 / 3121                       | 1        | 20%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 434      | 62.99%  |
| 1     | 224      | 32.51%  |
| 2     | 29       | 4.21%   |
| 5     | 2        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 196      | 73.96%  |
| Net/wireless             | 27       | 10.19%  |
| Unassigned class         | 14       | 5.28%   |
| Communication controller | 6        | 2.26%   |
| Bluetooth                | 6        | 2.26%   |
| Storage/raid             | 3        | 1.13%   |
| Sound                    | 3        | 1.13%   |
| Multimedia controller    | 3        | 1.13%   |
| Chipcard                 | 2        | 0.75%   |
| Camera                   | 2        | 0.75%   |
| Wireless                 | 1        | 0.38%   |
| Network                  | 1        | 0.38%   |
| Modem                    | 1        | 0.38%   |

