Linux in Poland - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 2775

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | DG41RQ AAE54511-203         | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Acer          | WG43M                       | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| HP            | 1998                        | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| Acer          | WG43M                       | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | 304Ah                       | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | 03NVJ6 A02                  | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| MSI           | B85-G43                     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| MSI           | B85-G43                     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Dell          | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [afe81d4bfa](https://linux-hardware.org/?probe=afe81d4bfa) | Mar 12, 2023 |
| HP            | 213D A01                    | [8c6054a4f7](https://linux-hardware.org/?probe=8c6054a4f7) | Mar 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Biostar       | TA780G M2+                  | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| HP            | 18E5                        | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d9a9f6b904](https://linux-hardware.org/?probe=d9a9f6b904) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [5eb43b511f](https://linux-hardware.org/?probe=5eb43b511f) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [8db9ca3a4b](https://linux-hardware.org/?probe=8db9ca3a4b) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [241283977d](https://linux-hardware.org/?probe=241283977d) | Mar 04, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [07bb534dc9](https://linux-hardware.org/?probe=07bb534dc9) | Feb 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [df54545112](https://linux-hardware.org/?probe=df54545112) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [6a75456290](https://linux-hardware.org/?probe=6a75456290) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [73caef7b95](https://linux-hardware.org/?probe=73caef7b95) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| MSI           | B350M MORTAR                | [6a7ac3b38b](https://linux-hardware.org/?probe=6a7ac3b38b) | Feb 24, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [b2681528bd](https://linux-hardware.org/?probe=b2681528bd) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [39e6d492c4](https://linux-hardware.org/?probe=39e6d492c4) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [40bc5397ea](https://linux-hardware.org/?probe=40bc5397ea) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| Dell          | 0PU052                      | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Dell          | 03NVJ6 A02                  | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| ASRock        | J3355M                      | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [ae4f47209a](https://linux-hardware.org/?probe=ae4f47209a) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [f1c6e21bfb](https://linux-hardware.org/?probe=f1c6e21bfb) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | H55M-USB3                   | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| ASUSTek       | M3A78-CM                    | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| HP            | 3397                        | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| Dell          | 04YJ19 A00                  | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| ASRock        | X470 Gaming K4              | [086ea7a0e6](https://linux-hardware.org/?probe=086ea7a0e6) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| Dell          | 0DR845                      | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | DG31PR AAD97573-301         | [2080f0edf4](https://linux-hardware.org/?probe=2080f0edf4) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| MSI           | H410M-A PRO                 | [6ac747c27e](https://linux-hardware.org/?probe=6ac747c27e) | Feb 05, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [854b52f85c](https://linux-hardware.org/?probe=854b52f85c) | Feb 05, 2023 |
| Foxconn       | 2ABF                        | [54a305f83e](https://linux-hardware.org/?probe=54a305f83e) | Feb 03, 2023 |
| ASRock        | Z370 Gaming K6              | [203d5736d7](https://linux-hardware.org/?probe=203d5736d7) | Feb 03, 2023 |
| HP            | 212B                        | [f27b5c4aa0](https://linux-hardware.org/?probe=f27b5c4aa0) | Feb 03, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a4a3ea0e4e](https://linux-hardware.org/?probe=a4a3ea0e4e) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| Gigabyte      | B365M DS3H                  | [f04d195965](https://linux-hardware.org/?probe=f04d195965) | Feb 02, 2023 |
| ASUSTek       | P5QPL-AM                    | [c8ee9be68c](https://linux-hardware.org/?probe=c8ee9be68c) | Feb 02, 2023 |
| ASUSTek       | B85M-G                      | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| Gigabyte      | B365M DS3H                  | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| HP            | 8054                        | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| Dell          | 0HY9JP A00                  | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| HP            | 8054                        | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [9fcf89ea7c](https://linux-hardware.org/?probe=9fcf89ea7c) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6b5c46a680](https://linux-hardware.org/?probe=6b5c46a680) | Jan 19, 2023 |
| Huanan        | X99-TF V2.0                 | [3fa0103359](https://linux-hardware.org/?probe=3fa0103359) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Dell          | 0Y3R3K A00                  | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B560M DS3H                  | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | M3A78-CM                    | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| Gigabyte      | B365M DS3H                  | [78153a929d](https://linux-hardware.org/?probe=78153a929d) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Dell          | 0MGK50 A02                  | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Lenovo        | SKYBAY NOK                  | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | [0f51a2d7d5](https://linux-hardware.org/?probe=0f51a2d7d5) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| Dell          | 0J584C A00                  | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Dell          | 0Y3R3K A00                  | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [96150fc8a5](https://linux-hardware.org/?probe=96150fc8a5) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| HP            | 304Bh                       | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| MSI           | B250M PRO-VDH               | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Gigabyte      | H270-HD3-CF                 | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | Z97M-DS3H                   | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| HP            | ProLiant ML350 G6           | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| POSIFLEX      | KK-3703 D0                  | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| ASUSTek       | M3A78-CM                    | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| HP            | 213D A01                    | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Unknown       | HX90                        | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| MSI           | PRO H610M-B DDR4            | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Lenovo        | SKYBAY NOK                  | [24d16fa5df](https://linux-hardware.org/?probe=24d16fa5df) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0PU052                      | [b54afc7e1a](https://linux-hardware.org/?probe=b54afc7e1a) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Dell          | 0PU052                      | [802c39b94f](https://linux-hardware.org/?probe=802c39b94f) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | [220c131e59](https://linux-hardware.org/?probe=220c131e59) | Nov 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASUSTek       | M3A78-CM                    | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Intel         | H55                         | [0481a6ff8e](https://linux-hardware.org/?probe=0481a6ff8e) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| Gigabyte      | H81M-DS2                    | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| MSI           | Z97-G43                     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9914e4d771](https://linux-hardware.org/?probe=9914e4d771) | Oct 28, 2022 |
| Gigabyte      | P35-DS3L                    | [2f5cb804c0](https://linux-hardware.org/?probe=2f5cb804c0) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Dell          | 0HY9JP A00                  | [ecbfb1ca5c](https://linux-hardware.org/?probe=ecbfb1ca5c) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| ASUSTek       | M3A78-CM                    | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [7706fb5578](https://linux-hardware.org/?probe=7706fb5578) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cde031e816](https://linux-hardware.org/?probe=cde031e816) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | [be016db304](https://linux-hardware.org/?probe=be016db304) | Oct 08, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [563ae9b3df](https://linux-hardware.org/?probe=563ae9b3df) | Oct 03, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [339dcddca7](https://linux-hardware.org/?probe=339dcddca7) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Gigabyte      | Z97M-DS3H                   | [fcf7e031e3](https://linux-hardware.org/?probe=fcf7e031e3) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [1bdf72d415](https://linux-hardware.org/?probe=1bdf72d415) | Sep 27, 2022 |
| Intel         | DH61WW AAG23116-204         | [f35f96af50](https://linux-hardware.org/?probe=f35f96af50) | Sep 27, 2022 |
| Dell          | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| HP            | 805D                        | [b023737f63](https://linux-hardware.org/?probe=b023737f63) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Gigabyte      | B85M-D3H                    | [8de01689b6](https://linux-hardware.org/?probe=8de01689b6) | Sep 24, 2022 |
| HP            | 3032h                       | [efb6671159](https://linux-hardware.org/?probe=efb6671159) | Sep 23, 2022 |
| MSI           | 760GM-P34                   | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| MSI           | H81M-P33                    | [05d5a24774](https://linux-hardware.org/?probe=05d5a24774) | Sep 22, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| Dell          | 0D883F A06                  | [01c50a7a4c](https://linux-hardware.org/?probe=01c50a7a4c) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1f2bd2202c](https://linux-hardware.org/?probe=1f2bd2202c) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [b3cb8fc82e](https://linux-hardware.org/?probe=b3cb8fc82e) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| ASUSTek       | M3A78-CM                    | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Gigabyte      | G41MT-ES2L                  | [74ee0e38a3](https://linux-hardware.org/?probe=74ee0e38a3) | Sep 11, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| HP            | 1497                        | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Dell          | 0DR845                      | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| MSI           | MEG X570 ACE                | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| ASUSTek       | PRIME X470-PRO              | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [5d85db2c66](https://linux-hardware.org/?probe=5d85db2c66) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | 8054                        | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | P5B                         | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| ASUSTek       | P5K-E                       | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Gigabyte      | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| Gigabyte      | H270-Gaming 3               | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| MSI           | B365M PRO-VDH               | [213778bd3c](https://linux-hardware.org/?probe=213778bd3c) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| ASUSTek       | A88XM-E                     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| ASUSTek       | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| MSI           | A320M PRO-M2                | [43f6f3c828](https://linux-hardware.org/?probe=43f6f3c828) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X               | [b158696344](https://linux-hardware.org/?probe=b158696344) | Aug 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [70d84ddbc1](https://linux-hardware.org/?probe=70d84ddbc1) | Aug 05, 2022 |
| Gigabyte      | B550M DS3H                  | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [13eff519f6](https://linux-hardware.org/?probe=13eff519f6) | Jul 30, 2022 |
| HP            | 21B4 A01                    | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [cb1458b51e](https://linux-hardware.org/?probe=cb1458b51e) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [7940deabb7](https://linux-hardware.org/?probe=7940deabb7) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [711602c0ac](https://linux-hardware.org/?probe=711602c0ac) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [48e8d6fba9](https://linux-hardware.org/?probe=48e8d6fba9) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| MSI           | B250 PC MATE                | [dda7519d05](https://linux-hardware.org/?probe=dda7519d05) | Jul 27, 2022 |
| Dell          | 0G261D A00                  | [f7cb8645af](https://linux-hardware.org/?probe=f7cb8645af) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| ASUSTek       | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | [542296a447](https://linux-hardware.org/?probe=542296a447) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [63d34f24b6](https://linux-hardware.org/?probe=63d34f24b6) | Jul 20, 2022 |
| ASUSTek       | P5K-E                       | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| Intel         | DG31PR AAD97573-301         | [0ac01b7529](https://linux-hardware.org/?probe=0ac01b7529) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| ASUSTek       | M4A78 PRO                   | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | [fd9365ab43](https://linux-hardware.org/?probe=fd9365ab43) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| Lenovo        | SKYBAY NOK                  | [5e8f90f865](https://linux-hardware.org/?probe=5e8f90f865) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| MSI           | B250M BAZOOKA               | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| Dell          | 09KPNV A00                  | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| Gigabyte      | Z97M-DS3H                   | [6ffcfe37d6](https://linux-hardware.org/?probe=6ffcfe37d6) | Jul 03, 2022 |
| ASUSTek       | M4A78 PRO                   | [d76404df8d](https://linux-hardware.org/?probe=d76404df8d) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c8b31466ed](https://linux-hardware.org/?probe=c8b31466ed) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0ea209fffe](https://linux-hardware.org/?probe=0ea209fffe) | Jun 28, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d399933441](https://linux-hardware.org/?probe=d399933441) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| MSI           | H81M-P33                    | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| MSI           | H81M-P33                    | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Unknown       | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Dell          | 0HY9JP A00                  | [92c1597a97](https://linux-hardware.org/?probe=92c1597a97) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASRock        | P67 Pro3                    | [9804004de5](https://linux-hardware.org/?probe=9804004de5) | Jun 18, 2022 |
| Gigabyte      | Z97M-DS3H                   | [67757f27f2](https://linux-hardware.org/?probe=67757f27f2) | Jun 18, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| Dell          | 0P9XHK A00                  | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASRock        | P67 Pro3                    | [2c0a807c9c](https://linux-hardware.org/?probe=2c0a807c9c) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| ASRock        | P67 Pro3                    | [d56de69a04](https://linux-hardware.org/?probe=d56de69a04) | Jun 14, 2022 |
| Gigabyte      | Z97M-DS3H                   | [695e3a37d4](https://linux-hardware.org/?probe=695e3a37d4) | Jun 13, 2022 |
| ASRock        | P67 Pro3                    | [48cc60a732](https://linux-hardware.org/?probe=48cc60a732) | Jun 13, 2022 |
| ASUSTek       | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | 3396                        | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| Acer          | WG43M                       | [bdd6d72374](https://linux-hardware.org/?probe=bdd6d72374) | Jun 10, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| ASRock        | P67 Pro3                    | [30155bb328](https://linux-hardware.org/?probe=30155bb328) | Jun 06, 2022 |
| ASRock        | P67 Pro3                    | [a0cc6d57b8](https://linux-hardware.org/?probe=a0cc6d57b8) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Unknown       | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| Unknown       | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| HP            | 8056                        | [a52dec67e2](https://linux-hardware.org/?probe=a52dec67e2) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| ASRock        | P67 Pro3                    | [be79ac4787](https://linux-hardware.org/?probe=be79ac4787) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| ASRock        | P67 Pro3                    | [cd48749015](https://linux-hardware.org/?probe=cd48749015) | Jun 01, 2022 |
| Huanan        | X99-F8 NALEX, NALEX         | [5c3c77a5a0](https://linux-hardware.org/?probe=5c3c77a5a0) | May 31, 2022 |
| ASRock        | P67 Pro3                    | [0494b65f2c](https://linux-hardware.org/?probe=0494b65f2c) | May 31, 2022 |
| Dell          | 0J3C2F A02                  | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Gigabyte      | EP45C-DS3R                  | [dc6dbe40d9](https://linux-hardware.org/?probe=dc6dbe40d9) | May 30, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| Huanan        | X99-F8 NALEX, NALEX         | [d6de670b16](https://linux-hardware.org/?probe=d6de670b16) | May 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | [3192e3b512](https://linux-hardware.org/?probe=3192e3b512) | May 30, 2022 |
| Dell          | 0GWHMW A01                  | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| ASRock        | P67 Pro3                    | [e01dc9eb3d](https://linux-hardware.org/?probe=e01dc9eb3d) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [40ac10c85e](https://linux-hardware.org/?probe=40ac10c85e) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [bd8541bdaa](https://linux-hardware.org/?probe=bd8541bdaa) | May 28, 2022 |
| ASRock        | P67 Pro3                    | [79a9263b65](https://linux-hardware.org/?probe=79a9263b65) | May 28, 2022 |
| ASRock        | Z87 Extreme4                | [d3315c5c94](https://linux-hardware.org/?probe=d3315c5c94) | May 27, 2022 |
| Dell          | 09M8Y8 A01                  | [7514f64b6e](https://linux-hardware.org/?probe=7514f64b6e) | May 26, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| Acer          | WG43M                       | [ae5adc512f](https://linux-hardware.org/?probe=ae5adc512f) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Unknown       | Unknown                     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| HP            | 1495                        | [adf94f2549](https://linux-hardware.org/?probe=adf94f2549) | May 23, 2022 |
| HP            | 1495                        | [be2c2cbd65](https://linux-hardware.org/?probe=be2c2cbd65) | May 23, 2022 |
| HP            | 1495                        | [9d476ad9d1](https://linux-hardware.org/?probe=9d476ad9d1) | May 23, 2022 |
| HP            | 1495                        | [61f2119a07](https://linux-hardware.org/?probe=61f2119a07) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| MSI           | MS-7235                     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASRock        | P67 Pro3                    | [6bb8448487](https://linux-hardware.org/?probe=6bb8448487) | May 22, 2022 |
| MSI           | MS-7235                     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [855045a0fa](https://linux-hardware.org/?probe=855045a0fa) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [1cbf12b67a](https://linux-hardware.org/?probe=1cbf12b67a) | May 21, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| Gigabyte      | Z97M-DS3H                   | [1c9a384e09](https://linux-hardware.org/?probe=1c9a384e09) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| Dell          | 0HY9JP A02                  | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [1e1a8e1815](https://linux-hardware.org/?probe=1e1a8e1815) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [56fc7bcca2](https://linux-hardware.org/?probe=56fc7bcca2) | May 10, 2022 |
| ASRock        | B660M-ITX/ac                | [88d7b71293](https://linux-hardware.org/?probe=88d7b71293) | May 10, 2022 |
| Dell          | 07T4MC A06                  | [34e338f194](https://linux-hardware.org/?probe=34e338f194) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | H270M Pro4                  | [7fb19cf73f](https://linux-hardware.org/?probe=7fb19cf73f) | May 07, 2022 |
| ASRock        | H270M Pro4                  | [1b6f35a5d0](https://linux-hardware.org/?probe=1b6f35a5d0) | May 07, 2022 |
| MSI           | A320M-A PRO MAX             | [ccb1cda445](https://linux-hardware.org/?probe=ccb1cda445) | May 06, 2022 |
| MSI           | A320M-A PRO MAX             | [adf601077e](https://linux-hardware.org/?probe=adf601077e) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| HP            | 0B4Ch D                     | [47982d615d](https://linux-hardware.org/?probe=47982d615d) | May 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [d0b7db5920](https://linux-hardware.org/?probe=d0b7db5920) | May 02, 2022 |
| ASRock        | X370 Gaming X               | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Gigabyte      | H310M S2P                   | [c5303ab540](https://linux-hardware.org/?probe=c5303ab540) | May 01, 2022 |
| Lenovo        | ThinkCentre M58 7627AD5     | [05a686b922](https://linux-hardware.org/?probe=05a686b922) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [c2096251fc](https://linux-hardware.org/?probe=c2096251fc) | Apr 30, 2022 |
| Gigabyte      | B85M-D3H                    | [aab74c31b9](https://linux-hardware.org/?probe=aab74c31b9) | Apr 30, 2022 |
| Lenovo        | ThinkCentre M57 6072A5G     | [373677ac37](https://linux-hardware.org/?probe=373677ac37) | Apr 28, 2022 |
| ASRock        | G31M-S                      | [296df4a9d4](https://linux-hardware.org/?probe=296df4a9d4) | Apr 28, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d354934f98](https://linux-hardware.org/?probe=d354934f98) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f37918f4d4](https://linux-hardware.org/?probe=f37918f4d4) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASRock        | X570 Pro4                   | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | [d4a06d7bbe](https://linux-hardware.org/?probe=d4a06d7bbe) | Apr 24, 2022 |
| Gigabyte      | H310M H                     | [5c94950753](https://linux-hardware.org/?probe=5c94950753) | Apr 24, 2022 |
| MSI           | Z390-A PRO                  | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 821D                        | [6a70c646a5](https://linux-hardware.org/?probe=6a70c646a5) | Apr 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b65eeae8d](https://linux-hardware.org/?probe=2b65eeae8d) | Apr 24, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [e17b0d706a](https://linux-hardware.org/?probe=e17b0d706a) | Apr 23, 2022 |
| Gigabyte      | B450M GAMING                | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| Gigabyte      | Z170-Gaming K3              | [e21b7b0696](https://linux-hardware.org/?probe=e21b7b0696) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z170A GAMING M3             | [84f6645ca5](https://linux-hardware.org/?probe=84f6645ca5) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| Gigabyte      | H310M H                     | [9a462cda5a](https://linux-hardware.org/?probe=9a462cda5a) | Apr 20, 2022 |
| Gigabyte      | MZAPLBP-00                  | [62b2cada75](https://linux-hardware.org/?probe=62b2cada75) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [d162e9aa70](https://linux-hardware.org/?probe=d162e9aa70) | Apr 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [66ac59c0a3](https://linux-hardware.org/?probe=66ac59c0a3) | Apr 18, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| MSI           | B450-A PRO MAX              | [9ce44bf30d](https://linux-hardware.org/?probe=9ce44bf30d) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3                    | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| Gigabyte      | EP31-DS3L                   | [a0a68f0980](https://linux-hardware.org/?probe=a0a68f0980) | Apr 15, 2022 |
| Gigabyte      | H370M DS3H-CF               | [c3eadb27ad](https://linux-hardware.org/?probe=c3eadb27ad) | Apr 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8f490a29f3](https://linux-hardware.org/?probe=8f490a29f3) | Apr 15, 2022 |
| ASUSTek       | H61M-K                      | [b8da99fd26](https://linux-hardware.org/?probe=b8da99fd26) | Apr 14, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [0f449aecbc](https://linux-hardware.org/?probe=0f449aecbc) | Apr 13, 2022 |
| ASRock        | H97M Anniversary            | [4a73af14bf](https://linux-hardware.org/?probe=4a73af14bf) | Apr 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [40d527cfe8](https://linux-hardware.org/?probe=40d527cfe8) | Apr 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | [91037ebcec](https://linux-hardware.org/?probe=91037ebcec) | Apr 10, 2022 |
| Dell          | 0HY9JP A02                  | [84b46b3236](https://linux-hardware.org/?probe=84b46b3236) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [799106d1e6](https://linux-hardware.org/?probe=799106d1e6) | Apr 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| Intel         | DH55TC AAE70932-204         | [336fcaa613](https://linux-hardware.org/?probe=336fcaa613) | Apr 05, 2022 |
| Dell          | 0HY9JP A02                  | [ed1cda9998](https://linux-hardware.org/?probe=ed1cda9998) | Apr 05, 2022 |
| Gigabyte      | G31M-S2L                    | [7842a96018](https://linux-hardware.org/?probe=7842a96018) | Apr 05, 2022 |
| Gigabyte      | H97M-HD3                    | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| Gigabyte      | H410M H V3                  | [afc10b77f7](https://linux-hardware.org/?probe=afc10b77f7) | Apr 04, 2022 |
| Dell          | 0NDYHG A01                  | [26629406de](https://linux-hardware.org/?probe=26629406de) | Apr 03, 2022 |
| Gigabyte      | B450M S2H V2                | [f3fde51c72](https://linux-hardware.org/?probe=f3fde51c72) | Apr 03, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [01c14c16ca](https://linux-hardware.org/?probe=01c14c16ca) | Apr 03, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASRock        | X370 Killer SLI             | [ffb866117c](https://linux-hardware.org/?probe=ffb866117c) | Apr 02, 2022 |
| ASUSTek       | H81M-PLUS                   | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| Intel         | DH55TC AAE70932-204         | [5b54f9a1e1](https://linux-hardware.org/?probe=5b54f9a1e1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [405fedcff9](https://linux-hardware.org/?probe=405fedcff9) | Mar 28, 2022 |
| ASUSTek       | P7H55                       | [12a9db8849](https://linux-hardware.org/?probe=12a9db8849) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | M61VME-S2                   | [4e68853105](https://linux-hardware.org/?probe=4e68853105) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [fb365f1b1e](https://linux-hardware.org/?probe=fb365f1b1e) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [c53b2decec](https://linux-hardware.org/?probe=c53b2decec) | Mar 26, 2022 |
| ASRock        | P67 Pro3                    | [515f03c954](https://linux-hardware.org/?probe=515f03c954) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [d8b099aefa](https://linux-hardware.org/?probe=d8b099aefa) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [023e66a08d](https://linux-hardware.org/?probe=023e66a08d) | Mar 25, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [2a51a62d10](https://linux-hardware.org/?probe=2a51a62d10) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b2d23b47a5](https://linux-hardware.org/?probe=b2d23b47a5) | Mar 22, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| MSI           | B560-A PRO                  | [70f24bb773](https://linux-hardware.org/?probe=70f24bb773) | Mar 21, 2022 |
| HP            | 802E                        | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| Gigabyte      | P35-DS3P                    | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| MSI           | H81M-E34                    | [2278c36b03](https://linux-hardware.org/?probe=2278c36b03) | Mar 20, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d64fc66c4](https://linux-hardware.org/?probe=9d64fc66c4) | Mar 19, 2022 |
| Dell          | 0P611C A00                  | [0c433bca90](https://linux-hardware.org/?probe=0c433bca90) | Mar 18, 2022 |
| Gigabyte      | A520I AC                    | [5a27854c64](https://linux-hardware.org/?probe=5a27854c64) | Mar 18, 2022 |
| Dell          | 0P611C A00                  | [72593cf88a](https://linux-hardware.org/?probe=72593cf88a) | Mar 16, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [3563d1c4c9](https://linux-hardware.org/?probe=3563d1c4c9) | Mar 16, 2022 |
| MSI           | H110M PRO-D                 | [f7eac945c2](https://linux-hardware.org/?probe=f7eac945c2) | Mar 16, 2022 |
| MSI           | H110M PRO-D                 | [d31414b37d](https://linux-hardware.org/?probe=d31414b37d) | Mar 16, 2022 |
| MSI           | A88XM-E35 V2                | [4c836d3202](https://linux-hardware.org/?probe=4c836d3202) | Mar 16, 2022 |
| Dell          | 0HY9JP A02                  | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [314443b85b](https://linux-hardware.org/?probe=314443b85b) | Mar 14, 2022 |
| Intel         | DP43TF AAE34878-403         | [72da5eadd9](https://linux-hardware.org/?probe=72da5eadd9) | Mar 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [a504948f7f](https://linux-hardware.org/?probe=a504948f7f) | Mar 13, 2022 |
| MSI           | H81M-P33                    | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| MSI           | B560-A PRO                  | [b3b7fa5c21](https://linux-hardware.org/?probe=b3b7fa5c21) | Mar 12, 2022 |
| MSI           | A68HM-E33 V2                | [dfa0722637](https://linux-hardware.org/?probe=dfa0722637) | Mar 12, 2022 |
| ASUSTek       | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| Acer          | WG43M                       | [874dcfa2a0](https://linux-hardware.org/?probe=874dcfa2a0) | Mar 08, 2022 |
| Dell          | 0P611C A00                  | [8acced42b7](https://linux-hardware.org/?probe=8acced42b7) | Mar 06, 2022 |
| Gigabyte      | G41M-Combo                  | [21e65fb534](https://linux-hardware.org/?probe=21e65fb534) | Mar 04, 2022 |
| ASUSTek       | M2N-CM DVI                  | [499346b7ab](https://linux-hardware.org/?probe=499346b7ab) | Mar 04, 2022 |
| ASRock        | B450M-HDV R4.0              | [ddb21aba7b](https://linux-hardware.org/?probe=ddb21aba7b) | Mar 04, 2022 |
| HP            | 18E7                        | [795f8bd0ed](https://linux-hardware.org/?probe=795f8bd0ed) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [01922bdee0](https://linux-hardware.org/?probe=01922bdee0) | Mar 02, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [61f787045c](https://linux-hardware.org/?probe=61f787045c) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [e6bb78efda](https://linux-hardware.org/?probe=e6bb78efda) | Mar 02, 2022 |
| ASRock        | N68C-GS4 FX                 | [a6b02e2f3b](https://linux-hardware.org/?probe=a6b02e2f3b) | Mar 02, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| ASRock        | N68-S                       | [56c03860e3](https://linux-hardware.org/?probe=56c03860e3) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| Acer          | RS880M05                    | [53e88a31a0](https://linux-hardware.org/?probe=53e88a31a0) | Feb 27, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| ASUSTek       | AM1M-A                      | [6926e87bd5](https://linux-hardware.org/?probe=6926e87bd5) | Feb 26, 2022 |
| ASRock        | B450M-HDV R4.0              | [70fa55ac83](https://linux-hardware.org/?probe=70fa55ac83) | Feb 26, 2022 |
| MSI           | H410M PRO                   | [60cb5eed90](https://linux-hardware.org/?probe=60cb5eed90) | Feb 26, 2022 |
| HP            | 0AA0h                       | [eaf5cda818](https://linux-hardware.org/?probe=eaf5cda818) | Feb 24, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e4b379590](https://linux-hardware.org/?probe=7e4b379590) | Feb 22, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [77ab4a5017](https://linux-hardware.org/?probe=77ab4a5017) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| ASRock        | Z97 Pro4                    | [857a676f79](https://linux-hardware.org/?probe=857a676f79) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5b8dafb532](https://linux-hardware.org/?probe=5b8dafb532) | Feb 20, 2022 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [f5befc40e5](https://linux-hardware.org/?probe=f5befc40e5) | Feb 19, 2022 |
| Gigabyte      | Z97-HD3                     | [e9d45ff571](https://linux-hardware.org/?probe=e9d45ff571) | Feb 18, 2022 |
| ASUSTek       | H110M-R                     | [d3787fdf74](https://linux-hardware.org/?probe=d3787fdf74) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| HP            | 18E4                        | [1ddb4ff651](https://linux-hardware.org/?probe=1ddb4ff651) | Feb 18, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [d2088e6244](https://linux-hardware.org/?probe=d2088e6244) | Feb 18, 2022 |
| ABIT          | IP35-E                      | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| HP            | 821D                        | [f059d8132b](https://linux-hardware.org/?probe=f059d8132b) | Feb 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Dell          | 00V62H A01                  | [7e2f445655](https://linux-hardware.org/?probe=7e2f445655) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [9ca035e8ea](https://linux-hardware.org/?probe=9ca035e8ea) | Feb 14, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [a53c16de6d](https://linux-hardware.org/?probe=a53c16de6d) | Feb 14, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [aad23e9c01](https://linux-hardware.org/?probe=aad23e9c01) | Feb 14, 2022 |
| Lenovo        | ThinkCentre M58 7360WYV     | [dc7929d9bd](https://linux-hardware.org/?probe=dc7929d9bd) | Feb 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | [1bade168b7](https://linux-hardware.org/?probe=1bade168b7) | Feb 13, 2022 |
| MSI           | Z590 PRO WIFI               | [121d08a889](https://linux-hardware.org/?probe=121d08a889) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| HP            | 1825                        | [0e6723f81a](https://linux-hardware.org/?probe=0e6723f81a) | Feb 13, 2022 |
| Gigabyte      | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Gigabyte      | B85M-D3H                    | [02643059e9](https://linux-hardware.org/?probe=02643059e9) | Feb 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b8658db7ef](https://linux-hardware.org/?probe=b8658db7ef) | Feb 12, 2022 |
| ASRock        | 970 Pro3 R2.0               | [e9838d6bb3](https://linux-hardware.org/?probe=e9838d6bb3) | Feb 12, 2022 |
| Gigabyte      | B75M-D3V                    | [84ebaedb6c](https://linux-hardware.org/?probe=84ebaedb6c) | Feb 12, 2022 |
| HP            | 18E4                        | [ef8e0ed69f](https://linux-hardware.org/?probe=ef8e0ed69f) | Feb 11, 2022 |
| ASRock        | Q1900-ITX                   | [606783a7c4](https://linux-hardware.org/?probe=606783a7c4) | Feb 11, 2022 |
| Gigabyte      | GA-970A-UD3                 | [c68353f191](https://linux-hardware.org/?probe=c68353f191) | Feb 10, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASUSTek       | PRIME B250M-K               | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [efd6cf168c](https://linux-hardware.org/?probe=efd6cf168c) | Feb 10, 2022 |
| ASRock        | B450 Pro4                   | [9758db6134](https://linux-hardware.org/?probe=9758db6134) | Feb 09, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b01520659c](https://linux-hardware.org/?probe=b01520659c) | Feb 09, 2022 |
| ASRock        | H370M Pro4                  | [acd8487e01](https://linux-hardware.org/?probe=acd8487e01) | Feb 09, 2022 |
| Intel         | DH61WW AAG23116-204         | [638abe9878](https://linux-hardware.org/?probe=638abe9878) | Feb 09, 2022 |
| ASUSTek       | Z97I-PLUS                   | [3df98a2c5e](https://linux-hardware.org/?probe=3df98a2c5e) | Feb 09, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c904b1a608](https://linux-hardware.org/?probe=c904b1a608) | Feb 09, 2022 |
| ASUSTek       | M5A78L-M LE                 | [03c0e0a702](https://linux-hardware.org/?probe=03c0e0a702) | Feb 09, 2022 |
| MSI           | H110M PRO-D 2017-09-06      | [441f4bb2f9](https://linux-hardware.org/?probe=441f4bb2f9) | Feb 09, 2022 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [e19a7be811](https://linux-hardware.org/?probe=e19a7be811) | Feb 09, 2022 |
| Gigabyte      | H310M M.2 x.x               | [cdb7b11995](https://linux-hardware.org/?probe=cdb7b11995) | Feb 09, 2022 |
| ASRock        | B450M Steel Legend          | [f81e6843ba](https://linux-hardware.org/?probe=f81e6843ba) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASRock        | FM2A68M-HD+                 | [8545c3246e](https://linux-hardware.org/?probe=8545c3246e) | Feb 08, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [4ae22f289a](https://linux-hardware.org/?probe=4ae22f289a) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-A               | [59e0e72397](https://linux-hardware.org/?probe=59e0e72397) | Feb 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [c71df10fb4](https://linux-hardware.org/?probe=c71df10fb4) | Feb 07, 2022 |
| ASRock        | Z170 Extreme4               | [7586ccd3c6](https://linux-hardware.org/?probe=7586ccd3c6) | Feb 07, 2022 |
| HP            | 0AACh                       | [489486e81b](https://linux-hardware.org/?probe=489486e81b) | Feb 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [e21a51339e](https://linux-hardware.org/?probe=e21a51339e) | Feb 06, 2022 |
| Acer          | Predator G3120              | [d002f5e1b6](https://linux-hardware.org/?probe=d002f5e1b6) | Feb 06, 2022 |
| MSI           | Z97 GAMING 3                | [b4feb3ee6c](https://linux-hardware.org/?probe=b4feb3ee6c) | Feb 05, 2022 |
| MSI           | MS-7392                     | [e8f489c1fc](https://linux-hardware.org/?probe=e8f489c1fc) | Feb 04, 2022 |
| MSI           | X470 GAMING PLUS            | [b0c6fdf764](https://linux-hardware.org/?probe=b0c6fdf764) | Feb 04, 2022 |
| HP            | 0A80h                       | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| Acer          | Revo RN86                   | [d0b5fa877f](https://linux-hardware.org/?probe=d0b5fa877f) | Feb 04, 2022 |
| Foxconn       | 2A8Ch                       | [a4978d8283](https://linux-hardware.org/?probe=a4978d8283) | Feb 03, 2022 |
| Foxconn       | 2A8Ch                       | [1e60876b1e](https://linux-hardware.org/?probe=1e60876b1e) | Feb 03, 2022 |
| Inventec      | Z CLASS A02                 | [32bbd0c80c](https://linux-hardware.org/?probe=32bbd0c80c) | Feb 03, 2022 |
| MSI           | X570-A PRO                  | [df3c56c53c](https://linux-hardware.org/?probe=df3c56c53c) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| Dell          | 0MN1TX A02                  | [c22ec93e89](https://linux-hardware.org/?probe=c22ec93e89) | Feb 01, 2022 |
| ASRock        | X370 Gaming X               | [67d9bb3ace](https://linux-hardware.org/?probe=67d9bb3ace) | Jan 30, 2022 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [69b300dfb1](https://linux-hardware.org/?probe=69b300dfb1) | Jan 29, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| MSI           | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| Dell          | 0M9KCM A00                  | [8ce5fcb03f](https://linux-hardware.org/?probe=8ce5fcb03f) | Jan 27, 2022 |
| Acer          | Revo RN86                   | [ce1dd8b1f9](https://linux-hardware.org/?probe=ce1dd8b1f9) | Jan 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| Gigabyte      | M61VME-S2                   | [c91d9663e8](https://linux-hardware.org/?probe=c91d9663e8) | Jan 26, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [d0dde4a553](https://linux-hardware.org/?probe=d0dde4a553) | Jan 24, 2022 |
| Gigabyte      | 965P-S3                     | [9e4aca104e](https://linux-hardware.org/?probe=9e4aca104e) | Jan 24, 2022 |
| Gigabyte      | 945G-S3                     | [9adb1e8380](https://linux-hardware.org/?probe=9adb1e8380) | Jan 23, 2022 |
| MSI           | Z170A PC MATE               | [dd98b6fbca](https://linux-hardware.org/?probe=dd98b6fbca) | Jan 23, 2022 |
| HP            | 2215                        | [336671cc36](https://linux-hardware.org/?probe=336671cc36) | Jan 23, 2022 |
| HP            | 1998                        | [e728021985](https://linux-hardware.org/?probe=e728021985) | Jan 23, 2022 |
| ASRock        | H510M-ITX/ac                | [606c183545](https://linux-hardware.org/?probe=606c183545) | Jan 23, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [7f92d6ff46](https://linux-hardware.org/?probe=7f92d6ff46) | Jan 22, 2022 |
| MSI           | H110M PRO-VD PLUS           | [c51916b063](https://linux-hardware.org/?probe=c51916b063) | Jan 22, 2022 |
| ASRock        | P4i945GC                    | [b4ed754106](https://linux-hardware.org/?probe=b4ed754106) | Jan 22, 2022 |
| ASRock        | Z87 Killer                  | [0be767a418](https://linux-hardware.org/?probe=0be767a418) | Jan 22, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [fc20f2e1e3](https://linux-hardware.org/?probe=fc20f2e1e3) | Jan 22, 2022 |
| ASUSTek       | PRIME X470-PRO              | [6f8113e04c](https://linux-hardware.org/?probe=6f8113e04c) | Jan 21, 2022 |
| Foxconn       | A76GMV                      | [c25b49803b](https://linux-hardware.org/?probe=c25b49803b) | Jan 21, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| HP            | 339A                        | [9a1c8ec615](https://linux-hardware.org/?probe=9a1c8ec615) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| HP            | 1998                        | [d5e17cefbb](https://linux-hardware.org/?probe=d5e17cefbb) | Jan 20, 2022 |
| ASRock        | G31M-S                      | [9d338d58c9](https://linux-hardware.org/?probe=9d338d58c9) | Jan 20, 2022 |
| Medion        | H110H4-EM                   | [64a2a3257d](https://linux-hardware.org/?probe=64a2a3257d) | Jan 20, 2022 |
| MSI           | B450-A PRO MAX              | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| Medion        | H110H4-EM                   | [6eab6bd21a](https://linux-hardware.org/?probe=6eab6bd21a) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | [3caf7fb5f2](https://linux-hardware.org/?probe=3caf7fb5f2) | Jan 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | P9X79                       | [bfb8f77808](https://linux-hardware.org/?probe=bfb8f77808) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [e3f87f47e8](https://linux-hardware.org/?probe=e3f87f47e8) | Jan 18, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [2fdc6503ab](https://linux-hardware.org/?probe=2fdc6503ab) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| MSI           | B450-A PRO MAX              | [5baec4640b](https://linux-hardware.org/?probe=5baec4640b) | Jan 16, 2022 |
| Gigabyte      | 970A-DS3P                   | [d6d4dbbb78](https://linux-hardware.org/?probe=d6d4dbbb78) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASRock        | B550 Taichi                 | [7fca8e1118](https://linux-hardware.org/?probe=7fca8e1118) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [cd0c65171a](https://linux-hardware.org/?probe=cd0c65171a) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [77239f8808](https://linux-hardware.org/?probe=77239f8808) | Jan 15, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [5212a5cb92](https://linux-hardware.org/?probe=5212a5cb92) | Jan 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [63db02d0e6](https://linux-hardware.org/?probe=63db02d0e6) | Jan 13, 2022 |
| ASRock        | P67 Pro3                    | [12708e4124](https://linux-hardware.org/?probe=12708e4124) | Jan 11, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [004087e9c8](https://linux-hardware.org/?probe=004087e9c8) | Jan 09, 2022 |
| ASRock        | Z590 Phantom Gaming 4       | [2213b9d944](https://linux-hardware.org/?probe=2213b9d944) | Jan 09, 2022 |
| ASUSTek       | P5B-VM SE                   | [70d1a7ddc8](https://linux-hardware.org/?probe=70d1a7ddc8) | Jan 09, 2022 |
| ASUSTek       | P5B-VM SE                   | [6a043eb515](https://linux-hardware.org/?probe=6a043eb515) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [30212e6fd6](https://linux-hardware.org/?probe=30212e6fd6) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [52a27d926e](https://linux-hardware.org/?probe=52a27d926e) | Jan 07, 2022 |
| HP            | 1497                        | [adfca54c7c](https://linux-hardware.org/?probe=adfca54c7c) | Jan 07, 2022 |
| Dell          | 0WR7PY A01                  | [87ab60ffc4](https://linux-hardware.org/?probe=87ab60ffc4) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [b3d984f6a4](https://linux-hardware.org/?probe=b3d984f6a4) | Jan 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [711a037e72](https://linux-hardware.org/?probe=711a037e72) | Jan 07, 2022 |
| Gigabyte      | Z97N-WIFI                   | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Gigabyte      | B460M GAMING HD             | [4cfe82fefd](https://linux-hardware.org/?probe=4cfe82fefd) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| ASRock        | P67 Pro3                    | [db27d8ec7a](https://linux-hardware.org/?probe=db27d8ec7a) | Jan 06, 2022 |
| MSI           | B450M MORTAR MAX            | [da41cecf9e](https://linux-hardware.org/?probe=da41cecf9e) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| Dell          | 0D28YY A00                  | [8525880542](https://linux-hardware.org/?probe=8525880542) | Jan 04, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [3e37ded7e2](https://linux-hardware.org/?probe=3e37ded7e2) | Jan 04, 2022 |
| Lenovo        | SKYBAY NOK                  | [7d5840e2c1](https://linux-hardware.org/?probe=7d5840e2c1) | Jan 03, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [b924f29b41](https://linux-hardware.org/?probe=b924f29b41) | Jan 02, 2022 |
| ASUSTek       | CM1735                      | [92165700b1](https://linux-hardware.org/?probe=92165700b1) | Jan 02, 2022 |
| HP            | 2179                        | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 218      | 11.64%  |
| OpenMandriva 4.2   | 129      | 6.89%   |
| OpenMandriva 4.3   | 110      | 5.87%   |
| Ubuntu 18.04       | 107      | 5.71%   |
| Arch Rolling       | 61       | 3.26%   |
| Ubuntu 22.04       | 54       | 2.88%   |
| ROSA R10           | 47       | 2.51%   |
| ROSA R11           | 39       | 2.08%   |
| Debian 11          | 37       | 1.98%   |
| ROSA R9            | 31       | 1.66%   |
| OpenMandriva 23.01 | 31       | 1.66%   |
| Manjaro            | 29       | 1.55%   |
| ROSA R11.1         | 28       | 1.49%   |
| Zorin 16           | 27       | 1.44%   |
| Linux Mint 20.3    | 24       | 1.28%   |
| Linux Mint 20.1    | 24       | 1.28%   |
| Arch               | 24       | 1.28%   |
| Fedora 36          | 23       | 1.23%   |
| KDE neon 20.04     | 22       | 1.17%   |
| Linux Mint 20      | 21       | 1.12%   |
| Ubuntu 20.10       | 20       | 1.07%   |
| Fedora 37          | 20       | 1.07%   |
| ROSA R8.1          | 19       | 1.01%   |
| OpenMandriva 4.50  | 19       | 1.01%   |
| Ubuntu 19.10       | 18       | 0.96%   |
| Ubuntu 19.04       | 17       | 0.91%   |
| ROSA R8            | 17       | 0.91%   |
| Linux Mint 20.2    | 17       | 0.91%   |
| Fedora 35          | 17       | 0.91%   |
| Fedora 34          | 17       | 0.91%   |
| Ubuntu 21.04       | 16       | 0.85%   |
| Pop!_OS 22.04      | 16       | 0.85%   |
| Linux Mint 19.3    | 16       | 0.85%   |
| Kubuntu 20.04      | 16       | 0.85%   |
| Ubuntu 21.10       | 15       | 0.8%    |
| Pop!_OS 20.04      | 15       | 0.8%    |
| Fedora 33          | 14       | 0.75%   |
| Gentoo 2.7         | 13       | 0.69%   |
| Fedora 31          | 13       | 0.69%   |
| Debian 10          | 13       | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 452      | 26.54%  |
| OpenMandriva     | 285      | 16.74%  |
| ROSA             | 147      | 8.63%   |
| Linux Mint       | 132      | 7.75%   |
| Fedora           | 99       | 5.81%   |
| Arch             | 82       | 4.82%   |
| Manjaro          | 73       | 4.29%   |
| Debian           | 60       | 3.52%   |
| Pop!_OS          | 56       | 3.29%   |
| Kubuntu          | 39       | 2.29%   |
| Zorin            | 36       | 2.11%   |
| KDE neon         | 29       | 1.7%    |
| Xubuntu          | 21       | 1.23%   |
| Gentoo           | 21       | 1.23%   |
| openSUSE         | 14       | 0.82%   |
| Endless          | 12       | 0.7%    |
| BlackPanther     | 11       | 0.65%   |
| ArcoLinux        | 10       | 0.59%   |
| MX               | 9        | 0.53%   |
| EndeavourOS      | 9        | 0.53%   |
| Ubuntu Unity     | 8        | 0.47%   |
| Lubuntu          | 8        | 0.47%   |
| Elementary       | 8        | 0.47%   |
| Ubuntu MATE      | 7        | 0.41%   |
| LMDE             | 7        | 0.41%   |
| CentOS           | 7        | 0.41%   |
| Clear Linux      | 6        | 0.35%   |
| Kali             | 5        | 0.29%   |
| Void Linux       | 4        | 0.23%   |
| Ubuntu Budgie    | 3        | 0.18%   |
| NixOS            | 3        | 0.18%   |
| Xero             | 2        | 0.12%   |
| SteamOS          | 2        | 0.12%   |
| RHEL             | 2        | 0.12%   |
| Parrot           | 2        | 0.12%   |
| org.kde.Platform | 2        | 0.12%   |
| LinuxFX          | 2        | 0.12%   |
| Linux Lite       | 2        | 0.12%   |
| EuroLinux        | 2        | 0.12%   |
| Devuan           | 2        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 125      | 5.86%   |
| 5.16.7-desktop-1omv4003             | 97       | 4.55%   |
| 5.4.0-42-generic                    | 34       | 1.59%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 30       | 1.41%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 27       | 1.27%   |
| 6.1.1-desktop-1omv2290              | 25       | 1.17%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 22       | 1.03%   |
| 5.4.0-26-generic                    | 19       | 0.89%   |
| 5.4.0-52-generic                    | 15       | 0.7%    |
| 5.16.13-desktop-1omv4003            | 15       | 0.7%    |
| 5.15.0-56-generic                   | 15       | 0.7%    |
| 5.4.0-58-generic                    | 13       | 0.61%   |
| 5.15.0-52-generic                   | 13       | 0.61%   |
| 5.8.0-48-generic                    | 12       | 0.56%   |
| 5.4.0-72-generic                    | 12       | 0.56%   |
| 5.4.0-54-generic                    | 12       | 0.56%   |
| 5.4.0-48-generic                    | 12       | 0.56%   |
| 5.4.0-40-generic                    | 12       | 0.56%   |
| 5.19.0-35-generic                   | 12       | 0.56%   |
| 5.15.0-43-generic                   | 12       | 0.56%   |
| 5.4.0-66-generic                    | 11       | 0.52%   |
| 5.3.0-46-generic                    | 11       | 0.52%   |
| 5.13.0-39-generic                   | 11       | 0.52%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 11       | 0.52%   |
| 5.8.0-43-generic                    | 10       | 0.47%   |
| 5.4.0-56-generic                    | 10       | 0.47%   |
| 5.4.0-29-generic                    | 10       | 0.47%   |
| 5.15.0-58-generic                   | 10       | 0.47%   |
| 5.13.0-40-generic                   | 10       | 0.47%   |
| 5.13.0-27-generic                   | 10       | 0.47%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 10       | 0.47%   |
| 5.4.0-81-generic                    | 9        | 0.42%   |
| 5.4.0-65-generic                    | 9        | 0.42%   |
| 5.4.0-47-generic                    | 9        | 0.42%   |
| 5.4.0-37-generic                    | 9        | 0.42%   |
| 5.15.0-48-generic                   | 9        | 0.42%   |
| 4.18.16-desktop-1bP                 | 9        | 0.42%   |
| 5.8.0-53-generic                    | 8        | 0.38%   |
| 5.8.0-50-generic                    | 8        | 0.38%   |
| 5.8.0-44-generic                    | 8        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 290      | 14.61%  |
| 4.15.0  | 131      | 6.6%    |
| 5.10.14 | 126      | 6.35%   |
| 5.15.0  | 101      | 5.09%   |
| 5.16.7  | 99       | 4.99%   |
| 5.8.0   | 85       | 4.28%   |
| 5.11.0  | 71       | 3.58%   |
| 5.13.0  | 67       | 3.38%   |
| 5.3.0   | 56       | 2.82%   |
| 5.10.0  | 37       | 1.86%   |
| 5.0.0   | 37       | 1.86%   |
| 4.9.60  | 33       | 1.66%   |
| 5.19.0  | 30       | 1.51%   |
| 4.18.0  | 30       | 1.51%   |
| 4.9.20  | 27       | 1.36%   |
| 6.1.1   | 25       | 1.26%   |
| 4.19.0  | 19       | 0.96%   |
| 5.16.13 | 15       | 0.76%   |
| 4.1.38  | 14       | 0.71%   |
| 4.9.124 | 10       | 0.5%    |
| 4.1.34  | 10       | 0.5%    |
| 6.0.12  | 9        | 0.45%   |
| 4.9.155 | 9        | 0.45%   |
| 4.18.16 | 9        | 0.45%   |
| 5.17.5  | 8        | 0.4%    |
| 4.9.76  | 8        | 0.4%    |
| 6.0.8   | 7        | 0.35%   |
| 6.0.0   | 7        | 0.35%   |
| 5.6.0   | 7        | 0.35%   |
| 5.4.32  | 7        | 0.35%   |
| 6.2.6   | 6        | 0.3%    |
| 6.1.4   | 6        | 0.3%    |
| 6.1.12  | 6        | 0.3%    |
| 6.1.0   | 6        | 0.3%    |
| 5.9.16  | 6        | 0.3%    |
| 5.9.0   | 6        | 0.3%    |
| 5.19.5  | 6        | 0.3%    |
| 5.15.12 | 6        | 0.3%    |
| 5.12.4  | 6        | 0.3%    |
| 5.10.74 | 6        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 328      | 17.18%  |
| 5.10    | 210      | 11%     |
| 5.15    | 162      | 8.49%   |
| 5.16    | 133      | 6.97%   |
| 4.15    | 131      | 6.86%   |
| 5.8     | 106      | 5.55%   |
| 5.11    | 97       | 5.08%   |
| 5.13    | 79       | 4.14%   |
| 4.9     | 78       | 4.09%   |
| 6.1     | 62       | 3.25%   |
| 5.3     | 62       | 3.25%   |
| 5.19    | 52       | 2.72%   |
| 6.0     | 46       | 2.41%   |
| 5.0     | 41       | 2.15%   |
| 4.18    | 39       | 2.04%   |
| 5.12    | 31       | 1.62%   |
| 5.18    | 30       | 1.57%   |
| 5.14    | 28       | 1.47%   |
| 4.1     | 28       | 1.47%   |
| 5.9     | 27       | 1.41%   |
| 5.17    | 27       | 1.41%   |
| 5.6     | 24       | 1.26%   |
| 4.19    | 23       | 1.2%    |
| 5.5     | 16       | 0.84%   |
| 6.2     | 13       | 0.68%   |
| 5.7     | 13       | 0.68%   |
| 4.4     | 6        | 0.31%   |
| 4.16    | 3        | 0.16%   |
| 5.1     | 2        | 0.1%    |
| 4.8     | 2        | 0.1%    |
| 4.20    | 2        | 0.1%    |
| 5.2     | 1        | 0.05%   |
| 4.7     | 1        | 0.05%   |
| 4.14    | 1        | 0.05%   |
| 4.13    | 1        | 0.05%   |
| 4.12    | 1        | 0.05%   |
| 3.16    | 1        | 0.05%   |
| 3.13    | 1        | 0.05%   |
| 3.10    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1592     | 97.43%  |
| i686   | 40       | 2.45%   |
| ppc64  | 1        | 0.06%   |
| ppc    | 1        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 574      | 33.1%   |
| KDE5            | 503      | 29.01%  |
| Unknown         | 181      | 10.44%  |
| XFCE            | 113      | 6.52%   |
| X-Cinnamon      | 81       | 4.67%   |
| KDE4            | 78       | 4.5%    |
| KDE             | 52       | 3%      |
| MATE            | 48       | 2.77%   |
| Cinnamon        | 20       | 1.15%   |
| i3              | 16       | 0.92%   |
| LXQt            | 14       | 0.81%   |
| Unity           | 9        | 0.52%   |
| Pantheon        | 8        | 0.46%   |
| LXDE            | 8        | 0.46%   |
| Deepin          | 6        | 0.35%   |
| GNOME Flashback | 4        | 0.23%   |
| Budgie          | 4        | 0.23%   |
| GNOME Classic   | 3        | 0.17%   |
| qtile           | 2        | 0.12%   |
| awesome         | 2        | 0.12%   |
| xmonad          | 1        | 0.06%   |
| openbox         | 1        | 0.06%   |
| jwm             | 1        | 0.06%   |
| ICEWM           | 1        | 0.06%   |
| Hyprland        | 1        | 0.06%   |
| gnome-xorg      | 1        | 0.06%   |
| fluxbox         | 1        | 0.06%   |
| DWM             | 1        | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1401     | 83.1%   |
| Wayland | 165      | 9.79%   |
| Unknown | 76       | 4.51%   |
| Tty     | 44       | 2.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 740      | 43.12%  |
| SDDM    | 464      | 27.04%  |
| GDM     | 139      | 8.1%    |
| LightDM | 120      | 6.99%   |
| GDM3    | 104      | 6.06%   |
| KDM     | 86       | 5.01%   |
| TDM     | 52       | 3.03%   |
| XDM     | 4        | 0.23%   |
| SLiM    | 2        | 0.12%   |
| LXDM    | 2        | 0.12%   |
| SLIMSKI | 1        | 0.06%   |
| MDM     | 1        | 0.06%   |
| Ly      | 1        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pl_PL       | 975      | 56.75%  |
| en_US       | 374      | 21.77%  |
| Unknown     | 256      | 14.9%   |
| en_GB       | 47       | 2.74%   |
| C           | 26       | 1.51%   |
| ru_RU       | 9        | 0.52%   |
| en_CA       | 7        | 0.41%   |
| szl_PL      | 3        | 0.17%   |
| ru_UA       | 3        | 0.17%   |
| en_AG       | 3        | 0.17%   |
| de_DE       | 3        | 0.17%   |
| uk_UA       | 2        | 0.12%   |
| fr_FR       | 2        | 0.12%   |
| en_IE       | 2        | 0.12%   |
| sv_SE       | 1        | 0.06%   |
| en_US.UTF8  | 1        | 0.06%   |
| en_US.utf-8 | 1        | 0.06%   |
| en_SE       | 1        | 0.06%   |
| en_IN       | 1        | 0.06%   |
| en_DK       | 1        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1050     | 62.57%  |
| EFI  | 628      | 37.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1119     | 65.21%  |
| Overlay  | 282      | 16.43%  |
| Btrfs    | 146      | 8.51%   |
| Unknown  | 117      | 6.82%   |
| Xfs      | 23       | 1.34%   |
| Zfs      | 7        | 0.41%   |
| F2fs     | 7        | 0.41%   |
| Tmpfs    | 4        | 0.23%   |
| Ext2     | 4        | 0.23%   |
| Ext3     | 3        | 0.17%   |
| Jfs      | 2        | 0.12%   |
| SquXshfs | 1        | 0.06%   |
| Aufs     | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 827      | 48.42%  |
| GPT     | 548      | 32.08%  |
| MBR     | 333      | 19.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1271     | 75.16%  |
| Yes       | 420      | 24.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1006     | 59.81%  |
| Yes       | 676      | 40.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 390      | 23.94%  |
| ASUSTek Computer    | 364      | 22.34%  |
| MSI                 | 271      | 16.64%  |
| ASRock              | 157      | 9.64%   |
| Dell                | 140      | 8.59%   |
| Hewlett-Packard     | 104      | 6.38%   |
| Lenovo              | 57       | 3.5%    |
| Fujitsu             | 25       | 1.53%   |
| Intel               | 21       | 1.29%   |
| Acer                | 16       | 0.98%   |
| Foxconn             | 13       | 0.8%    |
| Fujitsu Siemens     | 10       | 0.61%   |
| Unknown             | 10       | 0.61%   |
| Inventec            | 5        | 0.31%   |
| Huanan              | 5        | 0.31%   |
| Medion              | 4        | 0.25%   |
| ECS                 | 4        | 0.25%   |
| ABIT                | 3        | 0.18%   |
| Supermicro          | 2        | 0.12%   |
| Pegatron            | 2        | 0.12%   |
| Hardkernel          | 2        | 0.12%   |
| Gateway             | 2        | 0.12%   |
| Biostar             | 2        | 0.12%   |
| Apple               | 2        | 0.12%   |
| AMI                 | 2        | 0.12%   |
| ACTION              | 2        | 0.12%   |
| Wortmann AG         | 1        | 0.06%   |
| WeiBu               | 1        | 0.06%   |
| Shuttle             | 1        | 0.06%   |
| POSIFLEX            | 1        | 0.06%   |
| OPTIMUS             | 1        | 0.06%   |
| Nvidia              | 1        | 0.06%   |
| MACHINIST           | 1        | 0.06%   |
| ITSUMI              | 1        | 0.06%   |
| HEDYCOMPUTER        | 1        | 0.06%   |
| Hampoo              | 1        | 0.06%   |
| EVGA                | 1        | 0.06%   |
| ASRockRack          | 1        | 0.06%   |
| AMD                 | 1        | 0.06%   |
| AAEON               | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 30       | 1.84%   |
| Gigabyte B450M DS3H          | 18       | 1.1%    |
| ASUS SABERTOOTH Z77          | 18       | 1.1%    |
| MSI MS-7B86                  | 16       | 0.98%   |
| MSI MS-7817                  | 16       | 0.98%   |
| Dell OptiPlex 780            | 15       | 0.92%   |
| MSI MS-7C02                  | 11       | 0.68%   |
| Gigabyte B450 AORUS ELITE    | 10       | 0.61%   |
| Dell OptiPlex 7010           | 10       | 0.61%   |
| Unknown                      | 10       | 0.61%   |
| MSI MS-7721                  | 9        | 0.55%   |
| Dell OptiPlex 755            | 9        | 0.55%   |
| ASUS TUF Gaming X570-PLUS    | 9        | 0.55%   |
| MSI MS-7C37                  | 8        | 0.49%   |
| MSI MS-7B79                  | 8        | 0.49%   |
| MSI MS-7A38                  | 8        | 0.49%   |
| Gigabyte B85M-D3H            | 8        | 0.49%   |
| Gigabyte B550 AORUS ELITE V2 | 8        | 0.49%   |
| ASUS PRIME B450M-A           | 8        | 0.49%   |
| ASUS PRIME X470-PRO          | 7        | 0.43%   |
| Gigabyte 970A-DS3P           | 6        | 0.37%   |
| Dell OptiPlex 790            | 6        | 0.37%   |
| ASUS PRIME B350-PLUS         | 6        | 0.37%   |
| MSI MS-7D25                  | 5        | 0.31%   |
| MSI MS-7C80                  | 5        | 0.31%   |
| MSI MS-7C52                  | 5        | 0.31%   |
| MSI MS-7B89                  | 5        | 0.31%   |
| MSI MS-7971                  | 5        | 0.31%   |
| MSI MS-7816                  | 5        | 0.31%   |
| HP t620 Quad Core TC         | 5        | 0.31%   |
| Gigabyte P31-DS3L            | 5        | 0.31%   |
| Gigabyte GA-MA770T-UD3P      | 5        | 0.31%   |
| Gigabyte G31M-S2L            | 5        | 0.31%   |
| Gigabyte A320M-S2H           | 5        | 0.31%   |
| Dell OptiPlex 9020           | 5        | 0.31%   |
| Dell OptiPlex 3040           | 5        | 0.31%   |
| ASUS TUF Gaming B550-PLUS    | 5        | 0.31%   |
| ASUS PRIME X370-PRO          | 5        | 0.31%   |
| ASUS P5G41T-M LX             | 5        | 0.31%   |
| ASUS M5A97 R2.0              | 5        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 97       | 5.95%   |
| ASUS PRIME              | 63       | 3.87%   |
| HP Compaq               | 41       | 2.52%   |
| Lenovo ThinkCentre      | 38       | 2.33%   |
| ASUS TUF                | 33       | 2.03%   |
| ASUS All                | 30       | 1.84%   |
| Gigabyte B450M          | 25       | 1.53%   |
| ASUS ROG                | 24       | 1.47%   |
| Dell Precision          | 20       | 1.23%   |
| ASUS SABERTOOTH         | 20       | 1.23%   |
| HP EliteDesk            | 19       | 1.17%   |
| Fujitsu ESPRIMO         | 17       | 1.04%   |
| MSI MS-7B86             | 16       | 0.98%   |
| MSI MS-7817             | 16       | 0.98%   |
| Gigabyte X570           | 14       | 0.86%   |
| Gigabyte B550           | 14       | 0.86%   |
| Gigabyte B450           | 14       | 0.86%   |
| MSI MS-7C02             | 11       | 0.68%   |
| Dell Vostro             | 11       | 0.68%   |
| ASUS M5A97              | 10       | 0.61%   |
| Unknown                 | 10       | 0.61%   |
| MSI MS-7721             | 9        | 0.55%   |
| ASRock B450             | 9        | 0.55%   |
| MSI MS-7C37             | 8        | 0.49%   |
| MSI MS-7B79             | 8        | 0.49%   |
| MSI MS-7A38             | 8        | 0.49%   |
| Gigabyte B85M-D3H       | 8        | 0.49%   |
| Lenovo IdeaCentre       | 7        | 0.43%   |
| Gigabyte GA-78LMT-USB3  | 7        | 0.43%   |
| ASUS P5G41T-M           | 7        | 0.43%   |
| Lenovo ThinkStation     | 6        | 0.37%   |
| HP t620                 | 6        | 0.37%   |
| HP ProDesk              | 6        | 0.37%   |
| Gigabyte Z390           | 6        | 0.37%   |
| Gigabyte B560M          | 6        | 0.37%   |
| Gigabyte 970A-DS3P      | 6        | 0.37%   |
| Fujitsu Siemens ESPRIMO | 6        | 0.37%   |
| ASUS P8Z77-V            | 6        | 0.37%   |
| ASUS M5A78L-M           | 6        | 0.37%   |
| ASRock B450M            | 6        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 182      | 11.17%  |
| 2012    | 158      | 9.7%    |
| 2013    | 143      | 8.78%   |
| 2011    | 111      | 6.81%   |
| 2019    | 110      | 6.75%   |
| 2009    | 109      | 6.69%   |
| 2014    | 106      | 6.51%   |
| 2020    | 99       | 6.08%   |
| 2017    | 94       | 5.77%   |
| 2010    | 89       | 5.46%   |
| 2007    | 86       | 5.28%   |
| 2008    | 75       | 4.6%    |
| 2015    | 70       | 4.3%    |
| 2016    | 64       | 3.93%   |
| 2021    | 58       | 3.56%   |
| 2006    | 41       | 2.52%   |
| 2022    | 16       | 0.98%   |
| 2005    | 7        | 0.43%   |
| 2004    | 4        | 0.25%   |
| Unknown | 4        | 0.25%   |
| 2023    | 2        | 0.12%   |
| 2001    | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1629     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1607     | 98.29%  |
| Enabled  | 28       | 1.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1628     | 99.94%  |
| Yes  | 1        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 369      | 21.99%  |
| 16.01-24.0      | 366      | 21.81%  |
| 3.01-4.0        | 261      | 15.55%  |
| 4.01-8.0        | 257      | 15.32%  |
| 32.01-64.0      | 228      | 13.59%  |
| 64.01-256.0     | 68       | 4.05%   |
| 1.01-2.0        | 52       | 3.1%    |
| 24.01-32.0      | 42       | 2.5%    |
| 2.01-3.0        | 25       | 1.49%   |
| 0.51-1.0        | 9        | 0.54%   |
| More than 256.0 | 1        | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 729      | 38.41%  |
| 2.01-3.0    | 373      | 19.65%  |
| 4.01-8.0    | 253      | 13.33%  |
| 0.51-1.0    | 198      | 10.43%  |
| 3.01-4.0    | 186      | 9.8%    |
| 8.01-16.0   | 78       | 4.11%   |
| 0.01-0.5    | 40       | 2.11%   |
| 16.01-24.0  | 28       | 1.48%   |
| 24.01-32.0  | 7        | 0.37%   |
| 32.01-64.0  | 3        | 0.16%   |
| 64.01-256.0 | 2        | 0.11%   |
| Unknown     | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 625      | 35.92%  |
| 2      | 514      | 29.54%  |
| 3      | 304      | 17.47%  |
| 4      | 148      | 8.51%   |
| 5      | 67       | 3.85%   |
| 6      | 28       | 1.61%   |
| 0      | 24       | 1.38%   |
| 7      | 14       | 0.8%    |
| 8      | 7        | 0.4%    |
| 9      | 3        | 0.17%   |
| 11     | 2        | 0.11%   |
| 10     | 2        | 0.11%   |
| 13     | 1        | 0.06%   |
| 12     | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 849      | 51.11%  |
| No        | 812      | 48.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1614     | 99.08%  |
| No        | 15       | 0.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1012     | 60.71%  |
| Yes       | 655      | 39.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1256     | 75.75%  |
| Yes       | 402      | 24.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 1629     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 330      | 18.24%  |
| Krakow                 | 117      | 6.47%   |
| Wroclaw                | 106      | 5.86%   |
| Poznan                 | 70       | 3.87%   |
| Katowice               | 53       | 2.93%   |
| Gdansk                 | 52       | 2.87%   |
| Lodz                   | 43       | 2.38%   |
| Lublin                 | 23       | 1.27%   |
| Gdynia                 | 22       | 1.22%   |
| Bialystok              | 21       | 1.16%   |
| Strzyzow               | 18       | 1%      |
| Gliwice                | 18       | 1%      |
| Częstochowa           | 18       | 1%      |
| Szczecin               | 17       | 0.94%   |
| Rzeszów               | 15       | 0.83%   |
| Bytom                  | 15       | 0.83%   |
| Torun                  | 14       | 0.77%   |
| Radom                  | 13       | 0.72%   |
| Płock                 | 12       | 0.66%   |
| Bydgoszcz              | 12       | 0.66%   |
| Bielsko-Biala          | 12       | 0.66%   |
| Rybnik                 | 11       | 0.61%   |
| Sosnowiec              | 9        | 0.5%    |
| Ruda Śląska          | 9        | 0.5%    |
| Wodzisław Śląski    | 8        | 0.44%   |
| Kielce                 | 8        | 0.44%   |
| Jaworzno               | 8        | 0.44%   |
| Debica                 | 8        | 0.44%   |
| Zabrze                 | 7        | 0.39%   |
| Wołomin               | 7        | 0.39%   |
| Tarnów                | 7        | 0.39%   |
| Siemianowice Śląskie | 7        | 0.39%   |
| Piaseczno              | 7        | 0.39%   |
| Będzin                | 7        | 0.39%   |
| Zdunska Wola           | 6        | 0.33%   |
| Tychy                  | 6        | 0.33%   |
| Swidnica               | 6        | 0.33%   |
| Olsztyn                | 6        | 0.33%   |
| Lubin                  | 6        | 0.33%   |
| Legnica                | 6        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 546      | 959    | 17.59%  |
| WDC                       | 536      | 920    | 17.27%  |
| Samsung Electronics       | 388      | 691    | 12.5%   |
| GOODRAM                   | 226      | 372    | 7.28%   |
| Toshiba                   | 182      | 327    | 5.86%   |
| Crucial                   | 137      | 243    | 4.41%   |
| Kingston                  | 129      | 192    | 4.16%   |
| A-DATA Technology         | 126      | 197    | 4.06%   |
| Hitachi                   | 94       | 163    | 3.03%   |
| SanDisk                   | 85       | 137    | 2.74%   |
| Patriot                   | 52       | 67     | 1.68%   |
| XPG                       | 37       | 54     | 1.19%   |
| SPCC                      | 37       | 65     | 1.19%   |
| Intel                     | 37       | 61     | 1.19%   |
| Plextor                   | 31       | 36     | 1%      |
| HGST                      | 31       | 44     | 1%      |
| PNY                       | 25       | 28     | 0.81%   |
| Phison                    | 25       | 34     | 0.81%   |
| Apacer                    | 24       | 40     | 0.77%   |
| Unknown                   | 21       | 36     | 0.68%   |
| OCZ                       | 21       | 24     | 0.68%   |
| Maxtor                    | 21       | 21     | 0.68%   |
| Corsair                   | 20       | 28     | 0.64%   |
| Micron Technology         | 18       | 26     | 0.58%   |
| Fujitsu                   | 16       | 19     | 0.52%   |
| Realtek Semiconductor     | 15       | 25     | 0.48%   |
| ASMT                      | 14       | 15     | 0.45%   |
| SK hynix                  | 13       | 23     | 0.42%   |
| Lite-On                   | 12       | 14     | 0.39%   |
| China                     | 12       | 12     | 0.39%   |
| Silicon Motion            | 10       | 12     | 0.32%   |
| Phison Electronics        | 10       | 20     | 0.32%   |
| Micron/Crucial Technology | 10       | 10     | 0.32%   |
| JMicron Technology        | 8        | 9      | 0.26%   |
| KIOXIA-EXCERIA            | 7        | 12     | 0.23%   |
| KIOXIA                    | 7        | 8      | 0.23%   |
| ADATA Technology          | 7        | 8      | 0.23%   |
| Transcend                 | 6        | 6      | 0.19%   |
| LITEON                    | 6        | 11     | 0.19%   |
| Lexar                     | 6        | 6      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                | 52       | 1.45%   |
| Seagate ST500DM002-1BD142 500GB    | 37       | 1.03%   |
| Crucial CT500MX500SSD1 500GB       | 33       | 0.92%   |
| Samsung SSD 850 EVO 250GB          | 32       | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB     | 28       | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB     | 28       | 0.78%   |
| Seagate ST3500418AS 500GB          | 27       | 0.75%   |
| GOODRAM SSD 120GB                  | 27       | 0.75%   |
| Samsung NVMe SSD Drive 500GB       | 26       | 0.72%   |
| Samsung HD502HJ 500GB              | 25       | 0.7%    |
| Crucial CT1000MX500SSD1 1TB        | 24       | 0.67%   |
| Kingston SV300S37A120G 120GB SSD   | 23       | 0.64%   |
| Toshiba DT01ACA100 1TB             | 22       | 0.61%   |
| Samsung SSD 860 EVO 250GB          | 21       | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB     | 20       | 0.56%   |
| Samsung SSD 860 EVO 500GB          | 19       | 0.53%   |
| GOODRAM SSDPR-CX400-512 512GB      | 19       | 0.53%   |
| Toshiba HDWD130 3TB                | 18       | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB     | 18       | 0.5%    |
| GOODRAM SSD 240GB                  | 18       | 0.5%    |
| A-DATA SU800 256GB SSD             | 18       | 0.5%    |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 17       | 0.47%   |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 17       | 0.47%   |
| Patriot Burst 120GB SSD            | 15       | 0.42%   |
| GOODRAM SSDPR-CL100-120-G2 120GB   | 15       | 0.42%   |
| Crucial CT240BX500SSD1 240GB       | 15       | 0.42%   |
| Samsung HD103SJ 1TB                | 14       | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 14       | 0.39%   |
| GOODRAM SSDPR-CX400-128 128GB      | 14       | 0.39%   |
| A-DATA SX8200PNP 512GB             | 14       | 0.39%   |
| SPCC Solid State Disk 120GB        | 13       | 0.36%   |
| Seagate ST3250410AS 250GB          | 13       | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 13       | 0.36%   |
| Samsung NVMe SSD Drive 1TB         | 13       | 0.36%   |
| Kingston SA400S37240G 240GB SSD    | 13       | 0.36%   |
| A-DATA SU650 240GB SSD             | 13       | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 12       | 0.33%   |
| Toshiba HDWD120 2TB                | 12       | 0.33%   |
| Seagate ST3500312CS 500GB          | 12       | 0.33%   |
| Seagate ST3250310AS 250GB          | 12       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 546      | 957    | 35.43%  |
| WDC                 | 507      | 863    | 32.9%   |
| Toshiba             | 166      | 309    | 10.77%  |
| Samsung Electronics | 131      | 198    | 8.5%    |
| Hitachi             | 94       | 163    | 6.1%    |
| HGST                | 31       | 44     | 2.01%   |
| Maxtor              | 20       | 20     | 1.3%    |
| Fujitsu             | 16       | 19     | 1.04%   |
| ASMT                | 14       | 15     | 0.91%   |
| Unknown             | 2        | 2      | 0.13%   |
| ASMedia             | 2        | 3      | 0.13%   |
| Unknown             | 2        | 2      | 0.13%   |
| WD MediaMax         | 1        | 2      | 0.06%   |
| Synology            | 1        | 1      | 0.06%   |
| PHD 3.0             | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HPE                 | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Hewlett-Packard     | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| GOODRAM             | 220      | 354    | 20.3%   |
| Samsung Electronics | 165      | 255    | 15.22%  |
| Crucial             | 132      | 237    | 12.18%  |
| A-DATA Technology   | 101      | 155    | 9.32%   |
| Kingston            | 87       | 126    | 8.03%   |
| SanDisk             | 66       | 108    | 6.09%   |
| Patriot             | 45       | 60     | 4.15%   |
| SPCC                | 32       | 58     | 2.95%   |
| WDC                 | 27       | 34     | 2.49%   |
| Plextor             | 25       | 30     | 2.31%   |
| Apacer              | 23       | 39     | 2.12%   |
| OCZ                 | 21       | 24     | 1.94%   |
| PNY                 | 19       | 22     | 1.75%   |
| Intel               | 16       | 22     | 1.48%   |
| Micron Technology   | 14       | 20     | 1.29%   |
| Toshiba             | 12       | 14     | 1.11%   |
| China               | 11       | 11     | 1.01%   |
| Corsair             | 8        | 9      | 0.74%   |
| Transcend           | 6        | 6      | 0.55%   |
| LITEON              | 6        | 11     | 0.55%   |
| KIOXIA-EXCERIA      | 4        | 8      | 0.37%   |
| JMicron Technology  | 4        | 4      | 0.37%   |
| Lexar               | 3        | 3      | 0.28%   |
| KingSpec            | 3        | 3      | 0.28%   |
| Intenso             | 3        | 8      | 0.28%   |
| BIWIN               | 3        | 3      | 0.28%   |
| Team                | 2        | 2      | 0.18%   |
| SK hynix            | 2        | 2      | 0.18%   |
| LITEONIT            | 2        | 2      | 0.18%   |
| HS-SSD-E100         | 2        | 2      | 0.18%   |
| XrayDisk            | 1        | 1      | 0.09%   |
| XPG                 | 1        | 1      | 0.09%   |
| WDC WDS2            | 1        | 1      | 0.09%   |
| Valuetech           | 1        | 1      | 0.09%   |
| Unknown             | 1        | 1      | 0.09%   |
| T-FORCE             | 1        | 1      | 0.09%   |
| SSSTC               | 1        | 1      | 0.09%   |
| Phison              | 1        | 1      | 0.09%   |
| Origin              | 1        | 1      | 0.09%   |
| OCZ-AGIL            | 1        | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1186     | 2606   | 46.29%  |
| SSD     | 896      | 1653   | 34.97%  |
| NVMe    | 431      | 774    | 16.82%  |
| Unknown | 40       | 66     | 1.56%   |
| MMC     | 9        | 9      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1494     | 4187   | 73.7%   |
| NVMe | 431      | 773    | 21.26%  |
| SAS  | 93       | 139    | 4.59%   |
| MMC  | 9        | 9      | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1233     | 2497   | 57%     |
| 0.51-1.0        | 583      | 1068   | 26.95%  |
| 1.01-2.0        | 179      | 306    | 8.28%   |
| 3.01-4.0        | 58       | 119    | 2.68%   |
| 2.01-3.0        | 56       | 143    | 2.59%   |
| 4.01-10.0       | 36       | 80     | 1.66%   |
| 10.01-20.0      | 15       | 28     | 0.69%   |
| More than 100.0 | 3        | 18     | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 435      | 23.99%  |
| 251-500        | 253      | 13.95%  |
| 501-1000       | 232      | 12.8%   |
| 1-20           | 201      | 11.09%  |
| 1001-2000      | 188      | 10.37%  |
| 51-100         | 144      | 7.94%   |
| More than 3000 | 112      | 6.18%   |
| Unknown        | 96       | 5.3%    |
| 21-50          | 84       | 4.63%   |
| 2001-3000      | 68       | 3.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 706      | 38.12%  |
| 21-50          | 232      | 12.53%  |
| 101-250        | 194      | 10.48%  |
| 51-100         | 161      | 8.69%   |
| 501-1000       | 146      | 7.88%   |
| 251-500        | 143      | 7.72%   |
| Unknown        | 96       | 5.18%   |
| 1001-2000      | 93       | 5.02%   |
| More than 3000 | 41       | 2.21%   |
| 2001-3000      | 40       | 2.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB           | 8        | 11     | 2.25%   |
| Seagate ST500DM002-1BD142 500GB     | 7        | 7      | 1.97%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 6      | 1.69%   |
| Seagate ST9500325AS 500GB           | 5        | 8      | 1.41%   |
| GOODRAM SSD 120GB                   | 5        | 5      | 1.41%   |
| ASMT 2135 12TB                      | 5        | 5      | 1.41%   |
| Seagate ST92505610AS 250GB          | 4        | 4      | 1.13%   |
| Seagate ST3320613AS 320GB           | 4        | 4      | 1.13%   |
| Seagate ST1000DX001-1CM162 1TB      | 4        | 7      | 1.13%   |
| Seagate ST3500312CS 500GB           | 3        | 3      | 0.85%   |
| Seagate ST3320418AS 320GB           | 3        | 3      | 0.85%   |
| Seagate ST3250410AS 250GB           | 3        | 3      | 0.85%   |
| Seagate ST31500341AS 1TB            | 3        | 4      | 0.85%   |
| Seagate ST2000DX002-2DV164 2TB      | 3        | 5      | 0.85%   |
| Samsung Electronics HD502HJ 500GB   | 3        | 3      | 0.85%   |
| Samsung Electronics HD321KJ 320GB   | 3        | 3      | 0.85%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.85%   |
| Kingston SA400S37480G 480GB SSD     | 3        | 3      | 0.85%   |
| WDC WD5002ABYS-01B1B0 500GB         | 2        | 14     | 0.56%   |
| WDC WD5000AVDS-63U7B1 500GB         | 2        | 2      | 0.56%   |
| WDC WD5000AACS-00G8B1 500GB         | 2        | 2      | 0.56%   |
| WDC WD3200AAJS-00B4A0 320GB         | 2        | 4      | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 10     | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 2      | 0.56%   |
| WDC WD15EARS-00Z5B1 1TB             | 2        | 2      | 0.56%   |
| WDC WD10JFCX-68N6GN0 1TB            | 2        | 3      | 0.56%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 3      | 0.56%   |
| WDC WD10EADS-22M2B0 1TB             | 2        | 4      | 0.56%   |
| Toshiba MQ04ABF100 1TB              | 2        | 3      | 0.56%   |
| Toshiba MK2546GSX 250GB             | 2        | 2      | 0.56%   |
| Toshiba DT01ACA100 1TB              | 2        | 2      | 0.56%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 2      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB     | 2        | 2      | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 2      | 0.56%   |
| Seagate ST3500320AS 500GB           | 2        | 2      | 0.56%   |
| Seagate ST3320620AS 320GB           | 2        | 2      | 0.56%   |
| Seagate ST3250310AS 250GB           | 2        | 2      | 0.56%   |
| Seagate ST3200826AS 200GB           | 2        | 2      | 0.56%   |
| Seagate ST31000528AS 1TB            | 2        | 2      | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 2      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 110      | 147    | 33.43%  |
| WDC                   | 82       | 136    | 24.92%  |
| Samsung Electronics   | 32       | 38     | 9.73%   |
| Hitachi               | 20       | 30     | 6.08%   |
| Toshiba               | 11       | 12     | 3.34%   |
| A-DATA Technology     | 11       | 12     | 3.34%   |
| SanDisk               | 9        | 11     | 2.74%   |
| Kingston              | 8        | 8      | 2.43%   |
| GOODRAM               | 8        | 8      | 2.43%   |
| ASMT                  | 6        | 7      | 1.82%   |
| Maxtor                | 5        | 5      | 1.52%   |
| Fujitsu               | 4        | 6      | 1.22%   |
| Hewlett-Packard       | 3        | 3      | 0.91%   |
| Apacer                | 3        | 6      | 0.91%   |
| SPCC                  | 2        | 2      | 0.61%   |
| HGST                  | 2        | 2      | 0.61%   |
| XPG                   | 1        | 1      | 0.3%    |
| WDC WDS2              | 1        | 1      | 0.3%    |
| WD MediaMax           | 1        | 2      | 0.3%    |
| SSSTC                 | 1        | 1      | 0.3%    |
| Realtek Semiconductor | 1        | 1      | 0.3%    |
| OCZ                   | 1        | 1      | 0.3%    |
| LITEONIT              | 1        | 1      | 0.3%    |
| LITEON                | 1        | 1      | 0.3%    |
| KingFast              | 1        | 1      | 0.3%    |
| Intel                 | 1        | 1      | 0.3%    |
| Crucial               | 1        | 1      | 0.3%    |
| Corsair               | 1        | 2      | 0.3%    |
| Unknown               | 1        | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 110      | 147    | 40.74%  |
| WDC                 | 81       | 134    | 30%     |
| Samsung Electronics | 28       | 34     | 10.37%  |
| Hitachi             | 20       | 30     | 7.41%   |
| Toshiba             | 11       | 12     | 4.07%   |
| ASMT                | 6        | 7      | 2.22%   |
| Maxtor              | 5        | 5      | 1.85%   |
| Fujitsu             | 4        | 6      | 1.48%   |
| HGST                | 2        | 2      | 0.74%   |
| WD MediaMax         | 1        | 2      | 0.37%   |
| Hewlett-Packard     | 1        | 1      | 0.37%   |
| Unknown             | 1        | 1      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 240      | 381    | 80.27%  |
| SSD  | 53       | 61     | 17.73%  |
| NVMe | 6        | 6      | 2.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB       | 1        | 1      | 14.29%  |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 14.29%  |
| Toshiba DT01ACA100 1TB            | 1        | 2      | 14.29%  |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 14.29%  |
| OCZ-AGIL ITY3 64GB SSD            | 1        | 1      | 14.29%  |
| HGST HTS725025A7 250GB            | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 28.57%  |
| Toshiba             | 1        | 2      | 14.29%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| OCZ-AGIL            | 1        | 1      | 14.29%  |
| HGST                | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 849      | 2525   | 44.66%  |
| Works    | 755      | 2127   | 39.72%  |
| Malfunc  | 290      | 448    | 15.26%  |
| Failed   | 7        | 8      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 990      | 41.67%  |
| AMD                            | 556      | 23.4%   |
| Samsung Electronics            | 146      | 6.14%   |
| ASMedia Technology             | 94       | 3.96%   |
| JMicron Technology             | 89       | 3.75%   |
| Nvidia                         | 68       | 2.86%   |
| Phison Electronics             | 67       | 2.82%   |
| ADATA Technology               | 65       | 2.74%   |
| Kingston Technology Company    | 49       | 2.06%   |
| Marvell Technology Group       | 42       | 1.77%   |
| SanDisk                        | 35       | 1.47%   |
| Silicon Motion                 | 23       | 0.97%   |
| Realtek Semiconductor          | 23       | 0.97%   |
| Lite-On Technology             | 18       | 0.76%   |
| VIA Technologies               | 16       | 0.67%   |
| Micron/Crucial Technology      | 14       | 0.59%   |
| LSI Logic / Symbios Logic      | 12       | 0.51%   |
| KIOXIA                         | 12       | 0.51%   |
| SK hynix                       | 9        | 0.38%   |
| Shenzhen Longsys Electronics   | 9        | 0.38%   |
| Silicon Image                  | 7        | 0.29%   |
| Micron Technology              | 5        | 0.21%   |
| Hewlett-Packard                | 4        | 0.17%   |
| Broadcom / LSI                 | 4        | 0.17%   |
| Toshiba America Info Systems   | 3        | 0.13%   |
| INNOGRIT                       | 3        | 0.13%   |
| Union Memory (Shenzhen)        | 2        | 0.08%   |
| ULi Electronics                | 2        | 0.08%   |
| Solid State Storage Technology | 2        | 0.08%   |
| Integrated Technology Express  | 2        | 0.08%   |
| Tekram Technology              | 1        | 0.04%   |
| Seagate Technology             | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 1        | 0.04%   |
| Broadcom                       | 1        | 0.04%   |
| Adaptec                        | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 317      | 10.31%  |
| AMD 400 Series Chipset SATA Controller                                                  | 153      | 4.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 127      | 4.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 94       | 3.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 92       | 2.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 90       | 2.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 89       | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 84       | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 80       | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 74       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 73       | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 68       | 2.21%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 64       | 2.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 61       | 1.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 60       | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 57       | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 51       | 1.66%   |
| AMD 500 Series Chipset SATA Controller                                                  | 51       | 1.66%   |
| Intel SATA Controller [RAID mode]                                                       | 50       | 1.63%   |
| Nvidia MCP61 SATA Controller                                                            | 37       | 1.2%    |
| Phison E12 NVMe Controller                                                              | 36       | 1.17%   |
| Nvidia MCP61 IDE                                                                        | 36       | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 33       | 1.07%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 32       | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 27       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 27       | 0.88%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 25       | 0.81%   |
| Kingston Company A2000 NVMe SSD                                                         | 24       | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 24       | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                                  | 24       | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 23       | 0.75%   |
| Samsung NVMe SSD Controller 980                                                         | 22       | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 21       | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 19       | 0.62%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 19       | 0.62%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 19       | 0.62%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 18       | 0.59%   |
| JMicron JMB368 IDE controller                                                           | 17       | 0.55%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 0.55%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 17       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1264     | 54.25%  |
| IDE  | 516      | 22.15%  |
| NVMe | 438      | 18.8%   |
| RAID | 90       | 3.86%   |
| SAS  | 11       | 0.47%   |
| SCSI | 11       | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1001     | 61.45%  |
| AMD          | 626      | 38.43%  |
| PowerMac11,2 | 1        | 0.06%   |
| PowerBook6,7 | 1        | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 39       | 2.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 26       | 1.58%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 1.34%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 22       | 1.34%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 20       | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 19       | 1.15%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 18       | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 18       | 1.09%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 15       | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 0.91%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 15       | 0.91%   |
| AMD Phenom II X4 955 Processor              | 15       | 0.91%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 14       | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 13       | 0.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 13       | 0.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 11       | 0.67%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 11       | 0.67%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 11       | 0.67%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 11       | 0.67%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 10       | 0.61%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 10       | 0.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 10       | 0.61%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 10       | 0.61%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 10       | 0.61%   |
| AMD FX-8350 Eight-Core Processor            | 10       | 0.61%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 0.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 9        | 0.55%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 9        | 0.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 0.55%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 9        | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8        | 0.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 8        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 309      | 18.83%  |
| Intel Core i7           | 161      | 9.81%   |
| AMD Ryzen 5             | 160      | 9.75%   |
| Intel Core i3           | 99       | 6.03%   |
| AMD Ryzen 7             | 89       | 5.42%   |
| Intel Xeon              | 86       | 5.24%   |
| Intel Core 2 Duo        | 81       | 4.94%   |
| Intel Core 2 Quad       | 59       | 3.6%    |
| AMD FX                  | 48       | 2.93%   |
| AMD Ryzen 9             | 44       | 2.68%   |
| Intel Pentium           | 43       | 2.62%   |
| Intel Celeron           | 37       | 2.25%   |
| AMD Phenom II X4        | 37       | 2.25%   |
| Other                   | 34       | 2.07%   |
| Intel Pentium Dual-Core | 32       | 1.95%   |
| AMD Athlon 64 X2        | 30       | 1.83%   |
| AMD Ryzen 3             | 29       | 1.77%   |
| AMD Athlon II X2        | 27       | 1.65%   |
| Intel Core 2            | 20       | 1.22%   |
| AMD A10                 | 19       | 1.16%   |
| AMD Athlon II X4        | 18       | 1.1%    |
| AMD A8                  | 17       | 1.04%   |
| Intel Pentium Dual      | 15       | 0.91%   |
| AMD Ryzen Threadripper  | 11       | 0.67%   |
| AMD A6                  | 11       | 0.67%   |
| Intel Core i9           | 10       | 0.61%   |
| AMD Athlon              | 9        | 0.55%   |
| AMD GX                  | 8        | 0.49%   |
| Intel Pentium D         | 7        | 0.43%   |
| Intel Pentium 4         | 7        | 0.43%   |
| AMD Phenom II X6        | 7        | 0.43%   |
| AMD Athlon 64           | 7        | 0.43%   |
| AMD A4                  | 7        | 0.43%   |
| Intel Pentium Gold      | 6        | 0.37%   |
| AMD Sempron             | 6        | 0.37%   |
| AMD Athlon II X3        | 6        | 0.37%   |
| Intel Atom              | 5        | 0.3%    |
| AMD Ryzen 5 PRO         | 5        | 0.3%    |
| AMD Phenom II X2        | 5        | 0.3%    |
| AMD G                   | 5        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 650      | 39.35%  |
| 2       | 426      | 25.79%  |
| 6       | 254      | 15.38%  |
| 8       | 132      | 7.99%   |
| 12      | 49       | 2.97%   |
| Unknown | 45       | 2.72%   |
| 1       | 37       | 2.24%   |
| 16      | 22       | 1.33%   |
| 3       | 21       | 1.27%   |
| 10      | 8        | 0.48%   |
| 32      | 2        | 0.12%   |
| 24      | 2        | 0.12%   |
| 64      | 1        | 0.06%   |
| 44      | 1        | 0.06%   |
| 20      | 1        | 0.06%   |
| 18      | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1606     | 98.53%  |
| 2      | 24       | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 828      | 50.27%  |
| 2       | 774      | 46.99%  |
| Unknown | 45       | 2.73%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1611     | 98.59%  |
| Unknown        | 17       | 1.04%   |
| 32-bit         | 6        | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 342      | 20.02%  |
| 0x306c3    | 149      | 8.72%   |
| 0x1067a    | 106      | 6.21%   |
| 0x306a9    | 96       | 5.62%   |
| 0x206a7    | 79       | 4.63%   |
| 0x0800820d | 62       | 3.63%   |
| 0x506e3    | 60       | 3.51%   |
| 0x08701021 | 56       | 3.28%   |
| 0x010000c8 | 49       | 2.87%   |
| 0x906ea    | 44       | 2.58%   |
| 0x906e9    | 40       | 2.34%   |
| 0x08701013 | 27       | 1.58%   |
| 0x6fb      | 26       | 1.52%   |
| 0x10676    | 24       | 1.41%   |
| 0x06001119 | 24       | 1.41%   |
| 0xa0653    | 23       | 1.35%   |
| 0x06000852 | 22       | 1.29%   |
| 0x08001138 | 21       | 1.23%   |
| 0x6fd      | 18       | 1.05%   |
| 0x06003106 | 17       | 1%      |
| 0x206c2    | 15       | 0.88%   |
| 0x106e5    | 15       | 0.88%   |
| 0x10677    | 15       | 0.88%   |
| 0x6f6      | 14       | 0.82%   |
| 0x0a201016 | 13       | 0.76%   |
| 0x08101016 | 12       | 0.7%    |
| 0x08001137 | 12       | 0.7%    |
| 0x0a201009 | 11       | 0.64%   |
| 0x08108109 | 11       | 0.64%   |
| 0x010000db | 11       | 0.64%   |
| 0xa0671    | 10       | 0.59%   |
| 0xa0655    | 10       | 0.59%   |
| 0x0a50000c | 10       | 0.59%   |
| 0x306f2    | 9        | 0.53%   |
| 0x206d7    | 9        | 0.53%   |
| 0x906ed    | 8        | 0.47%   |
| 0x906ec    | 8        | 0.47%   |
| 0x90672    | 8        | 0.47%   |
| 0x906eb    | 7        | 0.41%   |
| 0x6f2      | 7        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 180      | 10.97%  |
| Penryn           | 153      | 9.32%   |
| KabyLake         | 130      | 7.92%   |
| IvyBridge        | 115      | 7.01%   |
| Zen 2            | 112      | 6.83%   |
| K10              | 107      | 6.52%   |
| SandyBridge      | 103      | 6.28%   |
| Zen+             | 96       | 5.85%   |
| Core             | 81       | 4.94%   |
| Skylake          | 77       | 4.69%   |
| Zen              | 68       | 4.14%   |
| Piledriver       | 62       | 3.78%   |
| Zen 3            | 57       | 3.47%   |
| K8 Hammer        | 50       | 3.05%   |
| CometLake        | 40       | 2.44%   |
| Unknown          | 32       | 1.95%   |
| Westmere         | 26       | 1.58%   |
| Nehalem          | 26       | 1.58%   |
| Steamroller      | 18       | 1.1%    |
| NetBurst         | 17       | 1.04%   |
| Jaguar           | 13       | 0.79%   |
| Bulldozer        | 12       | 0.73%   |
| Silvermont       | 11       | 0.67%   |
| Alderlake Hybrid | 11       | 0.67%   |
| Bobcat           | 10       | 0.61%   |
| K10 Llano        | 7        | 0.43%   |
| Icelake          | 7        | 0.43%   |
| Broadwell        | 5        | 0.3%    |
| Goldmont plus    | 4        | 0.24%   |
| Goldmont         | 4        | 0.24%   |
| Excavator        | 3        | 0.18%   |
| Puma             | 2        | 0.12%   |
| P6               | 1        | 0.06%   |
| Bonnell          | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 774      | 44.56%  |
| AMD                        | 536      | 30.86%  |
| Intel                      | 420      | 24.18%  |
| ASPEED Technology          | 4        | 0.23%   |
| Matrox Electronics Systems | 2        | 0.12%   |
| S3 Graphics                | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 91       | 5.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 86       | 4.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 55       | 3.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 40       | 2.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 40       | 2.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 39       | 2.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 37       | 2.05%   |
| Intel HD Graphics 530                                                       | 34       | 1.89%   |
| Nvidia GT218 [GeForce 210]                                                  | 29       | 1.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 29       | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 26       | 1.44%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 26       | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 24       | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 24       | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 22       | 1.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 20       | 1.11%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 20       | 1.11%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 19       | 1.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 19       | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 19       | 1.05%   |
| Intel HD Graphics 630                                                       | 17       | 0.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 17       | 0.94%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 16       | 0.89%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 16       | 0.89%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 15       | 0.83%   |
| Nvidia GF119 [GeForce GT 610]                                               | 15       | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 15       | 0.83%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 15       | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 14       | 0.78%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 14       | 0.78%   |
| Nvidia GF108 [GeForce GT 630]                                               | 14       | 0.78%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 14       | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 13       | 0.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 13       | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 13       | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 12       | 0.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 12       | 0.67%   |
| AMD RS780L [Radeon 3000]                                                    | 11       | 0.61%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 11       | 0.61%   |
| Intel AlderLake-S GT1                                                       | 10       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 732      | 44.02%  |
| 1 x AMD         | 489      | 29.4%   |
| 1 x Intel       | 354      | 21.29%  |
| 2 x AMD         | 23       | 1.38%   |
| Intel + Nvidia  | 22       | 1.32%   |
| AMD + Nvidia    | 14       | 0.84%   |
| Intel + AMD     | 13       | 0.78%   |
| 2 x Nvidia      | 4        | 0.24%   |
| 3 x AMD         | 2        | 0.12%   |
| 2 x Intel       | 2        | 0.12%   |
| Nvidia + ASPEED | 2        | 0.12%   |
| 1 x Matrox      | 2        | 0.12%   |
| 1 x ASPEED      | 2        | 0.12%   |
| Other           | 1        | 0.06%   |
| 1 x S3 Graphics | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1197     | 71.04%  |
| Proprietary | 411      | 24.39%  |
| Unknown     | 77       | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 586      | 33.95%  |
| 1.01-2.0   | 250      | 14.48%  |
| 0.51-1.0   | 241      | 13.96%  |
| 0.01-0.5   | 232      | 13.44%  |
| 7.01-8.0   | 160      | 9.27%   |
| 3.01-4.0   | 137      | 7.94%   |
| 5.01-6.0   | 70       | 4.06%   |
| 8.01-16.0  | 35       | 2.03%   |
| 2.01-3.0   | 12       | 0.7%    |
| 16.01-24.0 | 3        | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 300      | 17.17%  |
| Goldstar             | 205      | 11.73%  |
| Dell                 | 172      | 9.85%   |
| Philips              | 121      | 6.93%   |
| Iiyama               | 107      | 6.12%   |
| Hewlett-Packard      | 97       | 5.55%   |
| BenQ                 | 93       | 5.32%   |
| Acer                 | 92       | 5.27%   |
| AOC                  | 75       | 4.29%   |
| Eizo                 | 60       | 3.43%   |
| NEC Computers        | 54       | 3.09%   |
| Ancor Communications | 47       | 2.69%   |
| LG Electronics       | 31       | 1.77%   |
| Fujitsu Siemens      | 27       | 1.55%   |
| Sony                 | 25       | 1.43%   |
| Lenovo               | 23       | 1.32%   |
| Unknown              | 15       | 0.86%   |
| Idek Iiyama          | 14       | 0.8%    |
| ASUSTek Computer     | 13       | 0.74%   |
| ViewSonic            | 10       | 0.57%   |
| Gateway              | 10       | 0.57%   |
| Belinea              | 10       | 0.57%   |
| Toshiba              | 9        | 0.52%   |
| Panasonic            | 8        | 0.46%   |
| MSI                  | 8        | 0.46%   |
| Medion               | 7        | 0.4%    |
| Hyundai ImageQuest   | 7        | 0.4%    |
| Gigabyte Technology  | 6        | 0.34%   |
| IBM                  | 5        | 0.29%   |
| Arnos Instruments    | 5        | 0.29%   |
| Unknown              | 5        | 0.29%   |
| Vestel Elektronik    | 4        | 0.23%   |
| RTK                  | 4        | 0.23%   |
| Hitachi              | 4        | 0.23%   |
| Xiaomi               | 3        | 0.17%   |
| Vestel               | 3        | 0.17%   |
| TCL                  | 3        | 0.17%   |
| Sharp                | 3        | 0.17%   |
| Onkyo                | 3        | 0.17%   |
| Valve                | 2        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                  | 14       | 0.74%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 12       | 0.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 11       | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 10       | 0.53%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 9        | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 8        | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 8        | 0.42%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 8        | 0.42%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 8        | 0.42%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 7        | 0.37%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 7        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 7        | 0.37%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 7        | 0.37%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 6        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 6        | 0.32%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 6        | 0.32%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch           | 6        | 0.32%   |
| Eizo EV2316W ENC2394 1920x1080 510x287mm 23.0-inch                     | 6        | 0.32%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                      | 6        | 0.32%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch                | 5        | 0.27%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 5        | 0.27%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                   | 5        | 0.27%   |
| Dell U2212HM DELD047 1920x1080 475x267mm 21.5-inch                     | 5        | 0.27%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 5        | 0.27%   |
| Unknown                                                                | 5        | 0.27%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4        | 0.21%   |
| Toshiba TV TSB0108 1920x540                                            | 4        | 0.21%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch      | 4        | 0.21%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 4        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 4        | 0.21%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 4        | 0.21%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 4        | 0.21%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch           | 4        | 0.21%   |
| NEC Computers EA244WMi NEC68D5 1920x1200 519x324mm 24.1-inch           | 4        | 0.21%   |
| NEC Computers EA223WM NEC6890 1680x1050 474x296mm 22.0-inch            | 4        | 0.21%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 4        | 0.21%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                   | 4        | 0.21%   |
| Iiyama PL2440HS IVM615E 1920x1080 527x296mm 23.8-inch                  | 4        | 0.21%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                    | 4        | 0.21%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch           | 4        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 772      | 45.15%  |
| 1280x1024 (SXGA)   | 189      | 11.05%  |
| 1680x1050 (WSXGA+) | 117      | 6.84%   |
| 2560x1440 (QHD)    | 109      | 6.37%   |
| 3840x2160 (4K)     | 108      | 6.32%   |
| 1920x1200 (WUXGA)  | 87       | 5.09%   |
| 1440x900 (WXGA+)   | 70       | 4.09%   |
| Unknown            | 37       | 2.16%   |
| 1366x768 (WXGA)    | 34       | 1.99%   |
| 3440x1440          | 27       | 1.58%   |
| 2560x1080          | 27       | 1.58%   |
| 1360x768           | 18       | 1.05%   |
| 1600x1200          | 17       | 0.99%   |
| 1024x768 (XGA)     | 14       | 0.82%   |
| 3840x1080          | 12       | 0.7%    |
| 1600x900 (HD+)     | 10       | 0.58%   |
| 1920x540           | 9        | 0.53%   |
| 1280x720 (HD)      | 5        | 0.29%   |
| 2048x1152          | 4        | 0.23%   |
| 5120x1440          | 3        | 0.18%   |
| 3200x1080          | 3        | 0.18%   |
| 2560x1600          | 3        | 0.18%   |
| 1280x960           | 3        | 0.18%   |
| 5760x1080          | 2        | 0.12%   |
| 4480x1440          | 2        | 0.12%   |
| 3840x1200          | 2        | 0.12%   |
| 3600x1080          | 2        | 0.12%   |
| 2288x1287          | 2        | 0.12%   |
| 7280x1440          | 1        | 0.06%   |
| 720x576            | 1        | 0.06%   |
| 720x480            | 1        | 0.06%   |
| 6880x1440          | 1        | 0.06%   |
| 6400x1440          | 1        | 0.06%   |
| 5760x1200          | 1        | 0.06%   |
| 5120x2160          | 1        | 0.06%   |
| 5120x1080          | 1        | 0.06%   |
| 5040x1050          | 1        | 0.06%   |
| 4920x1200          | 1        | 0.06%   |
| 4480x1600          | 1        | 0.06%   |
| 4480x1200          | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 248      | 14.26%  |
| 21      | 222      | 12.77%  |
| 23      | 221      | 12.71%  |
| Unknown | 191      | 10.98%  |
| 27      | 189      | 10.87%  |
| 19      | 146      | 8.4%    |
| 17      | 87       | 5%      |
| 22      | 77       | 4.43%   |
| 18      | 52       | 2.99%   |
| 34      | 45       | 2.59%   |
| 31      | 39       | 2.24%   |
| 20      | 34       | 1.96%   |
| 72      | 19       | 1.09%   |
| 84      | 18       | 1.04%   |
| 15      | 18       | 1.04%   |
| 32      | 17       | 0.98%   |
| 25      | 17       | 0.98%   |
| 40      | 15       | 0.86%   |
| 54      | 14       | 0.81%   |
| 33      | 8        | 0.46%   |
| 65      | 7        | 0.4%    |
| 42      | 6        | 0.35%   |
| 46      | 5        | 0.29%   |
| 28      | 5        | 0.29%   |
| 39      | 4        | 0.23%   |
| 26      | 4        | 0.23%   |
| 14      | 4        | 0.23%   |
| 55      | 3        | 0.17%   |
| 49      | 3        | 0.17%   |
| 48      | 3        | 0.17%   |
| 142     | 2        | 0.12%   |
| 50      | 2        | 0.12%   |
| 43      | 2        | 0.12%   |
| 37      | 2        | 0.12%   |
| 35      | 2        | 0.12%   |
| 29      | 2        | 0.12%   |
| 59      | 1        | 0.06%   |
| 57      | 1        | 0.06%   |
| 52      | 1        | 0.06%   |
| 47      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 630      | 37.23%  |
| 401-500        | 427      | 25.24%  |
| Unknown        | 191      | 11.29%  |
| 301-350        | 103      | 6.09%   |
| 351-400        | 99       | 5.85%   |
| 701-800        | 71       | 4.2%    |
| 601-700        | 57       | 3.37%   |
| 1001-1500      | 39       | 2.3%    |
| 1501-2000      | 37       | 2.19%   |
| 801-900        | 24       | 1.42%   |
| 901-1000       | 8        | 0.47%   |
| 201-300        | 4        | 0.24%   |
| More than 2000 | 2        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 912      | 55.95%  |
| 16/10   | 259      | 15.89%  |
| 5/4     | 174      | 10.67%  |
| Unknown | 173      | 10.61%  |
| 21/9    | 49       | 3.01%   |
| 4/3     | 34       | 2.09%   |
| 3/2     | 16       | 0.98%   |
| 32/9    | 6        | 0.37%   |
| 6/5     | 4        | 0.25%   |
| 1.00    | 2        | 0.12%   |
| 0.56    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 595      | 34.71%  |
| 151-200        | 244      | 14.24%  |
| 301-350        | 191      | 11.14%  |
| Unknown        | 191      | 11.14%  |
| 251-300        | 124      | 7.23%   |
| 141-150        | 120      | 7%      |
| 351-500        | 116      | 6.77%   |
| More than 1000 | 71       | 4.14%   |
| 501-1000       | 39       | 2.28%   |
| 101-110        | 14       | 0.82%   |
| 111-120        | 4        | 0.23%   |
| 91-100         | 3        | 0.18%   |
| 81-90          | 1        | 0.06%   |
| 71-80          | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1005     | 61.81%  |
| 101-120 | 311      | 19.13%  |
| Unknown | 191      | 11.75%  |
| 1-50    | 60       | 3.69%   |
| 121-160 | 39       | 2.4%    |
| 161-240 | 20       | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1326     | 79.4%   |
| 2     | 227      | 13.59%  |
| 0     | 79       | 4.73%   |
| 3     | 32       | 1.92%   |
| 4     | 6        | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 997      | 42.59%  |
| Intel                                  | 571      | 24.39%  |
| Qualcomm Atheros                       | 173      | 7.39%   |
| Broadcom                               | 76       | 3.25%   |
| TP-Link                                | 74       | 3.16%   |
| Ralink Technology                      | 52       | 2.22%   |
| Nvidia                                 | 50       | 2.14%   |
| Qualcomm Atheros Communications        | 38       | 1.62%   |
| Ralink                                 | 34       | 1.45%   |
| Huawei Technologies                    | 28       | 1.2%    |
| Microsoft                              | 27       | 1.15%   |
| Marvell Technology Group               | 25       | 1.07%   |
| Broadcom Limited                       | 19       | 0.81%   |
| ASUSTek Computer                       | 19       | 0.81%   |
| Xiaomi                                 | 18       | 0.77%   |
| Samsung Electronics                    | 16       | 0.68%   |
| MediaTek                               | 16       | 0.68%   |
| Aquantia                               | 10       | 0.43%   |
| Edimax Technology                      | 9        | 0.38%   |
| D-Link                                 | 9        | 0.38%   |
| VIA Technologies                       | 6        | 0.26%   |
| Motorola PCS                           | 6        | 0.26%   |
| Sony Ericsson Mobile Communications AB | 5        | 0.21%   |
| NetGear                                | 4        | 0.17%   |
| D-Link System                          | 4        | 0.17%   |
| Sagem                                  | 3        | 0.13%   |
| HTC (High Tech Computer)               | 3        | 0.13%   |
| ZyXEL Communications                   | 2        | 0.09%   |
| ZyDAS                                  | 2        | 0.09%   |
| Texas Instruments                      | 2        | 0.09%   |
| Research In Motion                     | 2        | 0.09%   |
| QLogic                                 | 2        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.09%   |
| Loupedeck                              | 2        | 0.09%   |
| Belkin Components                      | 2        | 0.09%   |
| Apple                                  | 2        | 0.09%   |
| 3Com                                   | 2        | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| Z-Com                                  | 1        | 0.04%   |
| Wacom                                  | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 811      | 31.74%  |
| Intel I211 Gigabit Network Connection                             | 75       | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 71       | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 2.31%   |
| Intel Wi-Fi 6 AX200                                               | 55       | 2.15%   |
| Intel Ethernet Connection (2) I219-V                              | 55       | 2.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38       | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 35       | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33       | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 33       | 1.29%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.17%   |
| Intel Ethernet Connection (7) I219-V                              | 30       | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 29       | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                   | 28       | 1.1%    |
| Ralink MT7601U Wireless Adapter                                   | 23       | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 22       | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.82%   |
| Intel Wireless-AC 9260                                            | 20       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 20       | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19       | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                               | 18       | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 16       | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 15       | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 15       | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 14       | 0.55%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 14       | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 13       | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13       | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13       | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 155      | 22.08%  |
| Realtek Semiconductor           | 140      | 19.94%  |
| Qualcomm Atheros                | 84       | 11.97%  |
| TP-Link                         | 73       | 10.4%   |
| Ralink Technology               | 52       | 7.41%   |
| Qualcomm Atheros Communications | 38       | 5.41%   |
| Ralink                          | 34       | 4.84%   |
| Microsoft                       | 27       | 3.85%   |
| Broadcom                        | 22       | 3.13%   |
| ASUSTek Computer                | 19       | 2.71%   |
| MediaTek                        | 15       | 2.14%   |
| Edimax Technology               | 9        | 1.28%   |
| D-Link                          | 9        | 1.28%   |
| NetGear                         | 4        | 0.57%   |
| Sagem                           | 3        | 0.43%   |
| D-Link System                   | 3        | 0.43%   |
| ZyXEL Communications            | 2        | 0.28%   |
| ZyDAS                           | 2        | 0.28%   |
| Broadcom Limited                | 2        | 0.28%   |
| Belkin Components               | 2        | 0.28%   |
| Z-Com                           | 1        | 0.14%   |
| Wacom                           | 1        | 0.14%   |
| Marvell Technology Group        | 1        | 0.14%   |
| Linksys                         | 1        | 0.14%   |
| IMC Networks                    | 1        | 0.14%   |
| AVM                             | 1        | 0.14%   |
| Accton Technology               | 1        | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 55       | 7.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 33       | 4.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 29       | 4.1%    |
| Qualcomm Atheros AR9271 802.11n                                               | 28       | 3.95%   |
| Ralink MT7601U Wireless Adapter                                               | 23       | 3.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 21       | 2.97%   |
| Intel Wireless-AC 9260                                                        | 20       | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 20       | 2.82%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 18       | 2.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 15       | 2.12%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 15       | 2.12%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 14       | 1.98%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 14       | 1.98%   |
| Ralink RT5370 Wireless Adapter                                                | 13       | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 13       | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 13       | 1.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 10       | 1.41%   |
| Intel Wireless 7260                                                           | 9        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 9        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 8        | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 8        | 1.13%   |
| Realtek 802.11ac NIC                                                          | 8        | 1.13%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 8        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8        | 1.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 8        | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 7        | 0.99%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 7        | 0.99%   |
| Microsoft XBOX ACC                                                            | 7        | 0.99%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 7        | 0.99%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 6        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 6        | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6        | 0.85%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 6        | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 6        | 0.85%   |
| Intel Wireless 8260                                                           | 6        | 0.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 6        | 0.85%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 6        | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 5        | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 5        | 0.71%   |
| TP-Link 802.11ac NIC                                                          | 5        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 933      | 52.68%  |
| Intel                                  | 495      | 27.95%  |
| Qualcomm Atheros                       | 94       | 5.31%   |
| Broadcom                               | 54       | 3.05%   |
| Nvidia                                 | 50       | 2.82%   |
| Marvell Technology Group               | 25       | 1.41%   |
| Xiaomi                                 | 18       | 1.02%   |
| Broadcom Limited                       | 17       | 0.96%   |
| Samsung Electronics                    | 16       | 0.9%    |
| Huawei Technologies                    | 16       | 0.9%    |
| Aquantia                               | 10       | 0.56%   |
| VIA Technologies                       | 6        | 0.34%   |
| Motorola PCS                           | 5        | 0.28%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.23%   |
| HTC (High Tech Computer)               | 3        | 0.17%   |
| TP-Link                                | 2        | 0.11%   |
| Research In Motion                     | 2        | 0.11%   |
| QLogic                                 | 2        | 0.11%   |
| Apple                                  | 2        | 0.11%   |
| 3Com                                   | 2        | 0.11%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.06%   |
| Qualcomm                               | 1        | 0.06%   |
| OPPO Electronics                       | 1        | 0.06%   |
| NetXen Incorporated                    | 1        | 0.06%   |
| Mellanox Technologies                  | 1        | 0.06%   |
| MediaTek                               | 1        | 0.06%   |
| Lenovo                                 | 1        | 0.06%   |
| ICS Advent                             | 1        | 0.06%   |
| Google                                 | 1        | 0.06%   |
| Foxconn / Hon Hai                      | 1        | 0.06%   |
| D-Link System                          | 1        | 0.06%   |
| ASIX Electronics                       | 1        | 0.06%   |
| American Megatrends                    | 1        | 0.06%   |
| AMD                                    | 1        | 0.06%   |
| ADMtek                                 | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 811      | 44.71%  |
| Intel I211 Gigabit Network Connection                             | 75       | 4.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 71       | 3.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 3.25%   |
| Intel Ethernet Connection (2) I219-V                              | 55       | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38       | 2.09%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.93%   |
| Intel 82579V Gigabit Network Connection                           | 35       | 1.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 33       | 1.82%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 30       | 1.65%   |
| Intel Ethernet Controller I225-V                                  | 22       | 1.21%   |
| Intel Ethernet Connection (2) I218-V                              | 20       | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19       | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 16       | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11       | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11       | 0.61%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.61%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 11       | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.55%   |
| Huawei E353/E3131                                                 | 10       | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.44%   |
| Nvidia MCP55 Ethernet                                             | 8        | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 7        | 0.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 0.39%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1613     | 70.31%  |
| WiFi     | 652      | 28.42%  |
| Modem    | 23       | 1%      |
| Unknown  | 6        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1289     | 77.84%  |
| WiFi     | 366      | 22.1%   |
| Unknown  | 1        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1169     | 71.11%  |
| 2     | 404      | 24.57%  |
| 3     | 48       | 2.92%   |
| 0     | 11       | 0.67%   |
| 4     | 6        | 0.36%   |
| 5     | 3        | 0.18%   |
| 17    | 1        | 0.06%   |
| 9     | 1        | 0.06%   |
| 6     | 1        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1538     | 93.84%  |
| Yes  | 101      | 6.16%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 145      | 34.94%  |
| Cambridge Silicon Radio         | 131      | 31.57%  |
| ASUSTek Computer                | 60       | 14.46%  |
| Broadcom                        | 17       | 4.1%    |
| Realtek Semiconductor           | 13       | 3.13%   |
| Qualcomm Atheros Communications | 11       | 2.65%   |
| TP-Link                         | 6        | 1.45%   |
| MediaTek                        | 5        | 1.2%    |
| Integrated System Solution      | 4        | 0.96%   |
| Edimax Technology               | 4        | 0.96%   |
| Apple                           | 4        | 0.96%   |
| IMC Networks                    | 3        | 0.72%   |
| Conwise Technology              | 3        | 0.72%   |
| Lite-On Technology              | 2        | 0.48%   |
| Foxconn / Hon Hai               | 2        | 0.48%   |
| SINO WEALTH                     | 1        | 0.24%   |
| Realtek                         | 1        | 0.24%   |
| Logitech                        | 1        | 0.24%   |
| Belkin Components               | 1        | 0.24%   |
| Unknown                         | 1        | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 131      | 31.49%  |
| Intel AX200 Bluetooth                                 | 54       | 12.98%  |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 44       | 10.58%  |
| Intel Bluetooth wireless interface                    | 20       | 4.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 19       | 4.57%   |
| Intel Wireless-AC 3168 Bluetooth                      | 19       | 4.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 14       | 3.37%   |
| Realtek Bluetooth Radio                               | 12       | 2.88%   |
| Intel AX210 Bluetooth                                 | 9        | 2.16%   |
| Intel AX201 Bluetooth                                 | 9        | 2.16%   |
| ASUS ASUS USB-BT500                                   | 8        | 1.92%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 7        | 1.68%   |
| TP-Link UB500 Adapter                                 | 6        | 1.44%   |
| MediaTek Wireless_Device                              | 5        | 1.2%    |
| Broadcom HP Portable Bumble Bee                       | 4        | 0.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.96%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.72%   |
| Conwise CW6622                                        | 3        | 0.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 3        | 0.72%   |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.72%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.72%   |
| IMC Networks Wireless_Device                          | 2        | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 0.48%   |
| Edimax Bluetooth Adapter                              | 2        | 0.48%   |
| ASUS BCM20702A0                                       | 2        | 0.48%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.24%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.24%   |
| Realtek Bluetooth Radio                               | 1        | 0.24%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.24%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.24%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1        | 0.24%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.24%   |
| Lite-On Bluetooth Radio                               | 1        | 0.24%   |
| Lite-On Bluetooth Device                              | 1        | 0.24%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.24%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1        | 0.24%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.24%   |
| IMC Networks Bluetooth Radio                          | 1        | 0.24%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter           | 1        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 949      | 34.41%  |
| AMD                                  | 735      | 26.65%  |
| Nvidia                               | 683      | 24.76%  |
| Creative Labs                        | 80       | 2.9%    |
| C-Media Electronics                  | 65       | 2.36%   |
| Creative Technology                  | 27       | 0.98%   |
| VIA Technologies                     | 15       | 0.54%   |
| JMTek                                | 15       | 0.54%   |
| Texas Instruments                    | 13       | 0.47%   |
| Logitech                             | 13       | 0.47%   |
| Kingston Technology                  | 11       | 0.4%    |
| GYROCOM C&C                          | 10       | 0.36%   |
| SteelSeries ApS                      | 8        | 0.29%   |
| Realtek Semiconductor                | 7        | 0.25%   |
| SAVITECH                             | 6        | 0.22%   |
| Plantronics                          | 6        | 0.22%   |
| Generalplus Technology               | 6        | 0.22%   |
| Dell                                 | 6        | 0.22%   |
| ASUSTek Computer                     | 6        | 0.22%   |
| Razer USA                            | 5        | 0.18%   |
| Valve Software                       | 4        | 0.15%   |
| Sony                                 | 4        | 0.15%   |
| BEHRINGER International              | 4        | 0.15%   |
| RODE Microphones                     | 3        | 0.11%   |
| PreSonus Audio Electronics           | 3        | 0.11%   |
| M-Audio                              | 3        | 0.11%   |
| Focusrite-Novation                   | 3        | 0.11%   |
| Corsair                              | 3        | 0.11%   |
| AudioQuest                           | 3        | 0.11%   |
| AOKEO                                | 3        | 0.11%   |
| XMOS                                 | 2        | 0.07%   |
| USB MICROPHONE                       | 2        | 0.07%   |
| ULi Electronics                      | 2        | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.07%   |
| SM900T Microphone                    | 2        | 0.07%   |
| SM900 Microphone                     | 2        | 0.07%   |
| Samson Technologies                  | 2        | 0.07%   |
| ROCCAT                               | 2        | 0.07%   |
| GN Netcom                            | 2        | 0.07%   |
| Giga-Byte Technology                 | 2        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 150      | 4.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 141      | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 124      | 3.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 117      | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 99       | 3.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 98       | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 95       | 2.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 92       | 2.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 87       | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 86       | 2.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 66       | 2.07%   |
| AMD FCH Azalia Controller                                                  | 64       | 2%      |
| Intel 200 Series PCH HD Audio                                              | 62       | 1.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 62       | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 62       | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 54       | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 54       | 1.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 48       | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 46       | 1.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 42       | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 40       | 1.25%   |
| Nvidia High Definition Audio Controller                                    | 39       | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 39       | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 38       | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 37       | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                         | 35       | 1.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 34       | 1.06%   |
| Nvidia MCP61 High Definition Audio                                         | 33       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33       | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 31       | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29       | 0.91%   |
| AMD Navi 10 HDMI Audio                                                     | 29       | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 29       | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                              | 28       | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26       | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                         | 23       | 0.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 22       | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 21       | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                              | 21       | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                              | 20       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 230      | 20.43%  |
| Kingston                     | 210      | 18.65%  |
| Samsung Electronics          | 96       | 8.53%   |
| GOODRAM                      | 95       | 8.44%   |
| SK hynix                     | 87       | 7.73%   |
| G.Skill                      | 86       | 7.64%   |
| Corsair                      | 69       | 6.13%   |
| Crucial                      | 63       | 5.6%    |
| Patriot                      | 33       | 2.93%   |
| Micron Technology            | 26       | 2.31%   |
| A-DATA Technology            | 26       | 2.31%   |
| Nanya Technology             | 15       | 1.33%   |
| Elpida                       | 12       | 1.07%   |
| Unknown                      | 10       | 0.89%   |
| Wilk Elektronik              | 9        | 0.8%    |
| GeIL                         | 9        | 0.8%    |
| Apacer                       | 8        | 0.71%   |
| Wilk                         | 7        | 0.62%   |
| Ramaxel Technology           | 4        | 0.36%   |
| Unknown (ABCD)               | 3        | 0.27%   |
| Silicon Power                | 3        | 0.27%   |
| Qimonda                      | 3        | 0.27%   |
| OCZ                          | 3        | 0.27%   |
| Patriot Memory (PDP Systems) | 2        | 0.18%   |
| ASint Technology             | 2        | 0.18%   |
| AMD                          | 2        | 0.18%   |
| Unknown (0x7FFF)             | 1        | 0.09%   |
| Unifosa                      | 1        | 0.09%   |
| Transcend                    | 1        | 0.09%   |
| tigo                         | 1        | 0.09%   |
| Team                         | 1        | 0.09%   |
| PNY                          | 1        | 0.09%   |
| Lexar                        | 1        | 0.09%   |
| Kingmax                      | 1        | 0.09%   |
| KingFast                     | 1        | 0.09%   |
| ISD Technology Limited       | 1        | 0.09%   |
| Golden Empire                | 1        | 0.09%   |
| Aeneon                       | 1        | 0.09%   |
| 48spaces                     | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s  | 19       | 1.48%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 18       | 1.41%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s    | 16       | 1.25%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 13       | 1.02%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 12       | 0.94%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 12       | 0.94%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s     | 12       | 0.94%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 12       | 0.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 12       | 0.94%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 11       | 0.86%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 11       | 0.86%   |
| GOODRAM RAM GR1600D364L11/8G 8GB DIMM DDR3 1600MT/s    | 10       | 0.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 10       | 0.78%   |
| Unknown                                                | 10       | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9        | 0.7%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 8        | 0.63%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s    | 8        | 0.63%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 7        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 7        | 0.55%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 7        | 0.55%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 7        | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 7        | 0.55%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 7        | 0.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 7        | 0.55%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 7        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 6        | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 6        | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 6        | 0.47%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 6        | 0.47%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 6        | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 6        | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 6        | 0.47%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3266MT/s  | 6        | 0.47%   |
| GOODRAM RAM IR2400D464L15S/4G 4GB DIMM DDR4 2866MT/s   | 6        | 0.47%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s  | 6        | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 5        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 5        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s             | 5        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 5        | 0.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 5        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 399      | 39.74%  |
| DDR3    | 328      | 32.67%  |
| Unknown | 122      | 12.15%  |
| DDR2    | 69       | 6.87%   |
| SDRAM   | 54       | 5.38%   |
| DDR     | 21       | 2.09%   |
| DDR5    | 7        | 0.7%    |
| LPDDR4  | 3        | 0.3%    |
| DRAM    | 1        | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 943      | 95.83%  |
| SODIMM  | 38       | 3.86%   |
| RIMM    | 2        | 0.2%    |
| FB-DIMM | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 343      | 30.82%  |
| 4096  | 257      | 23.09%  |
| 2048  | 223      | 20.04%  |
| 16384 | 128      | 11.5%   |
| 1024  | 85       | 7.64%   |
| 32768 | 57       | 5.12%   |
| 512   | 17       | 1.53%   |
| 1536  | 1        | 0.09%   |
| 256   | 1        | 0.09%   |
| 64    | 1        | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 202      | 18.18%  |
| 1333    | 126      | 11.34%  |
| 3200    | 94       | 8.46%   |
| 800     | 85       | 7.65%   |
| 3600    | 70       | 6.3%    |
| 2400    | 59       | 5.31%   |
| 667     | 47       | 4.23%   |
| 2667    | 45       | 4.05%   |
| 2133    | 36       | 3.24%   |
| 3000    | 26       | 2.34%   |
| 3266    | 24       | 2.16%   |
| Unknown | 23       | 2.07%   |
| 3400    | 20       | 1.8%    |
| 1867    | 19       | 1.71%   |
| 3466    | 16       | 1.44%   |
| 1866    | 16       | 1.44%   |
| 3866    | 15       | 1.35%   |
| 1067    | 15       | 1.35%   |
| 2933    | 14       | 1.26%   |
| 1066    | 14       | 1.26%   |
| 400     | 14       | 1.26%   |
| 1800    | 13       | 1.17%   |
| 3733    | 9        | 0.81%   |
| 2666    | 9        | 0.81%   |
| 533     | 9        | 0.81%   |
| 3800    | 8        | 0.72%   |
| 1334    | 8        | 0.72%   |
| 2866    | 7        | 0.63%   |
| 333     | 6        | 0.54%   |
| 49926   | 5        | 0.45%   |
| 4800    | 5        | 0.45%   |
| 2800    | 5        | 0.45%   |
| 2000    | 4        | 0.36%   |
| 1648    | 4        | 0.36%   |
| 3333    | 3        | 0.27%   |
| 1332    | 3        | 0.27%   |
| 4400    | 2        | 0.18%   |
| 4000    | 2        | 0.18%   |
| 3334    | 2        | 0.18%   |
| 3066    | 2        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 36       | 46.15%  |
| Brother Industries    | 11       | 14.1%   |
| Samsung Electronics   | 10       | 12.82%  |
| Canon                 | 6        | 7.69%   |
| Prolific Technology   | 5        | 6.41%   |
| Seiko Epson           | 4        | 5.13%   |
| Zebra                 | 2        | 2.56%   |
| Lexmark International | 2        | 2.56%   |
| Xerox                 | 1        | 1.28%   |
| Datamax-O'Neil        | 1        | 1.28%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port          | 5        | 6.25%   |
| HP LaserJet P2015 series               | 3        | 3.75%   |
| HP LaserJet 1020                       | 3        | 3.75%   |
| Canon iP7200 series                    | 3        | 3.75%   |
| Samsung ML-216x Series Laser Printer   | 2        | 2.5%    |
| Samsung ML-2010P Mono Laser Printer    | 2        | 2.5%    |
| HP LaserJet M14-M17                    | 2        | 2.5%    |
| HP Deskjet F4500 series                | 2        | 2.5%    |
| HP DeskJet F4100 Printer series        | 2        | 2.5%    |
| HP DeskJet 845c                        | 2        | 2.5%    |
| HP DeskJet 840c                        | 2        | 2.5%    |
| HP DeskJet 3700 series                 | 2        | 2.5%    |
| HP Deskjet 1050 J410                   | 2        | 2.5%    |
| Brother DCP-J105                       | 2        | 2.5%    |
| Zebra LP2844 Printer                   | 1        | 1.25%   |
| Zebra LP2824                           | 1        | 1.25%   |
| Xerox WorkCentre PE16                  | 1        | 1.25%   |
| Seiko Epson Stylus NX230/SX235W Series | 1        | 1.25%   |
| Seiko Epson L405 Series                | 1        | 1.25%   |
| Seiko Epson L1110 Series               | 1        | 1.25%   |
| Seiko Epson ET-2710 Series             | 1        | 1.25%   |
| Samsung SCX-4300 Series                | 1        | 1.25%   |
| Samsung SCX-4200 series                | 1        | 1.25%   |
| Samsung SCX-3400 Series                | 1        | 1.25%   |
| Samsung ML-3050/ML-3051 Laser Printer  | 1        | 1.25%   |
| Samsung ML-2540 Series Laser Printer   | 1        | 1.25%   |
| Samsung M2020 Series                   | 1        | 1.25%   |
| Lexmark International MS415dn          | 1        | 1.25%   |
| Lexmark International Lexmark E352dn   | 1        | 1.25%   |
| HP Smart Tank 510 series               | 1        | 1.25%   |
| HP PSC 1100 series                     | 1        | 1.25%   |
| HP Printing Support                    | 1        | 1.25%   |
| HP LaserJet P1102                      | 1        | 1.25%   |
| HP LaserJet M101-M106                  | 1        | 1.25%   |
| HP LaserJet CM1415fn                   | 1        | 1.25%   |
| HP LaserJet 3030                       | 1        | 1.25%   |
| HP LaserJet 1320                       | 1        | 1.25%   |
| HP LaserJet 1022                       | 1        | 1.25%   |
| HP DeskJet 4530 series                 | 1        | 1.25%   |
| HP DeskJet 2600 series                 | 1        | 1.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 8        | 61.54%  |
| Seiko Epson                 | 2        | 15.38%  |
| Ultima Electronics          | 1        | 7.69%   |
| Plustek                     | 1        | 7.69%   |
| Acer Peripherals (now BenQ) | 1        | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 3        | 23.08%  |
| Canon CanoScan LiDE 120                                  | 2        | 15.38%  |
| Ultima Artec E+ 48U                                      | 1        | 7.69%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1        | 7.69%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 7.69%   |
| Plustek OpticPro 1248U Scanner #2                        | 1        | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 7.69%   |
| Canon CanoScan LIDE 25                                   | 1        | 7.69%   |
| Canon CanoScan LiDE 110                                  | 1        | 7.69%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1        | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 69       | 33.01%  |
| Creative Technology                    | 24       | 11.48%  |
| Microdia                               | 22       | 10.53%  |
| Microsoft                              | 12       | 5.74%   |
| Samsung Electronics                    | 11       | 5.26%   |
| Z-Star Microelectronics                | 8        | 3.83%   |
| Hewlett-Packard                        | 6        | 2.87%   |
| Cubeternet                             | 6        | 2.87%   |
| Aveo Technology                        | 4        | 1.91%   |
| Xiongmai                               | 3        | 1.44%   |
| Jieli Technology                       | 3        | 1.44%   |
| Generalplus Technology                 | 3        | 1.44%   |
| GEMBIRD                                | 3        | 1.44%   |
| Chicony Electronics                    | 3        | 1.44%   |
| Apple                                  | 3        | 1.44%   |
| Alcor Micro                            | 3        | 1.44%   |
| Valve Software                         | 2        | 0.96%   |
| Trust                                  | 2        | 0.96%   |
| Sunplus Innovation Technology          | 2        | 0.96%   |
| Realtek Semiconductor                  | 2        | 0.96%   |
| Razer USA                              | 2        | 0.96%   |
| Pixart Imaging                         | 2        | 0.96%   |
| LG Electronics                         | 2        | 0.96%   |
| MacroSilicon                           | 1        | 0.48%   |
| Lenovo                                 | 1        | 0.48%   |
| KYE Systems (Mouse Systems)            | 1        | 0.48%   |
| HY_JUNmeng                             | 1        | 0.48%   |
| Huawei Technologies                    | 1        | 0.48%   |
| Google                                 | 1        | 0.48%   |
| Etron Technology                       | 1        | 0.48%   |
| DigitalPersona                         | 1        | 0.48%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.48%   |
| Asuscom Network                        | 1        | 0.48%   |
| Arkmicro Technologies                  | 1        | 0.48%   |
| ARC International                      | 1        | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 18       | 8.61%   |
| Creative Live! Cam Sync HD [VF0770]               | 13       | 6.22%   |
| Logitech HD Pro Webcam C920                       | 11       | 5.26%   |
| Samsung Galaxy A5 (MTP)                           | 10       | 4.78%   |
| Microdia USB 2.0 Camera                           | 9        | 4.31%   |
| Logitech Webcam C310                              | 8        | 3.83%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 2.87%   |
| Logitech Webcam C170                              | 5        | 2.39%   |
| Microsoft LifeCam HD-3000                         | 4        | 1.91%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 1.91%   |
| HP Webcam HD 2300                                 | 4        | 1.91%   |
| Cubeternet USB2.0 Camera                          | 4        | 1.91%   |
| Creative Live! Cam Chat HD [VF0700]               | 4        | 1.91%   |
| Xiongmai web camera                               | 3        | 1.44%   |
| Microdia Webcam Vitade AF                         | 3        | 1.44%   |
| Microdia Integrated Camera                        | 3        | 1.44%   |
| Logitech Webcam C120                              | 3        | 1.44%   |
| Jieli USB PHY 2.0                                 | 3        | 1.44%   |
| Generalplus GENERAL WEBCAM                        | 3        | 1.44%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 1.44%   |
| Creative Live! Cam Optia                          | 3        | 1.44%   |
| Aveo USB2.0 Camera                                | 3        | 1.44%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 3        | 1.44%   |
| Valve Software 3D Camera                          | 2        | 0.96%   |
| Razer USA Gaming Webcam [Kiyo]                    | 2        | 0.96%   |
| Pixart Imaging USB2.0_Camera                      | 2        | 0.96%   |
| Microsoft LifeCam VX-500 [1357]                   | 2        | 0.96%   |
| Microsoft LifeCam NX-6000                         | 2        | 0.96%   |
| Microsoft LifeCam HD-5000                         | 2        | 0.96%   |
| Microdia Camera                                   | 2        | 0.96%   |
| Logitech Webcam C930e                             | 2        | 0.96%   |
| Logitech StreamCam                                | 2        | 0.96%   |
| Logitech QuickCam Pro 9000                        | 2        | 0.96%   |
| Logitech Logitech Webcam C100                     | 2        | 0.96%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 0.96%   |
| Logitech C920 PRO HD Webcam                       | 2        | 0.96%   |
| Creative Live! Cam Sync 1080p                     | 2        | 0.96%   |
| Chicony FULL HD 5MP Webcam                        | 2        | 0.96%   |
| Alcor Micro USB 2.0 PC Camera                     | 2        | 0.96%   |
| Z-Star Vimicro USB Camera (Altair)                | 1        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 1        | 25%     |
| STMicroelectronics    | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 25%     |
| STMicroelectronics Fingerprint Reader        | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 25%     |
| AuthenTec AES1600                            | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Advanced Card Systems    | 3        | 27.27%  |
| OmniKey                  | 2        | 18.18%  |
| SCM Microsystems         | 1        | 9.09%   |
| Reiner SCT Kartensysteme | 1        | 9.09%   |
| Gemalto (was Gemplus)    | 1        | 9.09%   |
| Clay Logic               | 1        | 9.09%   |
| Cherry                   | 1        | 9.09%   |
| Alcor Micro              | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                                                | 2        | 18.18%  |
| Advanced Card Systems ACR39U                                               | 2        | 18.18%  |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 9.09%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 9.09%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 9.09%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 9.09%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 9.09%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 9.09%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1429     | 85.21%  |
| 1     | 217      | 12.94%  |
| 2     | 24       | 1.43%   |
| 3     | 4        | 0.24%   |
| 4     | 2        | 0.12%   |
| 7     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 104      | 38.1%   |
| Net/wireless             | 60       | 21.98%  |
| Communication controller | 20       | 7.33%   |
| Unassigned class         | 18       | 6.59%   |
| Multimedia controller    | 13       | 4.76%   |
| Sound                    | 10       | 3.66%   |
| Camera                   | 7        | 2.56%   |
| Bluetooth                | 7        | 2.56%   |
| Network                  | 5        | 1.83%   |
| Chipcard                 | 5        | 1.83%   |
| Storage/ide              | 4        | 1.47%   |
| Net/ethernet             | 4        | 1.47%   |
| Fingerprint reader       | 4        | 1.47%   |
| Storage/raid             | 3        | 1.1%    |
| Dvb card                 | 3        | 1.1%    |
| Storage                  | 2        | 0.73%   |
| Modem                    | 2        | 0.73%   |
| Firewire controller      | 2        | 0.73%   |

