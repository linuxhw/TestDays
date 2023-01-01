Linux in Brazil - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 6225

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Z390-PRO GAMING         | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Dell          | 0VR8V9 A01                  | [0e7d4ac326](https://linux-hardware.org/?probe=0e7d4ac326) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| ASRock        | B360M Performance           | [679d25f9be](https://linux-hardware.org/?probe=679d25f9be) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [83608f4248](https://linux-hardware.org/?probe=83608f4248) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | [8658fa0fa3](https://linux-hardware.org/?probe=8658fa0fa3) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | [cf7ba71c5e](https://linux-hardware.org/?probe=cf7ba71c5e) | Dec 27, 2022 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | [868a87a1f8](https://linux-hardware.org/?probe=868a87a1f8) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e12a45a65f](https://linux-hardware.org/?probe=e12a45a65f) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [4f28247dcb](https://linux-hardware.org/?probe=4f28247dcb) | Dec 25, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [d66db29328](https://linux-hardware.org/?probe=d66db29328) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [27612d2f72](https://linux-hardware.org/?probe=27612d2f72) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [2979740651](https://linux-hardware.org/?probe=2979740651) | Dec 24, 2022 |
| ASRock        | A320M-HD                    | [5307c53c91](https://linux-hardware.org/?probe=5307c53c91) | Dec 22, 2022 |
| PERTOSA       | IPMSBA                      | [8cd4fff2ce](https://linux-hardware.org/?probe=8cd4fff2ce) | Dec 22, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Intel         | X99 V1.0                    | [20c96ed6dd](https://linux-hardware.org/?probe=20c96ed6dd) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Intel         | B75                         | [368e71afd7](https://linux-hardware.org/?probe=368e71afd7) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| Gigabyte      | F2A68HM-H                   | [79cf1b618f](https://linux-hardware.org/?probe=79cf1b618f) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [533bf9eafc](https://linux-hardware.org/?probe=533bf9eafc) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [6870f7c47f](https://linux-hardware.org/?probe=6870f7c47f) | Dec 18, 2022 |
| Intel         | HM570                       | [627a39bc3f](https://linux-hardware.org/?probe=627a39bc3f) | Dec 18, 2022 |
| Intel         | HM570                       | [303e68f585](https://linux-hardware.org/?probe=303e68f585) | Dec 18, 2022 |
| Dell          | 0UY894 A02                  | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| ASRock        | 960GC-GS FX                 | [a61b5c0129](https://linux-hardware.org/?probe=a61b5c0129) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Biostar       | X470GTN                     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| Intel         | H55                         | [c034f3b3db](https://linux-hardware.org/?probe=c034f3b3db) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| Pegatron      | IPM41-D3                    | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [6bd184b75a](https://linux-hardware.org/?probe=6bd184b75a) | Dec 15, 2022 |
| Biostar       | B460GTQ                     | [7f3836bddf](https://linux-hardware.org/?probe=7f3836bddf) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [bed03c8f85](https://linux-hardware.org/?probe=bed03c8f85) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d6244def87](https://linux-hardware.org/?probe=d6244def87) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| ASUSTek       | M4N78 SE                    | [e37cb274ff](https://linux-hardware.org/?probe=e37cb274ff) | Dec 14, 2022 |
| Gigabyte      | B75M-D3H                    | [f522fb6cbd](https://linux-hardware.org/?probe=f522fb6cbd) | Dec 13, 2022 |
| Gigabyte      | B75M-D3H                    | [4de5804244](https://linux-hardware.org/?probe=4de5804244) | Dec 13, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [70506a428c](https://linux-hardware.org/?probe=70506a428c) | Dec 13, 2022 |
| PCWare        | IPMH110G                    | [baa0f26af0](https://linux-hardware.org/?probe=baa0f26af0) | Dec 13, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Dell          | 042P49 A01                  | [fc5be35686](https://linux-hardware.org/?probe=fc5be35686) | Dec 12, 2022 |
| ASUSTek       | SABERTOOTH X99              | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| Braview       | BRW-BSWI-D2                 | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [dcd96a2b45](https://linux-hardware.org/?probe=dcd96a2b45) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [9f9fafa75b](https://linux-hardware.org/?probe=9f9fafa75b) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| Intel         | DX58SO AAE29331-702         | [685274600b](https://linux-hardware.org/?probe=685274600b) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a64decb842](https://linux-hardware.org/?probe=a64decb842) | Dec 10, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [830ec0e7be](https://linux-hardware.org/?probe=830ec0e7be) | Dec 10, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [62779a600c](https://linux-hardware.org/?probe=62779a600c) | Dec 09, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [ac8d321e9a](https://linux-hardware.org/?probe=ac8d321e9a) | Dec 09, 2022 |
| ASRock        | A320M-HD                    | [aea1c7da95](https://linux-hardware.org/?probe=aea1c7da95) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [b1ac2fbabe](https://linux-hardware.org/?probe=b1ac2fbabe) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| PCWare        | IPMH61R3                    | [d216c11fea](https://linux-hardware.org/?probe=d216c11fea) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| Unknown       | PCWARE APMCP68              | [bf85f27d83](https://linux-hardware.org/?probe=bf85f27d83) | Dec 07, 2022 |
| Gigabyte      | B75M-D3H                    | [33472ea902](https://linux-hardware.org/?probe=33472ea902) | Dec 06, 2022 |
| Gigabyte      | B75M-D3H                    | [f4f7580aff](https://linux-hardware.org/?probe=f4f7580aff) | Dec 06, 2022 |
| HP            | 3397                        | [efcd9d806e](https://linux-hardware.org/?probe=efcd9d806e) | Dec 06, 2022 |
| Dell          | 0HN7XN A01                  | [72203965d8](https://linux-hardware.org/?probe=72203965d8) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [97595fe5a1](https://linux-hardware.org/?probe=97595fe5a1) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| PCWare        | IPMH110G                    | [0574aeace9](https://linux-hardware.org/?probe=0574aeace9) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| MSI           | MAG B550M MORTAR            | [ad81cbb6e4](https://linux-hardware.org/?probe=ad81cbb6e4) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | 2A9C                        | [d7b2898f42](https://linux-hardware.org/?probe=d7b2898f42) | Dec 03, 2022 |
| Intel         | H61                         | [4050e46b94](https://linux-hardware.org/?probe=4050e46b94) | Dec 03, 2022 |
| MSI           | 2A9C                        | [52ab7bcdde](https://linux-hardware.org/?probe=52ab7bcdde) | Dec 03, 2022 |
| Unknown       | DH61BR G32662-203           | [c22d1caae4](https://linux-hardware.org/?probe=c22d1caae4) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| Intel         | X99                         | [bd1d84cf82](https://linux-hardware.org/?probe=bd1d84cf82) | Dec 02, 2022 |
| Intel         | X99                         | [4051f684d8](https://linux-hardware.org/?probe=4051f684d8) | Dec 02, 2022 |
| ABIT          | I-45CV                      | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| Lenovo        | 3102 NOK                    | [8bfdcedec6](https://linux-hardware.org/?probe=8bfdcedec6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7ff54a3b05](https://linux-hardware.org/?probe=7ff54a3b05) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | [ef8cb053dc](https://linux-hardware.org/?probe=ef8cb053dc) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | [9831bd75b9](https://linux-hardware.org/?probe=9831bd75b9) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Intel         | H61                         | [42f943bc9c](https://linux-hardware.org/?probe=42f943bc9c) | Nov 28, 2022 |
| PCWare        | IPMH61R1                    | [7872d8f10f](https://linux-hardware.org/?probe=7872d8f10f) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| AMD           | 58514                       | [7558bc36a0](https://linux-hardware.org/?probe=7558bc36a0) | Nov 27, 2022 |
| ASUSTek       | H81M-K                      | [4de72d3d12](https://linux-hardware.org/?probe=4de72d3d12) | Nov 26, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| ASUSTek       | B150M-C                     | [bbbdc2b291](https://linux-hardware.org/?probe=bbbdc2b291) | Nov 26, 2022 |
| Unknown       | PCWARE APMCP68              | [0cb03d53bb](https://linux-hardware.org/?probe=0cb03d53bb) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Intel         | Unknown                     | [bcf46201bc](https://linux-hardware.org/?probe=bcf46201bc) | Nov 25, 2022 |
| ASRock        | B460M-HDV                   | [00c07e7aa9](https://linux-hardware.org/?probe=00c07e7aa9) | Nov 25, 2022 |
| Intel         | H61                         | [76825e4753](https://linux-hardware.org/?probe=76825e4753) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Positivo      | P5VD2-MX                    | [c9d4c5ea2b](https://linux-hardware.org/?probe=c9d4c5ea2b) | Nov 25, 2022 |
| ASUSTek       | J1800I-C/BR                 | [9cfe40fa0b](https://linux-hardware.org/?probe=9cfe40fa0b) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| PCWare        | APM-A320G                   | [a56cdcbd3b](https://linux-hardware.org/?probe=a56cdcbd3b) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| HP            | 0266                        | [13e2e10478](https://linux-hardware.org/?probe=13e2e10478) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| Intel         | B75                         | [24b64d225a](https://linux-hardware.org/?probe=24b64d225a) | Nov 22, 2022 |
| PCWare        | IPMH61R2                    | [93db11744b](https://linux-hardware.org/?probe=93db11744b) | Nov 22, 2022 |
| PCWare        | IPMH110G                    | [7d952c2b0d](https://linux-hardware.org/?probe=7d952c2b0d) | Nov 22, 2022 |
| Biostar       | A320MH                      | [79eeacd665](https://linux-hardware.org/?probe=79eeacd665) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [4599b81a6b](https://linux-hardware.org/?probe=4599b81a6b) | Nov 21, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [93bb909388](https://linux-hardware.org/?probe=93bb909388) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| MSI           | H61M-P21                    | [a91ee7dc9d](https://linux-hardware.org/?probe=a91ee7dc9d) | Nov 19, 2022 |
| ASUSTek       | P8H61-M PLUS V2             | [ff279b1860](https://linux-hardware.org/?probe=ff279b1860) | Nov 18, 2022 |
| Dell          | 0KWVT8 A02                  | [e1b586a15a](https://linux-hardware.org/?probe=e1b586a15a) | Nov 18, 2022 |
| Gigabyte      | G31M-S2L                    | [bc588177c4](https://linux-hardware.org/?probe=bc588177c4) | Nov 18, 2022 |
| AMD           | A88                         | [4f23ffbfe2](https://linux-hardware.org/?probe=4f23ffbfe2) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| PCWare        | IPX4005G                    | [9989340108](https://linux-hardware.org/?probe=9989340108) | Nov 17, 2022 |
| Login Info... | LOG-H61H2-M2                | [aff41de38e](https://linux-hardware.org/?probe=aff41de38e) | Nov 17, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| Dell          | 0RW199                      | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e7f05e6eac](https://linux-hardware.org/?probe=e7f05e6eac) | Nov 15, 2022 |
| Huanan        | X99-F8                      | [0e3b4121ea](https://linux-hardware.org/?probe=0e3b4121ea) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [62348f8b41](https://linux-hardware.org/?probe=62348f8b41) | Nov 13, 2022 |
| PCWare        | IPMH61R3                    | [7b7925f93d](https://linux-hardware.org/?probe=7b7925f93d) | Nov 13, 2022 |
| ASUSTek       | TUF B360-PLUS GAMING        | [d29245dafc](https://linux-hardware.org/?probe=d29245dafc) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Intel         | H55                         | [b3cbb34a98](https://linux-hardware.org/?probe=b3cbb34a98) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Intel         | H55                         | [c4171c6957](https://linux-hardware.org/?probe=c4171c6957) | Nov 12, 2022 |
| Colorful T... | DJ H310M-E V20              | [6ac470070c](https://linux-hardware.org/?probe=6ac470070c) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Intel         | H61                         | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [13f37888d5](https://linux-hardware.org/?probe=13f37888d5) | Nov 11, 2022 |
| Intel         | DG41WV AAE90316-102         | [517598326a](https://linux-hardware.org/?probe=517598326a) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [f20eddfba9](https://linux-hardware.org/?probe=f20eddfba9) | Nov 10, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
| PCWare        | IPMH61R1                    | [6a668c9151](https://linux-hardware.org/?probe=6a668c9151) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [3e90cd2d25](https://linux-hardware.org/?probe=3e90cd2d25) | Nov 09, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [f2841b0f4d](https://linux-hardware.org/?probe=f2841b0f4d) | Nov 08, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [3ffeeccb58](https://linux-hardware.org/?probe=3ffeeccb58) | Nov 08, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [58cb07d7e1](https://linux-hardware.org/?probe=58cb07d7e1) | Nov 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | [533c6216c7](https://linux-hardware.org/?probe=533c6216c7) | Nov 08, 2022 |
| Intel         | H61                         | [67af788bd9](https://linux-hardware.org/?probe=67af788bd9) | Nov 08, 2022 |
| ASRock        | H81M-HG4 R4.0               | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Dell          | 0GDG8Y A02                  | [e61ccb96d0](https://linux-hardware.org/?probe=e61ccb96d0) | Nov 06, 2022 |
| PCWare        | IPMH110G                    | [3409bf9968](https://linux-hardware.org/?probe=3409bf9968) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | [185fcc2c4f](https://linux-hardware.org/?probe=185fcc2c4f) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | [7d038a7549](https://linux-hardware.org/?probe=7d038a7549) | Nov 06, 2022 |
| Huanan        | X99-F8D PLUS V1.1           | [a552bf9362](https://linux-hardware.org/?probe=a552bf9362) | Nov 06, 2022 |
| MSI           | Z170A SLI PLUS              | [f9b39389e6](https://linux-hardware.org/?probe=f9b39389e6) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [0f6ca0628c](https://linux-hardware.org/?probe=0f6ca0628c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [31234e156e](https://linux-hardware.org/?probe=31234e156e) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [787df838b7](https://linux-hardware.org/?probe=787df838b7) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [0081f15a32](https://linux-hardware.org/?probe=0081f15a32) | Nov 03, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [0f369008f6](https://linux-hardware.org/?probe=0f369008f6) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
| Gigabyte      | H81M-S1                     | [fa134687f2](https://linux-hardware.org/?probe=fa134687f2) | Nov 03, 2022 |
| Lenovo        | NOK                         | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [df76e744d7](https://linux-hardware.org/?probe=df76e744d7) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | H61M-P31                    | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| VS Company    | G31T-M                      | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Pegatron      | 2AABh                       | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| ASRock        | H510M-HVS                   | [e9ce2f5011](https://linux-hardware.org/?probe=e9ce2f5011) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | [e377db3a9e](https://linux-hardware.org/?probe=e377db3a9e) | Oct 28, 2022 |
| Lenovo        | 3102 NOK                    | [973ebfcf3e](https://linux-hardware.org/?probe=973ebfcf3e) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Intel         | H55                         | [fb3cf518ac](https://linux-hardware.org/?probe=fb3cf518ac) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P7H57D-V EVO                | [785405287b](https://linux-hardware.org/?probe=785405287b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| Toshiba       | STI 005492G                 | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| ASRock        | H61M-VG4                    | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [31cae2266e](https://linux-hardware.org/?probe=31cae2266e) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4540d714bc](https://linux-hardware.org/?probe=4540d714bc) | Oct 24, 2022 |
| Biostar       | A320MH                      | [b38eca2979](https://linux-hardware.org/?probe=b38eca2979) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| ASRock        | H81M-HG4 R4.0               | [da9c01eb20](https://linux-hardware.org/?probe=da9c01eb20) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2P                   | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| ASUSTek       | H81M-A/BR                   | [462091e8a8](https://linux-hardware.org/?probe=462091e8a8) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| Dell          | 0YXT71 A02                  | [137e154b2d](https://linux-hardware.org/?probe=137e154b2d) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [d46ae4e597](https://linux-hardware.org/?probe=d46ae4e597) | Oct 19, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c395183020](https://linux-hardware.org/?probe=c395183020) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [e57ed46372](https://linux-hardware.org/?probe=e57ed46372) | Oct 19, 2022 |
| Dell          | 0XJ8C4 A00                  | [83da6e6509](https://linux-hardware.org/?probe=83da6e6509) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [d9b4d01e7f](https://linux-hardware.org/?probe=d9b4d01e7f) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| ASRock        | B450M Steel Legend          | [6718ea22a9](https://linux-hardware.org/?probe=6718ea22a9) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| PCWare        | IPMH110G                    | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Pegatron      | 2AD2A                       | [01827879c5](https://linux-hardware.org/?probe=01827879c5) | Oct 13, 2022 |
| ASRock        | N68-VS3 FX                  | [b271788734](https://linux-hardware.org/?probe=b271788734) | Oct 12, 2022 |
| Gigabyte      | 945GCM-S2C                  | [d0fe56248f](https://linux-hardware.org/?probe=d0fe56248f) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| PCWare        | IPMH110G                    | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| Unknown       | Unknown                     | [3414f3f4c0](https://linux-hardware.org/?probe=3414f3f4c0) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Intel         | DH67CL AAG10212-206         | [01ebc77ef1](https://linux-hardware.org/?probe=01ebc77ef1) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0085d792fd](https://linux-hardware.org/?probe=0085d792fd) | Oct 07, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Intel         | B75                         | [a15b4ede9b](https://linux-hardware.org/?probe=a15b4ede9b) | Oct 05, 2022 |
| HP            | 2AA2                        | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Intel         | X99 V1.0                    | [d96984ac77](https://linux-hardware.org/?probe=d96984ac77) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| ASUSTek       | A78M-A                      | [91434dfd86](https://linux-hardware.org/?probe=91434dfd86) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Positivo      | POS-PIH81DL                 | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| ASUSTek       | A78M-A                      | [5ad2e5f2a6](https://linux-hardware.org/?probe=5ad2e5f2a6) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | A320MH                      | [b07b6c4fc5](https://linux-hardware.org/?probe=b07b6c4fc5) | Oct 01, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Intel         | H61                         | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [2c08befa41](https://linux-hardware.org/?probe=2c08befa41) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [5cdce489b9](https://linux-hardware.org/?probe=5cdce489b9) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [3bfbb3744e](https://linux-hardware.org/?probe=3bfbb3744e) | Sep 30, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| Intel         | H55                         | [a155052bce](https://linux-hardware.org/?probe=a155052bce) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | P7H55-M LX                  | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Gigabyte      | 970A-DS3P                   | [1e9a7dd793](https://linux-hardware.org/?probe=1e9a7dd793) | Sep 24, 2022 |
| ASUSTek       | M2N68                       | [4b23dadbca](https://linux-hardware.org/?probe=4b23dadbca) | Sep 23, 2022 |
| Foxconn       | Q77M                        | [63d0fe0c57](https://linux-hardware.org/?probe=63d0fe0c57) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASRock        | G31M-S                      | [76d9b33c76](https://linux-hardware.org/?probe=76d9b33c76) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [fef79bcff4](https://linux-hardware.org/?probe=fef79bcff4) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| Intel         | DN2800MT AAG23738-801       | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | 0D883F A06                  | [55f97310c8](https://linux-hardware.org/?probe=55f97310c8) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| MSI           | A68HM-E33                   | [2905913e7e](https://linux-hardware.org/?probe=2905913e7e) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| ASUSTek       | M4A785-M                    | [411449bc6d](https://linux-hardware.org/?probe=411449bc6d) | Sep 18, 2022 |
| Intel         | H61                         | [923e50e023](https://linux-hardware.org/?probe=923e50e023) | Sep 18, 2022 |
| MSI           | J1800I                      | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| Intel         | X79M-S                      | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| Intel         | X79M-S                      | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Intel         | H61                         | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Unknown       | Unknown                     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME B350M-A               | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| Positivo      | POS-PQ45AU                  | [0879f8d9ce](https://linux-hardware.org/?probe=0879f8d9ce) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| PCWare        | IPMH61R3                    | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| Intel         | H61                         | [d805e24841](https://linux-hardware.org/?probe=d805e24841) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [aa4d90c7e7](https://linux-hardware.org/?probe=aa4d90c7e7) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| Intel         | Unknown                     | [74059aa424](https://linux-hardware.org/?probe=74059aa424) | Sep 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [944fa39fb6](https://linux-hardware.org/?probe=944fa39fb6) | Sep 09, 2022 |
| Intel         | X79G V2.x                   | [8efdbea978](https://linux-hardware.org/?probe=8efdbea978) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [c716a6bba5](https://linux-hardware.org/?probe=c716a6bba5) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [4942b09228](https://linux-hardware.org/?probe=4942b09228) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Biostar       | G41D3C                      | [2825db69bf](https://linux-hardware.org/?probe=2825db69bf) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [f547e07cca](https://linux-hardware.org/?probe=f547e07cca) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [b1bdd1703e](https://linux-hardware.org/?probe=b1bdd1703e) | Sep 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f61f170b4c](https://linux-hardware.org/?probe=f61f170b4c) | Sep 06, 2022 |
| Intel         | H61                         | [b2d888f266](https://linux-hardware.org/?probe=b2d888f266) | Sep 05, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [078680a25d](https://linux-hardware.org/?probe=078680a25d) | Sep 04, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Intel         | H61                         | [af78b53f51](https://linux-hardware.org/?probe=af78b53f51) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ECS           | H61H2-M2                    | [11dd923e56](https://linux-hardware.org/?probe=11dd923e56) | Sep 02, 2022 |
| Intel         | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| AMI           | T3 MRD                      | [d0a254e1b7](https://linux-hardware.org/?probe=d0a254e1b7) | Sep 02, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [9525064f53](https://linux-hardware.org/?probe=9525064f53) | Sep 02, 2022 |
| Lenovo        | 3168 NOK                    | [58c82b01e2](https://linux-hardware.org/?probe=58c82b01e2) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-S1                  | [420036f4d6](https://linux-hardware.org/?probe=420036f4d6) | Aug 28, 2022 |
| MSI           | B560M PRO-VDH               | [d8a638184b](https://linux-hardware.org/?probe=d8a638184b) | Aug 28, 2022 |
| Intel         | H61                         | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| MSI           | B560M PRO-VDH               | [437118237f](https://linux-hardware.org/?probe=437118237f) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| HP            | 3397                        | [f65d0fdb85](https://linux-hardware.org/?probe=f65d0fdb85) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| AMI           | Cherry Trail Tablet         | [8cdf70d6e3](https://linux-hardware.org/?probe=8cdf70d6e3) | Aug 23, 2022 |
| ASUSTek       | P5KPL-CM                    | [53a4b425d3](https://linux-hardware.org/?probe=53a4b425d3) | Aug 22, 2022 |
| ASUSTek       | PRIME H410M-E               | [5270930555](https://linux-hardware.org/?probe=5270930555) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASRock        | X370 Taichi                 | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Biostar       | G31-M7 TE                   | [aaacebef4a](https://linux-hardware.org/?probe=aaacebef4a) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Gigabyte      | B75M-D3H                    | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [2e1445b2c8](https://linux-hardware.org/?probe=2e1445b2c8) | Aug 19, 2022 |
| Dell          | 0TVR1F A01                  | [1b8906bb20](https://linux-hardware.org/?probe=1b8906bb20) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Arquimedes... | 760GM                       | [5f653afdff](https://linux-hardware.org/?probe=5f653afdff) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4242f8b9c2](https://linux-hardware.org/?probe=4242f8b9c2) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [bac870dd75](https://linux-hardware.org/?probe=bac870dd75) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [52b9313de4](https://linux-hardware.org/?probe=52b9313de4) | Aug 18, 2022 |
| Intel         | Unknown                     | [23f3bdae8a](https://linux-hardware.org/?probe=23f3bdae8a) | Aug 18, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| ASRock        | AB350M-HDV                  | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Intel         | B75                         | [8eb918ea53](https://linux-hardware.org/?probe=8eb918ea53) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| ASRock        | FM2A55M-HD+                 | [dc086ed32c](https://linux-hardware.org/?probe=dc086ed32c) | Aug 14, 2022 |
| ASUSTek       | P8H61-M LX3                 | [7c37c2a6d7](https://linux-hardware.org/?probe=7c37c2a6d7) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | [6c7f56d3cd](https://linux-hardware.org/?probe=6c7f56d3cd) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [4443a6c129](https://linux-hardware.org/?probe=4443a6c129) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [082a5297bd](https://linux-hardware.org/?probe=082a5297bd) | Aug 14, 2022 |
| Gigabyte      | Z77M-D3H                    | [15633ed7b1](https://linux-hardware.org/?probe=15633ed7b1) | Aug 14, 2022 |
| Biostar       | G31-M7 TE                   | [c5737e52bd](https://linux-hardware.org/?probe=c5737e52bd) | Aug 14, 2022 |
| ASUSTek       | Z97-A                       | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [f17b91fcb8](https://linux-hardware.org/?probe=f17b91fcb8) | Aug 13, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [98cc4a3075](https://linux-hardware.org/?probe=98cc4a3075) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| MSI           | X370 SLI PLUS               | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| Foxconn       | 2ADA                        | [9aae49b54c](https://linux-hardware.org/?probe=9aae49b54c) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [c66de39c4c](https://linux-hardware.org/?probe=c66de39c4c) | Aug 11, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [d081204e0a](https://linux-hardware.org/?probe=d081204e0a) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e54e09e3cf](https://linux-hardware.org/?probe=e54e09e3cf) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a84fd5a16](https://linux-hardware.org/?probe=5a84fd5a16) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [aada9001dd](https://linux-hardware.org/?probe=aada9001dd) | Aug 08, 2022 |
| HP            | 1998                        | [1ae818eb7c](https://linux-hardware.org/?probe=1ae818eb7c) | Aug 07, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| PCWare        | IPX3060E                    | [3fc0886f3b](https://linux-hardware.org/?probe=3fc0886f3b) | Aug 06, 2022 |
| Gigabyte      | F2A55M-S1                   | [cf3ed2131f](https://linux-hardware.org/?probe=cf3ed2131f) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| PCWare        | IPX3060E                    | [d5045f1364](https://linux-hardware.org/?probe=d5045f1364) | Aug 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [2030bc92d7](https://linux-hardware.org/?probe=2030bc92d7) | Aug 04, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Biostar       | G41D3C                      | [8a5b81e472](https://linux-hardware.org/?probe=8a5b81e472) | Aug 03, 2022 |
| HP            | 3047h                       | [a8301b8155](https://linux-hardware.org/?probe=a8301b8155) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| PCWare        | IPMH61R1                    | [0843909534](https://linux-hardware.org/?probe=0843909534) | Aug 01, 2022 |
| PCWare        | IPMH61R1                    | [7da7204a12](https://linux-hardware.org/?probe=7da7204a12) | Jul 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [16f64b6f1a](https://linux-hardware.org/?probe=16f64b6f1a) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ECS           | H61H2-M12                   | [6761a8774d](https://linux-hardware.org/?probe=6761a8774d) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f6ecfb2a51](https://linux-hardware.org/?probe=f6ecfb2a51) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [3249abb411](https://linux-hardware.org/?probe=3249abb411) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7ceff6f032](https://linux-hardware.org/?probe=7ceff6f032) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [5a750a1294](https://linux-hardware.org/?probe=5a750a1294) | Jul 30, 2022 |
| HP            | 3047h                       | [a9b59b34f9](https://linux-hardware.org/?probe=a9b59b34f9) | Jul 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [8c57fbc9e8](https://linux-hardware.org/?probe=8c57fbc9e8) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [51893f2237](https://linux-hardware.org/?probe=51893f2237) | Jul 29, 2022 |
| Intel         | H61                         | [7bb7deaca9](https://linux-hardware.org/?probe=7bb7deaca9) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Digiboard     | NM70-TI                     | [007a69093c](https://linux-hardware.org/?probe=007a69093c) | Jul 29, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [e84f999c94](https://linux-hardware.org/?probe=e84f999c94) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-GAMING II       | [0cc1bc9401](https://linux-hardware.org/?probe=0cc1bc9401) | Jul 29, 2022 |
| Biostar       | B350GTN                     | [75d6302ab0](https://linux-hardware.org/?probe=75d6302ab0) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| Positivo      | POS-RIB360EE 11158935       | [1c687dcef7](https://linux-hardware.org/?probe=1c687dcef7) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| Intel         | X99 V1.0                    | [da677f5a3b](https://linux-hardware.org/?probe=da677f5a3b) | Jul 28, 2022 |
| Intel         | B75                         | [0620ffff20](https://linux-hardware.org/?probe=0620ffff20) | Jul 27, 2022 |
| MSI           | X470 GAMING PLUS            | [722aa0951d](https://linux-hardware.org/?probe=722aa0951d) | Jul 27, 2022 |
| PCWare        | IPMH61R1                    | [18610dd9f0](https://linux-hardware.org/?probe=18610dd9f0) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| PCWare        | PW-945GCX                   | [128aafe763](https://linux-hardware.org/?probe=128aafe763) | Jul 27, 2022 |
| MSI           | 2A9C                        | [de5a8c7ecd](https://linux-hardware.org/?probe=de5a8c7ecd) | Jul 27, 2022 |
| Dell          | 01XK1W A00                  | [68159d9d39](https://linux-hardware.org/?probe=68159d9d39) | Jul 26, 2022 |
| Huanan        | X99-F8                      | [3ba1885fb4](https://linux-hardware.org/?probe=3ba1885fb4) | Jul 26, 2022 |
| Gigabyte      | Z370N WIFI-CF               | [eb3c3fceb3](https://linux-hardware.org/?probe=eb3c3fceb3) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [e471e3ed10](https://linux-hardware.org/?probe=e471e3ed10) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASRock        | H61M-DGS                    | [0dc55c5b73](https://linux-hardware.org/?probe=0dc55c5b73) | Jul 24, 2022 |
| ASUSTek       | Z87M-PLUS                   | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| Dell          | 01XK1W A00                  | [5c8a6b6f90](https://linux-hardware.org/?probe=5c8a6b6f90) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Dell          | 01XK1W A00                  | [91ce7c78ee](https://linux-hardware.org/?probe=91ce7c78ee) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| ASUSTek       | M2N68                       | [e8b27563a2](https://linux-hardware.org/?probe=e8b27563a2) | Jul 22, 2022 |
| Biostar       | B450MH                      | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2af5596c9e](https://linux-hardware.org/?probe=2af5596c9e) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| PCChips       | A15G                        | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [e0ffe80869](https://linux-hardware.org/?probe=e0ffe80869) | Jul 20, 2022 |
| Intel         | Unknown                     | [19327f830a](https://linux-hardware.org/?probe=19327f830a) | Jul 20, 2022 |
| Positivo      | POS-PIQ77CL                 | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [a6f87d56db](https://linux-hardware.org/?probe=a6f87d56db) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Intel         | Unknown                     | [8c87f55927](https://linux-hardware.org/?probe=8c87f55927) | Jul 19, 2022 |
| ECS           | A990FXM-A                   | [6351c9023d](https://linux-hardware.org/?probe=6351c9023d) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [cd6d617e34](https://linux-hardware.org/?probe=cd6d617e34) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [aaa3013f66](https://linux-hardware.org/?probe=aaa3013f66) | Jul 18, 2022 |
| Intel         | H55                         | [b58f7300e1](https://linux-hardware.org/?probe=b58f7300e1) | Jul 18, 2022 |
| Gigabyte      | H61M-S2PH                   | [554f6e65ed](https://linux-hardware.org/?probe=554f6e65ed) | Jul 18, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| Dell          | 08NPPY A00                  | [23d9101cd2](https://linux-hardware.org/?probe=23d9101cd2) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | [f8585ad958](https://linux-hardware.org/?probe=f8585ad958) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | [f2372286e0](https://linux-hardware.org/?probe=f2372286e0) | Jul 17, 2022 |
| Huanan        | B75                         | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| GALAX         | A320M Ver1.0 G10f           | [7bc0a0fe3a](https://linux-hardware.org/?probe=7bc0a0fe3a) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Dell          | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| Intel         | H61                         | [8865d7959a](https://linux-hardware.org/?probe=8865d7959a) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Intel         | H55                         | [f8e7b20a53](https://linux-hardware.org/?probe=f8e7b20a53) | Jul 14, 2022 |
| ASUSTek       | P8B75-M LE                  | [a4246a1ea8](https://linux-hardware.org/?probe=a4246a1ea8) | Jul 14, 2022 |
| ASUSTek       | M5A97 PRO                   | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| Intel         | H55                         | [b199ed9707](https://linux-hardware.org/?probe=b199ed9707) | Jul 14, 2022 |
| Gigabyte      | Z690 GAMING X               | [7babf837f9](https://linux-hardware.org/?probe=7babf837f9) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [44638b5241](https://linux-hardware.org/?probe=44638b5241) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Positivo      | POS-MI945AA                 | [ab451b5409](https://linux-hardware.org/?probe=ab451b5409) | Jul 11, 2022 |
| ASUSTek       | H81M-A/BR                   | [851a8e12f8](https://linux-hardware.org/?probe=851a8e12f8) | Jul 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [012a999377](https://linux-hardware.org/?probe=012a999377) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8ac6704c06](https://linux-hardware.org/?probe=8ac6704c06) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| PCWare        | IPX4005G                    | [2e447eb751](https://linux-hardware.org/?probe=2e447eb751) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | [a39b9bab73](https://linux-hardware.org/?probe=a39b9bab73) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| MSI           | 2A9C                        | [40457980de](https://linux-hardware.org/?probe=40457980de) | Jul 08, 2022 |
| Positivo      | POS-PIQ77CL                 | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| congatec      | TS170 B.0                   | [b9469e26f8](https://linux-hardware.org/?probe=b9469e26f8) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| ASUSTek       | H110M-E/M.2                 | [cfe354b7b2](https://linux-hardware.org/?probe=cfe354b7b2) | Jul 06, 2022 |
| Positivo      | POS-MIG31AG                 | [3a03195633](https://linux-hardware.org/?probe=3a03195633) | Jul 06, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel         | H61                         | [da6d35599a](https://linux-hardware.org/?probe=da6d35599a) | Jul 04, 2022 |
| HP            | 3048h                       | [a007a37d76](https://linux-hardware.org/?probe=a007a37d76) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| ECS           | H61H2-M12                   | [e450395aeb](https://linux-hardware.org/?probe=e450395aeb) | Jul 04, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [eb89cf02af](https://linux-hardware.org/?probe=eb89cf02af) | Jul 03, 2022 |
| Positivo      | POS-EIH61CE POSITIVO        | [2d040c142f](https://linux-hardware.org/?probe=2d040c142f) | Jul 03, 2022 |
| Positivo      | POS-EIH61CE POSITIVO        | [bc149c173f](https://linux-hardware.org/?probe=bc149c173f) | Jul 03, 2022 |
| ECS           | H61H2-M12                   | [33b81dcd60](https://linux-hardware.org/?probe=33b81dcd60) | Jul 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [a746300279](https://linux-hardware.org/?probe=a746300279) | Jul 03, 2022 |
| ASRock        | N68-VS3 UCC                 | [dd43bf961c](https://linux-hardware.org/?probe=dd43bf961c) | Jul 02, 2022 |
| Pegatron      | IPM41-D3                    | [a7cc8d2654](https://linux-hardware.org/?probe=a7cc8d2654) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [2f0ac248ed](https://linux-hardware.org/?probe=2f0ac248ed) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [5a6d827ebe](https://linux-hardware.org/?probe=5a6d827ebe) | Jul 01, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a40fb66860](https://linux-hardware.org/?probe=a40fb66860) | Jun 30, 2022 |
| ASUSTek       | B85M-E/BR                   | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
| PCWare        | IPMH61R3                    | [492951e8cf](https://linux-hardware.org/?probe=492951e8cf) | Jun 29, 2022 |
| Gigabyte      | H81M-S1                     | [6dfee96211](https://linux-hardware.org/?probe=6dfee96211) | Jun 29, 2022 |
| Intel         | DP43BF AAE78171-302         | [0115160101](https://linux-hardware.org/?probe=0115160101) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a9ddf668c4](https://linux-hardware.org/?probe=a9ddf668c4) | Jun 28, 2022 |
| ASUSTek       | P5KPL-AM                    | [f9a3a492d9](https://linux-hardware.org/?probe=f9a3a492d9) | Jun 27, 2022 |
| Dell          | 0J3C2F A03                  | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| MSI           | H55M-E33                    | [035cfe1a5b](https://linux-hardware.org/?probe=035cfe1a5b) | Jun 26, 2022 |
| Intel         | X99                         | [4322217bc5](https://linux-hardware.org/?probe=4322217bc5) | Jun 26, 2022 |
| ASUSTek       | PRIME Z270-A                | [8c2de24375](https://linux-hardware.org/?probe=8c2de24375) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [fc35cfc7f6](https://linux-hardware.org/?probe=fc35cfc7f6) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [8f2b511688](https://linux-hardware.org/?probe=8f2b511688) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ace55b44d7](https://linux-hardware.org/?probe=ace55b44d7) | Jun 25, 2022 |
| Intel         | X99 V1.0                    | [17e64443b0](https://linux-hardware.org/?probe=17e64443b0) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Intel         | H61                         | [e5a2c316f3](https://linux-hardware.org/?probe=e5a2c316f3) | Jun 24, 2022 |
| Intel         | H61                         | [d3b87d18d8](https://linux-hardware.org/?probe=d3b87d18d8) | Jun 24, 2022 |
| Intel         | H55                         | [853a94f10d](https://linux-hardware.org/?probe=853a94f10d) | Jun 23, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [c44391986b](https://linux-hardware.org/?probe=c44391986b) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [da57ce522d](https://linux-hardware.org/?probe=da57ce522d) | Jun 23, 2022 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [3747f62fa6](https://linux-hardware.org/?probe=3747f62fa6) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [914da7c9a4](https://linux-hardware.org/?probe=914da7c9a4) | Jun 23, 2022 |
| ASUSTek       | PRIME Z270-A                | [463b7612de](https://linux-hardware.org/?probe=463b7612de) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [836efa773c](https://linux-hardware.org/?probe=836efa773c) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [380b66353e](https://linux-hardware.org/?probe=380b66353e) | Jun 21, 2022 |
| PCWare        | IPMH61R1                    | [130bb25912](https://linux-hardware.org/?probe=130bb25912) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| ASUSTek       | M2NPV-VM                    | [818e78cbe0](https://linux-hardware.org/?probe=818e78cbe0) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASUSTek       | M5A97 PLUS                  | [bef449f943](https://linux-hardware.org/?probe=bef449f943) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a0d16e2b3c](https://linux-hardware.org/?probe=a0d16e2b3c) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3fad3e1c0b](https://linux-hardware.org/?probe=3fad3e1c0b) | Jun 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [6446ac4750](https://linux-hardware.org/?probe=6446ac4750) | Jun 18, 2022 |
| Dell          | 0D883F A06                  | [6296a553c6](https://linux-hardware.org/?probe=6296a553c6) | Jun 18, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Intel         | H61                         | [358da63cbc](https://linux-hardware.org/?probe=358da63cbc) | Jun 18, 2022 |
| ASUSTek       | H110M-CS/BR                 | [35cfc3daf7](https://linux-hardware.org/?probe=35cfc3daf7) | Jun 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [494419a571](https://linux-hardware.org/?probe=494419a571) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [47e88dae48](https://linux-hardware.org/?probe=47e88dae48) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [772bf458a3](https://linux-hardware.org/?probe=772bf458a3) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Dell          | 01XK1W A00                  | [f73ae16c57](https://linux-hardware.org/?probe=f73ae16c57) | Jun 16, 2022 |
| ECS           | 945GZ/CT-M                  | [ca6bdad27e](https://linux-hardware.org/?probe=ca6bdad27e) | Jun 15, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| ASRock        | B75M-DGS R2.0               | [457047ad06](https://linux-hardware.org/?probe=457047ad06) | Jun 13, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f3cb75acef](https://linux-hardware.org/?probe=f3cb75acef) | Jun 13, 2022 |
| Intel         | DH61CR AAG14064-207         | [a840bbb5a3](https://linux-hardware.org/?probe=a840bbb5a3) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [6a36412f6d](https://linux-hardware.org/?probe=6a36412f6d) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [0e1115fdc9](https://linux-hardware.org/?probe=0e1115fdc9) | Jun 12, 2022 |
| Biostar       | B450MX-S                    | [be9e9c5a99](https://linux-hardware.org/?probe=be9e9c5a99) | Jun 11, 2022 |
| MSI           | 2A9C                        | [c2007961e1](https://linux-hardware.org/?probe=c2007961e1) | Jun 11, 2022 |
| Intel         | H61                         | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| Dell          | 0TDG4V A01                  | [3da09dbe5d](https://linux-hardware.org/?probe=3da09dbe5d) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ec2e52372f](https://linux-hardware.org/?probe=ec2e52372f) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
| ASUSTek       | P8P67-M                     | [619b49a078](https://linux-hardware.org/?probe=619b49a078) | Jun 10, 2022 |
| ASRock        | B450M Steel Legend          | [9744f09d7e](https://linux-hardware.org/?probe=9744f09d7e) | Jun 09, 2022 |
| ASRock        | B450M Steel Legend          | [75510afde6](https://linux-hardware.org/?probe=75510afde6) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d0fa25e5f0](https://linux-hardware.org/?probe=d0fa25e5f0) | Jun 08, 2022 |
| Gigabyte      | 970A-DS3P                   | [a68fb9489c](https://linux-hardware.org/?probe=a68fb9489c) | Jun 08, 2022 |
| HP            | 1998                        | [362416dfc1](https://linux-hardware.org/?probe=362416dfc1) | Jun 08, 2022 |
| PCWare        | IPX4105G Pro                | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASRock        | H110M-HG4                   | [a25254d5c3](https://linux-hardware.org/?probe=a25254d5c3) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| Kllisre       | B75 V1.1                    | [d9a9aa6243](https://linux-hardware.org/?probe=d9a9aa6243) | Jun 06, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Gigabyte      | H81M-S1                     | [6a2b3dfc3e](https://linux-hardware.org/?probe=6a2b3dfc3e) | Jun 06, 2022 |
| OEM           | H110                        | [d9bb28c841](https://linux-hardware.org/?probe=d9bb28c841) | Jun 05, 2022 |
| Dell          | 0YXT71 A02                  | [4dd5ceef26](https://linux-hardware.org/?probe=4dd5ceef26) | Jun 05, 2022 |
| MSI           | B85M-E45                    | [4446978a6f](https://linux-hardware.org/?probe=4446978a6f) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| HP            | 3029h                       | [6bbd8d0ebe](https://linux-hardware.org/?probe=6bbd8d0ebe) | Jun 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [5b481a2d9f](https://linux-hardware.org/?probe=5b481a2d9f) | Jun 02, 2022 |
| ASRock        | 760GM-HDV                   | [b72f6362e5](https://linux-hardware.org/?probe=b72f6362e5) | Jun 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [d1cd1862cf](https://linux-hardware.org/?probe=d1cd1862cf) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Intel         | H61                         | [7f87ff703e](https://linux-hardware.org/?probe=7f87ff703e) | May 30, 2022 |
| Intel         | DG43GT AAE62768-300         | [643ebac3b3](https://linux-hardware.org/?probe=643ebac3b3) | May 29, 2022 |
| ASRock        | A320M-HD                    | [b9b89a0256](https://linux-hardware.org/?probe=b9b89a0256) | May 29, 2022 |
| ASUSTek       | AM1M-A/BR                   | [c8532fbb66](https://linux-hardware.org/?probe=c8532fbb66) | May 29, 2022 |
| Gigabyte      | H310M H                     | [60e8f2017c](https://linux-hardware.org/?probe=60e8f2017c) | May 29, 2022 |
| ASUSTek       | H61M-K                      | [1001d81aa0](https://linux-hardware.org/?probe=1001d81aa0) | May 28, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [e2e854cde1](https://linux-hardware.org/?probe=e2e854cde1) | May 28, 2022 |
| Positivo      | POS-PIQ57BQA                | [f33ecab5de](https://linux-hardware.org/?probe=f33ecab5de) | May 27, 2022 |
| Intel         | MAHOBAY                     | [1eddee7bcd](https://linux-hardware.org/?probe=1eddee7bcd) | May 26, 2022 |
| Positivo      | POS-PIQ57BQA                | [2175bbae83](https://linux-hardware.org/?probe=2175bbae83) | May 26, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| ASUSTek       | B85M-E                      | [d153ce4509](https://linux-hardware.org/?probe=d153ce4509) | May 26, 2022 |
| Intel         | H55                         | [fa014a938e](https://linux-hardware.org/?probe=fa014a938e) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [66b8c4e68c](https://linux-hardware.org/?probe=66b8c4e68c) | May 24, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [7fae2860ed](https://linux-hardware.org/?probe=7fae2860ed) | May 23, 2022 |
| Intel         | DH55HC AAE70933-505         | [6c27613f85](https://linux-hardware.org/?probe=6c27613f85) | May 23, 2022 |
| Intel         | H55                         | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| Intel         | H55                         | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Unknown       | P4M800Pro-8237              | [31c80b1ea7](https://linux-hardware.org/?probe=31c80b1ea7) | May 23, 2022 |
| ASRock        | 760GM-HDV                   | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| ASUSTek       | H81M-CS/BR                  | [d7908e91b2](https://linux-hardware.org/?probe=d7908e91b2) | May 22, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [da237b1570](https://linux-hardware.org/?probe=da237b1570) | May 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | ThinkCentre M57 9181A28     | [51ec46a243](https://linux-hardware.org/?probe=51ec46a243) | May 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [f11849c880](https://linux-hardware.org/?probe=f11849c880) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| ASRock        | B450M Steel Legend          | [82304dff79](https://linux-hardware.org/?probe=82304dff79) | May 18, 2022 |
| Gigabyte      | A520M AORUS ELITE           | [959370d8dc](https://linux-hardware.org/?probe=959370d8dc) | May 18, 2022 |
| Gigabyte      | A520M AORUS ELITE           | [3f7443585b](https://linux-hardware.org/?probe=3f7443585b) | May 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b93895e03f](https://linux-hardware.org/?probe=b93895e03f) | May 17, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b9f903a680](https://linux-hardware.org/?probe=b9f903a680) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| Intel         | B75 V124                    | [fe86136319](https://linux-hardware.org/?probe=fe86136319) | May 17, 2022 |
| Gigabyte      | G31M-ES2L                   | [06d20940b6](https://linux-hardware.org/?probe=06d20940b6) | May 17, 2022 |
| Gigabyte      | B75M-D3H                    | [b16118393d](https://linux-hardware.org/?probe=b16118393d) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [5e9289dcf5](https://linux-hardware.org/?probe=5e9289dcf5) | May 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [ef49485481](https://linux-hardware.org/?probe=ef49485481) | May 16, 2022 |
| Gigabyte      | X38-DQ6                     | [653ffc4014](https://linux-hardware.org/?probe=653ffc4014) | May 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [e2b0f10f58](https://linux-hardware.org/?probe=e2b0f10f58) | May 15, 2022 |
| Gigabyte      | B75M-D3H                    | [285fd45173](https://linux-hardware.org/?probe=285fd45173) | May 15, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [903b5a7b61](https://linux-hardware.org/?probe=903b5a7b61) | May 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| Positivo      | POS-PIH81DI                 | [2e519d3320](https://linux-hardware.org/?probe=2e519d3320) | May 14, 2022 |
| Intel         | X99 V1.0                    | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| Positivo      | POS-PIH77CM POSITIVO        | [8dbd7b8e3a](https://linux-hardware.org/?probe=8dbd7b8e3a) | May 13, 2022 |
| ASRock        | H61M-HVS                    | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASRock        | H61M-HP4                    | [f0bda638ba](https://linux-hardware.org/?probe=f0bda638ba) | May 13, 2022 |
| Pegatron      | IPMIP-GS                    | [76783b5ce4](https://linux-hardware.org/?probe=76783b5ce4) | May 12, 2022 |
| Pegatron      | IPMIP-GS                    | [1f60b52d11](https://linux-hardware.org/?probe=1f60b52d11) | May 12, 2022 |
| Biostar       | G31M+                       | [7440220607](https://linux-hardware.org/?probe=7440220607) | May 12, 2022 |
| ASUSTek       | PRIME B350M-E               | [c1c97167a7](https://linux-hardware.org/?probe=c1c97167a7) | May 11, 2022 |
| Positivo      | DA18HV1 POSITIVO            | [9d5e3583e2](https://linux-hardware.org/?probe=9d5e3583e2) | May 11, 2022 |
| Intel         | B75                         | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| MSI           | G31M3-L V2                  | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [2091818d85](https://linux-hardware.org/?probe=2091818d85) | May 10, 2022 |
| ASUSTek       | PRIME B350M-E               | [11a6c9f35a](https://linux-hardware.org/?probe=11a6c9f35a) | May 10, 2022 |
| ASRock        | FM2A55M-VG3+                | [43c813fe70](https://linux-hardware.org/?probe=43c813fe70) | May 10, 2022 |
| Positivo      | POS-PIQ57BQA                | [f3abe22dd6](https://linux-hardware.org/?probe=f3abe22dd6) | May 09, 2022 |
| Intel         | H61                         | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| Dell          | 0RW203                      | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [c5c38a0da4](https://linux-hardware.org/?probe=c5c38a0da4) | May 08, 2022 |
| Positivo      | POS-PIG41BA                 | [40a9a00430](https://linux-hardware.org/?probe=40a9a00430) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [d4e02db7d2](https://linux-hardware.org/?probe=d4e02db7d2) | May 07, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [4c2b573647](https://linux-hardware.org/?probe=4c2b573647) | May 07, 2022 |
| Positivo      | POS-MI945AA                 | [dffab0e390](https://linux-hardware.org/?probe=dffab0e390) | May 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [39beda4841](https://linux-hardware.org/?probe=39beda4841) | May 07, 2022 |
| MSI           | 880GMA-E35                  | [a2998f652e](https://linux-hardware.org/?probe=a2998f652e) | May 07, 2022 |
| Positivo      | POS-PIH81DI                 | [f7b64e05f8](https://linux-hardware.org/?probe=f7b64e05f8) | May 06, 2022 |
| MSI           | 880GMA-E35                  | [862de68566](https://linux-hardware.org/?probe=862de68566) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Positivo      | POS-PARS760GCD              | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| Gigabyte      | H410M H V3                  | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| Intel         | H61                         | [ef0e75557e](https://linux-hardware.org/?probe=ef0e75557e) | May 05, 2022 |
| ASUSTek       | Z97-K                       | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [8d41e2310f](https://linux-hardware.org/?probe=8d41e2310f) | May 04, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Lenovo        | SDK0E50515 STD              | [9a67a9ecfe](https://linux-hardware.org/?probe=9a67a9ecfe) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [489d69a9ee](https://linux-hardware.org/?probe=489d69a9ee) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [914e422e76](https://linux-hardware.org/?probe=914e422e76) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| JINGSHA       | Unknown                     | [94dd890d71](https://linux-hardware.org/?probe=94dd890d71) | May 02, 2022 |
| Intel         | H61M-DS2                    | [78f738c029](https://linux-hardware.org/?probe=78f738c029) | May 02, 2022 |
| Intel         | H61M-DS2                    | [10c3d8c8a0](https://linux-hardware.org/?probe=10c3d8c8a0) | May 02, 2022 |
| Pegatron      | 2AB5                        | [5ad527dcd2](https://linux-hardware.org/?probe=5ad527dcd2) | May 01, 2022 |
| Intel         | DG31PR AAE58249-306         | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| Positivo      | POS-EIBTPDC                 | [a9a49f094d](https://linux-hardware.org/?probe=a9a49f094d) | May 01, 2022 |
| Positivo      | POS-EIH110EA                | [d0a20e98ac](https://linux-hardware.org/?probe=d0a20e98ac) | May 01, 2022 |
| Pegatron      | 2AB5                        | [534476ac99](https://linux-hardware.org/?probe=534476ac99) | Apr 30, 2022 |
| Positivo      | POS-ECIG41BSA               | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | [6afc1a0af8](https://linux-hardware.org/?probe=6afc1a0af8) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| JINGSHA       | Unknown                     | [e1b9c4eab0](https://linux-hardware.org/?probe=e1b9c4eab0) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| Unknown       | Intel X79                   | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| PCWare        | IPX4105G Pro                | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [6a5bc03a3a](https://linux-hardware.org/?probe=6a5bc03a3a) | Apr 29, 2022 |
| Intel         | MAHOBAY                     | [ca65be05f0](https://linux-hardware.org/?probe=ca65be05f0) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [c82cd4f476](https://linux-hardware.org/?probe=c82cd4f476) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [8dafe7350b](https://linux-hardware.org/?probe=8dafe7350b) | Apr 27, 2022 |
| MSI           | Z97-G45 GAMING              | [6660cb5133](https://linux-hardware.org/?probe=6660cb5133) | Apr 27, 2022 |
| Itautec       | NT 2030                     | [ce556d6808](https://linux-hardware.org/?probe=ce556d6808) | Apr 26, 2022 |
| MSI           | MS-6701                     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| ASRock        | A320M-HD                    | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| ASRock        | B450M Steel Legend          | [06ecfd2026](https://linux-hardware.org/?probe=06ecfd2026) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [d7d46c682c](https://linux-hardware.org/?probe=d7d46c682c) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [4570a2caf7](https://linux-hardware.org/?probe=4570a2caf7) | Apr 25, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [b0a2546f9f](https://linux-hardware.org/?probe=b0a2546f9f) | Apr 24, 2022 |
| Positivo      | POS-EIBTDB                  | [2b6822eb50](https://linux-hardware.org/?probe=2b6822eb50) | Apr 24, 2022 |
| Biostar       | NM70I-1017U                 | [c27061c8f4](https://linux-hardware.org/?probe=c27061c8f4) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [20d9884cb6](https://linux-hardware.org/?probe=20d9884cb6) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [dac092d7bc](https://linux-hardware.org/?probe=dac092d7bc) | Apr 24, 2022 |
| MSI           | H81M-E33                    | [a56e939c9f](https://linux-hardware.org/?probe=a56e939c9f) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | [73ac7e5e3e](https://linux-hardware.org/?probe=73ac7e5e3e) | Apr 23, 2022 |
| MSI           | G41M-S01                    | [cd81f73a4d](https://linux-hardware.org/?probe=cd81f73a4d) | Apr 23, 2022 |
| Intel         | H81                         | [9720e797c4](https://linux-hardware.org/?probe=9720e797c4) | Apr 23, 2022 |
| Intel         | H81                         | [2c89989829](https://linux-hardware.org/?probe=2c89989829) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | [26a1791ea4](https://linux-hardware.org/?probe=26a1791ea4) | Apr 22, 2022 |
| ASUSTek       | P7H55-M BR                  | [e3c7a6ade9](https://linux-hardware.org/?probe=e3c7a6ade9) | Apr 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [0150424029](https://linux-hardware.org/?probe=0150424029) | Apr 22, 2022 |
| Dell          | 073MMW A03                  | [f3ecf74145](https://linux-hardware.org/?probe=f3ecf74145) | Apr 22, 2022 |
| Intel         | X99                         | [f7410bb2fd](https://linux-hardware.org/?probe=f7410bb2fd) | Apr 21, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| Dell          | 0200DY A01                  | [5cb77cb68e](https://linux-hardware.org/?probe=5cb77cb68e) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d126b742fe](https://linux-hardware.org/?probe=d126b742fe) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [888cf862fc](https://linux-hardware.org/?probe=888cf862fc) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| MSI           | Boston                      | [ee1d487c1e](https://linux-hardware.org/?probe=ee1d487c1e) | Apr 18, 2022 |
| Gigabyte      | G41MT-ES2L                  | [fbeec44852](https://linux-hardware.org/?probe=fbeec44852) | Apr 18, 2022 |
| Intel         | Unknown                     | [b734cf3221](https://linux-hardware.org/?probe=b734cf3221) | Apr 17, 2022 |
| Gigabyte      | 970A-UD3                    | [7128f5f2b4](https://linux-hardware.org/?probe=7128f5f2b4) | Apr 17, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [8f8f3b74e6](https://linux-hardware.org/?probe=8f8f3b74e6) | Apr 16, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| MSI           | A320M PRO-M2 V2             | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| Gigabyte      | H61M-S1                     | [dfd89c6a60](https://linux-hardware.org/?probe=dfd89c6a60) | Apr 16, 2022 |
| Dell          | 0VHXCD A03                  | [290987223e](https://linux-hardware.org/?probe=290987223e) | Apr 16, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [0a8d0e5302](https://linux-hardware.org/?probe=0a8d0e5302) | Apr 15, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [172be13d6d](https://linux-hardware.org/?probe=172be13d6d) | Apr 15, 2022 |
| GALAX         | A320M G10g                  | [958fc1bf94](https://linux-hardware.org/?probe=958fc1bf94) | Apr 14, 2022 |
| Itautec       | ST 4262 ST-4262 Padrao 0... | [1dd8e2f31b](https://linux-hardware.org/?probe=1dd8e2f31b) | Apr 14, 2022 |
| Dell          | 0NW6H5 A00                  | [dd5d897f4c](https://linux-hardware.org/?probe=dd5d897f4c) | Apr 14, 2022 |
| Dell          | 0YR541 A01                  | [f206c3667e](https://linux-hardware.org/?probe=f206c3667e) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [83dda83cdf](https://linux-hardware.org/?probe=83dda83cdf) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [92eaa72b3c](https://linux-hardware.org/?probe=92eaa72b3c) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [33cce38b5e](https://linux-hardware.org/?probe=33cce38b5e) | Apr 13, 2022 |
| ASRock        | N68-VS3 UCC                 | [1ca06f94c7](https://linux-hardware.org/?probe=1ca06f94c7) | Apr 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | [4f5a780267](https://linux-hardware.org/?probe=4f5a780267) | Apr 12, 2022 |
| Toshiba       | STI 010433                  | [9eb114e523](https://linux-hardware.org/?probe=9eb114e523) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f4cb39e804](https://linux-hardware.org/?probe=f4cb39e804) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [80c51dad27](https://linux-hardware.org/?probe=80c51dad27) | Apr 12, 2022 |
| MSI           | G31TM-P21                   | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| ASUSTek       | H81M-CS/BR                  | [e2452fa831](https://linux-hardware.org/?probe=e2452fa831) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [4f13d38f2e](https://linux-hardware.org/?probe=4f13d38f2e) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [0a89a1b47b](https://linux-hardware.org/?probe=0a89a1b47b) | Apr 11, 2022 |
| PCWare        | IPMH61R1                    | [4f465b1b2d](https://linux-hardware.org/?probe=4f465b1b2d) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Positivo      | POS-MI945AA                 | [581272b7c1](https://linux-hardware.org/?probe=581272b7c1) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| Itautec       | ST 4265                     | [b2facb728e](https://linux-hardware.org/?probe=b2facb728e) | Apr 10, 2022 |
| Dell          | 08NPPY A00                  | [5c2b30a7e1](https://linux-hardware.org/?probe=5c2b30a7e1) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Unknown       | TIGD-CI4                    | [266aef8b2e](https://linux-hardware.org/?probe=266aef8b2e) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Intel         | H81                         | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| ASRock        | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| Intel         | Unknown                     | [28f0edef8f](https://linux-hardware.org/?probe=28f0edef8f) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| Unknown       | Unknown                     | [a78f13de9e](https://linux-hardware.org/?probe=a78f13de9e) | Apr 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Intel         | X99                         | [4b1591958f](https://linux-hardware.org/?probe=4b1591958f) | Apr 06, 2022 |
| Acer          | Aspire XC-605               | [201896f70b](https://linux-hardware.org/?probe=201896f70b) | Apr 06, 2022 |
| ASRock        | FM2A78M-ITX+                | [63799d0adb](https://linux-hardware.org/?probe=63799d0adb) | Apr 06, 2022 |
| HP            | 3047h                       | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | [adf960d914](https://linux-hardware.org/?probe=adf960d914) | Apr 05, 2022 |
| Intel         | H61                         | [d378493561](https://linux-hardware.org/?probe=d378493561) | Apr 05, 2022 |
| Dell          | 02YRK5 A03                  | [8f30fb0a3f](https://linux-hardware.org/?probe=8f30fb0a3f) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [4014bf184c](https://linux-hardware.org/?probe=4014bf184c) | Apr 04, 2022 |
| Gigabyte      | H55M-S2HP                   | [5079856030](https://linux-hardware.org/?probe=5079856030) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| HP            | 1998                        | [d30791d695](https://linux-hardware.org/?probe=d30791d695) | Apr 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 562      | 12.51%  |
| Ubuntu 18.04      | 408      | 9.08%   |
| OpenMandriva 4.2  | 171      | 3.81%   |
| OpenMandriva 4.3  | 127      | 2.83%   |
| Linux Mint 20     | 118      | 2.63%   |
| Pop!_OS 20.04     | 114      | 2.54%   |
| Linux Mint 19.3   | 114      | 2.54%   |
| Linux Mint 19.1   | 110      | 2.45%   |
| Ubuntu 22.04      | 103      | 2.29%   |
| KDE neon 20.04    | 97       | 2.16%   |
| Ubuntu 19.04      | 95       | 2.12%   |
| Linux Mint 20.1   | 84       | 1.87%   |
| Arch              | 69       | 1.54%   |
| Zorin 16          | 67       | 1.49%   |
| Linux Mint 20.3   | 65       | 1.45%   |
| Linux Mint 20.2   | 63       | 1.4%    |
| Pop!_OS 20.10     | 61       | 1.36%   |
| Debian 10         | 61       | 1.36%   |
| Ubuntu MATE 20.04 | 58       | 1.29%   |
| Ubuntu 19.10      | 58       | 1.29%   |
| Pop!_OS 21.04     | 57       | 1.27%   |
| Manjaro           | 57       | 1.27%   |
| Zorin 15          | 54       | 1.2%    |
| Debian 11         | 51       | 1.14%   |
| Fedora 36         | 49       | 1.09%   |
| Linux Mint 19.2   | 48       | 1.07%   |
| Arch Rolling      | 47       | 1.05%   |
| Xubuntu 20.04     | 44       | 0.98%   |
| Fedora 34         | 43       | 0.96%   |
| Fedora 32         | 39       | 0.87%   |
| Pop!_OS 22.04     | 38       | 0.85%   |
| Fedora 33         | 38       | 0.85%   |
| Ubuntu 18.10      | 36       | 0.8%    |
| Kubuntu 20.04     | 36       | 0.8%    |
| Ubuntu 20.10      | 35       | 0.78%   |
| Linux Mint 21     | 34       | 0.76%   |
| Xubuntu 18.04     | 33       | 0.73%   |
| Ubuntu 21.10      | 31       | 0.69%   |
| Pop!_OS 21.10     | 31       | 0.69%   |
| Fedora 35         | 29       | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1340     | 31.13%  |
| Linux Mint    | 636      | 14.77%  |
| OpenMandriva  | 331      | 7.69%   |
| Pop!_OS       | 288      | 6.69%   |
| Fedora        | 226      | 5.25%   |
| Endless       | 159      | 3.69%   |
| Debian        | 156      | 3.62%   |
| Manjaro       | 131      | 3.04%   |
| Zorin         | 126      | 2.93%   |
| KDE neon      | 114      | 2.65%   |
| Arch          | 114      | 2.65%   |
| Xubuntu       | 92       | 2.14%   |
| Kubuntu       | 76       | 1.77%   |
| ROSA          | 72       | 1.67%   |
| Ubuntu MATE   | 69       | 1.6%    |
| openSUSE      | 43       | 1%      |
| Lubuntu       | 29       | 0.67%   |
| Ubuntu Unity  | 28       | 0.65%   |
| Elementary    | 26       | 0.6%    |
| LMDE          | 22       | 0.51%   |
| ArcoLinux     | 20       | 0.46%   |
| LinuxFX       | 16       | 0.37%   |
| CentOS        | 16       | 0.37%   |
| BlackPanther  | 16       | 0.37%   |
| Deepin        | 15       | 0.35%   |
| Kali          | 12       | 0.28%   |
| Ubuntu Budgie | 10       | 0.23%   |
| Gentoo        | 8        | 0.19%   |
| Clear Linux   | 8        | 0.19%   |
| Linux Lite    | 7        | 0.16%   |
| BigLinux      | 7        | 0.16%   |
| Peppermint    | 6        | 0.14%   |
| Parrot        | 6        | 0.14%   |
| EndeavourOS   | 6        | 0.14%   |
| Ubuntu Studio | 5        | 0.12%   |
| Solus         | 5        | 0.12%   |
| MX            | 5        | 0.12%   |
| UbuntuDDE     | 4        | 0.09%   |
| Garuda Linux  | 4        | 0.09%   |
| Void Linux    | 3        | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 228      | 4.69%   |
| 5.10.14-desktop-1omv4002 | 166      | 3.42%   |
| 5.16.7-desktop-1omv4003  | 120      | 2.47%   |
| 4.15.0-46-generic        | 84       | 1.73%   |
| 5.4.0-48-generic         | 65       | 1.34%   |
| 4.18.0-15-generic        | 49       | 1.01%   |
| 5.4.0-7634-generic       | 48       | 0.99%   |
| 5.4.0-58-generic         | 45       | 0.93%   |
| 5.4.0-52-generic         | 43       | 0.88%   |
| 5.3.0-40-generic         | 43       | 0.88%   |
| 5.4.0-40-generic         | 41       | 0.84%   |
| 5.4.0-47-generic         | 40       | 0.82%   |
| 5.11.0-7620-generic      | 37       | 0.76%   |
| 5.3.0-28-generic         | 36       | 0.74%   |
| 5.4.0-26-generic         | 35       | 0.72%   |
| 4.15.0-20-generic        | 33       | 0.68%   |
| 5.4.0-70-generic         | 32       | 0.66%   |
| 5.4.0-72-generic         | 31       | 0.64%   |
| 5.0.0-32-generic         | 30       | 0.62%   |
| 5.3.0-46-generic         | 28       | 0.58%   |
| 5.0.0-37-generic         | 28       | 0.58%   |
| 5.8.0-7630-generic       | 27       | 0.56%   |
| 4.15.0-54-generic        | 27       | 0.56%   |
| 5.4.0-91-generic         | 26       | 0.53%   |
| 5.4.0-33-generic         | 26       | 0.53%   |
| 5.15.0-46-generic        | 25       | 0.51%   |
| 5.11.0-37-generic        | 24       | 0.49%   |
| 5.8.0-59-generic         | 23       | 0.47%   |
| 5.8.0-14-generic         | 23       | 0.47%   |
| 5.4.0-74-generic         | 23       | 0.47%   |
| 5.4.0-66-generic         | 23       | 0.47%   |
| 5.4.0-54-generic         | 23       | 0.47%   |
| 5.4.0-37-generic         | 23       | 0.47%   |
| 5.15.0-56-generic        | 23       | 0.47%   |
| 5.15.0-52-generic        | 23       | 0.47%   |
| 5.11.0-27-generic        | 23       | 0.47%   |
| 5.0.0-13-generic         | 23       | 0.47%   |
| 4.18.0-16-generic        | 23       | 0.47%   |
| 5.4.0-80-generic         | 22       | 0.45%   |
| 5.4.0-77-generic         | 22       | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1106     | 24.14%  |
| 4.15.0  | 414      | 9.04%   |
| 5.8.0   | 257      | 5.61%   |
| 5.11.0  | 246      | 5.37%   |
| 5.3.0   | 244      | 5.33%   |
| 5.0.0   | 230      | 5.02%   |
| 5.15.0  | 203      | 4.43%   |
| 4.18.0  | 173      | 3.78%   |
| 5.13.0  | 172      | 3.75%   |
| 5.10.14 | 166      | 3.62%   |
| 5.16.7  | 120      | 2.62%   |
| 4.19.0  | 74       | 1.62%   |
| 5.10.0  | 71       | 1.55%   |
| 5.19.0  | 26       | 0.57%   |
| 5.7.9   | 21       | 0.46%   |
| 5.17.5  | 21       | 0.46%   |
| 4.9.0   | 18       | 0.39%   |
| 4.4.0   | 18       | 0.39%   |
| 4.9.60  | 15       | 0.33%   |
| 5.13.19 | 14       | 0.31%   |
| 5.7.0   | 13       | 0.28%   |
| 6.0.10  | 12       | 0.26%   |
| 5.18.12 | 12       | 0.26%   |
| 5.17.15 | 12       | 0.26%   |
| 5.15.5  | 12       | 0.26%   |
| 4.18.16 | 12       | 0.26%   |
| 5.16.11 | 11       | 0.24%   |
| 5.16.0  | 11       | 0.24%   |
| 5.14.0  | 11       | 0.24%   |
| 5.12.4  | 11       | 0.24%   |
| 4.9.20  | 11       | 0.24%   |
| 5.6.19  | 10       | 0.22%   |
| 5.7.10  | 9        | 0.2%    |
| 5.6.15  | 9        | 0.2%    |
| 5.9.16  | 8        | 0.17%   |
| 5.16.13 | 8        | 0.17%   |
| 3.10.0  | 8        | 0.17%   |
| 6.0.6   | 7        | 0.15%   |
| 5.7.7   | 7        | 0.15%   |
| 5.6.14  | 7        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 1153     | 25.49%  |
| 4.15    | 414      | 9.15%   |
| 5.10    | 316      | 6.98%   |
| 5.8     | 299      | 6.61%   |
| 5.15    | 273      | 6.03%   |
| 5.11    | 271      | 5.99%   |
| 5.3     | 264      | 5.84%   |
| 5.0     | 244      | 5.39%   |
| 5.13    | 205      | 4.53%   |
| 4.18    | 189      | 4.18%   |
| 5.16    | 173      | 3.82%   |
| 4.19    | 90       | 1.99%   |
| 5.19    | 73       | 1.61%   |
| 5.7     | 70       | 1.55%   |
| 5.18    | 55       | 1.22%   |
| 4.9     | 55       | 1.22%   |
| 5.17    | 53       | 1.17%   |
| 6.0     | 52       | 1.15%   |
| 5.6     | 52       | 1.15%   |
| 5.12    | 49       | 1.08%   |
| 5.14    | 41       | 0.91%   |
| 5.9     | 35       | 0.77%   |
| 4.4     | 18       | 0.4%    |
| 5.5     | 16       | 0.35%   |
| 5.2     | 13       | 0.29%   |
| 5.1     | 11       | 0.24%   |
| 4.1     | 8        | 0.18%   |
| 3.10    | 8        | 0.18%   |
| 4.13    | 6        | 0.13%   |
| 4.20    | 5        | 0.11%   |
| 4.12    | 5        | 0.11%   |
| 4.10    | 4        | 0.09%   |
| 4.8     | 2        | 0.04%   |
| 6.1     | 1        | 0.02%   |
| 4.14    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4018     | 97.03%  |
| i686   | 123      | 2.97%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 1697     | 39.11%  |
| Unknown                  | 761      | 17.54%  |
| KDE5                     | 617      | 14.22%  |
| X-Cinnamon               | 372      | 8.57%   |
| XFCE                     | 309      | 7.12%   |
| MATE                     | 147      | 3.39%   |
| KDE                      | 140      | 3.23%   |
| Cinnamon                 | 84       | 1.94%   |
| KDE4                     | 38       | 0.88%   |
| Unity                    | 29       | 0.67%   |
| LXQt                     | 26       | 0.6%    |
| Pantheon                 | 22       | 0.51%   |
| Budgie                   | 19       | 0.44%   |
| Deepin                   | 18       | 0.41%   |
| LXDE                     | 16       | 0.37%   |
| GNOME Flashback          | 13       | 0.3%    |
| i3                       | 8        | 0.18%   |
| GNOME Classic            | 4        | 0.09%   |
| awesome                  | 4        | 0.09%   |
| openbox                  | 3        | 0.07%   |
| Enlightenment            | 3        | 0.07%   |
| sway                     | 2        | 0.05%   |
| qtile                    | 2        | 0.05%   |
| bspwm                    | 2        | 0.05%   |
| icewm                    | 1        | 0.02%   |
| 03WindowMaker            | 1        | 0.02%   |
| /usr/bin/openbox-session | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3493     | 82.81%  |
| Unknown | 354      | 8.39%   |
| Wayland | 337      | 7.99%   |
| Tty     | 32       | 0.76%   |
| Web     | 2        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2636     | 61.92%  |
| SDDM    | 538      | 12.64%  |
| GDM     | 395      | 9.28%   |
| TDM     | 236      | 5.54%   |
| GDM3    | 205      | 4.82%   |
| LightDM | 199      | 4.67%   |
| KDM     | 39       | 0.92%   |
| XDM     | 4        | 0.09%   |
| SLiM    | 2        | 0.05%   |
| SLIMSKI | 1        | 0.02%   |
| MDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pt_BR       | 2736     | 64.62%  |
| Unknown     | 746      | 17.62%  |
| en_US       | 652      | 15.4%   |
| C           | 54       | 1.28%   |
| pt_PT       | 15       | 0.35%   |
| en_GB       | 15       | 0.35%   |
| es_ES       | 5        | 0.12%   |
| en_CA       | 3        | 0.07%   |
| en_AG       | 2        | 0.05%   |
| pt_BRutf8   | 1        | 0.02%   |
| eo          | 1        | 0.02%   |
| en_US.utf-8 | 1        | 0.02%   |
| en_IN       | 1        | 0.02%   |
| de_DE       | 1        | 0.02%   |
| C.UTF8      | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2936     | 69.51%  |
| EFI  | 1288     | 30.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3195     | 75.55%  |
| Overlay | 397      | 9.39%   |
| Unknown | 304      | 7.19%   |
| Btrfs   | 252      | 5.96%   |
| Xfs     | 35       | 0.83%   |
| Zfs     | 17       | 0.4%    |
| Ext3    | 8        | 0.19%   |
| F2fs    | 7        | 0.17%   |
| Ext2    | 7        | 0.17%   |
| Tmpfs   | 6        | 0.14%   |
| Aufs    | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2789     | 65.92%  |
| GPT     | 828      | 19.57%  |
| MBR     | 614      | 14.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3584     | 84.85%  |
| Yes       | 640      | 15.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2855     | 67.59%  |
| Yes       | 1369     | 32.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1100     | 26.59%  |
| Gigabyte Technology | 712      | 17.21%  |
| ASRock              | 365      | 8.82%   |
| Intel               | 329      | 7.95%   |
| Dell                | 240      | 5.8%    |
| Positivo            | 177      | 4.28%   |
| MSI                 | 177      | 4.28%   |
| Unknown             | 142      | 3.43%   |
| Hewlett-Packard     | 128      | 3.09%   |
| PCWare              | 104      | 2.51%   |
| Biostar             | 81       | 1.96%   |
| Lenovo              | 69       | 1.67%   |
| Pegatron            | 62       | 1.5%    |
| ECS                 | 60       | 1.45%   |
| Semp Toshiba        | 42       | 1.02%   |
| Itautec             | 36       | 0.87%   |
| Megaware            | 27       | 0.65%   |
| Huanan              | 27       | 0.65%   |
| Foxconn             | 27       | 0.65%   |
| OEM                 | 16       | 0.39%   |
| Login Informatica   | 14       | 0.34%   |
| Qbex                | 12       | 0.29%   |
| VS Company          | 10       | 0.24%   |
| PCChips             | 10       | 0.24%   |
| Digiboard           | 10       | 0.24%   |
| AMD                 | 10       | 0.24%   |
| Supermicro          | 9        | 0.22%   |
| Philco              | 9        | 0.22%   |
| MACHINIST           | 8        | 0.19%   |
| Digitron            | 7        | 0.17%   |
| Phitronics          | 6        | 0.15%   |
| INTELBRAS           | 6        | 0.15%   |
| IBM                 | 5        | 0.12%   |
| Colorful Technology | 5        | 0.12%   |
| Centrium            | 5        | 0.12%   |
| CCE                 | 5        | 0.12%   |
| AMI                 | 5        | 0.12%   |
| MEGA                | 4        | 0.1%    |
| Kllisre             | 4        | 0.1%    |
| Daten Tecnologia    | 4        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 156      | 3.77%   |
| ASUS All Series               | 133      | 3.21%   |
| Intel H61                     | 66       | 1.6%    |
| ASUS PRIME B450M-GAMING/BR    | 58       | 1.4%    |
| ASRock A320M-HD               | 49       | 1.18%   |
| ASUS PRIME A320M-K/BR         | 47       | 1.14%   |
| Intel H55                     | 43       | 1.04%   |
| Semp Toshiba STI              | 41       | 0.99%   |
| ASUS M5A78L-M LX/BR           | 41       | 0.99%   |
| Gigabyte H61M-S1              | 34       | 0.82%   |
| Gigabyte B75M-D3H             | 33       | 0.8%    |
| Gigabyte A320M-S2H            | 31       | 0.75%   |
| ASUS P8H61-M LX3 R2.0         | 31       | 0.75%   |
| ASUS M5A78L-M PLUS/USB3       | 30       | 0.73%   |
| ASRock B450M Steel Legend     | 30       | 0.73%   |
| ASRock N68-S3 FX              | 27       | 0.65%   |
| Gigabyte B450M DS3H           | 23       | 0.56%   |
| ASUS M5A78L-M/USB3            | 23       | 0.56%   |
| ASUS H61M-A/BR                | 23       | 0.56%   |
| Gigabyte AB350M-DS3H V2       | 21       | 0.51%   |
| ASUS TUF Gaming X570-PLUS_BR  | 21       | 0.51%   |
| ASUS P8H61-M LX2 R2.0         | 21       | 0.51%   |
| ASUS P5G41T-M LX2/BR          | 21       | 0.51%   |
| Intel MAHOBAY                 | 20       | 0.48%   |
| Gigabyte 970A-DS3P            | 19       | 0.46%   |
| ASUS M4N68T-M LE              | 19       | 0.46%   |
| Positivo POS-EIH61CE          | 18       | 0.44%   |
| Intel B75                     | 18       | 0.44%   |
| HP Compaq 6005 Pro SFF PC     | 17       | 0.41%   |
| ASUS TUF B360M-PLUS GAMING/BR | 17       | 0.41%   |
| Gigabyte G31M-ES2C            | 16       | 0.39%   |
| ASUS PRIME H310M-E R2.0/BR    | 16       | 0.39%   |
| Gigabyte 945GCM-S2C           | 15       | 0.36%   |
| Dell XPS 8700                 | 15       | 0.36%   |
| ASUS PRIME A320M-K            | 15       | 0.36%   |
| ASUS P8H61-M LE/BR            | 15       | 0.36%   |
| ASRock N68-GS4 FX R2.0        | 15       | 0.36%   |
| Pegatron IPM41-D3             | 14       | 0.34%   |
| MSI MS-7788                   | 14       | 0.34%   |
| Gigabyte GA-78LMT-S2          | 14       | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 212      | 5.12%   |
| Unknown                | 156      | 3.77%   |
| Dell OptiPlex          | 142      | 3.43%   |
| ASUS All               | 133      | 3.21%   |
| ASUS M5A78L-M          | 110      | 2.66%   |
| ASUS TUF               | 89       | 2.15%   |
| ASUS P8H61-M           | 78       | 1.89%   |
| Intel H61              | 68       | 1.64%   |
| HP Compaq              | 67       | 1.62%   |
| ASRock A320M-HD        | 50       | 1.21%   |
| Lenovo ThinkCentre     | 46       | 1.11%   |
| ASUS ROG               | 46       | 1.11%   |
| Intel H55              | 43       | 1.04%   |
| Semp Toshiba STI       | 42       | 1.02%   |
| Gigabyte H61M-S1       | 34       | 0.82%   |
| Gigabyte B75M-D3H      | 33       | 0.8%    |
| Itautec Infoway        | 32       | 0.77%   |
| Gigabyte B450M         | 31       | 0.75%   |
| Gigabyte A320M-S2H     | 31       | 0.75%   |
| ASRock B450M           | 30       | 0.73%   |
| ASRock N68-S3          | 28       | 0.68%   |
| Dell XPS               | 26       | 0.63%   |
| Dell Precision         | 26       | 0.63%   |
| Gigabyte GA-78LMT-USB3 | 25       | 0.6%    |
| Dell Inspiron          | 24       | 0.58%   |
| ASUS P5G41T-M          | 24       | 0.58%   |
| ASUS H61M-A            | 23       | 0.56%   |
| HP EliteDesk           | 22       | 0.53%   |
| Gigabyte B450          | 22       | 0.53%   |
| Gigabyte AB350M-DS3H   | 21       | 0.51%   |
| Intel MAHOBAY          | 20       | 0.48%   |
| Intel B75              | 20       | 0.48%   |
| Gigabyte 970A-DS3P     | 19       | 0.46%   |
| ASUS M4N68T-M          | 19       | 0.46%   |
| ASRock N68-GS4         | 19       | 0.46%   |
| Positivo POS-EIH61CE   | 18       | 0.44%   |
| Intel X99              | 18       | 0.44%   |
| ASUS P5GC-MX           | 18       | 0.44%   |
| ASUS M5A97             | 18       | 0.44%   |
| Gigabyte H110M-H       | 17       | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 445      | 10.76%  |
| 2012    | 436      | 10.54%  |
| 2011    | 436      | 10.54%  |
| 2017    | 348      | 8.41%   |
| 2013    | 322      | 7.78%   |
| 2010    | 299      | 7.23%   |
| 2014    | 289      | 6.99%   |
| 2009    | 268      | 6.48%   |
| 2019    | 265      | 6.41%   |
| 2008    | 220      | 5.32%   |
| 2016    | 188      | 4.54%   |
| 2007    | 182      | 4.4%    |
| 2020    | 172      | 4.16%   |
| 2015    | 100      | 2.42%   |
| 2021    | 66       | 1.6%    |
| 2006    | 60       | 1.45%   |
| 2005    | 17       | 0.41%   |
| 2022    | 13       | 0.31%   |
| 2004    | 5        | 0.12%   |
| Unknown | 5        | 0.12%   |
| 2003    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4137     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4067     | 98.02%  |
| Enabled  | 82       | 1.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4137     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 1036     | 24.5%   |
| 8.01-16.0       | 979      | 23.15%  |
| 16.01-24.0      | 788      | 18.63%  |
| 4.01-8.0        | 762      | 18.02%  |
| 1.01-2.0        | 242      | 5.72%   |
| 32.01-64.0      | 219      | 5.18%   |
| 2.01-3.0        | 78       | 1.84%   |
| 24.01-32.0      | 54       | 1.28%   |
| 64.01-256.0     | 48       | 1.14%   |
| 0.51-1.0        | 19       | 0.45%   |
| Unknown         | 2        | 0.05%   |
| More than 256.0 | 1        | 0.02%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1753     | 38.4%   |
| 2.01-3.0   | 1153     | 25.26%  |
| 3.01-4.0   | 530      | 11.61%  |
| 4.01-8.0   | 523      | 11.46%  |
| 0.51-1.0   | 418      | 9.16%   |
| 8.01-16.0  | 105      | 2.3%    |
| 0.01-0.5   | 60       | 1.31%   |
| 16.01-24.0 | 15       | 0.33%   |
| 24.01-32.0 | 5        | 0.11%   |
| Unknown    | 2        | 0.04%   |
| 32.01-64.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2139     | 49.83%  |
| 2       | 1213     | 28.26%  |
| 3       | 521      | 12.14%  |
| 4       | 235      | 5.47%   |
| 5       | 74       | 1.72%   |
| 0       | 48       | 1.12%   |
| 6       | 42       | 0.98%   |
| 7       | 10       | 0.23%   |
| 8       | 7        | 0.16%   |
| 9       | 3        | 0.07%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2565     | 61.3%   |
| Yes       | 1619     | 38.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4068     | 98.31%  |
| No        | 70       | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2725     | 64.94%  |
| Yes       | 1471     | 35.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3497     | 83.68%  |
| Yes       | 682      | 16.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 4137     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Sao Paulo            | 579      | 13.46%  |
| Rio de Janeiro       | 277      | 6.44%   |
| Brasília            | 121      | 2.81%   |
| Belo Horizonte       | 116      | 2.7%    |
| Porto Alegre         | 100      | 2.32%   |
| Curitiba             | 96       | 2.23%   |
| Fortaleza            | 75       | 1.74%   |
| Campinas             | 59       | 1.37%   |
| Salvador             | 57       | 1.32%   |
| Recife               | 53       | 1.23%   |
| Goiânia             | 48       | 1.12%   |
| Santo André         | 45       | 1.05%   |
| Florianópolis       | 44       | 1.02%   |
| Guarulhos            | 41       | 0.95%   |
| Niterói             | 34       | 0.79%   |
| Manaus               | 34       | 0.79%   |
| Osasco               | 30       | 0.7%    |
| Sorocaba             | 29       | 0.67%   |
| Sao José dos Campos | 28       | 0.65%   |
| Maringá             | 28       | 0.65%   |
| Juiz de Fora         | 28       | 0.65%   |
| Campo Grande         | 28       | 0.65%   |
| Serra                | 27       | 0.63%   |
| Londrina             | 27       | 0.63%   |
| Natal                | 26       | 0.6%    |
| Duque de Caxias      | 26       | 0.6%    |
| Joinville            | 24       | 0.56%   |
| Belém               | 24       | 0.56%   |
| Blumenau             | 22       | 0.51%   |
| Ribeirao Preto       | 20       | 0.46%   |
| Maceió              | 20       | 0.46%   |
| Uberlândia          | 19       | 0.44%   |
| Sao Goncalo          | 19       | 0.44%   |
| Teresina             | 18       | 0.42%   |
| Sao Luís            | 18       | 0.42%   |
| Sao Jose             | 18       | 0.42%   |
| Cuiabá              | 18       | 0.42%   |
| Joao Pessoa          | 17       | 0.4%    |
| Contagem             | 17       | 0.4%    |
| Vitória             | 16       | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 1676     | 2534   | 25.16%  |
| WDC                   | 1253     | 1709   | 18.81%  |
| Samsung Electronics   | 914      | 1311   | 13.72%  |
| Kingston              | 753      | 1019   | 11.3%   |
| Toshiba               | 299      | 354    | 4.49%   |
| SanDisk               | 290      | 414    | 4.35%   |
| Hitachi               | 175      | 210    | 2.63%   |
| China                 | 164      | 189    | 2.46%   |
| Crucial               | 124      | 152    | 1.86%   |
| Maxtor                | 111      | 130    | 1.67%   |
| A-DATA Technology     | 92       | 109    | 1.38%   |
| Silicon Motion        | 82       | 109    | 1.23%   |
| Lexar                 | 50       | 54     | 0.75%   |
| XPG                   | 41       | 51     | 0.62%   |
| Realtek Semiconductor | 41       | 51     | 0.62%   |
| Unknown               | 40       | 56     | 0.6%    |
| KingSpec              | 38       | 45     | 0.57%   |
| Intel                 | 34       | 39     | 0.51%   |
| Corsair               | 34       | 46     | 0.51%   |
| Phison                | 33       | 51     | 0.5%    |
| HGST                  | 29       | 34     | 0.44%   |
| Hewlett-Packard       | 23       | 28     | 0.35%   |
| PNY                   | 19       | 20     | 0.29%   |
| JMicron Technology    | 19       | 21     | 0.29%   |
| Patriot               | 18       | 27     | 0.27%   |
| Gigabyte Technology   | 17       | 25     | 0.26%   |
| Netac                 | 16       | 25     | 0.24%   |
| XrayDisk              | 14       | 18     | 0.21%   |
| KingDian              | 14       | 15     | 0.21%   |
| LITEON                | 13       | 13     | 0.2%    |
| OCZ                   | 11       | 11     | 0.17%   |
| Fujitsu               | 11       | 12     | 0.17%   |
| Smart                 | 9        | 11     | 0.14%   |
| SK hynix              | 9        | 22     | 0.14%   |
| ExcelStor             | 9        | 10     | 0.14%   |
| Unknown               | 9        | 9      | 0.14%   |
| ADATA Technology      | 8        | 12     | 0.12%   |
| WALRAM                | 7        | 7      | 0.11%   |
| Phison Electronics    | 7        | 8      | 0.11%   |
| BHT                   | 7        | 11     | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 252      | 3.4%    |
| Seagate ST500DM002-1BD142 500GB     | 235      | 3.17%   |
| Seagate ST1000DM010-2EP102 1TB      | 187      | 2.52%   |
| Kingston SA400S37120G 120GB SSD     | 154      | 2.08%   |
| Samsung HD322HJ 320GB               | 113      | 1.53%   |
| Kingston SA400S37480G 480GB SSD     | 111      | 1.5%    |
| Samsung HD161HJ 160GB               | 96       | 1.3%    |
| Samsung HD502HJ 500GB               | 94       | 1.27%   |
| Samsung HD502HI 500GB               | 92       | 1.24%   |
| Seagate ST1000DM003-1ER162 1TB      | 91       | 1.23%   |
| Seagate ST1000DM003-1CH162 1TB      | 84       | 1.13%   |
| Kingston SV300S37A120G 120GB SSD    | 74       | 1%      |
| WDC WD5000AAKX-003CA0 500GB         | 73       | 0.99%   |
| WDC WD10EARS-00Y5B1 1TB             | 64       | 0.86%   |
| Seagate ST3500418AS 500GB           | 63       | 0.85%   |
| Seagate ST3500312CS 500GB           | 61       | 0.82%   |
| SanDisk SSD PLUS 240GB              | 61       | 0.82%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 57       | 0.77%   |
| WDC WD10EZEX-00BN5A0 1TB            | 54       | 0.73%   |
| Seagate ST31000524AS 1TB            | 54       | 0.73%   |
| WDC WD10EZEX-00WN4A0 1TB            | 53       | 0.72%   |
| Seagate Expansion 4TB               | 53       | 0.72%   |
| Toshiba DT01ACA050 500GB            | 52       | 0.7%    |
| Seagate ST2000DM006-2DM164 2TB      | 52       | 0.7%    |
| WDC WD5000AAKX-00U6AA0 500GB        | 50       | 0.67%   |
| Crucial CT240BX500SSD1 240GB        | 50       | 0.67%   |
| Toshiba HDWD110 1TB                 | 48       | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 47       | 0.63%   |
| Seagate ST3320418AS 320GB           | 45       | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 45       | 0.61%   |
| SanDisk SDSSDA120G 120GB            | 45       | 0.61%   |
| Samsung HD103SI 1TB                 | 43       | 0.58%   |
| Samsung HD161GJ 160GB               | 42       | 0.57%   |
| Samsung HD103SJ 1TB                 | 42       | 0.57%   |
| SanDisk SDSSDA240G 240GB            | 40       | 0.54%   |
| Seagate ST3500413AS 500GB           | 39       | 0.53%   |
| Seagate ST31000528AS 1TB            | 39       | 0.53%   |
| Toshiba DT01ACA100 1TB              | 38       | 0.51%   |
| SanDisk SSD PLUS 120GB              | 38       | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB      | 34       | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1671     | 2517   | 39.52%  |
| WDC                 | 1122     | 1514   | 26.54%  |
| Samsung Electronics | 782      | 1060   | 18.5%   |
| Toshiba             | 287      | 339    | 6.79%   |
| Hitachi             | 175      | 210    | 4.14%   |
| Maxtor              | 106      | 124    | 2.51%   |
| HGST                | 29       | 34     | 0.69%   |
| Hewlett-Packard     | 13       | 15     | 0.31%   |
| Fujitsu             | 11       | 12     | 0.26%   |
| Unknown             | 9        | 9      | 0.21%   |
| ExcelStor           | 9        | 10     | 0.21%   |
| JMicron Technology  | 2        | 3      | 0.05%   |
| USB3.0              | 1        | 1      | 0.02%   |
| SAGE                | 1        | 2      | 0.02%   |
| MDT                 | 1        | 1      | 0.02%   |
| Lenovo              | 1        | 1      | 0.02%   |
| Initio              | 1        | 1      | 0.02%   |
| IBM                 | 1        | 3      | 0.02%   |
| HGST HTS            | 1        | 1      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| China               | 1        | 1      | 0.02%   |
| ASMT                | 1        | 1      | 0.02%   |
| Apple               | 1        | 1      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 733      | 984    | 37.04%  |
| SanDisk             | 262      | 373    | 13.24%  |
| China               | 163      | 188    | 8.24%   |
| WDC                 | 141      | 176    | 7.12%   |
| Crucial             | 119      | 146    | 6.01%   |
| Samsung Electronics | 97       | 177    | 4.9%    |
| A-DATA Technology   | 72       | 81     | 3.64%   |
| Lexar               | 50       | 54     | 2.53%   |
| KingSpec            | 38       | 45     | 1.92%   |
| Corsair             | 27       | 36     | 1.36%   |
| Intel               | 25       | 28     | 1.26%   |
| PNY                 | 17       | 18     | 0.86%   |
| Patriot             | 17       | 25     | 0.86%   |
| JMicron Technology  | 16       | 17     | 0.81%   |
| KingDian            | 14       | 15     | 0.71%   |
| Netac               | 12       | 20     | 0.61%   |
| Gigabyte Technology | 12       | 19     | 0.61%   |
| OCZ                 | 11       | 11     | 0.56%   |
| Smart               | 9        | 11     | 0.45%   |
| LITEON              | 9        | 9      | 0.45%   |
| Toshiba             | 8        | 10     | 0.4%    |
| Seagate             | 7        | 8      | 0.35%   |
| Hewlett-Packard     | 7        | 9      | 0.35%   |
| Unknown             | 7        | 7      | 0.35%   |
| Unknown             | 6        | 6      | 0.3%    |
| BHT                 | 6        | 10     | 0.3%    |
| Team                | 5        | 5      | 0.25%   |
| Maxtor              | 5        | 6      | 0.25%   |
| SK hynix            | 4        | 5      | 0.2%    |
| RZX                 | 4        | 7      | 0.2%    |
| HS-SSD-C100         | 4        | 4      | 0.2%    |
| Apacer              | 4        | 4      | 0.2%    |
| XrayDisk            | 3        | 3      | 0.15%   |
| Plextor             | 3        | 4      | 0.15%   |
| Pichau              | 3        | 3      | 0.15%   |
| KODAK               | 3        | 3      | 0.15%   |
| KINGBANK            | 3        | 5      | 0.15%   |
| Colorful            | 3        | 3      | 0.15%   |
| Zheino              | 2        | 5      | 0.1%    |
| WALRAM              | 2        | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3369     | 5863   | 60.52%  |
| SSD     | 1725     | 2601   | 30.99%  |
| NVMe    | 404      | 595    | 7.26%   |
| Unknown | 64       | 89     | 1.15%   |
| MMC     | 5        | 6      | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3983     | 8330   | 87.65%  |
| NVMe | 402      | 592    | 8.85%   |
| SAS  | 154      | 226    | 3.39%   |
| MMC  | 5        | 6      | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3315     | 5626   | 63.01%  |
| 0.51-1.0   | 1405     | 2058   | 26.71%  |
| 1.01-2.0   | 317      | 453    | 6.03%   |
| 3.01-4.0   | 116      | 177    | 2.2%    |
| 2.01-3.0   | 62       | 84     | 1.18%   |
| 4.01-10.0  | 42       | 60     | 0.8%    |
| 10.01-20.0 | 4        | 6      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1096     | 24.9%   |
| 251-500        | 1007     | 22.88%  |
| 501-1000       | 638      | 14.49%  |
| 1001-2000      | 433      | 9.84%   |
| 1-20           | 342      | 7.77%   |
| 51-100         | 303      | 6.88%   |
| 21-50          | 176      | 4%      |
| 2001-3000      | 165      | 3.75%   |
| More than 3000 | 142      | 3.23%   |
| Unknown        | 100      | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1732     | 38.37%  |
| 21-50          | 796      | 17.63%  |
| 101-250        | 528      | 11.7%   |
| 51-100         | 463      | 10.26%  |
| 251-500        | 326      | 7.22%   |
| 501-1000       | 314      | 6.96%   |
| 1001-2000      | 159      | 3.52%   |
| Unknown        | 100      | 2.22%   |
| 2001-3000      | 51       | 1.13%   |
| More than 3000 | 45       | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 41       | 44     | 5.82%   |
| WDC WD5000AAKX-003CA0 500GB         | 24       | 24     | 3.4%    |
| Samsung Electronics HD322HJ 320GB   | 20       | 24     | 2.84%   |
| Samsung Electronics HD161HJ 160GB   | 17       | 18     | 2.41%   |
| Samsung Electronics HD502HI 500GB   | 16       | 18     | 2.27%   |
| Samsung Electronics HD502HJ 500GB   | 14       | 14     | 1.99%   |
| WDC WD10EARS-00Y5B1 1TB             | 11       | 13     | 1.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10       | 10     | 1.42%   |
| WDC WD3200AAJS-00L7A0 320GB         | 9        | 9      | 1.28%   |
| Seagate ST3500418AS 500GB           | 9        | 13     | 1.28%   |
| Samsung Electronics HD080HJ/ 80GB   | 9        | 11     | 1.28%   |
| Maxtor STM3160215AS 160GB           | 9        | 10     | 1.28%   |
| Seagate ST3320418AS 320GB           | 8        | 12     | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB      | 8        | 11     | 1.13%   |
| Samsung Electronics HD250HJ 250GB   | 8        | 9      | 1.13%   |
| Samsung Electronics HD103SJ 1TB     | 8        | 10     | 1.13%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7        | 7      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7        | 8      | 0.99%   |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 9      | 0.99%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6        | 7      | 0.85%   |
| Seagate ST31000524AS 1TB            | 6        | 6      | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB      | 6        | 7      | 0.85%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 6      | 0.85%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 9      | 0.85%   |
| WDC WD5000AAKX-083CA1 500GB         | 5        | 5      | 0.71%   |
| Toshiba MQ01ABD050 500GB            | 5        | 5      | 0.71%   |
| Toshiba DT01ACA050 500GB            | 5        | 5      | 0.71%   |
| Seagate ST3500413AS 500GB           | 5        | 6      | 0.71%   |
| Seagate ST3500312CS 500GB           | 5        | 5      | 0.71%   |
| Seagate ST3250318AS 250GB           | 5        | 5      | 0.71%   |
| Seagate ST3160318AS 160GB           | 5        | 5      | 0.71%   |
| Seagate ST31000528AS 1TB            | 5        | 8      | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 7      | 0.71%   |
| Samsung Electronics HD103SI 1TB     | 5        | 6      | 0.71%   |
| Samsung Electronics HD081GJ 80GB    | 5        | 5      | 0.71%   |
| Maxtor STM3250310AS 250GB           | 5        | 5      | 0.71%   |
| Kingston SV300S37A120G 120GB SSD    | 5        | 5      | 0.71%   |
| Kingston SA400S37480G 480GB SSD     | 5        | 6      | 0.71%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4        | 5      | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 4      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 214      | 268    | 32.42%  |
| WDC                 | 167      | 189    | 25.3%   |
| Samsung Electronics | 137      | 168    | 20.76%  |
| Hitachi             | 32       | 33     | 4.85%   |
| Toshiba             | 27       | 29     | 4.09%   |
| Kingston            | 23       | 27     | 3.48%   |
| Maxtor              | 19       | 20     | 2.88%   |
| SanDisk             | 6        | 6      | 0.91%   |
| China               | 6        | 6      | 0.91%   |
| XPG                 | 4        | 4      | 0.61%   |
| Intel               | 3        | 3      | 0.45%   |
| A-DATA Technology   | 3        | 3      | 0.45%   |
| OCZ                 | 2        | 2      | 0.3%    |
| Crucial             | 2        | 2      | 0.3%    |
| Unknown             | 2        | 2      | 0.3%    |
| PNY                 | 1        | 1      | 0.15%   |
| Plextor             | 1        | 1      | 0.15%   |
| OCZ-VERTEX3         | 1        | 1      | 0.15%   |
| Netac               | 1        | 1      | 0.15%   |
| Mushkin             | 1        | 1      | 0.15%   |
| Initio              | 1        | 1      | 0.15%   |
| HGST                | 1        | 1      | 0.15%   |
| Hewlett-Packard     | 1        | 1      | 0.15%   |
| Fujitsu             | 1        | 1      | 0.15%   |
| FEASSO              | 1        | 2      | 0.15%   |
| ExcelStor           | 1        | 2      | 0.15%   |
| EGON                | 1        | 1      | 0.15%   |
| Corsair             | 1        | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 214      | 268    | 35.91%  |
| WDC                 | 161      | 183    | 27.01%  |
| Samsung Electronics | 137      | 168    | 22.99%  |
| Hitachi             | 32       | 33     | 5.37%   |
| Toshiba             | 27       | 29     | 4.53%   |
| Maxtor              | 19       | 20     | 3.19%   |
| Initio              | 1        | 1      | 0.17%   |
| HGST                | 1        | 1      | 0.17%   |
| Hewlett-Packard     | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 1      | 0.17%   |
| FEASSO              | 1        | 2      | 0.17%   |
| ExcelStor           | 1        | 2      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 519      | 709    | 89.18%  |
| SSD  | 56       | 61     | 9.62%   |
| NVMe | 7        | 7      | 1.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 15.38%  |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 7.69%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 7.69%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 7.69%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD502HJ 500GB | 1        | 3      | 7.69%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 7.69%   |
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 7.69%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 38.46%  |
| Samsung Electronics | 5        | 7      | 38.46%  |
| WDC                 | 1        | 1      | 7.69%   |
| Toshiba             | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2849     | 6350   | 62.96%  |
| Works    | 1105     | 2012   | 24.42%  |
| Malfunc  | 558      | 777    | 12.33%  |
| Failed   | 13       | 15     | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2728     | 56.75%  |
| AMD                              | 1135     | 23.61%  |
| Nvidia                           | 211      | 4.39%   |
| Silicon Motion                   | 93       | 1.93%   |
| JMicron Technology               | 77       | 1.6%    |
| Marvell Technology Group         | 75       | 1.56%   |
| ASMedia Technology               | 65       | 1.35%   |
| Realtek Semiconductor            | 63       | 1.31%   |
| Samsung Electronics              | 58       | 1.21%   |
| Phison Electronics               | 52       | 1.08%   |
| VIA Technologies                 | 48       | 1%      |
| SanDisk                          | 48       | 1%      |
| ADATA Technology                 | 44       | 0.92%   |
| Kingston Technology Company      | 28       | 0.58%   |
| Micron/Crucial Technology        | 12       | 0.25%   |
| LSI Logic / Symbios Logic        | 9        | 0.19%   |
| Silicon Integrated Systems [SiS] | 8        | 0.17%   |
| Broadcom / LSI                   | 8        | 0.17%   |
| Lite-On Technology               | 6        | 0.12%   |
| Silicon Image                    | 5        | 0.1%    |
| SK hynix                         | 4        | 0.08%   |
| Seagate Technology               | 4        | 0.08%   |
| OCZ Technology Group             | 4        | 0.08%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.08%   |
| Beijing Starblaze Technology     | 4        | 0.08%   |
| Adaptec                          | 3        | 0.06%   |
| Shenzhen Longsys Electronics     | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Micron Technology                | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| INNOGRIT                         | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 625      | 9.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 543      | 7.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 417      | 6.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 373      | 5.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 288      | 4.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 279      | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 230      | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 230      | 3.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 220      | 3.21%   |
| AMD FCH SATA Controller D                                                               | 206      | 3.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 200      | 2.92%   |
| Nvidia MCP61 SATA Controller                                                            | 173      | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 154      | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 154      | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 145      | 2.12%   |
| Nvidia MCP61 IDE                                                                        | 141      | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 105      | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 99       | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 86       | 1.26%   |
| Intel SATA Controller [RAID mode]                                                       | 84       | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 80       | 1.17%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 78       | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                                  | 77       | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 64       | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 62       | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 55       | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 55       | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 53       | 0.77%   |
| AMD 500 Series Chipset SATA Controller                                                  | 52       | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 46       | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 46       | 0.67%   |
| AMD FCH IDE Controller                                                                  | 41       | 0.6%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 39       | 0.57%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 38       | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 37       | 0.54%   |
| JMicron JMB368 IDE controller                                                           | 35       | 0.51%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 34       | 0.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 33       | 0.48%   |
| Phison E12 NVMe Controller                                                              | 31       | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2758     | 55.28%  |
| IDE  | 1688     | 33.83%  |
| NVMe | 408      | 8.18%   |
| RAID | 119      | 2.39%   |
| SCSI | 10       | 0.2%    |
| SAS  | 6        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 2793     | 67.51%  |
| AMD          | 1338     | 32.34%  |
| CentaurHauls | 5        | 0.12%   |
| Unknown      | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 89       | 2.14%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 75       | 1.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 72       | 1.73%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 71       | 1.71%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 59       | 1.42%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 59       | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor           | 55       | 1.32%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 54       | 1.3%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 53       | 1.27%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 53       | 1.27%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 52       | 1.25%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 51       | 1.23%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 50       | 1.2%    |
| Intel Celeron CPU J1800 @ 2.41GHz           | 50       | 1.2%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 46       | 1.11%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 45       | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 43       | 1.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 43       | 1.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 40       | 0.96%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 38       | 0.91%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 37       | 0.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 34       | 0.82%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 32       | 0.77%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.72%   |
| AMD FX-8300 Eight-Core Processor            | 30       | 0.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 29       | 0.7%    |
| Intel Core i3-7100 CPU @ 3.90GHz            | 28       | 0.67%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 28       | 0.67%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 27       | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 27       | 0.65%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 27       | 0.65%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 26       | 0.62%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 26       | 0.62%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 26       | 0.62%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 25       | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 25       | 0.6%    |
| Intel Core i5-4440 CPU @ 3.10GHz            | 25       | 0.6%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 25       | 0.6%    |
| AMD FX-8350 Eight-Core Processor            | 25       | 0.6%    |
| AMD FX-4300 Quad-Core Processor             | 25       | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 695      | 16.72%  |
| Intel Core i3           | 485      | 11.67%  |
| Intel Core i7           | 384      | 9.24%   |
| AMD Ryzen 5             | 320      | 7.7%    |
| AMD FX                  | 246      | 5.92%   |
| Intel Core 2 Duo        | 225      | 5.41%   |
| Intel Celeron           | 216      | 5.2%    |
| Intel Xeon              | 181      | 4.35%   |
| Intel Pentium Dual-Core | 168      | 4.04%   |
| AMD Ryzen 7             | 134      | 3.22%   |
| Intel Pentium           | 120      | 2.89%   |
| Intel Core 2 Quad       | 96       | 2.31%   |
| AMD Ryzen 3             | 87       | 2.09%   |
| Intel Pentium Dual      | 71       | 1.71%   |
| AMD Phenom II X4        | 71       | 1.71%   |
| AMD Athlon II X2        | 67       | 1.61%   |
| AMD Athlon 64 X2        | 42       | 1.01%   |
| AMD A8                  | 38       | 0.91%   |
| AMD Athlon              | 36       | 0.87%   |
| AMD A10                 | 36       | 0.87%   |
| Intel Core 2            | 32       | 0.77%   |
| Intel Atom              | 31       | 0.75%   |
| AMD A4                  | 31       | 0.75%   |
| AMD Sempron             | 30       | 0.72%   |
| AMD Ryzen 9             | 29       | 0.7%    |
| Intel Pentium 4         | 28       | 0.67%   |
| AMD Phenom II X6        | 26       | 0.63%   |
| AMD A6                  | 23       | 0.55%   |
| Intel Pentium Gold      | 19       | 0.46%   |
| AMD Athlon II X4        | 18       | 0.43%   |
| Other                   | 17       | 0.41%   |
| Intel Core i9           | 17       | 0.41%   |
| AMD Phenom II X2        | 17       | 0.41%   |
| AMD Phenom              | 14       | 0.34%   |
| Intel Pentium D         | 13       | 0.31%   |
| Intel Genuine           | 13       | 0.31%   |
| AMD Athlon II X3        | 13       | 0.31%   |
| AMD Ryzen 3 PRO         | 7        | 0.17%   |
| AMD E                   | 6        | 0.14%   |
| CentaurHauls VIA C7     | 5        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1622     | 39.03%  |
| 4       | 1488     | 35.8%   |
| 6       | 451      | 10.85%  |
| 8       | 201      | 4.84%   |
| 1       | 177      | 4.26%   |
| 3       | 128      | 3.08%   |
| 12      | 41       | 0.99%   |
| 16      | 15       | 0.36%   |
| 10      | 15       | 0.36%   |
| Unknown | 11       | 0.26%   |
| 24      | 3        | 0.07%   |
| 14      | 2        | 0.05%   |
| 28      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4118     | 99.52%  |
| 2       | 19       | 0.46%   |
| Unknown | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2117     | 51.1%   |
| 2       | 2015     | 48.64%  |
| Unknown | 11       | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3893     | 93.47%  |
| Unknown        | 228      | 5.47%   |
| 64-bit         | 29       | 0.7%    |
| 32-bit         | 15       | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 769      | 18.01%  |
| 0x306a9    | 364      | 8.52%   |
| 0x206a7    | 360      | 8.43%   |
| 0x1067a    | 353      | 8.27%   |
| 0x306c3    | 290      | 6.79%   |
| 0x06000852 | 147      | 3.44%   |
| 0x906e9    | 120      | 2.81%   |
| 0x010000c8 | 108      | 2.53%   |
| 0x906ea    | 107      | 2.51%   |
| 0x6fd      | 98       | 2.3%    |
| 0x0800820d | 77       | 1.8%    |
| 0x08701021 | 71       | 1.66%   |
| 0x20655    | 69       | 1.62%   |
| 0x08108109 | 69       | 1.62%   |
| 0x08701013 | 51       | 1.19%   |
| 0x6fb      | 50       | 1.17%   |
| 0x506e3    | 46       | 1.08%   |
| 0x306f2    | 45       | 1.05%   |
| 0x20652    | 45       | 1.05%   |
| 0x10676    | 42       | 0.98%   |
| 0x06001119 | 38       | 0.89%   |
| 0x30678    | 35       | 0.82%   |
| 0x08101016 | 35       | 0.82%   |
| 0x106e5    | 33       | 0.77%   |
| 0x08001138 | 32       | 0.75%   |
| 0x010000db | 31       | 0.73%   |
| 0x06003106 | 29       | 0.68%   |
| 0xa0653    | 27       | 0.63%   |
| 0x906ed    | 27       | 0.63%   |
| 0x306e4    | 27       | 0.63%   |
| 0x0600611a | 27       | 0.63%   |
| 0x906eb    | 26       | 0.61%   |
| 0x10661    | 25       | 0.59%   |
| 0x010000dc | 25       | 0.59%   |
| 0x0810100b | 24       | 0.56%   |
| 0x0600063e | 24       | 0.56%   |
| 0x206d7    | 20       | 0.47%   |
| 0x08001137 | 20       | 0.47%   |
| 0x6f2      | 18       | 0.42%   |
| 0x08108102 | 17       | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 460      | 11.1%   |
| Penryn           | 452      | 10.9%   |
| SandyBridge      | 434      | 10.47%  |
| Haswell          | 394      | 9.5%    |
| KabyLake         | 342      | 8.25%   |
| K10              | 256      | 6.17%   |
| Piledriver       | 255      | 6.15%   |
| Core             | 229      | 5.52%   |
| Zen+             | 208      | 5.02%   |
| Zen              | 179      | 4.32%   |
| Zen 2            | 160      | 3.86%   |
| Westmere         | 139      | 3.35%   |
| Silvermont       | 68       | 1.64%   |
| Skylake          | 66       | 1.59%   |
| K8 Hammer        | 63       | 1.52%   |
| Zen 3            | 59       | 1.42%   |
| CometLake        | 57       | 1.37%   |
| Nehalem          | 53       | 1.28%   |
| NetBurst         | 49       | 1.18%   |
| Bulldozer        | 40       | 0.96%   |
| Steamroller      | 36       | 0.87%   |
| Excavator        | 34       | 0.82%   |
| Bonnell          | 26       | 0.63%   |
| Bobcat           | 17       | 0.41%   |
| Jaguar           | 16       | 0.39%   |
| K10 Llano        | 13       | 0.31%   |
| Unknown          | 11       | 0.27%   |
| Broadwell        | 10       | 0.24%   |
| Goldmont plus    | 9        | 0.22%   |
| Icelake          | 6        | 0.14%   |
| Alderlake Hybrid | 3        | 0.07%   |
| Puma             | 1        | 0.02%   |
| K6               | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1582     | 36.37%  |
| Nvidia                           | 1509     | 34.69%  |
| AMD                              | 1207     | 27.75%  |
| VIA Technologies                 | 31       | 0.71%   |
| Matrox Electronics Systems       | 7        | 0.16%   |
| Silicon Integrated Systems [SiS] | 5        | 0.11%   |
| Silicon Motion                   | 4        | 0.09%   |
| ATI Technologies                 | 3        | 0.07%   |
| S3 Graphics                      | 1        | 0.02%   |
| ASPEED Technology                | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 261      | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 226      | 5.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 174      | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 154      | 3.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 152      | 3.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 147      | 3.31%   |
| Nvidia GT218 [GeForce 210]                                                  | 139      | 3.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 97       | 2.19%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 95       | 2.14%   |
| Intel Core Processor Integrated Graphics Controller                         | 94       | 2.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 84       | 1.89%   |
| AMD RS780L [Radeon 3000]                                                    | 77       | 1.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 77       | 1.74%   |
| Nvidia GK208B [GeForce GT 710]                                              | 70       | 1.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 65       | 1.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 65       | 1.46%   |
| Intel HD Graphics 630                                                       | 64       | 1.44%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 59       | 1.33%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 56       | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 56       | 1.26%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 56       | 1.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 50       | 1.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 49       | 1.1%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 47       | 1.06%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 46       | 1.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 44       | 0.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 43       | 0.97%   |
| Nvidia GF108 [GeForce GT 730]                                               | 37       | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 34       | 0.77%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 33       | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 32       | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 31       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 30       | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 28       | 0.63%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 28       | 0.63%   |
| AMD RS880 [Radeon HD 4200]                                                  | 28       | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 27       | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 27       | 0.61%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 27       | 0.61%   |
| Intel HD Graphics 530                                                       | 26       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 1454     | 34.66%  |
| 1 x Nvidia              | 1423     | 33.92%  |
| 1 x AMD                 | 1141     | 27.2%   |
| Intel + Nvidia          | 41       | 0.98%   |
| 2 x AMD                 | 33       | 0.79%   |
| 1 x VIA                 | 30       | 0.72%   |
| AMD + Nvidia            | 19       | 0.45%   |
| Intel + AMD             | 18       | 0.43%   |
| 2 x Nvidia              | 14       | 0.33%   |
| 1 x Matrox              | 6        | 0.14%   |
| 1 x SiS                 | 5        | 0.12%   |
| Intel + Silicon Motion  | 2        | 0.05%   |
| Other                   | 1        | 0.02%   |
| 2 x Intel               | 1        | 0.02%   |
| 1 x Silicon Motion      | 1        | 0.02%   |
| 1 x S3 Graphics         | 1        | 0.02%   |
| Nvidia + Silicon Motion | 1        | 0.02%   |
| Intel + 2 x AMD         | 1        | 0.02%   |
| 1 x ASPEED              | 1        | 0.02%   |
| AMD + 2 x Nvidia        | 1        | 0.02%   |
| AMD + Matrox            | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3195     | 76.04%  |
| Proprietary | 799      | 19.01%  |
| Unknown     | 208      | 4.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1876     | 43.94%  |
| 1.01-2.0   | 652      | 15.27%  |
| 0.51-1.0   | 584      | 13.68%  |
| 0.01-0.5   | 468      | 10.96%  |
| 3.01-4.0   | 358      | 8.39%   |
| 7.01-8.0   | 158      | 3.7%    |
| 5.01-6.0   | 110      | 2.58%   |
| 2.01-3.0   | 40       | 0.94%   |
| 8.01-16.0  | 19       | 0.45%   |
| 4.01-5.0   | 2        | 0.05%   |
| 16.01-24.0 | 2        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 1088     | 26.67%  |
| Samsung Electronics  | 922      | 22.6%   |
| AOC                  | 613      | 15.03%  |
| Dell                 | 321      | 7.87%   |
| Philips              | 220      | 5.39%   |
| LG Electronics       | 141      | 3.46%   |
| Acer                 | 134      | 3.29%   |
| Hewlett-Packard      | 83       | 2.03%   |
| BenQ                 | 54       | 1.32%   |
| Sony                 | 49       | 1.2%    |
| Unknown              | 48       | 1.18%   |
| Positivo             | 36       | 0.88%   |
| Lenovo               | 34       | 0.83%   |
| Ancor Communications | 21       | 0.51%   |
| Panasonic            | 16       | 0.39%   |
| ASUSTek Computer     | 15       | 0.37%   |
| TXD                  | 12       | 0.29%   |
| GDH                  | 12       | 0.29%   |
| Daewoo               | 12       | 0.29%   |
| NCS                  | 11       | 0.27%   |
| HB@                  | 10       | 0.25%   |
| Toshiba              | 9        | 0.22%   |
| RTK                  | 9        | 0.22%   |
| Envision             | 9        | 0.22%   |
| VIE                  | 8        | 0.2%    |
| AGO                  | 8        | 0.2%    |
| Unknown (XXX)        | 7        | 0.17%   |
| JRY                  | 7        | 0.17%   |
| ___                  | 6        | 0.15%   |
| STA                  | 6        | 0.15%   |
| SKY                  | 6        | 0.15%   |
| PZG                  | 6        | 0.15%   |
| MSI                  | 6        | 0.15%   |
| Envision Peripherals | 6        | 0.15%   |
| CVT                  | 6        | 0.15%   |
| Proview              | 5        | 0.12%   |
| MStar                | 5        | 0.12%   |
| Semp Toshiba         | 4        | 0.1%    |
| Philco               | 4        | 0.1%    |
| AU Optronics         | 4        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 89       | 2.04%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 58       | 1.33%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 52       | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 49       | 1.12%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 43       | 0.99%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 35       | 0.8%    |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 30       | 0.69%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 30       | 0.69%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 29       | 0.67%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 27       | 0.62%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 26       | 0.6%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 26       | 0.6%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 26       | 0.6%    |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 24       | 0.55%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                       | 24       | 0.55%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 23       | 0.53%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 22       | 0.5%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 22       | 0.5%    |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                | 21       | 0.48%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 20       | 0.46%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 19       | 0.44%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                       | 19       | 0.44%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 19       | 0.44%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 18       | 0.41%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 18       | 0.41%   |
| AOC 1619w AOC1619 1366x768 340x190mm 15.3-inch                       | 18       | 0.41%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 17       | 0.39%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 17       | 0.39%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch               | 17       | 0.39%   |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                       | 17       | 0.39%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 16       | 0.37%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 16       | 0.37%   |
| Positivo LCD Monitor NON1801 1360x768 410x230mm 18.5-inch            | 16       | 0.37%   |
| AOC 712Sa AOC1712 1280x1024 340x270mm 17.1-inch                      | 16       | 0.37%   |
| Goldstar L1552S GSM3BAE 1024x768 304x228mm 15.0-inch                 | 15       | 0.34%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 15       | 0.34%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 14       | 0.32%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch | 14       | 0.32%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                  | 14       | 0.32%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                   | 14       | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1387     | 33.69%  |
| 1366x768 (WXGA)    | 668      | 16.23%  |
| 1600x900 (HD+)     | 308      | 7.48%   |
| 1440x900 (WXGA+)   | 287      | 6.97%   |
| 1280x1024 (SXGA)   | 278      | 6.75%   |
| 1360x768           | 251      | 6.1%    |
| 2560x1080          | 206      | 5%      |
| 3840x2160 (4K)     | 156      | 3.79%   |
| 1680x1050 (WSXGA+) | 140      | 3.4%    |
| 1024x768 (XGA)     | 94       | 2.28%   |
| Unknown            | 92       | 2.23%   |
| 2560x1440 (QHD)    | 42       | 1.02%   |
| 1280x720 (HD)      | 36       | 0.87%   |
| 3840x1080          | 26       | 0.63%   |
| 1920x540           | 18       | 0.44%   |
| 1920x1200 (WUXGA)  | 15       | 0.36%   |
| 2288x1287          | 12       | 0.29%   |
| 3440x1440          | 11       | 0.27%   |
| 1152x864           | 9        | 0.22%   |
| 4480x1080          | 6        | 0.15%   |
| 1280x800 (WXGA)    | 6        | 0.15%   |
| 5760x1080          | 4        | 0.1%    |
| 3360x1080          | 4        | 0.1%    |
| 3286x1080          | 4        | 0.1%    |
| 3200x1080          | 4        | 0.1%    |
| 1600x1200          | 4        | 0.1%    |
| 3520x1080          | 3        | 0.07%   |
| 2732x768           | 3        | 0.07%   |
| 6400x1080          | 2        | 0.05%   |
| 3360x1050          | 2        | 0.05%   |
| 2800x900           | 2        | 0.05%   |
| 2720x1024          | 2        | 0.05%   |
| 2646x768           | 2        | 0.05%   |
| 2646x1024          | 2        | 0.05%   |
| 2560x1600          | 2        | 0.05%   |
| 1280x960           | 2        | 0.05%   |
| 640x480            | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5440x1080          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 631      | 15.26%  |
| 21      | 489      | 11.82%  |
| 23      | 434      | 10.49%  |
| Unknown | 434      | 10.49%  |
| 17      | 316      | 7.64%   |
| 15      | 262      | 6.33%   |
| 19      | 229      | 5.54%   |
| 20      | 225      | 5.44%   |
| 24      | 218      | 5.27%   |
| 27      | 176      | 4.26%   |
| 34      | 172      | 4.16%   |
| 22      | 93       | 2.25%   |
| 31      | 72       | 1.74%   |
| 72      | 41       | 0.99%   |
| 32      | 35       | 0.85%   |
| 28      | 31       | 0.75%   |
| 40      | 29       | 0.7%    |
| 84      | 28       | 0.68%   |
| 54      | 26       | 0.63%   |
| 26      | 25       | 0.6%    |
| 16      | 22       | 0.53%   |
| 46      | 21       | 0.51%   |
| 52      | 17       | 0.41%   |
| 14      | 16       | 0.39%   |
| 12      | 16       | 0.39%   |
| 13      | 12       | 0.29%   |
| 142     | 8        | 0.19%   |
| 47      | 8        | 0.19%   |
| 48      | 6        | 0.15%   |
| 39      | 5        | 0.12%   |
| 37      | 5        | 0.12%   |
| 25      | 5        | 0.12%   |
| 65      | 3        | 0.07%   |
| 50      | 3        | 0.07%   |
| 43      | 3        | 0.07%   |
| 41      | 3        | 0.07%   |
| 38      | 2        | 0.05%   |
| 29      | 2        | 0.05%   |
| 8       | 2        | 0.05%   |
| 75      | 1        | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 1559     | 38.77%  |
| 501-600        | 786      | 19.55%  |
| 301-350        | 504      | 12.53%  |
| Unknown        | 434      | 10.79%  |
| 701-800        | 207      | 5.15%   |
| 351-400        | 154      | 3.83%   |
| 601-700        | 127      | 3.16%   |
| 1001-1500      | 88       | 2.19%   |
| 1501-2000      | 70       | 1.74%   |
| 801-900        | 41       | 1.02%   |
| 201-300        | 34       | 0.85%   |
| More than 2000 | 8        | 0.2%    |
| 901-1000       | 7        | 0.17%   |
| 101-200        | 2        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2495     | 64.11%  |
| Unknown | 387      | 9.94%   |
| 16/10   | 371      | 9.53%   |
| 5/4     | 275      | 7.07%   |
| 21/9    | 189      | 4.86%   |
| 4/3     | 131      | 3.37%   |
| 3/2     | 32       | 0.82%   |
| 1.00    | 8        | 0.21%   |
| 6/5     | 1        | 0.03%   |
| 32/9    | 1        | 0.03%   |
| 2.00    | 1        | 0.03%   |
| 0.31    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1039     | 25.44%  |
| 141-150        | 797      | 19.52%  |
| 151-200        | 622      | 15.23%  |
| Unknown        | 434      | 10.63%  |
| 351-500        | 290      | 7.1%    |
| 101-110        | 238      | 5.83%   |
| 301-350        | 178      | 4.36%   |
| More than 1000 | 136      | 3.33%   |
| 251-300        | 91       | 2.23%   |
| 131-140        | 86       | 2.11%   |
| 501-1000       | 79       | 1.93%   |
| 111-120        | 29       | 0.71%   |
| 81-90          | 17       | 0.42%   |
| 71-80          | 16       | 0.39%   |
| 91-100         | 16       | 0.39%   |
| 121-130        | 12       | 0.29%   |
| 1-40           | 2        | 0.05%   |
| 51-60          | 1        | 0.02%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2530     | 64.36%  |
| 101-120 | 689      | 17.53%  |
| Unknown | 435      | 11.07%  |
| 1-50    | 198      | 5.04%   |
| 121-160 | 47       | 1.2%    |
| 161-240 | 32       | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3388     | 80.61%  |
| 2     | 542      | 12.9%   |
| 0     | 238      | 5.66%   |
| 3     | 31       | 0.74%   |
| 4     | 4        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2919     | 52.58%  |
| Intel                             | 751      | 13.53%  |
| Qualcomm Atheros                  | 494      | 8.9%    |
| Ralink Technology                 | 312      | 5.62%   |
| Nvidia                            | 180      | 3.24%   |
| Broadcom                          | 133      | 2.4%    |
| TP-Link                           | 111      | 2%      |
| Qualcomm Atheros Communications   | 100      | 1.8%    |
| Ralink                            | 76       | 1.37%   |
| Samsung Electronics               | 54       | 0.97%   |
| D-Link                            | 50       | 0.9%    |
| VIA Technologies                  | 45       | 0.81%   |
| Marvell Technology Group          | 40       | 0.72%   |
| Microsoft                         | 38       | 0.68%   |
| D-Link System                     | 27       | 0.49%   |
| Broadcom Limited                  | 25       | 0.45%   |
| Xiaomi                            | 22       | 0.4%    |
| JMicron Technology                | 20       | 0.36%   |
| MediaTek                          | 18       | 0.32%   |
| Motorola PCS                      | 16       | 0.29%   |
| Motorola                          | 13       | 0.23%   |
| ASIX Electronics                  | 7        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.11%   |
| Mercucys                          | 5        | 0.09%   |
| ICS Advent                        | 5        | 0.09%   |
| Edimax Technology                 | 5        | 0.09%   |
| ASUSTek Computer                  | 5        | 0.09%   |
| 3Com                              | 5        | 0.09%   |
| Sundance Technology Inc / IC Plus | 4        | 0.07%   |
| Huawei Technologies               | 4        | 0.07%   |
| DisplayLink                       | 4        | 0.07%   |
| Qualcomm                          | 3        | 0.05%   |
| LG Electronics                    | 3        | 0.05%   |
| Hangzhou Silan Microelectronics   | 3        | 0.05%   |
| Encore Electronics                | 3        | 0.05%   |
| Arduino SA                        | 3        | 0.05%   |
| Accton Technology                 | 3        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.04%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| STMicroelectronics                | 2        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2253     | 37.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 399      | 6.62%   |
| Ralink MT7601U Wireless Adapter                                   | 172      | 2.86%   |
| Nvidia MCP61 Ethernet                                             | 153      | 2.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 90       | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 87       | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 85       | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 83       | 1.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 78       | 1.29%   |
| Intel I211 Gigabit Network Connection                             | 76       | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 73       | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 71       | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 70       | 1.16%   |
| Ralink RT5370 Wireless Adapter                                    | 65       | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 63       | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 62       | 1.03%   |
| Intel Wi-Fi 6 AX200                                               | 54       | 0.9%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 47       | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 45       | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 44       | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 42       | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 39       | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 36       | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                               | 33       | 0.55%   |
| Intel 82578DC Gigabit Network Connection                          | 33       | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 33       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32       | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 30       | 0.5%    |
| Realtek 802.11ac NIC                                              | 29       | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 28       | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27       | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 27       | 0.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 25       | 0.42%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 25       | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 24       | 0.4%    |
| Intel 82578DM Gigabit Network Connection                          | 23       | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 22       | 0.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 22       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 407      | 26.11%  |
| Ralink Technology                     | 312      | 20.01%  |
| Qualcomm Atheros                      | 230      | 14.75%  |
| Intel                                 | 146      | 9.36%   |
| TP-Link                               | 108      | 6.93%   |
| Qualcomm Atheros Communications       | 100      | 6.41%   |
| Ralink                                | 76       | 4.87%   |
| D-Link                                | 50       | 3.21%   |
| Microsoft                             | 38       | 2.44%   |
| Broadcom                              | 31       | 1.99%   |
| D-Link System                         | 16       | 1.03%   |
| MediaTek                              | 12       | 0.77%   |
| Mercucys                              | 5        | 0.32%   |
| Marvell Technology Group              | 5        | 0.32%   |
| Edimax Technology                     | 5        | 0.32%   |
| Encore Electronics                    | 3        | 0.19%   |
| Linksys                               | 2        | 0.13%   |
| IMC Networks                          | 2        | 0.13%   |
| Broadcom Limited                      | 2        | 0.13%   |
| ASUSTek Computer                      | 2        | 0.13%   |
| Texas Instruments                     | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| Philips (or NXP)                      | 1        | 0.06%   |
| NetGear                               | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| Accton Technology                     | 1        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 172      | 10.91%  |
| Qualcomm Atheros AR9271 802.11n                                      | 90       | 5.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 78       | 4.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 70       | 4.44%   |
| Ralink RT5370 Wireless Adapter                                       | 65       | 4.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 62       | 3.93%   |
| Intel Wi-Fi 6 AX200                                                  | 54       | 3.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 39       | 2.47%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 33       | 2.09%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 30       | 1.9%    |
| Realtek 802.11ac NIC                                                 | 29       | 1.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 28       | 1.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 27       | 1.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 25       | 1.59%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 25       | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 24       | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 22       | 1.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 22       | 1.4%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 22       | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 21       | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 21       | 1.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 20       | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 17       | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 17       | 1.08%   |
| Intel Wireless-AC 9260                                               | 15       | 0.95%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 14       | 0.89%   |
| Intel Wireless 7260                                                  | 14       | 0.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 14       | 0.89%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 13       | 0.82%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 13       | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 12       | 0.76%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 12       | 0.76%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 11       | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 10       | 0.63%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 10       | 0.63%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 10       | 0.63%   |
| Ralink RT2070 Wireless Adapter                                       | 10       | 0.63%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 10       | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10       | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 10       | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2792     | 64.58%  |
| Intel                             | 676      | 15.64%  |
| Qualcomm Atheros                  | 283      | 6.55%   |
| Nvidia                            | 180      | 4.16%   |
| Broadcom                          | 103      | 2.38%   |
| Samsung Electronics               | 53       | 1.23%   |
| VIA Technologies                  | 44       | 1.02%   |
| Marvell Technology Group          | 35       | 0.81%   |
| Broadcom Limited                  | 23       | 0.53%   |
| Xiaomi                            | 22       | 0.51%   |
| JMicron Technology                | 20       | 0.46%   |
| Motorola PCS                      | 12       | 0.28%   |
| D-Link System                     | 11       | 0.25%   |
| ASIX Electronics                  | 7        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.14%   |
| MediaTek                          | 6        | 0.14%   |
| ICS Advent                        | 5        | 0.12%   |
| 3Com                              | 5        | 0.12%   |
| Sundance Technology Inc / IC Plus | 4        | 0.09%   |
| DisplayLink                       | 4        | 0.09%   |
| TP-Link                           | 3        | 0.07%   |
| Qualcomm                          | 3        | 0.07%   |
| LG Electronics                    | 3        | 0.07%   |
| Hangzhou Silan Microelectronics   | 3        | 0.07%   |
| ASUSTek Computer                  | 3        | 0.07%   |
| T & A Mobile Phones               | 2        | 0.05%   |
| Huawei Technologies               | 2        | 0.05%   |
| Aquantia                          | 2        | 0.05%   |
| Apple                             | 2        | 0.05%   |
| Accton Technology                 | 2        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| SK hynix                          | 1        | 0.02%   |
| OPPO Electronics                  | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| AMD                               | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2253     | 51.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 399      | 9.06%   |
| Nvidia MCP61 Ethernet                                             | 153      | 3.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 87       | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 85       | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 83       | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 76       | 1.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 73       | 1.66%   |
| Intel Ethernet Connection (7) I219-V                              | 71       | 1.61%   |
| Intel 82579V Gigabit Network Connection                           | 63       | 1.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 47       | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 45       | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 44       | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 42       | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 36       | 0.82%   |
| Intel 82578DC Gigabit Network Connection                          | 33       | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 33       | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32       | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.66%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27       | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 23       | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21       | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 19       | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19       | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.39%   |
| Intel Ethernet Connection I217-V                                  | 17       | 0.39%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16       | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.34%   |
| Intel Ethernet Controller I225-V                                  | 15       | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 14       | 0.32%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 13       | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 13       | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.27%   |
| Motorola PCS moto g(9) play                                       | 12       | 0.27%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.27%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 11       | 0.25%   |
| Intel Ethernet Connection (12) I219-V                             | 11       | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 10       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4068     | 72.89%  |
| WiFi     | 1471     | 26.36%  |
| Modem    | 31       | 0.56%   |
| Unknown  | 11       | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3258     | 77.06%  |
| WiFi     | 969      | 22.92%  |
| Unknown  | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3269     | 78.45%  |
| 2     | 770      | 18.48%  |
| 0     | 66       | 1.58%   |
| 3     | 55       | 1.32%   |
| 4     | 5        | 0.12%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3423     | 80.85%  |
| Yes  | 811      | 19.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 380      | 55.15%  |
| Intel                           | 128      | 18.58%  |
| Realtek Semiconductor           | 52       | 7.55%   |
| Qualcomm Atheros Communications | 51       | 7.4%    |
| Broadcom                        | 22       | 3.19%   |
| ASUSTek Computer                | 17       | 2.47%   |
| MediaTek                        | 8        | 1.16%   |
| Integrated System Solution      | 7        | 1.02%   |
| IMC Networks                    | 5        | 0.73%   |
| Apple                           | 5        | 0.73%   |
| Conwise Technology              | 3        | 0.44%   |
| Unknown                         | 3        | 0.44%   |
| Foxconn / Hon Hai               | 2        | 0.29%   |
| SINO WEALTH                     | 1        | 0.15%   |
| Realtek                         | 1        | 0.15%   |
| Ralink                          | 1        | 0.15%   |
| Motorola PCS                    | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| D-Link                          | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 380      | 55.07%  |
| Realtek Bluetooth Radio                               | 49       | 7.1%    |
| Intel AX200 Bluetooth                                 | 47       | 6.81%   |
| Intel Bluetooth wireless interface                    | 35       | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                    | 20       | 2.9%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 15       | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 15       | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 10       | 1.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 9        | 1.3%    |
| MediaTek Wireless_Device                              | 8        | 1.16%   |
| Intel AX210 Bluetooth                                 | 7        | 1.01%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.72%   |
| ASUS Bluetooth Radio                                  | 5        | 0.72%   |
| Apple Bluetooth USB Host Controller                   | 5        | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 4        | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4        | 0.58%   |
| Intel AX201 Bluetooth                                 | 4        | 0.58%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.58%   |
| Broadcom BCM92045B3 ROM                               | 4        | 0.58%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.58%   |
| ASUS Bluetooth Adapter                                | 4        | 0.58%   |
| Qualcomm Atheros Bluetooth                            | 3        | 0.43%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.43%   |
| IMC Networks Bluetooth Radio                          | 3        | 0.43%   |
| Conwise CW6622                                        | 3        | 0.43%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 3        | 0.43%   |
| Unknown                                               | 3        | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.29%   |
| Broadcom Bluetooth Controller                         | 2        | 0.29%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 2        | 0.29%   |
| Broadcom BCM2210 Bluetooth                            | 2        | 0.29%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 0.29%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.29%   |
| ASUS BCM20702A0                                       | 2        | 0.29%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.14%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.14%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.14%   |
| Realtek 802.11n WLAN Adapter                          | 1        | 0.14%   |
| Realtek Bluetooth Radio                               | 1        | 0.14%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 2686     | 43.11%  |
| AMD                                             | 1516     | 24.33%  |
| Nvidia                                          | 1342     | 21.54%  |
| C-Media Electronics                             | 167      | 2.68%   |
| Generalplus Technology                          | 71       | 1.14%   |
| VIA Technologies                                | 49       | 0.79%   |
| JMTek                                           | 43       | 0.69%   |
| Logitech                                        | 41       | 0.66%   |
| Creative Labs                                   | 37       | 0.59%   |
| Texas Instruments                               | 26       | 0.42%   |
| Kingston Technology                             | 26       | 0.42%   |
| Corsair                                         | 17       | 0.27%   |
| Microsoft                                       | 14       | 0.22%   |
| Tenx Technology                                 | 12       | 0.19%   |
| BEHRINGER International                         | 12       | 0.19%   |
| Razer USA                                       | 10       | 0.16%   |
| Plantronics                                     | 9        | 0.14%   |
| Licensed by Sony Computer Entertainment America | 9        | 0.14%   |
| Sony                                            | 7        | 0.11%   |
| Silicon Integrated Systems [SiS]                | 7        | 0.11%   |
| GN Netcom                                       | 7        | 0.11%   |
| M-Audio                                         | 6        | 0.1%    |
| Fry's Electronics                               | 6        | 0.1%    |
| Philips (or NXP)                                | 5        | 0.08%   |
| Focusrite-Novation                              | 5        | 0.08%   |
| Creative Technology                             | 5        | 0.08%   |
| Cirrus Logic                                    | 5        | 0.08%   |
| BY EDIFIER                                      | 5        | 0.08%   |
| SteelSeries ApS                                 | 4        | 0.06%   |
| Goldvish                                        | 4        | 0.06%   |
| Dell                                            | 4        | 0.06%   |
| UCQ01000                                        | 3        | 0.05%   |
| JBL                                             | 3        | 0.05%   |
| Elite Silicon                                   | 3        | 0.05%   |
| Cambridge Silicon Radio                         | 3        | 0.05%   |
| ATI Technologies                                | 3        | 0.05%   |
| ASUSTek Computer                                | 3        | 0.05%   |
| Turtle Beach                                    | 2        | 0.03%   |
| Tdlasunnic                                      | 2        | 0.03%   |
| Samson Technologies                             | 2        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 613      | 8.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 542      | 7.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 365      | 5.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 306      | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 235      | 3.26%   |
| AMD Family 17h/19h HD Audio Controller                                            | 218      | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 199      | 2.76%   |
| Nvidia High Definition Audio Controller                                           | 198      | 2.74%   |
| AMD Starship/Matisse HD Audio Controller                                          | 189      | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 177      | 2.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 176      | 2.44%   |
| Nvidia MCP61 High Definition Audio                                                | 167      | 2.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 160      | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 160      | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 149      | 2.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 136      | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 132      | 1.83%   |
| Intel 200 Series PCH HD Audio                                                     | 127      | 1.76%   |
| AMD FCH Azalia Controller                                                         | 125      | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                        | 115      | 1.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 108      | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 93       | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                     | 93       | 1.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 81       | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                     | 79       | 1.09%   |
| Generalplus Technology USB Audio Device                                           | 71       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 67       | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 56       | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 54       | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 49       | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                     | 47       | 0.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 47       | 0.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 46       | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                | 45       | 0.62%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 44       | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                | 41       | 0.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 39       | 0.54%   |
| Nvidia GM206 High Definition Audio Controller                                     | 38       | 0.53%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 38       | 0.53%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 38       | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 567      | 29.56%  |
| Kingston            | 483      | 25.18%  |
| Corsair             | 158      | 8.24%   |
| Smart               | 117      | 6.1%    |
| Crucial             | 90       | 4.69%   |
| A-DATA Technology   | 65       | 3.39%   |
| Samsung Electronics | 59       | 3.08%   |
| SK hynix            | 52       | 2.71%   |
| Team                | 39       | 2.03%   |
| G.Skill             | 32       | 1.67%   |
| Unknown             | 29       | 1.51%   |
| Teikon              | 25       | 1.3%    |
| Micron Technology   | 24       | 1.25%   |
| Multilaser          | 19       | 0.99%   |
| Patriot             | 12       | 0.63%   |
| Atermiter           | 10       | 0.52%   |
| Apacer              | 10       | 0.52%   |
| GeIL                | 7        | 0.36%   |
| Avant               | 7        | 0.36%   |
| Kreton              | 6        | 0.31%   |
| Unknown (82B5)      | 5        | 0.26%   |
| RZX                 | 5        | 0.26%   |
| HBS                 | 5        | 0.26%   |
| GLOWAY              | 5        | 0.26%   |
| Elpida              | 5        | 0.26%   |
| CSX                 | 5        | 0.26%   |
| Nanya Technology    | 4        | 0.21%   |
| MemoWise            | 4        | 0.21%   |
| Kllisre             | 4        | 0.21%   |
| Smart Modular       | 3        | 0.16%   |
| Qbex                | 3        | 0.16%   |
| PUSKILL             | 3        | 0.16%   |
| Positivo            | 3        | 0.16%   |
| Kingmax             | 3        | 0.16%   |
| AMD                 | 3        | 0.16%   |
| Transcend           | 2        | 0.1%    |
| Silicon Power       | 2        | 0.1%    |
| SanDisk             | 2        | 0.1%    |
| Qimonda             | 2        | 0.1%    |
| pqi                 | 2        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 42       | 1.97%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 30       | 1.4%    |
| Unknown RAM Module 2GB DIMM SDRAM                        | 30       | 1.4%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s   | 30       | 1.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 29       | 1.36%   |
| Unknown                                                  | 29       | 1.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 28       | 1.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 27       | 1.26%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 26       | 1.22%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s          | 17       | 0.8%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 16       | 0.75%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 16       | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 15       | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2                         | 15       | 0.7%    |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 15       | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 15       | 0.7%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s      | 15       | 0.7%    |
| Unknown RAM Module 4GB DIMM SDRAM                        | 13       | 0.61%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 13       | 0.61%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s    | 13       | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 12       | 0.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 12       | 0.56%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 11       | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 11       | 0.51%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 11       | 0.51%   |
| Kingston RAM 9905471-006.A00LF 4096MB DIMM DDR3 1333MT/s | 11       | 0.51%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 11       | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 10       | 0.47%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s      | 10       | 0.47%   |
| Smart RAM SH564568FH8N0QHSCR 2GB DIMM DDR3 1333MT/s      | 10       | 0.47%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s            | 10       | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 9        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 9        | 0.42%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 9        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 9        | 0.42%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 9        | 0.42%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 9        | 0.42%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 9        | 0.42%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s     | 9        | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 8        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 676      | 40.14%  |
| DDR4         | 547      | 32.48%  |
| Unknown      | 180      | 10.69%  |
| DDR2         | 130      | 7.72%   |
| SDRAM        | 114      | 6.77%   |
| DDR          | 32       | 1.9%    |
| DDR5         | 2        | 0.12%   |
| LPDDR4       | 1        | 0.06%   |
| DRAM         | 1        | 0.06%   |
| DDR2 FB-DIMM | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1603     | 96.22%  |
| SODIMM  | 59       | 3.54%   |
| RIMM    | 3        | 0.18%   |
| FB-DIMM | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 633      | 33.65%  |
| 8192  | 582      | 30.94%  |
| 2048  | 391      | 20.79%  |
| 16384 | 144      | 7.66%   |
| 1024  | 72       | 3.83%   |
| 32768 | 43       | 2.29%   |
| 512   | 12       | 0.64%   |
| 256   | 2        | 0.11%   |
| 1536  | 1        | 0.05%   |
| 16    | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 383      | 20.61%  |
| 1600    | 323      | 17.38%  |
| Unknown | 144      | 7.75%   |
| 2400    | 121      | 6.51%   |
| 800     | 94       | 5.06%   |
| 667     | 79       | 4.25%   |
| 2667    | 74       | 3.98%   |
| 3200    | 63       | 3.39%   |
| 3400    | 57       | 3.07%   |
| 3000    | 57       | 3.07%   |
| 2133    | 55       | 2.96%   |
| 3600    | 53       | 2.85%   |
| 1867    | 37       | 1.99%   |
| 3466    | 31       | 1.67%   |
| 1866    | 31       | 1.67%   |
| 1066    | 24       | 1.29%   |
| 2800    | 23       | 1.24%   |
| 1067    | 18       | 0.97%   |
| 3151    | 16       | 0.86%   |
| 2666    | 16       | 0.86%   |
| 400     | 16       | 0.86%   |
| 3733    | 14       | 0.75%   |
| 2933    | 14       | 0.75%   |
| 333     | 14       | 0.75%   |
| 533     | 13       | 0.7%    |
| 3800    | 11       | 0.59%   |
| 3334    | 8        | 0.43%   |
| 1334    | 7        | 0.38%   |
| 3333    | 6        | 0.32%   |
| 41632   | 4        | 0.22%   |
| 3066    | 3        | 0.16%   |
| 2733    | 3        | 0.16%   |
| 2132    | 3        | 0.16%   |
| 49926   | 2        | 0.11%   |
| 5354    | 2        | 0.11%   |
| 4800    | 2        | 0.11%   |
| 3100    | 2        | 0.11%   |
| 3007    | 2        | 0.11%   |
| 1400    | 2        | 0.11%   |
| 1332    | 2        | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 86       | 46.74%  |
| Seiko Epson           | 44       | 23.91%  |
| Samsung Electronics   | 16       | 8.7%    |
| Canon                 | 14       | 7.61%   |
| Brother Industries    | 13       | 7.07%   |
| Lexmark International | 3        | 1.63%   |
| QinHeng Electronics   | 2        | 1.09%   |
| Apple                 | 2        | 1.09%   |
| Ricoh                 | 1        | 0.54%   |
| Prolific Technology   | 1        | 0.54%   |
| Oki Data              | 1        | 0.54%   |
| ARGOX                 | 1        | 0.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ET-2600 Series                   | 8        | 4.32%   |
| HP DeskJet 2130 series                       | 8        | 4.32%   |
| Seiko Epson L365 Series                      | 7        | 3.78%   |
| Seiko Epson L355 Series                      | 6        | 3.24%   |
| Seiko Epson L3150 Series                     | 6        | 3.24%   |
| HP Ink Tank Wireless 410 series              | 6        | 3.24%   |
| HP Deskjet 3050 J610 series                  | 5        | 2.7%    |
| HP Deskjet 2540 series                       | 5        | 2.7%    |
| Canon G3010 series                           | 5        | 2.7%    |
| Samsung SCX-4200 series                      | 4        | 2.16%   |
| Samsung M2070 Series                         | 4        | 2.16%   |
| HP LaserJet P1005                            | 4        | 2.16%   |
| HP DeskJet F4100 Printer series              | 4        | 2.16%   |
| HP DeskJet 2620 All-in-One Printer           | 4        | 2.16%   |
| HP Deskjet 2050 J510                         | 4        | 2.16%   |
| HP LaserJet Professional P1102w              | 3        | 1.62%   |
| HP LaserJet 1020                             | 3        | 1.62%   |
| HP Deskjet F4400 series                      | 3        | 1.62%   |
| HP DeskJet F4200 series                      | 3        | 1.62%   |
| HP DeskJet 3630 series                       | 3        | 1.62%   |
| Brother HL-1200 series                       | 3        | 1.62%   |
| Seiko Epson XP-243 245 247 Series            | 2        | 1.08%   |
| Seiko Epson L375 Series                      | 2        | 1.08%   |
| Seiko Epson L3110 Series                     | 2        | 1.08%   |
| Seiko Epson L220 Series                      | 2        | 1.08%   |
| Seiko Epson L210 Series                      | 2        | 1.08%   |
| Samsung SCX-3200 Series                      | 2        | 1.08%   |
| Samsung M2020 Series                         | 2        | 1.08%   |
| QinHeng CH340S                               | 2        | 1.08%   |
| HP Printing Support                          | 2        | 1.08%   |
| HP LaserJet 1018                             | 2        | 1.08%   |
| HP Deskjet 4620 series                       | 2        | 1.08%   |
| HP DeskJet 2700 series                       | 2        | 1.08%   |
| Canon PIXMA MG3000 series                    | 2        | 1.08%   |
| Brother HL-1210W series                      | 2        | 1.08%   |
| Brother DCP-7055 scanner/printer             | 2        | 1.08%   |
| Apple Gamesir-G3s 2.15                       | 2        | 1.08%   |
| Seiko Epson XP-211 214 216 Series            | 1        | 0.54%   |
| Seiko Epson Printer                          | 1        | 0.54%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 6        | 42.86%  |
| Canon           | 5        | 35.71%  |
| Seiko Epson     | 2        | 14.29%  |
| Mustek Systems  | 1        | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                        | 4        | 28.57%  |
| Canon CanoScan LIDE 25                                  | 4        | 28.57%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 7.14%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 7.14%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 7.14%   |
| HP ScanJet G4050                                        | 1        | 7.14%   |
| HP ScanJet 3800c                                        | 1        | 7.14%   |
| Canon CanoScan LiDE 210                                 | 1        | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 195      | 31.6%   |
| Generalplus Technology        | 44       | 7.13%   |
| Microsoft                     | 40       | 6.48%   |
| Microdia                      | 35       | 5.67%   |
| Z-Star Microelectronics       | 33       | 5.35%   |
| Samsung Electronics           | 33       | 5.35%   |
| Aveo Technology               | 27       | 4.38%   |
| GEMBIRD                       | 17       | 2.76%   |
| Cubeternet                    | 14       | 2.27%   |
| Jieli Technology              | 12       | 1.94%   |
| Sunplus Innovation Technology | 11       | 1.78%   |
| Pixart Imaging                | 11       | 1.78%   |
| Chicony Electronics           | 10       | 1.62%   |
| LG Electronics                | 8        | 1.3%    |
| Genesys Logic                 | 8        | 1.3%    |
| Alcor Micro                   | 8        | 1.3%    |
| Apple                         | 7        | 1.13%   |
| MacroSilicon                  | 6        | 0.97%   |
| Arkmicro Technologies         | 6        | 0.97%   |
| Realtek Semiconductor         | 5        | 0.81%   |
| Philips (or NXP)              | 5        | 0.81%   |
| KYE Systems (Mouse Systems)   | 5        | 0.81%   |
| Hewlett-Packard               | 5        | 0.81%   |
| Acer                          | 5        | 0.81%   |
| Sunplus Technology            | 4        | 0.65%   |
| Lenovo                        | 4        | 0.65%   |
| Huawei Technologies           | 4        | 0.65%   |
| SunplusIT                     | 3        | 0.49%   |
| Sonix Technology              | 3        | 0.49%   |
| Silicon Motion                | 3        | 0.49%   |
| IMC Networks                  | 3        | 0.49%   |
| Creative Technology           | 3        | 0.49%   |
| ARC International             | 3        | 0.49%   |
| A4Tech                        | 3        | 0.49%   |
| Xiongmai                      | 2        | 0.32%   |
| WCM_USB                       | 2        | 0.32%   |
| Mimaki Engineering            | 2        | 0.32%   |
| GenesysLogic Technology       | 2        | 0.32%   |
| AVerMedia Technologies        | 2        | 0.32%   |
| Asuscom Network               | 2        | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 73       | 11.77%  |
| Logitech HD Pro Webcam C920              | 45       | 7.26%   |
| Samsung Galaxy A5 (MTP)                  | 32       | 5.16%   |
| Generalplus GENERAL WEBCAM               | 30       | 4.84%   |
| Logitech C922 Pro Stream Webcam          | 18       | 2.9%    |
| GEMBIRD USB2.0 PC CAMERA                 | 15       | 2.42%   |
| Z-Star Venus USB2.0 Camera               | 14       | 2.26%   |
| Aveo USB2.0 Camera                       | 13       | 2.1%    |
| Logitech BRIO Ultra HD Webcam            | 12       | 1.94%   |
| Jieli USB PHY 2.0                        | 12       | 1.94%   |
| Logitech HD Webcam C525                  | 11       | 1.77%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 10       | 1.61%   |
| Generalplus 808 Camera #9 (web-cam mode) | 10       | 1.61%   |
| Microdia USB 2.0 Camera                  | 9        | 1.45%   |
| Microdia Integrated Camera               | 9        | 1.45%   |
| Z-Star Vimicro USB Camera (Altair)       | 8        | 1.29%   |
| Microsoft LifeCam VX-500 [1357]          | 8        | 1.29%   |
| Logitech C920 PRO HD Webcam              | 8        | 1.29%   |
| Microsoft LifeCam HD-3000                | 7        | 1.13%   |
| Aveo Camera                              | 7        | 1.13%   |
| Microsoft LifeCam VX-800                 | 6        | 0.97%   |
| Microsoft LifeCam VX-2000                | 6        | 0.97%   |
| Microsoft LifeCam HD-5000                | 6        | 0.97%   |
| Microsoft LifeCam Cinema                 | 6        | 0.97%   |
| Logitech Webcam C925e                    | 6        | 0.97%   |
| Chicony HP Webcam                        | 6        | 0.97%   |
| Alcor Micro USB 2.0 PC Camera            | 6        | 0.97%   |
| Sunplus SPCA2650 AV Camera               | 5        | 0.81%   |
| Philips (or NXP) Webcam SPC530NC         | 5        | 0.81%   |
| Microdia Webcam Vitade AF                | 5        | 0.81%   |
| Microdia Sonix USB 2.0 Camera            | 5        | 0.81%   |
| MacroSilicon USB Video                   | 5        | 0.81%   |
| Logitech Logi Webcam C920e               | 5        | 0.81%   |
| Cubeternet GL-UPC822 UVC WebCam          | 5        | 0.81%   |
| Aveo UVC camera (Bresser microscope)     | 5        | 0.81%   |
| Apple iPhone5/5C/5S/6                    | 5        | 0.81%   |
| Lenovo FHD Webcam Audio                  | 4        | 0.65%   |
| Huawei UVC Camera                        | 4        | 0.65%   |
| Generalplus 2K HD Camera                 | 4        | 0.65%   |
| Cubeternet WebCam                        | 4        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Futronic Technology | 1        | 50%     |
| Dell                | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Futronic FS81 Fingerprint Scanner Module       | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 14       | 41.18%  |
| Giesecke & Devrient               | 4        | 11.76%  |
| Alcor Micro                       | 4        | 11.76%  |
| Chicony Electronics               | 3        | 8.82%   |
| Watchdata                         | 2        | 5.88%   |
| SCM Microsystems                  | 2        | 5.88%   |
| OmniKey                           | 2        | 5.88%   |
| VASCO Data Security International | 1        | 2.94%   |
| Realtek Semiconductor             | 1        | 2.94%   |
| Aladdin Knowledge Systems         | 1        | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 13       | 38.24%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 11.76%  |
| Giesecke & Devrient StarSign CUT S                              | 3        | 8.82%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 3        | 8.82%   |
| Watchdata USB Key                                               | 2        | 5.88%   |
| OmniKey CardMan 3021 / 3121                                     | 2        | 5.88%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 2.94%   |
| SCM Microsystems SCR35xx Smart Card Reader                      | 1        | 2.94%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 1        | 2.94%   |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 2.94%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 2.94%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 2.94%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3594     | 85.41%  |
| 1     | 549      | 13.05%  |
| 2     | 48       | 1.14%   |
| 3     | 10       | 0.24%   |
| 4     | 7        | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 254      | 38.43%  |
| Net/wireless             | 176      | 26.63%  |
| Communication controller | 45       | 6.81%   |
| Unassigned class         | 43       | 6.51%   |
| Sound                    | 25       | 3.78%   |
| Chipcard                 | 23       | 3.48%   |
| Multimedia controller    | 22       | 3.33%   |
| Modem                    | 16       | 2.42%   |
| Camera                   | 16       | 2.42%   |
| Net/ethernet             | 11       | 1.66%   |
| Storage/ide              | 6        | 0.91%   |
| Bluetooth                | 6        | 0.91%   |
| Network                  | 5        | 0.76%   |
| Card reader              | 5        | 0.76%   |
| Storage/raid             | 4        | 0.61%   |
| Video                    | 1        | 0.15%   |
| Storage                  | 1        | 0.15%   |
| Firewire controller      | 1        | 0.15%   |
| Dvb card                 | 1        | 0.15%   |

