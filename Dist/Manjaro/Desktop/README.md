Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3747

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| HP            | 1495                        | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| MSI           | X570-A PRO                  | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| HP            | 212B                        | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| MSI           | B75MA-P45                   | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| HP            | 8597                        | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H                  | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [178d910ec8](https://linux-hardware.org/?probe=178d910ec8) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| ASRock        | B550M Pro4                  | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| Dell          | 0C27VV A01                  | [bf0f5c5d07](https://linux-hardware.org/?probe=bf0f5c5d07) | May 14, 2022 |
| ASRock        | X570 Taichi                 | [4d3e26ea12](https://linux-hardware.org/?probe=4d3e26ea12) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7a7065c273](https://linux-hardware.org/?probe=7a7065c273) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| ASRock        | B550M Pro4                  | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| ASRock        | B550M Pro4                  | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [326b50009b](https://linux-hardware.org/?probe=326b50009b) | May 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | [23b8b07484](https://linux-hardware.org/?probe=23b8b07484) | May 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fa341f81f](https://linux-hardware.org/?probe=3fa341f81f) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| HP            | 1905                        | [91a5807da1](https://linux-hardware.org/?probe=91a5807da1) | May 10, 2022 |
| HP            | 1905                        | [40dbe34df3](https://linux-hardware.org/?probe=40dbe34df3) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| BESSTAR Te... | UM350                       | [c5234552de](https://linux-hardware.org/?probe=c5234552de) | May 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASRock        | B550M Steel Legend          | [a384972a7a](https://linux-hardware.org/?probe=a384972a7a) | May 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Pegatron      | NARRA5                      | [bfe1e3f80d](https://linux-hardware.org/?probe=bfe1e3f80d) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | X370 Taichi                 | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASRock        | AB350 Pro4                  | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| Gigabyte      | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| ASRock        | B550AM Gaming               | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a19c88dc27](https://linux-hardware.org/?probe=a19c88dc27) | May 02, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | AB350M Pro4                 | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| Gigabyte      | B450 AORUS M                | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Dell          | 09M8Y8 A01                  | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| ASUSTek       | GRYPHON Z87                 | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| HP            | 18E4                        | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| ASRock        | B250M Performance           | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Biostar       | TB250-BTC                   | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Dell          | 0N867P A02                  | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASRock        | Z77 Extreme4                | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 1081     | 40.89%  |
| Manjaro 20.1      | 135      | 5.11%   |
| Manjaro 20.2.1    | 108      | 4.08%   |
| Manjaro 22.0.0    | 102      | 3.86%   |
| Manjaro 20.2      | 89       | 3.37%   |
| Manjaro 20.0.3    | 81       | 3.06%   |
| Manjaro 18.1.5    | 56       | 2.12%   |
| Manjaro 21.2.6    | 53       | 2%      |
| Manjaro 21.2.5    | 53       | 2%      |
| Manjaro 21.1.0    | 53       | 2%      |
| Manjaro 18.0.4    | 46       | 1.74%   |
| Manjaro 21.2.0    | 45       | 1.7%    |
| Manjaro 20.0      | 45       | 1.7%    |
| Manjaro 21.1.6    | 38       | 1.44%   |
| Manjaro 21.0.7    | 36       | 1.36%   |
| Manjaro 21.0.5    | 35       | 1.32%   |
| Manjaro 21.0      | 35       | 1.32%   |
| Manjaro 19.0.2    | 31       | 1.17%   |
| Manjaro 20.1.2    | 29       | 1.1%    |
| Manjaro 20.0.1    | 29       | 1.1%    |
| Manjaro 21.2.3    | 27       | 1.02%   |
| Manjaro 20.1.1    | 24       | 0.91%   |
| Manjaro 21.2.1    | 23       | 0.87%   |
| Manjaro 21.3.7    | 20       | 0.76%   |
| Manjaro 21.3.6    | 17       | 0.64%   |
| Manjaro 22.0.4    | 16       | 0.61%   |
| Manjaro 21.0.4    | 16       | 0.61%   |
| Manjaro 21.0.1    | 14       | 0.53%   |
| Manjaro 21.0.2    | 13       | 0.49%   |
| Manjaro 21.2rc    | 12       | 0.45%   |
| Manjaro 21.2.4    | 12       | 0.45%   |
| Manjaro 21.1.2    | 12       | 0.45%   |
| Manjaro 21.0.3    | 12       | 0.45%   |
| Manjaro 18.0.0-rc | 12       | 0.45%   |
| Manjaro 22.0      | 11       | 0.42%   |
| Manjaro 21.3.1    | 11       | 0.42%   |
| Manjaro 21.1.5    | 11       | 0.42%   |
| Manjaro 21.3.0    | 10       | 0.38%   |
| Manjaro 21.2.2    | 10       | 0.38%   |
| Manjaro 21.1.4    | 10       | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2427     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 3.91%   |
| 5.8.6-1-MANJARO   | 68       | 2.31%   |
| 5.13.19-2-MANJARO | 65       | 2.21%   |
| 5.15.28-1-MANJARO | 49       | 1.67%   |
| 5.9.11-3-MANJARO  | 47       | 1.6%    |
| 5.8.11-1-MANJARO  | 46       | 1.57%   |
| 5.10.42-1-MANJARO | 40       | 1.36%   |
| 6.1.1-1-MANJARO   | 38       | 1.29%   |
| 5.8.18-1-MANJARO  | 38       | 1.29%   |
| 6.1.12-1-MANJARO  | 32       | 1.09%   |
| 5.15.32-1-MANJARO | 32       | 1.09%   |
| 5.6.16-1-MANJARO  | 31       | 1.05%   |
| 5.15.60-1-MANJARO | 30       | 1.02%   |
| 5.10.36-2-MANJARO | 30       | 1.02%   |
| 5.7.9-1-MANJARO   | 29       | 0.99%   |
| 5.15.12-1-MANJARO | 29       | 0.99%   |
| 5.8.3-2-MANJARO   | 25       | 0.85%   |
| 5.8.16-2-MANJARO  | 25       | 0.85%   |
| 5.6.19-2-MANJARO  | 24       | 0.82%   |
| 5.6.15-1-MANJARO  | 24       | 0.82%   |
| 5.17.1-3-MANJARO  | 24       | 0.82%   |
| 5.7.0-3-MANJARO   | 23       | 0.78%   |
| 5.10.2-2-MANJARO  | 23       | 0.78%   |
| 5.6.7-1-MANJARO   | 22       | 0.75%   |
| 5.6.12-1-MANJARO  | 22       | 0.75%   |
| 5.16.14-1-MANJARO | 22       | 0.75%   |
| 5.15.2-2-MANJARO  | 22       | 0.75%   |
| 5.10.23-1-MANJARO | 22       | 0.75%   |
| 5.9.1-1-MANJARO   | 21       | 0.71%   |
| 5.11.6-1-MANJARO  | 21       | 0.71%   |
| 5.4.15-2-MANJARO  | 20       | 0.68%   |
| 5.7.17-2-MANJARO  | 19       | 0.65%   |
| 5.4.6-2-MANJARO   | 19       | 0.65%   |
| 5.10.7-3-MANJARO  | 19       | 0.65%   |
| 5.10.15-1-MANJARO | 19       | 0.65%   |
| 5.14.10-1-MANJARO | 17       | 0.58%   |
| 5.11.2-1-MANJARO  | 17       | 0.58%   |
| 5.10.53-1-MANJARO | 17       | 0.58%   |
| 5.9.3-1-MANJARO   | 16       | 0.54%   |
| 5.6.11-1-MANJARO  | 16       | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 3.91%   |
| 5.8.6   | 68       | 2.31%   |
| 5.13.19 | 65       | 2.21%   |
| 5.9.11  | 50       | 1.7%    |
| 5.15.28 | 49       | 1.67%   |
| 5.8.11  | 47       | 1.6%    |
| 5.10.42 | 40       | 1.36%   |
| 6.1.1   | 38       | 1.29%   |
| 5.8.18  | 38       | 1.29%   |
| 6.1.12  | 32       | 1.09%   |
| 5.15.32 | 32       | 1.09%   |
| 5.6.16  | 31       | 1.06%   |
| 5.15.60 | 30       | 1.02%   |
| 5.10.36 | 30       | 1.02%   |
| 5.7.9   | 29       | 0.99%   |
| 5.7.0   | 29       | 0.99%   |
| 5.17.1  | 29       | 0.99%   |
| 5.15.12 | 29       | 0.99%   |
| 5.9.1   | 28       | 0.95%   |
| 5.6.19  | 27       | 0.92%   |
| 5.8.3   | 26       | 0.88%   |
| 5.8.16  | 25       | 0.85%   |
| 5.6.15  | 24       | 0.82%   |
| 5.6.12  | 23       | 0.78%   |
| 5.15.2  | 23       | 0.78%   |
| 5.10.2  | 23       | 0.78%   |
| 5.6.7   | 22       | 0.75%   |
| 5.16.14 | 22       | 0.75%   |
| 5.10.23 | 22       | 0.75%   |
| 5.11.6  | 21       | 0.71%   |
| 5.7.17  | 20       | 0.68%   |
| 5.4.15  | 20       | 0.68%   |
| 5.10.7  | 20       | 0.68%   |
| 5.4.6   | 19       | 0.65%   |
| 5.10.15 | 19       | 0.65%   |
| 5.15.7  | 17       | 0.58%   |
| 5.14.10 | 17       | 0.58%   |
| 5.14.0  | 17       | 0.58%   |
| 5.11.2  | 17       | 0.58%   |
| 5.10.53 | 17       | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 426      | 15.5%   |
| 5.10    | 358      | 13.02%  |
| 5.4     | 253      | 9.2%    |
| 5.9     | 229      | 8.33%   |
| 5.8     | 228      | 8.29%   |
| 5.6     | 172      | 6.26%   |
| 5.13    | 125      | 4.55%   |
| 6.1     | 120      | 4.37%   |
| 5.7     | 109      | 3.97%   |
| 5.11    | 91       | 3.31%   |
| 4.19    | 66       | 2.4%    |
| 5.17    | 64       | 2.33%   |
| 5.16    | 64       | 2.33%   |
| 5.14    | 61       | 2.22%   |
| 6.0     | 60       | 2.18%   |
| 5.18    | 55       | 2%      |
| 5.19    | 53       | 1.93%   |
| 5.12    | 49       | 1.78%   |
| 5.5     | 39       | 1.42%   |
| 4.14    | 33       | 1.2%    |
| 5.3     | 23       | 0.84%   |
| 5.2     | 17       | 0.62%   |
| 5.1     | 13       | 0.47%   |
| 5.0     | 11       | 0.4%    |
| 6.2     | 8        | 0.29%   |
| 4.20    | 5        | 0.18%   |
| 4.18    | 5        | 0.18%   |
| 4.17    | 3        | 0.11%   |
| 4.16    | 3        | 0.11%   |
| 4.9     | 2        | 0.07%   |
| 4.7     | 2        | 0.07%   |
| 4.4     | 2        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2427     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 927      | 36.44%  |
| XFCE                     | 553      | 21.74%  |
| GNOME                    | 486      | 19.1%   |
| KDE                      | 247      | 9.71%   |
| Unknown                  | 103      | 4.05%   |
| X-Cinnamon               | 79       | 3.11%   |
| i3                       | 44       | 1.73%   |
| MATE                     | 22       | 0.86%   |
| Cinnamon                 | 22       | 0.86%   |
| Deepin                   | 21       | 0.83%   |
| Budgie                   | 13       | 0.51%   |
| LXQt                     | 7        | 0.28%   |
| awesome                  | 4        | 0.16%   |
| sway                     | 3        | 0.12%   |
| bspwm                    | 3        | 0.12%   |
| ICEWM                    | 2        | 0.08%   |
| GNOME Classic            | 2        | 0.08%   |
| Yaru:ubuntu:GNOME        | 1        | 0.04%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2219     | 89.77%  |
| Wayland | 189      | 7.65%   |
| Unknown | 39       | 1.58%   |
| Tty     | 25       | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1076     | 42.94%  |
| SDDM    | 629      | 25.1%   |
| LightDM | 423      | 16.88%  |
| GDM     | 278      | 11.09%  |
| TDM     | 89       | 3.55%   |
| LXDM    | 5        | 0.2%    |
| SLiM    | 2        | 0.08%   |
| GREETD  | 2        | 0.08%   |
| XDM     | 1        | 0.04%   |
| LYNDE   | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 974      | 39.47%  |
| de_DE   | 213      | 8.63%   |
| ru_RU   | 191      | 7.74%   |
| Unknown | 154      | 6.24%   |
| en_GB   | 153      | 6.2%    |
| pt_BR   | 104      | 4.21%   |
| fr_FR   | 65       | 2.63%   |
| en_CA   | 65       | 2.63%   |
| es_ES   | 61       | 2.47%   |
| it_IT   | 54       | 2.19%   |
| pl_PL   | 47       | 1.9%    |
| en_AU   | 35       | 1.42%   |
| nl_NL   | 20       | 0.81%   |
| de_AT   | 20       | 0.81%   |
| en_IN   | 19       | 0.77%   |
| ru_UA   | 18       | 0.73%   |
| sv_SE   | 15       | 0.61%   |
| es_AR   | 15       | 0.61%   |
| zh_CN   | 14       | 0.57%   |
| es_MX   | 13       | 0.53%   |
| fi_FI   | 12       | 0.49%   |
| en_IE   | 11       | 0.45%   |
| fr_CA   | 10       | 0.41%   |
| hu_HU   | 9        | 0.36%   |
| en_ZA   | 9        | 0.36%   |
| en_PH   | 9        | 0.36%   |
| da_DK   | 9        | 0.36%   |
| en_NZ   | 8        | 0.32%   |
| cs_CZ   | 8        | 0.32%   |
| pt_PT   | 7        | 0.28%   |
| es_CL   | 7        | 0.28%   |
| uk_UA   | 6        | 0.24%   |
| en_IL   | 6        | 0.24%   |
| en_DK   | 6        | 0.24%   |
| ja_JP   | 5        | 0.2%    |
| fr_BE   | 5        | 0.2%    |
| tr_TR   | 4        | 0.16%   |
| nb_NO   | 4        | 0.16%   |
| es_UY   | 4        | 0.16%   |
| es_PE   | 4        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1546     | 62.29%  |
| EFI  | 936      | 37.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2073     | 84%     |
| Btrfs   | 246      | 9.97%   |
| Unknown | 40       | 1.62%   |
| Xfs     | 39       | 1.58%   |
| Overlay | 37       | 1.5%    |
| F2fs    | 12       | 0.49%   |
| Tmpfs   | 10       | 0.41%   |
| Zfs     | 4        | 0.16%   |
| Ext2    | 3        | 0.12%   |
| Ext3    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1177     | 47.23%  |
| GPT     | 1049     | 42.09%  |
| MBR     | 266      | 10.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2050     | 82.63%  |
| Yes       | 431      | 17.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1544     | 62.26%  |
| Yes       | 936      | 37.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 723      | 29.79%  |
| Gigabyte Technology                  | 498      | 20.52%  |
| MSI                                  | 388      | 15.99%  |
| ASRock                               | 270      | 11.12%  |
| Dell                                 | 126      | 5.19%   |
| Hewlett-Packard                      | 112      | 4.61%   |
| Intel                                | 58       | 2.39%   |
| Lenovo                               | 49       | 2.02%   |
| Acer                                 | 27       | 1.11%   |
| Biostar                              | 20       | 0.82%   |
| Unknown                              | 19       | 0.78%   |
| Pegatron                             | 15       | 0.62%   |
| Huanan                               | 13       | 0.54%   |
| Foxconn                              | 10       | 0.41%   |
| Medion                               | 8        | 0.33%   |
| Apple                                | 8        | 0.33%   |
| Fujitsu                              | 7        | 0.29%   |
| ECS                                  | 7        | 0.29%   |
| BESSTAR Tech                         | 5        | 0.21%   |
| Shuttle                              | 4        | 0.16%   |
| Positivo                             | 4        | 0.16%   |
| AZW                                  | 4        | 0.16%   |
| Alienware                            | 4        | 0.16%   |
| PCWare                               | 3        | 0.12%   |
| ZOTAC                                | 2        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| OEM                                  | 2        | 0.08%   |
| Minix                                | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| Inventec                             | 2        | 0.08%   |
| Google                               | 2        | 0.08%   |
| Fujitsu Siemens                      | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |
| Samsung Electronics                  | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 71       | 2.93%   |
| MSI MS-7C37                      | 26       | 1.07%   |
| Gigabyte B450M DS3H              | 25       | 1.03%   |
| MSI MS-7C02                      | 24       | 0.99%   |
| Unknown                          | 21       | 0.87%   |
| ASUS TUF Gaming X570-PLUS        | 20       | 0.82%   |
| ASUS PRIME A320M-K               | 18       | 0.74%   |
| MSI MS-7C91                      | 17       | 0.7%    |
| ASRock B450M Pro4                | 16       | 0.66%   |
| MSI MS-7B86                      | 15       | 0.62%   |
| MSI MS-7B79                      | 15       | 0.62%   |
| ASUS ROG STRIX B450-F GAMING     | 14       | 0.58%   |
| MSI MS-7A38                      | 12       | 0.49%   |
| Gigabyte X570 AORUS ELITE        | 12       | 0.49%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.49%   |
| ASUS ROG STRIX B550-F GAMING     | 12       | 0.49%   |
| ASUS PRIME B450M-A               | 12       | 0.49%   |
| Dell OptiPlex 9020               | 11       | 0.45%   |
| Dell OptiPlex 7010               | 11       | 0.45%   |
| ASUS PRIME B350-PLUS             | 11       | 0.45%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.41%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.41%   |
| Gigabyte B450 AORUS M            | 10       | 0.41%   |
| Gigabyte 970A-DS3P               | 10       | 0.41%   |
| ASUS ROG STRIX X570-E GAMING     | 10       | 0.41%   |
| MSI MS-7B89                      | 9        | 0.37%   |
| MSI MS-7817                      | 9        | 0.37%   |
| MSI MS-7693                      | 9        | 0.37%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.37%   |
| ASUS PRIME X470-PRO              | 9        | 0.37%   |
| ASUS PRIME B450-PLUS             | 9        | 0.37%   |
| MSI MS-7C94                      | 8        | 0.33%   |
| MSI MS-7A34                      | 8        | 0.33%   |
| Gigabyte B450 AORUS ELITE        | 8        | 0.33%   |
| ASUS PRIME X370-PRO              | 8        | 0.33%   |
| ASUS PRIME B350M-A               | 8        | 0.33%   |
| ASRock B450M Steel Legend        | 8        | 0.33%   |
| ASRock B450 Pro4                 | 8        | 0.33%   |
| ASUS ROG STRIX X570-F GAMING     | 7        | 0.29%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 157      | 6.47%   |
| ASUS ROG           | 137      | 5.64%   |
| Dell OptiPlex      | 78       | 3.21%   |
| ASUS TUF           | 74       | 3.05%   |
| ASUS All           | 71       | 2.93%   |
| Gigabyte X570      | 46       | 1.9%    |
| Gigabyte B450M     | 42       | 1.73%   |
| HP Compaq          | 34       | 1.4%    |
| Gigabyte B450      | 32       | 1.32%   |
| MSI MS-7C37        | 26       | 1.07%   |
| ASRock B450M       | 26       | 1.07%   |
| MSI MS-7C02        | 24       | 0.99%   |
| Lenovo ThinkCentre | 23       | 0.95%   |
| Unknown            | 21       | 0.87%   |
| ASRock X570        | 20       | 0.82%   |
| Dell Precision     | 19       | 0.78%   |
| HP EliteDesk       | 18       | 0.74%   |
| ASRock B450        | 18       | 0.74%   |
| MSI MS-7C91        | 17       | 0.7%    |
| Acer Aspire        | 17       | 0.7%    |
| Gigabyte B550      | 16       | 0.66%   |
| MSI MS-7B86        | 15       | 0.62%   |
| MSI MS-7B79        | 15       | 0.62%   |
| ASUS P8Z77-V       | 15       | 0.62%   |
| Gigabyte Z390      | 14       | 0.58%   |
| ASUS M5A97         | 14       | 0.58%   |
| ASUS M5A78L-M      | 13       | 0.54%   |
| MSI MS-7A38        | 12       | 0.49%   |
| Gigabyte X470      | 12       | 0.49%   |
| ASUS Maximus       | 12       | 0.49%   |
| Gigabyte B550M     | 11       | 0.45%   |
| Gigabyte 970A-DS3P | 11       | 0.45%   |
| ASUS P8H61-M       | 11       | 0.45%   |
| MSI MS-7B89        | 9        | 0.37%   |
| MSI MS-7817        | 9        | 0.37%   |
| MSI MS-7693        | 9        | 0.37%   |
| HP Pavilion        | 9        | 0.37%   |
| ASRock X470        | 9        | 0.37%   |
| ASRock B550M       | 9        | 0.37%   |
| ASRock AB350       | 9        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 400      | 16.48%  |
| 2019    | 309      | 12.73%  |
| 2020    | 266      | 10.96%  |
| 2017    | 207      | 8.53%   |
| 2012    | 201      | 8.28%   |
| 2013    | 173      | 7.13%   |
| 2014    | 143      | 5.89%   |
| 2011    | 133      | 5.48%   |
| 2015    | 108      | 4.45%   |
| 2016    | 105      | 4.33%   |
| 2021    | 85       | 3.5%    |
| 2010    | 84       | 3.46%   |
| 2009    | 74       | 3.05%   |
| 2008    | 46       | 1.9%    |
| 2007    | 43       | 1.77%   |
| 2022    | 33       | 1.36%   |
| 2006    | 12       | 0.49%   |
| 2005    | 4        | 0.16%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2427     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2425     | 99.88%  |
| Enabled  | 3        | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2425     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 894      | 36.15%  |
| 32.01-64.0  | 506      | 20.46%  |
| 8.01-16.0   | 445      | 17.99%  |
| 4.01-8.0    | 234      | 9.46%   |
| 3.01-4.0    | 165      | 6.67%   |
| 64.01-256.0 | 117      | 4.73%   |
| 24.01-32.0  | 77       | 3.11%   |
| 1.01-2.0    | 30       | 1.21%   |
| 2.01-3.0    | 5        | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 682      | 24.85%  |
| 2.01-3.0    | 621      | 22.63%  |
| 1.01-2.0    | 617      | 22.49%  |
| 3.01-4.0    | 451      | 16.44%  |
| 8.01-16.0   | 231      | 8.42%   |
| 0.51-1.0    | 70       | 2.55%   |
| 16.01-24.0  | 40       | 1.46%   |
| 24.01-32.0  | 11       | 0.4%    |
| 0.01-0.5    | 11       | 0.4%    |
| 32.01-64.0  | 9        | 0.33%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 766      | 30.04%  |
| 1      | 598      | 23.45%  |
| 3      | 514      | 20.16%  |
| 4      | 335      | 13.14%  |
| 5      | 188      | 7.37%   |
| 6      | 70       | 2.75%   |
| 7      | 36       | 1.41%   |
| 8      | 14       | 0.55%   |
| 0      | 11       | 0.43%   |
| 9      | 9        | 0.35%   |
| 11     | 4        | 0.16%   |
| 12     | 2        | 0.08%   |
| 10     | 2        | 0.08%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1625     | 65.9%   |
| Yes       | 841      | 34.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2401     | 98.93%  |
| No        | 26       | 1.07%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1313     | 53.35%  |
| Yes       | 1148     | 46.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1470     | 59.56%  |
| Yes       | 998      | 40.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 461      | 18.88%  |
| Germany      | 297      | 12.16%  |
| Russia       | 226      | 9.25%   |
| Brazil       | 146      | 5.98%   |
| Canada       | 97       | 3.97%   |
| France       | 88       | 3.6%    |
| Spain        | 81       | 3.32%   |
| UK           | 79       | 3.24%   |
| Italy        | 75       | 3.07%   |
| Poland       | 73       | 2.99%   |
| Ukraine      | 54       | 2.21%   |
| Netherlands  | 47       | 1.92%   |
| Sweden       | 42       | 1.72%   |
| Austria      | 37       | 1.52%   |
| Australia    | 37       | 1.52%   |
| Finland      | 29       | 1.19%   |
| Belgium      | 26       | 1.06%   |
| Mexico       | 25       | 1.02%   |
| Romania      | 23       | 0.94%   |
| India        | 23       | 0.94%   |
| Argentina    | 22       | 0.9%    |
| Greece       | 20       | 0.82%   |
| Bulgaria     | 19       | 0.78%   |
| Norway       | 18       | 0.74%   |
| Portugal     | 17       | 0.7%    |
| Hungary      | 17       | 0.7%    |
| Denmark      | 17       | 0.7%    |
| Switzerland  | 16       | 0.66%   |
| South Africa | 14       | 0.57%   |
| China        | 14       | 0.57%   |
| Belarus      | 13       | 0.53%   |
| Israel       | 12       | 0.49%   |
| Czechia      | 12       | 0.49%   |
| Turkey       | 11       | 0.45%   |
| Saudi Arabia | 10       | 0.41%   |
| New Zealand  | 10       | 0.41%   |
| Lithuania    | 10       | 0.41%   |
| Ireland      | 10       | 0.41%   |
| Philippines  | 9        | 0.37%   |
| Chile        | 9        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 53       | 2.06%   |
| St Petersburg     | 24       | 0.93%   |
| Berlin            | 19       | 0.74%   |
| Warsaw            | 18       | 0.7%    |
| Vienna            | 18       | 0.7%    |
| Kyiv              | 17       | 0.66%   |
| Madrid            | 15       | 0.58%   |
| Toronto           | 14       | 0.54%   |
| Sao Paulo         | 14       | 0.54%   |
| Athens            | 14       | 0.54%   |
| Rome              | 13       | 0.5%    |
| Stockholm         | 12       | 0.47%   |
| Rio de Janeiro    | 12       | 0.47%   |
| Frankfurt am Main | 12       | 0.47%   |
| Helsinki          | 11       | 0.43%   |
| Amsterdam         | 11       | 0.43%   |
| Sydney            | 10       | 0.39%   |
| Portland          | 10       | 0.39%   |
| Paris             | 10       | 0.39%   |
| Krakow            | 10       | 0.39%   |
| Hamburg           | 10       | 0.39%   |
| Bucharest         | 10       | 0.39%   |
| Sofia             | 9        | 0.35%   |
| Milan             | 9        | 0.35%   |
| Dallas            | 9        | 0.35%   |
| Copenhagen        | 9        | 0.35%   |
| Barcelona         | 9        | 0.35%   |
| Stuttgart         | 8        | 0.31%   |
| New York          | 8        | 0.31%   |
| Minsk             | 8        | 0.31%   |
| Miami             | 8        | 0.31%   |
| Melbourne         | 8        | 0.31%   |
| Indianapolis      | 8        | 0.31%   |
| Austin            | 8        | 0.31%   |
| Yekaterinburg     | 7        | 0.27%   |
| Omsk              | 7        | 0.27%   |
| Munich            | 7        | 0.27%   |
| Montreal          | 7        | 0.27%   |
| Istanbul          | 7        | 0.27%   |
| Denver            | 7        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 957      | 1603   | 17.94%  |
| Seagate                     | 930      | 1504   | 17.44%  |
| Samsung Electronics         | 887      | 1560   | 16.63%  |
| Kingston                    | 339      | 478    | 6.36%   |
| Toshiba                     | 292      | 380    | 5.48%   |
| Crucial                     | 279      | 427    | 5.23%   |
| SanDisk                     | 271      | 364    | 5.08%   |
| Hitachi                     | 134      | 194    | 2.51%   |
| Intel                       | 106      | 145    | 1.99%   |
| Phison                      | 83       | 111    | 1.56%   |
| A-DATA Technology           | 82       | 116    | 1.54%   |
| HGST                        | 61       | 96     | 1.14%   |
| China                       | 50       | 70     | 0.94%   |
| Silicon Motion              | 46       | 63     | 0.86%   |
| PNY                         | 41       | 62     | 0.77%   |
| OCZ                         | 39       | 53     | 0.73%   |
| Unknown                     | 36       | 61     | 0.68%   |
| SPCC                        | 35       | 42     | 0.66%   |
| Patriot                     | 34       | 42     | 0.64%   |
| Intenso                     | 34       | 50     | 0.64%   |
| Micron/Crucial Technology   | 33       | 42     | 0.62%   |
| XPG                         | 32       | 36     | 0.6%    |
| SK hynix                    | 30       | 34     | 0.56%   |
| Corsair                     | 27       | 38     | 0.51%   |
| Micron Technology           | 23       | 29     | 0.43%   |
| Transcend                   | 21       | 21     | 0.39%   |
| Plextor                     | 21       | 24     | 0.39%   |
| Phison Electronics          | 19       | 22     | 0.36%   |
| JMicron Technology          | 19       | 25     | 0.36%   |
| GOODRAM                     | 19       | 23     | 0.36%   |
| Team                        | 18       | 23     | 0.34%   |
| Realtek Semiconductor       | 18       | 23     | 0.34%   |
| Lexar                       | 18       | 20     | 0.34%   |
| Apacer                      | 15       | 17     | 0.28%   |
| Kingston Technology Company | 14       | 15     | 0.26%   |
| Maxtor                      | 13       | 15     | 0.24%   |
| Gigabyte Technology         | 12       | 21     | 0.23%   |
| ASMT                        | 11       | 18     | 0.21%   |
| KingDian                    | 10       | 10     | 0.19%   |
| Hewlett-Packard             | 10       | 14     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 88       | 1.38%   |
| Samsung SSD 860 EVO 500GB                           | 80       | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                      | 77       | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB                      | 70       | 1.1%    |
| Samsung NVMe SSD Drive 500GB                        | 63       | 0.99%   |
| Samsung SSD 850 EVO 500GB                           | 62       | 0.98%   |
| Samsung SSD 850 EVO 250GB                           | 60       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 54       | 0.85%   |
| Toshiba DT01ACA100 1TB                              | 52       | 0.82%   |
| Kingston SA400S37120G 120GB SSD                     | 52       | 0.82%   |
| Samsung SSD 860 EVO 1TB                             | 49       | 0.77%   |
| Samsung NVMe SSD Drive 1TB                          | 49       | 0.77%   |
| Crucial CT500MX500SSD1 500GB                        | 48       | 0.76%   |
| Seagate ST500DM002-1BD142 500GB                     | 40       | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                      | 40       | 0.63%   |
| Samsung SSD 860 EVO 250GB                           | 40       | 0.63%   |
| Kingston SA400S37480G 480GB SSD                     | 40       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 39       | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 39       | 0.61%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 37       | 0.58%   |
| Toshiba HDWD110 1TB                                 | 37       | 0.58%   |
| Crucial CT240BX500SSD1 240GB                        | 35       | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 33       | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                      | 32       | 0.5%    |
| Seagate ST2000DM001-1ER164 2TB                      | 31       | 0.49%   |
| SanDisk NVMe SSD Drive 500GB                        | 31       | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                    | 31       | 0.49%   |
| Seagate ST3500418AS 500GB                           | 30       | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 28       | 0.44%   |
| Toshiba DT01ACA200 2TB                              | 28       | 0.44%   |
| Seagate ST4000DM004-2CV104 4TB                      | 27       | 0.42%   |
| Seagate Expansion+ 2TB                              | 27       | 0.42%   |
| Toshiba DT01ACA050 500GB                            | 25       | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB                      | 25       | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 24       | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                      | 24       | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 24       | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 24       | 0.38%   |
| Seagate ST31000524AS 1TB                            | 23       | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 23       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 911      | 1463   | 37.37%  |
| WDC                 | 850      | 1373   | 34.86%  |
| Toshiba             | 261      | 334    | 10.71%  |
| Samsung Electronics | 136      | 210    | 5.58%   |
| Hitachi             | 134      | 194    | 5.5%    |
| HGST                | 60       | 95     | 2.46%   |
| Unknown             | 16       | 25     | 0.66%   |
| Maxtor              | 13       | 15     | 0.53%   |
| ASMT                | 9        | 16     | 0.37%   |
| SABRENT             | 8        | 8      | 0.33%   |
| Fujitsu             | 8        | 8      | 0.33%   |
| Intenso             | 6        | 10     | 0.25%   |
| Apple               | 5        | 8      | 0.21%   |
| USB3.0              | 4        | 4      | 0.16%   |
| HGST HTS            | 3        | 3      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB                 | 2        | 2      | 0.08%   |
| Maxone              | 2        | 2      | 0.08%   |
| JMicron Technology  | 2        | 4      | 0.08%   |
| Hewlett-Packard     | 2        | 2      | 0.08%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 527      | 805    | 26.25%  |
| Kingston            | 297      | 411    | 14.79%  |
| Crucial             | 252      | 391    | 12.55%  |
| SanDisk             | 164      | 215    | 8.17%   |
| WDC                 | 130      | 184    | 6.47%   |
| A-DATA Technology   | 68       | 97     | 3.39%   |
| Intel               | 52       | 70     | 2.59%   |
| China               | 49       | 69     | 2.44%   |
| OCZ                 | 39       | 53     | 1.94%   |
| PNY                 | 36       | 57     | 1.79%   |
| Patriot             | 32       | 40     | 1.59%   |
| SPCC                | 29       | 36     | 1.44%   |
| Toshiba             | 22       | 32     | 1.1%    |
| Intenso             | 20       | 30     | 1%      |
| Plextor             | 19       | 22     | 0.95%   |
| Corsair             | 19       | 28     | 0.95%   |
| Lexar               | 18       | 20     | 0.9%    |
| GOODRAM             | 18       | 22     | 0.9%    |
| Transcend           | 16       | 16     | 0.8%    |
| Micron Technology   | 15       | 17     | 0.75%   |
| Apacer              | 15       | 17     | 0.75%   |
| Team                | 14       | 19     | 0.7%    |
| SK hynix            | 11       | 12     | 0.55%   |
| KingDian            | 10       | 10     | 0.5%    |
| Gigabyte Technology | 10       | 14     | 0.5%    |
| Seagate             | 9        | 12     | 0.45%   |
| Leven               | 8        | 8      | 0.4%    |
| KingSpec            | 7        | 9      | 0.35%   |
| JMicron Technology  | 7        | 8      | 0.35%   |
| LITEONIT            | 5        | 7      | 0.25%   |
| Apple               | 5        | 5      | 0.25%   |
| Verbatim            | 4        | 5      | 0.2%    |
| Mushkin             | 4        | 4      | 0.2%    |
| LITEON              | 4        | 4      | 0.2%    |
| Hoodisk             | 4        | 4      | 0.2%    |
| TO Exter            | 3        | 3      | 0.15%   |
| NGFF                | 3        | 3      | 0.15%   |
| Kingmax             | 3        | 4      | 0.15%   |
| Hewlett-Packard     | 3        | 4      | 0.15%   |
| Smartbuy            | 2        | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1761     | 3782   | 40.98%  |
| SSD     | 1564     | 2846   | 36.4%   |
| NVMe    | 880      | 1401   | 20.48%  |
| Unknown | 87       | 121    | 2.02%   |
| MMC     | 5        | 5      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2238     | 6399   | 66.99%  |
| NVMe | 876      | 1396   | 26.22%  |
| SAS  | 222      | 355    | 6.64%   |
| MMC  | 5        | 5      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1678     | 3250   | 44.25%  |
| 0.51-1.0        | 1162     | 1888   | 30.64%  |
| 1.01-2.0        | 527      | 789    | 13.9%   |
| 3.01-4.0        | 159      | 250    | 4.19%   |
| 2.01-3.0        | 125      | 196    | 3.3%    |
| 4.01-10.0       | 124      | 223    | 3.27%   |
| 10.01-20.0      | 14       | 29     | 0.37%   |
| More than 100.0 | 3        | 3      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 446      | 17.21%  |
| 251-500        | 445      | 17.17%  |
| 1001-2000      | 432      | 16.67%  |
| 501-1000       | 422      | 16.29%  |
| More than 3000 | 366      | 14.13%  |
| 2001-3000      | 224      | 8.65%   |
| Unknown        | 92       | 3.55%   |
| 51-100         | 90       | 3.47%   |
| 1-20           | 41       | 1.58%   |
| 21-50          | 33       | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 417      | 15.48%  |
| 1-20           | 392      | 14.55%  |
| 501-1000       | 349      | 12.95%  |
| 251-500        | 319      | 11.84%  |
| 21-50          | 318      | 11.8%   |
| 51-100         | 293      | 10.88%  |
| 1001-2000      | 262      | 9.73%   |
| More than 3000 | 148      | 5.49%   |
| 2001-3000      | 103      | 3.82%   |
| Unknown        | 92       | 3.41%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.21%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.58%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.58%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.58%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.58%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.26%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.26%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.26%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.26%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.95%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.95%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.95%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.95%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 3        | 3      | 0.95%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.95%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 10     | 0.95%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.95%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.95%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.95%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.95%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.95%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.63%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.63%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.63%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.63%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.63%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.63%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.63%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.63%   |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.63%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 3      | 0.63%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 97       | 113    | 31.8%   |
| Seagate             | 85       | 124    | 27.87%  |
| Samsung Electronics | 27       | 33     | 8.85%   |
| Hitachi             | 19       | 21     | 6.23%   |
| Kingston            | 12       | 12     | 3.93%   |
| Toshiba             | 11       | 14     | 3.61%   |
| SanDisk             | 9        | 12     | 2.95%   |
| Intel               | 9        | 10     | 2.95%   |
| HGST                | 7        | 7      | 2.3%    |
| Crucial             | 7        | 7      | 2.3%    |
| A-DATA Technology   | 4        | 4      | 1.31%   |
| OCZ                 | 2        | 2      | 0.66%   |
| Apacer              | 2        | 2      | 0.66%   |
| Transcend           | 1        | 1      | 0.33%   |
| SPCC                | 1        | 1      | 0.33%   |
| SK hynix            | 1        | 2      | 0.33%   |
| Phison              | 1        | 2      | 0.33%   |
| Patriot             | 1        | 1      | 0.33%   |
| Maxtor              | 1        | 1      | 0.33%   |
| MaxDigital          | 1        | 1      | 0.33%   |
| KingSpec            | 1        | 2      | 0.33%   |
| Intenso             | 1        | 4      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| Fujitsu             | 1        | 1      | 0.33%   |
| Drevo               | 1        | 1      | 0.33%   |
| Corsair             | 1        | 5      | 0.33%   |
| ASMT                | 1        | 5      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 96       | 112    | 40%     |
| Seagate             | 84       | 121    | 35%     |
| Samsung Electronics | 19       | 24     | 7.92%   |
| Hitachi             | 19       | 21     | 7.92%   |
| Toshiba             | 11       | 14     | 4.58%   |
| HGST                | 7        | 7      | 2.92%   |
| Maxtor              | 1        | 1      | 0.42%   |
| MaxDigital          | 1        | 1      | 0.42%   |
| Fujitsu             | 1        | 1      | 0.42%   |
| ASMT                | 1        | 5      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 221      | 307    | 77.82%  |
| SSD  | 53       | 70     | 18.66%  |
| NVMe | 10       | 12     | 3.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1595     | 5068   | 56.62%  |
| Works    | 941      | 2685   | 33.4%   |
| Malfunc  | 269      | 389    | 9.55%   |
| Failed   | 12       | 13     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1285     | 34.51%  |
| AMD                              | 1129     | 30.32%  |
| Samsung Electronics              | 376      | 10.1%   |
| ASMedia Technology               | 157      | 4.22%   |
| SanDisk                          | 143      | 3.84%   |
| Phison Electronics               | 115      | 3.09%   |
| Marvell Technology Group         | 69       | 1.85%   |
| Micron/Crucial Technology        | 62       | 1.66%   |
| Silicon Motion                   | 61       | 1.64%   |
| Kingston Technology Company      | 60       | 1.61%   |
| JMicron Technology               | 56       | 1.5%    |
| ADATA Technology                 | 42       | 1.13%   |
| Nvidia                           | 35       | 0.94%   |
| Realtek Semiconductor            | 29       | 0.78%   |
| SK hynix                         | 19       | 0.51%   |
| Toshiba America Info Systems     | 9        | 0.24%   |
| Seagate Technology               | 9        | 0.24%   |
| KIOXIA                           | 9        | 0.24%   |
| Micron Technology                | 8        | 0.21%   |
| LSI Logic / Symbios Logic        | 8        | 0.21%   |
| VIA Technologies                 | 7        | 0.19%   |
| Silicon Image                    | 5        | 0.13%   |
| Lite-On Technology               | 5        | 0.13%   |
| Broadcom / LSI                   | 4        | 0.11%   |
| Adaptec                          | 4        | 0.11%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Shenzhen Longsys Electronics     | 2        | 0.05%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Promise Technology               | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |
| Beijing Starblaze Technology     | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 765      | 16.41%  |
| AMD 400 Series Chipset SATA Controller                                                  | 332      | 7.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 230      | 4.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 154      | 3.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 154      | 3.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 142      | 3.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 127      | 2.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 106      | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 106      | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 105      | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 101      | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 94       | 2.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 85       | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 82       | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 76       | 1.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 67       | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 61       | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 55       | 1.18%   |
| Phison E12 NVMe Controller                                                              | 55       | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53       | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 53       | 1.14%   |
| AMD FCH SATA Controller D                                                               | 51       | 1.09%   |
| AMD X370 Series Chipset SATA Controller                                                 | 42       | 0.9%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 40       | 0.86%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 38       | 0.82%   |
| Kingston Company A2000 NVMe SSD                                                         | 37       | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 35       | 0.75%   |
| Intel SSD 660P Series                                                                   | 34       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 33       | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 33       | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 30       | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 29       | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 28       | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 26       | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 25       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2151     | 60.71%  |
| NVMe | 881      | 24.87%  |
| IDE  | 365      | 10.3%   |
| RAID | 126      | 3.56%   |
| SAS  | 17       | 0.48%   |
| SCSI | 3        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1263     | 52.02%  |
| AMD    | 1165     | 47.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 129      | 5.29%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 75       | 3.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 61       | 2.5%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 61       | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 45       | 1.85%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 32       | 1.31%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 31       | 1.27%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 28       | 1.15%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 26       | 1.07%   |
| AMD FX-8350 Eight-Core Processor            | 26       | 1.07%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 1.03%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 24       | 0.98%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 0.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 23       | 0.94%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 22       | 0.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.9%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 22       | 0.9%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 22       | 0.9%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 22       | 0.9%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 22       | 0.9%    |
| AMD FX-6300 Six-Core Processor              | 22       | 0.9%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 20       | 0.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 19       | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 19       | 0.78%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 19       | 0.78%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.74%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 18       | 0.74%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 17       | 0.7%    |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 17       | 0.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 16       | 0.66%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.62%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 0.62%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 15       | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 415      | 17.06%  |
| AMD Ryzen 5             | 406      | 16.69%  |
| Intel Core i7           | 342      | 14.06%  |
| AMD Ryzen 7             | 274      | 11.26%  |
| Intel Core i3           | 128      | 5.26%   |
| Intel Xeon              | 116      | 4.77%   |
| AMD Ryzen 9             | 113      | 4.64%   |
| AMD FX                  | 106      | 4.36%   |
| Other                   | 47       | 1.93%   |
| AMD Ryzen 3             | 45       | 1.85%   |
| Intel Core 2 Duo        | 43       | 1.77%   |
| Intel Celeron           | 34       | 1.4%    |
| Intel Pentium           | 30       | 1.23%   |
| AMD Ryzen Threadripper  | 26       | 1.07%   |
| AMD Phenom II X4        | 26       | 1.07%   |
| Intel Core 2 Quad       | 25       | 1.03%   |
| Intel Pentium Dual-Core | 22       | 0.9%    |
| Intel Core i9           | 22       | 0.9%    |
| AMD Athlon II X2        | 19       | 0.78%   |
| AMD A10                 | 19       | 0.78%   |
| AMD A8                  | 18       | 0.74%   |
| AMD A4                  | 15       | 0.62%   |
| AMD Athlon              | 12       | 0.49%   |
| Intel Core 2            | 11       | 0.45%   |
| AMD Phenom II X6        | 11       | 0.45%   |
| AMD Athlon 64 X2        | 11       | 0.45%   |
| AMD Athlon II X4        | 9        | 0.37%   |
| Intel Atom              | 8        | 0.33%   |
| AMD Ryzen 5 PRO         | 8        | 0.33%   |
| AMD Athlon X4           | 8        | 0.33%   |
| AMD Phenom              | 7        | 0.29%   |
| Intel Pentium Gold      | 6        | 0.25%   |
| Intel Pentium Dual      | 6        | 0.25%   |
| AMD Ryzen 7 PRO         | 6        | 0.25%   |
| Intel Genuine           | 5        | 0.21%   |
| AMD Athlon II X3        | 5        | 0.21%   |
| Intel Pentium D         | 4        | 0.16%   |
| AMD Sempron             | 3        | 0.12%   |
| AMD Phenom II X2        | 3        | 0.12%   |
| AMD E1                  | 3        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 857      | 35.21%  |
| 6       | 578      | 23.75%  |
| 2       | 375      | 15.41%  |
| 8       | 361      | 14.83%  |
| 12      | 103      | 4.23%   |
| 16      | 61       | 2.51%   |
| 3       | 43       | 1.77%   |
| 1       | 26       | 1.07%   |
| 10      | 18       | 0.74%   |
| 24      | 5        | 0.21%   |
| 32      | 3        | 0.12%   |
| Unknown | 2        | 0.08%   |
| 20      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2409     | 99.26%  |
| 2      | 18       | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1639     | 67.34%  |
| 1       | 793      | 32.58%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2399     | 98.64%  |
| Unknown        | 33       | 1.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1242     | 49.36%  |
| 0x08701021 | 132      | 5.25%   |
| 0x306c3    | 101      | 4.01%   |
| 0x0800820d | 100      | 3.97%   |
| 0x08701013 | 76       | 3.02%   |
| 0x306a9    | 66       | 2.62%   |
| 0x206a7    | 61       | 2.42%   |
| 0x906ea    | 56       | 2.23%   |
| 0x506e3    | 50       | 1.99%   |
| 0x06000852 | 47       | 1.87%   |
| 0x1067a    | 34       | 1.35%   |
| 0x08001138 | 32       | 1.27%   |
| 0x906e9    | 28       | 1.11%   |
| 0x306f2    | 22       | 0.87%   |
| 0x0a201009 | 22       | 0.87%   |
| 0x010000c8 | 22       | 0.87%   |
| 0x0a201016 | 21       | 0.83%   |
| 0x08108109 | 20       | 0.79%   |
| 0x206d7    | 19       | 0.76%   |
| 0x08001137 | 19       | 0.76%   |
| 0x08101016 | 14       | 0.56%   |
| 0x06003106 | 14       | 0.56%   |
| 0xa0655    | 13       | 0.52%   |
| 0x906ed    | 13       | 0.52%   |
| 0x106e5    | 12       | 0.48%   |
| 0x06001119 | 12       | 0.48%   |
| 0x90672    | 11       | 0.44%   |
| 0x08600106 | 11       | 0.44%   |
| 0x0a50000c | 9        | 0.36%   |
| 0x0a20120a | 9        | 0.36%   |
| 0x08001129 | 9        | 0.36%   |
| 0xa0671    | 8        | 0.32%   |
| 0xa0653    | 8        | 0.32%   |
| 0x906ec    | 8        | 0.32%   |
| 0x906eb    | 8        | 0.32%   |
| 0x6fd      | 8        | 0.32%   |
| 0x406f1    | 7        | 0.28%   |
| 0x10676    | 7        | 0.28%   |
| 0x0a601203 | 7        | 0.28%   |
| 0x0a50000d | 7        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 350      | 14.37%  |
| Haswell          | 258      | 10.6%   |
| KabyLake         | 247      | 10.14%  |
| Zen+             | 231      | 9.49%   |
| Zen              | 158      | 6.49%   |
| SandyBridge      | 156      | 6.41%   |
| IvyBridge        | 152      | 6.24%   |
| Zen 3            | 141      | 5.79%   |
| Piledriver       | 117      | 4.8%    |
| Skylake          | 109      | 4.48%   |
| Penryn           | 88       | 3.61%   |
| K10              | 80       | 3.29%   |
| CometLake        | 54       | 2.22%   |
| Unknown          | 44       | 1.81%   |
| Core             | 39       | 1.6%    |
| Nehalem          | 33       | 1.36%   |
| Westmere         | 29       | 1.19%   |
| Steamroller      | 25       | 1.03%   |
| Bulldozer        | 18       | 0.74%   |
| Broadwell        | 17       | 0.7%    |
| K8 Hammer        | 14       | 0.57%   |
| Alderlake Hybrid | 11       | 0.45%   |
| Excavator        | 8        | 0.33%   |
| Icelake          | 7        | 0.29%   |
| Goldmont plus    | 7        | 0.29%   |
| Bonnell          | 7        | 0.29%   |
| Silvermont       | 6        | 0.25%   |
| NetBurst         | 6        | 0.25%   |
| Goldmont         | 6        | 0.25%   |
| K10 Llano        | 5        | 0.21%   |
| Jaguar           | 4        | 0.16%   |
| Bobcat           | 4        | 0.16%   |
| Puma             | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |
| TigerLake        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1232     | 47.08%  |
| AMD                        | 927      | 35.42%  |
| Intel                      | 456      | 17.42%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 231      | 8.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 91       | 3.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 85       | 3.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 84       | 3.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 83       | 3.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 62       | 2.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 53       | 1.97%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 52       | 1.93%   |
| Nvidia GK208B [GeForce GT 710]                                              | 51       | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 48       | 1.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 42       | 1.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 39       | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 38       | 1.41%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 34       | 1.26%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 32       | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 32       | 1.19%   |
| Intel HD Graphics 530                                                       | 30       | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30       | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 28       | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 28       | 1.04%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 27       | 1%      |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 26       | 0.97%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 24       | 0.89%   |
| Intel HD Graphics 630                                                       | 23       | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.85%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 23       | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 0.74%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 0.74%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 20       | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 19       | 0.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 19       | 0.71%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 18       | 0.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 18       | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 17       | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1123     | 45.56%  |
| 1 x AMD            | 843      | 34.2%   |
| 1 x Intel          | 335      | 13.59%  |
| Intel + Nvidia     | 46       | 1.87%   |
| AMD + Nvidia       | 38       | 1.54%   |
| 2 x AMD            | 37       | 1.5%    |
| 2 x Nvidia         | 26       | 1.05%   |
| Intel + AMD        | 14       | 0.57%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1442     | 58.67%  |
| Proprietary | 1004     | 40.85%  |
| Unknown     | 12       | 0.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 987      | 39.46%  |
| 7.01-8.0   | 388      | 15.51%  |
| 1.01-2.0   | 306      | 12.24%  |
| 3.01-4.0   | 261      | 10.44%  |
| 5.01-6.0   | 174      | 6.96%   |
| 0.51-1.0   | 150      | 6%      |
| 8.01-16.0  | 94       | 3.76%   |
| 0.01-0.5   | 82       | 3.28%   |
| 2.01-3.0   | 44       | 1.76%   |
| 16.01-24.0 | 13       | 0.52%   |
| 4.01-5.0   | 2        | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 454      | 15.69%  |
| Goldstar             | 309      | 10.68%  |
| Dell                 | 267      | 9.23%   |
| Acer                 | 235      | 8.12%   |
| AOC                  | 177      | 6.12%   |
| Ancor Communications | 175      | 6.05%   |
| BenQ                 | 170      | 5.87%   |
| Hewlett-Packard      | 138      | 4.77%   |
| Philips              | 118      | 4.08%   |
| LG Electronics       | 97       | 3.35%   |
| ViewSonic            | 65       | 2.25%   |
| ASUSTek Computer     | 61       | 2.11%   |
| Lenovo               | 45       | 1.55%   |
| Iiyama               | 42       | 1.45%   |
| Unknown              | 41       | 1.42%   |
| Sony                 | 26       | 0.9%    |
| Unknown              | 26       | 0.9%    |
| Vizio                | 21       | 0.73%   |
| MSI                  | 17       | 0.59%   |
| AUS                  | 17       | 0.59%   |
| Eizo                 | 16       | 0.55%   |
| Fujitsu Siemens      | 15       | 0.52%   |
| NEC Computers        | 14       | 0.48%   |
| Idek Iiyama          | 14       | 0.48%   |
| Sceptre Tech         | 12       | 0.41%   |
| Medion               | 12       | 0.41%   |
| Gigabyte Technology  | 11       | 0.38%   |
| Sharp                | 10       | 0.35%   |
| Vestel Elektronik    | 8        | 0.28%   |
| Microstep            | 8        | 0.28%   |
| Lenovo Group Limited | 8        | 0.28%   |
| HannStar             | 8        | 0.28%   |
| Toshiba              | 7        | 0.24%   |
| Panasonic            | 7        | 0.24%   |
| Pixio                | 6        | 0.21%   |
| KTC                  | 6        | 0.21%   |
| HPN                  | 6        | 0.21%   |
| Apple                | 6        | 0.21%   |
| Vestel               | 5        | 0.17%   |
| Plain Tree Systems   | 5        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 26       | 0.83%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 18       | 0.57%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 17       | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 17       | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 13       | 0.41%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 10       | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 9        | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 9        | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 9        | 0.29%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 9        | 0.29%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 8        | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8        | 0.25%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                | 8        | 0.25%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 8        | 0.25%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8        | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 7        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 7        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 7        | 0.22%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                       | 7        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 7        | 0.22%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 6        | 0.19%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 6        | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 6        | 0.19%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 6        | 0.19%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                   | 6        | 0.19%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 6        | 0.19%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 6        | 0.19%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 0.19%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 6        | 0.19%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 6        | 0.19%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                         | 6        | 0.19%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 6        | 0.19%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 6        | 0.19%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6        | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 6        | 0.19%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 6        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 5        | 0.16%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 5        | 0.16%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch      | 5        | 0.16%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1243     | 44.14%  |
| 2560x1440 (QHD)    | 261      | 9.27%   |
| 3840x2160 (4K)     | 257      | 9.13%   |
| Unknown            | 160      | 5.68%   |
| 1680x1050 (WSXGA+) | 117      | 4.15%   |
| 1280x1024 (SXGA)   | 113      | 4.01%   |
| 1366x768 (WXGA)    | 74       | 2.63%   |
| 1920x1200 (WUXGA)  | 73       | 2.59%   |
| 3440x1440          | 72       | 2.56%   |
| 1440x900 (WXGA+)   | 68       | 2.41%   |
| 2560x1080          | 64       | 2.27%   |
| 3840x1080          | 63       | 2.24%   |
| 1600x900 (HD+)     | 56       | 1.99%   |
| 1360x768           | 25       | 0.89%   |
| 4480x1440          | 12       | 0.43%   |
| 5760x1080          | 10       | 0.36%   |
| 1920x540           | 10       | 0.36%   |
| 5120x1440          | 9        | 0.32%   |
| 1280x720 (HD)      | 9        | 0.32%   |
| 1024x768 (XGA)     | 9        | 0.32%   |
| 5760x2160          | 7        | 0.25%   |
| 3600x1080          | 7        | 0.25%   |
| 2560x1600          | 6        | 0.21%   |
| 3840x1600          | 5        | 0.18%   |
| 3360x1080          | 5        | 0.18%   |
| 3200x1080          | 5        | 0.18%   |
| 7680x2160          | 4        | 0.14%   |
| 6400x2160          | 4        | 0.14%   |
| 3840x1200          | 4        | 0.14%   |
| 3520x1080          | 4        | 0.14%   |
| 1600x1200          | 4        | 0.14%   |
| 3286x1080          | 3        | 0.11%   |
| 5504x1440          | 2        | 0.07%   |
| 5120x1080          | 2        | 0.07%   |
| 4480x1080          | 2        | 0.07%   |
| 4240x1440          | 2        | 0.07%   |
| 3360x1050          | 2        | 0.07%   |
| 2944x1080          | 2        | 0.07%   |
| 2880x900           | 2        | 0.07%   |
| 2720x1024          | 2        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 488      | 17.54%  |
| 24      | 398      | 14.3%   |
| 27      | 387      | 13.91%  |
| 23      | 327      | 11.75%  |
| 21      | 288      | 10.35%  |
| 19      | 122      | 4.38%   |
| 31      | 107      | 3.84%   |
| 34      | 106      | 3.81%   |
| 22      | 79       | 2.84%   |
| 18      | 69       | 2.48%   |
| 20      | 63       | 2.26%   |
| 17      | 48       | 1.72%   |
| 84      | 34       | 1.22%   |
| 72      | 21       | 0.75%   |
| 32      | 21       | 0.75%   |
| 25      | 20       | 0.72%   |
| 54      | 19       | 0.68%   |
| 40      | 18       | 0.65%   |
| 15      | 15       | 0.54%   |
| 28      | 12       | 0.43%   |
| 65      | 11       | 0.4%    |
| 48      | 10       | 0.36%   |
| 49      | 9        | 0.32%   |
| 43      | 8        | 0.29%   |
| 33      | 8        | 0.29%   |
| 46      | 7        | 0.25%   |
| 37      | 7        | 0.25%   |
| 36      | 6        | 0.22%   |
| 29      | 6        | 0.22%   |
| 26      | 6        | 0.22%   |
| 14      | 6        | 0.22%   |
| 12      | 6        | 0.22%   |
| 42      | 5        | 0.18%   |
| 39      | 5        | 0.18%   |
| 35      | 5        | 0.18%   |
| 60      | 4        | 0.14%   |
| 47      | 4        | 0.14%   |
| 16      | 4        | 0.14%   |
| 64      | 3        | 0.11%   |
| 52      | 3        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 989      | 37.19%  |
| 401-500     | 540      | 20.31%  |
| Unknown     | 488      | 18.35%  |
| 601-700     | 163      | 6.13%   |
| 701-800     | 141      | 5.3%    |
| 351-400     | 79       | 2.97%   |
| 1001-1500   | 71       | 2.67%   |
| 301-350     | 60       | 2.26%   |
| 1501-2000   | 60       | 2.26%   |
| 801-900     | 40       | 1.5%    |
| 201-300     | 15       | 0.56%   |
| 901-1000    | 13       | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1526     | 60.48%  |
| Unknown | 457      | 18.11%  |
| 16/10   | 249      | 9.87%   |
| 21/9    | 116      | 4.6%    |
| 5/4     | 107      | 4.24%   |
| 4/3     | 28       | 1.11%   |
| 3/2     | 18       | 0.71%   |
| 32/9    | 12       | 0.48%   |
| 6/5     | 5        | 0.2%    |
| 3.20    | 1        | 0.04%   |
| 1.96    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 876      | 32.17%  |
| Unknown        | 488      | 17.92%  |
| 301-350        | 388      | 14.25%  |
| 351-500        | 261      | 9.59%   |
| 151-200        | 252      | 9.25%   |
| 251-300        | 138      | 5.07%   |
| More than 1000 | 112      | 4.11%   |
| 141-150        | 94       | 3.45%   |
| 501-1000       | 74       | 2.72%   |
| 101-110        | 18       | 0.66%   |
| 131-140        | 7        | 0.26%   |
| 71-80          | 6        | 0.22%   |
| 81-90          | 2        | 0.07%   |
| 51-60          | 2        | 0.07%   |
| 111-120        | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |
| 121-130        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1379     | 53.37%  |
| 101-120 | 490      | 18.96%  |
| Unknown | 488      | 18.89%  |
| 121-160 | 93       | 3.6%    |
| 1-50    | 86       | 3.33%   |
| 161-240 | 48       | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1794     | 72.19%  |
| 2     | 572      | 23.02%  |
| 3     | 79       | 3.18%   |
| 0     | 35       | 1.41%   |
| 4     | 5        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1481     | 42.61%  |
| Intel                                  | 1098     | 31.59%  |
| Qualcomm Atheros                       | 184      | 5.29%   |
| Broadcom                               | 98       | 2.82%   |
| Ralink Technology                      | 88       | 2.53%   |
| TP-Link                                | 87       | 2.5%    |
| Microsoft                              | 45       | 1.29%   |
| Nvidia                                 | 30       | 0.86%   |
| Aquantia                               | 30       | 0.86%   |
| Ralink                                 | 26       | 0.75%   |
| MediaTek                               | 26       | 0.75%   |
| Qualcomm Atheros Communications        | 23       | 0.66%   |
| Samsung Electronics                    | 20       | 0.58%   |
| Xiaomi                                 | 18       | 0.52%   |
| ASUSTek Computer                       | 17       | 0.49%   |
| NetGear                                | 15       | 0.43%   |
| Marvell Technology Group               | 15       | 0.43%   |
| D-Link                                 | 15       | 0.43%   |
| Huawei Technologies                    | 13       | 0.37%   |
| Broadcom Limited                       | 12       | 0.35%   |
| Linksys                                | 11       | 0.32%   |
| Microchip Technology                   | 8        | 0.23%   |
| D-Link System                          | 8        | 0.23%   |
| Edimax Technology                      | 7        | 0.2%    |
| Mellanox Technologies                  | 6        | 0.17%   |
| Motorola PCS                           | 5        | 0.14%   |
| ASIX Electronics                       | 5        | 0.14%   |
| ZyXEL Communications                   | 4        | 0.12%   |
| InterBiometrics                        | 4        | 0.12%   |
| T & A Mobile Phones                    | 3        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.09%   |
| SEGGER                                 | 3        | 0.09%   |
| Qualcomm                               | 3        | 0.09%   |
| OPPO Electronics                       | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| JMicron Technology                     | 3        | 0.09%   |
| IMC Networks                           | 3        | 0.09%   |
| Google                                 | 3        | 0.09%   |
| Belkin Components                      | 3        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1212     | 30.31%  |
| Intel I211 Gigabit Network Connection                             | 277      | 6.93%   |
| Intel Wi-Fi 6 AX200                                               | 187      | 4.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 136      | 3.4%    |
| Intel Ethernet Connection (2) I219-V                              | 120      | 3%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 77       | 1.93%   |
| Intel Ethernet Controller I225-V                                  | 73       | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 64       | 1.6%    |
| Intel Ethernet Connection (7) I219-V                              | 55       | 1.38%   |
| Intel Wireless-AC 9260                                            | 47       | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 37       | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32       | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 31       | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 30       | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 29       | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.63%   |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.63%   |
| Realtek 802.11ac NIC                                              | 24       | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                   | 23       | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.55%   |
| Intel Wireless 7265                                               | 22       | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 21       | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 20       | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 19       | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.45%   |
| Intel Wireless 8265 / 8275                                        | 18       | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17       | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.43%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 17       | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 16       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15       | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 454      | 36.47%  |
| Realtek Semiconductor                 | 244      | 19.6%   |
| Qualcomm Atheros                      | 92       | 7.39%   |
| Ralink Technology                     | 88       | 7.07%   |
| TP-Link                               | 86       | 6.91%   |
| Broadcom                              | 62       | 4.98%   |
| Microsoft                             | 45       | 3.61%   |
| Ralink                                | 26       | 2.09%   |
| Qualcomm Atheros Communications       | 23       | 1.85%   |
| MediaTek                              | 22       | 1.77%   |
| ASUSTek Computer                      | 17       | 1.37%   |
| NetGear                               | 15       | 1.2%    |
| D-Link                                | 15       | 1.2%    |
| Linksys                               | 11       | 0.88%   |
| Edimax Technology                     | 7        | 0.56%   |
| D-Link System                         | 5        | 0.4%    |
| Broadcom Limited                      | 5        | 0.4%    |
| ZyXEL Communications                  | 4        | 0.32%   |
| IMC Networks                          | 3        | 0.24%   |
| Belkin Components                     | 3        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.24%   |
| ZyDAS                                 | 2        | 0.16%   |
| Tenda                                 | 2        | 0.16%   |
| Mercucys                              | 2        | 0.16%   |
| AVM                                   | 2        | 0.16%   |
| Xiaomi                                | 1        | 0.08%   |
| Wacom                                 | 1        | 0.08%   |
| Senao                                 | 1        | 0.08%   |
| Philips (or NXP)                      | 1        | 0.08%   |
| Marvell Technology Group              | 1        | 0.08%   |
| Fujitsu Siemens Computers             | 1        | 0.08%   |
| Encore Electronics                    | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 187      | 14.88%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 64       | 5.09%   |
| Intel Wireless-AC 9260                                         | 47       | 3.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32       | 2.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 31       | 2.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 30       | 2.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.31%   |
| Ralink MT7601U Wireless Adapter                                | 29       | 2.31%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 1.99%   |
| Realtek 802.11ac NIC                                           | 24       | 1.91%   |
| Qualcomm Atheros AR9271 802.11n                                | 23       | 1.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.75%   |
| Intel Wireless 7265                                            | 22       | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20       | 1.59%   |
| Intel Wireless 8265 / 8275                                     | 18       | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17       | 1.35%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15       | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 1.19%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 14       | 1.11%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 14       | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13       | 1.03%   |
| Microsoft XBOX ACC                                             | 13       | 1.03%   |
| Intel Wireless 3165                                            | 12       | 0.95%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 11       | 0.88%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.88%   |
| Intel Wireless 7260                                            | 11       | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 9        | 0.72%   |
| TP-Link 802.11ac NIC                                           | 9        | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 0.72%   |
| Intel Wireless 8260                                            | 9        | 0.72%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 8        | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1397     | 53.48%  |
| Intel                                  | 886      | 33.92%  |
| Qualcomm Atheros                       | 107      | 4.1%    |
| Broadcom                               | 39       | 1.49%   |
| Nvidia                                 | 30       | 1.15%   |
| Aquantia                               | 30       | 1.15%   |
| Samsung Electronics                    | 20       | 0.77%   |
| Xiaomi                                 | 17       | 0.65%   |
| Marvell Technology Group               | 14       | 0.54%   |
| Huawei Technologies                    | 11       | 0.42%   |
| Broadcom Limited                       | 7        | 0.27%   |
| Mellanox Technologies                  | 6        | 0.23%   |
| ASIX Electronics                       | 5        | 0.19%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.11%   |
| OPPO Electronics                       | 3        | 0.11%   |
| MediaTek                               | 3        | 0.11%   |
| JMicron Technology                     | 3        | 0.11%   |
| Google                                 | 3        | 0.11%   |
| D-Link System                          | 3        | 0.11%   |
| T & A Mobile Phones                    | 2        | 0.08%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.08%   |
| Qualcomm                               | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.08%   |
| National Semiconductor                 | 2        | 0.08%   |
| Motorola PCS                           | 2        | 0.08%   |
| HMD Global                             | 2        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| ICS Advent                             | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1212     | 44.84%  |
| Intel I211 Gigabit Network Connection                             | 277      | 10.25%  |
| Realtek RTL8125 2.5GbE Controller                                 | 136      | 5.03%   |
| Intel Ethernet Connection (2) I219-V                              | 120      | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 77       | 2.85%   |
| Intel Ethernet Controller I225-V                                  | 73       | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 55       | 2.03%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.74%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.59%   |
| Intel Ethernet Connection I217-V                                  | 37       | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.92%   |
| Intel 82574L Gigabit Network Connection                           | 21       | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.7%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17       | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 12       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 10       | 0.37%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.37%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 9        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                             | 9        | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 7        | 0.26%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.26%   |
| Huawei ANA-NX9                                                    | 7        | 0.26%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2402     | 66.96%  |
| WiFi     | 1148     | 32%     |
| Modem    | 29       | 0.81%   |
| Unknown  | 8        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1931     | 76.44%  |
| WiFi     | 595      | 23.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1545     | 63.06%  |
| 2     | 760      | 31.02%  |
| 3     | 110      | 4.49%   |
| 0     | 19       | 0.78%   |
| 5     | 7        | 0.29%   |
| 4     | 7        | 0.29%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2050     | 82.93%  |
| Yes  | 422      | 17.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 427      | 41.26%  |
| Cambridge Silicon Radio         | 288      | 27.83%  |
| ASUSTek Computer                | 95       | 9.18%   |
| Realtek Semiconductor           | 65       | 6.28%   |
| Broadcom                        | 52       | 5.02%   |
| Qualcomm Atheros Communications | 15       | 1.45%   |
| IMC Networks                    | 13       | 1.26%   |
| Apple                           | 13       | 1.26%   |
| TP-Link                         | 9        | 0.87%   |
| Edimax Technology               | 8        | 0.77%   |
| MediaTek                        | 7        | 0.68%   |
| Foxconn / Hon Hai               | 7        | 0.68%   |
| Dynex                           | 6        | 0.58%   |
| HTC (High Tech Computer)        | 5        | 0.48%   |
| Lite-On Technology              | 4        | 0.39%   |
| Conwise Technology              | 4        | 0.39%   |
| SINO WEALTH                     | 3        | 0.29%   |
| Realtek                         | 3        | 0.29%   |
| Integrated System Solution      | 3        | 0.29%   |
| Belkin Components               | 3        | 0.29%   |
| Ralink                          | 2        | 0.19%   |
| Sitecom Europe                  | 1        | 0.1%    |
| Micro Star International        | 1        | 0.1%    |
| D-Link                          | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 288      | 27.72%  |
| Intel AX200 Bluetooth                                                | 172      | 16.55%  |
| Intel Bluetooth wireless interface                                   | 71       | 6.83%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 63       | 6.06%   |
| Realtek Bluetooth Radio                                              | 52       | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 47       | 4.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 39       | 3.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 34       | 3.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 33       | 3.18%   |
| Intel AX201 Bluetooth                                                | 22       | 2.12%   |
| Intel AX210 Bluetooth                                                | 15       | 1.44%   |
| ASUS Bluetooth Radio                                                 | 15       | 1.44%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.25%   |
| ASUS ASUS USB-BT500                                                  | 13       | 1.25%   |
| ASUS BCM20702A0                                                      | 10       | 0.96%   |
| TP-Link UB500 Adapter                                                | 9        | 0.87%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 9        | 0.87%   |
| IMC Networks Bluetooth Radio                                         | 8        | 0.77%   |
| MediaTek Wireless_Device                                             | 7        | 0.67%   |
| Apple Bluetooth Host Controller                                      | 7        | 0.67%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6        | 0.58%   |
| Edimax Bluetooth Adapter                                             | 6        | 0.58%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.58%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.48%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 5        | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 0.38%   |
| Conwise CW6622                                                       | 4        | 0.38%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.38%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.29%   |
| Realtek Bluetooth 5.1 Radio                                          | 3        | 0.29%   |
| Realtek Bluetooth Radio                                              | 3        | 0.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.29%   |
| Intel Bluetooth Device                                               | 3        | 0.29%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.29%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.19%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.19%   |
| Lite-On Bluetooth Device                                             | 2        | 0.19%   |
| Integrated System Solution Bluetooth Device                          | 2        | 0.19%   |
| IMC Networks Wireless_Device                                         | 2        | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1378     | 29.18%  |
| Intel                                | 1218     | 25.79%  |
| Nvidia                               | 1179     | 24.97%  |
| C-Media Electronics                  | 176      | 3.73%   |
| Creative Labs                        | 70       | 1.48%   |
| Logitech                             | 66       | 1.4%    |
| Kingston Technology                  | 44       | 0.93%   |
| JMTek                                | 37       | 0.78%   |
| Texas Instruments                    | 34       | 0.72%   |
| Corsair                              | 32       | 0.68%   |
| SteelSeries ApS                      | 28       | 0.59%   |
| Focusrite-Novation                   | 27       | 0.57%   |
| Creative Technology                  | 27       | 0.57%   |
| Blue Microphones                     | 26       | 0.55%   |
| Razer USA                            | 25       | 0.53%   |
| ASUSTek Computer                     | 25       | 0.53%   |
| Generalplus Technology               | 22       | 0.47%   |
| BEHRINGER International              | 20       | 0.42%   |
| Plantronics                          | 14       | 0.3%    |
| Sony                                 | 13       | 0.28%   |
| Realtek Semiconductor                | 11       | 0.23%   |
| GYROCOM C&C                          | 11       | 0.23%   |
| VIA Technologies                     | 9        | 0.19%   |
| M-Audio                              | 9        | 0.19%   |
| Sennheiser Communications            | 8        | 0.17%   |
| Samson Technologies                  | 8        | 0.17%   |
| Turtle Beach                         | 7        | 0.15%   |
| SAVITECH                             | 7        | 0.15%   |
| RODE Microphones                     | 7        | 0.15%   |
| GN Netcom                            | 7        | 0.15%   |
| Giga-Byte Technology                 | 7        | 0.15%   |
| Yamaha                               | 6        | 0.13%   |
| XMOS                                 | 6        | 0.13%   |
| Micro Star International             | 6        | 0.13%   |
| Dell                                 | 6        | 0.13%   |
| Astro Gaming                         | 6        | 0.13%   |
| Valve Software                       | 5        | 0.11%   |
| Elgato Systems                       | 5        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 4        | 0.08%   |
| ROCCAT                               | 4        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 418      | 7.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 292      | 5.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 233      | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 161      | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 160      | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 150      | 2.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 149      | 2.7%    |
| Intel 200 Series PCH HD Audio                                              | 132      | 2.39%   |
| Nvidia GP104 High Definition Audio Controller                              | 125      | 2.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 119      | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 112      | 2.03%   |
| AMD Navi 10 HDMI Audio                                                     | 107      | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 106      | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 106      | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 97       | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 91       | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 75       | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 69       | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 68       | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 68       | 1.23%   |
| AMD FCH Azalia Controller                                                  | 67       | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 66       | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 62       | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                              | 61       | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 60       | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 59       | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 57       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 55       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 52       | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52       | 0.94%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 43       | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 42       | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 42       | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 42       | 0.76%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 40       | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 37       | 0.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 35       | 0.63%   |
| Nvidia GP102 HDMI Audio Controller                                         | 34       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 298      | 18.78%  |
| Kingston                     | 285      | 17.96%  |
| G.Skill                      | 222      | 13.99%  |
| Unknown                      | 195      | 12.29%  |
| Crucial                      | 145      | 9.14%   |
| Samsung Electronics          | 89       | 5.61%   |
| SK hynix                     | 59       | 3.72%   |
| Micron Technology            | 48       | 3.02%   |
| Team                         | 40       | 2.52%   |
| A-DATA Technology            | 40       | 2.52%   |
| Patriot                      | 31       | 1.95%   |
| Nanya Technology             | 11       | 0.69%   |
| GOODRAM                      | 11       | 0.69%   |
| Elpida                       | 9        | 0.57%   |
| Unknown                      | 9        | 0.57%   |
| Unknown (ABCD)               | 7        | 0.44%   |
| Ramaxel Technology           | 7        | 0.44%   |
| Kllisre                      | 5        | 0.32%   |
| GeIL                         | 5        | 0.32%   |
| Transcend                    | 4        | 0.25%   |
| Smart                        | 4        | 0.25%   |
| Silicon Power                | 4        | 0.25%   |
| PNY                          | 4        | 0.25%   |
| AMD                          | 4        | 0.25%   |
| Kingmax                      | 3        | 0.19%   |
| CSX                          | 3        | 0.19%   |
| Apacer                       | 3        | 0.19%   |
| Unknown (08C8)               | 2        | 0.13%   |
| Qumo                         | 2        | 0.13%   |
| Patriot Memory (PDP Systems) | 2        | 0.13%   |
| Patriot Memory               | 2        | 0.13%   |
| Neo Forza                    | 2        | 0.13%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| TEXTORM                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 41       | 2.34%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 32       | 1.82%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 20       | 1.14%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 20       | 1.14%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 17       | 0.97%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 16       | 0.91%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 16       | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 14       | 0.8%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 14       | 0.8%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 13       | 0.74%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 12       | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 11       | 0.63%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 10       | 0.57%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s          | 10       | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 10       | 0.57%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 10       | 0.57%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                 | 10       | 0.57%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 9        | 0.51%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 9        | 0.51%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 9        | 0.51%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s        | 9        | 0.51%   |
| Unknown                                                      | 9        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 8        | 0.46%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 8        | 0.46%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s        | 8        | 0.46%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 8        | 0.46%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 7        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 7        | 0.4%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1600MT/s          | 7        | 0.4%    |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s          | 7        | 0.4%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 7        | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 6        | 0.34%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s        | 6        | 0.34%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 6        | 0.34%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s          | 6        | 0.34%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s        | 6        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 6        | 0.34%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s           | 6        | 0.34%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 6        | 0.34%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 5        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 833      | 58.37%  |
| DDR3    | 402      | 28.17%  |
| Unknown | 79       | 5.54%   |
| DDR2    | 41       | 2.87%   |
| SDRAM   | 38       | 2.66%   |
| DDR5    | 13       | 0.91%   |
| DDR     | 12       | 0.84%   |
| LPDDR4  | 7        | 0.49%   |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1374     | 97.38%  |
| SODIMM  | 32       | 2.27%   |
| FB-DIMM | 3        | 0.21%   |
| RIMM    | 2        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 687      | 44.47%  |
| 4096  | 317      | 20.52%  |
| 16384 | 282      | 18.25%  |
| 2048  | 142      | 9.19%   |
| 32768 | 72       | 4.66%   |
| 1024  | 40       | 2.59%   |
| 512   | 4        | 0.26%   |
| 3072  | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 226      | 14.25%  |
| 3200    | 198      | 12.48%  |
| 3600    | 168      | 10.59%  |
| 1333    | 141      | 8.89%   |
| 2400    | 93       | 5.86%   |
| 2133    | 71       | 4.48%   |
| 2667    | 68       | 4.29%   |
| 3466    | 57       | 3.59%   |
| 3400    | 56       | 3.53%   |
| 1867    | 52       | 3.28%   |
| 3000    | 50       | 3.15%   |
| 800     | 44       | 2.77%   |
| 3800    | 31       | 1.95%   |
| 1866    | 30       | 1.89%   |
| 667     | 28       | 1.77%   |
| 3866    | 26       | 1.64%   |
| 3733    | 25       | 1.58%   |
| 2933    | 18       | 1.13%   |
| 3266    | 16       | 1.01%   |
| Unknown | 16       | 1.01%   |
| 2666    | 15       | 0.95%   |
| 2800    | 14       | 0.88%   |
| 1066    | 14       | 0.88%   |
| 1800    | 11       | 0.69%   |
| 3666    | 10       | 0.63%   |
| 4800    | 8        | 0.5%    |
| 3334    | 6        | 0.38%   |
| 1334    | 6        | 0.38%   |
| 1067    | 5        | 0.32%   |
| 333     | 5        | 0.32%   |
| 3534    | 4        | 0.25%   |
| 3500    | 4        | 0.25%   |
| 3100    | 4        | 0.25%   |
| 2448    | 4        | 0.25%   |
| 2048    | 4        | 0.25%   |
| 1648    | 4        | 0.25%   |
| 533     | 4        | 0.25%   |
| 400     | 4        | 0.25%   |
| 49926   | 3        | 0.19%   |
| 5200    | 3        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 43       | 40.95%  |
| Brother Industries    | 20       | 19.05%  |
| Canon                 | 12       | 11.43%  |
| Seiko Epson           | 6        | 5.71%   |
| Samsung Electronics   | 6        | 5.71%   |
| Pantum                | 3        | 2.86%   |
| Apple                 | 3        | 2.86%   |
| Xerox                 | 2        | 1.9%    |
| Ricoh                 | 2        | 1.9%    |
| Prolific Technology   | 2        | 1.9%    |
| STMicroelectronics    | 1        | 0.95%   |
| QinHeng Electronics   | 1        | 0.95%   |
| Oki Data              | 1        | 0.95%   |
| Lexmark International | 1        | 0.95%   |
| Graphtec America      | 1        | 0.95%   |
| Dymo-CoStar           | 1        | 0.95%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 3.77%   |
| HP LaserJet 1300                                          | 3        | 2.83%   |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.83%   |
| Xerox Phaser 3020                                         | 2        | 1.89%   |
| Seiko Epson L120 Series                                   | 2        | 1.89%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.89%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.89%   |
| HP Officejet 2620 series                                  | 2        | 1.89%   |
| HP DeskJet 4530 series                                    | 2        | 1.89%   |
| HP DeskJet 2600 series                                    | 2        | 1.89%   |
| HP DeskJet 2130 series                                    | 2        | 1.89%   |
| HP Color LaserJet Pro M453-4                              | 2        | 1.89%   |
| Canon PIXMA MG2500 Series                                 | 2        | 1.89%   |
| Canon MG5700 series                                       | 2        | 1.89%   |
| Brother HL-5370DW series                                  | 2        | 1.89%   |
| Brother DCP-7040                                          | 2        | 1.89%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.94%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.94%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.94%   |
| Seiko Epson L805 Series                                   | 1        | 0.94%   |
| Seiko Epson ET-4760 Series                                | 1        | 0.94%   |
| Seiko Epson ET-3850 Series                                | 1        | 0.94%   |
| Samsung ML-1660 Series                                    | 1        | 0.94%   |
| Samsung M2020 Series                                      | 1        | 0.94%   |
| Samsung CLX-3300 Series                                   | 1        | 0.94%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.94%   |
| Ricoh SP 112SU                                            | 1        | 0.94%   |
| Ricoh Printing Support                                    | 1        | 0.94%   |
| QinHeng CH340S                                            | 1        | 0.94%   |
| Pantum P2500W series                                      | 1        | 0.94%   |
| Pantum P2200 series                                       | 1        | 0.94%   |
| Pantum M6500 series                                       | 1        | 0.94%   |
| Oki Data USB Device                                       | 1        | 0.94%   |
| Lexmark International Lexmark MS312dn                     | 1        | 0.94%   |
| HP Smart Install                                          | 1        | 0.94%   |
| HP OfficeJet Pro 8020 series                              | 1        | 0.94%   |
| HP LaserJet P2015 series                                  | 1        | 0.94%   |
| HP Laserjet P1505                                         | 1        | 0.94%   |
| HP LaserJet P1005                                         | 1        | 0.94%   |
| HP LaserJet 3020                                          | 1        | 0.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 12       | 52.17%  |
| Seiko Epson        | 5        | 21.74%  |
| Hewlett-Packard    | 2        | 8.7%    |
| Visioneer          | 1        | 4.35%   |
| Ultima Electronics | 1        | 4.35%   |
| Mustek Systems     | 1        | 4.35%   |
| AGFA-Gevaert NV    | 1        | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 17.39%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.04%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 8.7%    |
| Canon CanoScan LIDE 25                                                                | 2        | 8.7%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.35%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.35%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.35%   |
| HP ScanJet 3500c                                                                      | 1        | 4.35%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.35%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                                               | 1        | 4.35%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.35%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 236      | 41.55%  |
| Microsoft                     | 47       | 8.27%   |
| Microdia                      | 44       | 7.75%   |
| Samsung Electronics           | 23       | 4.05%   |
| Z-Star Microelectronics       | 19       | 3.35%   |
| Sunplus Innovation Technology | 13       | 2.29%   |
| Creative Technology           | 12       | 2.11%   |
| Apple                         | 10       | 1.76%   |
| Generalplus Technology        | 8        | 1.41%   |
| GEMBIRD                       | 8        | 1.41%   |
| Realtek Semiconductor         | 7        | 1.23%   |
| MacroSilicon                  | 7        | 1.23%   |
| Cubeternet                    | 7        | 1.23%   |
| LG Electronics                | 6        | 1.06%   |
| Google                        | 6        | 1.06%   |
| Chicony Electronics           | 6        | 1.06%   |
| ARC International             | 6        | 1.06%   |
| Valve Software                | 5        | 0.88%   |
| Aveo Technology               | 5        | 0.88%   |
| Pixart Imaging                | 4        | 0.7%    |
| KYE Systems (Mouse Systems)   | 4        | 0.7%    |
| Jieli Technology              | 4        | 0.7%    |
| Genesys Logic                 | 4        | 0.7%    |
| Alcor Micro                   | 4        | 0.7%    |
| Xiongmai                      | 3        | 0.53%   |
| webcam                        | 3        | 0.53%   |
| WCM_USB                       | 3        | 0.53%   |
| Sonix Technology              | 3        | 0.53%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.53%   |
| Razer USA                     | 3        | 0.53%   |
| Huawei Technologies           | 3        | 0.53%   |
| AVerMedia Technologies        | 3        | 0.53%   |
| Arkmicro Technologies         | 3        | 0.53%   |
| Xiaomi                        | 2        | 0.35%   |
| WaveRider Communications      | 2        | 0.35%   |
| SunplusIT                     | 2        | 0.35%   |
| Silicon Motion                | 2        | 0.35%   |
| Philips (or NXP)              | 2        | 0.35%   |
| OPPO Electronics              | 2        | 0.35%   |
| Linux Foundation              | 2        | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 58       | 10.18%  |
| Logitech HD Pro Webcam C920                           | 42       | 7.37%   |
| Samsung Galaxy A5 (MTP)                               | 23       | 4.04%   |
| Microsoft LifeCam HD-3000                             | 21       | 3.68%   |
| Logitech C922 Pro Stream Webcam                       | 18       | 3.16%   |
| Microdia Webcam Vitade AF                             | 16       | 2.81%   |
| Microdia USB 2.0 Camera                               | 14       | 2.46%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.93%   |
| Logitech Webcam C310                                  | 11       | 1.93%   |
| Logitech HD Webcam C615                               | 9        | 1.58%   |
| Logitech Webcam C170                                  | 8        | 1.4%    |
| Logitech HD Webcam C525                               | 8        | 1.4%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 8        | 1.4%    |
| MacroSilicon USB Video                                | 7        | 1.23%   |
| Logitech Webcam C930e                                 | 7        | 1.23%   |
| Logitech C920 PRO HD Webcam                           | 7        | 1.23%   |
| Logitech BRIO Ultra HD Webcam                         | 7        | 1.23%   |
| Sunplus WEMISS CM-A1                                  | 6        | 1.05%   |
| Microsoft LifeCam VX-2000                             | 6        | 1.05%   |
| Logitech StreamCam                                    | 6        | 1.05%   |
| Valve Software 3D Camera                              | 5        | 0.88%   |
| Logitech Webcam Pro 9000                              | 5        | 0.88%   |
| Logitech HD Webcam C910                               | 5        | 0.88%   |
| Logitech HD Webcam C510                               | 5        | 0.88%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.88%   |
| GEMBIRD USB2.0 PC CAMERA                              | 5        | 0.88%   |
| ARC International Camera                              | 5        | 0.88%   |
| Sunplus Full HD webcam                                | 4        | 0.7%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.7%    |
| Microsoft LifeCam Cinema                              | 4        | 0.7%    |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.7%    |
| Logitech B525 HD Webcam                               | 4        | 0.7%    |
| Jieli USB PHY 2.0                                     | 4        | 0.7%    |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.7%    |
| Generalplus GENERAL WEBCAM                            | 4        | 0.7%    |
| Generalplus 808 Camera #9 (web-cam mode)              | 4        | 0.7%    |
| Creative Live! Cam Chat HD [VF0700]                   | 4        | 0.7%    |
| Z-Star Vimicro USB Camera (Altair)                    | 3        | 0.53%   |
| Xiongmai web camera                                   | 3        | 0.53%   |
| webcam webcam                                         | 3        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| STMicroelectronics    | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Futronic Technology   | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| STMicroelectronics Fingerprint Reader       | 1        | 14.29%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 14.29%  |
| AuthenTec AES1600                           | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 21.74%  |
| Alcor Micro                       | 5        | 21.74%  |
| VASCO Data Security International | 4        | 17.39%  |
| Realtek Semiconductor             | 4        | 17.39%  |
| OmniKey                           | 2        | 8.7%    |
| SCM Microsystems                  | 1        | 4.35%   |
| Cherry                            | 1        | 4.35%   |
| BIT4ID                            | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 21.74%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 17.39%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 17.39%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8.7%    |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8.7%    |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.35%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.35%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.35%   |
| BIT4ID miniLector EVO                                           | 1        | 4.35%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2126     | 85.83%  |
| 1     | 315      | 12.72%  |
| 2     | 33       | 1.33%   |
| 3     | 3        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 148      | 39.89%  |
| Graphics card            | 51       | 13.75%  |
| Unassigned class         | 50       | 13.48%  |
| Camera                   | 20       | 5.39%   |
| Chipcard                 | 15       | 4.04%   |
| Net/ethernet             | 12       | 3.23%   |
| Multimedia controller    | 12       | 3.23%   |
| Sound                    | 11       | 2.96%   |
| Communication controller | 11       | 2.96%   |
| Bluetooth                | 10       | 2.7%    |
| Dvb card                 | 9        | 2.43%   |
| Storage/raid             | 6        | 1.62%   |
| Fingerprint reader       | 6        | 1.62%   |
| Network                  | 5        | 1.35%   |
| Storage/ide              | 2        | 0.54%   |
| Video                    | 1        | 0.27%   |
| Storage/ata              | 1        | 0.27%   |
| Storage                  | 1        | 0.27%   |

